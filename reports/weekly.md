# 文献候选七日汇总 · 2026-10-29—2026-11-04

主题为规则建议或机器分析结果；候选不等同于正式收录。

## Computational Biology and Cellular Dynamics

- [DreamFold: A World Model to efficiently generate protein folding pathways in the latent space.](https://europepmc.org/article/MED/42813590) · 建议纳入，待审核 · `p-14e20f1cb202524e7adb`
  DreamFold在潜空间构建蛋白质折叠世界模型：用VAE编码蛋白构象与二面角动作，FFN学习动作条件下的构象转移，控制器从非折叠态迭代rollout生成折叠路径，并与长时MD及实验数据比较。
- [Nano-Bioadhesives for Gastrointestinal Hemostasis and Healing: Integrating Artificial Intelligence for Precision Design and Application.](https://pubmed.ncbi.nlm.nih.gov/42975278/) · 相关综述／资源 · `p-2fd34f283489ce52280f`
  该文为综述，讨论纳米生物黏合剂用于胃肠道止血与黏膜修复，并主张以AI驱动的多目标材料设计（预测建模、分子模拟、高通量实验、数字孪生与闭环优化）加速配方开发。
- [Digital twin-enabled toxicology: Current applications, opportunities, and future directions.](https://pubmed.ncbi.nlm.nih.gov/42686080/) · 相关综述／资源 · `p-345fc899021da38e74dd`
  该文综述数字孪生在毒理学中的应用，涵盖药物安全、环境与职业健康及个体化医学；强调以真实世界数据持续更新的生物系统虚拟副本可模拟器官或整体毒性反应并预测剂量反应，但多为概念性证据。
- [The (Butter)fly Dream: Linear Separability of World-Model Rollouts in a Connectome-Constrained Visual Model](https://arxiv.org/abs/2611.01866) · 相关综述／资源 · `p-36a47b650bec2b072b22`
  论文以连接组约束的果蝇视觉网络为固定观察者，将其细胞类型反应用于二样本检验，判断真实视频与三类世界模型生成的短序列“梦境”能否被线性区分，并考察训练、检测时域和分级时间扰动的影响。
- [Computational Models of the Foreign Body Response: A Focus on Biomaterial Properties.](https://pubmed.ncbi.nlm.nih.gov/42974717/) · 相关综述／资源 · `p-3d64048702f422c07394`
  该文综述植入性生物材料异物反应的计算建模进展，涵盖常微分方程、偏微分方程、基于个体及数据驱动等方法，关注炎症信号、巨噬细胞动态、纤维化与囊膜形成，并讨论材料属性的量化整合、校准与验证数据缺乏，以及异物反应数字孪生这一最终目标。
- [From self-quantification to predictive ageing: Digital twins as a framework for healthy ageing and longevity.](https://pubmed.ncbi.nlm.nih.gov/42705483/) · 相关综述／资源 · `p-66a09f461840356fd044`
  文章提出将衰老视为潜在动力系统的数字孪生框架，整合纵向生物标志物与可穿戴数据，区分可观测生理变化与潜在衰老动态，并设想模拟衰老轨迹和干预反事实测试；但属概念性综述与框架提案。
- [It's about time: modeling circadian regulation of cardiac electrophysiology and arrhythmogenesis.](https://pubmed.ncbi.nlm.nih.gov/42911378/) · 相关综述／资源 · `p-7a76802f9f6ba53b8147`
  该文综述将昼夜节律调控纳入心脏电生理计算模型的进展，提出“源—传递—靶”框架及 Hodgkin-Huxley 型电流级公式，讨论起搏、心律失常与药物致心律失常风险，并展望昼夜节律感知的心脏数字孪生。
- [Uncovering disease progression trajectories across multiple timescales with hybrid ODE-mixture models](https://europepmc.org/article/PPR/PPR1355727) · 待核验 · `p-7b979c23b8d6f0903630`
  提出LCPTA混合框架，将短期机制的ODE建模与长期参数演化的潜在类别轨迹建模结合，并开发TemporalMixtureModels.jl；在高血压与胰岛素抵抗合成纵向数据中恢复亚组结构与轨迹，摘要仅报告合成评估。
- [Reimagining antimicrobial resistance: AI-driven predictive epidemiology and the C-AMRE framework for next-generation antibiotic discovery.](https://pubmed.ncbi.nlm.nih.gov/42562952/) · 相关综述／资源 · `p-f07bebc7334c95ac54d8`
  该综述提出C-AMRE计算抗微生物耐药生态系统框架，整合进化智能、AI、全基因组监测、分子模拟与数字孪生，主张将AMR从表型检测与回顾性监测转向分子—患者—群体多层次的预测建模与适应性治疗决策。
- [Stand-In Effects and Pooling Amplification: Design-Based Tests of Whether Biological World Models Use Actions](https://arxiv.org/abs/2611.01666) · 相关综述／资源 · `p-63564ae7e4cfeb2df2c3`
  提出基于设计律的条件随机化检验，用于判断生物世界模型的预测是否真正受动作影响；揭示替代诊断的“替身效应”和多站点汇集的放大偏差，并在光遗传ERK细胞实验与像素世界模型中验证。
- [Prediction of Plasma Concentration-Time Profiles in Mice from Chemical Structure Using a Kinetically Constrained Hybrid Neural ODE.](https://europepmc.org/article/MED/42969730) · 待核验 · `p-079ddee0912cb0cecfb8`
  提出KCH-NODE，将可学习的二室PK典型轨迹与Neural ODE刻画的化合物特异连续时间偏差结合，从化学结构预测小鼠静脉和口服血浆浓度-时间曲线，并在交叉验证及时间外推集报告RMSE。
- [Nerandomilast is Associated With Altered Alveolar Epithelial Cell State Dynamics While Attenuating Fibrotic Remodeling in Pulmonary Fibrosis.](https://europepmc.org/article/MED/42827411) · 相关综述／资源 · `p-39dcf4a2058ac039ebf2`
  该研究在小鼠博来霉素肺纤维化模型中结合scRNA-seq、RNA velocity与组织学，发现nerandomilast减轻纤维化并改变肺泡上皮细胞状态动态，尤其是AT2向过渡态的方向性流动。

## Longitudinal EHR and Clinical Trajectories

- [Digital twins in geriatrics and gerontology: Applications, challenges, and future directions.](https://pubmed.ncbi.nlm.nih.gov/42570533/) · 相关综述／资源 · `p-669c1b5d73c6fbe25cd2`
  一篇叙述性综述，系统检索2014–2025年文献，梳理数字孪生在高龄人群与老年医学中的应用，涵盖心血管监测、跌倒预防、痴呆管理、多重用药优化与慢病自我管理，并讨论IoT、人工智能与电子健康档案等使能条件以及隐私、互操作、算力与伦理挑战。
- [From self-quantification to predictive ageing: Digital twins as a framework for healthy ageing and longevity.](https://pubmed.ncbi.nlm.nih.gov/42705483/) · 相关综述／资源 · `p-66a09f461840356fd044`
  文章提出将衰老视为潜在动力系统的数字孪生框架，整合纵向生物标志物与可穿戴数据，区分可观测生理变化与潜在衰老动态，并设想模拟衰老轨迹和干预反事实测试；但属概念性综述与框架提案。
- [Digital Twins in Clinical Neurology: From Concept to Clinical Application in Multiple Sclerosis.](https://pubmed.ncbi.nlm.nih.gov/42949247/) · 相关综述／资源 · `p-6f597cce41d570496499`
  叙述性综述，以多发性硬化为例梳理神经科患者数字孪生的概念、建模路径与转化障碍。将现有工作映射到数据整合、预测建模、动态更新与临床整合四大组件，指出多模态数据整合、数字生物标志物、机制仿真、虚拟患者与in silico试验等尚属构建模块，尚未整合为持续运行的临床系统。
- [Artificial intelligence in pediatric nephrology: current applications and emerging frameworks for evidence generation.](https://pubmed.ncbi.nlm.nih.gov/41739204/) · 相关综述／资源 · `p-304203b461b8ba725929`
  叙述性综述，概述人工智能在儿童肾脏病学中已可用或新兴的应用，涵盖诊断支持、预后建模、影像与病理分析、治疗个体化，并讨论AI虚拟试验与数字孪生等证据生成框架，以及儿童特有的伦理、监管与公平问题。
- [A proposed organization of multifaceted knowledge in data repositories: structuring record collections and evidence sets for data lakehouses and moonshots.](https://pubmed.ncbi.nlm.nih.gov/42608552/) · 相关综述／资源 · `p-a4fbaeac98f7c02bd914`
  该文提出PHENOM云平台，以混合湖仓架构和四类数据“箱”整合TBI多模态纵向数据，支持FAIR共享、跨研究查询，并提出数字孪生建模应用愿景。
- [Entity-aware pathology workflow informatics: Structured evidence mapping and a reference architecture for governed orchestration.](https://pubmed.ncbi.nlm.nih.gov/42893223/) · 相关综述／资源 · `p-1d6534420636f64b3762`
  该文以结构化证据映射梳理病理工作流中病例、标本、蜡块、切片、扫描与报告的表征和治理，并提出语义感知、实体感知过程状态、受限编排与治理执行的参考架构；属综述与架构设计，而非已部署验证的世界模型。

## Medical Imaging and Radiology

- [Non-invasive Computational Techniques for Diagnosing Myocardial Ischemia: Challenges and Future of FFRCT/iFRCT.](https://pubmed.ncbi.nlm.nih.gov/42209956/) · 相关综述／资源 · `p-36aa4c085ad367a2ad27`
  该文系统回顾基于计算流体力学（CFD）的无创FFRCT/iFRCT心肌缺血评估模型，指出刚性管壁假设与微循环代偿机制造成的计算偏差，并梳理提升计算效率的模型改进研究；未来设想为融合多模态临床数据、人工智能与数字孪生构建高保真心血管仿真模型。
- [Artificial intelligence in pediatric nephrology: current applications and emerging frameworks for evidence generation.](https://pubmed.ncbi.nlm.nih.gov/41739204/) · 相关综述／资源 · `p-304203b461b8ba725929`
  叙述性综述，概述人工智能在儿童肾脏病学中已可用或新兴的应用，涵盖诊断支持、预后建模、影像与病理分析、治疗个体化，并讨论AI虚拟试验与数字孪生等证据生成框架，以及儿童特有的伦理、监管与公平问题。
- [biv-me: Open-source software for generating time-varying biventricular meshes from cine cardiovascular magnetic resonance imaging with multi-cohort validation.](https://pubmed.ncbi.nlm.nih.gov/42579973/) · 相关综述／资源 · `p-a71c28b9c87bf3c9339f`
  biv-me 是开源端到端流程，可从电影心血管磁共振 DICOM 自动生成随时间变化的心室网格，并在五个公开数据集共 1313 项检查上外部验证，报告与临床参考软件高度一致、生成快速且可行。

## Surgical Simulation and Embodied Healthcare

- [\[Digital operating room-From dream to workflow\].](https://pubmed.ncbi.nlm.nih.gov/42862343/) · 相关综述／资源 · `p-61cb80c63a8819dcd31c`
  该文概述人工智能在创伤患者围手术期护理中的应用，包括术前规划、术中导航与机器人、环境AI与数字孪生、手术记录，以及数据异质性和伦理监管等挑战。

## Treatment Planning and Clinical Decision Support

- [Non-invasive Computational Techniques for Diagnosing Myocardial Ischemia: Challenges and Future of FFRCT/iFRCT.](https://pubmed.ncbi.nlm.nih.gov/42209956/) · 相关综述／资源 · `p-36aa4c085ad367a2ad27`
  该文系统回顾基于计算流体力学（CFD）的无创FFRCT/iFRCT心肌缺血评估模型，指出刚性管壁假设与微循环代偿机制造成的计算偏差，并梳理提升计算效率的模型改进研究；未来设想为融合多模态临床数据、人工智能与数字孪生构建高保真心血管仿真模型。
- [Pulse Physiology Engine to simulate transient oxygen changes and closed-loop, autonomous pump control during venovenous extracorporeal membrane oxygenation](https://europepmc.org/article/PPR/PPR1356081) · 相关综述／资源 · `p-5f1eac4c6aec205d313d`
  该研究基于Pulse生理引擎构建VV-ECMO患者特异模型，比较瞬时SvO2仿真与猪体内数据，将泵速作为模型输入并模拟PI闭环泵控制，报告时间常数相关性与血流预测。
- [Digital twins in geriatrics and gerontology: Applications, challenges, and future directions.](https://pubmed.ncbi.nlm.nih.gov/42570533/) · 相关综述／资源 · `p-669c1b5d73c6fbe25cd2`
  一篇叙述性综述，系统检索2014–2025年文献，梳理数字孪生在高龄人群与老年医学中的应用，涵盖心血管监测、跌倒预防、痴呆管理、多重用药优化与慢病自我管理，并讨论IoT、人工智能与电子健康档案等使能条件以及隐私、互操作、算力与伦理挑战。
- [Digital Twins in Clinical Neurology: From Concept to Clinical Application in Multiple Sclerosis.](https://pubmed.ncbi.nlm.nih.gov/42949247/) · 相关综述／资源 · `p-6f597cce41d570496499`
  叙述性综述，以多发性硬化为例梳理神经科患者数字孪生的概念、建模路径与转化障碍。将现有工作映射到数据整合、预测建模、动态更新与临床整合四大组件，指出多模态数据整合、数字生物标志物、机制仿真、虚拟患者与in silico试验等尚属构建模块，尚未整合为持续运行的临床系统。
- [A digital twin roadmap for adult spinal deformity.](https://pubmed.ncbi.nlm.nih.gov/42975781/) · 相关综述／资源 · `p-c871f470abda8f63a3f7`
  该叙述性综述将五组件医学数字孪生框架映射到成人脊柱畸形，提出以患者特异计算模型比较手术路径，并规划从回顾性回放到临床试点的路线图；所提供摘要未报告已实现的系统或评估。
- [Reimagining antimicrobial resistance: AI-driven predictive epidemiology and the C-AMRE framework for next-generation antibiotic discovery.](https://pubmed.ncbi.nlm.nih.gov/42562952/) · 相关综述／资源 · `p-f07bebc7334c95ac54d8`
  该综述提出C-AMRE计算抗微生物耐药生态系统框架，整合进化智能、AI、全基因组监测、分子模拟与数字孪生，主张将AMR从表型检测与回顾性监测转向分子—患者—群体多层次的预测建模与适应性治疗决策。
- [Artificial intelligence in pediatric nephrology: current applications and emerging frameworks for evidence generation.](https://pubmed.ncbi.nlm.nih.gov/41739204/) · 相关综述／资源 · `p-304203b461b8ba725929`
  叙述性综述，概述人工智能在儿童肾脏病学中已可用或新兴的应用，涵盖诊断支持、预后建模、影像与病理分析、治疗个体化，并讨论AI虚拟试验与数字孪生等证据生成框架，以及儿童特有的伦理、监管与公平问题。
- [\[Digital operating room-From dream to workflow\].](https://pubmed.ncbi.nlm.nih.gov/42862343/) · 相关综述／资源 · `p-61cb80c63a8819dcd31c`
  该文概述人工智能在创伤患者围手术期护理中的应用，包括术前规划、术中导航与机器人、环境AI与数字孪生、手术记录，以及数据异质性和伦理监管等挑战。

## 待分类

- [Advancing process control toward intelligent continuous biopharmaceutical manufacturing: Challenges, strategies, and future directions.](https://pubmed.ncbi.nlm.nih.gov/42472568/) · 相关综述／资源 · `p-6d54950836d3f8e83dc0`
  该文为连续生物制药制造过程控制的综述，梳理从常规反馈控制到模型预测控制、强化学习及数字孪生框架的策略演进，并讨论过程分析技术（PAT）与感知—建模—控制架构的整合，以维持持续受控状态。
- [Implementation Science Driven Identification of Barriers to AI Diagnostic Decision Support: A Stakeholder-Informed Concept Mapping Study](https://arxiv.org/abs/2611.02554) · 机器建议排除，待抽查 · `p-cdc8043e2de8b38f5ab3`
  采用结构化概念映射与整合知识转化框架，汇集96条陈述并归纳为11个集群，识别AI诊断决策支持在基础设施、伦理法律、工作流整合与算法信任方面的落地障碍，并将数字孪生作为未来延伸情境加以讨论。
