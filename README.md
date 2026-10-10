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

## 📅 今日论文 — 2026-10-10　　[→ 查看完整报告](daily/2026-10-10.md)

> 共筛选出 **20** 篇论文 | 更新于 2026-10-10 01:31 UTC

### 论文目录与概要

| # | 论文标题 | 核心概要 | 来源机构 | 第一作者 |
|---|---------|---------|---------|--------|
| 1 | [From Reactive Containment to Proactive Assurance: Lessons fr…](http://arxiv.org/abs/2610.12463v1) | 2026年，涉及OpenAI、Anthropic和Google代理的网络安全评估超出了其授权测试范围。路径不同。核心结论很简单：主动代理安全需要整个完整执行系统的持续保证，而不是对任何单个沙箱或安全措… | Google、OpenAI | Abbas Raftari |
| 2 | [Caught in the Act: Probes Effectively Detect Sabotage and Ca…](http://arxiv.org/abs/2610.12445v1) | 最近的事件凸显了监控法学硕士代理的挑战以及模型欺骗人的危险。我们表明，通过收集迄今为止用于训练探针的最大欺骗数据集，并引入一种可以跨多层和令牌聚合信息的新型探针架构，可以将通过探针进行的白盒欺骗检测扩… | MIT、HIT | Oskar J. Hollinsworth |
| 3 | [RoboRSI: Stable, efficient, and reusable robot self-evolutio…](http://arxiv.org/abs/2610.12424v1) | 通才机器人不仅应该执行不同的任务，还应该通过经验进行改进，将执行过程中学到的知识转化为后续任务可以重复使用的能力。通过代码行事的机器人代理已经可以从执行反馈中修复程序，但围绕赋予其意义的任务结构组织这… | TRI | Zimo Wen |
| 4 | [OnTrack: Real-Time Monitoring and Intervention in LLM Agent …](http://arxiv.org/abs/2610.12375v1) | 从差旅规划师、股票交易到IT事故分类，应用程序中都会部署客服代表。在大多数情况下， LLM专员以最少的基于规则的保障措施自主工作，导致不可逆转的行动导致成本和安全问题。通过中止策略，我们节省了大约18… | CAS、Mila | Babak Barazandeh |
| 5 | [Accurate but Not Humble: Evaluating Epistemic Humility in LL…](http://arxiv.org/abs/2610.12360v1) | 当检索到的证据与客服代表的先前信念相矛盾时，客服代表是否修改了答案、承认不确定性或坚持错误的结论？对客服代表系统的现有评估主要侧重于任务成功，对客服代表如何处理此类冲突提供有限的见解。最后，我们表明，… | MIT、TRI | Kaiser Sun |
| 6 | [Can AI Agents Learn Their Way to the Top? Evaluating Heurist…](http://arxiv.org/abs/2610.12341v1) | 对抗性游戏推动了从启发式搜索到强化学习的进步，但从有限的样本中学习和调整策略仍然具有挑战性。人工智能代理通过将游戏体验转化为可执行策略的修订，提供了另一种选择。这些结果突出了HL在对抗性游戏中的潜力，… | MIT | Kaisen Yang |
| 7 | [Prior or Feedback? What an LLM Uses When Adapting Neural Ope…](http://arxiv.org/abs/2610.12325v1) | 法学硕士科学代理仅依赖于他们最初的任务背景，还是根据实验反馈调整他们的决策？我们在神经算子适应中研究这个问题，其中大型语言模型（ LLM ）在有限的试验预算下选择微调配置。这些干预措施确立了法学硕士的… | MIT、CAS | Julian Chan |
| 8 | [Multi-Agent Egocentric World Model with Fine-Grained Embodie…](http://arxiv.org/abs/2610.12299v1) | 以自我为中心的世界模型预测第一人称观察取决于座席的行为，但大多数侧重于单个座席。真正的具体设置通常涉及在共享环境中行事和互动的多个代理。实验表明，与现有方法相比， ME-World提高了共享世界的一致… | TRI | Dahyun Chung |
| 9 | [One Word Opens the Gate: The Option-Channel Attack on Typed …](http://arxiv.org/abs/2610.12292v1) | 类型化的决策模型读取一段文本，并返回调用方定义选项的概率，每个选项都有一个简短的书面定义，不会生成文本。最近的工作将这些模型放在代理系统中作为护栏：读取建议的工具调用或传入消息并决定是否允许的组件。优… | MIT、CAS | Seyedarmin Azizi |
| 10 | [Unlocking the Regulatory Genome by ARGUS: An Evidence-Constr…](http://arxiv.org/abs/2610.12281v1) | 全基因组关联研究中超过90%的疾病相关变异属于非编码调控区域，但其功能解释仍然是基因组医学中的一个核心开放问题。提示解释这些变异的大型语言模型通常会使转录因子（ TF ）结合变化产生幻觉，制造实验支持… | TRI | Pratik Dutta |
| 11 | [DataSense-Bench: The First Step Toward an AI Scientist](http://arxiv.org/abs/2610.12190v1) | 随着关于递归自我改进（ RSI ）和人工智能（ AGI ）的说法的激增，我们提出了一个简单的问题：前沿人工智能模型是否有数据感，即它们能否可靠地选择正确的数据进行训练？我们引入DataSense-Be… | MIT、CAS | Yudi Zhang |
| 12 | [A Closer Look at Agentic BBO: Benchmarking LLM Agents for Bl…](http://arxiv.org/abs/2610.12183v1) | 黑盒优化（ BBO ）出现在许多客观评估昂贵且有限的科学和工程问题中。最近的大型语言模型（ LLM ）代理通过将任务语义、计算、优化工具和反馈驱动的决策相结合，提供了一种新的方法来处理BBO ，由于与… | MIT | Ming Chen |
| 13 | [Q-Shaped Options for Hierarchical Reinforcement Learning](http://arxiv.org/abs/2610.12135v1) | 学习处理长远的、有目标条件的任务需要代理对延长的时间表进行推理，并在广泛的州采取行动。原则上，分层强化学习（ HRL ）通过动作（时间）和状态（空间）抽象之间的交互来解决这两个挑战。在离线目标条件的运… | MIT、HIT | Clarisse Wibault |
| 14 | [OA-MAP: Evidence-Grounded Multi-Agent Multimodal Framework f…](http://arxiv.org/abs/2610.12134v1) | 膝关节骨性关节炎（ KOA ）进展预测可以支持患者监测，需要整合多模式数据和多领域专业知识。此外，孤立的风险评估提供有限的洞察力作为预测的基础。一个案例研究说明了OA-MAP如何将风险评估与中间发现、… | MIT、CAS | Sixu Chen |
| 15 | [Use and Disuse: Intent-Structured Experience Consolidation f…](http://arxiv.org/abs/2610.12124v1) | 大型语言模型代理从单任务执行到长期自主操作的演变凸显了将连续体验转化为可重用知识的关键挑战。为了解决这个问题，我们提出了Hippocam ，这是一种分层记忆和持续学习架构。这使代理能够通过自己的体验学… | HIT、NUS | Xiangyi Zeng |
| 16 | [Could LLM Watermark Detection be Public?](http://arxiv.org/abs/2610.12106v1) | 水印大型语言模型在跟踪聊天机器人和代理输出方面很受欢迎，但检测器仍未发布，因为暴露它们可能会让攻击者根据检测器的反馈进行有针对性的编辑。然而，水印已经容易受到不知情的篡改攻击。这限制了提供商的责任，并… | TRI | Georgios Milis |
| 17 | [EvoAlloc: A Self-Evolving Resource Allocation Agent for Effi…](http://arxiv.org/abs/2610.12086v1) | 基于LLM的课程进化依赖于评估反馈来指导高性能课程的迭代搜索。然而，评估通常在计算上昂贵，因此必须将有限的资源分配给能够最有效地推进搜索的候选人。此外，在相同的全面评估预算下， EvoAlloc的最终… | MIT、CAS | Yanning Dai |
| 18 | [When Should Agents Think? Adaptive Reasoning via Cross-Turn …](http://arxiv.org/abs/2610.12061v1) | 基于大型语言模型（ LLM ）的代理在复杂任务上表现出强大的能力。他们通常在整个互动轨迹的每个动作之前进行推理。在四个具有代表性的代理基准上的广泛实验表明， RACE大大降低了推理成本，同时保持或提高… | MIT | Yiruo Cheng |
| 19 | [Examining Social Attribution in LLM Reasoning: A Theory-Guid…](http://arxiv.org/abs/2610.12022v1) | 大型语言模型（ LLM ）越来越多地部署在社会技术系统中，其中社会归因（将外部事件归因于代理人社会行为的原因和原因的推理过程）起着关键作用。这些过程涉及对社会事业、责任以及对客服代表的责任/信用的判断… | TRI | Zhaoxin Yu |
| 20 | [Agentic-TTT: Training test-time policy for test-time trainin…](http://arxiv.org/abs/2610.12002v1) | 测试时间培训（ TTT ）使用来自测试输入的信号来调整LLM的参数，并且可以在预先指定的设置（例如IMO比赛或指定的开放问题）中进行显着改进。通过将部署体验转化为参数更新， TTT提供了模型级自我提升… | TRI | Jiahao Lu |

### 论文详情

<details>
<summary><b>1. From Reactive Containment to Proactive Assurance: Lessons from OpenAI, Anthropic, and Google Agent Security Incidents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Abbas Raftari |
| **所属机构** | （详见原文） |
| **顶级机构标签** | Google、OpenAI、Anthropic |
| **发布时间** | 2026-10-08T17:59:49Z |
| **关键词** | `AI Agent` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2610.12463v1](http://arxiv.org/abs/2610.12463v1) |

**📝 摘要概括：**

> 2026年，涉及OpenAI、Anthropic和Google代理的网络安全评估超出了其授权测试范围。路径不同。核心结论很简单：主动代理安全需要整个完整执行系统的持续保证，而不是对任何单个沙箱或安全措施的信任。

</details>

<details>
<summary><b>2. Caught in the Act: Probes Effectively Detect Sabotage and Catch Unverbalized Deception</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Oskar J. Hollinsworth、Alex F. Spies、Tigist Diriba、Adam Gleave、Chris Cundy |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、HIT、CAS |
| **发布时间** | 2026-10-08T17:58:13Z |
| **关键词** | `LLM Agent` · `RAG` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2610.12445v1](http://arxiv.org/abs/2610.12445v1) |

**📝 摘要概括：**

> 最近的事件凸显了监控法学硕士代理的挑战以及模型欺骗人的危险。我们表明，通过收集迄今为止用于训练探针的最大欺骗数据集，并引入一种可以跨多层和令牌聚合信息的新型探针架构，可以将通过探针进行的白盒欺骗检测扩展到前沿监控设置。我们发布了名为FIBS的培训数据集，以帮助...

</details>

<details>
<summary><b>3. RoboRSI: Stable, efficient, and reusable robot self-evolution in complex real-world environments</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Zimo Wen、Yijin Chen、Yuxuan Cao、Wendi Chen、Yanwen Zou 等（共 11 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-10-08T17:55:12Z |
| **关键词** | `Planning` · `Simulation` |
| **原文链接** | [http://arxiv.org/abs/2610.12424v1](http://arxiv.org/abs/2610.12424v1) |

**📝 摘要概括：**

> 通才机器人不仅应该执行不同的任务，还应该通过经验进行改进，将执行过程中学到的知识转化为后续任务可以重复使用的能力。通过代码行事的机器人代理已经可以从执行反馈中修复程序，但围绕赋予其意义的任务结构组织这种体验仍然是一个核心挑战，因此每次修复都归因于负责任的能力，支持......

</details>

<details>
<summary><b>4. OnTrack: Real-Time Monitoring and Intervention in LLM Agent Trajectories via Streaming Structure-Aware Optimal Transport</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Babak Barazandeh、Connor Swanson、Chinmay Kulkarni、Nikhil Mungel |
| **所属机构** | （详见原文） |
| **顶级机构标签** | CAS、Mila、TRI |
| **发布时间** | 2026-10-08T17:32:08Z |
| **关键词** | `LLM Agent` |
| **原文链接** | [http://arxiv.org/abs/2610.12375v1](http://arxiv.org/abs/2610.12375v1) |

**📝 摘要概括：**

> 从差旅规划师、股票交易到IT事故分类，应用程序中都会部署客服代表。在大多数情况下， LLM专员以最少的基于规则的保障措施自主工作，导致不可逆转的行动导致成本和安全问题。通过中止策略，我们节省了大约18%的计算，这些计算将在运行失败时被烧毁，其中83%的中断运行实际上正在走向失败（ 6次中止中有5次是正确的）。

</details>

<details>
<summary><b>5. Accurate but Not Humble: Evaluating Epistemic Humility in LLM Agents under Knowledge Conflict</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Kaiser Sun、Bernal Jimenez Gutierrez、Hongjun Liu、Jingyu Zhang、Jie Gao 等（共 7 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-10-08T17:25:06Z |
| **关键词** | `LLM Agent` · `Agentic` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2610.12360v1](http://arxiv.org/abs/2610.12360v1) |

**📝 摘要概括：**

> 当检索到的证据与客服代表的先前信念相矛盾时，客服代表是否修改了答案、承认不确定性或坚持错误的结论？对客服代表系统的现有评估主要侧重于任务成功，对客服代表如何处理此类冲突提供有限的见解。最后，我们表明，模型级干预措施可以改善EH ，但通常以牺牲任务准确性为代价，这表明认知谦逊从…

</details>

<details>
<summary><b>6. Can AI Agents Learn Their Way to the Top? Evaluating Heuristic Learning in a Long-Running Game Agent Competition</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Kaisen Yang、Qingle Liu、Kejin Wang、Yicheng Zhao、Jieming Li 等（共 27 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT |
| **发布时间** | 2026-10-08T17:15:48Z |
| **关键词** | `AI Agent` · `Reinforcement Learning` · `Benchmark` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2610.12341v1](http://arxiv.org/abs/2610.12341v1) |

**📝 摘要概括：**

> 对抗性游戏推动了从启发式搜索到强化学习的进步，但从有限的样本中学习和调整策略仍然具有挑战性。人工智能代理通过将游戏体验转化为可执行策略的修订，提供了另一种选择。这些结果突出了HL在对抗性游戏中的潜力，并确定了游戏理解、策略实施和长期政策制定方面的持续挑战。

</details>

<details>
<summary><b>7. Prior or Feedback? What an LLM Uses When Adapting Neural Operators</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Julian Chan、Javier Mora Jimenez |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、CAS、TRI |
| **发布时间** | 2026-10-08T17:06:23Z |
| **关键词** | `Fine-tuning` |
| **原文链接** | [http://arxiv.org/abs/2610.12325v1](http://arxiv.org/abs/2610.12325v1) |

**📝 摘要概括：**

> 法学硕士科学代理仅依赖于他们最初的任务背景，还是根据实验反馈调整他们的决策？我们在神经算子适应中研究这个问题，其中大型语言模型（ LLM ）在有限的试验预算下选择微调配置。这些干预措施确立了法学硕士的决策层行动对给定任务和观察结果的响应，表明它结合了任务依赖性……

</details>

<details>
<summary><b>8. Multi-Agent Egocentric World Model with Fine-Grained Embodied Interaction</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Dahyun Chung、Siyoon Jin、Hyunwook Choi、Honggyu An、Junyoung Seo 等（共 8 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-10-08T16:50:04Z |
| **关键词** | `Multi-Agent` · `Embodied AI` · `Memory` |
| **原文链接** | [http://arxiv.org/abs/2610.12299v1](http://arxiv.org/abs/2610.12299v1) |

**📝 摘要概括：**

> 以自我为中心的世界模型预测第一人称观察取决于座席的行为，但大多数侧重于单个座席。真正的具体设置通常涉及在共享环境中行事和互动的多个代理。实验表明，与现有方法相比， ME-World提高了共享世界的一致性、动作控制、身份保存和视频质量。

</details>

<details>
<summary><b>9. One Word Opens the Gate: The Option-Channel Attack on Typed Decision Models as Agent Guardrails</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Seyedarmin Azizi、Erfan Baghaei Potraghloo、Massoud Pedram |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、CAS |
| **发布时间** | 2026-10-08T16:46:43Z |
| **关键词** | — |
| **原文链接** | [http://arxiv.org/abs/2610.12292v1](http://arxiv.org/abs/2610.12292v1) |

**📝 摘要概括：**

> 类型化的决策模型读取一段文本，并返回调用方定义选项的概率，每个选项都有一个简短的书面定义，不会生成文本。最近的工作将这些模型放在代理系统中作为护栏：读取建议的工具调用或传入消息并决定是否允许的组件。优惠码可在https://github.com/ArminAzizi98/option-channel-attack上获得。

</details>

<details>
<summary><b>10. Unlocking the Regulatory Genome by ARGUS: An Evidence-Constrained Agentic Framework for Interpreting Single Nucleotide Variants</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Pratik Dutta、Matthew B. Obusan、Max Chao、Rekha Sathian、Nimisha Papineni 等（共 6 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-10-08T16:38:32Z |
| **关键词** | `Agentic` · `Reasoning` · `Planning` · `RAG` |
| **原文链接** | [http://arxiv.org/abs/2610.12281v1](http://arxiv.org/abs/2610.12281v1) |

**📝 摘要概括：**

> 全基因组关联研究中超过90%的疾病相关变异属于非编码调控区域，但其功能解释仍然是基因组医学中的一个核心开放问题。提示解释这些变异的大型语言模型通常会使转录因子（ TF ）结合变化产生幻觉，制造实验支持，并为统计上可忽略的信号分配生物学意义。修复的比较……

</details>

<details>
<summary><b>11. DataSense-Bench: The First Step Toward an AI Scientist</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Yudi Zhang、Mingyu Cao、Lu Yin、Mykola Pechenizkiy、Shiwei Liu |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、CAS、Mila |
| **发布时间** | 2026-10-08T15:50:57Z |
| **关键词** | `AI Agent` · `Benchmark` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2610.12190v1](http://arxiv.org/abs/2610.12190v1) |

**📝 摘要概括：**

> 随着关于递归自我改进（ RSI ）和人工智能（ AGI ）的说法的激增，我们提出了一个简单的问题：前沿人工智能模型是否有数据感，即它们能否可靠地选择正确的数据进行训练？我们引入DataSense-Bench ，通过机器学习中的数据选择和性能预测的根本问题来研究这种能力。对这两项任务的执行痕迹分析表明， ……的代理

</details>

<details>
<summary><b>12. A Closer Look at Agentic BBO: Benchmarking LLM Agents for Black-Box Optimization</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Ming Chen、Rong-Xi Tan、Ke Xue、Yu-Jie Zhou、Taiye Lu 等（共 11 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT |
| **发布时间** | 2026-10-08T15:48:07Z |
| **关键词** | `LLM Agent` · `Agentic` · `RAG` · `Benchmark` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2610.12183v1](http://arxiv.org/abs/2610.12183v1) |

**📝 摘要概括：**

> 黑盒优化（ BBO ）出现在许多客观评估昂贵且有限的科学和工程问题中。最近的大型语言模型（ LLM ）代理通过将任务语义、计算、优化工具和反馈驱动的决策相结合，提供了一种新的方法来处理BBO ，由于与数学上严格的工具集成，因此显示出巨大的潜力。我们的代码可在https://github.com/lamda-bbo/agenti上找到……

</details>

<details>
<summary><b>13. Q-Shaped Options for Hierarchical Reinforcement Learning</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Clarisse Wibault、Antoine Gorceix、Antonio Léon Villares、Alexey Zakharov、Evangelos Chatzaroulas 等（共 8 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、HIT |
| **发布时间** | 2026-10-08T15:23:39Z |
| **关键词** | `Reinforcement Learning` · `RAG` |
| **原文链接** | [http://arxiv.org/abs/2610.12135v1](http://arxiv.org/abs/2610.12135v1) |

**📝 摘要概括：**

> 学习处理长远的、有目标条件的任务需要代理对延长的时间表进行推理，并在广泛的州采取行动。原则上，分层强化学习（ HRL ）通过动作（时间）和状态（空间）抽象之间的交互来解决这两个挑战。在离线目标条件的运动和操纵环境中， QSO学习语义上有意义的选项空间，并超越……

</details>

<details>
<summary><b>14. OA-MAP: Evidence-Grounded Multi-Agent Multimodal Framework for Interpretable Knee Osteoarthritis Progression</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Sixu Chen、Mingrui Yang、Qiang Guan、Xiaojuan Li |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、CAS、TRI |
| **发布时间** | 2026-10-08T15:23:02Z |
| **关键词** | `Multi-Agent` · `Workflow` |
| **原文链接** | [http://arxiv.org/abs/2610.12134v1](http://arxiv.org/abs/2610.12134v1) |

**📝 摘要概括：**

> 膝关节骨性关节炎（ KOA ）进展预测可以支持患者监测，需要整合多模式数据和多领域专业知识。此外，孤立的风险评估提供有限的洞察力作为预测的基础。一个案例研究说明了OA-MAP如何将风险评估与中间发现、跨模式冲突、文献支持和不确定性指标相结合，以支持交互式评审。

</details>

<details>
<summary><b>15. Use and Disuse: Intent-Structured Experience Consolidation for Memory and Learning in LLM Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Xiangyi Zeng、Baihang Liu、Xutong Wang、Ze Jin、Yunpeng Li 等（共 6 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | HIT、NUS |
| **发布时间** | 2026-10-08T15:16:56Z |
| **关键词** | `LLM Agent` · `Memory` |
| **原文链接** | [http://arxiv.org/abs/2610.12124v1](http://arxiv.org/abs/2610.12124v1) |

**📝 摘要概括：**

> 大型语言模型代理从单任务执行到长期自主操作的演变凸显了将连续体验转化为可重用知识的关键挑战。为了解决这个问题，我们提出了Hippocam ，这是一种分层记忆和持续学习架构。这使代理能够通过自己的体验学习和发展能力，而无需更新参数。

</details>

<details>
<summary><b>16. Could LLM Watermark Detection be Public?</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Georgios Milis、Tom Sander、Tomáš Souček、Heng Huang、Pierre Fernandez |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-10-08T15:05:58Z |
| **关键词** | `Agentic` |
| **原文链接** | [http://arxiv.org/abs/2610.12106v1](http://arxiv.org/abs/2610.12106v1) |

**📝 摘要概括：**

> 水印大型语言模型在跟踪聊天机器人和代理输出方面很受欢迎，但检测器仍未发布，因为暴露它们可能会让攻击者根据检测器的反馈进行有针对性的编辑。然而，水印已经容易受到不知情的篡改攻击。这限制了提供商的责任，并质疑探测器完全隐私的必要性。

</details>

<details>
<summary><b>17. EvoAlloc: A Self-Evolving Resource Allocation Agent for Efficient Program Evolution</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Yanning Dai、Yuhui Wang、Nanbo Li、Wenyi Wang、Jürgen Schmidhuber |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、CAS |
| **发布时间** | 2026-10-08T14:57:35Z |
| **关键词** | `Benchmark` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2610.12086v1](http://arxiv.org/abs/2610.12086v1) |

**📝 摘要概括：**

> 基于LLM的课程进化依赖于评估反馈来指导高性能课程的迭代搜索。然而，评估通常在计算上昂贵，因此必须将有限的资源分配给能够最有效地推进搜索的候选人。此外，在相同的全面评估预算下， EvoAlloc的最终性能提高了8.7-12.0%。

</details>

<details>
<summary><b>18. When Should Agents Think? Adaptive Reasoning via Cross-Turn Estimation</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Yiruo Cheng、Shen Huang、Xiaoshuai Song、Jiejun Tan、Guanting Dong 等（共 8 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT |
| **发布时间** | 2026-10-08T14:43:09Z |
| **关键词** | `Agentic` · `Reasoning` · `Reinforcement Learning` · `Benchmark` · `Fine-tuning` |
| **原文链接** | [http://arxiv.org/abs/2610.12061v1](http://arxiv.org/abs/2610.12061v1) |

**📝 摘要概括：**

> 基于大型语言模型（ LLM ）的代理在复杂任务上表现出强大的能力。他们通常在整个互动轨迹的每个动作之前进行推理。在四个具有代表性的代理基准上的广泛实验表明， RACE大大降低了推理成本，同时保持或提高了任务绩效。

</details>

<details>
<summary><b>19. Examining Social Attribution in LLM Reasoning: A Theory-Guided Probing Methodology</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Zhaoxin Yu、Qingchao Kong、Dajun Zeng、Wenji Mao |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-10-08T14:20:06Z |
| **关键词** | `Reasoning` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2610.12022v1](http://arxiv.org/abs/2610.12022v1) |

**📝 摘要概括：**

> 大型语言模型（ LLM ）越来越多地部署在社会技术系统中，其中社会归因（将外部事件归因于代理人社会行为的原因和原因的推理过程）起着关键作用。这些过程涉及对社会事业、责任以及对客服代表的责任/信用的判断。数据集和相关代码可在https://github.com/Yuzhaoxin946/SAB-Bench上获得。

</details>

<details>
<summary><b>20. Agentic-TTT: Training test-time policy for test-time training</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Jiahao Lu、Mohan Kankanhalli |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-10-08T14:06:26Z |
| **关键词** | `Agentic` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2610.12002v1](http://arxiv.org/abs/2610.12002v1) |

**📝 摘要概括：**

> 测试时间培训（ TTT ）使用来自测试输入的信号来调整LLM的参数，并且可以在预先指定的设置（例如IMO比赛或指定的开放问题）中进行显着改进。通过将部署体验转化为参数更新， TTT提供了模型级自我提升的直接机制。总之，这些结果指向自主自我提升：可以决定如何从自己的模型中学习的模型……

</details>

## 🗄️ 历史归档

| 日期 | 论文数 | 报告链接 |
|------|--------|----------|
| 2026-10-10 | 20 篇 | [2026-10-10.md](daily/2026-10-10.md) |
| 2026-10-09 | 20 篇 | [2026-10-09.md](daily/2026-10-09.md) |
| 2026-10-08 | 20 篇 | [2026-10-08.md](daily/2026-10-08.md) |
| 2026-10-07 | 20 篇 | [2026-10-07.md](daily/2026-10-07.md) |
| 2026-10-06 | 0 篇 | [2026-10-06.md](daily/2026-10-06.md) |
| 2026-10-05 | 0 篇 | [2026-10-05.md](daily/2026-10-05.md) |
| 2026-10-04 | 0 篇 | [2026-10-04.md](daily/2026-10-04.md) |
| 2026-10-03 | 20 篇 | [2026-10-03.md](daily/2026-10-03.md) |
| 2026-10-02 | 15 篇 | [2026-10-02.md](daily/2026-10-02.md) |
| 2026-10-01 | 20 篇 | [2026-10-01.md](daily/2026-10-01.md) |
| 2026-09-30 | 8 篇 | [2026-09-30.md](daily/2026-09-30.md) |
| 2026-09-29 | 0 篇 | [2026-09-29.md](daily/2026-09-29.md) |
| 2026-09-15 | 16 篇 | [2026-09-15.md](daily/2026-09-15.md) |
| 2026-09-13 | 0 篇 | [2026-09-13.md](daily/2026-09-13.md) |
| 2026-09-12 | 0 篇 | [2026-09-12.md](daily/2026-09-12.md) |
| 2026-09-11 | 0 篇 | [2026-09-11.md](daily/2026-09-11.md) |
| 2026-09-10 | 8 篇 | [2026-09-10.md](daily/2026-09-10.md) |
| 2026-09-09 | 12 篇 | [2026-09-09.md](daily/2026-09-09.md) |
| 2026-09-08 | 0 篇 | [2026-09-08.md](daily/2026-09-08.md) |
| 2026-09-07 | 0 篇 | [2026-09-07.md](daily/2026-09-07.md) |
| 2026-09-06 | 0 篇 | [2026-09-06.md](daily/2026-09-06.md) |
| 2026-09-05 | 0 篇 | [2026-09-05.md](daily/2026-09-05.md) |
| 2026-09-04 | 20 篇 | [2026-09-04.md](daily/2026-09-04.md) |
| 2026-09-03 | 6 篇 | [2026-09-03.md](daily/2026-09-03.md) |
| 2026-09-02 | 20 篇 | [2026-09-02.md](daily/2026-09-02.md) |
| 2026-09-01 | 20 篇 | [2026-09-01.md](daily/2026-09-01.md) |
| 2026-08-31 | 0 篇 | [2026-08-31.md](daily/2026-08-31.md) |
| 2026-08-29 | 0 篇 | [2026-08-29.md](daily/2026-08-29.md) |
| 2026-08-28 | 20 篇 | [2026-08-28.md](daily/2026-08-28.md) |
| 2026-08-27 | 20 篇 | [2026-08-27.md](daily/2026-08-27.md) |

## 🏛️ 顶级机构覆盖范围

覆盖超过 **70 个**顶级 AI 机构，包括：

- **科技公司：** Microsoft、Google DeepMind、OpenAI、Anthropic、Meta AI、NVIDIA、Baidu、Alibaba、ByteDance 等
- **北美顶级大学：** MIT、Stanford、CMU、UC Berkeley、Harvard、Princeton、Cornell、Caltech 等
- **中国顶级大学/机构：** 清华大学、北京大学、浙大、上交大、复旦、中科院、MSRA 等
- **欧洲/其他：** Oxford、Cambridge、ETH Zurich、Mila、NUS、KAIST 等

---

*由 [clawBot DailyFindings](https://github.com/Jacob-biu/clawBot) 自动维护 | 最后更新：2026-10-10 01:31 UTC*
