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

## 📅 今日论文 — 2026-11-21　　[→ 查看完整报告](daily/2026-11-21.md)

> 共筛选出 **16** 篇论文 | 更新于 2026-11-21 03:01 UTC

### 论文目录与概要

| # | 论文标题 | 核心概要 | 来源机构 | 第一作者 |
|---|---------|---------|---------|--------|
| 1 | [PlayCraft: Designing Engaging Games from Agent Play Experien…](http://arxiv.org/abs/2611.26624v1) | 近期的 AI 智能体可以生成可玩的游戏，但这些游戏不一定有吸引力。精通是吸引力的关键来源，但要为此进行设计，则需要大量的人类游玩和调整。在每个智能设置下，它在每个指标的宏观平均值上也优于基线。 | TRI | Weihao Cheng |
| 2 | [TideCache: Efficient Hybrid LLM Serving with Transparent Cac…](http://arxiv.org/abs/2611.26619v1) | 混合架构已成为开放权重语言模型的主流。它们的全局注意力层和有界状态层维护着异构缓存，这些缓存的需求随上下文长度和并发性而变化。TideCache 在 SGLang 中实现，并在 GB300 和 GH2… | HIT、TRI | Jinbin Luo |
| 3 | [SoK: Assessing the Evolution of LLM Capability in Software V…](http://arxiv.org/abs/2611.26601v1) | 基于LLM的代理在发现、验证和修补真实软件中的漏洞方面正变得越来越有能力，供应商和研究人员报告称，这已经在改变发现和修补漏洞的方式。然而，这些说法散见于各种论文、供应商报告和披露中，很少具有可比性。我… | MIT、TRI | Amine Lbath |
| 4 | [Cost-Aware Agentic Feature Optimization System for Fleet-Sca…](http://arxiv.org/abs/2611.26531v1) | 大型网络平台运行着庞大的排名模型群，每个模型都从包含数万个特征的共享池中选择特征。我们提出了一种端到端代理系统，该系统在各模型共享的资源约束以及各模型单独设定的资源约束（例如，分别为特征管道成本和服务… | TRI | Chang Yang |
| 5 | [Backtracking Agent Applications Security Incidents](http://arxiv.org/abs/2611.26525v1) | 代理应用程序的部署日益增多，但针对代理的攻击对其构成了实实在在的威胁。发生安全事件时，组织会回溯以识别 CEP（入侵入口点），修复损害并防止其再次发生。对八起攻击事件中五款热门代理应用程序的案例研究表… | FAIR、MIT | Yicheng Cai |
| 6 | [Grid Cells as Spectral Successor Features: A Reusable Basis …](http://arxiv.org/abs/2611.26504v1) | 持续性强化学习要求智能体在任务发生变化时能够适应，同时重用它们对环境的了解。后继特征将动态与任务特定奖励区分开来，但它们的有效性取决于基特征的选择。在一个双目标网格世界中，以均匀随机游走作为参考策略，… | TRI | Élodie Côté-Gauthier |
| 7 | [Mind2Act World: A Diagnostic Benchmark for Embodied Mind, Ph…](http://arxiv.org/abs/2611.26444v1) | 具身智能旨在让机器人以类似人类的适应性和可靠性来执行复杂的物理任务，这需要三种相辅相成的能力：基于历史的认知推理、精确及时的物理执行，以及通过环境反馈将推理和执行结合起来。然而，现有的基准要么在同一项… | TRI | Yuzhi Huang |
| 8 | [Seer: Guiding Small Deep-Research Agents with Shared Decisio…](http://arxiv.org/abs/2611.26423v1) | 深度研究代理会反复决定要搜索、阅读和验证的内容，通常使用大型云托管语言模型来提出行动建议。然而，隐私和本地控制促使代理在用户设备上运行，而有限的内存和计算能力更适合较小的模型，并使设备上的训练变得复杂… | MIT | Yuhao Zhou |
| 9 | [ZeroVLN: Learning to Navigate without Supervised Fine-Tuning…](http://arxiv.org/abs/2611.26414v1) | 具有代表性的视觉-语言导航（VLN）方法通常将视觉-语言模型（VLM）大脑与可学习的动作头相结合，并在导航领域数据上对VLM大脑进行微调，以预测几何目标。然而，这种适配可能会大幅改变基础 VLM 的权… | TRI | Zixuan Huang |
| 10 | [Democratizing Cross-Project Knowledge for Transforming Water…](http://arxiv.org/abs/2611.26398v1) | 欧盟资助的项目以交付成果、报告和案例研究的形式提供大量证据。然而，这些知识通常分散在各个项目和文档结构中，因此在做出决策时很难找到相关的情境信息。在语料库的检索基准测试中，与单领域嵌入基线相比，所提出… | CAS、TRI | Oriol Alàs |
| 11 | [Perfumer: A Large Language Model-based Agentic Framework Acc…](http://arxiv.org/abs/2611.26349v1) | 第一性原理结构弛豫和能带计算需要大量的计算和专业知识。本文介绍Perfumer，这是一个基于大型语言模型的代理框架，将Quantum ESPRESSO与两个预测模型相结合。该代理将自然语言请求转换为从… | MIT、NTU | Zhiwei Li |
| 12 | [Context as a Resource](http://arxiv.org/abs/2611.26346v1) | 跨多个独立代理会话管理并发任务会很快耗尽人类的注意力，因此需要借助单个连续界面背后的全天候个人代理。然而，当每个上下文都共享相同的冻结主干权重时，将交错对话和外部事件导入一个线性会话中，会导致跨主题约… | HIT、TRI | Xufei Tian |
| 13 | [DeepQuest: From Knowledge Gaps to Scientific Discovery in Al…](http://arxiv.org/abs/2611.26343v1) | 实验自动化并不一定能推进科学认识。研究代理必须识别有意义的知识缺口，确定哪些可用数据可以解决问题，并评估其研究结果是否能推进现有知识。我们的源代码可在 https://anonymous.4open.… | TRI | Chunbo Jiang |
| 14 | [SKILL.PNG: Learning Agent Skills in Pixel Space](http://arxiv.org/abs/2611.26296v1) | AI 代理通常使用技能（即置于其上下文中的自然语言指令）来针对新任务和领域进行专业化。我们的代码可在此处获取： https://github.com/omseeth/skill.png | MIT | Maximilian Seeth |
| 15 | [SkillBridge: Cost-Aware Diagnosis and Repair of Cross-OS Com…](http://arxiv.org/abs/2611.26256v1) | LLM 代理越来越多地通过技能重复使用可执行功能，但适用于某个操作系统的技能可能在另一个操作系统上失败，因为操作系统假设分散在指南文本、脚本、元数据、安装合约和本地入口点中。通过在每个操作系统上运行每… | CAS | Anjie Xu |
| 16 | [The Stability Gap in Continual Reinforcement Learning](http://arxiv.org/abs/2611.26252v1) | 持续强化学习（CRL）旨在使智能体能够适应不断变化的任务，同时保留先前习得的能力。评估通常依赖于最终的聚合指标，这些指标可能会掩盖适应过程中的暂时性性能下降。尽管智能体可以完全访问过去的任务，但仍会出… | TRI | Sebastian Pusch |

### 论文详情

<details>
<summary><b>1. PlayCraft: Designing Engaging Games from Agent Play Experience</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Weihao Cheng |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-11-19T18:59:34Z |
| **关键词** | `AI Agent` · `RAG` · `Memory` |
| **原文链接** | [http://arxiv.org/abs/2611.26624v1](http://arxiv.org/abs/2611.26624v1) |

**📝 摘要概括：**

> 近期的 AI 智能体可以生成可玩的游戏，但这些游戏不一定有吸引力。精通是吸引力的关键来源，但要为此进行设计，则需要大量的人类游玩和调整。在每个智能设置下，它在每个指标的宏观平均值上也优于基线。

</details>

<details>
<summary><b>2. TideCache: Efficient Hybrid LLM Serving with Transparent Cache Management and Layer-Wise Streaming</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Jinbin Luo、Xiaozhe Yao、Shang Yang、Zhijian Liu、Song Han 等（共 6 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | HIT、TRI |
| **发布时间** | 2026-11-19T18:58:31Z |
| **关键词** | `Memory` |
| **原文链接** | [http://arxiv.org/abs/2611.26619v1](http://arxiv.org/abs/2611.26619v1) |

**📝 摘要概括：**

> 混合架构已成为开放权重语言模型的主流。它们的全局注意力层和有界状态层维护着异构缓存，这些缓存的需求随上下文长度和并发性而变化。TideCache 在 SGLang 中实现，并在 GB300 和 GH200 上跨七种模型/平台配置进行了评估，它可完成多达 2.04 倍的代理轮次，将整体 P50 每令牌延迟降低 20--59%，并将代理 P50 TTFT 提升 1.40…

</details>

<details>
<summary><b>3. SoK: Assessing the Evolution of LLM Capability in Software Vulnerability Research</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Amine Lbath、Manan Suri、Aurelien Delaitre、Vadim Okun、Massih-Reza Amini 等（共 6 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-11-19T18:54:19Z |
| **关键词** | — |
| **原文链接** | [http://arxiv.org/abs/2611.26601v1](http://arxiv.org/abs/2611.26601v1) |

**📝 摘要概括：**

> 基于LLM的代理在发现、验证和修补真实软件中的漏洞方面正变得越来越有能力，供应商和研究人员报告称，这已经在改变发现和修补漏洞的方式。然而，这些说法散见于各种论文、供应商报告和披露中，很少具有可比性。我们使用明确的评分细则对文献中提出的缓解措施进行评分，并为每个群体制定指导……

</details>

<details>
<summary><b>4. Cost-Aware Agentic Feature Optimization System for Fleet-Scale Ranking Models</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Chang Yang、Yao Xuan、Wendan Yan、Nhat Le、Jiang Liu 等（共 9 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-11-19T18:12:04Z |
| **关键词** | `LLM Agent` · `Agentic` · `RAG` |
| **原文链接** | [http://arxiv.org/abs/2611.26531v1](http://arxiv.org/abs/2611.26531v1) |

**📝 摘要概括：**

> 大型网络平台运行着庞大的排名模型群，每个模型都从包含数万个特征的共享池中选择特征。我们提出了一种端到端代理系统，该系统在各模型共享的资源约束以及各模型单独设定的资源约束（例如，分别为特征管道成本和服务吞吐量（QPS））下，对整个模型群的特征进行优化。经过优化的模型已上线，在在线A/B测试中，它们改善了一项主要的在线指标……

</details>

<details>
<summary><b>5. Backtracking Agent Applications Security Incidents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Yicheng Cai、Taegyu Kim、Peng Liu |
| **所属机构** | （详见原文） |
| **顶级机构标签** | FAIR、MIT、CAS |
| **发布时间** | 2026-11-19T18:01:28Z |
| **关键词** | — |
| **原文链接** | [http://arxiv.org/abs/2611.26525v1](http://arxiv.org/abs/2611.26525v1) |

**📝 摘要概括：**

> 代理应用程序的部署日益增多，但针对代理的攻击对其构成了实实在在的威胁。发生安全事件时，组织会回溯以识别 CEP（入侵入口点），修复损害并防止其再次发生。对八起攻击事件中五款热门代理应用程序的案例研究表明，使用 Origin 的分析师能够正确识别所有 CEP。

</details>

<details>
<summary><b>6. Grid Cells as Spectral Successor Features: A Reusable Basis for Continual Reinforcement Learning</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Élodie Côté-Gauthier、Doina Precup、Isabeau Prémont-Schwarz |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-11-19T17:54:04Z |
| **关键词** | `Reinforcement Learning` |
| **原文链接** | [http://arxiv.org/abs/2611.26504v1](http://arxiv.org/abs/2611.26504v1) |

**📝 摘要概括：**

> 持续性强化学习要求智能体在任务发生变化时能够适应，同时重用它们对环境的了解。后继特征将动态与任务特定奖励区分开来，但它们的有效性取决于基特征的选择。在一个双目标网格世界中，以均匀随机游走作为参考策略，其特征向量是低频拉普拉斯特征向量，以这种方式构建的智能体能够保持接近最大值的回报……

</details>

<details>
<summary><b>7. Mind2Act World: A Diagnostic Benchmark for Embodied Mind, Physical Action, and Mind-Action Composition in Robotic Manipulation</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Yuzhi Huang、Jie Wu、Fanding Huang、Junchao Lin、Weichen Zhang 等（共 43 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-11-19T17:15:38Z |
| **关键词** | `Reasoning` · `Benchmark` · `Evaluation` · `Embodied AI` |
| **原文链接** | [http://arxiv.org/abs/2611.26444v1](http://arxiv.org/abs/2611.26444v1) |

**📝 摘要概括：**

> 具身智能旨在让机器人以类似人类的适应性和可靠性来执行复杂的物理任务，这需要三种相辅相成的能力：基于历史的认知推理、精确及时的物理执行，以及通过环境反馈将推理和执行结合起来。然而，现有的基准要么在同一项任务中评估推理和执行，要么在没有它们……的情况下分别评估它们。

</details>

<details>
<summary><b>8. Seer: Guiding Small Deep-Research Agents with Shared Decision Models</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Yuhao Zhou、Yang Zhou、Yuanxi Li、Jindi Lv、Dan Si 等（共 7 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT |
| **发布时间** | 2026-11-19T17:03:24Z |
| **关键词** | `RAG` · `Benchmark` · `Evaluation` · `Simulation` · `Memory` |
| **原文链接** | [http://arxiv.org/abs/2611.26423v1](http://arxiv.org/abs/2611.26423v1) |

**📝 摘要概括：**

> 深度研究代理会反复决定要搜索、阅读和验证的内容，通常使用大型云托管语言模型来提出行动建议。然而，隐私和本地控制促使代理在用户设备上运行，而有限的内存和计算能力更适合较小的模型，并使设备上的训练变得复杂。这些发现凸显了可重复使用模型在预测和评估方面的潜力，通过额外的本地……来增强小型研究代理。

</details>

<details>
<summary><b>9. ZeroVLN: Learning to Navigate without Supervised Fine-Tuning of the VLM Brain</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Zixuan Huang、Yang Zhou、Guli Zhang、Sunzhu Li、Hongyan Xie 等（共 11 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-11-19T17:01:00Z |
| **关键词** | `Agentic` · `Reinforcement Learning` · `Benchmark` · `Fine-tuning` |
| **原文链接** | [http://arxiv.org/abs/2611.26414v1](http://arxiv.org/abs/2611.26414v1) |

**📝 摘要概括：**

> 具有代表性的视觉-语言导航（VLN）方法通常将视觉-语言模型（VLM）大脑与可学习的动作头相结合，并在导航领域数据上对VLM大脑进行微调，以预测几何目标。然而，这种适配可能会大幅改变基础 VLM 的权重，并削弱一般视觉能力。据我们所知，ZeroVLN 是首个慢-快 VLN 框架，VLM 脑的导航域 SFT 为零，并且……

</details>

<details>
<summary><b>10. Democratizing Cross-Project Knowledge for Transforming Water Governance and Climate Resilience: an Agentic AI Ecosystem</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Oriol Alàs、Ian Palacín、Iván Cester、Edgar Rubión |
| **所属机构** | （详见原文） |
| **顶级机构标签** | CAS、TRI |
| **发布时间** | 2026-11-19T16:49:04Z |
| **关键词** | `Agentic` · `Retrieval` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2611.26398v1](http://arxiv.org/abs/2611.26398v1) |

**📝 摘要概括：**

> 欧盟资助的项目以交付成果、报告和案例研究的形式提供大量证据。然而，这些知识通常分散在各个项目和文档结构中，因此在做出决策时很难找到相关的情境信息。在语料库的检索基准测试中，与单领域嵌入基线相比，所提出的方法将平均倒数排名（MRR）提高了26.7%（相对值），这表明……

</details>

<details>
<summary><b>11. Perfumer: A Large Language Model-based Agentic Framework Accelerating Structural Relaxation and Electronic Band Prediction for First-Principle Calculation</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Zhiwei Li、Yuhao Zhou、Yikai Yang、Haonan Wang、Qing Ye 等（共 7 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、NTU |
| **发布时间** | 2026-11-19T16:23:33Z |
| **关键词** | `Agentic` · `Workflow` |
| **原文链接** | [http://arxiv.org/abs/2611.26349v1](http://arxiv.org/abs/2611.26349v1) |

**📝 摘要概括：**

> 第一性原理结构弛豫和能带计算需要大量的计算和专业知识。本文介绍Perfumer，这是一个基于大型语言模型的代理框架，将Quantum ESPRESSO与两个预测模型相结合。该代理将自然语言请求转换为从弛豫到能带的工作流程，从单个上传的结构到自动构建的新候选结构，并返回预测的性质。

</details>

<details>
<summary><b>12. Context as a Resource</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Xufei Tian、Han Hu、Wenli Du |
| **所属机构** | （详见原文） |
| **顶级机构标签** | HIT、TRI |
| **发布时间** | 2026-11-19T16:19:56Z |
| **关键词** | `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2611.26346v1](http://arxiv.org/abs/2611.26346v1) |

**📝 摘要概括：**

> 跨多个独立代理会话管理并发任务会很快耗尽人类的注意力，因此需要借助单个连续界面背后的全天候个人代理。然而，当每个上下文都共享相同的冻结主干权重时，将交错对话和外部事件导入一个线性会话中，会导致跨主题约束溢出和队列头部停滞。在持续的激增流量下，ClonAct实现了最高的完成率（95.0%），同时……

</details>

<details>
<summary><b>13. DeepQuest: From Knowledge Gaps to Scientific Discovery in Alzheimer's Disease</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Chunbo Jiang、Yifei Chen、Beining Wu、Fuyou Mao、Weihong Chen 等（共 9 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-11-19T16:18:26Z |
| **关键词** | — |
| **原文链接** | [http://arxiv.org/abs/2611.26343v1](http://arxiv.org/abs/2611.26343v1) |

**📝 摘要概括：**

> 实验自动化并不一定能推进科学认识。研究代理必须识别有意义的知识缺口，确定哪些可用数据可以解决问题，并评估其研究结果是否能推进现有知识。我们的源代码可在 https://anonymous.4open.science/r/DeepQuest-3066/ 获取。

</details>

<details>
<summary><b>14. SKILL.PNG: Learning Agent Skills in Pixel Space</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Maximilian Seeth、Chengzhi Martin Hu、Marie Kempkes、Paul Röttger、Leo Schwinn |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT |
| **发布时间** | 2026-11-19T15:51:03Z |
| **关键词** | `AI Agent` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2611.26296v1](http://arxiv.org/abs/2611.26296v1) |

**📝 摘要概括：**

> AI 代理通常使用技能（即置于其上下文中的自然语言指令）来针对新任务和领域进行专业化。我们的代码可在此处获取： https://github.com/omseeth/skill.png

</details>

<details>
<summary><b>15. SkillBridge: Cost-Aware Diagnosis and Repair of Cross-OS Compatibility Defects in Agent Skills</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Anjie Xu、Zixing Wang、Yifeng Cai、Leye Wang |
| **所属机构** | （详见原文） |
| **顶级机构标签** | CAS |
| **发布时间** | 2026-11-19T15:30:28Z |
| **关键词** | `LLM Agent` · `Workflow` |
| **原文链接** | [http://arxiv.org/abs/2611.26256v1](http://arxiv.org/abs/2611.26256v1) |

**📝 摘要概括：**

> LLM 代理越来越多地通过技能重复使用可执行功能，但适用于某个操作系统的技能可能在另一个操作系统上失败，因为操作系统假设分散在指南文本、脚本、元数据、安装合约和本地入口点中。通过在每个操作系统上运行每个技能来诊断此类故障成本高昂：许多执行操作都会消耗模型令牌、运行时间和审核工作量，然后才会揭示故障是否确实与操作系统相关。回顾性……

</details>

<details>
<summary><b>16. The Stability Gap in Continual Reinforcement Learning</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Sebastian Pusch、Matthia Sabatelli、Gido M. van de Ven |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-11-19T15:26:41Z |
| **关键词** | `Reinforcement Learning` · `Benchmark` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2611.26252v1](http://arxiv.org/abs/2611.26252v1) |

**📝 摘要概括：**

> 持续强化学习（CRL）旨在使智能体能够适应不断变化的任务，同时保留先前习得的能力。评估通常依赖于最终的聚合指标，这些指标可能会掩盖适应过程中的暂时性性能下降。尽管智能体可以完全访问过去的任务，但仍会出现这种模式。

</details>

## 🗄️ 历史归档

| 日期 | 论文数 | 报告链接 |
|------|--------|----------|
| 2026-11-21 | 16 篇 | [2026-11-21.md](daily/2026-11-21.md) |
| 2026-11-20 | 20 篇 | [2026-11-20.md](daily/2026-11-20.md) |
| 2026-11-05 | 13 篇 | [2026-11-05.md](daily/2026-11-05.md) |
| 2026-11-04 | 20 篇 | [2026-11-04.md](daily/2026-11-04.md) |
| 2026-11-03 | 0 篇 | [2026-11-03.md](daily/2026-11-03.md) |
| 2026-11-02 | 0 篇 | [2026-11-02.md](daily/2026-11-02.md) |
| 2026-11-01 | 0 篇 | [2026-11-01.md](daily/2026-11-01.md) |
| 2026-10-31 | 17 篇 | [2026-10-31.md](daily/2026-10-31.md) |
| 2026-10-30 | 0 篇 | [2026-10-30.md](daily/2026-10-30.md) |
| 2026-10-29 | 20 篇 | [2026-10-29.md](daily/2026-10-29.md) |
| 2026-10-28 | 20 篇 | [2026-10-28.md](daily/2026-10-28.md) |
| 2026-10-27 | 0 篇 | [2026-10-27.md](daily/2026-10-27.md) |
| 2026-10-25 | 0 篇 | [2026-10-25.md](daily/2026-10-25.md) |
| 2026-10-24 | 0 篇 | [2026-10-24.md](daily/2026-10-24.md) |
| 2026-10-23 | 20 篇 | [2026-10-23.md](daily/2026-10-23.md) |
| 2026-10-22 | 20 篇 | [2026-10-22.md](daily/2026-10-22.md) |
| 2026-10-21 | 20 篇 | [2026-10-21.md](daily/2026-10-21.md) |
| 2026-10-20 | 0 篇 | [2026-10-20.md](daily/2026-10-20.md) |
| 2026-10-18 | 0 篇 | [2026-10-18.md](daily/2026-10-18.md) |
| 2026-10-17 | 0 篇 | [2026-10-17.md](daily/2026-10-17.md) |
| 2026-10-16 | 8 篇 | [2026-10-16.md](daily/2026-10-16.md) |
| 2026-10-15 | 20 篇 | [2026-10-15.md](daily/2026-10-15.md) |
| 2026-10-14 | 0 篇 | [2026-10-14.md](daily/2026-10-14.md) |
| 2026-10-13 | 0 篇 | [2026-10-13.md](daily/2026-10-13.md) |
| 2026-10-12 | 0 篇 | [2026-10-12.md](daily/2026-10-12.md) |
| 2026-10-11 | 0 篇 | [2026-10-11.md](daily/2026-10-11.md) |
| 2026-10-10 | 20 篇 | [2026-10-10.md](daily/2026-10-10.md) |
| 2026-10-09 | 20 篇 | [2026-10-09.md](daily/2026-10-09.md) |
| 2026-10-08 | 20 篇 | [2026-10-08.md](daily/2026-10-08.md) |
| 2026-10-07 | 20 篇 | [2026-10-07.md](daily/2026-10-07.md) |

## 🏛️ 顶级机构覆盖范围

覆盖超过 **70 个**顶级 AI 机构，包括：

- **科技公司：** Microsoft、Google DeepMind、OpenAI、Anthropic、Meta AI、NVIDIA、Baidu、Alibaba、ByteDance 等
- **北美顶级大学：** MIT、Stanford、CMU、UC Berkeley、Harvard、Princeton、Cornell、Caltech 等
- **中国顶级大学/机构：** 清华大学、北京大学、浙大、上交大、复旦、中科院、MSRA 等
- **欧洲/其他：** Oxford、Cambridge、ETH Zurich、Mila、NUS、KAIST 等

---

*由 [clawBot DailyFindings](https://github.com/Jacob-biu/clawBot) 自动维护 | 最后更新：2026-11-21 03:01 UTC*
