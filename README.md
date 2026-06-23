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

## 📅 今日论文 — 2026-06-23　　[→ 查看完整报告](daily/2026-06-23.md)

> 共筛选出 **15** 篇论文 | 更新于 2026-06-23 23:08 UTC

### 论文目录与概要

| # | 论文标题 | 核心概要 | 来源机构 | 第一作者 |
|---|---------|---------|---------|--------|
| 1 | [Semantic Browsing: Controllable Diversity for Image Generati…](http://arxiv.org/abs/2606.23679v1) | 现代文本到图像模型在视觉保真度和及时遵守方面表现出色。然而，这种严格的坚持是以牺牲多样性为代价的：生成的样本往往会崩溃成单一的视觉解释。我们证明了我们的方法产生了多样化和可导航的设计空间，其中每个变体… | TRI | Sara Dorfman |
| 2 | [Causal Discovery in the Era of Agents](http://arxiv.org/abs/2606.23608v1) | 最近尝试将大型语言模型（ LLM ）与因果发现相结合，要求模型推断成对方向，提出图形结构，或将语言模型输出作为先验和约束注入。这些方法有望实现更快的分析，但它们也模糊了因果证据是得到数据和假设的支持，… | CAS、TRI | Yujia Zheng |
| 3 | [Kamera: Unified Position-Invariant Multimodal KV Cache for T…](http://arxiv.org/abs/2606.23581v1) | 当上下文窗口幻灯片和推理迭代时，多模式代理会反复重新检查相同的视频帧、UI屏幕截图和渲染工件，但每个回溯都会从头开始重新编码，因为前缀缓存仅在固定的领先位置提供重用。我们证明这种重新计算是可以避免的，… | TRI | Bole Ma |
| 4 | [Concordia: JIT-Compiled Persistent-Kernel Checkpointing for …](http://arxiv.org/abs/2606.23521v1) | 长期运行的LLM代理将宝贵的状态驻留在GPU上： KV缓存、请求调度程序、通信状态，有时还包括在线适配器。在GPU或通信器故障后失去此状态可能会丢弃几分钟到几小时的工作，但现有的恢复机制要么重新启动整… | MIT、TRI | Yuhang Gan |
| 5 | [AOHP: An Open-Source OS-Level Agent Harness for Personalized…](http://arxiv.org/abs/2606.23449v1) | 人工智能代理正在推动一种新的软件范式，能够自主调用工具、提取信息、管理内存并完成跨应用程序和数据源的任务。然而，大多数现有的最终用户操作系统都是为以应用程序为中心的工作流而设计的，几乎没有为人工智能代… | MIT、HIT | Shanhui Zhao |
| 6 | [Detecting Malicious Agent Skills in the Wild using Attention](http://arxiv.org/abs/2606.23416v1) | LLM代理越来越多地加载技能，即由第三方编写并通过市场分发的基于文件的自然语言指令包，这些指令以用户的权限执行。单个恶意技能可以窃取数据、劫持代理或持续作为供应链立足点，从而将技能市场转变为代理系统的… | TRI | Bacem Etteib |
| 7 | [ReasoningLens: Hierarchical Visualization and Diagnostic Aud…](http://arxiv.org/abs/2606.23404v1) | 大型推理模型的出现引入了异常长的思维链痕迹，造成了透明度负担，关键逻辑往往被埋藏在大量的程序文本之下。为了解决这个问题，我们推出了ReasoningLens ，这是一个开源框架，专为复杂推理链的分层可… | TRI | Jun Zhang |
| 8 | [Litmus: Zero-Label, Code-Driven Metric Specification for Eva…](http://arxiv.org/abs/2606.23403v1) | 随着代理LLM系统在日益多样化的领域从原型转向部署，对其进行评估变得更加重要和困难。挑战不仅是个人指标可能不可靠，而且评估目标往往是隐含的。我们的结果支持从自动指标实施到自动指标规范的转变：在询问要计… | TRI | Prajjwal Gupta |
| 9 | [Superhuman AI for Generals.io Using Self-Play Reinforcement …](http://arxiv.org/abs/2606.23348v1) | 我们为Generals.io提供了一个超人的人工智能代理，这是一款实时战略游戏，在强大的不完美信息下需要长远规划和短期战术。我们的代理在4个NVIDIA H200 GPU上接受了为期四天的培训，在超过… | NVIDIA | Matej Straka |
| 10 | [VideoAgent: All-in-One Framework for Video Understanding and…](http://arxiv.org/abs/2606.23327v1) | 视频编辑在数字媒体创作中已变得至关重要，但现有的自动化系统仅限于短片段处理和特定领域的任务。他们面临两个关键限制： i ）无法处理不同的视频理解和编辑操作，以及ii ）缺乏对连贯叙事创作的长视频理解。… | MIT、TRI | Hengji Zhou |
| 11 | [GIF: Locally Sound Geometric Information Flow Control for LL…](http://arxiv.org/abs/2606.23277v1) | 大型语言模型越来越多地介导敏感数据、不受信任的输入和代理系统中的特权操作之间的交互，从而产生安全和隐私风险。这些范围从操纵下游工具使用的提示注入到通过模型输出泄露机密信息。用小型代理模型检测到的GIF… | TRI | Adam Storek |
| 12 | [Dynamic multi-agent deep reinforcement learning-based pricin…](http://arxiv.org/abs/2606.23257v1) | 在多式联运系统中，共享出行服务（ SMS ）因其增强灵活性和减少拥堵的潜力而得到推广。然而，短信需求通常集中在高密度地区，这可能会限制各种通勤群体的有效性和可访问性。拟议的方法为可持续和公平的多式联运… | MIT、TRI | Khadidja Kadem |
| 13 | [RS-Gen: A Multi-Stage Agentic Framework for Reasoning and Se…](http://arxiv.org/abs/2606.23221v1) | 近年来，图像生成和编辑取得了显着进展，特别是在指令跟踪和视觉保真度方面。然而，在处理模棱两可的意图、逻辑推理和不分布（ OOD ）知识时，由于缺乏深度推理和实时外部信息，现有图像模型通常会产生次优结果… | TRI | Feifei Bian |
| 14 | [Memory Contagion: Cross-Temporal Propagation of Evaluator Bi…](http://arxiv.org/abs/2606.23195v1) | 大型语言模型（ LLM ）代理越来越依赖于记忆系统来保持长期一致性。最近的研究表明，智能体记忆在持续整合过程中会退化。我们的研究结果暴露了当前代理内存设计中的一个关键漏洞，并提供了用于测量跨时偏差传播… | TRI | Zewen Liu |
| 15 | [Position: Correct Answer, Wrong Mechanism -- When AI Scienti…](http://arxiv.org/abs/2606.23175v1) | 人工智能科学家系统被描述为工具、合著者或创始人，但我们对它们的评估就好像只有最终答案才重要一样。本立场文件认为，仅有结果的评估是不够的，必须分别衡量任务结果、机制保真度和认识诚实度。总之，这些检查标记… | CAS | Steven Young Eulig |

### 论文详情

<details>
<summary><b>1. Semantic Browsing: Controllable Diversity for Image Generation</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Sara Dorfman、Maya Vishnevsky、Omer Dahary、Or Patashnik、Daniel Cohen-Or |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-06-22T17:59:17Z |
| **关键词** | `Agentic` · `RAG` · `Workflow` |
| **原文链接** | [http://arxiv.org/abs/2606.23679v1](http://arxiv.org/abs/2606.23679v1) |

**📝 摘要概括：**

> 现代文本到图像模型在视觉保真度和及时遵守方面表现出色。然而，这种严格的坚持是以牺牲多样性为代价的：生成的样本往往会崩溃成单一的视觉解释。我们证明了我们的方法产生了多样化和可导航的设计空间，其中每个变体都对应于特定的、用户可理解的语义决策。

</details>

<details>
<summary><b>2. Causal Discovery in the Era of Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Yujia Zheng、Vishal Verma、Mantej Gill、Haoyue Dai、Peter Spirtes 等（共 6 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | CAS、TRI |
| **发布时间** | 2026-06-22T17:09:22Z |
| **关键词** | `Workflow` |
| **原文链接** | [http://arxiv.org/abs/2606.23608v1](http://arxiv.org/abs/2606.23608v1) |

**📝 摘要概括：**

> 最近尝试将大型语言模型（ LLM ）与因果发现相结合，要求模型推断成对方向，提出图形结构，或将语言模型输出作为先验和约束注入。这些方法有望实现更快的分析，但它们也模糊了因果证据是得到数据和假设的支持，还是得到文本关联、提示文物和幻觉机制的支持。该平台可在causallearn.com上找到……

</details>

<details>
<summary><b>3. Kamera: Unified Position-Invariant Multimodal KV Cache for Training-Free Reuse</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Bole Ma、Jan Eitzinger、Harald Koestler、Gerhard Wellein |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-06-22T16:47:00Z |
| **关键词** | `Reasoning` · `Retrieval` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2606.23581v1](http://arxiv.org/abs/2606.23581v1) |

**📝 摘要概括：**

> 当上下文窗口幻灯片和推理迭代时，多模式代理会反复重新检查相同的视频帧、UI屏幕截图和渲染工件，但每个回溯都会从头开始重新编码，因为前缀缓存仅在固定的领先位置提供重用。我们证明这种重新计算是可以避免的，并准确地确定天真的KV重复使用损失：跨块调节块从其邻居吸收。调节信号为ST…

</details>

<details>
<summary><b>4. Concordia: JIT-Compiled Persistent-Kernel Checkpointing for Fault-Tolerant LLM Inference</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Yuhang Gan、Yiwei Yang、Yuyi Li、Xiangyu Gao、Yichen Wang 等（共 9 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-06-22T16:06:11Z |
| **关键词** | `LLM Agent` · `Memory` |
| **原文链接** | [http://arxiv.org/abs/2606.23521v1](http://arxiv.org/abs/2606.23521v1) |

**📝 摘要概括：**

> 长期运行的LLM代理将宝贵的状态驻留在GPU上： KV缓存、请求调度程序、通信状态，有时还包括在线适配器。在GPU或通信器故障后失去此状态可能会丢弃几分钟到几小时的工作，但现有的恢复机制要么重新启动整个服务堆栈，要么在每个注意力和运行时组件中需要特定于应用程序的检查点逻辑。持久内核消耗无锁的RIN……

</details>

<details>
<summary><b>5. AOHP: An Open-Source OS-Level Agent Harness for Personalized, Efficient and Secure Interaction</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Shanhui Zhao、Jiacheng Liu、Guohong Liu、Jichao Yan、Jialei Ye 等（共 16 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、HIT、TRI |
| **发布时间** | 2026-06-22T15:02:42Z |
| **关键词** | `AI Agent` · `Memory` · `Workflow` |
| **原文链接** | [http://arxiv.org/abs/2606.23449v1](http://arxiv.org/abs/2606.23449v1) |

**📝 摘要概括：**

> 人工智能代理正在推动一种新的软件范式，能够自主调用工具、提取信息、管理内存并完成跨应用程序和数据源的任务。然而，大多数现有的最终用户操作系统都是为以应用程序为中心的工作流而设计的，几乎没有为人工智能代理提供原生支持。基于涵盖OS代理关键能力的挑战性任务的初步实验， AOHP显示出明显的优势……

</details>

<details>
<summary><b>6. Detecting Malicious Agent Skills in the Wild using Attention</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Bacem Etteib、Daniele Lunghi、Tégawendé F. Bissyandé |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-06-22T14:41:06Z |
| **关键词** | `LLM Agent` · `Agentic` |
| **原文链接** | [http://arxiv.org/abs/2606.23416v1](http://arxiv.org/abs/2606.23416v1) |

**📝 摘要概括：**

> LLM代理越来越多地加载技能，即由第三方编写并通过市场分发的基于文件的自然语言指令包，这些指令以用户的权限执行。单个恶意技能可以窃取数据、劫持代理或持续作为供应链立足点，从而将技能市场转变为代理系统的新攻击面。我们发布生成的标记数据集。

</details>

<details>
<summary><b>7. ReasoningLens: Hierarchical Visualization and Diagnostic Auditing for Large Reasoning Models</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Jun Zhang、Jiasheng Zheng、Boxi Cao、Yaojie Lu、Hongyu Lin 等（共 8 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-06-22T14:28:35Z |
| **关键词** | `Agentic` · `Reasoning` · `RAG` · `Chain-of-Thought` |
| **原文链接** | [http://arxiv.org/abs/2606.23404v1](http://arxiv.org/abs/2606.23404v1) |

**📝 摘要概括：**

> 大型推理模型的出现引入了异常长的思维链痕迹，造成了透明度负担，关键逻辑往往被埋藏在大量的程序文本之下。为了解决这个问题，我们推出了ReasoningLens ，这是一个开源框架，专为复杂推理链的分层可视化和诊断审计而设计。通过将非结构化的文本墙转化为可操作的见解， ReasoningLens证明……

</details>

<details>
<summary><b>8. Litmus: Zero-Label, Code-Driven Metric Specification for Evaluating AI Systems</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Prajjwal Gupta、Prasang Gupta、Vishal Bhutani、Apoorva Sharma、Sumanth Chundru 等（共 7 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-06-22T14:26:48Z |
| **关键词** | `Agentic` · `RAG` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2606.23403v1](http://arxiv.org/abs/2606.23403v1) |

**📝 摘要概括：**

> 随着代理LLM系统在日益多样化的领域从原型转向部署，对其进行评估变得更加重要和困难。挑战不仅是个人指标可能不可靠，而且评估目标往往是隐含的。我们的结果支持从自动指标实施到自动指标规范的转变：在询问要计算哪个指标之前，评估系统应该询问……

</details>

<details>
<summary><b>9. Superhuman AI for Generals.io Using Self-Play Reinforcement Learning</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Matej Straka、Viliam Lisý、Martin Schmid |
| **所属机构** | （详见原文） |
| **顶级机构标签** | NVIDIA |
| **发布时间** | 2026-06-22T13:52:22Z |
| **关键词** | `AI Agent` · `Planning` · `Reinforcement Learning` · `RAG` |
| **原文链接** | [http://arxiv.org/abs/2606.23348v1](http://arxiv.org/abs/2606.23348v1) |

**📝 摘要概括：**

> 我们为Generals.io提供了一个超人的人工智能代理，这是一款实时战略游戏，在强大的不完美信息下需要长远规划和短期战术。我们的代理在4个NVIDIA H200 GPU上接受了为期四天的培训，在超过5,000名人类玩家的公开1v1排行榜上排名第一，领先排名第二的玩家，将第二名与第二十五名分开，并以优异的成绩击败两位排名第一的人类。

</details>

<details>
<summary><b>10. VideoAgent: All-in-One Framework for Video Understanding and Editing</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Hengji Zhou、Lingxuan Huang、Jian Wang、Bing Zhou、Si Wu 等（共 7 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-06-22T13:37:08Z |
| **关键词** | `Multi-Agent` · `Agentic` · `Planning` · `Retrieval` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2606.23327v1](http://arxiv.org/abs/2606.23327v1) |

**📝 摘要概括：**

> 视频编辑在数字媒体创作中已变得至关重要，但现有的自动化系统仅限于短片段处理和特定领域的任务。他们面临两个关键限制： i ）无法处理不同的视频理解和编辑操作，以及ii ）缺乏对连贯叙事创作的长视频理解。我们在https://github.com/HKUDS/VideoAgent上发布我们的代码。

</details>

<details>
<summary><b>11. GIF: Locally Sound Geometric Information Flow Control for LLMs</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Adam Storek、Nikolaus Holzer、Zhuo Zhang、Suman Jana |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-06-22T12:54:04Z |
| **关键词** | `Agentic` · `Reasoning` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2606.23277v1](http://arxiv.org/abs/2606.23277v1) |

**📝 摘要概括：**

> 大型语言模型越来越多地介导敏感数据、不受信任的输入和代理系统中的特权操作之间的交互，从而产生安全和隐私风险。这些范围从操纵下游工具使用的提示注入到通过模型输出泄露机密信息。用小型代理模型检测到的GIF流量转移到较大的最先进模型和其他模型家族，即使代理…

</details>

<details>
<summary><b>12. Dynamic multi-agent deep reinforcement learning-based pricing and incentivization approach in multimodal transportation networks</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Khadidja Kadem、Mostafa Ameli、Carlos Lima Azevedo、Mahdi Zargayouna、Latifa Oukhellou |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-06-22T12:39:40Z |
| **关键词** | `Multi-Agent` · `Planning` · `Reinforcement Learning` |
| **原文链接** | [http://arxiv.org/abs/2606.23257v1](http://arxiv.org/abs/2606.23257v1) |

**📝 摘要概括：**

> 在多式联运系统中，共享出行服务（ SMS ）因其增强灵活性和减少拥堵的潜力而得到推广。然而，短信需求通常集中在高密度地区，这可能会限制各种通勤群体的有效性和可访问性。拟议的方法为可持续和公平的多式联运规划提供了决策支持工具。

</details>

<details>
<summary><b>13. RS-Gen: A Multi-Stage Agentic Framework for Reasoning and Search-Augmented Image Generation</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Feifei Bian、Zhimin Zheng、Wei Deng、Daiguo Zhou、Jian Luan |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-06-22T12:09:29Z |
| **关键词** | `Agentic` · `Reasoning` · `Planning` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2606.23221v1](http://arxiv.org/abs/2606.23221v1) |

**📝 摘要概括：**

> 近年来，图像生成和编辑取得了显着进展，特别是在指令跟踪和视觉保真度方面。然而，在处理模棱两可的意图、逻辑推理和不分布（ OOD ）知识时，由于缺乏深度推理和实时外部信息，现有图像模型通常会产生次优结果。具体而言，在WISE验证和RISEBench基准测试中， RS…

</details>

<details>
<summary><b>14. Memory Contagion: Cross-Temporal Propagation of Evaluator Bias via Agent Memory</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Zewen Liu |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-06-22T11:43:37Z |
| **关键词** | `Memory` |
| **原文链接** | [http://arxiv.org/abs/2606.23195v1](http://arxiv.org/abs/2606.23195v1) |

**📝 摘要概括：**

> 大型语言模型（ LLM ）代理越来越依赖于记忆系统来保持长期一致性。最近的研究表明，智能体记忆在持续整合过程中会退化。我们的研究结果暴露了当前代理内存设计中的一个关键漏洞，并提供了用于测量跨时偏差传播的正式工具。

</details>

<details>
<summary><b>15. Position: Correct Answer, Wrong Mechanism -- When AI Scientists Defend General Claims Their Own Data Contradicts</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Steven Young Eulig |
| **所属机构** | （详见原文） |
| **顶级机构标签** | CAS |
| **发布时间** | 2026-06-22T11:14:07Z |
| **关键词** | `Reasoning` · `Evaluation` · `Simulation` |
| **原文链接** | [http://arxiv.org/abs/2606.23175v1](http://arxiv.org/abs/2606.23175v1) |

**📝 摘要概括：**

> 人工智能科学家系统被描述为工具、合著者或创始人，但我们对它们的评估就好像只有最终答案才重要一样。本立场文件认为，仅有结果的评估是不够的，必须分别衡量任务结果、机制保真度和认识诚实度。总之，这些检查标记了本研究中的每个CAWM病例。

</details>

## 🗄️ 历史归档

| 日期 | 论文数 | 报告链接 |
|------|--------|----------|
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

## 🏛️ 顶级机构覆盖范围

覆盖超过 **70 个**顶级 AI 机构，包括：

- **科技公司：** Microsoft、Google DeepMind、OpenAI、Anthropic、Meta AI、NVIDIA、Baidu、Alibaba、ByteDance 等
- **北美顶级大学：** MIT、Stanford、CMU、UC Berkeley、Harvard、Princeton、Cornell、Caltech 等
- **中国顶级大学/机构：** 清华大学、北京大学、浙大、上交大、复旦、中科院、MSRA 等
- **欧洲/其他：** Oxford、Cambridge、ETH Zurich、Mila、NUS、KAIST 等

---

*由 [clawBot DailyFindings](https://github.com/Jacob-biu/clawBot) 自动维护 | 最后更新：2026-06-23 23:08 UTC*
