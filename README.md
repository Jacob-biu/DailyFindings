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

## 📅 今日论文 — 2026-06-16　　[→ 查看完整报告](daily/2026-06-16.md)

> 共筛选出 **18** 篇论文 | 更新于 2026-06-16 23:24 UTC

### 论文目录与概要

| # | 论文标题 | 核心概要 | 来源机构 | 第一作者 |
|---|---------|---------|---------|--------|
| 1 | [TokenPilot: Cache-Efficient Context Management for LLM Agent…](http://arxiv.org/abs/2606.17016v1) | 随着LLM代理在长时间会话中部署，上下文积累会推高推理成本。现有方法利用文本修剪或动态内存逐出来最小化令牌足迹；然而，它们不受约束的序列突变改变了布局，引入了前缀不匹配和缓存失效。TokenPilot… | ZJU | Buqiang Xu |
| 2 | [Bayesian Inference and Decision Audits for Public Archives o…](http://arxiv.org/abs/2606.17005v1) | 公开的人工智能评估通常被解读为终端排行榜，但潜在的证据是由报告规则、基准修订和缺失形成的选择性时间序列。LiveBench和Open LLM Leaderboard v2的重复公共档案作为主要纵向记录… | MIT、TRI | Yanan Long |
| 3 | [Agent trajectories as programs: fingerprinting and programmi…](http://arxiv.org/abs/2606.16988v1) | 基准分数告诉你客服代表做对了什么；他们不会告诉你它是如何到达那里的。在这项工作中，我们介绍了在不同上下文中程序性地比较代理的方法，其中模型、任务和方法各不相同。我们相信这项工作有一系列应用程序可以帮助… | Mila、TRI | Hamidah Oderinwale |
| 4 | [Consensus-based Agentic Large Language Model Framework for H…](http://arxiv.org/abs/2606.16987v1) | 准确的统一关税表（ HTS ）代码分类对于海运物流中的清关、关税评估、贸易统计和监管合规至关重要。然而，确切的高温超导分类仍然具有挑战性，因为产品描述通常简短、不完整或模棱两可，而正确的分类取决于等级… | TRI | Truong Thanh Hung Nguyen |
| 5 | [A Unified Causal-Origin Taxonomy of Distributional Shifts in…](http://arxiv.org/abs/2606.16933v1) | 当操作条件与以前遇到的不同时，强化学习（ RL ）系统通常会退化，这反映了底层数据生成过程中的分布变化。这种转变可能发生在训练和评估之间，例如在分布内（ ID ）和分布外（ OOD ）泛化中，或者在环… | MIT、TRI | Ardianto Wibowo |
| 6 | [Binary Tracking for Spatial QA and Navigation with Open Visi…](http://arxiv.org/abs/2606.16902v1) | 这项工作解决了服务机器人穿越长距离自我中心路线的空间问答问题。给定一个查询，例如“在回家的路上在哪里可以找到干洗店？” ，系统会返回一个指标坐标，下游导航组件可以根据该坐标采取行动。源代码和数据集可在… | MIT、TRI | Dongbin Na |
| 7 | [Semantic Flip: Synthetic OOD Generation for Robust Refusal i…](http://arxiv.org/abs/2606.16898v1) | 检测无法回答的用户查询对于可靠部署真实世界的具体化代理仍然至关重要。然而，现代视觉语言模型（ VLM ）通常会生成过于自信的答案，即使可用的视觉记忆无法支持查询。源代码和数据集可在https://gi… | TRI | Dongbin Na |
| 8 | [LabOSBench: Benchmarking Computer Use Agents for Scientific …](http://arxiv.org/abs/2606.16802v1) | 当前的计算机使用基准主要关注虚拟化系统中的软件操作任务，而科学仪器场景需要对复杂接口进行协调控制，以及反馈驱动的参数调整。然而，由于成本高、安全风险大、可及性有限以及难以确保评估的可重复性，在物理高精… | MIT | Anqi Zou |
| 9 | [Skill-to-LoRA: From Using Skills to Learning Behaviors for T…](http://arxiv.org/abs/2606.16769v1) | 代理技能通常以SKILL.md文件的形式分发：描述工作流程、工具、资源和领域约定的人类可读程序文档。虽然便于检查和重用，但此设计需要将相同的可重用过程反复注入到运行时上下文中。代码将在验收后发布。 | MIT、TRI | Tianyi Zhang |
| 10 | [A First-Principles Derivation of LLM Policy Optimization: Fr…](http://arxiv.org/abs/2606.16733v1) | 语言模型的策略梯度算法优化了相同的目标$ J (θ) =\ mathbb {E} * {τ\ sim p * θ (τ)} [R (τ)] $ ，它正好有两个因素：轨迹概率$ p_θ (τ) $和奖励… | CAS | Jianghan Shen |
| 11 | [AgentFairBench: Do LLM Agents Discriminate When They Act?](http://arxiv.org/abs/2606.16723v1) | 大型语言模型（ LLM ）专员越来越多地采取行动（筛选申请人，推荐学分，对患者进行分类） ，但LLM的公平性仍然通过评分答案来衡量。我们引入了AgentFairBench ，这是一个廉价、可重复、多领… | FAIR、MIT | Triveni Morla |
| 12 | [User as Code: Executable Memory for Personalized Agents](http://arxiv.org/abs/2606.16707v1) | 个性化的人工智能代理需要用户记忆：用户是谁的持久模型，建立在许多对话中，并在每个新对话中进行咨询。如今，这种记忆几乎总是以非结构化文本、知识图或事实的平面存储形式存储，并通过检索进行查询--获取与当前… | Mila、TRI | Bojie Li |
| 13 | [Multimodal Evaluator Preference Collapse: Cross-Modal Contag…](http://arxiv.org/abs/2606.16682v1) | 当人工智能代理使用语言模型在反馈循环中评估自己的输出时，就会出现系统偏差。我们表明，评估者偏好崩溃（ EPC ）在多模态环境中显着放大。引入评价者身份索引的传染矩阵，发布MM-EPC实验框架，确定跨模… | HIT、TRI | Zewen Liu |
| 14 | [The Integrator Advantage: Controlled Agentic AI for Small an…](http://arxiv.org/abs/2606.16649v1) | Agentic AI标志着企业自动化的新阶段。与传统的自动化或对话式人工智能不同，代理系统可以解释目标、规划多步骤任务、访问工具、与企业系统交互以及执行具有不同程度自主性的工作流程。本文得出的结论是，… | CAS | Christopner Koch |
| 15 | [CoffeeBench: Benchmarking Long-Horizon LLM Agents in Heterog…](http://arxiv.org/abs/2606.16613v1) | 随着法学硕士代理商越来越能够胜任长期任务，评估他们在经济体系中的表现变得越来越重要。与主要评估与被动环境交互的单个座席的现有基准不同，经济系统本质上是多座席的，需要自主座席在长期追求自己的目标的同时进… | CAS | Issa Sugiura |
| 16 | [ARB4WM: An Adversarial Robustness Benchmark for World Models…](http://arxiv.org/abs/2606.16605v1) | 世界模型广泛应用于机器人和代理工程控制系统中，因为它们能够学习规划和决策的潜在动力学。随着这些系统越来越多地部署在安全关键环境中，了解其在对抗条件下的鲁棒性已变得至关重要。源代码可在https://g… | DeepMind、MIT | Junjian Zhang |
| 17 | [VeriGraph: Towards Verifiable Data-Analytic Agents](http://arxiv.org/abs/2606.16603v1) | 基于LLM的代理在数据密集型分析任务中表现出强大的能力，但他们的输出很少可验证：依赖线性文本轨迹使他们的推理难以审核。特别是，对原始数据的确定性计算和对自然语言主张的语义推断往往纠缠在非结构化流中，使… | MIT | Jiajie Jin |
| 18 | [Infant Spontaneous Movement Noise Improves Exploration in De…](http://arxiv.org/abs/2606.16590v1) | 深度强化学习（ RL ）中的探索通常以时间不相关白噪声的形式实施。然而，最近的工作表明，时间相关的有色噪声可以通过产生更好的状态空间覆盖的平滑轨迹来提高勘探效率。我们的代码可在https://gith… | HIT、TRI | Francisco M. López |

### 论文详情

<details>
<summary><b>1. TokenPilot: Cache-Efficient Context Management for LLM Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Buqiang Xu、Zirui Xue、Dianmou Chen、Chenyang Fu、Chiyu Wu 等（共 15 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | ZJU |
| **发布时间** | 2026-06-15T17:46:50Z |
| **关键词** | `LLM Agent` · `Memory` |
| **原文链接** | [http://arxiv.org/abs/2606.17016v1](http://arxiv.org/abs/2606.17016v1) |

**📝 摘要概括：**

> 随着LLM代理在长时间会话中部署，上下文积累会推高推理成本。现有方法利用文本修剪或动态内存逐出来最小化令牌足迹；然而，它们不受约束的序列突变改变了布局，引入了前缀不匹配和缓存失效。TokenPilot已集成到LightMem2中，网址为https://github.com/zjunlp/LightMem2。

</details>

<details>
<summary><b>2. Bayesian Inference and Decision Audits for Public Archives of Frontier AI Evaluations</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Yanan Long |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-06-15T17:38:39Z |
| **关键词** | `Agentic` · `Benchmark` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2606.17005v1](http://arxiv.org/abs/2606.17005v1) |

**📝 摘要概括：**

> 公开的人工智能评估通常被解读为终端排行榜，但潜在的证据是由报告规则、基准修订和缺失形成的选择性时间序列。LiveBench和Open LLM Leaderboard v2的重复公共档案作为主要纵向记录； LMArena提供偏好压力测试； GAIA和tau-bench提供有限的代理试点。归档和裁决协议重建公共……

</details>

<details>
<summary><b>3. Agent trajectories as programs: fingerprinting and programming coding-agent behavior</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Hamidah Oderinwale |
| **所属机构** | （详见原文） |
| **顶级机构标签** | Mila、TRI |
| **发布时间** | 2026-06-15T17:28:41Z |
| **关键词** | `Benchmark` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2606.16988v1](http://arxiv.org/abs/2606.16988v1) |

**📝 摘要概括：**

> 基准分数告诉你客服代表做对了什么；他们不会告诉你它是如何到达那里的。在这项工作中，我们介绍了在不同上下文中程序性地比较代理的方法，其中模型、任务和方法各不相同。我们相信这项工作有一系列应用程序可以帮助开发人员使用和编程编码代理，例如任务感知模型路由、代理监控和细粒度成本分析。

</details>

<details>
<summary><b>4. Consensus-based Agentic Large Language Model Framework for Harmonized Tariff Schedule Code Classification</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Truong Thanh Hung Nguyen、Khanh Van Quynh Nguyen、Hoang-Loc Cao、Tri Duong、Phuc Ho 等（共 8 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-06-15T17:24:07Z |
| **关键词** | `Multi-Agent` · `Agentic` · `Reasoning` · `Retrieval` · `Workflow` |
| **原文链接** | [http://arxiv.org/abs/2606.16987v1](http://arxiv.org/abs/2606.16987v1) |

**📝 摘要概括：**

> 准确的统一关税表（ HTS ）代码分类对于海运物流中的清关、关税评估、贸易统计和监管合规至关重要。然而，确切的高温超导分类仍然具有挑战性，因为产品描述通常简短、不完整或模棱两可，而正确的分类取决于等级关税结构、法律说明和特定司法管辖区的规则。我们的代码可在以下网址获得……

</details>

<details>
<summary><b>5. A Unified Causal-Origin Taxonomy of Distributional Shifts in Reinforcement Learning</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Ardianto Wibowo、Paulo E Santos、Amer Baghdadi、Matthew Stephenson、Karl Sammut 等（共 6 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-06-15T16:32:40Z |
| **关键词** | `Reinforcement Learning` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2606.16933v1](http://arxiv.org/abs/2606.16933v1) |

**📝 摘要概括：**

> 当操作条件与以前遇到的不同时，强化学习（ RL ）系统通常会退化，这反映了底层数据生成过程中的分布变化。这种转变可能发生在训练和评估之间，例如在分布内（ ID ）和分布外（ OOD ）泛化中，或者在环境动态随时间演变的非平稳环境中。通过在因果关系中接地分配转移…

</details>

<details>
<summary><b>6. Binary Tracking for Spatial QA and Navigation with Open Vision-Language Models</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Dongbin Na、Chanwoo Kim、Soonbin Rho、Giyun Choi、Gangbok Lee 等（共 6 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-06-15T16:10:03Z |
| **关键词** | `Reasoning` · `RAG` · `Retrieval` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2606.16902v1](http://arxiv.org/abs/2606.16902v1) |

**📝 摘要概括：**

> 这项工作解决了服务机器人穿越长距离自我中心路线的空间问答问题。给定一个查询，例如“在回家的路上在哪里可以找到干洗店？” ，系统会返回一个指标坐标，下游导航组件可以根据该坐标采取行动。源代码和数据集可在https://github.com/ndb796/BinaryTracking上公开获得

</details>

<details>
<summary><b>7. Semantic Flip: Synthetic OOD Generation for Robust Refusal in Embodied Question Answering and Spatial Localization</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Dongbin Na、Chanwoo Kim、Giyun Choi、Dooyoung Hong |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-06-15T16:07:24Z |
| **关键词** | `Reasoning` · `Benchmark` · `Embodied AI` · `Memory` |
| **原文链接** | [http://arxiv.org/abs/2606.16898v1](http://arxiv.org/abs/2606.16898v1) |

**📝 摘要概括：**

> 检测无法回答的用户查询对于可靠部署真实世界的具体化代理仍然至关重要。然而，现代视觉语言模型（ VLM ）通常会生成过于自信的答案，即使可用的视觉记忆无法支持查询。源代码和数据集可在https://github.com/ndb796/SemanticFlip上公开获得。

</details>

<details>
<summary><b>8. LabOSBench: Benchmarking Computer Use Agents for Scientific Instrument Control</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Anqi Zou、Han Deng、Chengyu Zhang、Junquan Hu、Yu Wang 等（共 12 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT |
| **发布时间** | 2026-06-15T14:42:33Z |
| **关键词** | `Agentic` · `Benchmark` · `Evaluation` · `Workflow` |
| **原文链接** | [http://arxiv.org/abs/2606.16802v1](http://arxiv.org/abs/2606.16802v1) |

**📝 摘要概括：**

> 当前的计算机使用基准主要关注虚拟化系统中的软件操作任务，而科学仪器场景需要对复杂接口进行协调控制，以及反馈驱动的参数调整。然而，由于成本高、安全风险大、可及性有限以及难以确保评估的可重复性，在物理高精度仪器上直接评估试剂是不切实际的。总体而言， LabO…

</details>

<details>
<summary><b>9. Skill-to-LoRA: From Using Skills to Learning Behaviors for Token-Efficient LLM Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Tianyi Zhang、Zhonghao Qi |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-06-15T14:17:39Z |
| **关键词** | `LLM Agent` · `Workflow` |
| **原文链接** | [http://arxiv.org/abs/2606.16769v1](http://arxiv.org/abs/2606.16769v1) |

**📝 摘要概括：**

> 代理技能通常以SKILL.md文件的形式分发：描述工作流程、工具、资源和领域约定的人类可读程序文档。虽然便于检查和重用，但此设计需要将相同的可重用过程反复注入到运行时上下文中。代码将在验收后发布。

</details>

<details>
<summary><b>10. A First-Principles Derivation of LLM Policy Optimization: From Expected Reward to GRPO and Its Structural Extensions</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Jianghan Shen、Siqi Luo、Yue Li、Jiyao Liu、Wanying Qu 等（共 12 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | CAS |
| **发布时间** | 2026-06-15T13:55:23Z |
| **关键词** | `Agentic` |
| **原文链接** | [http://arxiv.org/abs/2606.16733v1](http://arxiv.org/abs/2606.16733v1) |

**📝 摘要概括：**

> 语言模型的策略梯度算法优化了相同的目标$ J (θ) =\ mathbb {E} * {τ\ sim p * θ (τ)} [R (τ)] $ ，它正好有两个因素：轨迹概率$ p_θ (τ) $和奖励$ R (τ) $。从REFINE到PPO到GRPO及其后代的每种方法都会修改一个或两个因素，以解决前述配方中的特定故障。由此地图标记确定的边界情况和耦合故障，其中现有解决方案…

</details>

<details>
<summary><b>11. AgentFairBench: Do LLM Agents Discriminate When They Act?</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Triveni Morla、Rohith Reddy Bellibaltu、Manpreet Singh、Manmeet Singh Kapoor |
| **所属机构** | （详见原文） |
| **顶级机构标签** | FAIR、MIT、TRI |
| **发布时间** | 2026-06-15T13:50:26Z |
| **关键词** | `Multi-Agent` · `LLM Agent` · `Benchmark` · `Chain-of-Thought` |
| **原文链接** | [http://arxiv.org/abs/2606.16723v1](http://arxiv.org/abs/2606.16723v1) |

**📝 摘要概括：**

> 大型语言模型（ LLM ）专员越来越多地采取行动（筛选申请人，推荐学分，对患者进行分类） ，但LLM的公平性仍然通过评分答案来衡量。我们引入了AgentFairBench ，这是一个廉价、可重复、多领域的基准，用于衡量LLM代理人行动中的人口差异。代码、数据和线束在开放许可下发布，并带有匿名审阅制品。

</details>

<details>
<summary><b>12. User as Code: Executable Memory for Personalized Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Bojie Li |
| **所属机构** | （详见原文） |
| **顶级机构标签** | Mila、TRI |
| **发布时间** | 2026-06-15T13:39:41Z |
| **关键词** | `AI Agent` · `Reasoning` · `Retrieval` · `Benchmark` · `Memory` |
| **原文链接** | [http://arxiv.org/abs/2606.16707v1](http://arxiv.org/abs/2606.16707v1) |

**📝 摘要概括：**

> 个性化的人工智能代理需要用户记忆：用户是谁的持久模型，建立在许多对话中，并在每个新对话中进行咨询。如今，这种记忆几乎总是以非结构化文本、知识图或事实的平面存储形式存储，并通过检索进行查询--获取与当前请求最相似的条目。由于其规则每当状态发生变化时都会确定性地执行，因此UaC可以在未经请求的情况下……

</details>

<details>
<summary><b>13. Multimodal Evaluator Preference Collapse: Cross-Modal Contagion in Self-Evolving Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Zewen Liu |
| **所属机构** | （详见原文） |
| **顶级机构标签** | HIT、TRI |
| **发布时间** | 2026-06-15T13:18:20Z |
| **关键词** | `AI Agent` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2606.16682v1](http://arxiv.org/abs/2606.16682v1) |

**📝 摘要概括：**

> 当人工智能代理使用语言模型在反馈循环中评估自己的输出时，就会出现系统偏差。我们表明，评估者偏好崩溃（ EPC ）在多模态环境中显着放大。引入评价者身份索引的传染矩阵，发布MM-EPC实验框架，确定跨模型评价者架构为偏好传染的主要风险因素。

</details>

<details>
<summary><b>14. The Integrator Advantage: Controlled Agentic AI for Small and Medium-Sized Companies</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Christopner Koch、Joshua A. Wellbrock |
| **所属机构** | （详见原文） |
| **顶级机构标签** | CAS |
| **发布时间** | 2026-06-15T12:38:53Z |
| **关键词** | `Agentic` · `Workflow` |
| **原文链接** | [http://arxiv.org/abs/2606.16649v1](http://arxiv.org/abs/2606.16649v1) |

**📝 摘要概括：**

> Agentic AI标志着企业自动化的新阶段。与传统的自动化或对话式人工智能不同，代理系统可以解释目标、规划多步骤任务、访问工具、与企业系统交互以及执行具有不同程度自主性的工作流程。本文得出的结论是，当Agentic AI作为以人为中心的能力实施时，可以成为一个生产力杠杆，并由人们保留责任和问责制。

</details>

<details>
<summary><b>15. CoffeeBench: Benchmarking Long-Horizon LLM Agents in Heterogeneous Multi-Agent Economies</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Issa Sugiura、Daichi Hattori、Kazuo Araragi、Keita Ogawa、Shota Onose 等（共 8 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | CAS |
| **发布时间** | 2026-06-15T12:04:44Z |
| **关键词** | `Multi-Agent` · `LLM Agent` · `Benchmark` · `Simulation` |
| **原文链接** | [http://arxiv.org/abs/2606.16613v1](http://arxiv.org/abs/2606.16613v1) |

**📝 摘要概括：**

> 随着法学硕士代理商越来越能够胜任长期任务，评估他们在经济体系中的表现变得越来越重要。与主要评估与被动环境交互的单个座席的现有基准不同，经济系统本质上是多座席的，需要自主座席在长期追求自己的目标的同时进行沟通、谈判和交易。我们发布代码和……

</details>

<details>
<summary><b>16. ARB4WM: An Adversarial Robustness Benchmark for World Models in Continuous Control</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Junjian Zhang、Hao Tan、Ruonan Li、Dong Zhu、Aiping Li 等（共 6 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | DeepMind、MIT、HIT |
| **发布时间** | 2026-06-15T11:51:19Z |
| **关键词** | `Agentic` · `Planning` · `Benchmark` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2606.16605v1](http://arxiv.org/abs/2606.16605v1) |

**📝 摘要概括：**

> 世界模型广泛应用于机器人和代理工程控制系统中，因为它们能够学习规划和决策的潜在动力学。随着这些系统越来越多地部署在安全关键环境中，了解其在对抗条件下的鲁棒性已变得至关重要。源代码可在https://github.com/zaoanguai/ARB4WM上获得。

</details>

<details>
<summary><b>17. VeriGraph: Towards Verifiable Data-Analytic Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Jiajie Jin、Zhao Yang、Wenle Liao、Yuyang Hu、Guanting Dong 等（共 8 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT |
| **发布时间** | 2026-06-15T11:50:56Z |
| **关键词** | `Reasoning` · `Benchmark` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2606.16603v1](http://arxiv.org/abs/2606.16603v1) |

**📝 摘要概括：**

> 基于LLM的代理在数据密集型分析任务中表现出强大的能力，但他们的输出很少可验证：依赖线性文本轨迹使他们的推理难以审核。特别是，对原始数据的确定性计算和对自然语言主张的语义推断往往纠缠在非结构化流中，使得数值结论难以重现，定性判断难以……

</details>

<details>
<summary><b>18. Infant Spontaneous Movement Noise Improves Exploration in Deep RL</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Francisco M. López、Markus R. Ernst、Francisco Cruz、Matej Hoffmann、and Jochen Triesch |
| **所属机构** | （详见原文） |
| **顶级机构标签** | HIT、TRI |
| **发布时间** | 2026-06-15T11:35:06Z |
| **关键词** | `Reinforcement Learning` · `RAG` |
| **原文链接** | [http://arxiv.org/abs/2606.16590v1](http://arxiv.org/abs/2606.16590v1) |

**📝 摘要概括：**

> 深度强化学习（ RL ）中的探索通常以时间不相关白噪声的形式实施。然而，最近的工作表明，时间相关的有色噪声可以通过产生更好的状态空间覆盖的平滑轨迹来提高勘探效率。我们的代码可在https://github.com/trieschlab/baby-noise-rl上找到。

</details>

## 🗄️ 历史归档

| 日期 | 论文数 | 报告链接 |
|------|--------|----------|
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
| 2026-05-19 | 0 篇 | [2026-05-19.md](daily/2026-05-19.md) |
| 2026-05-17 | 0 篇 | [2026-05-17.md](daily/2026-05-17.md) |

## 🏛️ 顶级机构覆盖范围

覆盖超过 **70 个**顶级 AI 机构，包括：

- **科技公司：** Microsoft、Google DeepMind、OpenAI、Anthropic、Meta AI、NVIDIA、Baidu、Alibaba、ByteDance 等
- **北美顶级大学：** MIT、Stanford、CMU、UC Berkeley、Harvard、Princeton、Cornell、Caltech 等
- **中国顶级大学/机构：** 清华大学、北京大学、浙大、上交大、复旦、中科院、MSRA 等
- **欧洲/其他：** Oxford、Cambridge、ETH Zurich、Mila、NUS、KAIST 等

---

*由 [clawBot DailyFindings](https://github.com/Jacob-biu/clawBot) 自动维护 | 最后更新：2026-06-16 23:24 UTC*
