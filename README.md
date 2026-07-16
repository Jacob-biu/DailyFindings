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

## 📅 今日论文 — 2026-07-16　　[→ 查看完整报告](daily/2026-07-16.md)

> 共筛选出 **11** 篇论文 | 更新于 2026-07-16 22:57 UTC

### 论文目录与概要

| # | 论文标题 | 核心概要 | 来源机构 | 第一作者 |
|---|---------|---------|---------|--------|
| 1 | [AI-accelerated End-to-End Framework for Rapid Professional U…](http://arxiv.org/abs/2607.14044v1) | 到2030年，每100名工人中将有59人需要再培训或提升技能，但缩小企业技能差距的平均时间从2014年的约3天增加到2018年的36天。大多数当前的框架加速了技能提升计划的单一阶段，并且通常缺乏行业验… | NVIDIA | Tam Nguyen |
| 2 | [Early Adoption of Agentic Coding Tools by GitHub Projects](http://arxiv.org/abs/2607.14037v1) | 代理编码工具越来越能够生成并向软件项目提交拉取请求（ PR ） ，从而在软件开发中引入了新的人机协作形式。虽然之前的研究已经检查了代理生成的贡献的PR级结果，但对于代理编码工具如何在项目级采用和管理知… | MIT、TRI | Maliha Noushin Raida |
| 3 | [Rethinking Penetration Testing for AI-Enabled Systems: From …](http://arxiv.org/abs/2607.14006v1) | 渗透测试传统上评估对手是否可以利用软件、基础设施、配置或操作控制中的弱点来实现与安全相关的妥协。对于支持人工智能的系统来说，这种范式仍然是必要的，但它已不再足够。定义、工作流程和示例共同为评估部署的人… | TRI | Mohammad Allahbakhsh |
| 4 | [Lyapunov Exponent as Physics-Informed Dense Reward: RL Disco…](http://arxiv.org/abs/2607.14001v1) | 我们建议使用Lyapunov特征指数（ LCE ）作为垂直运动稳定倒立摆的强化学习问题的密集奖励信号。使用LCE ，代理不仅成功地发现了称为Kapitza摆锤的振荡运动，而且还抑制了摆锤的枢轴转动，使… | TRI | Slava Andrejev |
| 5 | [The Dynamic Verifiable Multi-Agent Human Agentic Loyalty Loo…](http://arxiv.org/abs/2607.13998v1) | 智能体人工智能的快速扩散从根本上颠覆了传统的客户忠诚度范式。随着人工智能从被动推荐算法演变为能够执行购买决策的自主、目标导向型代理，对消费者品牌关系的传统理解需要进行结构性重新评估。此框架提供了品牌在… | TRI | Sai Srikanth Madugula |
| 6 | [TRACE: Turn-level Reward Assignment via Credit Estimation fo…](http://arxiv.org/abs/2607.13988v1) | 在生成最终答案之前，多轮代理通过延长的工具交互序列来解决复杂的任务，使学分分配成为培训后期间的基本挑战。结果奖励为短视推理提供了可靠的监督，但随着轨迹增长到数十或数百个工具调用，结果奖励变得稀疏和高方… | NTU | Leitian Tao |
| 7 | [A Self-Evolving Agent for Longitudinal Personal Health Manag…](http://arxiv.org/abs/2607.13940v1) | 个人健康管理是通过反复接触来展开的，但大多数健康人工智能系统都是孤立地处理每个请求的。我们开发了HealthClaw ，这是一种开源代理架构，可根据个人的日常生活、偏好、测量和风险变化更新支持。Hea… | HIT、CAS | Haoran Li |
| 8 | [Experience Memory Graph: One-Shot Error Correction for Agent…](http://arxiv.org/abs/2607.13884v1) | 大型语言模型（ LLM ）代理通过生成状态、动作和观察的连续轨迹，在自主决策方面表现出非凡的能力。然而，在复杂、长远的任务中，这些代理经常会遇到复杂的错误，并且很难从故障中恢复过来。ALFWorld和… | TRI | Wenjun Wang |
| 9 | [Unleashing Multimodal Large Language Models for Training-fre…](http://arxiv.org/abs/2607.13881v1) | 人物交互检测（ HOID ）传统上被公式化为针对预定义交互类别的监督检测问题。虽然这些范式在封闭集基准上取得了强劲的表现，但它们从根本上将交互理解与特定于数据集的监督纠缠在一起，限制了它们推广到开放世… | MIT | Ting Lei |
| 10 | [Task-Oriented Sensing and Covert Transmissions for Collabora…](http://arxiv.org/abs/2607.13880v1) | 在水下秘密合作任务中，自主水下航行器（ AUV ）通常不能依靠主动声纳持续获取完整信息，因为主动传感和频繁的通信增加了暴露的风险。因此， AUV主要依赖于被动观察，这种方法会产生不完整的局部感知和有限… | MIT、CAS | Xueyao Zhang |
| 11 | [CAVA: Canonical Action Verification and Attestation for Runt…](http://arxiv.org/abs/2607.13716v1) | 代理人工智能系统越来越多地通过异构运行时：本地编码挂钩、SDK工具、浏览器自动化、托管代理跟踪、API网关和工作流引擎。因此，发布代码、更改身份状态、移动资金或导出数据等单个操作行为可能由许多不兼容的… | TRI | Zexun Wang |

### 论文详情

<details>
<summary><b>1. AI-accelerated End-to-End Framework for Rapid Professional Upskilling</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Tam Nguyen、Hung Nguyen、Robert Ogburn |
| **所属机构** | （详见原文） |
| **顶级机构标签** | NVIDIA |
| **发布时间** | 2026-07-15T17:14:03Z |
| **关键词** | `Multi-Agent` · `Agentic` · `RAG` |
| **原文链接** | [http://arxiv.org/abs/2607.14044v1](http://arxiv.org/abs/2607.14044v1) |

**📝 摘要概括：**

> 到2030年，每100名工人中将有59人需要再培训或提升技能，但缩小企业技能差距的平均时间从2014年的约3天增加到2018年的36天。大多数当前的框架加速了技能提升计划的单一阶段，并且通常缺乏行业验证。三个强有力的外部信号验证了这一框架：美国国家会计委员会协会审查并批准了一项技能提升计划。

</details>

<details>
<summary><b>2. Early Adoption of Agentic Coding Tools by GitHub Projects</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Maliha Noushin Raida、Daqing Hou |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-07-15T17:05:06Z |
| **关键词** | `Agentic` · `RAG` |
| **原文链接** | [http://arxiv.org/abs/2607.14037v1](http://arxiv.org/abs/2607.14037v1) |

**📝 摘要概括：**

> 代理编码工具越来越能够生成并向软件项目提交拉取请求（ PR ） ，从而在软件开发中引入了新的人机协作形式。虽然之前的研究已经检查了代理生成的贡献的PR级结果，但对于代理编码工具如何在项目级采用和管理知之甚少。因为这项研究捕捉到了代理采用的早期快照，所以未来的工作应该……

</details>

<details>
<summary><b>3. Rethinking Penetration Testing for AI-Enabled Systems: From Resource Compromise to Behavioral Objective Violation</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Mohammad Allahbakhsh、Mohammad Hassan Bahari、Moslem Attar-Raouf |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-07-15T16:36:54Z |
| **关键词** | `Agentic` · `Retrieval` · `Evaluation` · `Memory` · `Workflow` |
| **原文链接** | [http://arxiv.org/abs/2607.14006v1](http://arxiv.org/abs/2607.14006v1) |

**📝 摘要概括：**

> 渗透测试传统上评估对手是否可以利用软件、基础设施、配置或操作控制中的弱点来实现与安全相关的妥协。对于支持人工智能的系统来说，这种范式仍然是必要的，但它已不再足够。定义、工作流程和示例共同为评估部署的人工智能系统中的对抗性成功提供了技术框架。

</details>

<details>
<summary><b>4. Lyapunov Exponent as Physics-Informed Dense Reward: RL Discovery of Stabilization Beyond the Kapitza Pendulum</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Slava Andrejev |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-07-15T16:29:20Z |
| **关键词** | `Reinforcement Learning` |
| **原文链接** | [http://arxiv.org/abs/2607.14001v1](http://arxiv.org/abs/2607.14001v1) |

**📝 摘要概括：**

> 我们建议使用Lyapunov特征指数（ LCE ）作为垂直运动稳定倒立摆的强化学习问题的密集奖励信号。使用LCE ，代理不仅成功地发现了称为Kapitza摆锤的振荡运动，而且还抑制了摆锤的枢轴转动，使其处于严格直立的位置。

</details>

<details>
<summary><b>5. The Dynamic Verifiable Multi-Agent Human Agentic Loyalty Loop (DVM-HALL) Model and the Net Human-Agent Score (NHAS) in Autonomous Commerce</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Sai Srikanth Madugula、Peplluis Esteva de la Rosa、Daya Shankar |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-07-15T16:27:48Z |
| **关键词** | `Multi-Agent` · `Agentic` · `Benchmark` · `Evaluation` · `Simulation` |
| **原文链接** | [http://arxiv.org/abs/2607.13998v1](http://arxiv.org/abs/2607.13998v1) |

**📝 摘要概括：**

> 智能体人工智能的快速扩散从根本上颠覆了传统的客户忠诚度范式。随着人工智能从被动推荐算法演变为能够执行购买决策的自主、目标导向型代理，对消费者品牌关系的传统理解需要进行结构性重新评估。此框架提供了品牌在即将到来的交易中导航所需的基本理论……

</details>

<details>
<summary><b>6. TRACE: Turn-level Reward Assignment via Credit Estimation for Long-Horizon Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Leitian Tao、Baolin Peng、Wenlin Yao、Tao Ge、Hao Cheng 等（共 8 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | NTU |
| **发布时间** | 2026-07-15T16:16:42Z |
| **关键词** | `Agentic` · `Reasoning` · `Reinforcement Learning` · `Benchmark` · `Fine-tuning` |
| **原文链接** | [http://arxiv.org/abs/2607.13988v1](http://arxiv.org/abs/2607.13988v1) |

**📝 摘要概括：**

> 在生成最终答案之前，多轮代理通过延长的工具交互序列来解决复杂的任务，使学分分配成为培训后期间的基本挑战。结果奖励为短视推理提供了可靠的监督，但随着轨迹增长到数十或数百个工具调用，结果奖励变得稀疏和高方差。学习的搜索行为也会转移到开放网络基准，而学习曲线……

</details>

<details>
<summary><b>7. A Self-Evolving Agent for Longitudinal Personal Health Management</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Haoran Li、Jiebi Deng、Tong Jin、Jinghong Han、Yuxin Wang 等（共 13 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | HIT、CAS、TRI |
| **发布时间** | 2026-07-15T15:22:11Z |
| **关键词** | `Benchmark` · `Evaluation` · `Memory` |
| **原文链接** | [http://arxiv.org/abs/2607.13940v1](http://arxiv.org/abs/2607.13940v1) |

**📝 摘要概括：**

> 个人健康管理是通过反复接触来展开的，但大多数健康人工智能系统都是孤立地处理每个请求的。我们开发了HealthClaw ，这是一种开源代理架构，可根据个人的日常生活、偏好、测量和风险变化更新支持。HealthClaw可在https://github.com/HC-Guo/HealthClaw上公开获得。

</details>

<details>
<summary><b>8. Experience Memory Graph: One-Shot Error Correction for Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Wenjun Wang、Yuchen Fang、Fengrui Liu、Zibo Liang、Kai Zheng |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-07-15T14:33:15Z |
| **关键词** | `RAG` · `Memory` · `Workflow` |
| **原文链接** | [http://arxiv.org/abs/2607.13884v1](http://arxiv.org/abs/2607.13884v1) |

**📝 摘要概括：**

> 大型语言模型（ LLM ）代理通过生成状态、动作和观察的连续轨迹，在自主决策方面表现出非凡的能力。然而，在复杂、长远的任务中，这些代理经常会遇到复杂的错误，并且很难从故障中恢复过来。ALFWorld和ScienceWorld的实验表明， EMG在成功率和平均成功率方面始终优于最先进的反思基线。

</details>

<details>
<summary><b>9. Unleashing Multimodal Large Language Models for Training-free HOI Detection in the Wild</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Ting Lei、Jialin Liu、Zhu Xu、Yuxin Peng、Yang Liu |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT |
| **发布时间** | 2026-07-15T14:30:20Z |
| **关键词** | `Agentic` · `Reasoning` · `RAG` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2607.13881v1](http://arxiv.org/abs/2607.13881v1) |

**📝 摘要概括：**

> 人物交互检测（ HOID ）传统上被公式化为针对预定义交互类别的监督检测问题。虽然这些范式在封闭集基准上取得了强劲的表现，但它们从根本上将交互理解与特定于数据集的监督纠缠在一起，限制了它们推广到开放世界和组合场景的能力。广泛的实验表明， AgentHOI实现了……

</details>

<details>
<summary><b>10. Task-Oriented Sensing and Covert Transmissions for Collaborative Multi-AUV Systems</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Xueyao Zhang、Chenyang Yan、Bo Yang、Xuelin Cao、Zhiwen Yu 等（共 9 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、CAS、TRI |
| **发布时间** | 2026-07-15T14:29:25Z |
| **关键词** | `Multi-Agent` · `Reinforcement Learning` · `RAG` |
| **原文链接** | [http://arxiv.org/abs/2607.13880v1](http://arxiv.org/abs/2607.13880v1) |

**📝 摘要概括：**

> 在水下秘密合作任务中，自主水下航行器（ AUV ）通常不能依靠主动声纳持续获取完整信息，因为主动传感和频繁的通信增加了暴露的风险。因此， AUV主要依赖于被动观察，这种方法会产生不完整的局部感知和有限的任务效率。通过隐蔽的多AUV合作本地化案例研究

</details>

<details>
<summary><b>11. CAVA: Canonical Action Verification and Attestation for Runtime Governance of Agentic AI Systems</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Zexun Wang |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-07-15T11:34:34Z |
| **关键词** | `Agentic` · `Benchmark` · `Workflow` |
| **原文链接** | [http://arxiv.org/abs/2607.13716v1](http://arxiv.org/abs/2607.13716v1) |

**📝 摘要概括：**

> 代理人工智能系统越来越多地通过异构运行时：本地编码挂钩、SDK工具、浏览器自动化、托管代理跟踪、API网关和工作流引擎。因此，发布代码、更改身份状态、移动资金或导出数据等单个操作行为可能由许多不兼容的运行时记录表示。贡献是行动级规范化和策略可寻址的系统制定……

</details>

## 🗄️ 历史归档

| 日期 | 论文数 | 报告链接 |
|------|--------|----------|
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
| 2026-06-27 | 0 篇 | [2026-06-27.md](daily/2026-06-27.md) |
| 2026-06-26 | 17 篇 | [2026-06-26.md](daily/2026-06-26.md) |
| 2026-06-25 | 11 篇 | [2026-06-25.md](daily/2026-06-25.md) |
| 2026-06-24 | 9 篇 | [2026-06-24.md](daily/2026-06-24.md) |
| 2026-06-23 | 15 篇 | [2026-06-23.md](daily/2026-06-23.md) |
| 2026-06-22 | 0 篇 | [2026-06-22.md](daily/2026-06-22.md) |
| 2026-06-21 | 0 篇 | [2026-06-21.md](daily/2026-06-21.md) |
| 2026-06-20 | 0 篇 | [2026-06-20.md](daily/2026-06-20.md) |
| 2026-06-19 | 20 篇 | [2026-06-19.md](daily/2026-06-19.md) |
| 2026-06-18 | 11 篇 | [2026-06-18.md](daily/2026-06-18.md) |
| 2026-06-17 | 18 篇 | [2026-06-17.md](daily/2026-06-17.md) |
| 2026-06-16 | 18 篇 | [2026-06-16.md](daily/2026-06-16.md) |

## 🏛️ 顶级机构覆盖范围

覆盖超过 **70 个**顶级 AI 机构，包括：

- **科技公司：** Microsoft、Google DeepMind、OpenAI、Anthropic、Meta AI、NVIDIA、Baidu、Alibaba、ByteDance 等
- **北美顶级大学：** MIT、Stanford、CMU、UC Berkeley、Harvard、Princeton、Cornell、Caltech 等
- **中国顶级大学/机构：** 清华大学、北京大学、浙大、上交大、复旦、中科院、MSRA 等
- **欧洲/其他：** Oxford、Cambridge、ETH Zurich、Mila、NUS、KAIST 等

---

*由 [clawBot DailyFindings](https://github.com/Jacob-biu/clawBot) 自动维护 | 最后更新：2026-07-16 22:57 UTC*
