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

## 📅 今日论文 — 2026-05-12　　[→ 查看完整报告](daily/2026-05-12.md)

> 共筛选出 **20** 篇论文 | 更新于 2026-05-12 23:01 UTC

### 论文目录与概要

| # | 论文标题 | 核心概要 | 来源机构 | 第一作者 |
|---|---------|---------|---------|--------|
| 1 | [Dynamic Skill Lifecycle Management for Agentic Reinforcement…](http://arxiv.org/abs/2605.10923v1) | 大型语言模型代理越来越依赖外部技能来解决复杂的任务，其中技能充当模块化单元，将其功能扩展到仅参数内存支持的范围之外。现有的方法假设外部技能要么作为持久的指导积累，要么内化到政策中，最终导致零技能推断。… | MIT、NTU | Junhao Shen |
| 2 | [Optimal and Scalable MAPF via Multi-Marginal Optimal Transpo…](http://arxiv.org/abs/2605.10917v1) | 我们考虑匿名多智能体路径查找（ MAPF ） ，其中一组机器人的任务是在有限的连通图上行进到一组目标。我们证明了MAPF可以作为一类特殊的多边缘最优传输（ MMOT ）问题，具有潜在的马尔可夫结构，在… | MIT、CAS | Usman A. Khan |
| 3 | [Equivariant Reinforcement Learning for Clifford Quantum Circ…](http://arxiv.org/abs/2605.10910v1) | 我们考虑了为具有全量子位连接的设备合成Clifford量子电路的问题。我们将此任务视为强化学习问题，其中智能体学习发现基本Clifford门序列，该序列将Clifford电路的给定辛矩阵表示简化为恒等… | MIT、HIT | Richie Yeung |
| 4 | [Revisiting Policy Gradients for Restricted Policy Classes: E…](http://arxiv.org/abs/2605.10909v1) | 这项工作重新审视了受限策略类上使用的标准策略梯度方法，已知这些方法会陷入次优临界点。我们确定了这种现象的一个重要原因是政策梯度本身从根本上是短视的，即我们的界限避免了无处不在的分布失配因子$ ｜｜ d… | TRI | Alex DeWeese |
| 5 | [Engineering Robustness into Personal Agents with the AI Work…](http://arxiv.org/abs/2605.10907v1) | 人工智能代理的主导范式是一个“即时”循环，其中代理在几秒钟或几分钟内合成计划并响应用户提示执行操作。我们认为，这种范式缩短了有纪律的软件工程（ SE ）流程--迭代设计、严格测试、对抗性评估、分阶段部… | Google、Columbia University | Roxana Geambasu |
| 6 | [Shields to Guarantee Probabilistic Safety in MDPs](http://arxiv.org/abs/2605.10888v1) | 屏蔽是一种突出的基于模型的技术，可确保自主代理的安全性。经典屏蔽旨在确保不会发生任何坏事，并对安全性和最大限度的宽容性提供强有力的保证。实证评估突出了新屏蔽的实际优势及其计算可行性。 | TRI | Linus Heck |
| 7 | [AssayBench: An Assay-Level Virtual Cell Benchmark for LLMs a…](http://arxiv.org/abs/2605.10876v1) | 机器学习和大规模生物数据收集的最新进展重振了构建虚拟细胞的前景，虚拟细胞是可以加速生物发现的细胞行为的计算模型。这一愿景最引人注目的承诺之一是在电脑表型屏幕中执行的能力，其中模型预测了细胞扰动在看不见… | TRI | Edward De Brouwer |
| 8 | [Remember the Decision, Not the Description: A Rate-Distortio…](http://arxiv.org/abs/2605.10870v1) | 长视野语言代理必须在有限的运行时内存下运行，但现有的记忆机制通常围绕相关性、突出性或摘要质量等描述性标准组织经验。然而，对于座席来说，记忆之所以有价值，并不是因为它忠实地描述了过去，而是因为它保留了历… | MIT、CAS | Mingxi Zou |
| 9 | [The Generalized Turing Test: A Foundation for Comparing Inte…](http://arxiv.org/abs/2605.10851v1) | 我们引入了广义图灵测试（ GTT ） ，这是一个通过不可区分性来比较任意代理能力的正式框架。对于代理A和代理B ，我们定义了图灵比较器A $\ geq $ B ，如果B作为一个区分器，不能可靠地区分与… | MIT、TRI | Daniel Mitropolsky |
| 10 | [Rethinking Agentic Search with Pi-Serini: Is Lexical Retriev…](http://arxiv.org/abs/2605.10848v1) | 随着大型语言模型（ LLM ）在代理循环中变得更有能力，词汇检索器是否足够？在构建深度研究系统时，自然会出现这个问题。源代码可在https://github.com/justram/pi-serini… | TRI | Tz-Huan Hsu |
| 11 | [Training-Free Cultural Alignment of Large Language Models vi…](http://arxiv.org/abs/2605.10843v1) | 大型语言模型越来越多地调解转向道德判断的决策，但越来越多的证据表明，它们的隐性偏好在文化上并不中立。现有的文化调整方法要么需要每个国家的偏好数据和微调预算，要么假设白盒访问商业API不会暴露的模型内部… | HIT、TRI | Huynh Trung Kiet |
| 12 | [From Controlled to the Wild: Evaluation of Pentesting Agents…](http://arxiv.org/abs/2605.10834v1) | 人工智能渗透测试代理作为攻击性安全系统的可信度越来越高，但目前的基准仍然提供有限的指导，哪些指标在现实世界的目标中表现最佳。现有的评估协议在简化或狭窄的设置中评估和优化预定义目标，例如捕获标志、远程代… | MIT、Mila | Pedro Conde |
| 13 | [The First Drop of Ink: Nonlinear Impact of Misleading Inform…](http://arxiv.org/abs/2605.10828v1) | 随着大型语言模型越来越多地部署在检索增强生成和代理系统中，这些系统积累了大量的上下文，了解分散注意力的信息如何影响长上下文性能变得至关重要。先前的研究表明，语义相关但具有误导性的文档会降低性能，但干扰… | TRI | Muhan Gao |
| 14 | [MaD Physics: Evaluating information seeking under constraint…](http://arxiv.org/abs/2605.10820v1) | 科学发现基本上是一个资源受限的过程，由于物理和成本限制，需要在测量的质量和数量之间进行复杂的权衡。测量通过揭示新现象来提高我们的理解，从而推动科学过程。我们使用四种Gemini模型（ 2.5 Flas… | MIT、TRI | Moksh Jain |
| 15 | [Policy Gradient Methods for Non-Markovian Reinforcement Lear…](http://arxiv.org/abs/2605.10816v1) | 我们研究了非马尔可夫决策过程（ NMDP ）中强化学习的策略梯度方法，其中观察和奖励取决于整个交互历史。为了处理这种依赖关系，客服代表保持内部状态，该状态会递归更新，以提供过去观察和操作的简洁摘要。我… | TRI | Avik Kar |
| 16 | [NanoResearch: Co-Evolving Skills, Memory, and Policy for Per…](http://arxiv.org/abs/2605.10813v1) | 基于LLM的多智能体系统现在可以自动化从构思到论文写作的整个研究流程，但一个基本问题仍然存在：自动化适用于谁？研究人员在不同的资源配置下工作，持有不同的方法论偏好，并针对不同的输出格式。广泛的实验表明… | TRI | Jinhang Xu |
| 17 | [ComplexMCP: Evaluation of LLM Agents in Dynamic, Interdepend…](http://arxiv.org/abs/2605.10787v1) | 目前的LLM代理精通调用孤立的API ，但在商业软件自动化的“最后一英里”中苦苦挣扎。在现实世界中，工具不是独立的；它们是原子的、相互依存的，并且容易受到环境噪音的影响。这些发现强调了当前代理对于相互… | HIT、TRI | Yuanyang Li |
| 18 | [MATRA: Modeling the Attack Surface of Agentic AI Systems -- …](http://arxiv.org/abs/2605.10763v1) | LLM越来越多地被部署为可以访问工具、数据库和外部服务的自主代理，但从业者（跨不同部门）缺乏系统的方法来评估已知威胁类别如何在特定代理部署中转化为具体风险。我们提出了MATRA ，这是一个用于代理人工… | MIT、HIT | Tim Van hamme |
| 19 | [The Agent Use of Agent Beings: Agent Cybernetics Is the Miss…](http://arxiv.org/abs/2605.10754v1) | 基于法学硕士的基础代理在数千个推理步骤中感知、推理并采取行动，正迅速成为在开放式、长远的复杂任务中部署人工智能的主导范例。尽管具有这一重要意义，但该领域仍然主要由工程驱动。我们希望智能体控制论能够开辟… | MIT、HIT | Xinrun Wang |
| 20 | [An Uncertainty-Aware Resilience Micro-Agent for Causal Obser…](http://arxiv.org/abs/2605.10718v1) | 计算连续体中的灰色故障会产生模糊的重叠症状，现有方法无法可靠地诊断这些症状，要么是由于缺乏因果意识，要么是在高认知不确定性下采取行动，从而面临破坏性干预的风险。本文提出了一种具有不确定性的因果可观测性… | MIT、TRI | Suvi De Silva |

### 论文详情

<details>
<summary><b>1. Dynamic Skill Lifecycle Management for Agentic Reinforcement Learning</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Junhao Shen、Teng Zhang、Xiaoyan Zhao、Hong Cheng |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、NTU、TRI |
| **发布时间** | 2026-05-11T17:55:13Z |
| **关键词** | `Agentic` · `Reinforcement Learning` · `RAG` · `Memory` |
| **原文链接** | [http://arxiv.org/abs/2605.10923v1](http://arxiv.org/abs/2605.10923v1) |

**📝 摘要概括：**

> 大型语言模型代理越来越依赖外部技能来解决复杂的任务，其中技能充当模块化单元，将其功能扩展到仅参数内存支持的范围之外。现有的方法假设外部技能要么作为持久的指导积累，要么内化到政策中，最终导致零技能推断。结果进一步表明，政策学习和外部技能保留并不是相互的……

</details>

<details>
<summary><b>2. Optimal and Scalable MAPF via Multi-Marginal Optimal Transport and Schrödinger Bridges</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Usman A. Khan、Joseph W. Durham |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、CAS |
| **发布时间** | 2026-05-11T17:52:15Z |
| **关键词** | `Multi-Agent` |
| **原文链接** | [http://arxiv.org/abs/2605.10917v1](http://arxiv.org/abs/2605.10917v1) |

**📝 摘要概括：**

> 我们考虑匿名多智能体路径查找（ MAPF ） ，其中一组机器人的任务是在有限的连通图上行进到一组目标。我们证明了MAPF可以作为一类特殊的多边缘最优传输（ MMOT ）问题，具有潜在的马尔可夫结构，在该结构下，指数大的MMOT坍缩为线性规划（ LP ）多项式的大小。广泛的实验凸显了T……的优化和可扩展性。

</details>

<details>
<summary><b>3. Equivariant Reinforcement Learning for Clifford Quantum Circuit Synthesis</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Richie Yeung、Aleks Kissinger、Rob Cornish |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、HIT、NTU |
| **发布时间** | 2026-05-11T17:49:28Z |
| **关键词** | `Reinforcement Learning` · `RAG` |
| **原文链接** | [http://arxiv.org/abs/2605.10910v1](http://arxiv.org/abs/2605.10910v1) |

**📝 摘要概括：**

> 我们考虑了为具有全量子位连接的设备合成Clifford量子电路的问题。我们将此任务视为强化学习问题，其中智能体学习发现基本Clifford门序列，该序列将Clifford电路的给定辛矩阵表示简化为恒等式。在十量子位实例上继续培训后，代理可扩展到未见过的Clifford tableaus ，最多可扩展到……

</details>

<details>
<summary><b>4. Revisiting Policy Gradients for Restricted Policy Classes: Escaping Myopic Local Optima with $k$-step Policy Gradients</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Alex DeWeese、Guannan Qu |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-05-11T17:49:09Z |
| **关键词** | `Multi-Agent` |
| **原文链接** | [http://arxiv.org/abs/2605.10909v1](http://arxiv.org/abs/2605.10909v1) |

**📝 摘要概括：**

> 这项工作重新审视了受限策略类上使用的标准策略梯度方法，已知这些方法会陷入次优临界点。我们确定了这种现象的一个重要原因是政策梯度本身从根本上是短视的，即我们的界限避免了无处不在的分布失配因子$ || d_μ ^ {π ^ *}/d_μ ^ π ||_\ infty $和$ || d_μ ^ {π ^ *}/μ ||_\ infty $使$ k $步政策梯度方法能够…

</details>

<details>
<summary><b>5. Engineering Robustness into Personal Agents with the AI Workflow Store</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Roxana Geambasu、Mariana Raykova、Pierre Tholoniat、Trishita Tiwari、Lillian Tsai 等（共 6 人） |
| **所属机构** | Google and Columbia University；Google |
| **顶级机构标签** | Google、Columbia University |
| **发布时间** | 2026-05-11T17:46:33Z |
| **关键词** | `AI Agent` · `Agentic` · `Evaluation` · `Workflow` |
| **原文链接** | [http://arxiv.org/abs/2605.10907v1](http://arxiv.org/abs/2605.10907v1) |

**📝 摘要概括：**

> 人工智能代理的主导范式是一个“即时”循环，其中代理在几秒钟或几分钟内合成计划并响应用户提示执行操作。我们认为，这种范式缩短了有纪律的软件工程（ SE ）流程--迭代设计、严格测试、对抗性评估、分阶段部署等--这些流程提供了我们今天使用的（相对）可靠和安全的系统。我们概述了解决方案……

</details>

<details>
<summary><b>6. Shields to Guarantee Probabilistic Safety in MDPs</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Linus Heck、Filip Macák、Roman Andriushchenko、Milan Češka、Sebastian Junges |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-05-11T17:33:01Z |
| **关键词** | `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2605.10888v1](http://arxiv.org/abs/2605.10888v1) |

**📝 摘要概括：**

> 屏蔽是一种突出的基于模型的技术，可确保自主代理的安全性。经典屏蔽旨在确保不会发生任何坏事，并对安全性和最大限度的宽容性提供强有力的保证。实证评估突出了新屏蔽的实际优势及其计算可行性。

</details>

<details>
<summary><b>7. AssayBench: An Assay-Level Virtual Cell Benchmark for LLMs and Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Edward De Brouwer、Carl Edwards、Alexander Wu、Jenna Collier、Graham Heimberg 等（共 12 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-05-11T17:27:16Z |
| **关键词** | `Agentic` · `Benchmark` · `Evaluation` · `Fine-tuning` · `Workflow` |
| **原文链接** | [http://arxiv.org/abs/2605.10876v1](http://arxiv.org/abs/2605.10876v1) |

**📝 摘要概括：**

> 机器学习和大规模生物数据收集的最新进展重振了构建虚拟细胞的前景，虚拟细胞是可以加速生物发现的细胞行为的计算模型。这一愿景最引人注目的承诺之一是在电脑表型屏幕中执行的能力，其中模型预测了细胞扰动在看不见的生物环境中的影响。总体而言， AssayBench提供……

</details>

<details>
<summary><b>8. Remember the Decision, Not the Description: A Rate-Distortion Framework for Agent Memory</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Mingxi Zou、Zhihan Guo、Langzhang Liang、Zhuo Wang、Qifan Wang 等（共 9 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、CAS、TRI |
| **发布时间** | 2026-05-11T17:20:58Z |
| **关键词** | `Benchmark` · `Memory` |
| **原文链接** | [http://arxiv.org/abs/2605.10870v1](http://arxiv.org/abs/2605.10870v1) |

**📝 摘要概括：**

> 长视野语言代理必须在有限的运行时内存下运行，但现有的记忆机制通常围绕相关性、突出性或摘要质量等描述性标准组织经验。然而，对于座席来说，记忆之所以有价值，并不是因为它忠实地描述了过去，而是因为它保留了历史之间的区别，这些历史必须在固定的预算下保持分离，以支持良好的决策。在两个受控系统上……

</details>

<details>
<summary><b>9. The Generalized Turing Test: A Foundation for Comparing Intelligence</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Daniel Mitropolsky、Susan S. Hong、Riccardo Neumarker、Emanuele Rimoldi、Tomaso Poggio |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-05-11T17:00:18Z |
| **关键词** | `Reasoning` · `Benchmark` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2605.10851v1](http://arxiv.org/abs/2605.10851v1) |

**📝 摘要概括：**

> 我们引入了广义图灵测试（ GTT ） ，这是一个通过不可区分性来比较任意代理能力的正式框架。对于代理A和代理B ，我们定义了图灵比较器A $\ geq $ B ，如果B作为一个区分器，不能可靠地区分与A的交互（被指示模仿B ）和B的另一个实例，我们的结果将不可区分性定位为智能推理的统一透镜……

</details>

<details>
<summary><b>10. Rethinking Agentic Search with Pi-Serini: Is Lexical Retrieval Sufficient?</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Tz-Huan Hsu、Jheng-Hong Yang、Jimmy Lin |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-05-11T16:58:57Z |
| **关键词** | `Agentic` · `Reasoning` · `Retrieval` |
| **原文链接** | [http://arxiv.org/abs/2605.10848v1](http://arxiv.org/abs/2605.10848v1) |

**📝 摘要概括：**

> 随着大型语言模型（ LLM ）在代理循环中变得更有能力，词汇检索器是否足够？在构建深度研究系统时，自然会出现这个问题。源代码可在https://github.com/justram/pi-serini上获得。

</details>

<details>
<summary><b>11. Training-Free Cultural Alignment of Large Language Models via Persona Disagreement</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Huynh Trung Kiet、Dao Sy Duy Minh、Tuan Nguyen、Chi-Nguyen Tran、Phu-Hoa Pham 等（共 8 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | HIT、TRI |
| **发布时间** | 2026-05-11T16:55:16Z |
| **关键词** | `Fine-tuning` |
| **原文链接** | [http://arxiv.org/abs/2605.10843v1](http://arxiv.org/abs/2605.10843v1) |

**📝 摘要概括：**

> 大型语言模型越来越多地调解转向道德判断的决策，但越来越多的证据表明，它们的隐性偏好在文化上并不中立。现有的文化调整方法要么需要每个国家的偏好数据和微调预算，要么假设白盒访问商业API不会暴露的模型内部。我们的研究结果表明，推理时间校准是精细……的可扩展替代方案。

</details>

<details>
<summary><b>12. From Controlled to the Wild: Evaluation of Pentesting Agents for the Real-World</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Pedro Conde、Henrique Branquinho、Valerio Mazzone、Bruno Mendes、André Baptista 等（共 6 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、Mila、TRI |
| **发布时间** | 2026-05-11T16:50:00Z |
| **关键词** | `Benchmark` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2605.10834v1](http://arxiv.org/abs/2605.10834v1) |

**📝 摘要概括：**

> 人工智能渗透测试代理作为攻击性安全系统的可信度越来越高，但目前的基准仍然提供有限的指导，哪些指标在现实世界的目标中表现最佳。现有的评估协议在简化或狭窄的设置中评估和优化预定义目标，例如捕获标志、远程代码执行、利用再现或轨迹相似性。为了实现可重复性，我们还发布了专家注释地图……

</details>

<details>
<summary><b>13. The First Drop of Ink: Nonlinear Impact of Misleading Information in Long-Context Reasoning</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Muhan Gao、Zih-Ching Chen、Kuan-Hao Huang |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-05-11T16:46:20Z |
| **关键词** | `Agentic` · `Reasoning` · `Retrieval` |
| **原文链接** | [http://arxiv.org/abs/2605.10828v1](http://arxiv.org/abs/2605.10828v1) |

**📝 摘要概括：**

> 随着大型语言模型越来越多地部署在检索增强生成和代理系统中，这些系统积累了大量的上下文，了解分散注意力的信息如何影响长上下文性能变得至关重要。先前的研究表明，语义相关但具有误导性的文档会降低性能，但干扰因素比例与性能之间的定量关系仍未得到研究。

</details>

<details>
<summary><b>14. MaD Physics: Evaluating information seeking under constraints in physical environments</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Moksh Jain、Mehdi Bennani、Johannes Bausch、Yuri Chervonyi、Bogdan Georgiev 等（共 7 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-05-11T16:37:19Z |
| **关键词** | `Reasoning` · `Planning` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2605.10820v1](http://arxiv.org/abs/2605.10820v1) |

**📝 摘要概括：**

> 科学发现基本上是一个资源受限的过程，由于物理和成本限制，需要在测量的质量和数量之间进行复杂的权衡。测量通过揭示新现象来提高我们的理解，从而推动科学过程。我们使用四种Gemini模型（ 2.5 Flash Lite、2.5 Flash、2.5 Pro和3 Flash ）对MaD Physics代理进行基准测试，找出其结构上的缺陷……

</details>

<details>
<summary><b>15. Policy Gradient Methods for Non-Markovian Reinforcement Learning</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Avik Kar、Siddharth Chandak、Rahul Singh、Soumitra Sinhahajari、Eric Moulines 等（共 7 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-05-11T16:34:28Z |
| **关键词** | `Reinforcement Learning` · `RAG` |
| **原文链接** | [http://arxiv.org/abs/2605.10816v1](http://arxiv.org/abs/2605.10816v1) |

**📝 摘要概括：**

> 我们研究了非马尔可夫决策过程（ NMDP ）中强化学习的策略梯度方法，其中观察和奖励取决于整个交互历史。为了处理这种依赖关系，客服代表保持内部状态，该状态会递归更新，以提供过去观察和操作的简洁摘要。我们建立了有限时间和几乎肯定的收敛保证，并实证地证明，在一系列非…

</details>

<details>
<summary><b>16. NanoResearch: Co-Evolving Skills, Memory, and Policy for Personalized Research Automation</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Jinhang Xu、Qiyuan Zhu、Yujun Wu、Zirui Wang、Dongxu Zhang 等（共 15 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-05-11T16:33:47Z |
| **关键词** | `Multi-Agent` · `Planning` · `Memory` |
| **原文链接** | [http://arxiv.org/abs/2605.10813v1](http://arxiv.org/abs/2605.10813v1) |

**📝 摘要概括：**

> 基于LLM的多智能体系统现在可以自动化从构思到论文写作的整个研究流程，但一个基本问题仍然存在：自动化适用于谁？研究人员在不同的资源配置下工作，持有不同的方法论偏好，并针对不同的输出格式。广泛的实验表明，与最先进的人工智能研究系统相比， NanoResearch带来了巨大的收益，并逐渐重塑了……

</details>

<details>
<summary><b>17. ComplexMCP: Evaluation of LLM Agents in Dynamic, Interdependent, and Large-Scale Tool Sandbox</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Yuanyang Li、Xue Yang、Longyue Wang、Weihua Luo、Hongyang Chen |
| **所属机构** | （详见原文） |
| **顶级机构标签** | HIT、TRI |
| **发布时间** | 2026-05-11T16:20:51Z |
| **关键词** | `LLM Agent` · `RAG` · `Retrieval` · `Benchmark` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2605.10787v1](http://arxiv.org/abs/2605.10787v1) |

**📝 摘要概括：**

> 目前的LLM代理精通调用孤立的API ，但在商业软件自动化的“最后一英里”中苦苦挣扎。在现实世界中，工具不是独立的；它们是原子的、相互依存的，并且容易受到环境噪音的影响。这些发现强调了当前代理对于相互依赖的工作流的不足，将$\ textbf {ComplexMCP} $定位为下一代弹性自主系统的关键测试平台……

</details>

<details>
<summary><b>18. MATRA: Modeling the Attack Surface of Agentic AI Systems -- OpenClaw Case Study</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Tim Van hamme、Thomas Vissers、Javier Carnerero-Cano、Mario Fritz、Emil C. Lupu 等（共 7 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、HIT |
| **发布时间** | 2026-05-11T15:58:37Z |
| **关键词** | `AI Agent` · `Agentic` · `RAG` |
| **原文链接** | [http://arxiv.org/abs/2605.10763v1](http://arxiv.org/abs/2605.10763v1) |

**📝 摘要概括：**

> LLM越来越多地被部署为可以访问工具、数据库和外部服务的自主代理，但从业者（跨不同部门）缺乏系统的方法来评估已知威胁类别如何在特定代理部署中转化为具体风险。我们提出了MATRA ，这是一个用于代理人工智能系统的务实威胁建模框架，它采用既定的风险评估方法来系统地评估已知法学硕士如何……

</details>

<details>
<summary><b>19. The Agent Use of Agent Beings: Agent Cybernetics Is the Missing Science of Foundation Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Xinrun Wang、Chang Yang、He Zhao、Zhuoyi Lin、Shuyue Hu |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、HIT、NTU |
| **发布时间** | 2026-05-11T15:53:54Z |
| **关键词** | `Reasoning` · `Code Generation` · `Memory` |
| **原文链接** | [http://arxiv.org/abs/2605.10754v1](http://arxiv.org/abs/2605.10754v1) |

**📝 摘要概括：**

> 基于法学硕士的基础代理在数千个推理步骤中感知、推理并采取行动，正迅速成为在开放式、长远的复杂任务中部署人工智能的主导范例。尽管具有这一重要意义，但该领域仍然主要由工程驱动。我们希望智能体控制论能够开辟一个新的研究场所，并为基础智能体建立有原则、可靠的科学基础……

</details>

<details>
<summary><b>20. An Uncertainty-Aware Resilience Micro-Agent for Causal Observability in the Computing Continuum</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Suvi De Silva、Alfreds Lapkovskis、Alaa Saleh、Sasu Tarkoma、Praveen Kumar Donta |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-05-11T15:28:37Z |
| **关键词** | — |
| **原文链接** | [http://arxiv.org/abs/2605.10718v1](http://arxiv.org/abs/2605.10718v1) |

**📝 摘要概括：**

> 计算连续体中的灰色故障会产生模糊的重叠症状，现有方法无法可靠地诊断这些症状，要么是由于缺乏因果意识，要么是在高认知不确定性下采取行动，从而面临破坏性干预的风险。本文提出了一种具有不确定性的因果可观测性弹性微代理（ AURORA ） ，这是一种用于诊断和缓解边缘层环境中灰色故障的轻量级框架。我们…

</details>

## 🗄️ 历史归档

| 日期 | 论文数 | 报告链接 |
|------|--------|----------|
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

*由 [clawBot DailyFindings](https://github.com/Jacob-biu/clawBot) 自动维护 | 最后更新：2026-05-12 23:01 UTC*
