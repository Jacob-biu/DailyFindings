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

## 📅 今日论文 — 2026-06-18　　[→ 查看完整报告](daily/2026-06-18.md)

> 共筛选出 **11** 篇论文 | 更新于 2026-06-18 23:45 UTC

### 论文目录与概要

| # | 论文标题 | 核心概要 | 来源机构 | 第一作者 |
|---|---------|---------|---------|--------|
| 1 | [Data Intelligence Agents: Interpreting, Modeling, and Queryi…](http://arxiv.org/abs/2606.19319v1) | 生产数据集成受到数据所有者、工程师和分析师之间重复、有损切换的瓶颈，他们必须协同发现、构建和查询企业数据。我们提出了数据智能代理（ DIA ） ，这是一个由三个代理（数据解释器、架构创建器和查询生成器… | MIT、HIT | Anoushka Vyas |
| 2 | [Optimal scenario design for climate emulation](http://arxiv.org/abs/2606.19302v1) | 随着物理系统的深度学习越来越受欢迎，提高可推广性的努力主要集中在设计嵌入物理约束的架构上。然而，对于机器学习的替代气候模型（模拟器） ，我们表明，通常用于生成训练数据的现有场景中的低结构多样性给预测技… | HIT | Christopher B. Womack |
| 3 | [Forecasting what Matters: Decision-Focused RL for Controlled…](http://arxiv.org/abs/2606.19199v1) | 最近电动汽车普及率的增长给电力系统带来了挑战，包括峰值需求的增加和潜在的电网不稳定。智能控制电动汽车充电-例如，基于强化学习（ RL ） -可以通过从历史数据中学习时间和背景模式来缓解这些问题。预测人… | MIT、CAS | Giuseppe Gabriele |
| 4 | [Learning to Annotate Delayed and False AEB Events: A Practic…](http://arxiv.org/abs/2606.19186v1) | 自动紧急制动（ AEB ）优化依赖于精确注释的真实世界触发事件，特别是暴露系统缺陷的罕见但关键的延迟和错误的AEB触发事件。然而，这些少数民族样本占每天数千个触发因素的不到5% ，这使得大规模手动注释… | HIT、TRI | Mengxiang Hao |
| 5 | [AdsMind: A Physics-Grounded Multi-Agent System for Self-Corr…](http://arxiv.org/abs/2606.19152v1) | 确定最低能量的表面吸附物配置对于建模异质催化至关重要，但从头开始计算的详尽勘探在计算上是禁止的。机器学习力场（ MLFF ）加速了结构松弛，但使对广阔配置空间的搜索成为主要瓶颈，而开环大语言模型（ L… | CAS | Zongmin Zhang |
| 6 | [A Technical Taxonomy of LLM Agent Communication Protocols](http://arxiv.org/abs/2606.19135v1) | 随着大型语言模型（ LLM ）的进步和多代理系统旨在克服独立代理的局限性，强大的通信协议正成为分布式代理网络的必不可少的基础设施。尽管如此，分散的协议环境带来了重大的互操作性挑战。该框架指导协议选择，… | MIT、HIT | Linus Sander |
| 7 | [Towards an Agent-First Web: Redesigning the Web for AI Agent…](http://arxiv.org/abs/2606.19116v1) | 万维网建立在三十年的假设之上：网络内容的主要消费者是人类。这渗透到每一层；其访问模型假设人类访客，其经济依赖于人类的注意力，其内容针对人类的感知。这些共同构成了代理优先互联网的十个设计原则，其中代理是… | MIT、HIT | Eranga Bandara |
| 8 | [RODS: Reward-Driven Online Data Synthesis for Multi-Turn Too…](http://arxiv.org/abs/2606.19047v1) | 静态数据集中信息样本的快速枯竭是多圈工具使用RL的瓶颈。我们观察到， GRPO中的梯度信号集中在具有最高推出奖励方差的任务上，这是Popoviciu上限的结果。从400个人类种子开始，并保持约800个… | TRI | Ruishan Fang |
| 9 | [TRAP: Benchmark for Task-completion and Resistance to Active…](http://arxiv.org/abs/2606.18996v1) | 代理越来越多地部署在文档密集型工作流程中，其中敏感的私人信息不是边缘情况，而是常规输入，例如，代理预订航班需要护照号码。在这些设置中，代理必须使用私人信息来准确完成任务，而不会在其响应中暴露它，因为它… | CAS、TRI | Moon Ye-Bin |
| 10 | [CAPRA: Scaling Feedback on Software Architecture Deliverable…](http://arxiv.org/abs/2606.18976v1) | 软件工程教育的自动化评估在代码评分和论文评分方面取得了显著进步。然而，审查软件架构交付件（需要分析结构完整性和需求可追溯性）尚未完全自动化。虽然这些结果支持LLM支持的建筑反馈的可行性，但人工监督对于… | MIT、HIT | Marco Becattini |
| 11 | [EfficientRollout: System-Aware Self-Speculative Decoding for…](http://arxiv.org/abs/2606.18967v1) | 强化学习（ RL ）已成为LLM的代表性培训后范式，实现了强大的推理和代理能力。然而，推出生成仍然是主要的延迟瓶颈，因为自回归采样按顺序解码响应，而少数长尾代通常决定完成时间。EfficientRol… | TRI | Minseo Kim |

### 论文详情

<details>
<summary><b>1. Data Intelligence Agents: Interpreting, Modeling, and Querying Enterprise Data via Autonomous Coding Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Anoushka Vyas、Aarushi Dhanuka、Sina Khoshfetrat Pakazad、Henrik Ohlsson |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、HIT、CAS |
| **发布时间** | 2026-06-17T17:45:32Z |
| **关键词** | `Benchmark` · `Memory` · `Workflow` |
| **原文链接** | [http://arxiv.org/abs/2606.19319v1](http://arxiv.org/abs/2606.19319v1) |

**📝 摘要概括：**

> 生产数据集成受到数据所有者、工程师和分析师之间重复、有损切换的瓶颈，他们必须协同发现、构建和查询企业数据。我们提出了数据智能代理（ DIA ） ，这是一个由三个代理（数据解释器、架构创建器和查询生成器）组成的系统，它通过将自主编码代理（ ACA ）视为一流的抽象来压缩此工作流程：而不是发出文本，而是……

</details>

<details>
<summary><b>2. Optimal scenario design for climate emulation</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Christopher B. Womack、Shahine Bouabid、Andrei Sokolov、Popat Salunke、Glenn Flierl 等（共 7 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | HIT |
| **发布时间** | 2026-06-17T17:26:22Z |
| **关键词** | — |
| **原文链接** | [http://arxiv.org/abs/2606.19302v1](http://arxiv.org/abs/2606.19302v1) |

**📝 摘要概括：**

> 随着物理系统的深度学习越来越受欢迎，提高可推广性的努力主要集中在设计嵌入物理约束的架构上。然而，对于机器学习的替代气候模型（模拟器） ，我们表明，通常用于生成训练数据的现有场景中的低结构多样性给预测技能设置了上限。我们的研究结果表明，在计算约束中……

</details>

<details>
<summary><b>3. Forecasting what Matters: Decision-Focused RL for Controlled EV Charging with Unknown Departure Times</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Giuseppe Gabriele、Fabio Pavirani、Seyed Soroush Karimi Madahi、Chris Develder |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、CAS |
| **发布时间** | 2026-06-17T15:37:35Z |
| **关键词** | `Reinforcement Learning` |
| **原文链接** | [http://arxiv.org/abs/2606.19199v1](http://arxiv.org/abs/2606.19199v1) |

**📝 摘要概括：**

> 最近电动汽车普及率的增长给电力系统带来了挑战，包括峰值需求的增加和潜在的电网不稳定。智能控制电动汽车充电-例如，基于强化学习（ RL ） -可以通过从历史数据中学习时间和背景模式来缓解这些问题。预测人员和控制员的这种联合培训最终导致了更高质量的行动：我们提出的DF-RL方法产生了优越的……

</details>

<details>
<summary><b>4. Learning to Annotate Delayed and False AEB Events: A Practical System for Extreme Class Imbalance and Asymmetric Label Noise</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Mengxiang Hao、Xin Jiang、Xinghao Huang、Wenliang Su、Zhiteng Wang 等（共 13 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | HIT、TRI |
| **发布时间** | 2026-06-17T15:27:15Z |
| **关键词** | — |
| **原文链接** | [http://arxiv.org/abs/2606.19186v1](http://arxiv.org/abs/2606.19186v1) |

**📝 摘要概括：**

> 自动紧急制动（ AEB ）优化依赖于精确注释的真实世界触发事件，特别是暴露系统缺陷的罕见但关键的延迟和错误的AEB触发事件。然而，这些少数民族样本占每天数千个触发因素的不到5% ，这使得大规模手动注释的成本高得令人望而却步。除了立竿见影的效果之外，该系统还能通过积累的高质量产品实现持续的自我提升……

</details>

<details>
<summary><b>5. AdsMind: A Physics-Grounded Multi-Agent System for Self-Correcting Discovery of Adsorption Configurations on Heterogeneous Catalyst Surfaces</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Zongmin Zhang、Yuyang Lou、Bowen Zhang、Junwu Chen、Ryo Kuroki 等（共 9 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | CAS |
| **发布时间** | 2026-06-17T14:57:16Z |
| **关键词** | `Multi-Agent` · `Benchmark` · `Workflow` |
| **原文链接** | [http://arxiv.org/abs/2606.19152v1](http://arxiv.org/abs/2606.19152v1) |

**📝 摘要概括：**

> 确定最低能量的表面吸附物配置对于建模异质催化至关重要，但从头开始计算的详尽勘探在计算上是禁止的。机器学习力场（ MLFF ）加速了结构松弛，但使对广阔配置空间的搜索成为主要瓶颈，而开环大语言模型（ LLM ）代理缺乏基于物理的反馈机制来纠正……

</details>

<details>
<summary><b>6. A Technical Taxonomy of LLM Agent Communication Protocols</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Linus Sander、Habtom Kahsay Gidey、Alexander Lenz、Alois Knoll |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、HIT、TRI |
| **发布时间** | 2026-06-17T14:45:20Z |
| **关键词** | `Multi-Agent` · `LLM Agent` · `RAG` |
| **原文链接** | [http://arxiv.org/abs/2606.19135v1](http://arxiv.org/abs/2606.19135v1) |

**📝 摘要概括：**

> 随着大型语言模型（ LLM ）的进步和多代理系统旨在克服独立代理的局限性，强大的通信协议正成为分布式代理网络的必不可少的基础设施。尽管如此，分散的协议环境带来了重大的互操作性挑战。该框架指导协议选择，并突出了隐私和政策执行等开放的研究差距。}

</details>

<details>
<summary><b>7. Towards an Agent-First Web: Redesigning the Web for AI Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Eranga Bandara、Ross Gore、Ravi Mukkamala、Asanga Gunaratna、Safdar H. Bouk 等（共 21 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、HIT |
| **发布时间** | 2026-06-17T14:31:07Z |
| **关键词** | `AI Agent` |
| **原文链接** | [http://arxiv.org/abs/2606.19116v1](http://arxiv.org/abs/2606.19116v1) |

**📝 摘要概括：**

> 万维网建立在三十年的假设之上：网络内容的主要消费者是人类。这渗透到每一层；其访问模型假设人类访客，其经济依赖于人类的注意力，其内容针对人类的感知。这些共同构成了代理优先互联网的十个设计原则，其中代理是一流的公民，其集成需要重新协商网络的目标……

</details>

<details>
<summary><b>8. RODS: Reward-Driven Online Data Synthesis for Multi-Turn Tool-Use Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Ruishan Fang、Siyuan Lu、Chenyi Zhuang、Tao Lin |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-06-17T13:13:32Z |
| **关键词** | — |
| **原文链接** | [http://arxiv.org/abs/2606.19047v1](http://arxiv.org/abs/2606.19047v1) |

**📝 摘要概括：**

> 静态数据集中信息样本的快速枯竭是多圈工具使用RL的瓶颈。我们观察到， GRPO中的梯度信号集中在具有最高推出奖励方差的任务上，这是Popoviciu上限的结果。从400个人类种子开始，并保持约800个样本的活跃训练池，棒实现了与17K样本离线管道相当的性能，同时需要大约20倍的处理量。

</details>

<details>
<summary><b>9. TRAP: Benchmark for Task-completion and Resistance to Active Privacy-extraction</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Moon Ye-Bin、Nam Hyeon-Woo、Baek Seong-Eun、Yejin Yeo、Tae-Hyun Oh |
| **所属机构** | （详见原文） |
| **顶级机构标签** | CAS、TRI |
| **发布时间** | 2026-06-17T12:17:02Z |
| **关键词** | `Benchmark` · `Workflow` |
| **原文链接** | [http://arxiv.org/abs/2606.18996v1](http://arxiv.org/abs/2606.18996v1) |

**📝 摘要概括：**

> 代理越来越多地部署在文档密集型工作流程中，其中敏感的私人信息不是边缘情况，而是常规输入，例如，代理预订航班需要护照号码。在这些设置中，代理必须使用私人信息来准确完成任务，而不会在其响应中暴露它，因为它无法验证谁实际上在键盘上。这种方法在很大程度上防止了泄漏，同时保持了任务的准确性……

</details>

<details>
<summary><b>10. CAPRA: Scaling Feedback on Software Architecture Deliverables with a Multi-Agent LLM System</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Marco Becattini、Niccolò Caselli、Matteo Minin、Roberto Verdecchia、Enrico Vicario |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、HIT、TRI |
| **发布时间** | 2026-06-17T12:00:21Z |
| **关键词** | `Multi-Agent` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2606.18976v1](http://arxiv.org/abs/2606.18976v1) |

**📝 摘要概括：**

> 软件工程教育的自动化评估在代码评分和论文评分方面取得了显著进步。然而，审查软件架构交付件（需要分析结构完整性和需求可追溯性）尚未完全自动化。虽然这些结果支持LLM支持的建筑反馈的可行性，但人工监督对于主观评估维度仍然至关重要。

</details>

<details>
<summary><b>11. EfficientRollout: System-Aware Self-Speculative Decoding for RL Rollouts</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Minseo Kim、Minjae Lee、Seunghyuk Oh、Kevin Galim、Donghoon Kim 等（共 10 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-06-17T11:51:06Z |
| **关键词** | `Agentic` · `Reasoning` · `Reinforcement Learning` · `Memory` |
| **原文链接** | [http://arxiv.org/abs/2606.18967v1](http://arxiv.org/abs/2606.18967v1) |

**📝 摘要概括：**

> 强化学习（ RL ）已成为LLM的代表性培训后范式，实现了强大的推理和代理能力。然而，推出生成仍然是主要的延迟瓶颈，因为自回归采样按顺序解码响应，而少数长尾代通常决定完成时间。EfficientRollout可将部署和端到端延迟分别减少高达19.6%和12.7% ，超过……

</details>

## 🗄️ 历史归档

| 日期 | 论文数 | 报告链接 |
|------|--------|----------|
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
| 2026-05-24 | 0 篇 | [2026-05-24.md](daily/2026-05-24.md) |
| 2026-05-23 | 0 篇 | [2026-05-23.md](daily/2026-05-23.md) |
| 2026-05-22 | 20 篇 | [2026-05-22.md](daily/2026-05-22.md) |
| 2026-05-21 | 0 篇 | [2026-05-21.md](daily/2026-05-21.md) |
| 2026-05-20 | 16 篇 | [2026-05-20.md](daily/2026-05-20.md) |

## 🏛️ 顶级机构覆盖范围

覆盖超过 **70 个**顶级 AI 机构，包括：

- **科技公司：** Microsoft、Google DeepMind、OpenAI、Anthropic、Meta AI、NVIDIA、Baidu、Alibaba、ByteDance 等
- **北美顶级大学：** MIT、Stanford、CMU、UC Berkeley、Harvard、Princeton、Cornell、Caltech 等
- **中国顶级大学/机构：** 清华大学、北京大学、浙大、上交大、复旦、中科院、MSRA 等
- **欧洲/其他：** Oxford、Cambridge、ETH Zurich、Mila、NUS、KAIST 等

---

*由 [clawBot DailyFindings](https://github.com/Jacob-biu/clawBot) 自动维护 | 最后更新：2026-06-18 23:45 UTC*
