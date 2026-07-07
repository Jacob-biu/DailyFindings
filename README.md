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

## 📅 今日论文 — 2026-07-07　　[→ 查看完整报告](daily/2026-07-07.md)

> 共筛选出 **18** 篇论文 | 更新于 2026-07-07 23:00 UTC

### 论文目录与概要

| # | 论文标题 | 核心概要 | 来源机构 | 第一作者 |
|---|---------|---------|---------|--------|
| 1 | [LLM-as-a-Verifier: A General-Purpose Verification Framework](http://arxiv.org/abs/2607.05391v1) | 扩展培训前、培训后和测试时间计算已成为提高LLM能力的核心范例。在这项工作中，我们确定验证，即确定解决方案正确性的能力，作为新的缩放轴。最后，我们证明LLM-as-a-Verifier可以为RL提供密… | TRI | Jacky Kwok |
| 2 | [Search Beyond What Can Be Taught: Evolving the Knowledge Bou…](http://arxiv.org/abs/2607.05382v1) | 可视化生成器擅长渲染，但他们自信地制造他们不知道的东西。用户请求是无限的、不断发展的，并且是长尾的：新角色、热门实体、截止后事件等。我们发布了完整的数据集、共同训练语料库和搜索语料库，作为工具增强、基… | TRI | Haozhe Wang |
| 3 | [CompactionRL: Reinforcement Learning with Context Compaction…](http://arxiv.org/abs/2607.05378v1) | 长视野代理LLM越来越受到有限上下文窗口的限制，因为在任务完成之前，扩展的交互轨迹可以超过最大上下文长度。上下文压缩通过总结以前的交互状态并在压缩上下文下继续推出，提供了一种自然的解决方案，但将压缩纳… | MIT | Yujiang Li |
| 4 | [Cortex: A Bidirectionally Aligned Embodied Agent Framework f…](http://arxiv.org/abs/2607.05377v1) | 虽然最近的视觉-语言-行动（ VLA ）模型显示出对多面手操纵政策的希望，但由于其马尔可夫性质（仅依赖于当前观察） ，它们难以处理长远任务。分层双系统方法可以解决这个问题，但是在高级规划语义和低级执行… | MIT、TRI | Jiaqi Peng |
| 5 | [GaP: A Graph-as-Policy Multi-Agent Self-Learning Harness For…](http://arxiv.org/abs/2607.05369v1) | 为了让机器人在商业和工业应用中可靠地工作，代理编码系统的最新进展能否将可解释的机器人编程与无模型策略的开放世界适应性相结合？我们专注于“变分自动化” （ VA ） ，这是一类在对象几何形状和姿势方面变… | TRI | Kaiyuan Chen |
| 6 | [SovereignPA-Bench: Evaluating User-Owned Personal Agents und…](http://arxiv.org/abs/2607.05363v1) | 个人代理正在成为持久的用户自有中介：他们记住偏好，过滤平台中介的信息，使用工具，并与服务进行谈判。现有基准评估工具使用、网页导航、桌面控制、个性化、推荐和不断变化的背景，但很少询问客服代表是否保留了用… | CAS、TRI | Dylan Zongmin Liu |
| 7 | [Multiplayer Interactive World Models with Representation Aut…](http://arxiv.org/abs/2607.05352v1) | 我们引入了第一个针对由复杂物理交互控制的高度动态环境的多人游戏世界模型。单人世界模型将其他智能体视为环境的一部分，而我们的条件是多个智能体的动作流，学习将场景中的变化归因于正确的玩家，并在其动作的任意… | NVIDIA、TRI | Anthony Hu |
| 8 | [OptiAgent: End-to-End Optimization Modeling via Multi-Agent …](http://arxiv.org/abs/2607.05346v1) | 我们提出了OptiAgent ，这是一个多智能体框架，给定运筹学问题的自然语言描述，能够输出求解器就绪的数学公式以及可执行代码。我们的架构优先考虑数学建模步骤，其中专用代理提取决策变量和约束等结构，从… | HIT | Adriana Laurindo Monteiro |
| 9 | [TREK: Distill to Explore, Reinforce to Refine](http://arxiv.org/abs/2607.05339v1) | 当当前策略已经对有用的推理轨迹进行采样时，组相对策略优化（ GRPO ）是有效的，但它停留在硬提示上，其正确的解决方案模式位于学生的策略支持之外。我们提出了TREK （ Teacher-Routed … | MIT、HIT | Yuanda Xu |
| 10 | [MetaSkill-Evolve: Recursive Self-Improvement of LLM Agents v…](http://arxiv.org/abs/2607.05297v1) | 最近的LLM代理处理越来越长远、开放式的任务，以及外部技能、提供给代理的可重复使用的程序知识，进一步扩展了这一能力。然而，固定的、手写的技能很少是最佳的，也不能适应客服代表遇到的多样化任务。由于所有五… | TRI | Zefeng Wang |
| 11 | [Untrusted Content Masking for Web Agents with Security Guara…](http://arxiv.org/abs/2607.05277v1) | 针对即时注入攻击提供安全保证的防御措施依赖于可信指令和不可信数据之间的严格隔离。在工具使用API等基于文本的环境中，这种分离是自然而然的：代理可以从接口定义中进行推理，而无需处理不受信任的内容。该代码… | TRI | Kristina Nikolić |
| 12 | [Unified Audio Intelligence Without Regressing on Text Intell…](http://arxiv.org/abs/2607.05196v1) | 音频智能涉及理解、推理和生成音频和语音。在这项工作中，我们介绍了Nemotron-Labs-Audex-30B-A3B （ Audex ） ，这是一种基于Nemotron-Cascade-2-30B-… | HIT、CAS | Zhifeng Kong |
| 13 | [When Claws Remember but Do Not Tell: Stealthy Memory Injecti…](http://arxiv.org/abs/2607.05189v1) | 持久的个人代理将长期记忆与对用户外部环境的访问相结合，实现个性化的前台协助和主动后台执行。这种集成还创建了一条新的妥协路径：不受信任的外部内容可以静默地写入永久内存，然后作为受信任状态重用。这些结果表… | HIT、CAS | Yechao Zhang |
| 14 | [Agent Data Injection Attacks are Realistic Threats to AI Age…](http://arxiv.org/abs/2607.05120v1) | AI代理代表用户提示行事，使用外部数据并根据代理上下文采取行动。之前对人工智能代理安全性的研究主要集中在间接提示注入（ IPI ）上。ADI暴露了代理安全性的关键差距，这意味着当前的AI代理没有采用基… | MIT、Mila | Woohyuk Choi |
| 15 | [Toward Trustworthy Large Language Model Agents in Healthcare](http://arxiv.org/abs/2607.05055v1) | 由于手动协调、分散的遗留系统和高昂的管理开销，医疗保健预约安排仍然是一个持续存在的运营瓶颈。这些低效率限制了提供者的可用性，并降低了患者获得医疗服务的机会。源代码和系统实现可在https://gith… | CAS、TRI | Hadi Hasan |
| 16 | [Your Agent's Memories Are Not Its Own: Forged Reasoning Atta…](http://arxiv.org/abs/2607.05029v1) | 持久记忆使大型语言模型（ LLM ）代理能够存储事实知识、先前决策、推理历史、工具使用信息和上下文。虽然这改善了代理的功能和跨任务的连续性，但它也引入了一个新的攻击面：代理自己的推理历史记录。我们的工… | TRI | Neeraj Karamchandani |
| 17 | [TACTIC-KG: Toward Small Agent Teams for Cyber Threat Intelli…](http://arxiv.org/abs/2607.05001v1) | 网络威胁情报（ CTI ）报告主要是非结构化的、异构的和嘈杂的，这限制了它们对自动化分析和推理的直接可用性。网络安全知识图（ CSKG ）提供了对抗实体、行动和关系的结构化表示，但从自由文本CTI构建… | MIT、Mila | Mouhamed Amine Bouchiha |
| 18 | [Multi-Robot Open Adaptive Teaming Across Unseen Environments…](http://arxiv.org/abs/2607.04972v1) | 在现实世界中部署机器人团队需要同时适应看不见的环境、未知的合作伙伴和不同的团队规模，但现有的方法通常在固定队友的封闭世界中孤立地解决这些挑战。我们将此形式化为开放式自适应多机器人分组，并提出了一种超图… | HIT | Yang Li |

### 论文详情

<details>
<summary><b>1. LLM-as-a-Verifier: A General-Purpose Verification Framework</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Jacky Kwok、Shulu Li、Pranav Atreya、Yuejiang Liu、Yixing Jiang 等（共 9 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-07-06T17:59:35Z |
| **关键词** | `Agentic` · `Reasoning` · `Benchmark` · `Evaluation` · `Robotics` |
| **原文链接** | [http://arxiv.org/abs/2607.05391v1](http://arxiv.org/abs/2607.05391v1) |

**📝 摘要概括：**

> 扩展培训前、培训后和测试时间计算已成为提高LLM能力的核心范例。在这项工作中，我们确定验证，即确定解决方案正确性的能力，作为新的缩放轴。最后，我们证明LLM-as-a-Verifier可以为RL提供密集的反馈，提高SAC和GRPO在机器人和数学推理基准上的样本效率。

</details>

<details>
<summary><b>2. Search Beyond What Can Be Taught: Evolving the Knowledge Boundary in Agentic Visual Generation</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Haozhe Wang、Weijia Feng、Jinpeng Yu、Che Liu、Ping Nie 等（共 11 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-07-06T17:56:12Z |
| **关键词** | `Agentic` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2607.05382v1](http://arxiv.org/abs/2607.05382v1) |

**📝 摘要概括：**

> 可视化生成器擅长渲染，但他们自信地制造他们不知道的东西。用户请求是无限的、不断发展的，并且是长尾的：新角色、热门实体、截止后事件等。我们发布了完整的数据集、共同训练语料库和搜索语料库，作为工具增强、基于世界知识的视觉生成的可重播线束。

</details>

<details>
<summary><b>3. CompactionRL: Reinforcement Learning with Context Compaction for Long-Horizon Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Yujiang Li、Zhenyu Hou、Yi Jing、Jie Tang、Yuxiao Dong |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT |
| **发布时间** | 2026-07-06T17:55:12Z |
| **关键词** | `LLM Agent` · `Agentic` · `Reinforcement Learning` |
| **原文链接** | [http://arxiv.org/abs/2607.05378v1](http://arxiv.org/abs/2607.05378v1) |

**📝 摘要概括：**

> 长视野代理LLM越来越受到有限上下文窗口的限制，因为在任务完成之前，扩展的交互轨迹可以超过最大上下文长度。上下文压缩通过总结以前的交互状态并在压缩上下文下继续推出，提供了一种自然的解决方案，但将压缩纳入强化学习仍未得到充分探索。因此， CompactionRL部署在RL pipeli中…

</details>

<details>
<summary><b>4. Cortex: A Bidirectionally Aligned Embodied Agent Framework for Long-horizon Manipulation</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Jiaqi Peng、Xiqian Yu、Delin Feng、Yuqiang Yang、Wenzhe Cai 等（共 13 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-07-06T17:55:05Z |
| **关键词** | `Planning` · `Evaluation` · `Fine-tuning` · `Simulation` · `Embodied AI` |
| **原文链接** | [http://arxiv.org/abs/2607.05377v1](http://arxiv.org/abs/2607.05377v1) |

**📝 摘要概括：**

> 虽然最近的视觉-语言-行动（ VLA ）模型显示出对多面手操纵政策的希望，但由于其马尔可夫性质（仅依赖于当前观察） ，它们难以处理长远任务。分层双系统方法可以解决这个问题，但是在高级规划语义和低级执行运动学之间存在差距。值得注意的是， Cortex的多面手VLM能够实现看不见的现实世界长时间零拍摄完成……

</details>

<details>
<summary><b>5. GaP: A Graph-as-Policy Multi-Agent Self-Learning Harness For Variational Automation Tasks</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Kaiyuan Chen、Shuangyu Xie、Letian Fu、Justin Yu、William Pacini 等（共 24 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-07-06T17:47:31Z |
| **关键词** | `Multi-Agent` · `Agentic` · `Planning` · `Benchmark` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2607.05369v1](http://arxiv.org/abs/2607.05369v1) |

**📝 摘要概括：**

> 为了让机器人在商业和工业应用中可靠地工作，代理编码系统的最新进展能否将可解释的机器人编程与无模型策略的开放世界适应性相结合？我们专注于“变分自动化” （ VA ） ，这是一类在对象几何形状和姿势方面变化比固定自动化更大的任务。详细信息、代码和数据可在线找到： https://graph-robots.github.io/gap

</details>

<details>
<summary><b>6. SovereignPA-Bench: Evaluating User-Owned Personal Agents under Evolving Intent, Platform Mediation, and Consent Constraints</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Dylan Zongmin Liu |
| **所属机构** | （详见原文） |
| **顶级机构标签** | CAS、TRI |
| **发布时间** | 2026-07-06T17:39:05Z |
| **关键词** | `Benchmark` · `Evaluation` · `Memory` |
| **原文链接** | [http://arxiv.org/abs/2607.05363v1](http://arxiv.org/abs/2607.05363v1) |

**📝 摘要概括：**

> 个人代理正在成为持久的用户自有中介：他们记住偏好，过滤平台中介的信息，使用工具，并与服务进行谈判。现有基准评估工具使用、网页导航、桌面控制、个性化、推荐和不断变化的背景，但很少询问客服代表是否保留了用户主权：在尊重隐私、同意、证据、用户利益的同时推进用户的当前利益……

</details>

<details>
<summary><b>7. Multiplayer Interactive World Models with Representation Autoencoders</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Anthony Hu、Václav Volhejn、Adrien Ramanana Rahary、Chris Mulder、Aditya Makkar 等（共 27 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | NVIDIA、TRI |
| **发布时间** | 2026-07-06T17:31:52Z |
| **关键词** | `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2607.05352v1](http://arxiv.org/abs/2607.05352v1) |

**📝 摘要概括：**

> 我们引入了第一个针对由复杂物理交互控制的高度动态环境的多人游戏世界模型。单人世界模型将其他智能体视为环境的一部分，而我们的条件是多个智能体的动作流，学习将场景中的变化归因于正确的玩家，并在其动作的任意组合下保持连贯性。为了支持对多人游戏世界的持续研究……

</details>

<details>
<summary><b>8. OptiAgent: End-to-End Optimization Modeling via Multi-Agent Iterative Refinement</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Adriana Laurindo Monteiro、Nayse Fagundes、Gabriel Mattos Langeloh、Gustavo de Oliveira Kanno、Priscila Louise Aguirre 等（共 7 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | HIT |
| **发布时间** | 2026-07-06T17:27:16Z |
| **关键词** | `Multi-Agent` · `Reasoning` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2607.05346v1](http://arxiv.org/abs/2607.05346v1) |

**📝 摘要概括：**

> 我们提出了OptiAgent ，这是一个多智能体框架，给定运筹学问题的自然语言描述，能够输出求解器就绪的数学公式以及可执行代码。我们的架构优先考虑数学建模步骤，其中专用代理提取决策变量和约束等结构，从而实现迭代自校正。我们的框架在3……上实现了最先进的性能

</details>

<details>
<summary><b>9. TREK: Distill to Explore, Reinforce to Refine</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Yuanda Xu、Zhengze Zhou、Kayhan Behdin、Jelena Markovic-Voronov、Hejian Sang 等（共 13 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、HIT |
| **发布时间** | 2026-07-06T17:21:16Z |
| **关键词** | `Agentic` · `Reasoning` |
| **原文链接** | [http://arxiv.org/abs/2607.05339v1](http://arxiv.org/abs/2607.05339v1) |

**📝 摘要概括：**

> 当当前策略已经对有用的推理轨迹进行采样时，组相对策略优化（ GRPO ）是有效的，但它停留在硬提示上，其正确的解决方案模式位于学生的策略支持之外。我们提出了TREK （ Teacher-Routed Exploration via Forward KL ） ，这是一种简单的分阶段程序，使用蒸馏不是为了模仿，而是为了勘探支持扩展。在特工任务中， TREK提高了ALFWorld的成功率……

</details>

<details>
<summary><b>10. MetaSkill-Evolve: Recursive Self-Improvement of LLM Agents via Two-Timescale Meta-Skill Evolution</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Zefeng Wang、Minxi Yan、Jinhe Bi、Sikuan Yan、Volker Tresp 等（共 6 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-07-06T16:40:23Z |
| **关键词** | `LLM Agent` · `Agentic` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2607.05297v1](http://arxiv.org/abs/2607.05297v1) |

**📝 摘要概括：**

> 最近的LLM代理处理越来越长远、开放式的任务，以及外部技能、提供给代理的可重复使用的程序知识，进一步扩展了这一能力。然而，固定的、手写的技能很少是最佳的，也不能适应客服代表遇到的多样化任务。由于所有五个管道代理共享单个冻结骨干， MetaSkill-Evolve的表现优于无技能、静态技能和单级进化基线……

</details>

<details>
<summary><b>11. Untrusted Content Masking for Web Agents with Security Guarantees</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Kristina Nikolić、Egor Zverev、Javier Rando、Matthew Jagielski、Edoardo Debenedetti 等（共 6 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-07-06T16:22:37Z |
| **关键词** | `RAG` · `Web Agent` |
| **原文链接** | [http://arxiv.org/abs/2607.05277v1](http://arxiv.org/abs/2607.05277v1) |

**📝 摘要概括：**

> 针对即时注入攻击提供安全保证的防御措施依赖于可信指令和不可信数据之间的严格隔离。在工具使用API等基于文本的环境中，这种分离是自然而然的：代理可以从接口定义中进行推理，而无需处理不受信任的内容。该代码是公开的。

</details>

<details>
<summary><b>12. Unified Audio Intelligence Without Regressing on Text Intelligence</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Zhifeng Kong、Sang-gil Lee、Jaehyeon Kim、Boxin Wang、Zihan Liu 等（共 20 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | HIT、CAS |
| **发布时间** | 2026-07-06T15:11:57Z |
| **关键词** | `Agentic` · `Reasoning` |
| **原文链接** | [http://arxiv.org/abs/2607.05196v1](http://arxiv.org/abs/2607.05196v1) |

**📝 摘要概括：**

> 音频智能涉及理解、推理和生成音频和语音。在这项工作中，我们介绍了Nemotron-Labs-Audex-30B-A3B （ Audex ） ，这是一种基于Nemotron-Cascade-2-30B-A3B的统一音频文本LLM ，这是一种强大的纯文本教育部LLM。我们发布模型检查点以促进开放研究。

</details>

<details>
<summary><b>13. When Claws Remember but Do Not Tell: Stealthy Memory Injection in Persistent Personal Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Yechao Zhang、Shiqian Zhao、Jiawen Zhang、Jie Zhang、Gelei Deng 等（共 8 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | HIT、CAS |
| **发布时间** | 2026-07-06T15:08:58Z |
| **关键词** | `Reinforcement Learning` · `Benchmark` · `Evaluation` · `Fine-tuning` · `Memory` |
| **原文链接** | [http://arxiv.org/abs/2607.05189v1](http://arxiv.org/abs/2607.05189v1) |

**📝 摘要概括：**

> 持久的个人代理将长期记忆与对用户外部环境的访问相结合，实现个性化的前台协助和主动后台执行。这种集成还创建了一条新的妥协路径：不受信任的外部内容可以静默地写入永久内存，然后作为受信任状态重用。这些结果表明，持久性记忆可以将普通的外部处理转化为实际的途径……

</details>

<details>
<summary><b>14. Agent Data Injection Attacks are Realistic Threats to AI Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Woohyuk Choi、Juhee Kim、Taehyun Kang、Jihyeon Jeong、Luyi Xing 等（共 6 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、Mila |
| **发布时间** | 2026-07-06T14:07:49Z |
| **关键词** | `AI Agent` · `Web Agent` |
| **原文链接** | [http://arxiv.org/abs/2607.05120v1](http://arxiv.org/abs/2607.05120v1) |

**📝 摘要概括：**

> AI代理代表用户提示行事，使用外部数据并根据代理上下文采取行动。之前对人工智能代理安全性的研究主要集中在间接提示注入（ IPI ）上。ADI暴露了代理安全性的关键差距，这意味着当前的AI代理没有采用基本的安全原则：当前的代理不会将受信任的数据与不受信任的数据隔离开来。

</details>

<details>
<summary><b>15. Toward Trustworthy Large Language Model Agents in Healthcare</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Hadi Hasan、Safaa Salman、Adam Tai Abou Dargham、Ammar Mohanna、Ali Chehab |
| **所属机构** | （详见原文） |
| **顶级机构标签** | CAS、TRI |
| **发布时间** | 2026-07-06T13:29:07Z |
| **关键词** | `RAG` · `Retrieval` · `Benchmark` · `Evaluation` · `Workflow` |
| **原文链接** | [http://arxiv.org/abs/2607.05055v1](http://arxiv.org/abs/2607.05055v1) |

**📝 摘要概括：**

> 由于手动协调、分散的遗留系统和高昂的管理开销，医疗保健预约安排仍然是一个持续存在的运营瓶颈。这些低效率限制了提供者的可用性，并降低了患者获得医疗服务的机会。源代码和系统实现可在https://github.com/Hadi-Hsn/CareConnect上公开获得。

</details>

<details>
<summary><b>16. Your Agent's Memories Are Not Its Own: Forged Reasoning Attacks on LLM Agent Memory and Defenses</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Neeraj Karamchandani、Piyush Nagasubramaniam、Sencun Zhu、Dinghao Wu |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-07-06T13:10:13Z |
| **关键词** | `LLM Agent` · `Reasoning` · `Evaluation` · `Memory` |
| **原文链接** | [http://arxiv.org/abs/2607.05029v1](http://arxiv.org/abs/2607.05029v1) |

**📝 摘要概括：**

> 持久记忆使大型语言模型（ LLM ）代理能够存储事实知识、先前决策、推理历史、工具使用信息和上下文。虽然这改善了代理的功能和跨任务的连续性，但它也引入了一个新的攻击面：代理自己的推理历史记录。我们的工作表明，不仅需要保护代理的检索内容，还需要保护其推理历史的完整性……

</details>

<details>
<summary><b>17. TACTIC-KG: Toward Small Agent Teams for Cyber Threat Intelligence Knowledge Graph Construction</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Mouhamed Amine Bouchiha、Gregory Blanc |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、Mila |
| **发布时间** | 2026-07-06T12:41:11Z |
| **关键词** | `LLM Agent` · `Agentic` · `Reasoning` |
| **原文链接** | [http://arxiv.org/abs/2607.05001v1](http://arxiv.org/abs/2607.05001v1) |

**📝 摘要概括：**

> 网络威胁情报（ CTI ）报告主要是非结构化的、异构的和嘈杂的，这限制了它们对自动化分析和推理的直接可用性。网络安全知识图（ CSKG ）提供了对抗实体、行动和关系的结构化表示，但从自由文本CTI构建此类图形仍然是一个挑战。对人工注释CTI报告的实验表明，客服代表的专业化一致……

</details>

<details>
<summary><b>18. Multi-Robot Open Adaptive Teaming Across Unseen Environments, Partners, and Scales</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Yang Li、Feng Xue、Fan Mo、Yunhao Liu、Jianhong Wang 等（共 9 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | HIT |
| **发布时间** | 2026-07-06T12:02:02Z |
| **关键词** | `Fine-tuning` |
| **原文链接** | [http://arxiv.org/abs/2607.04972v1](http://arxiv.org/abs/2607.04972v1) |

**📝 摘要概括：**

> 在现实世界中部署机器人团队需要同时适应看不见的环境、未知的合作伙伴和不同的团队规模，但现有的方法通常在固定队友的封闭世界中孤立地解决这些挑战。我们将此形式化为开放式自适应多机器人分组，并提出了一种超图形形式的游戏配方，该配方捕捉了团队级合作关系，超越了成对互动，证明……

</details>

## 🗄️ 历史归档

| 日期 | 论文数 | 报告链接 |
|------|--------|----------|
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
| 2026-06-09 | 20 篇 | [2026-06-09.md](daily/2026-06-09.md) |
| 2026-06-08 | 0 篇 | [2026-06-08.md](daily/2026-06-08.md) |

## 🏛️ 顶级机构覆盖范围

覆盖超过 **70 个**顶级 AI 机构，包括：

- **科技公司：** Microsoft、Google DeepMind、OpenAI、Anthropic、Meta AI、NVIDIA、Baidu、Alibaba、ByteDance 等
- **北美顶级大学：** MIT、Stanford、CMU、UC Berkeley、Harvard、Princeton、Cornell、Caltech 等
- **中国顶级大学/机构：** 清华大学、北京大学、浙大、上交大、复旦、中科院、MSRA 等
- **欧洲/其他：** Oxford、Cambridge、ETH Zurich、Mila、NUS、KAIST 等

---

*由 [clawBot DailyFindings](https://github.com/Jacob-biu/clawBot) 自动维护 | 最后更新：2026-07-07 23:00 UTC*
