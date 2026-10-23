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

## 📅 今日论文 — 2026-10-23　　[→ 查看完整报告](daily/2026-10-23.md)

> 共筛选出 **20** 篇论文 | 更新于 2026-10-23 00:25 UTC

### 论文目录与概要

| # | 论文标题 | 核心概要 | 来源机构 | 第一作者 |
|---|---------|---------|---------|--------|
| 1 | [The End of Consensus Research?](http://arxiv.org/abs/2610.30114v1) | 共识是分布式计算中的一个基本问题，也是状态机复制（ SMR ）的核心。尽管人类进行了数十年的积极研究，但发现该问题的实用低延迟解决方案仍然是开放的，因为它需要结合协议知识、正确性推理、实施和实验评估。… | CAS、TRI | Clément Burgelin |
| 2 | [Quant-Arena: Benchmarking LLM Agents for Quantitative Tradin…](http://arxiv.org/abs/2610.30113v1) | 定量研究是一个迭代循环：研究人员提出一个市场假设，将其作为可执行信号实施，在历史数据上进行测试，并决定保留什么。现有基准对公式、代码或个人交易决策进行评分，大型语言模型（ LLM ）是否可以完成此循环… | CAS | Houde Qian |
| 3 | [Multimodal Embodied Agents: A Unified Capability-centric Per…](http://arxiv.org/abs/2610.30108v1) | 多模态代理（ MMA ）通过推理、记忆、工具和反馈来维持互动，最明显的是作为计算机使用代理，而机器人系统（ RS ）在物理动力学下耦合传感和驱动。我们将多模态具体化代理（ MMEA ）定义为目标导向系… | HIT、TRI | Yanzhe Chen |
| 4 | [Asymmetric On-Policy Distillation Learns In-Context Explorat…](http://arxiv.org/abs/2610.30105v1) | 在部分可观察性下，顺序决策是困难的，因为代理必须探索推断隐藏的、与任务相关的信息，然后才能有效地采取行动。通过在线强化学习学习这种信息收集行为表格效率低下，而离线模仿则在隐藏状态下平均专家行动，无法学… | MIT、Mila | Sriyash Poddar |
| 5 | [Circuits of LLM Classifiers](http://arxiv.org/abs/2610.30076v1) | 通过简单地提示带有样本的模型进行分类，语言模型可以轻松构建分类器。然而，他们的预测在样本中既不是确定性的，也不是一致可靠的。我们的方法跨越安全、健康、政治科学、人类偏好、代理评估、决策和推理等七个分类… | MIT、CAS | Hadi Khalaf |
| 6 | [Parallel AI Agent Collaboration as Graph-Structured Distribu…](http://arxiv.org/abs/2610.30074v1) | 并行AI代理可以生成有用的本地编辑，但在合并编辑时会降低共享解决方案的性能。我们将这个协调问题建模为具有精确可评估目标和已知依赖关系图的离散块优化。对于共享车辆路线独家访问权限的路线搜索代理，分数调度… | TRI | Hanmin Li |
| 7 | [Charts as Epistemic Actions for Experience-Driven Agentic Da…](http://arxiv.org/abs/2610.30072v1) | 基于ReAct风格循环构建的数据代理现在可以在结构化数据上执行复杂的分析工作流，但它们的中间推理仍然几乎完全通过文本运行。相反，人类分析师在数字、表格和图表之间移动，阅读视觉证据，以揭示文本摘要掉落的… | MIT | Xinzhe Wang |
| 8 | [SWE-DIVE: Multi-Turn Coding Agent Evaluation with Dynamic Us…](http://arxiv.org/abs/2610.30047v1) | 编码代理通常使用一次性、精心设计的提示进行评估。SWE-bench等基准使用现有的GitHub问题作为编码代理的输入，并评估代理是否成功解决了任务。我们的结果和源代码可在我们的GitHub存储库（ h… | MIT、CAS | Lorenz Brehme |
| 9 | [HGM-Dual: Lineage-Aware Guided Agent Harness Optimization fo…](http://arxiv.org/abs/2610.30042v1) | 线束优化可改善客服代表的提示、工具和工作流程，是增强基于冻结或闭源LLM构建的客服代表的一种越来越有效的方法。Darwin--Godel Machine和Huxley--Godel Machine （… | CAS、TRI | Sudipta Paul |
| 10 | [Robust Soft Skill Adaptation via Behavioral Localization in …](http://arxiv.org/abs/2610.30041v1) | 文本技能可以扩展使用工具的代理的功能，但冗长的技能描述会增加计算成本。软提示提供了一个紧凑的替代方案，但从整个成功轨迹中学习也可能引入不必要的行为改变。这些结果表明，一小部分与行为相关的轨迹位置可以提… | TRI | Zijian Jiang |
| 11 | [What the Author Wrote, What the Agent Reads: Silent Cue Loss…](http://arxiv.org/abs/2610.30026v1) | 企业代理根据文档执行操作。在代理可以遵循策略、回答合规性问题或提交工单之前，某些接收层必须将Word文件或PDF转换为令牌-该层是部署在野外的代理静默丢失信息的地方。对于代理构建者来说，实际发现是，摄… | OpenAI、TRI | Yikai Zhao |
| 12 | [GuideEvolve: Self-Evolving Agent Framework with Expert Guida…](http://arxiv.org/abs/2610.30017v1) | 本研究介绍了GuideEvolve ，这是一个自我发展的代理框架，结合了专家指导和三种自主监管机制，统称为3T ： Think Fast and Slow、Throwback和Termination … | MIT、TRI | Meihong Jia |
| 13 | [Agent Behavior Maps: Locating Agents by What They Would Do, …](http://arxiv.org/abs/2610.30014v1) | 具有相似成功率的LLM代理可以遵循不同的操作序列。Agent Behavior Map代表LLM-harness组合，使用共享参考轨迹上的居中操作日志可能性，而不需要目标Agent推出新的环境。作为扩… | Mila | Shota Fujikawa |
| 14 | [CORD: Conflict-Aware Optimization for Joint RL and Distillat…](http://arxiv.org/abs/2610.29965v1) | 联合强化学习和自馏将任务奖励与密集的教师指导相结合，用于代理培训，但它们的梯度可以部分取消。混合系数控制相对比例，而不选择性地去除相对的成分。我们的分析解释了为什么必须一起选择保护方向和投影闸门，以及… | TRI | Wenhao Yu |
| 15 | [FrontierCS 2: A Benchmark for Computer Science R&D](http://arxiv.org/abs/2610.29932v1) | 法学硕士代理能否为前沿计算机科学研发做出贡献？我们引入了FrontierCS 2 ，这是48个开放式任务的基准。在客服代表和任务的共享能力量表中，任务中位数与最强的客服代表所能处理的任务大致相同。 | MIT、TRI | Qiuyang Mang |
| 16 | [Automated Materials Data and Knowledge Extraction using Mach…](http://arxiv.org/abs/2610.29895v1) | 在过去的十年中，我们一直致力于开发机器学习（ ML ）方法，用于直接从科学文献中提取材料数据，并在可能的情况下提取材料知识。本综述追溯了这些方法从启发式、基于规则的管道到自然语言处理（ NLP ）模型… | MIT | Aravindan Kamatchi Sundaram |
| 17 | [PAUSE: Search-Free Steering of Coding Agents Before Their Fi…](http://arxiv.org/abs/2610.29870v1) | 编码代理可以在存储库探索和测试方面投入大量精力，但仍然会产生不成功的补丁。现有的在线指导方法定期审查轨迹，或者在监控人员检测到行为问题时调用顾问；频繁的审查代价高昂，没有异常行为并不意味着客服代表走在… | Mila、TRI | Viral Patel |
| 18 | [Real PMIDs, Wrong Papers: Harness Design for Biomedical Clai…](http://arxiv.org/abs/2610.29812v1) | 文献搜索语言代理正在成为生命科学科学助手的标准组成部分，但很少有受控的证据表明它们的哪些部分是重要的。我们使用实时PubMed API作为唯一工具，对生物医学索赔验证（ SciFact ）进行受控消融… | TRI | Mohammed Saqlain |
| 19 | [Retrieval Augmented Generation Compositionality](http://arxiv.org/abs/2610.29722v1) | 检索增强生成（ RAG ）基于外部知识中的大型语言模型。现代管道结合了嵌入、分块、检索、重新排序、查询增强、上下文压缩和代理验证，但这些技术通常一次评估一个。我们呼吁研究人员这样做，并提供千层面来简化… | TRI | Ido Levy |
| 20 | [Toward Recursive Self-Improvement in Physical AI](http://arxiv.org/abs/2610.29677v1) | 递归自我改善（ RSI ）描述了一个不仅可以改善其行为，还可以改善其改进过程的系统。最近的数字代理通过重写自己的代码并通过可执行测试检查每个版本来测试这个想法。我们将这些发现综合到机器的评估原则和研究… | TRI | Meng Luo |

### 论文详情

<details>
<summary><b>1. The End of Consensus Research?</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Clément Burgelin、Rachid Guerraoui、Zicong Hong、Yinan Hu、Anne-Marie Kermarrec 等（共 8 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | CAS、TRI |
| **发布时间** | 2026-10-21T17:55:19Z |
| **关键词** | `Reasoning` · `RAG` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2610.30114v1](http://arxiv.org/abs/2610.30114v1) |

**📝 摘要概括：**

> 共识是分布式计算中的一个基本问题，也是状态机复制（ SMR ）的核心。尽管人类进行了数十年的积极研究，但发现该问题的实用低延迟解决方案仍然是开放的，因为它需要结合协议知识、正确性推理、实施和实验评估。然而，我们认为，人类共识专家在搜索之前、期间和之后仍然是必不可少的： agent resha……

</details>

<details>
<summary><b>2. Quant-Arena: Benchmarking LLM Agents for Quantitative Trading Research</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Houde Qian、Zheng Jiang、Wenyi Li、Chenxi Xu、Xinjie Lin 等（共 12 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | CAS |
| **发布时间** | 2026-10-21T17:54:01Z |
| **关键词** | `LLM Agent` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2610.30113v1](http://arxiv.org/abs/2610.30113v1) |

**📝 摘要概括：**

> 定量研究是一个迭代循环：研究人员提出一个市场假设，将其作为可执行信号实施，在历史数据上进行测试，并决定保留什么。现有基准对公式、代码或个人交易决策进行评分，大型语言模型（ LLM ）是否可以完成此循环并产生超出研究期的策略。Quant-Arena开放供任何模特或代理商提交……

</details>

<details>
<summary><b>3. Multimodal Embodied Agents: A Unified Capability-centric Perspective from Computer-Use to Robot-Use</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Yanzhe Chen、Ziyi Yang、Jifeng Zhu、Qiming Huang、Ruihe An 等（共 17 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | HIT、TRI |
| **发布时间** | 2026-10-21T17:52:48Z |
| **关键词** | `Reasoning` · `Benchmark` · `Evaluation` · `Embodied AI` · `Memory` |
| **原文链接** | [http://arxiv.org/abs/2610.30108v1](http://arxiv.org/abs/2610.30108v1) |

**📝 摘要概括：**

> 多模态代理（ MMA ）通过推理、记忆、工具和反馈来维持互动，最明显的是作为计算机使用代理，而机器人系统（ RS ）在物理动力学下耦合传感和驱动。我们将多模态具体化代理（ MMEA ）定义为目标导向系统，该系统将多模态任务推理与物理操作相结合，并根据由此产生的反馈修改决策。因此， PAPAV为设计Relia提供了一个共同的基础……

</details>

<details>
<summary><b>4. Asymmetric On-Policy Distillation Learns In-Context Exploration</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Sriyash Poddar、Yanda Bao、Jacob Krantz、Matthew Chang、Xavier Puig 等（共 8 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、Mila |
| **发布时间** | 2026-10-21T17:50:31Z |
| **关键词** | `Reinforcement Learning` · `RAG` · `Benchmark` · `Simulation` |
| **原文链接** | [http://arxiv.org/abs/2610.30105v1](http://arxiv.org/abs/2610.30105v1) |

**📝 摘要概括：**

> 在部分可观察性下，顺序决策是困难的，因为代理必须探索推断隐藏的、与任务相关的信息，然后才能有效地采取行动。通过在线强化学习学习这种信息收集行为表格效率低下，而离线模仿则在隐藏状态下平均专家行动，无法学习探索。总的来说，它提供了一个简单但令人惊讶的有效框架……

</details>

<details>
<summary><b>5. Circuits of LLM Classifiers</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Hadi Khalaf、Sajani Vithana、Kunal Talreja、Haewon Jeong、Viveck R. Cadambe 等（共 6 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、CAS |
| **发布时间** | 2026-10-21T17:27:46Z |
| **关键词** | `Reasoning` · `RAG` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2610.30076v1](http://arxiv.org/abs/2610.30076v1) |

**📝 摘要概括：**

> 通过简单地提示带有样本的模型进行分类，语言模型可以轻松构建分类器。然而，他们的预测在样本中既不是确定性的，也不是一致可靠的。我们的方法跨越安全、健康、政治科学、人类偏好、代理评估、决策和推理等七个分类任务，提高了成本准确性前沿，超过了路由和级联基线。

</details>

<details>
<summary><b>6. Parallel AI Agent Collaboration as Graph-Structured Distributed Block Optimization</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Hanmin Li、Yury Demidovich、Peter Richtárik |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-10-21T17:27:17Z |
| **关键词** | `AI Agent` |
| **原文链接** | [http://arxiv.org/abs/2610.30074v1](http://arxiv.org/abs/2610.30074v1) |

**📝 摘要概括：**

> 并行AI代理可以生成有用的本地编辑，但在合并编辑时会降低共享解决方案的性能。我们将这个协调问题建模为具有精确可评估目标和已知依赖关系图的离散块优化。对于共享车辆路线独家访问权限的路线搜索代理，分数调度将12次配对运行的测量墙壁时间减少了15%的中位数，路线成本变化因运行而异。

</details>

<details>
<summary><b>7. Charts as Epistemic Actions for Experience-Driven Agentic Data Analysis</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Xinzhe Wang、Xudong Weng、Zang Li、Shaolei Zhang |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT |
| **发布时间** | 2026-10-21T17:26:53Z |
| **关键词** | `Agentic` · `Reasoning` · `Benchmark` · `Workflow` |
| **原文链接** | [http://arxiv.org/abs/2610.30072v1](http://arxiv.org/abs/2610.30072v1) |

**📝 摘要概括：**

> 基于ReAct风格循环构建的数据代理现在可以在结构化数据上执行复杂的分析工作流，但它们的中间推理仍然几乎完全通过文本运行。相反，人类分析师在数字、表格和图表之间移动，阅读视觉证据，以揭示文本摘要掉落的趋势和异常。在具有四个LLM骨干的三个公开基准上，\ method {}提高了分析准确性和视觉证据质量。

</details>

<details>
<summary><b>8. SWE-DIVE: Multi-Turn Coding Agent Evaluation with Dynamic User Simulation</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Lorenz Brehme、Benjamin Steenhoek、Ruth Breu |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、CAS |
| **发布时间** | 2026-10-21T17:06:34Z |
| **关键词** | `Benchmark` · `Evaluation` · `Simulation` |
| **原文链接** | [http://arxiv.org/abs/2610.30047v1](http://arxiv.org/abs/2610.30047v1) |

**📝 摘要概括：**

> 编码代理通常使用一次性、精心设计的提示进行评估。SWE-bench等基准使用现有的GitHub问题作为编码代理的输入，并评估代理是否成功解决了任务。我们的结果和源代码可在我们的GitHub存储库（ https://github.com/lorenzbrehme/swe-dive_usersim ）中找到。

</details>

<details>
<summary><b>9. HGM-Dual: Lineage-Aware Guided Agent Harness Optimization for Long-Horizon Planning</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Sudipta Paul、Pengrui Quan、Aounon Kumar、Nicholas Tzou、Vivek Kulkarni 等（共 6 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | CAS、TRI |
| **发布时间** | 2026-10-21T17:02:28Z |
| **关键词** | `Planning` · `Evaluation` · `Workflow` |
| **原文链接** | [http://arxiv.org/abs/2610.30042v1](http://arxiv.org/abs/2610.30042v1) |

**📝 摘要概括：**

> 线束优化可改善客服代表的提示、工具和工作流程，是增强基于冻结或闭源LLM构建的客服代表的一种越来越有效的方法。Darwin--Godel Machine和Huxley--Godel Machine （ HGM ）等领先方法依赖于递归自我改进，主要用于编码，其中改进代理所需的能力与提高的能力相吻合。HGM-Dual的表现优于……

</details>

<details>
<summary><b>10. Robust Soft Skill Adaptation via Behavioral Localization in Tool-Using Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Zijian Jiang、Xilu Wang |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-10-21T17:02:06Z |
| **关键词** | — |
| **原文链接** | [http://arxiv.org/abs/2610.30041v1](http://arxiv.org/abs/2610.30041v1) |

**📝 摘要概括：**

> 文本技能可以扩展使用工具的代理的功能，但冗长的技能描述会增加计算成本。软提示提供了一个紧凑的替代方案，但从整个成功轨迹中学习也可能引入不必要的行为改变。这些结果表明，一小部分与行为相关的轨迹位置可以提供对软技能的有效监督。

</details>

<details>
<summary><b>11. What the Author Wrote, What the Agent Reads: Silent Cue Loss in Enterprise Document Ingestion</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Yikai Zhao、Saurabh Pandey、Pradeep Kumar Misra |
| **所属机构** | （详见原文） |
| **顶级机构标签** | OpenAI、TRI |
| **发布时间** | 2026-10-21T16:51:25Z |
| **关键词** | `Reasoning` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2610.30026v1](http://arxiv.org/abs/2610.30026v1) |

**📝 摘要概括：**

> 企业代理根据文档执行操作。在代理可以遵循策略、回答合规性问题或提交工单之前，某些接收层必须将Word文件或PDF转换为令牌-该层是部署在野外的代理静默丢失信息的地方。对于代理构建者来说，实际发现是，摄取而不是推理是赢得或失去这种可靠性的地方，并且修复成本低廉且可衡量。

</details>

<details>
<summary><b>12. GuideEvolve: Self-Evolving Agent Framework with Expert Guidance and 3Ts Mechanisms</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Meihong Jia、Yasemin Timar、Jonathan Taws |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-10-21T16:46:22Z |
| **关键词** | `Benchmark` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2610.30017v1](http://arxiv.org/abs/2610.30017v1) |

**📝 摘要概括：**

> 本研究介绍了GuideEvolve ，这是一个自我发展的代理框架，结合了专家指导和三种自主监管机制，统称为3T ： Think Fast and Slow、Throwback和Termination by choice。该框架通过双重创新解决了现有自我进化代理范式的关键局限性： （ 1 ）特定任务的专家评估驱动的进化管道，以及（ 2 ） 3Ts机制的集成……

</details>

<details>
<summary><b>13. Agent Behavior Maps: Locating Agents by What They Would Do, Without Running Them</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Shota Fujikawa、Takuya Tamura、Kosuke Akimoto、Daichi Haraguchi、Masafumi Oyamada |
| **所属机构** | （详见原文） |
| **顶级机构标签** | Mila |
| **发布时间** | 2026-10-21T16:44:02Z |
| **关键词** | `LLM Agent` |
| **原文链接** | [http://arxiv.org/abs/2610.30014v1](http://arxiv.org/abs/2610.30014v1) |

**📝 摘要概括：**

> 具有相似成功率的LLM代理可以遵循不同的操作序列。Agent Behavior Map代表LLM-harness组合，使用共享参考轨迹上的居中操作日志可能性，而不需要目标Agent推出新的环境。作为扩展，线束组件位移大致构成，精度因组件和环境而异。

</details>

<details>
<summary><b>14. CORD: Conflict-Aware Optimization for Joint RL and Distillation in Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Wenhao Yu、Zhengcheng Wang、Jiahong Liu、Zexuan Qiu、Minda Hu 等（共 10 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-10-21T16:19:22Z |
| **关键词** | `Reinforcement Learning` |
| **原文链接** | [http://arxiv.org/abs/2610.29965v1](http://arxiv.org/abs/2610.29965v1) |

**📝 摘要概括：**

> 联合强化学习和自馏将任务奖励与密集的教师指导相结合，用于代理培训，但它们的梯度可以部分取消。混合系数控制相对比例，而不选择性地去除相对的成分。我们的分析解释了为什么必须一起选择保护方向和投影闸门，以及为什么蒸馏目标及其混合重量在投影后仍然重要。

</details>

<details>
<summary><b>15. FrontierCS 2: A Benchmark for Computer Science R&D</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Qiuyang Mang、Wenhao Chai、Runyuan He、Dongruixuan Li、Zihan Zheng 等（共 61 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-10-21T16:04:27Z |
| **关键词** | `LLM Agent` · `Benchmark` · `Robotics` |
| **原文链接** | [http://arxiv.org/abs/2610.29932v1](http://arxiv.org/abs/2610.29932v1) |

**📝 摘要概括：**

> 法学硕士代理能否为前沿计算机科学研发做出贡献？我们引入了FrontierCS 2 ，这是48个开放式任务的基准。在客服代表和任务的共享能力量表中，任务中位数与最强的客服代表所能处理的任务大致相同。

</details>

<details>
<summary><b>16. Automated Materials Data and Knowledge Extraction using Machine Learning and Large Language Models</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Aravindan Kamatchi Sundaram、B. Pabitramohan Prusty、Rohit Batra |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT |
| **发布时间** | 2026-10-21T15:38:05Z |
| **关键词** | `Agentic` · `Benchmark` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2610.29895v1](http://arxiv.org/abs/2610.29895v1) |

**📝 摘要概括：**

> 在过去的十年中，我们一直致力于开发机器学习（ ML ）方法，用于直接从科学文献中提取材料数据，并在可能的情况下提取材料知识。本综述追溯了这些方法从启发式、基于规则的管道到自然语言处理（ NLP ）模型和基于变压器的编码器的演变，最后是大型语言模型（ LLM ）和代理系统的演变。

</details>

<details>
<summary><b>17. PAUSE: Search-Free Steering of Coding Agents Before Their First Source-Code Edit</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Viral Patel、Boyin Tan、Jason Xue、Youcheng Sun |
| **所属机构** | （详见原文） |
| **顶级机构标签** | Mila、TRI |
| **发布时间** | 2026-10-21T15:24:44Z |
| **关键词** | `Planning` |
| **原文链接** | [http://arxiv.org/abs/2610.29870v1](http://arxiv.org/abs/2610.29870v1) |

**📝 摘要概括：**

> 编码代理可以在存储库探索和测试方面投入大量精力，但仍然会产生不成功的补丁。现有的在线指导方法定期审查轨迹，或者在监控人员检测到行为问题时调用顾问；频繁的审查代价高昂，没有异常行为并不意味着客服代表走在正确的轨道上。离线，暂停恢复35.4 ％的合格失败的已验证任务，并恢复F...

</details>

<details>
<summary><b>18. Real PMIDs, Wrong Papers: Harness Design for Biomedical Claim-Verification Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Mohammed Saqlain |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-10-21T14:35:56Z |
| **关键词** | `Reasoning` · `Retrieval` |
| **原文链接** | [http://arxiv.org/abs/2610.29812v1](http://arxiv.org/abs/2610.29812v1) |

**📝 摘要概括：**

> 文献搜索语言代理正在成为生命科学科学助手的标准组成部分，但很少有受控的证据表明它们的哪些部分是重要的。我们使用实时PubMed API作为唯一工具，对生物医学索赔验证（ SciFact ）进行受控消融。我们在https://github.com/saqlain2204/real-pmids-wrong-papers上发布代码、提示和所有缓存的工具调用。

</details>

<details>
<summary><b>19. Retrieval Augmented Generation Compositionality</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Ido Levy、Segev Shlomov、Leshem Choshen |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-10-21T13:30:29Z |
| **关键词** | `Agentic` · `RAG` · `Retrieval` · `Benchmark` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2610.29722v1](http://arxiv.org/abs/2610.29722v1) |

**📝 摘要概括：**

> 检索增强生成（ RAG ）基于外部知识中的大型语言模型。现代管道结合了嵌入、分块、检索、重新排序、查询增强、上下文压缩和代理验证，但这些技术通常一次评估一个。我们呼吁研究人员这样做，并提供千层面来简化这些实验。

</details>

<details>
<summary><b>20. Toward Recursive Self-Improvement in Physical AI</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Meng Luo、Zechen Bai、Shanqing Xu、Yanlin Li、Kaixin Li 等（共 12 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-10-21T12:54:50Z |
| **关键词** | `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2610.29677v1](http://arxiv.org/abs/2610.29677v1) |

**📝 摘要概括：**

> 递归自我改善（ RSI ）描述了一个不仅可以改善其行为，还可以改善其改进过程的系统。最近的数字代理通过重写自己的代码并通过可执行测试检查每个版本来测试这个想法。我们将这些发现综合到机器的评估原则和研究方向中，这些机器经过试验，可以安全地改进它们的改进方式。

</details>

## 🗄️ 历史归档

| 日期 | 论文数 | 报告链接 |
|------|--------|----------|
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

## 🏛️ 顶级机构覆盖范围

覆盖超过 **70 个**顶级 AI 机构，包括：

- **科技公司：** Microsoft、Google DeepMind、OpenAI、Anthropic、Meta AI、NVIDIA、Baidu、Alibaba、ByteDance 等
- **北美顶级大学：** MIT、Stanford、CMU、UC Berkeley、Harvard、Princeton、Cornell、Caltech 等
- **中国顶级大学/机构：** 清华大学、北京大学、浙大、上交大、复旦、中科院、MSRA 等
- **欧洲/其他：** Oxford、Cambridge、ETH Zurich、Mila、NUS、KAIST 等

---

*由 [clawBot DailyFindings](https://github.com/Jacob-biu/clawBot) 自动维护 | 最后更新：2026-10-23 00:25 UTC*
