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

## 📅 今日论文 — 2026-07-30　　[→ 查看完整报告](daily/2026-07-30.md)

> 共筛选出 **16** 篇论文 | 更新于 2026-07-30 23:05 UTC

### 论文目录与概要

| # | 论文标题 | 核心概要 | 来源机构 | 第一作者 |
|---|---------|---------|---------|--------|
| 1 | [Can AI agents conduct open-ended AI research? Early evidence…](http://arxiv.org/abs/2607.27191v1) | 人工智能爆炸性进展的预测取决于人工智能代理自动化人工智能研究。但是，关于智能体是否可以进行开放式人工智能研究的证据很少。我们的研究结果提供了早期证据，证明当今的代理可以进行人工智能研究工程，但与研究生… | MIT、CAS | Peter Kirgis |
| 2 | [Partner Capability Estimation for Task-Agnostic Adaptation i…](http://arxiv.org/abs/2607.27177v1) | 与新颖且多元化的合作伙伴进行有效协作是自主代理的关键技能。大多数当前的临时团队合作（ AHT ）方法都假设客服代表将在单个固定任务上进行协作，并且合作伙伴的能力，即他们成功执行所需操作的能力，已经众所… | MIT | Peter Tisnikar |
| 3 | [OmegaUse-OfficeVal: Benchmarking LLM Agents on Long-Horizon …](http://arxiv.org/abs/2607.27155v1) | 大型语言模型（ LLM ）代理越来越多地被期望帮助用户完成任务。但是，现有基准为评估客服代表是否能够以合理的成本执行办公室套房工作流程提供了有限的支持。代码和数据集是完全开源的，更多信息请访问我们的项… | MIT | Jingbo Zhou |
| 4 | [AgentMap: Joint Equivalence and Subsumption Discovery for On…](http://arxiv.org/abs/2607.27130v1) | 本体匹配（ OM ）传统上被公式化为等价发现或隶属匹配。现有的OM系统只能识别一种类型的语义对应，不能同时发现等价和隶属映射。实验结果表明， AgentMap在混合设置上取得了良好的性能，同时在性能上… | TRI | Yiping Song |
| 5 | [SciFigQual-Bench: A Benchmark for Scientific Figure Quality …](http://arxiv.org/abs/2607.27084v1) | 科学图像是提出实验结论、阐述系统架构和支持科学论文中比较论证的核心要素。然而，现有的图像质量评估（ IQA ）方法主要是针对自然照片或人工智能生成的内容而设计的，不能直接应用于科学论文。在测试子集ev… | HIT、NUS | Zihan Deng |
| 6 | [Scores Are Not Decisions: Cost-Aware Stopping for Tool Acqui…](http://arxiv.org/abs/2607.27083v1) | 随着LLM代理越来越依赖于搜索引擎、数据库和连接器等多样化的外部服务，代理利用面临着一个根本性的工具选择挑战：获取太少的工具会使任务信息不足，而太多的工具会增加成本、上下文负载和隐私泄露。路由器和检索… | TRI | Yicheng Feng |
| 7 | [MemSecBench: Tracking Agent Memory Poisoning from Persistenc…](http://arxiv.org/abs/2607.27080v1) | 内存系统允许代理保留和重复使用过去交互的信息，但它们也可以让恶意内容持续存在。攻击者精心制作的恶意指令可能会存储在长期内存中，在很长一段时间后被召回，并悄悄地形成真正的动作。这些描述性对比表明，评估的… | CAS、TRI | Xuanze Chen |
| 8 | [Setoka: A Benchmark for Hierarchical User Understanding in P…](http://arxiv.org/abs/2607.27056v1) | 个性化座席越来越多地用于帮助用户完成各种任务。有效的个性化协助不仅需要从代理记忆中存储的过去交互中检索明确的事实，还需要推断抽象的个人特征。这些发现表明，用户理解不能通过简单的事实检索来处理，这激发了… | TRI | Lingyang Zeng |
| 9 | [What Does It Take to Detect an AI Agent? Minimal Feature Set…](http://arxiv.org/abs/2607.26935v1) | 大规模部署的机器人检测器将流量视为二进制：人类或机器人。当人工智能代理通过浏览器自动化浏览网页时，这种假设就会破裂，而浏览器自动化既不是流量类，也不是二进制分类器在结构上无法表示的流量类。两个功能强大… | MIT、HIT | Vishisht Choudhary |
| 10 | [Two Calls Beat Five Agents: Evaluating Multi-Agent Pipelines…](http://arxiv.org/abs/2607.26922v1) | 多代理LLM流水线系统将任务分解为多个角色以获得更好的推理，但主要使用大规模商业模型进行基准测试。在这项研究中，我们通过在两个数据集（ GSM8K （ 500个问题）和HumanEval （ 164个… | HIT | Ashish Prajapati |
| 11 | [BioVLN: A Simulation Platform for Visual Language Navigation…](http://arxiv.org/abs/2607.26914v1) | 生物医学实验室机器人必须在执行实验程序之前导航到仪器。现有的具体化导航平台专为家庭环境而设计，将目标视为对象中心或任意附近位置。实验表明，几何勘探成功率达到74.4--87.5% ，而在作业区域抽取多… | MIT、TRI | Zhe Liu |
| 12 | [Forecasting Trajectory-Level Safety Risks in Black-Box Multi…](http://arxiv.org/abs/2607.26820v1) | 随着大型语言模型（ LLM ）从独立助理演变为自主代理，确保其安全需要超越逐点风险评估，以了解风险如何在长远轨迹中出现和展开。在多回合交互中，恶意意图可以在看似无害的回合中分解，并通过交互轨迹逐渐重建… | MIT、CAS | Shi Lin |
| 13 | [A First Look at Coding Agents' Compliance with AI Contributi…](http://arxiv.org/abs/2607.26819v1) | 开源社区充斥着人工智能产生的贡献。在国防方面，他们有书面的贡献规则来规范编码代理的行为，从全面禁止、强制披露到验证门和人工签核。这一状况表明，核实和披露问题可以通过现有机制解决，但执行禁令和人为升级仍… | TRI | Wenhao Yang |
| 14 | [SecRespond: Benchmarking AI Agents for Real-World Post-Compr…](http://arxiv.org/abs/2607.26791v1) | 大型语言模型（ LLM ）代理在现实世界的安全操作中越来越多地被采用，可以访问主机制品和命令行界面（ CLI ） ，因此彻底评估其安全能力至关重要。但是，现有的网络安全基准侧重于在发生攻击之前将代理放… | Alibaba | Lehan Wang |
| 15 | [SkillRise: Agentic Reinforcement Learning for Cross-Task Ski…](http://arxiv.org/abs/2607.26784v1) | 大型语言模型代理经常遇到相关但截然不同的任务，这些任务共享可重用的解决方案模式。然而，标准的代理强化学习将任务视为独立的情节，而现有的技能学习方法要么专注于一个任务的重复尝试，要么使用具有多个阶段的管… | TRI | Zhiyuan Yao |
| 16 | [Do Latent Channels Actually Communicate? A Causal Audit of L…](http://arxiv.org/abs/2607.26773v1) | 基于大语言模型（ LLM ）的多智能体系统（ MAS ）中的潜在通信传输的是连续的内部表示，而不是文本，但更大的表示容量并不能确定接收者使用的是与任务相关的信息。最终任务性能本身也不能揭示观察到的效果… | MIT、TRI | Huixiang Zhang |

### 论文详情

<details>
<summary><b>1. Can AI agents conduct open-ended AI research? Early evidence from two case studies</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Peter Kirgis、Sayash Kapoor、Andrew Schwartz、Stephan Rabanser、David Africa 等（共 24 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、CAS |
| **发布时间** | 2026-07-29T17:57:19Z |
| **关键词** | `AI Agent` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2607.27191v1](http://arxiv.org/abs/2607.27191v1) |

**📝 摘要概括：**

> 人工智能爆炸性进展的预测取决于人工智能代理自动化人工智能研究。但是，关于智能体是否可以进行开放式人工智能研究的证据很少。我们的研究结果提供了早期证据，证明当今的代理可以进行人工智能研究工程，但与研究生命周期的关键部分作斗争。

</details>

<details>
<summary><b>2. Partner Capability Estimation for Task-Agnostic Adaptation in Ad-Hoc Teamwork</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Peter Tisnikar、Maja Swieczkowska、Benteng Ma、Gerard Canal、Matteo Leonetti |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT |
| **发布时间** | 2026-07-29T17:50:39Z |
| **关键词** | `Multi-Agent` · `Planning` · `Simulation` |
| **原文链接** | [http://arxiv.org/abs/2607.27177v1](http://arxiv.org/abs/2607.27177v1) |

**📝 摘要概括：**

> 与新颖且多元化的合作伙伴进行有效协作是自主代理的关键技能。大多数当前的临时团队合作（ AHT ）方法都假设客服代表将在单个固定任务上进行协作，并且合作伙伴的能力，即他们成功执行所需操作的能力，已经众所周知。我们的研究结果表明，在研究的环境中，基于能力的建模是一种有前途的可解释的、与任务无关的表示。

</details>

<details>
<summary><b>3. OmegaUse-OfficeVal: Benchmarking LLM Agents on Long-Horizon Office-Suite Tasks with Economic Grounding</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Jingbo Zhou、Yusai Zhao、Qi Bao、Jingjia Cao、Zhenghai Chen 等（共 15 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT |
| **发布时间** | 2026-07-29T17:33:47Z |
| **关键词** | `LLM Agent` · `RAG` · `Benchmark` · `Evaluation` · `Workflow` |
| **原文链接** | [http://arxiv.org/abs/2607.27155v1](http://arxiv.org/abs/2607.27155v1) |

**📝 摘要概括：**

> 大型语言模型（ LLM ）代理越来越多地被期望帮助用户完成任务。但是，现有基准为评估客服代表是否能够以合理的成本执行办公室套房工作流程提供了有限的支持。代码和数据集是完全开源的，更多信息请访问我们的项目网站： https://omegause-officeval.github.io。

</details>

<details>
<summary><b>4. AgentMap: Joint Equivalence and Subsumption Discovery for Ontology Matching</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Yiping Song、Jiaoyan Chen、Renate Schmidt、Hui Yang、Wen Zhang |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-07-29T16:58:10Z |
| **关键词** | `Multi-Agent` · `Reasoning` · `Retrieval` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2607.27130v1](http://arxiv.org/abs/2607.27130v1) |

**📝 摘要概括：**

> 本体匹配（ OM ）传统上被公式化为等价发现或隶属匹配。现有的OM系统只能识别一种类型的语义对应，不能同时发现等价和隶属映射。实验结果表明， AgentMap在混合设置上取得了良好的性能，同时在性能上优于等价匹配和归纳匹配基线。

</details>

<details>
<summary><b>5. SciFigQual-Bench: A Benchmark for Scientific Figure Quality Assessment with Full-Manuscript Context</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Zihan Deng、Chuanzhi Xu、Huiqi Liang、Haoyang Li、Xiaozhen Zhong 等（共 6 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | HIT、NUS |
| **发布时间** | 2026-07-29T16:07:44Z |
| **关键词** | `RAG` · `Benchmark` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2607.27084v1](http://arxiv.org/abs/2607.27084v1) |

**📝 摘要概括：**

> 科学图像是提出实验结论、阐述系统架构和支持科学论文中比较论证的核心要素。然而，现有的图像质量评估（ IQA ）方法主要是针对自然照片或人工智能生成的内容而设计的，不能直接应用于科学论文。在测试子集eval1200和SFQ-Agent上评估了多个主流大型模型…

</details>

<details>
<summary><b>6. Scores Are Not Decisions: Cost-Aware Stopping for Tool Acquisition in LLM Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Yicheng Feng、Yan Zhang、Yan Cheng、Wei Qi |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-07-29T16:07:37Z |
| **关键词** | `LLM Agent` · `Fine-tuning` |
| **原文链接** | [http://arxiv.org/abs/2607.27083v1](http://arxiv.org/abs/2607.27083v1) |

**📝 摘要概括：**

> 随着LLM代理越来越依赖于搜索引擎、数据库和连接器等多样化的外部服务，代理利用面临着一个根本性的工具选择挑战：获取太少的工具会使任务信息不足，而太多的工具会增加成本、上下文负载和隐私泄露。路由器和检索器可以根据相关性对候选工具进行排名，但仅靠排名并不能确定值得选择的工具数量。CAM-DF系列是一种连接器……

</details>

<details>
<summary><b>7. MemSecBench: Tracking Agent Memory Poisoning from Persistence to Consequence and Repair</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Xuanze Chen、Xukang Xie、Wentao Fu、Jiajun Zhou、Shanqing Yu 等（共 6 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | CAS、TRI |
| **发布时间** | 2026-07-29T16:06:54Z |
| **关键词** | `Benchmark` · `Evaluation` · `Memory` |
| **原文链接** | [http://arxiv.org/abs/2607.27080v1](http://arxiv.org/abs/2607.27080v1) |

**📝 摘要概括：**

> 内存系统允许代理保留和重复使用过去交互的信息，但它们也可以让恶意内容持续存在。攻击者精心制作的恶意指令可能会存储在长期内存中，在很长一段时间后被召回，并悄悄地形成真正的动作。这些描述性对比表明，评估的内存系统堆栈在生命周期安全性方面存在差异，无论是在恶意内存的传播方面，还是在……之后的选择性修复方面。

</details>

<details>
<summary><b>8. Setoka: A Benchmark for Hierarchical User Understanding in Personalized Agents over Heterogeneous Data</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Lingyang Zeng、Guangze Chen、Kaichen Yu、Zhicheng Pan、Siyang Weng 等（共 12 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-07-29T15:47:40Z |
| **关键词** | `RAG` · `Retrieval` · `Benchmark` · `Evaluation` · `Memory` |
| **原文链接** | [http://arxiv.org/abs/2607.27056v1](http://arxiv.org/abs/2607.27056v1) |

**📝 摘要概括：**

> 个性化座席越来越多地用于帮助用户完成各种任务。有效的个性化协助不仅需要从代理记忆中存储的过去交互中检索明确的事实，还需要推断抽象的个人特征。这些发现表明，用户理解不能通过简单的事实检索来处理，这激发了跨源集成和抽象内存机制的设计。

</details>

<details>
<summary><b>9. What Does It Take to Detect an AI Agent? Minimal Feature Sets for Behavioral Detection under Browser Automation</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Vishisht Choudhary、Lukas Schmidt、Anne Zoë Kenntner、Feras Skhab、Michel Osswald 等（共 6 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、HIT |
| **发布时间** | 2026-07-29T14:05:26Z |
| **关键词** | `AI Agent` · `Reasoning` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2607.26935v1](http://arxiv.org/abs/2607.26935v1) |

**📝 摘要概括：**

> 大规模部署的机器人检测器将流量视为二进制：人类或机器人。当人工智能代理通过浏览器自动化浏览网页时，这种假设就会破裂，而浏览器自动化既不是流量类，也不是二进制分类器在结构上无法表示的流量类。两个功能强大地隔离了代理；五个单独的所有三个流量类在宏-F1 $\ geq 0.99 $。

</details>

<details>
<summary><b>10. Two Calls Beat Five Agents: Evaluating Multi-Agent Pipelines Against Self-Refinement for Local Language Models</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Ashish Prajapati、Om Mohite |
| **所属机构** | （详见原文） |
| **顶级机构标签** | HIT |
| **发布时间** | 2026-07-29T13:53:02Z |
| **关键词** | `Multi-Agent` · `Reasoning` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2607.26922v1](http://arxiv.org/abs/2607.26922v1) |

**📝 摘要概括：**

> 多代理LLM流水线系统将任务分解为多个角色以获得更好的推理，但主要使用大规模商业模型进行基准测试。在这项研究中，我们通过在两个数据集（ GSM8K （ 500个问题）和HumanEval （ 164个问题） ）上的本地模型Qwen2.5-7B-Instruct上部署Parishad （一个涉及五个角色的结构化多Agent系统） ，并将其与直接提示和双调用自我完善进行比较。所有代码…

</details>

<details>
<summary><b>11. BioVLN: A Simulation Platform for Visual Language Navigation in Biomedical Laboratories</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Zhe Liu、Quan Lu、Zhaohui Du、Zhe Wang、Huanbo Jin 等（共 10 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-07-29T13:44:46Z |
| **关键词** | `Evaluation` · `Simulation` · `Embodied AI` |
| **原文链接** | [http://arxiv.org/abs/2607.26914v1](http://arxiv.org/abs/2607.26914v1) |

**📝 摘要概括：**

> 生物医学实验室机器人必须在执行实验程序之前导航到仪器。现有的具体化导航平台专为家庭环境而设计，将目标视为对象中心或任意附近位置。实验表明，几何勘探成功率达到74.4--87.5% ，而在作业区域抽取多个有效位置，成功率提高到83.3--92.5% ，减少不安全接近。

</details>

<details>
<summary><b>12. Forecasting Trajectory-Level Safety Risks in Black-Box Multi-Turn Interactions</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Shi Lin、Peng Qian、Dinghao Liu、Renjie Sun、Sifan Wu 等（共 8 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、CAS、NTU |
| **发布时间** | 2026-07-29T12:14:23Z |
| **关键词** | `RAG` |
| **原文链接** | [http://arxiv.org/abs/2607.26820v1](http://arxiv.org/abs/2607.26820v1) |

**📝 摘要概括：**

> 随着大型语言模型（ LLM ）从独立助理演变为自主代理，确保其安全需要超越逐点风险评估，以了解风险如何在长远轨迹中出现和展开。在多回合交互中，恶意意图可以在看似无害的回合中分解，并通过交互轨迹逐渐重建，最终导致安全故障。广泛的实验…

</details>

<details>
<summary><b>13. A First Look at Coding Agents' Compliance with AI Contribution Rules in Open-Source Communities</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Wenhao Yang、Runzhi He、Minghui Zhou |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-07-29T12:14:17Z |
| **关键词** | — |
| **原文链接** | [http://arxiv.org/abs/2607.26819v1](http://arxiv.org/abs/2607.26819v1) |

**📝 摘要概括：**

> 开源社区充斥着人工智能产生的贡献。在国防方面，他们有书面的贡献规则来规范编码代理的行为，从全面禁止、强制披露到验证门和人工签核。这一状况表明，核实和披露问题可以通过现有机制解决，但执行禁令和人为升级仍然是一个悬而未决的问题。

</details>

<details>
<summary><b>14. SecRespond: Benchmarking AI Agents for Real-World Post-Compromise Incident Response</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Lehan Wang、Boli Chen、Ruixue Ding、Pengjun Xie、Jinwei Huang 等（共 10 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | Alibaba |
| **发布时间** | 2026-07-29T11:32:23Z |
| **关键词** | `LLM Agent` · `AI Agent` · `Benchmark` · `Workflow` |
| **原文链接** | [http://arxiv.org/abs/2607.26791v1](http://arxiv.org/abs/2607.26791v1) |

**📝 摘要概括：**

> 大型语言模型（ LLM ）代理在现实世界的安全操作中越来越多地被采用，可以访问主机制品和命令行界面（ CLI ） ，因此彻底评估其安全能力至关重要。但是，现有的网络安全基准侧重于在发生攻击之前将代理放置在干净理想环境中的入侵前设置。该基准可在https://github.com/Al上公开获得……

</details>

<details>
<summary><b>15. SkillRise: Agentic Reinforcement Learning for Cross-Task Skill Evolution</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Zhiyuan Yao、Yuxin Chen、Zhengxi Lu、Zishan Xu、Yueqing Sun 等（共 16 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-07-29T11:26:33Z |
| **关键词** | `LLM Agent` · `Agentic` · `Reinforcement Learning` · `Retrieval` |
| **原文链接** | [http://arxiv.org/abs/2607.26784v1](http://arxiv.org/abs/2607.26784v1) |

**📝 摘要概括：**

> 大型语言模型代理经常遇到相关但截然不同的任务，这些任务共享可重用的解决方案模式。然而，标准的代理强化学习将任务视为独立的情节，而现有的技能学习方法要么专注于一个任务的重复尝试，要么使用具有多个阶段的管道来纠缠提取、检索和执行。总之，这些结果为L…提供了一个简单有效的培训范例。

</details>

<details>
<summary><b>16. Do Latent Channels Actually Communicate? A Causal Audit of Latent Multi-Agent LLM</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Huixiang Zhang、Mahzabeen Emu |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-07-29T11:14:27Z |
| **关键词** | `Multi-Agent` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2607.26773v1](http://arxiv.org/abs/2607.26773v1) |

**📝 摘要概括：**

> 基于大语言模型（ LLM ）的多智能体系统（ MAS ）中的潜在通信传输的是连续的内部表示，而不是文本，但更大的表示容量并不能确定接收者使用的是与任务相关的信息。最终任务性能本身也不能揭示观察到的效果是否依赖于消息的存在、为评估的示例生成的内容或由单独的代理提供的信息。这些…

</details>

## 🗄️ 历史归档

| 日期 | 论文数 | 报告链接 |
|------|--------|----------|
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
| 2026-06-30 | 20 篇 | [2026-06-30.md](daily/2026-06-30.md) |

## 🏛️ 顶级机构覆盖范围

覆盖超过 **70 个**顶级 AI 机构，包括：

- **科技公司：** Microsoft、Google DeepMind、OpenAI、Anthropic、Meta AI、NVIDIA、Baidu、Alibaba、ByteDance 等
- **北美顶级大学：** MIT、Stanford、CMU、UC Berkeley、Harvard、Princeton、Cornell、Caltech 等
- **中国顶级大学/机构：** 清华大学、北京大学、浙大、上交大、复旦、中科院、MSRA 等
- **欧洲/其他：** Oxford、Cambridge、ETH Zurich、Mila、NUS、KAIST 等

---

*由 [clawBot DailyFindings](https://github.com/Jacob-biu/clawBot) 自动维护 | 最后更新：2026-07-30 23:05 UTC*
