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

## 📅 今日论文 — 2026-11-25　　[→ 查看完整报告](daily/2026-11-25.md)

> 共筛选出 **20** 篇论文 | 更新于 2026-11-25 04:49 UTC

### 论文目录与概要

| # | 论文标题 | 核心概要 | 来源机构 | 第一作者 |
|---|---------|---------|---------|--------|
| 1 | [Attestation is All You Need: Toward a Zero-Trust Architectur…](http://arxiv.org/abs/2611.32958v1) | AI 代理正开始在 HPC 环境中实现数据分析、编排和模拟引导的自动化，但它们也带来了一个现有集群防御措施无法解决的安全问题：被劫持的授权代理。攻击者可以通过提示注入、中毒的共享数据、受损的工具或多代… | TRI | Jie Li |
| 2 | [LoomKV: Lossless KV Cache Compression from GPU Memory to SSD…](http://arxiv.org/abs/2611.32954v1) | 大型语言模型（LLM）服务引擎将键/值（KV）缓存从GPU内存卸载到主机DRAM和SSD，以便多轮和代理请求可以重用提示前缀。然后，容量在两个层面上限制服务：外部层在驱逐之前控制前缀的重用，而 GPU… | MIT | Wentao Zhu |
| 3 | [Reading Decisions Before Spans: Efficient Generative Verific…](http://arxiv.org/abs/2611.32931v1) | 开发人员在检查助手的报告时，可能只需要一个提示，告知某项主张没有得到支持。然而，生成式核验器可以继续解码，以引用和分类错误。受控证据干预和首个位置解码确定了这些较短的读出结果保留了哪些内容，以及哪些内… | TRI | Yanbin Gong |
| 4 | [Lazy Agents Answer Against Their Own Beliefs: Reinforcement …](http://arxiv.org/abs/2611.32884v1) | 处理长任务的 AI 代理通常会在没有足够证据的情况下就给出答案，这种行为被称为“懒惰”。在我们的评估中，即使它们所陈述的信念仍然列出了几个可能的答案，它们也经常做出承诺。在证据不足且其行中仍列出多个答… | MIT | Richmond Sin Jing Xuan |
| 5 | [Breaking the Joint Action Space Dependence in Distributional…](http://arxiv.org/abs/2611.32812v1) | 我们研究了在具有已知奖励和名义转移生成模型的有限时域、广义和、分布鲁棒马尔可夫博弈中学习鲁棒粗相关均衡（CCE）的样本复杂度。每个博弈者根据策略在以每个阶段、状态和联合行动的名义转移分布为中心的总变差… | CAS、TRI | Yue Wang |
| 6 | [Interactive Neural Computers](http://arxiv.org/abs/2611.32811v1) | 计算机及其界面通常被视为固定的，因此人（或者越来越多地是人工智能代理）必须适应操作系统所呈现的一切。当有人需要不同的工作流程，或者需要适合免提使用或残障人士使用的界面时，这就显得很受限制。最后，由于内… | MIT、TRI | Ross Murphy |
| 7 | [EviCraft: Can Minecraft Agents Find What They Cannot See?](http://arxiv.org/abs/2611.32765v1) | 在 Minecraft 中，作为具身智能体的常见测试平台，mineBlock 等语义工具会从模拟器加载的世界状态中选择目标，而无需进行可见性测试，因此，智能体从未见过的埋藏矿石只需一次调用即可获得，且… | MIT | Wenyou Yi |
| 8 | [CAPTA: Identifying LLMs Behind AI Agents](http://arxiv.org/abs/2611.32686v1) | 基于大型语言模型（LLM）的代理通过工具访问远程服务以完成用户任务，通常通过 API 调用来实现。在这种情况下，远程服务可能希望识别代理的后端LLM，以发起针对特定模型的攻击，包括提示注入或有选择地提… | MIT | Kailun Yan |
| 9 | [Economic World Model](http://arxiv.org/abs/2611.32663v1) | 人工智能能否再现家庭、企业和政府通过市场和机构进行互动和适应时所产生的经济动态？为了回答这个问题，我们将经济世界模型（EWM）定义为代理人对经济系统运作方式的内部表征，使之能够在资源受限的情况下进行反… | CAS、TRI | Qirui Mi |
| 10 | [Bathys: Advancing Deep Search Agents](http://arxiv.org/abs/2611.32660v1) | 深度搜索是智能体应对复杂、开放式任务的关键能力，在这种任务中，解决问题需要迭代式的信息收集、查询重构和基于证据的验证，而不仅仅是一个检索步骤。为了满足这些要求，我们推出了 Bathys 9B 和 27… | TRI | Zixuan Chen |
| 11 | [ICLWorld: Benchmarking In-Context Learning of Agents from Di…](http://arxiv.org/abs/2611.32649v1) | 情境学习（ICL）使智能体能够从情境中学习新规则，并在推理时适应特定于用户的要求。如今，同样的尖端大模型既能操作计算机，也能操作机器人，但其ICL仍未得到充分评估：现有的基准大多是离线的，依赖于文本或… | MIT、NTU | Qingle Liu |
| 12 | [TeamFlowRL: Online Policy Optimization of Decentralized Flow…](http://arxiv.org/abs/2611.32645v1) | 复杂的协作任务需要多智能体行为的协调。离线生成式策略从轨迹中学习富有表现力的合作行为，但仍然受到固定数据集的限制。在6项双手任务中，与高斯策略微调相比，它在探索噪声下的平均成功率也高出33.1%。 | MIT | Guowei Zou |
| 13 | [RoboRecast: Intent-Preserving Demonstration Augmentation via…](http://arxiv.org/abs/2611.32622v1) | 收集各种各样的真实世界操作示范成本高昂，因此有必要使用模拟来扩充现有的示范，以用于机器人策略学习。当物体、布局或机器人发生变化时，从源示范中迁移动作可能会在新环境中产生语义上不合理或物理上不可行的行为… | CAS | Yushi Long |
| 14 | [Next-Manip: On-Demand Agent-Policy Collaboration for Robotic…](http://arxiv.org/abs/2611.32533v1) | 通用机器人操纵需要任务推理、故障恢复和精确控制，但由于操纵数据有限，很难从单一策略中获得这些能力。最近的多模态智能体在任务推理和故障恢复方面表现出潜力，但缺乏可靠的精细控制，且推理成本较高；而学习型策… | MIT | Jiayi Liu |
| 15 | [VISE: Verifier-Independent Skill Self-Evolution with Feedbac…](http://arxiv.org/abs/2611.32480v1) | Agent技能提供可重复使用的工作流，指导LLM Agent使用工具。要优化这些工作流，需要就缺失或不正确的指令提供反馈，但并非总能找到针对具体任务的核验器。这些结果支持将工具实现作为技能自我进化的实… | CAS | Yuxuan Liu |
| 16 | [See the Answer, Learn to Embed: Learning Universal Multimoda…](http://arxiv.org/abs/2611.32439v1) | 通用多模态嵌入（UME）模型将异构多模态输入映射到共享嵌入空间，其中成对相似性支持多种下游任务。最近的推理驱动型 UME 方法使用中间推理来生成用于嵌入的额外上下文，但通常会在推理时产生额外的计算。在… | MIT、Mila | Yoonki Cho |
| 17 | [Within-task hazards of AI agents: unidentified by time-horiz…](http://arxiv.org/abs/2611.32415v1) | 人工智能体的时间范围是从一条曲线上读出的：这条曲线将人工智能体完成任务的概率与人类完成该任务所需的时间绘制在一起。最近的几项分析将生存模型拟合到这条曲线上，并得出结论：随着任务的进行，智能体的失败风险… | MIT | Ruiqi Zhao |
| 18 | [Verify then Steer: Progress Hallucination-Aware Recovery for…](http://arxiv.org/abs/2611.32400v1) | 视觉-语言导航 (VLN) 要求智能体遵循语言指令，在未曾见过的 3D 环境中到达目标位置。然而，现有方法在测试时仍难以从路线偏离中恢复。通过对 R2R-CE 和 RxR-CE 进行大量实验，我们的框… | MIT | Jiewen Hou |
| 19 | [Evolve to Learn: Gradient-aligned experience evolution for m…](http://arxiv.org/abs/2611.32390v1) | 自我演进的语言模型可以通过测试时交互、反思和提示优化来持续获得有用的经验，但将此类经验转化为模型本身以确保自我改进仍然是一项挑战。策略内自我蒸馏（OPSD）提供了一种将测试时信息内化为模型参数的自然机… | MIT | Haoyuan Li |
| 20 | [Can AI Design a Better nnU-Net? A Hypothesis-Driven Architec…](http://arxiv.org/abs/2611.32384v1) | 神经架构搜索和LLM驱动的演化通常会将评估简化为标量适应度得分，从而舍弃了那些能够解释设计成功或失败原因的失败案例。我们提出了一种以假设为驱动的架构发现循环，其中LLM代理诊断结构化错误模式，提出可证… | HIT、TRI | Songtao Jiang |

### 论文详情

<details>
<summary><b>1. Attestation is All You Need: Toward a Zero-Trust Architecture for HPC AI Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Jie Li、Chenxu Niu、Tongyang Wang、Yong Chen |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-11-24T16:57:12Z |
| **关键词** | `Multi-Agent` · `AI Agent` · `RAG` · `Simulation` · `Workflow` |
| **原文链接** | [http://arxiv.org/abs/2611.32958v1](http://arxiv.org/abs/2611.32958v1) |

**📝 摘要概括：**

> AI 代理正开始在 HPC 环境中实现数据分析、编排和模拟引导的自动化，但它们也带来了一个现有集群防御措施无法解决的安全问题：被劫持的授权代理。攻击者可以通过提示注入、中毒的共享数据、受损的工具或多代理协调来颠覆代理，然后通过合法的加密 LLM API 流量窃取敏感数据。受控实验……

</details>

<details>
<summary><b>2. LoomKV: Lossless KV Cache Compression from GPU Memory to SSD for LLM Serving</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Wentao Zhu、Ziao Sheng、Peng Deng、Huiqi Hu、Xuan Zhou 等（共 7 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT |
| **发布时间** | 2026-11-24T16:54:37Z |
| **关键词** | `RAG` · `Memory` |
| **原文链接** | [http://arxiv.org/abs/2611.32954v1](http://arxiv.org/abs/2611.32954v1) |

**📝 摘要概括：**

> 大型语言模型（LLM）服务引擎将键/值（KV）缓存从GPU内存卸载到主机DRAM和SSD，以便多轮和代理请求可以重用提示前缀。然后，容量在两个层面上限制服务：外部层在驱逐之前控制前缀的重用，而 GPU KV 池则限制并发的长请求，有损压缩会改变 KV 值和输出。在原始容量足够的情况下，压缩最多只会使吞吐量降低 2.2%；ti…

</details>

<details>
<summary><b>3. Reading Decisions Before Spans: Efficient Generative Verification</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Yanbin Gong、Lei Chen |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-11-24T16:38:25Z |
| **关键词** | — |
| **原文链接** | [http://arxiv.org/abs/2611.32931v1](http://arxiv.org/abs/2611.32931v1) |

**📝 摘要概括：**

> 开发人员在检查助手的报告时，可能只需要一个提示，告知某项主张没有得到支持。然而，生成式核验器可以继续解码，以引用和分类错误。受控证据干预和首个位置解码确定了这些较短的读出结果保留了哪些内容，以及哪些内容需要进一步生成。

</details>

<details>
<summary><b>4. Lazy Agents Answer Against Their Own Beliefs: Reinforcement Learning with Verifiable Beliefs Teaches Them to Act on What They Believe</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Richmond Sin Jing Xuan、Peilin Feng、Wenbin Wang、Soujanya Poria |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT |
| **发布时间** | 2026-11-24T16:17:51Z |
| **关键词** | `AI Agent` · `Reinforcement Learning` · `RAG` · `Benchmark` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2611.32884v1](http://arxiv.org/abs/2611.32884v1) |

**📝 摘要概括：**

> 处理长任务的 AI 代理通常会在没有足够证据的情况下就给出答案，这种行为被称为“懒惰”。在我们的评估中，即使它们所陈述的信念仍然列出了几个可能的答案，它们也经常做出承诺。在证据不足且其行中仍列出多个答案的回合中，它仅在 0.1% 至 2.2% 的回合中做出承诺，而基准模型则为 3% 至 68%。

</details>

<details>
<summary><b>5. Breaking the Joint Action Space Dependence in Distributionally Robust Multi-Agent Reinforcement Learning</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Yue Wang |
| **所属机构** | （详见原文） |
| **顶级机构标签** | CAS、TRI |
| **发布时间** | 2026-11-24T15:32:04Z |
| **关键词** | `Multi-Agent` · `Reinforcement Learning` |
| **原文链接** | [http://arxiv.org/abs/2611.32812v1](http://arxiv.org/abs/2611.32812v1) |

**📝 摘要概括：**

> 我们研究了在具有已知奖励和名义转移生成模型的有限时域、广义和、分布鲁棒马尔可夫博弈中学习鲁棒粗相关均衡（CCE）的样本复杂度。每个博弈者根据策略在以每个阶段、状态和联合行动的名义转移分布为中心的总变差 (TV) 球上的最坏情况回报来评估该策略；这是标准的 $(s,a)$-矩形不确定性…

</details>

<details>
<summary><b>6. Interactive Neural Computers</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Ross Murphy、Marcel Hedman、Gabriel Brostow |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-11-24T15:30:05Z |
| **关键词** | `AI Agent` · `Reasoning` · `Memory` · `Workflow` |
| **原文链接** | [http://arxiv.org/abs/2611.32811v1](http://arxiv.org/abs/2611.32811v1) |

**📝 摘要概括：**

> 计算机及其界面通常被视为固定的，因此人（或者越来越多地是人工智能代理）必须适应操作系统所呈现的一切。当有人需要不同的工作流程，或者需要适合免提使用或残障人士使用的界面时，这就显得很受限制。最后，由于内存是显式的，因此可以在测试时移植内存，从而因果性地改变模型的渲染内容。

</details>

<details>
<summary><b>7. EviCraft: Can Minecraft Agents Find What They Cannot See?</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Wenyou Yi、Lantian Zhang、Guanlin Chen、Xingqiu Xu、Haiyang Sun 等（共 10 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT |
| **发布时间** | 2026-11-24T15:03:47Z |
| **关键词** | `Benchmark` · `Embodied AI` |
| **原文链接** | [http://arxiv.org/abs/2611.32765v1](http://arxiv.org/abs/2611.32765v1) |

**📝 摘要概括：**

> 在 Minecraft 中，作为具身智能体的常见测试平台，mineBlock 等语义工具会从模拟器加载的世界状态中选择目标，而无需进行可见性测试，因此，智能体从未见过的埋藏矿石只需一次调用即可获得，且得分无法显示智能体是否进行了搜索。我们将缺失的要求形式化为证据封闭性：智能体系统的每个决策（包括其工具内部的决策）可能仅通过w的……事实来依赖世界。

</details>

<details>
<summary><b>8. CAPTA: Identifying LLMs Behind AI Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Kailun Yan、Yue Huang、Sisi Duan |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT |
| **发布时间** | 2026-11-24T14:25:39Z |
| **关键词** | `AI Agent` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2611.32686v1](http://arxiv.org/abs/2611.32686v1) |

**📝 摘要概括：**

> 基于大型语言模型（LLM）的代理通过工具访问远程服务以完成用户任务，通常通过 API 调用来实现。在这种情况下，远程服务可能希望识别代理的后端LLM，以发起针对特定模型的攻击，包括提示注入或有选择地提供经过篡改的内容。我们使用四种广泛使用的代理和七种具有代表性的LLM进一步评估了CAPTA，在……方面实现了99.7%的平均识别准确率。

</details>

<details>
<summary><b>9. Economic World Model</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Qirui Mi、Yujia Ming、Bo Li、Haifeng Zhang |
| **所属机构** | （详见原文） |
| **顶级机构标签** | CAS、TRI |
| **发布时间** | 2026-11-24T14:14:40Z |
| **关键词** | `LLM Agent` · `Planning` · `Benchmark` · `Evaluation` · `Simulation` |
| **原文链接** | [http://arxiv.org/abs/2611.32663v1](http://arxiv.org/abs/2611.32663v1) |

**📝 摘要概括：**

> 人工智能能否再现家庭、企业和政府通过市场和机构进行互动和适应时所产生的经济动态？为了回答这个问题，我们将经济世界模型（EWM）定义为代理人对经济系统运作方式的内部表征，使之能够在资源受限的情况下进行反事实模拟和决策。我们共同的目标不仅是再现真实的经济动态，而且……

</details>

<details>
<summary><b>10. Bathys: Advancing Deep Search Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Zixuan Chen、Shengyou Yuan、Nang Yuan、Ming Ma、Zelin Xiao 等（共 13 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-11-24T14:12:23Z |
| **关键词** | `Reinforcement Learning` · `RAG` · `Retrieval` · `Evaluation` · `Fine-tuning` |
| **原文链接** | [http://arxiv.org/abs/2611.32660v1](http://arxiv.org/abs/2611.32660v1) |

**📝 摘要概括：**

> 深度搜索是智能体应对复杂、开放式任务的关键能力，在这种任务中，解决问题需要迭代式的信息收集、查询重构和基于证据的验证，而不仅仅是一个检索步骤。为了满足这些要求，我们推出了 Bathys 9B 和 27B 深度搜索代理，它们基于一个训练框架构建，该框架涵盖可验证的问题合成、训练后和在线强化学习 (RL)……

</details>

<details>
<summary><b>11. ICLWorld: Benchmarking In-Context Learning of Agents from Digital to Physical Worlds</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Qingle Liu、Jieming Li、Pei-lin Li、Shenghan Zheng、Ruize Yang 等（共 10 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、NTU |
| **发布时间** | 2026-11-24T14:07:17Z |
| **关键词** | `Benchmark` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2611.32649v1](http://arxiv.org/abs/2611.32649v1) |

**📝 摘要概括：**

> 情境学习（ICL）使智能体能够从情境中学习新规则，并在推理时适应特定于用户的要求。如今，同样的尖端大模型既能操作计算机，也能操作机器人，但其ICL仍未得到充分评估：现有的基准大多是离线的，依赖于文本或静态图像，并存在训练数据污染的风险，而机器人评估则仅限于方法层面的消融。这些发现揭示了显著的差距……

</details>

<details>
<summary><b>12. TeamFlowRL: Online Policy Optimization of Decentralized Flow Policies for Multi-Agent Coordination</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Guowei Zou、Beiwen Zhang、Haitao Wang、Hong Hong、Zhiquan Chen 等（共 6 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT |
| **发布时间** | 2026-11-24T14:04:38Z |
| **关键词** | `Multi-Agent` · `Reinforcement Learning` · `RAG` · `Fine-tuning` · `Simulation` |
| **原文链接** | [http://arxiv.org/abs/2611.32645v1](http://arxiv.org/abs/2611.32645v1) |

**📝 摘要概括：**

> 复杂的协作任务需要多智能体行为的协调。离线生成式策略从轨迹中学习富有表现力的合作行为，但仍然受到固定数据集的限制。在6项双手任务中，与高斯策略微调相比，它在探索噪声下的平均成功率也高出33.1%。

</details>

<details>
<summary><b>13. RoboRecast: Intent-Preserving Demonstration Augmentation via Diagnosis-Driven Optimization</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Yushi Long、Juzhan Xu、Haibin Huang、Chi Zhang、Yin Chen 等（共 8 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | CAS |
| **发布时间** | 2026-11-24T13:48:19Z |
| **关键词** | `Agentic` · `Simulation` |
| **原文链接** | [http://arxiv.org/abs/2611.32622v1](http://arxiv.org/abs/2611.32622v1) |

**📝 摘要概括：**

> 收集各种各样的真实世界操作示范成本高昂，因此有必要使用模拟来扩充现有的示范，以用于机器人策略学习。当物体、布局或机器人发生变化时，从源示范中迁移动作可能会在新环境中产生语义上不合理或物理上不可行的行为。即使在目标配置中没有示范，RoboRecast也能对源示范进行调整……

</details>

<details>
<summary><b>14. Next-Manip: On-Demand Agent-Policy Collaboration for Robotic Manipulation</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Jiayi Liu、Ke Ye、Jiaming Zhou、Yufei Huang、Haotian Liang 等（共 7 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT |
| **发布时间** | 2026-11-24T12:58:21Z |
| **关键词** | `Reasoning` · `Benchmark` · `Simulation` |
| **原文链接** | [http://arxiv.org/abs/2611.32533v1](http://arxiv.org/abs/2611.32533v1) |

**📝 摘要概括：**

> 通用机器人操纵需要任务推理、故障恢复和精确控制，但由于操纵数据有限，很难从单一策略中获得这些能力。最近的多模态智能体在任务推理和故障恢复方面表现出潜力，但缺乏可靠的精细控制，且推理成本较高；而学习型策略则能提供高效的精细执行，但在其所学技能之外就力不从心。在两个……

</details>

<details>
<summary><b>15. VISE: Verifier-Independent Skill Self-Evolution with Feedback from Tool Implementations</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Yuxuan Liu、Chongyang Du、Yuhao Zhang、Jiahe Guo、Kawai Chung 等（共 12 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | CAS |
| **发布时间** | 2026-11-24T12:08:40Z |
| **关键词** | `LLM Agent` · `RAG` · `Workflow` |
| **原文链接** | [http://arxiv.org/abs/2611.32480v1](http://arxiv.org/abs/2611.32480v1) |

**📝 摘要概括：**

> Agent技能提供可重复使用的工作流，指导LLM Agent使用工具。要优化这些工作流，需要就缺失或不正确的指令提供反馈，但并非总能找到针对具体任务的核验器。这些结果支持将工具实现作为技能自我进化的实用反馈来源。

</details>

<details>
<summary><b>16. See the Answer, Learn to Embed: Learning Universal Multimodal Embeddings from Hindsight</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Yoonki Cho、Youngju Na、Taegeun Yang、Jinhwan Seo、Sung-Eui Yoon |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、Mila、TRI |
| **发布时间** | 2026-11-24T11:39:03Z |
| **关键词** | `Reasoning` |
| **原文链接** | [http://arxiv.org/abs/2611.32439v1](http://arxiv.org/abs/2611.32439v1) |

**📝 摘要概括：**

> 通用多模态嵌入（UME）模型将异构多模态输入映射到共享嵌入空间，其中成对相似性支持多种下游任务。最近的推理驱动型 UME 方法使用中间推理来生成用于嵌入的额外上下文，但通常会在推理时产生额外的计算。在 MMEB-V2 以及 MMEB-V3 的代理和文本任务上进行的实验表明，HEME 具有有效性，并显示其……

</details>

<details>
<summary><b>17. Within-task hazards of AI agents: unidentified by time-horizon curves, identified by repeated runs</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Ruiqi Zhao |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT |
| **发布时间** | 2026-11-24T11:18:43Z |
| **关键词** | `AI Agent` · `RAG` |
| **原文链接** | [http://arxiv.org/abs/2611.32415v1](http://arxiv.org/abs/2611.32415v1) |

**📝 摘要概括：**

> 人工智能体的时间范围是从一条曲线上读出的：这条曲线将人工智能体完成任务的概率与人类完成该任务所需的时间绘制在一起。最近的几项分析将生存模型拟合到这条曲线上，并得出结论：随着任务的进行，智能体的失败风险会降低。$k>1$是否反映了任务中出现的风险，或者反映了人类时间只能粗略衡量其难度的任务，需要通过实验来观察同一任务在多个……

</details>

<details>
<summary><b>18. Verify then Steer: Progress Hallucination-Aware Recovery for Continuous Vision-and-Language Navigation</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Jiewen Hou、Guanxiang Qi、Meina Kan、Shiguang Shan、Xilin Chen |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT |
| **发布时间** | 2026-11-24T11:05:44Z |
| **关键词** | — |
| **原文链接** | [http://arxiv.org/abs/2611.32400v1](http://arxiv.org/abs/2611.32400v1) |

**📝 摘要概括：**

> 视觉-语言导航 (VLN) 要求智能体遵循语言指令，在未曾见过的 3D 环境中到达目标位置。然而，现有方法在测试时仍难以从路线偏离中恢复。通过对 R2R-CE 和 RxR-CE 进行大量实验，我们的框架在测试时提高了多种先进视觉-语言导航方法的可靠性。

</details>

<details>
<summary><b>19. Evolve to Learn: Gradient-aligned experience evolution for model self-improvement</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Haoyuan Li、Gangyi Zhang、Dong Wang、Yang Liu、Daoxuan Liu 等（共 10 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT |
| **发布时间** | 2026-11-24T10:54:17Z |
| **关键词** | — |
| **原文链接** | [http://arxiv.org/abs/2611.32390v1](http://arxiv.org/abs/2611.32390v1) |

**📝 摘要概括：**

> 自我演进的语言模型可以通过测试时交互、反思和提示优化来持续获得有用的经验，但将此类经验转化为模型本身以确保自我改进仍然是一项挑战。策略内自我蒸馏（OPSD）提供了一种将测试时信息内化为模型参数的自然机制，但它在很大程度上假定所生成的经验值得学习。E2L 弥补了……

</details>

<details>
<summary><b>20. Can AI Design a Better nnU-Net? A Hypothesis-Driven Architecture Discovery Loop from Failures to Design Rules</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Songtao Jiang、Yuan Wang、Fucheng Niu、Hualiang Wang、Jian Wu 等（共 6 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | HIT、TRI |
| **发布时间** | 2026-11-24T10:49:50Z |
| **关键词** | `LLM Agent` · `Benchmark` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2611.32384v1](http://arxiv.org/abs/2611.32384v1) |

**📝 摘要概括：**

> 神经架构搜索和LLM驱动的演化通常会将评估简化为标量适应度得分，从而舍弃了那些能够解释设计成功或失败原因的失败案例。我们提出了一种以假设为驱动的架构发现循环，其中LLM代理诊断结构化错误模式，提出可证伪的假设，在冻结的nnU-Net管道下测试反事实对照，并将经过验证的机制提炼为可执行的触发-行动规则……

</details>

## 🗄️ 历史归档

| 日期 | 论文数 | 报告链接 |
|------|--------|----------|
| 2026-11-25 | 20 篇 | [2026-11-25.md](daily/2026-11-25.md) |
| 2026-11-24 | 20 篇 | [2026-11-24.md](daily/2026-11-24.md) |
| 2026-11-23 | 0 篇 | [2026-11-23.md](daily/2026-11-23.md) |
| 2026-11-22 | 0 篇 | [2026-11-22.md](daily/2026-11-22.md) |
| 2026-11-21 | 16 篇 | [2026-11-21.md](daily/2026-11-21.md) |
| 2026-11-20 | 20 篇 | [2026-11-20.md](daily/2026-11-20.md) |
| 2026-11-05 | 13 篇 | [2026-11-05.md](daily/2026-11-05.md) |
| 2026-11-04 | 20 篇 | [2026-11-04.md](daily/2026-11-04.md) |
| 2026-11-03 | 0 篇 | [2026-11-03.md](daily/2026-11-03.md) |
| 2026-11-02 | 0 篇 | [2026-11-02.md](daily/2026-11-02.md) |
| 2026-11-01 | 0 篇 | [2026-11-01.md](daily/2026-11-01.md) |
| 2026-10-31 | 17 篇 | [2026-10-31.md](daily/2026-10-31.md) |
| 2026-10-30 | 0 篇 | [2026-10-30.md](daily/2026-10-30.md) |
| 2026-10-29 | 20 篇 | [2026-10-29.md](daily/2026-10-29.md) |
| 2026-10-28 | 20 篇 | [2026-10-28.md](daily/2026-10-28.md) |
| 2026-10-27 | 0 篇 | [2026-10-27.md](daily/2026-10-27.md) |
| 2026-10-25 | 0 篇 | [2026-10-25.md](daily/2026-10-25.md) |
| 2026-10-24 | 0 篇 | [2026-10-24.md](daily/2026-10-24.md) |
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

## 🏛️ 顶级机构覆盖范围

覆盖超过 **70 个**顶级 AI 机构，包括：

- **科技公司：** Microsoft、Google DeepMind、OpenAI、Anthropic、Meta AI、NVIDIA、Baidu、Alibaba、ByteDance 等
- **北美顶级大学：** MIT、Stanford、CMU、UC Berkeley、Harvard、Princeton、Cornell、Caltech 等
- **中国顶级大学/机构：** 清华大学、北京大学、浙大、上交大、复旦、中科院、MSRA 等
- **欧洲/其他：** Oxford、Cambridge、ETH Zurich、Mila、NUS、KAIST 等

---

*由 [clawBot DailyFindings](https://github.com/Jacob-biu/clawBot) 自动维护 | 最后更新：2026-11-25 04:49 UTC*
