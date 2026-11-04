# Literature discovery and local/GitHub digests

The pipeline searches arXiv, Europe PMC and PubMed, merges exact identifiers/titles, routes candidates to catalog topics, and produces daily/weekly Markdown reports. Optional model analysis adds Chinese summaries, evidence-backed scope decisions and catalog proposals. It does not edit the curated README or send messages to people.

## Run locally

Python 3.9 or newer; no third-party Python dependencies:

```bash
python3 -m scripts.literature_pipeline.cli --metadata-only
```

Run from the repository root. The first run imports the existing main catalog as historical records and searches the previous 30 days. Later runs start seven days before each successful query's watermark. Configure query families, window overlap and per-query/per-run caps in `config/literature.json`.

```bash
# Explicit historical coverage. A later complete run must not rewind a watermark.
python3 -m scripts.literature_pipeline.cli --since 2026-10-05 --until 2026-11-04

# Small connectivity run. Hitting the cap is incomplete and returns exit code 2.
python3 -m scripts.literature_pipeline.cli --sources europepmc --max-records 5 --metadata-only
```

Outputs:

| Path | Purpose |
|---|---|
| `.local/literature.sqlite3` | Private local state, including fetched abstracts; ignored by Git |
| `data/literature-state.json` | Portable public state, identifiers, short analysis evidence and query watermarks; omits full abstracts and full texts |
| `reports/latest.md` | Latest run's daily candidate digest |
| `reports/daily/YYYY-MM-DD.md` | Daily discoveries, material updates and completed analyses; reruns do not duplicate entries |
| `reports/weekly.md` | Rolling seven-day topic index |
| `reports/catalog-proposals.md` | Full-text-supported machine inclusion proposals, with draft metadata and short evidence quotes |
| `reports/run-status.json` | Per-query completeness and analysis mode/failure counts |

The SQLite file is authoritative locally. The JSON state is restored only into an empty database. To move to another machine, copy the JSON state before the first run; full-text/abstract data is fetched again when needed. Keep backups of local SQLite state for private access history. Run only one process per SQLite/state/output set; GitHub Actions serializes runs with a concurrency group.

## Enable Chinese model analysis

Set these environment variables in your shell/secret manager (do not commit keys):

- `LITERATURE_LLM_ENDPOINT`: the complete HTTPS chat-completions-compatible endpoint, including `/chat/completions`; HTTP is permitted only for localhost.
- `LITERATURE_LLM_MODEL`: your provider's model identifier.
- `LITERATURE_LLM_API_KEY`: the provider credential, if required.
- `LITERATURE_LLM_CACHE_NAMESPACE`: optional explicit provider identity for cache invalidation; defaults to an endpoint hash.
- `NCBI_EMAIL`: optional real contact address for NCBI requests.

Then run with `--require-model`. This flag refuses missing model configuration and a zero review budget. The model API must support JSON-object responses, chat messages, `temperature` and `max_tokens`. The implementation is provider-compatible, not a guarantee that every model supports these parameters. No provider credentials are discovered automatically.

Default analysis budget: 100 candidates per run, prioritized by deterministic scope clues. These routing clues only rank candidates; they do not exclude records from the candidate database. Historical catalog imports are not automatically re-reviewed or treated as a verified gold standard. Unprocessed records remain queued. Revisions, provider changes and material metadata changes invalidate old model results. Explicit metadata-only runs remain available for discovery diagnostics.

Full-text retrieval attempts official arXiv article HTML or Europe PMC open-access article XML when a suitable identifier is present. No paywall bypass or bulk PDF redistribution is performed. Missing/failed full text falls back to the abstract. Article text is sent to the configured model provider for analysis; use a provider suitable for public scholarly content. Full article bodies are not stored or exported by this pipeline. A maximum of 100,000 normalized characters is supplied per analysis, with truncation recorded.

The model must return five scope-evidence items, topic labels, capability labels, a Chinese summary and limitations. Code verifies the controlled vocabulary, Chinese prose and exact evidence spans in the supplied text. Invalid JSON/evidence triggers up to two corrective retries; transient API failures also have bounded retries. Abstract-only analysis cannot produce an inclusion proposal. `Plan`, `Control` and `Counterfactual` proposals require `Action-conditioned` dynamics. Exact quotes prevent invented spans, but cannot prove that the interpretation is scientifically correct. All inclusion/exclusion decisions remain machine suggestions. Review proposals before moving entries into the annual and topic catalogs. Failed full-text access is eligible for rechecking after one day; other abstract-only analyses after seven days.

