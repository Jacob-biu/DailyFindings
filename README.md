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

## 📅 今日论文 — 2026-06-03　　[→ 查看完整报告](daily/2026-06-03.md)

> 共筛选出 **20** 篇论文 | 更新于 2026-06-03 23:43 UTC

### 论文目录与概要

| # | 论文标题 | 核心概要 | 来源机构 | 第一作者 |
|---|---------|---------|---------|--------|
| 1 | [Using Reward Uncertainty to Induce Diverse Behaviour in Rein…](http://arxiv.org/abs/2606.03962v1) | 经典强化学习（ RL ）通常寻求一种确定性策略，使标量奖励的预期总和最大化。然而，语言模型微调或科学发现等现代应用需要多样性。我们的实证结果表明，该框架为复杂的强化学习任务提供了一个强大且理论基础的替… | MIT、CAS | Anthony GX-Chen |
| 2 | [VLESA: Vision-Language Embodied Safety Agent for Human Activ…](http://arxiv.org/abs/2606.03954v1) | 随着人工智能系统越来越多地帮助人类完成物理任务，确保安全变得至关重要--物理行为会带来数字错误所没有的直接和不可逆转的后果。我们推出了Vision-Language Embodied Safety A… | TRI | Hanjiang Hu |
| 3 | [Hedge-Bench: Benchmarking Agents on Hard, Realistic Tasks Pe…](http://arxiv.org/abs/2606.03918v1) | 人工智能代理可以越来越多地处理财务分析的机械任务：检索文档、计算公式、更新电子表格。更困难、更有价值的挑战是通过定义专家分析师工作的开放式问题进行推理。我们在github.com/Trata-Inc/… | TRI | Eric Cho |
| 4 | [The Impact of Configuring Agentic AI Coding Tools on Build-v…](http://arxiv.org/abs/2606.03907v1) | Agentic AI编码工具以越来越大的自主权编写代码，并在此过程中决定何时导入库以及何时从头开始实施功能。这些决定，无论是从头开始构建功能还是购买外部库（以下简称“构建与购买” ） ，都会对软件安全… | OpenAI | Jai Lal Lulla |
| 5 | [Agent libOS: A Library-OS-Inspired Runtime for Long-Running,…](http://arxiv.org/abs/2606.03895v1) | 大型语言模型（ LLM ）代理正在从请求响应助理演变为长期运行的软件参与者：他们跨模型调用维护状态，分叉子任务，等待外部事件，请求人为权限，生成工具，并执行必须恢复和审计的副作用。本文介绍了Agent… | MIT | Yingqi Zhang |
| 6 | [From 'What' to 'How' and 'Why': Sharing LLM-Generated Retros…](http://arxiv.org/abs/2606.03876v1) | 随着现代无处不在的计算技术的日益普及，多模式跟踪系统有望为利益相关者提供及时的意识和保证，例如老年人的远程家庭成员（ RFM ） ，他们在护理协调中发挥着核心作用。然而，将异构数据流整合到高级别、有意… | MIT | Jiachen Li |
| 7 | [A Training-Free Mixture-of-Agents Framework for Multi-Docume…](http://arxiv.org/abs/2606.03867v1) | 多文档摘要（ MDS ）在从文本数据集中提取基本信息方面发挥着关键作用。现有方法通常难以捕捉复杂的文档间关系，严重依赖大量标记数据进行监督培训，或在域和语言之间表现出有限的泛化。在英语和越南语的四个数… | MIT | Cuong Vuong Tuan |
| 8 | [EvoDS: Self-Evolving Autonomous Data Science Agent with Skil…](http://arxiv.org/abs/2606.03841v1) | 大型语言模型（ LLM ）代理的最新进展使自动化数据科学取得了有希望的进步。然而，现有方法仍然从根本上受到其静态动作集和缺乏有原则的长期上下文管理的限制，阻碍了它们在任务中积累可重用经验并在多阶段、迭… | MIT | Zherui Yang |
| 9 | [Enhancing Operational Safety via Agentic Dialogue Hazard Ide…](http://arxiv.org/abs/2606.03812v1) | 高风险领域（如工业过程控制、自主和安全关键系统）的运营安全要求可靠的危险识别。虽然大型语言模型（ LLM ）在自动化安全分析任务方面显示出希望，但单回合、整体推理是脆弱的：它缺乏安全工程师迭代应用的自… | TRI | Sanjay Das |
| 10 | [AI Agents Enable Adaptive Computer Worms](http://arxiv.org/abs/2606.03811v1) | 计算机蠕虫是通过将自身从一台机器复制到另一台机器而在网络上传播的恶意软件。像WannaCry这样的传统蠕虫利用了预先确定的漏洞，可以通过修补这些漏洞来阻止其传播。我们必须为自主生成对手做好准备：恶意软… | MIT | Jonas Guan |
| 11 | [Easy-to-Use Shielding for Reinforcement Learning](http://arxiv.org/abs/2606.03804v1) | 安全探索是强化学习（ RL ）中的一项关键挑战，旨在防止代理在探索其环境时做出有害决策。安全探索是强化学习（ RL ）中的一项关键挑战，旨在防止代理在探索其环境时做出有害决策。MiniGridSafe… | MIT、NTU | Stefan Pranger |
| 12 | [From Control Boundary to Insurance Claim: Reconstructing AI-…](http://arxiv.org/abs/2606.03777v1) | 通过被保险组织的生成或代理AI系统产生的AI损失需要状态重建，而不仅仅是事件重建，因为相关状态随着系统的原因、检索、调用工具和行为而变化。相关的问题不仅仅是发生了什么损失，而是系统被允许做什么，它实际… | CAS、TRI | Alex Leung |
| 13 | [Tool-Aware Optimization with Entropy Guidance for Efficient …](http://arxiv.org/abs/2606.03762v1) | Agentic强化学习（ RL ）为大型语言模型（ LLM ）配备了工具使用功能，大大改善了对复杂任务的推理。然而，整合外部工具往往会破坏培训的稳定性：过度依赖工具会导致输入分配的转移，而过度保守的工… | MIT、CAS | Hongye Cao |
| 14 | [LAP: An Agent-to-Instrument Protocol for Autonomous Science](http://arxiv.org/abs/2606.03755v1) | 自主科学正在从示范转向基础设施。大型语言模型代理现在计划实验，自动驾驶实验室执行它们。LAP与A2A/MCP生态系统传输兼容，并封装而不是取代SiLA 2和OPC-UA等现有设备标准。 | Google、Anthropic | Linwu Zhu |
| 15 | [Proof-Refactor: Refactoring Generated Formal Proofs into Mod…](http://arxiv.org/abs/2606.03743v1) | 虽然大型语言模型（ LLM ）在生成正式证明方面表现出强大的性能，但其输出通常比成熟的正式数学库中的证明更不可读、模块化、可维护和可重用。我们认为，这种差距部分源于大多数证明生成管道中隐含的编译优先目… | TRI | Yiming Fu |
| 16 | [Multi$^2$: Hierarchical Multi-Agent Decision-Making with LLM…](http://arxiv.org/abs/2606.03698v1) | 大型语言模型（ LLM ）研究的核心目标是构建能够通过与动态环境的持续交互来规划、行动和适应的代理系统。虽然最近基于法学硕士的代理人表现出令人印象深刻的背景推理，但他们的长期决策仍然很脆弱，往往存在客… | MIT | Sangeun Park |
| 17 | [SkillPyramid: A Hierarchical Skill Consolidation Framework f…](http://arxiv.org/abs/2606.03692v1) | 最近的人工智能智能体可以灵活地调用技能来解决复杂的任务，但它们的长期改进从根本上受到缺乏系统的技能构建、积累和转移的制约。特别是，如果没有统一的技能整合框架，代理往往会在不同的任务中多余地构建类似的能… | MIT、Mila | Yuan Xiong |
| 18 | [The DeepSpeak-Agentic Dataset](http://arxiv.org/abs/2606.03686v1) | 我们展示了DeepSpeak-Agentic ，这是一个视频数据集，包含人类和具体的人工智能代理之间超过37小时的半结构化对话。我们使用此数据集来评估AI智能体的自动取证识别（音频、视频或文本） ，研… | TRI | Sarah Barrington |
| 19 | [EvoDrive: Pareto Evolution for Safety-Critical Autonomous Dr…](http://arxiv.org/abs/2606.03678v1) | 生成安全关键场景对于验证和改进自动驾驶系统至关重要，但它本质上需要最大化对抗性以暴露故障，同时保持现实性。现有的方法通常通过手工启发式来处理这种权衡，将生成局限于已知的先验，并忽略未充分探索的模式。M… | MIT、HIT | Tong Nie |
| 20 | [Diagnosing Knowledge Gaps in LLM Tool Use: An Agentic Benchm…](http://arxiv.org/abs/2606.03657v1) | 用于代码生成的大型语言模型通常需要使用预训练数据中不存在的API。这需要的不仅仅是调用函数名称：模型必须协调签名、模块路径、输入输出合约、语义和可执行使用模式。这些结果表明，检索和调整起着互补的作用：… | TRI | Jinnuo Liu |

### 论文详情

<details>
<summary><b>1. Using Reward Uncertainty to Induce Diverse Behaviour in Reinforcement Learning</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Anthony GX-Chen、Ankit Anand、Gheorghe Comanici、Zaheer Abbas、Eser Aygün 等（共 10 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、CAS、NUS |
| **发布时间** | 2026-06-02T17:50:14Z |
| **关键词** | `Reinforcement Learning` · `RAG` · `Fine-tuning` |
| **原文链接** | [http://arxiv.org/abs/2606.03962v1](http://arxiv.org/abs/2606.03962v1) |

**📝 摘要概括：**

> 经典强化学习（ RL ）通常寻求一种确定性策略，使标量奖励的预期总和最大化。然而，语言模型微调或科学发现等现代应用需要多样性。我们的实证结果表明，该框架为复杂的强化学习任务提供了一个强大且理论基础的替代方案，在这种情况下，问题的传统表述无法诱导期望的广度。

</details>

<details>
<summary><b>2. VLESA: Vision-Language Embodied Safety Agent for Human Activity Monitoring</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Hanjiang Hu、Yiyuan Pan、Jiaxing Li、Xusheng Luo、Alexander Robey 等（共 8 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-06-02T17:42:17Z |
| **关键词** | `Benchmark` · `Embodied AI` |
| **原文链接** | [http://arxiv.org/abs/2606.03954v1](http://arxiv.org/abs/2606.03954v1) |

**📝 摘要概括：**

> 随着人工智能系统越来越多地帮助人类完成物理任务，确保安全变得至关重要--物理行为会带来数字错误所没有的直接和不可逆转的后果。我们推出了Vision-Language Embodied Safety Agent （ VLESA ）框架，该框架通过以自我为中心的视频监控人类活动，并在预测到危险行为时触发实时安全干预措施。优惠码可在https://github.com/HanjiangHu/上获得……

</details>

<details>
<summary><b>3. Hedge-Bench: Benchmarking Agents on Hard, Realistic Tasks Pertaining to Financial Reasoning</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Eric Cho、Shawn Huang、Alice Lu、Andy Lyu |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-06-02T17:11:56Z |
| **关键词** | `AI Agent` · `Reasoning` · `Benchmark` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2606.03918v1](http://arxiv.org/abs/2606.03918v1) |

**📝 摘要概括：**

> 人工智能代理可以越来越多地处理财务分析的机械任务：检索文档、计算公式、更新电子表格。更困难、更有价值的挑战是通过定义专家分析师工作的开放式问题进行推理。我们在github.com/Trata-Inc/trata-hedge-bench上发布数据集和评估线束。

</details>

<details>
<summary><b>4. The Impact of Configuring Agentic AI Coding Tools on Build-vs-Buy Decisions: A Study Protocol</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Jai Lal Lulla、Matthias Galster、Jie M. Zhang、Sebastian Baltes、Christoph Treude |
| **所属机构** | （详见原文） |
| **顶级机构标签** | OpenAI |
| **发布时间** | 2026-06-02T17:01:28Z |
| **关键词** | `Agentic` · `Benchmark` · `Workflow` |
| **原文链接** | [http://arxiv.org/abs/2606.03907v1](http://arxiv.org/abs/2606.03907v1) |

**📝 摘要概括：**

> Agentic AI编码工具以越来越大的自主权编写代码，并在此过程中决定何时导入库以及何时从头开始实施功能。这些决定，无论是从头开始构建功能还是购买外部库（以下简称“构建与购买” ） ，都会对软件安全性、许可合规性、性能和长期可维护性产生直接影响。由此产生的基准数据集和分析管道……

</details>

<details>
<summary><b>5. Agent libOS: A Library-OS-Inspired Runtime for Long-Running, Capability-Controlled LLM Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Yingqi Zhang |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT |
| **发布时间** | 2026-06-02T16:53:24Z |
| **关键词** | `LLM Agent` · `Evaluation` · `Memory` |
| **原文链接** | [http://arxiv.org/abs/2606.03895v1](http://arxiv.org/abs/2606.03895v1) |

**📝 摘要概括：**

> 大型语言模型（ LLM ）代理正在从请求响应助理演变为长期运行的软件参与者：他们跨模型调用维护状态，分叉子任务，等待外部事件，请求人为权限，生成工具，并执行必须恢复和审计的副作用。本文介绍了Agent libOS ，这是一种受库-OS启发的LLM代理运行时底物。代理libOS非但没有提高规划师的准确性，反而展示了……

</details>

<details>
<summary><b>6. From 'What' to 'How' and 'Why': Sharing LLM-Generated Retrospective Summaries of Older Adults' Passive Tracking Data with Remote Family Members</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Jiachen Li、Reina Szeyi Chan、Akshat Choube、Xiang Zhi Tan、Elizabeth Mynatt 等（共 6 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT |
| **发布时间** | 2026-06-02T16:46:00Z |
| **关键词** | `Multi-Agent` · `RAG` |
| **原文链接** | [http://arxiv.org/abs/2606.03876v1](http://arxiv.org/abs/2606.03876v1) |

**📝 摘要概括：**

> 随着现代无处不在的计算技术的日益普及，多模式跟踪系统有望为利益相关者提供及时的意识和保证，例如老年人的远程家庭成员（ RFM ） ，他们在护理协调中发挥着核心作用。然而，将异构数据流整合到高级别、有意义的内容中（例如回顾性摘要）仍然具有挑战性。最后，我们将展示设计……

</details>

<details>
<summary><b>7. A Training-Free Mixture-of-Agents Framework for Multi-Document Summarization using LLMs and Knowledge Graphs</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Cuong Vuong Tuan、Trang Mai Xuan、Tien-Cuong Nguyen、Vu-Duc Ngo、Thien Van Luong |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT |
| **发布时间** | 2026-06-02T16:39:07Z |
| **关键词** | `RAG` · `Fine-tuning` |
| **原文链接** | [http://arxiv.org/abs/2606.03867v1](http://arxiv.org/abs/2606.03867v1) |

**📝 摘要概括：**

> 多文档摘要（ MDS ）在从文本数据集中提取基本信息方面发挥着关键作用。现有方法通常难以捕捉复杂的文档间关系，严重依赖大量标记数据进行监督培训，或在域和语言之间表现出有限的泛化。在英语和越南语的四个数据集上的实验证明了最先进的或具有竞争力的……

</details>

<details>
<summary><b>8. EvoDS: Self-Evolving Autonomous Data Science Agent with Skill Learning and Context Management</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Zherui Yang、Fan Liu、Yansong Ning、Hao Liu |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT |
| **发布时间** | 2026-06-02T16:20:58Z |
| **关键词** | `Multi-Agent` · `Agentic` · `Reinforcement Learning` · `RAG` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2606.03841v1](http://arxiv.org/abs/2606.03841v1) |

**📝 摘要概括：**

> 大型语言模型（ LLM ）代理的最新进展使自动化数据科学取得了有希望的进步。然而，现有方法仍然从根本上受到其静态动作集和缺乏有原则的长期上下文管理的限制，阻碍了它们在任务中积累可重用经验并在多阶段、迭代数据科学管道中可靠运行的能力。我们的代码和数据可在https://github.com/u上获得……

</details>

<details>
<summary><b>9. Enhancing Operational Safety via Agentic Dialogue Hazard Identification Analysis</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Sanjay Das、Ran Elgedawy、Ethan Seefried、Ryan Burchfield、Tirthankar Ghosal |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-06-02T15:54:51Z |
| **关键词** | `Multi-Agent` · `Agentic` · `Reasoning` |
| **原文链接** | [http://arxiv.org/abs/2606.03812v1](http://arxiv.org/abs/2606.03812v1) |

**📝 摘要概括：**

> 高风险领域（如工业过程控制、自主和安全关键系统）的运营安全要求可靠的危险识别。虽然大型语言模型（ LLM ）在自动化安全分析任务方面显示出希望，但单回合、整体推理是脆弱的：它缺乏安全工程师迭代应用的自我纠正、深思熟虑和上下文细化。这项工作推进了DIALO的交叉……

</details>

<details>
<summary><b>10. AI Agents Enable Adaptive Computer Worms</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Jonas Guan、Tom Blanchard、Hanna Foerster、Hengrui Jia、Gabriel Huang 等（共 6 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT |
| **发布时间** | 2026-06-02T15:54:39Z |
| **关键词** | `AI Agent` · `Reasoning` |
| **原文链接** | [http://arxiv.org/abs/2606.03811v1](http://arxiv.org/abs/2606.03811v1) |

**📝 摘要概括：**

> 计算机蠕虫是通过将自身从一台机器复制到另一台机器而在网络上传播的恶意软件。像WannaCry这样的传统蠕虫利用了预先确定的漏洞，可以通过修补这些漏洞来阻止其传播。我们必须为自主生成对手做好准备：恶意软件系统在没有人类操作员的情况下传播，并且不是由固定的漏洞利用代码定义，而是由推理目标，适应目标的能力来定义。

</details>

<details>
<summary><b>11. Easy-to-Use Shielding for Reinforcement Learning</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Stefan Pranger、Bettina Könighofer |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、NTU、TRI |
| **发布时间** | 2026-06-02T15:50:34Z |
| **关键词** | `Reinforcement Learning` · `Workflow` |
| **原文链接** | [http://arxiv.org/abs/2606.03804v1](http://arxiv.org/abs/2606.03804v1) |

**📝 摘要概括：**

> 安全探索是强化学习（ RL ）中的一项关键挑战，旨在防止代理在探索其环境时做出有害决策。安全探索是强化学习（ RL ）中的一项关键挑战，旨在防止代理在探索其环境时做出有害决策。MiniGridSafe通过以概率转换和附加代理为特色的安全导向场景扩展了MiniGrid ，实现了……

</details>

<details>
<summary><b>12. From Control Boundary to Insurance Claim: Reconstructing AI-Mediated Losses Through the CER Framework</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Alex Leung、Rex Zhang、Kentaroh Toyoda、SiewMei Loh |
| **所属机构** | （详见原文） |
| **顶级机构标签** | CAS、TRI |
| **发布时间** | 2026-06-02T15:29:43Z |
| **关键词** | `Agentic` · `RAG` · `Retrieval` |
| **原文链接** | [http://arxiv.org/abs/2606.03777v1](http://arxiv.org/abs/2606.03777v1) |

**📝 摘要概括：**

> 通过被保险组织的生成或代理AI系统产生的AI损失需要状态重建，而不仅仅是事件重建，因为相关状态随着系统的原因、检索、调用工具和行为而变化。相关的问题不仅仅是发生了什么损失，而是系统被允许做什么，它实际上做了什么，以及重建的损失是否可以支持保险索赔的恢复。关键词：人工智能系统……

</details>

<details>
<summary><b>13. Tool-Aware Optimization with Entropy Guidance for Efficient Agentic Reinforcement Learning</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Hongye Cao、Nuo Yan、Haoyuan Deng、Ziwei Wang、Tianpei Yang 等（共 8 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、CAS、NUS |
| **发布时间** | 2026-06-02T15:16:12Z |
| **关键词** | `Agentic` · `Reasoning` · `Reinforcement Learning` · `RAG` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2606.03762v1](http://arxiv.org/abs/2606.03762v1) |

**📝 摘要概括：**

> Agentic强化学习（ RL ）为大型语言模型（ LLM ）配备了工具使用功能，大大改善了对复杂任务的推理。然而，整合外部工具往往会破坏培训的稳定性：过度依赖工具会导致输入分配的转移，而过度保守的工具使用限制了有效的探索。在3个模型尺度上对7个具有挑战性的推理基准进行了广泛的实验，证明了优越性……

</details>

<details>
<summary><b>14. LAP: An Agent-to-Instrument Protocol for Autonomous Science</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Linwu Zhu、Liqiang Gao、Yan Chen、Dan Zhu、Jian Huang |
| **所属机构** | （详见原文） |
| **顶级机构标签** | Google、Anthropic、MIT |
| **发布时间** | 2026-06-02T15:03:43Z |
| **关键词** | `Agentic` · `Reasoning` · `RAG` · `Embodied AI` |
| **原文链接** | [http://arxiv.org/abs/2606.03755v1](http://arxiv.org/abs/2606.03755v1) |

**📝 摘要概括：**

> 自主科学正在从示范转向基础设施。大型语言模型代理现在计划实验，自动驾驶实验室执行它们。LAP与A2A/MCP生态系统传输兼容，并封装而不是取代SiLA 2和OPC-UA等现有设备标准。

</details>

<details>
<summary><b>15. Proof-Refactor: Refactoring Generated Formal Proofs into Modular Artifacts</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Yiming Fu、Peixuan Liu、Zichen Wang、Kun yuan |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-06-02T14:56:10Z |
| **关键词** | `Agentic` · `RAG` · `Workflow` |
| **原文链接** | [http://arxiv.org/abs/2606.03743v1](http://arxiv.org/abs/2606.03743v1) |

**📝 摘要概括：**

> 虽然大型语言模型（ LLM ）在生成正式证明方面表现出强大的性能，但其输出通常比成熟的正式数学库中的证明更不可读、模块化、可维护和可重用。我们认为，这种差距部分源于大多数证明生成管道中隐含的编译优先目标，该目标鼓励单片或临时证明脚本，而不是库质量的工件。这些结果表明……

</details>

<details>
<summary><b>16. Multi$^2$: Hierarchical Multi-Agent Decision-Making with LLM-Based Agents in Interactive Environments</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Sangeun Park、Minhae Kwon |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT |
| **发布时间** | 2026-06-02T14:20:09Z |
| **关键词** | `Multi-Agent` · `Agentic` · `Reasoning` · `Reinforcement Learning` · `RAG` |
| **原文链接** | [http://arxiv.org/abs/2606.03698v1](http://arxiv.org/abs/2606.03698v1) |

**📝 摘要概括：**

> 大型语言模型（ LLM ）研究的核心目标是构建能够通过与动态环境的持续交互来规划、行动和适应的代理系统。虽然最近基于法学硕士的代理人表现出令人印象深刻的背景推理，但他们的长期决策仍然很脆弱，往往存在客观偏差，目标和计划偏离了长时间的互动。除了性能之外，我们还引入并发布了三个分层……

</details>

<details>
<summary><b>17. SkillPyramid: A Hierarchical Skill Consolidation Framework for Self-Evolving Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Yuan Xiong、Ziqi Miao、Qian Chen、Lijun Li、Yequan Wang 等（共 8 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、Mila |
| **发布时间** | 2026-06-02T14:14:27Z |
| **关键词** | `AI Agent` · `RAG` |
| **原文链接** | [http://arxiv.org/abs/2606.03692v1](http://arxiv.org/abs/2606.03692v1) |

**📝 摘要概括：**

> 最近的人工智能智能体可以灵活地调用技能来解决复杂的任务，但它们的长期改进从根本上受到缺乏系统的技能构建、积累和转移的制约。特别是，如果没有统一的技能整合框架，代理往往会在不同的任务中多余地构建类似的能力，无法有效地将体验转化为可重用的资产，并且难以推广TAS……

</details>

<details>
<summary><b>18. The DeepSpeak-Agentic Dataset</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Sarah Barrington、Maty Bohacek、Hany Farid |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-06-02T14:10:18Z |
| **关键词** | `AI Agent` · `Agentic` · `Benchmark` · `Embodied AI` |
| **原文链接** | [http://arxiv.org/abs/2606.03686v1](http://arxiv.org/abs/2606.03686v1) |

**📝 摘要概括：**

> 我们展示了DeepSpeak-Agentic ，这是一个视频数据集，包含人类和具体的人工智能代理之间超过37小时的半结构化对话。我们使用此数据集来评估AI智能体的自动取证识别（音频、视频或文本） ，研究人与智能体交互的性质，并为大语言模型和AI生成的声音和面孔的未来发展提供基准。

</details>

<details>
<summary><b>19. EvoDrive: Pareto Evolution for Safety-Critical Autonomous Driving via Self-Improving LLM Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Tong Nie、Yuewen Mei、Yihong Tang、Junlin He、Jie Deng 等（共 7 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、HIT、TRI |
| **发布时间** | 2026-06-02T14:01:23Z |
| **关键词** | `LLM Agent` · `Agentic` · `Benchmark` · `Simulation` · `Memory` |
| **原文链接** | [http://arxiv.org/abs/2606.03678v1](http://arxiv.org/abs/2606.03678v1) |

**📝 摘要概括：**

> 生成安全关键场景对于验证和改进自动驾驶系统至关重要，但它本质上需要最大化对抗性以暴露故障，同时保持现实性。现有的方法通常通过手工启发式来处理这种权衡，将生成局限于已知的先验，并忽略未充分探索的模式。MetaDrive和CARLA的基准测试结果表明， EvoDrive不仅大大扩展了……

</details>

<details>
<summary><b>20. Diagnosing Knowledge Gaps in LLM Tool Use: An Agentic Benchmark for Novel API Acquisition</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Jinnuo Liu、Yue Peng、Jinhan Niu、Hongyi Wen |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-06-02T13:46:04Z |
| **关键词** | `Agentic` · `Retrieval` · `Benchmark` · `Code Generation` · `Fine-tuning` |
| **原文链接** | [http://arxiv.org/abs/2606.03657v1](http://arxiv.org/abs/2606.03657v1) |

**📝 摘要概括：**

> 用于代码生成的大型语言模型通常需要使用预训练数据中不存在的API。这需要的不仅仅是调用函数名称：模型必须协调签名、模块路径、输入输出合约、语义和可执行使用模式。这些结果表明，检索和调整起着互补的作用：检索提供易变的API内容，而调整则改善了过程集成。

</details>

## 🗄️ 历史归档

| 日期 | 论文数 | 报告链接 |
|------|--------|----------|
| 2026-06-03 | 20 篇 | [2026-06-03.md](daily/2026-06-03.md) |
| 2026-06-02 | 20 篇 | [2026-06-02.md](daily/2026-06-02.md) |
| 2026-06-01 | 0 篇 | [2026-06-01.md](daily/2026-06-01.md) |
| 2026-05-31 | 0 篇 | [2026-05-31.md](daily/2026-05-31.md) |
| 2026-05-30 | 0 篇 | [2026-05-30.md](daily/2026-05-30.md) |
| 2026-05-29 | 0 篇 | [2026-05-29.md](daily/2026-05-29.md) |
| 2026-05-28 | 0 篇 | [2026-05-28.md](daily/2026-05-28.md) |
| 2026-05-27 | 0 篇 | [2026-05-27.md](daily/2026-05-27.md) |
| 2026-05-26 | 0 篇 | [2026-05-26.md](daily/2026-05-26.md) |
| 2026-05-25 | 0 篇 | [2026-05-25.md](daily/2026-05-25.md) |
| 2026-05-24 | 0 篇 | [2026-05-24.md](daily/2026-05-24.md) |
| 2026-05-23 | 0 篇 | [2026-05-23.md](daily/2026-05-23.md) |
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

*由 [clawBot DailyFindings](https://github.com/Jacob-biu/clawBot) 自动维护 | 最后更新：2026-06-03 23:43 UTC*
