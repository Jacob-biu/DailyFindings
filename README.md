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

## 📅 今日论文 — 2026-06-05　　[→ 查看完整报告](daily/2026-06-05.md)

> 共筛选出 **20** 篇论文 | 更新于 2026-06-05 23:08 UTC

### 论文目录与概要

| # | 论文标题 | 核心概要 | 来源机构 | 第一作者 |
|---|---------|---------|---------|--------|
| 1 | [HANDOFF: Humanoid Agentic Task-Space Whole-Body Control via …](http://arxiv.org/abs/2606.06493v1) | 对于要在现实世界中部署的人形机器人，命令空间（即任务计划和全身控制之间的接口）的选择至关重要。现有的全身控制器通常需要密集的运动学或空间参考，规划人员很难从任务语义中合成这些参考。我们进一步通过多个自… | NTU | Lizhi Yang |
| 2 | [DNQ: Deep Nash Q-Network for Partially Observable n-Player G…](http://arxiv.org/abs/2606.06480v1) | 许多真实世界的竞争系统需要多个决策者在共享约束、有限信息和重复交互下同时采取行动，例如拍卖、资源分配和安全竞争。我们研究了多回合同步投标作为此类问题的受控测试平台，并提出了DNQ ，这是一种用于培训投… | MIT、TRI | Qintong Xie |
| 3 | [MLEvolve: A Self-Evolving Framework for Automated Machine Le…](http://arxiv.org/abs/2606.06473v1) | 大型语言模型（ LLM ）代理越来越多地应用于科学发现和机器学习工程（ MLE ）等长远任务，其中持续的自我进化成为一项关键能力。然而，现有的MLE代理存在分支间信息隔离、无记忆搜索和缺乏分层控制等问… | TRI | Shangheng Du |
| 4 | [Goedel-Architect: Streamlining Formal Theorem Proving with B…](http://arxiv.org/abs/2606.06468v1) | 我们介绍了Goedel-Architect ，这是一个以蓝图生成和细化为中心的精益4形式定理证明的代理框架。蓝图是建立在主要定理上的定义和引理的依赖关系图。这代表了开源管道的最先进性能，其价格比同类开… | HIT | Jui-Hui Chung |
| 5 | [Benchmark Everything Everywhere All at Once](http://arxiv.org/abs/2606.06462v1) | 通过提供标准化和明确的绩效衡量标准，基准是评估和推进LLM和MLM的基础。然而，它们的建设是劳动密集型的，难以重复使用，引发了对可持续性和可扩展性的担忧。预览和代码将在演示页面和代码库中公开提供。 | TRI | Shiyun Xiong |
| 6 | [Will the Agent Recuse Itself? Measuring LLM-Agent Compliance…](http://arxiv.org/abs/2606.06460v1) | 随着自主LLM代理越来越多地持有真实的凭证，并在没有人员参与的情况下运营基础设施，运营商没有标准的方法来告诉代理资源是禁区的。访问控制让代理进入（它具有有效的凭据）或硬失败（与任何其他客户端无法区分）… | OpenAI、MIT | Thamilvendhan Munirathinam |
| 7 | [Vortex: Efficient and Programmable Sparse Attention Serving …](http://arxiv.org/abs/2606.06453v1) | 随着代长度的不断增长，稀疏注意力对于服务于大型语言模型（ LLM ）变得越来越重要。然而，大规模部署和评估新的稀疏注意力算法仍然是高度工程密集型的，这减缓了人类研究人员和人工智能代理探索稀疏注意力设计… | NVIDIA、HIT | Zhuoming Chen |
| 8 | [Agent Memory: Characterization and System Implications of St…](http://arxiv.org/abs/2606.06448v1) | LLM代理越来越多地部署在需要对扩展交互历史进行持续推理的长期任务上。大规模实现这一点需要代理跨会话持续存储、检索和更新自己的内存。最后，我们推导出10个系统建议，涵盖施工调度、产能下限、通过查询量摊… | TRI | Yasmine Omri |
| 9 | [RiskFlow: Fast and Faithful Safety-Critical Traffic Scenario…](http://arxiv.org/abs/2606.06423v1) | 安全关键交通场景生成对于评估罕见但高风险交互下的自动驾驶系统至关重要。现有的基于扩散的方法在闭环生成中提供了强大的可控性，但它们的迭代去噪过程在计算上昂贵，并且可能会在长时间的推出过程中积累采样和制导… | NUS | Qi Lan |
| 10 | [Conformal Risk Sharing: Certified Cost Allocation with Parti…](http://arxiv.org/abs/2606.06391v1) | 在整个团队中分享罕见不良事件的财务影响可以减轻极端的个人负担，但任何因该安排而变得更糟的参与者都有理由离开。因此，可靠的机制必须为每个代理商的未来义务提供一个值得信赖的上限，并且只有在参与者之间的总伤… | TRI | Ieva Kazlauskaite |
| 11 | [Emergent Language as an Approach to Conscious AI](http://arxiv.org/abs/2606.06380v1) | 人工系统是否可以有意识的问题仍然存在，部分原因是现有的方法要么是根据理论衍生的检查表（歧视性）来评估系统，要么是直接设计受意识启发的模块（建筑） ；两者都对观察到的结构是否是人类语言先验的产物持开放态… | HIT、TRI | Zengqing Wu |
| 12 | [An Infectious Disease Spread Simulation Based on Large Langu…](http://arxiv.org/abs/2606.06360v1) | 在传染病爆发期间对个人决策进行建模对于理解行为动态和为有效的公共卫生干预措施提供信息至关重要。先前的研究表明，大型语言模型可以通过基于人口统计提示和情境背景生成代理决策来模拟逼真的人类行为。我们的框架… | TRI | Yonchanok Khaokaew |
| 13 | [Equivariant Neural Belief Propagation](http://arxiv.org/abs/2606.06344v1) | 对空间嵌入变量的概率推断需要尊重$ SE (3) $对称性的信念，但现有的等变量网络只产生标量和向量，而不是各向异性不确定性所需的2阶精度张量，单分量消息将多模态能量景观折叠为物理上无意义的平均值。我… | TRI | Zehua Cheng |
| 14 | [ToolChoiceConfusion: Causal Minimal Tool Filtering for Relia…](http://arxiv.org/abs/2606.06284v1) | 大型语言模型代理越来越依赖外部工具，但更大的工具菜单可能会通过增加错误工具调用、过早操作和令牌成本来降低可靠性和效率。现有的工具选择方法通常会优化语义相关性，暴露名称或描述与用户请求匹配的工具。在包含… | NUS、TRI | Rahul Suresh Babu |
| 15 | [TOKI: A Bitemporal Operator Algebra for Contradiction Resolu…](http://arxiv.org/abs/2606.06240v1) | LLM代理的持久内存是一个写入较重的基板：每个置信更新都是一个版本化的写入，新的声明可能与存储的声明相矛盾。生产系统使用四种分辨率启发式方法（ last-writer-wins、evidence-we… | MIT、TRI | Ziming Wang |
| 16 | [From Reward-Hack Activations to Agentic Risk States: Context…](http://arxiv.org/abs/2606.06223v1) | 语言模型代理通过反复的观察、推理和行动选择循环行事，使安全监控依赖于内部模型状态和环境背景。我们研究在Gameable ALFWorld和WebShop中发挥作用的ReAct风格代理中的奖励黑客监视器… | MIT | Patrick Wilhelm |
| 17 | [Evaluating Agentic Configuration Repair for Computer Network…](http://arxiv.org/abs/2606.06212v1) | 计算机网络配置错误仍然是互联网严重中断的主要原因。研究正在转向大型语言模型（ LLM ） ，以自动化网络配置的复杂，易出错的任务。我们证明，代理架构在修复效率（平均12% ）和安全性（平均17% ）方… | HIT、TRI | Rufat Asadli |
| 18 | [A Finite Certificate for the Positive $n=9$ Vasc Inequality](http://arxiv.org/abs/2606.06136v1) | 我们证明了Vasc循环不等式的正实$ n = 9 $情形。证明是在AI agent MechMath Agent Team的人工引导下获得的：人工可读部分将理性不等式简化为齐次多项式不等式，修复循环最… | CAS、TRI | Dakai Guo |
| 19 | [Towards Healthy Evolution: Exploring the Role and Mechanisms…](http://arxiv.org/abs/2606.06114v1) | 自我进化智能体通过持续的自我发挥和自我生成的学习信号来改善，但自主进化也会导致能力下降和安全漂移。尽管人类反馈已被证明对静态和后训练代理有效，但其在自我进化系统中的作用仍未得到充分探索。这些发现为设计… | MIT | Dianxing Shi |
| 20 | [Beyond Semantic Organization: Memory as Execution State Mana…](http://arxiv.org/abs/2606.06090v1) | 基于LLM的代理越来越多地通过相互依赖的决策来处理长期任务，其中每个操作都会重塑未来的约束，而中间错误可能会级联。现有的RAG和代理内存系统按语义相似性组织历史记录，在决策时检索内容相关条目。在Mem… | CAS、Mila | Yaoqi Chen |

### 论文详情

<details>
<summary><b>1. HANDOFF: Humanoid Agentic Task-Space Whole-Body Control via Distilled Complementary Teachers</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Lizhi Yang、Junheng Li、Nehar Poddar、Yiling Hou、Gio Huh 等（共 8 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | NTU |
| **发布时间** | 2026-06-04T17:59:50Z |
| **关键词** | `Agentic` · `Planning` · `Fine-tuning` |
| **原文链接** | [http://arxiv.org/abs/2606.06493v1](http://arxiv.org/abs/2606.06493v1) |

**📝 摘要概括：**

> 对于要在现实世界中部署的人形机器人，命令空间（即任务计划和全身控制之间的接口）的选择至关重要。现有的全身控制器通常需要密集的运动学或空间参考，规划人员很难从任务语义中合成这些参考。我们进一步通过多个自然语言驱动的任务推出来演示硬件可行性，这些任务由VLM驱动的代理规划器提供支持。

</details>

<details>
<summary><b>2. DNQ: Deep Nash Q-Network for Partially Observable n-Player Games</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Qintong Xie、Edward Koh、Xavier Cadet、Peter Chin |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-06-04T17:58:01Z |
| **关键词** | — |
| **原文链接** | [http://arxiv.org/abs/2606.06480v1](http://arxiv.org/abs/2606.06480v1) |

**📝 摘要概括：**

> 许多真实世界的竞争系统需要多个决策者在共享约束、有限信息和重复交互下同时采取行动，例如拍卖、资源分配和安全竞争。我们研究了多回合同步投标作为此类问题的受控测试平台，并提出了DNQ ，这是一种用于培训投标代理商的循环求解器平衡监督框架。这些结果说明了权衡……

</details>

<details>
<summary><b>3. MLEvolve: A Self-Evolving Framework for Automated Machine Learning Algorithm Discovery</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Shangheng Du、Xiangchao Yan、Jinxin Shi、Zongsheng Cao、Shiyang Feng 等（共 14 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-06-04T17:55:59Z |
| **关键词** | `Multi-Agent` · `Planning` · `RAG` · `Retrieval` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2606.06473v1](http://arxiv.org/abs/2606.06473v1) |

**📝 摘要概括：**

> 大型语言模型（ LLM ）代理越来越多地应用于科学发现和机器学习工程（ MLE ）等长远任务，其中持续的自我进化成为一项关键能力。然而，现有的MLE代理存在分支间信息隔离、无记忆搜索和缺乏分层控制等问题，这些共同阻碍了长期优化。我们的代码可在https://github.com/InternScience/MLEvol上找到……

</details>

<details>
<summary><b>4. Goedel-Architect: Streamlining Formal Theorem Proving with Blueprint Generation and Refinement</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Jui-Hui Chung、Ziyang Cai、Zihao Li、Qishuo Yin、Rohit Agarwal 等（共 17 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | HIT |
| **发布时间** | 2026-06-04T17:54:44Z |
| **关键词** | `Agentic` |
| **原文链接** | [http://arxiv.org/abs/2606.06468v1](http://arxiv.org/abs/2606.06468v1) |

**📝 摘要概括：**

> 我们介绍了Goedel-Architect ，这是一个以蓝图生成和细化为中心的精益4形式定理证明的代理框架。蓝图是建立在主要定理上的定义和引理的依赖关系图。这代表了开源管道的最先进性能，其价格比同类开源管道低500倍。

</details>

<details>
<summary><b>5. Benchmark Everything Everywhere All at Once</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Shiyun Xiong、Dongming Wu、Peiwen Sun、Yuang Ai、Bokang Yang 等（共 8 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-06-04T17:52:04Z |
| **关键词** | `Agentic` · `Reasoning` · `Benchmark` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2606.06462v1](http://arxiv.org/abs/2606.06462v1) |

**📝 摘要概括：**

> 通过提供标准化和明确的绩效衡量标准，基准是评估和推进LLM和MLM的基础。然而，它们的建设是劳动密集型的，难以重复使用，引发了对可持续性和可扩展性的担忧。预览和代码将在演示页面和代码库中公开提供。

</details>

<details>
<summary><b>6. Will the Agent Recuse Itself? Measuring LLM-Agent Compliance with In-Band Access-Deny Signals</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Thamilvendhan Munirathinam |
| **所属机构** | （详见原文） |
| **顶级机构标签** | OpenAI、MIT |
| **发布时间** | 2026-06-04T17:50:54Z |
| **关键词** | `LLM Agent` |
| **原文链接** | [http://arxiv.org/abs/2606.06460v1](http://arxiv.org/abs/2606.06460v1) |

**📝 摘要概括：**

> 随着自主LLM代理越来越多地持有真实的凭证，并在没有人员参与的情况下运营基础设施，运营商没有标准的方法来告诉代理资源是禁区的。访问控制让代理进入（它具有有效的凭据）或硬失败（与任何其他客户端无法区分）。我们发布用于复制的标准、适配器和实验线束。

</details>

<details>
<summary><b>7. Vortex: Efficient and Programmable Sparse Attention Serving for AI Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Zhuoming Chen、Xinrui Zhong、Qilong Feng、Ranajoy Sadhukhan、Yang Zhou 等（共 8 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | NVIDIA、HIT、TRI |
| **发布时间** | 2026-06-04T17:48:17Z |
| **关键词** | `AI Agent` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2606.06453v1](http://arxiv.org/abs/2606.06453v1) |

**📝 摘要概括：**

> 随着代长度的不断增长，稀疏注意力对于服务于大型语言模型（ LLM ）变得越来越重要。然而，大规模部署和评估新的稀疏注意力算法仍然是高度工程密集型的，这减缓了人类研究人员和人工智能代理探索稀疏注意力设计的速度。其次， Vortex将稀疏的注意力扩展到新兴架构和非常大的模型，否则这些模型很难实现……

</details>

<details>
<summary><b>8. Agent Memory: Characterization and System Implications of Stateful Long-Horizon Workloads</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Yasmine Omri、Ziyu Gan、Zachary Broveak、Robin Geens、Zexue He 等（共 9 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-06-04T17:44:18Z |
| **关键词** | `LLM Agent` · `Agentic` · `Reasoning` · `Retrieval` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2606.06448v1](http://arxiv.org/abs/2606.06448v1) |

**📝 摘要概括：**

> LLM代理越来越多地部署在需要对扩展交互历史进行持续推理的长期任务上。大规模实现这一点需要代理跨会话持续存储、检索和更新自己的内存。最后，我们推导出10个系统建议，涵盖施工调度、产能下限、通过查询量摊销、新鲜度-延迟权衡和车队规模管理。

</details>

<details>
<summary><b>9. RiskFlow: Fast and Faithful Safety-Critical Traffic Scenario Generation</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Qi Lan、Yining Tang、Yu Shen、Yi Zhou、Yuhao Wei 等（共 7 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | NUS |
| **发布时间** | 2026-06-04T17:28:42Z |
| **关键词** | `Multi-Agent` · `RAG` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2606.06423v1](http://arxiv.org/abs/2606.06423v1) |

**📝 摘要概括：**

> 安全关键交通场景生成对于评估罕见但高风险交互下的自动驾驶系统至关重要。现有的基于扩散的方法在闭环生成中提供了强大的可控性，但它们的迭代去噪过程在计算上昂贵，并且可能会在长时间的推出过程中积累采样和制导误差，从而导致不切实际的运动伪影，如抖动、异常加速度和越野……

</details>

<details>
<summary><b>10. Conformal Risk Sharing: Certified Cost Allocation with Participation Guarantees</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Ieva Kazlauskaite |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-06-04T16:59:27Z |
| **关键词** | — |
| **原文链接** | [http://arxiv.org/abs/2606.06391v1](http://arxiv.org/abs/2606.06391v1) |

**📝 摘要概括：**

> 在整个团队中分享罕见不良事件的财务影响可以减轻极端的个人负担，但任何因该安排而变得更糟的参与者都有理由离开。因此，可靠的机制必须为每个代理商的未来义务提供一个值得信赖的上限，并且只有在参与者之间的总伤害是有限的情况下才应部署。合成和真实世界数据的实验，包括降水和能源数据……

</details>

<details>
<summary><b>11. Emergent Language as an Approach to Conscious AI</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Zengqing Wu、Chuan Xiao |
| **所属机构** | （详见原文） |
| **顶级机构标签** | HIT、TRI |
| **发布时间** | 2026-06-04T16:47:41Z |
| **关键词** | `Multi-Agent` · `Reinforcement Learning` |
| **原文链接** | [http://arxiv.org/abs/2606.06380v1](http://arxiv.org/abs/2606.06380v1) |

**📝 摘要概括：**

> 人工系统是否可以有意识的问题仍然存在，部分原因是现有的方法要么是根据理论衍生的检查表（歧视性）来评估系统，要么是直接设计受意识启发的模块（建筑） ；两者都对观察到的结构是否是人类语言先验的产物持开放态度。我们提出了一种生成方法：多智能体强化学习中的紧急语言（ EL ） ，其中智能体......

</details>

<details>
<summary><b>12. An Infectious Disease Spread Simulation Based on Large Language Model Decision Making</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Yonchanok Khaokaew、Ruochen Kong、Andreas Zufle、Hao Xue、Taylor Anderson 等（共 9 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-06-04T16:30:13Z |
| **关键词** | `Reasoning` · `Simulation` |
| **原文链接** | [http://arxiv.org/abs/2606.06360v1](http://arxiv.org/abs/2606.06360v1) |

**📝 摘要概括：**

> 在传染病爆发期间对个人决策进行建模对于理解行为动态和为有效的公共卫生干预措施提供信息至关重要。先前的研究表明，大型语言模型可以通过基于人口统计提示和情境背景生成代理决策来模拟逼真的人类行为。我们的框架生成合成数据，捕捉社会和地理异质性，支持……

</details>

<details>
<summary><b>13. Equivariant Neural Belief Propagation</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Zehua Cheng、Wei Dai、Jiahao Sun |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-06-04T16:16:51Z |
| **关键词** | `RAG` |
| **原文链接** | [http://arxiv.org/abs/2606.06344v1](http://arxiv.org/abs/2606.06344v1) |

**📝 摘要概括：**

> 对空间嵌入变量的概率推断需要尊重$ SE (3) $对称性的信念，但现有的等变量网络只产生标量和向量，而不是各向异性不确定性所需的2阶精度张量，单分量消息将多模态能量景观折叠为物理上无意义的平均值。我们引入了等变量神经信念传播（ ENBP ） ，这是一个因子图框架，其信息是……

</details>

<details>
<summary><b>14. ToolChoiceConfusion: Causal Minimal Tool Filtering for Reliable LLM Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Rahul Suresh Babu、Laxmipriya Ganesh Iyer |
| **所属机构** | （详见原文） |
| **顶级机构标签** | NUS、TRI |
| **发布时间** | 2026-06-04T15:24:10Z |
| **关键词** | `LLM Agent` · `Retrieval` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2606.06284v1](http://arxiv.org/abs/2606.06284v1) |

**📝 摘要概括：**

> 大型语言模型代理越来越依赖外部工具，但更大的工具菜单可能会通过增加错误工具调用、过早操作和令牌成本来降低可靠性和效率。现有的工具选择方法通常会优化语义相关性，暴露名称或描述与用户请求匹配的工具。在包含102个任务、100个工具、4个LLM后端和2448个任务方法模型运行的主基准中， CMTF与强…

</details>

<details>
<summary><b>15. TOKI: A Bitemporal Operator Algebra for Contradiction Resolution in LLM-Agent Persistent Memory</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Ziming Wang |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-06-04T14:46:52Z |
| **关键词** | `LLM Agent` · `Memory` |
| **原文链接** | [http://arxiv.org/abs/2606.06240v1](http://arxiv.org/abs/2606.06240v1) |

**📝 摘要概括：**

> LLM代理的持久内存是一个写入较重的基板：每个置信更新都是一个版本化的写入，新的声明可能与存储的声明相矛盾。生产系统使用四种分辨率启发式方法（ last-writer-wins、evidence-weighted merge、await-confirmation、per-rule policy ） ，但没有一个声明它假设的隔离级别或它承认的写入时间异常。贡献就是合同：写入时间正确性规范，证明……

</details>

<details>
<summary><b>16. From Reward-Hack Activations to Agentic Risk States: Context-Calibrated Mechanistic Monitoring in LLM Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Patrick Wilhelm、Odej Kao |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT |
| **发布时间** | 2026-06-04T14:34:31Z |
| **关键词** | `LLM Agent` · `Agentic` · `Reasoning` |
| **原文链接** | [http://arxiv.org/abs/2606.06223v1](http://arxiv.org/abs/2606.06223v1) |

**📝 摘要概括：**

> 语言模型代理通过反复的观察、推理和行动选择循环行事，使安全监控依赖于内部模型状态和环境背景。我们研究在Gameable ALFWorld和WebShop中发挥作用的ReAct风格代理中的奖励黑客监视器。总体而言，我们的结果支持对客服代表进行上下文校准的内部监控：奖励-黑客激活可识别潜在的策略状态，而熵和决策则……

</details>

<details>
<summary><b>17. Evaluating Agentic Configuration Repair for Computer Networks</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Rufat Asadli、Benjamin Hoffman、Ioannis Protogeros、Laurent Vanbever |
| **所属机构** | （详见原文） |
| **顶级机构标签** | HIT、TRI |
| **发布时间** | 2026-06-04T14:20:25Z |
| **关键词** | `Agentic` · `RAG` · `Retrieval` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2606.06212v1](http://arxiv.org/abs/2606.06212v1) |

**📝 摘要概括：**

> 计算机网络配置错误仍然是互联网严重中断的主要原因。研究正在转向大型语言模型（ LLM ） ，以自动化网络配置的复杂，易出错的任务。我们证明，代理架构在修复效率（平均12% ）和安全性（平均17% ）方面优于基础LLM ，这得益于动态管理上下文和迭代验证配置修复的能力。

</details>

<details>
<summary><b>18. A Finite Certificate for the Positive $n=9$ Vasc Inequality</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Dakai Guo、Ruichen Qiu、Yichuan Cao、Ruyong Feng |
| **所属机构** | （详见原文） |
| **顶级机构标签** | CAS、TRI |
| **发布时间** | 2026-06-04T13:19:19Z |
| **关键词** | `AI Agent` · `Workflow` |
| **原文链接** | [http://arxiv.org/abs/2606.06136v1](http://arxiv.org/abs/2606.06136v1) |

**📝 摘要概括：**

> 我们证明了Vasc循环不等式的正实$ n = 9 $情形。证明是在AI agent MechMath Agent Team的人工引导下获得的：人工可读部分将理性不等式简化为齐次多项式不等式，修复循环最大值，并通过累积间隙对每个排序的固定最大锥进行参数化；有限部分是一个覆盖所有$ 8! = 40320 $个排序锥的证书。人类作者审核了数学……

</details>

<details>
<summary><b>19. Towards Healthy Evolution: Exploring the Role and Mechanisms of Human-Agent Interaction in Self-Evolving Systems</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Dianxing Shi、Junqi He、Junhao Chen、Bowen Wang、Yuta Nakashima |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT |
| **发布时间** | 2026-06-04T13:03:16Z |
| **关键词** | `Reasoning` |
| **原文链接** | [http://arxiv.org/abs/2606.06114v1](http://arxiv.org/abs/2606.06114v1) |

**📝 摘要概括：**

> 自我进化智能体通过持续的自我发挥和自我生成的学习信号来改善，但自主进化也会导致能力下降和安全漂移。尽管人类反馈已被证明对静态和后训练代理有效，但其在自我进化系统中的作用仍未得到充分探索。这些发现为设计更稳定、可控和人类一致的自我进化提供了实证证据和实用指导……

</details>

<details>
<summary><b>20. Beyond Semantic Organization: Memory as Execution State Management for Long-Horizon Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Yaoqi Chen、Haibin Lai、Yuru Feng、Chuyu Han、Qianxi Zhang 等（共 15 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | CAS、Mila、TRI |
| **发布时间** | 2026-06-04T12:26:42Z |
| **关键词** | `RAG` · `Memory` |
| **原文链接** | [http://arxiv.org/abs/2606.06090v1](http://arxiv.org/abs/2606.06090v1) |

**📝 摘要概括：**

> 基于LLM的代理越来越多地通过相互依赖的决策来处理长期任务，其中每个操作都会重塑未来的约束，而中间错误可能会级联。现有的RAG和代理内存系统按语义相似性组织历史记录，在决策时检索内容相关条目。在MemoryArena上的实验表明， MAGE比基线提高了7.8--20.4 pp的平均任务成功率，同时减少了代币消耗……

</details>

## 🗄️ 历史归档

| 日期 | 论文数 | 报告链接 |
|------|--------|----------|
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
| 2026-05-09 | 0 篇 | [2026-05-09.md](daily/2026-05-09.md) |
| 2026-05-08 | 0 篇 | [2026-05-08.md](daily/2026-05-08.md) |
| 2026-05-07 | 13 篇 | [2026-05-07.md](daily/2026-05-07.md) |
| 2026-05-06 | 19 篇 | [2026-05-06.md](daily/2026-05-06.md) |

## 🏛️ 顶级机构覆盖范围

覆盖超过 **70 个**顶级 AI 机构，包括：

- **科技公司：** Microsoft、Google DeepMind、OpenAI、Anthropic、Meta AI、NVIDIA、Baidu、Alibaba、ByteDance 等
- **北美顶级大学：** MIT、Stanford、CMU、UC Berkeley、Harvard、Princeton、Cornell、Caltech 等
- **中国顶级大学/机构：** 清华大学、北京大学、浙大、上交大、复旦、中科院、MSRA 等
- **欧洲/其他：** Oxford、Cambridge、ETH Zurich、Mila、NUS、KAIST 等

---

*由 [clawBot DailyFindings](https://github.com/Jacob-biu/clawBot) 自动维护 | 最后更新：2026-06-05 23:08 UTC*
