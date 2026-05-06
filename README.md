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

## 📅 今日论文 — 2026-05-06　　[→ 查看完整报告](daily/2026-05-06.md)

> 共筛选出 **20** 篇论文 | 更新于 2026-05-06 02:34 UTC

### 论文目录与概要

| # | 论文标题 | 核心概要 | 来源机构 | 第一作者 |
|---|---------|---------|---------|--------|
| 1 | [Safety and accuracy follow different scaling laws in clinica…](http://arxiv.org/abs/2605.04039v1) | 临床LLM通常通过增加模型大小、上下文长度、检索复杂性或推理时间计算进行缩放，隐含期望更高的准确性意味着更安全的行为。这种假设在医学上是不完整的，一些自信、高风险或证据矛盾的错误可能比平均基准表现更重… | MIT、CAS | Sebastian Wind |
| 2 | [OpenSeeker-v2: Pushing the Limits of Search Agents with Info…](http://arxiv.org/abs/2605.04036v1) | 深度搜索能力已成为前沿大型语言模型（ LLM ）代理商不可或缺的能力，但其发展仍然由工业巨头主导。典型的行业配方涉及高度资源密集型的管道，涵盖预培训、持续预培训(CPT)、监督微调(SFT)和强化学习… | TRI | Yuwen Du |
| 3 | [Redefining AI Red Teaming in the Agentic Era: From Weeks to …](http://arxiv.org/abs/2605.04019v1) | 人工智能系统正在进入医疗保健、金融和国防等关键领域，但仍然容易受到对抗性攻击。虽然人工智能红色分组是主要的防御手段，但目前的方法迫使操作员采用手动、特定于库的工作流程。我们红队Meta Llama S… | CAS、TRI | Raja Sekhar Rao Dheekonda |
| 4 | [SymptomAI: Towards a Conversational AI Agent for Everyday Sy…](http://arxiv.org/abs/2605.04012v1) | 语言模型擅长对精心策划的医学案例研究和小插曲进行诊断评估，其表现与临床专业人员相当或优于临床专业人员。然而，现有的研究侧重于具有丰富背景的复杂场景，因此很难得出关于这些系统在日常生活中报告症状的患者的… | MIT、CAS | Joseph Breda |
| 5 | [Physics-Grounded Multi-Agent Architecture for Traceable, Ris…](http://arxiv.org/abs/2605.04003v1) | 自由形式的航空航天部件的高精度数控加工需要通过检查、模拟和工艺知识进行有界补偿。现成的大型语言模型（ LLM ）助理可以生成文本，但他们无法可靠地执行受风险约束的多步数字工作流程，也无法为高风险决策提… | HIT、TRI | Danny Hoang |
| 6 | [An Agent-Oriented Pluggable Experience-RAG Skill for Experie…](http://arxiv.org/abs/2605.03989v1) | 检索增强生成系统通常假设一个固定的检索管道在异构任务中就足够了，但事实类问题回答、多跳推理和科学验证表现出不同的检索偏好。我们展示了Experience-RAG Skill ，这是一个面向代理的可插拔… | TRI | Dutao Zhang |
| 7 | [From Intent to Execution: Composing Agentic Workflows with A…](http://arxiv.org/abs/2605.03986v1) | 使用AI代理构建的多代理系统(MAS)满足各种用户意图，可用于设计和构建一系列相关应用程序。但是，此类MAS的创建目前涉及手动组合计划、手动选择适当的代理以及手动创建执行图。我们表明，纳入批评代理进一… | TRI | Kishan Athrey |
| 8 | [MOSAIC-Bench: Measuring Compositional Vulnerability Inductio…](http://arxiv.org/abs/2605.03952v1) | 编码代理通常会通过每次提示的安全审查，但当他们的任务分解为常规工程票证时，他们会发送可利用的代码。挑战是结构性的：现有的安全一致性孤立地评估公开请求，使模型对恶意最终状态视而不见，这些恶意最终状态来自… | Google、OpenAI | Jonathan Steinberg |
| 9 | [A Benchmark for Interactive World Models with a Unified Acti…](http://arxiv.org/abs/2605.03941v1) | 实现通用人工智能（ AGI ）需要能够自适应学习和交互的代理，交互式世界模型为感知、推理和行动提供可扩展的环境。然而，目前的研究仍然缺乏大规模的数据集和统一的基准来评估它们的物理交互能力。iWorld… | MIT | Jianjie Fang |
| 10 | [QKVShare: Quantized KV-Cache Handoff for Multi-Agent On-Devi…](http://arxiv.org/abs/2605.03884v1) | 边缘设备上的多代理LLM系统需要有效地切换潜在环境，但今天的实际选择是昂贵的重新预充或全精度KV传输。我们研究QKVShare ，这是一个用于代理之间量化KV缓存切换的框架，它结合了令牌级混合精度分配… | Apple | Pratik Honavar |
| 11 | [Mechanical Conscience: A Mathematical Framework for Dependab…](http://arxiv.org/abs/2605.03847v1) | 分布式协作智能（ DCI ）包括边缘到边缘架构、联合学习、迁移学习和群体系统，创造了结构上不可避免的紧急风险的环境：个体代理的局部正确决策在不确定性下构成了全球不可接受的行为轨迹。现有的方法，如约束优… | HIT、TRI | Munkhdegerekh Batzorig |
| 12 | [SOAR: Real-Time Joint Optimization of Order Allocation and R…](http://arxiv.org/abs/2605.03842v1) | 机器人移动履行系统（ RMFS ）依靠移动机器人进行自动化库存运输、协调订单分配和机器人调度，以提高仓储效率。然而，由于严格的实时约束和多阶段决策的强耦合，优化RMFS具有挑战性。该代码可在https… | TRI | Yibang Tang |
| 13 | [TRACE: A Metrologically-Grounded Engineering Framework for T…](http://arxiv.org/abs/2605.03838v1) | 我们引入了TRACE ，这是一个跨领域的工程框架，适用于运营关键领域中值得信赖的代理人工智能。TRACE将四层参考架构与明确的经典-ML与TRACE相结合，将心肺复苏作为可信赖的人工智能工程中的一流设… | HIT、TRI | Serhii Zabolotnii |
| 14 | [Agentic-imodels: Evolving agentic interpretability tools via…](http://arxiv.org/abs/2605.03808v1) | 代理数据科学（ ADS ）系统正在迅速提高其自主分析、拟合和解释数据的能力，有可能朝着代理进行绝大多数数据科学工作的未来迈进。但是，当前的ADS系统使用的统计工具旨在由人类解释，而不是由代理解释。此外… | TRI | Chandan Singh |
| 15 | [ScrapMem: A Bio-inspired Framework for On-device Personalize…](http://arxiv.org/abs/2605.03804v1) | 由于高存储成本和多模式复杂性， LLM代理的长期个性化内存在资源有限的边缘设备上具有挑战性。为了解决这个问题，我们提出了ScrapMem ，这是一个将多模式数据集成到“剪贴簿页面”的框架。“Scrap… | MIT、CAS | Jiale Chang |
| 16 | [Say the Mission, Execute the Swarm: Agent-Enhanced LLM Reaso…](http://arxiv.org/abs/2605.03788v1) | 大型语言模型（ LLM ）越来越多地被探索为网络物理系统的高级推理引擎，但由于异构接口、有限的接地和长期运行的闭环执行需求，它们在实时无人机群管理中的应用仍然具有挑战性。本文提出了一个与任务无关的、代… | MIT、HIT | Andrea Iannoli |
| 17 | [What You Think is What You See: Driving Exploration in VLM A…](http://arxiv.org/abs/2605.03782v1) | 为了在部分可观察到的视觉环境中导航，最近的VLM代理越来越多地通过明确的CoT推理将世界建模能力内化到他们的策略中，使他们能够在行动之前模拟未来。然而，仅仅依靠被访状态的被动推理不足以完成稀疏奖励任务… | TRI | Haoxi Li |
| 18 | [MEMTIER: Tiered Memory Architecture and Retrieval Bottleneck…](http://arxiv.org/abs/2605.03675v1) | 长期运行的自主AI代理存在一个有据可查的内存一致性问题：由于现有平面文件内存系统中的四种复合故障模式，工具执行成功率在72小时操作窗口内降低了14个百分点。我们介绍了MEMTIER ，它是OpenCl… | HIT、TRI | Bronislav Sidik |
| 19 | [Agent-Based Modeling of Low-Emission Fertilizer Adoption for…](http://arxiv.org/abs/2605.03648v1) | 要了解奶牛养殖中的复杂系统动态，必须使用建模工具来捕捉农场的异质性、社会互动和累积环境影响。本研究提出了一个基于代理的建模（ ABM ）框架，用于在15年期间模拟295个爱尔兰奶牛场的氮管理和低排放肥… | MIT | Surya Jayakumar |
| 20 | [Multi-Agent Strategic Games with LLMs](http://arxiv.org/abs/2605.03604v1) | 本文询问是否可以使用大型语言模型（ LLM ）来研究冲突与合作的战略基础。我在重复的安全困境中引入法学硕士作为实验对象，并评估他们是否从国际关系理论中复制了规范机制。基于LLM的实验为探索理论机制提供… | TRI | Maxim Chupilkin |

### 论文详情

<details>
<summary><b>1. Safety and accuracy follow different scaling laws in clinical large language models</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Sebastian Wind、Tri-Thien Nguyen、Jeta Sopa、Mahshad Lotfinia、Sebastian Bickelhaup 等（共 12 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、CAS、TRI |
| **发布时间** | 2026-05-05T17:57:19Z |
| **关键词** | `Agentic` · `RAG` · `Retrieval` · `Benchmark` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2605.04039v1](http://arxiv.org/abs/2605.04039v1) |

**📝 摘要概括：**

> 临床LLM通常通过增加模型大小、上下文长度、检索复杂性或推理时间计算进行缩放，隐含期望更高的准确性意味着更安全的行为。这种假设在医学上是不完整的，一些自信、高风险或证据矛盾的错误可能比平均基准表现更重要。因此，临床法学硕士的安全性不是扩展的被动结果，而是一种部署方案……

</details>

<details>
<summary><b>2. OpenSeeker-v2: Pushing the Limits of Search Agents with Informative and High-Difficulty Trajectories</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Yuwen Du、Rui Ye、Shuo Tang、Keduan Huang、Xinyu Zhu 等（共 7 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-05-05T17:55:25Z |
| **关键词** | `Reinforcement Learning` · `Benchmark` · `Fine-tuning` |
| **原文链接** | [http://arxiv.org/abs/2605.04036v1](http://arxiv.org/abs/2605.04036v1) |

**📝 摘要概括：**

> 深度搜索能力已成为前沿大型语言模型（ LLM ）代理商不可或缺的能力，但其发展仍然由工业巨头主导。典型的行业配方涉及高度资源密集型的管道，涵盖预培训、持续预培训(CPT)、监督微调(SFT)和强化学习(RL)。我们很高兴开源OpenSeeker-v2模型权重，并分享我们简单的……

</details>

<details>
<summary><b>3. Redefining AI Red Teaming in the Agentic Era: From Weeks to Hours</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Raja Sekhar Rao Dheekonda、Will Pearce、Nick Landers |
| **所属机构** | （详见原文） |
| **顶级机构标签** | CAS、TRI |
| **发布时间** | 2026-05-05T17:43:52Z |
| **关键词** | `Multi-Agent` · `Agentic` · `Workflow` |
| **原文链接** | [http://arxiv.org/abs/2605.04019v1](http://arxiv.org/abs/2605.04019v1) |

**📝 摘要概括：**

> 人工智能系统正在进入医疗保健、金融和国防等关键领域，但仍然容易受到对抗性攻击。虽然人工智能红色分组是主要的防御手段，但目前的方法迫使操作员采用手动、特定于库的工作流程。我们红队Meta Llama Scout ，使用零人工开发的代码，达到85 ％的攻击成功率，严重程度高达1.0

</details>

<details>
<summary><b>4. SymptomAI: Towards a Conversational AI Agent for Everyday Symptom Assessment</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Joseph Breda、Fadi Yousif、Beszel Hawkins、Marinela Cotoi、Miao Liu 等（共 33 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、CAS、TRI |
| **发布时间** | 2026-05-05T17:36:12Z |
| **关键词** | `AI Agent` · `Agentic` |
| **原文链接** | [http://arxiv.org/abs/2605.04012v1](http://arxiv.org/abs/2605.04012v1) |

**📝 摘要概括：**

> 语言模型擅长对精心策划的医学案例研究和小插曲进行诊断评估，其表现与临床专业人员相当或优于临床专业人员。然而，现有的研究侧重于具有丰富背景的复杂场景，因此很难得出关于这些系统在日常生活中报告症状的患者的表现的结论。虽然受到自我报告的事实真相的限制，但这些结果表明了奉献精神的好处……

</details>

<details>
<summary><b>5. Physics-Grounded Multi-Agent Architecture for Traceable, Risk-Aware Human-AI Decision Support in Manufacturing</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Danny Hoang、Ryan Matthiessen、Christopher Miller、Nasir Mannan、Ruby ElKharboutly 等（共 8 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | HIT、TRI |
| **发布时间** | 2026-05-05T17:24:53Z |
| **关键词** | `Multi-Agent` · `Retrieval` · `Benchmark` · `Simulation` · `Workflow` |
| **原文链接** | [http://arxiv.org/abs/2605.04003v1](http://arxiv.org/abs/2605.04003v1) |

**📝 摘要概括：**

> 自由形式的航空航天部件的高精度数控加工需要通过检查、模拟和工艺知识进行有界补偿。现成的大型语言模型（ LLM ）助理可以生成文本，但他们无法可靠地执行受风险约束的多步数字工作流程，也无法为高风险决策提供可审计的来源。数字孪生假设研究表明， MAKA可以协调可追溯的候选薪酬……

</details>

<details>
<summary><b>6. An Agent-Oriented Pluggable Experience-RAG Skill for Experience-Driven Retrieval Strategy Orchestration</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Dutao Zhang、Tian Liao |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-05-05T17:10:25Z |
| **关键词** | `Reasoning` · `RAG` · `Retrieval` · `Memory` · `Workflow` |
| **原文链接** | [http://arxiv.org/abs/2605.03989v1](http://arxiv.org/abs/2605.03989v1) |

**📝 摘要概括：**

> 检索增强生成系统通常假设一个固定的检索管道在异构任务中就足够了，但事实类问题回答、多跳推理和科学验证表现出不同的检索偏好。我们展示了Experience-RAG Skill ，这是一个面向代理的可插拔检索编排层，位于代理和检索器池之间。结果表明，检索策略选择可以…

</details>

<details>
<summary><b>7. From Intent to Execution: Composing Agentic Workflows with Agent Recommendation</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Kishan Athrey、Ramin Pishehvar、Brian Riordan、Mahesh Viswanathan |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-05-05T17:08:26Z |
| **关键词** | `Multi-Agent` · `AI Agent` · `Agentic` · `Planning` · `Retrieval` |
| **原文链接** | [http://arxiv.org/abs/2605.03986v1](http://arxiv.org/abs/2605.03986v1) |

**📝 摘要概括：**

> 使用AI代理构建的多代理系统(MAS)满足各种用户意图，可用于设计和构建一系列相关应用程序。但是，此类MAS的创建目前涉及手动组合计划、手动选择适当的代理以及手动创建执行图。我们表明，纳入批评代理进一步提高了召回分数，证明了全面审查和修订……

</details>

<details>
<summary><b>8. MOSAIC-Bench: Measuring Compositional Vulnerability Induction in Coding Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Jonathan Steinberg、Oren Gal |
| **所属机构** | （详见原文） |
| **顶级机构标签** | Google、OpenAI、Anthropic |
| **发布时间** | 2026-05-05T16:38:23Z |
| **关键词** | `RAG` · `Benchmark` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2605.03952v1](http://arxiv.org/abs/2605.03952v1) |

**📝 摘要概括：**

> 编码代理通常会通过每次提示的安全审查，但当他们的任务分解为常规工程票证时，他们会发送可利用的代码。挑战是结构性的：现有的安全一致性孤立地评估公开请求，使模型对恶意最终状态视而不见，这些恶意最终状态来自对无害请求的顺序合规性。作为一种可部署但非自适应的缓解措施，将审稿人重新构建为对抗性的pentester……

</details>

<details>
<summary><b>9. A Benchmark for Interactive World Models with a Unified Action Generation Framework</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Jianjie Fang、Yingshan Lei、Qin Wan、Ziyou Wang、Yuchao Huang 等（共 11 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT |
| **发布时间** | 2026-05-05T16:30:03Z |
| **关键词** | `Reasoning` · `Benchmark` · `Evaluation` · `Memory` |
| **原文链接** | [http://arxiv.org/abs/2605.03941v1](http://arxiv.org/abs/2605.03941v1) |

**📝 摘要概括：**

> 实现通用人工智能（ AGI ）需要能够自适应学习和交互的代理，交互式世界模型为感知、推理和行动提供可扩展的环境。然而，目前的研究仍然缺乏大规模的数据集和统一的基准来评估它们的物理交互能力。iWorld-Bench模型排行榜可在iWorld-Bench.com上公开获得。

</details>

<details>
<summary><b>10. QKVShare: Quantized KV-Cache Handoff for Multi-Agent On-Device LLMs</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Pratik Honavar、Tejpratap GVSL |
| **所属机构** | （详见原文） |
| **顶级机构标签** | Apple |
| **发布时间** | 2026-05-05T15:44:29Z |
| **关键词** | `Multi-Agent` |
| **原文链接** | [http://arxiv.org/abs/2605.03884v1](http://arxiv.org/abs/2605.03884v1) |

**📝 摘要概括：**

> 边缘设备上的多代理LLM系统需要有效地切换潜在环境，但今天的实际选择是昂贵的重新预充或全精度KV传输。我们研究QKVShare ，这是一个用于代理之间量化KV缓存切换的框架，它结合了令牌级混合精度分配、自包含的CacheCard表示和HuggingFace兼容的缓存注入路径。这些结果将量化KV切换定位为专业……

</details>

<details>
<summary><b>11. Mechanical Conscience: A Mathematical Framework for Dependability of Machine Intelligenc</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Munkhdegerekh Batzorig、Purevbaatar Ganbold、Kyungbin Park、Pilkong Jeong、Kangbin |
| **所属机构** | （详见原文） |
| **顶级机构标签** | HIT、TRI |
| **发布时间** | 2026-05-05T15:14:02Z |
| **关键词** | `Multi-Agent` · `Reinforcement Learning` |
| **原文链接** | [http://arxiv.org/abs/2605.03847v1](http://arxiv.org/abs/2605.03847v1) |

**📝 摘要概括：**

> 分布式协作智能（ DCI ）包括边缘到边缘架构、联合学习、迁移学习和群体系统，创造了结构上不可避免的紧急风险的环境：个体代理的局部正确决策在不确定性下构成了全球不可接受的行为轨迹。现有的方法，如约束优化、安全强化学习和运行时保证……

</details>

<details>
<summary><b>12. SOAR: Real-Time Joint Optimization of Order Allocation and Robot Scheduling in Robotic Mobile Fulfillment Systems</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Yibang Tang、Yifan Yang、Jingyuan Wang、Junhua Chen、Zhen Zhao |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-05-05T15:09:32Z |
| **关键词** | `Reinforcement Learning` · `RAG` |
| **原文链接** | [http://arxiv.org/abs/2605.03842v1](http://arxiv.org/abs/2605.03842v1) |

**📝 摘要概括：**

> 机器人移动履行系统（ RMFS ）依靠移动机器人进行自动化库存运输、协调订单分配和机器人调度，以提高仓储效率。然而，由于严格的实时约束和多阶段决策的强耦合，优化RMFS具有挑战性。该代码可在https://github.com/200815147/SOAR上获得。

</details>

<details>
<summary><b>13. TRACE: A Metrologically-Grounded Engineering Framework for Trustworthy Agentic AI Systems in Operationally Critical Domains</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Serhii Zabolotnii |
| **所属机构** | （详见原文） |
| **顶级机构标签** | HIT、TRI |
| **发布时间** | 2026-05-05T15:05:00Z |
| **关键词** | `Agentic` |
| **原文链接** | [http://arxiv.org/abs/2605.03838v1](http://arxiv.org/abs/2605.03838v1) |

**📝 摘要概括：**

> 我们引入了TRACE ，这是一个跨领域的工程框架，适用于运营关键领域中值得信赖的代理人工智能。TRACE将四层参考架构与明确的经典-ML与TRACE相结合，将心肺复苏作为可信赖的人工智能工程中的一流设计原则。

</details>

<details>
<summary><b>14. Agentic-imodels: Evolving agentic interpretability tools via autoresearch</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Chandan Singh、Yan Shuo Tan、Weijia Xu、Zelalem Gero、Weiwei Yang 等（共 7 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-05-05T14:35:47Z |
| **关键词** | `Agentic` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2605.03808v1](http://arxiv.org/abs/2605.03808v1) |

**📝 摘要概括：**

> 代理数据科学（ ADS ）系统正在迅速提高其自主分析、拟合和解释数据的能力，有可能朝着代理进行绝大多数数据科学工作的未来迈进。但是，当前的ADS系统使用的统计工具旨在由人类解释，而不是由代理解释。此外，这些演进的模型改善了下游端到端广告，提高了Copil的性能……

</details>

<details>
<summary><b>15. ScrapMem: A Bio-inspired Framework for On-device Personalized Agent Memory via Optical Forgetting</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Jiale Chang、Yuxiang Ren |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、CAS |
| **发布时间** | 2026-05-05T14:30:30Z |
| **关键词** | `LLM Agent` · `RAG` · `Memory` |
| **原文链接** | [http://arxiv.org/abs/2605.03804v1](http://arxiv.org/abs/2605.03804v1) |

**📝 摘要概括：**

> 由于高存储成本和多模式复杂性， LLM代理的长期个性化内存在资源有限的边缘设备上具有挑战性。为了解决这个问题，我们提出了ScrapMem ，这是一个将多模式数据集成到“剪贴簿页面”的框架。“ScrapMem引入了Optical Forgetting ，这是一种光学压缩机制，可逐步降低旧内存的分辨率，降低存储成本，同时抑制低价值细节。ScrapM……

</details>

<details>
<summary><b>16. Say the Mission, Execute the Swarm: Agent-Enhanced LLM Reasoning in the Web-of-Drones</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Andrea Iannoli、Lorenzo Gigli、Luca Sciullo、Angelo Trotta、Marco Di Felice |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、HIT |
| **发布时间** | 2026-05-05T14:14:57Z |
| **关键词** | `Reasoning` · `Planning` · `Code Generation` · `Simulation` |
| **原文链接** | [http://arxiv.org/abs/2605.03788v1](http://arxiv.org/abs/2605.03788v1) |

**📝 摘要概括：**

> 大型语言模型（ LLM ）越来越多地被探索为网络物理系统的高级推理引擎，但由于异构接口、有限的接地和长期运行的闭环执行需求，它们在实时无人机群管理中的应用仍然具有挑战性。本文提出了一个与任务无关的、代理增强的无人机群控制LLM框架，其中用户用自然语言表达任务目标…

</details>

<details>
<summary><b>17. What You Think is What You See: Driving Exploration in VLM Agents via Visual-Linguistic Curiosity</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Haoxi Li、Qinglin Hou、Jianfei Ma、Jinxiang Lai、Tao Han 等（共 9 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-05-05T14:08:54Z |
| **关键词** | `Agentic` · `Reasoning` · `Reinforcement Learning` · `RAG` |
| **原文链接** | [http://arxiv.org/abs/2605.03782v1](http://arxiv.org/abs/2605.03782v1) |

**📝 摘要概括：**

> 为了在部分可观察到的视觉环境中导航，最近的VLM代理越来越多地通过明确的CoT推理将世界建模能力内化到他们的策略中，使他们能够在行动之前模拟未来。然而，仅仅依靠被访状态的被动推理不足以完成稀疏奖励任务，因为它缺乏积极揭示稳健概括所需的“已知未知”的认识动力。

</details>

<details>
<summary><b>18. MEMTIER: Tiered Memory Architecture and Retrieval Bottleneck Analysis for Long-Running Autonomous AI Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Bronislav Sidik、Lior Rokach |
| **所属机构** | （详见原文） |
| **顶级机构标签** | HIT、TRI |
| **发布时间** | 2026-05-05T12:14:10Z |
| **关键词** | `AI Agent` · `Reasoning` · `RAG` · `Retrieval` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2605.03675v1](http://arxiv.org/abs/2605.03675v1) |

**📝 摘要概括：**

> 长期运行的自主AI代理存在一个有据可查的内存一致性问题：由于现有平面文件内存系统中的四种复合故障模式，工具执行成功率在72小时操作窗口内降低了14个百分点。我们介绍了MEMTIER ，它是OpenClaw代理运行时的三方内存架构，引入了结构化的情节JSONL存储、五信号加权检索引擎、注意力属性……

</details>

<details>
<summary><b>19. Agent-Based Modeling of Low-Emission Fertilizer Adoption for Dairy Farm Decarbonisation using Empirical Farm Data</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Surya Jayakumar、Kieran Sullivan、John McLaughlin、Christine OMeara、Indrakshi Dey |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT |
| **发布时间** | 2026-05-05T11:25:03Z |
| **关键词** | `Simulation` |
| **原文链接** | [http://arxiv.org/abs/2605.03648v1](http://arxiv.org/abs/2605.03648v1) |

**📝 摘要概括：**

> 要了解奶牛养殖中的复杂系统动态，必须使用建模工具来捕捉农场的异质性、社会互动和累积环境影响。本研究提出了一个基于代理的建模（ ABM ）框架，用于在15年期间模拟295个爱尔兰奶牛场的氮管理和低排放肥料的采用。通过将脱碳视为一种社会技术扩散过程，而不是……

</details>

<details>
<summary><b>20. Multi-Agent Strategic Games with LLMs</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Maxim Chupilkin |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-05-05T10:28:17Z |
| **关键词** | `Multi-Agent` · `Reasoning` |
| **原文链接** | [http://arxiv.org/abs/2605.03604v1](http://arxiv.org/abs/2605.03604v1) |

**📝 摘要概括：**

> 本文询问是否可以使用大型语言模型（ LLM ）来研究冲突与合作的战略基础。我在重复的安全困境中引入法学硕士作为实验对象，并评估他们是否从国际关系理论中复制了规范机制。基于LLM的实验为探索理论机制提供了一种可扩展、透明和可复制的方法。

</details>

## 🗄️ 历史归档

| 日期 | 论文数 | 报告链接 |
|------|--------|----------|
| 2026-05-06 | 20 篇 | [2026-05-06.md](daily/2026-05-06.md) |
| 2026-05-05 | 20 篇 | [2026-05-05.md](daily/2026-05-05.md) |

## 🏛️ 顶级机构覆盖范围

覆盖超过 **70 个**顶级 AI 机构，包括：

- **科技公司：** Microsoft、Google DeepMind、OpenAI、Anthropic、Meta AI、NVIDIA、Baidu、Alibaba、ByteDance 等
- **北美顶级大学：** MIT、Stanford、CMU、UC Berkeley、Harvard、Princeton、Cornell、Caltech 等
- **中国顶级大学/机构：** 清华大学、北京大学、浙大、上交大、复旦、中科院、MSRA 等
- **欧洲/其他：** Oxford、Cambridge、ETH Zurich、Mila、NUS、KAIST 等

---

*由 [clawBot DailyFindings](https://github.com/Jacob-biu/clawBot) 自动维护 | 最后更新：2026-05-06 02:34 UTC*
