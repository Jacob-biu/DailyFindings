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

## 📅 今日论文 — 2026-10-08　　[→ 查看完整报告](daily/2026-10-08.md)

> 共筛选出 **20** 篇论文 | 更新于 2026-10-08 01:34 UTC

### 论文目录与概要

| # | 论文标题 | 核心概要 | 来源机构 | 第一作者 |
|---|---------|---------|---------|--------|
| 1 | [AgentTime: Can Agents Estimate and Control Their Own Runtime…](http://arxiv.org/abs/2610.09944v1) | AI代理的一个重要控制是其管理运行时的能力。这种能力需要时间意识，以预测和估计挂钟时间并控制自己的行为。为了让客服代表在长时间内可靠、安全和自主地运行，我们需要对两者进行评估。 | CAS | Michael Ofengenden |
| 2 | [Expected Sample Complexity in Multi-Armed Bandits](http://arxiv.org/abs/2610.09929v1) | 样本复杂度是连续决策问题中广泛使用的度量标准，定义为代理和环境之间交互过程中次优决策的数量。我们研究了随机多臂土匪问题的样本复杂度，并引入了预期样本复杂度性能度量，在称为近似正确预期（ ACE ）的新… | TRI | Nadav Sukenik |
| 3 | [Constrained-Action AI Remediation for SIEM/XDR via a NeMo-Gu…](http://arxiv.org/abs/2610.09906v1) | 信息技术和运营技术的安全运营中心（ SOC ）有一个共同的事件响应问题：大量的相关警报和分析师太少。大型语言模型（ LLM ）越来越多地被提议作为推理引擎，用于分类警报，并在自主部署中发出阻止IP、终… | HIT、TRI | Georgios Koutidis |
| 4 | [LiveMACE: Process-Aware Evaluation of LLM Agent Capabilities…](http://arxiv.org/abs/2610.09872v1) | 仅根据结果评估客服代表可能会模糊产生这些结果的能力。在不断变化的环境中，这一问题尤其明显，在这种环境中，结果反映了客服代表行为和不断变化的外部条件之间的闭环互动。LiveMACEBench使这种区别变… | Mila | Jun Zhao |
| 5 | [Deadline-Aware Multi-Agent Reinforcement Learning for TSN-Ba…](http://arxiv.org/abs/2610.09870v1) | 车辆边缘计算(VEC)通过使计算和网络资源更接近车辆，实现了对延迟敏感的应用。然而，现有的方法往往忽略了具有异构动态延迟需求的同地服务之间的网络竞争。此外，与其他基于紧急情况的启发式方法不同， MAP… | MIT | Bernardo A. C. Pereira |
| 6 | [Training Advisors for LLM Agents from Task Outcomes](http://arxiv.org/abs/2610.09858v1) | 大型语言模型代理通过将推理和工具调用与环境观察交织在一起来处理多步骤任务。先前的研究表明，自然语言反馈可以帮助这些代理在任务执行过程中修改其决策。我们的结果表明，客服代表可以在推理时决定何时向批评者寻… | HIT | Sergei Polezhaev |
| 7 | [Self-Evolve With a Reference:Anchored Training of Tool-Integ…](http://arxiv.org/abs/2610.09856v1) | 自我进化工具集成的客服代表从自己的培训循环中生成的任务和反馈中学习。课程代理生成任务，而执行代理通过强化学习从自洽信号中学习。这些结果表明，在没有外部任务或答案监督的情况下，将轻量级历史参考引入自演进… | MIT | Wenjie Liao |
| 8 | [SkillForge: Co-Evolving Skills and Agents via Dynamic Skill …](http://arxiv.org/abs/2610.09832v1) | 记忆增强强化学习增强了LLM代理解决复杂长远任务的能力。技能是记忆的一种此类形式，将指令与任务类型的适用性条件配对。我们引入了SkillFurnace ，这是一个包含5k +注释记录的数据集，捆绑了退… | TRI | Yuyao Ge |
| 9 | [Homogenization in Multi-Agent Systems](http://arxiv.org/abs/2610.09824v1) | 多代理系统(MAS)利用代理之间的交互来执行复杂的任务。尽管他们取得了成功，但我们表明，这些互动也可能导致同质化，即客服代表会采取类似的行为。最后，我们表明，增加多样性的简单方法--杠杆化采样随机性和… | MIT、Mila | Prakhar Ganesh |
| 10 | [Artificial intelligence pathways from weather to climate](http://arxiv.org/abs/2610.09770v1) | 深度学习在天气预报方面取得了快速进展：在大气再分析上训练的自回归模型现在可以与预报、中程和季下交货时间的动态模型相媲美，从而以更低的成本生成校准良好的集成预报。我们回顾了这些进展，并考虑将其扩展到气候… | CAS、TRI | Tom Beucler |
| 11 | [From Expert-Guided Proof Search to Automated Open-Problem So…](http://arxiv.org/abs/2610.09769v1) | 大型语言模型越来越多地为数学研究做出贡献，而数学研究的进展通常取决于高效的证明搜索、渐进式改进和仔细验证。我们描述了Bolzano ，这是一个多代理开源系统，使用并行证明代理和验证代理，并保持人类可读… | CAS、TRI | Adrián Zámečník |
| 12 | [Beyond Policy Support: Interaction Constrained Offline Reinf…](http://arxiv.org/abs/2610.09763v1) | 离线强化学习可以从固定数据集中进行奖励驱动的策略改进，而无需在线探索，使其在安全关键领域特别具有吸引力。然而，一个核心挑战是分布转变：策略优化可能有利于离线数据支持较弱的行动，从而使价值估算不可靠。项… | TRI | Mahmoud Selim |
| 13 | [System Switch: When Should a Fast Decision Model Stop and Th…](http://arxiv.org/abs/2610.09683v1) | 双进程代理将快速策略与缓慢的审议模型配对。在实时设置中，慢速模型通常连续运行；在基于回合的代理和机器人规划器中，在不确定性或检测到故障等事件时调用慢速模型。我们发布代码、提示、数据和日志。 | MIT、Mila | Gian Luca Bailo |
| 14 | [CircuitATLAS: Agentic reasoning over a systems neuroscience …](http://arxiv.org/abs/2610.09643v1) | 神经系统疾病的药物发现传统上以疾病改变的分子为中心。但引起病理的分子不一定是逆转它的最佳点。因此， CircuitATLAS提供了一个框架，用于发现不仅基于疾病中分子破坏的治疗方法，而且基于可以控制以… | TRI | Gabriel Ocana-Santero |
| 15 | [Coding-Agent Benchmarks Should Match Their Users' Task Flows](http://arxiv.org/abs/2610.09633v1) | 编码代理的评估通常力求尽可能真实。在我们的研究中，我们收集了JetBrains IDE中真实软件工程师的4,782个代理会话，我们称之为生产会话。在700个SWE-Bench Pro任务的试点中，按几… | CAS、TRI | Igor Slinko |
| 16 | [Learning Situation-Conditioned Thinking Policies for Long-Te…](http://arxiv.org/abs/2610.09590v1) | 长期运行的自主代理必须重复使用积累的推理经验，而不允许明确的历史记忆和LLM上下文无限期地增长。然而，现有的记忆机制主要是检索、总结或压缩过去的内容，并不能直接学习何时应该激活特定种类的思维，也不能从… | TRI | Hong Su |
| 17 | [Correct Answers, Unsupported Findings: Evidence Binding in F…](http://arxiv.org/abs/2610.09581v1) | LLM代理操作的法医重建不仅需要恢复正确的值，还需要确定哪些保留的记录支持该发现。工具日志、生成的解释和本地引文标识符捕获此证据的不同部分，但除非保留其与记录的绑定，否则引文标识符不会建立源。这些结果… | CAS | Taehyeon Yun |
| 18 | [DrugTargetWorld: A Synthetic Biobank for Training and Benchm…](http://arxiv.org/abs/2610.09558v1) | 药物靶点发现需要区分因果驱动疾病的分子和仅与其相关的分子。培训和评估AI代理以端到端执行此工作流程很困难，因为现实世界的生物库缺乏已知的因果基础事实，并且参与者级别的数据受到访问控制。通过让评估者知道… | MIT | Samuel Margolis |
| 19 | [Constitution-Guided Watermarking](http://arxiv.org/abs/2610.09552v1) | 水印使语言模型提供者能够识别其模型生成的文本。但是，其所需的属性可能会发生冲突（\ ie ~更强的水印信号会降低文本质量） ，而抵制编辑的设计也可能会促进伪造。在使用KGW和五规则结构的概念验证评估中… | TRI | Toluwani Aremu |
| 20 | [Ream: Unfolding Mutual Awareness in Human-Agent Workspaces](http://arxiv.org/abs/2610.09497v1) | 随着人工智能代理在共享工作空间中与人类一起工作，一个共同的意识挑战出现了：代理的行动速度超过了人类的监控速度，并且用户不断变化的兴趣并不总是在聊天中表达出来。这一挑战在文献综述中尤为紧迫，双方都在检索… | TRI | Peiling Jiang |

### 论文详情

<details>
<summary><b>1. AgentTime: Can Agents Estimate and Control Their Own Runtime?</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Michael Ofengenden、Maksym Andriushchenko |
| **所属机构** | （详见原文） |
| **顶级机构标签** | CAS |
| **发布时间** | 2026-10-07T12:26:24Z |
| **关键词** | `AI Agent` · `Agentic` · `Benchmark` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2610.09944v1](http://arxiv.org/abs/2610.09944v1) |

**📝 摘要概括：**

> AI代理的一个重要控制是其管理运行时的能力。这种能力需要时间意识，以预测和估计挂钟时间并控制自己的行为。为了让客服代表在长时间内可靠、安全和自主地运行，我们需要对两者进行评估。

</details>

<details>
<summary><b>2. Expected Sample Complexity in Multi-Armed Bandits</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Nadav Sukenik、Nadav Merlis |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-10-07T12:16:27Z |
| **关键词** | — |
| **原文链接** | [http://arxiv.org/abs/2610.09929v1](http://arxiv.org/abs/2610.09929v1) |

**📝 摘要概括：**

> 样本复杂度是连续决策问题中广泛使用的度量标准，定义为代理和环境之间交互过程中次优决策的数量。我们研究了随机多臂土匪问题的样本复杂度，并引入了预期样本复杂度性能度量，在称为近似正确预期（ ACE ）的新框架中对其进行了分析。最后，我们建立了几乎匹配的……

</details>

<details>
<summary><b>3. Constrained-Action AI Remediation for SIEM/XDR via a NeMo-Guardrails Proxy</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Georgios Koutidis、Nikolaos Kekatos、Tom Nianios、Alexios Lekidis |
| **所属机构** | （详见原文） |
| **顶级机构标签** | HIT、TRI |
| **发布时间** | 2026-10-07T12:00:51Z |
| **关键词** | `Reasoning` |
| **原文链接** | [http://arxiv.org/abs/2610.09906v1](http://arxiv.org/abs/2610.09906v1) |

**📝 摘要概括：**

> 信息技术和运营技术的安全运营中心（ SOC ）有一个共同的事件响应问题：大量的相关警报和分析师太少。大型语言模型（ LLM ）越来越多地被提议作为推理引擎，用于分类警报，并在自主部署中发出阻止IP、终止进程或隔离生产主机上文件的命令。循环最好是人工在循环中运行或延迟： mea…

</details>

<details>
<summary><b>4. LiveMACE: Process-Aware Evaluation of LLM Agent Capabilities in Evolving Markets</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Jun Zhao、Leiming Fu、Yanbo Wen、Yiding Wang、Xuantong Liu 等（共 12 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | Mila |
| **发布时间** | 2026-10-07T11:33:21Z |
| **关键词** | `Multi-Agent` · `LLM Agent` · `Benchmark` · `Evaluation` · `Memory` |
| **原文链接** | [http://arxiv.org/abs/2610.09872v1](http://arxiv.org/abs/2610.09872v1) |

**📝 摘要概括：**

> 仅根据结果评估客服代表可能会模糊产生这些结果的能力。在不断变化的环境中，这一问题尤其明显，在这种环境中，结果反映了客服代表行为和不断变化的外部条件之间的闭环互动。LiveMACEBench使这种区别变得可衡量，将实时市场从绩效排行榜转变为代理能力的诊断环境

</details>

<details>
<summary><b>5. Deadline-Aware Multi-Agent Reinforcement Learning for TSN-Based Vehicular Edge Networks</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Bernardo A. C. Pereira、Marcos Carvalho、Fatih Temiz、Shavbo Salehi、Melike Erol-Kantarci 等（共 8 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT |
| **发布时间** | 2026-10-07T11:30:19Z |
| **关键词** | `Multi-Agent` · `Reinforcement Learning` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2610.09870v1](http://arxiv.org/abs/2610.09870v1) |

**📝 摘要概括：**

> 车辆边缘计算(VEC)通过使计算和网络资源更接近车辆，实现了对延迟敏感的应用。然而，现有的方法往往忽略了具有异构动态延迟需求的同地服务之间的网络竞争。此外，与其他基于紧急情况的启发式方法不同， MAPPO确保了均衡的调度，同时与其他MARL方法相比，实现了更低的推理时间。

</details>

<details>
<summary><b>6. Training Advisors for LLM Agents from Task Outcomes</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Sergei Polezhaev、Barys Liskavets、Ori Press、Alexander Golubev |
| **所属机构** | （详见原文） |
| **顶级机构标签** | HIT |
| **发布时间** | 2026-10-07T11:14:26Z |
| **关键词** | `LLM Agent` · `Reasoning` · `Reinforcement Learning` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2610.09858v1](http://arxiv.org/abs/2610.09858v1) |

**📝 摘要概括：**

> 大型语言模型代理通过将推理和工具调用与环境观察交织在一起来处理多步骤任务。先前的研究表明，自然语言反馈可以帮助这些代理在任务执行过程中修改其决策。我们的结果表明，客服代表可以在推理时决定何时向批评者寻求帮助，而基于结果的批评者培训可以产生跨基本模型和任务域的指导……

</details>

<details>
<summary><b>7. Self-Evolve With a Reference:Anchored Training of Tool-Integrated Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Wenjie Liao、Liangjie Zhao、Zehong Cao |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT |
| **发布时间** | 2026-10-07T11:13:35Z |
| **关键词** | `Reasoning` · `Reinforcement Learning` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2610.09856v1](http://arxiv.org/abs/2610.09856v1) |

**📝 摘要概括：**

> 自我进化工具集成的客服代表从自己的培训循环中生成的任务和反馈中学习。课程代理生成任务，而执行代理通过强化学习从自洽信号中学习。这些结果表明，在没有外部任务或答案监督的情况下，将轻量级历史参考引入自演进工具集成代理的好处。

</details>

<details>
<summary><b>8. SkillForge: Co-Evolving Skills and Agents via Dynamic Skill Lifecycles</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Yuyao Ge、Yiwei Wang、Yuchen He、Baolong Bi、Lingrui Mei 等（共 8 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-10-07T10:52:15Z |
| **关键词** | `LLM Agent` · `Agentic` · `Reinforcement Learning` · `Benchmark` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2610.09832v1](http://arxiv.org/abs/2610.09832v1) |

**📝 摘要概括：**

> 记忆增强强化学习增强了LLM代理解决复杂长远任务的能力。技能是记忆的一种此类形式，将指令与任务类型的适用性条件配对。我们引入了SkillFurnace ，这是一个包含5k +注释记录的数据集，捆绑了退休过滤的SFT轨迹，带有健身注释的进化技能库，以及带有人工注释故障类别的退休事件，以支持解决方案……

</details>

<details>
<summary><b>9. Homogenization in Multi-Agent Systems</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Prakhar Ganesh、Kyra Wilson、Luca Zappella、Barry-John Theobald、Nicholas Apostoloff 等（共 7 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、Mila、TRI |
| **发布时间** | 2026-10-07T10:49:29Z |
| **关键词** | `Multi-Agent` · `RAG` · `Evaluation` · `Code Generation` |
| **原文链接** | [http://arxiv.org/abs/2610.09824v1](http://arxiv.org/abs/2610.09824v1) |

**📝 摘要概括：**

> 多代理系统(MAS)利用代理之间的交互来执行复杂的任务。尽管他们取得了成功，但我们表明，这些互动也可能导致同质化，即客服代表会采取类似的行为。最后，我们表明，增加多样性的简单方法--杠杆化采样随机性和混合模型MAS--不能降低均匀化风险，强调需要有效地利用代理数据的策略。

</details>

<details>
<summary><b>10. Artificial intelligence pathways from weather to climate</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Tom Beucler、J. David Neelin、Hui Su、Shivanshi Asthana、Chris Bretherton 等（共 13 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | CAS、TRI |
| **发布时间** | 2026-10-07T09:52:47Z |
| **关键词** | — |
| **原文链接** | [http://arxiv.org/abs/2610.09770v1](http://arxiv.org/abs/2610.09770v1) |

**📝 摘要概括：**

> 深度学习在天气预报方面取得了快速进展：在大气再分析上训练的自回归模型现在可以与预报、中程和季下交货时间的动态模型相媲美，从而以更低的成本生成校准良好的集成预报。我们回顾了这些进展，并考虑将其扩展到气候视野，其中挑战从初始条件技能转变为产生可靠的统计响应……

</details>

<details>
<summary><b>11. From Expert-Guided Proof Search to Automated Open-Problem Solving</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Adrián Zámečník、Matěj Kripner、Martin Koutecký、Martin Balko、Jan Grebík 等（共 8 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | CAS、TRI |
| **发布时间** | 2026-10-07T09:52:46Z |
| **关键词** | `Multi-Agent` |
| **原文链接** | [http://arxiv.org/abs/2610.09769v1](http://arxiv.org/abs/2610.09769v1) |

**📝 摘要概括：**

> 大型语言模型越来越多地为数学研究做出贡献，而数学研究的进展通常取决于高效的证明搜索、渐进式改进和仔细验证。我们描述了Bolzano ，这是一个多代理开源系统，使用并行证明代理和验证代理，并保持人类可读的研究状态。在那里，我们回答了论文中提出的四个问题，并得到了作者的确认。

</details>

<details>
<summary><b>12. Beyond Policy Support: Interaction Constrained Offline Reinforcement Learning for Autonomous Driving</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Mahmoud Selim、Cristina Cipriani、Karl Henrik Johansson |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-10-07T09:48:53Z |
| **关键词** | `Reinforcement Learning` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2610.09763v1](http://arxiv.org/abs/2610.09763v1) |

**📝 摘要概括：**

> 离线强化学习可以从固定数据集中进行奖励驱动的策略改进，而无需在线探索，使其在安全关键领域特别具有吸引力。然而，一个核心挑战是分布转变：策略优化可能有利于离线数据支持较弱的行动，从而使价值估算不可靠。项目网页： https://mahmoud-selim.github.io/ICDP/

</details>

<details>
<summary><b>13. System Switch: When Should a Fast Decision Model Stop and Think?</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Gian Luca Bailo |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、Mila |
| **发布时间** | 2026-10-07T08:44:47Z |
| **关键词** | `Reasoning` |
| **原文链接** | [http://arxiv.org/abs/2610.09683v1](http://arxiv.org/abs/2610.09683v1) |

**📝 摘要概括：**

> 双进程代理将快速策略与缓慢的审议模型配对。在实时设置中，慢速模型通常连续运行；在基于回合的代理和机器人规划器中，在不确定性或检测到故障等事件时调用慢速模型。我们发布代码、提示、数据和日志。

</details>

<details>
<summary><b>14. CircuitATLAS: Agentic reasoning over a systems neuroscience knowledge graph for target discovery in circuitopathies</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Gabriel Ocana-Santero、Marko Tvrdic |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-10-07T08:19:27Z |
| **关键词** | `Agentic` · `Reasoning` · `Workflow` |
| **原文链接** | [http://arxiv.org/abs/2610.09643v1](http://arxiv.org/abs/2610.09643v1) |

**📝 摘要概括：**

> 神经系统疾病的药物发现传统上以疾病改变的分子为中心。但引起病理的分子不一定是逆转它的最佳点。因此， CircuitATLAS提供了一个框架，用于发现不仅基于疾病中分子破坏的治疗方法，而且基于可以控制以恢复电路功能的治疗方法。

</details>

<details>
<summary><b>15. Coding-Agent Benchmarks Should Match Their Users' Task Flows</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Igor Slinko、Yaroslav Golubev、Sergey Titov |
| **所属机构** | （详见原文） |
| **顶级机构标签** | CAS、TRI |
| **发布时间** | 2026-10-07T08:08:39Z |
| **关键词** | `Planning` · `Benchmark` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2610.09633v1](http://arxiv.org/abs/2610.09633v1) |

**📝 摘要概括：**

> 编码代理的评估通常力求尽可能真实。在我们的研究中，我们收集了JetBrains IDE中真实软件工程师的4,782个代理会话，我们称之为生产会话。在700个SWE-Bench Pro任务的试点中，按几个步骤顺序解决任务大约使代理成本翻了一番，而没有稳定的解决率变化：交互协议本身就是评估的一个重要维度。

</details>

<details>
<summary><b>16. Learning Situation-Conditioned Thinking Policies for Long-Term LLM Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Hong Su |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-10-07T07:34:08Z |
| **关键词** | `LLM Agent` · `Reasoning` · `Memory` |
| **原文链接** | [http://arxiv.org/abs/2610.09590v1](http://arxiv.org/abs/2610.09590v1) |

**📝 摘要概括：**

> 长期运行的自主代理必须重复使用积累的推理经验，而不允许明确的历史记忆和LLM上下文无限期地增长。然而，现有的记忆机制主要是检索、总结或压缩过去的内容，并不能直接学习何时应该激活特定种类的思维，也不能从暂时分散的经历中发现新的思维知识。实验表明，学到的策略实现了……

</details>

<details>
<summary><b>17. Correct Answers, Unsupported Findings: Evidence Binding in Forensic Reconstruction of LLM Agent Logs</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Taehyeon Yun、Dongho Kim、Geonwoo Kim、Juyoung Seo、Minseok Hur 等（共 6 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | CAS |
| **发布时间** | 2026-10-07T07:26:33Z |
| **关键词** | `LLM Agent` |
| **原文链接** | [http://arxiv.org/abs/2610.09581v1](http://arxiv.org/abs/2610.09581v1) |

**📝 摘要概括：**

> LLM代理操作的法医重建不仅需要恢复正确的值，还需要确定哪些保留的记录支持该发现。工具日志、生成的解释和本地引文标识符捕获此证据的不同部分，但除非保留其与记录的绑定，否则引文标识符不会建立源。这些结果表明，仅凭事实协议不足以评估取证……

</details>

<details>
<summary><b>18. DrugTargetWorld: A Synthetic Biobank for Training and Benchmarking AI Scientists</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Samuel Margolis、Paul Schmiedmayer、Alan Huang、Ethan Chen、Ishan Bhattacharjee 等（共 15 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT |
| **发布时间** | 2026-10-07T06:59:54Z |
| **关键词** | `AI Agent` · `RAG` · `Benchmark` · `Evaluation` · `Workflow` |
| **原文链接** | [http://arxiv.org/abs/2610.09558v1](http://arxiv.org/abs/2610.09558v1) |

**📝 摘要概括：**

> 药物靶点发现需要区分因果驱动疾病的分子和仅与其相关的分子。培训和评估AI代理以端到端执行此工作流程很困难，因为现实世界的生物库缺乏已知的因果基础事实，并且参与者级别的数据受到访问控制。通过让评估者知道每个世界的因果结构，但对代理人隐藏， DrugTargetWorld变成了端到端的药物……

</details>

<details>
<summary><b>19. Constitution-Guided Watermarking</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Toluwani Aremu、Samuele Poppi、Nils Lukas |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-10-07T06:50:47Z |
| **关键词** | `Reasoning` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2610.09552v1](http://arxiv.org/abs/2610.09552v1) |

**📝 摘要概括：**

> 水印使语言模型提供者能够识别其模型生成的文本。但是，其所需的属性可能会发生冲突（\ ie ~更强的水印信号会降低文本质量） ，而抵制编辑的设计也可能会促进伪造。在使用KGW和五规则结构的概念验证评估中，我们的框架选择响应提供商优先级的配置，并改进鲁棒性的释义后检测……

</details>

<details>
<summary><b>20. Ream: Unfolding Mutual Awareness in Human-Agent Workspaces</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Peiling Jiang、Sangho Suh、Varsha Kishore、Jonathan Bragg、Haijun Xia 等（共 9 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-10-07T05:52:15Z |
| **关键词** | `AI Agent` |
| **原文链接** | [http://arxiv.org/abs/2610.09497v1](http://arxiv.org/abs/2610.09497v1) |

**📝 摘要概括：**

> 随着人工智能代理在共享工作空间中与人类一起工作，一个共同的意识挑战出现了：代理的行动速度超过了人类的监控速度，并且用户不断变化的兴趣并不总是在聊天中表达出来。这一挑战在文献综述中尤为紧迫，双方都在检索、阅读和合成越来越多的论文。这些调查结果说明了共享文档中的参与度跟踪如何支持透明度、个性化……

</details>

## 🗄️ 历史归档

| 日期 | 论文数 | 报告链接 |
|------|--------|----------|
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
| 2026-08-25 | 12 篇 | [2026-08-25.md](daily/2026-08-25.md) |
| 2026-08-24 | 0 篇 | [2026-08-24.md](daily/2026-08-24.md) |

## 🏛️ 顶级机构覆盖范围

覆盖超过 **70 个**顶级 AI 机构，包括：

- **科技公司：** Microsoft、Google DeepMind、OpenAI、Anthropic、Meta AI、NVIDIA、Baidu、Alibaba、ByteDance 等
- **北美顶级大学：** MIT、Stanford、CMU、UC Berkeley、Harvard、Princeton、Cornell、Caltech 等
- **中国顶级大学/机构：** 清华大学、北京大学、浙大、上交大、复旦、中科院、MSRA 等
- **欧洲/其他：** Oxford、Cambridge、ETH Zurich、Mila、NUS、KAIST 等

---

*由 [clawBot DailyFindings](https://github.com/Jacob-biu/clawBot) 自动维护 | 最后更新：2026-10-08 01:34 UTC*
