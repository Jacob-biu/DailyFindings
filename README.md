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

## 📅 今日论文 — 2026-08-29　　[→ 查看完整报告](daily/2026-08-29.md)

> 共筛选出 **8** 篇论文 | 更新于 2026-08-29 03:30 UTC

### 论文目录与概要

| # | 论文标题 | 核心概要 | 来源机构 | 第一作者 |
|---|---------|---------|---------|--------|
| 1 | [WikiSkill: Compiling Agent Experience into Persistent Knowle…](http://arxiv.org/abs/2608.27454v1) | 客服代表技能将专业知识和工作流程整合到可重用的资源中，从而扩展AI客服代表的功能。最近的工作会根据客服代表的经验自动发现此类技能，从而使客服代表能够通过互动逐步适应。这些结果证明了系统地积累和完善代理… | MIT | Liyan Tang |
| 2 | [SWE-Prime: Fewer Trajectories, Better Performance](http://arxiv.org/abs/2608.27449v1) | 为了提高大型语言模型解决实际软件问题的能力，之前的工作重点是构建大规模代理轨迹数据集，并对成功轨迹进行监督微调（ SFT ）。然而，任务成功并不能保证高质量的监督：成功的轨迹可能仍然包含无效、多余或冒… | MIT、TRI | Dewu Zheng |
| 3 | [RedEvoAgent: Automatic Red-Teaming Agent with Experience-Dri…](http://arxiv.org/abs/2608.27439v1) | 基于LLM的代理越来越多地部署在产品级执行工具中，越狱会触发有害工具的使用和持续的状态变化，比单独的不安全文本生成带来更大的风险。现有的自动红队方法通常依赖于固定攻击，而最近的代理攻击者协调多个越狱工… | CAS、TRI | Junjie Zhang |
| 4 | [Persona-Execution Separation: An Architecture Pattern for Ev…](http://arxiv.org/abs/2608.27427v1) | 受管理组织中的大型语言模型（ LLM ）代理必须让角色（指令、语气、自我呈现）自由发展，同时保持执行（有状态、受审计的工作）的可追溯性。单个信任域并不能同时满足这两种需求。当多用户部署、执行审计和预期… | HIT、CAS | Yisen Xi |
| 5 | [CLAP: Cross-Embodiment Video World Models are Zero-Shot Phys…](http://arxiv.org/abs/2608.27406v1) | 最先进的动作条件视频模型通常仅限于单个机器人实施例，防止它们利用包含丰富信号的大量异构视频数据来学习可广义物理。为了弥合这一差距，我们引入了CLAP ，这是一个跨体验的动作条件视频生成框架，可以在人类… | MIT、TRI | Kechen Liu |
| 6 | [Verify Smarter, Evolve Further: Efficient Harness Evolution …](http://arxiv.org/abs/2608.27311v1) | Agent利用语言模型代理如何使用指令、工具和运行时组件，但调整这些线束需要昂贵的验证。现有的提议和验证方法通常会对固定任务集中的每个候选人进行评分，浪费在不相关行为的推广上，并允许汇总分数掩盖特定的… | TRI | Jinghan Xu |
| 7 | [Naive Prompt Optimization: Rethinking the Need for Complex P…](http://arxiv.org/abs/2608.27266v1) | 在不同的任务中有效地改进自治代理是加速代理人工智能中的递归自我改进（ RSI ）的核心，迅速优化成为一种有前途的方法，能够提供与微调模型权重相媲美的性能提升，同时降低优化和服务的计算成本。然而，最近的… | Mila | Yuan Chang |
| 8 | [What Makes Good Agentic Data? An ACE Lens on Data Generation…](http://arxiv.org/abs/2608.27260v1) | LLM代理越来越依赖于生成的交互数据来学习如何与外部环境交互。代理数据生成必须保持环境、任务、交互和成功信号之间的一致性，同时产生有用的经验，而不仅仅是丰富的经验。总体而言，核心挑战不仅仅是生成更多数… | TRI | Xingshan Zeng |

### 论文详情

<details>
<summary><b>1. WikiSkill: Compiling Agent Experience into Persistent Knowledge for Skill Evolution</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Liyan Tang、Cyrus Rashtchian、Chun-Sung Ferng、Andrew Tomkins、Da-Cheng Juan 等（共 6 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT |
| **发布时间** | 2026-08-27T17:59:11Z |
| **关键词** | `AI Agent` · `Benchmark` · `Workflow` |
| **原文链接** | [http://arxiv.org/abs/2608.27454v1](http://arxiv.org/abs/2608.27454v1) |

**📝 摘要概括：**

> 客服代表技能将专业知识和工作流程整合到可重用的资源中，从而扩展AI客服代表的功能。最近的工作会根据客服代表的经验自动发现此类技能，从而使客服代表能够通过互动逐步适应。这些结果证明了系统地积累和完善代理经验对于开发可重复使用和可转移技能的好处。

</details>

<details>
<summary><b>2. SWE-Prime: Fewer Trajectories, Better Performance</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Dewu Zheng、Ruizhe Ye、Yanlin Wang、Yang Ye、Hongyu Zhang 等（共 10 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-08-27T17:58:10Z |
| **关键词** | `RAG` · `Fine-tuning` |
| **原文链接** | [http://arxiv.org/abs/2608.27449v1](http://arxiv.org/abs/2608.27449v1) |

**📝 摘要概括：**

> 为了提高大型语言模型解决实际软件问题的能力，之前的工作重点是构建大规模代理轨迹数据集，并对成功轨迹进行监督微调（ SFT ）。然而，任务成功并不能保证高质量的监督：成功的轨迹可能仍然包含无效、多余或冒险的步骤。在SWE-Bench Pro和SWE-Bench Verified上的实验表明，培训……

</details>

<details>
<summary><b>3. RedEvoAgent: Automatic Red-Teaming Agent with Experience-Driven Skill Evolution</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Junjie Zhang、Hui Liu、Kecheng Chen、Xianbo Mo、Changsheng Chen 等（共 6 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | CAS、TRI |
| **发布时间** | 2026-08-27T17:55:33Z |
| **关键词** | `Agentic` · `Retrieval` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2608.27439v1](http://arxiv.org/abs/2608.27439v1) |

**📝 摘要概括：**

> 基于LLM的代理越来越多地部署在产品级执行工具中，越狱会触发有害工具的使用和持续的状态变化，比单独的不安全文本生成带来更大的风险。现有的自动红队方法通常依赖于固定攻击，而最近的代理攻击者协调多个越狱工具，并通过基于轨迹的检索显示出更强的潜力。多个基准的实验， ……

</details>

<details>
<summary><b>4. Persona-Execution Separation: An Architecture Pattern for Evolving LLM Agents under Execution Audit</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Yisen Xi |
| **所属机构** | （详见原文） |
| **顶级机构标签** | HIT、CAS、TRI |
| **发布时间** | 2026-08-27T17:50:07Z |
| **关键词** | `LLM Agent` |
| **原文链接** | [http://arxiv.org/abs/2608.27427v1](http://arxiv.org/abs/2608.27427v1) |

**📝 摘要概括：**

> 受管理组织中的大型语言模型（ LLM ）代理必须让角色（指令、语气、自我呈现）自由发展，同时保持执行（有状态、受审计的工作）的可追溯性。单个信任域并不能同时满足这两种需求。当多用户部署、执行审计和预期角色流失共同保持时，该模式适用。

</details>

<details>
<summary><b>5. CLAP: Cross-Embodiment Video World Models are Zero-Shot Physical Simulators</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Kechen Liu、Ola Shorinwa |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-08-27T17:35:10Z |
| **关键词** | `RAG` |
| **原文链接** | [http://arxiv.org/abs/2608.27406v1](http://arxiv.org/abs/2608.27406v1) |

**📝 摘要概括：**

> 最先进的动作条件视频模型通常仅限于单个机器人实施例，防止它们利用包含丰富信号的大量异构视频数据来学习可广义物理。为了弥合这一差距，我们引入了CLAP ，这是一个跨体验的动作条件视频生成框架，可以在人类和机器人代理的多样化互联网规模视频上进行培训。项目……

</details>

<details>
<summary><b>6. Verify Smarter, Evolve Further: Efficient Harness Evolution through Behavior-Aware Verification</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Jinghan Xu、Yikai Zhang、Aili Chen、Weiyuan Li、Jiaqing Liang 等（共 6 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-08-27T16:12:23Z |
| **关键词** | `RAG` · `Benchmark` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2608.27311v1](http://arxiv.org/abs/2608.27311v1) |

**📝 摘要概括：**

> Agent利用语言模型代理如何使用指令、工具和运行时组件，但调整这些线束需要昂贵的验证。现有的提议和验证方法通常会对固定任务集中的每个候选人进行评分，浪费在不相关行为的推广上，并允许汇总分数掩盖特定的回归。我们的代码可在https://github.com/jhxu5214/HarnessLens上找到。

</details>

<details>
<summary><b>7. Naive Prompt Optimization: Rethinking the Need for Complex Prompt Search</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Yuan Chang、Xiaoqi Chen |
| **所属机构** | （详见原文） |
| **顶级机构标签** | Mila |
| **发布时间** | 2026-08-27T15:47:58Z |
| **关键词** | `Agentic` · `Reasoning` · `Fine-tuning` |
| **原文链接** | [http://arxiv.org/abs/2608.27266v1](http://arxiv.org/abs/2608.27266v1) |

**📝 摘要概括：**

> 在不同的任务中有效地改进自治代理是加速代理人工智能中的递归自我改进（ RSI ）的核心，迅速优化成为一种有前途的方法，能够提供与微调模型权重相媲美的性能提升，同时降低优化和服务的计算成本。然而，最近的发展越来越有利于不必要的复杂提示优化器。……

</details>

<details>
<summary><b>8. What Makes Good Agentic Data? An ACE Lens on Data Generation for LLM Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Xingshan Zeng、Zishan Xu、Boju Zhang、Yuzhou Wu、Lingzhi Wang 等（共 14 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-08-27T15:43:50Z |
| **关键词** | `LLM Agent` · `Agentic` · `RAG` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2608.27260v1](http://arxiv.org/abs/2608.27260v1) |

**📝 摘要概括：**

> LLM代理越来越依赖于生成的交互数据来学习如何与外部环境交互。代理数据生成必须保持环境、任务、交互和成功信号之间的一致性，同时产生有用的经验，而不仅仅是丰富的经验。总体而言，核心挑战不仅仅是生成更多数据，而是不断分配有效、信息丰富和非冗余的经验，作为代理商……

</details>

## 🗄️ 历史归档

| 日期 | 论文数 | 报告链接 |
|------|--------|----------|
| 2026-08-29 | 8 篇 | [2026-08-29.md](daily/2026-08-29.md) |
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

## 🏛️ 顶级机构覆盖范围

覆盖超过 **70 个**顶级 AI 机构，包括：

- **科技公司：** Microsoft、Google DeepMind、OpenAI、Anthropic、Meta AI、NVIDIA、Baidu、Alibaba、ByteDance 等
- **北美顶级大学：** MIT、Stanford、CMU、UC Berkeley、Harvard、Princeton、Cornell、Caltech 等
- **中国顶级大学/机构：** 清华大学、北京大学、浙大、上交大、复旦、中科院、MSRA 等
- **欧洲/其他：** Oxford、Cambridge、ETH Zurich、Mila、NUS、KAIST 等

---

*由 [clawBot DailyFindings](https://github.com/Jacob-biu/clawBot) 自动维护 | 最后更新：2026-08-29 03:30 UTC*
