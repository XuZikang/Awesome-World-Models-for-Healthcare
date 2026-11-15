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

## Learning a patient world model for health system simulation in intensive care

年度：2026；主题：Longitudinal EHR and Clinical Trajectories、Treatment Planning and Clinical Decision Support

```markdown
- (*arXiv'26*) **Learning a patient world model for health system simulation in intensive care**
  [[📝 Paper](https://arxiv.org/abs/2611.08392)]
  **Metadata:** `State: Patient` · `Dynamics: Temporal + Event sequence` · `Capability: Forecast + Simulate` · `Assets: Paper only`
  > **Why it qualifies:** 全文明确给出医疗运行任务、患者状态表示、学习式状态转移、十四天自回归推演以及在真实重症数据库上的实现与对照评估，满足纳入标准；但属观察性模拟研究，不能解读为因果性政策效果。
```

### 方法证据

- dynamics：sampled states and events are appended to the patient’s history before the next query
- evaluation：Extensive experiments show that our model matches task-fitted Markov and semi-Markov comparators in aggregate occupancy and directional responses
- medical：Taking intensive care unit (ICU) operations as a working example, we train the model on MIMIC-IV
- rollout：repeated sampling from a single patient’s anchor history generates alternative futures for that individual
- state：encodes irregular clinical records as sequences drawn from a structured vocabulary of physiological measurements

