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

## 📅 今日论文 — 2026-06-30　　[→ 查看完整报告](daily/2026-06-30.md)

> 共筛选出 **20** 篇论文 | 更新于 2026-06-30 23:11 UTC

### 论文目录与概要

| # | 论文标题 | 核心概要 | 来源机构 | 第一作者 |
|---|---------|---------|---------|--------|
| 1 | [Self-Evolving World Models for LLM Agent Planning](http://arxiv.org/abs/2606.30639v1) | 世界模型提供了一种有原则的方式，使长期法学硕士代理具有远见：在执行之前预测行动后果。然而，不可靠的预见性可能会被忽视、滥用，甚至降低下游决策。广泛的实验表明， WorldEvolver在三个主干上实现… | TRI | Xuan Zhang |
| 2 | [MESA: Prioritizing Vulnerable Communication Channels for Sec…](http://arxiv.org/abs/2606.30602v1) | 多代理系统（ MAS ）越来越多地用于自动化复杂的分布式工作流程。然而，他们的代理间通信渠道引入了新的攻击面，这些攻击面仍然知之甚少，难以防御。总体而言，我们的研究结果表明， MAS中的边缘级别风险通… | MIT、TRI | Kunyang Li |
| 3 | [Attractor States Emerge in Multi-Turn LLM Conversations](http://arxiv.org/abs/2606.30571v1) | 大型语言模型（ LLM ）越来越多地用于开放式多智能体环境中，但对模型-模型交互的长期动态仍知之甚少。我们研究开放式法学硕士讨论是否表现出类似吸引子的行为，即总体而言，我们的分析揭示了开放式多智能体交… | TRI | Ting-Wen Ko |
| 4 | [Forensic Trajectory Signatures for Agent Memory Poisoning De…](http://arxiv.org/abs/2606.30566v1) | 我们在持续记忆中毒的情况下发现LLM代理的行为不变性：在通过可观察到的内存工具调用来检索路由信息的架构中，成功的攻击需要在email_send_email之前调用memory_recall_fact … | HIT、TRI | Jun Wen Leong |
| 5 | [TraceLab: Characterizing Coding Agent Workloads for LLM Serv…](http://arxiv.org/abs/2606.30560v1) | 编码代理正在迅速成为代理LLM的主要应用，但高效地为他们提供服务仍然具有挑战性。这一挑战的进展需要了解真实的工作负载模式，但此类分析所需的数据在很大程度上是缺失的。我们在https://github.… | HIT | Kan Zhu |
| 6 | [Linguistic Firewall: Geometry as Defense in Multi-Agent Syst…](http://arxiv.org/abs/2606.30555v1) | 大型语言模型(LLM)的快速集成推动了多代理系统(MAS)的演变，专业代理协同执行复杂的工作流程。这些环境中的有效编排需要强大的路由机制，以有效地将任务分配给最合适的代理。针对自适应嵌入攻击， ANT… | HIT | Dvir Alsheich |
| 7 | [Latent Actions from Factorized Transition Effects under Agen…](http://arxiv.org/abs/2606.30544v1) | 潜在动作模型（ LAM ）从观察转换中学习类似动作的代理。然而，在多对象或干扰源丰富的场景中，这些视觉效果将智能体动作与干扰源、摄像机动态和背景变化混合在一起，使得潜在的动作源在没有监督的情况下变得模… | MIT | Heejeong Nam |
| 8 | [Staged Hybridisation for Visual Quantum Reinforcement Learni…](http://arxiv.org/abs/2606.30520v1) | 视觉环境是量子强化学习（ QRL ）的苛刻环境：高维观测、不稳定的RL优化和约束变分量子电路（ VQC ）很难联合训练。本文研究知识蒸馏（ KD ）作为视觉QRL的分阶段杂交策略。总体而言，分阶段KD… | NTU、TRI | Javier Lazaro |
| 9 | [COHORT: Collaborative Orchestration for Hardening via Offens…](http://arxiv.org/abs/2606.30479v1) | 在企业网络中缓解观察到的对手通常需要数周的专家工作：分析师为该对手量身定制缓解措施，在不破坏生产的情况下对其进行验证，并验证其是否中断了特定的攻击。该程序依赖于专家的判断，不能针对生产网络安全地执行。… | MIT | Chen Frydman |
| 10 | [Field Order Should Not Matter: Permutation-Invariant Embeddi…](http://arxiv.org/abs/2606.30473v1) | 我们研究对结构化元数据目录的检索，其中每个记录都是一个小架构，其字段回答不同类型的查询。使用文本编码器嵌入记录首先将其字段序列化为字符串，从而强制选择字段顺序。我们发布了基准、管道、模型和可重用的PI… | TRI | Aivin V. Solatorio |
| 11 | [Collective cooperation without individual fidelity in LLM ag…](http://arxiv.org/abs/2606.30454v1) | 大型语言模型（ LLM ）越来越多地被用作模拟社会系统的代理，但目前尚不清楚它们的行为何时可以被解释为人类决策的忠实代理。在这里，我们根据一个直接的经验基准来测试法学硕士代理：与人类参与者进行的大规模… | TRI | Henrique Ferraz de Arruda |
| 12 | [Internal-State Probes Read the Situation, Not the Action: Th…](http://arxiv.org/abs/2606.30449v1) | 如果代理系统在生成这些操作之前识别出有害文本或工具操作，则对模型内部的探测可以帮助监控代理系统。我们询问内部读数是否支持这种更强大的行动前声明，而不仅仅是描述提示、施工对比或当前轨迹。代码发布于htt… | CAS、TRI | Max Fomin |
| 13 | [Translating Natural Language to Strategic Temporal Specifica…](http://arxiv.org/abs/2606.30441v1) | 系统要求的严格形式化是多Agent系统（ MAS ）验证的基本先决条件。然而，编写正确的正式规范是一项众所周知的容易出错、耗时和专业知识密集型任务。为了评估生成的规范的实际适用性，我们将我们的工具嵌入… | NTU | Marco Aruta |
| 14 | [Whose Side Is Your Agent On? Multi-Party Principal Loyalty i…](http://arxiv.org/abs/2606.30383v1) | 一个快速增长的LLM代理类别是多方：代理代表委托人（向委托人汇报、发送跟进和接收结果） ，同时还与利益可能存在分歧的对手方在单独的渠道中交谈（与供应商谈判、筛选入站请求或在员工之间进行调解）。在这里，… | TRI | Bojie Li |
| 15 | [BayesEvolve: Explicit Belief States for Autonomous Scientifi…](http://arxiv.org/abs/2606.30335v1) | 自主科学发现系统越来越多地使用大型语言模型（ LLM ）来提出新的假设，但许多此类系统主要取决于实验记忆：高分候选人档案或最近试验的启发式总结。我们认为，发现代理应该对假设质量保持明确的、具有不确定性… | NUS、TRI | Xuening Wu |
| 16 | [Always-OnAgents:A Survey of Persistent Memory, State, and Go…](http://arxiv.org/abs/2606.30306v1) | Always-on agent是其未来行为取决于早期交互中累积的持久状态的系统。我们将它们视为持久状态系统：操作系统包括可检索的记忆，还包括任务分类账、权限、凭据、承诺、出处和审计记录、共享状态、触发… | MIT、TRI | Tianyu Ding |
| 17 | [ManimAgent: Self-Evolving Multimodal Agents for Visual Educa…](http://arxiv.org/abs/2606.30296v1) | 多轮反思允许基于大型语言模型构建的代理从单个任务中的失败中恢复，但每个任务仍然是一个孤立的事件：在一个任务的多轮反思中学到的经验教训会在下一个任务开始之前被丢弃。我们在代码生成任务上研究了这一差距：从… | TRI | Wenjia Jiang |
| 18 | [Rehearsed Multi-Agent Live Product Demonstrations with Real-…](http://arxiv.org/abs/2606.30294v1) | 实时产品演示是软件组织中反复出现的高成本活动：人工演示者必须选择功能，在运行的应用程序上调度相应的交互，连贯地叙述它们，并实时回答问题。现有的自动化仅解决片段--通用浏览器代理针对指令条件的任务完成，… | HIT、CAS | Rahul Khedar |
| 19 | [Towards Continual Motion-Language Agents: LoRA Variants for …](http://arxiv.org/abs/2606.30266v1) | 运动语言代理必须具备双向能力，既能理解人类运动（运动到文本， M2T ） ，又能从自然语言（文本到运动， T2M ）生成运动。虽然基础模型在静态环境中取得了强大的性能，但在动态环境中运行的自主智能体必… | MIT、HIT | Bertram Taetz |
| 20 | [Clarus: Coordinating Autonomous Research Agents toward Web-S…](http://arxiv.org/abs/2606.30246v1) | 现有的自主研究代理可以支持部分研究过程，但大多数系统仍然将研究视为孤立的助理任务或封闭的工作流程。因此，自主科学需要一个协调项目、代理、数字和物理资源的协作基础设施。Clarus现已在clarus.h… | CAS、TRI | Zihan Guo |

### 论文详情

<details>
<summary><b>1. Self-Evolving World Models for LLM Agent Planning</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Xuan Zhang、Wenxuan Zhang、See-Kiong Ng、Yang Deng |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-06-29T17:58:43Z |
| **关键词** | `LLM Agent` · `Reasoning` · `Planning` · `Retrieval` · `Simulation` |
| **原文链接** | [http://arxiv.org/abs/2606.30639v1](http://arxiv.org/abs/2606.30639v1) |

**📝 摘要概括：**

> 世界模型提供了一种有原则的方式，使长期法学硕士代理具有远见：在执行之前预测行动后果。然而，不可靠的预见性可能会被忽视、滥用，甚至降低下游决策。广泛的实验表明， WorldEvolver在三个主干上实现了最高的预测精度，并在下游代理成功率方面领先于其他世界模型基线，这表明测试时间Mem…

</details>

<details>
<summary><b>2. MESA: Prioritizing Vulnerable Communication Channels for Securing Multi-Agent Systems</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Kunyang Li、Kyle Domico、Jonathan Gregory、Patrick McDaniel |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-06-29T17:40:45Z |
| **关键词** | `Multi-Agent` · `Workflow` |
| **原文链接** | [http://arxiv.org/abs/2606.30602v1](http://arxiv.org/abs/2606.30602v1) |

**📝 摘要概括：**

> 多代理系统（ MAS ）越来越多地用于自动化复杂的分布式工作流程。然而，他们的代理间通信渠道引入了新的攻击面，这些攻击面仍然知之甚少，难以防御。总体而言，我们的研究结果表明， MAS中的边缘级别风险通常是集中且可预测的，允许主动加强多智能体基础设施。

</details>

<details>
<summary><b>3. Attractor States Emerge in Multi-Turn LLM Conversations</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Ting-Wen Ko、Jonas Geiping |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-06-29T17:14:29Z |
| **关键词** | `Multi-Agent` · `Agentic` |
| **原文链接** | [http://arxiv.org/abs/2606.30571v1](http://arxiv.org/abs/2606.30571v1) |

**📝 摘要概括：**

> 大型语言模型（ LLM ）越来越多地用于开放式多智能体环境中，但对模型-模型交互的长期动态仍知之甚少。我们研究开放式法学硕士讨论是否表现出类似吸引子的行为，即总体而言，我们的分析揭示了开放式多智能体交互的复杂行为，我们希望这有助于设计，预测和监测自主智能体系统。

</details>

<details>
<summary><b>4. Forensic Trajectory Signatures for Agent Memory Poisoning Detection</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Jun Wen Leong |
| **所属机构** | （详见原文） |
| **顶级机构标签** | HIT、TRI |
| **发布时间** | 2026-06-29T17:09:03Z |
| **关键词** | `LLM Agent` · `Retrieval` · `Memory` |
| **原文链接** | [http://arxiv.org/abs/2606.30566v1](http://arxiv.org/abs/2606.30566v1) |

**📝 摘要概括：**

> 我们在持续记忆中毒的情况下发现LLM代理的行为不变性：在通过可观察到的内存工具调用来检索路由信息的架构中，成功的攻击需要在email_send_email之前调用memory_recall_fact ，这是一种非渗透会话很少显示的转换。在评估的架构下，这种不变量遵循攻击的信息检索依赖关系，而不是……

</details>

<details>
<summary><b>5. TraceLab: Characterizing Coding Agent Workloads for LLM Serving</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Kan Zhu、Mathew Jacob、Chenxi Ma、Yi Pan、Stephanie Wang 等（共 7 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | HIT |
| **发布时间** | 2026-06-29T16:59:05Z |
| **关键词** | `Agentic` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2606.30560v1](http://arxiv.org/abs/2606.30560v1) |

**📝 摘要概括：**

> 编码代理正在迅速成为代理LLM的主要应用，但高效地为他们提供服务仍然具有挑战性。这一挑战的进展需要了解真实的工作负载模式，但此类分析所需的数据在很大程度上是缺失的。我们在https://github.com/uw-syfi/TraceLab.git上发布数据集、跟踪收集管道和分析代码；项目网站为https://tracelab.cs.washington.edu。

</details>

<details>
<summary><b>6. Linguistic Firewall: Geometry as Defense in Multi-Agent Systems Routing</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Dvir Alsheich、Adar Peleg、Ben Hagag、Rom Himelstein、Amit Levi 等（共 6 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | HIT |
| **发布时间** | 2026-06-29T16:51:06Z |
| **关键词** | `Multi-Agent` · `Evaluation` · `Workflow` |
| **原文链接** | [http://arxiv.org/abs/2606.30555v1](http://arxiv.org/abs/2606.30555v1) |

**📝 摘要概括：**

> 大型语言模型(LLM)的快速集成推动了多代理系统(MAS)的演变，专业代理协同执行复杂的工作流程。这些环境中的有效编排需要强大的路由机制，以有效地将任务分配给最合适的代理。针对自适应嵌入攻击， ANTAP实现了远低于基于嵌入的基线的ASR ，降低了20 ％ ，同时......

</details>

<details>
<summary><b>7. Latent Actions from Factorized Transition Effects under Agent Ambiguity</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Heejeong Nam、Chandradithya S Jonnalagadda、Harshit Aggarwal、Eric Xu、Randall Balestriero |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT |
| **发布时间** | 2026-06-29T16:45:04Z |
| **关键词** | — |
| **原文链接** | [http://arxiv.org/abs/2606.30544v1](http://arxiv.org/abs/2606.30544v1) |

**📝 摘要概括：**

> 潜在动作模型（ LAM ）从观察转换中学习类似动作的代理。然而，在多对象或干扰源丰富的场景中，这些视觉效果将智能体动作与干扰源、摄像机动态和背景变化混合在一起，使得潜在的动作源在没有监督的情况下变得模糊不清。此外，在复杂的过渡模糊性下，下游政策学习结果与基线相匹配或优于基线。

</details>

<details>
<summary><b>8. Staged Hybridisation for Visual Quantum Reinforcement Learning via Knowledge Distillation</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Javier Lazaro、Juan-Ignacio Vazquez、Pablo Garcia-Bringas |
| **所属机构** | （详见原文） |
| **顶级机构标签** | NTU、TRI |
| **发布时间** | 2026-06-29T16:28:57Z |
| **关键词** | `Reinforcement Learning` · `RAG` · `Simulation` |
| **原文链接** | [http://arxiv.org/abs/2606.30520v1](http://arxiv.org/abs/2606.30520v1) |

**📝 摘要概括：**

> 视觉环境是量子强化学习（ QRL ）的苛刻环境：高维观测、不稳定的RL优化和约束变分量子电路（ VQC ）很难联合训练。本文研究知识蒸馏（ KD ）作为视觉QRL的分阶段杂交策略。总体而言，分阶段KD将视觉QRL重新构建为紧凑型头部学习问题，为小量训练开辟了一条实用路线……

</details>

<details>
<summary><b>9. COHORT: Collaborative Orchestration for Hardening via Offensive Replay on Emulated Topologies</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Chen Frydman、Aviram Zilberman、Rubin Krief、Abed Showgan、Andres Murillo 等（共 9 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT |
| **发布时间** | 2026-06-29T15:39:05Z |
| **关键词** | `Multi-Agent` · `Evaluation` · `Simulation` · `Workflow` |
| **原文链接** | [http://arxiv.org/abs/2606.30479v1](http://arxiv.org/abs/2606.30479v1) |

**📝 摘要概括：**

> 在企业网络中缓解观察到的对手通常需要数周的专家工作：分析师为该对手量身定制缓解措施，在不破坏生产的情况下对其进行验证，并验证其是否中断了特定的攻击。该程序依赖于专家的判断，不能针对生产网络安全地执行。通过我们发布的工件，可以获得演示视频。

</details>

<details>
<summary><b>10. Field Order Should Not Matter: Permutation-Invariant Embedding Model Fine-Tuning for Structured Metadata Retrieval</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Aivin V. Solatorio、Olivier Dupriez、Rafael Macalaba |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-06-29T15:33:04Z |
| **关键词** | `Retrieval` · `Benchmark` · `Evaluation` · `Fine-tuning` |
| **原文链接** | [http://arxiv.org/abs/2606.30473v1](http://arxiv.org/abs/2606.30473v1) |

**📝 摘要概括：**

> 我们研究对结构化元数据目录的检索，其中每个记录都是一个小架构，其字段回答不同类型的查询。使用文本编码器嵌入记录首先将其字段序列化为字符串，从而强制选择字段顺序。我们发布了基准、管道、模型和可重用的PI-FT框架。

</details>

<details>
<summary><b>11. Collective cooperation without individual fidelity in LLM agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Henrique Ferraz de Arruda、Carlos Gracia Lázaro、Alberto Aleta、Yamir Moreno |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-06-29T15:22:21Z |
| **关键词** | `LLM Agent` · `Benchmark` · `Simulation` |
| **原文链接** | [http://arxiv.org/abs/2606.30454v1](http://arxiv.org/abs/2606.30454v1) |

**📝 摘要概括：**

> 大型语言模型（ LLM ）越来越多地被用作模拟社会系统的代理，但目前尚不清楚它们的行为何时可以被解释为人类决策的忠实代理。在这里，我们根据一个直接的经验基准来测试法学硕士代理：与人类参与者进行的大规模网络化囚犯困境实验。他们建议，将LLM代理人验证为人类代理人需要跨聚合动态进行比较……

</details>

<details>
<summary><b>12. Internal-State Probes Read the Situation, Not the Action: Three Negative Results for Pre-Action Misalignment Monitoring</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Max Fomin、Elad David、Amit LeVi |
| **所属机构** | （详见原文） |
| **顶级机构标签** | CAS、TRI |
| **发布时间** | 2026-06-29T15:18:36Z |
| **关键词** | `Agentic` |
| **原文链接** | [http://arxiv.org/abs/2606.30449v1](http://arxiv.org/abs/2606.30449v1) |

**📝 摘要概括：**

> 如果代理系统在生成这些操作之前识别出有害文本或工具操作，则对模型内部的探测可以帮助监控代理系统。我们询问内部读数是否支持这种更强大的行动前声明，而不仅仅是描述提示、施工对比或当前轨迹。代码发布于https://github.com/maxf-zn/misalignment_monitoring

</details>

<details>
<summary><b>13. Translating Natural Language to Strategic Temporal Specifications via LLMs</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Marco Aruta、Francesco Improta、Vadim Malvone、Aniello Murano、Vladana Perlic |
| **所属机构** | （详见原文） |
| **顶级机构标签** | NTU |
| **发布时间** | 2026-06-29T15:15:40Z |
| **关键词** | `Multi-Agent` · `Fine-tuning` |
| **原文链接** | [http://arxiv.org/abs/2606.30441v1](http://arxiv.org/abs/2606.30441v1) |

**📝 摘要概括：**

> 系统要求的严格形式化是多Agent系统（ MAS ）验证的基本先决条件。然而，编写正确的正式规范是一项众所周知的容易出错、耗时和专业知识密集型任务。为了评估生成的规范的实际适用性，我们将我们的工具嵌入到现有的战略逻辑模型检查器中，使非专家用户能够指定战略属性。

</details>

<details>
<summary><b>14. Whose Side Is Your Agent On? Multi-Party Principal Loyalty in LLM Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Bojie Li、Noah Shi |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-06-29T14:39:38Z |
| **关键词** | `LLM Agent` · `Benchmark` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2606.30383v1](http://arxiv.org/abs/2606.30383v1) |

**📝 摘要概括：**

> 一个快速增长的LLM代理类别是多方：代理代表委托人（向委托人汇报、发送跟进和接收结果） ，同时还与利益可能存在分歧的对手方在单独的渠道中交谈（与供应商谈判、筛选入站请求或在员工之间进行调解）。在这里， “帮助你正在与之交谈的人”是错误的目标。（课程）两种机制仅沿着常见的泄漏/过度回避移动……

</details>

<details>
<summary><b>15. BayesEvolve: Explicit Belief States for Autonomous Scientific Discovery</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Xuening Wu、Shan Yu、Qianya Xu、Shenqin Yin |
| **所属机构** | （详见原文） |
| **顶级机构标签** | NUS、TRI |
| **发布时间** | 2026-06-29T14:14:33Z |
| **关键词** | `Evaluation` · `Memory` |
| **原文链接** | [http://arxiv.org/abs/2606.30335v1](http://arxiv.org/abs/2606.30335v1) |

**📝 摘要概括：**

> 自主科学发现系统越来越多地使用大型语言模型（ LLM ）来提出新的假设，但许多此类系统主要取决于实验记忆：高分候选人档案或最近试验的启发式总结。我们认为，发现代理应该对假设质量保持明确的、具有不确定性的信念。我们进一步表明，信念状态是对坚持不懈的候选人粪便的预测……

</details>

<details>
<summary><b>16. Always-OnAgents:A Survey of Persistent Memory, State, and Governance in LLMAgents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Tianyu Ding、Aditya Nannapaneni、Bingfan Liu、Ling Zhang |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-06-29T13:47:42Z |
| **关键词** | `Evaluation` · `Memory` |
| **原文链接** | [http://arxiv.org/abs/2606.30306v1](http://arxiv.org/abs/2606.30306v1) |

**📝 摘要概括：**

> Always-on agent是其未来行为取决于早期交互中累积的持久状态的系统。我们将它们视为持久状态系统：操作系统包括可检索的记忆，还包括任务分类账、权限、凭据、承诺、出处和审计记录、共享状态、触发条件以及与这些记录相关的外部承诺效果。由此产生的议程将始终在线的代理连接到数据……

</details>

<details>
<summary><b>17. ManimAgent: Self-Evolving Multimodal Agents for Visual Education</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Wenjia Jiang、Zongyuan Cai、Yuanhang Shao、Chenru Wang、Boyan Han 等（共 10 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-06-29T13:37:56Z |
| **关键词** | `Retrieval` · `Evaluation` · `Memory` |
| **原文链接** | [http://arxiv.org/abs/2606.30296v1](http://arxiv.org/abs/2606.30296v1) |

**📝 摘要概括：**

> 多轮反思允许基于大型语言模型构建的代理从单个任务中的失败中恢复，但每个任务仍然是一个孤立的事件：在一个任务的多轮反思中学到的经验教训会在下一个任务开始之前被丢弃。我们在代码生成任务上研究了这一差距：从科学论文部分，代理在开源Manim库中编写Python以渲染数学动画。我们将发布代码， froz……

</details>

<details>
<summary><b>18. Rehearsed Multi-Agent Live Product Demonstrations with Real-Time Voice Question Answering</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Rahul Khedar、Mayank Malhotra、Avinash Karn、Mouli V、Prakhar Mehrotra |
| **所属机构** | （详见原文） |
| **顶级机构标签** | HIT、CAS、TRI |
| **发布时间** | 2026-06-29T13:36:51Z |
| **关键词** | `Multi-Agent` · `RAG` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2606.30294v1](http://arxiv.org/abs/2606.30294v1) |

**📝 摘要概括：**

> 实时产品演示是软件组织中反复出现的高成本活动：人工演示者必须选择功能，在运行的应用程序上调度相应的交互，连贯地叙述它们，并实时回答问题。现有的自动化仅解决片段--通用浏览器代理针对指令条件的任务完成，演示视频工具生成无法查询的固定MP4工件……

</details>

<details>
<summary><b>19. Towards Continual Motion-Language Agents: LoRA Variants for Incremental Motion Understanding and Generation</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Bertram Taetz、Hugo Albuquerque Cosme da Silva、Gabriele Bleser-Taetz |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、HIT、TRI |
| **发布时间** | 2026-06-29T13:14:57Z |
| **关键词** | `Benchmark` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2606.30266v1](http://arxiv.org/abs/2606.30266v1) |

**📝 摘要概括：**

> 运动语言代理必须具备双向能力，既能理解人类运动（运动到文本， M2T ） ，又能从自然语言（文本到运动， T2M ）生成运动。虽然基础模型在静态环境中取得了强大的性能，但在动态环境中运行的自主智能体必须不断融入新的运动概念，例如新颖的运动风格或专门的手势，而不会造成灾难性的遗忘……

</details>

<details>
<summary><b>20. Clarus: Coordinating Autonomous Research Agents toward Web-Scale Scientific Collaboration</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Zihan Guo、Zeyi Chen、Zhiyu Chen、Zicai Cui、Shuai Shao 等（共 18 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | CAS、TRI |
| **发布时间** | 2026-06-29T12:56:08Z |
| **关键词** | `Workflow` |
| **原文链接** | [http://arxiv.org/abs/2606.30246v1](http://arxiv.org/abs/2606.30246v1) |

**📝 摘要概括：**

> 现有的自主研究代理可以支持部分研究过程，但大多数系统仍然将研究视为孤立的助理任务或封闭的工作流程。因此，自主科学需要一个协调项目、代理、数字和物理资源的协作基础设施。Clarus现已在clarus.holosai.io上提供。

</details>

## 🗄️ 历史归档

| 日期 | 论文数 | 报告链接 |
|------|--------|----------|
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
| 2026-06-07 | 0 篇 | [2026-06-07.md](daily/2026-06-07.md) |
| 2026-06-06 | 0 篇 | [2026-06-06.md](daily/2026-06-06.md) |
| 2026-06-05 | 20 篇 | [2026-06-05.md](daily/2026-06-05.md) |
| 2026-06-04 | 0 篇 | [2026-06-04.md](daily/2026-06-04.md) |
| 2026-06-03 | 20 篇 | [2026-06-03.md](daily/2026-06-03.md) |
| 2026-06-02 | 20 篇 | [2026-06-02.md](daily/2026-06-02.md) |
| 2026-06-01 | 0 篇 | [2026-06-01.md](daily/2026-06-01.md) |

## 🏛️ 顶级机构覆盖范围

覆盖超过 **70 个**顶级 AI 机构，包括：

- **科技公司：** Microsoft、Google DeepMind、OpenAI、Anthropic、Meta AI、NVIDIA、Baidu、Alibaba、ByteDance 等
- **北美顶级大学：** MIT、Stanford、CMU、UC Berkeley、Harvard、Princeton、Cornell、Caltech 等
- **中国顶级大学/机构：** 清华大学、北京大学、浙大、上交大、复旦、中科院、MSRA 等
- **欧洲/其他：** Oxford、Cambridge、ETH Zurich、Mila、NUS、KAIST 等

---

*由 [clawBot DailyFindings](https://github.com/Jacob-biu/clawBot) 自动维护 | 最后更新：2026-06-30 23:11 UTC*
