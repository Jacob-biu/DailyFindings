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

## 📅 今日论文 — 2026-11-26　　[→ 查看完整报告](daily/2026-11-26.md)

> 共筛选出 **20** 篇论文 | 更新于 2026-11-26 03:58 UTC

### 论文目录与概要

| # | 论文标题 | 核心概要 | 来源机构 | 第一作者 |
|---|---------|---------|---------|--------|
| 1 | [StateWeaver: Multi-Agent Coordination of Story-State Transit…](http://arxiv.org/abs/2611.34290v1) | 现代视频基础模型可以生成高质量的短视频片段，但要保持长视频的一致性并正确描绘事件驱动的状态变化仍然是一项挑战。现有代理工作流程面临这些挑战，因为持续的规划和修复会积累上下文，而参考更新仍然有限。在多个… | MIT、TRI | Modi Jin |
| 2 | [Latent-in-the-Middle: On the Security of Cross-Model Latent …](http://arxiv.org/abs/2611.34278v1) | 随着大型语言模型在异构多智能体系统中日益频繁地开展协作，隐性通信已成为一种高效的替代方案，可用于替代自然语言消息的交换。通过共享内部表征，智能体可以避免重复处理相同的上下文，从而减少通信开销和预填充计… | MIT、HIT | Manit Baser |
| 3 | [Crucible: Evaluating LLM Agents in Executable Chemistry Rese…](http://arxiv.org/abs/2611.34254v1) | 大型语言模型（LLM）在化学知识基准测试中表现出色，这些基准测试主要评估回答问题和独立任务的能力。然而，化学研究需要使用专门的工具并解释其输出，以获得在化学上有效的结果。更强大的模型能从工具访问中受益… | MIT | Yinjun Liu |
| 4 | [Navigent: A Geometry-Grounded Agentic Framework for Vision L…](http://arxiv.org/abs/2611.34249v1) | 使用通用多模态大语言模型（MLLM）的视觉-语言导航（VLN）为针对特定任务的导航策略提供了一种灵活的替代方案，但可靠的远期执行仍然是一项挑战。智能体必须跟踪导航进度，检测指令运动与实际运动之间的差异… | TRI | Xinyu Zhou |
| 5 | [PROVE: Mitigating Long-Horizon LLM Collusion with Reinforcem…](http://arxiv.org/abs/2611.34215v1) | 当 LLM 代理在长时间的交互中相互核验对方的工作时，它们会逐渐陷入串通：它们开始在没有核验协议所要求的证据的情况下接受工作。串通行为在开始时并不存在，而是随着一次次互动而逐渐形成，我们将其归因于记忆… | MIT | Haochen Luo |
| 6 | [Compute-Aware Submodular Online Learning in Open Multi-Agent…](http://arxiv.org/abs/2611.34211v1) | 本文研究了开放式多智能体系统中用于合作任务分配的策略学习，其中次模效用函数建模了由于智能体贡献重叠而导致的边际收益递减。虽然标准方法会评估每个候选行动以更新策略，但这可能会导致过高的在线计算成本。在合… | TRI | Jing Liu |
| 7 | [MINE: A Training-Free Defense against Indirect Prompt Inject…](http://arxiv.org/abs/2611.34188v1) | 现有的检索增强生成（RAG）间接提示注入防御措施本质上是被动的：提示工程方法通常会被注入的指令覆盖，而监督式检测器必须针对每种新的攻击方式进行重新训练。我们提出了一种不同的范式：通过最大化相关性来防御… | TRI | Truong Phan |
| 8 | [Strategic and Robust Task Allocation for Combat Objectives i…](http://arxiv.org/abs/2611.34158v1) | 在争夺目标的团队游戏中，任务分配需要在不确定性、空间限制和不断变化的战术条件下做出协调一致的决策。在这种情况下，多个智能体必须同时预测队友的行为和对手的行动。结果表明，在严格的实时约束条件下，经过学习… | MIT、TRI | Jonas Peché |
| 9 | [Letting Models Manage Their Own Context: Where We Stand](http://arxiv.org/abs/2611.34147v1) | 如今，代理框架代表模型管理上下文：当窗口填满时，框架会触发一次压缩，以总结历史记录。我们研究了另一种\emph{模型驱动}的上下文管理方式，在这种方式中，模型本身通过上下文API决定何时压缩以及压缩什… | NVIDIA、TRI | Alessio Devoto |
| 10 | [Reproducer Synthesis for AI-Reported Bugs in the Linux Kerne…](http://arxiv.org/abs/2611.34142v1) | 智能体审核系统正越来越多地以文本报告的形式标记 Linux 内核补丁中疑似存在的漏洞。收到此类报告的维护人员需要进一步检查，以确定报告是否属实。令人兴奋的是，通过我们生成的 PoC，Linux 内核维… | TRI | Xiao Wu |
| 11 | [Unstable Action Boundaries in Lethal Drone Agents](http://arxiv.org/abs/2611.34121v1) | 使用工具的大型语言模型（LLM）代理会带来安全风险，而仅靠纯文本拒绝行为无法识别这些风险，特别是在工具可能触发高影响行动的情况下。这一问题在军事领域尤为突出，因为自主武器增加了将武力决策委托给软件代理… | TRI | Jacques Dumora |
| 12 | [Not Every Input Needs Everything: Unifying Expert Gating, Mo…](http://arxiv.org/abs/2611.34112v1) | 对每个输入统一执行单体式神经网络权重、前沿基础模型或整个多智能体工作流，会导致巨大的计算、延迟和资金开销。条件计算通过动态决定针对每个请求调用哪些内部专家、模型端点或专用代理，从而降低这种成本。与此同… | MIT、HIT | Dat Tat Mai |
| 13 | [Feature Engineered Reinforcement Learning for S-pair Selecti…](http://arxiv.org/abs/2611.34088v1) | 在布赫伯格 (Buchberger) 算法中，选择处理 S-对的顺序是一个关键决策，用于计算格罗布纳 (Groebner) 基：这一选择可以使成本发生数个数量级的变化。最近的研究表明，在二项式理想上，… | Mila、TRI | Uzma Shafiq |
| 14 | [Post-Training Policy Replication for Strategy-Following Mult…](http://arxiv.org/abs/2611.34035v1) | 虽然多智能体深度强化学习能够实现协调行为，但由于智能体之间的相互作用十分复杂，因此要使其与管理意图保持一致仍然很困难。虽然遵循策略的分布式注意力行为体架构 (sfDA7-X) 通过区域指令提高了可控性… | HIT、TRI | Yamato Takahagi |
| 15 | [DosePET: An Open-Source Dataset with 2100 Radiation Dose Map…](http://arxiv.org/abs/2611.34008v1) | 为了开发用于核医学个性化体内剂量测定的机器学习模型，需要大量与患者解剖结构相关联的三维辐射剂量图，但此类数据的获取仍然有限。本文介绍了DosePET，这是一个开源数据集，包含2,100个患者特异性吸收… | MIT、TRI | Eleftherios Tzanis |
| 16 | [PatternMiner: Automated Mathematical Discovery Through LLM-G…](http://arxiv.org/abs/2611.33966v1) | 有几种方法可以实现人工智能驱动的数学发现。其中一种方法是使用大型语言模型（LLM）通过基于文本的推理来解决明确的猜想，而另一种方法则是使用窄域模型和可解释性，利用基于对象的数学数据进行更开放式的人机协… | MIT、CAS | Michael Ruofan Zeng |
| 17 | [AI Buckingham: Agentic Discovery of Dimensionless Scaling La…](http://arxiv.org/abs/2611.33961v1) | 经典量纲分析定义了可接受的无量纲表示，但并未确定哪些组合能够捕捉到主要的物理依赖关系，也未确定这种依赖关系是否在不同的物理体系中发生变化，或者何时需要对因变量进行重新标度。我们推出了AI Buckin… | Mila、TRI | Ao Cheng |
| 18 | [What Does Skill Lift Actually Measure? A Source-Code-Level A…](http://arxiv.org/abs/2611.33943v1) | Agent 技能是指令、参考资料和脚本的目录，由 Coding Agent 按需加载。根据 SkillsBench 的数据，虽然人工策划的技能平均可以将通过率提高约 16.6 个百分点（pp），但它们… | CAS、TRI | Haozhe Zhang |
| 19 | [Connecting AI Agents to Live Discrete Element Simulations vi…](http://arxiv.org/abs/2611.33926v1) | 本文介绍了一种模型上下文协议（MCP）服务器，通过该服务器，通用人工智能代理在模拟运行期间可以操作商业或开源的离散元引擎。代理将一个长时间模拟提交给引擎，并在引擎计算过程中读取正在运行的模型、对其进行… | MIT、CAS | Yusong Han |
| 20 | [EGSE: Evidence-Grounded Skill Evolution for Medical Reasonin…](http://arxiv.org/abs/2611.33909v1) | 医学推理代理将基础模型与专用工具相结合来解读医学影像，但要重复利用它们的历史经验仍然存在挑战。正确的最终答案可能会掩盖有缺陷的推理或工具使用，合成的建议可能缺乏来源支持，表面上相似的病例可能需要不同的… | CAS、Mila | Mingyuan Li |

### 论文详情

<details>
<summary><b>1. StateWeaver: Multi-Agent Coordination of Story-State Transitions for Long-Horizon Video Generation</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Modi Jin、Xuying Zhang、Yijing Guo、Haoran Li、Yanwen Ma 等（共 9 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-11-25T12:43:37Z |
| **关键词** | `Multi-Agent` · `Agentic` · `Planning` · `Benchmark` · `Memory` |
| **原文链接** | [http://arxiv.org/abs/2611.34290v1](http://arxiv.org/abs/2611.34290v1) |

**📝 摘要概括：**

> 现代视频基础模型可以生成高质量的短视频片段，但要保持长视频的一致性并正确描绘事件驱动的状态变化仍然是一项挑战。现有代理工作流程面临这些挑战，因为持续的规划和修复会积累上下文，而参考更新仍然有限。在多个基准测试中，StateWeaver的表现优于现有方法，并能够生成具有持续跨镜头一致性的长视频……

</details>

<details>
<summary><b>2. Latent-in-the-Middle: On the Security of Cross-Model Latent Communication in Multi-Agent Systems</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Manit Baser、Vyoman Jain、Rachel Yeo Hui Min、Xianglin Yang、Meenatchi Sundaram Muthu Selva Annamalai 等（共 6 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、HIT |
| **发布时间** | 2026-11-25T12:35:33Z |
| **关键词** | `Multi-Agent` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2611.34278v1](http://arxiv.org/abs/2611.34278v1) |

**📝 摘要概括：**

> 随着大型语言模型在异构多智能体系统中日益频繁地开展协作，隐性通信已成为一种高效的替代方案，可用于替代自然语言消息的交换。通过共享内部表征，智能体可以避免重复处理相同的上下文，从而减少通信开销和预填充计算。为了解决这些漏洞，我们提出了一种轻量级目标端缓存防护机制，用于纠正传输的……

</details>

<details>
<summary><b>3. Crucible: Evaluating LLM Agents in Executable Chemistry Research Environments</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Yinjun Liu、Xinye Li、Ruisen Peng、Lang Gao、Zixiang Xu 等（共 7 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT |
| **发布时间** | 2026-11-25T12:18:29Z |
| **关键词** | `LLM Agent` · `Planning` · `Benchmark` · `Simulation` |
| **原文链接** | [http://arxiv.org/abs/2611.34254v1](http://arxiv.org/abs/2611.34254v1) |

**📝 摘要概括：**

> 大型语言模型（LLM）在化学知识基准测试中表现出色，这些基准测试主要评估回答问题和独立任务的能力。然而，化学研究需要使用专门的工具并解释其输出，以获得在化学上有效的结果。更强大的模型能从工具访问中受益更多，但可靠地使用化学软件仍然是一项挑战，Crucible Bench可以在模型改进的过程中跟踪这一挑战。

</details>

<details>
<summary><b>4. Navigent: A Geometry-Grounded Agentic Framework for Vision Language Navigation</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Xinyu Zhou、Weiren Cai、Yitong Chen、Shenghai Yuan、Zihang Mu 等（共 10 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-11-25T12:12:31Z |
| **关键词** | `Agentic` · `Memory` |
| **原文链接** | [http://arxiv.org/abs/2611.34249v1](http://arxiv.org/abs/2611.34249v1) |

**📝 摘要概括：**

> 使用通用多模态大语言模型（MLLM）的视觉-语言导航（VLN）为针对特定任务的导航策略提供了一种灵活的替代方案，但可靠的远期执行仍然是一项挑战。智能体必须跟踪导航进度，检测指令运动与实际运动之间的差异，并识别运动何时已经过相关地标或入口。项目页面： https://marslab-navigent.github.io/navige…

</details>

<details>
<summary><b>5. PROVE: Mitigating Long-Horizon LLM Collusion with Reinforcement Learning from Verified Evidence</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Haochen Luo、Jie Fu、Mukai Li、Yuqi Wang、Qi Liu |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT |
| **发布时间** | 2026-11-25T11:39:39Z |
| **关键词** | `Multi-Agent` · `LLM Agent` · `Reinforcement Learning` · `Memory` |
| **原文链接** | [http://arxiv.org/abs/2611.34215v1](http://arxiv.org/abs/2611.34215v1) |

**📝 摘要概括：**

> 当 LLM 代理在长时间的交互中相互核验对方的工作时，它们会逐渐陷入串通：它们开始在没有核验协议所要求的证据的情况下接受工作。串通行为在开始时并不存在，而是随着一次次互动而逐渐形成，我们将其归因于记忆中积累的准确反馈。代码可在 https://github.com/Haochen-Luo/PROVE 获取。

</details>

<details>
<summary><b>6. Compute-Aware Submodular Online Learning in Open Multi-Agent Systems</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Jing Liu、Luca Ballotta、Fangfei Li、Yang Tang、Ruggero Carli |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-11-25T11:35:43Z |
| **关键词** | `Multi-Agent` · `RAG` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2611.34211v1](http://arxiv.org/abs/2611.34211v1) |

**📝 摘要概括：**

> 本文研究了开放式多智能体系统中用于合作任务分配的策略学习，其中次模效用函数建模了由于智能体贡献重叠而导致的边际收益递减。虽然标准方法会评估每个候选行动以更新策略，但这可能会导致过高的在线计算成本。在合作信息覆盖方面的实验表明，我们的方法在保持高性能的同时，显著减少了……

</details>

<details>
<summary><b>7. MINE: A Training-Free Defense against Indirect Prompt Injection via Mutual Information and Embedding Variance</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Truong Phan、Ngoc-Quan Pham、Dat Quoc Nguyen |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-11-25T11:16:43Z |
| **关键词** | `RAG` · `Retrieval` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2611.34188v1](http://arxiv.org/abs/2611.34188v1) |

**📝 摘要概括：**

> 现有的检索增强生成（RAG）间接提示注入防御措施本质上是被动的：提示工程方法通常会被注入的指令覆盖，而监督式检测器必须针对每种新的攻击方式进行重新训练。我们提出了一种不同的范式：通过最大化相关性来防御，而不是通过检测攻击来防御。这也是唯一一种在面对完全自适应攻击者时仍能发挥作用的防御措施，它具有……的普遍性。

</details>

<details>
<summary><b>8. Strategic and Robust Task Allocation for Combat Objectives in Adversarial Multi-Agent Environments</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Jonas Peché、Dmitry Matveev、Vladimir Ciric、Lizaveta Sakalova、Günter Wallner |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-11-25T10:51:03Z |
| **关键词** | `Multi-Agent` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2611.34158v1](http://arxiv.org/abs/2611.34158v1) |

**📝 摘要概括：**

> 在争夺目标的团队游戏中，任务分配需要在不确定性、空间限制和不断变化的战术条件下做出协调一致的决策。在这种情况下，多个智能体必须同时预测队友的行为和对手的行动。结果表明，在严格的实时约束条件下，经过学习的战术估算能够支持稳定、可行且可检验的目标分配。

</details>

<details>
<summary><b>9. Letting Models Manage Their Own Context: Where We Stand</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Alessio Devoto、Avinash Vem、Tara Safavi、Sanjay Kariyappa、Yu-Hsuan Tseng 等（共 7 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | NVIDIA、TRI |
| **发布时间** | 2026-11-25T10:44:04Z |
| **关键词** | — |
| **原文链接** | [http://arxiv.org/abs/2611.34147v1](http://arxiv.org/abs/2611.34147v1) |

**📝 摘要概括：**

> 如今，代理框架代表模型管理上下文：当窗口填满时，框架会触发一次压缩，以总结历史记录。我们研究了另一种\emph{模型驱动}的上下文管理方式，在这种方式中，模型本身通过上下文API决定何时压缩以及压缩什么内容。这些结果共同指向了一个新的协同设计前沿：模型经过训练，能够管理自己的上下文，由支持 KV 缓存编辑的推理引擎提供服务……

</details>

<details>
<summary><b>10. Reproducer Synthesis for AI-Reported Bugs in the Linux Kernel</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Xiao Wu、Yunbo Ni、Hao Sun、Yuanyuan Yuan、Shaohua Li |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-11-25T10:40:46Z |
| **关键词** | `Agentic` |
| **原文链接** | [http://arxiv.org/abs/2611.34142v1](http://arxiv.org/abs/2611.34142v1) |

**📝 摘要概括：**

> 智能体审核系统正越来越多地以文本报告的形式标记 Linux 内核补丁中疑似存在的漏洞。收到此类报告的维护人员需要进一步检查，以确定报告是否属实。令人兴奋的是，通过我们生成的 PoC，Linux 内核维护人员确认了其中 69.4%，远高于 Sashiko 的 9.3%（Sashiko 仅提供文本说明），这使 AI 审核在实践中更具可操作性。

</details>

<details>
<summary><b>11. Unstable Action Boundaries in Lethal Drone Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Jacques Dumora、André-Louis Rochet、Simon Roburin |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-11-25T10:23:38Z |
| **关键词** | `LLM Agent` |
| **原文链接** | [http://arxiv.org/abs/2611.34121v1](http://arxiv.org/abs/2611.34121v1) |

**📝 摘要概括：**

> 使用工具的大型语言模型（LLM）代理会带来安全风险，而仅靠纯文本拒绝行为无法识别这些风险，特别是在工具可能触发高影响行动的情况下。这一问题在军事领域尤为突出，因为自主武器增加了将武力决策委托给软件代理的可能性。其次，在受保护的描述符下最初看起来保守的智能体，在简单的语义目标偏移下可能会变得不安全……

</details>

<details>
<summary><b>12. Not Every Input Needs Everything: Unifying Expert Gating, Model Cascades, and Agent Orchestration</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Dat Tat Mai、Hung Tran Quy、Thai Viet Pham、James Jin Kang |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、HIT、CAS |
| **发布时间** | 2026-11-25T10:15:28Z |
| **关键词** | `Multi-Agent` · `Agentic` · `Workflow` |
| **原文链接** | [http://arxiv.org/abs/2611.34112v1](http://arxiv.org/abs/2611.34112v1) |

**📝 摘要概括：**

> 对每个输入统一执行单体式神经网络权重、前沿基础模型或整个多智能体工作流，会导致巨大的计算、延迟和资金开销。条件计算通过动态决定针对每个请求调用哪些内部专家、模型端点或专用代理，从而降低这种成本。与此同时，在代理任务委派方面，论文发表数量的增长速度最快，其中路由机制……

</details>

<details>
<summary><b>13. Feature Engineered Reinforcement Learning for S-pair Selection in Buchberger's Algorithm</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Uzma Shafiq、Matthew England、Nayyar Zaidi |
| **所属机构** | （详见原文） |
| **顶级机构标签** | Mila、TRI |
| **发布时间** | 2026-11-25T09:59:45Z |
| **关键词** | `Reinforcement Learning` |
| **原文链接** | [http://arxiv.org/abs/2611.34088v1](http://arxiv.org/abs/2611.34088v1) |

**📝 摘要概括：**

> 在布赫伯格 (Buchberger) 算法中，选择处理 S-对的顺序是一个关键决策，用于计算格罗布纳 (Groebner) 基：这一选择可以使成本发生数个数量级的变化。最近的研究表明，在二项式理想上，观察多项式指数向量的强化学习代理的性能优于经典启发式算法。特征工程的额外成本意味着实际运行时间成本与基线成本相差不大，但我们的……

</details>

<details>
<summary><b>14. Post-Training Policy Replication for Strategy-Following Multi-Agent Deep Reinforcement Learning across Team Sizes</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Yamato Takahagi、Yoshinari Motokawa、Toshiharu Sugawara |
| **所属机构** | （详见原文） |
| **顶级机构标签** | HIT、TRI |
| **发布时间** | 2026-11-25T09:18:04Z |
| **关键词** | `Multi-Agent` · `Reinforcement Learning` |
| **原文链接** | [http://arxiv.org/abs/2611.34035v1](http://arxiv.org/abs/2611.34035v1) |

**📝 摘要概括：**

> 虽然多智能体深度强化学习能够实现协调行为，但由于智能体之间的相互作用十分复杂，因此要使其与管理意图保持一致仍然很困难。虽然遵循策略的分布式注意力行为体架构 (sfDA7-X) 通过区域指令提高了可控性，但指令组合会随着团队和指令规模的增大而呈指数级增长，导致训练成本过高且可迁移性较差。这些……

</details>

<details>
<summary><b>15. DosePET: An Open-Source Dataset with 2100 Radiation Dose Maps for PET/CT</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Eleftherios Tzanis、Antonios Tzortzakakis、Michail E. Klontzas |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-11-25T08:55:37Z |
| **关键词** | `Simulation` |
| **原文链接** | [http://arxiv.org/abs/2611.34008v1](http://arxiv.org/abs/2611.34008v1) |

**📝 摘要概括：**

> 为了开发用于核医学个性化体内剂量测定的机器学习模型，需要大量与患者解剖结构相关联的三维辐射剂量图，但此类数据的获取仍然有限。本文介绍了DosePET，这是一个开源数据集，包含2,100个患者特异性吸收剂量图，这些图是通过对公开的PET/CT检查进行蒙特卡洛模拟生成的：1,503项来自ENHA的[18F]FDG检查……

</details>

<details>
<summary><b>16. PatternMiner: Automated Mathematical Discovery Through LLM-Guided Training and Interpretation of Small Models</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Michael Ruofan Zeng、Junaid Hasan、Xuanyu Yang、Emily Xia Meng、Henry Kvinge |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、CAS、TRI |
| **发布时间** | 2026-11-25T08:30:13Z |
| **关键词** | `LLM Agent` · `Reasoning` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2611.33966v1](http://arxiv.org/abs/2611.33966v1) |

**📝 摘要概括：**

> 有几种方法可以实现人工智能驱动的数学发现。其中一种方法是使用大型语言模型（LLM）通过基于文本的推理来解决明确的猜想，而另一种方法则是使用窄域模型和可解释性，利用基于对象的数学数据进行更开放式的人机协同探索。最后，我们将分析 PatternMiner 在我们的案例研究中用于生成猜想的最常见途径……

</details>

<details>
<summary><b>17. AI Buckingham: Agentic Discovery of Dimensionless Scaling Laws Across Physical Regimes</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Ao Cheng、Lei Zhang、Guowei He |
| **所属机构** | （详见原文） |
| **顶级机构标签** | Mila、TRI |
| **发布时间** | 2026-11-25T08:24:47Z |
| **关键词** | `Agentic` · `Reasoning` · `Planning` · `RAG` · `Retrieval` |
| **原文链接** | [http://arxiv.org/abs/2611.33961v1](http://arxiv.org/abs/2611.33961v1) |

**📝 摘要概括：**

> 经典量纲分析定义了可接受的无量纲表示，但并未确定哪些组合能够捕捉到主要的物理依赖关系，也未确定这种依赖关系是否在不同的物理体系中发生变化，或者何时需要对因变量进行重新标度。我们推出了AI Buckingham，这是一个代理框架，用于从物理问题的自然语言描述和观测数据中自主发现无量纲关系。针对长期存在的挑战……

</details>

<details>
<summary><b>18. What Does Skill Lift Actually Measure? A Source-Code-Level Audit and Noise-Aware Reanalysis of SkillsBench</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Haozhe Zhang、Zhen Long |
| **所属机构** | （详见原文） |
| **顶级机构标签** | CAS、TRI |
| **发布时间** | 2026-11-25T08:02:04Z |
| **关键词** | `RAG` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2611.33943v1](http://arxiv.org/abs/2611.33943v1) |

**📝 摘要概括：**

> Agent 技能是指令、参考资料和脚本的目录，由 Coding Agent 按需加载。根据 SkillsBench 的数据，虽然人工策划的技能平均可以将通过率提高约 16.6 个百分点（pp），但它们实际上降低了一些任务的结果。我们已发布审计账本和分析脚本。

</details>

<details>
<summary><b>19. Connecting AI Agents to Live Discrete Element Simulations via the Model Context Protocol</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Yusong Han、Ryosuke Uzuoka、Kyohei Ueda |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、CAS、TRI |
| **发布时间** | 2026-11-25T07:46:35Z |
| **关键词** | `AI Agent` · `RAG` · `Simulation` |
| **原文链接** | [http://arxiv.org/abs/2611.33926v1](http://arxiv.org/abs/2611.33926v1) |

**📝 摘要概括：**

> 本文介绍了一种模型上下文协议（MCP）服务器，通过该服务器，通用人工智能代理在模拟运行期间可以操作商业或开源的离散元引擎。代理将一个长时间模拟提交给引擎，并在引擎计算过程中读取正在运行的模型、对其进行更改或将其停止。服务器和桥接器以两个开源软件包的形式发布，即itasca-mcp，该软件包还适用于FLAC、3DEC、MPoint和MassFlow，以及y…

</details>

<details>
<summary><b>20. EGSE: Evidence-Grounded Skill Evolution for Medical Reasoning Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Mingyuan Li、Tong Jia、Ziyuan Yang、Wenbo Qi、Haoran Wang 等（共 7 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | CAS、Mila、TRI |
| **发布时间** | 2026-11-25T07:28:21Z |
| **关键词** | `Reasoning` · `Benchmark` · `Workflow` |
| **原文链接** | [http://arxiv.org/abs/2611.33909v1](http://arxiv.org/abs/2611.33909v1) |

**📝 摘要概括：**

> 医学推理代理将基础模型与专用工具相结合来解读医学影像，但要重复利用它们的历史经验仍然存在挑战。正确的最终答案可能会掩盖有缺陷的推理或工具使用，合成的建议可能缺乏来源支持，表面上相似的病例可能需要不同的诊断程序。它还在七个基础模型中实现了稳定的准确性提升，并支持技能迁移……

</details>

## 🗄️ 历史归档

| 日期 | 论文数 | 报告链接 |
|------|--------|----------|
| 2026-11-26 | 20 篇 | [2026-11-26.md](daily/2026-11-26.md) |
| 2026-11-25 | 20 篇 | [2026-11-25.md](daily/2026-11-25.md) |
| 2026-11-24 | 20 篇 | [2026-11-24.md](daily/2026-11-24.md) |
| 2026-11-23 | 0 篇 | [2026-11-23.md](daily/2026-11-23.md) |
| 2026-11-22 | 0 篇 | [2026-11-22.md](daily/2026-11-22.md) |
| 2026-11-21 | 16 篇 | [2026-11-21.md](daily/2026-11-21.md) |
| 2026-11-20 | 20 篇 | [2026-11-20.md](daily/2026-11-20.md) |
| 2026-11-05 | 13 篇 | [2026-11-05.md](daily/2026-11-05.md) |
| 2026-11-04 | 20 篇 | [2026-11-04.md](daily/2026-11-04.md) |
| 2026-11-03 | 0 篇 | [2026-11-03.md](daily/2026-11-03.md) |
| 2026-11-02 | 0 篇 | [2026-11-02.md](daily/2026-11-02.md) |
| 2026-11-01 | 0 篇 | [2026-11-01.md](daily/2026-11-01.md) |
| 2026-10-31 | 17 篇 | [2026-10-31.md](daily/2026-10-31.md) |
| 2026-10-30 | 0 篇 | [2026-10-30.md](daily/2026-10-30.md) |
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

## 🏛️ 顶级机构覆盖范围

覆盖超过 **70 个**顶级 AI 机构，包括：

- **科技公司：** Microsoft、Google DeepMind、OpenAI、Anthropic、Meta AI、NVIDIA、Baidu、Alibaba、ByteDance 等
- **北美顶级大学：** MIT、Stanford、CMU、UC Berkeley、Harvard、Princeton、Cornell、Caltech 等
- **中国顶级大学/机构：** 清华大学、北京大学、浙大、上交大、复旦、中科院、MSRA 等
- **欧洲/其他：** Oxford、Cambridge、ETH Zurich、Mila、NUS、KAIST 等

---

*由 [clawBot DailyFindings](https://github.com/Jacob-biu/clawBot) 自动维护 | 最后更新：2026-11-26 03:58 UTC*
