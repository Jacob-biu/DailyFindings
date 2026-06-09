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

## 📅 今日论文 — 2026-06-09　　[→ 查看完整报告](daily/2026-06-09.md)

> 共筛选出 **20** 篇论文 | 更新于 2026-06-09 23:19 UTC

### 论文目录与概要

| # | 论文标题 | 核心概要 | 来源机构 | 第一作者 |
|---|---------|---------|---------|--------|
| 1 | [FASE: Fast Adaptive Semantic Entropy for Code Quality](http://arxiv.org/abs/2606.09800v1) | 多代理代码生成通过模拟人类软件工程生命周期，为自主软件开发提供了一个有希望的范例。然而，系统可靠性仍然受到LLM幻觉和交互主体的错误传播的阻碍。这些结果将FASE定位为优化现实世界多智能体工作流程中的… | CAS、Mila | Shizhe Lin |
| 2 | [SIGA: Self-Evolving Coding-Agent Adapters for Scientific Sim…](http://arxiv.org/abs/2606.09774v1) | 先进的科学模拟器揭示了将模拟目标转化为可执行配置的专用输入语言，但学习它们可能会使领域科学家花费数小时到数天的时间。我们将模拟器设置作为代理工具接地问题进行研究：现成的编码代理操作真正的科学软件需要哪… | NTU、TRI | Matthew Ho |
| 3 | [Collaborative Human-Agent Protocol (CHAP)](http://arxiv.org/abs/2606.09751v1) | 基础模型正在从响应生成转变为运营角色。他们计划跨步骤，调用工具，请求人工输入，与其他代理商协调，并越来越多地承担影响客户、索赔、代码、合同和临床决策的工作责任。规范、参考实现、一致性套件和工作示例可在… | TRI | Arsalan Shahid |
| 4 | [Multi-Turn Evaluation of Deep Research Agents Under Process-…](http://arxiv.org/abs/2606.09748v1) | 深度研究代理（ DRA ）的现有基准仅评估单次产出，忽略了一个关键问题： DRA在反馈的指导下能否改进其报告？为了调查这一点，我们在两种反馈设置下对DRA进行了多轮评估：自我反思，其中客服代表在没有任… | HIT | Rishabh Sabharwal |
| 5 | [Observability for Delegated Execution in Agentic AI Systems](http://arxiv.org/abs/2606.09692v1) | 委派范围的执行无法从标准可观察对象中识别：在多个不兼容的委派分配下，审核日志和执行跟踪可以相同。这种差距在基于LLM的代理系统中尤其严重，其中代理动态选择工具，在相同指令的运行中改变执行顺序，并生成协… | TRI | Abhinav Mishra |
| 6 | [AutoMegaKernel: A Statically-Checked Agent Harness for Self-…](http://arxiv.org/abs/2606.09682v1) | AutoMegaKernel （ AMK ）将HuggingFace Llama家族模型编译为单个持久协作CUDA内核，该内核在一次启动中运行整个向前传递，无需按模型手写CUDA。贡献在于系统，而不是… | NVIDIA、TRI | Jaber Jaber |
| 7 | [SpatialWorld: Benchmarking Interactive Spatial Reasoning of …](http://arxiv.org/abs/2606.09669v1) | 空间推理是多模态大型语言模型（ MLLM ）在物理世界中感知和操作的基础能力。然而，现有的基准主要依赖于被动评估（例如静态VQA ）或模拟器特定的管道，无法评估一般的交互式空间理解。积极探索和长远规划… | TRI | Hongcheng Gao |
| 8 | [From 0-to-1 to 1-to-N: Reproducible Engineering Evidence for…](http://arxiv.org/abs/2606.09663v1) | 递归自我设计是指人工智能辅助修改构建、评估和改进人工智能系统的机制。本文认为MetaAI不是一个成熟的范式，而是人类种子， AI扩展的发展模式的工作术语，其中设计空间本身成为修改的目标。由于此构建中不… | TRI | Dun Li |
| 9 | [End-to-End Context Compression at Scale](http://arxiv.org/abs/2606.09659v1) | 长上下文语言模型推断受到内存的瓶颈，因为KV缓存随着上下文长度而增长。最近压缩KV缓存的技术不足：它们要么大幅降低模型质量，要么需要相当长的时间和计算来压缩单个长提示。我们证明， LCLM是长期代理的… | HIT | Ang Li |
| 10 | [AGENTSERVESIM: A Hardware-aware Simulator for Multi-Turn LLM…](http://arxiv.org/abs/2606.09613v1) | 多轮LLM代理将模型调用与外部工具调用交织在一起，将服务从无状态请求处理转变为有状态程序执行。为这些工作负载提供服务需要调度、KV缓存管理和使用程序级上下文的路由策略，包括TURN依赖项、工具引起的间… | MIT、TRI | Rakibul Hasan Rajib |
| 11 | [Shape Formation for the Cooperative Transportation of Arbitr…](http://arxiv.org/abs/2606.09610v1) | 合作对象运输在许多领域都是必不可少的，包括工业到家庭服务。一种流行的运输策略是在多机器人系统上携带物体。我们对不同环境和不同数量的机器人的评估表明，我们的方法导致了可靠地产生平衡构造的政策，并将其推广… | TRI | Mohamed Sayed |
| 12 | [PRISM: Recovering Instruction Sets from Language Model Activ…](http://arxiv.org/abs/2606.09563v1) | 由于LLM作为代理部署，可靠的监控不仅需要了解他们输出的内容，还需要知道哪些指令在引导他们的行为。当模型推断出意想不到的子目标、遵循情境线索或受到及时注入和隐藏目标的影响时，这很困难。在良性、受限、提… | TRI | Gilad Gressel |
| 13 | [AI Scientists Are Only as Good as Their Evidence: A Stratifi…](http://arxiv.org/abs/2606.09556v1) | 人工智能科学家代理通常被评估为能力主要是模型质量、提示或推理支架的函数。我们在药物资产估值中测试了一个不同的假设：对于知识密集型的科学决策，限制因素通常是药剂可以访问的证据基础。相反，专有证据为人工智… | MIT、Mila | Yinan Wang |
| 14 | [SecureClaw: Clawing Back Control of LLM Agents](http://arxiv.org/abs/2606.09549v1) | 使用工具的大型语言模型（ LLM ）代理面临两种截然不同的安全故障：未经授权的外部操作和运行时内敏感明文的暴露，然后才能进行任何最终输出检查。现有的防御通常保护一个边界，无论是规划器/运行时还是动作水… | MIT、HIT | Yuhan Ma |
| 15 | [Memory Beyond Recall: A Dual-Process Cognitive Memory System…](http://arxiv.org/abs/2606.09483v1) | LLM专员的长期记忆不仅仅是在正确的时间检索正确的段落。当前的内存系统将信念修正、因果耦合和跨域抽象收缩到一个单一的检索表面，该检索表面针对表面召回进行了调整，因此在隐式个性化方面遇到了困难，这需要对… | HIT、TRI | Tianxiang Fei |
| 16 | [LargeMonitor: Monitoring Online Task-Free Continual Learning…](http://arxiv.org/abs/2606.09430v1) | 在线无任务持续学习（ TFCL ）要求智能代理在严格的单通道约束下，在没有任何明确的任务标识符的情况下，从无限的非平稳数据流中顺序积累知识。现有的在线TFCL范式主要依赖于参数高效的提示调谐或由训练耦… | TRI | Mingqi Yuan |
| 17 | [WeaveBench: A Long-Horizon, Real-World Benchmark for Compute…](http://arxiv.org/abs/2606.09426v1) | 计算机使用代理(CUA)越来越多地在结合了可视化桌面控制、命令行执行、代码编辑、浏览器和外部工具的运行时中运行。然而，现有的基准测试通常将这些接口评估为可分离的功能，使得长时间的跨接口编排测试不足。总… | NTU、TRI | Wanli Li |
| 18 | [RunAgent SuperBrowser: A Theory of Autonomous Web Navigation…](http://arxiv.org/abs/2606.09399v1) | 我们介绍了SUPERBROWSER ，这是一种针对单一指导假设设计的自主网络导航代理：网络代理应该浏览一个人的浏览方式。阅读页面的人并不会保留他们所看到的每个像素；他们会查看几个候选目标，决定一个目标… | MIT、CAS | Radeen Mostafa |
| 19 | [Experience Makes Skillful: Enabling Generalizable Medical Ag…](http://arxiv.org/abs/2606.09365v1) | 越来越多的人期望医疗代理系统支持交互式临床决策，而不仅仅是静态问答。在这种情况下，有效的代理必须在不断变化的案例中重复使用先前的经验，但现有的记忆机制通常会保留冗余、嘈杂且难以管理的原始历史痕迹。所有… | MIT、CAS | Haoran Sun |
| 20 | [PBSD: Privileged Bayesian Self-Distillation for Long-Horizon…](http://arxiv.org/abs/2606.09348v1) | 长期代理任务为基于结果的强化学习提出了基本的信用分配挑战：轨迹级奖励验证最终正确性，但对哪些中间推理步骤或工具交互有助于结果提供有限的指导。这种困难在多回合搜索代理中尤其明显，其中成功的轨迹可能包含误… | MIT、TRI | Yang Tian |

### 论文详情

<details>
<summary><b>1. FASE: Fast Adaptive Semantic Entropy for Code Quality</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Shizhe Lin、Ladan Tahvildari |
| **所属机构** | （详见原文） |
| **顶级机构标签** | CAS、Mila、TRI |
| **发布时间** | 2026-06-08T17:53:05Z |
| **关键词** | `Multi-Agent` · `RAG` · `Evaluation` · `Code Generation` · `Workflow` |
| **原文链接** | [http://arxiv.org/abs/2606.09800v1](http://arxiv.org/abs/2606.09800v1) |

**📝 摘要概括：**

> 多代理代码生成通过模拟人类软件工程生命周期，为自主软件开发提供了一个有希望的范例。然而，系统可靠性仍然受到LLM幻觉和交互主体的错误传播的阻碍。这些结果将FASE定位为优化现实世界多智能体工作流程中的不确定性量化的实用且具有成本效益的解决方案。

</details>

<details>
<summary><b>2. SIGA: Self-Evolving Coding-Agent Adapters for Scientific Simulation</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Matthew Ho、Brian Liu、Jixuan Chen、Audrey Wang、Lianhui Qin |
| **所属机构** | （详见原文） |
| **顶级机构标签** | NTU、TRI |
| **发布时间** | 2026-06-08T17:35:17Z |
| **关键词** | `Retrieval` · `Simulation` · `Memory` |
| **原文链接** | [http://arxiv.org/abs/2606.09774v1](http://arxiv.org/abs/2606.09774v1) |

**📝 摘要概括：**

> 先进的科学模拟器揭示了将模拟目标转化为可执行配置的专用输入语言，但学习它们可能会使领域科学家花费数小时到数天的时间。我们将模拟器设置作为代理工具接地问题进行研究：现成的编码代理操作真正的科学软件需要哪些最小的模拟器特定的适应性？这些结果表明，轻量级、可自我改进的接地……

</details>

<details>
<summary><b>3. Collaborative Human-Agent Protocol (CHAP)</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Arsalan Shahid、Gordon Suttie、Philip Black |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-06-08T17:11:42Z |
| **关键词** | `Multi-Agent` · `Memory` |
| **原文链接** | [http://arxiv.org/abs/2606.09751v1](http://arxiv.org/abs/2606.09751v1) |

**📝 摘要概括：**

> 基础模型正在从响应生成转变为运营角色。他们计划跨步骤，调用工具，请求人工输入，与其他代理商协调，并越来越多地承担影响客户、索赔、代码、合同和临床决策的工作责任。规范、参考实现、一致性套件和工作示例可在以下网站获得： https://github.com/BrightbeamAI/chap

</details>

<details>
<summary><b>4. Multi-Turn Evaluation of Deep Research Agents Under Process-Level Feedback</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Rishabh Sabharwal、Hongru Wang、Amos Storkey、Jeff Z. Pan |
| **所属机构** | （详见原文） |
| **顶级机构标签** | HIT |
| **发布时间** | 2026-06-08T17:08:36Z |
| **关键词** | `Benchmark` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2606.09748v1](http://arxiv.org/abs/2606.09748v1) |

**📝 摘要概括：**

> 深度研究代理（ DRA ）的现有基准仅评估单次产出，忽略了一个关键问题： DRA在反馈的指导下能否改进其报告？为了调查这一点，我们在两种反馈设置下对DRA进行了多轮评估：自我反思，其中客服代表在没有任何外部诊断信号的情况下修改其报告，以及流程级反馈，其中客服代表接收针对其研究差距的指导......

</details>

<details>
<summary><b>5. Observability for Delegated Execution in Agentic AI Systems</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Abhinav Mishra、Kumar Sharad |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-06-08T16:10:05Z |
| **关键词** | `Agentic` · `Reasoning` · `RAG` |
| **原文链接** | [http://arxiv.org/abs/2606.09692v1](http://arxiv.org/abs/2606.09692v1) |

**📝 摘要概括：**

> 委派范围的执行无法从标准可观察对象中识别：在多个不兼容的委派分配下，审核日志和执行跟踪可以相同。这种差距在基于LLM的代理系统中尤其严重，其中代理动态选择工具，在相同指令的运行中改变执行顺序，并生成协作的子代理。这可以实现可靠的跨工具委托范围的重建和直接的……

</details>

<details>
<summary><b>6. AutoMegaKernel: A Statically-Checked Agent Harness for Self-Retargeting Megakernel Synthesis</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Jaber Jaber、Osama Jaber |
| **所属机构** | （详见原文） |
| **顶级机构标签** | NVIDIA、TRI |
| **发布时间** | 2026-06-08T16:02:03Z |
| **关键词** | — |
| **原文链接** | [http://arxiv.org/abs/2606.09682v1](http://arxiv.org/abs/2606.09682v1) |

**📝 摘要概括：**

> AutoMegaKernel （ AMK ）将HuggingFace Llama家族模型编译为单个持久协作CUDA内核，该内核在一次启动中运行整个向前传递，无需按模型手写CUDA。贡献在于系统，而不是原始速度。代码和线束： https://github.com/RightNow-AI/AutoMegaKernel

</details>

<details>
<summary><b>7. SpatialWorld: Benchmarking Interactive Spatial Reasoning of Multimodal Agents in Real-World Tasks</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Hongcheng Gao、Hailong Qu、Jingyi Tang、Jiahao Wang、Zihao Huang 等（共 21 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-06-08T15:51:51Z |
| **关键词** | `Reasoning` · `Planning` · `RAG` · `Benchmark` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2606.09669v1](http://arxiv.org/abs/2606.09669v1) |

**📝 摘要概括：**

> 空间推理是多模态大型语言模型（ MLLM ）在物理世界中感知和操作的基础能力。然而，现有的基准主要依赖于被动评估（例如静态VQA ）或模拟器特定的管道，无法评估一般的交互式空间理解。积极探索和长远规划中的这些瓶颈将SpatialWorld定位为未来水疗的严格测试平台……

</details>

<details>
<summary><b>8. From 0-to-1 to 1-to-N: Reproducible Engineering Evidence for MetaAI Recursive Self-Design</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Dun Li、Jiatao Li、Hongzhi Li |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-06-08T15:45:15Z |
| **关键词** | — |
| **原文链接** | [http://arxiv.org/abs/2606.09663v1](http://arxiv.org/abs/2606.09663v1) |

**📝 摘要概括：**

> 递归自我设计是指人工智能辅助修改构建、评估和改进人工智能系统的机制。本文认为MetaAI不是一个成熟的范式，而是人类种子， AI扩展的发展模式的工作术语，其中设计空间本身成为修改的目标。由于此构建中不包含已完成的模型运行，因此MetaAI-Mini被报告为协议，而不是实验性...

</details>

<details>
<summary><b>9. End-to-End Context Compression at Scale</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Ang Li、Sean McLeish、Haozhe Chen、Nimit Kalra、Zaiqian Chen 等（共 15 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | HIT |
| **发布时间** | 2026-06-08T15:43:16Z |
| **关键词** | `Memory` |
| **原文链接** | [http://arxiv.org/abs/2606.09659v1](http://arxiv.org/abs/2606.09659v1) |

**📝 摘要概括：**

> 长上下文语言模型推断受到内存的瓶颈，因为KV缓存随着上下文长度而增长。最近压缩KV缓存的技术不足：它们要么大幅降低模型质量，要么需要相当长的时间和计算来压缩单个长提示。我们证明， LCLM是长期代理的高效骨干，让代理浏览压缩的长语境，并自适应扩展相关性……

</details>

<details>
<summary><b>10. AGENTSERVESIM: A Hardware-aware Simulator for Multi-Turn LLM Agent Serving</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Rakibul Hasan Rajib、Mengxin Zheng、Qian Lou |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-06-08T15:20:23Z |
| **关键词** | `LLM Agent` · `Simulation` · `Memory` |
| **原文链接** | [http://arxiv.org/abs/2606.09613v1](http://arxiv.org/abs/2606.09613v1) |

**📝 摘要概括：**

> 多轮LLM代理将模型调用与外部工具调用交织在一起，将服务从无状态请求处理转变为有状态程序执行。为这些工作负载提供服务需要调度、KV缓存管理和使用程序级上下文的路由策略，包括TURN依赖项、工具引起的间隙和可重用的KV状态。这些结果表明， AGENTSERVESIM能够实现可控的、可重复的药剂服务探索……

</details>

<details>
<summary><b>11. Shape Formation for the Cooperative Transportation of Arbitrary Objects Using Multi-Agent Reinforcement Learning</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Mohamed Sayed、Wolfram Burgard、Tanja Katharina Kaiser |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-06-08T15:18:14Z |
| **关键词** | `Multi-Agent` · `Reinforcement Learning` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2606.09610v1](http://arxiv.org/abs/2606.09610v1) |

**📝 摘要概括：**

> 合作对象运输在许多领域都是必不可少的，包括工业到家庭服务。一种流行的运输策略是在多机器人系统上携带物体。我们对不同环境和不同数量的机器人的评估表明，我们的方法导致了可靠地产生平衡构造的政策，并将其推广到具有复杂几何形状和不均匀质量分布的杂乱场景和物体……

</details>

<details>
<summary><b>12. PRISM: Recovering Instruction Sets from Language Model Activations</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Gilad Gressel、Rahul Pankajakshan、Julia Diament、Efim Hudis、Krishnashree Achuthan 等（共 6 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-06-08T14:37:46Z |
| **关键词** | `Agentic` · `Retrieval` |
| **原文链接** | [http://arxiv.org/abs/2606.09563v1](http://arxiv.org/abs/2606.09563v1) |

**📝 摘要概括：**

> 由于LLM作为代理部署，可靠的监控不仅需要了解他们输出的内容，还需要知道哪些指令在引导他们的行为。当模型推断出意想不到的子目标、遵循情境线索或受到及时注入和隐藏目标的影响时，这很困难。在良性、受限、提示注入和隐藏目标设置中， PRISM的表现优于激活到语言基线，特别是在安全相关方面……

</details>

<details>
<summary><b>13. AI Scientists Are Only as Good as Their Evidence: A Stratified Ablation of Proprietary Data and Reasoning Skills in Drug-Asset Valuation</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Yinan Wang |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、Mila、TRI |
| **发布时间** | 2026-06-08T14:31:32Z |
| **关键词** | `Reasoning` · `RAG` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2606.09556v1](http://arxiv.org/abs/2606.09556v1) |

**📝 摘要概括：**

> 人工智能科学家代理通常被评估为能力主要是模型质量、提示或推理支架的函数。我们在药物资产估值中测试了一个不同的假设：对于知识密集型的科学决策，限制因素通常是药剂可以访问的证据基础。相反，专有证据为人工智能科学家可以知道并因此做出决定设定了上限。

</details>

<details>
<summary><b>14. SecureClaw: Clawing Back Control of LLM Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Yuhan Ma、Stefan Schmid |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、HIT |
| **发布时间** | 2026-06-08T14:29:01Z |
| **关键词** | `LLM Agent` |
| **原文链接** | [http://arxiv.org/abs/2606.09549v1](http://arxiv.org/abs/2606.09549v1) |

**📝 摘要概括：**

> 使用工具的大型语言模型（ LLM ）代理面临两种截然不同的安全故障：未经授权的外部操作和运行时内敏感明文的暴露，然后才能进行任何最终输出检查。现有的防御通常保护一个边界，无论是规划器/运行时还是动作水槽，因此本身并不保护两个表面。在AgentDojo、AgentLeak和Agent Security Bench (ASB)中， SecureClaw是唯一……

</details>

<details>
<summary><b>15. Memory Beyond Recall: A Dual-Process Cognitive Memory System for Self-Evolving LLM Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Tianxiang Fei、Mingyang Song、Mao Zheng、Xiang Yu |
| **所属机构** | （详见原文） |
| **顶级机构标签** | HIT、TRI |
| **发布时间** | 2026-06-08T13:39:24Z |
| **关键词** | `LLM Agent` · `Reasoning` · `Retrieval` · `Benchmark` · `Memory` |
| **原文链接** | [http://arxiv.org/abs/2606.09483v1](http://arxiv.org/abs/2606.09483v1) |

**📝 摘要概括：**

> LLM专员的长期记忆不仅仅是在正确的时间检索正确的段落。当前的内存系统将信念修正、因果耦合和跨域抽象收缩到一个单一的检索表面，该检索表面针对表面召回进行了调整，因此在隐式个性化方面遇到了困难，这需要对用户如何进化进行推理。在LongMemEval、PersonaMem和PersonaMem-v2上，启用System2的贡献最大……

</details>

<details>
<summary><b>16. LargeMonitor: Monitoring Online Task-Free Continual Learning via Large Pretrained Models</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Mingqi Yuan、Xiaoquan Sun、Shihao Luo、Jiayu Chen |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-06-08T12:41:15Z |
| **关键词** | `RAG` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2606.09430v1](http://arxiv.org/abs/2606.09430v1) |

**📝 摘要概括：**

> 在线无任务持续学习（ TFCL ）要求智能代理在严格的单通道约束下，在没有任何明确的任务标识符的情况下，从无限的非平稳数据流中顺序积累知识。现有的在线TFCL范式主要依赖于参数高效的提示调谐或由训练耦合优化动力学驱动的动态结构扩展，例如经验损失波动或后期演变……

</details>

<details>
<summary><b>17. WeaveBench: A Long-Horizon, Real-World Benchmark for Computer-Use Agents with Hybrid Interfaces</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Wanli Li、Bowen Zhou、Yunyao Yu、Zhou Xu、Yifan Yang 等（共 7 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | NTU、TRI |
| **发布时间** | 2026-06-08T12:39:23Z |
| **关键词** | `Benchmark` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2606.09426v1](http://arxiv.org/abs/2606.09426v1) |

**📝 摘要概括：**

> 计算机使用代理(CUA)越来越多地在结合了可视化桌面控制、命令行执行、代码编辑、浏览器和外部工具的运行时中运行。然而，现有的基准测试通常将这些接口评估为可分离的功能，使得长时间的跨接口编排测试不足。总体而言， WeaveBench暴露了CUA评估中的一个关键差距，并提供了一个有效的测试平台来衡量药剂是否可以......

</details>

<details>
<summary><b>18. RunAgent SuperBrowser: A Theory of Autonomous Web Navigation Grounded in Human Browsing Behaviour</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Radeen Mostafa、Sawradip Saha |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、CAS、TRI |
| **发布时间** | 2026-06-08T12:18:22Z |
| **关键词** | `Reasoning` · `Benchmark` · `Web Agent` |
| **原文链接** | [http://arxiv.org/abs/2606.09399v1](http://arxiv.org/abs/2606.09399v1) |

**📝 摘要概括：**

> 我们介绍了SUPERBROWSER ，这是一种针对单一指导假设设计的自主网络导航代理：网络代理应该浏览一个人的浏览方式。阅读页面的人并不会保留他们所看到的每个像素；他们会查看几个候选目标，决定一个目标，并且只记住保持目标活跃所需的内容。我们认为，收益不是来自任何单一的技巧，而是来自认知契约的一致应用……

</details>

<details>
<summary><b>19. Experience Makes Skillful: Enabling Generalizable Medical Agent Reasoning via Self-Evolving Skill Memory</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Haoran Sun、Wenjie Li、Yujie Zhang、Zekai Lin、Fanrui Zhang 等（共 11 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、CAS、TRI |
| **发布时间** | 2026-06-08T11:37:01Z |
| **关键词** | `Reasoning` · `Retrieval` · `Memory` |
| **原文链接** | [http://arxiv.org/abs/2606.09365v1](http://arxiv.org/abs/2606.09365v1) |

**📝 摘要概括：**

> 越来越多的人期望医疗代理系统支持交互式临床决策，而不仅仅是静态问答。在这种情况下，有效的代理必须在不断变化的案例中重复使用先前的经验，但现有的记忆机制通常会保留冗余、嘈杂且难以管理的原始历史痕迹。所有数据和代码都将公开发布。

</details>

<details>
<summary><b>20. PBSD: Privileged Bayesian Self-Distillation for Long-Horizon Credit Assignment</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Yang Tian、Rui Wang、Xumeng Wen、Junjie Li、Shizhao Sun 等（共 8 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-06-08T11:20:58Z |
| **关键词** | `Agentic` · `Reasoning` · `Reinforcement Learning` |
| **原文链接** | [http://arxiv.org/abs/2606.09348v1](http://arxiv.org/abs/2606.09348v1) |

**📝 摘要概括：**

> 长期代理任务为基于结果的强化学习提出了基本的信用分配挑战：轨迹级奖励验证最终正确性，但对哪些中间推理步骤或工具交互有助于结果提供有限的指导。这种困难在多回合搜索代理中尤其明显，其中成功的轨迹可能包含误导性行为，而失败的轨迹可能包含价值……

</details>

## 🗄️ 历史归档

| 日期 | 论文数 | 报告链接 |
|------|--------|----------|
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
| 2026-05-20 | 16 篇 | [2026-05-20.md](daily/2026-05-20.md) |
| 2026-05-19 | 0 篇 | [2026-05-19.md](daily/2026-05-19.md) |
| 2026-05-17 | 0 篇 | [2026-05-17.md](daily/2026-05-17.md) |
| 2026-05-16 | 0 篇 | [2026-05-16.md](daily/2026-05-16.md) |
| 2026-05-15 | 20 篇 | [2026-05-15.md](daily/2026-05-15.md) |
| 2026-05-14 | 19 篇 | [2026-05-14.md](daily/2026-05-14.md) |
| 2026-05-13 | 20 篇 | [2026-05-13.md](daily/2026-05-13.md) |
| 2026-05-12 | 20 篇 | [2026-05-12.md](daily/2026-05-12.md) |
| 2026-05-11 | 0 篇 | [2026-05-11.md](daily/2026-05-11.md) |
| 2026-05-10 | 0 篇 | [2026-05-10.md](daily/2026-05-10.md) |

## 🏛️ 顶级机构覆盖范围

覆盖超过 **70 个**顶级 AI 机构，包括：

- **科技公司：** Microsoft、Google DeepMind、OpenAI、Anthropic、Meta AI、NVIDIA、Baidu、Alibaba、ByteDance 等
- **北美顶级大学：** MIT、Stanford、CMU、UC Berkeley、Harvard、Princeton、Cornell、Caltech 等
- **中国顶级大学/机构：** 清华大学、北京大学、浙大、上交大、复旦、中科院、MSRA 等
- **欧洲/其他：** Oxford、Cambridge、ETH Zurich、Mila、NUS、KAIST 等

---

*由 [clawBot DailyFindings](https://github.com/Jacob-biu/clawBot) 自动维护 | 最后更新：2026-06-09 23:19 UTC*
