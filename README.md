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

## 📅 今日论文 — 2026-10-28　　[→ 查看完整报告](daily/2026-10-28.md)

> 共筛选出 **20** 篇论文 | 更新于 2026-10-28 00:59 UTC

### 论文目录与概要

| # | 论文标题 | 核心概要 | 来源机构 | 第一作者 |
|---|---------|---------|---------|--------|
| 1 | [Work Agents: Systems, Capabilities, and Optimization](http://arxiv.org/abs/2610.35845v1) | 随着基础模型从信息生成发展到数字工作执行，代理商越来越有能力跨工具、应用程序和工作流完成复杂的任务。然而，现有的研究缺乏对代理如何可靠地完成委派工作的统一观点。本文为理解、优化和评估工作代理提供了一个… | TRI | Zishan Xu |
| 2 | [I-HITL: Inalienable Human-in-the-Loop](http://arxiv.org/abs/2610.35835v1) | 人工监督是人工智能安全的支柱。它通常由人工循环（ HITL ）执行，该人工循环（ HITL ）批准人工智能代理采取的关键行动。我们展示了一个名为会签的原型I-HITL系统，该系统可以使用现成的消费者移… | HIT | Samuel Breckenridge |
| 3 | [Reva: Real-Time Vulnerability Detection through Contextual P…](http://arxiv.org/abs/2610.35829v1) | 发现漏洞后，修复漏洞的成本会更高。由于编码代理生成代码的速度快于开发人员的审核速度，软件需要第一道防线来实时筛选每个新功能。因此，法学硕士的内部表征编码了代理检测器通过推理获得的大部分内容。 | TRI | Amine Lbath |
| 4 | [FOCUS: Active Critic Learning for Long-Horizon Language Mode…](http://arxiv.org/abs/2610.35801v1) | 稀疏的结果奖励使长期语言模型代理很难将功劳分配给较早的操作。已知的批评者提供了中间状态的值估计，但这些估计可能不准确，而从轨迹内的点重复连续样本估计中间值会产生大量成本。52.4 ）。 | MIT | Zhengping Jiang |
| 5 | [A Unified Arena for LLM Agents across Diverse Eurogame](http://arxiv.org/abs/2610.35773v1) | 交互式环境提供了一种实用的方法来评估大型语言模型（ LLM ）代理，竞争游戏将这种评估扩展到由竞争目标和其他代理的选择形成的决策。然而，现有的评估仅限于单个游戏或执行框架，不清楚哪些竞争优势在各种环境… | MIT | Fengrui Zhang |
| 6 | [Free to Look, Free to Reason: Simple LLM Harnesses Outdiagno…](http://arxiv.org/abs/2610.35767v1) | 微服务故障的根本原因分析（ RCA ）吸引了许多LLM代理，他们的调查是通过标准操作程序、固定阶段和角色代理手工制作的。每种设计都根据自己的数据对少数基线进行评估，因此尚不清楚这种设计是否胜过让一个有… | CAS | Tingzhu Bi |
| 7 | [Preference-Guided Cooperation in Multi-Objective Multi-Agent…](http://arxiv.org/abs/2610.35736v1) | 多目标多智能体强化学习（ MOMARL ）同时解决智能体协调和客观权衡，同时优化整体系统性能。现有工作倾向于将多智能体合作和多目标优化视为学习问题的主要独立组成部分，除了在琐碎的情况下，这相当于过高的… | CAS、TRI | Qiyue Xia |
| 8 | [EvoRouter: Cost-Efficient Multi-Agent Routing via Insight-Gu…](http://arxiv.org/abs/2610.35690v1) | 使用多代理系统大规模服务Web查询需要联合配置大型语言模型、协作模式、代理计数、交互轮次和技能。然而，由此产生的配置空间组合增长，而稀疏执行奖励为相互依赖的规划决策提供有限的细粒度监督。我们的代码在h… | MIT | Yitao Xiao |
| 9 | [Provably Efficient Q-learning for Robust Reinforcement Learn…](http://arxiv.org/abs/2610.35656v1) | 基于马尔可夫决策过程（ MDP ）的标准强化学习（ RL ）算法容易受到模拟与真实差距的影响。为了解决这个问题，已经提出了基于鲁棒MDP （ RMDP ）的分布式鲁棒RL算法，以确保代理可以在现实环境… | TRI | Yuchen Jiao |
| 10 | [From Language to Drives: A Multimodal Framework for Aligning…](http://arxiv.org/abs/2610.35629v1) | 这项工作探索了一种多模态方法，通过使用大型语言模型作为文化推动者，使开放式学习自主机器人的行为与人类目的保持一致。虽然自主机器人可以通过与环境的交互来产生自己的技能和目标，但它们通常缺乏确保这些技能和… | HIT | Diana Cerdas-Vargas |
| 11 | [Evolve on Graph: Self-Evolving Knowledge Graph Reasoning wit…](http://arxiv.org/abs/2610.35598v1) | 知识图（ KG ）为使用大型语言模型（ LLM ）进行多跳事实推理提供了可靠的外部知识，但金融和行业等现实领域的大多数KG缺乏问答（ QA ）注释。如果没有这样的注释，现有的方法很难改进LLM图推理：… | TRI | Zongyuan Sun |
| 12 | [KAPPA: Checking the Proofs in Statistics Papers with Lean 4 …](http://arxiv.org/abs/2610.35596v1) | 统计理论中的论文建立在很长一段时间的证明上，很少有读者逐行检查。我们展示了由Claude Code运行的组织语言模型代理的开源软件KAPPA （带有校对助手的校对文件代理工具包） ，将LaTeX论文的… | MIT | Zihua She |
| 13 | [Infinity Machine: a self-improving AI agent for research](http://arxiv.org/abs/2610.35579v1) | 我们展示了Infinity Machine ，这是一种自我改进的人工智能代理，我们使用它来研究程序或数据可以检查答案的问题。每个候选解决方案都由一个完整的工具使用代理生成，该代理在新的沙箱中工作长达一… | NTU、TRI | Harish Santhanalakshmi Ganesan |
| 14 | [The Agent in the Middle: How AI-Mediated Access Reshapes Web…](http://arxiv.org/abs/2610.35541v1) | Web服务越来越多地暴露后端接口，允许用户将任务委托给AI代理，这些代理无需导航网站即可直接调用服务操作。这种转变改变了利用现有Web漏洞的方式。我们的研究提供了一个系统的实证说明，说明代理介导的访问… | MIT、HIT | Ruozhao Yang |
| 15 | [Governing Enterprise AI Traffic at Scale: Design and Operati…](http://arxiv.org/abs/2610.35509v1) | 大型组织同时使用来自多个供应商的大型语言模型(LLM) ，每个供应商都有自己的API方言、凭据模型、流协议和定价。这种异构性直接集成，导致凭证蔓延、格式锁定、无限支出和不一致的治理。我们报告架构、政策… | HIT、CAS | Mithun Sasidharan |
| 16 | [Test-Time Confidence Adaptation under RL-Induced Trajectory …](http://arxiv.org/abs/2610.35500v1) | 通过利用大型语言模型（ LLM ）推理过程中的丰富信号，基于轨迹的置信度估计已显示出大型语言模型（ LLM ）的良好性能。然而，我们发现，这种置信度估计量在代理强化学习（ Agentic RL ）后会… | TRI | Zhenzhen Ren |
| 17 | [When Fine-Grained Credit Assignment Helps and Hurts: Multimo…](http://arxiv.org/abs/2610.35497v1) | 强化学习（ RL ）已显示出培训多式联运代理推理和使用工具的前景。然而，细粒度学分分配何时改善学习以及何时未能改善任务绩效仍不清楚。我们的分析揭示了教师-学生分歧和梯度幅度的差异，并暗示了信息信号在长… | MIT | Lei Zhao |
| 18 | [ShutdownMod: Turning Any Trajectory into a Shutdown Evaluati…](http://arxiv.org/abs/2610.35486v1) | 理论和实验表明，有能力的人工智能代理可以抵制关机。现有的关闭评估内容丰富，但覆盖范围有限，并且容易受到评估意识的影响。我们在https://github.com/prmbiy/ShutdownMod上… | MIT | Param Biyani |
| 19 | [Multi-Horizon Future Discovery for Physics-Informed Explorat…](http://arxiv.org/abs/2610.35468v1) | 在物理控制环境中的探索要求代理识别其后果揭示了潜在动态的先前未探索的方面的行动。然而，许多内在动机方法依赖于即时预测错误、状态新颖性或局部物理变化，这可能会忽略跨越延伸时间视野出现的信息性结果。与IC… | DeepMind、TRI | Shuwei Wang |
| 20 | [Beyond Federated Learning: Decentralized Agentic Systems for…](http://arxiv.org/abs/2610.35453v1) | 临床专业知识本质上是分布式的：它并不存在于任何单一的数据集或机构中，而是存在于数千名临床医生在不同患者群体、资源限制和不断变化的治疗方案中积累的推理经验中。然而，当前扩展医疗人工智能的方法，从集中式大… | HIT、TRI | Haoyuan Li |

### 论文详情

<details>
<summary><b>1. Work Agents: Systems, Capabilities, and Optimization</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Zishan Xu、Enjun Du、Mingqi Gao、Cheng Yang、Junhao Shen 等（共 16 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-10-26T17:56:21Z |
| **关键词** | `Evaluation` · `Workflow` |
| **原文链接** | [http://arxiv.org/abs/2610.35845v1](http://arxiv.org/abs/2610.35845v1) |

**📝 摘要概括：**

> 随着基础模型从信息生成发展到数字工作执行，代理商越来越有能力跨工具、应用程序和工作流完成复杂的任务。然而，现有的研究缺乏对代理如何可靠地完成委派工作的统一观点。本文为理解、优化和评估工作代理提供了一个统一的框架，支持开发能够提供…

</details>

<details>
<summary><b>2. I-HITL: Inalienable Human-in-the-Loop</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Samuel Breckenridge、Dani Vilardell、Wenhao Wang、Fan Zhang、Ari Juels |
| **所属机构** | （详见原文） |
| **顶级机构标签** | HIT |
| **发布时间** | 2026-10-26T17:52:14Z |
| **关键词** | `AI Agent` · `Agentic` |
| **原文链接** | [http://arxiv.org/abs/2610.35835v1](http://arxiv.org/abs/2610.35835v1) |

**📝 摘要概括：**

> 人工监督是人工智能安全的支柱。它通常由人工循环（ HITL ）执行，该人工循环（ HITL ）批准人工智能代理采取的关键行动。我们展示了一个名为会签的原型I-HITL系统，该系统可以使用现成的消费者移动设备插入并加强现有的HITL系统。

</details>

<details>
<summary><b>3. Reva: Real-Time Vulnerability Detection through Contextual Probing of Large Language Models</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Amine Lbath、Massih-Reza Amini |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-10-26T17:50:09Z |
| **关键词** | `LLM Agent` · `Agentic` · `Reasoning` · `RAG` |
| **原文链接** | [http://arxiv.org/abs/2610.35829v1](http://arxiv.org/abs/2610.35829v1) |

**📝 摘要概括：**

> 发现漏洞后，修复漏洞的成本会更高。由于编码代理生成代码的速度快于开发人员的审核速度，软件需要第一道防线来实时筛选每个新功能。因此，法学硕士的内部表征编码了代理检测器通过推理获得的大部分内容。

</details>

<details>
<summary><b>4. FOCUS: Active Critic Learning for Long-Horizon Language Model Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Zhengping Jiang、William Jurayj、Liaoyaqi Wang、Chunsheng Zuo、Anqi Liu 等（共 6 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT |
| **发布时间** | 2026-10-26T17:34:47Z |
| **关键词** | `Agentic` · `Reasoning` · `Reinforcement Learning` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2610.35801v1](http://arxiv.org/abs/2610.35801v1) |

**📝 摘要概括：**

> 稀疏的结果奖励使长期语言模型代理很难将功劳分配给较早的操作。已知的批评者提供了中间状态的值估计，但这些估计可能不准确，而从轨迹内的点重复连续样本估计中间值会产生大量成本。52.4 ）。

</details>

<details>
<summary><b>5. A Unified Arena for LLM Agents across Diverse Eurogame</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Fengrui Zhang、Xiang Li、Ruomeng Ding、Jiayi Yuan、Yuchen Huang 等（共 9 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT |
| **发布时间** | 2026-10-26T17:14:22Z |
| **关键词** | `LLM Agent` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2610.35773v1](http://arxiv.org/abs/2610.35773v1) |

**📝 摘要概括：**

> 交互式环境提供了一种实用的方法来评估大型语言模型（ LLM ）代理，竞争游戏将这种评估扩展到由竞争目标和其他代理的选择形成的决策。然而，现有的评估仅限于单个游戏或执行框架，不清楚哪些竞争优势在各种环境中持续存在。总之，研究结果支持通过竞争对手来评估完整的座席配置……

</details>

<details>
<summary><b>6. Free to Look, Free to Reason: Simple LLM Harnesses Outdiagnose Hand-Crafted Root Cause Analysis Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Tingzhu Bi、Xun Zhang、Jinglin Li、Ping Wang、Meng Ma |
| **所属机构** | （详见原文） |
| **顶级机构标签** | CAS |
| **发布时间** | 2026-10-26T17:12:02Z |
| **关键词** | `LLM Agent` · `Reasoning` |
| **原文链接** | [http://arxiv.org/abs/2610.35767v1](http://arxiv.org/abs/2610.35767v1) |

**📝 摘要概括：**

> 微服务故障的根本原因分析（ RCA ）吸引了许多LLM代理，他们的调查是通过标准操作程序、固定阶段和角色代理手工制作的。每种设计都根据自己的数据对少数基线进行评估，因此尚不清楚这种设计是否胜过让一个有能力的模型自己进行调查。在比最佳非LLM方法更准确的运行中，每个Pareto-最优运行的成本或时间都使用简单的harne……

</details>

<details>
<summary><b>7. Preference-Guided Cooperation in Multi-Objective Multi-Agent Reinforcement Learning</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Qiyue Xia、J. Michael Herrmann |
| **所属机构** | （详见原文） |
| **顶级机构标签** | CAS、TRI |
| **发布时间** | 2026-10-26T16:53:25Z |
| **关键词** | `Multi-Agent` · `Reinforcement Learning` |
| **原文链接** | [http://arxiv.org/abs/2610.35736v1](http://arxiv.org/abs/2610.35736v1) |

**📝 摘要概括：**

> 多目标多智能体强化学习（ MOMARL ）同时解决智能体协调和客观权衡，同时优化整体系统性能。现有工作倾向于将多智能体合作和多目标优化视为学习问题的主要独立组成部分，除了在琐碎的情况下，这相当于过高的复杂性。在多目标多粒子环境下的实验

</details>

<details>
<summary><b>8. EvoRouter: Cost-Efficient Multi-Agent Routing via Insight-Guided On-Policy Distillation</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Yitao Xiao、Xu Zhang、Ye Cheng、Shaoyong Guo、Yan Sun 等（共 9 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT |
| **发布时间** | 2026-10-26T16:21:00Z |
| **关键词** | `Multi-Agent` · `Planning` · `Reinforcement Learning` · `RAG` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2610.35690v1](http://arxiv.org/abs/2610.35690v1) |

**📝 摘要概括：**

> 使用多代理系统大规模服务Web查询需要联合配置大型语言模型、协作模式、代理计数、交互轮次和技能。然而，由此产生的配置空间组合增长，而稀疏执行奖励为相互依赖的规划决策提供有限的细粒度监督。我们的代码在https://github.com/CenYangtze/EvoRouter上开源。

</details>

<details>
<summary><b>9. Provably Efficient Q-learning for Robust Reinforcement Learning</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Yuchen Jiao、Gen Li |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-10-26T16:03:25Z |
| **关键词** | `Reinforcement Learning` |
| **原文链接** | [http://arxiv.org/abs/2610.35656v1](http://arxiv.org/abs/2610.35656v1) |

**📝 摘要概括：**

> 基于马尔可夫决策过程（ MDP ）的标准强化学习（ RL ）算法容易受到模拟与真实差距的影响。为了解决这个问题，已经提出了基于鲁棒MDP （ RMDP ）的分布式鲁棒RL算法，以确保代理可以在现实环境中对不可预测的条件下可靠地执行。此外，它实现了对现有界限的显着改进。

</details>

<details>
<summary><b>10. From Language to Drives: A Multimodal Framework for Aligning Autonomous Robots with Human Purposes</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Diana Cerdas-Vargas、Alejandro Romero、Richard J. Duro |
| **所属机构** | （详见原文） |
| **顶级机构标签** | HIT |
| **发布时间** | 2026-10-26T15:40:38Z |
| **关键词** | `Simulation` |
| **原文链接** | [http://arxiv.org/abs/2610.35629v1](http://arxiv.org/abs/2610.35629v1) |

**📝 摘要概括：**

> 这项工作探索了一种多模态方法，通过使用大型语言模型作为文化推动者，使开放式学习自主机器人的行为与人类目的保持一致。虽然自主机器人可以通过与环境的交互来产生自己的技能和目标，但它们通常缺乏确保这些技能和目标与人类用户保持相关性和一致性的机制。模拟实验和物理实验……

</details>

<details>
<summary><b>11. Evolve on Graph: Self-Evolving Knowledge Graph Reasoning without Question Annotations</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Zongyuan Sun、Shuai Zhao、Ke Shu、Ziyue Zhu、Shangyang Wu 等（共 11 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-10-26T15:23:04Z |
| **关键词** | `Reasoning` · `Reinforcement Learning` · `Retrieval` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2610.35598v1](http://arxiv.org/abs/2610.35598v1) |

**📝 摘要概括：**

> 知识图（ KG ）为使用大型语言模型（ LLM ）进行多跳事实推理提供了可靠的外部知识，但金融和行业等现实领域的大多数KG缺乏问答（ QA ）注释。如果没有这样的注释，现有的方法很难改进LLM图推理：无需培训的代理无法通过交互来改进他们的探索；强化学习（ RL ）代理依赖于QA数据注释……

</details>

<details>
<summary><b>12. KAPPA: Checking the Proofs in Statistics Papers with Lean 4 and Language Model Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Zihua She、Xiao Wang |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT |
| **发布时间** | 2026-10-26T15:22:15Z |
| **关键词** | — |
| **原文链接** | [http://arxiv.org/abs/2610.35596v1](http://arxiv.org/abs/2610.35596v1) |

**📝 摘要概括：**

> 统计理论中的论文建立在很长一段时间的证明上，很少有读者逐行检查。我们展示了由Claude Code运行的组织语言模型代理的开源软件KAPPA （带有校对助手的校对文件代理工具包） ，将LaTeX论文的证明翻译成带有Mathlib库的校对助手Lean 4 ，并在那里按结果进行检查。直接给定相同的论文，相同的语言模型起作用……

</details>

<details>
<summary><b>13. Infinity Machine: a self-improving AI agent for research</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Harish Santhanalakshmi Ganesan |
| **所属机构** | （详见原文） |
| **顶级机构标签** | NTU、TRI |
| **发布时间** | 2026-10-26T15:11:26Z |
| **关键词** | `AI Agent` |
| **原文链接** | [http://arxiv.org/abs/2610.35579v1](http://arxiv.org/abs/2610.35579v1) |

**📝 摘要概括：**

> 我们展示了Infinity Machine ，这是一种自我改进的人工智能代理，我们使用它来研究程序或数据可以检查答案的问题。每个候选解决方案都由一个完整的工具使用代理生成，该代理在新的沙箱中工作长达一个小时；提议者只看到公共分数，而私有拆分决定什么是重要的。我们仔细报告故障：一个自我衍生的线束生成因成本而被拒绝，提议者博弈宽松……

</details>

<details>
<summary><b>14. The Agent in the Middle: How AI-Mediated Access Reshapes Web Vulnerability Exploitation</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Ruozhao Yang、Jiongchi Yu、Ming Hu、Xiaofei Xie |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、HIT、CAS |
| **发布时间** | 2026-10-26T14:53:22Z |
| **关键词** | `AI Agent` · `Benchmark` · `Workflow` |
| **原文链接** | [http://arxiv.org/abs/2610.35541v1](http://arxiv.org/abs/2610.35541v1) |

**📝 摘要概括：**

> Web服务越来越多地暴露后端接口，允许用户将任务委托给AI代理，这些代理无需导航网站即可直接调用服务操作。这种转变改变了利用现有Web漏洞的方式。我们的研究提供了一个系统的实证说明，说明代理介导的访问如何重塑现有的Web漏洞，将未来的Web架构设计建立在测量的安全结果和权衡之间。

</details>

<details>
<summary><b>15. Governing Enterprise AI Traffic at Scale: Design and Operation of a Policy-Driven, Multi-Vendor LLM Gateway on Envoy</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Mithun Sasidharan、Srinivasan Manoharan、Rupesh Thakur、Abhinav TK、Ashwin Hegde 等（共 6 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | HIT、CAS |
| **发布时间** | 2026-10-26T14:33:48Z |
| **关键词** | `Benchmark` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2610.35509v1](http://arxiv.org/abs/2610.35509v1) |

**📝 摘要概括：**

> 大型组织同时使用来自多个供应商的大型语言模型(LLM) ，每个供应商都有自己的API方言、凭据模型、流协议和定价。这种异构性直接集成，导致凭证蔓延、格式锁定、无限支出和不一致的治理。我们报告架构、政策模式、评估和经验教训。

</details>

<details>
<summary><b>16. Test-Time Confidence Adaptation under RL-Induced Trajectory Shift</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Zhenzhen Ren、Xiaoqing Zhang、GuoBiao Li、Bowen Fang、Yanxi Wang 等（共 7 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-10-26T14:27:41Z |
| **关键词** | `Agentic` · `Reasoning` · `Reinforcement Learning` · `RAG` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2610.35500v1](http://arxiv.org/abs/2610.35500v1) |

**📝 摘要概括：**

> 通过利用大型语言模型（ LLM ）推理过程中的丰富信号，基于轨迹的置信度估计已显示出大型语言模型（ LLM ）的良好性能。然而，我们发现，这种置信度估计量在代理强化学习（ Agentic RL ）后会大大降低，因为它会导致推理轨迹的重大转变。在四个QA基准中， StaR-TTA的平均AUROC为\ (0.721\) ，并具有一致的即兴性…

</details>

<details>
<summary><b>17. When Fine-Grained Credit Assignment Helps and Hurts: Multimodal Agentic Reinforcement Learning through Video Editing</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Lei Zhao、Zongheng Cao、Xinyu Hu |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT |
| **发布时间** | 2026-10-26T14:25:40Z |
| **关键词** | `Agentic` · `Reasoning` · `Planning` · `Reinforcement Learning` · `RAG` |
| **原文链接** | [http://arxiv.org/abs/2610.35497v1](http://arxiv.org/abs/2610.35497v1) |

**📝 摘要概括：**

> 强化学习（ RL ）已显示出培训多式联运代理推理和使用工具的前景。然而，细粒度学分分配何时改善学习以及何时未能改善任务绩效仍不清楚。我们的分析揭示了教师-学生分歧和梯度幅度的差异，并暗示了信息信号在长轨道上可能被稀释。

</details>

<details>
<summary><b>18. ShutdownMod: Turning Any Trajectory into a Shutdown Evaluation</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Param Biyani、Sebastien Luyasu、Cedric Potvliege、Divij Chawla、Elliott Thornley 等（共 6 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT |
| **发布时间** | 2026-10-26T14:14:45Z |
| **关键词** | `LLM Agent` · `AI Agent` · `RAG` · `Benchmark` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2610.35486v1](http://arxiv.org/abs/2610.35486v1) |

**📝 摘要概括：**

> 理论和实验表明，有能力的人工智能代理可以抵制关机。现有的关闭评估内容丰富，但覆盖范围有限，并且容易受到评估意识的影响。我们在https://github.com/prmbiy/ShutdownMod上发布我们的代码库。

</details>

<details>
<summary><b>19. Multi-Horizon Future Discovery for Physics-Informed Exploration</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Shuwei Wang、Qiang Guan、Brian Qiu、Haoxiang Huang、Haoxi Wang 等（共 8 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | DeepMind、TRI |
| **发布时间** | 2026-10-26T14:01:10Z |
| **关键词** | `RAG` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2610.35468v1](http://arxiv.org/abs/2610.35468v1) |

**📝 摘要概括：**

> 在物理控制环境中的探索要求代理识别其后果揭示了潜在动态的先前未探索的方面的行动。然而，许多内在动机方法依赖于即时预测错误、状态新颖性或局部物理变化，这可能会忽略跨越延伸时间视野出现的信息性结果。与ICM、RIDE、E3B、Plan2Explore和一步Hamiltonian进行比较……

</details>

<details>
<summary><b>20. Beyond Federated Learning: Decentralized Agentic Systems for Self-Evolving Clinical Intelligence</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Haoyuan Li、Mathias Funk、Aaqib Saeed |
| **所属机构** | （详见原文） |
| **顶级机构标签** | HIT、TRI |
| **发布时间** | 2026-10-26T13:50:33Z |
| **关键词** | `AI Agent` · `Agentic` · `Reasoning` · `RAG` |
| **原文链接** | [http://arxiv.org/abs/2610.35453v1](http://arxiv.org/abs/2610.35453v1) |

**📝 摘要概括：**

> 临床专业知识本质上是分布式的：它并不存在于任何单一的数据集或机构中，而是存在于数千名临床医生在不同患者群体、资源限制和不断变化的治疗方案中积累的推理经验中。然而，当前扩展医疗人工智能的方法，从集中式大型语言模型到联合学习，仍然锚定在以数据为中心的范式上，将知识视为静态的。

</details>

## 🗄️ 历史归档

| 日期 | 论文数 | 报告链接 |
|------|--------|----------|
| 2026-10-28 | 20 篇 | [2026-10-28.md](daily/2026-10-28.md) |
| 2026-10-27 | 0 篇 | [2026-10-27.md](daily/2026-10-27.md) |
| 2026-10-25 | 0 篇 | [2026-10-25.md](daily/2026-10-25.md) |
| 2026-10-24 | 0 篇 | [2026-10-24.md](daily/2026-10-24.md) |
| 2026-10-23 | 20 篇 | [2026-10-23.md](daily/2026-10-23.md) |
| 2026-10-22 | 20 篇 | [2026-10-22.md](daily/2026-10-22.md) |
| 2026-10-21 | 20 篇 | [2026-10-21.md](daily/2026-10-21.md) |
| 2026-10-20 | 0 篇 | [2026-10-20.md](daily/2026-10-20.md) |
| 2026-10-18 | 0 篇 | [2026-10-18.md](daily/2026-10-18.md) |
| 2026-10-17 | 0 篇 | [2026-10-17.md](daily/2026-10-17.md) |
| 2026-10-16 | 8 篇 | [2026-10-16.md](daily/2026-10-16.md) |
| 2026-10-15 | 20 篇 | [2026-10-15.md](daily/2026-10-15.md) |
| 2026-10-14 | 0 篇 | [2026-10-14.md](daily/2026-10-14.md) |
| 2026-10-13 | 0 篇 | [2026-10-13.md](daily/2026-10-13.md) |
| 2026-10-12 | 0 篇 | [2026-10-12.md](daily/2026-10-12.md) |
| 2026-10-11 | 0 篇 | [2026-10-11.md](daily/2026-10-11.md) |
| 2026-10-10 | 20 篇 | [2026-10-10.md](daily/2026-10-10.md) |
| 2026-10-09 | 20 篇 | [2026-10-09.md](daily/2026-10-09.md) |
| 2026-10-08 | 20 篇 | [2026-10-08.md](daily/2026-10-08.md) |
| 2026-10-07 | 20 篇 | [2026-10-07.md](daily/2026-10-07.md) |
| 2026-10-06 | 0 篇 | [2026-10-06.md](daily/2026-10-06.md) |
| 2026-10-05 | 0 篇 | [2026-10-05.md](daily/2026-10-05.md) |
| 2026-10-04 | 0 篇 | [2026-10-04.md](daily/2026-10-04.md) |
| 2026-10-03 | 20 篇 | [2026-10-03.md](daily/2026-10-03.md) |
| 2026-10-02 | 15 篇 | [2026-10-02.md](daily/2026-10-02.md) |
| 2026-10-01 | 20 篇 | [2026-10-01.md](daily/2026-10-01.md) |
| 2026-09-30 | 8 篇 | [2026-09-30.md](daily/2026-09-30.md) |
| 2026-09-29 | 0 篇 | [2026-09-29.md](daily/2026-09-29.md) |
| 2026-09-15 | 16 篇 | [2026-09-15.md](daily/2026-09-15.md) |
| 2026-09-13 | 0 篇 | [2026-09-13.md](daily/2026-09-13.md) |

## 🏛️ 顶级机构覆盖范围

覆盖超过 **70 个**顶级 AI 机构，包括：

- **科技公司：** Microsoft、Google DeepMind、OpenAI、Anthropic、Meta AI、NVIDIA、Baidu、Alibaba、ByteDance 等
- **北美顶级大学：** MIT、Stanford、CMU、UC Berkeley、Harvard、Princeton、Cornell、Caltech 等
- **中国顶级大学/机构：** 清华大学、北京大学、浙大、上交大、复旦、中科院、MSRA 等
- **欧洲/其他：** Oxford、Cambridge、ETH Zurich、Mila、NUS、KAIST 等

---

*由 [clawBot DailyFindings](https://github.com/Jacob-biu/clawBot) 自动维护 | 最后更新：2026-10-28 00:59 UTC*
