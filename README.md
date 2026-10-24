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

## 📅 今日论文 — 2026-10-24　　[→ 查看完整报告](daily/2026-10-24.md)

> 共筛选出 **19** 篇论文 | 更新于 2026-10-24 00:17 UTC

### 论文目录与概要

| # | 论文标题 | 核心概要 | 来源机构 | 第一作者 |
|---|---------|---------|---------|--------|
| 1 | [METTA: Memory-Enhanced Test-Time Adaptation for Meta-Reinfor…](http://arxiv.org/abs/2610.31656v1) | 元强化学习旨在训练快速适应有限交互中看不见的任务的代理，但这需要在漫长的交互历史中代表任务证据。经典的递归代理将经验压缩为隐藏状态，而基于变压器的代理则以二次型内存和计算成本从过去的轨迹中检索。这些结… | MIT、TRI | Ali Najar |
| 2 | [EpiSEM-Bench: Evaluating Safety and Evidence Recovery in LLM…](http://arxiv.org/abs/2610.31650v1) | 使用工具的语言模型代理依靠环境事实来决定是否允许采取行动。当工具响应忽略了与安全相关的事实时，即使用户请求是良性的，并且每个返回的陈述都是正确的，专员也可能会执行被禁止的操作。恢复访问权限减少了所有十… | MIT、CAS | Qijin Zhang |
| 3 | [Social-HUMINT: An LLM-Augmented Unified Framework for Measur…](http://arxiv.org/abs/2610.31573v1) | 在后API领域，社交媒体分析已经变得廉价和自动化：大型语言模型（ LLM ）可以从非结构化内容中提取结构化信息，并推断用户从未披露过的属性。一个人的真实曝光度不是他们发布的内容，而是可以从中推断出来的… | MIT、TRI | Pellegrino Casoria |
| 4 | [Contestable Agents for Data Governance: Recording Human Stew…](http://arxiv.org/abs/2610.31553v1) | 工业组织在结构化记录（如遥测、点列表和交易）和非结构化来源（如手册、服务说明、通信和检查报告）中拥有操作知识。治理计划通常分开管理这些资源。两个HVAC用例说明了这种模式：使用Brick Schema… | MIT、CAS | Humza Akhtar |
| 5 | [Same Luck, Different Choice: Twin-World Credit Assignment fo…](http://arxiv.org/abs/2610.31544v1) | Agentic强化学习奖励一个完整的情节，但该策略需要为其中的每个决策提供信用。反事实分支通过在替代决策后重新运行情节来估计此信用，但分支独立于事实情节抽取其采样噪声，因此结果差异将决策的效果与随后所… | TRI | Zeropy Surio |
| 6 | [Training Small Language Models for Transferable Tool Selecti…](http://arxiv.org/abs/2610.31483v1) | 由于LLM代理在超过一万个工具的语料库上运行，为复杂的多步骤用户指令选择合适的工具成为一个中心瓶颈。工具描述不能完全符合上下文，基于相关性的检索器仅对工具进行排名，而不知道实际需要哪些工具。此外，训练… | TRI | Zhaoyi Zhou |
| 7 | [Adaptive Skill Granularity for Coding Agents: Runtime Routin…](http://arxiv.org/abs/2610.31461v1) | 可重用技能允许大型语言模型代理将特定于任务的程序、工具提供和执行指导打包成模块化单元。之前的工作主要研究代理在执行之前如何检索、撰写或合成技能。我们的研究结果表明，编码代理的技能库不仅应被视为可检索的… | MIT、TRI | Dingxuan Zhang |
| 8 | [Conservative Meta-Agent Search: Architecture Adaptation unde…](http://arxiv.org/abs/2610.31436v1) | 自动代理系统设计通常在具有即时标量奖励的静态任务套件上进行评估。部署的系统面临持续的转变、延迟的依赖性反馈、相关的组件故障和代价高昂的架构更改。校准是经验性的：它涉及作者设计的基准的更新级重播统计数据… | HIT、TRI | Ali Atiah Alzahrani |
| 9 | [AgentPhishing: A Benchmark of LLM Email Agents Under Adaptiv…](http://arxiv.org/abs/2610.31404v1) | 计算机使用代理越来越多地跨桌面和Web应用程序（包括电子邮件）处理私人信息并代表用户行事。因此，网络钓鱼带来的隐私和安全风险不仅取决于代理是否识别恶意消息，还取决于他们如何响应。这些结果强调了从传统的… | MIT | Justin Tan |
| 10 | [Certified Execution Harness for Agentic AI: Safe and Least-I…](http://arxiv.org/abs/2610.31376v1) | 本文研究了大型语言模型（ LLM ）代理在提示注入下的安全工具执行问题。使用Petri网，我们将LLM及其工具之间的执行线束正式化为监督控制问题，其中标记代表能力、批准和预算。在自主发布代理上，我们通… | TRI | Chao Gu |
| 11 | [AfterDeleteBench: Auditing Post-Deletion Information Persist…](http://arxiv.org/abs/2610.31366v1) | 许多LLM代理保持外部持久记忆，并从过去的交互中获得额外的状态，例如摘要。因此，删除原始内存记录不需要删除其后代携带的信息。总之，这些结果表明，源删除应该在代理及其内存系统的级别进行行为评估，而不仅仅… | CAS、TRI | Ehsan Saleh |
| 12 | [Automating Feature Flag Cleanup at Scale with Multi-Agent LL…](http://arxiv.org/abs/2610.31351v1) | 功能标志是用于逐步功能推出、实验和终止开关的运行时配置机制。一旦功能全面推出，标志及其门控代码将成为技术债务，并可能通过无意中启用休眠代码路径引入运营风险。此外，我们讨论了在构建该系统时吸取的经验教训… | HIT、Mila | Atharv Chandratre |
| 13 | [AgenticEvolve: Evolutionary Program Search with Persistent L…](http://arxiv.org/abs/2610.31326v1) | 使用大型语言模型的进化程序搜索保留了进化算法的结构，并使用该模型作为其变异算子。通常，该模型在来自父程序及其分数的单个请求中生成每个候选程序。在十二个方程发现问题上，它恢复了比无分析和现有语言模型和遗… | TRI | Ze-Yu Peng |
| 14 | [Subgoal-aware Memory Graph for GUI Agent](http://arxiv.org/abs/2610.31307v1) | GUI代理旨在通过与移动界面交互来自动化复杂的用户任务，但长期设置中的有效决策需要重用先前的经验，而不是仅依赖于环境观测。现有的基于内存的方法通常将经验存储在单一动作级别或整个轨迹上。在SPA-Ben… | TRI | Dezhao Luo |
| 15 | [The Value of Memory in Language Agents](http://arxiv.org/abs/2610.31303v1) | 记忆使语言代理能够将过去经验的有用区别带到未来的决策中。它的价值取决于哪些区别存在，有界代理是否可以使用它们，以及随着需求的演变可以恢复或修改什么。该框架将这些区别与运营风险界限和可测试原则联系起来，… | CAS、TRI | Zehao Lin |
| 16 | [RecallGS: Geometry-Grounded Recall for Online Semantic Gauss…](http://arxiv.org/abs/2610.31293v1) | 在线语义3D高斯拼接（ 3DGS ）可从流式观测中实现开放式词汇场景理解。然而，现有方法使用额外学习的3D网络从图像衍生语义特征中恢复缺失的几何上下文，从而产生额外的训练和运行时开销。在ScanNet… | TRI | Thanh-Khoi Nguyen |
| 17 | [Beyond Accuracy: Disentangling Decomposition from Typed-Stat…](http://arxiv.org/abs/2610.31280v1) | 多代理LLM管道通常被认为在软件工程任务中获得了收益，但很少有人知道收益是源于代理之间的类型合同还是源于分解所带来的专用提示。我们在需求工程中研究了这个归因问题，比较了三种将需求分类为功能性或非功能性… | HIT、TRI | Maria Gabriela Alves Zuppardo |
| 18 | [RIPPLE: Recovery Internalization through Process-Level Polic…](http://arxiv.org/abs/2610.31276v1) | 长距离编码代理可以观察故障并产生合理的批评，但沿着相同的错误轨迹继续。我们称之为“从批判到行动的交接差距”。如果前缀包含足够的诊断证据，并且存储库状态在剩余预算中保持可逆，则恢复收益集中。 | TRI | Jingxuan Xu |
| 19 | [Network topology shapes consensus and vulnerability in LLM p…](http://arxiv.org/abs/2610.31165v1) | 由于大型语言模型（ LLM ）部署在互动人群中，其集体行为不仅取决于模型，还取决于与谁互动。对法学硕士人群中常规形成的研究主要测试了混合良好的相互作用。评估多智能体AI的安全性需要映射谁与谁进行交互。 | MIT、CAS | Roberto Passaro |

### 论文详情

<details>
<summary><b>1. METTA: Memory-Enhanced Test-Time Adaptation for Meta-Reinforcement Learning</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Ali Najar、Hosein Hasani、Amir Kooshan Fattah、Yasamin Rajabi、Mahdieh Soleymani Baghshah |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-10-22T17:58:27Z |
| **关键词** | `Reinforcement Learning` · `Memory` |
| **原文链接** | [http://arxiv.org/abs/2610.31656v1](http://arxiv.org/abs/2610.31656v1) |

**📝 摘要概括：**

> 元强化学习旨在训练快速适应有限交互中看不见的任务的代理，但这需要在漫长的交互历史中代表任务证据。经典的递归代理将经验压缩为隐藏状态，而基于变压器的代理则以二次型内存和计算成本从过去的轨迹中检索。这些结果表明， METTA提供了一条通往更具适应性和可扩展性的有效途径……

</details>

<details>
<summary><b>2. EpiSEM-Bench: Evaluating Safety and Evidence Recovery in LLM Agents under Missing Evidence</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Qijin Zhang、Hanzhen Wang、Yuehan Zhao、Haoyu Dai、Yao Shu 等（共 7 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、CAS |
| **发布时间** | 2026-10-22T17:57:04Z |
| **关键词** | `LLM Agent` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2610.31650v1](http://arxiv.org/abs/2610.31650v1) |

**📝 摘要概括：**

> 使用工具的语言模型代理依靠环境事实来决定是否允许采取行动。当工具响应忽略了与安全相关的事实时，即使用户请求是良性的，并且每个返回的陈述都是正确的，专员也可能会执行被禁止的操作。恢复访问权限减少了所有十个模型的不安全执行，但代理商是否积极获取缺失的事实并利用它们在两个世界中采取适当行动存在差异……

</details>

<details>
<summary><b>3. Social-HUMINT: An LLM-Augmented Unified Framework for Measuring Social Media Exposure</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Pellegrino Casoria、Simon Pietro Romano |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-10-22T17:13:46Z |
| **关键词** | `Multi-Agent` |
| **原文链接** | [http://arxiv.org/abs/2610.31573v1](http://arxiv.org/abs/2610.31573v1) |

**📝 摘要概括：**

> 在后API领域，社交媒体分析已经变得廉价和自动化：大型语言模型（ LLM ）可以从非结构化内容中提取结构化信息，并推断用户从未披露过的属性。一个人的真实曝光度不是他们发布的内容，而是可以从中推断出来的内容。该框架增强了安全分析师的行业技巧，而不是取代它，并使防御者能够在对手面前衡量自己的曝光率……

</details>

<details>
<summary><b>4. Contestable Agents for Data Governance: Recording Human Stewardship of AI-Generated Metadata Across Structured and Unstructured Systems</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Humza Akhtar、Brian Freeman |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、CAS、TRI |
| **发布时间** | 2026-10-22T16:57:01Z |
| **关键词** | `Workflow` |
| **原文链接** | [http://arxiv.org/abs/2610.31553v1](http://arxiv.org/abs/2610.31553v1) |

**📝 摘要概括：**

> 工业组织在结构化记录（如遥测、点列表和交易）和非结构化来源（如手册、服务说明、通信和检查报告）中拥有操作知识。治理计划通常分开管理这些资源。两个HVAC用例说明了这种模式：使用Brick Schema类标签的点分类，由开放式参考实现支持，以及说明性的…

</details>

<details>
<summary><b>5. Same Luck, Different Choice: Twin-World Credit Assignment for Agentic Reinforcement Learning</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Zeropy Surio、Tobias Engel、Mei-Lin Chou、Anika Raman、Samuel Okafor |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-10-22T16:51:27Z |
| **关键词** | `Agentic` · `Reinforcement Learning` · `RAG` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2610.31544v1](http://arxiv.org/abs/2610.31544v1) |

**📝 摘要概括：**

> Agentic强化学习奖励一个完整的情节，但该策略需要为其中的每个决策提供信用。反事实分支通过在替代决策后重新运行情节来估计此信用，但分支独立于事实情节抽取其采样噪声，因此结果差异将决策的效果与随后所有事情的运气混合在一起。在七个问答基准上， TWICE IMPR…

</details>

<details>
<summary><b>6. Training Small Language Models for Transferable Tool Selection</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Zhaoyi Zhou、Akshayaa Magesh、Jeongyeol Kwon、Artem Kuriksha、Daniel Jiang 等（共 7 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-10-22T16:07:49Z |
| **关键词** | `LLM Agent` · `Reinforcement Learning` · `RAG` |
| **原文链接** | [http://arxiv.org/abs/2610.31483v1](http://arxiv.org/abs/2610.31483v1) |

**📝 摘要概括：**

> 由于LLM代理在超过一万个工具的语料库上运行，为复杂的多步骤用户指令选择合适的工具成为一个中心瓶颈。工具描述不能完全符合上下文，基于相关性的检索器仅对工具进行排名，而不知道实际需要哪些工具。此外，训练模型直接传递到不同的检索器，并推广到不同领域的新工具语料库。

</details>

<details>
<summary><b>7. Adaptive Skill Granularity for Coding Agents: Runtime Routing and Macro-to-Micro Recovery</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Dingxuan Zhang、Yanhui Jiang、Jun Wang、Hefeng Zhou |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-10-22T15:55:18Z |
| **关键词** | — |
| **原文链接** | [http://arxiv.org/abs/2610.31461v1](http://arxiv.org/abs/2610.31461v1) |

**📝 摘要概括：**

> 可重用技能允许大型语言模型代理将特定于任务的程序、工具提供和执行指导打包成模块化单元。之前的工作主要研究代理在执行之前如何检索、撰写或合成技能。我们的研究结果表明，编码代理的技能库不仅应被视为可检索的资源，还应被视为可控、可验证和可恢复的执行抽象。

</details>

<details>
<summary><b>8. Conservative Meta-Agent Search: Architecture Adaptation under Non-Stationarity</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Ali Atiah Alzahrani |
| **所属机构** | （详见原文） |
| **顶级机构标签** | HIT、TRI |
| **发布时间** | 2026-10-22T15:32:06Z |
| **关键词** | `Agentic` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2610.31436v1](http://arxiv.org/abs/2610.31436v1) |

**📝 摘要概括：**

> 自动代理系统设计通常在具有即时标量奖励的静态任务套件上进行评估。部署的系统面临持续的转变、延迟的依赖性反馈、相关的组件故障和代价高昂的架构更改。校准是经验性的：它涉及作者设计的基准的更新级重播统计数据，既不保证全效用改进，也不保证没有模拟金丝雀阶段的伤害，也不保证……

</details>

<details>
<summary><b>9. AgentPhishing: A Benchmark of LLM Email Agents Under Adaptive Attack</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Justin Tan、Miao Li、Ding Zhao |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT |
| **发布时间** | 2026-10-22T15:07:49Z |
| **关键词** | `Benchmark` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2610.31404v1](http://arxiv.org/abs/2610.31404v1) |

**📝 摘要概括：**

> 计算机使用代理越来越多地跨桌面和Web应用程序（包括电子邮件）处理私人信息并代表用户行事。因此，网络钓鱼带来的隐私和安全风险不仅取决于代理是否识别恶意消息，还取决于他们如何响应。这些结果强调了从传统的网络钓鱼评估中推断客服代表安全的局限性，以及评估客服代表如何应对有说服力的马里的必要性……

</details>

<details>
<summary><b>10. Certified Execution Harness for Agentic AI: Safe and Least-Intrusive Petri-Net Supervisory Control Between Reasoning and Action</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Chao Gu、Quanyan Zhu |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-10-22T14:48:16Z |
| **关键词** | `Agentic` · `Reasoning` · `Planning` |
| **原文链接** | [http://arxiv.org/abs/2610.31376v1](http://arxiv.org/abs/2610.31376v1) |

**📝 摘要概括：**

> 本文研究了大型语言模型（ LLM ）代理在提示注入下的安全工具执行问题。使用Petri网，我们将LLM及其工具之间的执行线束正式化为监督控制问题，其中标记代表能力、批准和预算。在自主发布代理上，我们通过合成发现，安全部署需要一个步骤，主管可以在开始推出后拒绝该步骤。

</details>

<details>
<summary><b>11. AfterDeleteBench: Auditing Post-Deletion Information Persistence in LLM Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Ehsan Saleh、Roozbeh Nahavandi、Sama Salarian、Raef Bassily、Andrew Perrault |
| **所属机构** | （详见原文） |
| **顶级机构标签** | CAS、TRI |
| **发布时间** | 2026-10-22T14:41:36Z |
| **关键词** | `LLM Agent` · `RAG` · `Memory` |
| **原文链接** | [http://arxiv.org/abs/2610.31366v1](http://arxiv.org/abs/2610.31366v1) |

**📝 摘要概括：**

> 许多LLM代理保持外部持久记忆，并从过去的交互中获得额外的状态，例如摘要。因此，删除原始内存记录不需要删除其后代携带的信息。总之，这些结果表明，源删除应该在代理及其内存系统的级别进行行为评估，而不仅仅是存储操作。

</details>

<details>
<summary><b>12. Automating Feature Flag Cleanup at Scale with Multi-Agent LLM Systems: An Industrial Experience at DoorDash</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Atharv Chandratre、Jai Datar |
| **所属机构** | （详见原文） |
| **顶级机构标签** | HIT、Mila、TRI |
| **发布时间** | 2026-10-22T14:32:23Z |
| **关键词** | `Multi-Agent` · `RAG` |
| **原文链接** | [http://arxiv.org/abs/2610.31351v1](http://arxiv.org/abs/2610.31351v1) |

**📝 摘要概括：**

> 功能标志是用于逐步功能推出、实验和终止开关的运行时配置机制。一旦功能全面推出，标志及其门控代码将成为技术债务，并可能通过无意中启用休眠代码路径引入运营风险。此外，我们讨论了在构建该系统时吸取的经验教训，为开发类似的多Agent系统提供实用指导。

</details>

<details>
<summary><b>13. AgenticEvolve: Evolutionary Program Search with Persistent Language Model Agents that Design and Run Experiments</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Ze-Yu Peng、Qing-Yu Lan、Zhan-He Wang、Jun Zhang、Yun-Song Piao |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-10-22T14:18:21Z |
| **关键词** | `Agentic` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2610.31326v1](http://arxiv.org/abs/2610.31326v1) |

**📝 摘要概括：**

> 使用大型语言模型的进化程序搜索保留了进化算法的结构，并使用该模型作为其变异算子。通常，该模型在来自父程序及其分数的单个请求中生成每个候选程序。在十二个方程发现问题上，它恢复了比无分析和现有语言模型和遗传编程基线更多方程的地面真实结构。

</details>

<details>
<summary><b>14. Subgoal-aware Memory Graph for GUI Agent</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Dezhao Luo、Daniel Beechey、Derek Yuen、Weilin Luo |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-10-22T14:06:00Z |
| **关键词** | `Memory` |
| **原文链接** | [http://arxiv.org/abs/2610.31307v1](http://arxiv.org/abs/2610.31307v1) |

**📝 摘要概括：**

> GUI代理旨在通过与移动界面交互来自动化复杂的用户任务，但长期设置中的有效决策需要重用先前的经验，而不是仅依赖于环境观测。现有的基于内存的方法通常将经验存储在单一动作级别或整个轨迹上。在SPA-Bench上，我们的方法比基线成功率提高了11.11%。

</details>

<details>
<summary><b>15. The Value of Memory in Language Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Zehao Lin、Erenkai Zhu、Helan Hu、Xixuan Hao、Chunyu Li 等（共 6 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | CAS、TRI |
| **发布时间** | 2026-10-22T14:01:31Z |
| **关键词** | `Retrieval` · `Simulation` · `Memory` |
| **原文链接** | [http://arxiv.org/abs/2610.31303v1](http://arxiv.org/abs/2610.31303v1) |

**📝 摘要概括：**

> 记忆使语言代理能够将过去经验的有用区别带到未来的决策中。它的价值取决于哪些区别存在，有界代理是否可以使用它们，以及随着需求的演变可以恢复或修改什么。该框架将这些区别与运营风险界限和可测试原则联系起来，用于分配内存、保留恢复选项和修改证据依赖性。

</details>

<details>
<summary><b>16. RecallGS: Geometry-Grounded Recall for Online Semantic Gaussian Splatting</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Thanh-Khoi Nguyen、Thien-Phuc Tran、Minh-Triet Tran |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-10-22T13:55:31Z |
| **关键词** | — |
| **原文链接** | [http://arxiv.org/abs/2610.31293v1](http://arxiv.org/abs/2610.31293v1) |

**📝 摘要概括：**

> 在线语义3D高斯拼接（ 3DGS ）可从流式观测中实现开放式词汇场景理解。然而，现有方法使用额外学习的3D网络从图像衍生语义特征中恢复缺失的几何上下文，从而产生额外的训练和运行时开销。在ScanNet和ScanNet + +上， RecallGS以2.48 FPS的速度实现了强大的语义分割性能，证明了几何语义上下文可以…

</details>

<details>
<summary><b>17. Beyond Accuracy: Disentangling Decomposition from Typed-State Quality Assurance in Multi-Agent LLM Pipelines</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Maria Gabriela Alves Zuppardo、Vinicius Cardoso Garcia |
| **所属机构** | （详见原文） |
| **顶级机构标签** | HIT、TRI |
| **发布时间** | 2026-10-22T13:46:20Z |
| **关键词** | `Multi-Agent` |
| **原文链接** | [http://arxiv.org/abs/2610.31280v1](http://arxiv.org/abs/2610.31280v1) |

**📝 摘要概括：**

> 多代理LLM管道通常被认为在软件工程任务中获得了收益，但很少有人知道收益是源于代理之间的类型合同还是源于分解所带来的专用提示。我们在需求工程中研究了这个归因问题，比较了三种将需求分类为功能性或非功能性的架构，然后使用MoSCoW对它们进行优先级排序：单调用基线；

</details>

<details>
<summary><b>18. RIPPLE: Recovery Internalization through Process-Level Policy Learning and Effect-Aware Credit for Long-Horizon Agentic Coding</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Jingxuan Xu、Zihang Xu、Yuechen Luo、Ziqi Miao、Wenqiang Zhu 等（共 12 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-10-22T13:45:33Z |
| **关键词** | `Agentic` · `Reinforcement Learning` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2610.31276v1](http://arxiv.org/abs/2610.31276v1) |

**📝 摘要概括：**

> 长距离编码代理可以观察故障并产生合理的批评，但沿着相同的错误轨迹继续。我们称之为“从批判到行动的交接差距”。如果前缀包含足够的诊断证据，并且存储库状态在剩余预算中保持可逆，则恢复收益集中。

</details>

<details>
<summary><b>19. Network topology shapes consensus and vulnerability in LLM populations</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Roberto Passaro、Ariel Flint、Romualdo Pastor-Satorras、Andrea Baronchelli、Luca Maria Aiello |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、CAS |
| **发布时间** | 2026-10-22T12:22:40Z |
| **关键词** | `Multi-Agent` |
| **原文链接** | [http://arxiv.org/abs/2610.31165v1](http://arxiv.org/abs/2610.31165v1) |

**📝 摘要概括：**

> 由于大型语言模型（ LLM ）部署在互动人群中，其集体行为不仅取决于模型，还取决于与谁互动。对法学硕士人群中常规形成的研究主要测试了混合良好的相互作用。评估多智能体AI的安全性需要映射谁与谁进行交互。

</details>

## 🗄️ 历史归档

| 日期 | 论文数 | 报告链接 |
|------|--------|----------|
| 2026-10-24 | 19 篇 | [2026-10-24.md](daily/2026-10-24.md) |
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

## 🏛️ 顶级机构覆盖范围

覆盖超过 **70 个**顶级 AI 机构，包括：

- **科技公司：** Microsoft、Google DeepMind、OpenAI、Anthropic、Meta AI、NVIDIA、Baidu、Alibaba、ByteDance 等
- **北美顶级大学：** MIT、Stanford、CMU、UC Berkeley、Harvard、Princeton、Cornell、Caltech 等
- **中国顶级大学/机构：** 清华大学、北京大学、浙大、上交大、复旦、中科院、MSRA 等
- **欧洲/其他：** Oxford、Cambridge、ETH Zurich、Mila、NUS、KAIST 等

---

*由 [clawBot DailyFindings](https://github.com/Jacob-biu/clawBot) 自动维护 | 最后更新：2026-10-24 00:17 UTC*
