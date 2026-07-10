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

## 📅 今日论文 — 2026-07-10　　[→ 查看完整报告](daily/2026-07-10.md)

> 共筛选出 **16** 篇论文 | 更新于 2026-07-10 22:59 UTC

### 论文目录与概要

| # | 论文标题 | 核心概要 | 来源机构 | 第一作者 |
|---|---------|---------|---------|--------|
| 1 | [Remember When It Matters: Proactive Memory Agent for Long-Ho…](http://arxiv.org/abs/2607.08716v1) | 在长期任务中，决策相关状态通常分散在不断扩展的轨迹上，而行动主体必须将其浮出水面并采取行动。随着轨迹的增长，任务要求、环境事实、先前的尝试、诊断和开放的子目标可能会被隐藏在上下文窗口中或超越上下文窗口… | TRI | Yifan Wu |
| 2 | [MPFlow: Learning Budgeted Max-Flow Optimization on the Light…](http://arxiv.org/abs/2607.08703v1) | 我们解决了比特币闪电网络（ LN ）中的流动性配置问题：给定固定预算，节点应打开哪些渠道以最大限度地提高其路由容量？我们将其描述为图上的预算受限组合优化问题，选择$ k $边加法，最大化$ s $ -… | CAS | Harrison Rush |
| 3 | [ProjAgent: Procedural Similarity Retrieval for Repository-Le…](http://arxiv.org/abs/2607.08691v1) | 存储库级代码生成需要实现目标函数，同时考虑复杂的跨文件依赖关系和项目特定约定。现有的检索方法主要依赖于词汇、结构或语义相似性，通常会忽略实现类似过程逻辑的存储库函数，尽管标识符或应用程序域不同。这些结… | Mila、TRI | QiHong Chen |
| 4 | [SolarChain-Eval: A Physics-Constrained Benchmark for Trustwo…](http://arxiv.org/abs/2607.08681v1) | 随着代理人工智能系统越来越多地应用于网络物理环境，它们的评估需要对任务性能和可信度进行评估。在分散的能源市场中，自主代理可能会提高市场效用，但也可能会利用无效的物理数据，创造人工流动性，并产生不稳定的… | FAIR、MIT | Shilin Ou |
| 5 | [WebSwarm: Recursive Multi-Agent Orchestration for Deep-and-W…](http://arxiv.org/abs/2607.08662v1) | 基于大型语言模型（ LLM ）的网络搜索代理正在将信息从简单的事实类问题回答转化为复杂、深入和广泛的搜索和面向研究的任务。单个ReAct风格的代理受限于一个长轨迹和有限的上下文，因此很难同时处理深度和… | MIT | Xiaoshuai Song |
| 6 | [Formal Mechanisms for Market Stability in Self-Interested Ag…](http://arxiv.org/abs/2607.08652v1) | 自私的代理人，不受约束，倾向于在反复出现的社会困境中叛逃，导致贸易合作收益崩溃。本文研究了在不受限制的沟通之上，哪些正式机制足以让这种代理商的社会维持市场稳定，以及这些机制对对抗性攻击的弹性。我们将对… | TRI | Eugene Ng Yi Sheng |
| 7 | [Multi-Modal, Multi-Environment Machine Teaching for Robust R…](http://arxiv.org/abs/2607.08647v1) | 随着自主代理越来越多地部署在不同的操作环境中，使其行为与人类意图保持一致需要奖励对这些变化保持鲁棒的功能，而不是过度拟合任何单一环境。反向强化学习（ IRL ）提供了一种从人类反馈中推断此类目标的原则… | MIT、TRI | Ali Larian |
| 8 | [SMetric: Rethink LLM Scheduling for Serving Agents with Bala…](http://arxiv.org/abs/2607.08565v1) | LLM调度对于服务至关重要，但目前尚不清楚现有设计是否适合代理服务-- LLM请求是由代理而不是人发出的。这以两种方式转移工作负载： （ 1 ）代理仅对完整响应采取行动，使集群的每秒令牌（ TPS ）… | TRI | Jiahao Wang |
| 9 | [Cognitive-structured Multimodal Agent for Multimodal Underst…](http://arxiv.org/abs/2607.08497v1) | 最近的统一多模态模型表明，单个架构可以联合执行视觉/语言理解和图像生成/编辑。然而，他们反复将所有历史视觉和文本输入输入到一个共享的上下文窗口中，由于视觉令牌爆炸和不可靠的交叉转向引用，限制了长时间的… | OpenAI、MIT | Feng Wang |
| 10 | [The Context Access Divide: Interaction-Level Architecture as…](http://arxiv.org/abs/2607.08495v1) | Sharp等人（ 2025 ）引入了“代理不平等”作为分析人工智能代理在可用性、质量和数量三个维度上的访问差异的框架。我们分析了模型上下文协议（ MCP ）和检索增强生成（ RAG ）架构中这种鸿沟的… | HIT、TRI | Masahiro Fujita |
| 11 | [ADORN: Adaptive Drift handling for Open RAN using Reinforcem…](http://arxiv.org/abs/2607.08443v1) | 开放无线电接入网络（ O-RAN ）中的动态流量变化会导致漂移，从而降低人工智能/机器学习（ AI/ML ）模型的性能。传统的再培训方法保持了预测的准确性，但会产生高昂的计算成本，并可能导致违反服务水… | MIT、CAS | Ashit Kumar Subudhi |
| 12 | [OmniFood-Bench: Evaluating VLMs for Nutrient Reasoning and P…](http://arxiv.org/abs/2607.08423v1) | 将大型视觉语言模型（ VLM ）快速集成到关键基础设施中，有望彻底改变个性化医疗保健和饮食管理。然而，在粮食系统领域，自主主体面临着一个独特而持久的挑战：视觉外观和内在营养成分之间的“系统信息不对称”… | TRI | Qian Jiang |
| 13 | [Game Theory Driven Multi-Agent Framework Mitigates Language …](http://arxiv.org/abs/2607.08403v1) | 轻量级大型语言模型在基于规则的科学领域的应用仍然受到严重限制，因为它们倾向于模仿语言模式而不是重现公理推理，从而导致频繁的幻觉。在这里，我们展示了G-Frame ，一个集成了贝叶斯和团队游戏原理的自适… | MIT、HIT | Runzhe Liu |
| 14 | [TRACE: A Two-Channel Robust Attribution Watermark via Comple…](http://arxiv.org/abs/2607.08400v1) | LLM代理通过经销商接触用户，经销商可能会重新命名开发商的代理或替换更便宜的模型。当来源有争议时，归因取决于轨迹日志（工具调用、观察和执行操作的记录，而不是模型的推理） ，经销商存储和处理该日志以计量… | TRI | Zheng Gao |
| 15 | [WCog-VLA: A Dual-Level World-Cognitive Vision-Language-Actio…](http://arxiv.org/abs/2607.08375v1) | 视觉语言行动（ VLA ）模型具有先进的端到端自动驾驶。然而，现有的方法要么缺乏全面的世界认知，要么缺乏碎片化的世界远见，这本质上将这些模型局限于被动驾驶。在NAVSIM基准上的大量实验表明， WCo… | MIT、CAS | Xuerun Yan |
| 16 | [Self-Adaptive Anomaly Detection with Reinforcement Learning …](http://arxiv.org/abs/2607.08373v1) | 联网车辆是自主网络物理系统，在运行过程中必须持续监控其行为，以便在其传播到故障之前检测与正常运行的偏差。这种评估具有挑战性，因为系统本身在不断发展：无线更新、配置更改和不断变化的工作负载改变了正常行为… | TRI | Matthias Weiß |

### 论文详情

<details>
<summary><b>1. Remember When It Matters: Proactive Memory Agent for Long-Horizon Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Yifan Wu、Lizhu Zhang、Yuhang Zhou、Mingyi Wang、Bo Peng 等（共 8 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-07-09T17:26:28Z |
| **关键词** | `Retrieval` · `Memory` |
| **原文链接** | [http://arxiv.org/abs/2607.08716v1](http://arxiv.org/abs/2607.08716v1) |

**📝 摘要概括：**

> 在长期任务中，决策相关状态通常分散在不断扩展的轨迹上，而行动主体必须将其浮出水面并采取行动。随着轨迹的增长，任务要求、环境事实、先前的尝试、诊断和开放的子目标可能会被隐藏在上下文窗口中或超越上下文窗口，无法在需要时影响决策。作为开放权重内存策略的早期步骤，我们使用SFT和GR在SETA上培训Qwen3.5-27B……

</details>

<details>
<summary><b>2. MPFlow: Learning Budgeted Max-Flow Optimization on the Lightning Network with Deep Graph Reinforcement Learning</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Harrison Rush、Vincent Davis、Simone Antonelli、Vikash Singh、Jesse Shrader 等（共 6 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | CAS |
| **发布时间** | 2026-07-09T17:09:20Z |
| **关键词** | `Reinforcement Learning` |
| **原文链接** | [http://arxiv.org/abs/2607.08703v1](http://arxiv.org/abs/2607.08703v1) |

**📝 摘要概括：**

> 我们解决了比特币闪电网络（ LN ）中的流动性配置问题：给定固定预算，节点应打开哪些渠道以最大限度地提高其路由容量？我们将其描述为图上的预算受限组合优化问题，选择$ k $边加法，最大化$ s $ -- $ t $ max-flow ，这是一种基于理论的路由容量度量，并用图强化学习解决。该代理已部署在生产环境中，用于同行……

</details>

<details>
<summary><b>3. ProjAgent: Procedural Similarity Retrieval for Repository-Level Code Generation</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | QiHong Chen、Aaron Imani、Iftekhar Ahmed |
| **所属机构** | （详见原文） |
| **顶级机构标签** | Mila、TRI |
| **发布时间** | 2026-07-09T16:50:54Z |
| **关键词** | `Agentic` · `Reasoning` · `Retrieval` · `Code Generation` · `Workflow` |
| **原文链接** | [http://arxiv.org/abs/2607.08691v1](http://arxiv.org/abs/2607.08691v1) |

**📝 摘要概括：**

> 存储库级代码生成需要实现目标函数，同时考虑复杂的跨文件依赖关系和项目特定约定。现有的检索方法主要依赖于词汇、结构或语义相似性，通常会忽略实现类似过程逻辑的存储库函数，尽管标识符或应用程序域不同。这些结果表明，程序相似性是一种有效的…

</details>

<details>
<summary><b>4. SolarChain-Eval: A Physics-Constrained Benchmark for Trustworthy Economic Agents in Decentralized Energy Markets</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Shilin Ou、Yifan Xu、Luyao Zhang |
| **所属机构** | （详见原文） |
| **顶级机构标签** | FAIR、MIT、TRI |
| **发布时间** | 2026-07-09T16:43:42Z |
| **关键词** | `Agentic` · `Benchmark` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2607.08681v1](http://arxiv.org/abs/2607.08681v1) |

**📝 摘要概括：**

> 随着代理人工智能系统越来越多地应用于网络物理环境，它们的评估需要对任务性能和可信度进行评估。在分散的能源市场中，自主代理可能会提高市场效用，但也可能会利用无效的物理数据，创造人工流动性，并产生不稳定的治理决策。我们在GitHub上将数据和代码作为开放访问发布，以实现可复制性。

</details>

<details>
<summary><b>5. WebSwarm: Recursive Multi-Agent Orchestration for Deep-and-Wide Web Search</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Xiaoshuai Song、Liancheng Zhang、Kangzhi Zhao、Yutao Zhu、Zhongyuan Wang 等（共 11 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT |
| **发布时间** | 2026-07-09T16:28:49Z |
| **关键词** | `Multi-Agent` · `Agentic` · `RAG` |
| **原文链接** | [http://arxiv.org/abs/2607.08662v1](http://arxiv.org/abs/2607.08662v1) |

**📝 摘要概括：**

> 基于大型语言模型（ LLM ）的网络搜索代理正在将信息从简单的事实类问题回答转化为复杂、深入和广泛的搜索和面向研究的任务。单个ReAct风格的代理受限于一个长轨迹和有限的上下文，因此很难同时处理深度和覆盖范围。对消融、任务难度、网络工具效率和模型泛化的进一步分析解释了WebSwar……

</details>

<details>
<summary><b>6. Formal Mechanisms for Market Stability in Self-Interested Agent Societies: A Marketplace Simulation Study</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Eugene Ng Yi Sheng、Bingquan Shen |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-07-09T16:21:16Z |
| **关键词** | `Multi-Agent` · `LLM Agent` · `Simulation` |
| **原文链接** | [http://arxiv.org/abs/2607.08652v1](http://arxiv.org/abs/2607.08652v1) |

**📝 摘要概括：**

> 自私的代理人，不受约束，倾向于在反复出现的社会困境中叛逃，导致贸易合作收益崩溃。本文研究了在不受限制的沟通之上，哪些正式机制足以让这种代理商的社会维持市场稳定，以及这些机制对对抗性攻击的弹性。我们将对抗鲁棒性定义为一种机制维持正面的能力……

</details>

<details>
<summary><b>7. Multi-Modal, Multi-Environment Machine Teaching for Robust Reward Learning</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Ali Larian、Qian Lin、Chang Zong Wu、Daniel S. Brown |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-07-09T16:18:16Z |
| **关键词** | `Reinforcement Learning` |
| **原文链接** | [http://arxiv.org/abs/2607.08647v1](http://arxiv.org/abs/2607.08647v1) |

**📝 摘要概括：**

> 随着自主代理越来越多地部署在不同的操作环境中，使其行为与人类意图保持一致需要奖励对这些变化保持鲁棒的功能，而不是过度拟合任何单一环境。反向强化学习（ IRL ）提供了一种从人类反馈中推断此类目标的原则性方法。根据经验，我们的方法大大降低了遗憾，并更强地概括了坚持不懈的环境……

</details>

<details>
<summary><b>8. SMetric: Rethink LLM Scheduling for Serving Agents with Balanced Session-centric Scheduling</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Jiahao Wang、Kaizhan Lin、Kaixi Zhang、Jinbo Han、Xingda Wei 等（共 10 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-07-09T14:55:02Z |
| **关键词** | `Agentic` |
| **原文链接** | [http://arxiv.org/abs/2607.08565v1](http://arxiv.org/abs/2607.08565v1) |

**📝 摘要概括：**

> LLM调度对于服务至关重要，但目前尚不清楚现有设计是否适合代理服务-- LLM请求是由代理而不是人发出的。这以两种方式转移工作负载： （ 1 ）代理仅对完整响应采取行动，使集群的每秒令牌（ TPS ）成为主要目标，并放松（而不是消除）每令牌延迟要求； （ 2 ）请求共享其大部分KV\ $重复使用超过80 ％的请求令牌……

</details>

<details>
<summary><b>9. Cognitive-structured Multimodal Agent for Multimodal Understanding, Generation, and Editing</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Feng Wang、Canmiao Fu、Zhipeng Huang、Chen Li、Jing Lyu 等（共 6 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | OpenAI、MIT、HIT |
| **发布时间** | 2026-07-09T13:55:55Z |
| **关键词** | `Reasoning` · `Planning` · `Reinforcement Learning` · `Retrieval` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2607.08497v1](http://arxiv.org/abs/2607.08497v1) |

**📝 摘要概括：**

> 最近的统一多模态模型表明，单个架构可以联合执行视觉/语言理解和图像生成/编辑。然而，他们反复将所有历史视觉和文本输入输入到一个共享的上下文窗口中，由于视觉令牌爆炸和不可靠的交叉转向引用，限制了长时间的多模式对话。代码： https://github.com/caseclose/cma-harness ；项目页面： https://caseclose.github.io/cma-har……

</details>

<details>
<summary><b>10. The Context Access Divide: Interaction-Level Architecture as a Complementary Dimension of Agentic Inequality</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Masahiro Fujita |
| **所属机构** | （详见原文） |
| **顶级机构标签** | HIT、TRI |
| **发布时间** | 2026-07-09T13:53:40Z |
| **关键词** | `AI Agent` · `Agentic` · `RAG` · `Retrieval` |
| **原文链接** | [http://arxiv.org/abs/2607.08495v1](http://arxiv.org/abs/2607.08495v1) |

**📝 摘要概括：**

> Sharp等人（ 2025 ）引入了“代理不平等”作为分析人工智能代理在可用性、质量和数量三个维度上的访问差异的框架。我们分析了模型上下文协议（ MCP ）和检索增强生成（ RAG ）架构中这种鸿沟的技术基础，并研究了其对知识工作分层和人工智能平台治理的影响。

</details>

<details>
<summary><b>11. ADORN: Adaptive Drift handling for Open RAN using Reinforcement Learning</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Ashit Kumar Subudhi、Bhargav Chirumamilla、Shubham Vaishnav、Mduduzi C. Hlophe、Praveen Kumar Donta 等（共 8 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、CAS |
| **发布时间** | 2026-07-09T13:05:42Z |
| **关键词** | `Reinforcement Learning` · `Memory` |
| **原文链接** | [http://arxiv.org/abs/2607.08443v1](http://arxiv.org/abs/2607.08443v1) |

**📝 摘要概括：**

> 开放无线电接入网络（ O-RAN ）中的动态流量变化会导致漂移，从而降低人工智能/机器学习（ AI/ML ）模型的性能。传统的再培训方法保持了预测的准确性，但会产生高昂的计算成本，并可能导致违反服务水平协议（ SLA ）。实验结果表明，与贪婪和贪婪相比，该方法有效地降低了再训练开销。

</details>

<details>
<summary><b>12. OmniFood-Bench: Evaluating VLMs for Nutrient Reasoning and Personalized Health Advice</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Qian Jiang、Zhecheng Shi、Jingpu Yang、Zirui Song、Miao Fang |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-07-09T12:46:00Z |
| **关键词** | `Reasoning` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2607.08423v1](http://arxiv.org/abs/2607.08423v1) |

**📝 摘要概括：**

> 将大型视觉语言模型（ VLM ）快速集成到关键基础设施中，有望彻底改变个性化医疗保健和饮食管理。然而，在粮食系统领域，自主主体面临着一个独特而持久的挑战：视觉外观和内在营养成分之间的“系统信息不对称”。代码和数据集可在以下网址获得： https://anonymous.4open.science/r/OmniFood-Ben……

</details>

<details>
<summary><b>13. Game Theory Driven Multi-Agent Framework Mitigates Language Model Hallucination</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Runzhe Liu、Biquan Bie、Zihao Wang、Yuchao Ma、Yexin Liu 等（共 10 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、HIT |
| **发布时间** | 2026-07-09T12:28:39Z |
| **关键词** | `Multi-Agent` · `Reasoning` · `Planning` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2607.08403v1](http://arxiv.org/abs/2607.08403v1) |

**📝 摘要概括：**

> 轻量级大型语言模型在基于规则的科学领域的应用仍然受到严重限制，因为它们倾向于模仿语言模式而不是重现公理推理，从而导致频繁的幻觉。在这里，我们展示了G-Frame ，一个集成了贝叶斯和团队游戏原理的自适应多智能体框架，为高质量的数据合成和模型训练建立了一个自动化的闭环。这项工作建立了……

</details>

<details>
<summary><b>14. TRACE: A Two-Channel Robust Attribution Watermark via Complementary Embeddings for LLM-Agent Trajectories</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Zheng Gao、Xiaoyu Li、Xiaoyan Feng、Jiaojiao Jiang、Yang Song 等（共 8 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-07-09T12:25:22Z |
| **关键词** | `LLM Agent` · `Reasoning` |
| **原文链接** | [http://arxiv.org/abs/2607.08400v1](http://arxiv.org/abs/2607.08400v1) |

**📝 摘要概括：**

> LLM代理通过经销商接触用户，经销商可能会重新命名开发商的代理或替换更便宜的模型。当来源有争议时，归因取决于轨迹日志（工具调用、观察和执行操作的记录，而不是模型的推理） ，经销商存储和处理该日志以计量使用情况。在ToolBench和ALFWorld上， TRACE匹配未水印代理的成功率，而其选择通道达到检测……

</details>

<details>
<summary><b>15. WCog-VLA: A Dual-Level World-Cognitive Vision-Language-Action Model for End-to-End Autonomous Driving</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Xuerun Yan、Zhexi Lian、Nuoheng Zhang、Shiyu Fang、Haoran Wang 等（共 8 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、CAS |
| **发布时间** | 2026-07-09T11:49:57Z |
| **关键词** | `Multi-Agent` · `Reasoning` · `RAG` · `Benchmark` · `Chain-of-Thought` |
| **原文链接** | [http://arxiv.org/abs/2607.08375v1](http://arxiv.org/abs/2607.08375v1) |

**📝 摘要概括：**

> 视觉语言行动（ VLA ）模型具有先进的端到端自动驾驶。然而，现有的方法要么缺乏全面的世界认知，要么缺乏碎片化的世界远见，这本质上将这些模型局限于被动驾驶。在NAVSIM基准上的大量实验表明， WCog-VLA达到了92.9的艺术状态（ SOTA ） PDMS分数。

</details>

<details>
<summary><b>16. Self-Adaptive Anomaly Detection with Reinforcement Learning and Human Feedback in Connected Vehicles</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Matthias Weiß、Athreya Hosahalli Prakash、Maurice Artelt、Falk Dettinger、Nasser Jazdi 等（共 6 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-07-09T11:48:52Z |
| **关键词** | `Reinforcement Learning` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2607.08373v1](http://arxiv.org/abs/2607.08373v1) |

**📝 摘要概括：**

> 联网车辆是自主网络物理系统，在运行过程中必须持续监控其行为，以便在其传播到故障之前检测与正常运行的偏差。这种评估具有挑战性，因为系统本身在不断发展：无线更新、配置更改和不断变化的工作负载改变了正常行为的定义，导致静态诊断方法随着时间的推移而无声地退化。跟随……

</details>

## 🗄️ 历史归档

| 日期 | 论文数 | 报告链接 |
|------|--------|----------|
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
| 2026-06-15 | 0 篇 | [2026-06-15.md](daily/2026-06-15.md) |
| 2026-06-14 | 0 篇 | [2026-06-14.md](daily/2026-06-14.md) |
| 2026-06-13 | 0 篇 | [2026-06-13.md](daily/2026-06-13.md) |
| 2026-06-12 | 20 篇 | [2026-06-12.md](daily/2026-06-12.md) |
| 2026-06-11 | 19 篇 | [2026-06-11.md](daily/2026-06-11.md) |

## 🏛️ 顶级机构覆盖范围

覆盖超过 **70 个**顶级 AI 机构，包括：

- **科技公司：** Microsoft、Google DeepMind、OpenAI、Anthropic、Meta AI、NVIDIA、Baidu、Alibaba、ByteDance 等
- **北美顶级大学：** MIT、Stanford、CMU、UC Berkeley、Harvard、Princeton、Cornell、Caltech 等
- **中国顶级大学/机构：** 清华大学、北京大学、浙大、上交大、复旦、中科院、MSRA 等
- **欧洲/其他：** Oxford、Cambridge、ETH Zurich、Mila、NUS、KAIST 等

---

*由 [clawBot DailyFindings](https://github.com/Jacob-biu/clawBot) 自动维护 | 最后更新：2026-07-10 22:59 UTC*
