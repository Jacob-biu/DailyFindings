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

## 📅 今日论文 — 2026-09-30　　[→ 查看完整报告](daily/2026-09-30.md)

> 共筛选出 **8** 篇论文 | 更新于 2026-09-30 01:04 UTC

### 论文目录与概要

| # | 论文标题 | 核心概要 | 来源机构 | 第一作者 |
|---|---------|---------|---------|--------|
| 1 | [SCA: Spatial Credit Assignment for Reinforcement Learning of…](http://arxiv.org/abs/2609.36939v1) | GUI代理通过在可视界面中接地语言指令来自动执行数字设备上的任务。现有的群体相对强化学习通过比较来自相同GUI状态的多个采样响应的奖励来改进GUI动作预测。在GUI接地和离线动作预测基准中， SCA改… | MIT、TRI | Shengtian Yang |
| 2 | [PrecogUI: Proactive GUI Agents via Pre-cognitive Simulation …](http://arxiv.org/abs/2609.36923v1) | 现有的被动式图形用户界面(GUI)代理通常在长时间的动态场景中失败，意外干扰会触发注意力转移和级联故障。为了解决这个问题，我们提出了PrecogUI ，这是一种预认知架构，将范式从被动执行转变为主动决… | HIT、CAS | Bin Kang |
| 3 | [Harness Evolution as Learning: Approximation, Generalization…](http://arxiv.org/abs/2609.36892v1) | 随着大型语言模型（ LLM ）的能力不断提高，人们越来越关注如何将他们的能力转化为有用的行为。个人代理将此问题带入日常设置，其中模型应为个人用户提供服务，并不断适应他们的偏好。这些结果共同为通过线束进… | MIT、HIT | Zeyu Gan |
| 4 | [WEFT: Scaling Tool-Use Post-Training for General-Purpose Age…](http://arxiv.org/abs/2609.36887v1) | 最近扩展工具使用后培训的努力主要集中在可执行环境的合成上，这些环境仅构成更广泛的代理交互系统的一个组成部分，该系统包括环境、任务、代理线束和评估器。然而，孤立地扩展环境并不能保证模型性能有相应的增益，… | TRI | Bo Mao |
| 5 | [SKILLLITE: Evidence-Guided Malicious Skill Auditing with Com…](http://arxiv.org/abs/2609.36879v1) | 随着基于LLM的客服代表执行日益复杂的任务，客服代表技能已成为扩展其能力的灵活机制。代理技能将特定于任务的指令与可执行组件和辅助资源打包在一起，以提供专门的功能。同时， SKILLLITE保持低推理延… | MIT | Haoran Ou |
| 6 | [State Trace Rationale As Auxiliary Task in Reinforcement Lea…](http://arxiv.org/abs/2609.36867v1) | 我们提出了STRAT ，这是一项辅助任务，用于训练深度强化学习（ RL ）代理预测其自身状态的简短文本跟踪。该描述受人类空间导航的启发，结合了地标、路线和调查知识，跟踪客服代表的位置、库存、目标和即时… | TRI | Muhammad U. Nasir |
| 7 | [Where the Model Changes Its Mind: Hindsight-Divergence Local…](http://arxiv.org/abs/2609.36864v1) | 具有可验证奖励（ RLVR ）的强化学习的群体相关方法从推出结果的差异中学习。独立采样完整轨迹是昂贵的，并且没有明确地探索关键位置的决策空间。尽管发电预算有所减少，但HDL在所有三个领域都提高了性能，… | TRI | Fanchao Chen |
| 8 | [When Upstream Messages Override Correct Answers: A Controlle…](http://arxiv.org/abs/2609.36855v1) | 多代理LLM系统依靠专业代理之间的消息传递来完成复杂的任务。但是，上游客服代表可能会提供有用的信息或不正确的答案，导致下游客服代表推翻由其自身证据支持的正确答案。删除不可靠的消息可以恢复部分丢失的准确… | CAS | Yaxin Gong |

### 论文详情

<details>
<summary><b>1. SCA: Spatial Credit Assignment for Reinforcement Learning of GUI Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Shengtian Yang、Ziyu Xiong、Kaibing Yang、Guangfeng Cai、Yewen Li 等（共 9 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-09-29T07:51:57Z |
| **关键词** | `Reinforcement Learning` · `Benchmark` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2609.36939v1](http://arxiv.org/abs/2609.36939v1) |

**📝 摘要概括：**

> GUI代理通过在可视界面中接地语言指令来自动执行数字设备上的任务。现有的群体相对强化学习通过比较来自相同GUI状态的多个采样响应的奖励来改进GUI动作预测。在GUI接地和离线动作预测基准中， SCA改善了跨专业领域的接地，并在……的强化-微调模型中取得了最强的结果

</details>

<details>
<summary><b>2. PrecogUI: Proactive GUI Agents via Pre-cognitive Simulation and Experience Retrieval</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Bin Kang、Jiarui Ouyang、Li Jiang、Bin Chen、Zhuotao Tian |
| **所属机构** | （详见原文） |
| **顶级机构标签** | HIT、CAS、TRI |
| **发布时间** | 2026-09-29T07:41:34Z |
| **关键词** | `Retrieval` · `Benchmark` · `Evaluation` · `Simulation` · `Memory` |
| **原文链接** | [http://arxiv.org/abs/2609.36923v1](http://arxiv.org/abs/2609.36923v1) |

**📝 摘要概括：**

> 现有的被动式图形用户界面(GUI)代理通常在长时间的动态场景中失败，意外干扰会触发注意力转移和级联故障。为了解决这个问题，我们提出了PrecogUI ，这是一种预认知架构，将范式从被动执行转变为主动决策。该代码将公开提供。

</details>

<details>
<summary><b>3. Harness Evolution as Learning: Approximation, Generalization, and Optimization Limits of Self-Improving Personal Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Zeyu Gan、Zixuan Gong、Yong Liu |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、HIT |
| **发布时间** | 2026-09-29T07:21:50Z |
| **关键词** | `Benchmark` · `Memory` |
| **原文链接** | [http://arxiv.org/abs/2609.36892v1](http://arxiv.org/abs/2609.36892v1) |

**📝 摘要概括：**

> 随着大型语言模型（ LLM ）的能力不断提高，人们越来越关注如何将他们的能力转化为有用的行为。个人代理将此问题带入日常设置，其中模型应为个人用户提供服务，并不断适应他们的偏好。这些结果共同为通过线束进化实现个性化的局限性提供了一个统一的视角，并为未来的发展提供了信息。

</details>

<details>
<summary><b>4. WEFT: Scaling Tool-Use Post-Training for General-Purpose Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Bo Mao、Hang He、Linting Wang、Lizhi Lin、Maosen Zhou 等（共 20 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-09-29T07:14:53Z |
| **关键词** | `Agentic` · `Benchmark` · `Workflow` |
| **原文链接** | [http://arxiv.org/abs/2609.36887v1](http://arxiv.org/abs/2609.36887v1) |

**📝 摘要概括：**

> 最近扩展工具使用后培训的努力主要集中在可执行环境的合成上，这些环境仅构成更广泛的代理交互系统的一个组成部分，该系统包括环境、任务、代理线束和评估器。然而，孤立地扩展环境并不能保证模型性能有相应的增益，因为可靠的学习信号取决于模型所有组成部分之间的相干交互。

</details>

<details>
<summary><b>5. SKILLLITE: Evidence-Guided Malicious Skill Auditing with Compact LLMs</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Haoran Ou、Gelei Deng、Xuanye Zhang、Wenbo Guo、Tianwei Zhang 等（共 6 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT |
| **发布时间** | 2026-09-29T07:11:33Z |
| **关键词** | `Agentic` · `Reasoning` |
| **原文链接** | [http://arxiv.org/abs/2609.36879v1](http://arxiv.org/abs/2609.36879v1) |

**📝 摘要概括：**

> 随着基于LLM的客服代表执行日益复杂的任务，客服代表技能已成为扩展其能力的灵活机制。代理技能将特定于任务的指令与可执行组件和辅助资源打包在一起，以提供专门的功能。同时， SKILLLITE保持低推理延迟，支持其实际部署。

</details>

<details>
<summary><b>6. State Trace Rationale As Auxiliary Task in Reinforcement Learning</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Muhammad U. Nasir、Alex Vogt、Steven D. James、Julian Togelius |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-09-29T07:07:22Z |
| **关键词** | `Reinforcement Learning` |
| **原文链接** | [http://arxiv.org/abs/2609.36867v1](http://arxiv.org/abs/2609.36867v1) |

**📝 摘要概括：**

> 我们提出了STRAT ，这是一项辅助任务，用于训练深度强化学习（ RL ）代理预测其自身状态的简短文本跟踪。该描述受人类空间导航的启发，结合了地标、路线和调查知识，跟踪客服代表的位置、库存、目标和即时进度。除了性能提升之外，预测的跟踪还提供了每一步代理信念的可读帐户，无需额外成本。

</details>

<details>
<summary><b>7. Where the Model Changes Its Mind: Hindsight-Divergence Localization for Efficient Reinforcement Learning with Verifiable Rewards</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Fanchao Chen、Hengyu Fu、Shivaram Venkataraman、Jiantao Jiao |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-09-29T07:05:29Z |
| **关键词** | `Reinforcement Learning` |
| **原文链接** | [http://arxiv.org/abs/2609.36864v1](http://arxiv.org/abs/2609.36864v1) |

**📝 摘要概括：**

> 具有可验证奖励（ RLVR ）的强化学习的群体相关方法从推出结果的差异中学习。独立采样完整轨迹是昂贵的，并且没有明确地探索关键位置的决策空间。尽管发电预算有所减少，但HDL在所有三个领域都提高了性能，在座席任务上提高了高达12.5分。

</details>

<details>
<summary><b>8. When Upstream Messages Override Correct Answers: A Controlled Study of Multi-Agent LLM Collaboration</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Yaxin Gong、Gangyi Zhang、Chongming Gao、Leyang Shen、Chenxiao Fan 等（共 10 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | CAS |
| **发布时间** | 2026-09-29T07:01:10Z |
| **关键词** | `Multi-Agent` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2609.36855v1](http://arxiv.org/abs/2609.36855v1) |

**📝 摘要概括：**

> 多代理LLM系统依靠专业代理之间的消息传递来完成复杂的任务。但是，上游客服代表可能会提供有用的信息或不正确的答案，导致下游客服代表推翻由其自身证据支持的正确答案。删除不可靠的消息可以恢复部分丢失的准确性，这表明沟通应该根据上游的可靠性和已有的证据进行选择……

</details>

## 🗄️ 历史归档

| 日期 | 论文数 | 报告链接 |
|------|--------|----------|
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
| 2026-08-16 | 0 篇 | [2026-08-16.md](daily/2026-08-16.md) |

## 🏛️ 顶级机构覆盖范围

覆盖超过 **70 个**顶级 AI 机构，包括：

- **科技公司：** Microsoft、Google DeepMind、OpenAI、Anthropic、Meta AI、NVIDIA、Baidu、Alibaba、ByteDance 等
- **北美顶级大学：** MIT、Stanford、CMU、UC Berkeley、Harvard、Princeton、Cornell、Caltech 等
- **中国顶级大学/机构：** 清华大学、北京大学、浙大、上交大、复旦、中科院、MSRA 等
- **欧洲/其他：** Oxford、Cambridge、ETH Zurich、Mila、NUS、KAIST 等

---

*由 [clawBot DailyFindings](https://github.com/Jacob-biu/clawBot) 自动维护 | 最后更新：2026-09-30 01:04 UTC*
