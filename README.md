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

## 📅 今日论文 — 2026-05-14　　[→ 查看完整报告](daily/2026-05-14.md)

> 共筛选出 **19** 篇论文 | 更新于 2026-05-14 22:57 UTC

### 论文目录与概要

| # | 论文标题 | 核心概要 | 来源机构 | 第一作者 |
|---|---------|---------|---------|--------|
| 1 | [EVA-Bench: A New End-to-end Framework for Evaluating Voice A…](http://arxiv.org/abs/2605.13841v1) | 语音代理是进行口头对话以完成任务的人工智能系统，越来越多地部署在企业应用程序中。然而，没有现有的基准共同解决两个核心评估挑战：生成逼真的模拟对话，以及测量整个语音特定故障模式的质量。我们在开源下发布完… | HIT、TRI | Tara Bogavelli |
| 2 | [History Anchors: How Prior Behavior Steers LLM Decisions Tow…](http://arxiv.org/abs/2605.13825v1) | Frontier LLM越来越多地被部署为在相同或不同模型生成的先前工具调用长日志后选择下一个操作的代理。我们问一个简单的安全问题：如果该日志中的先前步骤是有害的，模型是否会继续有害的过程？这些结果对… | TRI | Alberto G. Rodríguez Salgado |
| 3 | [Harnessing Agentic Evolution](http://arxiv.org/abs/2605.13821v1) | 通过迭代生成候选人、评估候选人并使用反馈来指导未来的搜索，代理进化已成为改进计划、工作流程和科学解决方案的强大范例。然而，现有的方法通常被实例化为固定的手工设计过程，这些过程是模块化的，但却是刚性的，… | MIT | Jiayi Zhang |
| 4 | [Learning POMDP World Models from Observations with Language-…](http://arxiv.org/abs/2605.13740v1) | 无论是在建筑物中导航、操作机器人还是玩游戏，在环境中有效行动的代理都必须首先学习该环境如何工作的内部模型。部分可观测马尔可夫决策过程（ POMDP ）为这种内部世界模型提供了一个灵活的建模类，但仅从观… | TRI | Valentin Six |
| 5 | [Senses Wide Shut: A Representation-Action Gap in Omnimodal L…](http://arxiv.org/abs/2605.13737v1) | 当一个全方位大型语言模型接受一个文本前提与它实际看到或听到的内容相矛盾的问题时，失败在于感知还是行动？最近的全模式模型被定位为以感知为基础的代理，共同处理视频、音频和文本，但接地的基本形式仍未经测试：… | TRI | Trung Nguyen Quang |
| 6 | [ScioMind: Cognitively Grounded Multi-Agent Social Simulation…](http://arxiv.org/abs/2605.13725v1) | 基于大型语言模型（ LLM ）的多智能体模拟为研究社会舆论动态提供了一个强大的测试平台。然而，目前的方法通常采用两种截然不同的方法：要么依赖于有限认知基础的固定更新规则，要么将信念变化主要委托给不受约… | MIT、HIT | Yitian Yang |
| 7 | [Identifying AI Web Scrapers Using Canary Tokens](http://arxiv.org/abs/2605.13706v1) | 从预训练到查询时间增强，网络抓取数据有助于提高大型语言模型（ LLM ）生成的内容的质量和上下文相关性。但是，为LLM提供大规模的网络抓取可能会影响网站的稳定性，并引发法律、隐私或道德问题。我们的方法… | MIT、TRI | Steven Seiden |
| 8 | [Causality-Aware End-to-End Autonomous Driving via Ego-Centri…](http://arxiv.org/abs/2605.13646v1) | 通过从传感器输入直接预测未来轨迹来绕过传统模块化管道的端到端自动驾驶最近取得了重大进展。然而，现有的方法往往忽略了自我车辆规划中的因果相互依赖性，忽略了自我车辆与周围主体之间的互惠关系。在Bench2… | MIT、TRI | Seokha Moon |
| 9 | [OpenAaaS: An Open Agent-as-a-Service Framework for Distribut…](http://arxiv.org/abs/2605.13618v1) | Materials Genome Initiative催化了集中式平台（ SaaS、PaaS和IaaS ）的激增，这些平台聚集了计算和实验资源，以加速材料发现。与此同时，大型语言模型（ LLM ）和自… | HIT、CAS | Peng Kang |
| 10 | [Unweighted ranking for value-based decision making with unce…](http://arxiv.org/abs/2605.13601v1) | 随着智能系统在我们的社会中越来越多地实现自主决策，它们对人类价值观的承诺引起了严重的关注。它们与人类价值观的一致性仍然是一个严峻挑战，因为它可能危及公民的完整性和安全性。所进行的评估表明，在大规模基于… | MIT、CAS | Aarón López García |
| 11 | [Position: Assistive Agents Need Accessibility Alignment](http://arxiv.org/abs/2605.13579v1) | 针对盲人和视障者（ BVI ）用户的辅助座席需要将无障碍对齐作为一流的设计目标。尽管代理人工智能进展迅速，但大多数系统都是在视觉交互、低成本验证和可容忍的试验和错误的假设下设计和评估的，导致辅助场景中… | TRI | Jie Hu |
| 12 | [Scaling Retrieval-Augmented Reasoning with Parallel Search a…](http://arxiv.org/abs/2605.13534v1) | 事实证明，深度搜索代理通过在多步推理过程中检索外部知识，有效地增强了LLM。然而，现有方法通常在每个推理步骤生成单个查询进行检索，从而限制了信息覆盖并引入高噪声。七个基准的广泛实验表明， MultiS… | MIT、TRI | Jiabei Liu |
| 13 | [Limits of Personalizing Differential Privacy Budgets](http://arxiv.org/abs/2605.13503v1) | 差异隐私的一个关键技术难题是选择满足隐私要求的隐私预算，同时最大限度地提高效用。一个自然且经过深入研究的解决方法是使用个性化的隐私预算，这可能因客服代表而异。我们还为任意隐私要求建立上限并确定最大增益… | MIT | Edwige Cyffers |
| 14 | [Cognifold: Always-On Proactive Memory via Cognitive Folding](http://arxiv.org/abs/2605.13438v1) | 现有的代理记忆仍然主要是被动和基于检索的，缺乏将经验自主组织成持久认知结构的能力。为了实现真正的自主代理，我们推出了Cognifold ，这是一种大脑启发的“始终在线”代理内存，专为下一代主动助理而设… | Mila、TRI | Suli Wang |
| 15 | [TRIAGE: Evaluating Prospective Metacognitive Control in LLMs…](http://arxiv.org/abs/2605.13414v1) | 将语言模型部署为自主代理需要的不仅仅是每个任务的准确性：当代理在有限的令牌预算下面临一系列问题时，它必须决定尝试哪一个，以何种顺序，以及对每个问题提交多少计算，所有这些都在任何执行反馈可用之前。这是几… | MIT、TRI | Zabir Al Nazi |
| 16 | [RS-Claw: Progressive Active Tool Exploration via Hierarchica…](http://arxiv.org/abs/2605.13391v1) | 多模态大型语言模型（ MLLM ）的兴起正在将遥感（ RS ）智能从“看到”转变为“行动” ，因为OpenClaw风格的框架使代理能够自主操作用于复杂任务的大规模RS图像处理工具。现有的RS代理采用被… | MIT、HIT | Liangtian Liu |
| 17 | [AI Harness Engineering: A Runtime Substrate for Foundation-M…](http://arxiv.org/abs/2605.13357v1) | 基础模型已经改变了自动化代码生成，但在现实的开发环境中，自主软件工程代理仍然不可靠。占主导地位的解释定位了模型能力的这种差距。我们概述了基础模型软件代理所需的运行时系统的研究计划。 | TRI | Hailin Zhong |
| 18 | [Contextual Bandits for Resource-Constrained Devices using Pr…](http://arxiv.org/abs/2605.13346v1) | 情境强盗（ CB ）是部分反馈下的在线顺序决策问题，是许多自适应服务的基础。在严格的内存、计算和能源限制下，直接在设备上部署CB代理的需求不断增长。使用Open Bandit Pipeline对标准化… | TRI | Marco Angioli |
| 19 | [Multi-Agent Systems in Emergency Departments: Validation Stu…](http://arxiv.org/abs/2605.13345v1) | 急诊科（ ED ）在患者护理和资源管理方面面临挑战。我们建议在现实和灵活的模型中探索优化策略，并开发一种模拟高度可配置ED环境的混合离散事件模拟（ DES ）和基于代理的模型（ ABM ）。这个模块化… | TRI | Markus Wenzel |

### 论文详情

<details>
<summary><b>1. EVA-Bench: A New End-to-end Framework for Evaluating Voice Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Tara Bogavelli、Gabrielle Gauthier Melançon、Katrina Stankiewicz、Oluwanifemi Bamgbose、Fanny Riols 等（共 13 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | HIT、TRI |
| **发布时间** | 2026-05-13T17:58:52Z |
| **关键词** | `Benchmark` · `Evaluation` · `Simulation` |
| **原文链接** | [http://arxiv.org/abs/2605.13841v1](http://arxiv.org/abs/2605.13841v1) |

**📝 摘要概括：**

> 语音代理是进行口头对话以完成任务的人工智能系统，越来越多地部署在企业应用程序中。然而，没有现有的基准共同解决两个核心评估挑战：生成逼真的模拟对话，以及测量整个语音特定故障模式的质量。我们在开源下发布完整的框架、评估套件和基准数据……

</details>

<details>
<summary><b>2. History Anchors: How Prior Behavior Steers LLM Decisions Toward Unsafe Actions</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Alberto G. Rodríguez Salgado |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-05-13T17:50:27Z |
| **关键词** | `Agentic` |
| **原文链接** | [http://arxiv.org/abs/2605.13825v1](http://arxiv.org/abs/2605.13825v1) |

**📝 摘要概括：**

> Frontier LLM越来越多地被部署为在相同或不同模型生成的先前工具调用长日志后选择下一个操作的代理。我们问一个简单的安全问题：如果该日志中的先前步骤是有害的，模型是否会继续有害的过程？这些结果对于可能重放、伪造或注入轨迹的代理部署来说是一个危险信号。

</details>

<details>
<summary><b>3. Harnessing Agentic Evolution</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Jiayi Zhang、Yongfeng Gu、Jianhao Ruan、Maojia Song、Yiran Peng 等（共 13 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT |
| **发布时间** | 2026-05-13T17:45:16Z |
| **关键词** | `Agentic` · `Reasoning` · `Benchmark` · `Evaluation` · `Workflow` |
| **原文链接** | [http://arxiv.org/abs/2605.13821v1](http://arxiv.org/abs/2605.13821v1) |

**📝 摘要概括：**

> 通过迭代生成候选人、评估候选人并使用反馈来指导未来的搜索，代理进化已成为改进计划、工作流程和科学解决方案的强大范例。然而，现有的方法通常被实例化为固定的手工设计过程，这些过程是模块化的，但却是刚性的，或者是灵活地集成反馈的通用代理，但可以在长时间的演进中漂移。跨越三个……

</details>

<details>
<summary><b>4. Learning POMDP World Models from Observations with Language-Model Priors</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Valentin Six、Frederik Panse、Mathis Fajeau、Lancelot Da Costa、Mridul Sharma 等（共 10 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-05-13T16:18:15Z |
| **关键词** | `RAG` |
| **原文链接** | [http://arxiv.org/abs/2605.13740v1](http://arxiv.org/abs/2605.13740v1) |

**📝 摘要概括：**

> 无论是在建筑物中导航、操作机器人还是玩游戏，在环境中有效行动的代理都必须首先学习该环境如何工作的内部模型。部分可观测马尔可夫决策过程（ POMDP ）为这种内部世界模型提供了一个灵活的建模类，但仅从观测-行动轨迹中学习它们具有挑战性，通常需要广泛的环境交互。代码是av…

</details>

<details>
<summary><b>5. Senses Wide Shut: A Representation-Action Gap in Omnimodal LLMs</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Trung Nguyen Quang、Yiming Gao、Fanyi Pu、Kaichen Zhang、Shuo Sun 等（共 6 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-05-13T16:14:44Z |
| **关键词** | `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2605.13737v1](http://arxiv.org/abs/2605.13737v1) |

**📝 摘要概括：**

> 当一个全方位大型语言模型接受一个文本前提与它实际看到或听到的内容相矛盾的问题时，失败在于感知还是行动？最近的全模式模型被定位为以感知为基础的代理，共同处理视频、音频和文本，但接地的基本形式仍未经测试：捕捉与模型自身感官输入冲突的文本声明。总之，这些结果表明机器人……

</details>

<details>
<summary><b>6. ScioMind: Cognitively Grounded Multi-Agent Social Simulation with Anchoring-Based Belief Dynamics and Dynamic Profiles</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Yitian Yang、Yiqun Duan、Linghan Huang、Yiqi Zhu、Francesco Bailo 等（共 7 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、HIT、CAS |
| **发布时间** | 2026-05-13T16:07:00Z |
| **关键词** | `Multi-Agent` · `Reasoning` · `Retrieval` · `Simulation` · `Memory` |
| **原文链接** | [http://arxiv.org/abs/2605.13725v1](http://arxiv.org/abs/2605.13725v1) |

**📝 摘要概括：**

> 基于大型语言模型（ LLM ）的多智能体模拟为研究社会舆论动态提供了一个强大的测试平台。然而，目前的方法通常采用两种截然不同的方法：要么依赖于有限认知基础的固定更新规则，要么将信念变化主要委托给不受约束的LLM互动。这些结果表明，我们以认知为基础的设计为基于LLM的社交模拟提供了一种新颖的解决方案，可以改善……

</details>

<details>
<summary><b>7. Identifying AI Web Scrapers Using Canary Tokens</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Steven Seiden、Triss Ren、Caroline Zhang、Taein Kim、Enze Liu 等（共 6 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-05-13T15:53:57Z |
| **关键词** | — |
| **原文链接** | [http://arxiv.org/abs/2605.13706v1](http://arxiv.org/abs/2605.13706v1) |

**📝 摘要概括：**

> 从预训练到查询时间增强，网络抓取数据有助于提高大型语言模型（ LLM ）生成的内容的质量和上下文相关性。但是，为LLM提供大规模的网络抓取可能会影响网站的稳定性，并引发法律、隐私或道德问题。我们的方法为无特权的第三方提供了一个有前途的途径来推断哪些爬虫服务于LLM的数据，从而可能更好地控制……

</details>

<details>
<summary><b>8. Causality-Aware End-to-End Autonomous Driving via Ego-Centric Joint Scene Modeling</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Seokha Moon、Minseung Lee、Joon Seo、Jinkyu Kim、Jungbeom Lee |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-05-13T15:06:22Z |
| **关键词** | `Planning` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2605.13646v1](http://arxiv.org/abs/2605.13646v1) |

**📝 摘要概括：**

> 通过从传感器输入直接预测未来轨迹来绕过传统模块化管道的端到端自动驾驶最近取得了重大进展。然而，现有的方法往往忽略了自我车辆规划中的因果相互依赖性，忽略了自我车辆与周围主体之间的互惠关系。在Bench2Drive和NAVSIM基准测试中， CaAD展示了强大的闭环规划能力。

</details>

<details>
<summary><b>9. OpenAaaS: An Open Agent-as-a-Service Framework for Distributed Materials-Informatics Research</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Peng Kang、Bixuan Li、Xiaoya Huang、Shuo Shi、Weiqiao Zhou 等（共 8 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | HIT、CAS、TRI |
| **发布时间** | 2026-05-13T14:47:01Z |
| **关键词** | `Multi-Agent` · `Reasoning` · `RAG` · `Workflow` |
| **原文链接** | [http://arxiv.org/abs/2605.13618v1](http://arxiv.org/abs/2605.13618v1) |

**📝 摘要概括：**

> Materials Genome Initiative催化了集中式平台（ SaaS、PaaS和IaaS ）的激增，这些平台聚集了计算和实验资源，以加速材料发现。与此同时，大型语言模型（ LLM ）和自主代理的突破为科学研究创造了强大的新推理能力。所有源代码均可在https://github.com/Wolido/OpenAaaS上获得。

</details>

<details>
<summary><b>10. Unweighted ranking for value-based decision making with uncertainty</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Aarón López García、Natalia Criado、Jose Such |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、CAS |
| **发布时间** | 2026-05-13T14:36:17Z |
| **关键词** | `Reasoning` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2605.13601v1](http://arxiv.org/abs/2605.13601v1) |

**📝 摘要概括：**

> 随着智能系统在我们的社会中越来越多地实现自主决策，它们对人类价值观的承诺引起了严重的关注。它们与人类价值观的一致性仍然是一个严峻挑战，因为它可能危及公民的完整性和安全性。所进行的评估表明，在大规模基于价值的决策问题中，计算成本降低，并且对于现有的…

</details>

<details>
<summary><b>11. Position: Assistive Agents Need Accessibility Alignment</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Jie Hu、Changyuan Yan、Yu Zheng、Ziqian Wang、Jiaming Zhang |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-05-13T14:13:53Z |
| **关键词** | `Agentic` |
| **原文链接** | [http://arxiv.org/abs/2605.13579v1](http://arxiv.org/abs/2605.13579v1) |

**📝 摘要概括：**

> 针对盲人和视障者（ BVI ）用户的辅助座席需要将无障碍对齐作为一流的设计目标。尽管代理人工智能进展迅速，但大多数系统都是在视觉交互、低成本验证和可容忍的试验和错误的假设下设计和评估的，导致辅助场景中的系统性故障，这些故障无法通过模型缩放或事后界面自适应来解决。我们得出结论…

</details>

<details>
<summary><b>12. Scaling Retrieval-Augmented Reasoning with Parallel Search and Explicit Merging</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Jiabei Liu、Wenyu Mao、Junfei Tan、Chunxu Shen、Lingling Yi 等（共 7 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-05-13T13:46:35Z |
| **关键词** | `Reasoning` · `Reinforcement Learning` · `RAG` · `Retrieval` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2605.13534v1](http://arxiv.org/abs/2605.13534v1) |

**📝 摘要概括：**

> 事实证明，深度搜索代理通过在多步推理过程中检索外部知识，有效地增强了LLM。然而，现有方法通常在每个推理步骤生成单个查询进行检索，从而限制了信息覆盖并引入高噪声。七个基准的广泛实验表明， MultiSearch优于基线方法，提高了检索的信噪比，并提高了推理性能。

</details>

<details>
<summary><b>13. Limits of Personalizing Differential Privacy Budgets</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Edwige Cyffers、Juba Ziani |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT |
| **发布时间** | 2026-05-13T13:24:50Z |
| **关键词** | — |
| **原文链接** | [http://arxiv.org/abs/2605.13503v1](http://arxiv.org/abs/2605.13503v1) |

**📝 摘要概括：**

> 差异隐私的一个关键技术难题是选择满足隐私要求的隐私预算，同时最大限度地提高效用。一个自然且经过深入研究的解决方法是使用个性化的隐私预算，这可能因客服代表而异。我们还为任意隐私要求建立上限并确定最大增益制度。

</details>

<details>
<summary><b>14. Cognifold: Always-On Proactive Memory via Cognitive Folding</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Suli Wang、Yiqun Duan、Yu Deng、Rundong Zhao、Dai Shi 等（共 6 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | Mila、TRI |
| **发布时间** | 2026-05-13T12:34:39Z |
| **关键词** | `RAG` · `Retrieval` · `Benchmark` · `Memory` |
| **原文链接** | [http://arxiv.org/abs/2605.13438v1](http://arxiv.org/abs/2605.13438v1) |

**📝 摘要概括：**

> 现有的代理记忆仍然主要是被动和基于检索的，缺乏将经验自主组织成持久认知结构的能力。为了实现真正的自主代理，我们推出了Cognifold ，这是一种大脑启发的“始终在线”代理内存，专为下一代主动助理而设计。此外，在跨越五个认知领域的7个广泛覆盖的基准中，我们同时验证了CogniFold……

</details>

<details>
<summary><b>15. TRIAGE: Evaluating Prospective Metacognitive Control in LLMs under Resource Constraints</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Zabir Al Nazi、Shubhashis Roy Dipta |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-05-13T12:10:05Z |
| **关键词** | `Reasoning` · `Evaluation` · `Code Generation` |
| **原文链接** | [http://arxiv.org/abs/2605.13414v1](http://arxiv.org/abs/2605.13414v1) |

**📝 摘要概括：**

> 将语言模型部署为自主代理需要的不仅仅是每个任务的准确性：当代理在有限的令牌预算下面临一系列问题时，它必须决定尝试哪一个，以何种顺序，以及对每个问题提交多少计算，所有这些都在任何执行反馈可用之前。这是几十年来在人类认知中研究的元认知控制的前瞻性形式，但语言模型是否具有它仍未经测试。我们评估…

</details>

<details>
<summary><b>16. RS-Claw: Progressive Active Tool Exploration via Hierarchical Skill Trees for Remote Sensing Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Liangtian Liu、Zeyuan Wang、Ziyu Li、Kai Ouyang、Zichao Tang 等（共 11 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、HIT、TRI |
| **发布时间** | 2026-05-13T11:49:18Z |
| **关键词** | `Reasoning` · `RAG` · `Retrieval` · `Benchmark` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2605.13391v1](http://arxiv.org/abs/2605.13391v1) |

**📝 摘要概括：**

> 多模态大型语言模型（ MLLM ）的兴起正在将遥感（ RS ）智能从“看到”转变为“行动” ，因为OpenClaw风格的框架使代理能够自主操作用于复杂任务的大规模RS图像处理工具。现有的RS代理采用被动选择范式进行工具调用，依赖于完整工具注册（ Flat ）或检索增强生成（ RAG ）。在地台b上的系统实验……

</details>

<details>
<summary><b>17. AI Harness Engineering: A Runtime Substrate for Foundation-Model Software Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Hailin Zhong、Shengxin Zhu |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-05-13T11:14:59Z |
| **关键词** | `Evaluation` · `Code Generation` · `Memory` |
| **原文链接** | [http://arxiv.org/abs/2605.13357v1](http://arxiv.org/abs/2605.13357v1) |

**📝 摘要概括：**

> 基础模型已经改变了自动化代码生成，但在现实的开发环境中，自主软件工程代理仍然不可靠。占主导地位的解释定位了模型能力的这种差距。我们概述了基础模型软件代理所需的运行时系统的研究计划。

</details>

<details>
<summary><b>18. Contextual Bandits for Resource-Constrained Devices using Probabilistic Learning</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Marco Angioli、Kevin Johansson、Antonello Rosato、Amy Loutfi、Denis Kleyko |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-05-13T11:04:47Z |
| **关键词** | `Benchmark` · `Evaluation` · `Memory` |
| **原文链接** | [http://arxiv.org/abs/2605.13346v1](http://arxiv.org/abs/2605.13346v1) |

**📝 摘要概括：**

> 情境强盗（ CB ）是部分反馈下的在线顺序决策问题，是许多自适应服务的基础。在严格的内存、计算和能源限制下，直接在设备上部署CB代理的需求不断增长。使用Open Bandit Pipeline对标准化合成CB基准进行的违规评估表明，概率HD-CB在相同的精度下始终优于二值化HD-CB ，而概率HD-CB在相同的精度下始终优于二值化HD-CB。

</details>

<details>
<summary><b>19. Multi-Agent Systems in Emergency Departments: Validation Study on a ED Digital Twin</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Markus Wenzel、Tobias Strapatsas、Jessika Kress、Dorothea Sauer、Nele Gessler 等（共 6 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-05-13T11:04:23Z |
| **关键词** | `Multi-Agent` · `Simulation` |
| **原文链接** | [http://arxiv.org/abs/2605.13345v1](http://arxiv.org/abs/2605.13345v1) |

**📝 摘要概括：**

> 急诊科（ ED ）在患者护理和资源管理方面面临挑战。我们建议在现实和灵活的模型中探索优化策略，并开发一种模拟高度可配置ED环境的混合离散事件模拟（ DES ）和基于代理的模型（ ABM ）。这个模块化的DES-ABM-MAS框架为探索急诊部门的资源优化策略提供了强大的工具。

</details>

## 🗄️ 历史归档

| 日期 | 论文数 | 报告链接 |
|------|--------|----------|
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

*由 [clawBot DailyFindings](https://github.com/Jacob-biu/clawBot) 自动维护 | 最后更新：2026-05-14 22:57 UTC*
