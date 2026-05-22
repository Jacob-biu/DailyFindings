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

## 📅 今日论文 — 2026-05-22　　[→ 查看完整报告](daily/2026-05-22.md)

> 共筛选出 **20** 篇论文 | 更新于 2026-05-22 22:58 UTC

### 论文目录与概要

| # | 论文标题 | 核心概要 | 来源机构 | 第一作者 |
|---|---------|---------|---------|--------|
| 1 | [Remember to be Curious: Episodic Context and Persistent Worl…](http://arxiv.org/abs/2605.22814v1) | 探索是在稀疏奖励的长期任务中学习有用行为的先决条件，特别是在3D环境中。好奇心驱动的强化学习通过代理对世界的预测模型与现实之间的不匹配所带来的内在奖励来解决这个问题。请访问https://recuri… | Apple、TRI | Lily Goli |
| 2 | [MOSS: Self-Evolution through Source-Level Rewriting in Auton…](http://arxiv.org/abs/2605.22794v1) | 自主代理系统在部署后基本上是静态的：它们不会从用户交互中学习，并且反复出现的故障会持续存在，直到下一次人为驱动的更新发布修复程序。作为回应，出现了自我进化的代理，但所有代理都将进化局限于可文本变更的工… | TRI | Qianshu Cai |
| 3 | [LCGuard: Latent Communication Guard for Safe KV Sharing in M…](http://arxiv.org/abs/2605.22786v1) | 基于大型语言模型（ LLM ）的多智能体系统越来越依赖于中间通信来协调复杂的任务。虽然大多数现有系统通过自然语言进行通信，但最近的工作表明，潜伏通信，特别是通过变压器键值（ KV ）缓存，可以提高效率… | MIT | Sadia Asif |
| 4 | [DeltaBox: Scaling Stateful AI Agents with Millisecond-Level …](http://arxiv.org/abs/2605.22781v1) | 基于LLM的AI代理需要高频状态探索（例如，测试时树搜索和强化学习） ，依赖于完整沙箱状态的快速检查点和回滚（ C/R ） ，包括文件和进程状态（例如，内存、上下文等）。现有机制复制整个状态，导致每个… | Mila、TRI | Yunpeng Dong |
| 5 | [Deep Reinforcement Learning for Flexible Job Shop Scheduling…](http://arxiv.org/abs/2605.22773v1) | 灵活作业车间调度问题（ FJSP ）是向机器分配一组作业的最佳方式。FJSP仍然存在两个主要挑战：未来工作的不可预测性和问题的组合复杂性，这使得传统的混合整数线性规划求解器难以解决问题。我们将我们的\… | MIT、TRI | Yu Tang |
| 6 | [Advancing Mathematics Research with AI-Driven Formal Proof S…](http://arxiv.org/abs/2605.22763v1) | 大型语言模型（ LLM ）越来越擅长数学推理，但它们的不可靠性限制了它们在数学研究中的实用性。缓解措施是使用LLM以精益等语言生成正式证明。这些发现展示了人工智能辅助正式证明搜索的强大功能，并阐明了实… | MIT、NTU | George Tsoukalas |
| 7 | [Towards a General Intelligence and Interface for Wearable He…](http://arxiv.org/abs/2605.22759v1) | 虽然无处不在的可穿戴传感器可以捕捉到丰富的行为和生理信息，但将这些信号有效地转化为个性化的健康见解具有挑战性。具体而言，由于个体基线健康、生理和生活方式因素的高表型多样性和变化，将低水平传感器数据转换… | MIT、TRI | Girish Narayanswamy |
| 8 | [HarnessAPI: A Skill-First Framework for Unified Streaming AP…](http://arxiv.org/abs/2605.22733v1) | 如今，作为LLM工具部署的每个Python函数都必须以两种形式存在：面向人的客户端和CI管道的HTTP端点，以及Claude和Cursor等代理运行时的MCP工具注册。这些表示共享业务逻辑，但在所有周… | MIT、HIT | Edwin Jose |
| 9 | [Beyond Acoustic Emotion Recognition: Multimodal Pathos Analy…](http://arxiv.org/abs/2605.22732v1) | 我们研究声学情感识别模型是否可以作为政治言论分析中Pathos维度的代理，由信任多代理大语言模型（ LLM ）管道操作。使用Felix Banaszak （ 51段， 245秒）的联邦议会全体会议演讲… | CAS | Juergen Dietrich |
| 10 | [Abstraction for Offline Goal-Conditioned Reinforcement Learn…](http://arxiv.org/abs/2605.22711v1) | 由于真实世界的目标条件强化学习（ GCRL ）中状态-目标对之间的对称性和共享结构，马尔可夫决策过程（ MDP ）通常表现出显著的冗余。虽然分层策略在离线GCRL中通过时间抽象来实现视野缩小，但我们证… | Mila、TRI | Clarisse Wibault |
| 11 | [WorkstreamBench: Evaluating LLM Agents on End-to-End Spreads…](http://arxiv.org/abs/2605.22664v1) | LLM代理越来越多地被期望执行端到端工作流程，根据高级用户指令生成完整的工件。为了满足企业需求，前沿人工智能实验室开发了可以从头开始构建整个电子表格的代理。这表明，目前的客服代表还无法在现实工作流程所… | CAS | Thomson Yen |
| 12 | [Claw AI Lab: An Autonomous Multi-Agent Research Team](http://arxiv.org/abs/2605.22662v1) | 我们推出了Claw AI Lab ，这是一个实验室原生的自主研究平台，可将自动化研究从隐藏的提示到纸张的管道推进到交互式AI实验室。我们允许用户从一个提示中实例化一个完整的研究团队，而不是围绕单个代理… | CAS、TRI | Fan Wu |
| 13 | [Spreadsheet-RL: Advancing Large Language Model Agents on Rea…](http://arxiv.org/abs/2605.22642v1) | 电子表格系统（例如Microsoft Excel、Google表格）在现代以数据为中心的工作流程中发挥着核心作用。随着人工智能代理越来越有能力自动化复杂的任务，例如控制计算机和生成演示文稿，构建人工智… | Microsoft、Google | Banghao Chi |
| 14 | [Agentic CLEAR: Automating Multi-Level Evaluation of LLM Agen…](http://arxiv.org/abs/2605.22608v1) | 代理系统变得越来越强大：代理定义策略、采取行动并与不同环境进行交互。这种自主性给监督和评估客服代表的行为带来了严峻挑战。我们的分析显示，与人工注释错误有很强的一致性，并且能够预测任务成功率。 | MIT、NTU | Asaf Yehudai |
| 15 | [Think Thrice Before You Speak: Dual knowledge-enhanced Theor…](http://arxiv.org/abs/2605.22602v1) | 有说服力的对话需要对他人潜在的心理状态进行推理，这种能力被称为心智理论（ ToM ）。然而，由于依赖于简单的提示策略和ToM知识不足，现有的LLM通常无法捕捉到心理状态之间的内在依赖性，从而导致分散的… | CAS、TRI | Minghui Ma |
| 16 | [VGenST-Bench: A Benchmark for Spatio-Temporal Reasoning via …](http://arxiv.org/abs/2605.22570v1) | 时空推理是现实世界中运行的多模态大型语言模型（ MLLM ）的核心功能。因此，精确评估已成为一项基本挑战。通过将范式从被动策展转变为主动合成， VGenST-Bench能够对MLLM中的时空理解进行细… | MIT | Jinho Park |
| 17 | [GraphFlow: A Graph-Based Workflow Management for Efficient L…](http://arxiv.org/abs/2605.22566v1) | 在结构化指令（通常称为工作流程）的指导下，基于大型语言模型（ LLM ）的代理在复杂任务上表现出强大的推理和执行能力。然而，现有的工作流辅助代理服务系统通常依赖于预定义的模板和浅层匹配机制，这限制了它… | MIT | Ao Li |
| 18 | [SynAE: A Framework for Measuring the Quality of Synthetic Da…](http://arxiv.org/abs/2605.22564v1) | 如今，工具调用代理通常在执行跟踪的静态数据集上进行评估或测试，包括输入命令、代理响应和相关工具调用。但是，内部生产数据集通常不足或无法用于测试；例如，它们可能包含敏感或专有数据，或者它们可能太稀疏，无… | NUS、TRI | Shuaiqi Wang |
| 19 | [Search-E1: Self-Distillation Drives Self-Evolution in Search…](http://arxiv.org/abs/2605.22511v1) | 后训练已成为将语言模型转变为合格的搜索增强推理代理的主要方法。最近的一系列工作通过在这条标准管道上添加精心设计的机器来进一步推动其性能。代码和完整版本将很快公开。 | NUS、TRI | Zihan Liang |
| 20 | [Towards Direct Evaluation of Harness Optimizers via Priority…](http://arxiv.org/abs/2605.22505v1) | 线束优化通过让优化器代理迭代更新目标代理的线束来实现自动化代理创建。尽管取得了成功，但目前的研究仅通过观察目标座席的绩效提升来评估优化器。代码和数据可在https://github.com/k5911… | TRI | Kai Tzu-iunn Ong |

### 论文详情

<details>
<summary><b>1. Remember to be Curious: Episodic Context and Persistent Worlds for 3D Exploration</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Lily Goli、Justin Kerr、Daniele Reda、Alec Jacobson、Andrea Tagliasacchi 等（共 6 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | Apple、TRI |
| **发布时间** | 2026-05-21T17:58:06Z |
| **关键词** | `Reinforcement Learning` |
| **原文链接** | [http://arxiv.org/abs/2605.22814v1](http://arxiv.org/abs/2605.22814v1) |

**📝 摘要概括：**

> 探索是在稀疏奖励的长期任务中学习有用行为的先决条件，特别是在3D环境中。好奇心驱动的强化学习通过代理对世界的预测模型与现实之间的不匹配所带来的内在奖励来解决这个问题。请访问https://recuriosity.github.io/查看视频结果。

</details>

<details>
<summary><b>2. MOSS: Self-Evolution through Source-Level Rewriting in Autonomous Agent Systems</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Qianshu Cai、Yonggang Zhang、Xianzhang Jia、Wei Xue、Jun Song 等（共 7 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-05-21T17:48:33Z |
| **关键词** | `Agentic` · `Memory` · `Workflow` |
| **原文链接** | [http://arxiv.org/abs/2605.22794v1](http://arxiv.org/abs/2605.22794v1) |

**📝 摘要概括：**

> 自主代理系统在部署后基本上是静态的：它们不会从用户交互中学习，并且反复出现的故障会持续存在，直到下一次人为驱动的更新发布修复程序。作为回应，出现了自我进化的代理，但所有代理都将进化局限于可文本变更的工件（技能文件、提示配置、内存架构、工作流程图） ，并保持代理利用不变。在OpenClaw上， MOSS提升了四项任务的平均分数……

</details>

<details>
<summary><b>3. LCGuard: Latent Communication Guard for Safe KV Sharing in Multi-Agent Systems</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Sadia Asif、Mohammad Mohammadi Amiri、Momin Abbas、Prasanna Sattigeri、Karthikeyan Natesan Ramamurthy |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT |
| **发布时间** | 2026-05-21T17:42:12Z |
| **关键词** | `Multi-Agent` · `Reasoning` · `Benchmark` · `Evaluation` · `Memory` |
| **原文链接** | [http://arxiv.org/abs/2605.22786v1](http://arxiv.org/abs/2605.22786v1) |

**📝 摘要概括：**

> 基于大型语言模型（ LLM ）的多智能体系统越来越依赖于中间通信来协调复杂的任务。虽然大多数现有系统通过自然语言进行通信，但最近的工作表明，潜伏通信，特别是通过变压器键值（ KV ）缓存，可以提高效率并保留更丰富的任务相关信息。跨多个模型系列和多代理基准的实证评估......

</details>

<details>
<summary><b>4. DeltaBox: Scaling Stateful AI Agents with Millisecond-Level Sandbox Checkpoint/Rollback</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Yunpeng Dong、Jingkai He、Yuze Hou、Dong Du、Zhonghu Xu 等（共 8 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | Mila、TRI |
| **发布时间** | 2026-05-21T17:36:17Z |
| **关键词** | `AI Agent` · `Reinforcement Learning` · `Benchmark` · `Evaluation` · `Memory` |
| **原文链接** | [http://arxiv.org/abs/2605.22781v1](http://arxiv.org/abs/2605.22781v1) |

**📝 摘要概括：**

> 基于LLM的AI代理需要高频状态探索（例如，测试时树搜索和强化学习） ，依赖于完整沙箱状态的快速检查点和回滚（ C/R ） ，包括文件和进程状态（例如，内存、上下文等）。现有机制复制整个状态，导致每个C/R数百毫秒到数秒的延迟，这严重阻碍了深度搜索和大规模扇出。评估…

</details>

<details>
<summary><b>5. Deep Reinforcement Learning for Flexible Job Shop Scheduling with Random Job Arrivals</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Yu Tang、Muhammad Zakwan、Efe Balta、John Lygeros、Alisa Rupenyan |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-05-21T17:33:09Z |
| **关键词** | `Reinforcement Learning` · `Benchmark` · `Simulation` |
| **原文链接** | [http://arxiv.org/abs/2605.22773v1](http://arxiv.org/abs/2605.22773v1) |

**📝 摘要概括：**

> 灵活作业车间调度问题（ FJSP ）是向机器分配一组作业的最佳方式。FJSP仍然存在两个主要挑战：未来工作的不可预测性和问题的组合复杂性，这使得传统的混合整数线性规划求解器难以解决问题。我们将我们的\ GLS {DRL}与到达触发的混合整数线性规划解决方案进行基准比较，并证明我们的方法实现了……

</details>

<details>
<summary><b>6. Advancing Mathematics Research with AI-Driven Formal Proof Search</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | George Tsoukalas、Anton Kovsharov、Sergey Shirobokov、Anja Surina、Moritz Firsching 等（共 20 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、NTU |
| **发布时间** | 2026-05-21T17:24:57Z |
| **关键词** | `Reasoning` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2605.22763v1](http://arxiv.org/abs/2605.22763v1) |

**📝 摘要概括：**

> 大型语言模型（ LLM ）越来越擅长数学推理，但它们的不可靠性限制了它们在数学研究中的实用性。缓解措施是使用LLM以精益等语言生成正式证明。这些发现展示了人工智能辅助正式证明搜索的强大功能，并阐明了实现这一功能的代理设计。

</details>

<details>
<summary><b>7. Towards a General Intelligence and Interface for Wearable Health Data</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Girish Narayanswamy、Maxwell A. Xu、A. Ali Heydari、Samy Abdel-Ghaffar、Marius Guerard 等（共 40 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-05-21T17:24:06Z |
| **关键词** | `LLM Agent` · `RAG` |
| **原文链接** | [http://arxiv.org/abs/2605.22759v1](http://arxiv.org/abs/2605.22759v1) |

**📝 摘要概括：**

> 虽然无处不在的可穿戴传感器可以捕捉到丰富的行为和生理信息，但将这些信号有效地转化为个性化的健康见解具有挑战性。具体而言，由于个体基线健康、生理和生活方式因素的高表型多样性和变化，将低水平传感器数据转换为能够表征更高水平状态的表征是困难的。最后，我们展示了如何……

</details>

<details>
<summary><b>8. HarnessAPI: A Skill-First Framework for Unified Streaming APIs and MCP Tools</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Edwin Jose |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、HIT |
| **发布时间** | 2026-05-21T17:03:44Z |
| **关键词** | — |
| **原文链接** | [http://arxiv.org/abs/2605.22733v1](http://arxiv.org/abs/2605.22733v1) |

**📝 摘要概括：**

> 如今，作为LLM工具部署的每个Python函数都必须以两种形式存在：面向人的客户端和CI管道的HTTP端点，以及Claude和Cursor等代理运行时的MCP工具注册。这些表示共享业务逻辑，但在所有周围的机器（路由、验证、序列化、流式处理和架构维护）中存在分歧，并且随着底层代码的发展而分离。它可以在https上找到…

</details>

<details>
<summary><b>9. Beyond Acoustic Emotion Recognition: Multimodal Pathos Analysis in Political Speech Using LLM-Based and Acoustic Emotion Models</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Juergen Dietrich |
| **所属机构** | （详见原文） |
| **顶级机构标签** | CAS |
| **发布时间** | 2026-05-21T17:03:37Z |
| **关键词** | `Multi-Agent` · `Benchmark` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2605.22732v1](http://arxiv.org/abs/2605.22732v1) |

**📝 摘要概括：**

> 我们研究声学情感识别模型是否可以作为政治言论分析中Pathos维度的代理，由信任多代理大语言模型（ LLM ）管道操作。使用Felix Banaszak （ 51段， 245秒）的联邦议会全体会议演讲作为案例研究，我们比较了三种分析方式： （ 1 ） emotion2vec_plus_large ，一种声音语音情感识别（ SER ）模型，其连续唤醒和…

</details>

<details>
<summary><b>10. Abstraction for Offline Goal-Conditioned Reinforcement Learning</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Clarisse Wibault、Alexander Goldie、Antonio Villares、Maike Osborne、Jakob Foerster |
| **所属机构** | （详见原文） |
| **顶级机构标签** | Mila、TRI |
| **发布时间** | 2026-05-21T16:50:26Z |
| **关键词** | `Reinforcement Learning` |
| **原文链接** | [http://arxiv.org/abs/2605.22711v1](http://arxiv.org/abs/2605.22711v1) |

**📝 摘要概括：**

> 由于真实世界的目标条件强化学习（ GCRL ）中状态-目标对之间的对称性和共享结构，马尔可夫决策过程（ MDP ）通常表现出显著的冗余。虽然分层策略在离线GCRL中通过时间抽象来实现视野缩小，但我们证明了层次结构也能够实现绝对抽象。我们的实验表明，这种归纳偏差显著改善了性能……

</details>

<details>
<summary><b>11. WorkstreamBench: Evaluating LLM Agents on End-to-End Spreadsheet Tasks in Finance</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Thomson Yen、Julian Poeltl、Harshith Srinivas Gear、Yilin Meng、Joshua Fan 等（共 12 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | CAS |
| **发布时间** | 2026-05-21T16:06:34Z |
| **关键词** | `LLM Agent` · `Benchmark` · `Evaluation` · `Workflow` |
| **原文链接** | [http://arxiv.org/abs/2605.22664v1](http://arxiv.org/abs/2605.22664v1) |

**📝 摘要概括：**

> LLM代理越来越多地被期望执行端到端工作流程，根据高级用户指令生成完整的工件。为了满足企业需求，前沿人工智能实验室开发了可以从头开始构建整个电子表格的代理。这表明，目前的客服代表还无法在现实工作流程所需的复杂程度上可靠地生成专业质量的电子表格。

</details>

<details>
<summary><b>12. Claw AI Lab: An Autonomous Multi-Agent Research Team</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Fan Wu、Cheng Chen、Zhenshan Tan、Taiyu Zhang、Xinzhen Xu 等（共 15 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | CAS、TRI |
| **发布时间** | 2026-05-21T16:02:53Z |
| **关键词** | `Multi-Agent` · `Evaluation` · `Workflow` |
| **原文链接** | [http://arxiv.org/abs/2605.22662v1](http://arxiv.org/abs/2605.22662v1) |

**📝 摘要概括：**

> 我们推出了Claw AI Lab ，这是一个实验室原生的自主研究平台，可将自动化研究从隐藏的提示到纸张的管道推进到交互式AI实验室。我们允许用户从一个提示中实例化一个完整的研究团队，而不是围绕单个代理或固定的序列工作流程来集中系统，该团队具有可定制的角色、协作工作流程、实时监控、工件检查和回滚/恢复控制……

</details>

<details>
<summary><b>13. Spreadsheet-RL: Advancing Large Language Model Agents on Realistic Spreadsheet Tasks via Reinforcement Learning</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Banghao Chi、Yining Xie、Mingyuan Wu、Jingcheng Yang、Jize Jiang 等（共 12 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | Microsoft、Google、TRI |
| **发布时间** | 2026-05-21T15:47:41Z |
| **关键词** | `AI Agent` · `Reinforcement Learning` · `Benchmark` · `Evaluation` · `Fine-tuning` |
| **原文链接** | [http://arxiv.org/abs/2605.22642v1](http://arxiv.org/abs/2605.22642v1) |

**📝 摘要概括：**

> 电子表格系统（例如Microsoft Excel、Google表格）在现代以数据为中心的工作流程中发挥着核心作用。随着人工智能代理越来越有能力自动化复杂的任务，例如控制计算机和生成演示文稿，构建人工智能驱动的电子表格代理已成为一个有前途的研究方向。这些结果凸显了Spreadsheet-RL在电子表格自动化中的泛化和现实应用的巨大潜力……

</details>

<details>
<summary><b>14. Agentic CLEAR: Automating Multi-Level Evaluation of LLM Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Asaf Yehudai、Lilach Eden、Michal Shmueli-Scheuer |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、NTU |
| **发布时间** | 2026-05-21T15:26:02Z |
| **关键词** | `LLM Agent` · `Agentic` · `Benchmark` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2605.22608v1](http://arxiv.org/abs/2605.22608v1) |

**📝 摘要概括：**

> 代理系统变得越来越强大：代理定义策略、采取行动并与不同环境进行交互。这种自主性给监督和评估客服代表的行为带来了严峻挑战。我们的分析显示，与人工注释错误有很强的一致性，并且能够预测任务成功率。

</details>

<details>
<summary><b>15. Think Thrice Before You Speak: Dual knowledge-enhanced Theory-of-Mind Reasoning for Persuasive Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Minghui Ma、Bin Guo、Runze Yang、Mengqi Chen、Yan Liu 等（共 10 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | CAS、TRI |
| **发布时间** | 2026-05-21T15:15:51Z |
| **关键词** | `Reasoning` · `RAG` |
| **原文链接** | [http://arxiv.org/abs/2605.22602v1](http://arxiv.org/abs/2605.22602v1) |

**📝 摘要概括：**

> 有说服力的对话需要对他人潜在的心理状态进行推理，这种能力被称为心智理论（ ToM ）。然而，由于依赖于简单的提示策略和ToM知识不足，现有的LLM通常无法捕捉到心理状态之间的内在依赖性，从而导致分散的表示和不稳定的推理。案例研究进一步表明，我们的方法增强了推理的可解释性和一致性……

</details>

<details>
<summary><b>16. VGenST-Bench: A Benchmark for Spatio-Temporal Reasoning via Active Video Synthesis</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Jinho Park、Youbin Kim、Hogun Park、Eunbyung Park |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT |
| **发布时间** | 2026-05-21T14:48:35Z |
| **关键词** | `Multi-Agent` · `Reasoning` · `Benchmark` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2605.22570v1](http://arxiv.org/abs/2605.22570v1) |

**📝 摘要概括：**

> 时空推理是现实世界中运行的多模态大型语言模型（ MLLM ）的核心功能。因此，精确评估已成为一项基本挑战。通过将范式从被动策展转变为主动合成， VGenST-Bench能够对MLLM中的时空理解进行细粒度诊断。

</details>

<details>
<summary><b>17. GraphFlow: A Graph-Based Workflow Management for Efficient LLM-Agent Serving</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Ao Li、Shangpeng Yang、Fahao Chen、Tianheng Xu、Peng Li 等（共 6 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT |
| **发布时间** | 2026-05-21T14:45:40Z |
| **关键词** | `Reasoning` · `RAG` · `Benchmark` · `Memory` · `Workflow` |
| **原文链接** | [http://arxiv.org/abs/2605.22566v1](http://arxiv.org/abs/2605.22566v1) |

**📝 摘要概括：**

> 在结构化指令（通常称为工作流程）的指导下，基于大型语言模型（ LLM ）的代理在复杂任务上表现出强大的推理和执行能力。然而，现有的工作流辅助代理服务系统通常依赖于预定义的模板和浅层匹配机制，这限制了它们捕获深层语义关系并将其推广到以前未见过的任务的能力。广泛的实验交流……

</details>

<details>
<summary><b>18. SynAE: A Framework for Measuring the Quality of Synthetic Data for Tool-Calling Agent Evaluations</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Shuaiqi Wang、Aadyaa Maddi、Zinan Lin、Giulia Fanti |
| **所属机构** | （详见原文） |
| **顶级机构标签** | NUS、TRI |
| **发布时间** | 2026-05-21T14:45:02Z |
| **关键词** | `Benchmark` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2605.22564v1](http://arxiv.org/abs/2605.22564v1) |

**📝 摘要概括：**

> 如今，工具调用代理通常在执行跟踪的静态数据集上进行评估或测试，包括输入命令、代理响应和相关工具调用。但是，内部生产数据集通常不足或无法用于测试；例如，它们可能包含敏感或专有数据，或者它们可能太稀疏，无法支持全面测试（尤其是部署前）。SynAE的演示可在https://synae…

</details>

<details>
<summary><b>19. Search-E1: Self-Distillation Drives Self-Evolution in Search-Augmented Reasoning</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Zihan Liang、Yufei Ma、Ben Chen、Zhipeng Qian、Xuxin Zhang 等（共 7 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | NUS、TRI |
| **发布时间** | 2026-05-21T14:00:57Z |
| **关键词** | `Reasoning` · `RAG` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2605.22511v1](http://arxiv.org/abs/2605.22511v1) |

**📝 摘要概括：**

> 后训练已成为将语言模型转变为合格的搜索增强推理代理的主要方法。最近的一系列工作通过在这条标准管道上添加精心设计的机器来进一步推动其性能。代码和完整版本将很快公开。

</details>

<details>
<summary><b>20. Towards Direct Evaluation of Harness Optimizers via Priority Ranking</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Kai Tzu-iunn Ong、Minseok Kang、Dongwook Choi、Junhee Cho、Seungju Kim 等（共 12 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-05-21T13:55:02Z |
| **关键词** | `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2605.22505v1](http://arxiv.org/abs/2605.22505v1) |

**📝 摘要概括：**

> 线束优化通过让优化器代理迭代更新目标代理的线束来实现自动化代理创建。尽管取得了成功，但目前的研究仅通过观察目标座席的绩效提升来评估优化器。代码和数据可在https://github.com/k59118/Harness_Optimizer_Evaluation上找到。

</details>

## 🗄️ 历史归档

| 日期 | 论文数 | 报告链接 |
|------|--------|----------|
| 2026-05-22 | 20 篇 | [2026-05-22.md](daily/2026-05-22.md) |
| 2026-05-21 | 0 篇 | [2026-05-21.md](daily/2026-05-21.md) |
| 2026-05-20 | 16 篇 | [2026-05-20.md](daily/2026-05-20.md) |
| 2026-05-19 | 0 篇 | [2026-05-19.md](daily/2026-05-19.md) |
| 2026-05-17 | 0 篇 | [2026-05-17.md](daily/2026-05-17.md) |
| 2026-05-16 | 0 篇 | [2026-05-16.md](daily/2026-05-16.md) |
| 2026-05-15 | 20 篇 | [2026-05-15.md](daily/2026-05-15.md) |
| 2026-05-14 | 19 篇 | [2026-05-14.md](daily/2026-05-14.md) |
| 2026-05-13 | 20 篇 | [2026-05-13.md](daily/2026-05-13.md) |
| 2026-05-12 | 20 篇 | [2026-05-12.md](daily/2026-05-12.md) |
| 2026-05-11 | 0 篇 | [2026-05-11.md](daily/2026-05-11.md) |
| 2026-05-10 | 0 篇 | [2026-05-10.md](daily/2026-05-10.md) |
| 2026-05-09 | 0 篇 | [2026-05-09.md](daily/2026-05-09.md) |
| 2026-05-08 | 0 篇 | [2026-05-08.md](daily/2026-05-08.md) |
| 2026-05-07 | 13 篇 | [2026-05-07.md](daily/2026-05-07.md) |
| 2026-05-06 | 19 篇 | [2026-05-06.md](daily/2026-05-06.md) |
| 2026-05-05 | 20 篇 | [2026-05-05.md](daily/2026-05-05.md) |

## 🏛️ 顶级机构覆盖范围

覆盖超过 **70 个**顶级 AI 机构，包括：

- **科技公司：** Microsoft、Google DeepMind、OpenAI、Anthropic、Meta AI、NVIDIA、Baidu、Alibaba、ByteDance 等
- **北美顶级大学：** MIT、Stanford、CMU、UC Berkeley、Harvard、Princeton、Cornell、Caltech 等
- **中国顶级大学/机构：** 清华大学、北京大学、浙大、上交大、复旦、中科院、MSRA 等
- **欧洲/其他：** Oxford、Cambridge、ETH Zurich、Mila、NUS、KAIST 等

---

*由 [clawBot DailyFindings](https://github.com/Jacob-biu/clawBot) 自动维护 | 最后更新：2026-05-22 22:58 UTC*
