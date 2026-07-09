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

## 📅 今日论文 — 2026-07-09　　[→ 查看完整报告](daily/2026-07-09.md)

> 共筛选出 **15** 篇论文 | 更新于 2026-07-09 23:11 UTC

### 论文目录与概要

| # | 论文标题 | 核心概要 | 来源机构 | 第一作者 |
|---|---------|---------|---------|--------|
| 1 | [Breaking Database Lock-in: Agentic Regeneration of High Perf…](http://arxiv.org/abs/2607.07696v1) | 对存储在外部数据库系统中的数据进行分析的工作负载面临着一个根本的瓶颈：数据访问完全由数据库驱动程序（如JDBC或ODBC ）保护，强制所有读取通过查询执行和其他未设计用于批量列式分析的驱动程序层。我们… | CAS | Victor Giannakouris |
| 2 | [Institutional Red-Teaming: Deployment Rules, Not Just Models…](http://arxiv.org/abs/2607.07695v1) | 我们引入了机构红队，这是一种在多Agent AI中测试部署规则的评估方法：保持Agent、目标和任务状态固定，仅更改一个规则，并将由此产生的集体行为变化归因于该规则。我们在IABench-CA中实例化… | CAS、TRI | Yujiao Chen |
| 3 | [Agon: Competitive Cross-Model RL with Implicit Rival Grading…](http://arxiv.org/abs/2607.07690v1) | 来自可验证奖励（例如GRPO ）的强化学习是当今推理模型背后的引擎，但它只给最终答案打分。目前，模型在文本中交谈；下一步是让他们在潜在的空间中共同推理。 | CAS | Vladislav Beliaev |
| 4 | [SkillCenter: A Large-Scale Source-Grounded Skill Library for…](http://arxiv.org/abs/2607.07676v1) | 自主人工智能代理可以在有限的人工审核下执行复杂的任务，但他们通常缺乏基础的操作知识，使其输出不仅可执行，而且正确、安全和可维护。我们引入了SkillCenter ，据我们所知，这是座席总数最大的开放技… | MIT、TRI | Tianming Sha |
| 5 | [CARLA-GS: Decoupling Representation, Reasoning, and Physics …](http://arxiv.org/abs/2607.07601v1) | 自动驾驶的安全评估以罕见的安全关键互动为主，这激发了模拟器的积极性，这些模拟器可以有意识地将角落案例与逼真的观察相结合。角点生成本质上是一个跨越视觉表示、场景推理和车辆轨迹生成和控制的多源问题。在Wa… | CAS、TRI | Kaicong Huang |
| 6 | [Creativity from Friction: Human-AI Interaction for Explorato…](http://arxiv.org/abs/2607.07521v1) | 基于用户输入生成最终答案的人工智能代理往往不能满足创意领域的需求。结构设计和建筑等领域需要交互式系统，帮助用户外化并开发想法，探索替代方案并完善部分解决方案。通过基于这些原则的试点设计界面以及与该领域… | HIT | Ricardo Maia Avelino |
| 7 | [Single-Rollout Asynchronous Optimization for Agentic Reinfor…](http://arxiv.org/abs/2607.07508v1) | 强化学习（ RL ）在训练大型语言模型（ LLM ）后变得越来越重要。以前用于LLM的RL管道大多是同步和批量交织的，这对于长期代理任务来说效率低下。为此， SAO已成功部署在代理RL管道中，用于训练… | TRI | Zhenyu Hou |
| 8 | [Do LLM-Generated Skills Make Better AI Data Scientists? A Co…](http://arxiv.org/abs/2607.07504v1) | 产品数据科学家经常要求基于LLM的代理帮助执行重复执行的任务，例如清理数据、编写SQL、选择统计测试和格式化结果。可重复使用的技能文件旨在通过为任务系列打包指南来避免从头开始提示。结果告诫不要使用每个… | Mila | Wei-Jung Huang |
| 9 | [Reward-Adaptive Iterative Discovery: A Case Study on Automat…](http://arxiv.org/abs/2607.07498v1) | 测试是游戏行业的一项重大工作，需要很大一部分开发预算和人力。我们展示了一个关于冰球游戏EA SPORTS NHL 26开发版本的案例研究，在这个版本中，人类玩家测试守门员AI的行为漏洞。在我们首次部署… | CAS、Mila | Florian Fuchs |
| 10 | [Beyond Attack-Success Rate: Action-Graded Severity Scale for…](http://arxiv.org/abs/2607.07474v1) | Agentic red-teaming基准测试报告注入的代理是否被泄露为单个位：攻击成功或未成功。我们认为，这种二进制攻击成功率丢弃了防御者最需要的信息，即由此产生的行为有多么有害。所有代码、提示和每… | MIT、CAS | Harry Owiredu-Ashley |
| 11 | [SpaCellAgent: A Self-Evolving LLM-Based Multi-Agent Framewor…](http://arxiv.org/abs/2607.07467v1) | 空间和单细胞转录组学在破译细胞动力学方面具有变革性。作为重建细胞发育路径的基本范式，轨迹推断（ TI ）至关重要。代码和材料可在https://github.com/LittleXH-shw/SpaC… | HIT | Songhan Wang |
| 12 | [The Blind Curator: How a Biased Judge Silently Disables Skil…](http://arxiv.org/abs/2607.07436v1) | 一个自我进化的代理通过看着他们失败来淘汰他们的坏技能，那么当法官看不到失败时会发生什么？技能退休是保持不断增长的库不低于非技能基线的结构性约束，但其保证假设无偏见的奖励，这对于法学硕士法官来说是错误的… | TRI | Xing Zhang |
| 13 | [Reason Less, Verify More: Deterministic Gates Recover a Sile…](http://arxiv.org/abs/2607.07405v1) | 使用工具的LLM代理可能会违反他们被部署执行的政策，同时似乎成功完成了任务。在策略允许的环境中，即使域策略禁止相应的状态转换，工具也可以执行任何格式良好的调用。贡献是有界的评估和可靠性结果：确定性门不… | TRI | Vikas Reddy |
| 14 | [Physics-Audited Agentic Discovery in Scientific Machine Lear…](http://arxiv.org/abs/2607.07379v1) | 在代理科学机器学习（ SciML ）中，大型语言模型（ LLM ）代理可以发现代理模型，并通过自动分数（通常是误差指标）选择一个模型。然而，低误差并不能确定预测场满足对力学至关重要的物理学，例如边界条… | CAS、Mila | Diab W. Abueidda |
| 15 | [Multi-Agent AI Control: Distributed Attacks Hamper Per-Insta…](http://arxiv.org/abs/2607.07368v1) | 人工智能控制是一系列技术，可以防止具有恶意目标的人工智能颠覆其运营商的意图。人工智能控制通常在一条轨迹上研究单个代理，但实际部署在共享基础设施上运行许多代理，最严重的风险（模型权重泄漏、训练运行中毒）… | TRI | Oliver Makins |

### 论文详情

<details>
<summary><b>1. Breaking Database Lock-in: Agentic Regeneration of High Performance Storage Readers for Database Bypass</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Victor Giannakouris、Immanuel Trummer |
| **所属机构** | （详见原文） |
| **顶级机构标签** | CAS |
| **发布时间** | 2026-07-08T17:55:00Z |
| **关键词** | `Agentic` · `RAG` · `Benchmark` · `Memory` |
| **原文链接** | [http://arxiv.org/abs/2607.07696v1](http://arxiv.org/abs/2607.07696v1) |

**📝 摘要概括：**

> 对存储在外部数据库系统中的数据进行分析的工作负载面临着一个根本的瓶颈：数据访问完全由数据库驱动程序（如JDBC或ODBC ）保护，强制所有读取通过查询执行和其他未设计用于批量列式分析的驱动程序层。我们提出了越狱，这是一种完全绕过数据库引擎的方法，通过直接读取存储文件并将数据具体化为内存列……

</details>

<details>
<summary><b>2. Institutional Red-Teaming: Deployment Rules, Not Just Models, Causally Shape Multi-Agent AI Safety</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Yujiao Chen |
| **所属机构** | （详见原文） |
| **顶级机构标签** | CAS、TRI |
| **发布时间** | 2026-07-08T17:53:56Z |
| **关键词** | `Multi-Agent` · `Reasoning` · `Benchmark` · `Evaluation` · `Workflow` |
| **原文链接** | [http://arxiv.org/abs/2607.07695v1](http://arxiv.org/abs/2607.07695v1) |

**📝 摘要概括：**

> 我们引入了机构红队，这是一种在多Agent AI中测试部署规则的评估方法：保持Agent、目标和任务状态固定，仅更改一个规则，并将由此产生的集体行为变化归因于该规则。我们在IABench-CA中实例化该方法，这是一个结果分配基准，跨越228个上下文，五个规范规则和七个模型群体（ 33,924个游戏） ，并具有规范性合作……

</details>

<details>
<summary><b>3. Agon: Competitive Cross-Model RL with Implicit Rival Grading of Reasoning</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Vladislav Beliaev |
| **所属机构** | （详见原文） |
| **顶级机构标签** | CAS |
| **发布时间** | 2026-07-08T17:49:14Z |
| **关键词** | `Reasoning` · `Reinforcement Learning` |
| **原文链接** | [http://arxiv.org/abs/2607.07690v1](http://arxiv.org/abs/2607.07690v1) |

**📝 摘要概括：**

> 来自可验证奖励（例如GRPO ）的强化学习是当今推理模型背后的引擎，但它只给最终答案打分。目前，模型在文本中交谈；下一步是让他们在潜在的空间中共同推理。

</details>

<details>
<summary><b>4. SkillCenter: A Large-Scale Source-Grounded Skill Library for Autonomous AI Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Tianming Sha、Yue Zhao、Lichao Sun、Yushun Dong |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-07-08T17:34:28Z |
| **关键词** | `AI Agent` |
| **原文链接** | [http://arxiv.org/abs/2607.07676v1](http://arxiv.org/abs/2607.07676v1) |

**📝 摘要概括：**

> 自主人工智能代理可以在有限的人工审核下执行复杂的任务，但他们通常缺乏基础的操作知识，使其输出不仅可执行，而且正确、安全和可维护。我们引入了SkillCenter ，据我们所知，这是座席总数最大的开放技能库： 24个域捆绑包中的216,938个结构化技能。所有技能都作为可离线搜索的SQLite FTS5捆绑包提供。

</details>

<details>
<summary><b>5. CARLA-GS: Decoupling Representation, Reasoning, and Physics Simulation for Autonomous Driving Corner-Case Synthesis</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Kaicong Huang、Meng Ma、Ruimin Ke |
| **所属机构** | （详见原文） |
| **顶级机构标签** | CAS、TRI |
| **发布时间** | 2026-07-08T16:20:19Z |
| **关键词** | `Multi-Agent` · `Reasoning` · `Evaluation` · `Simulation` |
| **原文链接** | [http://arxiv.org/abs/2607.07601v1](http://arxiv.org/abs/2607.07601v1) |

**📝 摘要概括：**

> 自动驾驶的安全评估以罕见的安全关键互动为主，这激发了模拟器的积极性，这些模拟器可以有意识地将角落案例与逼真的观察相结合。角点生成本质上是一个跨越视觉表示、场景推理和车辆轨迹生成和控制的多源问题。在Waymo Open Dataset上的实验表明，无论是定量和定性的，我们的框架……

</details>

<details>
<summary><b>6. Creativity from Friction: Human-AI Interaction for Exploratory Structural Design</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Ricardo Maia Avelino、Rita Sevastjanova、Tom Van Mele、Philippe Block、Mennatallah El-Assady |
| **所属机构** | （详见原文） |
| **顶级机构标签** | HIT |
| **发布时间** | 2026-07-08T15:17:23Z |
| **关键词** | `AI Agent` |
| **原文链接** | [http://arxiv.org/abs/2607.07521v1](http://arxiv.org/abs/2607.07521v1) |

**📝 摘要概括：**

> 基于用户输入生成最终答案的人工智能代理往往不能满足创意领域的需求。结构设计和建筑等领域需要交互式系统，帮助用户外化并开发想法，探索替代方案并完善部分解决方案。通过基于这些原则的试点设计界面以及与该领域专家的研究，本文展示了结构设计师如何感知交互式人工智能系统……

</details>

<details>
<summary><b>7. Single-Rollout Asynchronous Optimization for Agentic Reinforcement Learning</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Zhenyu Hou、Yujiang Li、Jie Tang、Yuxiao Dong |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-07-08T15:02:19Z |
| **关键词** | `Agentic` · `Reasoning` · `Reinforcement Learning` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2607.07508v1](http://arxiv.org/abs/2607.07508v1) |

**📝 摘要概括：**

> 强化学习（ RL ）在训练大型语言模型（ LLM ）后变得越来越重要。以前用于LLM的RL管道大多是同步和批量交织的，这对于长期代理任务来说效率低下。为此， SAO已成功部署在代理RL管道中，用于训练开放式GLM-5.2模型（ 750B-A40B ）。

</details>

<details>
<summary><b>8. Do LLM-Generated Skills Make Better AI Data Scientists? A Component Ablation Across Data-Science Workflows</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Wei-Jung Huang |
| **所属机构** | （详见原文） |
| **顶级机构标签** | Mila |
| **发布时间** | 2026-07-08T15:00:16Z |
| **关键词** | `Workflow` |
| **原文链接** | [http://arxiv.org/abs/2607.07504v1](http://arxiv.org/abs/2607.07504v1) |

**📝 摘要概括：**

> 产品数据科学家经常要求基于LLM的代理帮助执行重复执行的任务，例如清理数据、编写SQL、选择统计测试和格式化结果。可重复使用的技能文件旨在通过为任务系列打包指南来避免从头开始提示。结果告诫不要使用每个数据科学工作流程一个LLM生成的技能作为默认的单次提示策略。

</details>

<details>
<summary><b>9. Reward-Adaptive Iterative Discovery: A Case Study on Automated Game Testing for NHL26</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Florian Fuchs、Jessy Gosselin-Grant、Boris Skuin、Michele Petteni、Alessandro Sestini 等（共 8 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | CAS、Mila |
| **发布时间** | 2026-07-08T14:57:39Z |
| **关键词** | `Reinforcement Learning` |
| **原文链接** | [http://arxiv.org/abs/2607.07498v1](http://arxiv.org/abs/2607.07498v1) |

**📝 摘要概括：**

> 测试是游戏行业的一项重大工作，需要很大一部分开发预算和人力。我们展示了一个关于冰球游戏EA SPORTS NHL 26开发版本的案例研究，在这个版本中，人类玩家测试守门员AI的行为漏洞。在我们首次部署这种方法时，在一个实验中，我们能够发现六种曲棍球得分利用策略，这些策略在性质上类似于……

</details>

<details>
<summary><b>10. Beyond Attack-Success Rate: Action-Graded Severity Scale for Tool-Using AI Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Harry Owiredu-Ashley |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、CAS、TRI |
| **发布时间** | 2026-07-08T14:38:01Z |
| **关键词** | `AI Agent` · `Agentic` · `Benchmark` · `Simulation` |
| **原文链接** | [http://arxiv.org/abs/2607.07474v1](http://arxiv.org/abs/2607.07474v1) |

**📝 摘要概括：**

> Agentic red-teaming基准测试报告注入的代理是否被泄露为单个位：攻击成功或未成功。我们认为，这种二进制攻击成功率丢弃了防御者最需要的信息，即由此产生的行为有多么有害。所有代码、提示和每集日志均已发布。

</details>

<details>
<summary><b>11. SpaCellAgent: A Self-Evolving LLM-Based Multi-Agent Framework for Trajectory Analysis</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Songhan Wang、Haoang Chi、He Li、Zhiheng Zhang、Jiayan Yuan 等（共 9 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | HIT |
| **发布时间** | 2026-07-08T14:31:46Z |
| **关键词** | `Multi-Agent` · `Planning` · `Workflow` |
| **原文链接** | [http://arxiv.org/abs/2607.07467v1](http://arxiv.org/abs/2607.07467v1) |

**📝 摘要概括：**

> 空间和单细胞转录组学在破译细胞动力学方面具有变革性。作为重建细胞发育路径的基本范式，轨迹推断（ TI ）至关重要。代码和材料可在https://github.com/LittleXH-shw/SpaCellAgent上获得。

</details>

<details>
<summary><b>12. The Blind Curator: How a Biased Judge Silently Disables Skill Retirement in Self-Evolving Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Xing Zhang、Yanwei Cui、Guanghui Wang、Ziyuan Li、Wei Qiu 等（共 7 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-07-08T14:08:04Z |
| **关键词** | — |
| **原文链接** | [http://arxiv.org/abs/2607.07436v1](http://arxiv.org/abs/2607.07436v1) |

**📝 摘要概括：**

> 一个自我进化的代理通过看着他们失败来淘汰他们的坏技能，那么当法官看不到失败时会发生什么？技能退休是保持不断增长的库不低于非技能基线的结构性约束，但其保证假设无偏见的奖励，这对于法学硕士法官来说是错误的，因为无参考任务强加给我们。然后，廉价的缺陷注入审核在部署前告诉操作员……的哪一边

</details>

<details>
<summary><b>13. Reason Less, Verify More: Deterministic Gates Recover a Silent Policy-Violation Failure Mode in Tool-Using LLM Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Vikas Reddy、Sumanth Reddy Challaram、Abhishek Basu |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-07-08T13:38:54Z |
| **关键词** | `LLM Agent` · `Reasoning` · `Benchmark` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2607.07405v1](http://arxiv.org/abs/2607.07405v1) |

**📝 摘要概括：**

> 使用工具的LLM代理可能会违反他们被部署执行的政策，同时似乎成功完成了任务。在策略允许的环境中，即使域策略禁止相应的状态转换，工具也可以执行任何格式良好的调用。贡献是有界的评估和可靠性结果：确定性门不能保证任务成功，但它们可以确定性地阻止已知的类…

</details>

<details>
<summary><b>14. Physics-Audited Agentic Discovery in Scientific Machine Learning</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Diab W. Abueidda、Bilal Ahmed、Panos Pantidis、Mostafa E. Mobasher |
| **所属机构** | （详见原文） |
| **顶级机构标签** | CAS、Mila、TRI |
| **发布时间** | 2026-07-08T13:10:35Z |
| **关键词** | `Agentic` · `Workflow` |
| **原文链接** | [http://arxiv.org/abs/2607.07379v1](http://arxiv.org/abs/2607.07379v1) |

**📝 摘要概括：**

> 在代理科学机器学习（ SciML ）中，大型语言模型（ LLM ）代理可以发现代理模型，并通过自动分数（通常是误差指标）选择一个模型。然而，低误差并不能确定预测场满足对力学至关重要的物理学，例如边界条件、叠加、刚度缩放或因果关系。主要的区别在于每个候选人在预测场上的物理证据，而不是……

</details>

<details>
<summary><b>15. Multi-Agent AI Control: Distributed Attacks Hamper Per-Instance Monitors</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Oliver Makins、Orazio Angelini、Zohreh Shams、Mary Phuong |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-07-08T13:03:25Z |
| **关键词** | `Multi-Agent` · `RAG` |
| **原文链接** | [http://arxiv.org/abs/2607.07368v1](http://arxiv.org/abs/2607.07368v1) |

**📝 摘要概括：**

> 人工智能控制是一系列技术，可以防止具有恶意目标的人工智能颠覆其运营商的意图。人工智能控制通常在一条轨迹上研究单个代理，但实际部署在共享基础设施上运行许多代理，最严重的风险（模型权重泄漏、训练运行中毒）似乎需要几个代理协同行动。我们很乐意与安全研究人员分享我们的控制设置FakeLab……

</details>

## 🗄️ 历史归档

| 日期 | 论文数 | 报告链接 |
|------|--------|----------|
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
| 2026-06-10 | 19 篇 | [2026-06-10.md](daily/2026-06-10.md) |

## 🏛️ 顶级机构覆盖范围

覆盖超过 **70 个**顶级 AI 机构，包括：

- **科技公司：** Microsoft、Google DeepMind、OpenAI、Anthropic、Meta AI、NVIDIA、Baidu、Alibaba、ByteDance 等
- **北美顶级大学：** MIT、Stanford、CMU、UC Berkeley、Harvard、Princeton、Cornell、Caltech 等
- **中国顶级大学/机构：** 清华大学、北京大学、浙大、上交大、复旦、中科院、MSRA 等
- **欧洲/其他：** Oxford、Cambridge、ETH Zurich、Mila、NUS、KAIST 等

---

*由 [clawBot DailyFindings](https://github.com/Jacob-biu/clawBot) 自动维护 | 最后更新：2026-07-09 23:11 UTC*
