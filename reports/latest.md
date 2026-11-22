# 医疗世界模型文献摘要 · 2026-11-22

机器整理的候选与收录建议；未代表人工审核或实验复现。

候选库：115 篇；当日发现、更新或完成分析：88 篇。

已有有效中文分析：114 篇；待分析或缺少摘要证据：1 篇。

## 检索覆盖

- arxiv / 查询 0b853c5d2ddf：17 条；完整
- arxiv / 查询 974e2bc9882c：0 条；完整
- europepmc / 查询 f74b0612eaf2：24 条；完整
- europepmc / 查询 f11522d6c8db：1 条；完整
- pubmed / 查询 e190f0b25756：22 条；完整
- pubmed / 查询 1a5e763292f9：2 条；完整

模型分析失败 1 次，保留候选并等待重试。

## 当日候选

### [Longevitomics as the Science of the Longevitome: Towards a Unified Systems Science of Healthy Longevity.](https://europepmc.org/article/MED/43014623)

- 标识：`p-05a76bab5b63a10c0549`；发表：2026-11-11；发现：2026-11-15
- 主题：Computational Biology and Cellular Dynamics
- 状态：相关综述／资源

文章提出Longevitomics与Longevitome概念，主张纵向整合多组学、生理表型、环境暴露与适应反应，以建模和预测健康长寿，并讨论网络分析、因果推断、机器学习与数字孪生用于个体化长寿医学的潜力。

限制：仅有摘要；该文属概念框架与立场文章，所提供摘要未报告具体状态转移模型、可执行推演或已实现的实验评估，数字孪生与轨迹重建的实现程度无法核验。

判断：该文是健康长寿的系统科学框架文章，讨论纵向轨迹预测与数字孪生，但所提供摘要未报告具体动力学模型、rollout或已实现评估，不满足suggest_include；作为相关框架列为related。状态标签仅保留Physiology。

