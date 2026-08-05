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

## 📅 今日论文 — 2026-08-05　　[→ 查看完整报告](daily/2026-08-05.md)

> 共筛选出 **20** 篇论文 | 更新于 2026-08-05 22:57 UTC

### 论文目录与概要

| # | 论文标题 | 核心概要 | 来源机构 | 第一作者 |
|---|---------|---------|---------|--------|
| 1 | [TurnSight: Turn-Level Hindsight Self-Distillation for Tool-I…](http://arxiv.org/abs/2608.04007v1) | 工具集成推理（ TIR ）使LLM能够通过迭代工具交互来解决复杂的任务。然而，现有的强化学习方法通常依赖于轨迹级监督，限制了长时间TIR场景中的细粒度信用分配。我们的代码可在https://githu… | MIT、TRI | Changle Qu |
| 2 | [Video-DeepResearch: Towards the Next-Generation Multimodal D…](http://arxiv.org/abs/2608.03979v1) | 我们引入了Video-DeepResearch （ Video-DR ） ，将多模态代理从静态图像扩展到连续视频流，这种设置要求密集的时空接地与开放式网络探索相结合。初步评估揭示了当前模型的两个关键瓶… | MIT、TRI | Zhen Fang |
| 3 | [A game theory for foundation models shows new paths to ratio…](http://arxiv.org/abs/2608.03958v1) | 随着由基础模型驱动的自主代理越来越多地融入社会和经济体系，了解管理其集体行为的原则对于确保安全和合作至关重要。经典博弈论是理性互动建模的主导框架，建立在“解耦代理”的假设之上，其中代理人将自己的决策视… | Mila、TRI | Alexander Meulemans |
| 4 | [Implementing Causal Perception: Competing SCMs and Situated …](http://arxiv.org/abs/2608.03917v1) | 当具有相同系统的竞争结构因果模型（ SCM ）的智能体推断出不同的概率分布（包括每个智能体的SCM在相同干预集合下隐含的假设分布）时，就会出现因果感知。它决定了代理如何对系统进行推理，以及他们如何看待… | FAIR、TRI | Jose M. Álvarez |
| 5 | [Socially Grounded Agentic AI: Coordinating Plural Perspectiv…](http://arxiv.org/abs/2608.03910v1) | 随着人工智能系统部署在日益多样化的社会环境中，对齐不再是对单一、统一的价值观进行优化。相反，系统必须能够识别、代表和回应多种合法观点。我们概述了以结构化和负责任的方式涉及多个视角的系统的设计空间，并确… | TRI | Matt Ratto |
| 6 | [MultiGlobeQA: A Multilingual and Globally Diverse Benchmark …](http://arxiv.org/abs/2608.03882v1) | 地理空间推理，即计算距离、遏制和现实世界实体的其他空间关系，是导航和物流的核心，但大型语言模型（ LLM ）尽管存储了大量的地理知识，但仍难以进行所需的几何和拓扑计算。现有的基准仅部分本地化了这些故障… | MIT、TRI | Martin Böckling |
| 7 | [FedCritic-MIMO: Communication-Efficient Serverless Federated…](http://arxiv.org/abs/2608.03852v1) | 本文提出了FedCritic-MIMO ，这是一种高效通信的无服务器联合多智能体强化学习框架，用于在开放和分解的6G RAN中跨可独立部署的小区级控制器进行AI原生资源控制。控制器不共享培训师，保留本… | MIT、TRI | Amin Farajzadeh |
| 8 | [MAFIA: Query-Only Memory Attacks via Probing and Factual Inj…](http://arxiv.org/abs/2608.03844v1) | 内存增强的LLM代理依靠丰富的上下文进行长时间的推理和行动，但其内存模块暴露了恶意记录的持续攻击面，因此研究内存中毒威胁势在必行。然而，现有的仅查询攻击通常无法在两种现实和普遍的环境中保持有效：大规模… | MIT、Mila | Jiaming Chen |
| 9 | [Resume Means Resume: A Machine-Checked Conformance Contract …](http://arxiv.org/abs/2608.03836v1) | 一个持续执行状态的框架，以便运行可以被中断，在崩溃中幸存下来，并继续必须确定恢复对已经触发的效果意味着什么。五个广泛部署的代理工作流程框架的答案不同，没有一个会暴露机器可检查的合约，并且行为甚至违反了… | MIT、TRI | Sajjad Khan |
| 10 | [GDPevo: Evaluating Agent Self-Evolution on Real Business Tas…](http://arxiv.org/abs/2608.03764v1) | 客服代表的自我进化更新了以往经验中客服代表的持续状态，并重复使用它来更有效地解决相关任务。评估自我进化是困难的：现有基准对有经济价值的任务领域的覆盖范围有限，并不总是设计培训和测试任务，因此测试时间的… | MIT、TRI | Leijun Zhou |
| 11 | [Agents Catching Agents: Shortcut Cascades and Benchmark Gami…](http://arxiv.org/abs/2608.03744v1) | 临床决策支持正在转向语言模型代理委员会，在共享工作空间上进行审议。我们询问这些委员会是否可以通过快捷方式进行博弈，提示基准奖励，但临床医生会忽略。代码： https://github.com/crit… | MIT、CAS | Sebastián Andrés Cajas Ordóñez |
| 12 | [AgenticECO: An Agentic Framework for ECO on 3D Integrated Ci…](http://arxiv.org/abs/2608.03738v1) | 随着摩尔定律的放缓，该行业正在转向三维集成；然而，在合并的3D-IC流中，路由设计暴露了没有2D模拟的债券级缺陷，而路由后工程变更单（ ECO ）仍然是手动、专业知识的工作。更糟糕的是，标准的编辑-然… | CAS、TRI | Shuo Ren |
| 13 | [CARE-Bench: Benchmarking Patient-Facing LLM Triage](http://arxiv.org/abs/2608.03731v1) | 在临床医生联系之前，面向患者的医疗LLM和客服代表越来越多地回答症状问题，其中关键的安全问题是用户下一步应该采取什么行动。我们引入了CARE-Bench ，这是一个基于源的基准，将面向患者的顺序分流评… | CAS、TRI | Yining Hua |
| 14 | [SAT-Edge-Agent: Hardware-in-the-Loop Edge-Agent Orchestratio…](http://arxiv.org/abs/2608.03728v1) | 机载卫星智能需要一个任务层，该任务层将任务意图转换为本地工具调用，暴露执行状态，并在通信和功率限制下返回机器消耗的工件。我们推出了SAT-Edge-Agent ，这是一种部署在基于ARM的商用异构边缘… | OpenAI、FAIR | Longji He |
| 15 | [TARL: Transaction-Aware Reliable Ledgers for Executable Memo…](http://arxiv.org/abs/2608.03699v1) | 持久记忆有助于长期代理保留知识，但单个更新错误可能会反复扭曲未来的检索和推理。大多数现有系统将内存更新减少为二进制写入/保持决策，无法区分是否应添加、忽略、用于修改过时的信念、因不可靠而拒绝或延迟验证… | MIT、TRI | Han Xiao |
| 16 | [LiveEvalBench: Toward Open-World Evaluation for Web Generati…](http://arxiv.org/abs/2608.03689v1) | 大型语言模型越来越能够合成可执行的前端项目，但现有的基准仍然将Web生成视为静态评估问题。我们认为，前端工件需要不同的范式：它们是交互式而不是静态的，承认多样化但同样有效的实现，并且比刚性管道更快地发… | MIT | Yiyao Wang |
| 17 | [Is Inter-Seed Cross-Play Enough? Evaluating the Robustness o…](http://arxiv.org/abs/2608.03644v1) | 部署在现实环境中的人工智能代理必须能够与人类和他们以前从未遇到的其他人工智能代理进行协调。零点协调（ ZSC ）算法旨在通过指定高级学习规则来实现这一目标，以便独立设计的代理可以在测试时相互协调。我们… | HIT | Maksymilian Wolski |
| 18 | [A Security-Oriented Lifecycle Model for Large Language Model…](http://arxiv.org/abs/2608.03626v1) | 大型语言模型正以前所未有的规模集成到关键基础设施和企业工作流程中，但管理其开发和运营的生命周期框架旨在提高运营效率，而不是进行安全分析。因此，与安全相关的活动，如数据来源验证、工件签名、代理权限控制和… | TRI | Eleftherios Batzolis |
| 19 | [Formal Verification of Agentic Systems over Operational Data](http://arxiv.org/abs/2608.03609v1) | 由大型语言模型（ LLM ）驱动的代理系统越来越多地部署在现实世界的工作流程中，在那里它们对持久运营数据起作用。在部署之前，这些系统需要根据管理工作流程执行和数据演进的业务要求进行验证。最后，我们演示… | CAS、TRI | Alejandro J. Mercado |
| 20 | [Learning Clinical-Trial Strategy: Offline Policy Training fo…](http://arxiv.org/abs/2608.03606v1) | 临床开发是在不确定性下的连续决策，申办者必须根据异质性证据规划一系列实验。我们通过将肿瘤学临床开发作为离线决策问题来研究这一设置，其中药物根据决定日期可用的信息预测肿瘤学药物计划的下一个六个月试验组合… | TRI | William Bolton |

### 论文详情

<details>
<summary><b>1. TurnSight: Turn-Level Hindsight Self-Distillation for Tool-Integrated Reasoning</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Changle Qu、Sunhao Dai、Hengyi Cai、Yuqi Zhou、Xinran Chen 等（共 7 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-08-04T17:59:21Z |
| **关键词** | `Reasoning` · `Reinforcement Learning` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2608.04007v1](http://arxiv.org/abs/2608.04007v1) |

**📝 摘要概括：**

> 工具集成推理（ TIR ）使LLM能够通过迭代工具交互来解决复杂的任务。然而，现有的强化学习方法通常依赖于轨迹级监督，限制了长时间TIR场景中的细粒度信用分配。我们的代码可在https://github.com/quchangle1/TurnSight上找到。

</details>

<details>
<summary><b>2. Video-DeepResearch: Towards the Next-Generation Multimodal Deepresearch Agent</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Zhen Fang、Yu Zeng、Wenxuan Huang、Yiming Zhao、Shiting Huang 等（共 20 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-08-04T17:45:16Z |
| **关键词** | `RAG` · `Retrieval` · `Benchmark` · `Evaluation` · `Fine-tuning` |
| **原文链接** | [http://arxiv.org/abs/2608.03979v1](http://arxiv.org/abs/2608.03979v1) |

**📝 摘要概括：**

> 我们引入了Video-DeepResearch （ Video-DR ） ，将多模态代理从静态图像扩展到连续视频流，这种设置要求密集的时空接地与开放式网络探索相结合。初步评估揭示了当前模型的两个关键瓶颈： （ 1 ）模态偏差，即代理绕过视觉工具而支持文本搜索； （ 2 ）参数化知识泄漏，即模型依赖于内部记忆而不是……

</details>

<details>
<summary><b>3. A game theory for foundation models shows new paths to rational cooperation through similarity inference</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Alexander Meulemans、Maciej Wołczyk、Marissa A. Weis、Rajai Nasser、Roberta Rocca 等（共 14 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | Mila、TRI |
| **发布时间** | 2026-08-04T17:24:33Z |
| **关键词** | `AI Agent` · `Planning` |
| **原文链接** | [http://arxiv.org/abs/2608.03958v1](http://arxiv.org/abs/2608.03958v1) |

**📝 摘要概括：**

> 随着由基础模型驱动的自主代理越来越多地融入社会和经济体系，了解管理其集体行为的原则对于确保安全和合作至关重要。经典博弈论是理性互动建模的主导框架，建立在“解耦代理”的假设之上，其中代理人将自己的决策视为独立于环境和其他…

</details>

<details>
<summary><b>4. Implementing Causal Perception: Competing SCMs and Situated Fairness</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Jose M. Álvarez |
| **所属机构** | （详见原文） |
| **顶级机构标签** | FAIR、TRI |
| **发布时间** | 2026-08-04T16:48:19Z |
| **关键词** | — |
| **原文链接** | [http://arxiv.org/abs/2608.03917v1](http://arxiv.org/abs/2608.03917v1) |

**📝 摘要概括：**

> 当具有相同系统的竞争结构因果模型（ SCM ）的智能体推断出不同的概率分布（包括每个智能体的SCM在相同干预集合下隐含的假设分布）时，就会出现因果感知。它决定了代理如何对系统进行推理，以及他们如何看待其公平性。偏见证明了相对于代理的SCM的位置，表明在公平问题上相互竞争的世界观可以……

</details>

<details>
<summary><b>5. Socially Grounded Agentic AI: Coordinating Plural Perspectives through Social Theory</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Matt Ratto、Abhishek Moturu、Daniel Silver |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-08-04T16:37:09Z |
| **关键词** | `Agentic` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2608.03910v1](http://arxiv.org/abs/2608.03910v1) |

**📝 摘要概括：**

> 随着人工智能系统部署在日益多样化的社会环境中，对齐不再是对单一、统一的价值观进行优化。相反，系统必须能够识别、代表和回应多种合法观点。我们概述了以结构化和负责任的方式涉及多个视角的系统的设计空间，并确定了未来工作的方向，以实施和实证评估……

</details>

<details>
<summary><b>6. MultiGlobeQA: A Multilingual and Globally Diverse Benchmark for Geospatial Reasoning</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Martin Böckling、Elizaveta Nosova、Heiko Paulheim、Andreea Iana |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-08-04T16:18:52Z |
| **关键词** | `Agentic` · `Reasoning` · `RAG` · `Retrieval` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2608.03882v1](http://arxiv.org/abs/2608.03882v1) |

**📝 摘要概括：**

> 地理空间推理，即计算距离、遏制和现实世界实体的其他空间关系，是导航和物流的核心，但大型语言模型（ LLM ）尽管存储了大量的地理知识，但仍难以进行所需的几何和拓扑计算。现有的基准仅部分本地化了这些故障：它们是合成的或小规模的，主要是单语的，并且对……的控制有限

</details>

<details>
<summary><b>7. FedCritic-MIMO: Communication-Efficient Serverless Federated Critic Learning for Massive-MIMO Resource Control in Open and Disaggregated 6G RANs</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Amin Farajzadeh、Melike Erol-Kantarci |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-08-04T15:56:32Z |
| **关键词** | `Multi-Agent` · `Reinforcement Learning` · `Simulation` |
| **原文链接** | [http://arxiv.org/abs/2608.03852v1](http://arxiv.org/abs/2608.03852v1) |

**📝 摘要概括：**

> 本文提出了FedCritic-MIMO ，这是一种高效通信的无服务器联合多智能体强化学习框架，用于在开放和分解的6G RAN中跨可独立部署的小区级控制器进行AI原生资源控制。控制器不共享培训师，保留本地演员和个性化批评组件，并仅交换兼容的共享批评参数。这些结果表明，无服务器交换兼容性…

</details>

<details>
<summary><b>8. MAFIA: Query-Only Memory Attacks via Probing and Factual Injection against Audited LLM Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Jiaming Chen、Yisen Gao、Yanping Li、Zifan Liu、Yumeng Zhang 等（共 6 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、Mila、TRI |
| **发布时间** | 2026-08-04T15:50:26Z |
| **关键词** | `LLM Agent` · `Agentic` · `Reasoning` · `Retrieval` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2608.03844v1](http://arxiv.org/abs/2608.03844v1) |

**📝 摘要概括：**

> 内存增强的LLM代理依靠丰富的上下文进行长时间的推理和行动，但其内存模块暴露了恶意记录的持续攻击面，因此研究内存中毒威胁势在必行。然而，现有的仅查询攻击通常无法在两种现实和普遍的环境中保持有效：大规模良性内存池和主动输入审计。代码将在https://github上公开提供……

</details>

<details>
<summary><b>9. Resume Means Resume: A Machine-Checked Conformance Contract for Checkpoint, Interrupt, and Resume Semantics in Workflow Persistence Layers</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Sajjad Khan |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-08-04T15:45:31Z |
| **关键词** | `RAG` · `Workflow` |
| **原文链接** | [http://arxiv.org/abs/2608.03836v1](http://arxiv.org/abs/2608.03836v1) |

**📝 摘要概括：**

> 一个持续执行状态的框架，以便运行可以被中断，在崩溃中幸存下来，并继续必须确定恢复对已经触发的效果意味着什么。五个广泛部署的代理工作流程框架的答案不同，没有一个会暴露机器可检查的合约，并且行为甚至违反了它们所陈述的片段。交叉处理单元在读取路径处修复，该修复船只：选择加入门声称在共享中消耗……

</details>

<details>
<summary><b>10. GDPevo: Evaluating Agent Self-Evolution on Real Business Tasks</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Leijun Zhou、Zhihao Liu、Xiang Qu、Chenxu Liu、Yifei Liu 等（共 12 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-08-04T14:51:56Z |
| **关键词** | `RAG` · `Benchmark` · `Evaluation` · `Workflow` |
| **原文链接** | [http://arxiv.org/abs/2608.03764v1](http://arxiv.org/abs/2608.03764v1) |

**📝 摘要概括：**

> 客服代表的自我进化更新了以往经验中客服代表的持续状态，并重复使用它来更有效地解决相关任务。评估自我进化是困难的：现有基准对有经济价值的任务领域的覆盖范围有限，并不总是设计培训和测试任务，因此测试时间的增加可以归因于培训经验，并且仍然容易受到数据污染。我们公开发布管道， ……

</details>

<details>
<summary><b>11. Agents Catching Agents: Shortcut Cascades and Benchmark Gaming in Clinical Multi-Agent Systems</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Sebastián Andrés Cajas Ordóñez、Agastya Munnangi、Aldo Marzullo、Felipe Ocampo Osorio、Quang Bui 等（共 16 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、CAS、TRI |
| **发布时间** | 2026-08-04T14:37:16Z |
| **关键词** | `Multi-Agent` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2608.03744v1](http://arxiv.org/abs/2608.03744v1) |

**📝 摘要概括：**

> 临床决策支持正在转向语言模型代理委员会，在共享工作空间上进行审议。我们询问这些委员会是否可以通过快捷方式进行博弈，提示基准奖励，但临床医生会忽略。代码： https://github.com/criticaldata/benchmaxxing

</details>

<details>
<summary><b>12. AgenticECO: An Agentic Framework for ECO on 3D Integrated Circuits</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Shuo Ren、Yaohui Han、Libo Shen、Zhiqiang Jia、Rongliang Fu 等（共 7 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | CAS、TRI |
| **发布时间** | 2026-08-04T14:32:43Z |
| **关键词** | `Agentic` · `Workflow` |
| **原文链接** | [http://arxiv.org/abs/2608.03738v1](http://arxiv.org/abs/2608.03738v1) |

**📝 摘要概括：**

> 随着摩尔定律的放缓，该行业正在转向三维集成；然而，在合并的3D-IC流中，路由设计暴露了没有2D模拟的债券级缺陷，而路由后工程变更单（ ECO ）仍然是手动、专业知识的工作。更糟糕的是，标准的编辑-然后完全重新路由做法将修复与路由器流失纠缠在一起，因此签核号码不能归因于激励它的编辑。代码、环境和每集……

</details>

<details>
<summary><b>13. CARE-Bench: Benchmarking Patient-Facing LLM Triage</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Yining Hua、Hongbin Na、Cyrus Ayubcha |
| **所属机构** | （详见原文） |
| **顶级机构标签** | CAS、TRI |
| **发布时间** | 2026-08-04T14:26:45Z |
| **关键词** | `Benchmark` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2608.03731v1](http://arxiv.org/abs/2608.03731v1) |

**📝 摘要概括：**

> 在临床医生联系之前，面向患者的医疗LLM和客服代表越来越多地回答症状问题，其中关键的安全问题是用户下一步应该采取什么行动。我们引入了CARE-Bench ，这是一个基于源的基准，将面向患者的顺序分流评估为每回合四标签的当前动作任务。提示后这些错误的持续存在表明，面向患者的分流并不是一个简单的提示问题，并支持......

</details>

<details>
<summary><b>14. SAT-Edge-Agent: Hardware-in-the-Loop Edge-Agent Orchestration for Onboard Satellite Intelligence</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Longji He、Jeto Xu |
| **所属机构** | （详见原文） |
| **顶级机构标签** | OpenAI、FAIR |
| **发布时间** | 2026-08-04T14:25:27Z |
| **关键词** | `RAG` |
| **原文链接** | [http://arxiv.org/abs/2608.03728v1](http://arxiv.org/abs/2608.03728v1) |

**📝 摘要概括：**

> 机载卫星智能需要一个任务层，该任务层将任务意图转换为本地工具调用，暴露执行状态，并在通信和功率限制下返回机器消耗的工件。我们推出了SAT-Edge-Agent ，这是一种部署在基于ARM的商用异构边缘片上系统上的硬件在环（ HIL ）边缘代理系统。这些结果为可观测卫星建立了可重复的HIL边界……

</details>

<details>
<summary><b>15. TARL: Transaction-Aware Reliable Ledgers for Executable Memory Management in Long-Term Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Han Xiao、Hongjun Xu、Xin Zhang、Yidong Chen、Xiaodong Shi |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-08-04T14:02:55Z |
| **关键词** | `Reasoning` · `RAG` · `Retrieval` · `Benchmark` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2608.03699v1](http://arxiv.org/abs/2608.03699v1) |

**📝 摘要概括：**

> 持久记忆有助于长期代理保留知识，但单个更新错误可能会反复扭曲未来的检索和推理。大多数现有系统将内存更新减少为二进制写入/保持决策，无法区分是否应添加、忽略、用于修改过时的信念、因不可靠而拒绝或延迟验证新信息。完整的模型实现在补充材料中提供……

</details>

<details>
<summary><b>16. LiveEvalBench: Toward Open-World Evaluation for Web Generation</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Yiyao Wang、Zhen Wen、Yinghao Tang、Yixiao Fu、Lin Yuan 等（共 8 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT |
| **发布时间** | 2026-08-04T13:57:48Z |
| **关键词** | `Agentic` · `Benchmark` · `Evaluation` · `Workflow` |
| **原文链接** | [http://arxiv.org/abs/2608.03689v1](http://arxiv.org/abs/2608.03689v1) |

**📝 摘要概括：**

> 大型语言模型越来越能够合成可执行的前端项目，但现有的基准仍然将Web生成视为静态评估问题。我们认为，前端工件需要不同的范式：它们是交互式而不是静态的，承认多样化但同样有效的实现，并且比刚性管道更快地发展。代码可在https://github.com/wyysteelhead/LiveEvalBench上获得

</details>

<details>
<summary><b>17. Is Inter-Seed Cross-Play Enough? Evaluating the Robustness of Zero-Shot Coordination Algorithms to Implementation Details</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Maksymilian Wolski、Nicholas Hoernle、Johannes Forkel、Jakob Foerster |
| **所属机构** | （详见原文） |
| **顶级机构标签** | HIT |
| **发布时间** | 2026-08-04T13:29:00Z |
| **关键词** | `Multi-Agent` · `AI Agent` · `Reinforcement Learning` · `RAG` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2608.03644v1](http://arxiv.org/abs/2608.03644v1) |

**📝 摘要概括：**

> 部署在现实环境中的人工智能代理必须能够与人类和他们以前从未遇到的其他人工智能代理进行协调。零点协调（ ZSC ）算法旨在通过指定高级学习规则来实现这一目标，以便独立设计的代理可以在测试时相互协调。我们的调查结果令人鼓舞，并表明，对于Other-Play来说，标准的ZSC评估实际上是一个合理的代理......

</details>

<details>
<summary><b>18. A Security-Oriented Lifecycle Model for Large Language Model Systems</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Eleftherios Batzolis、George Drosatos、Vassilis Katsouros、Konstantinos Rantos |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-08-04T13:13:48Z |
| **关键词** | `Agentic` · `Workflow` |
| **原文链接** | [http://arxiv.org/abs/2608.03626v1](http://arxiv.org/abs/2608.03626v1) |

**📝 摘要概括：**

> 大型语言模型正以前所未有的规模集成到关键基础设施和企业工作流程中，但管理其开发和运营的生命周期框架旨在提高运营效率，而不是进行安全分析。因此，与安全相关的活动，如数据来源验证、工件签名、代理权限控制和退役，通常会被隐含或假定为……

</details>

<details>
<summary><b>19. Formal Verification of Agentic Systems over Operational Data</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Alejandro J. Mercado、Alessio Lomuscio |
| **所属机构** | （详见原文） |
| **顶级机构标签** | CAS、TRI |
| **发布时间** | 2026-08-04T13:01:30Z |
| **关键词** | `LLM Agent` · `Agentic` · `Workflow` |
| **原文链接** | [http://arxiv.org/abs/2608.03609v1](http://arxiv.org/abs/2608.03609v1) |

**📝 摘要概括：**

> 由大型语言模型（ LLM ）驱动的代理系统越来越多地部署在现实世界的工作流程中，在那里它们对持久运营数据起作用。在部署之前，这些系统需要根据管理工作流程执行和数据演进的业务要求进行验证。最后，我们演示了LLM专员协调个案管理工作流程的框架。

</details>

<details>
<summary><b>20. Learning Clinical-Trial Strategy: Offline Policy Training for Decision Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | William Bolton、Philip Torr |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-08-04T12:58:17Z |
| **关键词** | `LLM Agent` · `Retrieval` |
| **原文链接** | [http://arxiv.org/abs/2608.03606v1](http://arxiv.org/abs/2608.03606v1) |

**📝 摘要概括：**

> 临床开发是在不确定性下的连续决策，申办者必须根据异质性证据规划一系列实验。我们通过将肿瘤学临床开发作为离线决策问题来研究这一设置，其中药物根据决定日期可用的信息预测肿瘤学药物计划的下一个六个月试验组合。这些结果表明，结构化的离线学习可以……

</details>

## 🗄️ 历史归档

| 日期 | 论文数 | 报告链接 |
|------|--------|----------|
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

## 🏛️ 顶级机构覆盖范围

覆盖超过 **70 个**顶级 AI 机构，包括：

- **科技公司：** Microsoft、Google DeepMind、OpenAI、Anthropic、Meta AI、NVIDIA、Baidu、Alibaba、ByteDance 等
- **北美顶级大学：** MIT、Stanford、CMU、UC Berkeley、Harvard、Princeton、Cornell、Caltech 等
- **中国顶级大学/机构：** 清华大学、北京大学、浙大、上交大、复旦、中科院、MSRA 等
- **欧洲/其他：** Oxford、Cambridge、ETH Zurich、Mila、NUS、KAIST 等

---

*由 [clawBot DailyFindings](https://github.com/Jacob-biu/clawBot) 自动维护 | 最后更新：2026-08-05 22:57 UTC*
