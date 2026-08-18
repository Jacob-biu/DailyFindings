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

## 📅 今日论文 — 2026-08-18　　[→ 查看完整报告](daily/2026-08-18.md)

> 共筛选出 **20** 篇论文 | 更新于 2026-08-18 22:21 UTC

### 论文目录与概要

| # | 论文标题 | 核心概要 | 来源机构 | 第一作者 |
|---|---------|---------|---------|--------|
| 1 | [Don't Drop the BATON: Long-Horizon Robot Manipulation via Ag…](http://arxiv.org/abs/2608.16889v1) | 长视野机器人操纵将许多接触丰富的技能链接到一个多阶段任务中。视觉-语言-行动（ VLA ）模型越来越多地掌握个人技能，但链条仍然失败：错误超出了策略的纠正能力，一个子任务无声地限制了下一个子任务。在长… | MIT、TRI | Bingxin Xu |
| 2 | [AutoSR: Automatic Symbolic Regression by Searching Research …](http://arxiv.org/abs/2608.16876v1) | 我们引入了自动符号回归（ AutoSR ） ，这是一个完全自动化的系统，通过搜索持久的科学调查而不是孤立的方程来实例化研究空间符号回归。有限的、嘈杂的数据通常会产生数值竞争表达式，这意味着观察到的制度… | CAS | Kejia Zhang |
| 3 | [HAF: Adapting Generalist VLAs to Humanoid Whole-Body Loco-ma…](http://arxiv.org/abs/2608.16837v1) | 人形机器人在以人为中心的环境中作为通用代理具有很大的前景，但通用视觉-语言-行动（ VLA ）基础模型不容易适用于人形全身机器人操作。人形运动的高维度和相互依赖性使得传统的单级VLA架构难以有效协调运… | HIT、TRI | Langzhe Gu |
| 4 | [GEO-Flag: Detecting and Measuring GEO-Optimized Web Content](http://arxiv.org/abs/2608.16824v1) | 生成引擎优化（ GEO ）修改网络内容，以增加其被生成搜索引擎选择和引用的可能性。这可能会使战略上优化的页面可见性与其权威或相关性不成比例，甚至会使弱信息或虚假信息看起来得到很好的支持。我们的研究结果… | Google、TRI | Junjie Chu |
| 5 | [When State Becomes an Attack Surface: State-Semantic Injecti…](http://arxiv.org/abs/2608.16806v1) | 大型语言模型（ LLM ）已经展示了上下文学习、任务分解、逐步推理和代码生成的能力，推动其从文本生成模型逐渐演变为能够感知环境、调用工具和执行任务的代理核心。传统的LLM代理通常通过网页、文档、数据库… | TRI | Jiawei Liu |
| 6 | [When Agents Coordinate: Measuring Coordination in Multi-Agen…](http://arxiv.org/abs/2608.16801v1) | 我们研究AI编码代理团队在解决编程任务时如何协调。目前的评估通常会报告客服代表是否完成了任务以及运行成本，而团队内部的协调在很大程度上无法衡量。在244次额外的运行中，代理仍然在五分之四的运行中达到它… | CAS | Giuseppe Destefanis |
| 7 | [Neurosymbolic Embodied Agents](http://arxiv.org/abs/2608.16794v1) | 语言和视觉语言模型生成合理的具体计划，但不能保证可执行性，因为它们的输出可能会违反环境动态或对错误接地的实体采取行动。我们提出了一种神经符号代理，它将长视野家务分解为任务导向的视觉探索和约束的符号规划… | TRI | Mohammad Albinhassan |
| 8 | [Topological Attribution Distance (TAD): Revealing Segment-Le…](http://arxiv.org/abs/2608.16775v1) | 大型语言模型（ LLM ）越来越多地部署在网络安全运营中，以协助网络安全分析师快速制定应对新兴威胁的决策。但是，在网络安全中使用LLM时必须满足一个主要标准，即对生成的输出的信任。这可以根据每个LLM… | Mila、TRI | Reza Fayyazi |
| 9 | [Would this change your answer? Evaluating Explanations of LL…](http://arxiv.org/abs/2608.16747v1) | 人工智能研究的许多领域，如语言模型的可解释性和思维链的忠诚度，都试图解释模型行为。但是什么是“好”的解释呢？总体而言， CHIVE自动发现自然发生的LLM行为的解释，使我们能够评估和改进解释LLM行为… | TRI | Adam Karvonen |
| 10 | [TDD-Agent: Test-Driven Reasoning for Code Generation](http://arxiv.org/abs/2608.16742v1) | 大型语言模型（ LLM ）在代码生成方面取得了显着进展，但确保复杂存储库级任务的正确性仍然具有挑战性。现有方法通常将生成的测试用作静态事后验证器，这限制了它们指导实施的能力，并且在测试本身不完整或不正… | MIT、TRI | Hongyue Yu |
| 11 | [GoalEvolve: From Handcrafted Algorithm Priors to Goal-Driven…](http://arxiv.org/abs/2608.16733v1) | 物理设计算法在紧密耦合的多阶段优化流程中运行，其中阶段-局部增益可能消失或诱发下游退化。现有的程序进化框架通常依赖于阶段-局部目标或未分化的多指标反馈，这些反馈既不能保证更好的最终结果，也不能确定哪些… | TRI | Haixu Liu |
| 12 | [The Ethical Decision Head: Operationalizing Normative Ethics…](http://arxiv.org/abs/2608.16710v1) | 随着自动驾驶汽车（ AV ）接近4级和5级运营能力[SAE International, 2018] ，其车载决策系统不仅必须处理安全关键的运动，还必须处理其随后的道德权重。本文详细介绍了道德决策主管… | CAS | Thomas Mbrice |
| 13 | [Semantic Bandits: In-Context Exploration-Exploitation is Bia…](http://arxiv.org/abs/2608.16707v1) | 在需要复杂的环境探索的环境中，大型语言模型（ LLM ）越来越多地被部署为决策代理。然而，现有的工作提出了LLM如何真正平衡勘探和开发的问题。总的来说，我们认为，使用语言来定义环境和奖励会引入不可避免… | TRI | David Eric Austin |
| 14 | [Chronocooked: A Benchmark for Implicit Interval Timing in Re…](http://arxiv.org/abs/2608.16666v1) | 本文提出了Chronocooked ，这是一个强化学习（ RL ）基准套件，用于研究RL代理中的隐式间隔时间。套房的灵感来自Overcooked ，包括需要临时决策的烹饪场景。这项工作最终旨在强调将时… | MIT、TRI | Amrapali Pednekar |
| 15 | [Orbit-Planner: Towards Latent World Models for On-Orbit Obst…](http://arxiv.org/abs/2608.16651v1) | 用于在轨导航任务的卫星代理需要使用有限的机载观测来预测碰撞风险。然而，传统的规划者通常依赖于预定义的地图和固定的环境假设，限制了它们在动态在轨场景中的适应性。优惠码可在https://github.c… | MIT | Zhijian Li |
| 16 | [Reconstruction: A Blind Benchmark for Recovering Research Id…](http://arxiv.org/abs/2608.16645v1) | 当只给出论文的出版前参考书目时，语言模型能否恢复已发表论文的真正研究理念？我们引入了重建，这是一个盲目的想法恢复基准，它保留了种子纸和所有同期或未来的文献，并要求模型提出假设，即独立的大型语言模型法官… | TRI | Shaolong Chen |
| 17 | [PDDLCoder: Agentic PDDL Generation for LLM-Assisted Symbolic…](http://arxiv.org/abs/2608.16637v1) | LLM在长期规划中仍然不可靠，通常会产生逻辑不一致或不适用的计划。最近的混合方法将自然语言转换为规划域定义语言（ PDDL ） ，允许符号规划人员生成可验证的计划。我们的工作证明了代理PDDL生成用于… | MIT | Veit Laule |
| 18 | [The Working Set of a Coding Agent: Coherence Debt in Reposit…](http://arxiv.org/abs/2608.16630v1) | 存储库规模编码要求代理在有界上下文窗口内保持测试、导入、配置和迁移规则的一致性。我们将其建模为重建耦合事实图：在每次编辑时，所需的事实来自最近的上下文或参数记忆，而两者所涵盖的事实都不构成一致性债务。… | TRI | Bardia Mohammadi |
| 19 | [Cost Scales with Change, Not Corpus Size: Incrementally Main…](http://arxiv.org/abs/2608.16621v1) | 检索-增强和代理问答系统越来越多地在查询时重新推导语料库的含义。简单地说，不是重新推导语料库在每个问题上的含义，而是在文档到达时完成一次工作，然后仅被查阅-一个编译器，而不是一个意义的解释器。结果支持… | TRI | Yusuke Takahashi |
| 20 | [Physics of Agents: Statistical Mechanics Predicts Collective…](http://arxiv.org/abs/2608.16578v1) | 人工智能代理越来越多地作为交互系统的一部分而不是孤立地运行。随着代理人交换信息并共同做出决策，他们的互动可以改善集体推理，但也可能产生放牧、两极分化或放大共同的偏见。总体而言，我们的研究结果表明，像其… | TRI | Batu El |

### 论文详情

<details>
<summary><b>1. Don't Drop the BATON: Long-Horizon Robot Manipulation via Agentic Subtask Exploration and Transition-aware Memory</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Bingxin Xu、Yuzhang Shang、Emilio Ferrara |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-08-17T17:59:57Z |
| **关键词** | `LLM Agent` · `Agentic` · `Benchmark` · `Memory` |
| **原文链接** | [http://arxiv.org/abs/2608.16889v1](http://arxiv.org/abs/2608.16889v1) |

**📝 摘要概括：**

> 长视野机器人操纵将许多接触丰富的技能链接到一个多阶段任务中。视觉-语言-行动（ VLA ）模型越来越多地掌握个人技能，但链条仍然失败：错误超出了策略的纠正能力，一个子任务无声地限制了下一个子任务。在长期基准RoboMemArena上，与SoTA相比， BATON将任务成功率提高了11.6% ，累计成功率提高了14.9%。

</details>

<details>
<summary><b>2. AutoSR: Automatic Symbolic Regression by Searching Research States</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Kejia Zhang、Youran Sun、Xinyu Ren、Chugang Yi、Haizhao Yang |
| **所属机构** | （详见原文） |
| **顶级机构标签** | CAS |
| **发布时间** | 2026-08-17T17:55:26Z |
| **关键词** | `Reasoning` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2608.16876v1](http://arxiv.org/abs/2608.16876v1) |

**📝 摘要概括：**

> 我们引入了自动符号回归（ AutoSR ） ，这是一个完全自动化的系统，通过搜索持久的科学调查而不是孤立的方程来实例化研究空间符号回归。有限的、嘈杂的数据通常会产生数值竞争表达式，这意味着观察到的制度之外的行为非常不同，使得数值拟合和句法复杂性不足以衡量科学可信度。总的来说， Au…

</details>

<details>
<summary><b>3. HAF: Adapting Generalist VLAs to Humanoid Whole-Body Loco-manipulation via Hierarchical Action Flow and Spectral Latent RL</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Langzhe Gu、Chengkai Hou、Meng Li、Xinhua Wang、Jiaming Liu 等（共 17 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | HIT、TRI |
| **发布时间** | 2026-08-17T17:22:33Z |
| **关键词** | `Reinforcement Learning` · `RAG` |
| **原文链接** | [http://arxiv.org/abs/2608.16837v1](http://arxiv.org/abs/2608.16837v1) |

**📝 摘要概括：**

> 人形机器人在以人为中心的环境中作为通用代理具有很大的前景，但通用视觉-语言-行动（ VLA ）基础模型不容易适用于人形全身机器人操作。人形运动的高维度和相互依赖性使得传统的单级VLA架构难以有效协调运动、腰部姿势和双臂操纵。

</details>

<details>
<summary><b>4. GEO-Flag: Detecting and Measuring GEO-Optimized Web Content</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Junjie Chu、Ye Leng、Mingjie Li、Yun Shen、Xinyue Shen 等（共 6 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | Google、TRI |
| **发布时间** | 2026-08-17T17:12:11Z |
| **关键词** | `Retrieval` · `Benchmark` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2608.16824v1](http://arxiv.org/abs/2608.16824v1) |

**📝 摘要概括：**

> 生成引擎优化（ GEO ）修改网络内容，以增加其被生成搜索引擎选择和引用的可能性。这可能会使战略上优化的页面可见性与其权威或相关性不成比例，甚至会使弱信息或虚假信息看起来得到很好的支持。我们的研究结果为在真实世界的搜索生态系统中系统地检测、审核和测量GEO奠定了基础。

</details>

<details>
<summary><b>5. When State Becomes an Attack Surface: State-Semantic Injection in LLM-Driven Embodied Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Jiawei Liu、Jiacheng Guo、Tian Zhang、Yiwei Xu、Juan Wang 等（共 10 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-08-17T17:02:07Z |
| **关键词** | `LLM Agent` · `Reasoning` · `Planning` · `Code Generation` · `Embodied AI` |
| **原文链接** | [http://arxiv.org/abs/2608.16806v1](http://arxiv.org/abs/2608.16806v1) |

**📝 摘要概括：**

> 大型语言模型（ LLM ）已经展示了上下文学习、任务分解、逐步推理和代码生成的能力，推动其从文本生成模型逐渐演变为能够感知环境、调用工具和执行任务的代理核心。传统的LLM代理通常通过网页、文档、数据库或外部工具获取信息，并生成相应的调用…

</details>

<details>
<summary><b>6. When Agents Coordinate: Measuring Coordination in Multi-Agent AI Coding</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Giuseppe Destefanis、Tomaso Aste |
| **所属机构** | （详见原文） |
| **顶级机构标签** | CAS |
| **发布时间** | 2026-08-17T16:57:38Z |
| **关键词** | `Multi-Agent` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2608.16801v1](http://arxiv.org/abs/2608.16801v1) |

**📝 摘要概括：**

> 我们研究AI编码代理团队在解决编程任务时如何协调。目前的评估通常会报告客服代表是否完成了任务以及运行成本，而团队内部的协调在很大程度上无法衡量。在244次额外的运行中，代理仍然在五分之四的运行中达到它，而协调员和文件通道结果重现。

</details>

<details>
<summary><b>7. Neurosymbolic Embodied Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Mohammad Albinhassan、Yuming Feng、Alessandra Russo、Pranava Madhyastha |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-08-17T16:50:59Z |
| **关键词** | `Planning` · `Embodied AI` |
| **原文链接** | [http://arxiv.org/abs/2608.16794v1](http://arxiv.org/abs/2608.16794v1) |

**📝 摘要概括：**

> 语言和视觉语言模型生成合理的具体计划，但不能保证可执行性，因为它们的输出可能会违反环境动态或对错误接地的实体采取行动。我们提出了一种神经符号代理，它将长视野家务分解为任务导向的视觉探索和约束的符号规划。该方法还使用比扩展思维少几倍的生成令牌和少得多的模型访问……

</details>

<details>
<summary><b>8. Topological Attribution Distance (TAD): Revealing Segment-Level RAG Influence on LLM Output Geometry for Incident Log Analysis</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Reza Fayyazi、Michael Zuzak、Shanchieh Jay Yang |
| **所属机构** | （详见原文） |
| **顶级机构标签** | Mila、TRI |
| **发布时间** | 2026-08-17T16:21:18Z |
| **关键词** | `Agentic` · `RAG` · `Workflow` |
| **原文链接** | [http://arxiv.org/abs/2608.16775v1](http://arxiv.org/abs/2608.16775v1) |

**📝 摘要概括：**

> 大型语言模型（ LLM ）越来越多地部署在网络安全运营中，以协助网络安全分析师快速制定应对新兴威胁的决策。但是，在网络安全中使用LLM时必须满足一个主要标准，即对生成的输出的信任。这可以根据每个LLM的隐藏状态提供可解释且值得信赖的跟踪，以了解几何上不同的检索日志信息……

</details>

<details>
<summary><b>9. Would this change your answer? Evaluating Explanations of LLM Behavior In The Wild with Counterfactual Experiments</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Adam Karvonen、Euan Ong、Subhash Kantamneni、Samuel Marks |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-08-17T15:57:06Z |
| **关键词** | `Agentic` |
| **原文链接** | [http://arxiv.org/abs/2608.16747v1](http://arxiv.org/abs/2608.16747v1) |

**📝 摘要概括：**

> 人工智能研究的许多领域，如语言模型的可解释性和思维链的忠诚度，都试图解释模型行为。但是什么是“好”的解释呢？总体而言， CHIVE自动发现自然发生的LLM行为的解释，使我们能够评估和改进解释LLM行为的方法。

</details>

<details>
<summary><b>10. TDD-Agent: Test-Driven Reasoning for Code Generation</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Hongyue Yu、Kefan Li、Jiakun Li、Hongzheng Chai、Yuan Yuan 等（共 7 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-08-17T15:52:04Z |
| **关键词** | `Reasoning` · `RAG` · `Retrieval` · `Benchmark` · `Code Generation` |
| **原文链接** | [http://arxiv.org/abs/2608.16742v1](http://arxiv.org/abs/2608.16742v1) |

**📝 摘要概括：**

> 大型语言模型（ LLM ）在代码生成方面取得了显着进展，但确保复杂存储库级任务的正确性仍然具有挑战性。现有方法通常将生成的测试用作静态事后验证器，这限制了它们指导实施的能力，并且在测试本身不完整或不正确时可能会引入误导性反馈。我们的源代码可在https://anonymous.4open.science/r上找到……

</details>

<details>
<summary><b>11. GoalEvolve: From Handcrafted Algorithm Priors to Goal-Driven Evolution of Physical Design Algorithms</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Haixu Liu、Lei Zhou、Yuhao Ren、Yumao Wu、Zhiang Wang |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-08-17T15:45:33Z |
| **关键词** | `RAG` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2608.16733v1](http://arxiv.org/abs/2608.16733v1) |

**📝 摘要概括：**

> 物理设计算法在紧密耦合的多阶段优化流程中运行，其中阶段-局部增益可能消失或诱发下游退化。现有的程序进化框架通常依赖于阶段-局部目标或未分化的多指标反馈，这些反馈既不能保证更好的最终结果，也不能确定哪些未满足的要求应该指导下一次迭代。在根据Codex目标模式评估的所有三种设计中……

</details>

<details>
<summary><b>12. The Ethical Decision Head: Operationalizing Normative Ethics in Autonomous Vehicles via Reinforcement Learning from Human Feedback</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Thomas Mbrice、Ammar Ali、Sami Mian、Khai Hern Low、Eric Chen 等（共 8 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | CAS |
| **发布时间** | 2026-08-17T15:26:09Z |
| **关键词** | `Reasoning` · `Reinforcement Learning` · `Simulation` |
| **原文链接** | [http://arxiv.org/abs/2608.16710v1](http://arxiv.org/abs/2608.16710v1) |

**📝 摘要概括：**

> 随着自动驾驶汽车（ AV ）接近4级和5级运营能力[SAE International, 2018] ，其车载决策系统不仅必须处理安全关键的运动，还必须处理其随后的道德权重。本文详细介绍了道德决策主管（ EDH ） ，这是一个深度重组学习（ RL ）框架，将道德推理编码为可微分的奖励信号，使政治梯度代理能够学习道德标准……

</details>

<details>
<summary><b>13. Semantic Bandits: In-Context Exploration-Exploitation is Biased by Semantic Priors</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | David Eric Austin、Kaheer Suleman、Jackie Chi Kit Cheung |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-08-17T15:25:18Z |
| **关键词** | `LLM Agent` |
| **原文链接** | [http://arxiv.org/abs/2608.16707v1](http://arxiv.org/abs/2608.16707v1) |

**📝 摘要概括：**

> 在需要复杂的环境探索的环境中，大型语言模型（ LLM ）越来越多地被部署为决策代理。然而，现有的工作提出了LLM如何真正平衡勘探和开发的问题。总的来说，我们认为，使用语言来定义环境和奖励会引入不可避免的偏见，因为模型是在单词共现上训练的，这意味着……

</details>

<details>
<summary><b>14. Chronocooked: A Benchmark for Implicit Interval Timing in Reinforcement Learning Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Amrapali Pednekar、Alvaro Garrido-Perez、Yara Khaluf、Pieter Simoens |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-08-17T14:55:59Z |
| **关键词** | `Reinforcement Learning` · `Benchmark` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2608.16666v1](http://arxiv.org/abs/2608.16666v1) |

**📝 摘要概括：**

> 本文提出了Chronocooked ，这是一个强化学习（ RL ）基准套件，用于研究RL代理中的隐式间隔时间。套房的灵感来自Overcooked ，包括需要临时决策的烹饪场景。这项工作最终旨在强调将时间感知和时间处理整合到专为人类机器人交互和部署于时间依赖型人类社会的人工智能体中的必要性。

</details>

<details>
<summary><b>15. Orbit-Planner: Towards Latent World Models for On-Orbit Obstacle Avoidance of Satellite Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Zhijian Li、Chao Ren、Peijin Wang、Xian Sun |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT |
| **发布时间** | 2026-08-17T14:49:07Z |
| **关键词** | — |
| **原文链接** | [http://arxiv.org/abs/2608.16651v1](http://arxiv.org/abs/2608.16651v1) |

**📝 摘要概括：**

> 用于在轨导航任务的卫星代理需要使用有限的机载观测来预测碰撞风险。然而，传统的规划者通常依赖于预定义的地图和固定的环境假设，限制了它们在动态在轨场景中的适应性。优惠码可在https://github.com/ZhijianLi2003/Orbit_Planner上获得。

</details>

<details>
<summary><b>16. Reconstruction: A Blind Benchmark for Recovering Research Ideas from Pre-Publication Bibliographies</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Shaolong Chen、Yanlin Fei、Nazhou Liu、Xinmiao Yu、Lei Li 等（共 9 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-08-17T14:44:30Z |
| **关键词** | `Multi-Agent` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2608.16645v1](http://arxiv.org/abs/2608.16645v1) |

**📝 摘要概括：**

> 当只给出论文的出版前参考书目时，语言模型能否恢复已发表论文的真正研究理念？我们引入了重建，这是一个盲目的想法恢复基准，它保留了种子纸和所有同期或未来的文献，并要求模型提出假设，即独立的大型语言模型法官与坚持的地面真理想法相匹配。本草案报告了方案、防泄漏设备……

</details>

<details>
<summary><b>17. PDDLCoder: Agentic PDDL Generation for LLM-Assisted Symbolic Planning</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Veit Laule、Jiangtao Shuai、Manfred Hauswirth、Sonja Schimmler |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT |
| **发布时间** | 2026-08-17T14:34:56Z |
| **关键词** | `Agentic` · `Planning` · `Benchmark` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2608.16637v1](http://arxiv.org/abs/2608.16637v1) |

**📝 摘要概括：**

> LLM在长期规划中仍然不可靠，通常会产生逻辑不一致或不适用的计划。最近的混合方法将自然语言转换为规划域定义语言（ PDDL ） ，允许符号规划人员生成可验证的计划。我们的工作证明了代理PDDL生成用于规划的有效性，并为LLM辅助符号平台的未来研究建立了可重复的基准…

</details>

<details>
<summary><b>18. The Working Set of a Coding Agent: Coherence Debt in Repository-Scale Tasks</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Bardia Mohammadi、Lars Klein、Aman Chadha、Akhil Arora、Laurent Bindschaedler |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-08-17T14:30:41Z |
| **关键词** | `Memory` |
| **原文链接** | [http://arxiv.org/abs/2608.16630v1](http://arxiv.org/abs/2608.16630v1) |

**📝 摘要概括：**

> 存储库规模编码要求代理在有界上下文窗口内保持测试、导入、配置和迁移规则的一致性。我们将其建模为重建耦合事实图：在每次编辑时，所需的事实来自最近的上下文或参数记忆，而两者所涵盖的事实都不构成一致性债务。当客服代表写信时，线束应保留编辑所依赖的事实，并根据以下内容检查可用性……

</details>

<details>
<summary><b>19. Cost Scales with Change, Not Corpus Size: Incrementally Maintaining an Evolving Semantic Substrate</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Yusuke Takahashi、Kyle Wild、Asako Uraki |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-08-17T14:21:15Z |
| **关键词** | `Agentic` · `Retrieval` |
| **原文链接** | [http://arxiv.org/abs/2608.16621v1](http://arxiv.org/abs/2608.16621v1) |

**📝 摘要概括：**

> 检索-增强和代理问答系统越来越多地在查询时重新推导语料库的含义。简单地说，不是重新推导语料库在每个问题上的含义，而是在文档到达时完成一次工作，然后仅被查阅-一个编译器，而不是一个意义的解释器。结果支持保持而不是重复重建语义基础。

</details>

<details>
<summary><b>20. Physics of Agents: Statistical Mechanics Predicts Collective Behavior of AI Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Batu El、Jinhee Paeng、Fatih Dinc、Shiye Su、Mete Erdogan 等（共 10 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-08-17T13:41:24Z |
| **关键词** | `Multi-Agent` · `AI Agent` · `Reasoning` |
| **原文链接** | [http://arxiv.org/abs/2608.16578v1](http://arxiv.org/abs/2608.16578v1) |

**📝 摘要概括：**

> 人工智能代理越来越多地作为交互系统的一部分而不是孤立地运行。随着代理人交换信息并共同做出决策，他们的互动可以改善集体推理，但也可能产生放牧、两极分化或放大共同的偏见。总体而言，我们的研究结果表明，像其他复杂系统一样，人工智能代理的集体行为遵循紧凑和预测的动态规律。

</details>

## 🗄️ 历史归档

| 日期 | 论文数 | 报告链接 |
|------|--------|----------|
| 2026-08-18 | 20 篇 | [2026-08-18.md](daily/2026-08-18.md) |
| 2026-08-17 | 0 篇 | [2026-08-17.md](daily/2026-08-17.md) |
| 2026-08-16 | 0 篇 | [2026-08-16.md](daily/2026-08-16.md) |
| 2026-08-15 | 0 篇 | [2026-08-15.md](daily/2026-08-15.md) |
| 2026-08-14 | 20 篇 | [2026-08-14.md](daily/2026-08-14.md) |
| 2026-08-13 | 19 篇 | [2026-08-13.md](daily/2026-08-13.md) |
| 2026-08-12 | 13 篇 | [2026-08-12.md](daily/2026-08-12.md) |
| 2026-08-11 | 0 篇 | [2026-08-11.md](daily/2026-08-11.md) |
| 2026-08-10 | 0 篇 | [2026-08-10.md](daily/2026-08-10.md) |
| 2026-08-09 | 0 篇 | [2026-08-09.md](daily/2026-08-09.md) |
| 2026-08-08 | 0 篇 | [2026-08-08.md](daily/2026-08-08.md) |
| 2026-08-07 | 20 篇 | [2026-08-07.md](daily/2026-08-07.md) |
| 2026-08-05 | 20 篇 | [2026-08-05.md](daily/2026-08-05.md) |
| 2026-08-04 | 20 篇 | [2026-08-04.md](daily/2026-08-04.md) |
| 2026-08-03 | 0 篇 | [2026-08-03.md](daily/2026-08-03.md) |
| 2026-08-02 | 0 篇 | [2026-08-02.md](daily/2026-08-02.md) |
| 2026-08-01 | 0 篇 | [2026-08-01.md](daily/2026-08-01.md) |
| 2026-07-31 | 20 篇 | [2026-07-31.md](daily/2026-07-31.md) |
| 2026-07-30 | 16 篇 | [2026-07-30.md](daily/2026-07-30.md) |
| 2026-07-29 | 16 篇 | [2026-07-29.md](daily/2026-07-29.md) |
| 2026-07-28 | 14 篇 | [2026-07-28.md](daily/2026-07-28.md) |
| 2026-07-27 | 0 篇 | [2026-07-27.md](daily/2026-07-27.md) |
| 2026-07-26 | 0 篇 | [2026-07-26.md](daily/2026-07-26.md) |
| 2026-07-25 | 0 篇 | [2026-07-25.md](daily/2026-07-25.md) |
| 2026-07-24 | 17 篇 | [2026-07-24.md](daily/2026-07-24.md) |
| 2026-07-23 | 6 篇 | [2026-07-23.md](daily/2026-07-23.md) |
| 2026-07-22 | 20 篇 | [2026-07-22.md](daily/2026-07-22.md) |
| 2026-07-21 | 20 篇 | [2026-07-21.md](daily/2026-07-21.md) |
| 2026-07-20 | 0 篇 | [2026-07-20.md](daily/2026-07-20.md) |
| 2026-07-19 | 0 篇 | [2026-07-19.md](daily/2026-07-19.md) |

## 🏛️ 顶级机构覆盖范围

覆盖超过 **70 个**顶级 AI 机构，包括：

- **科技公司：** Microsoft、Google DeepMind、OpenAI、Anthropic、Meta AI、NVIDIA、Baidu、Alibaba、ByteDance 等
- **北美顶级大学：** MIT、Stanford、CMU、UC Berkeley、Harvard、Princeton、Cornell、Caltech 等
- **中国顶级大学/机构：** 清华大学、北京大学、浙大、上交大、复旦、中科院、MSRA 等
- **欧洲/其他：** Oxford、Cambridge、ETH Zurich、Mila、NUS、KAIST 等

---

*由 [clawBot DailyFindings](https://github.com/Jacob-biu/clawBot) 自动维护 | 最后更新：2026-08-18 22:21 UTC*