证据层级：abstract；[来源](https://europepmc.org/article/MED/43014623)；模型：qoder-cn/dfmodel。

### [Comparing Each Generation with Independent Siblings Gives Video World Model Post-Training a Proper Objective for Outcome Frequencies](https://arxiv.org/abs/2611.24512)

- 标识：`p-09c0a78312f760cd8470`；发表：2026-11-18；发现：2026-11-22
- 主题：待分类
- 状态：机器建议排除，待抽查

提出SibPO：用同一历史下独立生成的兄弟样本估计结果频率的截断逆频率权重，并加入兄弟项校正截断偏差，使视频世界模型后训练的目标在任意组大小下唯一最大化于数据分布；在PisaBench、Physion、Kubric和机器人策略成功率评估上验证。

限制：所提供全文为通用视频世界模型与机器人策略评估，未见医学任务、医学数据或临床/生理验证；不能支持生物医学纳入。

判断：论文聚焦视频世界模型后训练与物理/机器人仿真，虽具备状态、学习动力学、滚动预测和实现评估，但缺少医学任务与生物医学状态，且没有可标注的生物医学主题，故按标准不能纳入。

证据层级：full_text；[来源](https://arxiv.org/html/2611.24512v1)；模型：qoder-cn/dfmodel。

### [Advanced drug delivery strategies for overcoming tumor-mediated molecular hijacking: Emerging nanotherapeutics, advanced biotherapeutics, and artificial intelligence.](https://europepmc.org/article/MED/43034267)

- 标识：`p-0cb499d5d02a03d45e43`；发表：2026-11-14；发现：2026-11-22
- 主题：Computational Biology and Cellular Dynamics、Treatment Planning and Clinical Decision Support
- 状态：相关综述／资源

该综述将肿瘤耐药与微环境适应概括为“肿瘤介导的分子劫持”，评述纳米载体、ADC、CAR-T、CRISPR、RNA疗法及AI在结构设计、载体优化、疗效预测和患者数字孪生中的应用。

限制：仅提供摘要，无法核验全文方法、代码、实验与定量结果；未见可操作的状态转移模型或前瞻性临床验证，AI与数字孪生仅作综述性提及。

判断：摘要为综述，讨论肿瘤耐药机制及药物递送与AI辅助设计，与生物医学世界模型相关；但未描述可学习或混合状态转移、操作式预测或已实现评估，且摘要级综述不能建议纳入。

证据层级：abstract；[来源](https://europepmc.org/article/MED/43034267)；模型：qoder-cn/dfmodel。

### [Engineering smart liposomes to combat antimicrobial resistance: from mechanistic design to clinical translation.](https://europepmc.org/article/MED/42955867)

- 标识：`p-0e0c66c6a10cc278606c`；发表：2026-10-29；发现：2026-11-04
- 主题：Treatment Planning and Clinical Decision Support
- 状态：相关综述／资源

综述智能脂质体抗耐药菌感染，涵盖刺激响应与可编程递送、药代与药效改善、制造监管，以及人工智能配方优化和数字孪生决策支持，强调转化需感染特异证据。

限制：仅提供摘要，无法核验全文方法、代码或实验；所提供摘要未报告世界模型、状态转移、推演或定量预测评估。

判断：该文为抗耐药感染智能脂质体综述，讨论机制设计、药代与药效及临床转化，但未构建可学习或混合状态转移，也未报告操作性预测或实现评估，故归为相关。

证据层级：abstract；[来源](https://europepmc.org/article/MED/42955867)；模型：qoder-cn/dfmodel。

### [The road ahead for stem cell therapies in type 1 diabetes.](https://europepmc.org/article/MED/43010164)

- 标识：`p-11c7e17ae53f2ce59f88`；发表：2026-11-10；发现：2026-11-15
- 主题：Computational Biology and Cellular Dynamics
- 状态：相关综述／资源

该综述讨论1型糖尿病干细胞来源β细胞替代治疗的组织工程、合成生物学及计算与单细胞方法，提到数字孪生框架等预测工具可用于评估分化质量并预测移植物结局，但未提出或验证具体世界模型。

限制：仅提供摘要且为综述，未报告可核验的模型实现、代码、操作式推演或实验评估；数字孪生与预测工具仅为展望，无法核验其方法细节。

判断：文章属于干细胞治疗综述，涉及细胞状态与移植物结局，并提及数字孪生和预测工具；但所提供摘要未报告学习或混合转移动力学及已实现的评估，因此不满足 suggest_include 的完整证据要求。

证据层级：abstract；[来源](https://europepmc.org/article/MED/43010164)；模型：qoder-cn/dfmodel。

### [The Digital Twin Paradigm in Head and Neck Cancer: Clinical Opportunities and Challenges.](https://pubmed.ncbi.nlm.nih.gov/42976352/)

- 标识：`p-1253e40ab00bce9d55e0`；发表：2026-11-03；发现：2026-11-08
- 主题：Medical Imaging and Radiology、Treatment Planning and Clinical Decision Support、Computational Biology and Cellular Dynamics
- 状态：相关综述／资源

该文为头颈鳞癌数字孪生的观点/综述，提出解剖、剂量与生物三层框架，整合影像、组学与临床数据，讨论自适应放疗、虚拟临床试验、毒性监测、实施障碍与技术路线。

限制：所提供全文为观点/综述，未报告作者原创实现的数字孪生系统、代码或前瞻性临床验证；多项预测与疗效数据来自引用研究，属概念与路线图证据。

判断：文章系统讨论HNSCC数字孪生框架、临床机会与障碍，但属观点/综述，未报告作者实现并评估的可操作世界模型，故为related而非suggest_include。

证据层级：full_text；[来源](https://www.ebi.ac.uk/europepmc/webservices/rest/PMC13730516/fullTextXML)；模型：qoder-cn/dfmodel。

### [&lt;span data-teams="true"&gt;Biphasic Digital Twin for Dynamic Coronary Occlusion Risk of TAVR: Beyond Static Anatomical Assessment](https://europepmc.org/article/PPR/PPR1363898)

- 标识：`p-13fb6bc19e8f457ba5e8`；发表：2026-11-11；发现：2026-11-15
- 主题：Medical Imaging and Radiology、Treatment Planning and Clinical Decision Support
- 状态：相关综述／资源

该摘要报告一例重度主动脉瓣狭窄患者的双相数字孪生，融合收缩期与舒张期CT评估TAVR冠状动脉阻塞风险，并比较两种植入深度下虚拟瓣膜-冠状动脉距离变化。属患者特异性机制仿真，摘要未报告学习型动力学或系统验证。

限制：仅摘要级证据、单病例；未报告学习/混合转移、操作预测或系统评估，无法核验代码与临床获益。

判断：摘要满足医学任务、患者解剖状态与机制仿真，并展示植入深度改变VTC的推演；但缺乏学习/混合动力学和系统性实现评估，且仅摘要/单病例，按机制仿真归为related而非suggest_include。

证据层级：abstract；[来源](https://europepmc.org/article/PPR/PPR1363898)；模型：qoder-cn/dfmodel。

### [Development of a Digital Twin to Analyse Waiting Lists in a Sleep-Disordered Breathing Unit.](https://europepmc.org/article/MED/43000229)

- 标识：`p-141357781471e70bd67e`；发表：2026-11-08；发现：2026-11-15
- 主题：Longitudinal EHR and Clinical Trajectories
- 状态：相关综述／资源

该研究构建并验证睡眠呼吸障碍单元患者流与等待名单的数字孪生，用MATLAB离散事件仿真复现六个诊疗阶段，以2024年数据参数化、2025年数据验证，并用MAE、RMSE和RPD评估队列长度与等待时间。

限制：仅摘要；所提供摘要未报告学习/混合转移、代码或前瞻性部署；随访等待时间RPD达73.7%，外部有效性有限。

判断：摘要显示该数字孪生针对睡眠呼吸障碍单元的等待名单与患者流，复现六阶段并做了MAE/RMSE/RPD验证；但其转移为机制性离散事件仿真，所提供摘要未报告学习/混合转移，故为相关而非建议纳入。

证据层级：abstract；[来源](https://europepmc.org/article/MED/43000229)；模型：qoder-cn/dfmodel。

### [Agentic Artificial Intelligence-Driven Neutrosophic Multi-Objective Optimization of Oxygen Transfer Systems in Smart Bioreactors.](https://europepmc.org/article/MED/42954038)

- 标识：`p-153a1ea8b8272b8f8db6`；发表：2026-10-29；发现：2026-11-04
- 主题：Computational Biology and Cellular Dynamics
- 状态：相关综述／资源

提出集成同步数字孪生、智能体AI、模糊中性集建模与多目标决策的闭环框架，用于智能生物反应器氧传递控制；可连续重构过程状态、预测短期行为、生成并虚拟筛选控制方案，在扰动下报告溶氧稳定性与恢复时间。

限制：仅基于摘要；所提供摘要未报告具体学习型转移模型、代码、数据与完整实验细节，且生物反应器氧传递控制是否属医学任务不明确，无法核验临床或细胞级收益。

判断：该文为工业生物反应器氧传递控制的数字孪生与智能体决策框架，具备状态重构、短期预测与控制选项虚拟评估，但任务属生物过程工程而非明确医学任务，故列为相关而非纳入。

证据层级：abstract；[来源](https://europepmc.org/article/MED/42954038)；模型：qoder-cn/dfmodel。

### [In Silico Insights into Device-Artery Interactions in Endovascular Pulmonary Flow Restrictors for Neonates with Congenital Heart Defects.](https://pubmed.ncbi.nlm.nih.gov/42977806/)

- 标识：`p-1d8e9e16cd5bcf45fc55`；发表：2026-11-03；发现：2026-11-08
- 主题：Surgical Simulation and Embodied Healthcare
- 状态：相关综述／资源

该研究构建并验证MVP装置数字孪生，结合新生儿临床影像与理想化肺动脉几何，开展患者特异性有限元模拟，量化装置扩张后血管刚度及局部接触压力分布。

限制：仅提供摘要；所提供摘要未报告学习型或混合状态转移动力学、操作序列或代码链接，无法核验完整实验与临床获益。

判断：摘要显示其为机制性有限元/数字孪生模拟，用于装置-动脉相互作用；缺少学习或混合转移与操作式预测/rollout证据，故按机制性模拟器归为related。

证据层级：abstract；[来源](https://pubmed.ncbi.nlm.nih.gov/42977806/)；模型：qoder-cn/dfmodel。

### [Digital Twin Technology for Image-Guided Thermal Ablation of Pulmonary Nodules: From Computational Proof-of-Concept to Clinical Translation](https://europepmc.org/article/PPR/PPR1360029)

- 标识：`p-1da08ec4bf30b78640e9`；发表：2026-11-04；发现：2026-11-15
- 主题：Medical Imaging and Radiology、Treatment Planning and Clinical Decision Support
- 状态：相关综述／资源

该叙述性综述讨论肺结节经皮与经支气管热消融的数字孪生框架，提出三层术语体系与四层技术栈，并主张首个闭环肺消融数字孪生尚待构建。

限制：所提供摘要为叙述性综述，未报告作者实现的模型代码、前瞻性实验或临床效用；其所述验证细节与可复现性无法核验。

判断：属影像引导肺消融数字孪生的叙述性综述，提出规划与仿真框架，但所提供摘要未报告作者实现的动力学模型、运行式预测或评估，故不满足 suggest_include，按综述归为 related。

证据层级：abstract；[来源](https://europepmc.org/article/PPR/PPR1360029)；模型：qoder-cn/dfmodel。

### [Nano-Bioadhesives for Gastrointestinal Hemostasis and Healing: Integrating Artificial Intelligence for Precision Design and Application.](https://pubmed.ncbi.nlm.nih.gov/42975278/)

- 标识：`p-2fd34f283489ce52280f`；发表：2026-11-03；发现：2026-11-04
- 主题：Treatment Planning and Clinical Decision Support
- 状态：相关综述／资源

该文为综述，讨论胃肠道出血与黏膜损伤用纳米生物黏附剂的AI辅助设计，强调黏附、止血、降解、生物安全与愈合的多目标优化，并展望预测建模、分子模拟、数字孪生与闭环优化等方向。

限制：仅有摘要，无法核验完整方法、代码与实验；未报告具体世界模型、状态表征或可执行评估。综述性质且无实现细节，不能作为可纳入的动力学模型证据。

判断：摘要显示这是关于AI与纳米材料设计协同的综述，指出“predictive modeling, molecular simulations”与“digital twins and closed-loop optimization”为未来方向，但所提供摘要未报告任何已实现的状态转移模型、滚动预测或定量评估，故按综述处理为related；因缺乏可核验方法细节，不排除全文存在相关建模工作。

证据层级：abstract；[来源](https://pubmed.ncbi.nlm.nih.gov/42975278/)；模型：qoder-cn/dfmodel。

### [Digital twin-enabled toxicology: Current applications, opportunities, and future directions.](https://pubmed.ncbi.nlm.nih.gov/42686080/)

- 标识：`p-345fc899021da38e74dd`；发表：2026-09-02；发现：2026-11-04
- 主题：Computational Biology and Cellular Dynamics
- 状态：相关综述／资源

该叙述性综述讨论数字孪生毒理学应用，涵盖药物安全、环境与职业毒理及个体易感性，强调组学、可穿戴传感器和人工智能融合，并指出数据标准化、验证与监管接受等挑战。

限制：所提供摘要未报告具体模型实现、代码或定量验证，无法核验其预测性能；作为叙述性综述，不能据此建议纳入。

判断：摘要显示其为人毒理与药物安全相关数字孪生综述，具备生理系统状态与机制模拟概念；但未报告学习或混合状态转移、操作级滚动预测或已实施评估，故按综述归为相关。

证据层级：abstract；[来源](https://pubmed.ncbi.nlm.nih.gov/42686080/)；模型：qoder-cn/dfmodel。

### [Non-invasive Computational Techniques for Diagnosing Myocardial Ischemia: Challenges and Future of FFRCT/iFRCT.](https://pubmed.ncbi.nlm.nih.gov/42209956/)

- 标识：`p-36aa4c085ad367a2ad27`；发表：2026-05-28；发现：2026-11-04
- 主题：Medical Imaging and Radiology
- 状态：相关综述／资源

该文综述基于CFD的FFRCT/iFRCT无创评估心肌缺血的计算模型，指出刚性血管壁与微循环代偿等生理简化会限制诊断准确性及实时应用，并展望结合多模态数据、AI与数字孪生的高保真心血管仿真与动态预警。

限制：仅提供摘要，属综述；所提供摘要未报告作者实现的模型、前瞻性验证、代码链接或临床获益，也无法核验全文中的操作化预测/推演评估。

判断：主题为心肌缺血无创诊断的计算流体力学模型综述，涉及生理状态与机制建模，但未提出并评估可操作推演的世界模型；摘要属综述且无实施评估，故列为相关。

证据层级：abstract；[来源](https://pubmed.ncbi.nlm.nih.gov/42209956/)；模型：qoder-cn/dfmodel。

### [Digital twin oncology and multi-omics-driven artificial intelligence models for personalized drug response prediction: A systematic survey of emerging computational paradigms and clinical implementation challenges.](https://europepmc.org/article/MED/43025061)

- 标识：`p-39d94113417db46a8c2e`；发表：2026-11-10；发现：2026-11-15
- 主题：Computational Biology and Cellular Dynamics、Treatment Planning and Clinical Decision Support
- 状态：相关综述／资源

该文系统综述数字孪生肿瘤学与多组学人工智能结合的药物反应预测研究，归纳四类建模范式与多组学融合策略，并讨论肿瘤演化预测、虚拟临床试验及临床落地的数据、可解释性与监管挑战。

限制：仅提供摘要，无法核验全文的方法细节、代码与实验结果；所提供摘要未报告作者自身实现的模型或已执行的定量评估，仅说明开展系统综述与比较分析。

判断：摘要表明其为系统综述，主题覆盖数字孪生、多组学与AI药物反应预测，并提及肿瘤演化预测与虚拟临床试验；但缺少本工作实现的模型与已实施评估，按规则将综述归为related。

证据层级：abstract；[来源](https://europepmc.org/article/MED/43025061)；模型：qoder-cn/dfmodel。

### [Computational Models of the Foreign Body Response: A Focus on Biomaterial Properties.](https://pubmed.ncbi.nlm.nih.gov/42974717/)

- 标识：`p-3d64048702f422c07394`；发表：2026；发现：2026-11-04
- 主题：Computational Biology and Cellular Dynamics
- 状态：相关综述／资源

该文综述异物反应（FBR）的计算模型，涵盖常微分方程、偏微分方程与基于主体的模型，用于刻画炎症信号、巨噬细胞动态、纤维化进展与囊膜形成，并讨论材料属性（表面化学、形貌、刚度）在模型中的表征方式，提出以FBR数字孪生为最终目标、加强混合预测模型与实验数据结合的方向。

限制：仅有摘要，未报告具体模型实现、代码、数据或定量验证结果；所提供摘要未报告系统性评估实验或可复现资源，且明确指出标准化标定与验证数据稀缺，故无法核验其实际预测性能。

判断：该文为仅提供摘要的综述，聚焦异物反应的机制性与数据驱动计算模型，属于与生物医学世界模型相关的方法学综述；但未提出具名系统，未报告操作性预测推演或已实现的评估，仅将数字孪生列为未来目标，故按规则不宜列为纳入，也不应排除。

证据层级：abstract；[来源](https://pubmed.ncbi.nlm.nih.gov/42974717/)；模型：qoder-cn/dfmodel。

### [Patient-Specific Physical and Computational Models for Replicating Coronary Stent Deployment.](https://europepmc.org/article/MED/42998085)

- 标识：`p-45b40c994af820ae69e5`；发表：2026-11-06；发现：2026-11-15
- 主题：Medical Imaging and Radiology、Treatment Planning and Clinical Decision Support
- 状态：相关综述／资源

该研究利用患者影像重建冠状动脉，制作3D打印体模与有限元数字孪生，模拟同一支架和球囊部署，并与OCT比较。两平台复现关键手术特征，但管腔增益分别低估和高估，属机制性概念验证。

限制：仅有摘要；所提供摘要未报告学习或混合状态转移动力学、代码或完整验证；定量准确性有限，无法核验全文方法与临床效用。

判断：摘要显示患者特异性冠脉支架部署的有限元与物理孪生模拟，并以OCT作实现评估；但为机制性模拟器，所提供摘要未报告学习或混合转移，故不满足 suggest_include，归为 related。

证据层级：abstract；[来源](https://europepmc.org/article/MED/42998085)；模型：qoder-cn/dfmodel。

### [Reinforcement Learning with World Models in the Era of Scale: From Online Imagination to World Action Models](https://europepmc.org/article/PPR/PPR1353089)

- 标识：`p-596c8bcb2d36089a881e`；发表：2026-10-29；发现：2026-11-04
- 主题：Computational Biology and Cellular Dynamics
- 状态：相关综述／资源

这是一篇关于世界模型强化学习（WM-RL）的综述摘要，梳理2019至2026年间从在线基于模型的强化学习到预训练想象式策略训练、从解耦世界模型与策略到统一World Action Models的范式转变，并涵盖机器人、导航、自动驾驶、医疗与分子动力学等应用。

限制：仅提供摘要，无法核验具体方法、实验与代码；医疗与分子动力学仅作应用列举，摘要未报告医学任务定义、状态表示或评估细节。

判断：该文为摘要级综述，讨论世界模型与基于模型的强化学习，虽提及医疗治疗与分子动力学应用，但未给出具体医学任务、系统状态、转移学习与已实现评估，故按规则归为相关综述，不能suggest_include。

证据层级：abstract；[来源](https://europepmc.org/article/PPR/PPR1353089)；模型：qoder-cn/dfmodel。

### [Pulse Physiology Engine to simulate transient oxygen changes and closed-loop, autonomous pump control during venovenous extracorporeal membrane oxygenation](https://europepmc.org/article/PPR/PPR1356081)

- 标识：`p-5f1eac4c6aec205d313d`；发表：2026-11-03；发现：2026-11-04
- 主题：Treatment Planning and Clinical Decision Support
- 状态：相关综述／资源

该研究基于Pulse Physiology Engine构建VV-ECMO患者特异性生理模型，将瞬态静脉血氧饱和度仿真与猪体内数据比较，把泵速设为模型输入，并用PI控制器模拟闭环泵控制及扰动抑制。

限制：仅依据所提供摘要，无法核验全文方法、代码与实验规模；摘要未报告学习型或混合型状态转移，闭环控制仅在仿真中评估，临床效用无法核验。

判断：摘要报告基于Pulse Physiology Engine的VV-ECMO患者特异性机理模型，含泵速输入与闭环控制仿真，并开展与猪体内数据的相关性评估；但未见学习型或混合型状态转移，属机理型仿真，故建议related。

证据层级：abstract；[来源](https://europepmc.org/article/PPR/PPR1356081)；模型：qoder-cn/dfmodel。

### [From self-quantification to predictive ageing: Digital twins as a framework for healthy ageing and longevity.](https://pubmed.ncbi.nlm.nih.gov/42705483/)

- 标识：`p-66a09f461840356fd044`；发表：2026-09-08；发现：2026-11-04
- 主题：Computational Biology and Cellular Dynamics、Longitudinal EHR and Clinical Trajectories
- 状态：相关综述／资源

文章提出将衰老视为潜在动力系统的数字孪生框架，整合纵向生物标志物与可穿戴数据，拟用于模拟衰老轨迹、反事实评估干预，并区分短暂生物标志物改善与持久动力学改变。

限制：仅提供摘要；摘要未报告已实现模型、代码、具体数据或前瞻性验证结果，无法核验预测性能与临床效用；所述验证仅停留在策略层面。

判断：该文是概念性数字孪生框架/综述，提出状态空间模型及模拟、反事实评估设想，但摘要未报告已实现系统或实证评估；按规则综述与框架类工作列为相关，而非建议纳入。

证据层级：abstract；[来源](https://pubmed.ncbi.nlm.nih.gov/42705483/)；模型：qoder-cn/dfmodel。

### [AI-powered virtual cells, digital twins and agentic AI are reshaping multi-omics, spatial biology and drug discovery.](https://pubmed.ncbi.nlm.nih.gov/43046701/)

- 标识：`p-67078adf31f26ee425a4`；发表：2026-11-17；发现：2026-11-22
- 主题：Computational Biology and Cellular Dynamics
- 状态：相关综述／资源

该文为叙述性综述，提出AI虚拟细胞的六项能力嵌套框架，涵盖群体衍生模型、数字孪生与智能体孪生，主张融合单细胞与空间组学以建模细胞状态、相互作用及治疗反应，并用于药物发现中的前瞻性预测与扰动、靶点优先级排序。

限制：证据仅限摘要；所提供摘要未报告具体建模方法、代码链接或已实施的实验验证，前瞻性验证仅为作者主张，模型性能、泛化能力与临床价值均无法核验。

判断：该文讨论AI虚拟细胞与数字孪生对细胞状态及治疗反应的预测，属生物医学建模范畴；但为摘要级叙述性综述，未呈现已实现的系统状态定义、学习转移机制与实施评估，且摘要级综述不能建议纳入，故列为相关。

证据层级：abstract；[来源](https://pubmed.ncbi.nlm.nih.gov/43046701/)；模型：qoder-cn/dfmodel。

### [A mechanistic digital twin of the corneal endothelium separates early postoperative and long-term endothelial cell loss after keratoplasty](https://europepmc.org/article/PPR/PPR1366780)

- 标识：`p-696f9d6a86d28c01c984`；发表：2026-11-13；发现：2026-11-15
- 主题：Computational Biology and Cellular Dynamics、Treatment Planning and Clinical Decision Support
- 状态：相关综述／资源

该摘要构建角膜内皮的双阶段 agent-based 机理数字孪生，用 CPTS 校准并在 CDS 测试，预测术后内皮细胞密度轨迹，并以 ROCK 抑制剂在硅反事实评估细胞保全效果。

限制：仅有摘要，无法核验模型实现、代码与数据可用性及完整实验；所提供摘要未明确报告学习型或混合型状态转移，药物反事实也仅为在硅结果，缺乏临床验证。

判断：摘要显示其为校准后的 agent-based 机理数字孪生，具备细胞状态、时间 rollout、独立队列评估与药物在硅反事实；但转移机制以机理建模为主，摘要未明确学习或混合转移，故按机理型模拟器归为 related。

证据层级：abstract；[来源](https://europepmc.org/article/PPR/PPR1366780)；模型：qoder-cn/dfmodel。

### [Digital Twins in Clinical Neurology: From Concept to Clinical Application in Multiple Sclerosis.](https://pubmed.ncbi.nlm.nih.gov/42949247/)

- 标识：`p-6f597cce41d570496499`；发表：2026；发现：2026-11-04
- 主题：Longitudinal EHR and Clinical Trajectories、Treatment Planning and Clinical Decision Support
- 状态：相关综述／资源

该叙述性综述梳理神经病学尤其是多发性硬化中的患者数字孪生概念、建模路径与转化障碍，涵盖多模态数据整合、预测建模、机制仿真和虚拟患者/硅试验，但指出尚未形成持续运行、临床嵌入的闭环系统。

限制：所提供仅为摘要；无法核验全文方法、代码或实验；摘要未报告已实现的连续预测或滚动评估，不能据此断言全文缺失。

判断：摘要显示为叙述性综述，讨论数字孪生组件与挑战，而非提出并评估一个可运行的医学世界模型；按综述归为related，且摘要证据不足以suggest_include。

证据层级：abstract；[来源](https://pubmed.ncbi.nlm.nih.gov/42949247/)；模型：qoder-cn/dfmodel。

### [Testing World Models on Actions They Have Never Seen: Held-Out Plans, Forecast Accuracy and Price Rules in Retail](https://arxiv.org/abs/2611.22537)

- 标识：`p-77f1450f3377751f9dfb`；发表：2026-11-17；发现：2026-11-22
- 主题：Treatment Planning and Clinical Decision Support
- 状态：相关综述／资源

提出行动条件世界模型的留出计划测试：在零售价格/促销中比较世界模型、LightGBM与对数线性模型，并在生成给药世界作压力测试；给药世界含患者严重度、药物蓄积与剂量反应。

限制：给药世界为合成压力测试，作者明确其不是临床模型或任何药物/疾病模型；真实数据仅零售促销；无真实生物医学外部验证；不能据此推断临床获益。

判断：主评估是零售价格/促销世界模型；给药世界仅为生成式压力测试，作者明确其非临床或药物/疾病模型，且真实数据均为零售，故作为方法学相关而非建议纳入。

证据层级：full_text；[来源](https://arxiv.org/html/2611.22537v1)；模型：qoder-cn/dfmodel。

### [Measuring the Conservatism of Latent Safety Filters for World Models](https://arxiv.org/abs/2611.23685)

- 标识：`p-781bb1d7f62e7ed76629`；发表：2026-11-18；发现：2026-11-22
- 主题：待分类
- 状态：机器建议排除，待抽查

提出潜在安全过滤器的 overlap 度量，证明其为一格一决策过滤器为不放过数据中任何危险转移而必须拒绝安全转移的最小比例，并在 MuJoCo 视觉导航中比较三种安全标签注入设计；独立安全编码器的重叠最低、拒绝安全动作最少、到达目标最多。

限制：所提供全文为机器人视觉导航仿真实验，未报告医学数据、临床或生理场景；因此不能作为生物医学世界模型纳入本综述。

判断：该文研究机器人视觉导航中潜在安全过滤器与世界模型规划，未涉及任何生物医学任务、医学状态或临床/生理动态，超出本综述主题范围。

证据层级：full_text；[来源](https://arxiv.org/html/2611.23685v1)；模型：qoder-cn/dfmodel。

### [It's about time: modeling circadian regulation of cardiac electrophysiology and arrhythmogenesis.](https://pubmed.ncbi.nlm.nih.gov/42911378/)

- 标识：`p-7a76802f9f6ba53b8147`；发表：2026-10-12；发现：2026-11-04
- 主题：Computational Biology and Cellular Dynamics
- 状态：相关综述／资源

该综述讨论如何将昼夜节律调控纳入心脏电生理计算模型，涵盖窦房结与心室肌细胞起搏、致心律失常性及药物致心律失常风险，并提出“源—传递—靶”框架和Hodgkin-Huxley型电流级建模思路，面向节律感知数字孪生与时间分辨风险预测。

限制：仅提供摘要，无法核验具体模型实现、数据集、代码、定量实验与临床验证；所提供摘要未报告系统性评估或可复现资源。

判断：文章为迷你综述，聚焦机制性心脏电生理模型中的昼夜节律参数化与仿真框架，属生物医学世界模型相关文献；但摘要未报告可核验的实现与评估，且综述不能作为suggest_include。

证据层级：abstract；[来源](https://pubmed.ncbi.nlm.nih.gov/42911378/)；模型：qoder-cn/dfmodel。

### [Uncovering disease progression trajectories across multiple timescales with hybrid ODE-mixture models](https://europepmc.org/article/PPR/PPR1355727)

- 标识：`p-7b979c23b8d6f0903630`；发表：2026-11-02；发现：2026-11-04
- 主题：Computational Biology and Cellular Dynamics、Longitudinal EHR and Clinical Trajectories
- 状态：待核验

提出LCPTA混合框架，结合短期机制性ODE与长期潜类别参数轨迹，用于跨时间尺度疾病进展建模；在高血压和胰岛素抵抗的合成纵向队列中评估轨迹重建与亚组识别。

限制：证据仅为摘要；评估限于合成/虚拟队列，所提供摘要未报告真实患者验证或明确的操作性预测推演；无法核验全文方法细节与代码链接。

判断：摘要显示代谢病进展建模、ODE与潜类别混合动力学及合成纵向评估，但仅有摘要且未明确展示操作性的前瞻预测或推演；按规则暂缓纳入，而非排除。

证据层级：abstract；[来源](https://europepmc.org/article/PPR/PPR1355727)；模型：qoder-cn/dfmodel。

### [Transcriptome-Informed Digital Twins Reveal a Functional Response Landscape in Prostate Cancer.](https://europepmc.org/article/MED/43028297)

- 标识：`p-821d9f262689ee6d6460`；发表：2026-11-09；发现：2026-11-15
- 主题：Computational Biology and Cellular Dynamics
- 状态：建议纳入，待审核

该研究用TCGA-PRAD转录组构建8节点动力学数字孪生，个性化初始状态与基础产生参数，模拟AR/PI3K/TGF-β扰动，生成42维行为指纹并分析连续响应景观、临床/分子关联及敏感性。

限制：基于单一TCGA-PRAD队列的回顾性计算分析，缺乏纵向治疗反应数据；8节点网络与参数多为假设，未校准PK/PD；外部验证仅为细胞系方向性比较，不能证明临床预测或治疗获益。

判断：全文提供医学任务、可个性化状态、机制/数据混合动力学、扰动下时序推演及已实现评估，符合纳入条件；其能力为机制性反事实模拟而非自主临床预测。

证据层级：full_text；[来源](https://www.ebi.ac.uk/europepmc/webservices/rest/PMC13763592/fullTextXML)；模型：qoder-cn/dfmodel。

### [On-Chip Biomimetic Intelligence: Integrating Adaptive Molecular Sensing With Longitudinal Proteomic Profiling for Advanced Disease Diagnostics.](https://pubmed.ncbi.nlm.nih.gov/42989462/)

- 标识：`p-83c5441618463b0174e3`；发表：2026；发现：2026-11-08
- 主题：Computational Biology and Cellular Dynamics、Treatment Planning and Clinical Decision Support
- 状态：相关综述／资源

该观点文章提出芯片级仿生智能框架，将仿生分子识别、事件驱动信号处理、自适应本地计算与纵向蛋白质组解读结合，并设想利用患者数字孪生及药代/药效模型更新支持疾病诊断与闭环决策；完整系统尚未实现或临床验证。

限制：仅提供摘要，属观点或综述性文本；所提供摘要未报告已实现系统、代码、数据集或实验评估，并明言完整架构尚未作为单一临床验证系统展示，无法核验全文方法与性能。

判断：主题涉及分子传感、纵向蛋白质组状态估计及药代/药效模型更新，与生物医学动力学和临床决策支持相关；但所提供摘要仅为架构设想，无已实现的学习或混合转移动力学、运行式预测或实验评估，且明言完整架构尚未临床验证，故列为相关而非建议纳入。

证据层级：abstract；[来源](https://pubmed.ncbi.nlm.nih.gov/42989462/)；模型：qoder-cn/dfmodel。

Full-text access failed (TimeoutError); abstract retained.

### [Recurrent latent dynamics in spinal circuits enable a digital twin of autonomic state transitions.](https://pubmed.ncbi.nlm.nih.gov/42990874/)

- 标识：`p-85001ac2d610dca3da47`；发表：2026-10-26；发现：2026-11-22
- 主题：Computational Biology and Cellular Dynamics
- 状态：待核验

该研究提出基于流形的模型，从脊髓中间外侧核（IML）神经活动重建内部状态动力学：将低维环状流形作为动态储池嵌入循环神经网络，在无读出层情况下重建试次间变异与血压非线性动力学，指向自主神经生理的数字孪生与闭环脊髓神经调控。

限制：仅有摘要。所提供摘要未报告样本量、评价指标、基线比较与代码数据可用性；无法核验完整实验、泛化性及闭环控制效果，故不足以支持纳入。

判断：摘要显示医疗相关任务（血压/自主神经状态）、隐状态、循环网络动态转移与轨迹重建等要素，但证据级别仅为摘要。纳入需全文证据核验方法、评估与代码，故暂缓而非排除。

证据层级：abstract；[来源](https://pubmed.ncbi.nlm.nih.gov/42990874/)；模型：qoder-cn/dfmodel。

### [Causal regulators of human T-cell and macrophage activation from perturbation screens, and a replicated coupling of T-cell exhaustion markers with macrophage M1 activation in patients under checkpoint blockade](https://europepmc.org/article/PPR/PPR1372075)

- 标识：`p-882c314e34b8a30dd3f0`；发表：2026-11-19；发现：2026-11-22
- 主题：Computational Biology and Cellular Dynamics
- 状态：相关综述／资源

ImmunoTwin利用原代人类T细胞与巨噬细胞的CRISPR扰动筛选构建调控图谱，并在检查点阻断患者中复现T细胞耗竭标志与巨噬细胞M1激活的关联；但跨区室预测未改善，患者级数字孪生预设标准未达成。

限制：仅提供摘要，无法核验全文方法、代码与实验细节；所提供摘要未报告学习或混合状态转移、候选干预改变传播状态及操作式推演的证据。

判断：具备医学任务、细胞状态与实现评估，并报告扰动图谱和患者关联复现；但所提供摘要未显示学习或混合转移，也未显示候选干预改变传播状态的操作式推演，故列为相关而非纳入。

证据层级：abstract；[来源](https://europepmc.org/article/PPR/PPR1372075)；模型：qoder-cn/dfmodel。

### [Nonlinear stability phenotypes and collapse dynamics of multi-organ radiomics in total-body PET imaging: toward digital twin-oriented robustness assessment.](https://europepmc.org/article/MED/42899676)

- 标识：`p-8a815572639b6c939714`；发表：2026-10-30；发现：2026-11-04
- 主题：Medical Imaging and Radiology
- 状态：相关综述／资源

该研究基于550例全身PET扫描，模拟剂量降低并提取多器官放射组学特征，用组内相关系数与非线性模型刻画稳定性表型、塌缩模式及器官阈值，面向数字孪生稳健性评估。

限制：仅摘要；所提供摘要未报告代码或完整实验细节，无法核验滚动预测与动作干预；其轨迹为剂量-反应稳定性曲线，并非操作层面的状态转移。

判断：该摘要针对全身PET多器官放射组学，在模拟剂量降低下拟合非线性稳定性轨迹并做定量评估，属医学影像分析；但所提供摘要未展示可操作的状态转移、动作条件或滚动预测，故列为相关而非纳入。

证据层级：abstract；[来源](https://europepmc.org/article/MED/42899676)；模型：qoder-cn/dfmodel。

### [Validating complete-airway computational fluid dynamics (CA-CFD) predictions of regional aerosol deposition in human subjects: comparisons with in vivo data of pharmaceutical aerosol delivery during HFNC therapy.](https://pubmed.ncbi.nlm.nih.gov/42957071/)

- 标识：`p-973dc71a0df3e21f6364`；发表：2026-10-29；发现：2026-11-04
- 主题：Treatment Planning and Clinical Decision Support
- 状态：相关综述／资源

该摘要开发并验证完整气道CFD模型，模拟HFNC期间药物气溶胶的区域沉积，并与已发表人体在体数据比较；预测肺沉积约2.9%，显示递送效率低且区域异质性高，提出作为群体级数字孪生优化气溶胶输送。

限制：仅有摘要，无法核验全文方法、代码与独立实验；所提供摘要未报告学习/混合转移动力学或行动条件多步rollout；机制性CFD不能证明候选干预会改变传播状态。

判断：医学任务与解剖状态明确，且有机制性区域沉积模拟及在体数据验证；但摘要仅显示CFD机制模型，未见学习/混合转移动力学，也未证明候选干预改变多步传播状态，故按机制性模拟器列为相关。

证据层级：abstract；[来源](https://pubmed.ncbi.nlm.nih.gov/42957071/)；模型：qoder-cn/dfmodel。

### [Multimodal Digital Twin Architecture for Patient Monitoring in Art Therapy](https://europepmc.org/article/PPR/PPR1360320)

- 标识：`p-9a83bf68b2418712a257`；发表：2026-11-06；发现：2026-11-15
- 主题：Treatment Planning and Clinical Decision Support、Longitudinal EHR and Clinical Trajectories
- 状态：待核验

该文提出面向艺术治疗患者监测的多模态数字孪生架构：融合面部表情、语音、生理信号与交互行为，经 ConvNeXt V2、Wav2Vec2.0 与时间卷积网络提取表征，用状态空间模型学习时序行为，以跨模态注意力构建情境表征，并借助神经常微分方程实时同步患者数字孪生，最后用混合专家模型预测治疗反应并给出自适应治疗建议。摘要报告情绪时序预测准确率与治疗反应预测准确率较高，且计算延迟低于传统方法。

限制：仅提供摘要：所提供摘要未报告数据集来源与规模、对照基线、统计检验、真实临床干预验证，也无法核验代码或数据是否公开。摘要亦未说明是否存在可输入的候选治疗动作、以及该动作是否会改变被传播的患者状态，因此不主张规划、控制或反事实能力。

判断：摘要中确有医疗任务、患者状态、学习型时序转移，以及已报告的量化评估结果；但按纳入要求需全文证据支撑全部判据，而当前仅有摘要，无法核验实现细节与评估设计，故提出暂缓而非纳入。摘要亦无动作条件性证据，不主张规划与控制能力。

证据层级：abstract；[来源](https://europepmc.org/article/PPR/PPR1360320)；模型：qoder-cn/dfmodel。

### [Faithful Generative Modeling for Censored Time-to-Event Data: From Distributional Fidelity to Statistical Inference](https://arxiv.org/abs/2611.25464)

- 标识：`p-9c7cf2a73960bb3864ac`；发表：2026-11-19；发现：2026-11-22
- 主题：Longitudinal EHR and Clinical Trajectories
- 状态：相关综述／资源

提出 TSGSurv 两阶段生成框架：先按事件状态采样，再联合生成协变量与观测生存时间，以避免确定性时间回归的不可约误差；建立分布收敛率及合成数据 Cox 估计/推断理论，并用方差校正和分布校准恢复有效推断，在模拟与 NHANES、SUPPORT 数据上评估。

限制：所提供全文主要评估合成生存数据的分布保真与 Cox 推断，未呈现显式状态转移、动作条件动态或随时间 rollout 的预测；因此与世界模型的动态核心仍有距离。

判断：论文属于生物医学/临床生存数据的生成建模与统计推断，且实现了模拟和真实数据评估；但其核心是静态联合分布生成与 Cox 推断，不含候选动作改变传播状态或 operational forecasting/rollout，故不宜 suggest_include，按相关文献处理。

证据层级：full_text；[来源](https://arxiv.org/html/2611.25464v1)；模型：qoder-cn/dfmodel。

### [Speech Signal Processing and Deep Neural Modeling for Pronunciation Evaluation in College English Teaching.](https://pubmed.ncbi.nlm.nih.gov/42980249/)

- 标识：`p-9ded0bb875048559b076`；发表：2026-11-03；发现：2026-11-08
- 主题：待分类
- 状态：机器建议排除，待抽查

该研究提出CP-NDTF框架，融合语音信号处理、深度神经网络与动态状态空间学习，对分段、频谱、音高、节奏、流利度等特征建模，用于大学英语发音评估；在L2-ARCTIC语料上与传统静态DNN打分基线进行对比，并做扰动鲁棒性测试。

限制：仅有摘要；未报告硬件延迟、内存、参数量等部署实测结果，也缺乏前瞻性课堂验证。更重要的是，其任务为英语发音教学评估，不属于生物医学建模，缺少医学任务与生理/临床状态变量。

判断：研究对象是英语发音评估，属于语音与教育技术，不涉及患者、解剖、细胞、分子或临床流程等生物医学系统状态；虽含“digital twin”与状态空间更新，但缺少生物医学任务、机制或学习转移动力学以及临床/生理时序推演，故不满足纳入范围。

证据层级：abstract；[来源](https://pubmed.ncbi.nlm.nih.gov/42980249/)；模型：qoder-cn/dfmodel。

### [InSilico-K: a drug-agnostic digital twin showing that molecular weight, not molecular target, governs biologic delivery and its telmisartan-mediated rescue in non-small cell lung cancer](https://europepmc.org/article/PPR/PPR1360194)

- 标识：`p-9fa0b36cfd1879b82ca5`；发表：2026-11-06；发现：2026-11-15
- 主题：Computational Biology and Cellular Dynamics、Treatment Planning and Clinical Decision Support
- 状态：相关综述／资源

提出 InSilico-K 药物无关数字孪生：仅以分子量作为药物特异输入，结合 CT 肿瘤体积、平均动脉压与血清白蛋白估算间质液压力，模拟替米沙坦减压后大分子扩散与 InSilico-pCR；17 种药物在虚拟患者上推演，大分子加速、小分子无变化。属机制性计算模拟。

限制：仅基于所提供摘要，无法核验完整方法、代码与独立验证。结果来自单一虚拟患者和确定性机制模型，InSilico-pCR 并非临床终点；所提供摘要未报告真实患者或前瞻性组织验证证据。

判断：该工作针对 NSCLC 生物制剂递送构建患者生理状态数字孪生，含机制性时序推演、候选干预对比与虚拟患者实现评估，满足医学任务与 rollout 要求；但所提供摘要显示为确定性机制模型，未见学习或混合转移，故按机制性模拟器归为 related 而非 suggest_include。

证据层级：abstract；[来源](https://europepmc.org/article/PPR/PPR1360194)；模型：qoder-cn/dfmodel。

### [A digital twin roadmap for adult spinal deformity.](https://pubmed.ncbi.nlm.nih.gov/42975781/)

- 标识：`p-c871f470abda8f63a3f7`；发表：2026-11-03；发现：2026-11-04
- 主题：Treatment Planning and Clinical Decision Support
- 状态：相关综述／资源

该叙述性综述将五组件医疗数字孪生框架映射到成人脊柱畸形手术，提出以患者特异计算模型比较手术路径、辅助术前规划，并给出分阶段验证与部署路线图。

限制：仅提供摘要；其为叙述性综述与路线图，未报告已实现的数字孪生系统、代码或临床验证，评估与部署均为提议，全文方法细节无法核验。

判断：摘要明确为叙述性综述，仅提出成人脊柱畸形数字孪生框架、用例与路线图；术前规划任务与患者特异模拟相关，但未报告已实现的孪生系统或评估，故不满足建议纳入条件，按综述归为相关文献。

证据层级：abstract；[来源](https://pubmed.ncbi.nlm.nih.gov/42975781/)；模型：qoder-cn/dfmodel。

### [Fidelity Regret: Measuring Simulator Misspecification in Verifiable Design](https://arxiv.org/abs/2611.22263)

- 标识：`p-ca54c1ae23f79ed2d161`；发表：2026-11-17；发现：2026-11-22
- 主题：Computational Biology and Cellular Dynamics
- 状态：相关综述／资源

论文提出“保真度遗憾”，衡量廉价仿真器在可验证遗传电路设计中选出的设计相对高保真参考的遗憾；在5个Cello文库、72个单元上精确枚举，并分析优化压力与预算受限的缓解策略。

限制：所提供文本聚焦遗传电路设计，未显示医学任务或操作式时序rollout；参考分数由逐门湿实验测量组合而成，非全电路湿实验验证，且枚举主要覆盖组合子空间。

判断：该文属计算生物学/细胞动力学的仿真器保真度评估，但不是医学任务，也没有展示候选动作改变传播状态的操作式预测/rollout；其动力学为机制/拟合Hill仿真，未见学习或混合世界模型，故判为related。

证据层级：full_text；[来源](https://arxiv.org/html/2611.22263v1)；模型：qoder-cn/dfmodel。

### [Large language models as oncology world models](https://arxiv.org/abs/2611.18994)

- 标识：`p-d27708aa7de7ee53703f`；发表：2026-11-13；发现：2026-11-22
- 主题：Longitudinal EHR and Clinical Trajectories
- 状态：待核验

该工作系统考察大语言模型作为肿瘤学世界模型：仅指定肿瘤类型即可生成高度相似患者，并在12个临床情境中检验其是否遵循生物标志物与治疗逻辑；进一步延续真实患者轨迹预测12个月生存率，并提出可应用于真实患者的临床状态空间动态表征框架。

限制：当前仅有摘要，所提供摘要未报告方法细节、代码链接与完整实验设置；无法核验状态转移是否学习得到或动作条件化，生存预测属一致性检验而非临床效益证据，故证据不足，暂缓纳入。

判断：摘要显示患者级临床状态、真实轨迹延续的12个月生存预测并与72.2%观察值对比，涉及动态表征框架，具备预测与评估要素；但纳入需全文证据支撑全部标准，目前仅有摘要，方法、转移机制与实验实现无法核验，故暂缓而非排除。

证据层级：abstract；[来源](https://arxiv.org/abs/2611.18994)；模型：qoder-cn/dfmodel。

Full-text access failed (HTTPError); abstract retained.

### [Digital Twin-Guided Personalized Nutrition for Prediabetes in Primary Care: A Simulation-Based Technical Feasibility Study and Pragmatic Trial Protocol.](https://europepmc.org/article/MED/43064522)

- 标识：`p-d9b58008fd10fdb6bccb`；发表：2026-11-20；发现：2026-11-22
- 主题：Treatment Planning and Clinical Decision Support、Longitudinal EHR and Clinical Trajectories
- 状态：待核验

该摘要描述一个由临床医生监管的数字孪生框架：整合CGM、心率变异性、活动、睡眠与饮食数据，建立个体化状态空间模型，并用UKF/RTS做状态估计；在7个42天合成仿真场景中报告了决策可用率、硬约束拦截与状态估计误差，并给出未来实用性随机试验方案。

限制：仅提供摘要，未见完整全文；摘要层面未报告真实受试者结果、状态转移方程与参数学习细节。作者明确表示合成仿真不确立生理效度、临床有效性与安全性，未来试验尚未启动、未注册、未获伦理批准。

判断：仅凭所提供摘要无法核验完整方法、代码与实验细节，而纳入需全文级证据覆盖全部判据，故暂缓而非排除。摘要中确已可见医学任务、患者状态、时间动态与定量评估线索，待获取全文后可重新评估；此为提案，非人工批准。

证据层级：abstract；[来源](https://europepmc.org/article/MED/43064522)；模型：qoder-cn/dfmodel。

### [Review on modelling of thermoset and thermoplastic composites: constitutive equations, processing modelling and multiphysics modelling.](https://europepmc.org/article/MED/42996442)

- 标识：`p-dd3a9770c2f07399eebb`；发表：2026-11-05；发现：2026-11-15
- 主题：待分类
- 状态：机器建议排除，待抽查

该文综述热固性与热塑性纤维增强复合材料制造建模，涵盖热-化学本构、树脂流动、固化/结晶动力学、残余应力与多尺度多物理场仿真，并提及机器学习辅助过程预测。

限制：所提供全文为材料制造工程综述，未涉及生物医学任务、患者或生理状态，也未报告作者实现的生物医学预测评估；不能据此纳入生物医学世界模型。

判断：文章标题与全文聚焦复合材料本构方程、加工建模和多物理场仿真，应用场景为航空航天、汽车等制造，不是医学任务；虽涉及机理仿真与过程预测，但超出生物医学范围。

证据层级：full_text；[来源](https://www.ebi.ac.uk/europepmc/webservices/rest/PMC13740110/fullTextXML)；模型：qoder-cn/dfmodel。

### [Vision-Guided Robotic Arm with Deep Learning and Secure Digital Twin for Pre-Deployment Quadruped Robot Operation.](https://europepmc.org/article/MED/43029862)

- 标识：`p-e56aea0fa27158ae507f`；发表：2026-11-08；发现：2026-11-22
- 主题：待分类
- 状态：机器建议排除，待抽查

构建YOLO11视觉引导机械臂与DIATwin/Omniverse数字孪生框架，利用RGB-D定位目标，在仿真中预验证四足机器人维护轨迹，并评估TLS-MQTT通信。

限制：所提供全文聚焦工业四足机器人维护，未报告医学任务或临床验证；厘米级定位误差限制精细操作，螺钉拆卸仅在仿真中评估。

判断：该文为工业维护机器人系统，虽包含数字孪生轨迹推演与实验评估，但缺少医学任务，不属于生物医学世界模型文献。

证据层级：full_text；[来源](https://www.ebi.ac.uk/europepmc/webservices/rest/PMC13766417/fullTextXML)；模型：qoder-cn/dfmodel。

### [Optimizing AIS surgery with a digital twin framework integrating AI and personalized biomechanical modeling.](https://europepmc.org/article/MED/43004052)

- 标识：`p-e790c8b1f468bd8d42b8`；发表：2026-11-09；发现：2026-11-15
- 主题：Treatment Planning and Clinical Decision Support、Surgical Simulation and Embodied Healthcare
- 状态：待核验

该研究针对青少年特发性脊柱侧凸后路融合手术，基于MIMO试验数据构建患者特异性数字孪生，在多体动力学环境中变动AI预测的器械参数，每例生成972种构建并做多目标优化，与外科医生模拟方案比较。

限制：仅有摘要级证据：所提供摘要未报告代码、模型实现细节与前瞻性临床验证；作者亦指出模拟校正差异不构成临床优效证据。无法核验全文方法与实验设置。

判断：摘要显示存在医学任务、患者特异性解剖状态、AI与物理仿真结合的器械条件动力学及大规模模拟与MANOVA评估，方向契合；但纳入需全文证据，目前仅有摘要，无法核验完整方法与实施细节，故暂缓而非排除。

证据层级：abstract；[来源](https://europepmc.org/article/MED/43004052)；模型：qoder-cn/dfmodel。

### [Reimagining antimicrobial resistance: AI-driven predictive epidemiology and the C-AMRE framework for next-generation antibiotic discovery.](https://pubmed.ncbi.nlm.nih.gov/42562952/)

- 标识：`p-f07bebc7334c95ac54d8`；发表：2026-08-06；发现：2026-11-04
- 主题：Computational Biology and Cellular Dynamics、Treatment Planning and Clinical Decision Support
- 状态：相关综述／资源

该综述提出抗微生物药物耐药性研究的范式转变：融合演化智能、人工智能、基因组监测、分子模拟与数字孪生，构建C-AMRE多层计算生态系统，主张由表型检测与回顾性监测转向对耐药演化轨迹的前瞻预测与适应性干预，并讨论数据整合、可解释性、验证与伦理治理等落地障碍。

限制：所提供证据仅为综述摘要，未报告具体模型结构、训练数据、量化实验结果或代码链接；数字孪生实时预测多为愿景性论述，方法细节与评估结果均无法核验，也无法据此判断全文是否实现相关系统。

判断：该文属综述，且仅提供摘要：文中提及耐药演化预测、药代动力学/药效学与患者特异数字孪生等医学动态建模设想，但未见具体系统实现、状态转移学习证据及可核验的预测推演评估；按规则综述应归为相关文献，不能据此断言全文缺少方法或代码。

证据层级：abstract；[来源](https://pubmed.ncbi.nlm.nih.gov/42562952/)；模型：qoder-cn/dfmodel。

### [MitoWorld: A Stochastic World Model of the Single-Cell Cycle under Genetic Perturbation](https://arxiv.org/abs/2611.23953)

- 标识：`p-f3b9e82011b9032e6275`；发表：2026-11-18；发现：2026-11-22
- 主题：Computational Biology and Cellular Dynamics
- 状态：建议纳入，待审核

MitoWorld 将基因敲降下的单细胞周期建模为随机世界模型：在高斯参考潜空间中以基因条件 Ornstein–Uhlenbeck 转移生成未来状态，用状态、年龄和基因条件的风险模型决定分裂时间，并由扩散渲染器生成显微图像；在 MitoCheck 上评估个体轨迹与分裂时序。

限制：所提供全文仅在 MitoCheck/HeLa 的 17 个敲降与对照子集上评估，未报告外部数据集或临床验证；作者指出对少见单细胞生长轨迹和未见过基因条件的泛化仍有限。

判断：该文提出面向基因扰动下单细胞周期的随机世界模型，包含细胞状态、学习到的随机转移、分裂事件终止和扩散渲染，并执行多步 rollout；在 325 条留出 MitoCheck 轨迹上报告 FID、JEDi、区间覆盖与分裂时间 KS 等实现评估，满足医学任务、状态、动力学、rollout 与评估五项标准，因此建议纳入。

证据层级：full_text；[来源](https://arxiv.org/html/2611.23953v1)；模型：qoder-cn/dfmodel。

### [Population-level emulation enables fast Bayesian calibration of cardiac digital twins](https://europepmc.org/article/PPR/PPR1364816)

- 标识：`p-f7801c3524202da82a34`；发表：2026-11-11；发现：2026-11-15
- 主题：Treatment Planning and Clinical Decision Support
- 状态：相关综述／资源

提出跨患者人群训练的高斯过程仿真器，以患者临床特征的12维潜编码为输入，使新患者无需重新仿真即可在分钟级完成心脏数字双模型的贝叶斯校准；在26例左束支传导阻滞患者中与全仿真器比较误差与预测区间。

限制：仅提供摘要，无法核验完整方法、代码或外部验证；所提供摘要未报告随时间推进的操作性预测或rollout，评估集中于校准精度、速度与不确定性覆盖。

判断：该工作构建患者特异心脏数字双模型，用学习型仿真器替代机制仿真器进行不确定性校准，属机制仿真与代理建模的相关方向；但摘要聚焦参数校准而非状态时序前瞻预测，缺少动作条件与rollout证据，故列为相关而非纳入。

证据层级：abstract；[来源](https://europepmc.org/article/PPR/PPR1364816)；模型：qoder-cn/dfmodel。

Full-text access failed (ValueError); abstract retained.

### [Tumor digital twins uncover therapeutic strategies in triple-negative breast cancer.](https://europepmc.org/article/MED/42933397)

- 标识：`p-f876fb8d6d6b703c1671`；发表：2026-10-28；发现：2026-11-04
- 主题：Computational Biology and Cellular Dynamics、Treatment Planning and Clinical Decision Support
- 状态：相关综述／资源

该研究构建TNBC肿瘤数字孪生：以先验知识建立基因与蛋白为节点、相互作用为边的机制性定性网络，用患者分子数据参数化，识别耐药机制并提出个体化治疗建议，并借助PARTNER随机对照试验临床数据检验治疗反应预测与生物标志物。

限制：仅有摘要：模型为定性机制网络，所提供摘要未报告学习型或混合型状态转移、逐步推演过程及候选干预改变状态的证据，也未报告代码与完整方法细节，需全文核验。

判断：摘要显示该工作为用患者分子数据参数化的机制性定性网络数字孪生，具备医学任务与临床数据验证，但状态转移为纯机制型而非学习或混合型，且缺操作化推演与反事实干预证据，故归为机制型模拟相关工作。

证据层级：abstract；[来源](https://europepmc.org/article/MED/42933397)；模型：qoder-cn/dfmodel。

### [Detecting Interventional Spatiotemporal Causality in Dynamical Systems.](https://europepmc.org/article/MED/43052024)

- 标识：`p-f92ec3adbfdc2c12e3b0`；发表：2026-11-18；发现：2026-11-22
- 主题：Longitudinal EHR and Clinical Trajectories
- 状态：相关综述／资源

ISTC 通过延迟嵌入重构高维时空状态，以储备池计算构建数字孪生，并对“延迟-节点”输入施加掩蔽干预，用干预响应（DDI/DCI）识别含时滞的有向因果网络；在时滞洛伦兹系统、交通传感器、风洞以及香港空气污染与心血管住院数据上进行了验证。

限制：全文可得；但健康相关部分仅为香港污染物与心血管住院数据的因果拓扑示例，未报告临床结局预测或治疗决策评估；干预是模型内部的输入掩蔽，主要评价依赖合成基准与风洞真值。

判断：这是面向一般动力系统的因果发现框架，具备学习型数字孪生与干预式滚动推演，但医学应用仅为四个案例之一，且未针对医学任务开展预测或决策层面的实现评估，因此列为相关方法而非纳入。

证据层级：full_text；[来源](https://www.ebi.ac.uk/europepmc/webservices/rest/PMC13781652/fullTextXML)；模型：qoder-cn/dfmodel。

### [When to Trust Simulated Patient Responses:Support-Gated World Models for Vasopressor Decision Support](https://arxiv.org/abs/2611.18458)

- 标识：`p-ff17819941f66467ee3a`；发表：2026-11-13；发现：2026-11-22
- 主题：Longitudinal EHR and Clinical Trajectories、Treatment Planning and Clinical Decision Support
- 状态：建议纳入，待审核

SG-WM在eICU-CRD上以GRU集成动力学模型按去甲肾上腺素剂量类别预测MAP与心率短期响应，并用观测支持度和集成分歧门控LLM代理的候选模拟，输出预测或弃权；在留出医院比较覆盖率、预测误差和记录动作一致率。

限制：全文为回顾性eICU分析，作者明确不识别个体化治疗效应、不证明死亡率或临床获益；结果为聚合点估计，未报告逐种子或医院层面不确定性；所提供全文未报告代码链接，代码可用性无法核验。

判断：全文给出ICU血管升压药决策支持任务、患者生理状态、学习型动作条件短期动力学及eICU多医院留出评估，满足纳入要素；但作者限定为回顾性预测与界面行为，不主张因果或临床获益。

证据层级：full_text；[来源](https://arxiv.org/html/2611.18458v1)；模型：qoder-cn/dfmodel。

### [Mechanomedicine for Lung Transplantation: From Multiscale Forces to AI-Assisted Translation.](https://europepmc.org/article/MED/43052020)

- 标识：`p-0a3113c12e201ff94ba7`；发表：2026-11-18；发现：2026-11-22
- 主题：Computational Biology and Cellular Dynamics、Treatment Planning and Clinical Decision Support
- 状态：相关综述／资源

该文提出肺移植机械医学框架，连接器官尺度载荷、细胞机械转导与临床决策，并讨论计算模型和AI整合灌注波形、影像应变及分子标志物以支持移植物风险评估，最后给出数字孪生转化路线图。

限制：仅有摘要；所提供摘要未报告具体模型架构、学习式状态转移、操作级预测或已实施评估，也未给出代码或临床验证结果，无法核验全文方法与实验。

判断：属肺移植机械医学综述，讨论计算模型和AI辅助风险评估及数字孪生，但未展示带学习或混合转移的世界模型、操作级预测或已实现评估；按综述归为related，摘要证据不足以建议纳入。

证据层级：abstract；[来源](https://europepmc.org/article/MED/43052020)；模型：qoder-cn/dfmodel。

Full-text access failed (HTTPError); abstract retained.

### [AI-Enabled Patient Profiling for Personalized Nursing Care and Health Support: Scoping Review.](https://europepmc.org/article/MED/42955065)

- 标识：`p-0cddb9f876c8091ae26a`；发表：2026-10-29；发现：2026-11-04
- 主题：Longitudinal EHR and Clinical Trajectories、Treatment Planning and Clinical Decision Support
- 状态：相关综述／资源

该范围综述汇总61项研究，梳理AI患者画像（患者画像、数字表型、数字孪生、LLM个性化）在护理与健康支持中的应用，指出多数研究仅评估算法性能、可行性或系统开发，尚缺画像有效性、可操作性与实施结局证据。

限制：仅提供摘要，无法核验全文方法、代码或实验细节；所提供摘要未报告学习/混合状态转移、操作性预测/rollout及本文实施的评估。

判断：属摘要级范围综述，主题为护理患者画像与决策支持，符合related；缺乏可核验的动力学转移和前瞻rollout，且综述不能suggest_include。

证据层级：abstract；[来源](https://europepmc.org/article/MED/42955065)；模型：qoder-cn/dfmodel。

### [Digital twin control framework uncovers individualized cross-scale links between functional connectivity deviations, communication impairment, and molecular mechanisms in autism.](https://pubmed.ncbi.nlm.nih.gov/42918437/)

- 标识：`p-28fd16540d52d28aa2c6`；发表：2026-10-23；发现：2026-11-15
- 主题：Medical Imaging and Radiology、Computational Biology and Cellular Dynamics
- 状态：机器建议排除，待抽查

该研究提出基于深度对比学习的数字孪生对照分析框架，将每位ASD患者与匹配的数字孪生对照比较，量化个体功能连接偏差，并关联ADOS沟通评分、转录组、神经递质及线粒体图谱。

限制：仅有摘要；所提供摘要未报告可学习的跨时间状态转移或动作条件推演，也无法核验代码与完整实验；数字孪生对照主要用于静态偏差估计。

判断：该框架以深度对比学习构建匹配对照并提取静态功能连接偏差，再与临床及分子数据关联；摘要未显示状态转移、动作条件变化或操作性预测与rollout，因此不符合世界模型纳入标准。

证据层级：abstract；[来源](https://pubmed.ncbi.nlm.nih.gov/42918437/)；模型：qoder-cn/dfmodel。

### [Artificial intelligence in pediatric nephrology: current applications and emerging frameworks for evidence generation.](https://pubmed.ncbi.nlm.nih.gov/41739204/)

- 标识：`p-304203b461b8ba725929`；发表：2026-02-25；发现：2026-11-04
- 主题：Longitudinal EHR and Clinical Trajectories、Treatment Planning and Clinical Decision Support、Medical Imaging and Radiology
- 状态：相关综述／资源

该叙述性综述概述AI在儿科肾脏病中的应用，包括诊断支持、预后建模、影像分析与治疗个体化，并讨论数字孪生和虚拟试验作为证据生成框架，同时强调伦理、监管与公平问题。

限制：仅提供摘要；无法核验具体模型架构、状态转移、代码或实验。摘要未报告已实现的预测或rollout评估，数字孪生仅作为未来方向提及。

判断：该文为叙述性综述，综述AI在儿科肾脏病的应用及数字孪生与虚拟试验前景，但未提出具体世界模型、可核验的动力学实现或实验评估，故列为相关综述而非纳入。

证据层级：abstract；[来源](https://pubmed.ncbi.nlm.nih.gov/41739204/)；模型：qoder-cn/dfmodel。

### [Navigating the Drought Tolerance-Yield Trade-Off in Triticeae Cereals: From Molecular Networks to Climate-Resilient Breeding.](https://europepmc.org/article/MED/43053558)

- 标识：`p-31190555d3df63efee2e`；发表：2026-11-18；发现：2026-11-22
- 主题：待分类
- 状态：机器建议排除，待抽查

该文为小麦/大麦等麦类作物耐旱与产量权衡的综述，梳理转录级联、ABA激素信号、翻译后修饰、GWAS与多组学、单细胞转录组等进展，并展望快速育种、CRISPR、AI表型组与数字孪生建模等策略。

限制：仅有摘要，未见系统状态定义、可学习转移模型或任务级推演与评测；研究对象为植物育种与农业性状，不属于生物医学范畴；数字孪生仅为未来展望。

判断：主题为作物耐旱育种的分子机制与育种策略综述，既非生物医学任务（人体/临床前生理、细胞、分子或药代），也未提供世界模型的显式状态、学习或混合转移、操作性推演与实现级评测，且摘要级综述本身不满足纳入条件。

证据层级：abstract；[来源](https://europepmc.org/article/MED/43053558)；模型：qoder-cn/dfmodel。

### [Gadoxetic acid in China: a narrative review of the 15-year journey and the road ahead.](https://pubmed.ncbi.nlm.nih.gov/42999357/)

- 标识：`p-32d1e18477f8c056e36a`；发表：2026-09-30；发现：2026-11-15
- 主题：Medical Imaging and Radiology、Treatment Planning and Clinical Decision Support
- 状态：相关综述／资源

该文回顾中国15年来钆塞酸二钠肝细胞特异性肝胆MRI的临床演进，涵盖小肝癌检测、肝功能储备评估、影像组学/深度学习及“数字孪生”前景，强调数据驱动模型仍需前瞻性验证。

限制：仅有摘要；所提供摘要未报告具体学习模型、代码或实现性实验，也未报告学习型状态转移、操作级预测rollout或前瞻性临床验证，数字孪生属未来展望。

判断：这是一篇影像学叙述性综述，涉及肝胆MRI、radiomics/deep learning与数字孪生愿景，但所提供摘要未报告学习/混合动力学、操作级预测rollout或实现性评估；综述不能建议纳入，故列为相关。

证据层级：abstract；[来源](https://pubmed.ncbi.nlm.nih.gov/42999357/)；模型：qoder-cn/dfmodel。

### [Multilevel Integration of Artificial Intelligence and Wearable Biosensors for Precision Health and Clinical Translation.](https://pubmed.ncbi.nlm.nih.gov/43008140/)

- 标识：`p-3457f06babb4cc92d83e`；发表：2026-11-10；发现：2026-11-15
- 主题：Treatment Planning and Clinical Decision Support
- 状态：相关综述／资源

该综述提出AI与可穿戴生物传感器的三级集成框架：从信号解释、传感协同优化到系统级健康判断，并讨论多模态融合、闭环决策流程、数字孪生及临床转化挑战。

限制：所提供仅为摘要，未报告具体系统状态、学习或混合转移动态、操作级预测展开或已实现的评估；无法核验代码链接或临床获益。

判断：摘要属综述，聚焦可穿戴生物传感器与AI集成及健康预测管理，但未提供具体状态转移动态、操作级预测展开或实现评估，故列为相关综述而非建议纳入。

证据层级：abstract；[来源](https://pubmed.ncbi.nlm.nih.gov/43008140/)；模型：qoder-cn/dfmodel。

### [Digital Twin-Based Risk Stratification Integrating Aortic Shape and Wall Mechanics in Acute Uncomplicated Type B Aortic Dissection](https://europepmc.org/article/PPR/PPR1361020)

- 标识：`p-399b5ad67356713928bf`；发表：2026-11-06；发现：2026-11-15
- 主题：Medical Imaging and Radiology、Treatment Planning and Clinical Decision Support
- 状态：相关综述／资源

研究为50例急性非复杂型B型主动脉夹层患者构建个体化数字孪生：结合三维主动脉形态（统计形状建模）与降阶流固耦合计算的管壁应力，建立预测无主动脉事件生存的风险分层评分，并采用留一法交叉验证。多维模型C指数0.792，风险分层能力优于单纯直径阈值。

限制：仅有摘要：无法核验全文方法细节、代码与外部验证情况；摘要未报告候选干预下状态如何演化，也未报告随时间推演的运行性预测；样本50例、单中心回顾性，作者亦称需独立验证。

判断：摘要显示，这是基于CTA的力学数字孪生与风险分层评分：具备明确医学任务、解剖状态和机制性（流固耦合）应力计算，并实施了留一交叉验证。但未见学习式或混合式状态转移，也没有以患者状态为起点、随时间或干预条件推演的运行性预测，属于机制性模拟加静态风险分类，因此按规则归为相关，而非suggest_include。

证据层级：abstract；[来源](https://europepmc.org/article/PPR/PPR1361020)；模型：qoder-cn/dfmodel。

### [A Real-World Model of Multidisciplinary Survivorship Care: Clinical Pathways, Patient-Reported Outcomes, and Implementation Challenges](https://europepmc.org/article/PPR/PPR1361790)

- 标识：`p-48abd530c490e3cef5be`；发表：2026-11-09；发现：2026-11-15
- 主题：Treatment Planning and Clinical Decision Support
- 状态：机器建议排除，待抽查

回顾性描述某三级癌症中心的多学科生存者照护模式：将临床服务结构化映射与常规采集的患者报告结局相结合，用NCCN问题清单和困扰温度计量化困扰负担，并以EBICglasso网络分析考察困扰条目之间的条件关联。

限制：仅有摘要。所提供摘要未报告任何状态表征、转移模型、动作条件推演或预测性滚动评估，也无法核验代码、纵向随访或外部验证。

判断：该工作是对照护组织形式的实践性描述，并开展横断面患者报告结局网络分析；全文未呈现可学习或混合的状态转移机制，也没有动作输入下的状态演化与操作化预测评估，属于静态表征与关联分析，不符合世界模型的纳入要求，也并非机制性仿真器。

证据层级：abstract；[来源](https://europepmc.org/article/PPR/PPR1361790)；模型：qoder-cn/dfmodel。

### [A Unified World Model in Human Posterior Parietal Cortex.](https://pubmed.ncbi.nlm.nih.gov/42990437/)

- 标识：`p-5f9efa0cf0140e937e0a`；发表：2026-11-01；发现：2026-11-15
- 主题：Computational Biology and Cellular Dynamics
- 状态：相关综述／资源

该研究在两名四肢瘫痪参与者的上顶叶小叶记录神经群体活动，发现同一群体参与直觉物理判断、提前预测碰撞并编码手部动作意图，提出SPL是物理世界模型的神经基础。

限制：所提供摘要未报告可实现的转化模型、代码或临床任务；无法核验全文方法与实验细节。

判断：摘要研究人类后顶叶皮层神经群体对物理事件和动作意图的编码，属于神经科学世界模型证据；未提供医学任务、学习到的状态转移模型或可操作预测rollout，故不满足suggest_include。

证据层级：abstract；[来源](https://pubmed.ncbi.nlm.nih.gov/42990437/)；模型：qoder-cn/dfmodel。

### [\[Digital operating room-From dream to workflow\].](https://pubmed.ncbi.nlm.nih.gov/42862343/)

- 标识：`p-61cb80c63a8819dcd31c`；发表：2026-10-12；发现：2026-11-04
- 主题：Treatment Planning and Clinical Decision Support、Surgical Simulation and Embodied Healthcare
- 状态：相关综述／资源

该文为数字手术室与围手术期人工智能综述，概述术前规划工具、术中导航与机器人、环境人工智能及数字孪生连接围手术期数据并优化流程，同时讨论文档负担、互操作、成本与伦理责任。

限制：仅提供摘要；所提供摘要未报告具体模型、状态转移、操作预测或实现评估，无法核验代码与临床效果。

判断：属围手术期人工智能与数字手术室综述，涉及规划及数字孪生概念，但缺乏可核验的动力学建模、操作预测和实现评估，故为相关综述。

证据层级：abstract；[来源](https://pubmed.ncbi.nlm.nih.gov/42862343/)；模型：qoder-cn/dfmodel。

### [Fixing the Twin, Not the Detector: Sim-to-Real Roadside LiDAR Detection from Digital-Twin Data](https://arxiv.org/abs/2611.26035)

- 标识：`p-694eeb67c67a16d909d6`；发表：2026-11-19；发现：2026-11-22
- 主题：待分类
- 状态：机器建议排除，待抽查

该文报告了在UrbanTwin Sim2Real LiDAR挑战赛中获第一名的流程：将数字孪生与真实路侧传感器在坐标、点密度和框标注约定上对齐，并补充孪生缺失的行人与骑行者，使仅用合成数据训练的CenterPoint检测器迁移到真实路侧数据。

限制：仅有摘要，方法细节、代码与完整实验无法核验；研究对象是路侧LiDAR检测与数字孪生到现实的域适配，不涉及医学任务、患者或生理状态，也不涉及生物医学动力学。

判断：摘要全部围绕路侧LiDAR目标检测的合成到真实迁移与无标签后处理，缺少医疗任务、patient/physiology state、可学习的 biomedical 状态转移与操作式预测评估，不属于生物医学世界模型文献范围。

证据层级：abstract；[来源](https://arxiv.org/abs/2611.26035)；模型：qoder-cn/dfmodel。

Full-text access failed (HTTPError); abstract retained.

### [Advancing process control toward intelligent continuous biopharmaceutical manufacturing: Challenges, strategies, and future directions.](https://pubmed.ncbi.nlm.nih.gov/42472568/)

- 标识：`p-6d54950836d3f8e83dc0`；发表：2026-07-19；发现：2026-11-04
- 主题：Computational Biology and Cellular Dynamics
- 状态：相关综述／资源

该文为综述，梳理连续生物制药生产（上游细胞培养至下游纯化）的控制策略，涵盖QbD与ICH Q13监管背景、模型预测控制与强化学习等模型及数据驱动方法，并讨论PAT、模型控制与数字孪生整合为感知—建模—控制架构，以支撑预测性、自适应、风险感知的持续受控状态。

限制：仅依据所提供摘要；摘要为综述性概述，未报告具体系统状态定义、学习型或混合状态转移模型、运行式预测实验及代码链接，相关方法学细节无法核验，需获取全文后再评估。

判断：主题属生物制药连续生产过程控制，与世界模型的状态转移与预测控制相关；但所提供摘要为综述性叙述，未呈现具体医学任务、状态表征、学习型动力学与已实现的评估，且摘要层面的综述不能suggest_include，故定为related。

证据层级：abstract；[来源](https://pubmed.ncbi.nlm.nih.gov/42472568/)；模型：qoder-cn/dfmodel。

### [Multimodality imaging to enhance substrate characterization for ventricular tachycardia ablation: what's new?](https://pubmed.ncbi.nlm.nih.gov/42989946/)

- 标识：`p-803c8e6f839da27d527c`；发表：2026-11-06；发现：2026-11-08
- 主题：Medical Imaging and Radiology、Treatment Planning and Clinical Decision Support
- 状态：相关综述／资源

综述多模态影像（CMR、CT、ICE、光子计数CT）在室性心动过速消融基质刻画中的最新进展，讨论影像定义瘢痕与组织学的对应关系、通道识别，以及影像整合随机试验（InEurHeart）结果，并提及数字孪生引导消融已进入首次临床使用。

限制：仅有摘要，所提供摘要未报告世界模型的状态转移、学习式或混合式动力学、动作条件化推演或量化评估；亦无法核验全文方法与代码。数字孪生仅一句提及，细节无法核验。

判断：该文为影像整合用于室速消融基质刻画的叙述性综述，涉及医学任务与影像/解剖状态，但摘要未描述动力学转移模型、动作条件化推演或模型评估，仅为临床影像流程与一项随机试验结果，不满足suggest_include；摘要型综述按规则判为related。

证据层级：abstract；[来源](https://pubmed.ncbi.nlm.nih.gov/42989946/)；模型：qoder-cn/dfmodel。

### [Digital Twins of Pregnancy from Public Single-Cell Data: An In-Silico Framework for Predicting Maternal Immune Responses to Infection and Vaccination](https://europepmc.org/article/PPR/PPR1372859)

- 标识：`p-868fd350b4b9a364b42e`；发表：2026-11-20；发现：2026-11-22
- 主题：Computational Biology and Cellular Dynamics
- 状态：待核验

该研究利用公共单细胞测序数据构建孕产妇免疫数字孪生，整合免疫细胞图谱与供体响应特征，识别妊娠相关免疫程序，并在流感感染、疫苗接种及母婴抗体转移数据中检验。摘要未展示可操作的状态转移动力学或时序推演。

限制：仅提供摘要；所提供摘要未报告学习或混合状态转移动力学及操作式预测推演的实现细节，无法核验完整世界模型能力，亦未见代码链接。

判断：摘要显示医学任务、细胞状态及交叉验证评估，但未报告学习或混合转移动力学，也未展示候选干预改变传播状态的操作式预测推演，故暂缓纳入。

证据层级：abstract；[来源](https://europepmc.org/article/PPR/PPR1372859)；模型：qoder-cn/dfmodel。

### [Towards a digital twin for precision diabetes care: a phenotypic mapping and virtual representation of a person living with type 1 diabetes in the SFDT1 study.](https://europepmc.org/article/MED/42951245)

- 标识：`p-a001c5dc2b739a2c7444`；发表：2026-10-28；发现：2026-11-04
- 主题：Longitudinal EHR and Clinical Trajectories、Treatment Planning and Clinical Decision Support
- 状态：相关综述／资源

基于SFDT1队列2187名成人1型糖尿病患者的25项社会人口学、临床、生化与连续血糖监测变量，采用树结构判别降维构建可解释的七类表型图谱，并在235人独立样本中验证结构可复现性与个体投影精度（R² 0.85-0.98），另提供多语言应用估算肾病与心血管风险，作为糖尿病数字孪生的静态表征基础。

限制：所提供摘要未报告任何状态转移模型、时间推演或前瞻性预测评估；表型映射基于基线横截面数据，数字孪生仅为愿景表述。无法核验全文是否含动态建模、代码链接或外部验证，故不作否定性断言。

判断：该研究属生物医学范畴，具备患者层面状态表征与已实现的独立样本评估，但本质为静态表型映射与个体投影，摘要中缺少学习型或混合型状态转移、操作性预测与推演过程，亦无候选干预改变传播状态的证据，故不满足建议纳入所需的动力学与推演要件，判为相关。

证据层级：abstract；[来源](https://europepmc.org/article/MED/42951245)；模型：qoder-cn/dfmodel。

### [Dual-feature selectivity enables bidirectional coding in visual cortical neurons.](https://europepmc.org/article/MED/43001849)

- 标识：`p-a16fb893717ad45296a6`；发表：2026-11-09；发现：2026-11-15
- 主题：Computational Biology and Cellular Dynamics
- 状态：相关综述／资源

利用猕猴V1/V4与小鼠视觉皮层记录训练功能性数字孪生模型，在约120万张自然图像上筛选最强与最弱激活刺激，揭示非稀疏神经元具有双特征选择性：对优选特征兴奋、对另一类特征抑制，呈双向分级编码，并用独立模型与跨动物数据加以验证。

限制：结论主要依赖模型预测而非充分在体实验验证；模型未纳入序列时间上下文，V4预测精度较低；所提供全文属视觉神经生理研究，未见医学任务、临床结局或可干预动作空间。

判断：该工作训练学习式神经响应预测模型并在大规模in silico筛选中完成定量评估，属生理机制层面的生物医学预测模型，因而与世界模型相关；但缺少明确的医学任务、由候选动作引起的状态演化（Plan/Control/Counterfactual）与操作性rollout或预后预测，故不满足suggest_include，同时也不属于应排除的静态表征或分类器。

证据层级：full_text；[来源](https://www.ebi.ac.uk/europepmc/webservices/rest/PMC13747320/fullTextXML)；模型：qoder-cn/dfmodel。

### [A proposed organization of multifaceted knowledge in data repositories: structuring record collections and evidence sets for data lakehouses and moonshots.](https://pubmed.ncbi.nlm.nih.gov/42608552/)

- 标识：`p-a4fbaeac98f7c02bd914`；发表：2026-08-17；发现：2026-11-04
- 主题：Longitudinal EHR and Clinical Trajectories
- 状态：相关综述／资源

提出PHENOM云数据湖仓框架，面向TBI等神经健康研究，将多源数据按一次性采集、纵向访视、个人EHR和集体测量四类组织，支持FAIR整合、查询及数字孪生建模；摘要未给出可学习状态转移或预测推演。

限制：仅依据摘要；未报告世界模型的状态定义、学习/混合转移、行动条件rollout或预测评估；数字孪生仅作为平台支持方向，无法核验实现与代码。

判断：该文是神经健康数据平台/数据组织Perspective，聚焦TBI多研究数据整合与查询，而非世界模型；摘要未显示状态转移、rollout或模型评估。因属生物医学数据基础设施并提及数字孪生，判为related。

证据层级：abstract；[来源](https://pubmed.ncbi.nlm.nih.gov/42608552/)；模型：qoder-cn/dfmodel。

### [biv-me: Open-source software for generating time-varying biventricular meshes from cine cardiovascular magnetic resonance imaging with multi-cohort validation.](https://pubmed.ncbi.nlm.nih.gov/42579973/)

- 标识：`p-a71c28b9c87bf3c9339f`；发表：2026-08-06；发现：2026-11-04
- 主题：Medical Imaging and Radiology
- 状态：相关综述／资源

biv-me 是开源端到端流程，可从 cine CMR DICOM 自动生成时间变化的双心室网格，并在五个公开数据集、1313 项检查上进行外部验证；摘要报告左/右心室指标一致性和扫描-重扫描可重复性较好。

限制：仅基于摘要；所提供摘要未报告学习/混合状态转移或操作级预测/rollout，无法核验全文方法与代码细节。

判断：该工作提供医学影像到时间变化解剖网格的开源重建与多队列验证，可作为数字孪生几何基础；但摘要未显示学习/混合状态转移或操作级预测/rollout，故不满足 suggest_include。

证据层级：abstract；[来源](https://pubmed.ncbi.nlm.nih.gov/42579973/)；模型：qoder-cn/dfmodel。

### [Co-transduction-aware digital twinning of dual-AAV prime editing for genetically stratified CNS therapy](https://europepmc.org/article/PPR/PPR1369492)

- 标识：`p-b8216b578a28c71addd5`；发表：2026-11-17；发现：2026-11-22
- 主题：Computational Biology and Cellular Dynamics、Treatment Planning and Clinical Decision Support
- 状态：待核验

该研究提出DUAL-AAV PRIME-DT，将双AAV共转导作为细胞级状态并沿递送、编辑与救援链传播，在1万虚拟帕金森病患者中预测覆盖，并开展压力测试、敏感性与信息价值分析。

限制：仅摘要可核验，无法确认全文方法、代码或真实患者验证；结果为合成队列，作者明确不意味着临床疗效。

判断：摘要显示细胞级共转导状态与治疗链传播，但无全文证据核验学习/混合转移、实现评估与代码；按纳入需全文证据的规则暂缓，而非排除。

证据层级：abstract；[来源](https://europepmc.org/article/PPR/PPR1369492)；模型：qoder-cn/dfmodel。

### [Physician digital health literacy and generative AI for public health communication: a five-country comparative case study with a MedVid-informed digital twin model for Shanghai.](https://europepmc.org/article/MED/42967410)

- 标识：`p-b8bf089de352430e5422`；发表：2026-10-30；发现：2026-11-04
- 主题：待分类
- 状态：机器建议排除，待抽查

该文以五国比较案例研究，比较医生数字健康素养与生成式AI用于公共健康传播的现状，并基于新加坡MedVid项目提出面向上海的可检验“可信医生数字分身”传播模型，强调准确性、肖像权与时间三类障碍及治理与同意机制。

限制：所提供摘要未报告任何状态建模、学习或混合转移函数、动作条件化推演或定量模型评估；所谓“数字分身”是政策与治理层面的传播设想，且作者说明关联非因果、信任未评分，无法核验其技术实现。

判断：属卫生传播政策与素养的比较案例研究与概念性建议，不含医学状态表示、学习/混合动力学、动作条件化推演或已实现的模型评估，故不构成生物医学世界模型；亦非综述或纯机理仿真器。

证据层级：abstract；[来源](https://europepmc.org/article/MED/42967410)；模型：qoder-cn/dfmodel。

### [Tissue-to-bytes: A digital twin for single-cell omics data integration across BRAIN Initiative Cell Atlas Network.](https://europepmc.org/article/MED/43020053)

- 标识：`p-bebc1cffbe75b672ea0e`；发表：2026-11-12；发现：2026-11-15
- 主题：Computational Biology and Cellular Dynamics
- 状态：相关综述／资源

提出NIMP，一个面向BICAN联盟的网页平台，整合供者登记、解剖标注、组织分配、测序流程、质控和数据归档，管理762名供者、8449个脑块和21781个测序文库的端到端溯源。

限制：仅有摘要；所提供摘要描述数据与元数据管理及溯源，未报告学习或混合状态转移动力学、操作级预测或模型评估；无法核验全文方法与代码。

判断：该工作是单细胞组学资源与溯源管理平台，涉及解剖标本与测序文库等生物医学对象，但未体现候选动作改变传播状态的学习或混合动力学，也未报告操作级预测评估，故仅列为相关基础设施。

证据层级：abstract；[来源](https://europepmc.org/article/MED/43020053)；模型：qoder-cn/dfmodel。

### [Digital Twins to Mimic the Control Arm of a Neonatal Randomized Controlled Trial: A "Proof-of-Principle" Feasibility and Comparability Study.](https://pubmed.ncbi.nlm.nih.gov/42988320/)

- 标识：`p-c6abfaeaf9fa76b7caf4`；发表：2026-11-05；发现：2026-11-08
- 主题：Longitudinal EHR and Clinical Trajectories
- 状态：相关综述／资源

该研究利用加拿大新生儿网络注册库，为已完成的MOBYDICK随机对照试验对照组患儿匹配一至两名数字孪生对照，并用标准化差异、逐元素平均绝对差与Gower距离评估可行性和可比性；基线特征与结局总体相近，但数字孪生组坏死性小肠结肠炎发生率更高。

限制：仅有摘要：所提供摘要未报告学习式或混合状态转移模型、动作条件推演及时间演化滚动预测，也未给出代码或可复现资源链接；无法核验全文方法与实现细节，据摘要不能判断其是否具备世界模型意义上的动力学建模。

判断：该工作以注册库患者匹配构建试验外部数字孪生对照臂，属于人群层面的对照仿真，与患者状态及临床试验设计相关；但摘要未体现学习或混合状态转移、候选动作改变传播状态及操作性预测滚动推演，不满足建议纳入所需的动力学与滚动推演条件，故提议列为相关。

证据层级：abstract；[来源](https://pubmed.ncbi.nlm.nih.gov/42988320/)；模型：qoder-cn/dfmodel。

### [A digital twin of freely moving mouse V1 learns a general visual code bridging classical physiology and active vision](https://europepmc.org/article/PPR/PPR1368645)

- 标识：`p-c7c153cce96c2fd1473f`；发表：2026-11-16；发现：2026-11-22
- 主题：Computational Biology and Cellular Dynamics
- 状态：待核验

训练多模态数字孪生，从视网膜中心视频及运动、瞳孔、眼/头运动预测自由活动小鼠V1放电，并在冻结后通过夹持变量进行受控探测，学习到跨刺激、动物和记录条件泛化的视觉表征。

限制：证据仅限摘要；所提供摘要未报告明确的运行时序rollout或动作条件状态传播，也无法核验代码与完整实验。

判断：摘要显示其具备生理状态、学习到的预测模型与独立数据评估，但未报告可核验的运行时序rollout/动作条件状态传播，且证据仅限摘要，因此暂缓。

证据层级：abstract；[来源](https://europepmc.org/article/PPR/PPR1368645)；模型：qoder-cn/dfmodel。

### [Implementation Science Driven Identification of Barriers to AI Diagnostic Decision Support: A Stakeholder-Informed Concept Mapping Study](https://arxiv.org/abs/2611.02554)

- 标识：`p-cdc8043e2de8b38f5ab3`；发表：2026-11-02；发现：2026-11-04
- 主题：Treatment Planning and Clinical Decision Support
- 状态：相关综述／资源

该研究采用结构化概念映射（CM）与知识转化框架，组织利益相关者共同生成96条关于AI诊断决策支持落地障碍的陈述，并归纳为11个集群（基础设施、伦理法律、工作流整合、对算法推理的不信任等）。文中仅将数字孪生作为前瞻性延伸背景讨论，未构建或评估任何世界模型。

限制：仅提供摘要，无模型架构、状态转移或代码信息；无预测/rollout实验或定量评估结果；数字孪生部分为展望性论述，无法核验任何实现细节。

判断：属实施科学定性研究，聚焦AI诊断工具临床采纳障碍，未提出医学世界模型；但文中讨论数字孪生作为AI驱动预测与多模态数据整合的未来延伸，与世界模型议题相关，故列为related而非纳入。

证据层级：abstract；[来源](https://arxiv.org/abs/2611.02554)；模型：qoder-cn/dfmodel。

Full-text access failed (HTTPError); abstract retained.

### [MADJEPA: Enhanced Multi-Stage Joint-Embedding Predictive Architecture for Medical Anomaly Detection](https://arxiv.org/abs/2611.25194)

- 标识：`p-d0228b7e3a911e8f1391`；发表：2026-11-18；发现：2026-11-22
- 主题：Medical Imaging and Radiology
- 状态：相关综述／资源

MADJEPA 将 I-JEPA 潜空间预测、教师蒸馏与伪异常分类结合，构建无监督医学图像异常检测器；在 BMAD 六个影像数据集上评估图像级和像素级 AUROC，并报告在三个数据集上领先。

限制：所提供全文聚焦静态图像异常检测与阈值校准，未展示时间演化、动作条件 rollout 或前瞻性临床验证；世界模型动态性证据不足。

判断：虽含潜空间掩码预测，但任务是静态医学图像异常检测与分类校准，缺少随时间演化或动作条件的状态转移及 rollout；故归为相关而非纳入。

证据层级：full_text；[来源](https://arxiv.org/html/2611.25194v1)；模型：qoder-cn/dfmodel。

### [Advances in microfluidic platforms for phenotypic microbial analysis and digital-twin-oriented modeling: A comprehensive and critical review.](https://europepmc.org/article/MED/43034037)

- 标识：`p-d1a6ed51a6239e60fea1`；发表：2026-11-14；发现：2026-11-22
- 主题：Computational Biology and Cellular Dynamics
- 状态：相关综述／资源

该综述梳理微流控芯片用于微生物生长、抑制与应激表型的高通量测量，比较其相对传统培养的速度与资源效率，并讨论显微成像、传感、AI与机制建模耦合形成数字孪生的前景。

限制：仅提供摘要，所提供摘要未报告全文方法、代码或实验细节；未展示已实现的数字孪生状态转移、预测 rollout 或评估。

判断：属摘要级综述，主题涉及微生物表型测量及数字孪生/机制建模展望；但未展示医学任务、可学习状态转移或已实现的预测评估，按综述归为 related，不能 suggest_include。

证据层级：abstract；[来源](https://europepmc.org/article/MED/43034037)；模型：qoder-cn/dfmodel。

### [Intelligent immunotherapy: AI-driven optimization of CAR-T therapy in hematologic malignancies.](https://pubmed.ncbi.nlm.nih.gov/42904142/)

- 标识：`p-d3566a29f4f70f84cac4`；发表：2026-10-12；发现：2026-11-22
- 主题：Treatment Planning and Clinical Decision Support、Longitudinal EHR and Clinical Trajectories
- 状态：相关综述／资源

该综述按证据成熟度梳理CAR-T治疗中的AI应用：基于常规临床与实验室数据的风险分层、影像和病理多模态模型，以及数字孪生等原型，并比较18种工具和实施障碍。

限制：仅提供摘要，无法核验全文方法、代码与实验细节；数字孪生和闭环自适应治疗仍属原型，摘要未报告具体学习型状态转移或操作级 rollout 评估。

判断：该文为摘要级综述，按规则综述归为 related；内容涉及CAR-T患者风险预测与临床决策，但未提供所提出系统的学习型状态转移、操作级 rollout 或已实现评估证据。决策仅为建议。

证据层级：abstract；[来源](https://pubmed.ncbi.nlm.nih.gov/42904142/)；模型：qoder-cn/dfmodel。

### [Robotic ultrasound scanning platform with autonomous control, multimodal human-machine interface and real-time image analysis.](https://pubmed.ncbi.nlm.nih.gov/42533186/)

- 标识：`p-eb5970f417f8f125cf25`；发表：2026-07-30；发现：2026-11-15
- 主题：Medical Imaging and Radiology、Surgical Simulation and Embodied Healthcare
- 状态：待核验

提出集成式机器人超声扫描平台，支持手动/自主模式；自主控制结合AI驱动的超声目标分割与几何运动算法，并配LLM语音接口、3D数字孪生和AR；在合成体模肝肿瘤定位中取得84%成功率、平均5.75秒。

限制：仅基于所提供摘要；所提供摘要未报告学习/混合状态转移动力学、预测性rollout或代码链接，仅有合成体模结果，无法核验全文方法与临床获益。

判断：摘要显示医学任务、机器人/图像状态与体模评估，但自主控制主要是AI分割加几何运动，未提供学习/混合状态转移或预测性rollout证据；证据不足，暂缓而非排除。

证据层级：abstract；[来源](https://pubmed.ncbi.nlm.nih.gov/42533186/)；模型：qoder-cn/dfmodel。

### [Artificial Intelligence in Cleft and Craniofacial Care.](https://europepmc.org/article/MED/42951803)

- 标识：`p-edc619ca8269ca7f45c1`；发表：2026-10-28；发现：2026-11-04
- 主题：Medical Imaging and Radiology、Treatment Planning and Clinical Decision Support、Surgical Simulation and Embodied Healthcare
- 状态：相关综述／资源

该综述介绍人工智能在唇裂与颅面外科中的应用，包括三维影像、机器学习、自动化工作流、手术器械自动设计、治疗规划与数字孪生概念，目标是提升评估、规划与结局评价的精准性、效率与可及性。

限制：仅依据所提供摘要；该摘要为综述性概述，未报告具体世界模型架构、状态转移、操作式预测或实现评估；无法核验全文方法与代码。

判断：该文为唇裂与颅面人工智能综述，涉及三维影像、治疗规划与数字孪生，属于相关综述；但所提供摘要未给出形式化医学状态、学习或混合转移、操作式预测展开及实现评估，因此不满足建议纳入条件。

证据层级：abstract；[来源](https://europepmc.org/article/MED/42951803)；模型：qoder-cn/dfmodel。

### [Hierarchical Spatiotemporal World Modeling with Content-Adaptive Spatial Addressing](https://arxiv.org/abs/2611.25610)

- 标识：`p-fa0cedc8ff70d486ef49`；发表：2026-11-19；发现：2026-11-22
- 主题：待分类
- 状态：机器建议排除，待抽查

HiSTFormer提出分层时空Transformer世界模型，用时间RoPE、多周期空间RoPE、内容自适应空间地址和固定容量记忆，在MemoryMaze/HM3D上实现动作条件长时程视觉预测与远超训练长度的开环rollout。

限制：全文证据显示评估仅限MemoryMaze/HM3D导航视觉预测，非医学场景；依赖真实朝向，未报告临床或生理验证。

判断：论文是面向视觉导航的通用世界模型，任务为MemoryMaze/HM3D视觉预测，未涉及医学任务、患者状态或临床/生理应用；海马/网格细胞仅为架构灵感。

证据层级：full_text；[来源](https://arxiv.org/html/2611.25610v1)；模型：qoder-cn/dfmodel。

### [Prediction of Plasma Concentration-Time Profiles in Mice from Chemical Structure Using a Kinetically Constrained Hybrid Neural ODE.](https://europepmc.org/article/MED/42969730)

- 标识：`p-079ddee0912cb0cecfb8`；发表：2026-11-01；发现：2026-11-04
- 主题：Computational Biology and Cellular Dynamics
- 状态：待核验

提出KCH-NODE混合框架，以共享可学习双室典型轨迹为锚，用Neural ODE建模化合物特异的连续时间偏差，从化学结构预测小鼠静脉与口服血浆浓度-时间曲线；在1159个化合物上做交叉验证与时间留出评估，整体优于纯数据驱动Neural ODE，但口服时间外推准确性仍有限。

限制：仅提供摘要，无法核验全文方法、代码与完整实验细节；因此不能确认是否满足纳入所需的完整动力学、轨迹推演与评估证据。所提供摘要未报告代码发布情况，无法核验数据泄漏控制与可靠性指标的实现细节。

判断：摘要显示该工作涉及药代动力学浓度-时间轨迹预测，并含混合建模与定量评估，方向相关；但证据仅为摘要，纳入要求全部标准具备全文证据，故暂缓而非排除，待获取全文再判定。

证据层级：abstract；[来源](https://europepmc.org/article/MED/42969730)；模型：qoder-cn/dfmodel。

### [A System Dynamics Model for Zero-emission Heavy Vehicle Transition in Australia](https://arxiv.org/abs/2610.41042)

- 标识：`p-235fc0824fcffae6053e`；发表：2026-10-29；发现：2026-11-04
- 主题：待分类
- 状态：机器建议排除，待抽查

该文构建澳大利亚刚性及铰接卡车车队的系统动力学模型，评估零排放重卡采用路径与政策工具效果，预测2050年车队构成。属交通政策模拟，非生物医学世界模型。

限制：仅提供摘要；所提供摘要未报告生物医学任务、患者或生理状态、临床评估，无法核验代码与临床益处。

判断：研究对象为澳大利亚卡车车队及零排放政策，属交通政策系统动力学；所提供摘要无医学任务或生物医学状态，超出生物医学世界模型综述范围。

证据层级：abstract；[来源](https://arxiv.org/abs/2610.41042)；模型：qoder-cn/dfmodel。

Full-text access failed (HTTPError); abstract retained.

### [From Static Records to Virtual Digital Patients: An Artificial Intelligence-Driven Framework for Medical Data Assetization and Governance.](https://pubmed.ncbi.nlm.nih.gov/43016988/)

- 标识：`p-2e033da668c4dde484e3`；发表：2026-11-10；发现：2026-11-15
- 主题：Longitudinal EHR and Clinical Trajectories、Treatment Planning and Clinical Decision Support
- 状态：相关综述／资源

提出“虚拟数字患者”的社会技术治理框架，整合纵向患者表征、人工智能建模与仿真、治理控制及临床外部使用四个层次，并以肿瘤试验设计场景说明受限用途的输出审查，最后给出分阶段验证议程。

限制：仅提供摘要；属概念框架与叙事综述，未报告新算法、部署系统或临床验证，也未报告实现与实证评估细节，无法核验代码或实验。

判断：摘要为概念性社会技术框架与叙事综述，提出参考架构和验证议程，但明确未报告新算法、部署系统或临床验证；按规则综述类归为相关，且摘要证据不足以建议纳入。

证据层级：abstract；[来源](https://pubmed.ncbi.nlm.nih.gov/43016988/)；模型：qoder-cn/dfmodel。

### [Machine Learning of Temperature-Dependent Chemical Kinetics Using Parallel Droplet Microreactors.](https://pubmed.ncbi.nlm.nih.gov/42635630/)

- 标识：`p-874487e10ed1c42509af`；发表：2026-08-24；发现：2026-11-15
- 主题：Computational Biology and Cellular Dynamics
- 状态：待核验

提出液滴微流控与Neural ODE结合框架，获取温度梯度下大规模时间分辨数据并学习温度依赖反应/酶动力学，实现动力学预测。

限制：仅摘要；未报告具体评估指标、误差、代码链接或明确医学/临床任务，无法核验完整实验与泛化性。

判断：摘要显示已实现数据采集与Neural ODE酶动力学预测，但医学任务不明确；仅摘要无法核验评估细节和代码，故按证据不足暂缓而非排除。

证据层级：abstract；[来源](https://pubmed.ncbi.nlm.nih.gov/42635630/)；模型：qoder-cn/dfmodel。

### [High-dimensional neural ODE model to characterize clinical pharmacokinetics of MMAE-based antibody-drug conjugates.](https://europepmc.org/article/MED/43043563)

- 标识：`p-b5e1e37f09525867a5ff`；发表：2026-11-17；发现：2026-11-22
- 主题：Computational Biology and Cellular Dynamics
- 状态：建议纳入，待审核

该研究用神经常微分方程对MMAE抗体偶联药物的临床药代动力学建模，可分别或联合刻画总抗体、偶联MMAE、游离MMAE与ADC四类分析物，并在未见剂量及多剂量方案上评估外推预测能力。

限制：数据来自已发表研究的文献数字化，剂量与来源覆盖不均；未建模个体协变量与产品间变异，黑箱模型难以提供机制解释，超出观测时间范围的外推可靠性较低。

判断：全文报告了临床药代动力学任务、多分析物系统状态、由神经常微分方程学习的连续时间转移、多剂量情景下的轨迹推演，以及预测误差与交叉验证等具体评估，满足建议纳入条件。

证据层级：full_text；[来源](https://www.ebi.ac.uk/europepmc/webservices/rest/PMC13777853/fullTextXML)；模型：qoder-cn/dfmodel。

### [PROFET predicts continuous gene expression dynamics from scRNA-seq data to elucidate heterogeneity of cancer treatment responses.](https://pubmed.ncbi.nlm.nih.gov/42664975/)

- 标识：`p-c26c0ac9f18e57fa6c4a`；发表：2026-08-28；发现：2026-11-22
- 主题：Computational Biology and Cellular Dynamics
- 状态：待核验

PROFET 将粒子梯度流与无模拟力匹配结合，从稀疏 scRNA-seq 时序重建连续非线性细胞轨迹，并在乳腺癌治疗响应数据中推断表达动态、识别耐药亚群。

限制：所提供摘要未报告代码链接、完整方法细节或独立临床验证；全文实验与候选干预条件下的推演无法核验，故不能据摘要确认全部纳入标准。

判断：摘要显示该方法用于细胞状态、时序轨迹重建与预测且有定量误差比较，但仅摘要证据，无法核验全文方法、代码和完整实验，因此暂缓而非纳入。

证据层级：abstract；[来源](https://pubmed.ncbi.nlm.nih.gov/42664975/)；模型：qoder-cn/dfmodel。

### [Entity-aware pathology workflow informatics: Structured evidence mapping and a reference architecture for governed orchestration.](https://pubmed.ncbi.nlm.nih.gov/42893223/)

- 标识：`p-1d6534420636f64b3762`；发表：2026-09-14；发现：2026-11-04
- 主题：Longitudinal EHR and Clinical Trajectories、Medical Imaging and Radiology
- 状态：相关综述／资源

对98条记录做结构化证据映射，从数据采集、控制流重构、执行自主性与验证环境四个维度考察病理工作流（病例、标本、蜡块、切片、扫描与报告）的证据，并据此提出包含语义感知、实体感知过程状态、有界编排、执行前命令治理与受治理执行的参考架构；作者明确该架构尚未部署或验证。

限制：所提供摘要未报告任何实现代码、具体模型或已执行的评估实验；架构为设计目标而非已验证系统，评估仅以建议清单形式给出；纳入筛选依赖单一评审员编码，独立核验仅覆盖50条记录。

判断：该文为结构化证据综述并附参考架构提议，涉及病理工作流的临床过程状态，但所提供摘要未体现学习或混合转移动力学，也未实现操作级预测/推演与评估，不满足suggest_include的必需条件，故列为相关综述。

证据层级：abstract；[来源](https://pubmed.ncbi.nlm.nih.gov/42893223/)；模型：qoder-cn/dfmodel。
