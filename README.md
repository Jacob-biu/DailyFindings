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

## 📅 今日论文 — 2026-08-14　　[→ 查看完整报告](daily/2026-08-14.md)

> 共筛选出 **20** 篇论文 | 更新于 2026-08-14 22:21 UTC

### 论文目录与概要

| # | 论文标题 | 核心概要 | 来源机构 | 第一作者 |
|---|---------|---------|---------|--------|
| 1 | [OmniScientist: An Omni-Modal Omni-Discipline AI Scientist](http://arxiv.org/abs/2608.13558v1) | 基础模型的最新进展使人工智能科学家能够自动化越来越完整的研究工作流程，从假设生成和代码执行到手稿准备。然而，仅靠工作流程覆盖并不能提供科学发现所依赖的全部证据。这些结果表明，全生命周期感知对于以证据为… | CAS、NUS | Bobo Li |
| 2 | [QuoteBench: How Matched Scores Can Hide Command-Path Failure…](http://arxiv.org/abs/2608.13547v1) | LLM编码代理通过可能序列化、包装和重新分析模型输出的接口发出Bash命令。仅匹配的执行分数无法区分命令生成错误和生成后引入的失败。对命令发布代理的评估应报告模型配置、生成合同、执行路径、操作点和最终… | TRI | Shangao Li |
| 3 | [Vero: Can AI Agents Build Formally Verified Software Reposit…](http://arxiv.org/abs/2608.13522v1) | 人工智能代理越来越多地用于编程，但不能对生成的代码的正确性提供任何保证。经过验证的代码生成，其中代理生成其规范的实现和机器检查的证明，为可信赖的人工智能生成软件提供了更强大的途径。我们在https:/… | TRI | Zhe Ye |
| 4 | [On the Structural Limits of Machine Learning Decision System…](http://arxiv.org/abs/2608.13510v1) | 机器学习过程通常在预测准确性和计算效率方面进行评估。然而，它们的可实现性能从根本上受到底层数据生成过程的结构属性的限制，这些数据生成过程在信息边界方面形式化。这种观点强调了拥有足够的数据模型作为扩展预… | MIT、HIT | Nestor R. Barraza |
| 5 | [Intern-S2-Preview: Scientific Agentic Foundation Model](http://arxiv.org/abs/2608.13505v1) | 科学发现越来越需要人工智能系统，这些系统可以根据异构模式的科学证据进行推理，与科学工具和环境进行交互，并在长期任务范围内保持进展。我们提出了Intern-S2-Preview ，这是一系列科学代理基础… | HIT、CAS | Lei Bai |
| 6 | [MARC v1: An Open-Source Multi-Agent Framework for Clinical A…](http://arxiv.org/abs/2608.13476v1) | 我们提出了多Agent推理和协调（ MARC ） ，这是一个开源框架，用确定性的多Agent编排取代了单片LLM提示，用于临床推理。MARC通过明确的上下文传递和可追溯的中间输出，协调角色专用代理的提… | TRI | Saisha Shetty |
| 7 | [AaLLM: An End-to-End Analog Circuit Design Framework from To…](http://arxiv.org/abs/2608.13472v1) | 模拟电路设计是非线性和高维设计空间中耗时的迭代过程，严重依赖于专家的直觉。在最近的发展中，法学硕士通过将自然语言推理引入电路设计任务，引入了一种有前途的方法。结果还显示，与现有方法相比，挂钟时间减少了… | NTU、TRI | Mohammed Ayman Habib |
| 8 | [MLLM-Routed Heterogeneous Ensembles for Robust Cross-Dataset…](http://arxiv.org/abs/2608.13463v1) | 现代图像分类模型在单个任务特定数据集上训练时表现出色，但通常难以跨领域和难度级别进行泛化。我们提出了ARMDIL ，这是一种使用LLM进行多域图像分类的自适应路由器。跨数据集图像分类的这些进步为更可靠… | HIT、TRI | Daniel Perkins |
| 9 | [A Unifying Perspective on Causal World Models: From Observat…](http://arxiv.org/abs/2608.13456v1) | 世界模型（ WM ）越来越被视为智能代理的基础，这些智能代理可以预测、计划和行动，超越其培训分布。在本文中，我们从多个抽象层次的因果角度研究WM ，从感知观察到构建管理环境动态的结构的概念表示。因此，… | TRI | Avinash Kori |
| 10 | [UniTexture: Cross-Task Universal Adversarial Textures for Vi…](http://arxiv.org/abs/2608.13453v1) | 视觉-语言-行动（ VLA ）模型已成为通用机器人策略，能够遵循不同的语言指令并执行各种操作任务。然而，他们对具体代理人的直接控制也使他们面临对抗性干扰，这可能导致不安全的身体行为。这些发现共同揭示了… | TRI | Yukun Dai |
| 11 | [RAIL: An Automatic Classifier of the Artificial Intelligence…](http://arxiv.org/abs/2608.13428v1) | 评估人工智能技术的成熟度对于投资决策、项目管理和政策监控至关重要，但可用的准备框架是异构的，难以自动应用：技术准备水平对人工智能的适应缺乏特定于人工智能的门禁标准，机器学习技术准备水平预先假定访问内部… | TRI | Juan Irving Vasquez |
| 12 | [Enhancing Virtual Agents through SLMs and Edge-Computing: An…](http://arxiv.org/abs/2608.13420v1) | 嵌入式智能虚拟代理有望在复杂的虚拟和元宇宙世界中作为持久、自适应和上下文感知的实体运行。然而，在这样的环境中实施具有认知能力的智能体在概念上和技术上都具有挑战性。一系列模拟实验评估了路由精度、内存读取… | NVIDIA、HIT | Aimilios Hadjiliasi |
| 13 | [Beyond Final Scores: A Systematic Evaluation of Agents for L…](http://arxiv.org/abs/2608.13417v1) | 自主代理越来越有能力通过长距离实验来改进模型、系统和其他技术制品。然而，要了解这种能力的当前状态，评估必须超越最终分数，最终分数既不揭示取得或失去的进展，也不表明积累的经验是否改善了后来的决策。这些研… | Mila、TRI | Yiwei Li |
| 14 | [Heterogeneity-Aware Belief Synchronization for Semantic Comm…](http://arxiv.org/abs/2608.13394v1) | 6G网络将不仅仅用作通信基础设施；相反，它们有望发展成为智能系统，其中成千上万的自主人工智能（ AI ）代理相互连接。这些智能体部署在各种平台上，包括低地球轨道（ LEO ）卫星、高空平台（ HAP … | MIT、HIT | Muhammad Hannan Akram |
| 15 | [Training AI Scientists to Replicate Research](http://arxiv.org/abs/2608.13331v1) | 论文的可复制性是科学知识的基石，确保了现有结果的可靠性，并为进一步的实验提供了基础。复制行为通常会阐明以前未指定的细节，因此需要类似于假设驱动的探索来进行开放式研究。我们相信，我们的研究结果为能够进行… | Mila | Damon Falck |
| 16 | [StateBridge: Training-free Hidden-state Alignment for Latent…](http://arxiv.org/abs/2608.13317v1) | 基于大型语言模型的多智能体系统通常以文本形式进行通信，即使用离散令牌。然而，文本引入了一个离散的瓶颈。StateBridge在26个模型任务对中的22个模型任务对中取得了最佳或并列最佳分数，始终优于最… | MIT、TRI | Yanwen Peng |
| 17 | [Capability Sheaves for Compositional Agent-Harness Repair: C…](http://arxiv.org/abs/2608.13228v1) | 客服代表将检索、路由、状态、来源和验证相结合，但本地成功的组件可能在共享状态上存在分歧。我们使用有限的\ emph {capability sheaf}对此故障进行建模：跟踪编码类型化的行为签名，限制… | TRI | Saveliy Batruin |
| 18 | [Teach the Magnitude, Not the Direction: Verifier-Bounded Cre…](http://arxiv.org/abs/2608.13179v1) | 具有可验证奖励的强化学习（ RLVR ）为训练多回合工具使用代理提供了一个受验证者限制的性能上限，但其轨迹级信用分配将异构每回合结果合并为单个奖励信号。按策略蒸馏提供密集的每代币监督，但要么是教师限制… | TRI | Zechuan Wang |
| 19 | [SkillShapley: Boundary-Adaptive Shapley Valuation for Skill …](http://arxiv.org/abs/2608.13173v1) | 代理技能是至关重要的外部指令，使语言代理能够执行长时间的程序性任务，如编码或文档处理。现有的座席技能主要是通过人工手工制作或座席执行跟踪创建的，对每个步骤如何有助于特定任务的整体技能表现的理解有限；即… | MIT、TRI | Chang Liu |
| 20 | [SkillEvo: Self-Renewing Evolution Gradients from Multi-Turn …](http://arxiv.org/abs/2608.13120v1) | 今天，座席技能要么是手写的，要么是在单个LLM生成通行证中产生的，因此没有闭环，可以通过它们从实际导致的交互失败中改进。最近的工作确实关闭了这个循环，但其反馈来自单轮问答评估。在六个类别的云服务、9个… | CAS | Qianxi Yan |

### 论文详情

<details>
<summary><b>1. OmniScientist: An Omni-Modal Omni-Discipline AI Scientist</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Bobo Li、Hao Fei、Tianjie Ju、Mong-Li Lee、Wynne Hsu |
| **所属机构** | （详见原文） |
| **顶级机构标签** | CAS、NUS |
| **发布时间** | 2026-08-13T17:59:52Z |
| **关键词** | `Reasoning` · `RAG` · `Evaluation` · `Workflow` |
| **原文链接** | [http://arxiv.org/abs/2608.13558v1](http://arxiv.org/abs/2608.13558v1) |

**📝 摘要概括：**

> 基础模型的最新进展使人工智能科学家能够自动化越来越完整的研究工作流程，从假设生成和代码执行到手稿准备。然而，仅靠工作流程覆盖并不能提供科学发现所依赖的全部证据。这些结果表明，全生命周期感知对于以证据为基础的科学发现至关重要，并提供了一条通往...

</details>

<details>
<summary><b>2. QuoteBench: How Matched Scores Can Hide Command-Path Failures</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Shangao Li、Yao Zhang、Volker Tresp、Yuanyuan Yang |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-08-13T17:57:20Z |
| **关键词** | `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2608.13547v1](http://arxiv.org/abs/2608.13547v1) |

**📝 摘要概括：**

> LLM编码代理通过可能序列化、包装和重新分析模型输出的接口发出Bash命令。仅匹配的执行分数无法区分命令生成错误和生成后引入的失败。对命令发布代理的评估应报告模型配置、生成合同、执行路径、操作点和最终状态验证器，而不是将匹配的分数视为内在模型属性。

</details>

<details>
<summary><b>3. Vero: Can AI Agents Build Formally Verified Software Repositories?</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Zhe Ye、Hantao Lou、Yuechun Sun、Peiyang Song、Zhengxu Yan 等（共 11 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-08-13T17:41:27Z |
| **关键词** | `AI Agent` · `Benchmark` · `Evaluation` · `Code Generation` |
| **原文链接** | [http://arxiv.org/abs/2608.13522v1](http://arxiv.org/abs/2608.13522v1) |

**📝 摘要概括：**

> 人工智能代理越来越多地用于编程，但不能对生成的代码的正确性提供任何保证。经过验证的代码生成，其中代理生成其规范的实现和机器检查的证明，为可信赖的人工智能生成软件提供了更强大的途径。我们在https://github.com/sunblaze-ucb/vero上发布了基准、策展流程和评估工具。

</details>

<details>
<summary><b>4. On the Structural Limits of Machine Learning Decision Systems: An Information-Theoretic, Interaction-Based, and Stochastic-Dynamical Perspective</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Nestor R. Barraza、Gabriel Pena |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、HIT、TRI |
| **发布时间** | 2026-08-13T17:34:41Z |
| **关键词** | — |
| **原文链接** | [http://arxiv.org/abs/2608.13510v1](http://arxiv.org/abs/2608.13510v1) |

**📝 摘要概括：**

> 机器学习过程通常在预测准确性和计算效率方面进行评估。然而，它们的可实现性能从根本上受到底层数据生成过程的结构属性的限制，这些数据生成过程在信息边界方面形式化。这种观点强调了拥有足够的数据模型作为扩展预测能力的先决条件的重要性，以及…

</details>

<details>
<summary><b>5. Intern-S2-Preview: Scientific Agentic Foundation Model</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Lei Bai、Jiaqi Cao、Chiyu Chen、Guanzhou Chen、Kai Chen 等（共 125 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | HIT、CAS |
| **发布时间** | 2026-08-13T17:31:28Z |
| **关键词** | `Agentic` · `Reasoning` · `Reinforcement Learning` · `RAG` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2608.13505v1](http://arxiv.org/abs/2608.13505v1) |

**📝 摘要概括：**

> 科学发现越来越需要人工智能系统，这些系统可以根据异构模式的科学证据进行推理，与科学工具和环境进行交互，并在长期任务范围内保持进展。我们提出了Intern-S2-Preview ，这是一系列科学代理基础模型，旨在支持多模态科学理解、推理、生成和长视野任务。时间序列模块提高了科学特征……

</details>

<details>
<summary><b>6. MARC v1: An Open-Source Multi-Agent Framework for Clinical AI Reasoning and Coordination</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Saisha Shetty、Satvik Tripathi、Austin Lin、Colin Zhao、Theodore Kim 等（共 9 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-08-13T17:00:08Z |
| **关键词** | `Multi-Agent` · `Reasoning` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2608.13476v1](http://arxiv.org/abs/2608.13476v1) |

**📝 摘要概括：**

> 我们提出了多Agent推理和协调（ MARC ） ，这是一个开源框架，用确定性的多Agent编排取代了单片LLM提示，用于临床推理。MARC通过明确的上下文传递和可追溯的中间输出，协调角色专用代理的提取、推理、答案生成和评估，从而实现分阶段的故障归因。完整框架可在https://github…

</details>

<details>
<summary><b>7. AaLLM: An End-to-End Analog Circuit Design Framework from Topology Generation to Sizing Using Large Language Models</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Mohammed Ayman Habib、Rylan Hart、Morteza Fayazi |
| **所属机构** | （详见原文） |
| **顶级机构标签** | NTU、TRI |
| **发布时间** | 2026-08-13T16:57:07Z |
| **关键词** | `Multi-Agent` · `Reasoning` · `RAG` · `Workflow` |
| **原文链接** | [http://arxiv.org/abs/2608.13472v1](http://arxiv.org/abs/2608.13472v1) |

**📝 摘要概括：**

> 模拟电路设计是非线性和高维设计空间中耗时的迭代过程，严重依赖于专家的直觉。在最近的发展中，法学硕士通过将自然语言推理引入电路设计任务，引入了一种有前途的方法。结果还显示，与现有方法相比，挂钟时间减少了40倍。

</details>

<details>
<summary><b>8. MLLM-Routed Heterogeneous Ensembles for Robust Cross-Dataset Image Classification</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Daniel Perkins、John Squires、Janou Milligan、Chandra Raskoti、Linda Ungerboeck |
| **所属机构** | （详见原文） |
| **顶级机构标签** | HIT、TRI |
| **发布时间** | 2026-08-13T16:45:24Z |
| **关键词** | `Reasoning` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2608.13463v1](http://arxiv.org/abs/2608.13463v1) |

**📝 摘要概括：**

> 现代图像分类模型在单个任务特定数据集上训练时表现出色，但通常难以跨领域和难度级别进行泛化。我们提出了ARMDIL ，这是一种使用LLM进行多域图像分类的自适应路由器。跨数据集图像分类的这些进步为更可靠的通用视觉系统（如人工智能助手和自主机器人）铺平了道路。

</details>

<details>
<summary><b>9. A Unifying Perspective on Causal World Models: From Observations to Representations to Structure</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Avinash Kori、Fabrizio Russo |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-08-13T16:40:35Z |
| **关键词** | `Reasoning` |
| **原文链接** | [http://arxiv.org/abs/2608.13456v1](http://arxiv.org/abs/2608.13456v1) |

**📝 摘要概括：**

> 世界模型（ WM ）越来越被视为智能代理的基础，这些智能代理可以预测、计划和行动，超越其培训分布。在本文中，我们从多个抽象层次的因果角度研究WM ，从感知观察到构建管理环境动态的结构的概念表示。因此，我们将WM植根于支持因果关系的表征和结构中……

</details>

<details>
<summary><b>10. UniTexture: Cross-Task Universal Adversarial Textures for Vision-Language-Action Models</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Yukun Dai、Mingzhe Dai、Tianshi Wang、Fengling Li、Jingjing Li 等（共 6 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-08-13T16:38:57Z |
| **关键词** | `Evaluation` · `Embodied AI` |
| **原文链接** | [http://arxiv.org/abs/2608.13453v1](http://arxiv.org/abs/2608.13453v1) |

**📝 摘要概括：**

> 视觉-语言-行动（ VLA ）模型已成为通用机器人策略，能够遵循不同的语言指令并执行各种操作任务。然而，他们对具体代理人的直接控制也使他们面临对抗性干扰，这可能导致不安全的身体行为。这些发现共同揭示了多任务VLA中的共享交叉任务漏洞，这些漏洞可以通过以下方式系统地利用……

</details>

<details>
<summary><b>11. RAIL: An Automatic Classifier of the Artificial Intelligence Readiness Level</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Juan Irving Vasquez、Juan Terven、Laura-Ivoone Garay-Jimenez |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-08-13T16:17:41Z |
| **关键词** | — |
| **原文链接** | [http://arxiv.org/abs/2608.13428v1](http://arxiv.org/abs/2608.13428v1) |

**📝 摘要概括：**

> 评估人工智能技术的成熟度对于投资决策、项目管理和政策监控至关重要，但可用的准备框架是异构的，难以自动应用：技术准备水平对人工智能的适应缺乏特定于人工智能的门禁标准，机器学习技术准备水平预先假定访问内部流程工件，而人工智能/数据的准备程度黯淡……

</details>

<details>
<summary><b>12. Enhancing Virtual Agents through SLMs and Edge-Computing: An Exploratory Evaluation of Think and Memory Processes</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Aimilios Hadjiliasi、Louis Nisiotis |
| **所属机构** | （详见原文） |
| **顶级机构标签** | NVIDIA、HIT |
| **发布时间** | 2026-08-13T16:12:52Z |
| **关键词** | `Reasoning` · `Planning` · `Evaluation` · `Simulation` · `Embodied AI` |
| **原文链接** | [http://arxiv.org/abs/2608.13420v1](http://arxiv.org/abs/2608.13420v1) |

**📝 摘要概括：**

> 嵌入式智能虚拟代理有望在复杂的虚拟和元宇宙世界中作为持久、自适应和上下文感知的实体运行。然而，在这样的环境中实施具有认知能力的智能体在概念上和技术上都具有挑战性。一系列模拟实验评估了路由精度、内存读取性能和延迟，演示了一个由SLM驱动的原型代理系统，该系统部分实现了……

</details>

<details>
<summary><b>13. Beyond Final Scores: A Systematic Evaluation of Agents for Long-Horizon AI Research and Development</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Yiwei Li、Wanli Yang、Hexiang Tan、Xiangzhou Huang、Zhengyu Chen 等（共 13 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | Mila、TRI |
| **发布时间** | 2026-08-13T16:11:22Z |
| **关键词** | `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2608.13417v1](http://arxiv.org/abs/2608.13417v1) |

**📝 摘要概括：**

> 自主代理越来越有能力通过长距离实验来改进模型、系统和其他技术制品。然而，要了解这种能力的当前状态，评估必须超越最终分数，最终分数既不揭示取得或失去的进展，也不表明积累的经验是否改善了后来的决策。这些研究结果为改进模型训练、推理t……提出了具体的方向。

</details>

<details>
<summary><b>14. Heterogeneity-Aware Belief Synchronization for Semantic Communication in AI-Native 6G Networks</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Muhammad Hannan Akram、Muhammad Abubakar Rashid、Wassi Haider Kabir、Haejoon Jung、Kapal Dev 等（共 6 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、HIT、CAS |
| **发布时间** | 2026-08-13T15:53:15Z |
| **关键词** | — |
| **原文链接** | [http://arxiv.org/abs/2608.13394v1](http://arxiv.org/abs/2608.13394v1) |

**📝 摘要概括：**

> 6G网络将不仅仅用作通信基础设施；相反，它们有望发展成为智能系统，其中成千上万的自主人工智能（ AI ）代理相互连接。这些智能体部署在各种平台上，包括低地球轨道（ LEO ）卫星、高空平台（ HAP ）、无人机（ UAV ）、边缘服务器和地面设备。结果表明，我……

</details>

<details>
<summary><b>15. Training AI Scientists to Replicate Research</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Damon Falck、Samer Sabri、Anja Surina、Thom Foster、Anya Sims 等（共 11 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | Mila |
| **发布时间** | 2026-08-13T14:59:27Z |
| **关键词** | `AI Agent` · `RAG` |
| **原文链接** | [http://arxiv.org/abs/2608.13331v1](http://arxiv.org/abs/2608.13331v1) |

**📝 摘要概括：**

> 论文的可复制性是科学知识的基石，确保了现有结果的可靠性，并为进一步的实验提供了基础。复制行为通常会阐明以前未指定的细节，因此需要类似于假设驱动的探索来进行开放式研究。我们相信，我们的研究结果为能够进行长期科学创新的人工智能代理提供了踏脚石……

</details>

<details>
<summary><b>16. StateBridge: Training-free Hidden-state Alignment for Latent Communication in LLM Multi-Agent Systems</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Yanwen Peng、Delvin Ce Zhang、Xi Wang、Nikolaos Aletras |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-08-13T14:40:59Z |
| **关键词** | `Multi-Agent` · `Reasoning` · `Code Generation` · `Memory` |
| **原文链接** | [http://arxiv.org/abs/2608.13317v1](http://arxiv.org/abs/2608.13317v1) |

**📝 摘要概括：**

> 基于大型语言模型的多智能体系统通常以文本形式进行通信，即使用离散令牌。然而，文本引入了一个离散的瓶颈。StateBridge在26个模型任务对中的22个模型任务对中取得了最佳或并列最佳分数，始终优于最强基线。

</details>

<details>
<summary><b>17. Capability Sheaves for Compositional Agent-Harness Repair: Controlled Quotients and a Real-Repository Stress Test</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Saveliy Batruin |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-08-13T13:31:09Z |
| **关键词** | `Reasoning` · `Retrieval` |
| **原文链接** | [http://arxiv.org/abs/2608.13228v1](http://arxiv.org/abs/2608.13228v1) |

**📝 摘要概括：**

> 客服代表将检索、路由、状态、来源和验证相结合，但本地成功的组件可能在共享状态上存在分歧。我们使用有限的\ emph {capability sheaf}对此故障进行建模：跟踪编码类型化的行为签名，限制映射保留共享字段，并且接受的运行是有用的全局部分。该研究支持受控不变性机制和可识别性校正，但不支持真实世界的cohomol……

</details>

<details>
<summary><b>18. Teach the Magnitude, Not the Direction: Verifier-Bounded Credit Assignment for Multi-Turn Multi-step LLM Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Zechuan Wang、Siyuan Lu、Hongxuan Zhang、Linjian Mo、Chenyi Zhuang 等（共 6 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-08-13T12:44:37Z |
| **关键词** | `LLM Agent` · `Reinforcement Learning` |
| **原文链接** | [http://arxiv.org/abs/2608.13179v1](http://arxiv.org/abs/2608.13179v1) |

**📝 摘要概括：**

> 具有可验证奖励的强化学习（ RLVR ）为训练多回合工具使用代理提供了一个受验证者限制的性能上限，但其轨迹级信用分配将异构每回合结果合并为单个奖励信号。按策略蒸馏提供密集的每代币监督，但要么是教师限制的，要么容易梯度浓度崩溃。我们的工作表明，教师在政策选择中的作用……

</details>

<details>
<summary><b>19. SkillShapley: Boundary-Adaptive Shapley Valuation for Skill Step Attribution in LLM Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Chang Liu、Yuqi Zhang、Yiman Zhong、Boyi Liu、Hengjun Wang 等（共 6 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-08-13T12:41:03Z |
| **关键词** | `LLM Agent` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2608.13173v1](http://arxiv.org/abs/2608.13173v1) |

**📝 摘要概括：**

> 代理技能是至关重要的外部指令，使语言代理能够执行长时间的程序性任务，如编码或文档处理。现有的座席技能主要是通过人工手工制作或座席执行跟踪创建的，对每个步骤如何有助于特定任务的整体技能表现的理解有限；即，在量化单个步骤在……中的贡献方面仍然存在一个悬而未决的问题。

</details>

<details>
<summary><b>20. SkillEvo: Self-Renewing Evolution Gradients from Multi-Turn Interaction Feedback</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Qianxi Yan、Chunrong Chen、Jiuzhou Zhao、Min Zhang、Yongzhou Xu 等（共 6 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | CAS |
| **发布时间** | 2026-08-13T11:49:02Z |
| **关键词** | `Evaluation` · `Simulation` |
| **原文链接** | [http://arxiv.org/abs/2608.13120v1](http://arxiv.org/abs/2608.13120v1) |

**📝 摘要概括：**

> 今天，座席技能要么是手写的，要么是在单个LLM生成通行证中产生的，因此没有闭环，可以通过它们从实际导致的交互失败中改进。最近的工作确实关闭了这个循环，但其反馈来自单轮问答评估。在六个类别的云服务、9个生产技能和98个技能参考文件中， SkillEvo超越了自我反思……

</details>

## 🗄️ 历史归档

| 日期 | 论文数 | 报告链接 |
|------|--------|----------|
| 2026-08-14 | 20 篇 | [2026-08-14.md](daily/2026-08-14.md) |
| 2026-08-13 | 19 篇 | [2026-08-13.md](daily/2026-08-13.md) |
| 2026-08-12 | 13 篇 | [2026-08-12.md](daily/2026-08-12.md) |
| 2026-08-11 | 0 篇 | [2026-08-11.md](daily/2026-08-11.md) |
| 2026-08-10 | 0 篇 | [2026-08-10.md](daily/2026-08-10.md) |
| 2026-08-09 | 0 篇 | [2026-08-09.md](daily/2026-08-09.md) |
| 2026-08-08 | 0 篇 | [2026-08-08.md](daily/2026-08-08.md) |
| 2026-08-07 | 20 篇 | [2026-08-07.md](daily/2026-08-07.md) |
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

## 🏛️ 顶级机构覆盖范围

覆盖超过 **70 个**顶级 AI 机构，包括：

- **科技公司：** Microsoft、Google DeepMind、OpenAI、Anthropic、Meta AI、NVIDIA、Baidu、Alibaba、ByteDance 等
- **北美顶级大学：** MIT、Stanford、CMU、UC Berkeley、Harvard、Princeton、Cornell、Caltech 等
- **中国顶级大学/机构：** 清华大学、北京大学、浙大、上交大、复旦、中科院、MSRA 等
- **欧洲/其他：** Oxford、Cambridge、ETH Zurich、Mila、NUS、KAIST 等

---

*由 [clawBot DailyFindings](https://github.com/Jacob-biu/clawBot) 自动维护 | 最后更新：2026-08-14 22:21 UTC*
