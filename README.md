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

## 📅 今日论文 — 2026-06-02　　[→ 查看完整报告](daily/2026-06-02.md)

> 共筛选出 **20** 篇论文 | 更新于 2026-06-02 23:45 UTC

### 论文目录与概要

| # | 论文标题 | 核心概要 | 来源机构 | 第一作者 |
|---|---------|---------|---------|--------|
| 1 | [ClinEnv: An Interactive Multi-Stage Long Horizon EHR Environ…](http://arxiv.org/abs/2606.02568v1) | 临床实践不是从列举的选项中选择答案：医生逐渐收集异构信息，并在不确定的情况下做出连续、不可逆转的决定。静态基准无法探测，现有的交互式医疗基准每个都至少在其中一个上妥协。ClinEnv使这种信息获取缺口… | MIT、CAS | Yuxing Lu |
| 2 | [Auditing Asset-Specific Preferences in Financial Large Langu…](http://arxiv.org/abs/2606.02528v1) | 大型语言模型现在为机器人顾问和交易代理提供动力，但它们是否对特定资产具有内置偏见在很大程度上未经测试。我们提出三个问题：法学硕士是否系统地偏好某些金融工具；是否能够识别出对这些偏好具有因果杠杆作用的内… | MIT、TRI | Wenbin Wu |
| 3 | [Bridging the Last Mile of Time Series Forecasting with LLM A…](http://arxiv.org/abs/2606.02497v1) | 时间序列预测进展迅速，特别是随着基础模型的出现，在数值外推上显示出强大的零点性能。然而，在现实世界的预测环境中，统计上合理的基线很少是实践中使用的最终预测。通过实际案例研究，我们展示了LLM代理如何弥… | CAS、TRI | Yuhua Liao |
| 4 | [Monitoring Agentic Systems Before They're Reliable](http://arxiv.org/abs/2606.02494v1) | 进入生产的代理系统通常作为部分集成的组件运行，其中结构缺陷而非任务级错误主导了故障环境。在此成熟度级别，任务级错误检测可能不可行：结构故障模式掩盖了任务级监视器设计用于检测的信号。我们提出了一种监控和… | HIT、TRI | Marisa Ferrara Boston |
| 5 | [Iteris: Agentic Research Loops for Computational Mathematics](http://arxiv.org/abs/2606.02484v1) | 大型语言模型和智能人工智能系统的最新进展使数学发现取得了重大进展，从解决竞争问题到解决研究层面的猜想。然而，计算数学中的开放性问题受到的关注相对较少：该领域的研究通常不仅需要证明，还需要数值实验、对抗… | CAS、TRI | Leheng Chen |
| 6 | [Ghost Tool Calls: Issue-Time Privacy for Speculative Agent T…](http://arxiv.org/abs/2606.02483v1) | 工具增强的语言代理推测未来可能会发出隐藏延迟的工具调用，但这些调用在代理提交到分支之前泄露了用户对外部服务的意图。在代理放弃分支后，收到呼叫的每个外部观察者都会保留披露。推测性调度增加了观察者对用户意… | MIT、TRI | Bardia Mohammadi |
| 7 | [MCP-Persona: Benchmarking LLM Agents on Real-World Personal …](http://arxiv.org/abs/2606.02470v1) | 模型上下文协议（ MCP ）已成为连接大型语言模型（ LLM ）与外部数据源和工具的变革性标准，并已迅速被个人应用程序和开发平台采用。然而，现有的基准主要集中在通用信息搜索工具上，未能捕捉到个人社交应… | MIT | Wenhao Wang |
| 8 | [MASER: Modality-Adaptive Specialist Routing for Embodied 3D …](http://arxiv.org/abs/2606.02463v1) | 在3D环境中， Embodied Agents通过多种形式（包括自然语言、RGB图像、点云、深度图和相机姿势）的推理来回答空间相关的问题。现有的视觉语言模型（ VLM ）通过单一模式进行了微调。MAS… | CAS | Hilton Raj |
| 9 | [AGENTCL: Toward Rigorous Evaluation of Continual Learning in…](http://arxiv.org/abs/2606.02461v1) | 语言代理花费大量时间来解决单个任务，但在未来的情节中，在一个情节中获得的经验往往未得到充分利用。持续学习希望客服代表在一系列任务中积累可重复使用的经验，随着时间的推移而改进，并避免来自无关经验的干扰。… | MIT、TRI | Yiheng Shu |
| 10 | [ODTQA-FoRe: An Open-Domain Tabular Question Answering Datase…](http://arxiv.org/abs/2606.02433v1) | LLM的快速发展极大地促进了表格式问答，但大多数系统无法执行面向未来的数值预测。为了弥补这一差距，我们引入了一项新任务，即未来数据预测和推理的开放域表格问题答案，并提出了第一个数据集，涵盖使用房地产数… | MIT、CAS | Zhensheng Wang |
| 11 | [AgentPLM: Agentic Protein Language Models with Reasoning-Aug…](http://arxiv.org/abs/2606.02386v1) | 蛋白质语言模型（ PLM ）是被动的预言机：它们在单个正向传递中生成序列，当候选者违反热力学或结构约束时，没有机制来咨询外部生物物理反馈或重定向生成。我们介绍了AgentPLM ，它通过为预先训练的P… | MIT、HIT | Sahil Rahman |
| 12 | [Harness-1: Reinforcement Learning for Search Agents with Sta…](http://arxiv.org/abs/2606.02373v1) | 搜索代理通常作为生长成绩单的政策进行培训：模型必须决定如何搜索，同时还要记住它所看到的内容，哪些证据是有用的，哪些约束仍然存在，以及哪些声明实际上已经过检查。我们认为，这种提法在政策中放置了太多的常规… | TRI | Pengcheng Jiang |
| 13 | [COMAP: Co-Evolving World Models and Agent Policies for LLM A…](http://arxiv.org/abs/2606.02372v1) | 为语言代理配备世界模型，使他们能够在执行之前预测环境动态并评估候选人的行为。然而，现有的文本世界模型通常在训练后是固定的，防止它们适应由演化主体引起的政策上状态行为分布。我们的代码可在以下网址获得： … | MIT、TRI | Youwei Liu |
| 14 | [MOC: Multi-Order Communication in LLM-based Multi-Agent Syst…](http://arxiv.org/abs/2606.02359v1) | 尽管基于大语言模型（ LLM ）的多Agent系统取得了显着进展，但大多数研究都集中在优化协调拓扑，同时在很大程度上未充分探索同样关键的问题：如何有效地在Agent之间传输和优化消息？当前的通信方案通… | MIT、TRI | Yao Guan |
| 15 | [Do Multimodal Agents Really Benefit from Tool Use? A Systema…](http://arxiv.org/abs/2606.02357v1) | 工具增强的多式联运客服代表显示出强劲的基准收益，通常被视为客服代表已学会使用工具的证据。我们认为这种解释可能为时过早：工具调用跟踪本身并不能显示工具是否提供了关键答案信息。在我们研究的环境中，被分析的… | TRI | Garvin Guo |
| 16 | [SIRI: Self-Internalizing Reinforcement Learning with Intrins…](http://arxiv.org/abs/2606.02355v1) | 长期LLM代理可以从可重用技能中受益，但现有的基于技能的方法通常在培训期间依赖于外部技能生成器，或在推理时进行持续的技能检索，从而增加了工程复杂性、上下文长度和部署延迟。我们建议使用内在技能（ SIR… | TRI | Zhongyu He |
| 17 | [SeClaw: Spec-Driven Security Task Synthesis for Evaluating A…](http://arxiv.org/abs/2606.02302v1) | 自主LLM代理越来越多地在有状态的环境中运行，在那里他们可以访问工具、文件、内存和外部服务。虽然这些功能能够实现复杂的实际工作流程，但它们也会引入现有评估难以捕捉的安全风险。该代码可在https://… | MIT、TRI | Hao Cheng |
| 18 | [POIROT: Interrogating Agents for Failure Detection in Multi-…](http://arxiv.org/abs/2606.02282v1) | 将大型语言模型编排到多智能体系统（ LLM-MAS ）中已经释放了非凡的推理能力，但出现的失败和幻觉阻碍了它们在安全关键领域的部署--这一差距因新兴的人工智能监管而在法律上站不住脚。现有的评估范式有一… | HIT、TRI | Iñaki Dellibarda Varela |
| 19 | [AgentRedBench: Dynamic Redteaming and Integration-Aware Defe…](http://arxiv.org/abs/2606.02240v1) | 间接提示注入工具使用代理是一个具体的生产威胁： LLM代理读取集成（通过工具调用访问的第三方服务，如Gmail、Salesforce或Jira ） ，其响应内容用户既不编写也不控制。现有的基准不足以衡… | Google、OpenAI | Hiskias Dingeto |
| 20 | [Learning When Not to Act: Mitigating Tool Abuse in Agentic R…](http://arxiv.org/abs/2606.02132v1) | 代理强化学习可能导致工具滥用，其中模型过度使用外部工具，即使对于可通过内部推理解决的查询也是如此。现有的方法通过统一的工具使用处罚或硬性限制来缓解这一问题，这降低了工具频率，但也可能抑制有用的工具辅助… | MIT | Liuji Chen |

### 论文详情

<details>
<summary><b>1. ClinEnv: An Interactive Multi-Stage Long Horizon EHR Environment for Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Yuxing Lu、Yushuhong Lin、Wenqi Shi、J. Ben Tamo、Xukai Zhao 等（共 7 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、CAS |
| **发布时间** | 2026-06-01T17:56:26Z |
| **关键词** | `Benchmark` · `Evaluation` · `Simulation` |
| **原文链接** | [http://arxiv.org/abs/2606.02568v1](http://arxiv.org/abs/2606.02568v1) |

**📝 摘要概括：**

> 临床实践不是从列举的选项中选择答案：医生逐渐收集异构信息，并在不确定的情况下做出连续、不可逆转的决定。静态基准无法探测，现有的交互式医疗基准每个都至少在其中一个上妥协。ClinEnv使这种信息获取缺口成为可直接测量的，这种缺口对仅限结果的评估是不可见的。

</details>

<details>
<summary><b>2. Auditing Asset-Specific Preferences in Financial Large Language Models: Evidence from Bitcoin Representations and Portfolio Allocation</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Wenbin Wu |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-06-01T17:36:06Z |
| **关键词** | `RAG` |
| **原文链接** | [http://arxiv.org/abs/2606.02528v1](http://arxiv.org/abs/2606.02528v1) |

**📝 摘要概括：**

> 大型语言模型现在为机器人顾问和交易代理提供动力，但它们是否对特定资产具有内置偏见在很大程度上未经测试。我们提出三个问题：法学硕士是否系统地偏好某些金融工具；是否能够识别出对这些偏好具有因果杠杆作用的内部表征；这种表征是否会影响下游的财务决策？随着LLM成为自主的金融代理商，这是第一次……

</details>

<details>
<summary><b>3. Bridging the Last Mile of Time Series Forecasting with LLM Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Yuhua Liao、Zetian Wang、Qiangqiang Nie、Zhenhua Zhang |
| **所属机构** | （详见原文） |
| **顶级机构标签** | CAS、TRI |
| **发布时间** | 2026-06-01T17:03:40Z |
| **关键词** | `LLM Agent` · `Reasoning` · `Memory` |
| **原文链接** | [http://arxiv.org/abs/2606.02497v1](http://arxiv.org/abs/2606.02497v1) |

**📝 摘要概括：**

> 时间序列预测进展迅速，特别是随着基础模型的出现，在数值外推上显示出强大的零点性能。然而，在现实世界的预测环境中，统计上合理的基线很少是实践中使用的最终预测。通过实际案例研究，我们展示了LLM代理如何弥合统计预测和业务就绪预测之间的差距。

</details>

<details>
<summary><b>4. Monitoring Agentic Systems Before They're Reliable</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Marisa Ferrara Boston、Glen Hanson、Effi Georgala、JD Hudgens、Heather Frase |
| **所属机构** | （详见原文） |
| **顶级机构标签** | HIT、TRI |
| **发布时间** | 2026-06-01T17:01:53Z |
| **关键词** | `Agentic` · `Evaluation` · `Workflow` |
| **原文链接** | [http://arxiv.org/abs/2606.02494v1](http://arxiv.org/abs/2606.02494v1) |

**📝 摘要概括：**

> 进入生产的代理系统通常作为部分集成的组件运行，其中结构缺陷而非任务级错误主导了故障环境。在此成熟度级别，任务级错误检测可能不可行：结构故障模式掩盖了任务级监视器设计用于检测的信号。我们提出了一种监控和分类方法，将代理系统评估分解为三个维度（质量， …

</details>

<details>
<summary><b>5. Iteris: Agentic Research Loops for Computational Mathematics</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Leheng Chen、Zihao Liu、Wanyi He、Bin Dong |
| **所属机构** | （详见原文） |
| **顶级机构标签** | CAS、TRI |
| **发布时间** | 2026-06-01T16:54:31Z |
| **关键词** | `Agentic` · `Workflow` |
| **原文链接** | [http://arxiv.org/abs/2606.02484v1](http://arxiv.org/abs/2606.02484v1) |

**📝 摘要概括：**

> 大型语言模型和智能人工智能系统的最新进展使数学发现取得了重大进展，从解决竞争问题到解决研究层面的猜想。然而，计算数学中的开放性问题受到的关注相对较少：该领域的研究通常不仅需要证明，还需要数值实验、对抗构造和算法设计。这些案例研究……

</details>

<details>
<summary><b>6. Ghost Tool Calls: Issue-Time Privacy for Speculative Agent Tools</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Bardia Mohammadi、Lars Klein、Akhil Arora、Laurent Bindschaedler |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-06-01T16:53:19Z |
| **关键词** | — |
| **原文链接** | [http://arxiv.org/abs/2606.02483v1](http://arxiv.org/abs/2606.02483v1) |

**📝 摘要概括：**

> 工具增强的语言代理推测未来可能会发出隐藏延迟的工具调用，但这些调用在代理提交到分支之前泄露了用户对外部服务的意图。在代理放弃分支后，收到呼叫的每个外部观察者都会保留披露。推测性调度增加了观察者对用户意图的推断；事后过滤器、只读限制和访问控制允许……

</details>

<details>
<summary><b>7. MCP-Persona: Benchmarking LLM Agents on Real-World Personal Applications via Environment Simulation</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Wenhao Wang、Peizhi Niu、Gongyi Zou、Xiyuan Yang、Jingxing Wang 等（共 12 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT |
| **发布时间** | 2026-06-01T16:44:10Z |
| **关键词** | `LLM Agent` · `Benchmark` · `Simulation` |
| **原文链接** | [http://arxiv.org/abs/2606.02470v1](http://arxiv.org/abs/2606.02470v1) |

**📝 摘要概括：**

> 模型上下文协议（ MCP ）已成为连接大型语言模型（ LLM ）与外部数据源和工具的变革性标准，并已迅速被个人应用程序和开发平台采用。然而，现有的基准主要集中在通用信息搜索工具上，未能捕捉到个人社交应用程序带来的实际挑战，在这些应用程序中，工具与个人数据交互。

</details>

<details>
<summary><b>8. MASER: Modality-Adaptive Specialist Routing for Embodied 3D Spatial Intelligence</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Hilton Raj、Vishnuram AV |
| **所属机构** | （详见原文） |
| **顶级机构标签** | CAS |
| **发布时间** | 2026-06-01T16:36:21Z |
| **关键词** | `Reasoning` · `Benchmark` · `Evaluation` · `Embodied AI` |
| **原文链接** | [http://arxiv.org/abs/2606.02463v1](http://arxiv.org/abs/2606.02463v1) |

**📝 摘要概括：**

> 在3D环境中， Embodied Agents通过多种形式（包括自然语言、RGB图像、点云、深度图和相机姿势）的推理来回答空间相关的问题。现有的视觉语言模型（ VLM ）通过单一模式进行了微调。MASER路由具有51.3%的甲骨文协议，优于随机森林消融（ 43.5% ） ，每个问题只有一个适配器调用。

</details>

<details>
<summary><b>9. AGENTCL: Toward Rigorous Evaluation of Continual Learning in Language Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Yiheng Shu、Bernal Jiménez Gutiérrez、Saisri Padmaja Jonnalagedda、Yuguang Yao、Huan Sun 等（共 6 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-06-01T16:32:59Z |
| **关键词** | `Reasoning` · `Retrieval` · `Benchmark` · `Evaluation` · `Memory` |
| **原文链接** | [http://arxiv.org/abs/2606.02461v1](http://arxiv.org/abs/2606.02461v1) |

**📝 摘要概括：**

> 语言代理花费大量时间来解决单个任务，但在未来的情节中，在一个情节中获得的经验往往未得到充分利用。持续学习希望客服代表在一系列任务中积累可重复使用的经验，随着时间的推移而改进，并避免来自无关经验的干扰。这些结果突出表明，需要更强大的内存设计，以平衡可塑性和稳定的重复使用。

</details>

<details>
<summary><b>10. ODTQA-FoRe: An Open-Domain Tabular Question Answering Dataset for Future Data Forecasting and Reasoning</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Zhensheng Wang、Xiaole Liu、Wenmian Yang、Kun Zhou、Yiquan Zhang 等（共 6 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、CAS、TRI |
| **发布时间** | 2026-06-01T16:06:20Z |
| **关键词** | `LLM Agent` · `Reasoning` |
| **原文链接** | [http://arxiv.org/abs/2606.02433v1](http://arxiv.org/abs/2606.02433v1) |

**📝 摘要概括：**

> LLM的快速发展极大地促进了表格式问答，但大多数系统无法执行面向未来的数值预测。为了弥补这一差距，我们引入了一项新任务，即未来数据预测和推理的开放域表格问题答案，并提出了第一个数据集，涵盖使用房地产数据的时间序列预测和基于预测的推理场景。大量的实验表明，

</details>

<details>
<summary><b>11. AgentPLM: Agentic Protein Language Models with Reasoning-Augmented Decoding for Protein Sequence Design</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Sahil Rahman、Maxx Richard Rahman |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、HIT |
| **发布时间** | 2026-06-01T15:35:02Z |
| **关键词** | `Agentic` · `Reasoning` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2606.02386v1](http://arxiv.org/abs/2606.02386v1) |

**📝 摘要概括：**

> 蛋白质语言模型（ PLM ）是被动的预言机：它们在单个正向传递中生成序列，当候选者违反热力学或结构约束时，没有机制来咨询外部生物物理反馈或重定向生成。我们介绍了AgentPLM ，它通过为预先训练的PLM配备i ）推理增强解码（ RAD ）来解决这个问题，该RAD将自回归生成与工具调用（ ESMFold、FoldX、Auto……

</details>

<details>
<summary><b>12. Harness-1: Reinforcement Learning for Search Agents with State-Externalizing Harnesses</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Pengcheng Jiang、Zhiyi Shi、Kelly Hong、Xueqiang Xu、Jiashuo Sun 等（共 8 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-06-01T15:21:41Z |
| **关键词** | `Reinforcement Learning` · `RAG` · `Retrieval` · `Benchmark` · `Memory` |
| **原文链接** | [http://arxiv.org/abs/2606.02373v1](http://arxiv.org/abs/2606.02373v1) |

**📝 摘要概括：**

> 搜索代理通常作为生长成绩单的政策进行培训：模型必须决定如何搜索，同时还要记住它所看到的内容，哪些证据是有用的，哪些约束仍然存在，以及哪些声明实际上已经过检查。我们认为，这种提法在政策中放置了太多的常规状态管理：强化学习被迫优化语义搜索决策和可恢复簿记……

</details>

<details>
<summary><b>13. COMAP: Co-Evolving World Models and Agent Policies for LLM Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Youwei Liu、Jian Wang、Hanlin Wang、Wenjie Li |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-06-01T15:21:17Z |
| **关键词** | `LLM Agent` · `Planning` · `Benchmark` · `Embodied AI` |
| **原文链接** | [http://arxiv.org/abs/2606.02372v1](http://arxiv.org/abs/2606.02372v1) |

**📝 摘要概括：**

> 为语言代理配备世界模型，使他们能够在执行之前预测环境动态并评估候选人的行为。然而，现有的文本世界模型通常在训练后是固定的，防止它们适应由演化主体引起的政策上状态行为分布。我们的代码可在以下网址获得： https://github.com/loyiv/CoMAP。

</details>

<details>
<summary><b>14. MOC: Multi-Order Communication in LLM-based Multi-Agent Systems</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Yao Guan、Lin Wang、Zhihu Lu、Ziyi Wang、Wenzhu Yan 等（共 6 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-06-01T15:06:38Z |
| **关键词** | `Multi-Agent` |
| **原文链接** | [http://arxiv.org/abs/2606.02359v1](http://arxiv.org/abs/2606.02359v1) |

**📝 摘要概括：**

> 尽管基于大语言模型（ LLM ）的多Agent系统取得了显着进展，但大多数研究都集中在优化协调拓扑，同时在很大程度上未充分探索同样关键的问题：如何有效地在Agent之间传输和优化消息？当前的通信方案通常依赖于一阶邻居响应的直接串联，这导致了受限的证据接受场，并导致了…

</details>

<details>
<summary><b>15. Do Multimodal Agents Really Benefit from Tool Use? A Systematic Study of Capability Gains</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Garvin Guo、Donglei Yu、Yu Chen、Xiang Wang、Shuai Li 等（共 9 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-06-01T15:04:25Z |
| **关键词** | `Reasoning` · `Benchmark` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2606.02357v1](http://arxiv.org/abs/2606.02357v1) |

**📝 摘要概括：**

> 工具增强的多式联运客服代表显示出强劲的基准收益，通常被视为客服代表已学会使用工具的证据。我们认为这种解释可能为时过早：工具调用跟踪本身并不能显示工具是否提供了关键答案信息。在我们研究的环境中，被分析的代理似乎比工具提供的能力更可靠地学习工具调用模式，这表明评估应该区分……

</details>

<details>
<summary><b>16. SIRI: Self-Internalizing Reinforcement Learning with Intrinsic Skills for LLM Agent Training</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Zhongyu He、Yuanfan Li、Fei Huang、Tianyu Chen、Siyuan Chen 等（共 12 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-06-01T15:02:59Z |
| **关键词** | `LLM Agent` · `Reinforcement Learning` · `Retrieval` · `Memory` |
| **原文链接** | [http://arxiv.org/abs/2606.02355v1](http://arxiv.org/abs/2606.02355v1) |

**📝 摘要概括：**

> 长期LLM代理可以从可重用技能中受益，但现有的基于技能的方法通常在培训期间依赖于外部技能生成器，或在推理时进行持续的技能检索，从而增加了工程复杂性、上下文长度和部署延迟。我们建议使用内在技能（ SIRI ）进行自我内化强化学习，这是一个三阶段框架，使代理能够发现、验证和内化技能，而无需扩展……

</details>

<details>
<summary><b>17. SeClaw: Spec-Driven Security Task Synthesis for Evaluating Autonomous Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Hao Cheng、Changtao Miao、Tianle Song、Yin Wu、He Liu 等（共 24 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-06-01T14:23:42Z |
| **关键词** | `LLM Agent` · `RAG` · `Benchmark` · `Evaluation` · `Memory` |
| **原文链接** | [http://arxiv.org/abs/2606.02302v1](http://arxiv.org/abs/2606.02302v1) |

**📝 摘要概括：**

> 自主LLM代理越来越多地在有状态的环境中运行，在那里他们可以访问工具、文件、内存和外部服务。虽然这些功能能够实现复杂的实际工作流程，但它们也会引入现有评估难以捕捉的安全风险。该代码可在https://github.com/seclaw-eval/seclaw-eval上获得。

</details>

<details>
<summary><b>18. POIROT: Interrogating Agents for Failure Detection in Multi-Agent Systems</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Iñaki Dellibarda Varela、R. Sendra-Arranz、Pablo Romero-Sorozabal、J. M. Valverde-García、Annemarie F. Laudanski 等（共 8 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | HIT、TRI |
| **发布时间** | 2026-06-01T14:05:35Z |
| **关键词** | `Multi-Agent` · `Reasoning` · `RAG` · `Benchmark` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2606.02282v1](http://arxiv.org/abs/2606.02282v1) |

**📝 摘要概括：**

> 将大型语言模型编排到多智能体系统（ LLM-MAS ）中已经释放了非凡的推理能力，但出现的失败和幻觉阻碍了它们在安全关键领域的部署--这一差距因新兴的人工智能监管而在法律上站不住脚。现有的评估范式有一个共同的缺陷：集中判断会造成单点故障，需要特定领域的专业知识。我们发布……

</details>

<details>
<summary><b>19. AgentRedBench: Dynamic Redteaming and Integration-Aware Defense for LLM Agents over SaaS Integrations</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Hiskias Dingeto、Will Leeney |
| **所属机构** | （详见原文） |
| **顶级机构标签** | Google、OpenAI、Anthropic |
| **发布时间** | 2026-06-01T13:34:24Z |
| **关键词** | `LLM Agent` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2606.02240v1](http://arxiv.org/abs/2606.02240v1) |

**📝 摘要概括：**

> 间接提示注入工具使用代理是一个具体的生产威胁： LLM代理读取集成（通过工具调用访问的第三方服务，如Gmail、Salesforce或Jira ） ，其响应内容用户既不编写也不控制。现有的基准不足以衡量威胁：大多数仅涵盖少数具有相同攻击有效负载的集成，并且开源防护人员接受了聊天式数据的培训……

</details>

<details>
<summary><b>20. Learning When Not to Act: Mitigating Tool Abuse in Agentic Reinforcement Learning</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Liuji Chen、Dianxing Tang、Xing Shi、Dingshuo Chen、Qiang Liu 等（共 7 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT |
| **发布时间** | 2026-06-01T11:58:55Z |
| **关键词** | `Agentic` · `Reasoning` · `Reinforcement Learning` · `RAG` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2606.02132v1](http://arxiv.org/abs/2606.02132v1) |

**📝 摘要概括：**

> 代理强化学习可能导致工具滥用，其中模型过度使用外部工具，即使对于可通过内部推理解决的查询也是如此。现有的方法通过统一的工具使用处罚或硬性限制来缓解这一问题，这降低了工具频率，但也可能抑制有用的工具辅助探索。这些结果表明，在不影响工具集成推理的情况下，客服代表可以学习何时不使用工具。

</details>

## 🗄️ 历史归档

| 日期 | 论文数 | 报告链接 |
|------|--------|----------|
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

*由 [clawBot DailyFindings](https://github.com/Jacob-biu/clawBot) 自动维护 | 最后更新：2026-06-02 23:45 UTC*
