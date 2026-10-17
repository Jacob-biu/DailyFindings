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

## 📅 今日论文 — 2026-10-17　　[→ 查看完整报告](daily/2026-10-17.md)

> 共筛选出 **20** 篇论文 | 更新于 2026-10-17 00:12 UTC

### 论文目录与概要

| # | 论文标题 | 核心概要 | 来源机构 | 第一作者 |
|---|---------|---------|---------|--------|
| 1 | [LIBERO-PeRM: Benchmarking Personalized Robotic Manipulation](http://arxiv.org/abs/2610.22372v1) | 个性化对于通用机器人过渡到家庭环境并实现真正的实用性至关重要。虽然一般的机器人操作已被广泛研究，但个性化机器人操作（ PeRM ）缺乏将任务完成与偏好满意度分开的受控基准。代码、数据集和演示可在项目网… | TRI | Zhixu Li |
| 2 | [FDE-Gym: The Last Mile of AI Delivery](http://arxiv.org/abs/2610.22350v1) | 现有客服代表基准通常会根据问题报告、规格或任务工单定义的特定任务对客服代表进行评估。真实世界的客户交付是不同的：前沿部署的工程师（ FDE ）必须明确模糊的要求，在实时系统中工作，并发现未说明的约束。… | TRI | Dongxu Yang |
| 3 | [KnowGPO: Knowledge-Grouped Policy Optimization for Search Ag…](http://arxiv.org/abs/2610.22331v1) | 深度搜索代理通过长距离、多轮交互来解决知识密集型任务，在这种情况下，为个人搜索决策分配信用从根本上来说是困难的。基于结果的强化学习仅提供在整个轨迹上共享的单一终端奖励。在Xbench、BrowseCo… | TRI | Siqi Chen |
| 4 | [A team of Gemini 4 Argon agents beats Minecraft](http://arxiv.org/abs/2610.22319v1) | 我们将四名双子座4氩气特工安置在沙盒《我的世界》生存世界中，并为他们设定了一个目标：击败安德龙。每个特工通过一个名为Mineflayer的开源库控制一名玩家，并通过游戏内聊天和共享记忆与队友协调。我们… | MIT | Maxence Faldor |
| 5 | [CAT-alyzing Honesty: Continuous Adversarial Training for Tra…](http://arxiv.org/abs/2610.22292v1) | 大型语言模型（ LLM ）在诚实至关重要的场景中越来越流行。然而，尽管进行了对齐训练，这些模型仍然表现出不诚实的行为，例如输出与某些知识相矛盾或在上下文中无法访问的声明。然而，由于公用事业数据的新选择… | HIT | Yuan-Chen Chang |
| 6 | [Librarian Agents: Training LLMs to Curate Long-Context Works…](http://arxiv.org/abs/2610.22273v1) | 对于大型语言模型（ LLM ）来说，对长文档上下文的推理仍然是一个挑战。标准检索方法本质上是反应性的、瓶颈的代理，在推理时具有复杂的、跨文档的推理，而知识图等预先计算的结构通常因依赖于严格的启发式方法… | TRI | Anikait Singh |
| 7 | [X-RIC: An Agentic RAN-Intelligent Controller Benchmark for E…](http://arxiv.org/abs/2610.22269v1) | O-RAN联盟通过分解和人工智能驱动的控制引入了架构灵活性。虽然RAN智能控制器（ RIC ）实现了集中优化，但目前的人工智能方法缺乏推理能力和可解释性。X-RIC在保持SLA合规性的同时实现了89 … | HIT、TRI | Adhwaa Al-Chaab |
| 8 | [Disagreement-Guided Weak-to-Strong Routing](http://arxiv.org/abs/2610.22245v1) | 小型语言模型越来越多地部署在边缘设备和机器人系统上，以满足成本和延迟限制，但其有限的功能可能使可靠的部署具有挑战性。更强的模型可以在需要时提供帮助，但决定何时将弱模型响应路由到更强的模型通常依赖于响应… | MIT、TRI | Sima Noorani |
| 9 | [Language Is a Security Surface for Agent Guards](http://arxiv.org/abs/2610.22244v1) | 在每次工具调用之前，步骤级别的警卫会根据用户的请求和迄今为止的轨迹来决定客服代表的下一步行动是否安全。用户用多种语言编写这些请求，而专门构建的警卫培训和评估的警卫提示和基准是英语。我们发布基准和所有4… | HIT、TRI | Hasan Demirkiran |
| 10 | [Shortcut Sensitivity in Agent-Safety Evaluations](http://arxiv.org/abs/2610.22243v1) | 人工智能代理通过工具采取行动。有些操作是敏感的，因此必须对监督它们的警卫进行可靠的评估。我们建议采用域组保留、评估单元指标和安慰剂对照的配对干预措施。 | TRI | Hasan Demirkiran |
| 11 | [OS-Helix: Unifying GUI Interaction and Code Execution in Nat…](http://arxiv.org/abs/2610.22234v1) | 真正的桌面自动化既不是纯粹的可视化，也不是纯粹的程序化。代理必须了解面向用户的界面，同时有效地操作文件、脚本和系统状态。我们的项目主页位于https://os-copilot.github.io/OS… | NTU、TRI | Bowen Yang |
| 12 | [Architecting for Hardware Diversity: Meta's End-to-End Co-De…](http://arxiv.org/abs/2610.22230v1) | Meta部署了由NVIDIA GPU、AMD GPU和专有MTIA加速器组成的异构车队，以降低成本并减轻供应商锁定。但是， NVIDIA特定优化的广泛历史阻碍了其他硬件的性能可移植性。我们的贡献已经上… | NVIDIA、MIT | Haoyu Zhang |
| 13 | [FutureLift: Lifting Trajectory Proposals into Bidirectional …](http://arxiv.org/abs/2610.22215v1) | 准确的运动预测对于安全的自动驾驶至关重要，但即使是强大的预测人员也会在其多式联运提案中留下残留误差。现有的精简程序按顺序压缩完整的提案或更新其细分段，防止完整的提议未来用作明确的关系上下文进行更正。在… | CAS | Daniel Grimm |
| 14 | [Beyond Downstream QA: Rethinking How We Evaluate Agent Memor…](http://arxiv.org/abs/2610.22209v1) | 客服代表记忆基准评估客服代表的回答是否反映了正确的知识，衡量下游问答的准确性，以此作为记忆质量的代理。我们展示了这种评估范式是不完整的：它将记忆正确性与检索和生成质量混为一谈，产生了误报，其中正确的响… | TRI | Sebastian-Antonio Toma |
| 15 | [Decentralized LLM Workflows via Sequential Auctions](http://arxiv.org/abs/2610.22201v1) | 我们提出了一个可扩展的框架，通过去中心化的自利代理市场来解决多步骤任务。先前的理论工作表明，通过顺序拍卖组织的代理可以在马尔可夫决策过程（ MDP ）中收敛到全局最优策略，但依赖于完美克隆存在的限制性… | TRI | Ian Gemp |
| 16 | [AutoSFT: An Agentic System for Automated Data Research in Su…](http://arxiv.org/abs/2610.22194v1) | 语言模型代理越来越多地将训练后自动化，但是当给定完整的训练堆栈时，他们会聚集在受监督的微调上，并花费大部分精力修改训练数据。现有系统赋予代理一种控制权，从固定池中选择行或调用生成器，而人类数据工程师则… | TRI | Bingxiang He |
| 17 | [Terminal-RSI: Recursive Self-Improving Terminal Agents via R…](http://arxiv.org/abs/2610.22192v1) | 将验证器结果转换为有用的策略更新，并将部分进度转换为完整的任务解决，这对终端代理至关重要。我们提出了终端RSI ，它将已验证轨迹的递归自重写（ RSR ）与批评继承递归策略细化（ RPR ）交替。通过… | TRI | Junyao Yang |
| 18 | [Mosaic: Multi-Session Agentic Reinforcement Learning](http://arxiv.org/abs/2610.22174v1) | 大多数现有的代理强化学习方法都采用单会话轨迹，其中交互在一个连续积累的上下文中进行。然而，上下文压缩和子代理分叉等代理技术可能会产生跨越多个会话的轨迹，从而在单会话训练假设和推理时间执行之间产生不匹配… | CAS、TRI | Yilong Xu |
| 19 | [Realtime-Bench: Can Frontier Models Solve Real-time Interact…](http://arxiv.org/abs/2610.22155v1) | 实时交互要求代理感知不断变化的环境并在时间限制下采取行动，但对实时流模型的现有评估侧重于会话质量和流感知，从而使严格的时间限制下的有效行动未经测试。我们推出了Realtime-Bench ，这是一套精… | MIT、TRI | Jingyu Tang |
| 20 | [Specification Gaming and a Constrained Reinforcement Learnin…](http://arxiv.org/abs/2610.22152v1) | 强化学习代理精确地优化他们被给予的奖励信号，当该信号只是预期的真实目标的代理时，它可能会与预期的真实目标大相径庭；这种故障模式被称为规范博弈。这种故障模式的现有证据在很大程度上是观察性的，相对较少的演… | MIT | Hilda Adwubi Osei |

### 论文详情

<details>
<summary><b>1. LIBERO-PeRM: Benchmarking Personalized Robotic Manipulation</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Zhixu Li、Keqian Tang、Litian Gong、Jingyu Yao、Wenqian Zhang 等（共 10 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-10-15T17:59:59Z |
| **关键词** | `Benchmark` · `Simulation` · `Embodied AI` |
| **原文链接** | [http://arxiv.org/abs/2610.22372v1](http://arxiv.org/abs/2610.22372v1) |

**📝 摘要概括：**

> 个性化对于通用机器人过渡到家庭环境并实现真正的实用性至关重要。虽然一般的机器人操作已被广泛研究，但个性化机器人操作（ PeRM ）缺乏将任务完成与偏好满意度分开的受控基准。代码、数据集和演示可在项目网站上找到： https://libero-perm.github.io/。

</details>

<details>
<summary><b>2. FDE-Gym: The Last Mile of AI Delivery</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Dongxu Yang、Hongda Yan、Renxin Wang、Baoli Zhang、Haojia Zuo 等（共 26 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-10-15T17:57:23Z |
| **关键词** | `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2610.22350v1](http://arxiv.org/abs/2610.22350v1) |

**📝 摘要概括：**

> 现有客服代表基准通常会根据问题报告、规格或任务工单定义的特定任务对客服代表进行评估。真实世界的客户交付是不同的：前沿部署的工程师（ FDE ）必须明确模糊的要求，在实时系统中工作，并发现未说明的约束。这些结果表明，在解决明确规定的任务和为真实客户提供有效的人工智能系统之间存在巨大差距。

</details>

<details>
<summary><b>3. KnowGPO: Knowledge-Grouped Policy Optimization for Search Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Siqi Chen、Zhengxi Lu、Yuchen Yan、Xingyu Wu、Qipeng Chen 等（共 13 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-10-15T17:52:33Z |
| **关键词** | `Reinforcement Learning` |
| **原文链接** | [http://arxiv.org/abs/2610.22331v1](http://arxiv.org/abs/2610.22331v1) |

**📝 摘要概括：**

> 深度搜索代理通过长距离、多轮交互来解决知识密集型任务，在这种情况下，为个人搜索决策分配信用从根本上来说是困难的。基于结果的强化学习仅提供在整个轨迹上共享的单一终端奖励。在Xbench、BrowseComp-ZH和GAIA上的实验表明， KnowGPO的表现始终优于仅结果（ GRPO ）和流程监督基线（ GiGPO、IGPO ） 3。……

</details>

<details>
<summary><b>4. A team of Gemini 4 Argon agents beats Minecraft</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Maxence Faldor、Satinder Singh、Roberta Raileanu |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT |
| **发布时间** | 2026-10-15T17:51:32Z |
| **关键词** | `Multi-Agent` · `AI Agent` · `RAG` · `Memory` |
| **原文链接** | [http://arxiv.org/abs/2610.22319v1](http://arxiv.org/abs/2610.22319v1) |

**📝 摘要概括：**

> 我们将四名双子座4氩气特工安置在沙盒《我的世界》生存世界中，并为他们设定了一个目标：击败安德龙。每个特工通过一个名为Mineflayer的开源库控制一名玩家，并通过游戏内聊天和共享记忆与队友协调。我们描述了设置、运行如何展开、团队的策略（划分工作、分享他们学到的知识、恢复彼此的项目）以及解决方案的限制……

</details>

<details>
<summary><b>5. CAT-alyzing Honesty: Continuous Adversarial Training for Transferable LLM Honesty</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Yuan-Chen Chang、Niklas Herbster、Gauthier Gidel、Tommaso Tosato |
| **所属机构** | （详见原文） |
| **顶级机构标签** | HIT |
| **发布时间** | 2026-10-15T17:43:47Z |
| **关键词** | `Multi-Agent` · `Benchmark` · `Fine-tuning` |
| **原文链接** | [http://arxiv.org/abs/2610.22292v1](http://arxiv.org/abs/2610.22292v1) |

**📝 摘要概括：**

> 大型语言模型（ LLM ）在诚实至关重要的场景中越来越流行。然而，尽管进行了对齐训练，这些模型仍然表现出不诚实的行为，例如输出与某些知识相矛盾或在上下文中无法访问的声明。然而，由于公用事业数据的新选择， CATCH在维护公用事业方面超越了诚实导向。

</details>

<details>
<summary><b>6. Librarian Agents: Training LLMs to Curate Long-Context Workspaces that Anticipate Future Queries</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Anikait Singh、Teresa Zhang、Yoonho Lee、Roshen Sanjay Nair、Aviral Kumar 等（共 6 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-10-15T17:35:17Z |
| **关键词** | `LLM Agent` · `Agentic` · `Reasoning` · `Reinforcement Learning` · `RAG` |
| **原文链接** | [http://arxiv.org/abs/2610.22273v1](http://arxiv.org/abs/2610.22273v1) |

**📝 摘要概括：**

> 对于大型语言模型（ LLM ）来说，对长文档上下文的推理仍然是一个挑战。标准检索方法本质上是反应性的、瓶颈的代理，在推理时具有复杂的、跨文档的推理，而知识图等预先计算的结构通常因依赖于严格的启发式方法而失败。根据经验，图书管理员代理的表现优于最强的检索和预计算基线33个百分点。

</details>

<details>
<summary><b>7. X-RIC: An Agentic RAN-Intelligent Controller Benchmark for Enhancing Reinforcement Learning</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Adhwaa Al-Chaab、Ayman Younis、Dario Pompili |
| **所属机构** | （详见原文） |
| **顶级机构标签** | HIT、TRI |
| **发布时间** | 2026-10-15T17:34:17Z |
| **关键词** | `Agentic` · `Reasoning` · `Reinforcement Learning` · `Benchmark` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2610.22269v1](http://arxiv.org/abs/2610.22269v1) |

**📝 摘要概括：**

> O-RAN联盟通过分解和人工智能驱动的控制引入了架构灵活性。虽然RAN智能控制器（ RIC ）实现了集中优化，但目前的人工智能方法缺乏推理能力和可解释性。X-RIC在保持SLA合规性的同时实现了89 ％的运营成本降低，融合速度提高了75 ％ ，培训步骤减少了50 ％ ，差异降低了46 ％。

</details>

<details>
<summary><b>8. Disagreement-Guided Weak-to-Strong Routing</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Sima Noorani、Shayan Kiyani、George Pappas、Hamed Hassani |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-10-15T17:19:57Z |
| **关键词** | `Agentic` |
| **原文链接** | [http://arxiv.org/abs/2610.22245v1](http://arxiv.org/abs/2610.22245v1) |

**📝 摘要概括：**

> 小型语言模型越来越多地部署在边缘设备和机器人系统上，以满足成本和延迟限制，但其有限的功能可能使可靠的部署具有挑战性。更强的模型可以在需要时提供帮助，但决定何时将弱模型响应路由到更强的模型通常依赖于响应正确性的信号。此外，即使地面真实性正确性信号可用于训练， DISA…

</details>

<details>
<summary><b>9. Language Is a Security Surface for Agent Guards</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Hasan Demirkiran、Jens Ernstberger |
| **所属机构** | （详见原文） |
| **顶级机构标签** | HIT、TRI |
| **发布时间** | 2026-10-15T17:19:40Z |
| **关键词** | `Reasoning` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2610.22244v1](http://arxiv.org/abs/2610.22244v1) |

**📝 摘要概括：**

> 在每次工具调用之前，步骤级别的警卫会根据用户的请求和迄今为止的轨迹来决定客服代表的下一步行动是否安全。用户用多种语言编写这些请求，而专门构建的警卫培训和评估的警卫提示和基准是英语。我们发布基准和所有489k判决。

</details>

<details>
<summary><b>10. Shortcut Sensitivity in Agent-Safety Evaluations</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Hasan Demirkiran、Jens Ernstberger |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-10-15T17:18:05Z |
| **关键词** | `AI Agent` · `RAG` · `Benchmark` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2610.22243v1](http://arxiv.org/abs/2610.22243v1) |

**📝 摘要概括：**

> 人工智能代理通过工具采取行动。有些操作是敏感的，因此必须对监督它们的警卫进行可靠的评估。我们建议采用域组保留、评估单元指标和安慰剂对照的配对干预措施。

</details>

<details>
<summary><b>11. OS-Helix: Unifying GUI Interaction and Code Execution in Native Computer-Using Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Bowen Yang、Kaiming Jin、Zichen Ding、Zhenyu Wu、Zehao Li 等（共 11 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | NTU、TRI |
| **发布时间** | 2026-10-15T17:14:02Z |
| **关键词** | — |
| **原文链接** | [http://arxiv.org/abs/2610.22234v1](http://arxiv.org/abs/2610.22234v1) |

**📝 摘要概括：**

> 真正的桌面自动化既不是纯粹的可视化，也不是纯粹的程序化。代理必须了解面向用户的界面，同时有效地操作文件、脚本和系统状态。我们的项目主页位于https://os-copilot.github.io/OS-Helix/。

</details>

<details>
<summary><b>12. Architecting for Hardware Diversity: Meta's End-to-End Co-Design for High-Performance AI Training on AMD GPUs</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Haoyu Zhang、Arshad Rahman、Adnan Aziz、Ajith Prabhudev、Amin Farmahini 等（共 58 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | NVIDIA、MIT、HIT |
| **发布时间** | 2026-10-15T17:09:08Z |
| **关键词** | `Agentic` · `Workflow` |
| **原文链接** | [http://arxiv.org/abs/2610.22230v1](http://arxiv.org/abs/2610.22230v1) |

**📝 摘要概括：**

> Meta部署了由NVIDIA GPU、AMD GPU和专有MTIA加速器组成的异构车队，以降低成本并减轻供应商锁定。但是， NVIDIA特定优化的广泛历史阻碍了其他硬件的性能可移植性。我们的贡献已经上游到开源PyTorch、Triton和ROCm生态系统。

</details>

<details>
<summary><b>13. FutureLift: Lifting Trajectory Proposals into Bidirectional Future Graphs for Motion Forecasting</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Daniel Grimm、J. Marius Zöllner |
| **所属机构** | （详见原文） |
| **顶级机构标签** | CAS |
| **发布时间** | 2026-10-15T17:00:40Z |
| **关键词** | — |
| **原文链接** | [http://arxiv.org/abs/2610.22215v1](http://arxiv.org/abs/2610.22215v1) |

**📝 摘要概括：**

> 准确的运动预测对于安全的自动驾驶至关重要，但即使是强大的预测人员也会在其多式联运提案中留下残留误差。现有的精简程序按顺序压缩完整的提案或更新其细分段，防止完整的提议未来用作明确的关系上下文进行更正。在WOMD运动预测排行榜上， FutureLift在minADE （ 0.5049m ）和minFDE （ 0.9942m ）中排名第一。

</details>

<details>
<summary><b>14. Beyond Downstream QA: Rethinking How We Evaluate Agent Memory</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Sebastian-Antonio Toma、Jean de Kernier、Mike Ply、Oliviu Matei |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-10-15T16:58:12Z |
| **关键词** | `RAG` · `Retrieval` · `Benchmark` · `Evaluation` · `Memory` |
| **原文链接** | [http://arxiv.org/abs/2610.22209v1](http://arxiv.org/abs/2610.22209v1) |

**📝 摘要概括：**

> 客服代表记忆基准评估客服代表的回答是否反映了正确的知识，衡量下游问答的准确性，以此作为记忆质量的代理。我们展示了这种评估范式是不完整的：它将记忆正确性与检索和生成质量混为一谈，产生了误报，其中正确的响应掩盖了破碎的记忆，而错误的响应将正确的记忆归咎于检索失败……

</details>

<details>
<summary><b>15. Decentralized LLM Workflows via Sequential Auctions</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Ian Gemp、Shubhendu Trivedi、Adam Fisch、Fantine Huot、Michael Kaisers 等（共 10 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-10-15T16:52:16Z |
| **关键词** | `Workflow` |
| **原文链接** | [http://arxiv.org/abs/2610.22201v1](http://arxiv.org/abs/2610.22201v1) |

**📝 摘要概括：**

> 我们提出了一个可扩展的框架，通过去中心化的自利代理市场来解决多步骤任务。先前的理论工作表明，通过顺序拍卖组织的代理可以在马尔可夫决策过程（ MDP ）中收敛到全局最优策略，但依赖于完美克隆存在的限制性假设作为完美竞争的模型。在多元化的领域中，我们证明了……

</details>

<details>
<summary><b>16. AutoSFT: An Agentic System for Automated Data Research in Supervised Fine-Tuning</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Bingxiang He、Pengqi Sun、Shihao Peng、Shaoxuan Li、Huiyu Xiao 等（共 21 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-10-15T16:44:34Z |
| **关键词** | `Multi-Agent` · `Agentic` · `Fine-tuning` |
| **原文链接** | [http://arxiv.org/abs/2610.22194v1](http://arxiv.org/abs/2610.22194v1) |

**📝 摘要概括：**

> 语言模型代理越来越多地将训练后自动化，但是当给定完整的训练堆栈时，他们会聚集在受监督的微调上，并花费大部分精力修改训练数据。现有系统赋予代理一种控制权，从固定池中选择行或调用生成器，而人类数据工程师则调整比例、修剪、修复、替换和合成数据。我们的研究结果表明，自动化SFT数据研究……

</details>

<details>
<summary><b>17. Terminal-RSI: Recursive Self-Improving Terminal Agents via Recursive Self-Rewrite and Policy-Refine</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Junyao Yang、Zongxia Li、Yucheng Shi、Zhongzhi Li、Ruhan Wang 等（共 9 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-10-15T16:43:56Z |
| **关键词** | — |
| **原文链接** | [http://arxiv.org/abs/2610.22192v1](http://arxiv.org/abs/2610.22192v1) |

**📝 摘要概括：**

> 将验证器结果转换为有用的策略更新，并将部分进度转换为完整的任务解决，这对终端代理至关重要。我们提出了终端RSI ，它将已验证轨迹的递归自重写（ RSR ）与批评继承递归策略细化（ RPR ）交替。通过将经过验证的轨迹重写与批评者继承策略细化递归耦合，每个保留阶段都巩固了发现的行为和进展……

</details>

<details>
<summary><b>18. Mosaic: Multi-Session Agentic Reinforcement Learning</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Yilong Xu、Minrui Xu、Xinyu Zhou、Xiang Long、Haochen Tan 等（共 6 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | CAS、TRI |
| **发布时间** | 2026-10-15T16:32:44Z |
| **关键词** | `Agentic` · `Reinforcement Learning` · `RAG` |
| **原文链接** | [http://arxiv.org/abs/2610.22174v1](http://arxiv.org/abs/2610.22174v1) |

**📝 摘要概括：**

> 大多数现有的代理强化学习方法都采用单会话轨迹，其中交互在一个连续积累的上下文中进行。然而，上下文压缩和子代理分叉等代理技术可能会产生跨越多个会话的轨迹，从而在单会话训练假设和推理时间执行之间产生不匹配。进一步的分析表明，我们的方法在以下方面实现了改进……

</details>

<details>
<summary><b>19. Realtime-Bench: Can Frontier Models Solve Real-time Interactive Problems?</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Jingyu Tang、Xu Yang、Zhehao Zhang、Zheng Wang、Qi Cheng 等（共 10 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-10-15T16:20:47Z |
| **关键词** | `Reasoning` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2610.22155v1](http://arxiv.org/abs/2610.22155v1) |

**📝 摘要概括：**

> 实时交互要求代理感知不断变化的环境并在时间限制下采取行动，但对实时流模型的现有评估侧重于会话质量和流感知，从而使严格的时间限制下的有效行动未经测试。我们推出了Realtime-Bench ，这是一套精心策划的动态任务，延迟操作直接影响成功。这些发现为IMP提供了方向……

</details>

<details>
<summary><b>20. Specification Gaming and a Constrained Reinforcement Learning Mitigation in a Cleaning Gridworld</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Hilda Adwubi Osei |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT |
| **发布时间** | 2026-10-15T16:19:16Z |
| **关键词** | `Reinforcement Learning` |
| **原文链接** | [http://arxiv.org/abs/2610.22152v1](http://arxiv.org/abs/2610.22152v1) |

**📝 摘要概括：**

> 强化学习代理精确地优化他们被给予的奖励信号，当该信号只是预期的真实目标的代理时，它可能会与预期的真实目标大相径庭；这种故障模式被称为规范博弈。这种故障模式的现有证据在很大程度上是观察性的，相对较少的演示将受控的、故意构建的代理/真实差距与携带可验证保证的缓解措施配对……

</details>

## 🗄️ 历史归档

| 日期 | 论文数 | 报告链接 |
|------|--------|----------|
| 2026-10-17 | 20 篇 | [2026-10-17.md](daily/2026-10-17.md) |
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
| 2026-09-08 | 0 篇 | [2026-09-08.md](daily/2026-09-08.md) |
| 2026-09-07 | 0 篇 | [2026-09-07.md](daily/2026-09-07.md) |
| 2026-09-06 | 0 篇 | [2026-09-06.md](daily/2026-09-06.md) |
| 2026-09-05 | 0 篇 | [2026-09-05.md](daily/2026-09-05.md) |
| 2026-09-04 | 20 篇 | [2026-09-04.md](daily/2026-09-04.md) |

## 🏛️ 顶级机构覆盖范围

覆盖超过 **70 个**顶级 AI 机构，包括：

- **科技公司：** Microsoft、Google DeepMind、OpenAI、Anthropic、Meta AI、NVIDIA、Baidu、Alibaba、ByteDance 等
- **北美顶级大学：** MIT、Stanford、CMU、UC Berkeley、Harvard、Princeton、Cornell、Caltech 等
- **中国顶级大学/机构：** 清华大学、北京大学、浙大、上交大、复旦、中科院、MSRA 等
- **欧洲/其他：** Oxford、Cambridge、ETH Zurich、Mila、NUS、KAIST 等

---

*由 [clawBot DailyFindings](https://github.com/Jacob-biu/clawBot) 自动维护 | 最后更新：2026-10-17 00:12 UTC*
