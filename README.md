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

## 📅 今日论文 — 2026-08-04　　[→ 查看完整报告](daily/2026-08-04.md)

> 共筛选出 **20** 篇论文 | 更新于 2026-08-04 23:08 UTC

### 论文目录与概要

| # | 论文标题 | 核心概要 | 来源机构 | 第一作者 |
|---|---------|---------|---------|--------|
| 1 | [The Condition-Number Barrier in Sparse Least Squares](http://arxiv.org/abs/2608.02588v1) | 在[AS21]中， Axiotis和Sviridenko推测稀疏凸优化中对受限条件数的线性依赖性不能通过多项式时间算法来改善。我们建立了他们对最小二乘目标的推测下限，条件是Raghavendra、St… | Google、TRI | Honghao Lin |
| 2 | [UEmbed: Unified Sparse and Dense Multimodal Embeddings](http://arxiv.org/abs/2608.02583v1) | 稀疏检索是现代搜索系统的基础，从网络搜索到检索增强生成。现有的工作引入了学习稀疏检索（ LSR ） ，将精确的词汇匹配推向更丰富的语义。总体而言， UEmbed提供了一种新的范式：它在一个模型中统一了… | MIT、HIT | Tingyu Song |
| 3 | [A Taxonomy of Cognitive Capability Gaps in Generative and Ag…](http://arxiv.org/abs/2608.02553v1) | 认知人工智能旨在超越语言生成和自主任务执行，转向能够持续推理、自适应行为、持久记忆和自我调节的系统。虽然生成式和代理式人工智能在广泛的任务中表现出令人印象深刻的能力，但许多基本的认知功能仍然是分散的或… | MIT、HIT | Taye Akinrele |
| 4 | [Magnet: Detecting Cross-Session AI Misuse Through Capability…](http://arxiv.org/abs/2608.02518v1) | 最有能力的人工智能部署不是单一的模型，而是一群专门的代理人，他们委派并协调行动。这种架构释放了强大的新功能，它还引入了现有的监控、检测和缓解框架无法解决的风险。每次会话检查） ， Magnet按照其名… | MIT、HIT | Natalie Isak |
| 5 | [LiveMem: Maintaining Memory State Continuity in Long-Running…](http://arxiv.org/abs/2608.02515v1) | 长期运行的助手和客服代表使用最终超出上下文的互动流。现有的上下文保留、汇总和检索保留了对所选历史记录的访问权限，但在工作上下文更改时不提供整个生命周期的持久状态。因此， LiveMem将状态连续性确立… | NTU、TRI | Zhichen Liu |
| 6 | [RoMeRL: Balancing Feedback Coverage and the Memory-Reward Tr…](http://arxiv.org/abs/2608.02508v1) | 自我进化的LLM代理基于学习的记忆系统面临两个紧密耦合的挑战。首先，轨迹索引实用程序随着交互历史的增长而增长，从而在不断扩展的状态空间上分散有限的反馈。优惠码请访问： https://github.c… | MIT、TRI | Yi Yang |
| 7 | [Abduction Without a Body? Representational Grounding and the…](http://arxiv.org/abs/2608.02505v1) | 如果没有连续的感觉运动的实施，是否可以发生科学的诱拐？人工智能和科学哲学的最新论点认为，真正的假设生成需要一个与物理世界不断耦合的主体。贡献是一个机械的建议，一个架构和一个测试程序。 | HIT、TRI | Michael Farmer |
| 8 | [SWE-Touch: Benchmarking Coding Agents When Users Touch the C…](http://arxiv.org/abs/2608.02499v1) | 真实世界的软件开发要求编码代理在共享工作空间中运行，用户可以在正在进行的任务期间检查和修改代码，但现有的存储库级别基准通常会评估单独工作的代理或限制用户参与消息。这让我们要问：编码代理如何理解和响应共… | MIT、TRI | Yuqiao Tan |
| 9 | [Grounding Agentic VLMs with Dedicated Segmentation for Fine-…](http://arxiv.org/abs/2608.02470v1) | 视觉语言模型（ VLM ）越来越多地被部署为现实世界视觉评估管道中的推理代理，但对于细粒度、视觉模糊的目标，它们的空间接地仍然不可靠。我们在自动车辆损坏评估的背景下研究这一差距，其中划痕和发际线裂纹等… | HIT、TRI | Vishwajeet Shivaji Hogale |
| 10 | [Real-Time Detection and Repair of LLM Agent Failures](http://arxiv.org/abs/2608.02464v1) | LLM代理在情节中途失败-他们循环，级联工具错误，偏离目标，伪造结果或默默吸收损坏的内容-而标准补救措施，判断第二个LLM的每一步，成本高于代理本身。我们询问仅通过可观察的步长遥测就可以实现多少检测，… | MIT、CAS | Sunny Dubey |
| 11 | [ParEvalLayer: When Partial LLM-Agent Evaluations Support a D…](http://arxiv.org/abs/2608.02444v1) | LLM代理评估通常会在完整的基准测试运行完成之前很久就产生任务结果。部分分数很容易报告，但它没有显示观察到的任务是否支持与完成的评估相同的结论。这种差异说明了为什么仅有部分分数是不够的：报告还应说明决… | MIT | Wei-Jung Huang |
| 12 | [Agentic Incident Response through Digital Twin-Enhanced Mult…](http://arxiv.org/abs/2608.02422v1) | 事件响应目前由安全运营商使用预定义的剧本进行管理，导致缓慢、劳动密集型的安全决策过程。因此，对自动化事件响应规划的需求日益增长。在三种攻击场景中，我们的代理方法平均减少了15.1\ %的恢复执行时间，… | MIT、HIT | Yiran Gao |
| 13 | [Cooperative Coevolution for Resource-Constrained Agentic LLM…](http://arxiv.org/abs/2608.02391v1) | 使用工具的大型语言模型（ LLM ）代理产生长时间的多回合轨迹，使得基于梯度的训练后记忆密集型。进化策略（ ES ）无需反向传播即可实现高效记忆的全参数后训练，最终可以与基于梯度的强化学习（ RL ）… | NTU、TRI | Zhiyuan Wang |
| 14 | [Chess on Ice: Curling Tactical Decision-Making via Backward …](http://arxiv.org/abs/2608.02379v1) | 由于其决策过程的战术复杂性，冰壶通常被称为“冰上国际象棋”。然而，与国际象棋不同的是，从机器学习的角度来看，冰壶在很大程度上仍未得到充分的探索，之前的工作主要局限于统计方法。除了由此产生的政策之外，博… | TRI | Patrick Oberlin |
| 15 | [A Spectral Filtering Approach to Regret Analysis of Distribu…](http://arxiv.org/abs/2608.02375v1) | 本文研究了存在对抗扰动和时变凸代价的线性时不变（ LTI ）系统网络上的分布式在线控制问题。网络成本的特征在于局部成本函数的总和，其中每个局部函数仅依次向相应的代理显示。生成的界限还捕获了对网络规模和… | TRI | Ting-Jui Chang |
| 16 | [SkillTrace: Traversing a Query-Skill Graph for Composable LL…](http://arxiv.org/abs/2608.02356v1) | 大型语言模型代理越来越多地通过从库中组合可重用的技能来解决复杂的任务。为了解决这个问题，关键的挑战不仅仅是检索单独相关的技能，而是确定一个完整和可执行的技能组合。SkillTrace还在不同的主干语言… | Mila、TRI | Yue Yao |
| 17 | [Qwen-CUA: Native Computer Use for (almost) Everything](http://arxiv.org/abs/2608.02352v1) | 原生计算机使用为代理提供了一个通用界面，可以操作几乎所有可供人们使用的软件，但需要长时间的状态跟踪、大规模的交互体验以及从稀疏但可验证的结果中学习。我们介绍Qwen-CUA ，这是一种具有397B-A… | TRI | Dunjie Lu |
| 18 | [KC-Agent: A Dual-Process Cognitive Architecture for Efficien…](http://arxiv.org/abs/2608.02351v1) | 数据漂移对生产中的机器学习系统构成了重大挑战，需要不断更新模型以保持性能。我们提出了KC-Agent ，这是一种用于自动化ML模型改进的双进程认知架构，它将快速模式识别（系统1 ）与故意增量更新（系统… | HIT | Gusseppe Bravo-Rocca |
| 19 | [Can AI Agents Simulate A/B Test Outcomes? A Validation Frame…](http://arxiv.org/abs/2608.02345v1) | A/B测试仍然是技术行业推出新功能的标准。然而，每个实验都会消耗真实的流量、工程工作量和数周的挂钟时间。我们讨论了当前方法的局限性，并确定了实验者可以从代理信号中受益的应用。 | MIT、TRI | Stefan Hut |
| 20 | [Trajectories That Segment Themselves: Agent-Declared Boundar…](http://arxiv.org/abs/2608.02302v1) | 长视野编码代理轨迹与可用于训练的信用单位不匹配：单个动作没有稳定的价值，情节标签将生产性探索与放弃的方向合并，以及伐木力学落下的固定窗口切口。我们引入了集合时间语义自分割，其中声明式契约在生成轨迹的同… | TRI | Jingxi Wei |

### 论文详情

<details>
<summary><b>1. The Condition-Number Barrier in Sparse Least Squares</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Honghao Lin、Vahab Mirrokni、David P. Woodruff |
| **所属机构** | （详见原文） |
| **顶级机构标签** | Google、TRI |
| **发布时间** | 2026-08-03T17:57:01Z |
| **关键词** | `Agentic` · `RAG` |
| **原文链接** | [http://arxiv.org/abs/2608.02588v1](http://arxiv.org/abs/2608.02588v1) |

**📝 摘要概括：**

> 在[AS21]中， Axiotis和Sviridenko推测稀疏凸优化中对受限条件数的线性依赖性不能通过多项式时间算法来改善。我们建立了他们对最小二乘目标的推测下限，条件是Raghavendra、Steurer和Tulsiani [RST12]的加权正则图公式中的随机精确体积小集扩张假设。作者已验证……

</details>

<details>
<summary><b>2. UEmbed: Unified Sparse and Dense Multimodal Embeddings</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Tingyu Song、Mingxin Li、Yanzhao Zhang、Dingkun Long、Pengjun Xie 等（共 8 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、HIT、TRI |
| **发布时间** | 2026-08-03T17:54:11Z |
| **关键词** | `Agentic` · `Retrieval` |
| **原文链接** | [http://arxiv.org/abs/2608.02583v1](http://arxiv.org/abs/2608.02583v1) |

**📝 摘要概括：**

> 稀疏检索是现代搜索系统的基础，从网络搜索到检索增强生成。现有的工作引入了学习稀疏检索（ LSR ） ，将精确的词汇匹配推向更丰富的语义。总体而言， UEmbed提供了一种新的范式：它在一个模型中统一了密集和稀疏的嵌入，同时进一步扩展了稀疏检索，以统一文本和多模态输入。

</details>

<details>
<summary><b>3. A Taxonomy of Cognitive Capability Gaps in Generative and Agentic AI</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Taye Akinrele、Sindhuja Penchala、Noorbakhsh Amiri Golilarz、Sudip Mittal、Shahram Rahimi |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、HIT、TRI |
| **发布时间** | 2026-08-03T17:37:38Z |
| **关键词** | `Agentic` · `Reasoning` · `RAG` · `Evaluation` · `Memory` |
| **原文链接** | [http://arxiv.org/abs/2608.02553v1](http://arxiv.org/abs/2608.02553v1) |

**📝 摘要概括：**

> 认知人工智能旨在超越语言生成和自主任务执行，转向能够持续推理、自适应行为、持久记忆和自我调节的系统。虽然生成式和代理式人工智能在广泛的任务中表现出令人印象深刻的能力，但许多基本的认知功能仍然是分散的或薄弱的，限制了长时间的可靠操作。该调查强调了k……

</details>

<details>
<summary><b>4. Magnet: Detecting Cross-Session AI Misuse Through Capability Accumulation</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Natalie Isak、Matthew Dressman |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、HIT、CAS |
| **发布时间** | 2026-08-03T17:15:55Z |
| **关键词** | `Agentic` |
| **原文链接** | [http://arxiv.org/abs/2608.02518v1](http://arxiv.org/abs/2608.02518v1) |

**📝 摘要概括：**

> 最有能力的人工智能部署不是单一的模型，而是一群专门的代理人，他们委派并协调行动。这种架构释放了强大的新功能，它还引入了现有的监控、检测和缓解框架无法解决的风险。每次会话检查） ， Magnet按照其名称的含义行事：它从干草中吸引相关的针头，跨会话和跨时间， ……

</details>

<details>
<summary><b>5. LiveMem: Maintaining Memory State Continuity in Long-Running LLM Inference</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Zhichen Liu、Ruihan Sun、Hengjie Yang、Zipeng Wu、Zhaohan Chen 等（共 7 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | NTU、TRI |
| **发布时间** | 2026-08-03T17:12:05Z |
| **关键词** | `Retrieval` · `Memory` |
| **原文链接** | [http://arxiv.org/abs/2608.02515v1](http://arxiv.org/abs/2608.02515v1) |

**📝 摘要概括：**

> 长期运行的助手和客服代表使用最终超出上下文的互动流。现有的上下文保留、汇总和检索保留了对所选历史记录的访问权限，但在工作上下文更改时不提供整个生命周期的持久状态。因此， LiveMem将状态连续性确立为连续LLM推断的独特和互补的抽象。

</details>

<details>
<summary><b>6. RoMeRL: Balancing Feedback Coverage and the Memory-Reward Trap in Self-Evolving Agent Memory via Reduced-Order Utility States</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Yi Yang、Zhennan Chen、Yihong Zhuang、Tiehan Fan、Yinan Chen 等（共 8 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-08-03T17:07:50Z |
| **关键词** | `LLM Agent` · `Reinforcement Learning` · `RAG` · `Memory` |
| **原文链接** | [http://arxiv.org/abs/2608.02508v1](http://arxiv.org/abs/2608.02508v1) |

**📝 摘要概括：**

> 自我进化的LLM代理基于学习的记忆系统面临两个紧密耦合的挑战。首先，轨迹索引实用程序随着交互历史的增长而增长，从而在不断扩展的状态空间上分散有限的反馈。优惠码请访问： https://github.com/YOUNG-fnxm/RoMeRL

</details>

<details>
<summary><b>7. Abduction Without a Body? Representational Grounding and the Abduction Loop for Scientific Hypothesis Generation</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Michael Farmer |
| **所属机构** | （详见原文） |
| **顶级机构标签** | HIT、TRI |
| **发布时间** | 2026-08-03T17:05:31Z |
| **关键词** | `Retrieval` · `Benchmark` · `Evaluation` · `Memory` |
| **原文链接** | [http://arxiv.org/abs/2608.02505v1](http://arxiv.org/abs/2608.02505v1) |

**📝 摘要概括：**

> 如果没有连续的感觉运动的实施，是否可以发生科学的诱拐？人工智能和科学哲学的最新论点认为，真正的假设生成需要一个与物理世界不断耦合的主体。贡献是一个机械的建议，一个架构和一个测试程序。

</details>

<details>
<summary><b>8. SWE-Touch: Benchmarking Coding Agents When Users Touch the Code</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Yuqiao Tan、Jinxiang Meng、Fangyu Lei、Minzheng Wang、Shizhu He 等（共 7 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-08-03T17:03:19Z |
| **关键词** | `RAG` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2608.02499v1](http://arxiv.org/abs/2608.02499v1) |

**📝 摘要概括：**

> 真实世界的软件开发要求编码代理在共享工作空间中运行，用户可以在正在进行的任务期间检查和修改代码，但现有的存储库级别基准通常会评估单独工作的代理或限制用户参与消息。这让我们要问：编码代理如何理解和响应共享工作空间中的代码更改？这些研究结果表明，强大的自主性能尚未实现……

</details>

<details>
<summary><b>9. Grounding Agentic VLMs with Dedicated Segmentation for Fine-Grained Vehicle Damage Assessment</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Vishwajeet Shivaji Hogale、Anjali Pai、Nitya Ravi |
| **所属机构** | （详见原文） |
| **顶级机构标签** | HIT、TRI |
| **发布时间** | 2026-08-03T16:37:49Z |
| **关键词** | `Agentic` · `Reasoning` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2608.02470v1](http://arxiv.org/abs/2608.02470v1) |

**📝 摘要概括：**

> 视觉语言模型（ VLM ）越来越多地被部署为现实世界视觉评估管道中的推理代理，但对于细粒度、视觉模糊的目标，它们的空间接地仍然不可靠。我们在自动车辆损坏评估的背景下研究这一差距，其中划痕和发际线裂纹等细粒度缺陷占据很少的像素，产生微弱的梯度信号，并且容易与反射和表面混淆……

</details>

<details>
<summary><b>10. Real-Time Detection and Repair of LLM Agent Failures</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Sunny Dubey |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、CAS、TRI |
| **发布时间** | 2026-08-03T16:34:46Z |
| **关键词** | `LLM Agent` · `RAG` · `Memory` |
| **原文链接** | [http://arxiv.org/abs/2608.02464v1](http://arxiv.org/abs/2608.02464v1) |

**📝 摘要概括：**

> LLM代理在情节中途失败-他们循环，级联工具错误，偏离目标，伪造结果或默默吸收损坏的内容-而标准补救措施，判断第二个LLM的每一步，成本高于代理本身。我们询问仅通过可观察的步长遥测就可以实现多少检测，使用每步成本为微秒的监视器，并且仅在健康运行时进行培训。发布代码、跟踪和结果。

</details>

<details>
<summary><b>11. ParEvalLayer: When Partial LLM-Agent Evaluations Support a Decision</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Wei-Jung Huang、Bonan Shen |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT |
| **发布时间** | 2026-08-03T16:22:51Z |
| **关键词** | `Benchmark` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2608.02444v1](http://arxiv.org/abs/2608.02444v1) |

**📝 摘要概括：**

> LLM代理评估通常会在完整的基准测试运行完成之前很久就产生任务结果。部分分数很容易报告，但它没有显示观察到的任务是否支持与完成的评估相同的结论。这种差异说明了为什么仅有部分分数是不够的：报告还应说明决策规则以及有多少比较仍未做出决策。

</details>

<details>
<summary><b>12. Agentic Incident Response through Digital Twin-Enhanced Multiscale Planning</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Yiran Gao、Tao Li、Kim Hammar |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、HIT |
| **发布时间** | 2026-08-03T16:03:16Z |
| **关键词** | `LLM Agent` · `Agentic` · `Planning` · `Reinforcement Learning` · `RAG` |
| **原文链接** | [http://arxiv.org/abs/2608.02422v1](http://arxiv.org/abs/2608.02422v1) |

**📝 摘要概括：**

> 事件响应目前由安全运营商使用预定义的剧本进行管理，导致缓慢、劳动密集型的安全决策过程。因此，对自动化事件响应规划的需求日益增长。在三种攻击场景中，我们的代理方法平均减少了15.1\ %的恢复执行时间，并使恢复率比前沿LLM基线提高了33.6\ %。

</details>

<details>
<summary><b>13. Cooperative Coevolution for Resource-Constrained Agentic LLM Post-Training</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Zhiyuan Wang、Shengcai Liu、Jiahao Wu、Ning Lu、Hui Ouyang 等（共 8 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | NTU、TRI |
| **发布时间** | 2026-08-03T15:34:45Z |
| **关键词** | `Agentic` · `Reinforcement Learning` · `Benchmark` · `Memory` |
| **原文链接** | [http://arxiv.org/abs/2608.02391v1](http://arxiv.org/abs/2608.02391v1) |

**📝 摘要概括：**

> 使用工具的大型语言模型（ LLM ）代理产生长时间的多回合轨迹，使得基于梯度的训练后记忆密集型。进化策略（ ES ）无需反向传播即可实现高效记忆的全参数后训练，最终可以与基于梯度的强化学习（ RL ）的性能相匹配。该代码在https://github.com/MetaronWang/CoPES上开源

</details>

<details>
<summary><b>14. Chess on Ice: Curling Tactical Decision-Making via Backward Induction and Deep Reinforcement Learning</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Patrick Oberlin、Matteo Cederle、Aren Karapetyan、Saverio Bolognani、Gian Antonio Susto 等（共 6 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-08-03T15:23:42Z |
| **关键词** | `Reinforcement Learning` |
| **原文链接** | [http://arxiv.org/abs/2608.02379v1](http://arxiv.org/abs/2608.02379v1) |

**📝 摘要概括：**

> 由于其决策过程的战术复杂性，冰壶通常被称为“冰上国际象棋”。然而，与国际象棋不同的是，从机器学习的角度来看，冰壶在很大程度上仍未得到充分的探索，之前的工作主要局限于统计方法。除了由此产生的政策之外，博学的批评家还在整个连续行动空间中提供了密集的价值估计，从而可以对战术替代方案进行定量比较……

</details>

<details>
<summary><b>15. A Spectral Filtering Approach to Regret Analysis of Distributed Online Control for Linear Dynamical Systems</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Ting-Jui Chang |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-08-03T15:18:05Z |
| **关键词** | — |
| **原文链接** | [http://arxiv.org/abs/2608.02375v1](http://arxiv.org/abs/2608.02375v1) |

**📝 摘要概括：**

> 本文研究了存在对抗扰动和时变凸代价的线性时不变（ LTI ）系统网络上的分布式在线控制问题。网络成本的特征在于局部成本函数的总和，其中每个局部函数仅依次向相应的代理显示。生成的界限还捕获了对网络规模和连接的依赖性。

</details>

<details>
<summary><b>16. SkillTrace: Traversing a Query-Skill Graph for Composable LLM Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Yue Yao、Shengyuan Wang、Xin Chen、Minke Zhang、Jia He 等（共 7 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | Mila、TRI |
| **发布时间** | 2026-08-03T15:07:11Z |
| **关键词** | `LLM Agent` · `Retrieval` |
| **原文链接** | [http://arxiv.org/abs/2608.02356v1](http://arxiv.org/abs/2608.02356v1) |

**📝 摘要概括：**

> 大型语言模型代理越来越多地通过从库中组合可重用的技能来解决复杂的任务。为了解决这个问题，关键的挑战不仅仅是检索单独相关的技能，而是确定一个完整和可执行的技能组合。SkillTrace还在不同的主干语言模型中提供一致的改进，展示了基于图形的技能检索的一般性和鲁棒性。

</details>

<details>
<summary><b>17. Qwen-CUA: Native Computer Use for (almost) Everything</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Dunjie Lu、Shuai Bai、Tianyi Bai、Sicheng Fan、Chang Gao 等（共 46 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-08-03T15:04:20Z |
| **关键词** | `Benchmark` · `Workflow` |
| **原文链接** | [http://arxiv.org/abs/2608.02352v1](http://arxiv.org/abs/2608.02352v1) |

**📝 摘要概括：**

> 原生计算机使用为代理提供了一个通用界面，可以操作几乎所有可供人们使用的软件，但需要长时间的状态跟踪、大规模的交互体验以及从稀疏但可验证的结果中学习。我们介绍Qwen-CUA ，这是一种具有397B-A17B Qwen混合专家骨干的本地计算机使用代理。这些结果将本机计算机用作具有广泛功能的代理基础，并突出了可扩展的验证……

</details>

<details>
<summary><b>18. KC-Agent: A Dual-Process Cognitive Architecture for Efficient ML Model Improvement</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Gusseppe Bravo-Rocca、Jordi Guitart、Ajay Dholakia、David Ellison、Puneet Jain |
| **所属机构** | （详见原文） |
| **顶级机构标签** | HIT |
| **发布时间** | 2026-08-03T15:03:35Z |
| **关键词** | `RAG` · `Evaluation` · `Memory` |
| **原文链接** | [http://arxiv.org/abs/2608.02351v1](http://arxiv.org/abs/2608.02351v1) |

**📝 摘要概括：**

> 数据漂移对生产中的机器学习系统构成了重大挑战，需要不断更新模型以保持性能。我们提出了KC-Agent ，这是一种用于自动化ML模型改进的双进程认知架构，它将快速模式识别（系统1 ）与故意增量更新（系统2 ）相结合。我们的方法展示了以认知为灵感的自动化机器学习的理论基础和实践可行性……

</details>

<details>
<summary><b>19. Can AI Agents Simulate A/B Test Outcomes? A Validation Framework for Agentic Experimentation</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Stefan Hut、Lorenzo Masoero |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-08-03T14:58:06Z |
| **关键词** | `AI Agent` · `Agentic` · `Simulation` |
| **原文链接** | [http://arxiv.org/abs/2608.02345v1](http://arxiv.org/abs/2608.02345v1) |

**📝 摘要概括：**

> A/B测试仍然是技术行业推出新功能的标准。然而，每个实验都会消耗真实的流量、工程工作量和数周的挂钟时间。我们讨论了当前方法的局限性，并确定了实验者可以从代理信号中受益的应用。

</details>

<details>
<summary><b>20. Trajectories That Segment Themselves: Agent-Declared Boundaries as a Training Unit</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Jingxi Wei |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-08-03T14:27:58Z |
| **关键词** | — |
| **原文链接** | [http://arxiv.org/abs/2608.02302v1](http://arxiv.org/abs/2608.02302v1) |

**📝 摘要概括：**

> 长视野编码代理轨迹与可用于训练的信用单位不匹配：单个动作没有稳定的价值，情节标签将生产性探索与放弃的方向合并，以及伐木力学落下的固定窗口切口。我们引入了集合时间语义自分割，其中声明式契约在生成轨迹的同时，代理人暴露了自己的边界。

</details>

## 🗄️ 历史归档

| 日期 | 论文数 | 报告链接 |
|------|--------|----------|
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
| 2026-07-19 | 0 篇 | [2026-07-19.md](daily/2026-07-19.md) |
| 2026-07-18 | 0 篇 | [2026-07-18.md](daily/2026-07-18.md) |
| 2026-07-17 | 17 篇 | [2026-07-17.md](daily/2026-07-17.md) |
| 2026-07-16 | 11 篇 | [2026-07-16.md](daily/2026-07-16.md) |
| 2026-07-15 | 14 篇 | [2026-07-15.md](daily/2026-07-15.md) |
| 2026-07-13 | 0 篇 | [2026-07-13.md](daily/2026-07-13.md) |
| 2026-07-12 | 0 篇 | [2026-07-12.md](daily/2026-07-12.md) |
| 2026-07-11 | 0 篇 | [2026-07-11.md](daily/2026-07-11.md) |
| 2026-07-10 | 16 篇 | [2026-07-10.md](daily/2026-07-10.md) |
| 2026-07-09 | 15 篇 | [2026-07-09.md](daily/2026-07-09.md) |
| 2026-07-08 | 13 篇 | [2026-07-08.md](daily/2026-07-08.md) |
| 2026-07-07 | 18 篇 | [2026-07-07.md](daily/2026-07-07.md) |
| 2026-07-06 | 0 篇 | [2026-07-06.md](daily/2026-07-06.md) |
| 2026-07-05 | 0 篇 | [2026-07-05.md](daily/2026-07-05.md) |

## 🏛️ 顶级机构覆盖范围

覆盖超过 **70 个**顶级 AI 机构，包括：

- **科技公司：** Microsoft、Google DeepMind、OpenAI、Anthropic、Meta AI、NVIDIA、Baidu、Alibaba、ByteDance 等
- **北美顶级大学：** MIT、Stanford、CMU、UC Berkeley、Harvard、Princeton、Cornell、Caltech 等
- **中国顶级大学/机构：** 清华大学、北京大学、浙大、上交大、复旦、中科院、MSRA 等
- **欧洲/其他：** Oxford、Cambridge、ETH Zurich、Mila、NUS、KAIST 等

---

*由 [clawBot DailyFindings](https://github.com/Jacob-biu/clawBot) 自动维护 | 最后更新：2026-08-04 23:08 UTC*