[全文证据](https://arxiv.org/html/2611.08392v1)

## QCC-WM: Linking Macro-State Dynamics and Visual Generation via Quotient Causal Construction

年度：2026；主题：Medical Imaging and Radiology

```markdown
- (*arXiv'26*) **QCC-WM: Linking Macro-State Dynamics and Visual Generation via Quotient Causal Construction**
  [[📝 Paper](https://arxiv.org/abs/2611.12353)]
  **Metadata:** `State: Medical image` · `Dynamics: Action-conditioned + Temporal + Spatial/view` · `Capability: Forecast + Simulate` · `Assets: Paper only`
  > **Why it qualifies:** 全文报告了超声视频预测任务、宏观状态构建、动作条件递归转移、4/8/16步滚动生成及在US-VLA和Freehand US上的定量评估，满足纳入标准。
```

### 方法证据

- dynamics：Action-conditioned dynamics recursively predict content and motion states.
- evaluation：Comparative experiments on US-VLA and transfer experiments on Freehand US show improved ultrasound video prediction quality
- medical：action-conditioned ultrasound video prediction through short-window prediction and multi-step extrapolation
- rollout：recursively generate future observations in blocks of four frames
- state：construct macro-states that support action-conditioned prediction while preserving their connection to observation space

[全文证据](https://arxiv.org/html/2611.12353v1)

## Building an Extracorporeal Membrane Oxygenation Digital Twin Using High-Resolution Patient Data: An Artificial Intelligence Model for Virtual Reality Simulation.

年度：2026；主题：Surgical Simulation and Embodied Healthcare、Longitudinal EHR and Clinical Trajectories

```markdown
- (*Paper'26*) **Building an Extracorporeal Membrane Oxygenation Digital Twin Using High-Resolution Patient Data: An Artificial Intelligence Model for Virtual Reality Simulation.**
  [[📝 Paper](https://europepmc.org/article/MED/41712754)]
  **Metadata:** `State: Patient` · `Dynamics: Action-conditioned + Temporal` · `Capability: Forecast + Simulate` · `Assets: Paper only`
  > **Why it qualifies:** 具备明确的医学任务、患者生理状态表征、由设备设置驱动的学习型状态转移、VR实时推理滚动仿真，以及定量误差与专家评估；属生物医学数字孪生与仿真培训范畴。
```

### 方法证据

- dynamics：Model 1 predicts ECMO mechanical outputs (flow, pressures) from device settings (RPM, sweep gas flow)
- evaluation：Model performance was quantified using root mean squared error (RMSE), coefficient of determination
- medical：is a critical intervention in the management of severe cardiopulmonary failure
- rollout：deploy the resulting models for real-time inference in a VR training environment
- state：predicts patient vital signs responses (eg, blood pressure)

[全文证据](https://www.ebi.ac.uk/europepmc/webservices/rest/PMC13746011/fullTextXML)

## ICare-DT: a digital twin for continuous forecasting of intensive care patients

年度：2026；主题：Longitudinal EHR and Clinical Trajectories、Treatment Planning and Clinical Decision Support

```markdown
- (*arXiv'26*) **ICare-DT: a digital twin for continuous forecasting of intensive care patients**
  [[📝 Paper](https://arxiv.org/abs/2611.09712)]
  **Metadata:** `State: Patient` · `Dynamics: Temporal + Action-conditioned` · `Capability: Forecast + Counterfactual` · `Assets: Paper only`
  > **Why it qualifies:** 全文报告 ICU 连续预测任务、64 维患者状态、冻结 Transformer 的逐小时状态更新及测试集评估；治疗反应模块证据不足，但连续预测主线满足纳入标准。
```

### 方法证据

- dynamics：updates a latent patient state hourly from new measurements without retraining
- evaluation：On test data, later forecasts beat the twin’s own hour-6 forecasts
- medical：to forecast vital signs crossing their training-set means
- rollout：forecasts which of three events comes first within 48 hours
- state：keeps a patient state, a learned summary of the record so far

[全文证据](https://arxiv.org/html/2611.09712v1)

## Personalized health coaching via coachable health age and counterfactual wearable trajectories

年度：2026；主题：Longitudinal EHR and Clinical Trajectories、Treatment Planning and Clinical Decision Support

```markdown
- (*arXiv'26*) **Personalized health coaching via coachable health age and counterfactual wearable trajectories**
  [[📝 Paper](https://arxiv.org/abs/2611.08568)]
  **Metadata:** `State: Physiology` · `Dynamics: Action-conditioned + Temporal` · `Capability: Forecast + Simulate + Plan + Counterfactual` · `Assets: Paper only`
  > **Why it qualifies:** 全文报告了医疗健康任务、可穿戴生理状态、动作条件学习的转移模型、12周自回归rollout，以及R²、下游预测和专家盲评等已实施评估，满足纳入标准。
```

### 方法证据

- dynamics：The transition model then predicts how this representation changes over time based on the current physiological state
- evaluation：lifestyle coaches selected Counterfactual Coaching as the best overall plan in 71.4% of evaluations
- medical：integrate CHA and SensorWM into an agentic counterfactual coaching system to synthesize personalized 12-week coaching plans
- rollout：rolled forward for 12 weeks under candidate changes in daily steps, sleep duration, and cardio-intensity activity.
- state：Each participant was represented as a weekly sequence of physiological states and observable actions.

[全文证据](https://arxiv.org/html/2611.08568v1)

## CellCanon: An Agentic Cellular World Model for Prediction, Explanation, and Observation-Driven Updating

年度：2026；主题：Computational Biology and Cellular Dynamics

```markdown
- (*arXiv'26*) **CellCanon: An Agentic Cellular World Model for Prediction, Explanation, and Observation-Driven Updating**
  [[📝 Paper](https://arxiv.org/abs/2611.05890)]
  **Metadata:** `State: Cell` · `Dynamics: Action-conditioned + Temporal` · `Capability: Forecast + Simulate` · `Assets: Paper only`
  > **Why it qualifies:** 具备细胞/分子层面的医学任务、共享世界状态、学习型预测与观测驱动更新，并在留出条件及解释/更新基准上完成实现评估，故建议纳入。
```

### 方法证据

- dynamics：Update uses a newly measured drug response to revise predictions for the same drug in unmeasured cell contexts.
- evaluation：On 339 held-out SciPlex3 conditions across three cell lines, CellCanon improves differential-expression AUPRC and Macro-F1 over the best baseline
- medical：Single-cell perturbation screens reveal drug-induced transcriptional changes but leave many compounds and cell contexts unmeasured
- rollout：We evaluate this process by progressively revealing existing SciPlex3 measurements to simulate experimental feedback.
- state：The world state links responses, source-linked claims, and measurements.

[全文证据](https://arxiv.org/html/2611.05890v1)

## SurgWorld: Learning Surgical Representations Beyond Observation via Latent Prediction

年度：2026；主题：Surgical Simulation and Embodied Healthcare

```markdown
- (*arXiv'26*) **SurgWorld: Learning Surgical Representations Beyond Observation via Latent Prediction**
  [[📝 Paper](https://arxiv.org/abs/2611.11140)]
  **Metadata:** `State: Anatomy` · `Dynamics: Action-conditioned + Temporal + Spatial/view` · `Capability: Forecast` · `Assets: Paper only`
  > **Why it qualifies:** 该工作面向手术视频理解，明确建模手术场景状态，使用动作条件化的学习式潜空间转移，并对未来潜状态预测和17个基准进行了实现评估，符合纳入条件。
```

### 方法证据

- dynamics：treats a specified spatial or temporal shift as a pseudo-action and learns to predict the target latent representation from a partial observation
- evaluation：SurgWorld consistently outperforms the matched V-JEPA2 baseline across all evaluated temporal shifts on all three benchmarks.
- medical：Surgical procedures are inherently partially observable, requiring surgeons to continuously infer evolving anatomical dynamics and future surgical states
- rollout：SurgWorld predicts the latent representation of the entire target clip, which is subsequently used for downstream classification.
- state：out-of-sight surgical dynamics, namely the evolution of hidden anatomical structures and instrument-tissue interactions

[全文证据](https://arxiv.org/html/2611.11140v1)

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

## The Delta Gap: Cellular World Models for Perturbation Response Prediction Are Far Harder Than Global Correlation Implies

年度：2026；主题：Computational Biology and Cellular Dynamics

```markdown
- (*arXiv'26*) **The Delta Gap: Cellular World Models for Perturbation Response Prediction Are Far Harder Than Global Correlation Implies**
  [[📝 Paper](https://arxiv.org/abs/2611.10658)]
  **Metadata:** `State: Cell` · `Dynamics: Action-conditioned` · `Capability: Forecast + Simulate` · `Assets: Paper only`
  > **Why it qualifies:** 文章明确把扰动建模为动作、细胞表达谱建模为状态，学习扰动后状态转移，并在Replogle与Norman上实现delta Pearson、kNN校正和零样本跨细胞系预测评估，满足生物医学世界模型的预测与评测要求。
```

### 方法证据

- dynamics：maps a cellular state s and an action a (a genetic perturbation) to the next state s’
- evaluation：On the Replogle K562 screen (509 unseen perturbations, 5000 genes), GEARS achieves global Pearson 0.977
- medical：Cellular world models aim to predict how cells respond to genetic perturbations
- rollout：given a perturbation (an ’action’), predict the resulting cell state (’next observation’)
- state：action = gene knockout perturbation, state = gene expression vector, s’ = post-perturbation transcriptome

[全文证据](https://arxiv.org/html/2611.10658v1)

## SurgTransfer: Multi-Step Latent Action Modeling for Action Transfer in Surgical World Model

年度：2026；主题：Surgical Simulation and Embodied Healthcare、Medical Imaging and Radiology

```markdown
- (*arXiv'26*) **SurgTransfer: Multi-Step Latent Action Modeling for Action Transfer in Surgical World Model**
  [[📝 Paper](https://arxiv.org/abs/2611.05443)]
  **Metadata:** `State: Medical image` · `Dynamics: Action-conditioned + Spatial/view + Temporal` · `Capability: Counterfactual + Forecast + Simulate` · `Assets: Paper only`
  > **Why it qualifies:** 论文以单帧手术画面为状态，用潜动作条件扩散动力学预测未来帧并执行14帧rollout，在两个手术数据集上做了定量对比并由外科专家评分，满足医疗任务、状态、学习到的动作条件转移、操作化预测和已实现评估五项要求。
```

### 方法证据

- dynamics：a dynamics model that predicts future frames conditioned on past observations and actions.
- evaluation：verifying our approach with both quantitative metrics and qualitative evaluation by surgical experts.
- medical：Surgical world models have the potential to provide intra-operative guidance, accelerate risk-free training
- rollout：to roll out 14 more frames into the future
- state：target surgical context, which is represented by a single frame

[全文证据](https://arxiv.org/html/2611.05443v1)
