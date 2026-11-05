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

## 📅 今日论文 — 2026-11-05　　[→ 查看完整报告](daily/2026-11-05.md)

> 共筛选出 **13** 篇论文 | 更新于 2026-11-05 02:01 UTC

### 论文目录与概要

| # | 论文标题 | 核心概要 | 来源机构 | 第一作者 |
|---|---------|---------|---------|--------|
| 1 | [Adversarial Speculative Reasoning Improves Long Horizon Agen…](http://arxiv.org/abs/2611.05345v1) | 推测解码被纯粹视为在不改变模型行为的情况下加速大型语言模型解码的系统优化。在这种观点下，越来越多的培训更好的草稿模型的努力只集中在接受率上。我们的结果将推测解码机制从纯粹的加速器重构为活动分配器，以实… | CAS、TRI | Hongyin Luo |
| 2 | [PyRUA-DataFarm: LLM Agent as a Cost-Efficient Teleoperator f…](http://arxiv.org/abs/2611.05320v1) | 远程操作仍然是收集机器人演示的默认方式，但每集都要花费机器人和操作员的时间，每项新任务都要从头开始。我们询问编码代理是否可以接管远程操作员的工作。一小时的任务三视图数据平均成本为\ $ 107 ，这些… | TRI | Kewei Zhang |
| 3 | [HARP: Training-Free Dual-Profile Agentic Communication for L…](http://arxiv.org/abs/2611.05319v1) | 在基于LLM的建议中，内存充当内存增强主干中的用户级代理。然而，用户和项目仍然是不对称的：只有用户才会获得结构化的配置文件；它会进入带宽受限的重新排名提示；并且在预热后会被冻结。优惠码可在https:… | MIT、HIT | Zhen Tao |
| 4 | [Stabilizing On-Policy Targeted Guidance in Agentic Reinforce…](http://arxiv.org/abs/2611.05266v1) | 朴素的随策略强化学习常常受到基本模型功能的瓶颈--覆盖范围不足可能导致无法从某些奖励中学习。同时，现代训练后系统中的奖励通常来自丰富的文本来源，例如，我们进一步研究了在整个训练过程中导致稳定熵和减少振… | MIT | Kevin Frans |
| 5 | [OperAItor: An Agentic Framework for Fault-Tolerant Operation…](http://arxiv.org/abs/2611.05179v1) | OperAItor ，一个用于开发和评估大型语言模型代理的开源框架，用于监督化学过程中的故障管理。该框架是在代表异丙醇脱氢的动态反应器-蒸馏过程中演示的，具有基于物理的热力学和修改的反应动力学，以允许… | MIT、HIT | Javal Vyas |
| 6 | [AgentAM: An AI Agent for Spatter- and Defect-Aware Process O…](http://arxiv.org/abs/2611.05171v1) | 激光粉末床融合（ LPBF ）的预测模型很少在车间使用，因为查询它们需要编程和特定于模型的知识。我们介绍AgentAM ，这是一种大型语言模型(LLM)代理，它通过模型上下文协议(MCP)为过程工程师… | TRI | Olabode T. Ajenifujah |
| 7 | [Distributed Linear Bandits for Freshness-Aware Preprocessing…](http://arxiv.org/abs/2611.05115v1) | 数字孪生（ DT ）需要物联网（ IoT ）设备及时更新，以准确表示相应物理系统的状态，但传输大量数据可能会影响新鲜度。此外，不同的任务类具有不同的计算需求和新鲜度要求，而随机任务生成和大小使资源分配… | MIT、TRI | Mariam Yahya |
| 8 | [From AutoResearch to Continual AutoResearch: Do Agents Learn…](http://arxiv.org/abs/2611.05108v1) | Autresearch已经证明，智能体可以自主编写代码、运行实验并迭代改进机器学习解决方案。然而，大多数评估会针对每个新问题从头开始一个新的客服代表会话，这使得评估成本高昂，并且不清楚客服代表在适应新… | CAS | Jeremy Qin |
| 9 | [LatentTriad: Pre-Action Risk Representations for Malicious A…](http://arxiv.org/abs/2611.05088v1) | 大型语言模型代理越来越多地使用可重用技能进行扩展，但不受信任的技能内容可能会导致用户任务之外的操作。检测这种上下文风险需要的不仅仅是可疑模式匹配，而动态分析需要技能执行的成本。这些结果将行动前风险可读… | TRI | Zhe Yu |
| 10 | [Do Agentic Policies Need to Look at Every Step? Geometric Ab…](http://arxiv.org/abs/2611.05058v1) | 最近的多模态语言模型可以直接对机器人场景进行推理，但目前尚不清楚它们是否需要在交互的每一步重复重新诠释原始视觉观察。我们建议通过三维几何抽象将常规空间推理从图像转移到文本和符号，该抽象从观察中本地刷新… | TRI | Yihang Liu |
| 11 | [DRAP: Dynamics-Risk Adaptive Plasticity for Continual Learni…](http://arxiv.org/abs/2611.05029v1) | 物理AI中的持续学习不同于传统的持续学习，因为小的每步策略错误可以在一个轨迹上累积。每个偏差都可能使座席超出训练分布，增加后续预测误差，最终导致闭环任务失败。与标准的AdamW微调和EWC相比，结果显… | TRI | Oswaldo Ludwig |
| 12 | [GeoFaham: Domain-Specialized Multi-Agent Geospatial Analytic…](http://arxiv.org/abs/2611.04977v1) | 真实世界的地理空间决策支持需要的不仅仅是一步检索或代码生成。灾害响应问题通常涉及多源工作流程，这些工作流程结合了空间数据库、地图衍生特征、卫星图像、光栅产品和可重复使用的地理空间工件，其中正确性取决于… | Microsoft、TRI | Muhammad Sohail Danish |
| 13 | [Artifact-to-Capability: Diagnosing Breaks in Capability Form…](http://arxiv.org/abs/2611.04952v1) | 自我进化代理将交互体验写入工件，并在后续任务中重复使用。大多数工作通过三个代理信号支持此类方法：工件累积、加载后行为变化和指标上升。这些反例表明，基于信号的评估无法确定能力是否已经形成。 | TRI | Ziqian Ban |

### 论文详情

<details>
<summary><b>1. Adversarial Speculative Reasoning Improves Long Horizon Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Hongyin Luo、Wei Fang、Lijie Yang、Owen Stepan、Daniel Suit 等（共 8 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | CAS、TRI |
| **发布时间** | 2026-11-03T18:45:23Z |
| **关键词** | `Agentic` · `Reasoning` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2611.05345v1](http://arxiv.org/abs/2611.05345v1) |

**📝 摘要概括：**

> 推测解码被纯粹视为在不改变模型行为的情况下加速大型语言模型解码的系统优化。在这种观点下，越来越多的培训更好的草稿模型的努力只集中在接受率上。我们的结果将推测解码机制从纯粹的加速器重构为活动分配器，以实现上下文精度，通过训练0来提高长视野代理的准确性……

</details>

<details>
<summary><b>2. PyRUA-DataFarm: LLM Agent as a Cost-Efficient Teleoperator for Real-Ready Robot Data</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Kewei Zhang、Juncheng Ma、Guodong Lv、Duomin Wang、Feixiang Ruan 等（共 14 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-11-03T18:25:14Z |
| **关键词** | `LLM Agent` · `RAG` · `Simulation` |
| **原文链接** | [http://arxiv.org/abs/2611.05320v1](http://arxiv.org/abs/2611.05320v1) |

**📝 摘要概括：**

> 远程操作仍然是收集机器人演示的默认方式，但每集都要花费机器人和操作员的时间，每项新任务都要从头开始。我们询问编码代理是否可以接管远程操作员的工作。一小时的任务三视图数据平均成本为\ $ 107 ，这些成本包括，略低于中国远程操作报价\ $ 117 ，低于北美劳动力报价\ $ 290。

</details>

<details>
<summary><b>3. HARP: Training-Free Dual-Profile Agentic Communication for LLM-Based Recommendation</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Zhen Tao、Xun Zhou、Xuhui Chen、Ziyue Qiao、Qingqiang Sun |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、HIT、CAS |
| **发布时间** | 2026-11-03T18:24:20Z |
| **关键词** | `Agentic` · `Retrieval` · `Benchmark` · `Memory` |
| **原文链接** | [http://arxiv.org/abs/2611.05319v1](http://arxiv.org/abs/2611.05319v1) |

**📝 摘要概括：**

> 在基于LLM的建议中，内存充当内存增强主干中的用户级代理。然而，用户和项目仍然是不对称的：只有用户才会获得结构化的配置文件；它会进入带宽受限的重新排名提示；并且在预热后会被冻结。优惠码可在https://github.com/Jove-Zhen/HARP上获得。

</details>

<details>
<summary><b>4. Stabilizing On-Policy Targeted Guidance in Agentic Reinforcement Learning</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Kevin Frans、Alexander M Rush、Sergey Levine、Pieter Abbeel、Ashvin Nair |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT |
| **发布时间** | 2026-11-03T17:54:33Z |
| **关键词** | `Agentic` · `Reinforcement Learning` · `RAG` |
| **原文链接** | [http://arxiv.org/abs/2611.05266v1](http://arxiv.org/abs/2611.05266v1) |

**📝 摘要概括：**

> 朴素的随策略强化学习常常受到基本模型功能的瓶颈--覆盖范围不足可能导致无法从某些奖励中学习。同时，现代训练后系统中的奖励通常来自丰富的文本来源，例如，我们进一步研究了在整个训练过程中导致稳定熵和减少振荡行为的设计选择。

</details>

<details>
<summary><b>5. OperAItor: An Agentic Framework for Fault-Tolerant Operation of Chemical Processes</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Javal Vyas、Mehmet Mercang{ö}z |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、HIT、TRI |
| **发布时间** | 2026-11-03T16:40:46Z |
| **关键词** | `Agentic` · `Planning` · `Retrieval` · `Benchmark` · `Simulation` |
| **原文链接** | [http://arxiv.org/abs/2611.05179v1](http://arxiv.org/abs/2611.05179v1) |

**📝 摘要概括：**

> OperAItor ，一个用于开发和评估大型语言模型代理的开源框架，用于监督化学过程中的故障管理。该框架是在代表异丙醇脱氢的动态反应器-蒸馏过程中演示的，具有基于物理的热力学和修改的反应动力学，以允许液相运行。该研究为比较代理架构提供了一个可重复的基准…

</details>

<details>
<summary><b>6. AgentAM: An AI Agent for Spatter- and Defect-Aware Process Optimization in Laser Powder Bed Fusion</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Olabode T. Ajenifujah、Amir Barati Farimani |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-11-03T16:38:46Z |
| **关键词** | `AI Agent` · `Benchmark` · `Simulation` |
| **原文链接** | [http://arxiv.org/abs/2611.05171v1](http://arxiv.org/abs/2611.05171v1) |

**📝 摘要概括：**

> 激光粉末床融合（ LPBF ）的预测模型很少在车间使用，因为查询它们需要编程和特定于模型的知识。我们介绍AgentAM ，这是一种大型语言模型(LLM)代理，它通过模型上下文协议(MCP)为过程工程师提供自然语言访问CFD训练的SS316L飞溅和熔池几何代理。在主要基准的725次运行中，代理通过了预期的……

</details>

<details>
<summary><b>7. Distributed Linear Bandits for Freshness-Aware Preprocessing in MEC-Enabled Digital Twin Networks</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Mariam Yahya、Setareh Maghsudi |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-11-03T16:05:22Z |
| **关键词** | — |
| **原文链接** | [http://arxiv.org/abs/2611.05115v1](http://arxiv.org/abs/2611.05115v1) |

**📝 摘要概括：**

> 数字孪生（ DT ）需要物联网（ IoT ）设备及时更新，以准确表示相应物理系统的状态，但传输大量数据可能会影响新鲜度。此外，不同的任务类具有不同的计算需求和新鲜度要求，而随机任务生成和大小使资源分配复杂化。协作产生的识别加速几乎成比例……

</details>

<details>
<summary><b>8. From AutoResearch to Continual AutoResearch: Do Agents Learn Across Tasks?</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Jeremy Qin、Ruizhi Deng、Mohamed Osama Ahmed、Frederick Tung、Leo Feng |
| **所属机构** | （详见原文） |
| **顶级机构标签** | CAS |
| **发布时间** | 2026-11-03T16:02:34Z |
| **关键词** | `Evaluation` · `Memory` |
| **原文链接** | [http://arxiv.org/abs/2611.05108v1](http://arxiv.org/abs/2611.05108v1) |

**📝 摘要概括：**

> Autresearch已经证明，智能体可以自主编写代码、运行实验并迭代改进机器学习解决方案。然而，大多数评估会针对每个新问题从头开始一个新的客服代表会话，这使得评估成本高昂，并且不清楚客服代表在适应新任务时是否可以保留和应用之前的见解。总体而言，我们的研究结果表明，保留经验并有效利用经验是独特的能力。

</details>

<details>
<summary><b>9. LatentTriad: Pre-Action Risk Representations for Malicious Agent Skill Detection</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Zhe Yu、Yi Liu、Ying Zhang、Simin Chen |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-11-03T15:46:12Z |
| **关键词** | `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2611.05088v1](http://arxiv.org/abs/2611.05088v1) |

**📝 摘要概括：**

> 大型语言模型代理越来越多地使用可重用技能进行扩展，但不受信任的技能内容可能会导致用户任务之外的操作。检测这种上下文风险需要的不仅仅是可疑模式匹配，而动态分析需要技能执行的成本。这些结果将行动前风险可读性和功能影响与免执行技能筛选联系起来。

</details>

<details>
<summary><b>10. Do Agentic Policies Need to Look at Every Step? Geometric Abstraction for Reasoning and Action</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Yihang Liu、Yiming Chen、Mingzhe Zheng |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-11-03T15:22:46Z |
| **关键词** | `Agentic` · `Reasoning` |
| **原文链接** | [http://arxiv.org/abs/2611.05058v1](http://arxiv.org/abs/2611.05058v1) |

**📝 摘要概括：**

> 最近的多模态语言模型可以直接对机器人场景进行推理，但目前尚不清楚它们是否需要在交互的每一步重复重新诠释原始视觉观察。我们建议通过三维几何抽象将常规空间推理从图像转移到文本和符号，该抽象从观察中本地刷新并由语言模型直接读取。跨离线策略合成和连续在线执行……

</details>

<details>
<summary><b>11. DRAP: Dynamics-Risk Adaptive Plasticity for Continual Learning in Physical AI</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Oswaldo Ludwig |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-11-03T15:05:06Z |
| **关键词** | `Fine-tuning` · `Memory` |
| **原文链接** | [http://arxiv.org/abs/2611.05029v1](http://arxiv.org/abs/2611.05029v1) |

**📝 摘要概括：**

> 物理AI中的持续学习不同于传统的持续学习，因为小的每步策略错误可以在一个轨迹上累积。每个偏差都可能使座席超出训练分布，增加后续预测误差，最终导致闭环任务失败。与标准的AdamW微调和EWC相比，结果显示，在保留……的同时，大大提高了先前学习行为的保留率。

</details>

<details>
<summary><b>12. GeoFaham: Domain-Specialized Multi-Agent Geospatial Analytics for Disaster Response</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Muhammad Sohail Danish、Gilles Q. Hacheme、Akram Zaytar、Satej S. Soman、Inbal Becker-Reshef 等（共 8 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | Microsoft、TRI |
| **发布时间** | 2026-11-03T14:32:03Z |
| **关键词** | `Multi-Agent` · `Reasoning` · `Planning` · `Retrieval` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2611.04977v1](http://arxiv.org/abs/2611.04977v1) |

**📝 摘要概括：**

> 真实世界的地理空间决策支持需要的不仅仅是一步检索或代码生成。灾害响应问题通常涉及多源工作流程，这些工作流程结合了空间数据库、地图衍生特征、卫星图像、光栅产品和可重复使用的地理空间工件，其中正确性取决于保留空间范围、时间上下文和中间执行状态。我们的代码和基准测试可在http…上公开获得。

</details>

<details>
<summary><b>13. Artifact-to-Capability: Diagnosing Breaks in Capability Formation of Self-Evolving Agents in a Controlled Environment</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Ziqian Ban、Haoxiang Yang、Yanfei Zhang、Shixin Liang、Haoran Yu 等（共 9 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-11-03T14:12:22Z |
| **关键词** | `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2611.04952v1](http://arxiv.org/abs/2611.04952v1) |

**📝 摘要概括：**

> 自我进化代理将交互体验写入工件，并在后续任务中重复使用。大多数工作通过三个代理信号支持此类方法：工件累积、加载后行为变化和指标上升。这些反例表明，基于信号的评估无法确定能力是否已经形成。

</details>

## 🗄️ 历史归档

| 日期 | 论文数 | 报告链接 |
|------|--------|----------|
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
| 2026-10-11 | 0 篇 | [2026-10-11.md](daily/2026-10-11.md) |
| 2026-10-10 | 20 篇 | [2026-10-10.md](daily/2026-10-10.md) |
| 2026-10-09 | 20 篇 | [2026-10-09.md](daily/2026-10-09.md) |
| 2026-10-08 | 20 篇 | [2026-10-08.md](daily/2026-10-08.md) |
| 2026-10-07 | 20 篇 | [2026-10-07.md](daily/2026-10-07.md) |
| 2026-10-06 | 0 篇 | [2026-10-06.md](daily/2026-10-06.md) |
| 2026-10-05 | 0 篇 | [2026-10-05.md](daily/2026-10-05.md) |

## 🏛️ 顶级机构覆盖范围

覆盖超过 **70 个**顶级 AI 机构，包括：

- **科技公司：** Microsoft、Google DeepMind、OpenAI、Anthropic、Meta AI、NVIDIA、Baidu、Alibaba、ByteDance 等
- **北美顶级大学：** MIT、Stanford、CMU、UC Berkeley、Harvard、Princeton、Cornell、Caltech 等
- **中国顶级大学/机构：** 清华大学、北京大学、浙大、上交大、复旦、中科院、MSRA 等
- **欧洲/其他：** Oxford、Cambridge、ETH Zurich、Mila、NUS、KAIST 等

---

*由 [clawBot DailyFindings](https://github.com/Jacob-biu/clawBot) 自动维护 | 最后更新：2026-11-05 02:01 UTC*
