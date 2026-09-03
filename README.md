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

## 📅 今日论文 — 2026-09-03　　[→ 查看完整报告](daily/2026-09-03.md)

> 共筛选出 **6** 篇论文 | 更新于 2026-09-03 23:48 UTC

### 论文目录与概要

| # | 论文标题 | 核心概要 | 来源机构 | 第一作者 |
|---|---------|---------|---------|--------|
| 1 | [SafeEvolve: Harness-Policy Co-Evolution from Agent Experienc…](http://arxiv.org/abs/2609.02786v1) | 基于LLM的代理的性能由基础模型和与环境交互时使用的线束共同塑造。这使他们在有害的最终反应和多步骤执行轨迹中都面临安全风险。对于Qwen3.5-4B ， SafeEvolve在AgentDojo上实现… | TRI | Qinghua Mao |
| 2 | [Measurement-Driven Sub-Network Selection for On-Premise Retr…](http://arxiv.org/abs/2609.02760v1) | 内部部署助理可以为工厂工人提供对机器文档的会话访问权限，但能够执行该任务的模型很少适合车间硬件。我们表明，在结构压缩和检索接地自适应之后，模型大小不再是自适应答案质量的可靠预测指标：一般能力随参数计数… | MIT、CAS | Vasileios Rizeakos |
| 3 | [Bilevel Coordinated Reflection: A Game-Theoretic Approach to…](http://arxiv.org/abs/2609.02750v1) | 多代理LLM系统通常使用编排器来分解工作团队的任务，然后通过文本反思进行改进。尽管有强大的实证结果，但这些系统缺乏对协调、记忆力改善和外部验证作用的统一描述。代码： https://github.co… | CAS、TRI | Yihang Chen |
| 4 | [Repo-To-Skill: Distilling GitHub Repositories Into AI4AI Ski…](http://arxiv.org/abs/2609.02749v1) | 自主代理开始端到端地进行机器学习（ ML ）研究。这些代理将模型骨干与用于规划、执行、内存和验证的线束相结合，但这种架构仍然将特定领域的专业知识留在代理之外。这些收益来自于在固定设置下添加蒸馏操作环境… | HIT | Jianlyu Chen |
| 5 | [Loom: Weaving Diagnostic Strands into Free-Text Consensus vi…](http://arxiv.org/abs/2609.02649v1) | 在现实世界的工业环境中部署NLP系统时，将嘈杂、冲突的文本假设聚合成可靠的共识是一项根本挑战。虽然整体大型语言模型（ LLM ）代理为根本原因分析（ RCA ）等任务提供了无限的表达能力，但它们存在上… | MIT、TRI | Ron Begleiter |
| 6 | [Online Reinforcement Learning in the Met Office Unified Mode…](http://arxiv.org/abs/2609.02566v1) | 机器学习校正只有适应不断变化的模型状态，同时保持动态一致性和数值稳定性，才能补充数值天气预测。为了在全球预测模型中对此进行测试，我们通过秩-局部张量将气象局（ UKMO ）统一模型（ UM ）与分布式… | CAS、TRI | Pritthijit Nath |

### 论文详情

<details>
<summary><b>1. SafeEvolve: Harness-Policy Co-Evolution from Agent Experience for Safety Alignment</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Qinghua Mao、Wanying Qu、Dadi Guo、Leitao Yuan、Qingyu Liu 等（共 11 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-09-02T16:19:54Z |
| **关键词** | `Agentic` · `RAG` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2609.02786v1](http://arxiv.org/abs/2609.02786v1) |

**📝 摘要概括：**

> 基于LLM的代理的性能由基础模型和与环境交互时使用的线束共同塑造。这使他们在有害的最终反应和多步骤执行轨迹中都面临安全风险。对于Qwen3.5-4B ， SafeEvolve在AgentDojo上实现了$ 3\ times $ ASR降低，同时将良性效用从59.79%提高到61.86%。

</details>

<details>
<summary><b>2. Measurement-Driven Sub-Network Selection for On-Premise Retrieval-Augmented Factory Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Vasileios Rizeakos、Georgios Paisios、Alexandros Machairas、Michael Birbas、Athanasios Bachoumis |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、CAS、TRI |
| **发布时间** | 2026-09-02T16:00:05Z |
| **关键词** | `Retrieval` · `Memory` |
| **原文链接** | [http://arxiv.org/abs/2609.02760v1](http://arxiv.org/abs/2609.02760v1) |

**📝 摘要概括：**

> 内部部署助理可以为工厂工人提供对机器文档的会话访问权限，但能够执行该任务的模型很少适合车间硬件。我们表明，在结构压缩和检索接地自适应之后，模型大小不再是自适应答案质量的可靠预测指标：一般能力随参数计数几乎线性下降，而判断的检索增强答案质量则不会。在制造人员中……

</details>

<details>
<summary><b>3. Bilevel Coordinated Reflection: A Game-Theoretic Approach to Multi-Agent LLM Systems</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Yihang Chen、Yuxiang Chen、Yuxuan Huang、Meng Fang、Weilin Luo 等（共 6 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | CAS、TRI |
| **发布时间** | 2026-09-02T15:50:10Z |
| **关键词** | `Multi-Agent` · `Evaluation` · `Memory` |
| **原文链接** | [http://arxiv.org/abs/2609.02750v1](http://arxiv.org/abs/2609.02750v1) |

**📝 摘要概括：**

> 多代理LLM系统通常使用编排器来分解工作团队的任务，然后通过文本反思进行改进。尽管有强大的实证结果，但这些系统缺乏对协调、记忆力改善和外部验证作用的统一描述。代码： https://github.com/YihangChen9/Bilevel-Coordinated-Reflection

</details>

<details>
<summary><b>4. Repo-To-Skill: Distilling GitHub Repositories Into AI4AI Skills</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Jianlyu Chen、Yuyang Hu、Hongjin Qian、Jiawei Liu、Wenqing Wei 等（共 11 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | HIT |
| **发布时间** | 2026-09-02T15:49:41Z |
| **关键词** | `Planning` · `Memory` |
| **原文链接** | [http://arxiv.org/abs/2609.02749v1](http://arxiv.org/abs/2609.02749v1) |

**📝 摘要概括：**

> 自主代理开始端到端地进行机器学习（ ML ）研究。这些代理将模型骨干与用于规划、执行、内存和验证的线束相结合，但这种架构仍然将特定领域的专业知识留在代理之外。这些收益来自于在固定设置下添加蒸馏操作环境。

</details>

<details>
<summary><b>5. Loom: Weaving Diagnostic Strands into Free-Text Consensus via Embedding-Space Reweighting</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Ron Begleiter、Katya Egert Berg、Gilad Saban、Gil Shabat |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-09-02T14:24:32Z |
| **关键词** | `Agentic` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2609.02649v1](http://arxiv.org/abs/2609.02649v1) |

**📝 摘要概括：**

> 在现实世界的工业环境中部署NLP系统时，将嘈杂、冲突的文本假设聚合成可靠的共识是一项根本挑战。虽然整体大型语言模型（ LLM ）代理为根本原因分析（ RCA ）等任务提供了无限的表达能力，但它们存在上下文限制、复合幻觉和令人望而却步的推理延迟。我们讨论我们的部署经验，强调经验教训……

</details>

<details>
<summary><b>6. Online Reinforcement Learning in the Met Office Unified Model through Distributed Model-Agent Coupling</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Pritthijit Nath、Sebastian Schemm、Peter Haynes、Emily Shuckburgh、Mark Webb |
| **所属机构** | （详见原文） |
| **顶级机构标签** | CAS、TRI |
| **发布时间** | 2026-09-02T13:17:10Z |
| **关键词** | `Reinforcement Learning` · `Workflow` |
| **原文链接** | [http://arxiv.org/abs/2609.02566v1](http://arxiv.org/abs/2609.02566v1) |

**📝 摘要概括：**

> 机器学习校正只有适应不断变化的模型状态，同时保持动态一致性和数值稳定性，才能补充数值天气预测。为了在全球预测模型中对此进行测试，我们通过秩-局部张量将气象局（ UKMO ）统一模型（ UM ）与分布式RL代理耦合。这个单例实验证明了分布式在线学习的巨大前景和可行性……

</details>

## 🗄️ 历史归档

| 日期 | 论文数 | 报告链接 |
|------|--------|----------|
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
| 2026-08-15 | 0 篇 | [2026-08-15.md](daily/2026-08-15.md) |
| 2026-08-14 | 20 篇 | [2026-08-14.md](daily/2026-08-14.md) |
| 2026-08-13 | 19 篇 | [2026-08-13.md](daily/2026-08-13.md) |
| 2026-08-12 | 13 篇 | [2026-08-12.md](daily/2026-08-12.md) |
| 2026-08-11 | 0 篇 | [2026-08-11.md](daily/2026-08-11.md) |
| 2026-08-10 | 0 篇 | [2026-08-10.md](daily/2026-08-10.md) |
| 2026-08-09 | 0 篇 | [2026-08-09.md](daily/2026-08-09.md) |
| 2026-08-08 | 0 篇 | [2026-08-08.md](daily/2026-08-08.md) |
| 2026-08-07 | 20 篇 | [2026-08-07.md](daily/2026-08-07.md) |
| 2026-08-05 | 20 篇 | [2026-08-05.md](daily/2026-08-05.md) |
| 2026-08-04 | 20 篇 | [2026-08-04.md](daily/2026-08-04.md) |
| 2026-08-03 | 0 篇 | [2026-08-03.md](daily/2026-08-03.md) |
| 2026-08-02 | 0 篇 | [2026-08-02.md](daily/2026-08-02.md) |

## 🏛️ 顶级机构覆盖范围

覆盖超过 **70 个**顶级 AI 机构，包括：

- **科技公司：** Microsoft、Google DeepMind、OpenAI、Anthropic、Meta AI、NVIDIA、Baidu、Alibaba、ByteDance 等
- **北美顶级大学：** MIT、Stanford、CMU、UC Berkeley、Harvard、Princeton、Cornell、Caltech 等
- **中国顶级大学/机构：** 清华大学、北京大学、浙大、上交大、复旦、中科院、MSRA 等
- **欧洲/其他：** Oxford、Cambridge、ETH Zurich、Mila、NUS、KAIST 等

---

*由 [clawBot DailyFindings](https://github.com/Jacob-biu/clawBot) 自动维护 | 最后更新：2026-09-03 23:48 UTC*
