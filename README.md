# 📚 DailyFindings

> **每日 Agent 论文自动发现** · 由 [clawBot](https://github.com/Jacob-biu/clawBot) 驱动

自动从 [arxiv](https://arxiv.org/) 筛选来自**顶级 AI 机构**的最新 Agent 相关论文，  
每天北京时间 **08:00**（UTC 00:00）自动更新，包含结构化摘要概括与作者信息。

| 特性 | 说明 |
|------|------|
| 📡 数据来源 | arxiv API（cs.AI / cs.LG） |
| 🏛️ 机构筛选 | 70+ 顶级 AI 机构（MIT、Stanford、CMU、清华、OpenAI 等） |
| 🔍 关键词 | agent · multi-agent · LLM agent · agentic · autonomous agent |
| 📄 每日上限 | 最多 20 篇 |
| ⏰ 更新时间 | 每天 UTC 00:05（北京时间 08:05） |
| 📬 通知方式 | GitHub Issue @Jacob-biu |

---

## 📅 今日论文 — 2026-07-22　　[→ 查看完整报告](daily/2026-07-22.md)

> 共筛选出 **20** 篇论文 | 更新于 2026-07-22 23:02 UTC

### 论文目录与概要

| # | 论文标题 | 核心概要 | 来源机构 | 第一作者 |
|---|---------|---------|---------|--------|
| 1 | [CodeRescue: Budget-Calibrated Recovery Routing for Coding Ag…](http://arxiv.org/abs/2607.19338v1) | 编码代理越来越多地在可执行环境中运行，其中失败的尝试会产生可操作的反馈，而不仅仅是错误的答案。现有的成本感知系统通常将此类故障视为级联决策：首先尝试廉价模型，然后将困难案例升级为更强大、更昂贵的模型。… | CAS | Qijia He |
| 2 | [Agents in the Wild: Where Research Meets Deployment](http://arxiv.org/abs/2607.19336v1) | 代理系统基于大型语言模型（ LLM ）的架构能够与工具进行推理、规划、行动和协调，其他代理正在迅速从研究原型过渡到跨领域的生产规模部署，如软件工程、科学发现和财务。虽然学术工作强调基准和算法创新，但部… | MIT、HIT | Grace Hui Yang |
| 3 | [Fundamental limits of distributed multiclass classification …](http://arxiv.org/abs/2607.19334v1) | 我们考虑从$ O (\ log K) $简单二进制分类器的组合中构建$ K $类分类器的问题--这是以分布式方式构建复杂分类器的自然范式，每个代理执行相对简单的任务。我们研究了当相应的二进制分类器是超… | MIT、TRI | Ioannis Papageorgiou |
| 4 | [ResearchArena: Evaluating Sabotage and Monitoring in Automat…](http://arxiv.org/abs/2607.19321v1) | 随着人工智能代理开始自动化人工智能研发，我们需要方法来评估其输出是否可以安全部署，即使代理本身可能不受信任。人工智能控制提供了一种这样的方法：它不信任代理，而是将其视为潜在的对手，并在部署前使用监视器… | MIT | Lena Libon |
| 5 | [Staypoint Detection from Noisy Trajectory Data [Experiment P…](http://arxiv.org/abs/2607.19312v1) | 从原始轨迹数据中检测停留点是众多空间计算应用的基础。此过程将地理位置的原始数字序列转换为语义上有意义的位置，例如家庭、工作场所或餐馆。虽然这些结果非常有希望，但这些数据集和方法只是未来停留点检测研究的… | MIT、TRI | Lance Kennedy |
| 6 | [Graph-Based Agentic AI with LangGraph: Workflow Pathways for…](http://arxiv.org/abs/2607.19297v1) | 本文是业务流程中长期运行、有状态、多步骤生成AI系统的基于图形的工作流路径的从业人员指南。我们没有将LangGraph （一种用于有状态代理的低级编排框架）视为模型质量基准目标，而是提出了三种可执行配… | TRI | Daniel Pearson |
| 7 | [A Reinforcement-Learning-Augmented Liquid-Fueled Reactor Net…](http://arxiv.org/abs/2607.19281v1) | 本研究引入了一种用于生成最佳液体燃料反应堆的强化学习（ RL ）框架，以改善燃气轮机燃烧室中的贫气井喷（ LBO ）预测。现有的确定集群边界的方法依赖于输入空间中的手动启发式或基于距离的度量。总体而言… | TRI | Philip John |
| 8 | [They'll Verify. They Just Won't Act. How Authority Framing a…](http://arxiv.org/abs/2607.19267v1) | 我们研究了一个五代理CI/CD管道（分类- >开发人员- >安全扫描- >审查- >批准/部署） ，该管道由三个提供商的五个不同的生产LLM构建，位于LLM防火墙的影子模式后面。一个不受信任的输入-一… | CAS、TRI | Yohann Sidot |
| 9 | [Toward Auditable Fraud Detection: Combining Graph Features, …](http://arxiv.org/abs/2607.19266v1) | 欺诈检测系统必须随着交易量的增加而扩展，同时保持可解释性和可审查性。我们研究了PaySim数据集上的分层流水线，该流水线结合了梯度增强分类器、图衍生的结构特征、基于自编码器的异常信号、TreeSHAP… | CAS、TRI | Rahil Sharma |
| 10 | [S3: Stable Subgoal Selection by Constraining Uncertainty of …](http://arxiv.org/abs/2607.19232v1) | 分层强化学习（ HRL ）旨在将战略规划与原始执行分开。它在解决长视野和复杂任务方面已经取得了广泛的成功，其中flat-RL算法在学习方面存在困难。根据经验，我们观察到，密集的动态感知内在奖励会导致规… | MIT、TRI | Kshitij Kumar Srivastava |
| 11 | [Computing on the Fly: Navigating a Vision for the Future of …](http://arxiv.org/abs/2607.19213v1) | 该报告设想了一个十年，在这个十年中，无人机将以与高速公路和电网等国家基础设施投资相当的规模运输货物、医疗用品和信息。潜在的应用包括可在几分钟内发现野火源的自然灾害探测无人机，绕过地面拥堵到达农村医院的… | TRI | Kevin Butler |
| 12 | [ATLAS: A Foundation Neural Sampler for Amorphous Materials](http://arxiv.org/abs/2607.19198v1) | 无定形材料具有出色的机械和功能性能，但其坚固的能量景观是众所周知的难以采样的。在玻璃化转变温度以下，常规分子动力学和蒙特卡洛变得效率低下，因为平衡依赖于罕见的跨越障碍事件，而数据驱动的生成模型受到稀缺… | TRI | Mouyang Cheng |
| 13 | [ABot-World-0: Infinite Interactive World Rollout on a Single…](http://arxiv.org/abs/2607.19191v1) | 我们展示了ABot-World-0 ，这是一个用于实时、长视野闭环交互的动作条件视频世界模型，由跨越AAA游戏、模拟引擎和互联网视频的多源数据基础设施提供支持，以学习可控世界动态。WorldExplo… | NVIDIA、MIT | Fan Jiang |
| 14 | [Agentic Real2Sim: Physics-based World Modeling with Vision-L…](http://arxiv.org/abs/2607.19190v1) | 用于机器人与物体交互的Real-to-Sim转换仍然是劳动密集型的，因为它需要的不仅仅是视觉重建：简化的real2sim过程必须恢复场景几何形状和对象状态，推断物理参数，并将演员、物体、摄像机、姿势和… | TRI | Guanxiong Chen |
| 15 | [Comparative Study of Multi-Agent Actor-Critic Algorithms in …](http://arxiv.org/abs/2607.19117v1) | 参数化动作强化学习在需要离散动作选择和连续参数化的环境中表现出强大的性能。之前的工作确定了单代理Actor-Critic算法（贪婪Actor-Critic （ GAC ）、软Actor-Critic … | MIT | Ubayd Ali Bapoo |
| 16 | [Supra Cognitive Modes: A Routed Architecture for Agent Memor…](http://arxiv.org/abs/2607.19096v1) | 代理内存工作负载混合了直接的事实查找、关系链和当前状态推理，以及对长期历史的广泛综合。我们描述了Supra认知模式（ SCM ） ，这是一种将显式或自动选择的每次查询模式映射到一个共享摄取基质上的检索… | MIT、HIT | Joshua Tobkin |
| 17 | [FilmWorld: Agentic Novel-to-Film Generation through Dynamic …](http://arxiv.org/abs/2607.19038v1) | 将小说翻译成电影对生成式人工智能提出了巨大的挑战，需要将抽象文学散文转化为长篇、多场景的视觉叙事。虽然当前的视频生成模型在狭窄的时间和空间背景下擅长简短的单场景剪辑，但新颖到电影的生成在更复杂的制度下… | TRI | Jialong Zuo |
| 18 | [CoGoal3D: Collaborative 3D Object Detection with 3D-Aware Fu…](http://arxiv.org/abs/2607.19036v1) | V2X协作对象检测功能通过聚合来自多个协作代理的环境功能，克服了单车系统的局限性。然而，现有的主流V2X感知方法主要集中在2D BEV物体检测上。优惠码可在https://github.com/Meg… | MIT | Zhihao Yang |
| 19 | [MedDDC-Eval: Diagnosis-Decoupled Evaluation of Multi-Turn Me…](http://arxiv.org/abs/2607.18999v1) | 多轮医疗咨询代理人必须决定询问什么，适应患者的反应，并确定收集的证据何时足够。然而，耦合评估将策略引发的历史质量与策略特定的终端诊断生成混为一谈：强生成可以弥补薄弱的历史，而弱生成可以掩盖丰富的历史。… | CAS、TRI | Guofeng Zhang |
| 20 | [Athena-Brain Technical Report: An Efficient Robot Brain for …](http://arxiv.org/abs/2607.18985v1) | 大型语言模型（ LLM ）在语言理解、推理和世界知识方面表现出了非凡的能力。随着嵌入式代理变得越来越强大，对紧凑型模型的需求不断增长，这些模型可以充当设备上的大脑，保留LLM广泛的一般智能，同时实现与… | Mila | Jialian Li |

### 论文详情

<details>
<summary><b>1. CodeRescue: Budget-Calibrated Recovery Routing for Coding Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Qijia He、Jiayi Cheng、Chenqian Le、Rui Wang、Xunmei Liu 等（共 11 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | CAS |
| **发布时间** | 2026-07-21T17:56:49Z |
| **关键词** | `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2607.19338v1](http://arxiv.org/abs/2607.19338v1) |

**📝 摘要概括：**

> 编码代理越来越多地在可执行环境中运行，其中失败的尝试会产生可操作的反馈，而不仅仅是错误的答案。现有的成本感知系统通常将此类故障视为级联决策：首先尝试廉价模型，然后将困难案例升级为更强大、更昂贵的模型。优惠码可在https://github.com/Qijia-He/agent-budget-control上获得。

</details>

<details>
<summary><b>2. Agents in the Wild: Where Research Meets Deployment</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Grace Hui Yang、Pranav N. Venkit、Hooman Sedghamiz、Enrico Santus、Victor Dibia 等（共 6 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、HIT、CAS |
| **发布时间** | 2026-07-21T17:55:10Z |
| **关键词** | `Agentic` · `Reasoning` · `Planning` · `Benchmark` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2607.19336v1](http://arxiv.org/abs/2607.19336v1) |

**📝 摘要概括：**

> 代理系统基于大型语言模型（ LLM ）的架构能够与工具进行推理、规划、行动和协调，其他代理正在迅速从研究原型过渡到跨领域的生产规模部署，如软件工程、科学发现和财务。虽然学术工作强调基准和算法创新，但部署在稳健性、安全性和……方面提出了新的挑战。

</details>

<details>
<summary><b>3. Fundamental limits of distributed multiclass classification from simple binary decisions</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Ioannis Papageorgiou、Srinivas Nomula、Ayalvadi Ganesh、Sidharth Jaggi、Parimal Parag |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-07-21T17:53:44Z |
| **关键词** | `Simulation` |
| **原文链接** | [http://arxiv.org/abs/2607.19334v1](http://arxiv.org/abs/2607.19334v1) |

**📝 摘要概括：**

> 我们考虑从$ O (\ log K) $简单二进制分类器的组合中构建$ K $类分类器的问题--这是以分布式方式构建复杂分类器的自然范式，每个代理执行相对简单的任务。我们研究了当相应的二进制分类器是超平面时，这种分类器的基本性能极限。广泛的模拟实验提供了STRO...

</details>

<details>
<summary><b>4. ResearchArena: Evaluating Sabotage and Monitoring in Automated AI R&D</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Lena Libon、Ben Rank、Jehyeok Yeon、David Schmotz、Jeremy Qin 等（共 8 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT |
| **发布时间** | 2026-07-21T17:41:12Z |
| **关键词** | `AI Agent` · `Chain-of-Thought` |
| **原文链接** | [http://arxiv.org/abs/2607.19321v1](http://arxiv.org/abs/2607.19321v1) |

**📝 摘要概括：**

> 随着人工智能代理开始自动化人工智能研发，我们需要方法来评估其输出是否可以安全部署，即使代理本身可能不受信任。人工智能控制提供了一种这样的方法：它不信任代理，而是将其视为潜在的对手，并在部署前使用监视器检测秘密破坏。我们发布了ResearchArena ，作为评估自动化人工智能研发中的破坏和控制的模块化框架。

</details>

<details>
<summary><b>5. Staypoint Detection from Noisy Trajectory Data [Experiment Paper]</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Lance Kennedy、Hossein Amiri、Yueyang Liu、Riyang Bao、Hanqi Chen 等（共 12 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-07-21T17:27:06Z |
| **关键词** | `Benchmark` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2607.19312v1](http://arxiv.org/abs/2607.19312v1) |

**📝 摘要概括：**

> 从原始轨迹数据中检测停留点是众多空间计算应用的基础。此过程将地理位置的原始数字序列转换为语义上有意义的位置，例如家庭、工作场所或餐馆。虽然这些结果非常有希望，但这些数据集和方法只是未来停留点检测研究的起点。

</details>

<details>
<summary><b>6. Graph-Based Agentic AI with LangGraph: Workflow Pathways for Long-Running Stateful Business Processes</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Daniel Pearson、Sidney Shapiro、Emiliano Sebastian Gonzalez Venegas、Sanad Al-Khatib、Aurora Pinzón Arzola |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-07-21T17:07:13Z |
| **关键词** | `Agentic` · `Retrieval` · `Benchmark` · `Workflow` |
| **原文链接** | [http://arxiv.org/abs/2607.19297v1](http://arxiv.org/abs/2607.19297v1) |

**📝 摘要概括：**

> 本文是业务流程中长期运行、有状态、多步骤生成AI系统的基于图形的工作流路径的从业人员指南。我们没有将LangGraph （一种用于有状态代理的低级编排框架）视为模型质量基准目标，而是提出了三种可执行配方--带有修复循环的SQL分析、带有证据门控的代理检索增强生成，以及人机交互策略审查……

</details>

<details>
<summary><b>7. A Reinforcement-Learning-Augmented Liquid-Fueled Reactor Network Model for Predicting Lean Blowout in Gas Turbine Combustors</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Philip John、Eloghosa Ikponmwoba、Pinaki Pal、Opeoluwa Owoyele |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-07-21T16:53:08Z |
| **关键词** | `Reinforcement Learning` · `Simulation` |
| **原文链接** | [http://arxiv.org/abs/2607.19281v1](http://arxiv.org/abs/2607.19281v1) |

**📝 摘要概括：**

> 本研究引入了一种用于生成最佳液体燃料反应堆的强化学习（ RL ）框架，以改善燃气轮机燃烧室中的贫气井喷（ LBO ）预测。现有的确定集群边界的方法依赖于输入空间中的手动启发式或基于距离的度量。总体而言，强化学习驱动的方法作为一种计算效率高的降阶建模技术，具有很强的潜力，可以补充……

</details>

<details>
<summary><b>8. They'll Verify. They Just Won't Act. How Authority Framing and Laundered Code Turn a Trusted Agentic CI/CD Pipeline Into an Attack Surface</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Yohann Sidot |
| **所属机构** | （详见原文） |
| **顶级机构标签** | CAS、TRI |
| **发布时间** | 2026-07-21T16:38:32Z |
| **关键词** | `Agentic` · `Reasoning` |
| **原文链接** | [http://arxiv.org/abs/2607.19267v1](http://arxiv.org/abs/2607.19267v1) |

**📝 摘要概括：**

> 我们研究了一个五代理CI/CD管道（分类- >开发人员- >安全扫描- >审查- >批准/部署） ，该管道由三个提供商的五个不同的生产LLM构建，位于LLM防火墙的影子模式后面。一个不受信任的输入-一个请求“使用情况遥测”功能的外部问题-要求将进程机密（ dict （ os.environ ） ）泄露到攻击者URL的代码，作为可观察性进行清洗。所有数据都是100%合成的；水槽是m…

</details>

<details>
<summary><b>9. Toward Auditable Fraud Detection: Combining Graph Features, Model Explanations, and Agentic Case Investigation</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Rahil Sharma |
| **所属机构** | （详见原文） |
| **顶级机构标签** | CAS、TRI |
| **发布时间** | 2026-07-21T16:37:41Z |
| **关键词** | `Agentic` · `RAG` |
| **原文链接** | [http://arxiv.org/abs/2607.19266v1](http://arxiv.org/abs/2607.19266v1) |

**📝 摘要概括：**

> 欺诈检测系统必须随着交易量的增加而扩展，同时保持可解释性和可审查性。我们研究了PaySim数据集上的分层流水线，该流水线结合了梯度增强分类器、图衍生的结构特征、基于自编码器的异常信号、TreeSHAP解释以及应用于分类器评分不确定的案例的有界LLM调查代理。我们得出的结论是，分层欺诈系统的每个组成部分都包含……

</details>

<details>
<summary><b>10. S3: Stable Subgoal Selection by Constraining Uncertainty of Coarse Dynamics in Hierarchical Reinforcement Learning</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Kshitij Kumar Srivastava、Kshitij Jerath |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-07-21T16:03:34Z |
| **关键词** | `Planning` · `Reinforcement Learning` · `RAG` |
| **原文链接** | [http://arxiv.org/abs/2607.19232v1](http://arxiv.org/abs/2607.19232v1) |

**📝 摘要概括：**

> 分层强化学习（ HRL ）旨在将战略规划与原始执行分开。它在解决长视野和复杂任务方面已经取得了广泛的成功，其中flat-RL算法在学习方面存在困难。根据经验，我们观察到，密集的动态感知内在奖励会导致规避风险的子目标选择，使其能够在非平稳长视野环境中超越最先进的HRL方法。

</details>

<details>
<summary><b>11. Computing on the Fly: Navigating a Vision for the Future of Drone Computing</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Kevin Butler、Christopher Stewart、Nils Aschenbruck、Alina Gerall、Weisong Shi 等（共 7 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-07-21T15:42:35Z |
| **关键词** | `Agentic` |
| **原文链接** | [http://arxiv.org/abs/2607.19213v1](http://arxiv.org/abs/2607.19213v1) |

**📝 摘要概括：**

> 该报告设想了一个十年，在这个十年中，无人机将以与高速公路和电网等国家基础设施投资相当的规模运输货物、医疗用品和信息。潜在的应用包括可在几分钟内发现野火源的自然灾害探测无人机，绕过地面拥堵到达农村医院的医疗供应链，以及持续检查桥梁和电力线的全国车队。

</details>

<details>
<summary><b>12. ATLAS: A Foundation Neural Sampler for Amorphous Materials</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Mouyang Cheng、Denis Blessing、Botao Yu、Gerhard Neumann、Mingda Li 等（共 7 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-07-21T15:31:49Z |
| **关键词** | `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2607.19198v1](http://arxiv.org/abs/2607.19198v1) |

**📝 摘要概括：**

> 无定形材料具有出色的机械和功能性能，但其坚固的能量景观是众所周知的难以采样的。在玻璃化转变温度以下，常规分子动力学和蒙特卡洛变得效率低下，因为平衡依赖于罕见的跨越障碍事件，而数据驱动的生成模型受到稀缺和有偏见的参考集合的限制。这些结果共同建立了ATL……

</details>

<details>
<summary><b>13. ABot-World-0: Infinite Interactive World Rollout on a Single Desktop GPU</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Fan Jiang、Zhaoxu Sun、Mengchao Wang、Ziyu Zhu、Chiyu Wang 等（共 41 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | NVIDIA、MIT、TRI |
| **发布时间** | 2026-07-21T15:26:50Z |
| **关键词** | `Simulation` · `Memory` |
| **原文链接** | [http://arxiv.org/abs/2607.19191v1](http://arxiv.org/abs/2607.19191v1) |

**📝 摘要概括：**

> 我们展示了ABot-World-0 ，这是一个用于实时、长视野闭环交互的动作条件视频世界模型，由跨越AAA游戏、模拟引擎和互联网视频的多源数据基础设施提供支持，以学习可控世界动态。WorldExplorer在培训反馈的指导下执行代理驱动的收集，而统一的管道应用14个确定性质量检查、基于VLM的评估和同步动作……

</details>

<details>
<summary><b>14. Agentic Real2Sim: Physics-based World Modeling with Vision-Language Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Guanxiong Chen、Qianjun Xia、Jiawei Peng、Heng Zhang、Bole Ma 等（共 23 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-07-21T15:23:38Z |
| **关键词** | `Agentic` · `Evaluation` · `Simulation` · `Robotics` · `Workflow` |
| **原文链接** | [http://arxiv.org/abs/2607.19190v1](http://arxiv.org/abs/2607.19190v1) |

**📝 摘要概括：**

> 用于机器人与物体交互的Real-to-Sim转换仍然是劳动密集型的，因为它需要的不仅仅是视觉重建：简化的real2sim过程必须恢复场景几何形状和对象状态，推断物理参数，并将演员、物体、摄像机、姿势和轨迹组装成可运行的物理模拟。今天，这个过程仍然依赖于手动调整视觉基础模型、网格清理、坐标系……

</details>

<details>
<summary><b>15. Comparative Study of Multi-Agent Actor-Critic Algorithms in Parameterized Action Reinforcement Learning</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Ubayd Ali Bapoo、Clement N Nyirenda |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT |
| **发布时间** | 2026-07-21T14:03:29Z |
| **关键词** | `Multi-Agent` · `Reinforcement Learning` · `RAG` · `Benchmark` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2607.19117v1](http://arxiv.org/abs/2607.19117v1) |

**📝 摘要概括：**

> 参数化动作强化学习在需要离散动作选择和连续参数化的环境中表现出强大的性能。之前的工作确定了单代理Actor-Critic算法（贪婪Actor-Critic （ GAC ）、软Actor-Critic （ SAC ）和截断分位数Critics （ TQC ） ）在基准参数化行动任务上的有效性，但它们对多代理设置的扩展在很大程度上仍未得到探索。…

</details>

<details>
<summary><b>16. Supra Cognitive Modes: A Routed Architecture for Agent Memory</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Joshua Tobkin、David Yang |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、HIT、Mila |
| **发布时间** | 2026-07-21T13:37:17Z |
| **关键词** | `Reasoning` · `Retrieval` · `Benchmark` · `Memory` |
| **原文链接** | [http://arxiv.org/abs/2607.19096v1](http://arxiv.org/abs/2607.19096v1) |

**📝 摘要概括：**

> 代理内存工作负载混合了直接的事实查找、关系链和当前状态推理，以及对长期历史的广泛综合。我们描述了Supra认知模式（ SCM ） ，这是一种将显式或自动选择的每次查询模式映射到一个共享摄取基质上的检索和合成有效负载的架构。因果路由效应、效率提升和统计显著性仍在现有证据之外。

</details>

<details>
<summary><b>17. FilmWorld: Agentic Novel-to-Film Generation through Dynamic Cinematic World Modeling</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Jialong Zuo、Haotong Zuo、Shiwei Zhang、Xiang Wang、Chen Li 等（共 8 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-07-21T12:28:58Z |
| **关键词** | `Agentic` · `Planning` · `Benchmark` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2607.19038v1](http://arxiv.org/abs/2607.19038v1) |

**📝 摘要概括：**

> 将小说翻译成电影对生成式人工智能提出了巨大的挑战，需要将抽象文学散文转化为长篇、多场景的视觉叙事。虽然当前的视频生成模型在狭窄的时间和空间背景下擅长简短的单场景剪辑，但新颖到电影的生成在更复杂的制度下运行，需要跨不同场景的长时间内容，并具有动态演变的内容。

</details>

<details>
<summary><b>18. CoGoal3D: Collaborative 3D Object Detection with 3D-Aware Fusion and Refinement</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Zhihao Yang、Zhiyu Xiang、Peng Xu、Tianyu Pu、Kai Wang 等（共 8 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT |
| **发布时间** | 2026-07-21T12:20:48Z |
| **关键词** | `Multi-Agent` |
| **原文链接** | [http://arxiv.org/abs/2607.19036v1](http://arxiv.org/abs/2607.19036v1) |

**📝 摘要概括：**

> V2X协作对象检测功能通过聚合来自多个协作代理的环境功能，克服了单车系统的局限性。然而，现有的主流V2X感知方法主要集中在2D BEV物体检测上。优惠码可在https://github.com/Megalo-f/CoGoal3D上获得。

</details>

<details>
<summary><b>19. MedDDC-Eval: Diagnosis-Decoupled Evaluation of Multi-Turn Medical Consultation Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Guofeng Zhang、Yizeng Quan、Huaiyi Fang、Jianwei Lv、Jinyao Liu 等（共 9 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | CAS、TRI |
| **发布时间** | 2026-07-21T11:32:41Z |
| **关键词** | `RAG` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2607.18999v1](http://arxiv.org/abs/2607.18999v1) |

**📝 摘要概括：**

> 多轮医疗咨询代理人必须决定询问什么，适应患者的反应，并确定收集的证据何时足够。然而，耦合评估将策略引发的历史质量与策略特定的终端诊断生成混为一谈：强生成可以弥补薄弱的历史，而弱生成可以掩盖丰富的历史。这些结果表明， MedDDC-Eval支持受控归因…

</details>

<details>
<summary><b>20. Athena-Brain Technical Report: An Efficient Robot Brain for General Intelligence and Embodied Interactio</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Jialian Li、Junhong Liu、Yuchen Cao、Weiran Guo、Jiaming Song 等（共 9 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | Mila |
| **发布时间** | 2026-07-21T11:19:21Z |
| **关键词** | `Reasoning` · `Reinforcement Learning` · `Benchmark` · `Evaluation` · `Fine-tuning` |
| **原文链接** | [http://arxiv.org/abs/2607.18985v1](http://arxiv.org/abs/2607.18985v1) |

**📝 摘要概括：**

> 大型语言模型（ LLM ）在语言理解、推理和世界知识方面表现出了非凡的能力。随着嵌入式代理变得越来越强大，对紧凑型模型的需求不断增长，这些模型可以充当设备上的大脑，保留LLM广泛的一般智能，同时实现与嵌入式环境的有效高层交互。在域内体现的基准上， Athena-Brain-8B始终如一……

</details>

## 🗄️ 历史归档

| 日期 | 论文数 | 报告链接 |
|------|--------|----------|
| 2026-07-22 | 20 篇 | [2026-07-22.md](daily/2026-07-22.md) |
| 2026-07-21 | 20 篇 | [2026-07-21.md](daily/2026-07-21.md) |
| 2026-07-20 | 0 篇 | [2026-07-20.md](daily/2026-07-20.md) |
| 2026-07-19 | 0 篇 | [2026-07-19.md](daily/2026-07-19.md) |
| 2026-07-18 | 0 篇 | [2026-07-18.md](daily/2026-07-18.md) |
| 2026-07-17 | 17 篇 | [2026-07-17.md](daily/2026-07-17.md) |
| 2026-07-16 | 11 篇 | [2026-07-16.md](daily/2026-07-16.md) |
| 2026-07-15 | 14 篇 | [2026-07-15.md](daily/2026-07-15.md) |
| 2026-07-13 | 0 篇 | [2026-07-13.md](daily/2026-07-13.md) |
| 2026-07-12 | 0 篇 | [2026-07-12.md](daily/2026-07-12.md) |
| 2026-07-11 | 0 篇 | [2026-07-11.md](daily/2026-07-11.md) |
| 2026-07-10 | 16 篇 | [2026-07-10.md](daily/2026-07-10.md) |
| 2026-07-09 | 15 篇 | [2026-07-09.md](daily/2026-07-09.md) |
| 2026-07-08 | 13 篇 | [2026-07-08.md](daily/2026-07-08.md) |
| 2026-07-07 | 18 篇 | [2026-07-07.md](daily/2026-07-07.md) |
| 2026-07-06 | 0 篇 | [2026-07-06.md](daily/2026-07-06.md) |
| 2026-07-05 | 0 篇 | [2026-07-05.md](daily/2026-07-05.md) |
| 2026-07-04 | 0 篇 | [2026-07-04.md](daily/2026-07-04.md) |
| 2026-07-03 | 20 篇 | [2026-07-03.md](daily/2026-07-03.md) |
| 2026-07-02 | 0 篇 | [2026-07-02.md](daily/2026-07-02.md) |
| 2026-07-01 | 0 篇 | [2026-07-01.md](daily/2026-07-01.md) |
| 2026-06-30 | 20 篇 | [2026-06-30.md](daily/2026-06-30.md) |
| 2026-06-29 | 0 篇 | [2026-06-29.md](daily/2026-06-29.md) |
| 2026-06-28 | 0 篇 | [2026-06-28.md](daily/2026-06-28.md) |
| 2026-06-27 | 0 篇 | [2026-06-27.md](daily/2026-06-27.md) |
| 2026-06-26 | 17 篇 | [2026-06-26.md](daily/2026-06-26.md) |
| 2026-06-25 | 11 篇 | [2026-06-25.md](daily/2026-06-25.md) |
| 2026-06-24 | 9 篇 | [2026-06-24.md](daily/2026-06-24.md) |
| 2026-06-23 | 15 篇 | [2026-06-23.md](daily/2026-06-23.md) |
| 2026-06-22 | 0 篇 | [2026-06-22.md](daily/2026-06-22.md) |

## 🏛️ 顶级机构覆盖范围

覆盖超过 **70 个**顶级 AI 机构，包括：

- **科技公司：** Microsoft、Google DeepMind、OpenAI、Anthropic、Meta AI、NVIDIA、Baidu、Alibaba、ByteDance 等
- **北美顶级大学：** MIT、Stanford、CMU、UC Berkeley、Harvard、Princeton、Cornell、Caltech 等
- **中国顶级大学/机构：** 清华大学、北京大学、浙大、上交大、复旦、中科院、MSRA 等
- **欧洲/其他：** Oxford、Cambridge、ETH Zurich、Mila、NUS、KAIST 等

---

*由 [clawBot DailyFindings](https://github.com/Jacob-biu/clawBot) 自动维护 | 最后更新：2026-07-22 23:02 UTC*