## Weekly production deployment

Production runs on the existing IAI-61 server every **Sunday at 09:37 Asia/Shanghai** (01:37 UTC), using the systemd user units in `deploy/`. `Persistent=true` catches up after downtime. It calls the existing local Magpie gateway at `http://127.0.0.1:3425/v1/chat/completions` with **`qoder-cn/dfmodel` (Qoder DeepSeek-Flash)**. The Qoder sign-in and GitHub authentication stay on the server; no Qoder login token is copied into GitHub Secrets or this repository.

The production wrapper `scripts/run_weekly_literature.sh`:

1. The service fast-forwards current default-branch code before loading the wrapper; the wrapper locks against overlapping invocations and runs tests.
2. Restores public state/report history in a separate `literature-data` worktree, retaining private SQLite state on the server.
3. Searches and analyzes candidates with `--require-model`; failed-run diagnostics remain under `.local/weekly-run.*`, successful staging directories are removed.
4. Commits generated state/reports to `literature-data` with a regular non-forced push. It never merges into main or changes the curated README.
5. Preserves useful partial output but exits nonzero for incomplete coverage/model errors, visible through systemd status/journal.

Server source checkout: `~/.local/share/healthcare-literature/repo`; output worktree: `~/.local/share/healthcare-literature/output`; environment file: `~/.config/healthcare-literature.env`. The environment contains the loopback endpoint, model ID and `LITERATURE_LLM_CACHE_NAMESPACE=qoder-cn`, not the underlying Qoder credential.

```bash
systemctl --user status literature-weekly.timer
systemctl --user start literature-weekly.service
journalctl --user -u literature-weekly.service -n 80 --no-pager
```

Read `reports/latest.md`, `reports/weekly.md` and `reports/catalog-proposals.md` on GitHub's **literature-data** branch. The archive branch is persistent storage; Actions cache is not the database. Do not manually edit generated state/report files while a job is running.

The GitHub Actions workflow remains available for **manual dispatch only**, for an alternative deployment with an endpoint reachable from a hosted runner. It requires its own `LITERATURE_LLM_ENDPOINT`, `LITERATURE_LLM_MODEL` variables and optional API-key secret. It does not schedule a duplicate weekly run, and cannot reach IAI-61's loopback address. Repository CI still checks code and catalog changes on pushes/PRs.

## Failure handling and limits

- API failures never count as successful zero-hit searches. Truncated or failed queries do not advance watermarks; unfinished initial windows keep their original start date across later weekly runs. Successful queries advance independently.
- Exit code 0 means selected query windows completed and attempted analyses succeeded; it does not mean every queued candidate was analyzed or every source was searched. Exit code 2 means incomplete source coverage or model failures. See `run-status.json` for selected sources and counts.
- Source record caps require narrowing a date window or increasing the cap; repeatedly hitting a cap alone will not eventually complete the search.
- Exact DOI/arXiv/PMID/title aliases merge records. Conflicting matches are held as a query failure for manual reconciliation, without merging unrelated papers. Fuzzy title matches are not automatically merged.
- The current query windows use initial publication/submission dates. Revisions of much older papers require a historical backfill; automatic source-native revision/indexing-date harvesting is not yet implemented. The overlap window reduces recent indexing gaps but cannot guarantee complete discovery.
- The database retains metadata and source identities, not every raw source response. No citation-chasing crawler, interactive review UI, publisher-wide PDF parser or scholarly result reproduction is included.
- Validated source links and catalog consistency do not establish scientific quality. Include learned/hybrid dynamics in the core; classify pure mechanistic simulators as related to avoid silently inheriting the older catalog's mixed criteria.

## Verify

```bash
python3 -m unittest discover -s tests -v
python3 scripts/validate_catalog.py
git diff --check
```

API references: [arXiv API terms](https://info.arxiv.org/help/api/tou.html), [Europe PMC API](https://dev.europepmc.org/RestfulWebService), [NCBI E-utilities](https://www.ncbi.nlm.nih.gov/books/NBK25497/), [GitHub scheduled workflows](https://docs.github.com/en/actions/reference/workflows-and-actions/events-that-trigger-workflows#schedule).
