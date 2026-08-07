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

## 📅 今日论文 — 2026-08-07　　[→ 查看完整报告](daily/2026-08-07.md)

> 共筛选出 **20** 篇论文 | 更新于 2026-08-07 01:31 UTC

### 论文目录与概要

| # | 论文标题 | 核心概要 | 来源机构 | 第一作者 |
|---|---------|---------|---------|--------|
| 1 | [From Passive Mirrors to Active Agents: Holonic Digital Twins…](http://arxiv.org/abs/2608.06227v1) | 尽管人工智能（ AI ）在多个领域取得了进步，但当今的人工智能工具，包括深度学习和生成式人工智能，在嵌入到物理系统中时仍然失败，例如在现实世界的物理定律下运行的机器人和车辆。这源于他们无法在不确定性下… | MIT、HIT | Christo Kurisummoottil Thomas |
| 2 | [EnvACE: Internalizing Environment Dynamics via World Rehears…](http://arxiv.org/abs/2608.06197v1) | 训练大型语言模型代理以使用长期工具通常依赖于与真实或合成的可执行环境的交互，这些环境的构建和验证成本高昂，或者依赖于难以接地的外部模拟器。我们引入了EnvACE ，这是一种代理强化学习方法，用世界排练… | MIT | Zishan Xu |
| 3 | [Comparative Approaches to Agent Retrieval over Large Skill L…](http://arxiv.org/abs/2608.06196v1) | 由大型技能库支持的代理必须决定加载哪些技能以及以何种顺序加载。将整个库加载到上下文中是昂贵的，并且不提供自主测序的结构。我们的贡献是机械地解释了为什么添加结构不能改善强排序器的检索，并确定了在检索中添… | HIT、CAS | Indivara Kolluru |
| 4 | [iARCS: Iterative Agentic RL for Controllable 3D Scene Genera…](http://arxiv.org/abs/2608.06161v1) | 合成3D场景生成越来越多地用作计算机视觉和具体化AI的数据源，但现有生成器通常优化感知真实感，而不可靠地满足任务关键型功能约束。这种不匹配限制了合成数据在下游培训中的实用性，而可访问性、可遍历性和空间… | MIT | Saugat Adhikari |
| 5 | [Learning Globally Reusable Skills for Coding Agents](http://arxiv.org/abs/2608.06153v1) | 自动技能进化使大型语言模型（ LLM ）代理能够持续改进，而无需进行昂贵的再培训。然而，现有方法通常将技能进化视为一系列本地更新，忽略了技能之间的关系，并经常产生过度拟合的技能更新，无法跨任务概括。在… | TRI | Chen Yang |
| 6 | [FinEvo-Bench: A Longitudinal Benchmark for Self-Evolving Age…](http://arxiv.org/abs/2608.06144v1) | 大多数客服代表基准独立评估任务，无法衡量一项任务的经验是否有助于后续任务。现有的自我进化基准并不包括专业工作流程、开放式交付成果和多方面评估。FinEvo-Bench衡量专业绩效和自我进化能力：客服代… | Alibaba、Beihang University | Bo Deng |
| 7 | [SkillTFM: Gated Skill Evolution for Training-Free Adaptation…](http://arxiv.org/abs/2608.06137v1) | 表格数据在实际应用中无处不在，对于科学、工业、金融、医疗保健和公共服务领域的数据驱动预测和决策至关重要。表格基础模型（ TFM ）已成为通用表格学习的一个有前途的范例，为不同的数据集提供了可重用的预测… | CAS、TRI | Yi He |
| 8 | [Hardware Keystores for AI Agent Signing Workflows: A Zero-Tr…](http://arxiv.org/abs/2608.06130v1) | 执行加密操作（签署Git提交、验证API调用、颁发证书）的AI代理目前将私钥存储在软件可访问的位置：明文文件、环境变量或容器内存。任何具有足够读取权限的流程都可以提取原始密钥材料。在四种良性任务场景中… | MIT、TRI | Leo Sambrook |
| 9 | [Contextual Information Policy Optimization for Search Agents](http://arxiv.org/abs/2608.06128v1) | 搜索代理通过使他们能够在多步推理期间获取和使用外部证据，将大型语言模型扩展到静态参数内存之外。对于涉及复杂或不断发展的信息的知识密集型任务，其可靠性不仅取决于检索相关证据，还取决于使用相关证据来指导后… | TRI | Xingyu Guo |
| 10 | [From Siloed Algorithms to Compliance-First Agentic Platforms…](http://arxiv.org/abs/2608.06112v1) | 医院正在迅速采用人工智能进行分类、成像、调度等，但大多数部署仍然是锁定在部门孤岛内的孤立点解决方案，导致重复工作、隐藏风险和未实现的企业价值。尽管人工智能在医疗保健市场呈爆炸性增长，投资也在加速，但估… | HIT、TRI | Manideep Dhar |
| 11 | [ECHO: A Locally-Deployable Agentic Health Assistant with Tem…](http://arxiv.org/abs/2608.06110v1) | 本文介绍了ECHO （ Enhanced Care\ & Health Observer ） ，一种用于长期慢性病护理管理的本地部署会话健康助手。ECHO集成了在共享监督下开发的三个互补软件模块，作为… | MIT、CAS | Abdulkadir Külçe |
| 12 | [Evaluating Investment Logic in Large Language Models: A Real…](http://arxiv.org/abs/2608.06108v1) | 投资能力本质上是个性化的：相同的市场证据可以为具有不同目标、视野、投资组合和风险界限的投资者提供不同行动的理由。然而，财务LLM的评估要么通过静态问答，要么通过终端损益。金融是我们对更广泛的个性化客服… | MIT、TRI | Yuanhong Jiang |
| 13 | [Domain-Grounded Candidate Selection for Agentic Image Editin…](http://arxiv.org/abs/2608.06075v1) | 商业视觉语言模型正在重塑计算机视觉，其视觉先验足以与特定任务系统相媲美。这就提出了一个自然的问题：它们是否减少了对经典的、物理知情的低水平视觉的需求？这些结果表明，商业视觉语言模型不能取代经典的低级视… | TRI | Shilin Hu |
| 14 | [ProDVI: Programmatic Dynamics Priors for Value Network Initi…](http://arxiv.org/abs/2608.06015v1) | 众所周知，深度强化学习（ RL ）的样本效率低下。一个促成因素是， RL代理通常从头开始初始化，迫使他们通过在线交互获取与任务相关的知识。在OpenAI Gym和DeepMind Control Su… | DeepMind、OpenAI | Xinwei Liu |
| 15 | [HERALD: Counterfactual Audits and Minimal Repairs for Proof-…](http://arxiv.org/abs/2608.06012v1) | 搜索代理奖励组合答案质量、引用基础、工具成本和反黑客术语；因此，高分不一定意味着已检索到引用的证据，加上的处罚可以取消。我们引入了HERALD ，这是一种离线审计，应用完全相同的问题干预，将候选人可见… | TRI | Zhuowen Liu |
| 16 | [AgentOPSD: Recursive Self-Distillation for Agentic Reinforce…](http://arxiv.org/abs/2608.05987v1) | 具有可验证奖励的强化学习（ RL ）构建了轨迹级优势估计，但它通常无法归功于决定长期、多回合代理任务结果的少数关键决策。最近的工作引入了信用分配的特权自馏，提供了更密集的监督，但目前尚不清楚这些本地信… | TRI | Zi-Han Wang |
| 17 | [Training a Conditioned Video Game Agent on a VLM Annotated D…](http://arxiv.org/abs/2608.05954v1) | 强化学习（ RL ）是一种功能强大但远非易于使用的政策学习技术。在视频游戏的具体情况下，需要访问游戏引擎才能获得培训奖励（例如，我们展示了离线强化学习可用于训练相应于期望回报的条件代理，我们讨论了早期… | MIT、CAS | Katrin Schmid |
| 18 | [VLMs for Videogame Data Annotation](http://arxiv.org/abs/2608.05949v1) | 视觉语言模型(VLM)和人工智能(AI)代理已经彻底改变了工程师处理现实世界应用中复杂问题的方式。另一方面，它们在视频游戏中的采用受到合成场景的极端可变性以及它们对现实世界物理学的遵守程度的限制。我们… | MIT、Mila | Katrin Schmid |
| 19 | [AppDeltaWorld: Transition-Grounded Delta Code World Model fo…](http://arxiv.org/abs/2608.05891v1) | 移动GUI代理可以通过像素感知和触摸操作来操作应用程序，使其成为收集和改进长距离移动交互策略的有前途的界面。但是，对于敏感应用程序和隐私关键型操作，很难获得真实轨迹。此外，基于世界模型的测试时强化学习… | MIT、TRI | Weikai Xu |
| 20 | [CodeGrep: An RL-Trained Retrieval Agent for LLM Coding Agent…](http://arxiv.org/abs/2608.05886v1) | 现代LLM编码代理（如Claude Code和OpenHands ）有一个共同的低效率：他们花费大量的代币预算来寻找要修补的文件，而不是修补它。在SWE-Bench Verified上， 30B Op… | TRI | Wuya Chen |

### 论文详情

<details>
<summary><b>1. From Passive Mirrors to Active Agents: Holonic Digital Twins for Physical AI over Networks</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Christo Kurisummoottil Thomas、Omar Hashash、Walid Saad |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、HIT |
| **发布时间** | 2026-08-06T16:17:43Z |
| **关键词** | `Reasoning` · `Planning` |
| **原文链接** | [http://arxiv.org/abs/2608.06227v1](http://arxiv.org/abs/2608.06227v1) |

**📝 摘要概括：**

> 尽管人工智能（ AI ）在多个领域取得了进步，但当今的人工智能工具，包括深度学习和生成式人工智能，在嵌入到物理系统中时仍然失败，例如在现实世界的物理定律下运行的机器人和车辆。这源于他们无法在不确定性下维护可靠的长期规划世界模型，并将其推广到看不见的场景。最后，集成信息理论量化了……

</details>

<details>
<summary><b>2. EnvACE: Internalizing Environment Dynamics via World Rehearsal for Agentic Reinforcement Learning</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Zishan Xu、Zhiyuan Yao、Yuxin Chen、Yifu Guo、Zhengxi Lu 等（共 12 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT |
| **发布时间** | 2026-08-06T15:54:36Z |
| **关键词** | `LLM Agent` · `Agentic` · `Reinforcement Learning` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2608.06197v1](http://arxiv.org/abs/2608.06197v1) |

**📝 摘要概括：**

> 训练大型语言模型代理以使用长期工具通常依赖于与真实或合成的可执行环境的交互，这些环境的构建和验证成本高昂，或者依赖于难以接地的外部模拟器。我们引入了EnvACE ，这是一种代理强化学习方法，用世界排练取代了培训期间的外部环境交互。我们的代码可在https://github.com/上公开获得……

</details>

<details>
<summary><b>3. Comparative Approaches to Agent Retrieval over Large Skill Libraries</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Indivara Kolluru、Nathan Sportsman |
| **所属机构** | （详见原文） |
| **顶级机构标签** | HIT、CAS、TRI |
| **发布时间** | 2026-08-06T15:54:23Z |
| **关键词** | `Retrieval` · `Workflow` |
| **原文链接** | [http://arxiv.org/abs/2608.06196v1](http://arxiv.org/abs/2608.06196v1) |

**📝 摘要概括：**

> 由大型技能库支持的代理必须决定加载哪些技能以及以何种顺序加载。将整个库加载到上下文中是昂贵的，并且不提供自主测序的结构。我们的贡献是机械地解释了为什么添加结构不能改善强排序器的检索，并确定了在检索中添加结构相互依赖性是最佳的条件。

</details>

<details>
<summary><b>4. iARCS: Iterative Agentic RL for Controllable 3D Scene Generation</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Saugat Adhikari、Ashok Prasad Neupane、Pramish Paudel、Ajad Chhatkuli、Danda Pani Paudel |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT |
| **发布时间** | 2026-08-06T15:30:21Z |
| **关键词** | `Agentic` · `Reinforcement Learning` · `Fine-tuning` · `Embodied AI` |
| **原文链接** | [http://arxiv.org/abs/2608.06161v1](http://arxiv.org/abs/2608.06161v1) |

**📝 摘要概括：**

> 合成3D场景生成越来越多地用作计算机视觉和具体化AI的数据源，但现有生成器通常优化感知真实感，而不可靠地满足任务关键型功能约束。这种不匹配限制了合成数据在下游培训中的实用性，而可访问性、可遍历性和空间规则合规性往往是必不可少的。我们进一步表明， iARCS生成的数据改善了……

</details>

<details>
<summary><b>5. Learning Globally Reusable Skills for Coding Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Chen Yang、Jiashuo Tian、Ziqi Wang、Xinyin Liu、Meiru Ye 等（共 6 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-08-06T15:19:56Z |
| **关键词** | — |
| **原文链接** | [http://arxiv.org/abs/2608.06153v1](http://arxiv.org/abs/2608.06153v1) |

**📝 摘要概括：**

> 自动技能进化使大型语言模型（ LLM ）代理能够持续改进，而无需进行昂贵的再培训。然而，现有方法通常将技能进化视为一系列本地更新，忽略了技能之间的关系，并经常产生过度拟合的技能更新，无法跨任务概括。在内部工业代理上部署进一步提高了61.4%的F1分数，证明了效果……

</details>

<details>
<summary><b>6. FinEvo-Bench: A Longitudinal Benchmark for Self-Evolving Agents in Professional Financial Workflows</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Bo Deng、Kang Zhou、Lifan Guo、Chongyang Tao、Xuanren Chen 等（共 9 人） |
| **所属机构** | Beihang University；Qwen DianJin Team, Alibaba Cloud Computing |
| **顶级机构标签** | Alibaba、Beihang University |
| **发布时间** | 2026-08-06T15:14:54Z |
| **关键词** | `Benchmark` · `Evaluation` · `Memory` · `Workflow` |
| **原文链接** | [http://arxiv.org/abs/2608.06144v1](http://arxiv.org/abs/2608.06144v1) |

**📝 摘要概括：**

> 大多数客服代表基准独立评估任务，无法衡量一项任务的经验是否有助于后续任务。现有的自我进化基准并不包括专业工作流程、开放式交付成果和多方面评估。FinEvo-Bench衡量专业绩效和自我进化能力：客服代表如何有效地将以前的经验转化为以后的改进。

</details>

<details>
<summary><b>7. SkillTFM: Gated Skill Evolution for Training-Free Adaptation of Tabular Foundation Models</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Yi He、Zhengkang Guan、Anpeng Wu、Peng Cui、Fei Wu 等（共 6 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | CAS、TRI |
| **发布时间** | 2026-08-06T15:09:02Z |
| **关键词** | `Agentic` · `Fine-tuning` |
| **原文链接** | [http://arxiv.org/abs/2608.06137v1](http://arxiv.org/abs/2608.06137v1) |

**📝 摘要概括：**

> 表格数据在实际应用中无处不在，对于科学、工业、金融、医疗保健和公共服务领域的数据驱动预测和决策至关重要。表格基础模型（ TFM ）已成为通用表格学习的一个有前途的范例，为不同的数据集提供了可重用的预测器，并大大减少了对特定任务的训练、调整和模型开发的需求。进一步…

</details>

<details>
<summary><b>8. Hardware Keystores for AI Agent Signing Workflows: A Zero-Trust MCP Enforcement Architecture</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Leo Sambrook、Sampo Sovio |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-08-06T15:04:26Z |
| **关键词** | `AI Agent` · `Memory` · `Workflow` |
| **原文链接** | [http://arxiv.org/abs/2608.06130v1](http://arxiv.org/abs/2608.06130v1) |

**📝 摘要概括：**

> 执行加密操作（签署Git提交、验证API调用、颁发证书）的AI代理目前将私钥存储在软件可访问的位置：明文文件、环境变量或容器内存。任何具有足够读取权限的流程都可以提取原始密钥材料。在四种良性任务场景中零误报。

</details>

<details>
<summary><b>9. Contextual Information Policy Optimization for Search Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Xingyu Guo、Wei Chen、Linlin Yang、Baochang Zhang |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-08-06T15:01:29Z |
| **关键词** | `Reasoning` · `Reinforcement Learning` · `RAG` · `Retrieval` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2608.06128v1](http://arxiv.org/abs/2608.06128v1) |

**📝 摘要概括：**

> 搜索代理通过使他们能够在多步推理期间获取和使用外部证据，将大型语言模型扩展到静态参数内存之外。对于涉及复杂或不断发展的信息的知识密集型任务，其可靠性不仅取决于检索相关证据，还取决于使用相关证据来指导后续推理。七个域内和域外基准的广泛经验表明， CIPO减少了……

</details>

<details>
<summary><b>10. From Siloed Algorithms to Compliance-First Agentic Platforms: A Multi-Layered Architecture for Hospital AI Systems</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Manideep Dhar、Ritwik Singh、Sharat Chandra Kumar Manikonda |
| **所属机构** | （详见原文） |
| **顶级机构标签** | HIT、TRI |
| **发布时间** | 2026-08-06T14:44:31Z |
| **关键词** | `Multi-Agent` · `Agentic` · `RAG` · `Workflow` |
| **原文链接** | [http://arxiv.org/abs/2608.06112v1](http://arxiv.org/abs/2608.06112v1) |

**📝 摘要概括：**

> 医院正在迅速采用人工智能进行分类、成像、调度等，但大多数部署仍然是锁定在部门孤岛内的孤立点解决方案，导致重复工作、隐藏风险和未实现的企业价值。尽管人工智能在医疗保健市场呈爆炸性增长，投资也在加速，但估计有70-80%的医疗保健人工智能试点项目未能扩展，这主要是由于治理差距、数据分散、……

</details>

<details>
<summary><b>11. ECHO: A Locally-Deployable Agentic Health Assistant with Temporal Memory, Safety Guardrails, and Speech Assessment</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Abdulkadir Külçe、Alihan Esen、Cağla Fikir、Berke Kurt、Kuzey Arar 等（共 7 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、CAS |
| **发布时间** | 2026-08-06T14:44:12Z |
| **关键词** | `Agentic` · `Benchmark` · `Memory` |
| **原文链接** | [http://arxiv.org/abs/2608.06110v1](http://arxiv.org/abs/2608.06110v1) |

**📝 摘要概括：**

> 本文介绍了ECHO （ Enhanced Care\ & Health Observer ） ，一种用于长期慢性病护理管理的本地部署会话健康助手。ECHO集成了在共享监督下开发的三个互补软件模块，作为一个统一的系统。整个系统作为一个Web应用程序实现，可以完全在消费者硬件上运行，不会将患者数据传输到外部服务，从而支持遵守GDPR和K...

</details>

<details>
<summary><b>12. Evaluating Investment Logic in Large Language Models: A Real-World Benchmark Towards Personalzied Financial Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Yuanhong Jiang、Jingjie Zou、Zhenghong Lin、Xusheng Yu、Qiqi Huang 等（共 7 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-08-06T14:41:56Z |
| **关键词** | `Reasoning` · `Retrieval` · `Benchmark` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2608.06108v1](http://arxiv.org/abs/2608.06108v1) |

**📝 摘要概括：**

> 投资能力本质上是个性化的：相同的市场证据可以为具有不同目标、视野、投资组合和风险界限的投资者提供不同行动的理由。然而，财务LLM的评估要么通过静态问答，要么通过终端损益。金融是我们对更广泛的个性化客服代表的压力测试。

</details>

<details>
<summary><b>13. Domain-Grounded Candidate Selection for Agentic Image Editing: A Shadow Removal Case</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Shilin Hu、Jingyi Xu、Dimitris Samaras、Hieu Le |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-08-06T14:19:22Z |
| **关键词** | `Agentic` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2608.06075v1](http://arxiv.org/abs/2608.06075v1) |

**📝 摘要概括：**

> 商业视觉语言模型正在重塑计算机视觉，其视觉先验足以与特定任务系统相媲美。这就提出了一个自然的问题：它们是否减少了对经典的、物理知情的低水平视觉的需求？这些结果表明，商业视觉语言模型不能取代经典的低级视觉先验；相反，这种先验对于约束和引导身体受限的生成仍然有用。

</details>

<details>
<summary><b>14. ProDVI: Programmatic Dynamics Priors for Value Network Initialization</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Xinwei Liu、Junyuan Liang、Jianting Zhang、Wuhui Chen |
| **所属机构** | （详见原文） |
| **顶级机构标签** | DeepMind、OpenAI、TRI |
| **发布时间** | 2026-08-06T13:19:29Z |
| **关键词** | `Reinforcement Learning` · `RAG` |
| **原文链接** | [http://arxiv.org/abs/2608.06015v1](http://arxiv.org/abs/2608.06015v1) |

**📝 摘要概括：**

> 众所周知，深度强化学习（ RL ）的样本效率低下。一个促成因素是， RL代理通常从头开始初始化，迫使他们通过在线交互获取与任务相关的知识。在OpenAI Gym和DeepMind Control Suite任务上的实验表明， ProDVI可以有效地提高无模型RL算法的样本效率。

</details>

<details>
<summary><b>15. HERALD: Counterfactual Audits and Minimal Repairs for Proof-of-Retrieval Rewards</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Zhuowen Liu、Bohan Cui、YinShang Guo、Yuting Wang、Hao Li |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-08-06T13:15:54Z |
| **关键词** | `Retrieval` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2608.06012v1](http://arxiv.org/abs/2608.06012v1) |

**📝 摘要概括：**

> 搜索代理奖励组合答案质量、引用基础、工具成本和反黑客术语；因此，高分不一定意味着已检索到引用的证据，加上的处罚可以取消。我们引入了HERALD ，这是一种离线审计，应用完全相同的问题干预，将候选人可见与预言机信息分离，并在策略优化之前枚举检测器合同。因此， HERALD将稳健得分、稀疏叶片……分开。

</details>

<details>
<summary><b>16. AgentOPSD: Recursive Self-Distillation for Agentic Reinforcement Learning</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Zi-Han Wang、Zhengxi Lu、Zhiyuan Yao、Jinyang Wu、Jie Wu 等（共 13 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-08-06T13:00:59Z |
| **关键词** | `Agentic` · `Reinforcement Learning` |
| **原文链接** | [http://arxiv.org/abs/2608.05987v1](http://arxiv.org/abs/2608.05987v1) |

**📝 摘要概括：**

> 具有可验证奖励的强化学习（ RL ）构建了轨迹级优势估计，但它通常无法归功于决定长期、多回合代理任务结果的少数关键决策。最近的工作引入了信用分配的特权自馏，提供了更密集的监督，但目前尚不清楚这些本地信号应如何代表连续信用。消融研究将收益归因于……

</details>

<details>
<summary><b>17. Training a Conditioned Video Game Agent on a VLM Annotated Dataset</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Katrin Schmid、Iuri Frosio |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、CAS、NTU |
| **发布时间** | 2026-08-06T12:25:54Z |
| **关键词** | `Reinforcement Learning` |
| **原文链接** | [http://arxiv.org/abs/2608.05954v1](http://arxiv.org/abs/2608.05954v1) |

**📝 摘要概括：**

> 强化学习（ RL ）是一种功能强大但远非易于使用的政策学习技术。在视频游戏的具体情况下，需要访问游戏引擎才能获得培训奖励（例如，我们展示了离线强化学习可用于训练相应于期望回报的条件代理，我们讨论了早期实验中出现的困难和限制。

</details>

<details>
<summary><b>18. VLMs for Videogame Data Annotation</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Katrin Schmid、Iuri Frosio |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、Mila |
| **发布时间** | 2026-08-06T12:20:53Z |
| **关键词** | `Reinforcement Learning` |
| **原文链接** | [http://arxiv.org/abs/2608.05949v1](http://arxiv.org/abs/2608.05949v1) |

**📝 摘要概括：**

> 视觉语言模型(VLM)和人工智能(AI)代理已经彻底改变了工程师处理现实世界应用中复杂问题的方式。另一方面，它们在视频游戏中的采用受到合成场景的极端可变性以及它们对现实世界物理学的遵守程度的限制。我们还展示了输入序列长度、分辨率和问题批处理如何影响注释质量及其令牌消耗……

</details>

<details>
<summary><b>19. AppDeltaWorld: Transition-Grounded Delta Code World Model for Mobile GUI Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Weikai Xu、Yunren Feng、Haoxiang Lei、Kun Huang、Yuxuan Liu 等（共 9 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-08-06T11:15:41Z |
| **关键词** | `Reinforcement Learning` · `RAG` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2608.05891v1](http://arxiv.org/abs/2608.05891v1) |

**📝 摘要概括：**

> 移动GUI代理可以通过像素感知和触摸操作来操作应用程序，使其成为收集和改进长距离移动交互策略的有前途的界面。但是，对于敏感应用程序和隐私关键型操作，很难获得真实轨迹。此外，基于世界模型的测试时强化学习可以实现策略适应，并显示出进一步的改进，而无需与真实应用程序进行额外的交互……

</details>

<details>
<summary><b>20. CodeGrep: An RL-Trained Retrieval Agent for LLM Coding Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Wuya Chen、Yihao yang、Yang Cao、Yue Lin |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-08-06T11:07:42Z |
| **关键词** | `RAG` · `Retrieval` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2608.05886v1](http://arxiv.org/abs/2608.05886v1) |

**📝 摘要概括：**

> 现代LLM编码代理（如Claude Code和OpenHands ）有一个共同的低效率：他们花费大量的代币预算来寻找要修补的文件，而不是修补它。在SWE-Bench Verified上， 30B OpenHands代理平均每个已解决的问题有23个回合和631K令牌，在存储库浏览期间，许多调用花费在grep、glob和view_file上。我们将发布模型、培训流水线、强化学习环境和评估线束。

</details>

## 🗄️ 历史归档

| 日期 | 论文数 | 报告链接 |
|------|--------|----------|
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

## 🏛️ 顶级机构覆盖范围

覆盖超过 **70 个**顶级 AI 机构，包括：

- **科技公司：** Microsoft、Google DeepMind、OpenAI、Anthropic、Meta AI、NVIDIA、Baidu、Alibaba、ByteDance 等
- **北美顶级大学：** MIT、Stanford、CMU、UC Berkeley、Harvard、Princeton、Cornell、Caltech 等
- **中国顶级大学/机构：** 清华大学、北京大学、浙大、上交大、复旦、中科院、MSRA 等
- **欧洲/其他：** Oxford、Cambridge、ETH Zurich、Mila、NUS、KAIST 等

---

*由 [clawBot DailyFindings](https://github.com/Jacob-biu/clawBot) 自动维护 | 最后更新：2026-08-07 01:31 UTC*
