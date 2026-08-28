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

## 📅 今日论文 — 2026-08-28　　[→ 查看完整报告](daily/2026-08-28.md)

> 共筛选出 **20** 篇论文 | 更新于 2026-08-28 05:58 UTC

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
| 9 | [LLMs in Digital EDA: A perspective on shifting roles from Ge…](http://arxiv.org/abs/2608.27184v1) | 电子设计自动化（ EDA ）通过逐渐自动化合成、优化和验证的连续几代工具提高了工程生产力。大型语言模型（ LLM ）通过实现从设计意图到硬件实现的直接转换来扩展这一轨迹。三个角色的比较表明，目前的方法… | TRI | Matthew Youngman |
| 10 | [TraceBench: Controlled Evaluation of LLM Agents for Time-Ser…](http://arxiv.org/abs/2608.27182v1) | LLM代理越来越多地应用于从真实世界系统中收集的时间序列观测中的异常检测和根本原因分析；然而，它们在这些任务上的表现尚未在受控条件下进行系统评估。我们引入了TraceBench ，这是一个基于模拟的框… | MIT、TRI | Tommaso Bendinelli |
| 11 | [When Text Misleads: Inconsistent-Aware Reasoning for Audio-G…](http://arxiv.org/abs/2608.27176v1) | 理解口头对话需要对词汇内容和语言辅助声学信号（如情绪和对话意图）进行联合推理。然而，现有的评估通常允许基于成绩单或单模态解决方案的快捷方式，从而模糊了模型是否真正基于语音中的预测。这些结果将基于成绩单… | CAS | Yen-Ju Lu |
| 12 | [Calibrated Enough to Know, Not Calibrated to Act: Fabricated…](http://arxiv.org/abs/2608.27167v1) | 一位法学硕士代理人展示了一个专业的市场小组，致力于对一个可证明的不可预测的问题进行定向调用，其频率远远高于一个人提出的问题：在12个前沿模型中，随着证据的升级，承诺从6.5%上升到54.0%。当面板上… | MIT、CAS | Pranav Aggarwal |
| 13 | [Diffusion Policies for Short-Horizon Planning in Robot Crowd…](http://arxiv.org/abs/2608.27158v1) | 机器人人群导航需要在密集、动态和多模式的人机交互下进行安全、高效的决策。现有的强化学习方法通常在每个时间步输出单个被动行动，这限制了它们代表不同短期回避策略的能力。实验表明， PDPO的成功率高于强基… | MIT | Wendong Li |
| 14 | [Thomson: Continual Learning of Frontier Models for Sovereign…](http://arxiv.org/abs/2608.27147v1) | 前沿模型的开发通常被认为是少数资金雄厚的参与者的专属职责，在开发人员和现代人工智能的多样化用户群之间造成了信息、经济和权力的不对称。最近的公共话语承认了这种担忧，呼吁SovereignAI （一个组织… | MIT | Shengzhuang Chen |
| 15 | [When Tool Outputs Become Commands: Separating Action Inducti…](http://arxiv.org/abs/2608.27146v1) | 工具增强的LLM代理必须依靠不受信任的运行时观察来完成开放式任务；然而，当工具输出不再仅仅提供数据，而是开始指定具体行动时，它们实际上变成了“命令” ，可以驱动超出用户意图的现实世界副作用。我们认为，… | MIT | Xiaokun Guo |
| 16 | [GRAIN: Bridging Name and Narrative Shifts in Real-World Grap…](http://arxiv.org/abs/2608.27142v1) | 尽管大型语言模型（ LLM ）在标准化图形任务中具有潜力，但它们在节点标识符和任务制定方面对现实世界的转变仍然很脆弱。虽然确定性图形工具对这种变化是不变的，但从嘈杂的文本中提取拓扑结构对于LLM来说是… | MIT、TRI | Zike Yuan |
| 17 | [Safety Does Not Compose: Non-Decaying Loop State for Autonom…](http://arxiv.org/abs/2608.27141v1) | 大型语言模型代理越来越多地被部署为自主循环。从一个人的目标出发，这样一个系统反复发现工作、计划、执行工具调用、验证结果，并在许多无人参与的迭代中保持状态。我们为本机Agent-SafetyBench任… | MIT、HIT | Chenhao Wu |
| 18 | [TransMeme: A Multi-Agent Framework for Cross-Cultural Meme T…](http://arxiv.org/abs/2608.27127v1) | 互联网模因是一种普遍存在的多模态在线交流形式；然而，这种交流往往涉及来自不同语言和文化背景的用户。因此，跨文化和语言调整模因是实现在线沟通中相互理解的核心挑战。我们的错误分析表明，剩下的瓶颈在于幽默重… | CAS、TRI | Jingyi Zheng |
| 19 | [A Contract-Centered Architecture for Scalable and Manageable…](http://arxiv.org/abs/2608.27086v1) | 企业人工智能部署是一个跨业务部门、应用程序和人工智能团队、测试、平台工程、基础设施、安全、运营和数据治理的协调问题。用例基准显示一个代理是否完成了一项任务，而不是如何同时拥有、更改、接纳或证明更改功能… | MIT、HIT | Yaxiao Liu |
| 20 | [FaulT-Bench: Towards Benchmarking Network Troubleshooting LL…](http://arxiv.org/abs/2608.27021v1) | 基于LLM的代理越来越多地被提议用于网络故障诊断，但现有的基准仅在准确的工单上对其进行评估，并且始终假设存在故障，实际上很少满足条件。我们提出了FaulT-Bench ，这是一个跨八个网络拓扑的200… | TRI | Kuan-Hao Tseng |

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

<details>
<summary><b>9. LLMs in Digital EDA: A perspective on shifting roles from Generation to Orchestration</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Matthew Youngman、Cristian Sestito、Themis Prodromakis |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-08-27T14:29:35Z |
| **关键词** | `RAG` |
| **原文链接** | [http://arxiv.org/abs/2608.27184v1](http://arxiv.org/abs/2608.27184v1) |

**📝 摘要概括：**

> 电子设计自动化（ EDA ）通过逐渐自动化合成、优化和验证的连续几代工具提高了工程生产力。大型语言模型（ LLM ）通过实现从设计意图到硬件实现的直接转换来扩展这一轨迹。三个角色的比较表明，目前的方法难以扩展到工业品外观设计，促使转向……

</details>

<details>
<summary><b>10. TraceBench: Controlled Evaluation of LLM Agents for Time-Series Root-Cause Attribution</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Tommaso Bendinelli、Artur Dox、Christian Holz |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-08-27T14:29:13Z |
| **关键词** | `LLM Agent` · `Evaluation` · `Simulation` |
| **原文链接** | [http://arxiv.org/abs/2608.27182v1](http://arxiv.org/abs/2608.27182v1) |

**📝 摘要概括：**

> LLM代理越来越多地应用于从真实世界系统中收集的时间序列观测中的异常检测和根本原因分析；然而，它们在这些任务上的表现尚未在受控条件下进行系统评估。我们引入了TraceBench ，这是一个基于模拟的框架，用于生成受控的根本原因归因任务。我们在……上发布数据集、座席轨迹、实验结果和排行榜

</details>

<details>
<summary><b>11. When Text Misleads: Inconsistent-Aware Reasoning for Audio-Grounded Dialogue</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Yen-Ju Lu、Yuzhe Wang、Yaohan Guan、Xiluo He、Jiarui Hai 等（共 11 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | CAS |
| **发布时间** | 2026-08-27T14:26:46Z |
| **关键词** | `Agentic` · `Reasoning` · `Benchmark` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2608.27176v1](http://arxiv.org/abs/2608.27176v1) |

**📝 摘要概括：**

> 理解口头对话需要对词汇内容和语言辅助声学信号（如情绪和对话意图）进行联合推理。然而，现有的评估通常允许基于成绩单或单模态解决方案的快捷方式，从而模糊了模型是否真正基于语音中的预测。这些结果将基于成绩单的快捷方式确定为口语对话理解的重要失败模式，并表明

</details>

<details>
<summary><b>12. Calibrated Enough to Know, Not Calibrated to Act: Fabricated Evidence Makes LLM Agents Commit to the Unknowable</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Pranav Aggarwal |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、CAS |
| **发布时间** | 2026-08-27T14:20:08Z |
| **关键词** | `LLM Agent` · `RAG` · `Fine-tuning` |
| **原文链接** | [http://arxiv.org/abs/2608.27167v1](http://arxiv.org/abs/2608.27167v1) |

**📝 摘要概括：**

> 一位法学硕士代理人展示了一个专业的市场小组，致力于对一个可证明的不可预测的问题进行定向调用，其频率远远高于一个人提出的问题：在12个前沿模型中，随着证据的升级，承诺从6.5%上升到54.0%。当面板上的每个数字都被发明出来时，它同样容易实现：制造整个显示器，所以除了问题本身之外，模型看不到任何真实的东西，仍然提升了承诺……

</details>

<details>
<summary><b>13. Diffusion Policies for Short-Horizon Planning in Robot Crowd Navigation</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Wendong Li、Jochen Garcke |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT |
| **发布时间** | 2026-08-27T14:10:39Z |
| **关键词** | `Planning` · `Benchmark` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2608.27158v1](http://arxiv.org/abs/2608.27158v1) |

**📝 摘要概括：**

> 机器人人群导航需要在密集、动态和多模式的人机交互下进行安全、高效的决策。现有的强化学习方法通常在每个时间步输出单个被动行动，这限制了它们代表不同短期回避策略的能力。实验表明， PDPO的成功率高于强基线，消融表明动作块是特别的…

</details>

<details>
<summary><b>14. Thomson: Continual Learning of Frontier Models for SovereignAI</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Shengzhuang Chen、Jerrod Parker、Yejin Bang、Andrew M. Bean、Nabeel Seedat 等（共 26 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT |
| **发布时间** | 2026-08-27T13:59:36Z |
| **关键词** | `Agentic` · `Evaluation` · `Fine-tuning` |
| **原文链接** | [http://arxiv.org/abs/2608.27147v1](http://arxiv.org/abs/2608.27147v1) |

**📝 摘要概括：**

> 前沿模型的开发通常被认为是少数资金雄厚的参与者的专属职责，在开发人员和现代人工智能的多样化用户群之间造成了信息、经济和权力的不对称。最近的公共话语承认了这种担忧，呼吁SovereignAI （一个组织独立构建、部署和管理人工智能使用的能力） ，但几乎没有提供关于如何做到这一点的具体建议……

</details>

<details>
<summary><b>15. When Tool Outputs Become Commands: Separating Action Induction from Runtime Authorization in Tool-Augmented LLM Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Xiaokun Guo、Zhen Xu、Dongdong Huo、Yanqiu Zhang、Wei Wang 等（共 8 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT |
| **发布时间** | 2026-08-27T13:59:04Z |
| **关键词** | `LLM Agent` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2608.27146v1](http://arxiv.org/abs/2608.27146v1) |

**📝 摘要概括：**

> 工具增强的LLM代理必须依靠不受信任的运行时观察来完成开放式任务；然而，当工具输出不再仅仅提供数据，而是开始指定具体行动时，它们实际上变成了“命令” ，可以驱动超出用户意图的现实世界副作用。我们认为，这种风险源于将行动归纳与执行授权混为一谈。在AgentDojo和AgentDyn中， SARA将ASR限制为不超过\ …

</details>

<details>
<summary><b>16. GRAIN: Bridging Name and Narrative Shifts in Real-World Graph Reasoning through Invariance-Rewarded Agentic RL</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Zike Yuan、Han Zhang、Jianzhi Yan、Le Liu、Cai Ke 等（共 13 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-08-27T13:53:52Z |
| **关键词** | `Multi-Agent` · `Agentic` · `Reasoning` · `Reinforcement Learning` · `RAG` |
| **原文链接** | [http://arxiv.org/abs/2608.27142v1](http://arxiv.org/abs/2608.27142v1) |

**📝 摘要概括：**

> 尽管大型语言模型（ LLM ）在标准化图形任务中具有潜力，但它们在节点标识符和任务制定方面对现实世界的转变仍然很脆弱。虽然确定性图形工具对这种变化是不变的，但从嘈杂的文本中提取拓扑结构对于LLM来说是非常脆弱的， LLM通常过度拟合表面图案。此外，它还展示了卓越的结构泛化，将……的分布外（ OOD ）差距减半。

</details>

<details>
<summary><b>17. Safety Does Not Compose: Non-Decaying Loop State for Autonomous LLM Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Chenhao Wu、Haoxuan Jia、Yang Liu、Yingguang Yang、Yuhan Lin 等（共 14 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、HIT、TRI |
| **发布时间** | 2026-08-27T13:52:31Z |
| **关键词** | `LLM Agent` · `RAG` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2608.27141v1](http://arxiv.org/abs/2608.27141v1) |

**📝 摘要概括：**

> 大型语言模型代理越来越多地被部署为自主循环。从一个人的目标出发，这样一个系统反复发现工作、计划、执行工具调用、验证结果，并在许多无人参与的迭代中保持状态。我们为本机Agent-SafetyBench任务提供了一个完整的评估协议，其中包含成对的干净和被攻击的情节，这是一个外部状态攻击套件，其决定性证据仅存在于迭代、每模式……

</details>

<details>
<summary><b>18. TransMeme: A Multi-Agent Framework for Cross-Cultural Meme Transcreation</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Jingyi Zheng、Yule Liu、Zifan Peng、Tianyi Hu、Yuemeng Zhao 等（共 7 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | CAS、TRI |
| **发布时间** | 2026-08-27T13:40:11Z |
| **关键词** | `Multi-Agent` · `RAG` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2608.27127v1](http://arxiv.org/abs/2608.27127v1) |

**📝 摘要概括：**

> 互联网模因是一种普遍存在的多模态在线交流形式；然而，这种交流往往涉及来自不同语言和文化背景的用户。因此，跨文化和语言调整模因是实现在线沟通中相互理解的核心挑战。我们的错误分析表明，剩下的瓶颈在于幽默重建和图像-文本对齐，而不是简单的文化k……

</details>

<details>
<summary><b>19. A Contract-Centered Architecture for Scalable and Manageable Agentic Runtimes</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Yaxiao Liu、Pengbo Liu、Yiwen Liu、Yihua Guan、Zhenghe Hou 等（共 6 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、HIT、CAS |
| **发布时间** | 2026-08-27T13:09:49Z |
| **关键词** | `Agentic` · `RAG` · `Benchmark` · `Workflow` |
| **原文链接** | [http://arxiv.org/abs/2608.27086v1](http://arxiv.org/abs/2608.27086v1) |

**📝 摘要概括：**

> 企业人工智能部署是一个跨业务部门、应用程序和人工智能团队、测试、平台工程、基础设施、安全、运营和数据治理的协调问题。用例基准显示一个代理是否完成了一项任务，而不是如何同时拥有、更改、接纳或证明更改功能、模型、运行时机制、容量和企业数据。它没有报告任何已完成的实施、实验……

</details>

<details>
<summary><b>20. FaulT-Bench: Towards Benchmarking Network Troubleshooting LLM Agents under Unreliable User Tickets</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Kuan-Hao Tseng、Niruth Bogahawatta、Yasod Ginige、Kunjan Patel、Kosta Dakic 等（共 6 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-08-27T12:07:10Z |
| **关键词** | `LLM Agent` · `Agentic` · `Reasoning` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2608.27021v1](http://arxiv.org/abs/2608.27021v1) |

**📝 摘要概括：**

> 基于LLM的代理越来越多地被提议用于网络故障诊断，但现有的基准仅在准确的工单上对其进行评估，并且始终假设存在故障，实际上很少满足条件。我们提出了FaulT-Bench ，这是一个跨八个网络拓扑的200个故障排除场景的基准，其中五个是从公共从业者实验室重新实施的，涵盖了真正的故障、错误的故障报告、错误的设备归因和不正确……

</details>

## 🗄️ 历史归档

| 日期 | 论文数 | 报告链接 |
|------|--------|----------|
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
| 2026-07-28 | 14 篇 | [2026-07-28.md](daily/2026-07-28.md) |

## 🏛️ 顶级机构覆盖范围

覆盖超过 **70 个**顶级 AI 机构，包括：

- **科技公司：** Microsoft、Google DeepMind、OpenAI、Anthropic、Meta AI、NVIDIA、Baidu、Alibaba、ByteDance 等
- **北美顶级大学：** MIT、Stanford、CMU、UC Berkeley、Harvard、Princeton、Cornell、Caltech 等
- **中国顶级大学/机构：** 清华大学、北京大学、浙大、上交大、复旦、中科院、MSRA 等
- **欧洲/其他：** Oxford、Cambridge、ETH Zurich、Mila、NUS、KAIST 等

---

*由 [clawBot DailyFindings](https://github.com/Jacob-biu/clawBot) 自动维护 | 最后更新：2026-08-28 05:58 UTC*
