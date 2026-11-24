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

## 📅 今日论文 — 2026-11-24　　[→ 查看完整报告](daily/2026-11-24.md)

> 共筛选出 **20** 篇论文 | 更新于 2026-11-24 05:46 UTC

### 论文目录与概要

| # | 论文标题 | 核心概要 | 来源机构 | 第一作者 |
|---|---------|---------|---------|--------|
| 1 | [MMMem: Self-Improving Agents with Task-Aware Multimodal Expe…](http://arxiv.org/abs/2611.30287v1) | AI 代理通过与用户的长期互动来积累对话、图像和文档。回答后续问题通常需要将这些记录中的证据联系起来，但由此产生的理解很少得到保留，导致在相关问题上再次出现错误。消融实验表明，训练和记忆预热可以带来持… | MIT、CAS | Yuxuan Chen |
| 2 | [Attributing Security Outcomes in LLM-Agent Evaluations: The …](http://arxiv.org/abs/2611.30259v1) | LLM 代理的安全基准会记录每次攻击是否成功，并按攻击成功率 (ASR) 对代理、攻击和防御进行比较。只有当代理、攻击和防御导致每个判定结果时，此类比较才有效。我们发布了 TARE、ASB 补丁以及所… | CAS、TRI | Abdelmonaim Bounite |
| 3 | [TriSegAgent: Context-Efficient 3D Annotation with MLLMs via …](http://arxiv.org/abs/2611.30240v1) | 交互式分割模型只需几次点击，即可在多个领域生成分割预测，因此标注人员只需确定哪些地方的预测仍需修正。因此，标注就变成了一个检查预测并再次点击的循环。借助闪存级MLLM，它优于最近基于前沿MLLM构建的… | TRI | Qingqiao Hu |
| 4 | [Composing Independently Distilled Memory and Retrieval Polic…](http://arxiv.org/abs/2611.30230v1) | 长效网络助手需要有效的记忆和检索机制，以便访问过去用户交互中的信息。虽然这些能力可以通过专门的策略来学习，但目前仍不清楚在不同环境中独立训练的专家是否能够在没有联合优化的前提下有效组合。我们发布了教师… | TRI | Grigorii Davydenko |
| 5 | [Adopting AI Technologies without Traps: A Multi-Agent Reinfo…](http://arxiv.org/abs/2611.30200v1) | 人工智能技术和人工智能体在人类社会中发挥着越来越重要的作用，包括在教育、经济和研究领域。采用人工智能技术可以带来立竿见影的收益，有时甚至会带来巨大的收益，例如通过提高生产力，但它们也可能带来负面影响，… | MIT | Jitong Yang |
| 6 | [Trustworthy agentic lunar robotics: safety-constrained conti…](http://arxiv.org/abs/2611.30179v1) | 持续的月球基地运营需要机器人能够在部署前无法预见的条件下修复设备和运送货物。飞行空间自主系统执行预先验证的程序，并在其范围之外进入安全暂停状态，而基础模型则在现场合成无法在执行前进行验证的计划。AKR… | TRI | Bingqi Huang |
| 7 | [Audio-Visual Rearrangement](http://arxiv.org/abs/2611.30171v1) | 我们推出了视听重排（AVR），这是一项新颖的任务，其中智能体听到口头请求，检索合适的物体，然后将其递交给提出请求的用户或指令指定的目的地。AVR 要求智能体理解口头请求，并通过声音定位说话者以便递送物… | TRI | Ruohao Guo |
| 8 | [Reading the Tea Leaves, Again: Can Large Language Models Pre…](http://arxiv.org/abs/2611.30141v1) | LLM 代理现在可以提出研究想法并进行实验来检验这些想法，但它们会将每次运行训练到结束，而研究人员则会查看运行的配置及其曲线的起始部分，并停止那些没有前景的运行。以这种方式阅读运行需要的不只是描述或实… | CAS | Xinran Zhao |
| 9 | [AutoSECO: Automated Skill Evolution for Cross-Problem Combin…](http://arxiv.org/abs/2611.30139v1) | 通用大型语言模型（LLM）代理可以为组合优化问题开发完整的求解器。然而，它们的专业化通常依赖于为个别问题设计的工作流程，这限制了开发专业知识的重复利用。这些发现表明，求解器开发经验可以作为通用 LLM… | MIT | Zirui Zhu |
| 10 | [Post-Training Agents for Long-Document Reasoning](http://arxiv.org/abs/2611.30090v1) | 专业文档是一种长上下文工作负载，检索式基准无法捕捉到。在一个包含十个领域的企业集合中，一项任务的证据分散在平均长度为 27 页（平均 48.8 页，最长 873 页）的源文档中；三分之一的任务主要基于… | TRI | Sushant Mehta |
| 11 | [OWE-Bench: A long-horizon benchmark for measuring real-world…](http://arxiv.org/abs/2611.30017v1) | 我们推出了OWE-Bench（OpenWorldEngineer-Bench），这是一个由软件工程、物理工程、机器学习和科学计算领域的专家撰写的26项长周期工程任务的基准。任务范围包括优化内核、设计飞… | MIT、CAS | Jacob Cole |
| 12 | [Sequential Selection against an Adaptive Opponent](http://arxiv.org/abs/2611.30006v1) | 通过与对手对弈来选择策略，这在博弈型人工智能、语言模型的红队演练以及人工智能代理的安全评估中很常见。在许多此类场景中，对手会根据观察到的情况进行调整，因此，在实践中一直获胜的策略可能在使用时已经失效。… | TRI | Zhongyuan Lyu |
| 13 | [Antiphony: A Dual-Process Agent for Deepfake Video Detection…](http://arxiv.org/abs/2611.29999v1) | 可靠的视频深度伪造检测需要对未见过的生成器进行泛化，同时限制对真实影像的误报。虽然现有的检测器能够捕捉到各种视觉线索，但在生成器发生变化时，它们可能会产生过度自信的错误，从而限制了基于置信度的融合的可… | MIT、TRI | Xinyu Yan |
| 14 | [Conartist: Adaptive Agentic Red-Teaming of Computer-Using Ag…](http://arxiv.org/abs/2611.29977v1) | Harness 通过实施安全约束并防御提示注入攻击，来保护使用计算机的智能体。然而，我们发现代理约束的两种核心安全机制仍然存在漏洞。通过分析最受欢迎的代理之一Openclaw，我们进一步总结出七种现实… | MIT、CAS | Jiaqi Rong |
| 15 | [CARE-3D: Reinforcement Learning for Evidence Grounded Agenti…](http://arxiv.org/abs/2611.29969v1) | 情境化3D推理要求具身智能体解释物体、场景几何和视点相关的空间关系。现有方法从监督轨迹中学习基于现实的交互，但主要是在模仿预先规定的证据获取模式，而不是优化所返回的证据对正确答案的支持。我们的代码可在… | MIT、TRI | Xiaoqian Hu |
| 16 | [LLM-Assisted Software Migration: from Module-Level Transform…](http://arxiv.org/abs/2611.29942v1) | 软件迁移是将现有实现适配到新的语言、版本、API、框架或平台，同时保留其行为。大型语言模型（LLM）在单个函数和模块上取得了成功，但这种成功并不容易扩展到整个代码库，特别是可部署的应用程序。最后，我们… | HIT、Mila | Yanan Zhang |
| 17 | [Autonomous Multireference Quantum Chemistry with Artificial …](http://arxiv.org/abs/2611.29902v1) | 准确描述涉及强关联电子的化学反应仍然是计算化学领域的一大挑战。多重态电子结构方法可以应对这一挑战，但其应用需要专家的决策，而这些决策很难实现自动化，特别是在化学键形成和断裂导致电子结构发生变化时。除了… | CAS、NTU | Younghwan Kim |
| 18 | [MobileGrail: Learning Compact Guardrails for On-Device deplo…](http://arxiv.org/abs/2611.29847v1) | 运行时防护机制通过在执行前评估每个拟议操作来保护移动 GUI 代理，但现有的防护机制依赖于云端托管的大型多模态模型，这会将每个屏幕暴露给远程服务器，包括支付、消息和医疗记录等私人信息。我们提出了 Mo… | MIT | Zhiyu Zhang |
| 19 | [Who Makes the Decision? Auditing an Agentic LLM Pipeline for…](http://arxiv.org/abs/2611.29829v1) | 目前正在提出一种代理管道，它结合了图检测器、确定性规则、检索增强生成和LLM评判器，用于监测非法加密货币流动，并为分析师撰写引用法规的理由。对它们的评估基于端到端准确性或这些理由的质量，但两者都未显示… | CAS、TRI | Vaishnavi Chaughule |
| 20 | [Memphis: A Case Study in Seeding an Agent Task from a Model'…](http://arxiv.org/abs/2611.29824v1) | 通常，通过增加构建任务的数据量，代理基准会变得更加困难，但即使在基准上表现出色的模型，在实际工作中仍然会失败。我们建议根据模型在现实世界中尝试完成开放式任务的情况来构建模拟任务，这样模型的模拟任务失败… | CAS、TRI | Ibrahim A. Ahmed |

### 论文详情

<details>
<summary><b>1. MMMem: Self-Improving Agents with Task-Aware Multimodal Experience Consolidation</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Yuxuan Chen、Changwei Lv、Yunfei Li、Zhongjing Du、Kehui Tan 等（共 12 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、CAS、TRI |
| **发布时间** | 2026-11-23T08:44:23Z |
| **关键词** | `AI Agent` · `Retrieval` · `Benchmark` · `Memory` |
| **原文链接** | [http://arxiv.org/abs/2611.30287v1](http://arxiv.org/abs/2611.30287v1) |

**📝 摘要概括：**

> AI 代理通过与用户的长期互动来积累对话、图像和文档。回答后续问题通常需要将这些记录中的证据联系起来，但由此产生的理解很少得到保留，导致在相关问题上再次出现错误。消融实验表明，训练和记忆预热可以带来持续的收益，而案例研究则展示了各个组件在实践中的运作方式。

</details>

<details>
<summary><b>2. Attributing Security Outcomes in LLM-Agent Evaluations: The Role of Content-Free State</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Abdelmonaim Bounite、Zangir Iklassov |
| **所属机构** | （详见原文） |
| **顶级机构标签** | CAS、TRI |
| **发布时间** | 2026-11-23T08:24:44Z |
| **关键词** | `LLM Agent` · `Benchmark` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2611.30259v1](http://arxiv.org/abs/2611.30259v1) |

**📝 摘要概括：**

> LLM 代理的安全基准会记录每次攻击是否成功，并按攻击成功率 (ASR) 对代理、攻击和防御进行比较。只有当代理、攻击和防御导致每个判定结果时，此类比较才有效。我们发布了 TARE、ASB 补丁以及所有判决表。

</details>

<details>
<summary><b>3. TriSegAgent: Context-Efficient 3D Annotation with MLLMs via Tri-Planes</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Qingqiao Hu、Jialin Li、Meilong Xu、Kehan Qi、Yipeng Zhang 等（共 9 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-11-23T08:06:40Z |
| **关键词** | `LLM Agent` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2611.30240v1](http://arxiv.org/abs/2611.30240v1) |

**📝 摘要概括：**

> 交互式分割模型只需几次点击，即可在多个领域生成分割预测，因此标注人员只需确定哪些地方的预测仍需修正。因此，标注就变成了一个检查预测并再次点击的循环。借助闪存级MLLM，它优于最近基于前沿MLLM构建的3D分割代理。

</details>

<details>
<summary><b>4. Composing Independently Distilled Memory and Retrieval Policies for Long-Term Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Grigorii Davydenko、Artem Sakhno、Igor Pavlov、Julia Belikova、Andrey Savchenko 等（共 6 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-11-23T08:01:29Z |
| **关键词** | `Multi-Agent` · `Retrieval` · `Benchmark` · `Memory` |
| **原文链接** | [http://arxiv.org/abs/2611.30230v1](http://arxiv.org/abs/2611.30230v1) |

**📝 摘要概括：**

> 长效网络助手需要有效的记忆和检索机制，以便访问过去用户交互中的信息。虽然这些能力可以通过专门的策略来学习，但目前仍不清楚在不同环境中独立训练的专家是否能够在没有联合优化的前提下有效组合。我们发布了教师生成的记忆编辑和检索轨迹的源代码和数据集，以方便……

</details>

<details>
<summary><b>5. Adopting AI Technologies without Traps: A Multi-Agent Reinforcement Learning Framework</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Jitong Yang、Avinash Reddy Mudireddy、Ziqing Lu、Huan Cai、Weiyu Xu |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT |
| **发布时间** | 2026-11-23T07:41:07Z |
| **关键词** | `Multi-Agent` · `AI Agent` · `Reinforcement Learning` |
| **原文链接** | [http://arxiv.org/abs/2611.30200v1](http://arxiv.org/abs/2611.30200v1) |

**📝 摘要概括：**

> 人工智能技术和人工智能体在人类社会中发挥着越来越重要的作用，包括在教育、经济和研究领域。采用人工智能技术可以带来立竿见影的收益，有时甚至会带来巨大的收益，例如通过提高生产力，但它们也可能带来负面影响，包括但不限于失去工作和培训机会，以及认知能力下降。由于基于多智能体MDP的RL技术源自……

</details>

<details>
<summary><b>6. Trustworthy agentic lunar robotics: safety-constrained contingent planning with a foundation-model planner</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Bingqi Huang、Bingchuan Wei、Yingkai Cai、Zhaokui Wang |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-11-23T07:24:57Z |
| **关键词** | `Agentic` · `Planning` · `Robotics` |
| **原文链接** | [http://arxiv.org/abs/2611.30179v1](http://arxiv.org/abs/2611.30179v1) |

**📝 摘要概括：**

> 持续的月球基地运营需要机器人能够在部署前无法预见的条件下修复设备和运送货物。飞行空间自主系统执行预先验证的程序，并在其范围之外进入安全暂停状态，而基础模型则在现场合成无法在执行前进行验证的计划。AKR 在任务模型不变的情况下完成了 21 次应急和顺序故障运行中的 20 次；原始的 PLEXIL 和 EUROPA$\…

</details>

<details>
<summary><b>7. Audio-Visual Rearrangement</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Ruohao Guo、Jiatong Ye、Chenwei Dong、Jinxing Zhou、Dantong Niu 等（共 7 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-11-23T07:15:54Z |
| **关键词** | `Embodied AI` |
| **原文链接** | [http://arxiv.org/abs/2611.30171v1](http://arxiv.org/abs/2611.30171v1) |

**📝 摘要概括：**

> 我们推出了视听重排（AVR），这是一项新颖的任务，其中智能体听到口头请求，检索合适的物体，然后将其递交给提出请求的用户或指令指定的目的地。AVR 要求智能体理解口头请求，并通过声音定位说话者以便递送物品。代码即将公开。

</details>

<details>
<summary><b>8. Reading the Tea Leaves, Again: Can Large Language Models Predict Language Model Training Runs?</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Xinran Zhao、Xiang Li、Tong Chen、Jinchuan Tian、Zichun Yu 等（共 6 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | CAS |
| **发布时间** | 2026-11-23T06:47:39Z |
| **关键词** | `LLM Agent` · `Reinforcement Learning` · `Benchmark` · `Fine-tuning` |
| **原文链接** | [http://arxiv.org/abs/2611.30141v1](http://arxiv.org/abs/2611.30141v1) |

**📝 摘要概括：**

> LLM 代理现在可以提出研究想法并进行实验来检验这些想法，但它们会将每次运行训练到结束，而研究人员则会查看运行的配置及其曲线的起始部分，并停止那些没有前景的运行。以这种方式阅读运行需要的不只是描述或实施一种训练方法：还需要了解设计选择对运行有何影响。我们发布了基准、经过训练的阅读器及其训练数据，以供……

</details>

<details>
<summary><b>9. AutoSECO: Automated Skill Evolution for Cross-Problem Combinatorial Optimization with General-Purpose LLM Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Zirui Zhu、Cong Zhang、Ni Zhang、Kuan Xu、Zhiguang Cao |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT |
| **发布时间** | 2026-11-23T06:46:06Z |
| **关键词** | `LLM Agent` · `Benchmark` · `Evaluation` · `Workflow` |
| **原文链接** | [http://arxiv.org/abs/2611.30139v1](http://arxiv.org/abs/2611.30139v1) |

**📝 摘要概括：**

> 通用大型语言模型（LLM）代理可以为组合优化问题开发完整的求解器。然而，它们的专业化通常依赖于为个别问题设计的工作流程，这限制了开发专业知识的重复利用。这些发现表明，求解器开发经验可以作为通用 LLM 代理的可重用专业知识保留下来。

</details>

<details>
<summary><b>10. Post-Training Agents for Long-Document Reasoning</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Sushant Mehta、Logan Ritchie、Edwin Chen |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-11-23T05:51:19Z |
| **关键词** | `Reasoning` · `Reinforcement Learning` · `Retrieval` · `Benchmark` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2611.30090v1](http://arxiv.org/abs/2611.30090v1) |

**📝 摘要概括：**

> 专业文档是一种长上下文工作负载，检索式基准无法捕捉到。在一个包含十个领域的企业集合中，一项任务的证据分散在平均长度为 27 页（平均 48.8 页，最长 873 页）的源文档中；三分之一的任务主要基于图表、图纸和地图；70.9% 的任务需要两次或以上的推理跳跃。我们认为，对智能体的长上下文评估应将准确性与token和回合一起报告，……

</details>

<details>
<summary><b>11. OWE-Bench: A long-horizon benchmark for measuring real-world engineering</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Jacob Cole、Martin Dimakis、Victor Barres、Bertie Vidgen、Edward Hu 等（共 6 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、CAS |
| **发布时间** | 2026-11-23T04:19:40Z |
| **关键词** | `RAG` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2611.30017v1](http://arxiv.org/abs/2611.30017v1) |

**📝 摘要概括：**

> 我们推出了OWE-Bench（OpenWorldEngineer-Bench），这是一个由软件工程、物理工程、机器学习和科学计算领域的专家撰写的26项长周期工程任务的基准。任务范围包括优化内核、设计飞机，以及识别造成地震的断层。我们希望OWE-Bench能够为开发智能体奠定基础，使这些智能体的工程解决方案在部署时的表现与……一样出色。

</details>

<details>
<summary><b>12. Sequential Selection against an Adaptive Opponent</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Zhongyuan Lyu、Xiaocong Xu |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-11-23T04:10:06Z |
| **关键词** | `AI Agent` · `Evaluation` · `Simulation` |
| **原文链接** | [http://arxiv.org/abs/2611.30006v1](http://arxiv.org/abs/2611.30006v1) |

**📝 摘要概括：**

> 通过与对手对弈来选择策略，这在博弈型人工智能、语言模型的红队演练以及人工智能代理的安全评估中很常见。在许多此类场景中，对手会根据观察到的情况进行调整，因此，在实践中一直获胜的策略可能在使用时已经失效。通过模拟和两项使用真实数据的研究（其中一项使用记录的编码-a……）展示了Screen-then-SPAR的性能。

</details>

<details>
<summary><b>13. Antiphony: A Dual-Process Agent for Deepfake Video Detection with Real-Video Calibration</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Xinyu Yan、Yurong Hao、Zherui Li、Yebo Wu、Tiantong Wu 等（共 12 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-11-23T04:03:18Z |
| **关键词** | `RAG` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2611.29999v1](http://arxiv.org/abs/2611.29999v1) |

**📝 摘要概括：**

> 可靠的视频深度伪造检测需要对未见过的生成器进行泛化，同时限制对真实影像的误报。虽然现有的检测器能够捕捉到各种视觉线索，但在生成器发生变化时，它们可能会产生过度自信的错误，从而限制了基于置信度的融合的可靠性。在 FaceVid 的 20 个未见过的生成器上，它还平均比 ARGUS 高出 20.2 个百分点，在平衡准确率上高出 3.6 个百分点。

</details>

<details>
<summary><b>14. Conartist: Adaptive Agentic Red-Teaming of Computer-Using Agents against Multi-Step Prompt Injection</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Jiaqi Rong、Yunchen Lu、Lihai Nie、Yan Jia、Tong Li 等（共 6 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、CAS、TRI |
| **发布时间** | 2026-11-23T03:41:22Z |
| **关键词** | `Agentic` · `Benchmark` · `Workflow` |
| **原文链接** | [http://arxiv.org/abs/2611.29977v1](http://arxiv.org/abs/2611.29977v1) |

**📝 摘要概括：**

> Harness 通过实施安全约束并防御提示注入攻击，来保护使用计算机的智能体。然而，我们发现代理约束的两种核心安全机制仍然存在漏洞。通过分析最受欢迎的代理之一Openclaw，我们进一步总结出七种现实可被利用的攻击模式，这表明旨在防止恶意行为的安全机制本身也可能被操纵以助长……

</details>

<details>
<summary><b>15. CARE-3D: Reinforcement Learning for Evidence Grounded Agentic Reasoning in Situated 3D Scenes</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Xiaoqian Hu、Ruihong Qiu、Yanran Tang、Sen Wang |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-11-23T03:36:02Z |
| **关键词** | `Agentic` · `Reasoning` · `Reinforcement Learning` · `RAG` · `Fine-tuning` |
| **原文链接** | [http://arxiv.org/abs/2611.29969v1](http://arxiv.org/abs/2611.29969v1) |

**📝 摘要概括：**

> 情境化3D推理要求具身智能体解释物体、场景几何和视点相关的空间关系。现有方法从监督轨迹中学习基于现实的交互，但主要是在模仿预先规定的证据获取模式，而不是优化所返回的证据对正确答案的支持。我们的代码可在\href{https://github.com/xiaoqian-UQ/CARE-3D}{CARE-3D}获取。

</details>

<details>
<summary><b>16. LLM-Assisted Software Migration: from Module-Level Transformation to Repository-Level Integration</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Yanan Zhang、Shengqi Liu、Tao Zhang、Yidi Liu、Alan Tang 等（共 7 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | HIT、Mila、TRI |
| **发布时间** | 2026-11-23T03:02:55Z |
| **关键词** | `Multi-Agent` · `Benchmark` · `Evaluation` · `Workflow` |
| **原文链接** | [http://arxiv.org/abs/2611.29942v1](http://arxiv.org/abs/2611.29942v1) |

**📝 摘要概括：**

> 软件迁移是将现有实现适配到新的语言、版本、API、框架或平台，同时保留其行为。大型语言模型（LLM）在单个函数和模块上取得了成功，但这种成功并不容易扩展到整个代码库，特别是可部署的应用程序。最后，我们讨论了六个未决问题：应用程序集成、平台差异、非功能属性、泛化……

</details>

<details>
<summary><b>17. Autonomous Multireference Quantum Chemistry with Artificial Intelligence Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Younghwan Kim、Ming-Hsiu Hsieh、Ankit Mathanker、Arpan Choudhury、Joshua Zhou 等（共 8 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | CAS、NTU |
| **发布时间** | 2026-11-23T01:57:36Z |
| **关键词** | `Agentic` · `Workflow` |
| **原文链接** | [http://arxiv.org/abs/2611.29902v1](http://arxiv.org/abs/2611.29902v1) |

**📝 摘要概括：**

> 准确描述涉及强关联电子的化学反应仍然是计算化学领域的一大挑战。多重态电子结构方法可以应对这一挑战，但其应用需要专家的决策，而这些决策很难实现自动化，特别是在化学键形成和断裂导致电子结构发生变化时。除了自动化计算之外，此类代理还有潜力帮助研究……

</details>

<details>
<summary><b>18. MobileGrail: Learning Compact Guardrails for On-Device deployable Mobile GUI Agent Safety</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Zhiyu Zhang、Yuankai Li、Muhao Chen |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT |
| **发布时间** | 2026-11-23T00:09:33Z |
| **关键词** | `Reinforcement Learning` · `RAG` · `Benchmark` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2611.29847v1](http://arxiv.org/abs/2611.29847v1) |

**📝 摘要概括：**

> 运行时防护机制通过在执行前评估每个拟议操作来保护移动 GUI 代理，但现有的防护机制依赖于云端托管的大型多模态模型，这会将每个屏幕暴露给远程服务器，包括支付、消息和医疗记录等私人信息。我们提出了 MobileGrail，这是一种可在设备上部署的模型，能够同时解决这两个问题。MobileGrail 量化为 4 位，在 Snapdragon 8 Elite 上运行，中位数延迟为 4……

</details>

<details>
<summary><b>19. Who Makes the Decision? Auditing an Agentic LLM Pipeline for Illicit Cryptocurrency Transaction Monitoring</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Vaishnavi Chaughule、Yuchen Zhang、Mohammed Ahnaf Tajwar、Sai Akshay Menta、Saanidhya Vats 等（共 8 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | CAS、TRI |
| **发布时间** | 2026-11-22T23:16:50Z |
| **关键词** | `Agentic` · `Retrieval` |
| **原文链接** | [http://arxiv.org/abs/2611.29829v1](http://arxiv.org/abs/2611.29829v1) |

**📝 摘要概括：**

> 目前正在提出一种代理管道，它结合了图检测器、确定性规则、检索增强生成和LLM评判器，用于监测非法加密货币流动，并为分析师撰写引用法规的理由。对它们的评估基于端到端准确性或这些理由的质量，但两者都未显示是哪个组件做出了决定。因此，对于非法活动监控，LLM 的理由不应……

</details>

<details>
<summary><b>20. Memphis: A Case Study in Seeding an Agent Task from a Model's Real-World Attempt</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Ibrahim A. Ahmed、Ahmed Sameh Khalil |
| **所属机构** | （详见原文） |
| **顶级机构标签** | CAS、TRI |
| **发布时间** | 2026-11-22T23:03:45Z |
| **关键词** | `RAG` · `Benchmark` · `Evaluation` · `Simulation` |
| **原文链接** | [http://arxiv.org/abs/2611.29824v1](http://arxiv.org/abs/2611.29824v1) |

**📝 摘要概括：**

> 通常，通过增加构建任务的数据量，代理基准会变得更加困难，但即使在基准上表现出色的模型，在实际工作中仍然会失败。我们建议根据模型在现实世界中尝试完成开放式任务的情况来构建模拟任务，这样模型的模拟任务失败情况就与其实际任务失败情况相似。我们发布了任务、试验、审核以及经过编辑的真实世界评估记录。

</details>

## 🗄️ 历史归档

| 日期 | 论文数 | 报告链接 |
|------|--------|----------|
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
| 2026-10-11 | 0 篇 | [2026-10-11.md](daily/2026-10-11.md) |
| 2026-10-10 | 20 篇 | [2026-10-10.md](daily/2026-10-10.md) |

## 🏛️ 顶级机构覆盖范围

覆盖超过 **70 个**顶级 AI 机构，包括：

- **科技公司：** Microsoft、Google DeepMind、OpenAI、Anthropic、Meta AI、NVIDIA、Baidu、Alibaba、ByteDance 等
- **北美顶级大学：** MIT、Stanford、CMU、UC Berkeley、Harvard、Princeton、Cornell、Caltech 等
- **中国顶级大学/机构：** 清华大学、北京大学、浙大、上交大、复旦、中科院、MSRA 等
- **欧洲/其他：** Oxford、Cambridge、ETH Zurich、Mila、NUS、KAIST 等

---

*由 [clawBot DailyFindings](https://github.com/Jacob-biu/clawBot) 自动维护 | 最后更新：2026-11-24 05:46 UTC*
