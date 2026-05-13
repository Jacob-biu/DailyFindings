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

## 📅 今日论文 — 2026-05-13　　[→ 查看完整报告](daily/2026-05-13.md)

> 共筛选出 **20** 篇论文 | 更新于 2026-05-13 23:09 UTC

### 论文目录与概要

| # | 论文标题 | 核心概要 | 来源机构 | 第一作者 |
|---|---------|---------|---------|--------|
| 1 | [MEME: Multi-entity & Evolving Memory Evaluation](http://arxiv.org/abs/2605.12477v1) | 基于LLM的代理越来越多地在持久化环境中运行，他们必须在许多会话中存储、更新和推理信息。虽然先前的基准仅评估单个实体更新，但MEME定义了跨越多实体和不断演变的轴所定义的全部空间的六项任务，包括先前工… | CAS、TRI | Seokwon Jung |
| 2 | [KV-Fold: One-Step KV-Cache Recurrence for Long-Context Infer…](http://arxiv.org/abs/2605.12471v1) | 我们引入了KV-Fold ，这是一种简单、无需训练的长上下文推理协议，将关键值（ KV ）缓存视为序列块左侧折叠中的累加器。在每个步骤中，模型处理以累积缓存为条件的下一个块，追加新生成的键和值，并将放… | MIT、HIT | Alireza Nadali |
| 3 | [Multi-Stream LLMs: Unblocking Language Models with Parallel …](http://arxiv.org/abs/2605.12460v1) | 语言模型功能的持续改进已经解锁了它们作为自主代理的驱动程序的广泛使用，例如在编码或计算机使用应用程序中。然而，自ChatGPT等早期指令优化模型以来，这些系统的核心并没有太大变化。我们认为，这种数据驱… | MIT、Mila | Guinan Su |
| 4 | [Predicting Decisions of AI Agents from Limited Interaction t…](http://arxiv.org/abs/2605.12411v1) | 人工智能代理用自然语言与不熟悉的同行进行谈判和交易：面对未知卖家的买方机器人，或与供应商谈判的采购助理。在此类交互中，对方的LLM、提示、控制逻辑和基于规则的后备方案将被隐藏，而每个决策都可能产生金钱… | TRI | Eilam Shapira |
| 5 | [Events as Triggers for Behavioral Diversity in Multi-Agent R…](http://arxiv.org/abs/2605.12388v1) | 有效的多代理合作要求代理在任务条件发生变化时采取不同的行为，并在适当的时候这样做。然而，目前促进这种多样性的多Agent强化学习（ MARL ）框架仍然受到限制，因为它们将固定行为与固定Agent身份… | MIT、TRI | Hannes Büchi |
| 6 | [ProfiliTable: Profiling-Driven Tabular Data Processing via A…](http://arxiv.org/abs/2605.12376v1) | 表处理（包括清理、转换、增强和匹配）是现实数据管道中一个基本但容易出错的阶段。虽然最近基于LLM的方法显示出自动化此类任务的希望，但由于指令模糊、任务结构复杂和缺乏结构化反馈，它们在实践中经常遇到困难… | TRI | Wei Liu |
| 7 | [Agent-Based Post-Hoc Correction of Agricultural Yield Foreca…](http://arxiv.org/abs/2605.12375v1) | 商业软果生产中的准确作物产量预测受到典型商业农场记录中可用数据的限制，这些记录缺乏大多数最先进方法所假设的传感器网络、卫星图像和高分辨率气象输入。我们提出了一个结构化的LLM代理框架，该框架对现有模型… | CAS、AI2 | Matthew Beddows |
| 8 | [Classifier Context Rot: Monitor Performance Degrades with Co…](http://arxiv.org/abs/2605.12366v1) | 使用语言模型监控编码代理的危险行为需要对通常超过50万个令牌的成绩单进行分类，但先前的代理监控基准很少包含超过10万个令牌的成绩单。我们表明，当用作分类器时，当前的前沿模型无法在较长的转录本中更频繁地… | MIT | Sam Martin |
| 9 | [Attacks and Mitigations for Distributed Governance of Agenti…](http://arxiv.org/abs/2605.12364v1) | 代理AI治理是代理AI基础设施的关键组成部分，可确保代理遵循其所有者的通信和交互策略，并提供针对恶意代理攻击的保护。最先进的解决方案SAGA假设了一个逻辑上集中的信任点，即提供者，它充当用户和代理信息… | HIT、TRI | Matthew D. Laws |
| 10 | [$δ$-mem: Efficient Online Memory for Large Language Models](http://arxiv.org/abs/2605.12357v1) | 大型语言模型越来越需要在长期助手和代理系统中积累和重用历史信息。简单地扩展上下文窗口是昂贵的，并且通常无法确保有效的上下文利用。这些结果表明，通过紧凑的在线状态与注意力计算直接耦合，可以实现有效的记忆… | TRI | Jingdi Lei |
| 11 | [LISA: Cognitive Arbitration for Signal-Free Autonomous Inter…](http://arxiv.org/abs/2605.12321v1) | 大型语言模型（ LLM ）显示出智能交通系统（ ITS ）的巨大潜力，特别是在需要情境推理和多智能体协调的任务中。这些功能使其非常适合合作驾驶，在复杂和动态的交通环境中，基于规则的方法很难实现。这些结… | MIT | Abderrahmane Lakas |
| 12 | [Executable Agentic Memory for GUI Agent](http://arxiv.org/abs/2605.12294v1) | 现代GUI代理通常依赖于以模型为中心的分步交互范式，其中LLM必须重新解释UI并在每个屏幕上重新决定操作，这在长时间任务中是脆弱的。在本文中，我们提出了可执行代理内存（ EAM ） ，这是一种结构化的… | TRI | Zerui Qin |
| 13 | [PriorZero: Bridging Language Priors and World Models for Dec…](http://arxiv.org/abs/2605.12289v1) | 利用大型语言模型（ LLM ）的丰富知识来增强强化学习（ RL ）代理，为通用智能提供了一条充满希望的途径。然而，一个基本的先验动力学不匹配阻碍了现有的方法：静态LLM知识不能直接适应长视野任务的复杂… | MIT、NTU | Junyu Xiong |
| 14 | [Iterative Audit Convergence in LLM-Managed Multi-Agent Syste…](http://arxiv.org/abs/2605.12280v1) | 多智能体大型语言模型（ LLM ）系统的提示规范在许多相互依赖的文件中携带数据契约和集成逻辑，但很少受到结构化检查的严格约束。本文报告了应用于AEGIS （自主工程治理和智能系统）的迭代、代理驱动审计… | CAS、Mila | Elias Calboreanu |
| 15 | [No Action Without a NOD: A Heterogeneous Multi-Agent Archite…](http://arxiv.org/abs/2605.12240v1) | 大型语言模型（ LLM ）代理具有越来越先进的服务应用，例如预订机票。然而，这些服务代理在长期任务中受到不可靠性的影响，因为它们经常会产生策略违规、工具幻觉和错位行为，这极大地阻碍了他们在现实世界中的… | MIT、HIT | Zixu Yang |
| 16 | [Harness Engineering as Categorical Architecture](http://arxiv.org/abs/2605.12239v1) | 代理线束（包括围绕模型的提示、工具、内存和编排逻辑的系统层）已成为基于LLM的代理的中心工程抽象。然而，线束设计仍然是临时性的，没有正式的理论来管理组成、编译中属性的保存或跨框架的系统比较。结果将分类… | HIT、TRI | Bogdan Banu |
| 17 | [TMRL: Diffusion Timestep-Modulated Pretraining Enables Explo…](http://arxiv.org/abs/2605.12236v1) | 使用强化学习（ RL ）微调预训练机器人策略通常会继承使用行为克隆（ BC ）预训练引入的瓶颈，这会产生狭窄的动作分布，缺乏下游探索所需的覆盖范围。我们提出了一个统一的框架，通过桥接BC预训练和RL微… | MIT、TRI | Matthew M. Hong |
| 18 | [Intrinsic Vicarious Conditioning for Deep Reinforcement Lear…](http://arxiv.org/abs/2605.12224v1) | 强化学习的进步产生了各种复杂而有用的内在驱动力；至关重要的是，这些驱动力在直接条件范式下运行。这种制约形式通过限制我们的代理人从环境以及从其他人那里学习的方式来限制他们的能力。总的来说，这项工作模拟了… | MIT、TRI | Rodney A Sanchez |
| 19 | [TriBand-BEV: Real-Time LiDAR-Only 3D Pedestrian Detection vi…](http://arxiv.org/abs/2605.12220v1) | 安全的自动驾驶座席和移动机器人需要快速的实时3D感知，尤其是对于行人等弱势道路使用者（ VRU ）。我们引入了一种新的鸟瞰图（ BEV ）编码，它将完整的3D LiDAR点云映射到具有三个高度带的轻量… | TRI | Mohammad Khoshkdahan |
| 20 | [Goal-Oriented Reasoning for RAG-based Memory in Conversation…](http://arxiv.org/abs/2605.12213v1) | 由于上下文有限，基于法学硕士的会话式人工智能代理很难在长时间内保持连贯的行为。虽然越来越多地采用基于RAG的方法通过在外部存储模块中存储交互并从中进行检索来克服这一限制，但它们在回答具有挑战性的问题（… | MIT、Mila | Jiazhou Liang |

### 论文详情

<details>
<summary><b>1. MEME: Multi-entity & Evolving Memory Evaluation</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Seokwon Jung、Alexander Rubinstein、Arnas Uselis、Sangdoo Yun、Seong Joon Oh |
| **所属机构** | （详见原文） |
| **顶级机构标签** | CAS、TRI |
| **发布时间** | 2026-05-12T17:55:10Z |
| **关键词** | `Reasoning` · `RAG` · `Retrieval` · `Benchmark` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2605.12477v1](http://arxiv.org/abs/2605.12477v1) |

**📝 摘要概括：**

> 基于LLM的代理越来越多地在持久化环境中运行，他们必须在许多会话中存储、更新和推理信息。虽然先前的基准仅评估单个实体更新，但MEME定义了跨越多实体和不断演变的轴所定义的全部空间的六项任务，包括先前工作未评分的三项任务：级联和缺勤（依赖性推理）和删除（移除后状态）。代码和数据可在……上获得

</details>

<details>
<summary><b>2. KV-Fold: One-Step KV-Cache Recurrence for Long-Context Inference</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Alireza Nadali、Patrick Cooper、Ashutosh Trivedi、Alvaro Velasquez |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、HIT、TRI |
| **发布时间** | 2026-05-12T17:53:47Z |
| **关键词** | `Multi-Agent` · `Retrieval` · `Benchmark` · `Memory` |
| **原文链接** | [http://arxiv.org/abs/2605.12471v1](http://arxiv.org/abs/2605.12471v1) |

**📝 摘要概括：**

> 我们引入了KV-Fold ，这是一种简单、无需训练的长上下文推理协议，将关键值（ KV ）缓存视为序列块左侧折叠中的累加器。在每个步骤中，模型处理以累积缓存为条件的下一个块，追加新生成的键和值，并将放大的缓存向前传递；重复应用相同的一步更新，类似于函数式编程中的foldl。总的来说，我们的……

</details>

<details>
<summary><b>3. Multi-Stream LLMs: Unblocking Language Models with Parallel Streams of Thoughts, Inputs and Outputs</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Guinan Su、Yanwu Yang、Xueyan Li、Jonas Geiping |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、Mila |
| **发布时间** | 2026-05-12T17:47:41Z |
| **关键词** | `AI Agent` · `Chain-of-Thought` |
| **原文链接** | [http://arxiv.org/abs/2605.12460v1](http://arxiv.org/abs/2605.12460v1) |

**📝 摘要概括：**

> 语言模型功能的持续改进已经解锁了它们作为自主代理的驱动程序的广泛使用，例如在编码或计算机使用应用程序中。然而，自ChatGPT等早期指令优化模型以来，这些系统的核心并没有太大变化。我们认为，这种数据驱动的变化补救了如上所述的许多可用性限制，通过并行化提高了模型效率，改进了模型……

</details>

<details>
<summary><b>4. Predicting Decisions of AI Agents from Limited Interaction through Text-Tabular Modeling</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Eilam Shapira、Moshe Tennenholtz、Roi Reichart |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-05-12T17:09:32Z |
| **关键词** | `LLM Agent` · `AI Agent` |
| **原文链接** | [http://arxiv.org/abs/2605.12411v1](http://arxiv.org/abs/2605.12411v1) |

**📝 摘要概括：**

> 人工智能代理用自然语言与不熟悉的同行进行谈判和交易：面对未知卖家的买方机器人，或与供应商谈判的采购助理。在此类交互中，对方的LLM、提示、控制逻辑和基于规则的后备方案将被隐藏，而每个决策都可能产生金钱后果。这些结果表明，将对应预测制定为目标自适应文本表格任务可以有效地…

</details>

<details>
<summary><b>5. Events as Triggers for Behavioral Diversity in Multi-Agent Reinforcement Learning</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Hannes Büchi、Manon Flageat、Eduardo Sebastián、Amanda Prorok |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-05-12T16:51:23Z |
| **关键词** | `Multi-Agent` · `Reinforcement Learning` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2605.12388v1](http://arxiv.org/abs/2605.12388v1) |

**📝 摘要概括：**

> 有效的多代理合作要求代理在任务条件发生变化时采取不同的行为，并在适当的时候这样做。然而，目前促进这种多样性的多Agent强化学习（ MARL ）框架仍然受到限制，因为它们将固定行为与固定Agent身份绑定。实证结果表明，我们的框架在基准方面优于既定基准，同时表现出零...

</details>

<details>
<summary><b>6. ProfiliTable: Profiling-Driven Tabular Data Processing via Agentic Workflows</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Wei Liu、Yang Gu、Xi Yan、Zihan Nan、Beicheng Xu 等（共 8 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-05-12T16:42:38Z |
| **关键词** | `Multi-Agent` · `Agentic` · `Benchmark` · `Workflow` |
| **原文链接** | [http://arxiv.org/abs/2605.12376v1](http://arxiv.org/abs/2605.12376v1) |

**📝 摘要概括：**

> 表处理（包括清理、转换、增强和匹配）是现实数据管道中一个基本但容易出错的阶段。虽然最近基于LLM的方法显示出自动化此类任务的希望，但由于指令模糊、任务结构复杂和缺乏结构化反馈，它们在实践中经常遇到困难，从而导致语法正确但语义上有缺陷的代码。这些结果突出了关键的……

</details>

<details>
<summary><b>7. Agent-Based Post-Hoc Correction of Agricultural Yield Forecasts</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Matthew Beddows、Aiden Durrant、Georgios Leontidis |
| **所属机构** | （详见原文） |
| **顶级机构标签** | CAS、AI2 |
| **发布时间** | 2026-05-12T16:41:54Z |
| **关键词** | `LLM Agent` |
| **原文链接** | [http://arxiv.org/abs/2605.12375v1](http://arxiv.org/abs/2605.12375v1) |

**📝 摘要概括：**

> 商业软果生产中的准确作物产量预测受到典型商业农场记录中可用数据的限制，这些记录缺乏大多数最先进方法所假设的传感器网络、卫星图像和高分辨率气象输入。我们提出了一个结构化的LLM代理框架，该框架对现有模型预测进行事后校正，对跨工具的农业领域知识进行编码，以进行阶段…

</details>

<details>
<summary><b>8. Classifier Context Rot: Monitor Performance Degrades with Context Length</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Sam Martin、Fabien Roger |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT |
| **发布时间** | 2026-05-12T16:34:03Z |
| **关键词** | `Benchmark` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2605.12366v1](http://arxiv.org/abs/2605.12366v1) |

**📝 摘要概括：**

> 使用语言模型监控编码代理的危险行为需要对通常超过50万个令牌的成绩单进行分类，但先前的代理监控基准很少包含超过10万个令牌的成绩单。我们表明，当用作分类器时，当前的前沿模型无法在较长的转录本中更频繁地发现危险行为。不考虑长上下文退化的监控评估可能高估了监控……

</details>

<details>
<summary><b>9. Attacks and Mitigations for Distributed Governance of Agentic AI under Byzantine Adversaries</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Matthew D. Laws、Alina Oprea、Cristina Nita-Rotaru |
| **所属机构** | （详见原文） |
| **顶级机构标签** | HIT、TRI |
| **发布时间** | 2026-05-12T16:33:50Z |
| **关键词** | `Agentic` · `RAG` |
| **原文链接** | [http://arxiv.org/abs/2605.12364v1](http://arxiv.org/abs/2605.12364v1) |

**📝 摘要概括：**

> 代理AI治理是代理AI基础设施的关键组成部分，可确保代理遵循其所有者的通信和交互策略，并提供针对恶意代理攻击的保护。最先进的解决方案SAGA假设了一个逻辑上集中的信任点，即提供者，它充当用户和代理信息的存储库，并积极执行策略。我们讨论哪种解决方案最好，并且……

</details>

<details>
<summary><b>10. $δ$-mem: Efficient Online Memory for Large Language Models</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Jingdi Lei、Di Zhang、Junxian Li、Weida Wang、Kaixuan Fan 等（共 10 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-05-12T16:31:44Z |
| **关键词** | `RAG` · `Benchmark` · `Fine-tuning` · `Memory` |
| **原文链接** | [http://arxiv.org/abs/2605.12357v1](http://arxiv.org/abs/2605.12357v1) |

**📝 摘要概括：**

> 大型语言模型越来越需要在长期助手和代理系统中积累和重用历史信息。简单地扩展上下文窗口是昂贵的，并且通常无法确保有效的上下文利用。这些结果表明，通过紧凑的在线状态与注意力计算直接耦合，可以实现有效的记忆，而无需完全微调、主干替换或显式上下文扩展。

</details>

<details>
<summary><b>11. LISA: Cognitive Arbitration for Signal-Free Autonomous Intersection Management</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Abderrahmane Lakas、Mohamed Amine Ferrag、Merouane Debbah |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT |
| **发布时间** | 2026-05-12T16:04:50Z |
| **关键词** | `Multi-Agent` · `Reasoning` |
| **原文链接** | [http://arxiv.org/abs/2605.12321v1](http://arxiv.org/abs/2605.12321v1) |

**📝 摘要概括：**

> 大型语言模型（ LLM ）显示出智能交通系统（ ITS ）的巨大潜力，特别是在需要情境推理和多智能体协调的任务中。这些功能使其非常适合合作驾驶，在复杂和动态的交通环境中，基于规则的方法很难实现。这些结果表明，基于LLM的推理可以实现实时、无信号的交叉路口管理。

</details>

<details>
<summary><b>12. Executable Agentic Memory for GUI Agent</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Zerui Qin、Sheng Yue、Xingyuan Hua、Yongjian Fu、Ju Ren |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-05-12T15:48:44Z |
| **关键词** | `Agentic` · `Planning` · `RAG` · `Retrieval` · `Memory` |
| **原文链接** | [http://arxiv.org/abs/2605.12294v1](http://arxiv.org/abs/2605.12294v1) |

**📝 摘要概括：**

> 现代GUI代理通常依赖于以模型为中心的分步交互范式，其中LLM必须重新解释UI并在每个屏幕上重新决定操作，这在长时间任务中是脆弱的。在本文中，我们提出了可执行代理内存（ EAM ） ，这是一种结构化的知识图（ KG ） ，将GUI规划从自由形式生成转变为强大的检索和执行过程。EAM的平均延迟为$ 2.8 $ s ，可实现可靠、快速……

</details>

<details>
<summary><b>13. PriorZero: Bridging Language Priors and World Models for Decision Making</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Junyu Xiong、Yuan Pu、Jia Tang、Yazhe Niu |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、NTU |
| **发布时间** | 2026-05-12T15:47:18Z |
| **关键词** | `Planning` · `Reinforcement Learning` · `RAG` · `Benchmark` · `Fine-tuning` |
| **原文链接** | [http://arxiv.org/abs/2605.12289v1](http://arxiv.org/abs/2605.12289v1) |

**📝 摘要概括：**

> 利用大型语言模型（ LLM ）的丰富知识来增强强化学习（ RL ）代理，为通用智能提供了一条充满希望的途径。然而，一个基本的先验动力学不匹配阻碍了现有的方法：静态LLM知识不能直接适应长视野任务的复杂过渡动力学。我们的代码可在https://github.com/opendilab/LightZero上找到。

</details>

<details>
<summary><b>14. Iterative Audit Convergence in LLM-Managed Multi-Agent Systems: A Case Study in Prompt Engineering Quality Assurance</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Elias Calboreanu |
| **所属机构** | （详见原文） |
| **顶级机构标签** | CAS、Mila、TRI |
| **发布时间** | 2026-05-12T15:39:04Z |
| **关键词** | `Multi-Agent` |
| **原文链接** | [http://arxiv.org/abs/2605.12280v1](http://arxiv.org/abs/2605.12280v1) |

**📝 摘要概括：**

> 多智能体大型语言模型（ LLM ）系统的提示规范在许多相互依赖的文件中携带数据契约和集成逻辑，但很少受到结构化检查的严格约束。本文报告了应用于AEGIS （自主工程治理和智能系统）的迭代、代理驱动审计的单系统实证案例研究， AEGIS是一种生产七通道编排管道，其即时规范…

</details>

<details>
<summary><b>15. No Action Without a NOD: A Heterogeneous Multi-Agent Architecture for Reliable Service Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Zixu Yang、Hang Zheng、Nan Jiang、Zhiyang Tang、Situo Zhang 等（共 8 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、HIT |
| **发布时间** | 2026-05-12T15:10:15Z |
| **关键词** | `Multi-Agent` |
| **原文链接** | [http://arxiv.org/abs/2605.12240v1](http://arxiv.org/abs/2605.12240v1) |

**📝 摘要概括：**

> 大型语言模型（ LLM ）代理具有越来越先进的服务应用，例如预订机票。然而，这些服务代理在长期任务中受到不可靠性的影响，因为它们经常会产生策略违规、工具幻觉和错位行为，这极大地阻碍了他们在现实世界中的部署。更重要的是， NOD通过减少政策违规、工具幻觉和……来提高服务代理的可靠性。

</details>

<details>
<summary><b>16. Harness Engineering as Categorical Architecture</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Bogdan Banu |
| **所属机构** | （详见原文） |
| **顶级机构标签** | HIT、TRI |
| **发布时间** | 2026-05-12T15:09:46Z |
| **关键词** | `LLM Agent` · `Memory` |
| **原文链接** | [http://arxiv.org/abs/2605.12239v1](http://arxiv.org/abs/2605.12239v1) |

**📝 摘要概括：**

> 代理线束（包括围绕模型的提示、工具、内存和编排逻辑的系统层）已成为基于LLM的代理的中心工程抽象。然而，线束设计仍然是临时性的，没有正式的理论来管理组成、编译中属性的保存或跨框架的系统比较。结果将分类架构定位为线束引擎背后的形式理论……

</details>

<details>
<summary><b>17. TMRL: Diffusion Timestep-Modulated Pretraining Enables Exploration for Efficient Policy Finetuning</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Matthew M. Hong、Jesse Zhang、Anusha Nagabandi、Abhishek Gupta |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-05-12T15:07:04Z |
| **关键词** | `Reinforcement Learning` · `RAG` · `Fine-tuning` |
| **原文链接** | [http://arxiv.org/abs/2605.12236v1](http://arxiv.org/abs/2605.12236v1) |

**📝 摘要概括：**

> 使用强化学习（ RL ）微调预训练机器人策略通常会继承使用行为克隆（ BC ）预训练引入的瓶颈，这会产生狭窄的动作分布，缺乏下游探索所需的覆盖范围。我们提出了一个统一的框架，通过桥接BC预训练和RL微调，实现必要的探索，以实现高效的机器人策略微调。可用的视频和代码……

</details>

<details>
<summary><b>18. Intrinsic Vicarious Conditioning for Deep Reinforcement Learning</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Rodney A Sanchez、Ferat Sahin、Alex Ororbia、Jamison Heard |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-05-12T15:01:37Z |
| **关键词** | `Reinforcement Learning` · `RAG` · `Memory` |
| **原文链接** | [http://arxiv.org/abs/2605.12224v1](http://arxiv.org/abs/2605.12224v1) |

**📝 摘要概括：**

> 强化学习的进步产生了各种复杂而有用的内在驱动力；至关重要的是，这些驱动力在直接条件范式下运行。这种制约形式通过限制我们的代理人从环境以及从其他人那里学习的方式来限制他们的能力。总的来说，这项工作模拟了一种认知上合理的学习范式，更适合单身学习或持续学习等问题。

</details>

<details>
<summary><b>19. TriBand-BEV: Real-Time LiDAR-Only 3D Pedestrian Detection via Height-Aware BEV and High-Resolution Feature Fusion</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Mohammad Khoshkdahan、Alexey Vinel |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-05-12T14:58:16Z |
| **关键词** | — |
| **原文链接** | [http://arxiv.org/abs/2605.12220v1](http://arxiv.org/abs/2605.12220v1) |

**📝 摘要概括：**

> 安全的自动驾驶座席和移动机器人需要快速的实时3D感知，尤其是对于行人等弱势道路使用者（ VRU ）。我们引入了一种新的鸟瞰图（ BEV ）编码，它将完整的3D LiDAR点云映射到具有三个高度带的轻量级2D BEV张量中。我们的源代码可在GitHub上公开获取。

</details>

<details>
<summary><b>20. Goal-Oriented Reasoning for RAG-based Memory in Conversational Agentic LLM Systems</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Jiazhou Liang、Armin Toroghi、Yifan Simon Liu、Faeze Moradi Kalarde、Liam Gallagher 等（共 6 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、Mila、TRI |
| **发布时间** | 2026-05-12T14:51:02Z |
| **关键词** | `AI Agent` · `Agentic` · `Reasoning` · `RAG` · `Retrieval` |
| **原文链接** | [http://arxiv.org/abs/2605.12213v1](http://arxiv.org/abs/2605.12213v1) |

**📝 摘要概括：**

> 由于上下文有限，基于法学硕士的会话式人工智能代理很难在长时间内保持连贯的行为。虽然越来越多地采用基于RAG的方法通过在外部存储模块中存储交互并从中进行检索来克服这一限制，但它们在回答具有挑战性的问题（例如，多跳，常识）方面的有效性最终取决于代理对检索到的信息进行推理的能力……

</details>

## 🗄️ 历史归档

| 日期 | 论文数 | 报告链接 |
|------|--------|----------|
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

*由 [clawBot DailyFindings](https://github.com/Jacob-biu/clawBot) 自动维护 | 最后更新：2026-05-13 23:09 UTC*
