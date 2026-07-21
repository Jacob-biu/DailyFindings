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

## 📅 今日论文 — 2026-07-21　　[→ 查看完整报告](daily/2026-07-21.md)

> 共筛选出 **20** 篇论文 | 更新于 2026-07-21 22:55 UTC

### 论文目录与概要

| # | 论文标题 | 核心概要 | 来源机构 | 第一作者 |
|---|---------|---------|---------|--------|
| 1 | [FlashRT: Agent Harness for Guiding Agents to Deploy Real-Tim…](http://arxiv.org/abs/2607.18171v1) | 实时多模式应用程序，包括语音代理和交互式视频生成，将异构模型组合到管道中，其高效部署需要特定于应用程序的放置、流式传输和模型内并行度决策。现有的服务系统和自动并行编译器承诺进行有限的转换和固定的工作负… | NVIDIA、MIT | Krish Agarwal |
| 2 | [TRIM: Reducing AI-Generated CodeSlop via Agent Trajectory Mi…](http://arxiv.org/abs/2607.18161v1) | 编码代理越来越多地用于在许多下游任务中加速代码生成，例如修复错误、构建应用程序和原型设计。然而，尽管它们作为编码助手的价值，代理生成的代码往往比相应的人工编写的实现更大，更详细。TRIM也非常高效，所… | TRI | Alex Mathai |
| 3 | [LLMs and Agentic AI Systems for Smart Grids: A Tutorial on A…](http://arxiv.org/abs/2607.18147v1) | 大型语言模型（ LLM ）和智能AI系统已经从自然语言任务演变为使用外部工具来规划、检索和在技术领域采取行动。在智能电网中，最近的工作将代理方案应用于预测、优化和控制，将可信求解器包裹在语言接口后面，… | HIT、CAS | Daniela Rojas |
| 4 | [O-VAD: Industrial Video Anomaly Detection through Object-Cen…](http://arxiv.org/abs/2607.18142v1) | 工业视频异常检测（ IVAD ）旨在识别工业过程中的异常物体和事件，这对于现代制造和质量控制系统至关重要。现有的基于VLM的异常推理方法能够检测一般域中的开放式异常。在三个IVAD数据集上的广泛实验表… | MIT、TRI | Mei Yuan |
| 5 | [SGA: Plug&Play Geometric Verification for Educational Video …](http://arxiv.org/abs/2607.18116v1) | 最近的工作利用大型语言模型（ LLM ） ，使用Manim等库为教学动画生成可执行代码。然而，确保空间正确性和视觉易读性仍然具有挑战性，因为现有框架强调教学内容，而忽略了几何遮挡。在四个LLM骨干和两… | TRI | Lopez Jhon |
| 6 | [WorldCupArena: Fine-Grained Evaluation of Language Models an…](http://arxiv.org/abs/2607.18084v1) | 在开球前预测足球比赛需要的不仅仅是了解过去的结果：模型必须使用不断变化的信息，并在获得答案之前做出明确的预测。我们展示了WorldCupArena ，这是语言模型和深度研究代理的动态基准。代码、提示、… | Mila | Zhaokai Wang |
| 7 | [Sparse Evidence Can Suffice: Agentic Evidence Seeking for Mu…](http://arxiv.org/abs/2607.18080v1) | 多模态视频错误信息检测通常被制定为整体视频理解任务，其中整个视频及其相关内容在一次传递中进行处理和判断。然而，真实世界的错误信息往往表现出稀疏和成分的证据结构：可靠的决策可能仅取决于少数耦合的线索，而… | MIT、TRI | Haochen Zhao |
| 8 | [Autoresearch with Coding Agents: Generalizers and Metric-Max…](http://arxiv.org/abs/2607.18064v1) | 现在可以让编码代理独自改进软件的分数。在这种模式中--最近被推广为“自动搜索” --代理接收数据集、评估脚本和一个可编辑文件，并在没有监督的情况下进行迭代：修改代码，测量，如果分数提高则保留更改。从代… | OpenAI | Nursultan Askarbekuly |
| 9 | [Adaptive Adversaries: A Multi-Turn, Multi-LLM Benchmark for …](http://arxiv.org/abs/2607.18063v1) | 基于LLM的代理处理外部内容，将它们暴露于提示注射和多圈操作中。大多数安全基准评估防御者在评估、单回合或多回合之前收集的固定攻击池。我们发布了基准- 21个评估场景， 10个公共开发场景，编排器，基线… | Mila、TRI | Devina Jain |
| 10 | [SEE: Structure-aware Exploring \& Exploiting for Long-horizo…](http://arxiv.org/abs/2607.18046v1) | 由视觉语言模型提供支持的图形用户界面(GUI)代理有望实现真实世界移动任务的自动化。然而，由于缺乏从丰富元素和快速发展的应用程序中收集的高覆盖率、长距离交互轨迹，进展受到限制。我们将公开发布我们的合成… | MIT | Zhuohang Fan |
| 11 | [The Shared Discovery Paradox: How a One-Answer Rule Turns Be…](http://arxiv.org/abs/2607.18045v1) | 组织通常将分散的信息集中到一个排名中，然后允许许多代理根据该共享视图采取行动。在发现问题中，这可以改善信念，同时减少覆盖范围。贡献是一个紧凑的基准，将信息、分配、激励和依赖分成精确的可重复使用的数量。 | MIT、TRI | Yohei Nakajima |
| 12 | [Natural Language Access to Domain-Specific Metadata: A Reusa…](http://arxiv.org/abs/2607.18029v1) | 研究人员需要回答有关特定领域存档内容的特殊问题，但往往缺乏在元数据上编写结构化查询的专业知识。我们表明，当在精心设计的Web本体语言（ OWL ）本体中捕获领域词汇和语义时，大型语言模型（ LLM ）… | TRI | Blake G. Fitch |
| 13 | [MADA-RL: Multi-Agent Debate-Aware Reinforcement Learning for…](http://arxiv.org/abs/2607.18006v1) | 大型语言模型实现了强大的推理性能，但往往以高昂的训练成本-对于在有限预算下训练的紧凑模型（ $\ leq 4\ ，\ mathrm {B} $参数）来说，这一挑战尤其严峻。我们引入了MADA-RL ，… | MIT、NUS | Martino M. L. Pulici |
| 14 | [Self-State Attacks on Self-Hosted AI Agents: How Far Can OS …](http://arxiv.org/abs/2607.17986v1) | 自托管AI代理读取和写入自己的内存和配置文件以发挥作用。代理可能会通过自身状态的损坏而受到损害，这是通过合法的操作系统调用实现的损害。这些研究结果表明，针对新建立的自我状态攻击类别，需要重新考虑操作系… | MIT、TRI | Yimeng Chen |
| 15 | [Harness Engineering for LLM-Driven GPU Kernel Generation](http://arxiv.org/abs/2607.17979v1) | 大型语言模型（ LLM ）可以帮助GPU内核生成，但它们的实际有效性取决于生成的代码是否可以可靠地进行约束、验证、分析和选择。本文在NVIDIA Blackwell B200 GPU上的MLSys 2… | NVIDIA | Yue Shui |
| 16 | [RT-SHCUA: Real-Time Self-Hosted Computer-Use Agent for UAV C…](http://arxiv.org/abs/2607.17951v1) | 自然语言控制为无人机（ UAV ）提供了一个有前途的接口，但将自托管计算机使用代理（ SHCUA ）直接应用于无人机控制会引入结构不匹配。SHCUA专为交互式主机端工具使用而设计，其中延迟代理迭代通常… | HIT、TRI | Di Lu |
| 17 | [Towards Agentic Agent-based Models: Feasibility, Performance…](http://arxiv.org/abs/2607.17948v1) | 基于座席的模型（ ABM ）依赖于简单、明确和可重复的个人决策规则，而复杂的集体行为则来自座席之间的交互。大型语言模型（ LLM ）的最新进展使得使用基于LLM的代理功能来替换、丰富或扰乱这些规则变得… | Mila、NUS | Stefano Blando |
| 18 | [The Autonomous Agency Scale: A Behavioral Framework for Meas…](http://arxiv.org/abs/2607.17947v1) | 现有的人工智能测量框架量化了认知能力、任务自动化或灾难性风险，但没有一个量化了自主代理：系统以自我导向的方式表现的程度。系统可以使能力基准饱和，同时保持完全被动，仅在提示时才采取行动，并在任务完成时停… | MIT、HIT | Samuel Presgraves |
| 19 | [The Aura in the Machine: Genealogy and the Status of the Wor…](http://arxiv.org/abs/2607.17940v1) | 本文认为，生成人工智能（ AI ）不是前所未有的技术破裂，而是根深蒂固的历史进程的工业规模表现。通过生成艺术家谱，它展示了人工智能关于作者身份和创造力的问题是如何有确切的历史先例的。为了支持提出的论点… | TRI | Giorgio Presti |
| 20 | [Aggregate in the Advantage, Not the Ratio: A Canonical-Form …](http://arxiv.org/abs/2607.17924v1) | 以基于PPO的方法为例的多Agent策略优化是协作式多Agent强化学习（ MARL ）的一个关键分支。一个中心设计问题是多少邻居代理\脚注{在本文中， “邻居”不仅指物理上的接近，还指其行为相互影响… | MIT、TRI | Zijian Zhao |

### 论文详情

<details>
<summary><b>1. FlashRT: Agent Harness for Guiding Agents to Deploy Real-Time Multimodal Applications</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Krish Agarwal、Zhuoming Chen、Yanyuan Qin、Zhenyu Gu、Atri Rudra 等（共 6 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | NVIDIA、MIT、TRI |
| **发布时间** | 2026-07-20T17:12:28Z |
| **关键词** | `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2607.18171v1](http://arxiv.org/abs/2607.18171v1) |

**📝 摘要概括：**

> 实时多模式应用程序，包括语音代理和交互式视频生成，将异构模型组合到管道中，其高效部署需要特定于应用程序的放置、流式传输和模型内并行度决策。现有的服务系统和自动并行编译器承诺进行有限的转换和固定的工作负载假设，因此在新应用程序上实现高性能需要手工操作……

</details>

<details>
<summary><b>2. TRIM: Reducing AI-Generated CodeSlop via Agent Trajectory Minimization</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Alex Mathai、Shobini Iyer、Aleksandr Nogikh、Petros Maniatis、Franjo Ivancic 等（共 7 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-07-20T17:06:19Z |
| **关键词** | `Agentic` · `Code Generation` |
| **原文链接** | [http://arxiv.org/abs/2607.18161v1](http://arxiv.org/abs/2607.18161v1) |

**📝 摘要概括：**

> 编码代理越来越多地用于在许多下游任务中加速代码生成，例如修复错误、构建应用程序和原型设计。然而，尽管它们作为编码助手的价值，代理生成的代码往往比相应的人工编写的实现更大，更详细。TRIM也非常高效，所需的验证成本大约是Delta Debugging等算法基线的一半。

</details>

<details>
<summary><b>3. LLMs and Agentic AI Systems for Smart Grids: A Tutorial on Architectures and Applications</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Daniela Rojas、Abdulwahab Albassam、Aidan G. Leung、Jett Ngo、Ryan Luo 等（共 14 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | HIT、CAS、TRI |
| **发布时间** | 2026-07-20T16:45:13Z |
| **关键词** | `Agentic` · `Evaluation` · `Workflow` |
| **原文链接** | [http://arxiv.org/abs/2607.18147v1](http://arxiv.org/abs/2607.18147v1) |

**📝 摘要概括：**

> 大型语言模型（ LLM ）和智能AI系统已经从自然语言任务演变为使用外部工具来规划、检索和在技术领域采取行动。在智能电网中，最近的工作将代理方案应用于预测、优化和控制，将可信求解器包裹在语言接口后面，并协调多步骤的工作流程。出现了一致的分工：代理系统可靠地协调、检索和……

</details>

<details>
<summary><b>4. O-VAD: Industrial Video Anomaly Detection through Object-Centric Tracking and Reasoning</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Mei Yuan、Qi Long、Qifeng Wu、Zhenyang Li、Yizhou Zhao 等（共 8 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-07-20T16:36:00Z |
| **关键词** | `Agentic` · `Reasoning` |
| **原文链接** | [http://arxiv.org/abs/2607.18142v1](http://arxiv.org/abs/2607.18142v1) |

**📝 摘要概括：**

> 工业视频异常检测（ IVAD ）旨在识别工业过程中的异常物体和事件，这对于现代制造和质量控制系统至关重要。现有的基于VLM的异常推理方法能够检测一般域中的开放式异常。在三个IVAD数据集上的广泛实验表明，我们的方法优于前沿VLM、代理框架和传统的VAD方法。

</details>

<details>
<summary><b>5. SGA: Plug&Play Geometric Verification for Educational Video Synthesis</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Lopez Jhon、Hinojosa Carlos、Ghanem Bernard |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-07-20T16:11:19Z |
| **关键词** | `Agentic` · `RAG` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2607.18116v1](http://arxiv.org/abs/2607.18116v1) |

**📝 摘要概括：**

> 最近的工作利用大型语言模型（ LLM ） ，使用Manim等库为教学动画生成可执行代码。然而，确保空间正确性和视觉易读性仍然具有挑战性，因为现有框架强调教学内容，而忽略了几何遮挡。在四个LLM骨干和两个代理流水线上对MMMC-Code基准测试的实验表明， SGA的峰值MVQS为73.11 （ Cod…

</details>

<details>
<summary><b>6. WorldCupArena: Fine-Grained Evaluation of Language Models and Deep-Research Agents on Football Forecasting</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Zhaokai Wang、Tianlin Gui、Jiayuan Rao、Shangzhe Di、Yihong Tang 等（共 6 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | Mila |
| **发布时间** | 2026-07-20T15:52:48Z |
| **关键词** | `Benchmark` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2607.18084v1](http://arxiv.org/abs/2607.18084v1) |

**📝 摘要概括：**

> 在开球前预测足球比赛需要的不仅仅是了解过去的结果：模型必须使用不断变化的信息，并在获得答案之前做出明确的预测。我们展示了WorldCupArena ，这是语言模型和深度研究代理的动态基准。代码、提示、预测和评估脚本在https://github.com/wzk1015/WorldCupArena上开源。

</details>

<details>
<summary><b>7. Sparse Evidence Can Suffice: Agentic Evidence Seeking for Multimodal Video Misinformation Detection</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Haochen Zhao、Yongxiu Xu、Xinkui Lin、Dong Xie、Jiarui Lu 等（共 9 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-07-20T15:48:31Z |
| **关键词** | `Agentic` · `Reasoning` · `Reinforcement Learning` · `RAG` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2607.18080v1](http://arxiv.org/abs/2607.18080v1) |

**📝 摘要概括：**

> 多模态视频错误信息检测通常被制定为整体视频理解任务，其中整个视频及其相关内容在一次传递中进行处理和判断。然而，真实世界的错误信息往往表现出稀疏和成分的证据结构：可靠的决策可能仅取决于少数耦合的线索，而大多数视频内容提供的附加信息有限。此外，由此产生的交流……

</details>

<details>
<summary><b>8. Autoresearch with Coding Agents: Generalizers and Metric-Maximizers on Quran Recitation Data</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Nursultan Askarbekuly、Mohamad Al Mdfaa、Ahmed Helaly、Gonzalo Ferrer、Manuel Mazzara |
| **所属机构** | （详见原文） |
| **顶级机构标签** | OpenAI |
| **发布时间** | 2026-07-20T15:32:09Z |
| **关键词** | `Reasoning` · `Evaluation` · `Memory` |
| **原文链接** | [http://arxiv.org/abs/2607.18064v1](http://arxiv.org/abs/2607.18064v1) |

**📝 摘要概括：**

> 现在可以让编码代理独自改进软件的分数。在这种模式中--最近被推广为“自动搜索” --代理接收数据集、评估脚本和一个可编辑文件，并在没有监督的情况下进行迭代：修改代码，测量，如果分数提高则保留更改。从代理利用我们的线束的方式--通过共享的git状态读取同级运行，在持久内存中留下“未来运行”的笔记--我们……

</details>

<details>
<summary><b>9. Adaptive Adversaries: A Multi-Turn, Multi-LLM Benchmark for LLM Agent Security</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Devina Jain、David Hartmann、Chuan Li |
| **所属机构** | （详见原文） |
| **顶级机构标签** | Mila、TRI |
| **发布时间** | 2026-07-20T15:30:38Z |
| **关键词** | `LLM Agent` · `Benchmark` · `Evaluation` · `Memory` |
| **原文链接** | [http://arxiv.org/abs/2607.18063v1](http://arxiv.org/abs/2607.18063v1) |

**📝 摘要概括：**

> 基于LLM的代理处理外部内容，将它们暴露于提示注射和多圈操作中。大多数安全基准评估防御者在评估、单回合或多回合之前收集的固定攻击池。我们发布了基准- 21个评估场景， 10个公共开发场景，编排器，基线线束和多攻击者CLI -加上来自3 $\ times $ 3前沿矩阵的945个成绩单，攻击...

</details>

<details>
<summary><b>10. SEE: Structure-aware Exploring \& Exploiting for Long-horizon GUI Agent Trajectory Synthesis</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Zhuohang Fan、Beichen Zhang、Yuanfa Li、Changqiao Wu、Wei Liu 等（共 7 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT |
| **发布时间** | 2026-07-20T15:16:59Z |
| **关键词** | `Planning` · `RAG` |
| **原文链接** | [http://arxiv.org/abs/2607.18046v1](http://arxiv.org/abs/2607.18046v1) |

**📝 摘要概括：**

> 由视觉语言模型提供支持的图形用户界面(GUI)代理有望实现真实世界移动任务的自动化。然而，由于缺乏从丰富元素和快速发展的应用程序中收集的高覆盖率、长距离交互轨迹，进展受到限制。我们将公开发布我们的合成代码和数据集。

</details>

<details>
<summary><b>11. The Shared Discovery Paradox: How a One-Answer Rule Turns Better Information into Worse Search</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Yohei Nakajima |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-07-20T15:14:24Z |
| **关键词** | `RAG` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2607.18045v1](http://arxiv.org/abs/2607.18045v1) |

**📝 摘要概括：**

> 组织通常将分散的信息集中到一个排名中，然后允许许多代理根据该共享视图采取行动。在发现问题中，这可以改善信念，同时减少覆盖范围。贡献是一个紧凑的基准，将信息、分配、激励和依赖分成精确的可重复使用的数量。

</details>

<details>
<summary><b>12. Natural Language Access to Domain-Specific Metadata: A Reusable Framework for LLM Query Generation</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Blake G. Fitch、Cato Elia Kurtz |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-07-20T14:59:33Z |
| **关键词** | `Multi-Agent` · `Retrieval` · `Fine-tuning` |
| **原文链接** | [http://arxiv.org/abs/2607.18029v1](http://arxiv.org/abs/2607.18029v1) |

**📝 摘要概括：**

> 研究人员需要回答有关特定领域存档内容的特殊问题，但往往缺乏在元数据上编写结构化查询的专业知识。我们表明，当在精心设计的Web本体语言（ OWL ）本体中捕获领域词汇和语义时，大型语言模型（ LLM ）可以生成精确的结构化查询，而无需微调、检索增强或多代理编排。我们的恶魔…

</details>

<details>
<summary><b>13. MADA-RL: Multi-Agent Debate-Aware Reinforcement Learning for Parameter-Efficient Reasoning in Compact Models</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Martino M. L. Pulici、Cuong Xuan Chu、Evgeny Kharlamov、Zifeng Ding、Volker Tresp 等（共 6 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、NUS、TRI |
| **发布时间** | 2026-07-20T14:38:00Z |
| **关键词** | `Multi-Agent` · `Reasoning` · `Reinforcement Learning` · `Benchmark` · `Fine-tuning` |
| **原文链接** | [http://arxiv.org/abs/2607.18006v1](http://arxiv.org/abs/2607.18006v1) |

**📝 摘要概括：**

> 大型语言模型实现了强大的推理性能，但往往以高昂的训练成本-对于在有限预算下训练的紧凑模型（ $\ leq 4\ ，\ mathrm {B} $参数）来说，这一挑战尤其严峻。我们引入了MADA-RL ，这是一个后训练框架，它将紧凑模型专门用于生成者和批评者角色，并用辩论感知学习信号对他们进行训练，通过LoRA适配器仅微调一小部分参数……

</details>

<details>
<summary><b>14. Self-State Attacks on Self-Hosted AI Agents: How Far Can OS Defenses Go?</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Yimeng Chen、Nathanaël Denis、Roberto Di Pietro、Jürgen Schmidhuber |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-07-20T14:16:55Z |
| **关键词** | `AI Agent` · `Memory` |
| **原文链接** | [http://arxiv.org/abs/2607.17986v1](http://arxiv.org/abs/2607.17986v1) |

**📝 摘要概括：**

> 自托管AI代理读取和写入自己的内存和配置文件以发挥作用。代理可能会通过自身状态的损坏而受到损害，这是通过合法的操作系统调用实现的损害。这些研究结果表明，针对新建立的自我状态攻击类别，需要重新考虑操作系统级别的防御，这可能会在该领域开辟新的研究方向。

</details>

<details>
<summary><b>15. Harness Engineering for LLM-Driven GPU Kernel Generation</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Yue Shui、Chenyu Ma、Hangfei Xu、Shengzhao Wen、Yanpeng Wang |
| **所属机构** | （详见原文） |
| **顶级机构标签** | NVIDIA |
| **发布时间** | 2026-07-20T14:14:14Z |
| **关键词** | `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2607.17979v1](http://arxiv.org/abs/2607.17979v1) |

**📝 摘要概括：**

> 大型语言模型（ LLM ）可以帮助GPU内核生成，但它们的实际有效性取决于生成的代码是否可以可靠地进行约束、验证、分析和选择。本文在NVIDIA Blackwell B200 GPU上的MLSys 2026 FlashInfer AI内核生成竞赛中，介绍了一种以线束为中心的系统，用于LLM驱动的GPU内核优化。Agent辅助内核在评估中的表现优于Full-Agent工件……

</details>

<details>
<summary><b>16. RT-SHCUA: Real-Time Self-Hosted Computer-Use Agent for UAV Control</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Di Lu、Bo Zhang、Xiyuan Li、Yongzhi Liao、Xuewen Dong 等（共 8 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | HIT、TRI |
| **发布时间** | 2026-07-20T13:52:24Z |
| **关键词** | `Reasoning` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2607.17951v1](http://arxiv.org/abs/2607.17951v1) |

**📝 摘要概括：**

> 自然语言控制为无人机（ UAV ）提供了一个有前途的接口，但将自托管计算机使用代理（ SHCUA ）直接应用于无人机控制会引入结构不匹配。SHCUA专为交互式主机端工具使用而设计，其中延迟代理迭代通常是可以接受的。原型评估表明， RT-SHCUA保持有界任务级响应，同时支持降级处理、可信准入……

</details>

<details>
<summary><b>17. Towards Agentic Agent-based Models: Feasibility, Performance, and Statistical Model Checking</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Stefano Blando、Emanuele Guerrazzi、Riccardo Porcedda、Giuseppe Squillace、Max Tschaikowski 等（共 6 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | Mila、NUS |
| **发布时间** | 2026-07-20T13:49:51Z |
| **关键词** | `Agentic` · `Simulation` |
| **原文链接** | [http://arxiv.org/abs/2607.17948v1](http://arxiv.org/abs/2607.17948v1) |

**📝 摘要概括：**

> 基于座席的模型（ ABM ）依赖于简单、明确和可重复的个人决策规则，而复杂的集体行为则来自座席之间的交互。大型语言模型（ LLM ）的最新进展使得使用基于LLM的代理功能来替换、丰富或扰乱这些规则变得非常诱人。我们讨论了统计模型检查如何评估经典的ABM可观察性，并量化引入药剂的影响……

</details>

<details>
<summary><b>18. The Autonomous Agency Scale: A Behavioral Framework for Measuring Self-Directed Behavior in AI Systems</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Samuel Presgraves |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、HIT、NUS |
| **发布时间** | 2026-07-20T13:49:10Z |
| **关键词** | `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2607.17947v1](http://arxiv.org/abs/2607.17947v1) |

**📝 摘要概括：**

> 现有的人工智能测量框架量化了认知能力、任务自动化或灾难性风险，但没有一个量化了自主代理：系统以自我导向的方式表现的程度。系统可以使能力基准饱和，同时保持完全被动，仅在提示时才采取行动，并在任务完成时停止所有活动。我们讨论了局限性，包括单一评分来源、开发者-评估者对长期……的偏见

</details>

<details>
<summary><b>19. The Aura in the Machine: Genealogy and the Status of the Work of Art in the Generative Era</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Giorgio Presti |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-07-20T13:36:18Z |
| **关键词** | `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2607.17940v1](http://arxiv.org/abs/2607.17940v1) |

**📝 摘要概括：**

> 本文认为，生成人工智能（ AI ）不是前所未有的技术破裂，而是根深蒂固的历史进程的工业规模表现。通过生成艺术家谱，它展示了人工智能关于作者身份和创造力的问题是如何有确切的历史先例的。为了支持提出的论点，我们研究了两个互补的方面：分布式作者的激进化；以及重新评估……

</details>

<details>
<summary><b>20. Aggregate in the Advantage, Not the Ratio: A Canonical-Form Analysis of Cooperative Multi-Agent Policy Optimization</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Zijian Zhao、Sen Li |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-07-20T13:20:29Z |
| **关键词** | `Multi-Agent` · `Reinforcement Learning` |
| **原文链接** | [http://arxiv.org/abs/2607.17924v1](http://arxiv.org/abs/2607.17924v1) |

**📝 摘要概括：**

> 以基于PPO的方法为例的多Agent策略优化是协作式多Agent强化学习（ MARL ）的一个关键分支。一个中心设计问题是多少邻居代理\脚注{在本文中， “邻居”不仅指物理上的接近，还指其行为相互影响的代理。}为了有效地利用全球信息进行合作，需要聚合。由此产生的设计原则是明确的……

</details>

## 🗄️ 历史归档

| 日期 | 论文数 | 报告链接 |
|------|--------|----------|
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
| 2026-06-21 | 0 篇 | [2026-06-21.md](daily/2026-06-21.md) |

## 🏛️ 顶级机构覆盖范围

覆盖超过 **70 个**顶级 AI 机构，包括：

- **科技公司：** Microsoft、Google DeepMind、OpenAI、Anthropic、Meta AI、NVIDIA、Baidu、Alibaba、ByteDance 等
- **北美顶级大学：** MIT、Stanford、CMU、UC Berkeley、Harvard、Princeton、Cornell、Caltech 等
- **中国顶级大学/机构：** 清华大学、北京大学、浙大、上交大、复旦、中科院、MSRA 等
- **欧洲/其他：** Oxford、Cambridge、ETH Zurich、Mila、NUS、KAIST 等

---

*由 [clawBot DailyFindings](https://github.com/Jacob-biu/clawBot) 自动维护 | 最后更新：2026-07-21 22:55 UTC*
