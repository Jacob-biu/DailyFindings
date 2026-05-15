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

## 📅 今日论文 — 2026-05-15　　[→ 查看完整报告](daily/2026-05-15.md)

> 共筛选出 **20** 篇论文 | 更新于 2026-05-15 22:55 UTC

### 论文目录与概要

| # | 论文标题 | 核心概要 | 来源机构 | 第一作者 |
|---|---------|---------|---------|--------|
| 1 | [ATLAS: Agentic or Latent Visual Reasoning? One Word is Enoug…](http://arxiv.org/abs/2605.15198v1) | 视觉推理通常与中间视觉状态交织在一起，已成为该领域的一个有希望的方向。一种简单的方法是在推理过程中通过统一模型直接生成图像，但这在计算上是昂贵的，在架构上也不平凡。我们希望ATLAS能够提供一种新的范… | MIT、HIT | Ziyu Guo |
| 2 | [FutureSim: Replaying World Events to Evaluate Adaptive Agent…](http://arxiv.org/abs/2605.15188v1) | 人工智能代理越来越多地部署在动态的开放式环境中，这些环境需要在新信息到达时对其进行调整。为了有效地衡量现实用例的这种能力，我们建议构建接地模拟，按照真实世界事件发生的顺序重放它们。总体而言，我们希望我… | CAS | Shashwat Goel |
| 3 | [Position: Behavioural Assurance Cannot Verify the Safety Cla…](http://arxiv.org/abs/2605.15164v1) | 这份立场文件认为，行为保证，即使经过精心设计，也被要求携带无法验证的安全声明。2019年至2026年初颁布的人工智能治理框架需要可审查的特性证据，例如缺乏隐藏目标、对失控前体的抵抗力以及有限的灾难性能… | MIT、CAS | Pratinav Seth |
| 4 | [Self-Distilled Agentic Reinforcement Learning](http://arxiv.org/abs/2605.15155v1) | 强化学习（ RL ）已成为训练后LLM代理的核心范式，但其轨迹级奖励信号仅为长距离交互提供粗略的监督。On-Policy Self-Distillation （ OPSD ）通过从具有特权上下文的教师… | TRI | Zhengxi Lu |
| 5 | [APWA: A Distributed Architecture for Parallelizable Agentic …](http://arxiv.org/abs/2605.15132v1) | 基于大型语言模型（ LLM ）的自主多智能体系统在广泛的应用领域中独立解决复杂任务方面表现出了非凡的能力。然而，随着任务规模和复杂性的增长，这些系统遇到了关键的推理、协调和计算扩展瓶颈。在我们的评估中… | MIT、HIT | Evan Rose |
| 6 | [Why Neighborhoods Matter: Traversal Context and Provenance i…](http://arxiv.org/abs/2605.15109v1) | 检索-增强生成可以通过将答案建立在外部证据的基础上来改善事实性，但Agentic GraphRAG使引文忠实的含义复杂化。在这些系统中，代理在生成答案和一小组引文之前探索知识图谱。这些研究结果表明， … | TRI | Riccardo Terrenzi |
| 7 | [Concurrency without Model Changes: Future-based Asynchronous…](http://arxiv.org/abs/2605.15077v1) | 函数调用，也称为工具使用，是现代LLM代理的核心功能，但通常受同步执行语义的约束。在这些语义下， LLM解码被阻塞，直到每个函数调用完成，导致端到端延迟增加。此外，这些结果表明， LLM具有对表示未解… | MIT | Guangyu Feng |
| 8 | [SpeakerLLM: A Speaker-Specialized Audio-LLM for Speaker Unde…](http://arxiv.org/abs/2605.15044v1) | 随着音频优先代理在物理AI、会话机器人和无屏可穿戴设备中变得越来越普遍，音频大语言模型（ audio-LLMs ）必须整合特定于说话者的理解，以支持用户授权、个性化和情境感知交互。这需要对谁在说话、声… | MIT | KiHyun Nam |
| 9 | [Orchard: An Open-Source Agentic Modeling Framework](http://arxiv.org/abs/2605.15040v1) | Agentic建模旨在将LLM转化为能够通过规划、推理、工具使用以及与环境的多回合交互来解决复杂任务的自主代理。尽管投入了大量资金，但开放研究仍然受到基础设施和培训差距的限制。总的来说，这些结果表明，… | MIT | Baolin Peng |
| 10 | [WARD: Adversarially Robust Defense of Web Agents Against Pro…](http://arxiv.org/abs/2605.15030v1) | Web代理可以通过与网站交互自主完成在线任务，但它们暴露在开放的Web环境中，使它们容易受到嵌入在HTML内容或可视化界面中的提示注入攻击。现有的防护模型仍然存在对看不见的域和攻击模式的有限泛化、良性… | MIT、TRI | Tri Cao |
| 11 | [COTCAgent: Preventive Consultation via Probabilistic Chain-o…](http://arxiv.org/abs/2605.15016v1) | 随着大型语言模型赋予医疗保健能力，智能临床决策支持得到了快速发展。纵向电子健康记录（ EHR ）为准确的临床诊断和分析提供了重要的时间证据。该代码可在https://github.com/FrankD… | MIT、TRI | Zihan Deng |
| 12 | [Efficient Online Conformal Selection with Limited Feedback](http://arxiv.org/abs/2605.14953v1) | 我们解决了共形选择的问题，其中代理必须选择最小的选项子集，以确保至少有一个“成功”被识别为预先指定的目标概率$ φ $。虽然传统的在线共形预测侧重于保持观察序列的有效性，但最大限度地降低此类选择的资源… | MIT、TRI | Sreenivas Gollapudi |
| 13 | [Not All Symbols Are Equal: Importance-Aware Constellation De…](http://arxiv.org/abs/2605.14940v1) | 面向目标传输的语义通信系统不仅要通过源压缩来保护任务相关信息，还要通过物理层映射来保护任务相关信息。现有方法将星座设计和语义编码解耦，以与无关符号相同的速率将关键符号暴露于通道错误。仿真结果表明，所提… | TRI | Albert Shaju |
| 14 | [Slot-MPC: Goal-Conditioned Model Predictive Control with Obj…](http://arxiv.org/abs/2605.14937v1) | 预测世界模型使代理能够对场景动态进行建模，并对其行为的后果进行推理。受人类感知的启发，以对象为中心的世界模型使用对象级表示捕获场景动态，可用于动作计划等下游应用。代码和其他结果可在https://sl… | MIT、TRI | Jonathan Spieler |
| 15 | [Beyond Individual Intelligence: Surveying Collaboration, Fai…](http://arxiv.org/abs/2605.14892v1) | 基于LLM的自主代理在推理、规划和工具使用方面表现出强大的能力，但在任务需要跨角色、工具和环境的持续协调时仍然有限。多代理系统通过专业代理之间的结构化协作来解决这个问题，但更紧密的协调也放大了一个较少… | MIT、TRI | Shihao Qi |
| 16 | [Temporal Fair Division in Multi-Agent Systems: From Precise …](http://arxiv.org/abs/2605.14879v1) | 过多的真实世界环境要求代理反复竞争相同的有限资源，要求在整个交互历史中判断公平的时间概念。本文在重复多智能体资源竞争的统一框架内，通过引入Rotational Periodicity （ RP ） （… | FAIR、MIT | Nikolaos Al. Papadopoulos |
| 17 | [Towards In-Depth Root Cause Localization for Microservices w…](http://arxiv.org/abs/2605.14866v1) | 随着现代微服务系统由于动态交互和不断变化的运行时环境而变得越来越复杂，它们会经历越来越频繁的故障。因此，确保系统可靠性关键取决于准确的根本原因定位（ RCL ）。在多个公共基准上的广泛实验表明， RC… | MIT | Lingzhe Zhang |
| 18 | [Holistic Evaluation and Failure Diagnosis of AI Agents](http://arxiv.org/abs/2605.14865v1) | 人工智能代理执行复杂的多步骤流程，但目前的评估不足：结果指标报告成功或失败而没有解释原因，而流程级方法则难以在长时间的结构化跟踪中将失败类型与其精确位置联系起来。我们提出了一个整体代理评估框架，将自上… | TRI | Netta Madvil |
| 19 | [Do Coding Agents Understand Least-Privilege Authorization?](http://arxiv.org/abs/2605.14859v1) | 随着编码代理获得对shell、存储库和用户文件的访问权限，最低权限授权成为安全部署的先决条件：代理应获得足够的权限来完成任务，而不会暴露不必要的权限。为了研究当前模型是否可以自行推断此边界，我们首先引… | MIT、NUS | Zheng Yan |
| 20 | [A Deterministic Agentic Workflow for HS Tariff Classificatio…](http://arxiv.org/abs/2605.14857v1) | 协调制度（ HS ）关税分类是一项高风险的专家级任务，其中必须根据一般解释规则（ GIR ）、章节注释、章节注释和解释性说明，将自由格式的产品描述映射到特定的六位或八位代码。困难不在于知识量，而在于*… | HIT、TRI | Yu Zhang |

### 论文详情

<details>
<summary><b>1. ATLAS: Agentic or Latent Visual Reasoning? One Word is Enough for Both</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Ziyu Guo、Rain Liu、Xinyan Chen、Pheng-Ann Heng |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、HIT、TRI |
| **发布时间** | 2026-05-14T17:59:55Z |
| **关键词** | `Agentic` · `Reasoning` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2605.15198v1](http://arxiv.org/abs/2605.15198v1) |

**📝 摘要概括：**

> 视觉推理通常与中间视觉状态交织在一起，已成为该领域的一个有希望的方向。一种简单的方法是在推理过程中通过统一模型直接生成图像，但这在计算上是昂贵的，在架构上也不平凡。我们希望ATLAS能够提供一种新的范式，激发未来的视觉推理研究。

</details>

<details>
<summary><b>2. FutureSim: Replaying World Events to Evaluate Adaptive Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Shashwat Goel、Nikhil Chandak、Arvindh Arun、Ameya Prabhu、Steffen Staab 等（共 8 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | CAS |
| **发布时间** | 2026-05-14T17:59:28Z |
| **关键词** | `AI Agent` · `Reasoning` · `Benchmark` · `Simulation` · `Memory` |
| **原文链接** | [http://arxiv.org/abs/2605.15188v1](http://arxiv.org/abs/2605.15188v1) |

**📝 摘要概括：**

> 人工智能代理越来越多地部署在动态的开放式环境中，这些环境需要在新信息到达时对其进行调整。为了有效地衡量现实用例的这种能力，我们建议构建接地模拟，按照真实世界事件发生的顺序重放它们。总体而言，我们希望我们的基准设计能够为衡量现实世界中跨越长时间范围的开放式适应的人工智能进展铺平道路。

</details>

<details>
<summary><b>3. Position: Behavioural Assurance Cannot Verify the Safety Claims Governance Now Demands</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Pratinav Seth、Vinay Kumar Sankarapu |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、CAS、TRI |
| **发布时间** | 2026-05-14T17:54:28Z |
| **关键词** | `Agentic` · `RAG` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2605.15164v1](http://arxiv.org/abs/2605.15164v1) |

**📝 摘要概括：**

> 这份立场文件认为，行为保证，即使经过精心设计，也被要求携带无法验证的安全声明。2019年至2026年初颁布的人工智能治理框架需要可审查的特性证据，例如缺乏隐藏目标、对失控前体的抵抗力以及有限的灾难性能力；当前的保证方法（主要是行为评估和红队） ……

</details>

<details>
<summary><b>4. Self-Distilled Agentic Reinforcement Learning</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Zhengxi Lu、Zhiyuan Yao、Zhuowen Han、Zi-Han Wang、Jinyang Wu 等（共 11 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-05-14T17:51:26Z |
| **关键词** | `LLM Agent` · `Agentic` · `Reinforcement Learning` · `Retrieval` |
| **原文链接** | [http://arxiv.org/abs/2605.15155v1](http://arxiv.org/abs/2605.15155v1) |

**📝 摘要概括：**

> 强化学习（ RL ）已成为训练后LLM代理的核心范式，但其轨迹级奖励信号仅为长距离交互提供粗略的监督。On-Policy Self-Distillation （ OPSD ）通过从具有特权上下文的教师分支引入密集的令牌级指导来补充RL。在ALFWorld、WebShop和Search-QA上的Qwen2.5和Qwen3系列中， SDAR比…

</details>

<details>
<summary><b>5. APWA: A Distributed Architecture for Parallelizable Agentic Workflows</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Evan Rose、Tushin Mallick、Matthew D. Laws、Cristina Nita-Rotaru、Alina Oprea |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、HIT、TRI |
| **发布时间** | 2026-05-14T17:40:20Z |
| **关键词** | `Multi-Agent` · `Agentic` · `Reasoning` · `Evaluation` · `Workflow` |
| **原文链接** | [http://arxiv.org/abs/2605.15132v1](http://arxiv.org/abs/2605.15132v1) |

**📝 摘要概括：**

> 基于大型语言模型（ LLM ）的自主多智能体系统在广泛的应用领域中独立解决复杂任务方面表现出了非凡的能力。然而，随着任务规模和复杂性的增长，这些系统遇到了关键的推理、协调和计算扩展瓶颈。在我们的评估中，我们证明了APWA可以动态地将复杂的查询分解为可并行的工作流……

</details>

<details>
<summary><b>6. Why Neighborhoods Matter: Traversal Context and Provenance in Agentic GraphRAG</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Riccardo Terrenzi、Maximilian von Zastrow、Serkan Ayvaz |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-05-14T17:25:20Z |
| **关键词** | `Agentic` · `RAG` · `Retrieval` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2605.15109v1](http://arxiv.org/abs/2605.15109v1) |

**📝 摘要概括：**

> 检索-增强生成可以通过将答案建立在外部证据的基础上来改善事实性，但Agentic GraphRAG使引文忠实的含义复杂化。在这些系统中，代理在生成答案和一小组引文之前探索知识图谱。这些研究结果表明， Agentic GraphRAG中的引文评估应超越源支持，转向更广泛的检索轨迹上的出处。

</details>

<details>
<summary><b>7. Concurrency without Model Changes: Future-based Asynchronous Function Calling for LLMs</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Guangyu Feng、Huanzhi Mao、Prabal Dutta、Joseph E. Gonzalez |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT |
| **发布时间** | 2026-05-14T17:02:28Z |
| **关键词** | `LLM Agent` · `Benchmark` · `Fine-tuning` |
| **原文链接** | [http://arxiv.org/abs/2605.15077v1](http://arxiv.org/abs/2605.15077v1) |

**📝 摘要概括：**

> 函数调用，也称为工具使用，是现代LLM代理的核心功能，但通常受同步执行语义的约束。在这些语义下， LLM解码被阻塞，直到每个函数调用完成，导致端到端延迟增加。此外，这些结果表明， LLM具有对表示未解决的执行结果的符号期货进行推理的本机能力，从而实现异步……

</details>

<details>
<summary><b>8. SpeakerLLM: A Speaker-Specialized Audio-LLM for Speaker Understanding and Verification Reasoning</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | KiHyun Nam、Jungwoo Heo、Siu Bae、Ha-Jin Yu、Joon Son Chung |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT |
| **发布时间** | 2026-05-14T16:36:57Z |
| **关键词** | `Reasoning` |
| **原文链接** | [http://arxiv.org/abs/2605.15044v1](http://arxiv.org/abs/2605.15044v1) |

**📝 摘要概括：**

> 随着音频优先代理在物理AI、会话机器人和无屏可穿戴设备中变得越来越普遍，音频大语言模型（ audio-LLMs ）必须整合特定于说话者的理解，以支持用户授权、个性化和情境感知交互。这需要对谁在说话、声音听起来如何以及录音条件如何影响说话者线索进行建模。我们将发布元数据丰富的监督数据集……

</details>

<details>
<summary><b>9. Orchard: An Open-Source Agentic Modeling Framework</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Baolin Peng、Wenlin Yao、Qianhui Wu、Hao Cheng、Xiao Yu 等（共 14 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT |
| **发布时间** | 2026-05-14T16:35:12Z |
| **关键词** | `Agentic` · `Reasoning` · `Planning` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2605.15040v1](http://arxiv.org/abs/2605.15040v1) |

**📝 摘要概括：**

> Agentic建模旨在将LLM转化为能够通过规划、推理、工具使用以及与环境的多回合交互来解决复杂任务的自主代理。尽管投入了大量资金，但开放研究仍然受到基础设施和培训差距的限制。总的来说，这些结果表明，轻量级、开放、与线束无关的环境层可以实现跨领域的可重用代理数据、训练配方和评估……

</details>

<details>
<summary><b>10. WARD: Adversarially Robust Defense of Web Agents Against Prompt Injections</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Tri Cao、Yulin Chen、Hieu Cao、Yibo Li、Khoi Le 等（共 11 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-05-14T16:26:27Z |
| **关键词** | `Benchmark` · `Web Agent` · `Memory` |
| **原文链接** | [http://arxiv.org/abs/2605.15030v1](http://arxiv.org/abs/2605.15030v1) |

**📝 摘要概括：**

> Web代理可以通过与网站交互自主完成在线任务，但它们暴露在开放的Web环境中，使它们容易受到嵌入在HTML内容或可视化界面中的提示注入攻击。现有的防护模型仍然存在对看不见的域和攻击模式的有限泛化、良性内容的高误报率、由于每个步骤中增加的延迟而降低的部署效率以及漏洞……

</details>

<details>
<summary><b>11. COTCAgent: Preventive Consultation via Probabilistic Chain-of-Thought Completion</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Zihan Deng、Xiaozhen Zhong、Chuanzhi Xu |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-05-14T16:17:35Z |
| **关键词** | `Reasoning` · `RAG` · `Chain-of-Thought` |
| **原文链接** | [http://arxiv.org/abs/2605.15016v1](http://arxiv.org/abs/2605.15016v1) |

**📝 摘要概括：**

> 随着大型语言模型赋予医疗保健能力，智能临床决策支持得到了快速发展。纵向电子健康记录（ EHR ）为准确的临床诊断和分析提供了重要的时间证据。该代码可在https://github.com/FrankDengAI/COTCAgent/上获得。

</details>

<details>
<summary><b>12. Efficient Online Conformal Selection with Limited Feedback</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Sreenivas Gollapudi、Kostas Kollias、Kamesh Munagala、Ali Sinop |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-05-14T15:22:46Z |
| **关键词** | `RAG` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2605.14953v1](http://arxiv.org/abs/2605.14953v1) |

**📝 摘要概括：**

> 我们解决了共形选择的问题，其中代理必须选择最小的选项子集，以确保至少有一个“成功”被识别为预先指定的目标概率$ φ $。虽然传统的在线共形预测侧重于保持观察序列的有效性，但最大限度地降低此类选择的资源成本（效率） ，特别是在有限的反馈下，仍然是一个重大挑战。我们的方法h…

</details>

<details>
<summary><b>13. Not All Symbols Are Equal: Importance-Aware Constellation Design for Semantic Communication</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Albert Shaju、Christo Kurisummoottil Thomas、Mayukh Roy Chowdhury |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-05-14T15:15:57Z |
| **关键词** | `Reinforcement Learning` · `RAG` · `Simulation` |
| **原文链接** | [http://arxiv.org/abs/2605.14940v1](http://arxiv.org/abs/2605.14940v1) |

**📝 摘要概括：**

> 面向目标传输的语义通信系统不仅要通过源压缩来保护任务相关信息，还要通过物理层映射来保护任务相关信息。现有方法将星座设计和语义编码解耦，以与无关符号相同的速率将关键符号暴露于通道错误。仿真结果表明，所提出的星座在来自4-QAM的调制阶数上实现了接近100%的SPP。

</details>

<details>
<summary><b>14. Slot-MPC: Goal-Conditioned Model Predictive Control with Object-Centric Representations</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Jonathan Spieler、Angel Villar-Corrales、Sven Behnke |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-05-14T15:12:15Z |
| **关键词** | `Planning` · `Reinforcement Learning` · `RAG` |
| **原文链接** | [http://arxiv.org/abs/2605.14937v1](http://arxiv.org/abs/2605.14937v1) |

**📝 摘要概括：**

> 预测世界模型使代理能够对场景动态进行建模，并对其行为的后果进行推理。受人类感知的启发，以对象为中心的世界模型使用对象级表示捕获场景动态，可用于动作计划等下游应用。代码和其他结果可在https://slot-mpc.github.io上获得。

</details>

<details>
<summary><b>15. Beyond Individual Intelligence: Surveying Collaboration, Failure Attribution, and Self-Evolution in LLM-based Multi-Agent Systems</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Shihao Qi、Jie Ma、Rui Xing、Wei Guo、Xiao Huang 等（共 18 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-05-14T14:36:13Z |
| **关键词** | `Multi-Agent` · `Reasoning` · `Planning` · `RAG` |
| **原文链接** | [http://arxiv.org/abs/2605.14892v1](http://arxiv.org/abs/2605.14892v1) |

**📝 摘要概括：**

> 基于LLM的自主代理在推理、规划和工具使用方面表现出强大的能力，但在任务需要跨角色、工具和环境的持续协调时仍然有限。多代理系统通过专业代理之间的结构化协作来解决这个问题，但更紧密的协调也放大了一个较少探索的风险：错误可以在代理和交互回合中传播，从而产生困难的故障……

</details>

<details>
<summary><b>16. Temporal Fair Division in Multi-Agent Systems: From Precise Alternation Metrics to Scalable Coordination Proxies</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Nikolaos Al. Papadopoulos |
| **所属机构** | （详见原文） |
| **顶级机构标签** | FAIR、MIT、TRI |
| **发布时间** | 2026-05-14T14:23:32Z |
| **关键词** | `Multi-Agent` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2605.14879v1](http://arxiv.org/abs/2605.14879v1) |

**📝 摘要概括：**

> 过多的真实世界环境要求代理反复竞争相同的有限资源，要求在整个交互历史中判断公平的时间概念。本文在重复多智能体资源竞争的统一框架内，通过引入Rotational Periodicity （ RP ） （一个轻量级指标家族）以及ALT滑动窗口测量家族，推进了时间公平划分理论。……

</details>

<details>
<summary><b>17. Towards In-Depth Root Cause Localization for Microservices with Multi-Agent Recursion-of-Thought</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Lingzhe Zhang、Tong Jia、Kangjin Wang、Chiming Duan、Minghua He 等（共 11 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT |
| **发布时间** | 2026-05-14T14:13:59Z |
| **关键词** | `Multi-Agent` · `Reasoning` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2605.14866v1](http://arxiv.org/abs/2605.14866v1) |

**📝 摘要概括：**

> 随着现代微服务系统由于动态交互和不断变化的运行时环境而变得越来越复杂，它们会经历越来越频繁的故障。因此，确保系统可靠性关键取决于准确的根本原因定位（ RCL ）。在多个公共基准上的广泛实验表明， RCLAgent在定位精度和推理效率方面始终优于最先进的方法……

</details>

<details>
<summary><b>18. Holistic Evaluation and Failure Diagnosis of AI Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Netta Madvil、Gilad Dym、Alon Mecilati、Edo Dekel、Jonatan Liberman 等（共 15 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-05-14T14:12:39Z |
| **关键词** | `AI Agent` · `Benchmark` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2605.14865v1](http://arxiv.org/abs/2605.14865v1) |

**📝 摘要概括：**

> 人工智能代理执行复杂的多步骤流程，但目前的评估不足：结果指标报告成功或失败而没有解释原因，而流程级方法则难以在长时间的结构化跟踪中将失败类型与其精确位置联系起来。我们提出了一个整体代理评估框架，将自上而下的代理级诊断与自下而上的跨度级评估相结合，将分析分解为独立的每跨度…

</details>

<details>
<summary><b>19. Do Coding Agents Understand Least-Privilege Authorization?</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Zheng Yan、Jingxiang Weng、Charles Chen、Dengyun Peng、Ethan Qin 等（共 12 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、NUS |
| **发布时间** | 2026-05-14T14:05:58Z |
| **关键词** | `Reasoning` · `RAG` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2605.14859v1](http://arxiv.org/abs/2605.14859v1) |

**📝 摘要概括：**

> 随着编码代理获得对shell、存储库和用户文件的访问权限，最低权限授权成为安全部署的先决条件：代理应获得足够的权限来完成任务，而不会暴露不必要的权限。为了研究当前模型是否可以自行推断此边界，我们首先引入权限边界推断，其中模型映射任务指令和终端环境……

</details>

<details>
<summary><b>20. A Deterministic Agentic Workflow for HS Tariff Classification: Multi-Dimensional Rule Reasoning with Interpretable Decisions</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Yu Zhang、Dongjiang Zhuang、Qu Zhou、Zheng Huang、Junhe Wu 等（共 7 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | HIT、TRI |
| **发布时间** | 2026-05-14T14:04:46Z |
| **关键词** | `Agentic` · `Reasoning` · `Planning` · `Workflow` |
| **原文链接** | [http://arxiv.org/abs/2605.14857v1](http://arxiv.org/abs/2605.14857v1) |

**📝 摘要概括：**

> 协调制度（ HS ）关税分类是一项高风险的专家级任务，其中必须根据一般解释规则（ GIR ）、章节注释、章节注释和解释性说明，将自由格式的产品描述映射到特定的六位或八位代码。困难不在于知识量，而在于*多维规则推理* ：正确的分类必须满足沿着几个轴的优先级规则。

</details>

## 🗄️ 历史归档

| 日期 | 论文数 | 报告链接 |
|------|--------|----------|
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

*由 [clawBot DailyFindings](https://github.com/Jacob-biu/clawBot) 自动维护 | 最后更新：2026-05-15 22:55 UTC*
