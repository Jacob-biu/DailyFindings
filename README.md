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

## 📅 今日论文 — 2026-06-24　　[→ 查看完整报告](daily/2026-06-24.md)

> 共筛选出 **9** 篇论文 | 更新于 2026-06-24 23:06 UTC

### 论文目录与概要

| # | 论文标题 | 核心概要 | 来源机构 | 第一作者 |
|---|---------|---------|---------|--------|
| 1 | [OpenThoughts-Agent: Data Recipes for Agentic Models](http://arxiv.org/abs/2606.24855v1) | Agentic语言模型极大地扩展了人工智能的应用，但公众对如何为具有广泛能力的代理人策划培训数据知之甚少。现有的开放性工作，如SWE-Smith、SERA和Nemotron-Terminal ，通常针… | MIT | Negin Raoof |
| 2 | [World Models in Pieces: Structural Certification for General…](http://arxiv.org/abs/2606.24842v1) | 在大世界政权中，智能体不可能具有普遍的能力，他们的能力不可避免地分散在世界模型中。因此，标准统一保证无法区分对关键瓶颈的理解和不相关故障。这些结果通过本地化长期规划可靠的特定过渡，使一般代理能够进行可… | MIT、CAS | Yikai Lu |
| 3 | [Grading the Grader: Lessons from Evaluating an Agentic Data …](http://arxiv.org/abs/2606.24839v1) | 代理数据分析系统产生丰富的输出，包括代码、数值结果和口头诊断。这使得他们比单轮法学硕士的回答更难评估。我们在本案例研究中进一步观察到，变量类型是与流水线动态分级和观察结果分级最一致的任务元数据字段。 | HIT、CAS | Tian Zheng |
| 4 | [Paying to Know: Micro-Transaction Markets for Verified Produ…](http://arxiv.org/abs/2606.24783v1) | 商业NLP将购物聊天机器人视为推荐者或转换工具：其工作是将用户与目录条目匹配并完成销售。我们认为，代理原生微支付轨道的到来（例如， x402、AP2 ）改变了稀缺的东西。然后，我们将愿景转化为具体的自… | HIT、TRI | Filippos Ventirozos |
| 5 | [DeepBD: A Grounded Agentic Workflow for Variant Prioritizati…](http://arxiv.org/abs/2606.24779v1) | 出生缺陷是导致胎儿流失、新生儿发病和长期残疾的主要原因。在可疑遗传病因的亚组中，外显子组和基因组测序将许多病例从变异检测转移到测序后解释：临床医生必须将患者特异性候选变异在不完整的胎儿或婴儿表型和来自… | CAS | Shiyu Li |
| 6 | [SAFARI: Scaling Long Horizon Agentic Fault Attribution via A…](http://arxiv.org/abs/2606.24626v1) | 随着自治代理处理日益复杂的多步骤、多代理任务，它们的执行轨迹已经超出了即使是最大的上下文窗口的限制。当前有效诊断代理失败的方法将完整轨迹加载到LLM的上下文窗口中，该窗口存在注意力稀释问题，并且当代理… | MIT、HIT | Chenyang Zhu |
| 7 | [Privacy-Preserving RAG via Multi-Agent Semantic Rewriting: A…](http://arxiv.org/abs/2606.24623v1) | 检索增强生成通过整合外部知识来增强大型语言模型，但在敏感场景中部署它可能会通过恶意提示泄露隐私。为了解决这个问题，我们提出了一个多代理框架，通过语义重写对检索到的内容进行净化。为了提高可重复性，本作品… | TRI | Yuanhe Zhao |
| 8 | [ASALT: Adaptive State Alignment for Lateral Transfer in Mult…](http://arxiv.org/abs/2606.24601v1) | 多代理强化学习(MARL)解决了培训追求协作、竞争或混合目标的多代理的问题。先前的工作研究了MARL中源域和目标域之间的迁移学习；然而，大多数现有方法都施加了观测空间和全局状态空间的维度必须在不同域之… | MIT | Anurag Akula |
| 9 | [Governed Shared Memory for Multi-Agent LLM Systems](http://arxiv.org/abs/2606.24535v1) | 多代理LLM环境需要强大的知识共享管理机制。本文形式化了车队记忆问题，并确定了四种基本的故障模式：未经授权的泄漏、陈旧的传播、矛盾的持续存在和起源崩溃。受管理的共享内存需要明确的系统级抽象，实时评估对… | MIT、HIT | Yanki Margalit |

### 论文详情

<details>
<summary><b>1. OpenThoughts-Agent: Data Recipes for Agentic Models</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Negin Raoof、Richard Zhuang、Marianna Nezhurina、Etash Guha、Atula Tejaswi 等（共 50 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT |
| **发布时间** | 2026-06-23T17:34:29Z |
| **关键词** | `Agentic` · `RAG` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2606.24855v1](http://arxiv.org/abs/2606.24855v1) |

**📝 摘要概括：**

> Agentic语言模型极大地扩展了人工智能的应用，但公众对如何为具有广泛能力的代理人策划培训数据知之甚少。现有的开放性工作，如SWE-Smith、SERA和Nemotron-Terminal ，通常针对单个基准，留下了如何训练跨越不同代理任务的模型的问题。我们在公开场合公开发布我们的训练集、数据管道、实验数据和模型……

</details>

<details>
<summary><b>2. World Models in Pieces: Structural Certification for General Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Yikai Lu、Yifei Wu、Xinyu Lu、Tongxin Li |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、CAS、TRI |
| **发布时间** | 2026-06-23T17:21:09Z |
| **关键词** | `Planning` |
| **原文链接** | [http://arxiv.org/abs/2606.24842v1](http://arxiv.org/abs/2606.24842v1) |

**📝 摘要概括：**

> 在大世界政权中，智能体不可能具有普遍的能力，他们的能力不可避免地分散在世界模型中。因此，标准统一保证无法区分对关键瓶颈的理解和不相关故障。这些结果通过本地化长期规划可靠的特定过渡，使一般代理能够进行可认证的部署。

</details>

<details>
<summary><b>3. Grading the Grader: Lessons from Evaluating an Agentic Data Analysis System</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Tian Zheng、Kai-Tai Hsu |
| **所属机构** | （详见原文） |
| **顶级机构标签** | HIT、CAS、TRI |
| **发布时间** | 2026-06-23T17:18:28Z |
| **关键词** | `Multi-Agent` · `Agentic` |
| **原文链接** | [http://arxiv.org/abs/2606.24839v1](http://arxiv.org/abs/2606.24839v1) |

**📝 摘要概括：**

> 代理数据分析系统产生丰富的输出，包括代码、数值结果和口头诊断。这使得他们比单轮法学硕士的回答更难评估。我们在本案例研究中进一步观察到，变量类型是与流水线动态分级和观察结果分级最一致的任务元数据字段。

</details>

<details>
<summary><b>4. Paying to Know: Micro-Transaction Markets for Verified Product Information in Agentic E-Commerce</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Filippos Ventirozos、Matthew Shardlow |
| **所属机构** | （详见原文） |
| **顶级机构标签** | HIT、TRI |
| **发布时间** | 2026-06-23T16:42:21Z |
| **关键词** | `Agentic` |
| **原文链接** | [http://arxiv.org/abs/2606.24783v1](http://arxiv.org/abs/2606.24783v1) |

**📝 摘要概括：**

> 商业NLP将购物聊天机器人视为推荐者或转换工具：其工作是将用户与目录条目匹配并完成销售。我们认为，代理原生微支付轨道的到来（例如， x402、AP2 ）改变了稀缺的东西。然后，我们将愿景转化为具体的自然语言处理问题--成本优化的信息获取、数据定价和谈判、实时实体解析、接地价值交换和隐私保护……

</details>

<details>
<summary><b>5. DeepBD: A Grounded Agentic Workflow for Variant Prioritization and Diagnosis of Genetic Birth Defects</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Shiyu Li、Ziqi Yan、Zhihao Wu、Jielong Lu、Weiran Liao 等（共 10 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | CAS |
| **发布时间** | 2026-06-23T16:37:48Z |
| **关键词** | `Agentic` · `Benchmark` · `Workflow` |
| **原文链接** | [http://arxiv.org/abs/2606.24779v1](http://arxiv.org/abs/2606.24779v1) |

**📝 摘要概括：**

> 出生缺陷是导致胎儿流失、新生儿发病和长期残疾的主要原因。在可疑遗传病因的亚组中，外显子组和基因组测序将许多病例从变异检测转移到测序后解释：临床医生必须将患者特异性候选变异在不完整的胎儿或婴儿表型和来自群体遗传学、变异效应预测、基因疾病有效性的异质证据下进行排序……

</details>

<details>
<summary><b>6. SAFARI: Scaling Long Horizon Agentic Fault Attribution via Active Investigation</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Chenyang Zhu、Jiayu Yao、Kushal Chawla、Youbing Yin、Nathan Wolfe 等（共 13 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、HIT、TRI |
| **发布时间** | 2026-06-23T14:23:40Z |
| **关键词** | `Multi-Agent` · `Agentic` · `Reasoning` · `Memory` |
| **原文链接** | [http://arxiv.org/abs/2606.24626v1](http://arxiv.org/abs/2606.24626v1) |

**📝 摘要概括：**

> 随着自治代理处理日益复杂的多步骤、多代理任务，它们的执行轨迹已经超出了即使是最大的上下文窗口的限制。当前有效诊断代理失败的方法将完整轨迹加载到LLM的上下文窗口中，该窗口存在注意力稀释问题，并且当代理跟踪不可避免地超过上下文限制时会失败。最重要的是， SAFARI保持了0.58的精度……

</details>

<details>
<summary><b>7. Privacy-Preserving RAG via Multi-Agent Semantic Rewriting: Achieving Confidentiality Without Compromising Contextual Fidelity</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Yuanhe Zhao、Tianyu Zhang、Huafei Xing、Derek F. Wong、Jianbin Li 等（共 6 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-06-23T14:21:41Z |
| **关键词** | `Multi-Agent` · `RAG` · `Retrieval` |
| **原文链接** | [http://arxiv.org/abs/2606.24623v1](http://arxiv.org/abs/2606.24623v1) |

**📝 摘要概括：**

> 检索增强生成通过整合外部知识来增强大型语言模型，但在敏感场景中部署它可能会通过恶意提示泄露隐私。为了解决这个问题，我们提出了一个多代理框架，通过语义重写对检索到的内容进行净化。为了提高可重复性，本作品的源代码可在https://github.com/foursoils/Privacy-Preserving-RAG上公开获得。

</details>

<details>
<summary><b>8. ASALT: Adaptive State Alignment for Lateral Transfer in Multi-agent Reinforcement Learning</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Anurag Akula、Satheesh K. Perepu、Abhishek Sarkar、Kaushik Dey |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT |
| **发布时间** | 2026-06-23T14:03:36Z |
| **关键词** | `Multi-Agent` · `Reinforcement Learning` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2606.24601v1](http://arxiv.org/abs/2606.24601v1) |

**📝 摘要概括：**

> 多代理强化学习(MARL)解决了培训追求协作、竞争或混合目标的多代理的问题。先前的工作研究了MARL中源域和目标域之间的迁移学习；然而，大多数现有方法都施加了观测空间和全局状态空间的维度必须在不同域之间相同的约束。此外，我们的调查结果表明……

</details>

<details>
<summary><b>9. Governed Shared Memory for Multi-Agent LLM Systems</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Yanki Margalit、Nurit Cohen-Inger、Erni Avram、Ran Taig、Oded Margalit |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、HIT、TRI |
| **发布时间** | 2026-06-23T13:04:14Z |
| **关键词** | `Multi-Agent` · `Retrieval` · `Evaluation` · `Memory` |
| **原文链接** | [http://arxiv.org/abs/2606.24535v1](http://arxiv.org/abs/2606.24535v1) |

**📝 摘要概括：**

> 多代理LLM环境需要强大的知识共享管理机制。本文形式化了车队记忆问题，并确定了四种基本的故障模式：未经授权的泄漏、陈旧的传播、矛盾的持续存在和起源崩溃。受管理的共享内存需要明确的系统级抽象，实时评估对于暴露仅限设计的事件错过的强制执行和管道排序故障至关重要。

</details>

## 🗄️ 历史归档

| 日期 | 论文数 | 报告链接 |
|------|--------|----------|
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
| 2026-05-31 | 0 篇 | [2026-05-31.md](daily/2026-05-31.md) |
| 2026-05-30 | 0 篇 | [2026-05-30.md](daily/2026-05-30.md) |
| 2026-05-29 | 0 篇 | [2026-05-29.md](daily/2026-05-29.md) |
| 2026-05-28 | 0 篇 | [2026-05-28.md](daily/2026-05-28.md) |
| 2026-05-27 | 0 篇 | [2026-05-27.md](daily/2026-05-27.md) |
| 2026-05-26 | 0 篇 | [2026-05-26.md](daily/2026-05-26.md) |

## 🏛️ 顶级机构覆盖范围

覆盖超过 **70 个**顶级 AI 机构，包括：

- **科技公司：** Microsoft、Google DeepMind、OpenAI、Anthropic、Meta AI、NVIDIA、Baidu、Alibaba、ByteDance 等
- **北美顶级大学：** MIT、Stanford、CMU、UC Berkeley、Harvard、Princeton、Cornell、Caltech 等
- **中国顶级大学/机构：** 清华大学、北京大学、浙大、上交大、复旦、中科院、MSRA 等
- **欧洲/其他：** Oxford、Cambridge、ETH Zurich、Mila、NUS、KAIST 等

---

*由 [clawBot DailyFindings](https://github.com/Jacob-biu/clawBot) 自动维护 | 最后更新：2026-06-24 23:06 UTC*
