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

## 📅 今日论文 — 2026-10-01　　[→ 查看完整报告](daily/2026-10-01.md)

> 共筛选出 **20** 篇论文 | 更新于 2026-10-01 01:08 UTC

### 论文目录与概要

| # | 论文标题 | 核心概要 | 来源机构 | 第一作者 |
|---|---------|---------|---------|--------|
| 1 | [Beyond the Remembered World: Predictive 4D Belief for Persis…](http://arxiv.org/abs/2609.39166v1) | 持久的空间记忆使具体的座席能够在重复访问中导航熟悉的环境。但是，目标可能会在不被观察的情况下移动，包括在导航期间，这使得在客服代表到达时记住的位置不可靠。配对实验表明，在可学习的时间模式下获得了最明显… | MIT、CAS | Mingjian Gao |
| 2 | [DAGent: Evaluate-then-Grow Planning for Deep Research Agents](http://arxiv.org/abs/2609.39154v1) | 深度研究任务要求代理人在大型知识空间中导航，综合许多来源的证据，并在发现时调整他们的计划。基于定向非循环图(DAG)的多代理系统适合此设置，因为它们支持并行执行，并将每个子任务隔离在重点依赖关系上下文… | MIT、HIT | Hanwen Liu |
| 3 | [Do Self-Evolving Skills Generalize to Held-Out Tasks?](http://arxiv.org/abs/2609.39148v1) | 人工智能代理可以将他们从过去的任务中学到的东西外化为可重用的\ emph {skills} ，例如过程、清单、代码或其他可执行工件，这些工件可以在解决新任务时检索和重复使用。自我进化的技能方法在训练任… | TRI | Xihao Piao |
| 4 | [MADBench: Benchmarking the Security of Multi-Agent Debate](http://arxiv.org/abs/2609.39146v1) | 多代理辩论（ MAD ）可以通过允许多个代理交换和批评他们对同一任务的答案来改进大语言模型（ LLM ）推理。但是，使客服代表能够纠正错误的互动也可能会传播对抗性错误，并引导客服代表找到错误的答案。此… | MIT、CAS | Yuwan Liu |
| 5 | [Schema: Discovering Unknown Environments via Agentic Program…](http://arxiv.org/abs/2609.39140v1) | 学习在规则未知的陌生环境中完成任务仍然是LLM代理面临的关键挑战。目前的LLM代理人经常将他们的发现记录在散文中，这可能无法提供关于环境如何工作的紧凑，明确的描述。广泛的分析表明了Schema在未知机… | TRI | Guanning Zeng |
| 6 | [Characterizing High Bandwidth Flash for LLM Serving](http://arxiv.org/abs/2609.39131v1) | 大型语言模型（ LLM ）服务需要大量内存来存储模型权重和KV缓存。随着模型越来越大，上下文越来越长，内存容量和带宽越来越成为提供性能的瓶颈。这些结果证明了协调数据放置和调度的重要性，以提高服务效率，… | MIT | Zack Yu |
| 7 | [MASCRDM: Multi-Agent System for Compliance Risk Detection an…](http://arxiv.org/abs/2609.39107v1) | 大型语言模型（ LLM ）已应用于各个领域。然而，确保LLM的合规性和安全性，例如避免歧视和偏见，仍然是一个挑战。结果表明，我们的方法为系统地降低LLM内的合规风险提供了可执行路径。 | MIT、HIT | Yan Zhang |
| 8 | [False Frontiers: Diagnosing and Mitigating Co-Cheating in Se…](http://arxiv.org/abs/2609.39102v1) | 自我进化的搜索代理通过联合优化生成问题的提案者和回答问题的解决者来构建自己的培训课程。这种闭环引入了一种我们称之为共同作弊的故障模式：提议者和求解者越来越多地就共享错误达成一致，因此内部奖励在没有外部… | MIT | Meijia Chen |
| 9 | [Beyond Prediction: Steering VLM Agents with Retrospective Wo…](http://arxiv.org/abs/2609.39101v1) | 为VLM代理配备世界建模能力显示了复杂推理和长远规划的巨大潜力，同时减少了策略学习对昂贵的现实世界交互的依赖。现有方法主要依靠前瞻性模拟来预测求职者行为的后果。对不同代理任务的广泛实验表明，我们的方法… | MIT、TRI | Yongjiang Liu |
| 10 | [Trustworthy Runtime Error Healing in Real-World Repositories…](http://arxiv.org/abs/2609.39086v1) | 运行时错误修复通过生成修复其实时运行时状态的代码，允许崩溃的程序继续运行。最近的工作表明， LLM可以生成此类愈合代码，但仅在小型竞争计划中对其进行评估，并且在实时流程中执行LLM生成的代码会引发尚未… | CAS | Gou Tan |
| 11 | [Coding Agents for Coding Theory](http://arxiv.org/abs/2609.39081v1) | 我们花了五个星期的时间使用LLM编码代理来解决编码理论中的开放性问题：找到大量四个字母的单词，例如DNA条形码，它们在编辑距离上保持很远的距离。客服代表撰写了验证码和搜索代码；人类选择了问题并设置了验… | TRI | Abraham Yeung |
| 12 | [Can Agents Trust Their Skills? Uncovering Unsafe Chains of T…](http://arxiv.org/abs/2609.39065v1) | LLM代理越来越依赖可安装的技能，这些技能是指令、代码和资源包，它们具有特定于任务的功能，安装后可以在后续用户任务中自动调用。这创建了一个信任链，其中用户将权限委托给代理，而代理框架在验证不充分的情况… | MIT、TRI | Yan Wang |
| 13 | [RSIGame: Autonomous Agentic Game Development with Recursive …](http://arxiv.org/abs/2609.39045v1) | 大型语言模型的最新进展使自动游戏生成变得越来越可行，但除了可玩版本之外，可靠地改进生成的游戏仍然具有挑战性。朴素的迭代细化可以很容易地过度适应一小部分测试用例，从而产生脆弱的游戏，其中存在未解决的错误… | CAS | Wenyi Wu |
| 14 | [From Verification Failures to Reusable Guidance for Coding A…](http://arxiv.org/abs/2609.39022v1) | 编码代理需要确定程序满足规范，并且规范捕获了所请求的行为。我们研究了验证失败的专家诊断如何成为这项工作的可重复使用的指南。我们向交付具有可检查正确性论点的计划的客服代表报告进度、困难和教训。 | MIT | Yuqing Zhai |
| 15 | [The Invisible Language Tax: Token Premiums of French and Reg…](http://arxiv.org/abs/2609.39001v1) | LLM服务按令牌计费，上下文窗口以令牌衡量，但相同内容所需的令牌数量因语言而异。我们通过NTREX-128 （ 124种非英语参考翻译）和Universal De…上广泛使用的2026型号的七个令牌生… | OpenAI、Anthropic | Thomas Serval |
| 16 | [SimEX: Simulation-Integrated Robotics AutoResearch](http://arxiv.org/abs/2609.38982v1) | 由大型语言模型（ LLM ）提供支持的编码代理已显示出在数字世界中自主推理和实现目标的非凡能力。然而，将这种成功带入现实世界仍然具有挑战性。更多详情和机器人视频，请访问https://robo-sim… | TRI | Jiaheng Hu |
| 17 | [RealWorldShop: Benchmarking and Improving Conversational Sho…](http://arxiv.org/abs/2609.38974v1) | 大型语言模型正在将电子商务从静态推荐者重塑为交互式购物助手，但现实世界的购物需要会话级决策支持：用户揭示和修改约束，协调多个目标，并期望在完整的对话中获得基于产品的建议。现有的基准大多是以结果为导向或… | TRI | Xinwei Yang |
| 18 | [When Order Matters: First-Speaker Bias and Mitigation throug…](http://arxiv.org/abs/2609.38964v1) | 多代理辩论（ MAD ）通常用于改进大语言模型（ LLM ）推理，但顺序辩论很少是代理意见的中性聚合器。我们表明，连续性MAD存在明显的第一说话者偏见：代理人在第一次说话时会不成比例地塑造最终答案。这… | MIT | Duofeng Xu |
| 19 | [APTInvestBench: Evaluating Autonomous APT Investigation unde…](http://arxiv.org/abs/2609.38954v1) | 大型语言模型（ LLM ）代理可以通过将弱线索转化为入侵范围和响应的证据，帮助安全运营中心（ SOC ）调查高级持续威胁（ APT ）。然而，在一个遥测设置下成功并不能建立对日志收集、保留或采样变化的… | MIT、CAS | Yu Wang |
| 20 | [Risk-Aware Adaptive Evaluation: Finding High-Impact Failures…](http://arxiv.org/abs/2609.38914v1) | 评估交互式座席的成本很高。客服代表的行为是随机的，因此必须通过重复试验来衡量可靠性，但失败的情况很少见，而且失败的重要性差异很大。因此，具有风险意识的适应性分配有助于最准确地确定评估预算最稀缺的地方。 | TRI | Priyanath Maji |

### 论文详情

<details>
<summary><b>1. Beyond the Remembered World: Predictive 4D Belief for Persistent Navigation in Evolving Worlds</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Mingjian Gao、Zhaocheng Li、Haoyang Huang、Wenqiao Zhang、Yingjie Niu 等（共 10 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、CAS、TRI |
| **发布时间** | 2026-09-30T07:26:36Z |
| **关键词** | `Retrieval` · `Benchmark` · `Simulation` · `Embodied AI` · `Memory` |
| **原文链接** | [http://arxiv.org/abs/2609.39166v1](http://arxiv.org/abs/2609.39166v1) |

**📝 摘要概括：**

> 持久的空间记忆使具体的座席能够在重复访问中导航熟悉的环境。但是，目标可能会在不被观察的情况下移动，包括在导航期间，这使得在客服代表到达时记住的位置不可靠。配对实验表明，在可学习的时间模式下获得了最明显的收益，而消融证明了保持不确定性和纳入可见性感知证据的价值。

</details>

<details>
<summary><b>2. DAGent: Evaluate-then-Grow Planning for Deep Research Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Hanwen Liu、Yuanfu Sun、Qiaoyu Tan |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、HIT |
| **发布时间** | 2026-09-30T07:19:01Z |
| **关键词** | `Multi-Agent` · `Planning` · `RAG` |
| **原文链接** | [http://arxiv.org/abs/2609.39154v1](http://arxiv.org/abs/2609.39154v1) |

**📝 摘要概括：**

> 深度研究任务要求代理人在大型知识空间中导航，综合许多来源的证据，并在发现时调整他们的计划。基于定向非循环图(DAG)的多代理系统适合此设置，因为它们支持并行执行，并将每个子任务隔离在重点依赖关系上下文中。代码： https://github.com/hanwenliu6825/DAGent

</details>

<details>
<summary><b>3. Do Self-Evolving Skills Generalize to Held-Out Tasks?</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Xihao Piao、Zifeng Wang、Zhen Chen |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-09-30T07:14:35Z |
| **关键词** | `AI Agent` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2609.39148v1](http://arxiv.org/abs/2609.39148v1) |

**📝 摘要概括：**

> 人工智能代理可以将他们从过去的任务中学到的东西外化为可重用的\ emph {skills} ，例如过程、清单、代码或其他可执行工件，这些工件可以在解决新任务时检索和重复使用。自我进化的技能方法在训练任务的每一轮练习后不断重写这些技能，然后将该技能用于相同类型的新任务。基于这些发现，我们描述了广义技能优化（ GSO ） ……

</details>

<details>
<summary><b>4. MADBench: Benchmarking the Security of Multi-Agent Debate</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Yuwan Liu、Jiaming Zhang、Yue Huang、Sisi Duan |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、CAS |
| **发布时间** | 2026-09-30T07:12:59Z |
| **关键词** | `Multi-Agent` · `Reasoning` · `Benchmark` · `Evaluation` · `Workflow` |
| **原文链接** | [http://arxiv.org/abs/2609.39146v1](http://arxiv.org/abs/2609.39146v1) |

**📝 摘要概括：**

> 多代理辩论（ MAD ）可以通过允许多个代理交换和批评他们对同一任务的答案来改进大语言模型（ LLM ）推理。但是，使客服代表能够纠正错误的互动也可能会传播对抗性错误，并引导客服代表找到错误的答案。此外，即使五分之三的智能体相互串通，攻击也仅在28.30\ %的任务中将最终答案从正确改为错误……

</details>

<details>
<summary><b>5. Schema: Discovering Unknown Environments via Agentic Program Induction</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Guanning Zeng、Jiani Wang、Wenjie Ma、Shaofeng Yin、Chenyang Wang 等（共 11 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-09-30T07:08:31Z |
| **关键词** | `LLM Agent` · `Agentic` · `Planning` |
| **原文链接** | [http://arxiv.org/abs/2609.39140v1](http://arxiv.org/abs/2609.39140v1) |

**📝 摘要概括：**

> 学习在规则未知的陌生环境中完成任务仍然是LLM代理面临的关键挑战。目前的LLM代理人经常将他们的发现记录在散文中，这可能无法提供关于环境如何工作的紧凑，明确的描述。广泛的分析表明了Schema在未知机制发现中的有效性，消融确认了每个组件的贡献。

</details>

<details>
<summary><b>6. Characterizing High Bandwidth Flash for LLM Serving</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Zack Yu、Chloe Wong、Coleman Hooper、Minjae Lee、Wonjun Kang 等（共 10 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT |
| **发布时间** | 2026-09-30T07:02:56Z |
| **关键词** | `Agentic` · `RAG` · `Simulation` · `Memory` |
| **原文链接** | [http://arxiv.org/abs/2609.39131v1](http://arxiv.org/abs/2609.39131v1) |

**📝 摘要概括：**

> 大型语言模型（ LLM ）服务需要大量内存来存储模型权重和KV缓存。随着模型越来越大，上下文越来越长，内存容量和带宽越来越成为提供性能的瓶颈。这些结果证明了协调数据放置和调度的重要性，以提高服务效率，同时保持实际的HBF写入寿命。

</details>

<details>
<summary><b>7. MASCRDM: Multi-Agent System for Compliance Risk Detection and Mitigation in Training Process of Large Language Models</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Yan Zhang、Chuming Wei、Ruien Li、Yaoyao Peng、Wusheng Zhang 等（共 6 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、HIT、TRI |
| **发布时间** | 2026-09-30T06:47:05Z |
| **关键词** | `Multi-Agent` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2609.39107v1](http://arxiv.org/abs/2609.39107v1) |

**📝 摘要概括：**

> 大型语言模型（ LLM ）已应用于各个领域。然而，确保LLM的合规性和安全性，例如避免歧视和偏见，仍然是一个挑战。结果表明，我们的方法为系统地降低LLM内的合规风险提供了可执行路径。

</details>

<details>
<summary><b>8. False Frontiers: Diagnosing and Mitigating Co-Cheating in Self-Evolving Search Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Meijia Chen、Hao Li、Zheng Lu、Hongshan Lin、Junbai Tian 等（共 15 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT |
| **发布时间** | 2026-09-30T06:41:51Z |
| **关键词** | `RAG` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2609.39102v1](http://arxiv.org/abs/2609.39102v1) |

**📝 摘要概括：**

> 自我进化的搜索代理通过联合优化生成问题的提案者和回答问题的解决者来构建自己的培训课程。这种闭环引入了一种我们称之为共同作弊的故障模式：提议者和求解者越来越多地就共享错误达成一致，因此内部奖励在没有外部正确性匹配增益的情况下得到改善。在七个下游搜索基准中， CrossFit的平均性能优于标准……

</details>

<details>
<summary><b>9. Beyond Prediction: Steering VLM Agents with Retrospective World Modeling</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Yongjiang Liu、Jie Zhang、Haoyue Zhang、Jingcai Guo、Deze Zeng 等（共 6 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-09-30T06:41:04Z |
| **关键词** | `Agentic` · `Reasoning` · `Planning` · `Reinforcement Learning` · `Simulation` |
| **原文链接** | [http://arxiv.org/abs/2609.39101v1](http://arxiv.org/abs/2609.39101v1) |

**📝 摘要概括：**

> 为VLM代理配备世界建模能力显示了复杂推理和长远规划的巨大潜力，同时减少了策略学习对昂贵的现实世界交互的依赖。现有方法主要依靠前瞻性模拟来预测求职者行为的后果。对不同代理任务的广泛实验表明，我们的方法大大提高了策略的鲁棒性和泛化性……

</details>

<details>
<summary><b>10. Trustworthy Runtime Error Healing in Real-World Repositories: A Benchmark and Guardrail</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Gou Tan、Pengfei Chen、Zhensu Sun、Jieke Shi、Junkai Chen 等（共 12 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | CAS |
| **发布时间** | 2026-09-30T06:26:07Z |
| **关键词** | `LLM Agent` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2609.39086v1](http://arxiv.org/abs/2609.39086v1) |

**📝 摘要概括：**

> 运行时错误修复通过生成修复其实时运行时状态的代码，允许崩溃的程序继续运行。最近的工作表明， LLM可以生成此类愈合代码，但仅在小型竞争计划中对其进行评估，并且在实时流程中执行LLM生成的代码会引发尚未解决的安全问题。在684例对照病例中， HealGuard检测到所有不安全病例，误报率为68.42%。

</details>

<details>
<summary><b>11. Coding Agents for Coding Theory</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Abraham Yeung |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-09-30T06:17:28Z |
| **关键词** | — |
| **原文链接** | [http://arxiv.org/abs/2609.39081v1](http://arxiv.org/abs/2609.39081v1) |

**📝 摘要概括：**

> 我们花了五个星期的时间使用LLM编码代理来解决编码理论中的开放性问题：找到大量四个字母的单词，例如DNA条形码，它们在编辑距离上保持很远的距离。客服代表撰写了验证码和搜索代码；人类选择了问题并设置了验证协议。根据我们的协议要求，检查最终输出不会捕获此类错误。

</details>

<details>
<summary><b>12. Can Agents Trust Their Skills? Uncovering Unsafe Chains of Trust in Skill-Based LLM Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Yan Wang、Zhihao Zhang、Ke Chen、Kai Chen、Yaqin Zhang 等（共 8 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-09-30T06:04:44Z |
| **关键词** | `LLM Agent` |
| **原文链接** | [http://arxiv.org/abs/2609.39065v1](http://arxiv.org/abs/2609.39065v1) |

**📝 摘要概括：**

> LLM代理越来越依赖可安装的技能，这些技能是指令、代码和资源包，它们具有特定于任务的功能，安装后可以在后续用户任务中自动调用。这创建了一个信任链，其中用户将权限委托给代理，而代理框架在验证不充分的情况下将技能提供的内容承认到代理的上下文中，从而允许恶意技能提供信息……

</details>

<details>
<summary><b>13. RSIGame: Autonomous Agentic Game Development with Recursive Self-improvement</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Wenyi Wu、Minghao Fu、Jieyu You、Kun Zhou、Siqi Liu 等（共 13 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | CAS |
| **发布时间** | 2026-09-30T05:54:34Z |
| **关键词** | `Agentic` · `RAG` |
| **原文链接** | [http://arxiv.org/abs/2609.39045v1](http://arxiv.org/abs/2609.39045v1) |

**📝 摘要概括：**

> 大型语言模型的最新进展使自动游戏生成变得越来越可行，但除了可玩版本之外，可靠地改进生成的游戏仍然具有挑战性。朴素的迭代细化可以很容易地过度适应一小部分测试用例，从而产生脆弱的游戏，其中存在未解决的错误、缺失的行为以及对更广泛的玩家交互的不良泛化。值得注意的是，经验内化使Qwen3.8-27B达到61.38…

</details>

<details>
<summary><b>14. From Verification Failures to Reusable Guidance for Coding Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Yuqing Zhai、Xiaohong Chen、Lingming Zhang、Sriram Vishwanath、Grigore Rosu |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT |
| **发布时间** | 2026-09-30T05:27:26Z |
| **关键词** | `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2609.39022v1](http://arxiv.org/abs/2609.39022v1) |

**📝 摘要概括：**

> 编码代理需要确定程序满足规范，并且规范捕获了所请求的行为。我们研究了验证失败的专家诊断如何成为这项工作的可重复使用的指南。我们向交付具有可检查正确性论点的计划的客服代表报告进度、困难和教训。

</details>

<details>
<summary><b>15. The Invisible Language Tax: Token Premiums of French and Regional Languages in 2026 LLM Tokenizers, and a French-Optimized Prototype</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Thomas Serval |
| **所属机构** | （详见原文） |
| **顶级机构标签** | OpenAI、Anthropic |
| **发布时间** | 2026-09-30T05:14:43Z |
| **关键词** | `Agentic` |
| **原文链接** | [http://arxiv.org/abs/2609.39001v1](http://arxiv.org/abs/2609.39001v1) |

**📝 摘要概括：**

> LLM服务按令牌计费，上下文窗口以令牌衡量，但相同内容所需的令牌数量因语言而异。我们通过NTREX-128 （ 124种非英语参考翻译）和Universal De…上广泛使用的2026型号的七个令牌生成器（ OpenAI o200k、Llama 3、Qwen3、DeepSeek V3/V4、Gemma 3、Mistral Tekken和通过Anthropic的计数API的Claude generation-5令牌生成器）来衡量此令牌溢价。

</details>

<details>
<summary><b>16. SimEX: Simulation-Integrated Robotics AutoResearch</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Jiaheng Hu、Roberto Martin-Martin、Peter Stone、Rocky Duan、Zhenyu Jiang 等（共 6 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-09-30T04:58:21Z |
| **关键词** | `Simulation` · `Robotics` |
| **原文链接** | [http://arxiv.org/abs/2609.38982v1](http://arxiv.org/abs/2609.38982v1) |

**📝 摘要概括：**

> 由大型语言模型（ LLM ）提供支持的编码代理已显示出在数字世界中自主推理和实现目标的非凡能力。然而，将这种成功带入现实世界仍然具有挑战性。更多详情和机器人视频，请访问https://robo-simex.github.io/

</details>

<details>
<summary><b>17. RealWorldShop: Benchmarking and Improving Conversational Shopping Agents in Real-World E-commerce</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Xinwei Yang、Kelong Mao、Yudong Guo、Sulong Xu、Simiu Gu 等（共 7 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-09-30T04:49:10Z |
| **关键词** | `Retrieval` · `Benchmark` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2609.38974v1](http://arxiv.org/abs/2609.38974v1) |

**📝 摘要概括：**

> 大型语言模型正在将电子商务从静态推荐者重塑为交互式购物助手，但现实世界的购物需要会话级决策支持：用户揭示和修改约束，协调多个目标，并期望在完整的对话中获得基于产品的建议。现有的基准大多是以结果为导向或以执行为导向的，这使得这个不断发展的决策过程被低估了。实验sho…

</details>

<details>
<summary><b>18. When Order Matters: First-Speaker Bias and Mitigation through Personality in Sequential Multi-Agent Debate</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Duofeng Xu、Bryan Hooi、Dandan Qiao |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT |
| **发布时间** | 2026-09-30T04:33:46Z |
| **关键词** | `Multi-Agent` · `Reasoning` |
| **原文链接** | [http://arxiv.org/abs/2609.38964v1](http://arxiv.org/abs/2609.38964v1) |

**📝 摘要概括：**

> 多代理辩论（ MAD ）通常用于改进大语言模型（ LLM ）推理，但顺序辩论很少是代理意见的中性聚合器。我们表明，连续性MAD存在明显的第一说话者偏见：代理人在第一次说话时会不成比例地塑造最终答案。这些研究结果表明，有效的MAD设计不仅取决于模型能力，还取决于说话顺序和诱导互动的行为方式。

</details>

<details>
<summary><b>19. APTInvestBench: Evaluating Autonomous APT Investigation under Varying Telemetry</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Yu Wang、Shuhao Li、Tao Yin、Ziyang Li、Xueying Zhao 等（共 7 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、CAS |
| **发布时间** | 2026-09-30T04:21:45Z |
| **关键词** | `RAG` · `Benchmark` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2609.38954v1](http://arxiv.org/abs/2609.38954v1) |

**📝 摘要概括：**

> 大型语言模型（ LLM ）代理可以通过将弱线索转化为入侵范围和响应的证据，帮助安全运营中心（ SOC ）调查高级持续威胁（ APT ）。然而，在一个遥测设置下成功并不能建立对日志收集、保留或采样变化的鲁棒性。APTInvestBench提供可重复使用的调查环境和诊断评估，以识别这些差距并开发……

</details>

<details>
<summary><b>20. Risk-Aware Adaptive Evaluation: Finding High-Impact Failures Under Limited Budgets</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Priyanath Maji、Spandan Ghose Chowdhury |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-09-30T04:00:14Z |
| **关键词** | `Benchmark` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2609.38914v1](http://arxiv.org/abs/2609.38914v1) |

**📝 摘要概括：**

> 评估交互式座席的成本很高。客服代表的行为是随机的，因此必须通过重复试验来衡量可靠性，但失败的情况很少见，而且失败的重要性差异很大。因此，具有风险意识的适应性分配有助于最准确地确定评估预算最稀缺的地方。

</details>

## 🗄️ 历史归档

| 日期 | 论文数 | 报告链接 |
|------|--------|----------|
| 2026-10-01 | 20 篇 | [2026-10-01.md](daily/2026-10-01.md) |
| 2026-09-30 | 8 篇 | [2026-09-30.md](daily/2026-09-30.md) |
| 2026-09-29 | 0 篇 | [2026-09-29.md](daily/2026-09-29.md) |
| 2026-09-15 | 16 篇 | [2026-09-15.md](daily/2026-09-15.md) |
| 2026-09-13 | 0 篇 | [2026-09-13.md](daily/2026-09-13.md) |
| 2026-09-12 | 0 篇 | [2026-09-12.md](daily/2026-09-12.md) |
| 2026-09-11 | 0 篇 | [2026-09-11.md](daily/2026-09-11.md) |
| 2026-09-10 | 8 篇 | [2026-09-10.md](daily/2026-09-10.md) |
| 2026-09-09 | 12 篇 | [2026-09-09.md](daily/2026-09-09.md) |
| 2026-09-08 | 0 篇 | [2026-09-08.md](daily/2026-09-08.md) |
| 2026-09-07 | 0 篇 | [2026-09-07.md](daily/2026-09-07.md) |
| 2026-09-06 | 0 篇 | [2026-09-06.md](daily/2026-09-06.md) |
| 2026-09-05 | 0 篇 | [2026-09-05.md](daily/2026-09-05.md) |
| 2026-09-04 | 20 篇 | [2026-09-04.md](daily/2026-09-04.md) |
| 2026-09-03 | 6 篇 | [2026-09-03.md](daily/2026-09-03.md) |
| 2026-09-02 | 20 篇 | [2026-09-02.md](daily/2026-09-02.md) |
| 2026-09-01 | 20 篇 | [2026-09-01.md](daily/2026-09-01.md) |
| 2026-08-31 | 0 篇 | [2026-08-31.md](daily/2026-08-31.md) |
| 2026-08-29 | 0 篇 | [2026-08-29.md](daily/2026-08-29.md) |
| 2026-08-28 | 20 篇 | [2026-08-28.md](daily/2026-08-28.md) |
| 2026-08-27 | 20 篇 | [2026-08-27.md](daily/2026-08-27.md) |
| 2026-08-25 | 12 篇 | [2026-08-25.md](daily/2026-08-25.md) |
| 2026-08-24 | 0 篇 | [2026-08-24.md](daily/2026-08-24.md) |
| 2026-08-23 | 0 篇 | [2026-08-23.md](daily/2026-08-23.md) |
| 2026-08-22 | 0 篇 | [2026-08-22.md](daily/2026-08-22.md) |
| 2026-08-21 | 15 篇 | [2026-08-21.md](daily/2026-08-21.md) |
| 2026-08-20 | 13 篇 | [2026-08-20.md](daily/2026-08-20.md) |
| 2026-08-19 | 17 篇 | [2026-08-19.md](daily/2026-08-19.md) |
| 2026-08-18 | 20 篇 | [2026-08-18.md](daily/2026-08-18.md) |
| 2026-08-17 | 0 篇 | [2026-08-17.md](daily/2026-08-17.md) |

## 🏛️ 顶级机构覆盖范围

覆盖超过 **70 个**顶级 AI 机构，包括：

- **科技公司：** Microsoft、Google DeepMind、OpenAI、Anthropic、Meta AI、NVIDIA、Baidu、Alibaba、ByteDance 等
- **北美顶级大学：** MIT、Stanford、CMU、UC Berkeley、Harvard、Princeton、Cornell、Caltech 等
- **中国顶级大学/机构：** 清华大学、北京大学、浙大、上交大、复旦、中科院、MSRA 等
- **欧洲/其他：** Oxford、Cambridge、ETH Zurich、Mila、NUS、KAIST 等

---

*由 [clawBot DailyFindings](https://github.com/Jacob-biu/clawBot) 自动维护 | 最后更新：2026-10-01 01:08 UTC*
