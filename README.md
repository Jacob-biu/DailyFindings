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

## 📅 今日论文 — 2026-07-24　　[→ 查看完整报告](daily/2026-07-24.md)

> 共筛选出 **17** 篇论文 | 更新于 2026-07-24 23:01 UTC

### 论文目录与概要

| # | 论文标题 | 核心概要 | 来源机构 | 第一作者 |
|---|---------|---------|---------|--------|
| 1 | [OpenForgeRL: Train Harness-native Agents in Any Environment](http://arxiv.org/abs/2607.21557v1) | 现代人工智能代理依靠Claude Code、Codex和OpenClaw等精心设计的推理工具来推动多回合推理、工具使用和访问外部系统。虽然功能强大，但这些复杂的线束也使代理难以使用开放式基础设施进行端… | Mila | Xiao Yu |
| 2 | [Same Dangerous Objective, Opposite Advice: Direct Exposure v…](http://arxiv.org/abs/2607.21518v1) | 即使是当前的高性能LLM ，在直接显示危险目标时，也比其他代理人转换和传递其方向时看起来更安全。使用OpenAI的gpt-5.6-sol模型别名，我们测试了25个预先指定的镜像权衡配置文件。同样，仅具… | OpenAI | Linjun Li |
| 3 | [Agentic Context Management: Solving Agent Memory and Cost by…](http://arxiv.org/abs/2607.21503v1) | 生产AI代理的失败较少是因为无法进行良好的推理，更多是因为他们无法管理其推理上下文中的内容：对话历史记录、大型提示、大型工具定义和膨胀的工具输出。代理淹没在自己的累积历史记录中，同时支付不断增长的代币… | MIT、HIT | Gaurav Dadhich |
| 4 | [Toward Continuous Assurance for the Democratization of AI Ag…](http://arxiv.org/abs/2607.21495v1) | 人工智能代理越来越多地由非工程用户通过低代码、无代码和对话式开发环境在组织内部创建。这种民主化可以实现快速的本地创新，但也会造成可靠性差距：在用户看来，简单的生产力制品可能取决于不断变化的模型、工具、… | TRI | Natan Levy |
| 5 | [Compact Latent Coordination for Autonomous Vehicles at Unsig…](http://arxiv.org/abs/2607.21488v1) | 协调无信号交叉路口的自动驾驶汽车仍然是多智能体强化学习（ MARL ）系统面临的关键挑战，这些系统通常难以处理组合动作空间、依赖特权信息或僵化的智能体设计。我们提出主代理原始计划系统（ MAPS ） … | HIT | Gil Lifshits |
| 6 | [Agentic coding without the cloud: evaluating open-weight lar…](http://arxiv.org/abs/2607.21482v1) | 大型语言模型（ LLM ）和代理现在是代码开发中广泛使用的工具，通常将数据发送到第三方基于云的模型。它们在使用个人数据的研究中的采用受到治理要求的限制，这些要求通常禁止将数据传输到外部服务。我们的框架… | TRI | Mack Nixon |
| 7 | [AREX: Towards a Recursively Self-Improving Agent for Deep Re…](http://arxiv.org/abs/2607.21461v1) | 深入研究需要客服代表找到共同满足多个约束的答案。发现这样的答案是昂贵的，而验证候选人通常可以分解为易于处理的约束检查。在BrowseComp、WideSearch、DeepSearchQA、Human… | MIT | Shuqi Lu |
| 8 | [Agent-Guided Relational Concept Discovery: Toward Interpreta…](http://arxiv.org/abs/2607.21437v1) | 深度学习模型可以有效地使用快速蒸发电离质谱（ REIMS ）数据进行手术切缘评估。然而，由于对手术室条件的泛化有限，他们的临床采用仍然具有挑战性。在具有代表性的术中病例中，假阳性较少，表明对手术条件有… | MIT、CAS | Nooshin Maghsoodi |
| 9 | [PATS: Policy-Aware Training Scaffolding for Agentic Reinforc…](http://arxiv.org/abs/2607.21419v1) | 在长期LLM代理强化学习中，弱策略经常重复类似的失败，产生无信息的推出轨迹，限制了有效的策略优化。现有的以技能为中心的方法通过优化、过滤或内化可重复使用的技能来改善探索。在七个搜索增强的QA基准中，它… | MIT、Mila | Yipeng Shi |
| 10 | [Euclid-MCP: A Model Context Protocol Server for Deterministi…](http://arxiv.org/abs/2607.21412v1) | 大型语言模型（ LLM ）在自然语言理解和生成方面表现出色，但在多步骤逻辑推理方面仍然不可靠，尤其是在安全关键或合规敏感的领域。最近的神经符号方法通过将神经模型与外部符号引擎耦合来解决这一差距，但大多… | CAS | Bartolomeo Bogliolo |
| 11 | [VoLN: Vision-Only Long-Horizon Navigation---Paradigm, Benchm…](http://arxiv.org/abs/2607.21400v1) | 视觉和语言导航(VLN)使具体的代理能够遵循自然语言指令。然而，路由级指令通常编码空间先验信息，例如方向、距离和布局，这些信息在开放的GPS拒绝环境中的部署时无法从机载传感中明确获得。项目页面： ht… | TRI | Jiabin Lou |
| 12 | [Toward cryptographically verifiable authorization for autono…](http://arxiv.org/abs/2607.21325v1) | 自主人工智能代理越来越多地在有限的人工监督下执行操作、调用工具并使用受保护的资源进行操作。现有的身份验证和授权机制建立身份和委托权限，但不能固有地提供加密证据，证明特定代理发出的具体请求满足特定执行上… | MIT、TRI | M. Llambí-Morillas |
| 13 | [GRADRAG: Cross-Component Prompt Adaptation for Coordinated M…](http://arxiv.org/abs/2607.21324v1) | 检索增强生成（ RAG ）系统越来越多地使用多个LLM代理。然而，大多数先前的工作都是孤立地优化组件，而不是在整个管道中协调改进。在这两种情况下， GRADRAG的表现始终优于仅更新最终生成器的一步优… | TRI | Paolo Pedinotti |
| 14 | [Expert Behavior Prior Reinforcement Learning](http://arxiv.org/abs/2607.21302v1) | 行为先验强化学习（ BPRL ）已成为一种有希望的范例，通过利用线下演示得出的政策先验来提高在线强化学习（ RL ）的样本效率。然而，大多数现有的BPRL方法依赖于静态离线数据集，这些数据集通常存在低… | MIT、TRI | Gong Gao |
| 15 | [The Dark Room in the Reward Channel: Dense Prediction Reward…](http://arxiv.org/abs/2607.21273v1) | 对于稀疏奖励的长期LLM代理来说，密集的每步监督是一种有吸引力的补救措施：奖励代理预测其下一次观察，并且应该遵循记忆。我们表明，在组规范化RL （ GRPO ）下，这种配方不仅会失败，还会破坏策略。终… | TRI | Yu Wang |
| 16 | [pAI-Econ-claude: A Gated Human-in-the-Loop Multi-Agent Archi…](http://arxiv.org/abs/2607.21268v1) | 在许多社会科学研究任务中，例如经济学，基于法学硕士的代理必须产生没有廉价、任务完整、机器可读的正确性信号的输出。这为多智能体系统创造了一个独特的可靠性问题：当没有组件可以证明最终结果时，应该如何组织生… | HIT、CAS | Chen Zhu |
| 17 | [ICAE-Bench: Evaluating Coding Agents as Interactive Project …](http://arxiv.org/abs/2607.21217v1) | 最近出现的氛围编码工作流程正在改变编码代理应做的事情。代理商不是仅在完全指定的指令下完成代码，而是越来越多地期望通过结合各种能力，包括规划、需求澄清、工具使用、调试和存储库级构建，将不完整的产品意图转… | FAIR、Mila | Zhongyuan Peng |

### 论文详情

<details>
<summary><b>1. OpenForgeRL: Train Harness-native Agents in Any Environment</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Xiao Yu、Baolin Peng、Ruize Xu、Hao Zou、Qianhui Wu 等（共 10 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | Mila |
| **发布时间** | 2026-07-23T17:38:30Z |
| **关键词** | `AI Agent` · `Agentic` · `Reasoning` · `RAG` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2607.21557v1](http://arxiv.org/abs/2607.21557v1) |

**📝 摘要概括：**

> 现代人工智能代理依靠Claude Code、Codex和OpenClaw等精心设计的推理工具来推动多回合推理、工具使用和访问外部系统。虽然功能强大，但这些复杂的线束也使代理难以使用开放式基础设施进行端到端培训，其SFT/RL堆栈无法本机表达有状态的多进程线束推断。我们发现有些线束比其他线束更难学习，而强化学习……

</details>

<details>
<summary><b>2. Same Dangerous Objective, Opposite Advice: Direct Exposure versus Multi-Agent Mediation</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Linjun Li |
| **所属机构** | （详见原文） |
| **顶级机构标签** | OpenAI |
| **发布时间** | 2026-07-23T17:02:11Z |
| **关键词** | `Multi-Agent` · `Workflow` |
| **原文链接** | [http://arxiv.org/abs/2607.21518v1](http://arxiv.org/abs/2607.21518v1) |

**📝 摘要概括：**

> 即使是当前的高性能LLM ，在直接显示危险目标时，也比其他代理人转换和传递其方向时看起来更安全。使用OpenAI的gpt-5.6-sol模型别名，我们测试了25个预先指定的镜像权衡配置文件。同样，仅具有端点访问权限的用户不能直接检查包括目标在内的上游消息。

</details>

<details>
<summary><b>3. Agentic Context Management: Solving Agent Memory and Cost by Treating Them as Lifecycle and Architecture Problems</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Gaurav Dadhich |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、HIT、CAS |
| **发布时间** | 2026-07-23T16:51:31Z |
| **关键词** | `AI Agent` · `Agentic` · `Reasoning` · `RAG` · `Retrieval` |
| **原文链接** | [http://arxiv.org/abs/2607.21503v1](http://arxiv.org/abs/2607.21503v1) |

**📝 摘要概括：**

> 生产AI代理的失败较少是因为无法进行良好的推理，更多是因为他们无法管理其推理上下文中的内容：对话历史记录、大型提示、大型工具定义和膨胀的工具输出。代理淹没在自己的累积历史记录中，同时支付不断增长的代币成本，在对话中和交谈中产生缺失的召回。我们以现有基准的维度结束……

</details>

<details>
<summary><b>4. Toward Continuous Assurance for the Democratization of AI Agent Creation in Industry</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Natan Levy、Harel Berger |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-07-23T16:41:56Z |
| **关键词** | `AI Agent` · `Retrieval` |
| **原文链接** | [http://arxiv.org/abs/2607.21495v1](http://arxiv.org/abs/2607.21495v1) |

**📝 摘要概括：**

> 人工智能代理越来越多地由非工程用户通过低代码、无代码和对话式开发环境在组织内部创建。这种民主化可以实现快速的本地创新，但也会造成可靠性差距：在用户看来，简单的生产力制品可能取决于不断变化的模型、工具、检索源、权限、提示、时间表和外部服务。我们还介绍了最初的抗议活动……

</details>

<details>
<summary><b>5. Compact Latent Coordination for Autonomous Vehicles at Unsignalized Intersections</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Gil Lifshits、Igal Bilik、Gilad Katz |
| **所属机构** | （详见原文） |
| **顶级机构标签** | HIT |
| **发布时间** | 2026-07-23T16:28:35Z |
| **关键词** | `Multi-Agent` · `Reinforcement Learning` · `RAG` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2607.21488v1](http://arxiv.org/abs/2607.21488v1) |

**📝 摘要概括：**

> 协调无信号交叉路口的自动驾驶汽车仍然是多智能体强化学习（ MARL ）系统面临的关键挑战，这些系统通常难以处理组合动作空间、依赖特权信息或僵化的智能体设计。我们提出主代理原始计划系统（ MAPS ） ，这是一种分层深度强化学习（ DRL ）架构，其中集中的主代理生成紧凑、连续的嵌入……

</details>

<details>
<summary><b>6. Agentic coding without the cloud: evaluating open-weight large language models on longitudinal data preparation tasks</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Mack Nixon、Liam Wright、Yevgeniya Kovalchuk、Alison Fang-Wei Wu、Martin Danka 等（共 7 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-07-23T16:23:42Z |
| **关键词** | `AI Agent` · `Agentic` · `RAG` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2607.21482v1](http://arxiv.org/abs/2607.21482v1) |

**📝 摘要概括：**

> 大型语言模型（ LLM ）和代理现在是代码开发中广泛使用的工具，通常将数据发送到第三方基于云的模型。它们在使用个人数据的研究中的采用受到治理要求的限制，这些要求通常禁止将数据传输到外部服务。我们的框架可在以下网址公开获取： https://github.com/UCL-ARC/RRBench。

</details>

<details>
<summary><b>7. AREX: Towards a Recursively Self-Improving Agent for Deep Research</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Shuqi Lu、Chaofan Li、Kun Luo、Zhang Zhang、Hui Wang 等（共 24 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT |
| **发布时间** | 2026-07-23T16:05:46Z |
| **关键词** | `Agentic` · `Reasoning` · `Reinforcement Learning` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2607.21461v1](http://arxiv.org/abs/2607.21461v1) |

**📝 摘要概括：**

> 深入研究需要客服代表找到共同满足多个约束的答案。发现这样的答案是昂贵的，而验证候选人通常可以分解为易于处理的约束检查。在BrowseComp、WideSearch、DeepSearchQA、Humanity's Last Exam (HLE)以及其他推理和工具使用基准测试中， AREX的表现大大优于可比规模基线，并且与使用大幅……的模型保持竞争力

</details>

<details>
<summary><b>8. Agent-Guided Relational Concept Discovery: Toward Interpretable Surgical Margin Assessment</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Nooshin Maghsoodi、Amoon Jamzad、Robert Policelli、Mohammad Farahmand、Dilakshan Srikanthan 等（共 14 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、CAS |
| **发布时间** | 2026-07-23T15:44:04Z |
| **关键词** | `Reasoning` · `Workflow` |
| **原文链接** | [http://arxiv.org/abs/2607.21437v1](http://arxiv.org/abs/2607.21437v1) |

**📝 摘要概括：**

> 深度学习模型可以有效地使用快速蒸发电离质谱（ REIMS ）数据进行手术切缘评估。然而，由于对手术室条件的泛化有限，他们的临床采用仍然具有挑战性。在具有代表性的术中病例中，假阳性较少，表明对手术条件有更好的概括。

</details>

<details>
<summary><b>9. PATS: Policy-Aware Training Scaffolding for Agentic Reinforcement Learning</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Yipeng Shi、Zhipeng Ma、Yue Wang、Qitai Tan、Yang Li 等（共 7 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、Mila、TRI |
| **发布时间** | 2026-07-23T15:24:35Z |
| **关键词** | `LLM Agent` · `Agentic` · `Reinforcement Learning` · `Benchmark` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2607.21419v1](http://arxiv.org/abs/2607.21419v1) |

**📝 摘要概括：**

> 在长期LLM代理强化学习中，弱策略经常重复类似的失败，产生无信息的推出轨迹，限制了有效的策略优化。现有的以技能为中心的方法通过优化、过滤或内化可重复使用的技能来改善探索。在七个搜索增强的QA基准中，它仍然具有竞争力，同时使用的提示令牌比基准少32.1%。

</details>

<details>
<summary><b>10. Euclid-MCP: A Model Context Protocol Server for Deterministic Logical Reasoning via Prolog</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Bartolomeo Bogliolo |
| **所属机构** | （详见原文） |
| **顶级机构标签** | CAS |
| **发布时间** | 2026-07-23T15:15:37Z |
| **关键词** | `Agentic` · `Reasoning` · `RAG` |
| **原文链接** | [http://arxiv.org/abs/2607.21412v1](http://arxiv.org/abs/2607.21412v1) |

**📝 摘要概括：**

> 大型语言模型（ LLM ）在自然语言理解和生成方面表现出色，但在多步骤逻辑推理方面仍然不可靠，尤其是在安全关键或合规敏感的领域。最近的神经符号方法通过将神经模型与外部符号引擎耦合来解决这一差距，但大多数集成都是定制的，缺乏工具增强代理的标准化接口。我们认为，语义抹布从根本上说是……

</details>

<details>
<summary><b>11. VoLN: Vision-Only Long-Horizon Navigation---Paradigm, Benchmark, and Method</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Jiabin Lou、Haopeng Wang、Yuanshuai Wang、Xinyu Liu、Xuxin Lv 等（共 9 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-07-23T15:02:01Z |
| **关键词** | `Benchmark` · `Evaluation` · `Embodied AI` |
| **原文链接** | [http://arxiv.org/abs/2607.21400v1](http://arxiv.org/abs/2607.21400v1) |

**📝 摘要概括：**

> 视觉和语言导航(VLN)使具体的代理能够遵循自然语言指令。然而，路由级指令通常编码空间先验信息，例如方向、距离和布局，这些信息在开放的GPS拒绝环境中的部署时无法从机载传感中明确获得。项目页面： https://admire-ljb.github.io/VoLN-UAV/

</details>

<details>
<summary><b>12. Toward cryptographically verifiable authorization for autonomous AI agents: A security hypothesis, preliminary formal model, and proof-of-concept implementation</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | M. Llambí-Morillas、D. Fernández-Fernández |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-07-23T13:55:02Z |
| **关键词** | `AI Agent` · `Agentic` |
| **原文链接** | [http://arxiv.org/abs/2607.21325v1](http://arxiv.org/abs/2607.21325v1) |

**📝 摘要概括：**

> 自主人工智能代理越来越多地在有限的人工监督下执行操作、调用工具并使用受保护的资源进行操作。现有的身份验证和授权机制建立身份和委托权限，但不能固有地提供加密证据，证明特定代理发出的具体请求满足特定执行上下文中的适用策略。我们进一步确定并规范了结构分离……

</details>

<details>
<summary><b>13. GRADRAG: Cross-Component Prompt Adaptation for Coordinated Multi-Agent RAG</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Paolo Pedinotti、Enrico Santus |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-07-23T13:54:38Z |
| **关键词** | `Multi-Agent` · `LLM Agent` · `RAG` · `Retrieval` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2607.21324v1](http://arxiv.org/abs/2607.21324v1) |

**📝 摘要概括：**

> 检索增强生成（ RAG ）系统越来越多地使用多个LLM代理。然而，大多数先前的工作都是孤立地优化组件，而不是在整个管道中协调改进。在这两种情况下， GRADRAG的表现始终优于仅更新最终生成器的一步优化基线，在LLM判断的成对比较中实现了12-15个百分点的净优惠幅度，大多数收益在两个月内实现……

</details>

<details>
<summary><b>14. Expert Behavior Prior Reinforcement Learning</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Gong Gao、Weidong Zhao、Xianhui Liu、Ning Jia |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-07-23T13:26:57Z |
| **关键词** | `Reinforcement Learning` · `RAG` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2607.21302v1](http://arxiv.org/abs/2607.21302v1) |

**📝 摘要概括：**

> 行为先验强化学习（ BPRL ）已成为一种有希望的范例，通过利用线下演示得出的政策先验来提高在线强化学习（ RL ）的样本效率。然而，大多数现有的BPRL方法依赖于静态离线数据集，这些数据集通常存在低数据多样性和次优轨迹质量的问题。对机器人控制（健身房、PyBullet ）和工业控制进行了广泛的实验……

</details>

<details>
<summary><b>15. The Dark Room in the Reward Channel: Dense Prediction Rewards Collapse GRPO-Trained LLM Agents -- and What Actually Works</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Yu Wang |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-07-23T12:50:18Z |
| **关键词** | `LLM Agent` · `Memory` |
| **原文链接** | [http://arxiv.org/abs/2607.21273v1](http://arxiv.org/abs/2607.21273v1) |

**📝 摘要概括：**

> 对于稀疏奖励的长期LLM代理来说，密集的每步监督是一种有吸引力的补救措施：奖励代理预测其下一次观察，并且应该遵循记忆。我们表明，在组规范化RL （ GRPO ）下，这种配方不仅会失败，还会破坏策略。终点为单种子；种子复制和组大小对照已预先注册并正在进行中。

</details>

<details>
<summary><b>16. pAI-Econ-claude: A Gated Human-in-the-Loop Multi-Agent Architecture for AI-Assisted Economic Theory Development</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Chen Zhu、Xiaolu Wang、Weilong Zhang |
| **所属机构** | （详见原文） |
| **顶级机构标签** | HIT、CAS |
| **发布时间** | 2026-07-23T12:40:47Z |
| **关键词** | `Multi-Agent` · `Workflow` |
| **原文链接** | [http://arxiv.org/abs/2607.21268v1](http://arxiv.org/abs/2607.21268v1) |

**📝 摘要概括：**

> 在许多社会科学研究任务中，例如经济学，基于法学硕士的代理必须产生没有廉价、任务完整、机器可读的正确性信号的输出。这为多智能体系统创造了一个独特的可靠性问题：当没有组件可以证明最终结果时，应该如何组织生成、批评、协调和人类判断？工作流程可在https://github.com/maxwell2732/pAI-Eco上公开获取……

</details>

<details>
<summary><b>17. ICAE-Bench: Evaluating Coding Agents as Interactive Project Builders</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Zhongyuan Peng、Dan Huang、Chuyu Zhang、Caijun Xu、Changyi Xiao 等（共 11 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | FAIR、Mila |
| **发布时间** | 2026-07-23T11:31:38Z |
| **关键词** | `Planning` · `Benchmark` · `Simulation` · `Workflow` |
| **原文链接** | [http://arxiv.org/abs/2607.21217v1](http://arxiv.org/abs/2607.21217v1) |

**📝 摘要概括：**

> 最近出现的氛围编码工作流程正在改变编码代理应做的事情。代理商不是仅在完全指定的指令下完成代码，而是越来越多地期望通过结合各种能力，包括规划、需求澄清、工具使用、调试和存储库级构建，将不完整的产品意图转化为工作软件。第三，为了公平地评估开放式存储库， ICAE……

</details>

## 🗄️ 历史归档

| 日期 | 论文数 | 报告链接 |
|------|--------|----------|
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

## 🏛️ 顶级机构覆盖范围

覆盖超过 **70 个**顶级 AI 机构，包括：

- **科技公司：** Microsoft、Google DeepMind、OpenAI、Anthropic、Meta AI、NVIDIA、Baidu、Alibaba、ByteDance 等
- **北美顶级大学：** MIT、Stanford、CMU、UC Berkeley、Harvard、Princeton、Cornell、Caltech 等
- **中国顶级大学/机构：** 清华大学、北京大学、浙大、上交大、复旦、中科院、MSRA 等
- **欧洲/其他：** Oxford、Cambridge、ETH Zurich、Mila、NUS、KAIST 等

---

*由 [clawBot DailyFindings](https://github.com/Jacob-biu/clawBot) 自动维护 | 最后更新：2026-07-24 23:01 UTC*
