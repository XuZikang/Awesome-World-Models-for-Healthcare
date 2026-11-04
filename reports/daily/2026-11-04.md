# 医疗世界模型文献摘要 · 2026-11-04

机器整理的候选与收录建议；未代表人工审核或实验复现。

候选库：24 篇；当日发现、更新或完成分析：24 篇。

已有有效中文分析：24 篇；待分析或缺少摘要证据：0 篇。

## 检索覆盖

- arxiv / 查询 0b853c5d2ddf：3 条；完整
- arxiv / 查询 974e2bc9882c：0 条；完整
- europepmc / 查询 f74b0612eaf2：2 条；完整
- europepmc / 查询 f11522d6c8db：3 条；完整
- pubmed / 查询 e190f0b25756：17 条；完整
- pubmed / 查询 1a5e763292f9：2 条；完整

## 当日候选

### [DreamFold: A World Model to efficiently generate protein folding pathways in the latent space.](https://europepmc.org/article/MED/42813590)

- 标识：`p-14e20f1cb202524e7adb`；发表：2026-11-01；发现：2026-11-04
- 主题：Computational Biology and Cellular Dynamics
- 状态：建议纳入，待审核

DreamFold在潜空间构建蛋白质折叠世界模型：用VAE编码蛋白构象与二面角动作，FFN学习动作条件下的构象转移，控制器从非折叠态迭代rollout生成折叠路径，并与长时MD及实验数据比较。

限制：所提供全文显示，轨迹不满足细致平衡，不能直接给出动力学或热力学量；依赖Rosetta力场并继承其偏差；MSM重建被作者称为仅具定性参考。

判断：论文提出面向蛋白质折叠的生成式世界模型：状态为蛋白构象，动作为二面角扰动，学习潜空间动作条件转移并由控制器迭代rollout，且与长时MD和实验数据做路径相似性评估，符合纳入标准。

