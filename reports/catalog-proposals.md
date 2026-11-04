# 目录更新草稿

仅含全文证据支持的机器纳入建议。人工审核后，再同步年度目录与 By Topic；本程序不改写 README。

## DreamFold: A World Model to efficiently generate protein folding pathways in the latent space.

年度：2026；主题：Computational Biology and Cellular Dynamics

```markdown
- (*Paper'26*) **DreamFold: A World Model to efficiently generate protein folding pathways in the latent space.**
  [[📝 Paper](https://europepmc.org/article/MED/42813590)]
  **Metadata:** `State: Molecule` · `Dynamics: Action-conditioned + Temporal` · `Capability: Forecast + Simulate + Plan` · `Assets: Paper only`
  > **Why it qualifies:** 论文提出面向蛋白质折叠的生成式世界模型：状态为蛋白构象，动作为二面角扰动，学习潜空间动作条件转移并由控制器迭代rollout，且与长时MD和实验数据做路径相似性评估，符合纳入标准。
```

### 方法证据

- dynamics：predict the next latent structure given the current latent structure and action
- evaluation：tested against long MD simulations, against other enhanced path sampling methods and against available experimental data
- medical：DreamFold, the first generative World Model to evolve a policy to compute protein folding pathways
- rollout：starting from randomly generated unfolded states s and using the trained controller and FFN to iteratively perform 100 steps
- state：encode the protein structure S (Φ, Ψ dihedrals and C α distances from native)

[全文证据](https://www.ebi.ac.uk/europepmc/webservices/rest/PMC13625212/fullTextXML)

## PulmoWorld: An Asynchronous Multimodal Medical World Model for Longitudinal Pneumonia Dynamics

年度：2026；主题：Medical Imaging and Radiology、Longitudinal EHR and Clinical Trajectories、Treatment Planning and Clinical Decision Support

```markdown
- (*arXiv'26*) **PulmoWorld: An Asynchronous Multimodal Medical World Model for Longitudinal Pneumonia Dynamics**
  [[📝 Paper](https://arxiv.org/abs/2610.38289)]
  **Metadata:** `State: Patient` · `Dynamics: Action-conditioned + Temporal` · `Capability: Forecast + Simulate + Plan + Control + Counterfactual` · `Assets: Paper only`
  > **Why it qualifies:** 论文满足纳入标准：肺炎医疗任务、患者潜在状态、学习的异步状态转移与动作条件动力学、H1–H4递归rollout，以及MASS/MIMIC和MASS-Syn上的实现评估。
```

### 方法证据

- dynamics：History-aware filtering separates state propagation from observation-driven correction, so a measurement updates the shared belief only when it is observed.
- evaluation：On the pneumonia cohort MASS, recursive forecasts are competitive with task-trained sequence models
- medical：a world model for longitudinal pneumonia dynamics that connects asynchronous state estimation
- rollout：Recursive forecasts advance H1–H4 without factual intermediate observations.
- state：A shared patient world for longitudinal simulation and evidence-constrained planning.

[全文证据](https://arxiv.org/html/2610.38289v1)
