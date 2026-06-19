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

## 📅 今日论文 — 2026-06-19　　[→ 查看完整报告](daily/2026-06-19.md)

> 共筛选出 **20** 篇论文 | 更新于 2026-06-19 22:56 UTC

### 论文目录与概要

| # | 论文标题 | 核心概要 | 来源机构 | 第一作者 |
|---|---------|---------|---------|--------|
| 1 | [Execution-State Capsules: Graph-Bound Execution-State Checkp…](http://arxiv.org/abs/2606.20537v1) | 主流LLM服务系统重用前缀主要通过分页或基数键值(KV)缓存工作。这对于高吞吐量、高并发服务非常有效，但它只管理执行状态的一个位置片段： KV缓存。胶囊不是高吞吐量KV缓存服务的替代品；它们定义了一个… | NVIDIA、MIT | Liang Su |
| 2 | [LedgerAgent: Structured State for Policy-Adherent Tool-Calli…](http://arxiv.org/abs/2606.20529v1) | 客户服务域中的策略遵循工具调用代理必须在调用工具和遵守域策略的过程中跨回合维护任务状态。任务状态包括通过用户交互和工具调用观察到的相关事实、标识符、约束和条件。跨越四个客户服务域和一个混合的开放式和封… | TRI | Md Nayem Uddin |
| 3 | [Probe-and-Refine Tuning of Repository Guidance for Coding Ag…](http://arxiv.org/abs/2606.20512v1) | 基于LLM的编码代理需要更高级别的操作知识，了解代码本身不存在的存储库（存储哪些子系统、如何运行测试套件、哪些工作流程历来导致错误的修复）。工程师通常维护\ texttt {AGENTS.md}文件，… | NVIDIA、TRI | Asa Shepard |
| 4 | [Efficient and Sound Probabilistic Verification for AI Agents](http://arxiv.org/abs/2606.20510v1) | 保护在复杂数字环境中运行的人工智能代理已成为一项关键需求，而制定和执行以Datalog等正式语言表达的政策的运行时监控方法提供了一个有前途的解决方案。然而，现有的方法仅限于确定性的政策。在终端和工具调… | TRI | Alaia Solko-Breslin |
| 5 | [Contagion Networks: Evaluator Bias Propagation in Multi-Agen…](http://arxiv.org/abs/2606.20493v1) | 当大型语言模型在多智能体系统中充当评估者时，其系统评估偏差会通过智能体网络传播。我们介绍了Contagion Networks ，这是一个正式的框架，用于衡量评估者偏见如何在相互作用的LLM代理中传播… | MIT、TRI | Zewen Liu |
| 6 | [Optimal Order of Multi-Agent and General Many-Body Systems](http://arxiv.org/abs/2606.20485v1) | 本文开发了一个用于分析多智能体系统的通用框架，该框架在智能体动作和集体观察之间具有反馈循环。该框架建立在两个基本的代理级别变量之上：权力（衡量代理对集体结果的影响）和响应函数（确定代理对观察结果的反应… | TRI | Jake J. Xia |
| 7 | [Marginal Advantage Accumulation for Memory-Driven Agent Self…](http://arxiv.org/abs/2606.20475v1) | 在批量式痕量蒸馏中，相同的记忆操作可能在不同批次之间接收矛盾的反馈。现有方法缺乏跨批次、操作层面的证据累积机制，无法区分稳定有效的操作和意外命中。作为后处理架构， MAA在4个基准和4个目标模型的16… | HIT | Mingyu Yang |
| 8 | [Agentic Symbolic Search: Characterizing PDEs Beyond Hand-cra…](http://arxiv.org/abs/2606.20467v1) | 数学家通过数学结构而不是计算值的表来理解PDE解决方案。从历史上看，这是数学分析的产物，针对每个问题分别进行手工分析。ASYS展示了表征PDE解决方案的新范式的可能性，超越了手工制作的分析解决方案、基… | TRI | Zongmin Yu |
| 9 | [LLM agent safety, multi-turn red-teaming, jailbreak benchmar…](http://arxiv.org/abs/2606.20408v1) | 大型语言模型（ LLM ）代理越来越多地被提出作为安全关键系统的监督组件，但它们在持续、自适应对抗压力下的鲁棒性仍然很差。我们展示了NRT-Bench ，这是在模拟核电站控制室中实例化的充当安全关键系… | MIT、TRI | Hanwool Lee |
| 10 | [DataMagic: Transforming Tabular Data into Data Insight Video](http://arxiv.org/abs/2606.20388v1) | 数据视频集成了动态图表、语音旁白和同步动画，将数据见解作为时间叙述进行沟通，使其成为提高数据管理生命周期中数据消耗效率的有效媒介。然而，制作高质量的数据视频需要跨越数据分析、叙事设计和视频制作的专业知… | HIT | Yupeng Xie |
| 11 | [CRAX: Fast Safe Reinforcement Learning Benchmarking](http://arxiv.org/abs/2606.20376v1) | 在机器人和自动驾驶等现实领域部署强化学习（ RL ）代理时，安全是一个核心问题。虽然基准测试一直是强化学习进展的核心，但现有的高保真3D物理安全基准测试的计算速度仍然很慢，限制了大规模实验和快速原型设… | MIT | Tristan Tomilin |
| 12 | [AutoPass: Evidence-Guided LLM Agents for Compiler Performanc…](http://arxiv.org/abs/2606.20373v1) | 大型语言模型（ LLM ）显示出对代码编译任务的承诺，但由于复杂的微架构效应和嘈杂的运行时测量，将它们应用于运行时性能调优很困难。我们推出了AutoPass ，这是一个用于编译器性能调整的多代理框架，… | HIT、TRI | Zepeng Li |
| 13 | [Automating SKILL.md Generation for Computer-Using Agents via…](http://arxiv.org/abs/2606.20363v1) | 显式技能库使使用计算机的代理更容易检查，但目前尚不清楚这些库是否可以通过改善下游策略的方式从交互数据中挖掘出来。我们通过一个三阶段的管道来研究这个问题，该管道将GUI轨迹细分，将细分聚类为候选技能，并… | TRI | Yuexing Hao |
| 14 | [SoftSkill: Behavioral Compression for Contextual Adaptation](http://arxiv.org/abs/2606.20333v1) | 代理技能通常部署为自然语言Markdown文件，用于编码应答策略、证据使用习惯和任务过程。这些文件是可读和可移植的，但它们是间接消耗的：对于每个任务实例，冻结的语言模型必须将长文本工件转换为生成时间行… | MIT、CAS | Xijia Tao |
| 15 | [A Model-Driven Approach for Developing Families of Reinforce…](http://arxiv.org/abs/2606.20324v1) | 虚拟培训环境是软件密集型系统，其中强化学习（ RL ）代理学习、适应和展示有意义的行为。虚拟培训环境为现实环境中的代理人培训提供了一种安全且具有成本效益的替代方案。我们在野火缓解情景和课程学习中展示了… | MIT、Mila | Xiaoran Liu |
| 16 | [Navigating Unreliable Parametric and Contextual Knowledge: E…](http://arxiv.org/abs/2606.20245v1) | 大型语言模型（ LLM ）通过利用广泛的参数知识和上下文学习能力，在广泛的基于语言的任务中取得了强大的表现，使他们能够将输入提示中提供的外部信息结合起来。然而，外部知识的整合不仅会引入模型的内部参数知… | MIT、TRI | Huang Peng |
| 17 | [ScholarQuest: A Taxonomy-Guided Benchmark for Agentic Academ…](http://arxiv.org/abs/2606.20235v1) | 学术论文搜索是科学研究的核心步骤，基于法学硕士的搜索代理正在成为迭代、意图驱动的文献探索的一个有前途的范例。然而，现有的基准不足以系统地评估现实开放文献环境下的代理学术搜索。此外，对搜索效率、意图级鲁… | CAS、TRI | Tingyue Pan |
| 18 | [Augmenting Game AI with Deep Reinforcement Learning](http://arxiv.org/abs/2606.20210v1) | 沉浸在视频游戏中不仅取决于图形、音频和游戏机制，还取决于游戏中角色的质量。制作可信的角色或游戏AI仍然是一个重大挑战，因为用手工编码系统很难捕捉到行为复杂性。此外，我们确定了这些领域的瓶颈和难题，我们… | MIT | Alessandro Sestini |
| 19 | [FlowMaps: Modeling Long-Term Multimodal Object Dynamics with…](http://arxiv.org/abs/2606.20209v1) | 对3D场景的联合空间和时间理解是部署在日常家庭环境中的机器人的关键要求。这些代理不仅必须理解和导航空间布局，还必须推理这些空间如何随着时间的推移而演变。代码和其他材料可在https://fra-tsu… | Mila、TRI | Francesco Argenziano |
| 20 | [MedRLM: Recursive Multimodal Health Intelligence for Long-Co…](http://arxiv.org/abs/2606.20164v1) | 现实世界的临床决策支持需要对异质和纵向的患者信息进行推理，而不是回答孤立的医疗问题。然而，当前的医学大型语言模型和检索增强生成系统通常依赖于单步提示或检索，当临床证据分布在长电子健康记录、医学图像、传… | CAS、TRI | Aueaphum Aueawatthanaphisut |

### 论文详情

<details>
<summary><b>1. Execution-State Capsules: Graph-Bound Execution-State Checkpoint and Restore for Low-Latency, Small-Batch, On-Device Physical-AI Serving</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Liang Su |
| **所属机构** | （详见原文） |
| **顶级机构标签** | NVIDIA、MIT、HIT |
| **发布时间** | 2026-06-18T17:49:36Z |
| **关键词** | `LLM Agent` · `RAG` |
| **原文链接** | [http://arxiv.org/abs/2606.20537v1](http://arxiv.org/abs/2606.20537v1) |

**📝 摘要概括：**

> 主流LLM服务系统重用前缀主要通过分页或基数键值(KV)缓存工作。这对于高吞吐量、高并发服务非常有效，但它只管理执行状态的一个位置片段： KV缓存。胶囊不是高吞吐量KV缓存服务的替代品；它们定义了一个互补的延迟优先服务点，用于显式执行状态重用。

</details>

<details>
<summary><b>2. LedgerAgent: Structured State for Policy-Adherent Tool-Calling Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Md Nayem Uddin、Amir Saeidi、Eduardo Blanco、Chitta Baral |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-06-18T17:41:56Z |
| **关键词** | `RAG` |
| **原文链接** | [http://arxiv.org/abs/2606.20529v1](http://arxiv.org/abs/2606.20529v1) |

**📝 摘要概括：**

> 客户服务域中的策略遵循工具调用代理必须在调用工具和遵守域策略的过程中跨回合维护任务状态。任务状态包括通过用户交互和工具调用观察到的相关事实、标识符、约束和条件。跨越四个客户服务域和一个混合的开放式和封闭式权重模型面板，\ textsc {LedgerAgent}提高了平均通过率\ textasciicircum {} k超过标准...

</details>

<details>
<summary><b>3. Probe-and-Refine Tuning of Repository Guidance for Coding Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Asa Shepard、Jeannie Albrecht |
| **所属机构** | （详见原文） |
| **顶级机构标签** | NVIDIA、TRI |
| **发布时间** | 2026-06-18T17:30:15Z |
| **关键词** | `RAG` · `Workflow` |
| **原文链接** | [http://arxiv.org/abs/2606.20512v1](http://arxiv.org/abs/2606.20512v1) |

**📝 摘要概括：**

> 基于LLM的编码代理需要更高级别的操作知识，了解代码本身不存在的存储库（存储哪些子系统、如何运行测试套件、哪些工作流程历来导致错误的修复）。工程师通常维护\ texttt {AGENTS.md}文件，以提供此上下文作为编码代理的说明，但他们是否提供帮助是有争议的：最近的研究在LLM生成的指导是否影响……

</details>

<details>
<summary><b>4. Efficient and Sound Probabilistic Verification for AI Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Alaia Solko-Breslin、Pramod Kaushik Mudrakarta、Mihai Christodorescu、Somesh Jha、Krishnamurthy Dj Dvijotham |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-06-18T17:27:59Z |
| **关键词** | `AI Agent` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2606.20510v1](http://arxiv.org/abs/2606.20510v1) |

**📝 摘要概括：**

> 保护在复杂数字环境中运行的人工智能代理已成为一项关键需求，而制定和执行以Datalog等正式语言表达的政策的运行时监控方法提供了一个有前途的解决方案。然而，现有的方法仅限于确定性的政策。在终端和工具调用代理的标准基准上，我们证明了我们的方法优于现有技术，并提高了安全性。

</details>

<details>
<summary><b>5. Contagion Networks: Evaluator Bias Propagation in Multi-Agent LLM Systems</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Zewen Liu |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-06-18T17:09:34Z |
| **关键词** | `Multi-Agent` · `LLM Agent` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2606.20493v1](http://arxiv.org/abs/2606.20493v1) |

**📝 摘要概括：**

> 当大型语言模型在多智能体系统中充当评估者时，其系统评估偏差会通过智能体网络传播。我们介绍了Contagion Networks ，这是一个正式的框架，用于衡量评估者偏见如何在相互作用的LLM代理中传播。我们发布了开源Contagion Network实验框架。

</details>

<details>
<summary><b>6. Optimal Order of Multi-Agent and General Many-Body Systems</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Jake J. Xia |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-06-18T17:03:03Z |
| **关键词** | `Multi-Agent` · `RAG` |
| **原文链接** | [http://arxiv.org/abs/2606.20485v1](http://arxiv.org/abs/2606.20485v1) |

**📝 摘要概括：**

> 本文开发了一个用于分析多智能体系统的通用框架，该框架在智能体动作和集体观察之间具有反馈循环。该框架建立在两个基本的代理级别变量之上：权力（衡量代理对集体结果的影响）和响应函数（确定代理对观察结果的反应）。通过测量和设计代理功率分布和响应函数，可以投注……

</details>

<details>
<summary><b>7. Marginal Advantage Accumulation for Memory-Driven Agent Self-Evolution</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Mingyu Yang、Keye Zheng、Congchao Cheng、Yujie Liu、Xingkang Lu 等（共 7 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | HIT |
| **发布时间** | 2026-06-18T16:54:25Z |
| **关键词** | `Benchmark` · `Memory` |
| **原文链接** | [http://arxiv.org/abs/2606.20475v1](http://arxiv.org/abs/2606.20475v1) |

**📝 摘要概括：**

> 在批量式痕量蒸馏中，相同的记忆操作可能在不同批次之间接收矛盾的反馈。现有方法缺乏跨批次、操作层面的证据累积机制，无法区分稳定有效的操作和意外命中。作为后处理架构， MAA在4个基准和4个目标模型的16个设置中的14个中取得了最佳结果，始终优于……

</details>

<details>
<summary><b>8. Agentic Symbolic Search: Characterizing PDEs Beyond Hand-crafted Expressions, Meshes, and Neural Networks</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Zongmin Yu、Liu Yang |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-06-18T16:46:42Z |
| **关键词** | `Agentic` · `Simulation` |
| **原文链接** | [http://arxiv.org/abs/2606.20467v1](http://arxiv.org/abs/2606.20467v1) |

**📝 摘要概括：**

> 数学家通过数学结构而不是计算值的表来理解PDE解决方案。从历史上看，这是数学分析的产物，针对每个问题分别进行手工分析。ASYS展示了表征PDE解决方案的新范式的可能性，超越了手工制作的分析解决方案、基于网格的数值解决方案和神经网络近似。

</details>

<details>
<summary><b>9. LLM agent safety, multi-turn red-teaming, jailbreak benchmarks, adversarial robustness, safety-critical systems</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Hanwool Lee、Dasol Choi、Bokyeong Kim、Seung Geun Kim、Haon Park |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-06-18T15:57:53Z |
| **关键词** | `LLM Agent` · `Benchmark` · `Evaluation` · `Simulation` |
| **原文链接** | [http://arxiv.org/abs/2606.20408v1](http://arxiv.org/abs/2606.20408v1) |

**📝 摘要概括：**

> 大型语言模型（ LLM ）代理越来越多地被提出作为安全关键系统的监督组件，但它们在持续、自适应对抗压力下的鲁棒性仍然很差。我们展示了NRT-Bench ，这是在模拟核电站控制室中实例化的充当安全关键系统操作员的LLM代理多匝红色团队的基准。我们发布了模拟场地、攻击数据集和……

</details>

<details>
<summary><b>10. DataMagic: Transforming Tabular Data into Data Insight Video</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Yupeng Xie、Chen Ma、Zhenyang Wang、Liangwei Wang、Jiayi Zhu 等（共 9 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | HIT |
| **发布时间** | 2026-06-18T15:45:05Z |
| **关键词** | `Multi-Agent` · `RAG` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2606.20388v1](http://arxiv.org/abs/2606.20388v1) |

**📝 摘要概括：**

> 数据视频集成了动态图表、语音旁白和同步动画，将数据见解作为时间叙述进行沟通，使其成为提高数据管理生命周期中数据消耗效率的有效媒介。然而，制作高质量的数据视频需要跨越数据分析、叙事设计和视频制作的专业知识。主页： https://datamagic-home.github.io/

</details>

<details>
<summary><b>11. CRAX: Fast Safe Reinforcement Learning Benchmarking</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Tristan Tomilin、Mourad Boustani、Mickey Beurskens、Thiago D. Simão |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT |
| **发布时间** | 2026-06-18T15:36:13Z |
| **关键词** | `Reinforcement Learning` · `RAG` · `Benchmark` · `Robotics` |
| **原文链接** | [http://arxiv.org/abs/2606.20376v1](http://arxiv.org/abs/2606.20376v1) |

**📝 摘要概括：**

> 在机器人和自动驾驶等现实领域部署强化学习（ RL ）代理时，安全是一个核心问题。虽然基准测试一直是强化学习进展的核心，但现有的高保真3D物理安全基准测试的计算速度仍然很慢，限制了大规模实验和快速原型设计。我们发现，跨难度级别和安全转移的课程学习可以提高绩效，而不是直接……

</details>

<details>
<summary><b>12. AutoPass: Evidence-Guided LLM Agents for Compiler Performance Tuning</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Zepeng Li、Jie Ren、Zhanyong Tang、Jie Zheng、Zheng Wang |
| **所属机构** | （详见原文） |
| **顶级机构标签** | HIT、TRI |
| **发布时间** | 2026-06-18T15:35:40Z |
| **关键词** | `Multi-Agent` · `LLM Agent` · `Benchmark` · `Fine-tuning` |
| **原文链接** | [http://arxiv.org/abs/2606.20373v1](http://arxiv.org/abs/2606.20373v1) |

**📝 摘要概括：**

> 大型语言模型（ LLM ）显示出对代码编译任务的承诺，但由于复杂的微架构效应和嘈杂的运行时测量，将它们应用于运行时性能调优很困难。我们推出了AutoPass ，这是一个用于编译器性能调整的多代理框架，它使用编译器和运行时证据来指导LLM生成的优化决策。AutoPass的表现优于专家调优的启发式方法和经典的自动调优方法。

</details>

<details>
<summary><b>13. Automating SKILL.md Generation for Computer-Using Agents via Interaction Trajectory Mining</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Yuexing Hao、Xiaomin Li |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-06-18T15:25:42Z |
| **关键词** | `Benchmark` · `Workflow` |
| **原文链接** | [http://arxiv.org/abs/2606.20363v1](http://arxiv.org/abs/2606.20363v1) |

**📝 摘要概括：**

> 显式技能库使使用计算机的代理更容易检查，但目前尚不清楚这些库是否可以通过改善下游策略的方式从交互数据中挖掘出来。我们通过一个三阶段的管道来研究这个问题，该管道将GUI轨迹细分，将细分聚类为候选技能，并从所产生的注释中训练技能感知策略。因此，我们将该方法作为诊断研究提出： trajecto…

</details>

<details>
<summary><b>14. SoftSkill: Behavioral Compression for Contextual Adaptation</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Xijia Tao、Yihua Teng、Xinyu Fu、Ziru Liu、Kecheng Chen 等（共 9 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、CAS |
| **发布时间** | 2026-06-18T15:04:47Z |
| **关键词** | `Agentic` |
| **原文链接** | [http://arxiv.org/abs/2606.20333v1](http://arxiv.org/abs/2606.20333v1) |

**📝 摘要概括：**

> 代理技能通常部署为自然语言Markdown文件，用于编码应答策略、证据使用习惯和任务过程。这些文件是可读和可移植的，但它们是间接消耗的：对于每个任务实例，冻结的语言模型必须将长文本工件转换为生成时间行为。更广泛地说，结果表明，一些任务技能被更好地对待，而不是作为额外的Markdown来重新解释……

</details>

<details>
<summary><b>15. A Model-Driven Approach for Developing Families of Reinforcement Learning Environments</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Xiaoran Liu、Istvan David |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、Mila |
| **发布时间** | 2026-06-18T15:02:38Z |
| **关键词** | `Reinforcement Learning` |
| **原文链接** | [http://arxiv.org/abs/2606.20324v1](http://arxiv.org/abs/2606.20324v1) |

**📝 摘要概括：**

> 虚拟培训环境是软件密集型系统，其中强化学习（ RL ）代理学习、适应和展示有意义的行为。虚拟培训环境为现实环境中的代理人培训提供了一种安全且具有成本效益的替代方案。我们在野火缓解情景和课程学习中展示了我们方法的合理性-这是一种依赖于环境家庭的特定学习范式。

</details>

<details>
<summary><b>16. Navigating Unreliable Parametric and Contextual Knowledge: Explicit Knowledge Conflict Resolution for LLM Inference</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Huang Peng、Jiuyang Tang、Weixin Zeng、Hao Xu、Xiang Zhao |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-06-18T13:56:31Z |
| **关键词** | `Multi-Agent` · `Reasoning` · `RAG` · `Retrieval` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2606.20245v1](http://arxiv.org/abs/2606.20245v1) |

**📝 摘要概括：**

> 大型语言模型（ LLM ）通过利用广泛的参数知识和上下文学习能力，在广泛的基于语言的任务中取得了强大的表现，使他们能够将输入提示中提供的外部信息结合起来。然而，外部知识的整合不仅会引入模型的内部参数知识与外部信息之间的冲突，还会引入多元知识之间的冲突。

</details>

<details>
<summary><b>17. ScholarQuest: A Taxonomy-Guided Benchmark for Agentic Academic Paper Search in Open Literature Environments</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Tingyue Pan、Mingyue Cheng、Daoyu Wang、Yitong Zhou、Jie Ouyang 等（共 7 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | CAS、TRI |
| **发布时间** | 2026-06-18T13:47:20Z |
| **关键词** | `Agentic` · `Retrieval` · `Benchmark` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2606.20235v1](http://arxiv.org/abs/2606.20235v1) |

**📝 摘要概括：**

> 学术论文搜索是科学研究的核心步骤，基于法学硕士的搜索代理正在成为迭代、意图驱动的文献探索的一个有前途的范例。然而，现有的基准不足以系统地评估现实开放文献环境下的代理学术搜索。此外，对搜索效率、意图级鲁棒性和失败案例的分析进一步凸显了基准的能力……

</details>

<details>
<summary><b>18. Augmenting Game AI with Deep Reinforcement Learning</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Alessandro Sestini、Joakim Bergdahl、Amir Baghi、Jean-Philippe Barrette-LaPierre、Florian Fuchs 等（共 6 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT |
| **发布时间** | 2026-06-18T13:23:19Z |
| **关键词** | `Reinforcement Learning` |
| **原文链接** | [http://arxiv.org/abs/2606.20210v1](http://arxiv.org/abs/2606.20210v1) |

**📝 摘要概括：**

> 沉浸在视频游戏中不仅取决于图形、音频和游戏机制，还取决于游戏中角色的质量。制作可信的角色或游戏AI仍然是一个重大挑战，因为用手工编码系统很难捕捉到行为复杂性。此外，我们确定了这些领域的瓶颈和难题，我们认为这些领域为加速机器学习在g…

</details>

<details>
<summary><b>19. FlowMaps: Modeling Long-Term Multimodal Object Dynamics with Flow Matching</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Francesco Argenziano、Miguel Saavedra-Ruiz、Sacha Morin、Charlie Gauthier、Daniele Nardi 等（共 6 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | Mila、TRI |
| **发布时间** | 2026-06-18T13:21:40Z |
| **关键词** | — |
| **原文链接** | [http://arxiv.org/abs/2606.20209v1](http://arxiv.org/abs/2606.20209v1) |

**📝 摘要概括：**

> 对3D场景的联合空间和时间理解是部署在日常家庭环境中的机器人的关键要求。这些代理不仅必须理解和导航空间布局，还必须推理这些空间如何随着时间的推移而演变。代码和其他材料可在https://fra-tsuna.github.io/flowmaps/上获得。

</details>

<details>
<summary><b>20. MedRLM: Recursive Multimodal Health Intelligence for Long-Context Clinical Reasoning, Sensor-Guided Screening, Evidence-Grounded Decision Support, and Community-to-Tertiary Referral Optimization</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Aueaphum Aueawatthanaphisut |
| **所属机构** | （详见原文） |
| **顶级机构标签** | CAS、TRI |
| **发布时间** | 2026-06-18T12:30:39Z |
| **关键词** | `Reasoning` · `Planning` · `RAG` · `Retrieval` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2606.20164v1](http://arxiv.org/abs/2606.20164v1) |

**📝 摘要概括：**

> 现实世界的临床决策支持需要对异质和纵向的患者信息进行推理，而不是回答孤立的医疗问题。然而，当前的医学大型语言模型和检索增强生成系统通常依赖于单步提示或检索，当临床证据分布在长电子健康记录、医学图像、传感器流、指南和检索中时，这些提示或检索可能是脆弱的。

</details>

## 🗄️ 历史归档

| 日期 | 论文数 | 报告链接 |
|------|--------|----------|
| 2026-06-19 | 20 篇 | [2026-06-19.md](daily/2026-06-19.md) |
| 2026-06-18 | 11 篇 | [2026-06-18.md](daily/2026-06-18.md) |
| 2026-06-17 | 18 篇 | [2026-06-17.md](daily/2026-06-17.md) |
| 2026-06-16 | 18 篇 | [2026-06-16.md](daily/2026-06-16.md) |
| 2026-06-15 | 0 篇 | [2026-06-15.md](daily/2026-06-15.md) |
| 2026-06-14 | 0 篇 | [2026-06-14.md](daily/2026-06-14.md) |
| 2026-06-13 | 0 篇 | [2026-06-13.md](daily/2026-06-13.md) |
| 2026-06-12 | 20 篇 | [2026-06-12.md](daily/2026-06-12.md) |
| 2026-06-11 | 19 篇 | [2026-06-11.md](daily/2026-06-11.md) |
| 2026-06-10 | 19 篇 | [2026-06-10.md](daily/2026-06-10.md) |
| 2026-06-09 | 20 篇 | [2026-06-09.md](daily/2026-06-09.md) |
| 2026-06-08 | 0 篇 | [2026-06-08.md](daily/2026-06-08.md) |
| 2026-06-07 | 0 篇 | [2026-06-07.md](daily/2026-06-07.md) |
| 2026-06-06 | 0 篇 | [2026-06-06.md](daily/2026-06-06.md) |
| 2026-06-05 | 20 篇 | [2026-06-05.md](daily/2026-06-05.md) |
| 2026-06-04 | 0 篇 | [2026-06-04.md](daily/2026-06-04.md) |
| 2026-06-03 | 20 篇 | [2026-06-03.md](daily/2026-06-03.md) |
| 2026-06-02 | 20 篇 | [2026-06-02.md](daily/2026-06-02.md) |
| 2026-06-01 | 0 篇 | [2026-06-01.md](daily/2026-06-01.md) |
| 2026-05-31 | 0 篇 | [2026-05-31.md](daily/2026-05-31.md) |
| 2026-05-30 | 0 篇 | [2026-05-30.md](daily/2026-05-30.md) |
| 2026-05-29 | 0 篇 | [2026-05-29.md](daily/2026-05-29.md) |
| 2026-05-28 | 0 篇 | [2026-05-28.md](daily/2026-05-28.md) |
| 2026-05-27 | 0 篇 | [2026-05-27.md](daily/2026-05-27.md) |
| 2026-05-26 | 0 篇 | [2026-05-26.md](daily/2026-05-26.md) |
| 2026-05-25 | 0 篇 | [2026-05-25.md](daily/2026-05-25.md) |
| 2026-05-24 | 0 篇 | [2026-05-24.md](daily/2026-05-24.md) |
| 2026-05-23 | 0 篇 | [2026-05-23.md](daily/2026-05-23.md) |
| 2026-05-22 | 20 篇 | [2026-05-22.md](daily/2026-05-22.md) |
| 2026-05-21 | 0 篇 | [2026-05-21.md](daily/2026-05-21.md) |

## 🏛️ 顶级机构覆盖范围

覆盖超过 **70 个**顶级 AI 机构，包括：

- **科技公司：** Microsoft、Google DeepMind、OpenAI、Anthropic、Meta AI、NVIDIA、Baidu、Alibaba、ByteDance 等
- **北美顶级大学：** MIT、Stanford、CMU、UC Berkeley、Harvard、Princeton、Cornell、Caltech 等
- **中国顶级大学/机构：** 清华大学、北京大学、浙大、上交大、复旦、中科院、MSRA 等
- **欧洲/其他：** Oxford、Cambridge、ETH Zurich、Mila、NUS、KAIST 等

---

*由 [clawBot DailyFindings](https://github.com/Jacob-biu/clawBot) 自动维护 | 最后更新：2026-06-19 22:56 UTC*
