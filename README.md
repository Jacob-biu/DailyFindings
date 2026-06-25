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

## 📅 今日论文 — 2026-06-25　　[→ 查看完整报告](daily/2026-06-25.md)

> 共筛选出 **11** 篇论文 | 更新于 2026-06-25 23:17 UTC

### 论文目录与概要

| # | 论文标题 | 核心概要 | 来源机构 | 第一作者 |
|---|---------|---------|---------|--------|
| 1 | [RevengeBench: Reverse Engineering Code-Space Policies from B…](http://arxiv.org/abs/2606.26094v1) | 在大多数科学史中，研究行为的研究人员只能从外在行为中推断出隐藏的机制：当有针对性的干预增强观察时，这种反向问题变得更加容易处理。我们提出了一个计算模拟：给定游戏环境中智能体的行为痕迹，学习者可以将底层… | MIT、TRI | Babak Rahmani |
| 2 | [Neglected Free Lunch from Post-training: Progress Advantage …](http://arxiv.org/abs/2606.26080v1) | 过程奖励模型可以对LLM进行细粒度、阶梯级的评估，但为代理设置构建它们仍然非常困难：长距离交互、不可逆操作和随机环境反馈使人工注释和蒙特卡洛估计在大规模上都不可行。在这项工作中，我们表明，强化学习（ … | TRI | Changdae Oh |
| 3 | [The Unfireable Safety Kernel: Execution-Time AI Alignment fo…](http://arxiv.org/abs/2606.26057v1) | AI代理被授予对工具、API和其他基础设施的访问权限，使其成为这些系统中的活跃主体。主导方法将控件放置在代理自己的运行时内：系统提示、输出过滤器和护栏库。针对3个声称拥有代理控制平面的当代系统，代理调… | HIT、TRI | Seth Dobrin |
| 4 | [Can Trustless Agents Be Trusted? An Empirical Study of the E…](http://arxiv.org/abs/2606.26028v1) | 随着自主人工智能代理越来越多地跨组织边界进行交易，一个基本的信任挑战出现了：代理如何评估未知对手是否值得信赖？ ERC-8004协议通过人工智能代理经济体的第一个无权限信任层来解决这一挑战，该层围绕身… | TRI | Xihan Xiong |
| 5 | [Why Multi-Step Tool-Use Reinforcement Learning Collapses and…](http://arxiv.org/abs/2606.26027v1) | 工具使用使大型语言模型（ LLM ）能够执行复杂的任务，最近的代理强化学习（ RL ）方法有望增强模型功能。然而，仅靠强化学习往往会导致工具使用任务的不稳定或有限的收益。我们的守则可在https://… | MIT、TRI | Yupu Hao |
| 6 | [FORCE: Efficient VLA Reinforcement Fine-Tuning via Value-Cal…](http://arxiv.org/abs/2606.26006v1) | 视觉-语言-行动（ VLA ）模型通常受到次优数据所施加的模仿上限的限制。虽然强化学习（ RL ）微调可以超过这个限制，但众所周知，它的样本效率低下。至关重要的是，它减轻了常见的成功率下降，并在没有人… | MIT、TRI | Shuyi Zhang |
| 7 | [Hierarchical Reinforcement Learning for Neural Network Compr…](http://arxiv.org/abs/2606.26002v1) | 我们提出了HiReLC ，这是一个分层集成强化学习框架，用于深度神经网络的自动化联合量化和结构化修剪。该框架将压缩搜索分解为两个抽象级别：低级代理（ LLA ）在每个块上独立运行，在跨越比特宽度的多离… | MIT、HIT | Kamar Hibatallah Baghdadi |
| 8 | [Agentic System as Compressor: Quantifying System Intelligenc…](http://arxiv.org/abs/2606.25960v1) | 大型语言模型正在从孤立的预测器转变为代理系统：它们调用工具，检索证据，遵守环境约束，使用验证器，并通过搜索和多回合交互完成任务。我们采用基于“压缩就是智能”的分析观点：在固定的任务分布、接口和计算预算… | TRI | Zihan Qin |
| 9 | [Explainable Control Framework (XCF) based on Fuzzy Model-Agn…](http://arxiv.org/abs/2606.25941v1) | 在复杂场景中，对精确和可靠控制的需求不断增加，这导致了日益复杂的控制器的发展，包括采用闭箱模型的数据驱动方法和数学严谨而复杂的设计。这种复杂性凸显了对可解释控制的需求，可以为控制器行为提供人类可理解的… | CAS、TRI | Faliang Yin |
| 10 | [Semantic Consistency Policy Optimization for Reinforcement L…](http://arxiv.org/abs/2606.25852v1) | 基于小组的强化学习通过从轨迹结果中获得阶梯级功劳，有效地对LLM代理进行长期、稀疏奖励任务的后期培训。然而，这会将一个步骤的功劳与其推出的最终结果联系起来：语义上几乎相同的中间步骤会得到相反的功劳，这… | MIT、Mila | Peng Xu |
| 11 | [Uncertainty Quantification for Computer-Use Agents: A Benchm…](http://arxiv.org/abs/2606.25760v1) | 计算机使用代理将视觉语言模型(VLM)预测转化为可执行的GUI点击，因此可靠的不确定性估计对于拒绝、校准、错失严重程度排名和空间安全区域至关重要。然而，这些药剂的事后不确定性量化（ UQ ）的证据在孤… | TRI | Divake Kumar |

### 论文详情

<details>
<summary><b>1. RevengeBench: Reverse Engineering Code-Space Policies from Behavioral Experiments</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Babak Rahmani、Sebastian Dziadzio、Joschka Strüber、Sergio Hernández-Gutiérrez、Matthias Bethge |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-06-24T17:59:46Z |
| **关键词** | `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2606.26094v1](http://arxiv.org/abs/2606.26094v1) |

**📝 摘要概括：**

> 在大多数科学史中，研究行为的研究人员只能从外在行为中推断出隐藏的机制：当有针对性的干预增强观察时，这种反向问题变得更加容易处理。我们提出了一个计算模拟：给定游戏环境中智能体的行为痕迹，学习者可以将底层决策程序重构为可执行代码，并且这种重构在多大程度上随着时间的推移而改善。

</details>

<details>
<summary><b>2. Neglected Free Lunch from Post-training: Progress Advantage for LLM Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Changdae Oh、Wendi Li、Seongheon Park、Samuel Yeh、Tanwi Mallick 等（共 6 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-06-24T17:54:08Z |
| **关键词** | `LLM Agent` · `Agentic` · `Reinforcement Learning` · `Benchmark` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2606.26080v1](http://arxiv.org/abs/2606.26080v1) |

**📝 摘要概括：**

> 过程奖励模型可以对LLM进行细粒度、阶梯级的评估，但为代理设置构建它们仍然非常困难：长距离交互、不可逆操作和随机环境反馈使人工注释和蒙特卡洛估计在大规模上都不可行。在这项工作中，我们表明，强化学习（ RL ）训练后已经为有效的阶梯级评分提供了成分，消除了……

</details>

<details>
<summary><b>3. The Unfireable Safety Kernel: Execution-Time AI Alignment for AI Agents and Other Escapable AI Systems</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Seth Dobrin、Łukasz Chmiel |
| **所属机构** | （详见原文） |
| **顶级机构标签** | HIT、TRI |
| **发布时间** | 2026-06-24T17:32:27Z |
| **关键词** | `AI Agent` |
| **原文链接** | [http://arxiv.org/abs/2606.26057v1](http://arxiv.org/abs/2606.26057v1) |

**📝 摘要概括：**

> AI代理被授予对工具、API和其他基础设施的访问权限，使其成为这些系统中的活跃主体。主导方法将控件放置在代理自己的运行时内：系统提示、输出过滤器和护栏库。针对3个声称拥有代理控制平面的当代系统，代理调用控制；在这里，它缺乏这种选择。

</details>

<details>
<summary><b>4. Can Trustless Agents Be Trusted? An Empirical Study of the ERC-8004 Decentralized AI Agent Ecosystem</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Xihan Xiong、Zelin Li、Wei Wei、Qin Wang、William Knottenbelt 等（共 6 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-06-24T16:57:49Z |
| **关键词** | `AI Agent` |
| **原文链接** | [http://arxiv.org/abs/2606.26028v1](http://arxiv.org/abs/2606.26028v1) |

**📝 摘要概括：**

> 随着自主人工智能代理越来越多地跨组织边界进行交易，一个基本的信任挑战出现了：代理如何评估未知对手是否值得信赖？ ERC-8004协议通过人工智能代理经济体的第一个无权限信任层来解决这一挑战，该层围绕身份、声誉和验证的三个链上注册表构建。我们的研究得出了可行的方案设计含义和……

</details>

<details>
<summary><b>5. Why Multi-Step Tool-Use Reinforcement Learning Collapses and How Supervisory Signals Fix It</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Yupu Hao、Zhuoran Jin、Huanxuan Liao、Kang Liu、Jun Zhao |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-06-24T16:55:56Z |
| **关键词** | `Agentic` · `Reinforcement Learning` · `Evaluation` · `Fine-tuning` |
| **原文链接** | [http://arxiv.org/abs/2606.26027v1](http://arxiv.org/abs/2606.26027v1) |

**📝 摘要概括：**

> 工具使用使大型语言模型（ LLM ）能够执行复杂的任务，最近的代理强化学习（ RL ）方法有望增强模型功能。然而，仅靠强化学习往往会导致工具使用任务的不稳定或有限的收益。我们的守则可在https://github.com/hypasd-art/Tool-RL-Box上找到。

</details>

<details>
<summary><b>6. FORCE: Efficient VLA Reinforcement Fine-Tuning via Value-Calibrated Warm-up and Self-Distillation</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Shuyi Zhang、Yunfan Lou、Hongyang Cheng、Yichen Guo、Chuyao Fu 等（共 11 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-06-24T16:23:18Z |
| **关键词** | `Reinforcement Learning` · `Fine-tuning` · `Simulation` |
| **原文链接** | [http://arxiv.org/abs/2606.26006v1](http://arxiv.org/abs/2606.26006v1) |

**📝 摘要概括：**

> 视觉-语言-行动（ VLA ）模型通常受到次优数据所施加的模仿上限的限制。虽然强化学习（ RL ）微调可以超过这个限制，但众所周知，它的样本效率低下。至关重要的是，它减轻了常见的成功率下降，并在没有人为干预的情况下实现了这种强大的性能，标志着朝着部署有能力和自主的机器人代理迈出了重要一步。

</details>

<details>
<summary><b>7. Hierarchical Reinforcement Learning for Neural Network Compression (HiReLC): Pruning and Quantization</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Kamar Hibatallah Baghdadi、Kawther Guoual Belhamidi、Sara Belhadj、Aissa Boulmerka、Nadir Farhi |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、HIT |
| **发布时间** | 2026-06-24T16:19:29Z |
| **关键词** | `Reinforcement Learning` · `RAG` · `Benchmark` · `Evaluation` · `Fine-tuning` |
| **原文链接** | [http://arxiv.org/abs/2606.26002v1](http://arxiv.org/abs/2606.26002v1) |

**📝 摘要概括：**

> 我们提出了HiReLC ，这是一个分层集成强化学习框架，用于深度神经网络的自动化联合量化和结构化修剪。该框架将压缩搜索分解为两个抽象级别：低级代理（ LLA ）在每个块上独立运行，在跨越比特宽度的多离散动作空间上选择每个内核配置，修剪保持比率，量化类型和粒度，而高...

</details>

<details>
<summary><b>8. Agentic System as Compressor: Quantifying System Intelligence in Bits</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Zihan Qin、Hongrui Zhang |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-06-24T15:32:49Z |
| **关键词** | `Agentic` · `Retrieval` |
| **原文链接** | [http://arxiv.org/abs/2606.25960v1](http://arxiv.org/abs/2606.25960v1) |

**📝 摘要概括：**

> 大型语言模型正在从孤立的预测器转变为代理系统：它们调用工具，检索证据，遵守环境约束，使用验证器，并通过搜索和多回合交互完成任务。我们采用基于“压缩就是智能”的分析观点：在固定的任务分布、接口和计算预算下，更强大的代理系统可以用更少的位重构目标对象。

</details>

<details>
<summary><b>9. Explainable Control Framework (XCF) based on Fuzzy Model-Agnostic Explanation and LLM Agent-Supported Interface</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Faliang Yin、Hak-Keung Lam、David Watson |
| **所属机构** | （详见原文） |
| **顶级机构标签** | CAS、TRI |
| **发布时间** | 2026-06-24T15:17:54Z |
| **关键词** | `LLM Agent` |
| **原文链接** | [http://arxiv.org/abs/2606.25941v1](http://arxiv.org/abs/2606.25941v1) |

**📝 摘要概括：**

> 在复杂场景中，对精确和可靠控制的需求不断增加，这导致了日益复杂的控制器的发展，包括采用闭箱模型的数据驱动方法和数学严谨而复杂的设计。这种复杂性凸显了对可解释控制的需求，可以为控制器行为提供人类可理解的见解。倒立摆系统和Turtlebot障碍物的案例研究……

</details>

<details>
<summary><b>10. Semantic Consistency Policy Optimization for Reinforcement Learning of LLM Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Peng Xu、Sijia Chen、Junzhuo Li、Xuming Hu |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、Mila、NTU |
| **发布时间** | 2026-06-24T14:02:13Z |
| **关键词** | `LLM Agent` · `Reinforcement Learning` |
| **原文链接** | [http://arxiv.org/abs/2606.25852v1](http://arxiv.org/abs/2606.25852v1) |

**📝 摘要概括：**

> 基于小组的强化学习通过从轨迹结果中获得阶梯级功劳，有效地对LLM代理进行长期、稀疏奖励任务的后期培训。然而，这会将一个步骤的功劳与其推出的最终结果联系起来：语义上几乎相同的中间步骤会得到相反的功劳，这取决于它们的轨迹最终是成功还是失败。在ALFWorld和WebShop上， SCPO匹配或超过强大的基于组的基线， ……

</details>

<details>
<summary><b>11. Uncertainty Quantification for Computer-Use Agents: A Benchmark across Vision-Language Models and GUI Grounding Datasets</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Divake Kumar、Sina Tayebati、Devashri Naik、Amanda Sofie Rios、Nilesh Ahuja 等（共 8 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-06-24T12:34:28Z |
| **关键词** | `RAG` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2606.25760v1](http://arxiv.org/abs/2606.25760v1) |

**📝 摘要概括：**

> 计算机使用代理将视觉语言模型(VLM)预测转化为可执行的GUI点击，因此可靠的不确定性估计对于拒绝、校准、错失严重程度排名和空间安全区域至关重要。然而，这些药剂的事后不确定性量化（ UQ ）的证据在孤立的模型和数据集对中是分散的，使得尚不清楚当药剂、基准或可观察到的界面时， UQ排名是否保持稳定……

</details>

## 🗄️ 历史归档

| 日期 | 论文数 | 报告链接 |
|------|--------|----------|
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
| 2026-05-31 | 0 篇 | [2026-05-31.md](daily/2026-05-31.md) |
| 2026-05-30 | 0 篇 | [2026-05-30.md](daily/2026-05-30.md) |
| 2026-05-29 | 0 篇 | [2026-05-29.md](daily/2026-05-29.md) |
| 2026-05-28 | 0 篇 | [2026-05-28.md](daily/2026-05-28.md) |
| 2026-05-27 | 0 篇 | [2026-05-27.md](daily/2026-05-27.md) |

## 🏛️ 顶级机构覆盖范围

覆盖超过 **70 个**顶级 AI 机构，包括：

- **科技公司：** Microsoft、Google DeepMind、OpenAI、Anthropic、Meta AI、NVIDIA、Baidu、Alibaba、ByteDance 等
- **北美顶级大学：** MIT、Stanford、CMU、UC Berkeley、Harvard、Princeton、Cornell、Caltech 等
- **中国顶级大学/机构：** 清华大学、北京大学、浙大、上交大、复旦、中科院、MSRA 等
- **欧洲/其他：** Oxford、Cambridge、ETH Zurich、Mila、NUS、KAIST 等

---

*由 [clawBot DailyFindings](https://github.com/Jacob-biu/clawBot) 自动维护 | 最后更新：2026-06-25 23:17 UTC*
