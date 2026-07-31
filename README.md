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

## 📅 今日论文 — 2026-07-31　　[→ 查看完整报告](daily/2026-07-31.md)

> 共筛选出 **20** 篇论文 | 更新于 2026-07-31 22:59 UTC

### 论文目录与概要

| # | 论文标题 | 核心概要 | 来源机构 | 第一作者 |
|---|---------|---------|---------|--------|
| 1 | [AskChem: Claim-Centered Infrastructure for Chemistry Literat…](http://arxiv.org/abs/2607.28618v1) | 化学文献合成通常需要汇总分散在许多出版物中的特定发现，但现有的文献搜索系统主要返回排名文档列表。因此，科学家和人工智能代理需要定位相关信息，验证其出处，并手动组装跨纸答案。AskChem现已上线htt… | TRI | Bing Yan |
| 2 | [OSReward: Instituting Standardized Evaluation for Cross-Plat…](http://arxiv.org/abs/2607.28609v1) | 计算机使用代理（ CUA ）正在数字世界中迅速发展。CUA轨迹记录客服代表的行为、状态和推理。我们的代码、基准、数据集和模型检查点可在https://os-copilot.github.io/OSRe… | CAS | Qiushi Sun |
| 3 | [Change2Task: From Repository Changes to Executable Coding Ag…](http://arxiv.org/abs/2607.28591v1) | 扩展编码代理需要持续提供用于培训、基准测试和持续评估的可执行数据。每个任务都必须将真实的软件状态与规范、开发工具和可靠的验证相结合。根据药剂评估，历史和重建病例达到高达98.0%的匹配结局协议，而现代… | CAS | Haomin Qi |
| 4 | [Rethinking Inference-Time Scaling in Local Computer-Use Agen…](http://arxiv.org/abs/2607.28573v1) | 在本地部署自主计算机使用代理(CUA)对于隐私、成本效益和实用性越来越重要，但在严格的硬件限制下提高其性能仍然具有挑战性。虽然最近的研究表明，推理时间缩放可以通过执行期间的额外计算来改善前沿计算机使用… | MIT、Mila | Woongkyu Lee |
| 5 | [ORCA-bench: How Ready Are Language Model Agents for Oncall?](http://arxiv.org/abs/2607.28545v1) | 大型语言模型可以编写、修补和搜索代码，但呼叫根本原因分析（ RCA ）需要不同的东西：推理嘈杂的指标、日志、跟踪和源代码，从模糊的面向用户的报告开始，通常在事件发生几小时后开始。我们引入了ORCA-b… | TRI | Albert Gong |
| 6 | [MANTA: Multi-Agent Network Topology Adaptation for Self-Evol…](http://arxiv.org/abs/2607.28527v1) | 基于大型语言模型的多智能体系统通过任务分解、智能体专业化、信息交换和中间验证来改进复杂的问题解决。然而，现有系统通常将通信拓扑视为固定设计选择或离线优化目标。这些结果表明，推理时间自我完善可以扩展到协… | HIT | Mao-xun Huang |
| 7 | [Selective Credibility-Limited Belief Update](http://arxiv.org/abs/2607.28523v1) | 信念更新涉及潜在世界的变化引起的客服代表信念的变化。标准Katsuno-Mendelzon更新假设可以从每个最初可能的世界中纳入认知输入，而可信度有限的信念更新限制了每个源世界被认为是可信或可触及的后… | MIT、CAS | Theofanis Aravanis |
| 8 | [Agents That Certify Their Own Exploits: Confidence-Scheduled…](http://arxiv.org/abs/2607.28520v1) | 在两人零和缺陷信息游戏中玩纳什均衡策略的主体会确保游戏价值，但会丧失有缺陷的对手提供的额外价值。弥漫性偏差构成了一个特殊的挑战：二进制发布规则可能收集的证据太少而无法采取行动，而对不完整的对手模型的完… | MIT、TRI | Boning Li |
| 9 | [The Role of Causality in Algorithmic Recourse](http://arxiv.org/abs/2607.28497v1) | 算法追索旨在为个人提供可操作的更改，以改善他们在高风险分类环境中的预测结果，例如贷款和抵押贷款申请。然而，大多数现有方法只关注翻转模型的预测，而不考虑推荐的更改是否会真正改善个人的真实资格，还是仅仅使… | TRI | Srikanth Avasarala |
| 10 | [Why Are GUI Agents Correct but Late? Decode on the Decision-…](http://arxiv.org/abs/2607.28399v1) | 计算机使用代理通常会在瞬态GUI事件上失败，因为它们只有在相关窗口已关闭后才会产生正确的操作。我们将主要原因确定为决策时关键路径上昂贵的自回归解码。总之，这些结果表明，当可以提前列举候选人行动时， A… | TRI | Zihan Dong |
| 11 | [LEDGERMIND: Provenance-Constrained Multimodal Agentic Reason…](http://arxiv.org/abs/2607.28374v1) | 用于视觉问答的多模态代理越来越多地作为多步轨迹运行，将感知、检索和推理交织在一起，但评估仍然在很大程度上降低到最终答案的准确性。此汇总信号无法判断是否通过有根据的证据、语言先验或意外错误取消获得了正确… | TRI | Enjun Du |
| 12 | [How Benchmarks Mis-Score Computer-Use Agents](http://arxiv.org/abs/2607.28367v1) | 正在部署计算机使用代理（ CUA ）来浏览网页和操作桌面软件，但它们的基准分数仍然通常由脆弱的脚本预言机生成。分数是管道的输出，其中任务可能过时，轨迹可以省略决定性的视觉证据，评估人员可以拒绝有效的替… | MIT | Zihan Dong |
| 13 | [Paying for Honesty Without Knowing the Truth: Reputation-Pen…](http://arxiv.org/abs/2607.28330v1) | LLM代理商越来越多地充当自主商家，编写自己的产品清单，并且在竞争压力下，他们捏造属性以赢得销售。即使在诚实的指导下，他们也会在大多数模型中的房源中捏造属性。我们将这种区别追溯到惩罚门限的自我纠正推理… | TRI | Mingdai Yang |
| 14 | [MemHarness: Memory Is Reconstructed, Not Replayed](http://arxiv.org/abs/2607.28272v1) | 检索过去的经验已成为增强大型语言模型代理的常用策略。但是，大多数现有的记忆增强客服代表将检索到的体验视为要逐字重播的静态记录，将它们注入上下文，无论它们是否与客服代表的当前情况一致。此外，我们的分析显… | TRI | Rong Wu |
| 15 | [Agentic Method for Deterministic Validation of Legacy Code M…](http://arxiv.org/abs/2607.28271v1) | 将旧版COBOL程序迁移到Java需要进行广泛的测试，以确保正确的功能。由于缺乏测试数据以及难以验证所有转折点案例，这项工作通常会变得复杂。通过这些发现，据我们所知，我们展示了一种使用确定性预言机验证… | MIT、CAS | Andras Ferenczi |
| 16 | [Agentic Metaverse Services: A New As-a-Service Paradigm](http://arxiv.org/abs/2607.28242v1) | 生成人工智能（ GenAI ）正在重建数字虚拟世界，通过提高智能体在自主学习、多模态交互、内容生成和协作决策方面的能力来升级智能体。特别是，从对话式聊天机器人到智能人工智能的转变，这是GenAI最新的… | TRI | Xiaofei Xu |
| 17 | [EMBL AI Librarian: Life-Sciences Knowledge Layer for AI Agen…](http://arxiv.org/abs/2607.28229v1) | 网络越来越多地被人工智能代理而不是人类访问。每个代理都需要知识，特别是在生命科学领域，代理渠道正在快速增长。我们在https://github.com/petroni-lab/librarian上公开… | TRI | Luigi Sigillo |
| 18 | [Qwen-UI-Agent Technical Report: Toward Next-Generation Real-…](http://arxiv.org/abs/2607.28227v1) | GUI代理有可能成为现有数字设备的通用执行者。为了推动它们在现实世界中的使用，我们设想了在真实设备上可靠运行的代理，跨平台执行工作流程，将GUI交互与CLI执行相结合，完成长时间任务，主动启动有用的服… | TRI | Hanzhang Zhou |
| 19 | [Vibe-FDTR: An agent-oriented framework for reproducible freq…](http://arxiv.org/abs/2607.28200v1) | 频域温度反射率（ FDTR ）是一种激光泵浦探针技术，广泛用于测量微观和纳米尺度的热特性；然而，它依赖于复杂的数据分析过程，需要大量的领域专业知识，并且容易出现微妙的人为错误。在这里，我们展示了Vib… | MIT、HIT | Fuwei Yang |
| 20 | [Integrating AI into Requirements Quality Learning in Softwar…](http://arxiv.org/abs/2607.28176v1) | 在软件工程（ SE ）实践中快速采用生成式人工智能（ AI ） ，需要在SE教育中采用基于教学的人工智能集成方法，特别是在需求工程（ RE ）等概念密集型学科中。本研究考察了TPACK引导的多代理AI… | MIT | Hansika Ekanayake Mudiyanselage |

### 论文详情

<details>
<summary><b>1. AskChem: Claim-Centered Infrastructure for Chemistry Literature Synthesis</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Bing Yan、Gregory Wolfe、Stefano Martiniani、Kyunghyun Cho |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-07-30T17:59:11Z |
| **关键词** | `AI Agent` · `Retrieval` |
| **原文链接** | [http://arxiv.org/abs/2607.28618v1](http://arxiv.org/abs/2607.28618v1) |

**📝 摘要概括：**

> 化学文献合成通常需要汇总分散在许多出版物中的特定发现，但现有的文献搜索系统主要返回排名文档列表。因此，科学家和人工智能代理需要定位相关信息，验证其出处，并手动组装跨纸答案。AskChem现已上线https://askchem.org。

</details>

<details>
<summary><b>2. OSReward: Instituting Standardized Evaluation for Cross-Platform Computer-Use Reward Models</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Qiushi Sun、Kanzhi Cheng、Yian Wang、Bowen Yang、Hang Yan 等（共 23 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | CAS |
| **发布时间** | 2026-07-30T17:57:41Z |
| **关键词** | `Reasoning` · `Reinforcement Learning` · `Benchmark` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2607.28609v1](http://arxiv.org/abs/2607.28609v1) |

**📝 摘要概括：**

> 计算机使用代理（ CUA ）正在数字世界中迅速发展。CUA轨迹记录客服代表的行为、状态和推理。我们的代码、基准、数据集和模型检查点可在https://os-copilot.github.io/OSReward-Home/上找到。

</details>

<details>
<summary><b>3. Change2Task: From Repository Changes to Executable Coding Agent Tasks and Environments</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Haomin Qi、Xingliang Wang、Xuanqi Gao、Baihui Sang、Xin Zhang 等（共 12 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | CAS |
| **发布时间** | 2026-07-30T17:44:31Z |
| **关键词** | `RAG` · `Benchmark` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2607.28591v1](http://arxiv.org/abs/2607.28591v1) |

**📝 摘要概括：**

> 扩展编码代理需要持续提供用于培训、基准测试和持续评估的可执行数据。每个任务都必须将真实的软件状态与规范、开发工具和可靠的验证相结合。根据药剂评估，历史和重建病例达到高达98.0%的匹配结局协议，而现代基础的重复使用使整个管道中的测量支出减少了10.8%。

</details>

<details>
<summary><b>4. Rethinking Inference-Time Scaling in Local Computer-Use Agents: Failure Modes and Compute Tradeoffs</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Woongkyu Lee、Jungwook Choi |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、Mila、TRI |
| **发布时间** | 2026-07-30T17:36:36Z |
| **关键词** | `Agentic` · `Planning` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2607.28573v1](http://arxiv.org/abs/2607.28573v1) |

**📝 摘要概括：**

> 在本地部署自主计算机使用代理(CUA)对于隐私、成本效益和实用性越来越重要，但在严格的硬件限制下提高其性能仍然具有挑战性。虽然最近的研究表明，推理时间缩放可以通过执行期间的额外计算来改善前沿计算机使用代理，但其对资源受限的局部模型的有效性仍然知之甚少。……

</details>

<details>
<summary><b>5. ORCA-bench: How Ready Are Language Model Agents for Oncall?</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Albert Gong、Kyuseong Choi、Abhineet Agarwal、Jason Schechner、Ryan Huang 等（共 8 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-07-30T17:14:07Z |
| **关键词** | `Reasoning` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2607.28545v1](http://arxiv.org/abs/2607.28545v1) |

**📝 摘要概括：**

> 大型语言模型可以编写、修补和搜索代码，但呼叫根本原因分析（ RCA ）需要不同的东西：推理嘈杂的指标、日志、跟踪和源代码，从模糊的面向用户的报告开始，通常在事件发生几小时后开始。我们引入了ORCA-bench ，这是一个将通用编码代理置于生产保真随叫随到的基准。我们在https://hub.harborframework.com/data上发布公开套装……

</details>

<details>
<summary><b>6. MANTA: Multi-Agent Network Topology Adaptation for Self-Evolving Multi-Agent Systems</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Mao-xun Huang、Jerry Wang、Yi-Cheng Lai、Zhengxin Zhang、Claire Cardie 等（共 6 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | HIT |
| **发布时间** | 2026-07-30T17:01:27Z |
| **关键词** | `Multi-Agent` · `Reasoning` · `Planning` · `RAG` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2607.28527v1](http://arxiv.org/abs/2607.28527v1) |

**📝 摘要概括：**

> 基于大型语言模型的多智能体系统通过任务分解、智能体专业化、信息交换和中间验证来改进复杂的问题解决。然而，现有系统通常将通信拓扑视为固定设计选择或离线优化目标。这些结果表明，推理时间自我完善可以扩展到协作本身的架构。

</details>

<details>
<summary><b>7. Selective Credibility-Limited Belief Update</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Theofanis Aravanis、Costas D. Koutras |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、CAS、TRI |
| **发布时间** | 2026-07-30T17:00:38Z |
| **关键词** | — |
| **原文链接** | [http://arxiv.org/abs/2607.28523v1](http://arxiv.org/abs/2607.28523v1) |

**📝 摘要概括：**

> 信念更新涉及潜在世界的变化引起的客服代表信念的变化。标准Katsuno-Mendelzon更新假设可以从每个最初可能的世界中纳入认知输入，而可信度有限的信念更新限制了每个源世界被认为是可信或可触及的后续世界。这些结果表明，该框架提供了一个统一且严格更具表现力的……

</details>

<details>
<summary><b>8. Agents That Certify Their Own Exploits: Confidence-Scheduled Restricted Responses for Safe Opponent Exploitation</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Boning Li、Longbo Huang |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-07-30T16:57:57Z |
| **关键词** | — |
| **原文链接** | [http://arxiv.org/abs/2607.28520v1](http://arxiv.org/abs/2607.28520v1) |

**📝 摘要概括：**

> 在两人零和缺陷信息游戏中玩纳什均衡策略的主体会确保游戏价值，但会丧失有缺陷的对手提供的额外价值。弥漫性偏差构成了一个特殊的挑战：二进制发布规则可能收集的证据太少而无法采取行动，而对不完整的对手模型的完全最佳响应可能是高度可利用的。在Leduc、Liar's Dice和5级Leduc中，所有$ 36 {,} 000 $的审计手……

</details>

<details>
<summary><b>9. The Role of Causality in Algorithmic Recourse</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Srikanth Avasarala、Varun Gupta、Shahin Jabbari、Saber Salehkaleybar、Juba Ziani |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-07-30T16:42:51Z |
| **关键词** | — |
| **原文链接** | [http://arxiv.org/abs/2607.28497v1](http://arxiv.org/abs/2607.28497v1) |

**📝 摘要概括：**

> 算法追索旨在为个人提供可操作的更改，以改善他们在高风险分类环境中的预测结果，例如贷款和抵押贷款申请。然而，大多数现有方法只关注翻转模型的预测，而不考虑推荐的更改是否会真正改善个人的真实资格，还是仅仅使分类器的战略博弈成为可能。Experim…

</details>

<details>
<summary><b>10. Why Are GUI Agents Correct but Late? Decode on the Decision-Time Critical Path, Tested with Pre-Compiled Policy Trees</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Zihan Dong、Rui Qian、Qishi Zhan、Dongshen Peng、Kaixin Li 等（共 6 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-07-30T15:50:10Z |
| **关键词** | `Planning` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2607.28399v1](http://arxiv.org/abs/2607.28399v1) |

**📝 摘要概括：**

> 计算机使用代理通常会在瞬态GUI事件上失败，因为它们只有在相关窗口已关闭后才会产生正确的操作。我们将主要原因确定为决策时关键路径上昂贵的自回归解码。总之，这些结果表明，当可以提前列举候选人行动时， AAPT表现最佳，而当无法列举候选人行动时，被动执行仍然更强。

</details>

<details>
<summary><b>11. LEDGERMIND: Provenance-Constrained Multimodal Agentic Reasoning with a Structured Evidence Ledger</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Enjun Du、Hange Zhou、Chenxu Du、Siyi Liu、Zirong Chen 等（共 7 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-07-30T15:35:34Z |
| **关键词** | `Agentic` · `Reasoning` · `Retrieval` · `Benchmark` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2607.28374v1](http://arxiv.org/abs/2607.28374v1) |

**📝 摘要概括：**

> 用于视觉问答的多模态代理越来越多地作为多步轨迹运行，将感知、检索和推理交织在一起，但评估仍然在很大程度上降低到最终答案的准确性。此汇总信号无法判断是否通过有根据的证据、语言先验或意外错误取消获得了正确答案。跨多个多模态推理基准和主干传销的实验表明……

</details>

<details>
<summary><b>12. How Benchmarks Mis-Score Computer-Use Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Zihan Dong、Zhiyuan Ma、Zekun Wang、Yunqing Li、Zirou Liu 等（共 8 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT |
| **发布时间** | 2026-07-30T15:29:42Z |
| **关键词** | `Planning` · `Benchmark` · `Evaluation` · `Workflow` |
| **原文链接** | [http://arxiv.org/abs/2607.28367v1](http://arxiv.org/abs/2607.28367v1) |

**📝 摘要概括：**

> 正在部署计算机使用代理（ CUA ）来浏览网页和操作桌面软件，但它们的基准分数仍然通常由脆弱的脚本预言机生成。分数是管道的输出，其中任务可能过时，轨迹可以省略决定性的视觉证据，评估人员可以拒绝有效的替代方案，汇总报告可以隐藏失败的原因。我们将这些发现与较新的长期CUA基准和…

</details>

<details>
<summary><b>13. Paying for Honesty Without Knowing the Truth: Reputation-Penalty Design for LLM Marketplace Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Mingdai Yang、Shicheng Fan、Kejing Yu、Duohao Wang、Li Sun 等（共 8 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-07-30T14:59:29Z |
| **关键词** | `LLM Agent` · `Reasoning` |
| **原文链接** | [http://arxiv.org/abs/2607.28330v1](http://arxiv.org/abs/2607.28330v1) |

**📝 摘要概括：**

> LLM代理商越来越多地充当自主商家，编写自己的产品清单，并且在竞争压力下，他们捏造属性以赢得销售。即使在诚实的指导下，他们也会在大多数模型中的房源中捏造属性。我们将这种区别追溯到惩罚门限的自我纠正推理，并观察跨模型的绑定，并支持置信区间。

</details>

<details>
<summary><b>14. MemHarness: Memory Is Reconstructed, Not Replayed</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Rong Wu、Daocheng Fu、Licheng Wen、Xuemeng Yang、Shu Zou 等（共 13 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-07-30T14:25:49Z |
| **关键词** | `LLM Agent` · `Reasoning` · `Memory` |
| **原文链接** | [http://arxiv.org/abs/2607.28272v1](http://arxiv.org/abs/2607.28272v1) |

**📝 摘要概括：**

> 检索过去的经验已成为增强大型语言模型代理的常用策略。但是，大多数现有的记忆增强客服代表将检索到的体验视为要逐字重播的静态记录，将它们注入上下文，无论它们是否与客服代表的当前情况一致。此外，我们的分析显示，这种重建目标不仅可以防止负转移，还可以作为潜在的指南......

</details>

<details>
<summary><b>15. Agentic Method for Deterministic Validation of Legacy Code Migration</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Andras Ferenczi、Jordan Docherty、Mariya Bessonov、Matthew Findlay、Krishna Lingamneni |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、CAS |
| **发布时间** | 2026-07-30T14:25:23Z |
| **关键词** | `Agentic` · `RAG` |
| **原文链接** | [http://arxiv.org/abs/2607.28271v1](http://arxiv.org/abs/2607.28271v1) |

**📝 摘要概括：**

> 将旧版COBOL程序迁移到Java需要进行广泛的测试，以确保正确的功能。由于缺乏测试数据以及难以验证所有转折点案例，这项工作通常会变得复杂。通过这些发现，据我们所知，我们展示了一种使用确定性预言机验证代理编码输出的新方法。

</details>

<details>
<summary><b>16. Agentic Metaverse Services: A New As-a-Service Paradigm</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Xiaofei Xu、Quan Z. Sheng、Zhongjie Wang、Boualem Benatallah、Xiao Wang 等（共 6 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-07-30T14:06:23Z |
| **关键词** | `Agentic` |
| **原文链接** | [http://arxiv.org/abs/2607.28242v1](http://arxiv.org/abs/2607.28242v1) |

**📝 摘要概括：**

> 生成人工智能（ GenAI ）正在重建数字虚拟世界，通过提高智能体在自主学习、多模态交互、内容生成和协作决策方面的能力来升级智能体。特别是，从对话式聊天机器人到智能人工智能的转变，这是GenAI最新的重大技术突破，带来了一种新形式的服务、智能服务和代理即服务（ ……

</details>

<details>
<summary><b>17. EMBL AI Librarian: Life-Sciences Knowledge Layer for AI Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Luigi Sigillo、Matteo Silvestri、Francesco Tabaro、Rajat Bhatnagar、Syed Irtaza Mubashar 等（共 12 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-07-30T14:00:27Z |
| **关键词** | `AI Agent` · `Agentic` · `Retrieval` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2607.28229v1](http://arxiv.org/abs/2607.28229v1) |

**📝 摘要概括：**

> 网络越来越多地被人工智能代理而不是人类访问。每个代理都需要知识，特别是在生命科学领域，代理渠道正在快速增长。我们在https://github.com/petroni-lab/librarian上公开发布我们的代码

</details>

<details>
<summary><b>18. Qwen-UI-Agent Technical Report: Toward Next-Generation Real-World Centric Foundation GUI Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Hanzhang Zhou、Panrong Tong、Xu Zhang、Quyu Kong、Chenglin Cai 等（共 16 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-07-30T13:58:41Z |
| **关键词** | `Benchmark` · `Evaluation` · `Workflow` |
| **原文链接** | [http://arxiv.org/abs/2607.28227v1](http://arxiv.org/abs/2607.28227v1) |

**📝 摘要概括：**

> GUI代理有可能成为现有数字设备的通用执行者。为了推动它们在现实世界中的使用，我们设想了在真实设备上可靠运行的代理，跨平台执行工作流程，将GUI交互与CLI执行相结合，完成长时间任务，主动启动有用的服务，并以最少的人力自主提高自身能力。在浏览器使用和GUI接地方面，它……

</details>

<details>
<summary><b>19. Vibe-FDTR: An agent-oriented framework for reproducible frequency-domain thermoreflectance data analysis</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Fuwei Yang、Weiheng Li、Bai Song |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、HIT、TRI |
| **发布时间** | 2026-07-30T13:38:13Z |
| **关键词** | `Planning` · `Benchmark` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2607.28200v1](http://arxiv.org/abs/2607.28200v1) |

**📝 摘要概括：**

> 频域温度反射率（ FDTR ）是一种激光泵浦探针技术，广泛用于测量微观和纳米尺度的热特性；然而，它依赖于复杂的数据分析过程，需要大量的领域专业知识，并且容易出现微妙的人为错误。在这里，我们展示了Vibe-FDTR ，这是一个面向代理的框架，使大型语言模型（ LLM ）代理能够直接执行可靠且可重复的FDTR分析……

</details>

<details>
<summary><b>20. Integrating AI into Requirements Quality Learning in Software Engineering Education: A TPACK-Guided Empirical Study</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Hansika Ekanayake Mudiyanselage、Rohan Jai Dharmaraj、Malik Abdul Sami、Zheying Zhang |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT |
| **发布时间** | 2026-07-30T13:15:16Z |
| **关键词** | `Multi-Agent` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2607.28176v1](http://arxiv.org/abs/2607.28176v1) |

**📝 摘要概括：**

> 在软件工程（ SE ）实践中快速采用生成式人工智能（ AI ） ，需要在SE教育中采用基于教学的人工智能集成方法，特别是在需求工程（ RE ）等概念密集型学科中。本研究考察了TPACK引导的多代理AI工具集成到需求质量分析的主级RE分配中。研究结果表明， TPACK引导的…

</details>

## 🗄️ 历史归档

| 日期 | 论文数 | 报告链接 |
|------|--------|----------|
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
| 2026-07-06 | 0 篇 | [2026-07-06.md](daily/2026-07-06.md) |
| 2026-07-05 | 0 篇 | [2026-07-05.md](daily/2026-07-05.md) |
| 2026-07-04 | 0 篇 | [2026-07-04.md](daily/2026-07-04.md) |
| 2026-07-03 | 20 篇 | [2026-07-03.md](daily/2026-07-03.md) |
| 2026-07-02 | 0 篇 | [2026-07-02.md](daily/2026-07-02.md) |
| 2026-07-01 | 0 篇 | [2026-07-01.md](daily/2026-07-01.md) |

## 🏛️ 顶级机构覆盖范围

覆盖超过 **70 个**顶级 AI 机构，包括：

- **科技公司：** Microsoft、Google DeepMind、OpenAI、Anthropic、Meta AI、NVIDIA、Baidu、Alibaba、ByteDance 等
- **北美顶级大学：** MIT、Stanford、CMU、UC Berkeley、Harvard、Princeton、Cornell、Caltech 等
- **中国顶级大学/机构：** 清华大学、北京大学、浙大、上交大、复旦、中科院、MSRA 等
- **欧洲/其他：** Oxford、Cambridge、ETH Zurich、Mila、NUS、KAIST 等

---

*由 [clawBot DailyFindings](https://github.com/Jacob-biu/clawBot) 自动维护 | 最后更新：2026-07-31 22:59 UTC*
