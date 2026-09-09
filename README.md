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

## 📅 今日论文 — 2026-09-09　　[→ 查看完整报告](daily/2026-09-09.md)

> 共筛选出 **12** 篇论文 | 更新于 2026-09-09 23:50 UTC

### 论文目录与概要

| # | 论文标题 | 核心概要 | 来源机构 | 第一作者 |
|---|---------|---------|---------|--------|
| 1 | [Procedural Graphs: Self-Evolving Execution Structures for LL…](http://arxiv.org/abs/2609.09153v1) | 大型语言模型越来越多地被部署为长远规划并通过外部工具行事的代理。大多数客服代表在累积的历史中通过无约束的生成来选择行动，从而隐式地知道该做什么、按什么顺序做什么以及在什么条件下做什么。在多个数据集、任… | MIT、TRI | Yuxing Lu |
| 2 | [Co-Evolving Harnesses and Models: On-Policy Correction Helps…](http://arxiv.org/abs/2609.09134v1) | 代理利用（系统提示、工具集、执行挂钩和模型周围的上下文管理支架）是代理任务成功的关键决定因素。自动线束演进可以使较小的模型在特定领域的任务上表现良好，而成本仅为前沿模型的一小部分。我们的研究结果确定并… | MIT | Zhou Yu |
| 3 | [MeClear: Cooperative Game-Theoretic Attribution and Risk-Awa…](http://arxiv.org/abs/2609.09115v1) | Long horizon Large Language Model （ LLM ）代理依靠外部记忆系统在扩展交互中保留用户偏好和任务知识。传统的检索机制优化了语义兼容性，而不是下游实用性，经常将过时、… | TRI | Boyu Yang |
| 4 | [PlayTrain: An Efficient Reinforcement Learning Framework for…](http://arxiv.org/abs/2609.09059v1) | 虽然许多视频游戏环境（ VGE ）在推进强化学习（ RL ）、开发新型VGE或修改现有VGE以支持新功能方面发挥了关键作用，但这是一个艰巨的过程，需要大量的手工编码。在这里，我们介绍PlayTrain… | CAS | Ryan Truong |
| 5 | [Time-Varying Data as Sheaves: an Invitation to Narratives](http://arxiv.org/abs/2609.09056v1) | 现代科学和工程越来越依赖于时变数据，但用于模拟时间现象的数学工具通常是在不同的学科中开发的，模糊了共同的原则，并限制了跨领域的思想转移。本章介绍叙事理论，这是任何数学类型的时变对象的抽象框架，支持理论… | MIT | Wilmer Leal |
| 6 | [Omni Interaction Agent Technical Report](http://arxiv.org/abs/2609.08977v1) | 在这项工作中，我们介绍了Gander ，这是一种端到端模型，将全方位感知、实时交互和代理功能统一在一个框架中。与回合制传统范式相反， Gander通过多种模式（包括视频、语音和文本）持续接收流式输入，… | HIT | Orantqing |
| 7 | [PlannerForge: LLM Agents for Scenario-Based Testing of Motio…](http://arxiv.org/abs/2609.08965v1) | 确保自动驾驶的安全性是一项关键挑战。基于场景的测试是用于验证自动驾驶系统（ ADSS ）的系统过程，但它仍然是一个分散的模块化管道，其中场景生成、检索、修改、ADS执行和结果分析由单独的工具执行，几乎… | TRI | Yuan Gao |
| 8 | [SkillAdam: Stable and Efficient Skill Evolution for Agents](http://arxiv.org/abs/2609.08944v1) | 代理技能提供了一种轻量级的方式，为冷冻语言模型代理提供领域知识和程序指导，但获得高质量技能仍然昂贵且难以扩展。专家撰写的技能需要大量的人力。代码库： https://github.com/ruc-da… | CAS | Gaoyuan Li |
| 9 | [Closing the Consistency Gap: Self-Evolving Agents That Learn…](http://arxiv.org/abs/2609.08832v1) | 大型语言模型（ LLM ）支持的代理平均而言可能是准确的，但在生产中却不可靠，这种差异已经被观察到，但在很大程度上仍未得到解决。当给定相同的任务五次时，使用GPT-4.1的AppWorld基准上的Re… | MIT、Mila | Evelyn Duesterwald |
| 10 | [Hi-FLoop: Hierarchical State-Feedback Loops for Multi-Timesc…](http://arxiv.org/abs/2609.08796v1) | 多智能体交通模拟从地图和观察历史中寻找多样化、协调和物理上逼真的未来。长视野闭环生成必须协调多个决策时间尺度，同时其上下文随生成的状态而演变。在以代理为中心的oracle评估下， HI-FLOOP在8… | MIT、CAS | Rx Fan |
| 11 | [GoAnt: Quality-Diversity Multi-Agent Search for Alpha Factor…](http://arxiv.org/abs/2609.08719v1) | 自动阿尔法因子发现在固定的评估预算下从价格成交量面板和订单簿数据中搜索符号交易信号。现有的单代理和多代理程序搜索系统可能会过度拟合在执行成本后失败的预测代理，并反复探索冗余因子族，从而限制执行鲁棒性和… | MIT | Stella Zhao |
| 12 | [X2Streaming-ASR: wait when uncertain, emit when ready for st…](http://arxiv.org/abs/2609.08672v1) | 用于实时语音代理和全双工对话的流式自动语音识别（ ASR ）必须提供低提交延迟的准确部分转录。现有系统通常使用固定的块大小、前瞻或目标延迟，或鼓励在估计的声学边界附近排放。它在AISHELL-1和AI… | MIT | Zhiwei Lin |

### 论文详情

<details>
<summary><b>1. Procedural Graphs: Self-Evolving Execution Structures for LLM Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Yuxing Lu、Yicheng Chen、Shanchan Wu、Sercan Ö. Arık |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-09-08T17:59:41Z |
| **关键词** | `LLM Agent` · `RAG` · `Memory` |
| **原文链接** | [http://arxiv.org/abs/2609.09153v1](http://arxiv.org/abs/2609.09153v1) |

**📝 摘要概括：**

> 大型语言模型越来越多地被部署为长远规划并通过外部工具行事的代理。大多数客服代表在累积的历史中通过无约束的生成来选择行动，从而隐式地知道该做什么、按什么顺序做什么以及在什么条件下做什么。在多个数据集、任务类型和LLM中，程序图提供了基于内存基线的一致增益，以及自我进化……

</details>

<details>
<summary><b>2. Co-Evolving Harnesses and Models: On-Policy Correction Helps Weaker Models Catch Up Where Imitation Fails</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Zhou Yu、Bin Bi、Shiva Kumar Pentyala、Shubham Mehrotra、Sougata Chaudhuri 等（共 11 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT |
| **发布时间** | 2026-09-08T17:53:49Z |
| **关键词** | `Agentic` · `Planning` · `Fine-tuning` |
| **原文链接** | [http://arxiv.org/abs/2609.09134v1](http://arxiv.org/abs/2609.09134v1) |

**📝 摘要概括：**

> 代理利用（系统提示、工具集、执行挂钩和模型周围的上下文管理支架）是代理任务成功的关键决定因素。自动线束演进可以使较小的模型在特定领域的任务上表现良好，而成本仅为前沿模型的一小部分。我们的研究结果确定并解决了线束和重量更新之间的争议来源，为经济实惠的配方提供了兼容性保护。

</details>

<details>
<summary><b>3. MeClear: Cooperative Game-Theoretic Attribution and Risk-Aware Memory Clearance for Long-Horizon LLM Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Boyu Yang、Jiazheng Sun、Zilong Lu、Zhi Qiu、Xin Peng 等（共 6 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-09-08T17:46:00Z |
| **关键词** | `LLM Agent` · `Retrieval` · `Evaluation` · `Memory` |
| **原文链接** | [http://arxiv.org/abs/2609.09115v1](http://arxiv.org/abs/2609.09115v1) |

**📝 摘要概括：**

> Long horizon Large Language Model （ LLM ）代理依靠外部记忆系统在扩展交互中保留用户偏好和任务知识。传统的检索机制优化了语义兼容性，而不是下游实用性，经常将过时、误导或冲突的证据引入活动上下文。对十个长对话记忆池的全面实验评估表明， MeClear…

</details>

<details>
<summary><b>4. PlayTrain: An Efficient Reinforcement Learning Framework for LLM-Generated Adaptable JavaScript Games</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Ryan Truong、Lance Ying、Samuel J. Gershman、Kazuki Irie |
| **所属机构** | （详见原文） |
| **顶级机构标签** | CAS |
| **发布时间** | 2026-09-08T17:15:39Z |
| **关键词** | `Reinforcement Learning` |
| **原文链接** | [http://arxiv.org/abs/2609.09059v1](http://arxiv.org/abs/2609.09059v1) |

**📝 摘要概括：**

> 虽然许多视频游戏环境（ VGE ）在推进强化学习（ RL ）、开发新型VGE或修改现有VGE以支持新功能方面发挥了关键作用，但这是一个艰巨的过程，需要大量的手工编码。在这里，我们介绍PlayTrain ，这是一个RL框架，它结合了大型语言模型（ LLM ）的能力，从最小的人工提示和高效的管道中稳健地生成JavaScript （ JS ）游戏。

</details>

<details>
<summary><b>5. Time-Varying Data as Sheaves: an Invitation to Narratives</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Wilmer Leal、Benjamin Merlin Bumpus、Jana K. Nickel、Johan García、James Fairbanks 等（共 6 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT |
| **发布时间** | 2026-09-08T17:12:24Z |
| **关键词** | `Multi-Agent` |
| **原文链接** | [http://arxiv.org/abs/2609.09056v1](http://arxiv.org/abs/2609.09056v1) |

**📝 摘要概括：**

> 现代科学和工程越来越依赖于时变数据，但用于模拟时间现象的数学工具通常是在不同的学科中开发的，模糊了共同的原则，并限制了跨领域的思想转移。本章介绍叙事理论，这是任何数学类型的时变对象的抽象框架，支持理论调查和应用。更多信息…

</details>

<details>
<summary><b>6. Omni Interaction Agent Technical Report</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Orantqing、Shengpeng Ji、Junlong Tong、Jialong Zuo、Dongjie Fu 等（共 23 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | HIT |
| **发布时间** | 2026-09-08T16:22:23Z |
| **关键词** | `Agentic` · `Reasoning` · `Evaluation` · `Workflow` |
| **原文链接** | [http://arxiv.org/abs/2609.08977v1](http://arxiv.org/abs/2609.08977v1) |

**📝 摘要概括：**

> 在这项工作中，我们介绍了Gander ，这是一种端到端模型，将全方位感知、实时交互和代理功能统一在一个框架中。与回合制传统范式相反， Gander通过多种模式（包括视频、语音和文本）持续接收流式输入，从而在日常对话和复杂的工作流程座席场景中实现自然的全双工交互。我们释放甘德……

</details>

<details>
<summary><b>7. PlannerForge: LLM Agents for Scenario-Based Testing of Motion Planners in Autonomous Driving</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Yuan Gao、Sebastian Müller、Mattia Piccinini、Marc Kaufeld、Yuchen Zhang 等（共 8 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-09-08T16:19:06Z |
| **关键词** | `LLM Agent` · `Planning` · `RAG` · `Retrieval` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2609.08965v1](http://arxiv.org/abs/2609.08965v1) |

**📝 摘要概括：**

> 确保自动驾驶的安全性是一项关键挑战。基于场景的测试是用于验证自动驾驶系统（ ADSS ）的系统过程，但它仍然是一个分散的模块化管道，其中场景生成、检索、修改、ADS执行和结果分析由单独的工具执行，几乎没有交互。在N = 400时，成本调整将规划师的成功率从50.4%提高到70.2% ，并将碰撞从19…

</details>

<details>
<summary><b>8. SkillAdam: Stable and Efficient Skill Evolution for Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Gaoyuan Li、Meihao Fan、Yizhe Liu、Shaolei Zhang、Ju Fan 等（共 10 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | CAS |
| **发布时间** | 2026-09-08T16:04:45Z |
| **关键词** | `Benchmark` · `Memory` |
| **原文链接** | [http://arxiv.org/abs/2609.08944v1](http://arxiv.org/abs/2609.08944v1) |

**📝 摘要概括：**

> 代理技能提供了一种轻量级的方式，为冷冻语言模型代理提供领域知识和程序指导，但获得高质量技能仍然昂贵且难以扩展。专家撰写的技能需要大量的人力。代码库： https://github.com/ruc-datalab/SkillAdam

</details>

<details>
<summary><b>9. Closing the Consistency Gap: Self-Evolving Agents That Learn to Stay on Course</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Evelyn Duesterwald、Benjamin Elder、Lilian Ngweta、Shashanka Ubaru、Malgorzata Zimon |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、Mila |
| **发布时间** | 2026-09-08T14:53:43Z |
| **关键词** | `AI Agent` · `RAG` · `Benchmark` · `Evaluation` · `Memory` |
| **原文链接** | [http://arxiv.org/abs/2609.08832v1](http://arxiv.org/abs/2609.08832v1) |

**📝 摘要概括：**

> 大型语言模型（ LLM ）支持的代理平均而言可能是准确的，但在生产中却不可靠，这种差异已经被观察到，但在很大程度上仍未得到解决。当给定相同的任务五次时，使用GPT-4.1的AppWorld基准上的ReAct代理在所有五次运行中仅成功53 ％的时间，即使其每次运行通过率平均为77 ％。在带有ReAct/GPT-4.1的AppWorld上，我们的框架提高了所有成功任务的比例……

</details>

<details>
<summary><b>10. Hi-FLoop: Hierarchical State-Feedback Loops for Multi-Timescale World Modeling</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Rx Fan、Zhan H |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、CAS、TRI |
| **发布时间** | 2026-09-08T14:25:11Z |
| **关键词** | `Multi-Agent` · `Evaluation` · `Simulation` · `Memory` |
| **原文链接** | [http://arxiv.org/abs/2609.08796v1](http://arxiv.org/abs/2609.08796v1) |

**📝 摘要概括：**

> 多智能体交通模拟从地图和观察历史中寻找多样化、协调和物理上逼真的未来。长视野闭环生成必须协调多个决策时间尺度，同时其上下文随生成的状态而演变。在以代理为中心的oracle评估下， HI-FLOOP在8秒视野内达到1.196636米的oracle-minADE @ 8 ，在6秒视野内达到0.526米。

</details>

<details>
<summary><b>11. GoAnt: Quality-Diversity Multi-Agent Search for Alpha Factor Discovery in Market Microstructure Data</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Stella Zhao、Tommy Sha |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT |
| **发布时间** | 2026-09-08T13:19:18Z |
| **关键词** | `Multi-Agent` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2609.08719v1](http://arxiv.org/abs/2609.08719v1) |

**📝 摘要概括：**

> 自动阿尔法因子发现在固定的评估预算下从价格成交量面板和订单簿数据中搜索符号交易信号。现有的单代理和多代理程序搜索系统可能会过度拟合在执行成本后失败的预测代理，并反复探索冗余因子族，从而限制执行鲁棒性和行为多样性。其锁定人群在样品中保留了0.64和0.67的样品质量， ……

</details>

<details>
<summary><b>12. X2Streaming-ASR: wait when uncertain, emit when ready for streaming ASR</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Zhiwei Lin、Kaiqi Fu、Rime Wen、Zehan Liu、Shawn Qin 等（共 8 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT |
| **发布时间** | 2026-09-08T12:39:06Z |
| **关键词** | `RAG` |
| **原文链接** | [http://arxiv.org/abs/2609.08672v1](http://arxiv.org/abs/2609.08672v1) |

**📝 摘要概括：**

> 用于实时语音代理和全双工对话的流式自动语音识别（ ASR ）必须提供低提交延迟的准确部分转录。现有系统通常使用固定的块大小、前瞻或目标延迟，或鼓励在估计的声学边界附近排放。它在AISHELL-1和AISHELL-3的评估系统中实现了最佳的流式CER ，延迟大大降低。

</details>

## 🗄️ 历史归档

| 日期 | 论文数 | 报告链接 |
|------|--------|----------|
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
| 2026-08-25 | 12 篇 | [2026-08-25.md](daily/2026-08-25.md) |
| 2026-08-24 | 0 篇 | [2026-08-24.md](daily/2026-08-24.md) |
| 2026-08-23 | 0 篇 | [2026-08-23.md](daily/2026-08-23.md) |
| 2026-08-22 | 0 篇 | [2026-08-22.md](daily/2026-08-22.md) |
| 2026-08-21 | 15 篇 | [2026-08-21.md](daily/2026-08-21.md) |
| 2026-08-20 | 13 篇 | [2026-08-20.md](daily/2026-08-20.md) |
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

## 🏛️ 顶级机构覆盖范围

覆盖超过 **70 个**顶级 AI 机构，包括：

- **科技公司：** Microsoft、Google DeepMind、OpenAI、Anthropic、Meta AI、NVIDIA、Baidu、Alibaba、ByteDance 等
- **北美顶级大学：** MIT、Stanford、CMU、UC Berkeley、Harvard、Princeton、Cornell、Caltech 等
- **中国顶级大学/机构：** 清华大学、北京大学、浙大、上交大、复旦、中科院、MSRA 等
- **欧洲/其他：** Oxford、Cambridge、ETH Zurich、Mila、NUS、KAIST 等

---

*由 [clawBot DailyFindings](https://github.com/Jacob-biu/clawBot) 自动维护 | 最后更新：2026-09-09 23:50 UTC*
