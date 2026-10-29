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

## 📅 今日论文 — 2026-10-29　　[→ 查看完整报告](daily/2026-10-29.md)

> 共筛选出 **20** 篇论文 | 更新于 2026-10-29 01:32 UTC

### 论文目录与概要

| # | 论文标题 | 核心概要 | 来源机构 | 第一作者 |
|---|---------|---------|---------|--------|
| 1 | [Heads of Security: Learned Attention Gates Improve Prompt In…](http://arxiv.org/abs/2610.37657v1) | 我们引入了安全负责人（ HoS ） ，这是一种提示注入防御，通过一小部分学习的每头注意门强制执行指令数据分离。HoS了解每个HEAD如何在受信任和不受信任的令牌之间重新分配注意力，使模型能够在不遵循注… | HIT、Mila | Igor Shilov |
| 2 | [Rare, Relevant, and Still Wrong: How Memory Fails LLM Group …](http://arxiv.org/abs/2610.37624v1) | 当法学硕士小组的讨论被压缩成最终决策者的短暂记忆时，记忆应该保留什么？两种自然启发法保留了最罕见的主张或与决策标准相关的主张。在自然讨论中，证据在任何记忆作用之前都会丢失：完整的成绩单的准确性低于完全… | MIT、CAS | Anouar Imel |
| 3 | [EnvSched: Environment-Aware Scheduling for Rollout-Efficient…](http://arxiv.org/abs/2610.37609v1) | 随着语言代理的可执行环境的扩展，生成和验证其部署变得越来越昂贵。在有限的推出预算下，这提出了一个重要问题：环境层面的数据管理是否可以通过组织、评估和调度任务实例以及确定其工具、状态、转换和验证的环境来… | MIT、Mila | Sihan Yang |
| 4 | [Understanding the limits of latent world models](http://arxiv.org/abs/2610.37588v1) | 世界模型被广泛提出作为核心组件，使主体能够在漫长的时间和空间视野中进行推理。然而，目前的评估往往强调任务绩效，同时对学习世界模型是否获得反映环境底层结构的预测性潜在动态提供有限的见解。引人注目的是，我… | MIT、TRI | Rodrigo Gonzalez Laiz |
| 5 | [TeamGym: A Gym for Team Decision-Making by AI Agents with Di…](http://arxiv.org/abs/2610.37571v1) | 许多现实世界的决策要求团队整合分布在参与者之间的信息。然而，人工智能代理仍然主要是孤立地接受培训和基准测试。在两个政策培训实验中，我们发现培训提高了最终决策质量，并在参与、演讲者选择和沟通方面引起了紧… | TRI | Chanwoo Park |
| 6 | [Gym-Anything-RT: Scaling Real-Time Environments for Vision-L…](http://arxiv.org/abs/2610.37567v1) | 人工智能代理在数学、软件工程和在桌面应用程序上执行任务等领域取得了重大进展，在这些领域中，他们需要花费大量的时间来考虑各种操作。目前尚不清楚这些模型在需要实时交互的设置（例如玩视频游戏或操作物理设备）… | TRI | Pranjal Aggarwal |
| 7 | [Strategyproof Deep Reinforcement Learning for Online Resourc…](http://arxiv.org/abs/2610.37504v1) | 在线资源配置面临两个耦合的挑战： （ 1 ）在不确定的未来需求下有效分配稀缺资源； （ 2 ）确保代理如实报告任务估值和需求（策略证明）。强化学习（ RL ）通过经验调整分配决策，但不一定确保策略的可… | MIT | Fariba Dehghan |
| 8 | [PerceptRL: Making Visual Perception Rewardable in MLLMs from…](http://arxiv.org/abs/2610.37471v1) | 在多模态大型语言模型（ MLLM ）的后期训练中，细粒度视觉感知仍然是一个瓶颈，因为感知误差会限制以推理为重点的优化所带来的收益。虽然图像字幕预训练可以改善感知，但随着后续阶段改变数据混合和目标，其影… | CAS | Tongkun Guan |
| 9 | [M4Bench: Evaluating Procedural Specification for Clinical EH…](http://arxiv.org/abs/2610.37459v1) | 对电子健康记录的临床研究依赖于派生变量，其定义位于模式之外，包括项目代码、时间窗口、缺失规则以及改变队列和下游结论的输出粒度选择。我们介绍了M4Bench ，这是MIMIC-IV和eICU上跨15个任… | TRI | Hannes Ill |
| 10 | [Interpretable Meta-Policies for Neural Decision Making](http://arxiv.org/abs/2610.37451v1) | 由于神经网络的黑盒性质，深度强化学习仍然难以解释和对齐。虽然（神经）符号方法通过整合符号推理来提高透明度，但将它们直接应用于低级行动会导致过于复杂、不可读的政策。最后，我们分离和评估了不同的元策略架构… | HIT、TRI | Raban Emunds |
| 11 | [Test-Time Communication in Trading Agent Swarms](http://arxiv.org/abs/2610.37448v1) | 客服代表之间的沟通主要针对具有共同目标和快速、清晰的反馈的任务进行研究。交易两者都没有：每个代理商管理自己的账户，决策被市场迟到和吵闹地评分。由于孤立的群体也收敛于相同的种群，有时甚至完全收敛，因此牧… | CAS | Avid Fayaz |
| 12 | [FeatureArc: Benchmarking Coding Agents on Evolving Features](http://arxiv.org/abs/2610.37434v1) | 软件功能通常会随着时间的推移而发展：开发人员会随着新的用例和要求的出现而扩展其第一个版本，并且每个扩展都基于之前编写的代码。大多数功能基准评估固定代码库上的单个请求。在腾讯，该管道将内部评估扩展到此设… | Tencent、NYU | Yunlong Wang |
| 13 | [Constraining the Commit Boundary: A DIO/ODI-Informed Authori…](http://arxiv.org/abs/2610.37407v1) | 代理实体解析（ ER ）系统可以迭代计划行动、检索证据、修改假设和提出图形突变。错误的身份假设可能会导致后期检索并产生明显的确认。它不能防止错误的假设或假设条件检索；感知依赖性的证据流仍是未来的研究。 | MIT、HIT | Daniel Beránek |
| 14 | [Clearing the FoG: Training KG Agents to Retrieve the Evidenc…](http://arxiv.org/abs/2610.37405v1) | 大型语言模型（ LLM ）可以正确回答许多事实问题，但正确答案不一定是受支持的答案。对于LLM代理，知识图谱（ KG ）扮演两个角色：作为答案来源，它提供模型缺乏的事实；作为证据来源，它提供使答案可追… | TRI | Zongyuan Sun |
| 15 | [Aligning Institutional Power and Operational Ability](http://arxiv.org/abs/2610.37342v1) | 为了实现社会可持续性， Agentic AI系统需要规范性设计，使责任与履行责任的能力保持一致。识别不一致之处，如无法满足的期望或特权升级，对于避免规范陷阱至关重要。我们提出了一个以面向过程的建模和制… | TRI | Andrea Marino |
| 16 | [WCC: A Learning-Based Framework for Deciding When to Apply C…](http://arxiv.org/abs/2610.37329v1) | 协同协同进化（ CC ）和非分解算法（ NDA ）是大规模全局优化（ LSGO ）的两种主要方法。虽然两者都取得了成功，但它们在各种问题类型中表现出明显不同的表现，并且每种问题都面临着特定方法的局限性… | MIT、HIT | Wenjie Qiu |
| 17 | [AnalogScout: Simulation-Efficient PVT-Aware Analog Sizing wi…](http://arxiv.org/abs/2610.37319v1) | 模拟器件尺寸必须满足工艺、电压和温度（ PVT ）角的所有规格，以确保磁带输出成功，但模拟每个角落的每个候选器件都占据了尺寸调整时间的主导地位，并减慢了设计迭代。传统的基于代理的优化器直接搜索大小空间… | MIT | Yichen Long |
| 18 | [Your Policy Is Secretly a Harness: The Decision Geometry of …](http://arxiv.org/abs/2610.37255v1) | 语言模型代理通过线束、提示、工具和控制逻辑进行后期训练和部署，这些提示、工具和控制逻辑将任务呈现给模型并执行其输出。线束通常根据已经训练过的模型在线束下的表现进行修订和判断，假设模型在一个线束下学到的… | NUS | Jian Mu |
| 19 | [Grounding LLM Agents in Business Processes: Process-Aware Kn…](http://arxiv.org/abs/2610.37242v1) | 调用企业API的大型语言模型(LLM)代理必须选择正确的端点，遵循流程顺序，使用有效的有效负载密钥，并从预定义列表中选择编码值。但是，当前检索增强服务发现会独立处理端点，因此会错过进程和架构约束。这些… | MIT、TRI | Saiful Khan |
| 20 | [Spine: Compiling Subtask Trees into Structured Context for L…](http://arxiv.org/abs/2610.37224v1) | 长距离编码任务包含嵌套子任务。通常，客服代表会按顺序将互动记录到不断增长的历史记录中，从而导致上下文膨胀和绩效下降。我们还通过可重用的软件包将Spine集成到Pi中：使用Gemini 3.8 Flas… | TRI | Jiahong Xiang |

### 论文详情

<details>
<summary><b>1. Heads of Security: Learned Attention Gates Improve Prompt Injection Robustness</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Igor Shilov、Xiaoxue Yang、Alexander Panfilov、Evgenii Kortukov、Matthieu Meeus 等（共 9 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | HIT、Mila、TRI |
| **发布时间** | 2026-10-27T17:58:52Z |
| **关键词** | `Agentic` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2610.37657v1](http://arxiv.org/abs/2610.37657v1) |

**📝 摘要概括：**

> 我们引入了安全负责人（ HoS ） ，这是一种提示注入防御，通过一小部分学习的每头注意门强制执行指令数据分离。HoS了解每个HEAD如何在受信任和不受信任的令牌之间重新分配注意力，使模型能够在不遵循注入指令的情况下推理不受信任的内容。这些结果表明，通过有针对性的关注，可以实现和提高快速注射的鲁棒性……

</details>

<details>
<summary><b>2. Rare, Relevant, and Still Wrong: How Memory Fails LLM Group Decisions</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Anouar Imel、Imad Charradi、Abderrahman Sghir、Khalil El Khammar |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、CAS、TRI |
| **发布时间** | 2026-10-27T17:49:39Z |
| **关键词** | `RAG` · `Benchmark` · `Memory` |
| **原文链接** | [http://arxiv.org/abs/2610.37624v1](http://arxiv.org/abs/2610.37624v1) |

**📝 摘要概括：**

> 当法学硕士小组的讨论被压缩成最终决策者的短暂记忆时，记忆应该保留什么？两种自然启发法保留了最罕见的主张或与决策标准相关的主张。在自然讨论中，证据在任何记忆作用之前都会丢失：完整的成绩单的准确性低于完全没有音符的准确性。

</details>

<details>
<summary><b>3. EnvSched: Environment-Aware Scheduling for Rollout-Efficient Agent Reinforcement Learning</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Sihan Yang、Weichen Bai、Ruichuan An、Yiming Cheng、Zhiyuan Feng 等（共 12 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、Mila |
| **发布时间** | 2026-10-27T17:38:52Z |
| **关键词** | `Agentic` · `Reinforcement Learning` · `RAG` |
| **原文链接** | [http://arxiv.org/abs/2610.37609v1](http://arxiv.org/abs/2610.37609v1) |

**📝 摘要概括：**

> 随着语言代理的可执行环境的扩展，生成和验证其部署变得越来越昂贵。在有限的推出预算下，这提出了一个重要问题：环境层面的数据管理是否可以通过组织、评估和调度任务实例以及确定其工具、状态、转换和验证的环境来提高代理强化学习（ RL ）的效率？它…

</details>

<details>
<summary><b>4. Understanding the limits of latent world models</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Rodrigo Gonzalez Laiz、Steffen Schneider |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-10-27T17:25:50Z |
| **关键词** | `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2610.37588v1](http://arxiv.org/abs/2610.37588v1) |

**📝 摘要概括：**

> 世界模型被广泛提出作为核心组件，使主体能够在漫长的时间和空间视野中进行推理。然而，目前的评估往往强调任务绩效，同时对学习世界模型是否获得反映环境底层结构的预测性潜在动态提供有限的见解。引人注目的是，我们发现，在所研究的最先进的潜在世界模型中，没有一个能通过动作来解决这项任务……

</details>

<details>
<summary><b>5. TeamGym: A Gym for Team Decision-Making by AI Agents with Distributed Information</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Chanwoo Park、Jaywoong Jeong、Zachary Wojtowicz、Yubin Kim、Taekyun Lee 等（共 7 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-10-27T17:15:54Z |
| **关键词** | `AI Agent` · `Reinforcement Learning` · `RAG` · `Retrieval` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2610.37571v1](http://arxiv.org/abs/2610.37571v1) |

**📝 摘要概括：**

> 许多现实世界的决策要求团队整合分布在参与者之间的信息。然而，人工智能代理仍然主要是孤立地接受培训和基准测试。在两个政策培训实验中，我们发现培训提高了最终决策质量，并在参与、演讲者选择和沟通方面引起了紧急协调，即使奖励仅评估最终决策。

</details>

<details>
<summary><b>6. Gym-Anything-RT: Scaling Real-Time Environments for Vision-Language Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Pranjal Aggarwal、Sean Welleck |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-10-27T17:13:05Z |
| **关键词** | `AI Agent` · `Agentic` · `Reasoning` |
| **原文链接** | [http://arxiv.org/abs/2610.37567v1](http://arxiv.org/abs/2610.37567v1) |

**📝 摘要概括：**

> 人工智能代理在数学、软件工程和在桌面应用程序上执行任务等领域取得了重大进展，在这些领域中，他们需要花费大量的时间来考虑各种操作。目前尚不清楚这些模型在需要实时交互的设置（例如玩视频游戏或操作物理设备）中的表现如何。我们公开发布Gym-Anything-RT和生成的迷你游戏，以刺激进一步的研究……

</details>

<details>
<summary><b>7. Strategyproof Deep Reinforcement Learning for Online Resource Allocation</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Fariba Dehghan、Sebastian Stein、Vahid Yazdanpanah、Stephanie Gauthier |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT |
| **发布时间** | 2026-10-27T16:25:28Z |
| **关键词** | `Reinforcement Learning` |
| **原文链接** | [http://arxiv.org/abs/2610.37504v1](http://arxiv.org/abs/2610.37504v1) |

**📝 摘要概括：**

> 在线资源配置面临两个耦合的挑战： （ 1 ）在不确定的未来需求下有效分配稀缺资源； （ 2 ）确保代理如实报告任务估值和需求（策略证明）。强化学习（ RL ）通过经验调整分配决策，但不一定确保策略的可靠性。此外，模仿在261秒内达到97.5% ，比RL快约89倍。

</details>

<details>
<summary><b>8. PerceptRL: Making Visual Perception Rewardable in MLLMs from Answers to Interactions</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Tongkun Guan、Zhibo Yang、Mingkun Yang、Haocheng Wang、Wei Shen 等（共 6 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | CAS |
| **发布时间** | 2026-10-27T16:04:10Z |
| **关键词** | `Multi-Agent` · `Agentic` · `Reasoning` · `RAG` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2610.37471v1](http://arxiv.org/abs/2610.37471v1) |

**📝 摘要概括：**

> 在多模态大型语言模型（ MLLM ）的后期训练中，细粒度视觉感知仍然是一个瓶颈，因为感知误差会限制以推理为重点的优化所带来的收益。虽然图像字幕预训练可以改善感知，但随着后续阶段改变数据混合和目标，其影响可能会减弱。在共享工具使用协议下的七个基准中， PerceptRL实现了71.6%的平均准确率，超过了……

</details>

<details>
<summary><b>9. M4Bench: Evaluating Procedural Specification for Clinical EHR Derivation Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Hannes Ill、Rafi Al Attrach、Rajna Fani、Ahram Han、Ryohei Yamamoto 等（共 8 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-10-27T15:59:13Z |
| **关键词** | `Benchmark` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2610.37459v1](http://arxiv.org/abs/2610.37459v1) |

**📝 摘要概括：**

> 对电子健康记录的临床研究依赖于派生变量，其定义位于模式之外，包括项目代码、时间窗口、缺失规则以及改变队列和下游结论的输出粒度选择。我们介绍了M4Bench ，这是MIMIC-IV和eICU上跨15个任务系列的28个临床衍生任务，以测试AI编码代理是否可以重现这种衍生，以及临床医生审查的代理技能如何改变……

</details>

<details>
<summary><b>10. Interpretable Meta-Policies for Neural Decision Making</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Raban Emunds、Jannis Blüml、Quentin Delfosse、Kristian Kersting |
| **所属机构** | （详见原文） |
| **顶级机构标签** | HIT、TRI |
| **发布时间** | 2026-10-27T15:55:05Z |
| **关键词** | `Reasoning` · `Reinforcement Learning` |
| **原文链接** | [http://arxiv.org/abs/2610.37451v1](http://arxiv.org/abs/2610.37451v1) |

**📝 摘要概括：**

> 由于神经网络的黑盒性质，深度强化学习仍然难以解释和对齐。虽然（神经）符号方法通过整合符号推理来提高透明度，但将它们直接应用于低级行动会导致过于复杂、不可读的政策。最后，我们分离和评估了不同的元策略架构（神经、符号、神经符号）对环境回报和回报的影响。

</details>

<details>
<summary><b>11. Test-Time Communication in Trading Agent Swarms</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Avid Fayaz、Harry Zhang、Håvard Alstadheim、Erik Nordlöf、Vilhelm Karlin 等（共 6 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | CAS |
| **发布时间** | 2026-10-27T15:54:05Z |
| **关键词** | — |
| **原文链接** | [http://arxiv.org/abs/2610.37448v1](http://arxiv.org/abs/2610.37448v1) |

**📝 摘要概括：**

> 客服代表之间的沟通主要针对具有共同目标和快速、清晰的反馈的任务进行研究。交易两者都没有：每个代理商管理自己的账户，决策被市场迟到和吵闹地评分。由于孤立的群体也收敛于相同的种群，有时甚至完全收敛，因此牧群评估需要测量相对于无同行基线的过度收敛。

</details>

<details>
<summary><b>12. FeatureArc: Benchmarking Coding Agents on Evolving Features</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Yunlong Wang、Alyssa Wu、Cuiyun Gao、Jia Feng、Songyuanyi Lu 等（共 6 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | Tencent、NYU、CAS |
| **发布时间** | 2026-10-27T15:45:50Z |
| **关键词** | `Benchmark` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2610.37434v1](http://arxiv.org/abs/2610.37434v1) |

**📝 摘要概括：**

> 软件功能通常会随着时间的推移而发展：开发人员会随着新的用例和要求的出现而扩展其第一个版本，并且每个扩展都基于之前编写的代码。大多数功能基准评估固定代码库上的单个请求。在腾讯，该管道将内部评估扩展到此设置，并指导腾讯大型语言模型系列Hunyuan的开发。

</details>

<details>
<summary><b>13. Constraining the Commit Boundary: A DIO/ODI-Informed Authorization Guardrail for Agentic Entity Resolution</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Daniel Beránek |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、HIT、TRI |
| **发布时间** | 2026-10-27T15:22:00Z |
| **关键词** | `Agentic` · `Reasoning` · `RAG` · `Retrieval` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2610.37407v1](http://arxiv.org/abs/2610.37407v1) |

**📝 摘要概括：**

> 代理实体解析（ ER ）系统可以迭代计划行动、检索证据、修改假设和提出图形突变。错误的身份假设可能会导致后期检索并产生明显的确认。它不能防止错误的假设或假设条件检索；感知依赖性的证据流仍是未来的研究。

</details>

<details>
<summary><b>14. Clearing the FoG: Training KG Agents to Retrieve the Evidence Behind Their Answers</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Zongyuan Sun、Shuai Zhao、Yingjun Du、Ke Shu、Ziyue Zhu 等（共 6 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-10-27T15:20:37Z |
| **关键词** | `LLM Agent` · `RAG` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2610.37405v1](http://arxiv.org/abs/2610.37405v1) |

**📝 摘要概括：**

> 大型语言模型（ LLM ）可以正确回答许多事实问题，但正确答案不一定是受支持的答案。对于LLM代理，知识图谱（ KG ）扮演两个角色：作为答案来源，它提供模型缺乏的事实；作为证据来源，它提供使答案可追溯和可审计的支持三元组。三个KGQA基准的实验表明， FoG支持3B--4B开源代理……

</details>

<details>
<summary><b>15. Aligning Institutional Power and Operational Ability</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Andrea Marino、Giovanni Sileno、Thomas van Binsbergen、Tom van Engers |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-10-27T14:47:58Z |
| **关键词** | `Multi-Agent` · `Agentic` |
| **原文链接** | [http://arxiv.org/abs/2610.37342v1](http://arxiv.org/abs/2610.37342v1) |

**📝 摘要概括：**

> 为了实现社会可持续性， Agentic AI系统需要规范性设计，使责任与履行责任的能力保持一致。识别不一致之处，如无法满足的期望或特权升级，对于避免规范陷阱至关重要。我们提出了一个以面向过程的建模和制度权力为中心的正式框架，用于分析给定的规范性相关过程，讨论修复它的策略，以及……

</details>

<details>
<summary><b>16. WCC: A Learning-Based Framework for Deciding When to Apply Cooperative Coevolution in Large-Scale Optimization</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Wenjie Qiu、Hepei Li、Jianfeng Wang、Jun Zhang、Yue-Jiao Gong |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、HIT |
| **发布时间** | 2026-10-27T14:37:10Z |
| **关键词** | — |
| **原文链接** | [http://arxiv.org/abs/2610.37329v1](http://arxiv.org/abs/2610.37329v1) |

**📝 摘要概括：**

> 协同协同进化（ CC ）和非分解算法（ NDA ）是大规模全局优化（ LSGO ）的两种主要方法。虽然两者都取得了成功，但它们在各种问题类型中表现出明显不同的表现，并且每种问题都面临着特定方法的局限性，使得“何时使用CC”的问题未得到解决。此外，深入分析产生现有理论未捕获的见解，为……提供实用指导

</details>

<details>
<summary><b>17. AnalogScout: Simulation-Efficient PVT-Aware Analog Sizing with LLM Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Yichen Long、Keren Zhu |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT |
| **发布时间** | 2026-10-27T14:33:02Z |
| **关键词** | `LLM Agent` · `Simulation` |
| **原文链接** | [http://arxiv.org/abs/2610.37319v1](http://arxiv.org/abs/2610.37319v1) |

**📝 摘要概括：**

> 模拟器件尺寸必须满足工艺、电压和温度（ PVT ）角的所有规格，以确保磁带输出成功，但模拟每个角落的每个候选器件都占据了尺寸调整时间的主导地位，并减慢了设计迭代。传统的基于代理的优化器直接搜索大小空间，而最近的大型语言模型（ LLM ）代理将电路知识添加到设计中，但仍然将大小委托给全局优化器。它也是……

</details>

<details>
<summary><b>18. Your Policy Is Secretly a Harness: The Decision Geometry of Agent Interfaces</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Jian Mu、Ruibo Shen、Yao Shu |
| **所属机构** | （详见原文） |
| **顶级机构标签** | NUS |
| **发布时间** | 2026-10-27T13:52:25Z |
| **关键词** | — |
| **原文链接** | [http://arxiv.org/abs/2610.37255v1](http://arxiv.org/abs/2610.37255v1) |

**📝 摘要概括：**

> 语言模型代理通过线束、提示、工具和控制逻辑进行后期训练和部署，这些提示、工具和控制逻辑将任务呈现给模型并执行其输出。线束通常根据已经训练过的模型在线束下的表现进行修订和判断，假设模型在一个线束下学到的东西会传递到下一个线束。优惠码可在https://github.com/2020-qqtcg/HRP上获得。

</details>

<details>
<summary><b>19. Grounding LLM Agents in Business Processes: Process-Aware Knowledge Graphs for Reliable Multi-Step Service Invocation</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Saiful Khan、Afrah Farea |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-10-27T13:45:29Z |
| **关键词** | `LLM Agent` · `Retrieval` |
| **原文链接** | [http://arxiv.org/abs/2610.37242v1](http://arxiv.org/abs/2610.37242v1) |

**📝 摘要概括：**

> 调用企业API的大型语言模型(LLM)代理必须选择正确的端点，遵循流程顺序，使用有效的有效负载密钥，并从预定义列表中选择编码值。但是，当前检索增强服务发现会独立处理端点，因此会错过进程和架构约束。这些结果表明，在检索过程中暴露过程和模式约束提高了代理驱动A的可靠性。

</details>

<details>
<summary><b>20. Spine: Compiling Subtask Trees into Structured Context for Long-Horizon Coding Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Jiahong Xiang、Kunqiu Chen、Lingming Zhang、Yuqun Zhang |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-10-27T13:33:23Z |
| **关键词** | `RAG` |
| **原文链接** | [http://arxiv.org/abs/2610.37224v1](http://arxiv.org/abs/2610.37224v1) |

**📝 摘要概括：**

> 长距离编码任务包含嵌套子任务。通常，客服代表会按顺序将互动记录到不断增长的历史记录中，从而导致上下文膨胀和绩效下降。我们还通过可重用的软件包将Spine集成到Pi中：使用Gemini 3.8 Flash和Qwen 3.8 27B ，与原生Pi相比，它将SWE-Milestone得分提高了9.5-17.5% ，平均ProgramBench测试通过率提高了4.3-8.7%。

</details>

## 🗄️ 历史归档

| 日期 | 论文数 | 报告链接 |
|------|--------|----------|
| 2026-10-29 | 20 篇 | [2026-10-29.md](daily/2026-10-29.md) |
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

## 🏛️ 顶级机构覆盖范围

覆盖超过 **70 个**顶级 AI 机构，包括：

- **科技公司：** Microsoft、Google DeepMind、OpenAI、Anthropic、Meta AI、NVIDIA、Baidu、Alibaba、ByteDance 等
- **北美顶级大学：** MIT、Stanford、CMU、UC Berkeley、Harvard、Princeton、Cornell、Caltech 等
- **中国顶级大学/机构：** 清华大学、北京大学、浙大、上交大、复旦、中科院、MSRA 等
- **欧洲/其他：** Oxford、Cambridge、ETH Zurich、Mila、NUS、KAIST 等

---

*由 [clawBot DailyFindings](https://github.com/Jacob-biu/clawBot) 自动维护 | 最后更新：2026-10-29 01:32 UTC*
