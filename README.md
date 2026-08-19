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

## 📅 今日论文 — 2026-08-19　　[→ 查看完整报告](daily/2026-08-19.md)

> 共筛选出 **17** 篇论文 | 更新于 2026-08-19 22:22 UTC

### 论文目录与概要

| # | 论文标题 | 核心概要 | 来源机构 | 第一作者 |
|---|---------|---------|---------|--------|
| 1 | [On the Fragility of Self-Improving Agents: Variance, Task Or…](http://arxiv.org/abs/2608.18066v1) | 基于记忆的自我改善代理--那些从在线任务流中学习并通过维护文本记忆库而随着时间的推移而改进的代理--在最近的文献中显示出巨大的希望。然而，这些方法的可靠性方面被严重忽视。此外，我们关于低规格的研究结果… | TRI | Qinyuan Ye |
| 2 | [Delegation Asymmetry in Agentic Recommender Systems: Measuri…](http://arxiv.org/abs/2608.18058v1) | 代表用户交谈的自主LLM代理是匹配平台中新出现的设计模式，但其可行性取决于很少检查的条件：用户不仅必须接受将对话委托给代理，还必须接受来自其他人的代理中介通信。我们使用两项对主要约会平台活跃用户的大规… | TRI | Daria Leshchikova |
| 3 | [StagedWorkspace: A Versioned Workspace for Knowledge-Work Ag…](http://arxiv.org/abs/2608.18050v1) | 人工智能代理越来越多地执行知识工作（即生成和修改持久性数字工件，如代码存储库、文档、电子表格、幻灯片、报告） ，但他们搜索的解析视图、他们编辑的本机文件、他们查看的更改以及他们提交的工件可以引用同一工… | MIT | Yining Hua |
| 4 | [Policy-Invariant Reward Shaping from LLM Feedback: A Framewo…](http://arxiv.org/abs/2608.18008v1) | 将大型语言模型与强化学习相结合越来越受到探索，但LLM衍生奖励信号的理论状态往往是隐含的。我们将LLM-planner和RL-controller混合架构形式化为目标增强马尔可夫决策过程，并表明当LL… | HIT | Christophe D. Hounwanou |
| 5 | [EvoTS-Agent: A Self-Evolving LLM Agent for Financial Time Se…](http://arxiv.org/abs/2608.17933v1) | 金融时间序列表现出非平稳和异构的统计特性，使得变更点检测具有挑战性，因为没有单一的无监督算法在资产和市场制度中一致地执行。因此，传统工作流程在很大程度上依赖于专家驱动的模型选择、特征设计和超参数调整，… | MIT | Lei Jiang |
| 6 | [Collective Counterfactual Planning: Coordination, Consent, a…](http://arxiv.org/abs/2608.17932v1) | 小组通常会完成任何单个成员都无法单独计划、执行或验证的项目。我们提出了这种现象的正式模型，即集体反事实规划（ CCP ） ，其中每个代理的约束限制既不是能力，也不是知识，也不是可观察性，而是代表性几何… | MIT、TRI | Chainarong Amornbunchornvej |
| 7 | [A Theoretical Framework for Parallel Lifelong MAPF Using Gro…](http://arxiv.org/abs/2608.17928v1) | 在Lifelong Multi-Agent Path Finding （ L-MAPF ）问题中，座席必须反复从一个目的地移动到另一个目的地，同时避免障碍物和座席间碰撞。滚动地平线碰撞解决（ RHCR… | MIT、Mila | Alex DeWeese |
| 8 | [AutoResearch: Insight In, Hallucination Out](http://arxiv.org/abs/2608.17906v1) | 自主研究系统越来越能够执行长时间的研究工作流程，但仅靠自动化并不能确保由此产生的过程保持科学基础。我们引入了AutoResearch ，这是一个将创意生成与创意执行联系起来的两阶段系统，以解决研究创意… | TRI | Yiming Ren |
| 9 | [AdaLens: Interactive Storyline for Monitoring and Steering L…](http://arxiv.org/abs/2608.17834v1) | 大型语言模型正在将数据科学推向越来越自主和代理化的工作流程，最近的系统已经支持多步骤和长期运行的分析。随着这些工作流程变得更加自主，传统界面不再为两个关键要求提供足够的支持：理解客服代表不断发展的推理… | CAS | Yangtian Liu |
| 10 | [Debate Training Reduces Reward Hacking in RLAIF](http://arxiv.org/abs/2608.17776v1) | 我们证明，与从人工智能反馈（ RLAIF ）基线进行强化学习相比，使用辩论（由较弱的LLM法官裁定的生成者和批评者之间的双人对抗游戏）对LLM进行RL微调，可以减少奖励黑客攻击。奖励黑客是RLAIF的… | MIT、TRI | Zachary Kenton |
| 11 | [D$^2$ACCI: A Dual-Loop Diagnostic Protocol for Evidence-Pres…](http://arxiv.org/abs/2608.17756v1) | 内存是LLM代理的关键能力。持久记忆将此扩展到整个会话--启用召回、修改和个性化。这些结果表明，健壮的记忆系统迭代需要可追溯的、统计学上接地和回归感知的证据--正是差距D $ ^ 2 $ ACCI填补… | TRI | Xule Liu |
| 12 | [Beyond Suspicious Steps: Ontological Trust in Long-Horizon A…](http://arxiv.org/abs/2608.17718v1) | 远景代理越来越多地跨越许多步骤、工具和观察。在此设置中，相关的监督问题不仅是每个操作是否在本地有效，而且是不断变化的轨迹是否仍然对应于用户授权的任务。伪一致性更难：检测取决于任务完成是否在外部可见，这… | MIT | An He |
| 13 | [Cross-View Correspondence Is a Measurement Intervention: Two…](http://arxiv.org/abs/2608.17713v1) | 座席评估和基于跟踪的学习通常通过被视为中性预处理的回复后对应来比较转换后的视图中的输出。我们证明了这种对应是一种测量干预：省略它可以产生灵敏度，过度激进的映射可以产生不变性，多个最优对应可以留下机制标… | MIT、TRI | Zhen Zhang |
| 14 | [GADR: Gathering Architecture Decision Records from Meeting T…](http://arxiv.org/abs/2608.17694v1) | 现有的基于LLM的架构决策记录（ ADR ）生成方法共享一个关键且基本上未经审查的假设：该输入已经合理结构化。在实践中，建筑决策产生于非正式、嘈杂的会议，在这些会议中，选择是隐含的、支离破碎的，并且与… | HIT | Lucas Daniel Costa da Silva |
| 15 | [Benchmarking Automated Security Patch Backporting: How Far A…](http://arxiv.org/abs/2608.17671v1) | 自动安全补丁回移对于缓解N天的漏洞至关重要。最近的工具报告其各自数据集的成功率超过80%。可执行文件反馈细化可为最难的可执行文件提供有限但可衡量的恢复。 | MIT、CAS | Jincheng Yang |
| 16 | [GraphWake: Group Polarization via Memory-Mediated Polarizati…](http://arxiv.org/abs/2608.17665v1) | 由LLM驱动的代理可以在在线平台上自主交换意见并形成社区。这种智能体运营的社交平台引发了一个新的安全问题：攻击者可能会操纵智能体来诱发群体极化。这些发现揭示了社区层面的两极分化风险。 | CAS、TRI | Haoran Bu |
| 17 | [MobileWorldSafety: Benchmarking GUI Agent Safety Against Env…](http://arxiv.org/abs/2608.17659v1) | 自主操作智能手机的LLM驱动的GUI代理正在从研究原型迅速过渡到早期的真实世界部署。但是，由于这些药剂经常处理不可信的环境内容，因此它们非常容易受到环境注入攻击，包括间接提示注入和对抗性指令。Mobi… | CAS | Sujin Chen |

### 论文详情

<details>
<summary><b>1. On the Fragility of Self-Improving Agents: Variance, Task Order, and Underspecification</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Qinyuan Ye、Yu Li、Yada Pruksachatkun、Jiaxin Zhang、Chien-Sheng Wu |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-08-18T17:55:07Z |
| **关键词** | `RAG` · `Evaluation` · `Memory` |
| **原文链接** | [http://arxiv.org/abs/2608.18066v1](http://arxiv.org/abs/2608.18066v1) |

**📝 摘要概括：**

> 基于记忆的自我改善代理--那些从在线任务流中学习并通过维护文本记忆库而随着时间的推移而改进的代理--在最近的文献中显示出巨大的希望。然而，这些方法的可靠性方面被严重忽视。此外，我们关于低规格的研究结果要求系统和接口能够实现有效的人为监督，防止代理以不可预见的方式失败。

</details>

<details>
<summary><b>2. Delegation Asymmetry in Agentic Recommender Systems: Measuring Two-Sided Receptivity in Online Dating</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Daria Leshchikova、Valentina V. Kuskova、Dmitry Zaytsev、Valerii Klimov |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-08-18T17:51:16Z |
| **关键词** | `LLM Agent` · `Agentic` |
| **原文链接** | [http://arxiv.org/abs/2608.18058v1](http://arxiv.org/abs/2608.18058v1) |

**📝 摘要概括：**

> 代表用户交谈的自主LLM代理是匹配平台中新出现的设计模式，但其可行性取决于很少检查的条件：用户不仅必须接受将对话委托给代理，还必须接受来自其他人的代理中介通信。我们使用两项对主要约会平台活跃用户的大规模调查来研究这种情况（生成配置文件特征为N = 2,894 ；自主性为N = 2,617…

</details>

<details>
<summary><b>3. StagedWorkspace: A Versioned Workspace for Knowledge-Work Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Yining Hua、Hongbin Na、Yifan Zhou、Akshay Kalose、Cyrus Ayubcha 等（共 6 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT |
| **发布时间** | 2026-08-18T17:44:18Z |
| **关键词** | `AI Agent` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2608.18050v1](http://arxiv.org/abs/2608.18050v1) |

**📝 摘要概括：**

> 人工智能代理越来越多地执行知识工作（即生成和修改持久性数字工件，如代码存储库、文档、电子表格、幻灯片、报告） ，但他们搜索的解析视图、他们编辑的本机文件、他们查看的更改以及他们提交的工件可以引用同一工作产品的不同版本。我们将其制定为工作空间状态合同：每个视图都应明确绑定到……的版本

</details>

<details>
<summary><b>4. Policy-Invariant Reward Shaping from LLM Feedback: A Framework for Hybrid RL Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Christophe D. Hounwanou、John Emeka Eze、Yaé U. Gaba |
| **所属机构** | （详见原文） |
| **顶级机构标签** | HIT |
| **发布时间** | 2026-08-18T16:55:46Z |
| **关键词** | `Reinforcement Learning` |
| **原文链接** | [http://arxiv.org/abs/2608.18008v1](http://arxiv.org/abs/2608.18008v1) |

**📝 摘要概括：**

> 将大型语言模型与强化学习相结合越来越受到探索，但LLM衍生奖励信号的理论状态往往是隐含的。我们将LLM-planner和RL-controller混合架构形式化为目标增强马尔可夫决策过程，并表明当LLM每状态进度分数用作有界势函数时，即使LLM…

</details>

<details>
<summary><b>5. EvoTS-Agent: A Self-Evolving LLM Agent for Financial Time Series Change Point Detection</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Lei Jiang、Ye Wei、Xinyu Xi、Jordan Langham-Lopez、Yifan Bao 等（共 10 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT |
| **发布时间** | 2026-08-18T15:55:32Z |
| **关键词** | `LLM Agent` · `Benchmark` · `Workflow` |
| **原文链接** | [http://arxiv.org/abs/2608.17933v1](http://arxiv.org/abs/2608.17933v1) |

**📝 摘要概括：**

> 金融时间序列表现出非平稳和异构的统计特性，使得变更点检测具有挑战性，因为没有单一的无监督算法在资产和市场制度中一致地执行。因此，传统工作流程在很大程度上依赖于专家驱动的模型选择、特征设计和超参数调整，从而限制了其可扩展性和适应性。跨四个基准数据集的实验演示了……

</details>

<details>
<summary><b>6. Collective Counterfactual Planning: Coordination, Consent, and Verification under Representational Constraints</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Chainarong Amornbunchornvej |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-08-18T15:52:12Z |
| **关键词** | `Planning` · `Memory` |
| **原文链接** | [http://arxiv.org/abs/2608.17932v1](http://arxiv.org/abs/2608.17932v1) |

**📝 摘要概括：**

> 小组通常会完成任何单个成员都无法单独计划、执行或验证的项目。我们提出了这种现象的正式模型，即集体反事实规划（ CCP ） ，其中每个代理的约束限制既不是能力，也不是知识，也不是可观察性，而是代表性几何：每个代理感知状态，构思动作，同意行动，并仅通过对年龄的投影来证明目标要求……

</details>

<details>
<summary><b>7. A Theoretical Framework for Parallel Lifelong MAPF Using Group Decentralized Planning</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Alex DeWeese、Jiaoyang Li、Guannan Qu |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、Mila、TRI |
| **发布时间** | 2026-08-18T15:48:18Z |
| **关键词** | `Multi-Agent` · `Planning` · `RAG` |
| **原文链接** | [http://arxiv.org/abs/2608.17928v1](http://arxiv.org/abs/2608.17928v1) |

**📝 摘要概括：**

> 在Lifelong Multi-Agent Path Finding （ L-MAPF ）问题中，座席必须反复从一个目的地移动到另一个目的地，同时避免障碍物和座席间碰撞。滚动地平线碰撞解决（ RHCR ）框架被广泛认为是解决这一问题的最佳解决方案之一。最后，我们表明，在不同的地图中， GD-RHCR能够实现高吞吐量，可扩展到更高的座席数量，同时保持…

</details>

<details>
<summary><b>8. AutoResearch: Insight In, Hallucination Out</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Yiming Ren、Xiang Liu、Qumeng Sun、Xiao Zhang、Jiahao Li 等（共 7 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-08-18T15:38:26Z |
| **关键词** | `Retrieval` · `Benchmark` · `Workflow` |
| **原文链接** | [http://arxiv.org/abs/2608.17906v1](http://arxiv.org/abs/2608.17906v1) |

**📝 摘要概括：**

> 自主研究系统越来越能够执行长时间的研究工作流程，但仅靠自动化并不能确保由此产生的过程保持科学基础。我们引入了AutoResearch ，这是一个将创意生成与创意执行联系起来的两阶段系统，以解决研究创意是如何形成的，以及如何通过实验可靠地建立起来的。这些结果展示了一个研究过程，在这个过程中， …

</details>

<details>
<summary><b>9. AdaLens: Interactive Storyline for Monitoring and Steering Long-Running Agentic Data Analysis</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Yangtian Liu、Yan Miao、Shuhan Liu、Yunfan Zhou、Dae Hyun Kim 等（共 7 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | CAS |
| **发布时间** | 2026-08-18T14:34:45Z |
| **关键词** | `Agentic` · `Reasoning` · `Workflow` |
| **原文链接** | [http://arxiv.org/abs/2608.17834v1](http://arxiv.org/abs/2608.17834v1) |

**📝 摘要概括：**

> 大型语言模型正在将数据科学推向越来越自主和代理化的工作流程，最近的系统已经支持多步骤和长期运行的分析。随着这些工作流程变得更加自主，传统界面不再为两个关键要求提供足够的支持：理解客服代表不断发展的推理和证据的可观察性，以及重定向低价值方向或深化…

</details>

<details>
<summary><b>10. Debate Training Reduces Reward Hacking in RLAIF</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Zachary Kenton、Lili Janzer、Rory Greig、Tian Huey Teh、Kirill Tyshchuk 等（共 11 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-08-18T13:40:29Z |
| **关键词** | `Multi-Agent` · `Reinforcement Learning` |
| **原文链接** | [http://arxiv.org/abs/2608.17776v1](http://arxiv.org/abs/2608.17776v1) |

**📝 摘要概括：**

> 我们证明，与从人工智能反馈（ RLAIF ）基线进行强化学习相比，使用辩论（由较弱的LLM法官裁定的生成者和批评者之间的双人对抗游戏）对LLM进行RL微调，可以减少奖励黑客攻击。奖励黑客是RLAIF的核心障碍：随着培训的进展，该策略学会利用其AI判断中的系统错误，降低任务性能，这一问题在…

</details>

<details>
<summary><b>11. D$^2$ACCI: A Dual-Loop Diagnostic Protocol for Evidence-Preserving Agent Memory</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Xule Liu、Yijun Liu、Chao Li、Shao Kun |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-08-18T13:18:38Z |
| **关键词** | `LLM Agent` · `Retrieval` · `Benchmark` · `Evaluation` · `Memory` |
| **原文链接** | [http://arxiv.org/abs/2608.17756v1](http://arxiv.org/abs/2608.17756v1) |

**📝 摘要概括：**

> 内存是LLM代理的关键能力。持久记忆将此扩展到整个会话--启用召回、修改和个性化。这些结果表明，健壮的记忆系统迭代需要可追溯的、统计学上接地和回归感知的证据--正是差距D $ ^ 2 $ ACCI填补。

</details>

<details>
<summary><b>12. Beyond Suspicious Steps: Ontological Trust in Long-Horizon Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | An He、Yao Wang、Haibin Zhang |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT |
| **发布时间** | 2026-08-18T12:44:43Z |
| **关键词** | `RAG` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2608.17718v1](http://arxiv.org/abs/2608.17718v1) |

**📝 摘要概括：**

> 远景代理越来越多地跨越许多步骤、工具和观察。在此设置中，相关的监督问题不仅是每个操作是否在本地有效，而且是不断变化的轨迹是否仍然对应于用户授权的任务。伪一致性更难：检测取决于任务完成是否在外部可见，这是我们根据经验描述的结构限制。

</details>

<details>
<summary><b>13. Cross-View Correspondence Is a Measurement Intervention: Two-Sided Validation for Agent Evaluation and Credit Assignment</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Zhen Zhang、Ahmad Hafez、Amr Alanwar |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-08-18T12:39:21Z |
| **关键词** | `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2608.17713v1](http://arxiv.org/abs/2608.17713v1) |

**📝 摘要概括：**

> 座席评估和基于跟踪的学习通常通过被视为中性预处理的回复后对应来比较转换后的视图中的输出。我们证明了这种对应是一种测量干预：省略它可以产生灵敏度，过度激进的映射可以产生不变性，多个最优对应可以留下机制标签和签名学习信用未识别。跨视图对应…

</details>

<details>
<summary><b>14. GADR: Gathering Architecture Decision Records from Meeting Transcriptions</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Lucas Daniel Costa da Silva、Kiev Gama |
| **所属机构** | （详见原文） |
| **顶级机构标签** | HIT |
| **发布时间** | 2026-08-18T12:11:42Z |
| **关键词** | `Multi-Agent` · `Agentic` · `RAG` · `Evaluation` · `Workflow` |
| **原文链接** | [http://arxiv.org/abs/2608.17694v1](http://arxiv.org/abs/2608.17694v1) |

**📝 摘要概括：**

> 现有的基于LLM的架构决策记录（ ADR ）生成方法共享一个关键且基本上未经审查的假设：该输入已经合理结构化。在实践中，建筑决策产生于非正式、嘈杂的会议，在这些会议中，选择是隐含的、支离破碎的，并且与偏离主题的对话纠缠在一起，这正是单通道提示退化的条件。该研究还解决了未充分探索的权衡……

</details>

<details>
<summary><b>15. Benchmarking Automated Security Patch Backporting: How Far Are We?</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Jincheng Yang、Yulong Fu、Chengwei Liu、Lyuye Zhang、Fangyuan Zhang 等（共 8 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、CAS |
| **发布时间** | 2026-08-18T11:43:10Z |
| **关键词** | `LLM Agent` · `Benchmark` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2608.17671v1](http://arxiv.org/abs/2608.17671v1) |

**📝 摘要概括：**

> 自动安全补丁回移对于缓解N天的漏洞至关重要。最近的工具报告其各自数据集的成功率超过80%。可执行文件反馈细化可为最难的可执行文件提供有限但可衡量的恢复。

</details>

<details>
<summary><b>16. GraphWake: Group Polarization via Memory-Mediated Polarization Cascade in LLM-Agent Communities</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Haoran Bu、Zejian Chen、Litian Zhang、Xi Zhang |
| **所属机构** | （详见原文） |
| **顶级机构标签** | CAS、TRI |
| **发布时间** | 2026-08-18T11:38:56Z |
| **关键词** | `Retrieval` · `Memory` |
| **原文链接** | [http://arxiv.org/abs/2608.17665v1](http://arxiv.org/abs/2608.17665v1) |

**📝 摘要概括：**

> 由LLM驱动的代理可以在在线平台上自主交换意见并形成社区。这种智能体运营的社交平台引发了一个新的安全问题：攻击者可能会操纵智能体来诱发群体极化。这些发现揭示了社区层面的两极分化风险。

</details>

<details>
<summary><b>17. MobileWorldSafety: Benchmarking GUI Agent Safety Against Environmental Injection Attacks in Android Apps</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Sujin Chen、Lijun Li、Tianyi Du、Jing Shao |
| **所属机构** | （详见原文） |
| **顶级机构标签** | CAS |
| **发布时间** | 2026-08-18T11:33:22Z |
| **关键词** | `Benchmark` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2608.17659v1](http://arxiv.org/abs/2608.17659v1) |

**📝 摘要概括：**

> 自主操作智能手机的LLM驱动的GUI代理正在从研究原型迅速过渡到早期的真实世界部署。但是，由于这些药剂经常处理不可信的环境内容，因此它们非常容易受到环境注入攻击，包括间接提示注入和对抗性指令。MobileWorldSafety为量化这些漏洞和推进……提供了基础

</details>

## 🗄️ 历史归档

| 日期 | 论文数 | 报告链接 |
|------|--------|----------|
| 2026-08-19 | 17 篇 | [2026-08-19.md](daily/2026-08-19.md) |
| 2026-08-18 | 20 篇 | [2026-08-18.md](daily/2026-08-18.md) |
| 2026-08-17 | 0 篇 | [2026-08-17.md](daily/2026-08-17.md) |
| 2026-08-16 | 0 篇 | [2026-08-16.md](daily/2026-08-16.md) |
| 2026-08-15 | 0 篇 | [2026-08-15.md](daily/2026-08-15.md) |
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

## 🏛️ 顶级机构覆盖范围

覆盖超过 **70 个**顶级 AI 机构，包括：

- **科技公司：** Microsoft、Google DeepMind、OpenAI、Anthropic、Meta AI、NVIDIA、Baidu、Alibaba、ByteDance 等
- **北美顶级大学：** MIT、Stanford、CMU、UC Berkeley、Harvard、Princeton、Cornell、Caltech 等
- **中国顶级大学/机构：** 清华大学、北京大学、浙大、上交大、复旦、中科院、MSRA 等
- **欧洲/其他：** Oxford、Cambridge、ETH Zurich、Mila、NUS、KAIST 等

---

*由 [clawBot DailyFindings](https://github.com/Jacob-biu/clawBot) 自动维护 | 最后更新：2026-08-19 22:22 UTC*
