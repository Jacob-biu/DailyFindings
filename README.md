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

## 📅 今日论文 — 2026-07-28　　[→ 查看完整报告](daily/2026-07-28.md)

> 共筛选出 **14** 篇论文 | 更新于 2026-07-28 22:57 UTC

### 论文目录与概要

| # | 论文标题 | 核心概要 | 来源机构 | 第一作者 |
|---|---------|---------|---------|--------|
| 1 | [ClinFusion: A Vision-Centric Multimodal LLM System for Holis…](http://arxiv.org/abs/2607.24743v1) | 多模态大型语言模型（ MLLM ）具有革新临床实践的巨大潜力，但在医学领域部署它们从根本上是一个以视觉为中心的挑战：模型必须从异构2D和3D医学图像中吸收知识，评估方案必须与放射科医生的临床实践保持一… | MIT、HIT | Hangjie Yuan |
| 2 | [The Physics of Multi-Turn Long-Horizon Planning: From Pre-tr…](http://arxiv.org/abs/2607.24720v1) | 多轮长远规划对于基础模型代理至关重要，但如何从根本上改善它仍不清楚。现有模型在不可控和不透明的互联网数据上进行培训，因此很难确定规划能力是如何获得、塑造和整合的。兼容的模式能够实现跨环境的泛化，部分共… | TRI | Tianyi Men |
| 3 | [Explainable Reinforcement Learning via Physics-Aware Policy …](http://arxiv.org/abs/2607.24672v1) | 在机器人和汽车工程等安全关键领域，深度强化学习（ DRL ）的部署经常受到深度神经网络黑箱性质的阻碍。这种缺乏透明度的情况对监管合规和人员代理信任构成了重大挑战。仿真结果表明，在为SAF提供全局和局部… | MIT | Shaker Al-Tamari |
| 4 | [A corrective agentic hybrid RAG and an operations-grounded e…](http://arxiv.org/abs/2607.24663v1) | 科学用户设施积累了数十年的运营知识，没有单一的搜索索引涵盖：电子日志、技术文档、内部维基、运营聊天消息、维护记录和实时控制系统数据。我们介绍APS-RAG ，高级光子源检索增强生成，这是一个部署的平台… | TRI | Rajat Sainju |
| 5 | [Agentic Permissions Policy Algebra for Taint Confinement in …](http://arxiv.org/abs/2607.24625v1) | 处理混合保密数据的自主LLM代理面临来自即时注入攻击和推理错误的严重安全风险。虽然动态信息流控制（ IFC ）提供了结构安全保障，但传统的污点跟踪在读取未经审核的数据时会永久污染代理的上下文，严重限制… | TRI | Arseny Kravchenko |
| 6 | [Looping Is Not Reliability: State-Bound Evidence and Typed R…](http://arxiv.org/abs/2607.24604v1) | 生成-测试-修改循环在编码代理中很常见，但仅重复并不能提供可靠性保证。我们研究了找到正确的补丁与保留、验证和提交补丁之间的差距。实施是可执行规范和一致性制品，而不是提高维修能力或校准验证器依赖性的证据… | MIT | Xueping Gao |
| 7 | [SIREN: Towards End-to-End Extreme-Weather Early Warning with…](http://arxiv.org/abs/2607.24588v1) | 极端天气预警对于减轻危险天气事件带来的社会、经济和环境风险至关重要。然而，以专家为中心的预警工作流程成本高昂、劳动密集型，并且难以在整个预警到行动过程中扩展。广泛的实验表明，警报器在单个警告程序和端到… | MIT、CAS | Hang Ni |
| 8 | [Evaluating Fuzz Testing for Reinforcement Learning Agents](http://arxiv.org/abs/2607.24577v1) | 强化学习（ RL ）代理越来越多地部署在机器人、自动驾驶和无人机控制等安全关键领域，在这些领域，意外行为可能导致严重的现实后果。模糊测试最近已成为探索RL代理的广阔状态空间和暴露崩溃的一种有前途的方法… | TRI | Zhibin Kang |
| 9 | [Failures Reveal What Metrics Miss: An Evidence-Driven Agent …](http://arxiv.org/abs/2607.24419v1) | 深度模型已经大幅推进了12导联心电图分类，但它们的细化仍然严重依赖于人类专家来检查故障并迭代修改分类器设计。最近基于LLM的代理已经证明了自动化模型设计的潜力，但是当仅以汇总绩效指标为指导时，他们缺乏… | MIT、CAS | Jinliang Deng |
| 10 | [Beyond Aggregate Risk: Role-Stratified Conformal Risk Contro…](http://arxiv.org/abs/2607.24343v1) | 语言模型代理通过结构化工具调用采取行动，其参数具有不同的风险。不受信任的内容可能会安全地影响电子邮件正文，但不应确定收件人、帐户、命令或凭据。这些结果表明，结构化工具调用应该在语义角色层面进行认证，而… | TRI | Md Ashikur Rahman |
| 11 | [Gubernaut: A Deterministic Homeostatic Controller for Affect…](http://arxiv.org/abs/2607.24339v1) | 大型语言模型（ LLM ）代理人继承了反应性失败模式：挑衅下的升级，奉承下的讽刺漂移，卡住时的毅力。这些是倾向的失败，而不是能力的失败；它们涉及模型在持续压力下的作用，训练时间对齐会减少，但不会在运行… | HIT、TRI | Dushyant Sharma |
| 12 | [Teacher Knows It Best: Spontaneous Symmetry Breaking and Tip…](http://arxiv.org/abs/2607.24304v1) | 我们制定了一个统计物理框架，对由加性噪声和社会整合驱动的表现出双稳性的网络随机动力系统进行建模。我们应用此模型来理解和缓解人工智能引发的妄想螺旋现象，即大型语言模型的算法嘲讽不断强化社会互动社会中的不… | MIT、TRI | Sayantari Ghosh |
| 13 | [From Proprietary to Open-Source: Bridging the Distribution G…](http://arxiv.org/abs/2607.24280v1) | 代理搜索通过将多步推理和检索交织在一起，使大型语言模型能够解决知识密集型任务，但通过基于结果的强化学习（ RL ）进行优化只能提供稀疏的监督。知识蒸馏可以提供更密集的指导，具有强大推理能力的先进专有模… | MIT、TRI | Junlin Liu |
| 14 | [A Computational Ethical Framework for Financial Digital Phen…](http://arxiv.org/abs/2607.24275v1) | 人工智能驱动系统的道德治理通常通过高级原则和静态文档来表达，从而在监管要求和系统级验证之间造成差距。这一挑战在数字表型中尤为严重，持续的行为数据引发了对同意、隐私和公平性的担忧。我们讨论了局限性，包括… | FAIR、MIT | Oluwadara Adedeji |

### 论文详情

<details>
<summary><b>1. ClinFusion: A Vision-Centric Multimodal LLM System for Holistic Medical Understanding</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Hangjie Yuan、Yichen Qian、Zhiwei Tang、Xianzhe Xu、Lirong Wu 等（共 24 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、HIT、CAS |
| **发布时间** | 2026-07-27T17:59:49Z |
| **关键词** | `Agentic` · `Retrieval` · `Benchmark` · `Evaluation` · `Workflow` |
| **原文链接** | [http://arxiv.org/abs/2607.24743v1](http://arxiv.org/abs/2607.24743v1) |

**📝 摘要概括：**

> 多模态大型语言模型（ MLLM ）具有革新临床实践的巨大潜力，但在医学领域部署它们从根本上是一个以视觉为中心的挑战：模型必须从异构2D和3D医学图像中吸收知识，评估方案必须与放射科医生的临床实践保持一致，并提供准确、细粒度和以事实为导向的评估。在本文中，我们将介绍ClinFusion ，一种

</details>

<details>
<summary><b>2. The Physics of Multi-Turn Long-Horizon Planning: From Pre-training to Post-training via Single- and Multi-Teacher On-Policy Agentic Distillation</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Tianyi Men、Zhuoran Jin、Kang Liu、Jun Zhao |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-07-27T17:55:03Z |
| **关键词** | `Agentic` · `Planning` |
| **原文链接** | [http://arxiv.org/abs/2607.24720v1](http://arxiv.org/abs/2607.24720v1) |

**📝 摘要概括：**

> 多轮长远规划对于基础模型代理至关重要，但如何从根本上改善它仍不清楚。现有模型在不可控和不透明的互联网数据上进行培训，因此很难确定规划能力是如何获得、塑造和整合的。兼容的模式能够实现跨环境的泛化，部分共享的模式支持持续学习，而完全冲突的模式会导致...

</details>

<details>
<summary><b>3. Explainable Reinforcement Learning via Physics-Aware Policy Distillation</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Shaker Al-Tamari、Waled Kadour |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT |
| **发布时间** | 2026-07-27T17:14:42Z |
| **关键词** | `Reinforcement Learning` · `RAG` · `Benchmark` · `Simulation` · `Robotics` |
| **原文链接** | [http://arxiv.org/abs/2607.24672v1](http://arxiv.org/abs/2607.24672v1) |

**📝 摘要概括：**

> 在机器人和汽车工程等安全关键领域，深度强化学习（ DRL ）的部署经常受到深度神经网络黑箱性质的阻碍。这种缺乏透明度的情况对监管合规和人员代理信任构成了重大挑战。仿真结果表明，在为SAF提供全局和局部可解释性的同时，保持了有限输入有界输出（ BIBO ）的稳定性。

</details>

<details>
<summary><b>4. A corrective agentic hybrid RAG and an operations-grounded evaluation for a scientific facility</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Rajat Sainju、Dariusz Jarosz、Hairong Shang、Michael Prince、Ryan M. Aydelott 等（共 8 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-07-27T17:01:30Z |
| **关键词** | `Agentic` · `RAG` · `Retrieval` · `Evaluation` · `Workflow` |
| **原文链接** | [http://arxiv.org/abs/2607.24663v1](http://arxiv.org/abs/2607.24663v1) |

**📝 摘要概括：**

> 科学用户设施积累了数十年的运营知识，没有单一的搜索索引涵盖：电子日志、技术文档、内部维基、运营聊天消息、维护记录和实时控制系统数据。我们介绍APS-RAG ，高级光子源检索增强生成，这是一个部署的平台，使高级光子源（ APS ）的机构知识可供员工通过天然光子源访问。

</details>

<details>
<summary><b>5. Agentic Permissions Policy Algebra for Taint Confinement in LLM Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Arseny Kravchenko、Vadim Liventsev、Innokentii Konstantinov、Ildar Iskhakov、Matvey Kukuy |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-07-27T16:19:45Z |
| **关键词** | `LLM Agent` · `Agentic` · `Reasoning` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2607.24625v1](http://arxiv.org/abs/2607.24625v1) |

**📝 摘要概括：**

> 处理混合保密数据的自主LLM代理面临来自即时注入攻击和推理错误的严重安全风险。虽然动态信息流控制（ IFC ）提供了结构安全保障，但传统的污点跟踪在读取未经审核的数据时会永久污染代理的上下文，严重限制了下游实用程序。最后，我们在四个模型的多圈工具链基准上评估APPA ：它适用于……

</details>

<details>
<summary><b>6. Looping Is Not Reliability: State-Bound Evidence and Typed Revision Contracts for Agentic Code Repair</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Xueping Gao、Jianwei Yang、Qiang Yang |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT |
| **发布时间** | 2026-07-27T16:05:23Z |
| **关键词** | `Agentic` |
| **原文链接** | [http://arxiv.org/abs/2607.24604v1](http://arxiv.org/abs/2607.24604v1) |

**📝 摘要概括：**

> 生成-测试-修改循环在编码代理中很常见，但仅重复并不能提供可靠性保证。我们研究了找到正确的补丁与保留、验证和提交补丁之间的差距。实施是可执行规范和一致性制品，而不是提高维修能力或校准验证器依赖性的证据。

</details>

<details>
<summary><b>7. SIREN: Towards End-to-End Extreme-Weather Early Warning with Experience-Grounded LLM Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Hang Ni、Weijia Zhang、Fan Liu、Mengqian Lu、Hao Liu |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、CAS、TRI |
| **发布时间** | 2026-07-27T15:53:19Z |
| **关键词** | `LLM Agent` · `Agentic` · `Retrieval` · `Benchmark` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2607.24588v1](http://arxiv.org/abs/2607.24588v1) |

**📝 摘要概括：**

> 极端天气预警对于减轻危险天气事件带来的社会、经济和环境风险至关重要。然而，以专家为中心的预警工作流程成本高昂、劳动密集型，并且难以在整个预警到行动过程中扩展。广泛的实验表明，警报器在单个警告程序和端到端警告链上的性能优于气象代理基线。

</details>

<details>
<summary><b>8. Evaluating Fuzz Testing for Reinforcement Learning Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Zhibin Kang、Hanmo You、Dong Wang、Haiming Zheng、Junjie Chen |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-07-27T15:46:57Z |
| **关键词** | `Reinforcement Learning` · `RAG` · `Benchmark` · `Evaluation` · `Robotics` |
| **原文链接** | [http://arxiv.org/abs/2607.24577v1](http://arxiv.org/abs/2607.24577v1) |

**📝 摘要概括：**

> 强化学习（ RL ）代理越来越多地部署在机器人、自动驾驶和无人机控制等安全关键领域，在这些领域，意外行为可能导致严重的现实后果。模糊测试最近已成为探索RL代理的广阔状态空间和暴露崩溃的一种有前途的方法。除了这些实证研究结果之外，我们还为研究人员和从业人员提供了可行的指导……

</details>

<details>
<summary><b>9. Failures Reveal What Metrics Miss: An Evidence-Driven Agent for Recursive Refinement of ECG Classifiers</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Jinliang Deng、Yiming Niu、Yibo Pan、Zhiqi Shao、Qin Luo 等（共 6 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、CAS、TRI |
| **发布时间** | 2026-07-27T13:31:24Z |
| **关键词** | `RAG` |
| **原文链接** | [http://arxiv.org/abs/2607.24419v1](http://arxiv.org/abs/2607.24419v1) |

**📝 摘要概括：**

> 深度模型已经大幅推进了12导联心电图分类，但它们的细化仍然严重依赖于人类专家来检查故障并迭代修改分类器设计。最近基于LLM的代理已经证明了自动化模型设计的潜力，但是当仅以汇总绩效指标为指导时，他们缺乏对个别案例失败的原因以及如何修改分类器的见解。大量消融和移植……

</details>

<details>
<summary><b>10. Beyond Aggregate Risk: Role-Stratified Conformal Risk Control for LLM Tool Calls</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Md Ashikur Rahman、Md Arifur Rahman、Niamul Hassan Samin、Khandaker Rifah Tasnia、Sifat Rahman Ahona 等（共 6 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-07-27T12:21:18Z |
| **关键词** | — |
| **原文链接** | [http://arxiv.org/abs/2607.24343v1](http://arxiv.org/abs/2607.24343v1) |

**📝 摘要概括：**

> 语言模型代理通过结构化工具调用采取行动，其参数具有不同的风险。不受信任的内容可能会安全地影响电子邮件正文，但不应确定收件人、帐户、命令或凭据。这些结果表明，结构化工具调用应该在语义角色层面进行认证，而不是整个操作。

</details>

<details>
<summary><b>11. Gubernaut: A Deterministic Homeostatic Controller for Affect-Regulated LLM Agents, Validated Across Independent Model Families</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Dushyant Sharma |
| **所属机构** | （详见原文） |
| **顶级机构标签** | HIT、TRI |
| **发布时间** | 2026-07-27T12:17:21Z |
| **关键词** | `LLM Agent` |
| **原文链接** | [http://arxiv.org/abs/2607.24339v1](http://arxiv.org/abs/2607.24339v1) |

**📝 摘要概括：**

> 大型语言模型（ LLM ）代理人继承了反应性失败模式：挑衅下的升级，奉承下的讽刺漂移，卡住时的毅力。这些是倾向的失败，而不是能力的失败；它们涉及模型在持续压力下的作用，训练时间对齐会减少，但不会在运行时消除。没有意识声明。

</details>

<details>
<summary><b>12. Teacher Knows It Best: Spontaneous Symmetry Breaking and Tipping Points in Networked Langevin Dynamics AI Sycophancy</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Sayantari Ghosh、Saumik Bhattacharya、Partha Pratim Chakrabarti |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-07-27T11:47:57Z |
| **关键词** | — |
| **原文链接** | [http://arxiv.org/abs/2607.24304v1](http://arxiv.org/abs/2607.24304v1) |

**📝 摘要概括：**

> 我们制定了一个统计物理框架，对由加性噪声和社会整合驱动的表现出双稳性的网络随机动力系统进行建模。我们应用此模型来理解和缓解人工智能引发的妄想螺旋现象，即大型语言模型的算法嘲讽不断强化社会互动社会中的不准确信念。我们用数学方法证明，在某些条件下， ……

</details>

<details>
<summary><b>13. From Proprietary to Open-Source: Bridging the Distribution Gap via Multi-Agent Protocol Distillation in Agentic Search</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Junlin Liu、Jiangwang Chen、Zixin Song、Shuaiyu Zhou、Chunji Lv 等（共 10 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-07-27T11:27:38Z |
| **关键词** | `Multi-Agent` · `Agentic` · `Reasoning` · `Reinforcement Learning` · `RAG` |
| **原文链接** | [http://arxiv.org/abs/2607.24280v1](http://arxiv.org/abs/2607.24280v1) |

**📝 摘要概括：**

> 代理搜索通过将多步推理和检索交织在一起，使大型语言模型能够解决知识密集型任务，但通过基于结果的强化学习（ RL ）进行优化只能提供稀疏的监督。知识蒸馏可以提供更密集的指导，具有强大推理能力的先进专有模型是有前途的教师。至关重要的是，该框架稳健地概括了各种所有权……

</details>

<details>
<summary><b>14. A Computational Ethical Framework for Financial Digital Phenotyping for Mental Health</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Oluwadara Adedeji、Michael Mayowa Farayola、Jeff Brozena、Irina Tal、Regina Connolly 等（共 6 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | FAIR、MIT、CAS |
| **发布时间** | 2026-07-27T11:19:52Z |
| **关键词** | `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2607.24275v1](http://arxiv.org/abs/2607.24275v1) |

**📝 摘要概括：**

> 人工智能驱动系统的道德治理通常通过高级原则和静态文档来表达，从而在监管要求和系统级验证之间造成差距。这一挑战在数字表型中尤为严重，持续的行为数据引发了对同意、隐私和公平性的担忧。我们讨论了局限性，包括使用数据进行真实世界验证的必要性，以及主题的挑战……

</details>

## 🗄️ 历史归档

| 日期 | 论文数 | 报告链接 |
|------|--------|----------|
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
| 2026-07-05 | 0 篇 | [2026-07-05.md](daily/2026-07-05.md) |
| 2026-07-04 | 0 篇 | [2026-07-04.md](daily/2026-07-04.md) |
| 2026-07-03 | 20 篇 | [2026-07-03.md](daily/2026-07-03.md) |
| 2026-07-02 | 0 篇 | [2026-07-02.md](daily/2026-07-02.md) |
| 2026-07-01 | 0 篇 | [2026-07-01.md](daily/2026-07-01.md) |
| 2026-06-30 | 20 篇 | [2026-06-30.md](daily/2026-06-30.md) |
| 2026-06-29 | 0 篇 | [2026-06-29.md](daily/2026-06-29.md) |
| 2026-06-28 | 0 篇 | [2026-06-28.md](daily/2026-06-28.md) |

## 🏛️ 顶级机构覆盖范围

覆盖超过 **70 个**顶级 AI 机构，包括：

- **科技公司：** Microsoft、Google DeepMind、OpenAI、Anthropic、Meta AI、NVIDIA、Baidu、Alibaba、ByteDance 等
- **北美顶级大学：** MIT、Stanford、CMU、UC Berkeley、Harvard、Princeton、Cornell、Caltech 等
- **中国顶级大学/机构：** 清华大学、北京大学、浙大、上交大、复旦、中科院、MSRA 等
- **欧洲/其他：** Oxford、Cambridge、ETH Zurich、Mila、NUS、KAIST 等

---

*由 [clawBot DailyFindings](https://github.com/Jacob-biu/clawBot) 自动维护 | 最后更新：2026-07-28 22:57 UTC*