证据层级：full_text；[来源](https://www.ebi.ac.uk/europepmc/webservices/rest/PMC13625212/fullTextXML)；模型：qoder-cn/dfmodel。

### [Nano-Bioadhesives for Gastrointestinal Hemostasis and Healing: Integrating Artificial Intelligence for Precision Design and Application.](https://pubmed.ncbi.nlm.nih.gov/42975278/)

- 标识：`p-2fd34f283489ce52280f`；发表：2026-11-03；发现：2026-11-04
- 主题：Computational Biology and Cellular Dynamics
- 状态：相关综述／资源

该文为综述，讨论纳米生物黏合剂用于胃肠道止血与黏膜修复，并主张以AI驱动的多目标材料设计（预测建模、分子模拟、高通量实验、数字孪生与闭环优化）加速配方开发。

限制：仅有摘要，未提供状态定义、转移模型、代码或实验评估细节；所提供摘要未报告任何已实现的世界模型系统，无法核验全文方法与评估。该文为综述，非原始方法研究。

判断：主题属生物医学材料设计，提到预测建模、分子模拟与数字孪生，与世界模型概念相关；但这是摘要级综述，未描述可学习的转移模型、状态传播或已实现的评估，故不作为可纳入的方法，仅列为相关。

证据层级：abstract；[来源](https://pubmed.ncbi.nlm.nih.gov/42975278/)；模型：qoder-cn/dfmodel。

### [Digital twin-enabled toxicology: Current applications, opportunities, and future directions.](https://pubmed.ncbi.nlm.nih.gov/42686080/)

- 标识：`p-345fc899021da38e74dd`；发表：2026-09-02；发现：2026-11-04
- 主题：Computational Biology and Cellular Dynamics
- 状态：相关综述／资源

该文综述数字孪生在毒理学中的应用，涵盖药物安全、环境与职业健康及个体化医学；强调以真实世界数据持续更新的生物系统虚拟副本可模拟器官或整体毒性反应并预测剂量反应，但多为概念性证据。

限制：仅提供摘要，属叙述性综述；所提供摘要未报告具体模型实现、代码、前瞻性验证或可核验的临床与监管效益，无法核验操作化预测与评估细节。

判断：叙述性综述讨论数字孪生毒理学应用，涉及生理状态与毒性反应模拟，但摘要未报告可实现、可评估的系统或前瞻验证；摘要级综述不能建议纳入。

证据层级：abstract；[来源](https://pubmed.ncbi.nlm.nih.gov/42686080/)；模型：qoder-cn/dfmodel。

### [The (Butter)fly Dream: Linear Separability of World-Model Rollouts in a Connectome-Constrained Visual Model](https://arxiv.org/abs/2611.01866)

- 标识：`p-36a47b650bec2b072b22`；发表：2026-11-01；发现：2026-11-04
- 主题：Computational Biology and Cellular Dynamics
- 状态：相关综述／资源

论文以连接组约束的果蝇视觉网络为固定观察者，将其细胞类型反应用于二样本检验，判断真实视频与三类世界模型生成的短序列“梦境”能否被线性区分，并考察训练、检测时域和分级时间扰动的影响。

限制：仅限果蝇视觉与Sintel亮度序列，生成序列很短（14帧），未验证闭环行为或临床转化；全文称代码与结果文件未随预印本发布，且未分离连接组与flyvis的具体贡献。

判断：该文属于计算神经科学与世界模型评测：用固定果蝇视觉模型检验生成续帧的可分性，有状态、时序生成和实现评估，但没有医学任务或临床/生理预测应用，因此不满足 suggest_include 的医学任务要求。

证据层级：full_text；[来源](https://arxiv.org/html/2611.01866v1)；模型：qoder-cn/dfmodel。

### [Non-invasive Computational Techniques for Diagnosing Myocardial Ischemia: Challenges and Future of FFRCT/iFRCT.](https://pubmed.ncbi.nlm.nih.gov/42209956/)

- 标识：`p-36aa4c085ad367a2ad27`；发表：2026-05-28；发现：2026-11-04
- 主题：Medical Imaging and Radiology、Treatment Planning and Clinical Decision Support
- 状态：相关综述／资源

该文系统回顾基于计算流体力学（CFD）的无创FFRCT/iFRCT心肌缺血评估模型，指出刚性管壁假设与微循环代偿机制造成的计算偏差，并梳理提升计算效率的模型改进研究；未来设想为融合多模态临床数据、人工智能与数字孪生构建高保真心血管仿真模型。

限制：仅有摘要，属综述性文献；所提供摘要未报告自建模型的实现细节、随时间推演的预测或定量对照评估，代码与方法无法核验；数字孪生动态预警仅为未来设想而非已完成工作。

判断：文章聚焦心肌缺血的血流动力学机理仿真，属医学任务与生理状态，但为摘要级综述，未提供已实现的推演式预测与对照评估证据，也无动作输入条件，故不足以纳入建议清单，按规则将综述列为相关文献。

证据层级：abstract；[来源](https://pubmed.ncbi.nlm.nih.gov/42209956/)；模型：qoder-cn/dfmodel。

### [Computational Models of the Foreign Body Response: A Focus on Biomaterial Properties.](https://pubmed.ncbi.nlm.nih.gov/42974717/)

- 标识：`p-3d64048702f422c07394`；发表：未知；发现：2026-11-04
- 主题：Computational Biology and Cellular Dynamics
- 状态：相关综述／资源

该文综述植入性生物材料异物反应的计算建模进展，涵盖常微分方程、偏微分方程、基于个体及数据驱动等方法，关注炎症信号、巨噬细胞动态、纤维化与囊膜形成，并讨论材料属性的量化整合、校准与验证数据缺乏，以及异物反应数字孪生这一最终目标。

限制：仅提供摘要，无法核验具体模型结构、实验设计与代码实现；作为综述，其本身不报告原创预测系统或评估结果，所提供摘要未报告滚动预测与已实现评估。

判断：摘要表明本文为异物反应计算模型的综述，汇总机制性与数据驱动方法，属相关背景文献而非原始预测系统；所提供摘要未报告状态滚动推演或已实现的评估，依据规则综述不能建议纳入。

证据层级：abstract；[来源](https://pubmed.ncbi.nlm.nih.gov/42974717/)；模型：qoder-cn/dfmodel。

### [Pulse Physiology Engine to simulate transient oxygen changes and closed-loop, autonomous pump control during venovenous extracorporeal membrane oxygenation](https://europepmc.org/article/PPR/PPR1356081)

- 标识：`p-5f1eac4c6aec205d313d`；发表：2026-11-03；发现：2026-11-04
- 主题：Treatment Planning and Clinical Decision Support
- 状态：相关综述／资源

该研究基于Pulse生理引擎构建VV-ECMO患者特异模型，比较瞬时SvO2仿真与猪体内数据，将泵速作为模型输入并模拟PI闭环泵控制，报告时间常数相关性与血流预测。

限制：所提供仅为摘要，无法核验完整方法、代码与实现细节；摘要未报告学习或混合转移，Pulse为机制性生理引擎；闭环结论尚待大动物模型验证。

判断：摘要报告VV-ECMO生理任务、患者特异状态、瞬时动态、泵速作为输入、血流预测与PI闭环控制，并有猪体内数据的相关性评估；但核心为机制性生理引擎，摘要未报告学习或混合转移，故按规则归为related。

证据层级：abstract；[来源](https://europepmc.org/article/PPR/PPR1356081)；模型：qoder-cn/dfmodel。

### [Digital twins in geriatrics and gerontology: Applications, challenges, and future directions.](https://pubmed.ncbi.nlm.nih.gov/42570533/)

- 标识：`p-669c1b5d73c6fbe25cd2`；发表：2026-08-03；发现：2026-11-04
- 主题：Longitudinal EHR and Clinical Trajectories、Treatment Planning and Clinical Decision Support
- 状态：相关综述／资源

一篇叙述性综述，系统检索2014–2025年文献，梳理数字孪生在高龄人群与老年医学中的应用，涵盖心血管监测、跌倒预防、痴呆管理、多重用药优化与慢病自我管理，并讨论IoT、人工智能与电子健康档案等使能条件以及隐私、互操作、算力与伦理挑战。

限制：仅有摘要：所提供摘要未报告具体建模方法、状态转移机制、前瞻滚动预测实现或定量评估结果，无代码或数据可得性信息，无法核验。综述性质决定其不能作为方法学证据纳入。

判断：该文为叙述性综述，仅摘要可见，未报告实现的学习型或混合状态转移、可操作的滚动预测与已实施的评估；按规则综述归为相关文献，摘要级综述不可suggest_include。医疗任务与患者状态概念在摘要中有据，但方法与评估证据缺失，故不纳入。

证据层级：abstract；[来源](https://pubmed.ncbi.nlm.nih.gov/42570533/)；模型：qoder-cn/dfmodel。

### [From self-quantification to predictive ageing: Digital twins as a framework for healthy ageing and longevity.](https://pubmed.ncbi.nlm.nih.gov/42705483/)

- 标识：`p-66a09f461840356fd044`；发表：2026-09-08；发现：2026-11-04
- 主题：Computational Biology and Cellular Dynamics、Longitudinal EHR and Clinical Trajectories
- 状态：相关综述／资源

文章提出将衰老视为潜在动力系统的数字孪生框架，整合纵向生物标志物与可穿戴数据，区分可观测生理变化与潜在衰老动态，并设想模拟衰老轨迹和干预反事实测试；但属概念性综述与框架提案。

限制：摘要仅描述概念框架、模型架构与纵向验证策略，未报告实现、代码或实验评估；所述轨迹模拟属设想，无法核验性能。

判断：摘要为概念性综述/框架提案，提出状态空间模型及衰老轨迹模拟设想，但未报告已实现系统或实验评估；按摘要证据不能 suggest_include。

证据层级：abstract；[来源](https://pubmed.ncbi.nlm.nih.gov/42705483/)；模型：qoder-cn/dfmodel。

### [Digital Twins in Clinical Neurology: From Concept to Clinical Application in Multiple Sclerosis.](https://pubmed.ncbi.nlm.nih.gov/42949247/)

- 标识：`p-6f597cce41d570496499`；发表：未知；发现：2026-11-04
- 主题：Longitudinal EHR and Clinical Trajectories、Treatment Planning and Clinical Decision Support
- 状态：相关综述／资源

叙述性综述，以多发性硬化为例梳理神经科患者数字孪生的概念、建模路径与转化障碍。将现有工作映射到数据整合、预测建模、动态更新与临床整合四大组件，指出多模态数据整合、数字生物标志物、机制仿真、虚拟患者与in silico试验等尚属构建模块，尚未整合为持续运行的临床系统。

限制：仅有摘要，无法核验全文的方法细节、系统实现与代码；所提供摘要未报告具体模型性能或前瞻性验证结果，也未量化闭环交互能力。该文为综述，本身不含新模型或新实验。

判断：属综述性文献，讨论数字孪生框架与其在MS中的组成要素，但未提出或实现可评估的状态转移系统，摘要亦未报告定量评估，故作为相关工作而非可纳入的方法研究。

证据层级：abstract；[来源](https://pubmed.ncbi.nlm.nih.gov/42949247/)；模型：qoder-cn/dfmodel。

### [It's about time: modeling circadian regulation of cardiac electrophysiology and arrhythmogenesis.](https://pubmed.ncbi.nlm.nih.gov/42911378/)

- 标识：`p-7a76802f9f6ba53b8147`；发表：2026-10-12；发现：2026-11-04
- 主题：Computational Biology and Cellular Dynamics
- 状态：相关综述／资源

该文综述将昼夜节律调控纳入心脏电生理计算模型的进展，提出“源—传递—靶”框架及 Hodgkin-Huxley 型电流级公式，讨论起搏、心律失常与药物致心律失常风险，并展望昼夜节律感知的心脏数字孪生。

限制：所提供仅为摘要，无法核验全文方法、代码与实验；摘要未报告已实现的运行式预测或评估结果，故不能据此建议纳入。

判断：摘要显示其为心脏电生理昼夜节律建模的迷你综述，具有细胞状态与机制性时间动态，属于相关文献；但综述且仅有摘要，未提供实现的评估或运行式预测证据，不能 suggest_include。

证据层级：abstract；[来源](https://pubmed.ncbi.nlm.nih.gov/42911378/)；模型：qoder-cn/dfmodel。

### [Uncovering disease progression trajectories across multiple timescales with hybrid ODE-mixture models](https://europepmc.org/article/PPR/PPR1355727)

- 标识：`p-7b979c23b8d6f0903630`；发表：2026-11-02；发现：2026-11-04
- 主题：Computational Biology and Cellular Dynamics
- 状态：待核验

提出LCPTA混合框架，将短期机制的ODE建模与长期参数演化的潜在类别轨迹建模结合，并开发TemporalMixtureModels.jl；在高血压与胰岛素抵抗合成纵向数据中恢复亚组结构与轨迹，摘要仅报告合成评估。

限制：证据仅来自摘要；两项评估均为合成纵向研究，未报告真实患者数据、外部验证或可操作的前瞻性滚动预测；无法核验代码与数据可用性，亦未报告临床获益。

判断：摘要表明其面向代谢病进展，具患者状态及机制与学习混合的时序动力学，并完成合成纵向评估；但未提供可操作预测或rollout证据，且仅有摘要级合成验证，故建议hold。

证据层级：abstract；[来源](https://europepmc.org/article/PPR/PPR1355727)；模型：qoder-cn/dfmodel。

### [A digital twin roadmap for adult spinal deformity.](https://pubmed.ncbi.nlm.nih.gov/42975781/)

- 标识：`p-c871f470abda8f63a3f7`；发表：2026-11-03；发现：2026-11-04
- 主题：Treatment Planning and Clinical Decision Support
- 状态：相关综述／资源

该叙述性综述将五组件医学数字孪生框架映射到成人脊柱畸形，提出以患者特异计算模型比较手术路径，并规划从回顾性回放到临床试点的路线图；所提供摘要未报告已实现的系统或评估。

限制：仅有摘要，无法核验模型实现、数据来源、实验评估或代码；所述数字孪生与验证均为路线图构想，不能据此认定临床获益。

判断：成人脊柱畸形手术规划属医学任务，摘要提出患者特异状态与替代治疗路径模拟；但这是摘要级叙述性综述与路线图，所提供摘要未报告已实现的运行式预测或评估，故不满足纳入条件。

证据层级：abstract；[来源](https://pubmed.ncbi.nlm.nih.gov/42975781/)；模型：qoder-cn/dfmodel。

### [Reimagining antimicrobial resistance: AI-driven predictive epidemiology and the C-AMRE framework for next-generation antibiotic discovery.](https://pubmed.ncbi.nlm.nih.gov/42562952/)

- 标识：`p-f07bebc7334c95ac54d8`；发表：2026-08-06；发现：2026-11-04
- 主题：Computational Biology and Cellular Dynamics、Treatment Planning and Clinical Decision Support
- 状态：相关综述／资源

该综述提出C-AMRE计算抗微生物耐药生态系统框架，整合进化智能、AI、全基因组监测、分子模拟与数字孪生，主张将AMR从表型检测与回顾性监测转向分子—患者—群体多层次的预测建模与适应性治疗决策。

限制：仅有摘要：未见模型架构、数据集与训练细节，也未见任何已实现的预测或仿真评估结果与代码链接（所提供摘要未报告，无法核验）。数字孪生与AI药理学多属框架性设想，作者自述验证、可解释性与数据整合仍为未解决障碍。

判断：文章自述为综述，围绕耐药进化轨迹预测与患者感染动力学数字孪生提出多尺度计算框架，属生物医学动态建模相关文献；但摘要级综述不能suggest_include，且所提供摘要缺乏已实现评估与动作条件化推演证据，故定为related。

证据层级：abstract；[来源](https://pubmed.ncbi.nlm.nih.gov/42562952/)；模型：qoder-cn/dfmodel。

### [Artificial intelligence in pediatric nephrology: current applications and emerging frameworks for evidence generation.](https://pubmed.ncbi.nlm.nih.gov/41739204/)

- 标识：`p-304203b461b8ba725929`；发表：2026-02-25；发现：2026-11-04
- 主题：Longitudinal EHR and Clinical Trajectories、Treatment Planning and Clinical Decision Support、Medical Imaging and Radiology
- 状态：相关综述／资源

叙述性综述，概述人工智能在儿童肾脏病学中已可用或新兴的应用，涵盖诊断支持、预后建模、影像与病理分析、治疗个体化，并讨论AI虚拟试验与数字孪生等证据生成框架，以及儿童特有的伦理、监管与公平问题。

限制：仅有摘要，无法核验模型架构、数据集与实验细节；所提供摘要未报告任何已实现的动力学模型、运行式预测或性能评估指标，全文的方法与代码情况不明。

判断：该文为仅提供摘要的叙述性综述，讨论AI在儿童肾脏病学的诊断、预后与个体化治疗应用，并将数字孪生与虚拟试验列为未来方向；但所提供摘要未给出具体系统状态、学习或混合转移动力学、运行式推演及实现评估，无法满足suggest_include所需的五项要素，故按综述规则判为related。

证据层级：abstract；[来源](https://pubmed.ncbi.nlm.nih.gov/41739204/)；模型：qoder-cn/dfmodel。

### [\[Digital operating room-From dream to workflow\].](https://pubmed.ncbi.nlm.nih.gov/42862343/)

- 标识：`p-61cb80c63a8819dcd31c`；发表：2026-10-12；发现：2026-11-04
- 主题：Surgical Simulation and Embodied Healthcare、Treatment Planning and Clinical Decision Support
- 状态：相关综述／资源

该文概述人工智能在创伤患者围手术期护理中的应用，包括术前规划、术中导航与机器人、环境AI与数字孪生、手术记录，以及数据异质性和伦理监管等挑战。

限制：仅提供摘要，属综述性展望；所提供摘要未报告具体模型、学习式状态转移、操作化预测/rollout或已实施评估，无法核验代码与临床效益。

判断：摘要为围手术期AI应用综述，涉及手术流程与机器人状态及规划愿景，但未报告学习/混合动力学、可操作预测或已实施评估；按综述归为related，不能suggest_include。

证据层级：abstract；[来源](https://pubmed.ncbi.nlm.nih.gov/42862343/)；模型：qoder-cn/dfmodel。

### [Stand-In Effects and Pooling Amplification: Design-Based Tests of Whether Biological World Models Use Actions](https://arxiv.org/abs/2611.01666)

- 标识：`p-63564ae7e4cfeb2df2c3`；发表：2026-11-01；发现：2026-11-04
- 主题：Computational Biology and Cellular Dynamics
- 状态：相关综述／资源

提出基于设计律的条件随机化检验，用于判断生物世界模型的预测是否真正受动作影响；揭示替代诊断的“替身效应”和多站点汇集的放大偏差，并在光遗传ERK细胞实验与像素世界模型中验证。

限制：主要贡献是统计检验与验证框架，而非新的可操作生物世界模型；确证性证据仅一个ERK视野、一个时间窗，部分分析为探索性或事后分析；所提供全文未报告临床效用。

判断：全文以光遗传ERK细胞动力学为生物医学场景，评估动作条件世界模型的多步预测与动作检验，具备细胞状态、学习模型和实证评估；但核心是方法学检验框架，不是提出新的可操作预测/rollout世界模型，故列为相关。

证据层级：full_text；[来源](https://arxiv.org/html/2611.01666v1)；模型：qoder-cn/dfmodel。

### [Advancing process control toward intelligent continuous biopharmaceutical manufacturing: Challenges, strategies, and future directions.](https://pubmed.ncbi.nlm.nih.gov/42472568/)

- 标识：`p-6d54950836d3f8e83dc0`；发表：2026-07-19；发现：2026-11-04
- 主题：待分类
- 状态：相关综述／资源

该文为连续生物制药制造过程控制的综述，梳理从常规反馈控制到模型预测控制、强化学习及数字孪生框架的策略演进，并讨论过程分析技术（PAT）与感知—建模—控制架构的整合，以维持持续受控状态。

限制：仅提供摘要；所提供摘要未报告具体实验、代码或可核验的定量评估，且缺乏医疗任务与学习式状态转移的直接证据，故无法核验其方法学细节。

判断：摘要表明其为连续生物制药过程控制综述，涉及模型预测控制、强化学习与数字孪生，但未见医疗任务、候选动作改变传播状态的证据或已实施评估；按规则综述归为相关而非建议纳入。

证据层级：abstract；[来源](https://pubmed.ncbi.nlm.nih.gov/42472568/)；模型：qoder-cn/dfmodel。

### [A proposed organization of multifaceted knowledge in data repositories: structuring record collections and evidence sets for data lakehouses and moonshots.](https://pubmed.ncbi.nlm.nih.gov/42608552/)

- 标识：`p-a4fbaeac98f7c02bd914`；发表：2026-08-17；发现：2026-11-04
- 主题：Longitudinal EHR and Clinical Trajectories
- 状态：相关综述／资源

该文提出PHENOM云平台，以混合湖仓架构和四类数据“箱”整合TBI多模态纵向数据，支持FAIR共享、跨研究查询，并提出数字孪生建模应用愿景。

限制：仅提供摘要；未报告具体状态转移、预测/rollout方法或模型评估。所述初步部署仅涉及数据协调与查询性能，数字孪生能力无法核验。

判断：属TBI多模态数据基础设施/视角文章，涉及患者纵向数据与数字孪生愿景；所提供摘要仅见平台协调与查询性能的部署评估，未报告学习/混合转移动力学及operational forecasting/rollout，故定为related。

证据层级：abstract；[来源](https://pubmed.ncbi.nlm.nih.gov/42608552/)；模型：qoder-cn/dfmodel。

### [biv-me: Open-source software for generating time-varying biventricular meshes from cine cardiovascular magnetic resonance imaging with multi-cohort validation.](https://pubmed.ncbi.nlm.nih.gov/42579973/)

- 标识：`p-a71c28b9c87bf3c9339f`；发表：2026-08-06；发现：2026-11-04
- 主题：Medical Imaging and Radiology
- 状态：相关综述／资源

biv-me 是开源端到端流程，可从电影心血管磁共振 DICOM 自动生成随时间变化的心室网格，并在五个公开数据集共 1313 项检查上外部验证，报告与临床参考软件高度一致、生成快速且可行。

限制：仅基于摘要；未核验全文方法、代码实现细节及模型内部机制。所提供摘要未报告学习到的状态转移、动作条件动力学或操作性预测 rollout。

判断：该工作属于医学影像解剖结构重建与网格生成，具备医学任务、解剖状态、时间变化和实现评估；但摘要未显示 learned/hybrid transition、状态传播 rollout 或候选动作改变状态，因此不满足 suggest_include，按相关影像方法处理。

证据层级：abstract；[来源](https://pubmed.ncbi.nlm.nih.gov/42579973/)；模型：qoder-cn/dfmodel。

### [Implementation Science Driven Identification of Barriers to AI Diagnostic Decision Support: A Stakeholder-Informed Concept Mapping Study](https://arxiv.org/abs/2611.02554)

- 标识：`p-cdc8043e2de8b38f5ab3`；发表：2026-11-02；发现：2026-11-04
- 主题：待分类
- 状态：机器建议排除，待抽查

采用结构化概念映射与整合知识转化框架，汇集96条陈述并归纳为11个集群，识别AI诊断决策支持在基础设施、伦理法律、工作流整合与算法信任方面的落地障碍，并将数字孪生作为未来延伸情境加以讨论。

限制：仅有摘要，无法核验抽样、编码与集群效度等具体方法；该研究为定性实施科学调查，所提供摘要未报告任何模型、状态转移、前瞻展开或定量实验评估，也未提及代码或数据可获取性。

判断：该文为定性实施科学概念映射研究，主题是AI诊断工具的组织与工作流采纳障碍，未定义可演化的系统状态、未使用学习或混合转移、无操作性预测展开与已实现的评估；数字孪生仅在讨论中被提及为未来情境，所提供摘要未报告任何世界模型构建或实验，故不满足纳入标准。

证据层级：abstract；[来源](https://arxiv.org/abs/2611.02554)；模型：qoder-cn/dfmodel。

Full-text access failed (HTTPError); abstract retained.

### [Prediction of Plasma Concentration-Time Profiles in Mice from Chemical Structure Using a Kinetically Constrained Hybrid Neural ODE.](https://europepmc.org/article/MED/42969730)

- 标识：`p-079ddee0912cb0cecfb8`；发表：2026-11-01；发现：2026-11-04
- 主题：Computational Biology and Cellular Dynamics
- 状态：待核验

提出KCH-NODE，将可学习的二室PK典型轨迹与Neural ODE刻画的化合物特异连续时间偏差结合，从化学结构预测小鼠静脉和口服血浆浓度-时间曲线，并在交叉验证及时间外推集报告RMSE。

限制：仅有摘要，无法核验全文方法、代码与完整实验；所提供摘要未报告动作条件或反事实评估，口服PK在时间外推集准确度有限，临床转化无法核验。

判断：摘要显示药代动力学轨迹预测任务、二室状态、混合Neural ODE动力学与交叉验证/时间外推RMSE，方向契合；但证据仅为摘要，未能核验全文中的方法与实验细节，故按证据不足暂缓而非纳入。

证据层级：abstract；[来源](https://europepmc.org/article/MED/42969730)；模型：qoder-cn/dfmodel。

### [Nerandomilast is Associated With Altered Alveolar Epithelial Cell State Dynamics While Attenuating Fibrotic Remodeling in Pulmonary Fibrosis.](https://europepmc.org/article/MED/42827411)

- 标识：`p-39dcf4a2058ac039ebf2`；发表：2026-11-01；发现：2026-11-04
- 主题：Computational Biology and Cellular Dynamics
- 状态：相关综述／资源

该研究在小鼠博来霉素肺纤维化模型中结合scRNA-seq、RNA velocity与组织学，发现nerandomilast减轻纤维化并改变肺泡上皮细胞状态动态，尤其是AT2向过渡态的方向性流动。

限制：所提供全文为实验性机制研究，未提出可学习或混合的状态转移世界模型，也未报告可操作预测或rollout评估；样本量小、单剂量模型，因果机制未明。

判断：文章满足医学任务、细胞状态和时间动态证据，但仅用RNA velocity推断细胞状态轨迹，未构建动作条件化世界模型，也未实施预测或rollout评估，故不能suggest_include，仅作为细胞动力学相关文献。

证据层级：full_text；[来源](https://www.ebi.ac.uk/europepmc/webservices/rest/PMC13633504/fullTextXML)；模型：qoder-cn/dfmodel。

### [Entity-aware pathology workflow informatics: Structured evidence mapping and a reference architecture for governed orchestration.](https://pubmed.ncbi.nlm.nih.gov/42893223/)

- 标识：`p-1d6534420636f64b3762`；发表：2026-09-14；发现：2026-11-04
- 主题：Longitudinal EHR and Clinical Trajectories
- 状态：相关综述／资源

该文以结构化证据映射梳理病理工作流中病例、标本、蜡块、切片、扫描与报告的表征和治理，并提出语义感知、实体感知过程状态、受限编排与治理执行的参考架构；属综述与架构设计，而非已部署验证的世界模型。

限制：仅有摘要；未报告可核验的学习或混合状态转移动力学、操作级预测/rollout与已实现系统评估；作者明确架构未部署验证，无法核验代码或临床效益。

判断：所提供摘要为结构化证据映射并推导病理工作流参考架构；虽涉及实体感知过程状态与治理编排，但未给出学习/混合状态转移动力学、操作级预测/rollout或已实现系统评估，且作者称架构未部署验证，故不宜suggest_include，按综述/架构归为related。

证据层级：abstract；[来源](https://pubmed.ncbi.nlm.nih.gov/42893223/)；模型：qoder-cn/dfmodel。
