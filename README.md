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

## 📅 今日论文 — 2026-07-03　　[→ 查看完整报告](daily/2026-07-03.md)

> 共筛选出 **20** 篇论文 | 更新于 2026-07-03 23:01 UTC

### 论文目录与概要

| # | 论文标题 | 核心概要 | 来源机构 | 第一作者 |
|---|---------|---------|---------|--------|
| 1 | [Distributed Attacks in Persistent-State AI Control](http://arxiv.org/abs/2607.02514v1) | 随着人工智能编码代理变得更加自主，它们越来越多地迭代交付代码，代码库在多个会话中持续存在。这种持久性创建了一个新的攻击面：未对齐或提示注入的代理可以跨拉取请求（ PR ）分发攻击，并为具有最佳自然覆盖… | TRI | Josh Hills |
| 2 | [What LLM Agents Say When No One Is Watching: Social Structur…](http://arxiv.org/abs/2607.02507v1) | LLM代理将越来越多地在社会结构化环境中采取行动，在这些环境中，角色、受众和关系环境可以塑造有利或昂贵的说法。我们研究在提示中没有任何明确目标的情况下，这种社会结构是否会改变客服代表相对于在相同条件下… | CAS、Mila | Arman Ghaffarizadeh |
| 3 | [Controllable Sim Agents with Behavior Latents](http://arxiv.org/abs/2607.02496v1) | 逼真的流量模拟需要模仿记录行为的代理，也可以沿着可解释的轴引导。这种可控性使工程师能够隔离变量，重现特定的边缘案例，并在没有实际风险的情况下测试自治系统。此外，我们的实验表明，转向指标必须与物理合理性… | MIT、CAS | Juanwu Lu |
| 4 | [TestEvo-Bench: An Executable and Live Benchmark for Test and…](http://arxiv.org/abs/2607.02469v1) | 软件测试和代码一起发展：代码更改后应进行新的或更新的测试，以记录新的软件行为。然而，现有的测试生成和更新基准通常将测试与代码更改隔离开来，并依赖于静态元数据，这些元数据不会验证测试是可执行的还是在语义… | MIT、TRI | Jiale Amber Wang |
| 5 | [EvoPolicyGym: Evaluating Autonomous Policy Evolution in Inte…](http://arxiv.org/abs/2607.02440v1) | 人们越来越期待自主代理通过反馈来改进可执行策略，但现有的评估往往会将这一过程压缩为最终分数，或将其与开放式软件工程进度混淆。我们引入了自主策略演进（ Autonomous Policy Evoluti… | TRI | Zhilin Wang |
| 6 | [QFedAgent: Quantum-Enhanced Personalized Federated Learning …](http://arxiv.org/abs/2607.02426v1) | 联合学习（ FL ）支持跨分布式设备的协作模型训练，而无需共享原始数据，使其适用于对隐私敏感的机器人传感应用。然而，多智能体系统会生成异构、非独立和相同分布（非IID ）的多模态传感器流，这会降低传统… | NTU、TRI | Quoc Bao Phan |
| 7 | [Steerability via constraints: a substrate for scalable overs…](http://arxiv.org/abs/2607.02389v1) | 编码代理有能力；人为监督是瓶颈。无限制的代理引入了安全风险，侵蚀了代码库的可扩展性，并使人工审查的成本越来越高。我们故意选择Python ：默认情况下，在语言提供最少保证的情况下，基底级监督收益最大；… | TRI | Thomas Winninger |
| 8 | [Bringing Agentic Search to Earth Observation Data Discovery](http://arxiv.org/abs/2607.02387v1) | NASA及其数据中心拥有数千个地球科学数据集和工具，如Worldview、Giovanni、Science Discovery Engine和Harmony。即使对于领域专家来说，也很难找到合适的。在… | TRI | Minghan Yu |
| 9 | [Hardware-Enforced Semantic Coordination for Safety-Critical …](http://arxiv.org/abs/2607.02376v1) | 智能人工智能的最新进展正在产生越来越复杂的自主系统，这些系统集成了大型语言模型、世界模型、优化引擎、专用神经架构、自主平台和人工操作员。虽然目前的许多研究都集中在提高推理能力上，但安全关键的实时部署还… | MIT、HIT | Uwe M. Borghoff |
| 10 | [Understanding Agent-Based Patching of Compiler Missed Optimi…](http://arxiv.org/abs/2607.02370v1) | 编译器错过优化是指编译器未能优化某些代码的情况。许多编译器开发人员需要付出努力来实现或修补这种遗漏的优化。我们进一步介绍了通过检索和蒸馏利用先前LLVM优化拉取请求的历史知识增强技术，表明它们改善了开… | CAS、Mila | Batu Guan |
| 11 | [SkillFuzz: Fuzzing Skill Composition for Implicit Intents Di…](http://arxiv.org/abs/2607.02345v1) | 基于大型语言模型（ LLM ）的代理通过指导规划和执行的可重用技能、自然语言指令文档，越来越多地实现软件工程任务的自动化。开放的技能市场使用户能够通过共同激活社区贡献的技能来组装代理，但市场运营商通常… | TRI | Jinwei Hu |
| 12 | [Grounded autonomous research: a fault-tolerant LLM pipeline …](http://arxiv.org/abs/2607.02329v1) | 自主研究代理已在执行提供校准的机器学习沙盒中演示了端到端LLM自动化。前沿物理科学截然不同：物理推理是每种方法选择的基础，工具链通常未得到充分记录，校准必须来自外部文献锚点-未支架的代理人引用但不面对… | MIT、HIT | Haonan Huang |
| 13 | [AgenticSTS: A Bounded-Memory Testbed for Long-Horizon LLM Ag…](http://arxiv.org/abs/2607.02255v1) | 长期LLM专员的记忆是关于未来每个决策允许查看的内容的合同。最简单的合约将过去的观察、工具调用和反射附加到每个提示中，这使得先前的上下文易于访问，但也将其变成一个混乱的混合体，其中任何单个内存组件的效… | TRI | Xiangchen Cheng |
| 14 | [Copewell: A Multi-Agent Swarm Architecture for Equitable Men…](http://arxiv.org/abs/2607.02245v1) | 精神健康障碍影响着全球近10亿人，但由于劳动力短缺、成本障碍和污名化，中低收入国家75%的人得不到治疗。当前人工智能驱动的健康解决方案主要依赖于单模式对话界面，这些界面遭受高遗弃率，并且无法提供针对用… | MIT、HIT | Seren Yenikent |
| 15 | [Criticality-Based Guard Rail Validation for AI Agent Decisio…](http://arxiv.org/abs/2607.02210v1) | 向完全自主的电信网络（自主网络级别4-5 ）的演变要求AI/ML代理在没有人为干预的情况下做出实时网络决策。然而，没有标准化的运行时机制可以在触发实时网络状态更改之前拦截和验证单个推理输出，从而产生错… | HIT、TRI | Ravi Kant Sharma |
| 16 | [UA-ChatDev: Uncertainty-Aware Multi-Agent Collaboration for …](http://arxiv.org/abs/2607.02186v1) | 软件开发是一项复杂的任务，需要不同角色的智能体之间进行协作。大型语言模型（LLM）催生了自主的多智能体软件开发框架，该框架利用基于角色的协作来实现需求分析、编码、测试和改进的自动化。进一步的消融研究和… | TRI | Temitayo Olamilekan Ogunsusi |
| 17 | [A$^{2}$utoLPBench: An Auto-Generated, Agent-Friendly LP Benc…](http://arxiv.org/abs/2607.02141v1) | 大多数LP-from-text基准是手写和标记的单词问题的静态数据集。一旦这样的数据集被释放，它的大小是固定的，它的难度是固定的，并且每个问题都可以泄露到未来LLM的训练数据中。由于基准是生成器而不是… | MIT | Shuo Ren |
| 18 | [ContextNest: Verifiable Context Governance for Autonomous AI…](http://arxiv.org/abs/2607.02116v1) | 自主人工智能代理越来越依赖于外部知识库，但大多数检索管道在没有出处、版本身份、完整性、可追溯性或时间点重建的持久保证的情况下提供相关性。我们将此形式化为上下文治理，并推出了ContextNext ，这… | IBM Research | Misha Sulpovar |
| 19 | [HaloGuard 1.0: An Open Weights Constitutional Classifier for…](http://arxiv.org/abs/2607.02079v1) | 我们推出了HaloGuard 1.0 ，这是输入安全的宪法分类器范式的开放式实现。它在英语和多语言提示安全基准上实现了最先进的性能，其尺寸约为当前领先的开放式防护型号的十分之一。我们将模型作为开放式权… | CAS | Navaneeth Sangameswaran |
| 20 | [Prompt Coverage Adequacy](http://arxiv.org/abs/2607.02057v1) | 近年来，越来越明显的是，大型语言模型（ LLM ）和自主代理通过将重点从编写精确的程序转移到表达意图和目标，提高了软件开发中的抽象水平。这种范式转变引入了新的挑战，特别是当提示而不是代码成为主要的开发… | MIT、TRI | Florian Tambon |

### 论文详情

<details>
<summary><b>1. Distributed Attacks in Persistent-State AI Control</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Josh Hills、Ida Caspary、Asa Cooper Stickland |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-07-02T17:59:56Z |
| **关键词** | `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2607.02514v1](http://arxiv.org/abs/2607.02514v1) |

**📝 摘要概括：**

> 随着人工智能编码代理变得更加自主，它们越来越多地迭代交付代码，代码库在多个会话中持续存在。这种持久性创建了一个新的攻击面：未对齐或提示注入的代理可以跨拉取请求（ PR ）分发攻击，并为具有最佳自然覆盖的公关定时其有效负载。将这种更强大的监视器与四监视器组合中的轨迹监视器相结合，可减少93%的渐进式攻击规避……

</details>

<details>
<summary><b>2. What LLM Agents Say When No One Is Watching: Social Structure and Latent Objective Emergence in Multi-Agent Debates</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Arman Ghaffarizadeh、Danyal Mohaddes、Aliakbar Izadkhah、Shahriar Noroozizadeh |
| **所属机构** | （详见原文） |
| **顶级机构标签** | CAS、Mila、TRI |
| **发布时间** | 2026-07-02T17:59:23Z |
| **关键词** | `Multi-Agent` · `LLM Agent` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2607.02507v1](http://arxiv.org/abs/2607.02507v1) |

**📝 摘要概括：**

> LLM代理将越来越多地在社会结构化环境中采取行动，在这些环境中，角色、受众和关系环境可以塑造有利或昂贵的说法。我们研究在提示中没有任何明确目标的情况下，这种社会结构是否会改变客服代表相对于在相同条件下引发的非记录（ OTR ）渠道公开表达的内容。我们提出了一个双渠道评估框架和互补的行为测量……

</details>

<details>
<summary><b>3. Controllable Sim Agents with Behavior Latents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Juanwu Lu、Junyu Zhu、Ziran Wang |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、CAS、TRI |
| **发布时间** | 2026-07-02T17:55:39Z |
| **关键词** | `Benchmark` · `Simulation` |
| **原文链接** | [http://arxiv.org/abs/2607.02496v1](http://arxiv.org/abs/2607.02496v1) |

**📝 摘要概括：**

> 逼真的流量模拟需要模仿记录行为的代理，也可以沿着可解释的轴引导。这种可控性使工程师能够隔离变量，重现特定的边缘案例，并在没有实际风险的情况下测试自治系统。此外，我们的实验表明，转向指标必须与物理合理性护栏一起阅读，以避免奖励黑客混淆。

</details>

<details>
<summary><b>4. TestEvo-Bench: An Executable and Live Benchmark for Test and Code Co-Evolution</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Jiale Amber Wang、Kaiyuan Wang、Pengyu Nie |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-07-02T17:35:20Z |
| **关键词** | `RAG` · `Benchmark` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2607.02469v1](http://arxiv.org/abs/2607.02469v1) |

**📝 摘要概括：**

> 软件测试和代码一起发展：代码更改后应进行新的或更新的测试，以记录新的软件行为。然而，现有的测试生成和更新基准通常将测试与代码更改隔离开来，并依赖于静态元数据，这些元数据不会验证测试是可执行的还是在语义上与代码更改相关联的。然而，在最近的基准任务中，成功率要低得多，并且显著下降……

</details>

<details>
<summary><b>5. EvoPolicyGym: Evaluating Autonomous Policy Evolution in Interactive Environments</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Zhilin Wang、Han Song、Runzhe Zhan、Jusen Du、Jiacheng Chen 等（共 16 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-07-02T17:10:13Z |
| **关键词** | `Benchmark` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2607.02440v1](http://arxiv.org/abs/2607.02440v1) |

**📝 摘要概括：**

> 人们越来越期待自主代理通过反馈来改进可执行策略，但现有的评估往往会将这一过程压缩为最终分数，或将其与开放式软件工程进度混淆。我们引入了自主策略演进（ Autonomous Policy Evolution ） ，这是一种受控评估设置，其中线束模型代理在固定的交互预算下重复编辑可执行策略系统。这些分析表明，强大的自主性……

</details>

<details>
<summary><b>6. QFedAgent: Quantum-Enhanced Personalized Federated Learning for Multi-Agent Activity Recognition</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Quoc Bao Phan、Tuy Tan Nguyen |
| **所属机构** | （详见原文） |
| **顶级机构标签** | NTU、TRI |
| **发布时间** | 2026-07-02T16:54:35Z |
| **关键词** | `Multi-Agent` |
| **原文链接** | [http://arxiv.org/abs/2607.02426v1](http://arxiv.org/abs/2607.02426v1) |

**📝 摘要概括：**

> 联合学习（ FL ）支持跨分布式设备的协作模型训练，而无需共享原始数据，使其适用于对隐私敏感的机器人传感应用。然而，多智能体系统会生成异构、非独立和相同分布（非IID ）的多模态传感器流，这会降低传统的FL算法的性能，而经典的融合模块会引入大量的参数开销和通信……

</details>

<details>
<summary><b>7. Steerability via constraints: a substrate for scalable oversight of coding agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Thomas Winninger |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-07-02T16:24:47Z |
| **关键词** | `Agentic` |
| **原文链接** | [http://arxiv.org/abs/2607.02389v1](http://arxiv.org/abs/2607.02389v1) |

**📝 摘要概括：**

> 编码代理有能力；人为监督是瓶颈。无限制的代理引入了安全风险，侵蚀了代码库的可扩展性，并使人工审查的成本越来越高。我们故意选择Python ：默认情况下，在语言提供最少保证的情况下，基底级监督收益最大；这些原则扩展到Rust等语言。

</details>

<details>
<summary><b>8. Bringing Agentic Search to Earth Observation Data Discovery</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Minghan Yu、Youran Sun、Chugang Yi、Yixin Wen、Haizhao Yang |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-07-02T16:24:16Z |
| **关键词** | `Agentic` · `Reasoning` · `Retrieval` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2607.02387v1](http://arxiv.org/abs/2607.02387v1) |

**📝 摘要概括：**

> NASA及其数据中心拥有数千个地球科学数据集和工具，如Worldview、Giovanni、Science Discovery Engine和Harmony。即使对于领域专家来说，也很难找到合适的。在这个受监督的管道之上，我们添加了一个零点代理重新排名阶段，在不进行任何额外培训的情况下，将分层N = 200子集的MRR提高了28% ，这表明LLM推理与受监督的检索是互补的。

</details>

<details>
<summary><b>9. Hardware-Enforced Semantic Coordination for Safety-Critical Real-Time Autonomous Systems</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Uwe M. Borghoff、Paolo Bottoni、Remo Pareschi |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、HIT、TRI |
| **发布时间** | 2026-07-02T16:16:41Z |
| **关键词** | `Agentic` · `Reasoning` |
| **原文链接** | [http://arxiv.org/abs/2607.02376v1](http://arxiv.org/abs/2607.02376v1) |

**📝 摘要概括：**

> 智能人工智能的最新进展正在产生越来越复杂的自主系统，这些系统集成了大型语言模型、世界模型、优化引擎、专用神经架构、自主平台和人工操作员。虽然目前的许多研究都集中在提高推理能力上，但安全关键的实时部署还需要在异构组件之间进行有界和可验证的协调，这些组件同时运行在...

</details>

<details>
<summary><b>10. Understanding Agent-Based Patching of Compiler Missed Optimizations</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Batu Guan、Zirui Wang、Shaohua Li |
| **所属机构** | （详见原文） |
| **顶级机构标签** | CAS、Mila、TRI |
| **发布时间** | 2026-07-02T16:12:32Z |
| **关键词** | `RAG` · `Retrieval` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2607.02370v1](http://arxiv.org/abs/2607.02370v1) |

**📝 摘要概括：**

> 编译器错过优化是指编译器未能优化某些代码的情况。许多编译器开发人员需要付出努力来实现或修补这种遗漏的优化。我们进一步介绍了通过检索和蒸馏利用先前LLVM优化拉取请求的历史知识增强技术，表明它们改善了开发人员一致的泛化，并在应用于实际应用时产生了实际效益。

</details>

<details>
<summary><b>11. SkillFuzz: Fuzzing Skill Composition for Implicit Intents Discovery in Open Skill Marketplaces</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Jinwei Hu、Yi Dong、Youcheng Sun、Xiaowei Huang |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-07-02T15:49:21Z |
| **关键词** | `Planning` |
| **原文链接** | [http://arxiv.org/abs/2607.02345v1](http://arxiv.org/abs/2607.02345v1) |

**📝 摘要概括：**

> 基于大型语言模型（ LLM ）的代理通过指导规划和执行的可重用技能、自然语言指令文档，越来越多地实现软件工程任务的自动化。开放的技能市场使用户能够通过共同激活社区贡献的技能来组装代理，但市场运营商通常会孤立地审计技能。在具有代表性的技能市场工作负载中， skillfuzz发现了1000多个不同的含义……

</details>

<details>
<summary><b>12. Grounded autonomous research: a fault-tolerant LLM pipeline from corpus to manuscript in frontier computational physics</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Haonan Huang |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、HIT、NUS |
| **发布时间** | 2026-07-02T15:35:41Z |
| **关键词** | `Reasoning` |
| **原文链接** | [http://arxiv.org/abs/2607.02329v1](http://arxiv.org/abs/2607.02329v1) |

**📝 摘要概括：**

> 自主研究代理已在执行提供校准的机器学习沙盒中演示了端到端LLM自动化。前沿物理科学截然不同：物理推理是每种方法选择的基础，工具链通常未得到充分记录，校准必须来自外部文献锚点-未支架的代理人引用但不面对这些锚点，使人产生幻觉。

</details>

<details>
<summary><b>13. AgenticSTS: A Bounded-Memory Testbed for Long-Horizon LLM Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Xiangchen Cheng、Yunwei Jiang、Jianwen Sun、Zizhen Li、Chuanhao Li 等（共 10 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-07-02T14:44:32Z |
| **关键词** | `LLM Agent` · `Agentic` · `Retrieval` · `Benchmark` · `Memory` |
| **原文链接** | [http://arxiv.org/abs/2607.02255v1](http://arxiv.org/abs/2607.02255v1) |

**📝 摘要概括：**

> 长期LLM专员的记忆是关于未来每个决策允许查看的内容的合同。最简单的合约将过去的观察、工具调用和反射附加到每个提示中，这使得先前的上下文易于访问，但也将其变成一个混乱的混合体，其中任何单个内存组件的效果都难以隔离。我们发布了一个可重现的测试平台： 298个已完成的轨迹，包括条件标签、冻结的记忆/技能……

</details>

<details>
<summary><b>14. Copewell: A Multi-Agent Swarm Architecture for Equitable Mental Wellness Support</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Seren Yenikent、Jack Vinijtrongjit、Katherine Ng |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、HIT、TRI |
| **发布时间** | 2026-07-02T14:40:03Z |
| **关键词** | `Multi-Agent` · `AI Agent` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2607.02245v1](http://arxiv.org/abs/2607.02245v1) |

**📝 摘要概括：**

> 精神健康障碍影响着全球近10亿人，但由于劳动力短缺、成本障碍和污名化，中低收入国家75%的人得不到治疗。当前人工智能驱动的健康解决方案主要依赖于单模式对话界面，这些界面遭受高遗弃率，并且无法提供针对用户动态情绪状态进行校准的可衡量的即时缓解。此工作有助于……

</details>

<details>
<summary><b>15. Criticality-Based Guard Rail Validation for AI Agent Decisions in Autonomous Telecom Networks</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Ravi Kant Sharma |
| **所属机构** | （详见原文） |
| **顶级机构标签** | HIT、TRI |
| **发布时间** | 2026-07-02T14:21:26Z |
| **关键词** | `Multi-Agent` · `AI Agent` · `RAG` |
| **原文链接** | [http://arxiv.org/abs/2607.02210v1](http://arxiv.org/abs/2607.02210v1) |

**📝 摘要概括：**

> 向完全自主的电信网络（自主网络级别4-5 ）的演变要求AI/ML代理在没有人为干预的情况下做出实时网络决策。然而，没有标准化的运行时机制可以在触发实时网络状态更改之前拦截和验证单个推理输出，从而产生错误自主决策的风险。我们展示了架构、算法程序、O-RAN解决方案……

</details>

<details>
<summary><b>16. UA-ChatDev: Uncertainty-Aware Multi-Agent Collaboration for Reliable Software Development</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Temitayo Olamilekan Ogunsusi、Lijun Qian、Xishuang Dong |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-07-02T13:56:57Z |
| **关键词** | `Multi-Agent` · `RAG` · `Retrieval` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2607.02186v1](http://arxiv.org/abs/2607.02186v1) |

**📝 摘要概括：**

> 软件开发是一项复杂的任务，需要不同角色的智能体之间进行协作。大型语言模型（LLM）催生了自主的多智能体软件开发框架，该框架利用基于角色的协作来实现需求分析、编码、测试和改进的自动化。进一步的消融研究和通信分析证实，感知不确定性的交互能够提高代码执行的可靠性。

</details>

<details>
<summary><b>17. A$^{2}$utoLPBench: An Auto-Generated, Agent-Friendly LP Benchmark via Inverse-KKT Construction</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Shuo Ren、Yaohui Han、Yifan Shi、Libo Shen、Haodong Lu 等（共 9 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT |
| **发布时间** | 2026-07-02T13:18:57Z |
| **关键词** | `Benchmark` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2607.02141v1](http://arxiv.org/abs/2607.02141v1) |

**📝 摘要概括：**

> 大多数LP-from-text基准是手写和标记的单词问题的静态数据集。一旦这样的数据集被释放，它的大小是固定的，它的难度是固定的，并且每个问题都可以泄露到未来LLM的训练数据中。由于基准是生成器而不是固定数据集，因此它具有固定数据集无法匹配的属性：新问题的无限供应，由$ (n, m) $设置的难度旋钮，地面真实答案校正……

</details>

<details>
<summary><b>18. ContextNest: Verifiable Context Governance for Autonomous AI Agent</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Misha Sulpovar、Benn R. Konsynski、Qaish Kanchwala、Gabe Goodhart |
| **所属机构** | PromptOwl, LLC；Goizueta Business School, Emory University；IBM Research |
| **顶级机构标签** | IBM Research |
| **发布时间** | 2026-07-02T12:51:38Z |
| **关键词** | `AI Agent` · `RAG` · `Retrieval` |
| **原文链接** | [http://arxiv.org/abs/2607.02116v1](http://arxiv.org/abs/2607.02116v1) |

**📝 摘要概括：**

> 自主人工智能代理越来越依赖于外部知识库，但大多数检索管道在没有出处、版本身份、完整性、可追溯性或时间点重建的持久保证的情况下提供相关性。我们将此形式化为上下文治理，并推出了ContextNext ，这是一种针对受管理的人工智能消耗知识库的开放式规范和参考实现。我们在……下发布了核心引擎、CLI和MCP服务器

</details>

<details>
<summary><b>19. HaloGuard 1.0: An Open Weights Constitutional Classifier for Multilingual AI Safety</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Navaneeth Sangameswaran、Preetham S、Ashmiya Lenin |
| **所属机构** | （详见原文） |
| **顶级机构标签** | CAS |
| **发布时间** | 2026-07-02T12:21:16Z |
| **关键词** | `Agentic` · `RAG` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2607.02079v1](http://arxiv.org/abs/2607.02079v1) |

**📝 摘要概括：**

> 我们推出了HaloGuard 1.0 ，这是输入安全的宪法分类器范式的开放式实现。它在英语和多语言提示安全基准上实现了最先进的性能，其尺寸约为当前领先的开放式防护型号的十分之一。我们将模型作为开放式权重发布。

</details>

<details>
<summary><b>20. Prompt Coverage Adequacy</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Florian Tambon、Michael Konstantinou、Cedric Richter、Charles Chenouard、Mark Harman 等（共 6 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-07-02T11:35:39Z |
| **关键词** | `RAG` |
| **原文链接** | [http://arxiv.org/abs/2607.02057v1](http://arxiv.org/abs/2607.02057v1) |

**📝 摘要概括：**

> 近年来，越来越明显的是，大型语言模型（ LLM ）和自主代理通过将重点从编写精确的程序转移到表达意图和目标，提高了软件开发中的抽象水平。这种范式转变引入了新的挑战，特别是当提示而不是代码成为主要的开发工件时，应该如何指导测试。这些发现表明， Prompt Cov……

</details>

## 🗄️ 历史归档

| 日期 | 论文数 | 报告链接 |
|------|--------|----------|
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
| 2026-06-10 | 19 篇 | [2026-06-10.md](daily/2026-06-10.md) |
| 2026-06-09 | 20 篇 | [2026-06-09.md](daily/2026-06-09.md) |
| 2026-06-08 | 0 篇 | [2026-06-08.md](daily/2026-06-08.md) |
| 2026-06-07 | 0 篇 | [2026-06-07.md](daily/2026-06-07.md) |
| 2026-06-06 | 0 篇 | [2026-06-06.md](daily/2026-06-06.md) |
| 2026-06-05 | 20 篇 | [2026-06-05.md](daily/2026-06-05.md) |
| 2026-06-04 | 0 篇 | [2026-06-04.md](daily/2026-06-04.md) |

## 🏛️ 顶级机构覆盖范围

覆盖超过 **70 个**顶级 AI 机构，包括：

- **科技公司：** Microsoft、Google DeepMind、OpenAI、Anthropic、Meta AI、NVIDIA、Baidu、Alibaba、ByteDance 等
- **北美顶级大学：** MIT、Stanford、CMU、UC Berkeley、Harvard、Princeton、Cornell、Caltech 等
- **中国顶级大学/机构：** 清华大学、北京大学、浙大、上交大、复旦、中科院、MSRA 等
- **欧洲/其他：** Oxford、Cambridge、ETH Zurich、Mila、NUS、KAIST 等

---

*由 [clawBot DailyFindings](https://github.com/Jacob-biu/clawBot) 自动维护 | 最后更新：2026-07-03 23:01 UTC*
