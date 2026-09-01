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

## 📅 今日论文 — 2026-09-01　　[→ 查看完整报告](daily/2026-09-01.md)

> 共筛选出 **20** 篇论文 | 更新于 2026-09-01 23:48 UTC

### 论文目录与概要

| # | 论文标题 | 核心概要 | 来源机构 | 第一作者 |
|---|---------|---------|---------|--------|
| 1 | [Reconciling Process Supervision with Outcome-Based Credit in…](http://arxiv.org/abs/2608.31077v1) | 基于结果的强化学习为语言模型代理提供经过验证的反馈，但将轨迹级优势统一分配给所有决策，从而在长距离交互中产生粗略的信用。政策自馏通过使用仅在培训期间可用的特权信息（ PI ）重新评估抽样行为，提供了更… | TRI | Jingxiao Yang |
| 2 | [Learning to Evaluate Before Improving: Automatic Rubric Indu…](http://arxiv.org/abs/2608.31076v1) | 自主科学研究代理越来越多地应用于端到端科学工作流程，包括文献综述、数据分析、实验和报告生成。然而，开放式研究任务往往没有明确规定完成任务所需的分析、方法和成功标准。这些结果表明，评估优先指导为自主学习… | ZJU | Xuehai Wang |
| 3 | [Measure Before You Manage: Evaluating Agent Working Memory i…](http://arxiv.org/abs/2608.31057v1) | 客服代表的工作记忆是异构的。指令、工件、工具输出和代理生成的状态等对象扮演不同的语义角色，并表现出不同的大小、保留和表示配置文件。我们将这些课程分为四个层次：存储状态、交付的背景、管理工作以及任务或流… | MIT、TRI | Le Chen |
| 4 | [MNIST-PRO: MNIST is Back as a Partially Observable World for…](http://arxiv.org/abs/2608.31022v1) | 在部分可观察环境中，人工智能代理需要协调主动感知与工作记忆，以保持不断发展的感知状态。然而，现有的基准难以隔离这种感知状态构建和解释能力，因为它们引入了物理和控制复杂性。代理还必须能够构建和更新可靠的… | TRI | Vernon Toh |
| 5 | [Language-Informed Flow Matching for Trend-Guided Structure-B…](http://arxiv.org/abs/2608.31009v1) | 基于结构的药物设计（ SBDD ）需要同时满足3D靶标亲和力和1D化学有效性的配体。现有的可控生成方法通常依赖于特定任务的微调或外部施加的采样时间指导，增加了成本，并可能与不断变化的3D几何约束发生冲… | TRI | Tianyu Gao |
| 6 | [A Human-in-the-Loop Autonomous Agent for Industry Time Serie…](http://arxiv.org/abs/2608.30976v1) | 真实世界时间序列预测很少是一次性模型调用：从业者必须制定任务，连接数据和模型，整合领域专业知识，评估预测合理性，并传达不确定性。专门的预测模型提供了强大的数值预测，但通常在固定管道中运行，而通用大型语… | CAS、TRI | Xiaoyu Tao |
| 7 | [CogEvol: Towards Efficient and Reliable Learning Environment…](http://arxiv.org/abs/2608.30968v1) | 我们介绍CogEvol ，这是一个专门针对学习环境生成进行培训的模型系列：将课程简介转化为完整的学习工件（结构化JSON幻灯片或自包含的交互式HTML页面）。在22万个生产请求中， CogEvol在中… | CAS | Shangqing Tu |
| 8 | [A Universal Context-Reuse Layer for Cross-Model KV Sharing](http://arxiv.org/abs/2608.30963v1) | 现代大型语言模型（ LLM ）服务系统越来越多地在重复或共享上下文中运行，但即使另一个模型已经处理了相同的输入，每个模型通常也会执行自己的预填充计算。现有的KV缓存重用机制大大减少了单个模型内的冗余计… | HIT、TRI | Yi Li |
| 9 | [LightNav-0: Eliciting VLM Spatial Intelligence for Generalis…](http://arxiv.org/abs/2608.30935v1) | 具体化导航要求代理将异构目标和视觉观察转化为跨任务、环境和机器人实施例的行动。现代视觉语言模型（ VLM ）已经为视觉接地、空间推理和指向编码了空间先验，但这些功能很少直接用于机器人控制。这些结果确立… | MIT | Shaoan Wang |
| 10 | [S3C-LLM: Skill-Code Guided Agentic Language Models for Spect…](http://arxiv.org/abs/2608.30910v1) | 光谱结构阐明是分子分析的核心，但最近基于大语言模型（ LLM ）的方法大多将其表述为直接光谱-SMILES生成。虽然这种范式可以利用配对的光谱数据，但它并没有明确地模拟光谱学家使用的分析工作流程，例如… | TRI | Xuanle Zhao |
| 11 | [CAER: Causal Action Effect Reweighting for World Model Train…](http://arxiv.org/abs/2608.30897v1) | 世界模型正在成为具体化智能的核心基础设施，动作条件视频生成提供了对代理干预后场景如何演变的可控预测。然而，现有模型通常使用时空均匀均方误差进行训练，允许丰富的背景令牌主导梯度，而稀疏交互动态仍未得到优… | TRI | Jianjie Fang |
| 12 | [SkillZip Pro: Execution-Aware Dynamic Compression of Progres…](http://arxiv.org/abs/2608.30785v1) | 生产代理技能是目录捆绑包，而不是孤立的提示。根在激活时加载；引用、架构、脚本、资产和嵌套子技能仅在执行路径需要时加载。在多条目捆绑包上，\ method有效地降低了代币成本，同时几乎完美地保留了每条路… | MIT、TRI | Xiaofan Bai |
| 13 | [PRACTICE: From Experience to Expertise in Self-Evolving Embo…](http://arxiv.org/abs/2608.30760v1) | 最近的研究表明，多模态大型语言模型（ MLLM ）可以作为具体的代理，将语言指令和视觉观察转化为可执行计划。然而，能够通过互动不断改进并快速适应其环境的构建代理仍然具有挑战性。项目资源可在以下网址公开… | TRI | Ziyi Bai |
| 14 | [E-Commerce Bench: Evaluating LLM Agents on Long-Horizon Auto…](http://arxiv.org/abs/2608.30730v1) | 长距离代理任务不仅仅是在更多的交互回合中链接短任务。他们不断发展的动态环境和长期依赖性要求大型语言模型（ LLM ）不断探索、学习经验，并在数千个步骤中调整其政策。我们的代码可在https://git… | CAS | Wei Fan |
| 15 | [RailGen: Improving Railway Intrusion Detection via Agent-Gui…](http://arxiv.org/abs/2608.30727v1) | 长尾数据分布下的小对象检测是多媒体中的一个基本但具有挑战性的问题。铁路异物检测（ RFOD ）通过容易混淆的小入侵和稀缺样本体现了这一挑战。该范式为安全关键应用中的长尾小物体检测提供了有效的多模态生成… | TRI | Quan Hao |
| 16 | [BAITBENCH: Measuring Agent Reward Hacking with Optional Shor…](http://arxiv.org/abs/2608.30724v1) | LLM代理越来越多地用于运行自主机器学习实验，在很少人工监督的情况下迭代目标指标。之前的工作已经记录了这些环境中的奖励黑客行为，对已进行的研究的有效性和人工智能研发的更广泛安全案例提出了质疑。我们发布… | MIT、CAS | Pradyumna Shyama Prasad |
| 17 | [RailSyn: Diagnosis-Guided Image Generation for Traceable Dat…](http://arxiv.org/abs/2608.30709v1) | 铁路异物检测（ RFOD ）对于铁路安全运行至关重要，但稀缺的真实阳性样本不完全代表对象规模、入侵关系、铁路场景、照明和恶劣天气等与任务相关的变化。现有的合成增强可以改善RFOD检测，但其增益缺乏对由… | HIT | Quan Hao |
| 18 | [An Agentic Retrobiosynthesis Framework with Learned Frontier…](http://arxiv.org/abs/2608.30702v1) | 大型语言模型越来越多地被用作多步逆合成的代理，这引发了一个问题，即他们的搜索策略在多大程度上独立于潜在的反应模型。我们通过基于规则的逆生物合成在生物环境中研究这个问题：确定性生化引擎为每种方法生成相同… | TRI | Philippe Meyer |
| 19 | [ATLAS: Dual-Horizon Diagnostic Evaluation for Industrial Too…](http://arxiv.org/abs/2608.30685v1) | 大型语言模型（ LLM ）代理越来越多地部署在面向用户的服务中，这些服务需要在动态业务条件下使用迭代工具。可靠的评估对于持续改进至关重要：它必须揭示能力缺陷，告知优先事项并评估干预措施。离线实验评估诊… | Meituan、TRI | Wei Chen |
| 20 | [MedAgent-R1: Faithfulness-Aware Reinforcement Learning for E…](http://arxiv.org/abs/2608.30676v1) | 当医疗人工智能系统对临床推理产生幻觉时，后果不仅仅是不正确的答案：表面上引用检索到的证据的捏造理由可能会误导临床医生做出不安全的治疗决策。因此，医学推理代理不仅必须提供正确的答案，而且还必须提供临床医… | TRI | Jiangwang Chen |

### 论文详情

<details>
<summary><b>1. Reconciling Process Supervision with Outcome-Based Credit in Agentic Policy Optimization</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Jingxiao Yang、Wangjie Gan、Yingxuan Zhuang、Wenqi Zhang、Jintao Chen 等（共 6 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-08-31T16:51:50Z |
| **关键词** | `Agentic` · `Reinforcement Learning` · `RAG` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2608.31077v1](http://arxiv.org/abs/2608.31077v1) |

**📝 摘要概括：**

> 基于结果的强化学习为语言模型代理提供经过验证的反馈，但将轨迹级优势统一分配给所有决策，从而在长距离交互中产生粗略的信用。政策自馏通过使用仅在培训期间可用的特权信息（ PI ）重新评估抽样行为，提供了更精细的监督。这些发现为社区提供了另一个有趣的视角。

</details>

<details>
<summary><b>2. Learning to Evaluate Before Improving: Automatic Rubric Induction for Automatic Research Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Xuehai Wang、Haowei Qin、Tongxin Liu、Junkai Li、Buqiang Xu 等（共 9 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | ZJU |
| **发布时间** | 2026-08-31T16:48:51Z |
| **关键词** | `RAG` · `Evaluation` · `Workflow` |
| **原文链接** | [http://arxiv.org/abs/2608.31076v1](http://arxiv.org/abs/2608.31076v1) |

**📝 摘要概括：**

> 自主科学研究代理越来越多地应用于端到端科学工作流程，包括文献综述、数据分析、实验和报告生成。然而，开放式研究任务往往没有明确规定完成任务所需的分析、方法和成功标准。这些结果表明，评估优先指导为自主学习提供了一种有效且可推广的控制机制。

</details>

<details>
<summary><b>3. Measure Before You Manage: Evaluating Agent Working Memory in Coding Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Le Chen、Zishen Wan、Baixi Sun、Xiaolong Ma、Chih-Hsuan Yang 等（共 9 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-08-31T16:34:51Z |
| **关键词** | `Retrieval` · `Evaluation` · `Memory` |
| **原文链接** | [http://arxiv.org/abs/2608.31057v1](http://arxiv.org/abs/2608.31057v1) |

**📝 摘要概括：**

> 客服代表的工作记忆是异构的。指令、工件、工具输出和代理生成的状态等对象扮演不同的语义角色，并表现出不同的大小、保留和表示配置文件。我们将这些课程分为四个层次：存储状态、交付的背景、管理工作以及任务或流程结果。

</details>

<details>
<summary><b>4. MNIST-PRO: MNIST is Back as a Partially Observable World for AI Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Vernon Toh、Navonil Majumder、Zhengyuan Liu、Nancy F. Chen、Soujanya Poria |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-08-31T16:05:39Z |
| **关键词** | `AI Agent` · `Agentic` · `RAG` · `Benchmark` · `Memory` |
| **原文链接** | [http://arxiv.org/abs/2608.31022v1](http://arxiv.org/abs/2608.31022v1) |

**📝 摘要概括：**

> 在部分可观察环境中，人工智能代理需要协调主动感知与工作记忆，以保持不断发展的感知状态。然而，现有的基准难以隔离这种感知状态构建和解释能力，因为它们引入了物理和控制复杂性。代理还必须能够构建和更新可靠的感知状态。

</details>

<details>
<summary><b>5. Language-Informed Flow Matching for Trend-Guided Structure-Based 3D Molecular Generation</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Tianyu Gao、Zhikai Su、Jiashu Li、Wenjun Gao、Zichuan Ying 等（共 8 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-08-31T15:57:09Z |
| **关键词** | `Fine-tuning` |
| **原文链接** | [http://arxiv.org/abs/2608.31009v1](http://arxiv.org/abs/2608.31009v1) |

**📝 摘要概括：**

> 基于结构的药物设计（ SBDD ）需要同时满足3D靶标亲和力和1D化学有效性的配体。现有的可控生成方法通常依赖于特定任务的微调或外部施加的采样时间指导，增加了成本，并可能与不断变化的3D几何约束发生冲突。代码和发布的工件可在https://github.com/kasurl/LiFT上获得。

</details>

<details>
<summary><b>6. A Human-in-the-Loop Autonomous Agent for Industry Time Series Forecasting</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Xiaoyu Tao、Mingyue Cheng、Ze Guo、Bokai Pan、Qi Liu 等（共 7 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | CAS、TRI |
| **发布时间** | 2026-08-31T15:36:41Z |
| **关键词** | `Workflow` |
| **原文链接** | [http://arxiv.org/abs/2608.30976v1](http://arxiv.org/abs/2608.30976v1) |

**📝 摘要概括：**

> 真实世界时间序列预测很少是一次性模型调用：从业者必须制定任务，连接数据和模型，整合领域专业知识，评估预测合理性，并传达不确定性。专门的预测模型提供了强大的数值预测，但通常在固定管道中运行，而通用大型语言模型（ LLM ）代理通常缺乏特定于预测的检查、约束和...

</details>

<details>
<summary><b>7. CogEvol: Towards Efficient and Reliable Learning Environment Generation</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Shangqing Tu、Daniel Zhang-Li、Yucheng Wang、Shiyu Gan、Yanpeng Wang 等（共 24 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | CAS |
| **发布时间** | 2026-08-31T15:33:38Z |
| **关键词** | `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2608.30968v1](http://arxiv.org/abs/2608.30968v1) |

**📝 摘要概括：**

> 我们介绍CogEvol ，这是一个专门针对学习环境生成进行培训的模型系列：将课程简介转化为完整的学习工件（结构化JSON幻灯片或自包含的交互式HTML页面）。在22万个生产请求中， CogEvol在中位数为17秒的时间内完成了一张幻灯片，在59秒的时间内完成了一个交互式页面，取代了长达几分钟的多圈代理脚手架。支架编辑切割交互式页面基因…

</details>

<details>
<summary><b>8. A Universal Context-Reuse Layer for Cross-Model KV Sharing</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Yi Li、Dongming Jiang、Yi Zhao、Bingzhe Li |
| **所属机构** | （详见原文） |
| **顶级机构标签** | HIT、TRI |
| **发布时间** | 2026-08-31T15:28:17Z |
| **关键词** | `Multi-Agent` · `Workflow` |
| **原文链接** | [http://arxiv.org/abs/2608.30963v1](http://arxiv.org/abs/2608.30963v1) |

**📝 摘要概括：**

> 现代大型语言模型（ LLM ）服务系统越来越多地在重复或共享上下文中运行，但即使另一个模型已经处理了相同的输入，每个模型通常也会执行自己的预填充计算。现有的KV缓存重用机制大大减少了单个模型内的冗余计算，但通常假设缓存的生产者和使用者是相同的。这些结果提供了初步证据，证明……

</details>

<details>
<summary><b>9. LightNav-0: Eliciting VLM Spatial Intelligence for Generalist Embodied Navigation</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Shaoan Wang、Aocheng Luo、Fei Huang、Jingyi Xu、Xiaoyang Wang 等（共 20 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT |
| **发布时间** | 2026-08-31T15:08:53Z |
| **关键词** | `Reasoning` · `Reinforcement Learning` · `RAG` · `Benchmark` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2608.30935v1](http://arxiv.org/abs/2608.30935v1) |

**📝 摘要概括：**

> 具体化导航要求代理将异构目标和视觉观察转化为跨任务、环境和机器人实施例的行动。现代视觉语言模型（ VLM ）已经为视觉接地、空间推理和指向编码了空间先验，但这些功能很少直接用于机器人控制。这些结果确立了紧凑型VLM作为通才体现的统一和可转移的骨干……

</details>

<details>
<summary><b>10. S3C-LLM: Skill-Code Guided Agentic Language Models for Spectrum-to-Structure Elucidation</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Xuanle Zhao、Xinyuan Cai、Xiang Cheng、Bo Xu |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-08-31T14:55:32Z |
| **关键词** | `Agentic` · `Reasoning` · `Reinforcement Learning` · `RAG` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2608.30910v1](http://arxiv.org/abs/2608.30910v1) |

**📝 摘要概括：**

> 光谱结构阐明是分子分析的核心，但最近基于大语言模型（ LLM ）的方法大多将其表述为直接光谱-SMILES生成。虽然这种范式可以利用配对的光谱数据，但它并没有明确地模拟光谱学家使用的分析工作流程，例如诊断峰值解释、片段推理、公式约束和化学一致性检查。

</details>

<details>
<summary><b>11. CAER: Causal Action Effect Reweighting for World Model Training</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Jianjie Fang、Xvyuan Liu、Ziyou Wang、Rongze Tang、Zhaolu Wang 等（共 12 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-08-31T14:49:56Z |
| **关键词** | `Embodied AI` |
| **原文链接** | [http://arxiv.org/abs/2608.30897v1](http://arxiv.org/abs/2608.30897v1) |

**📝 摘要概括：**

> 世界模型正在成为具体化智能的核心基础设施，动作条件视频生成提供了对代理干预后场景如何演变的可控预测。然而，现有模型通常使用时空均匀均方误差进行训练，允许丰富的背景令牌主导梯度，而稀疏交互动态仍未得到优化；这种均匀拟合奖励重建外观……

</details>

<details>
<summary><b>12. SkillZip Pro: Execution-Aware Dynamic Compression of Progressively Loaded Skills for Self-Evolving Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Xiaofan Bai、Chao Liu、Hongqiang Lin、Di Wu、Mingli Song 等（共 8 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-08-31T13:41:16Z |
| **关键词** | `RAG` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2608.30785v1](http://arxiv.org/abs/2608.30785v1) |

**📝 摘要概括：**

> 生产代理技能是目录捆绑包，而不是孤立的提示。根在激活时加载；引用、架构、脚本、资产和嵌套子技能仅在执行路径需要时加载。在多条目捆绑包上，\ method有效地降低了代币成本，同时几乎完美地保留了每条路线和公共条目。

</details>

<details>
<summary><b>13. PRACTICE: From Experience to Expertise in Self-Evolving Embodied Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Ziyi Bai、Siqi Li、Tinglei Huang、Börje F. Karlsson |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-08-31T13:26:16Z |
| **关键词** | `Embodied AI` · `Workflow` |
| **原文链接** | [http://arxiv.org/abs/2608.30760v1](http://arxiv.org/abs/2608.30760v1) |

**📝 摘要概括：**

> 最近的研究表明，多模态大型语言模型（ MLLM ）可以作为具体的代理，将语言指令和视觉观察转化为可执行计划。然而，能够通过互动不断改进并快速适应其环境的构建代理仍然具有挑战性。项目资源可在以下网址公开获取： https://baai-agents.github.io/PRACTICE

</details>

<details>
<summary><b>14. E-Commerce Bench: Evaluating LLM Agents on Long-Horizon Autonomous Business Operation</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Wei Fan、Xinjie Shen、Xudong Guo、Jianhong Tu、Yang Su 等（共 11 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | CAS |
| **发布时间** | 2026-08-31T13:03:57Z |
| **关键词** | `LLM Agent` · `Agentic` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2608.30730v1](http://arxiv.org/abs/2608.30730v1) |

**📝 摘要概括：**

> 长距离代理任务不仅仅是在更多的交互回合中链接短任务。他们不断发展的动态环境和长期依赖性要求大型语言模型（ LLM ）不断探索、学习经验，并在数千个步骤中调整其政策。我们的代码可在https://github.com/QwenLM/E-CommerceBench上找到。

</details>

<details>
<summary><b>15. RailGen: Improving Railway Intrusion Detection via Agent-Guided Small-Scale Foreign Object Generation</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Quan Hao、Ziyang Tao、Chenxi Zhang、Yudong Wang、Rui Shi 等（共 6 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-08-31T13:01:12Z |
| **关键词** | `RAG` |
| **原文链接** | [http://arxiv.org/abs/2608.30727v1](http://arxiv.org/abs/2608.30727v1) |

**📝 摘要概括：**

> 长尾数据分布下的小对象检测是多媒体中的一个基本但具有挑战性的问题。铁路异物检测（ RFOD ）通过容易混淆的小入侵和稀缺样本体现了这一挑战。该范式为安全关键应用中的长尾小物体检测提供了有效的多模态生成解决方案。

</details>

<details>
<summary><b>16. BAITBENCH: Measuring Agent Reward Hacking with Optional Shortcuts Planted in ML Tasks</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Pradyumna Shyama Prasad、Meiri Anto、Leon Eshuijs、Julian Moncarz、Kaustubh Kislay 等（共 6 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、CAS、TRI |
| **发布时间** | 2026-08-31T12:59:33Z |
| **关键词** | `LLM Agent` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2608.30724v1](http://arxiv.org/abs/2608.30724v1) |

**📝 摘要概括：**

> LLM代理越来越多地用于运行自主机器学习实验，在很少人工监督的情况下迭代目标指标。之前的工作已经记录了这些环境中的奖励黑客行为，对已进行的研究的有效性和人工智能研发的更广泛安全案例提出了质疑。我们发布了BAITBENCH以及JUDGE实现，以及包含奖励黑客的注释成绩单数据集，作为评估奖励黑客行为的测试平台……

</details>

<details>
<summary><b>17. RailSyn: Diagnosis-Guided Image Generation for Traceable Data Completion in Railway Foreign Object Detection</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Quan Hao、Chenxi Zhang、Ziyang Tao、Yuyuan Zhou、Yudong Wang 等（共 9 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | HIT |
| **发布时间** | 2026-08-31T12:47:28Z |
| **关键词** | `RAG` |
| **原文链接** | [http://arxiv.org/abs/2608.30709v1](http://arxiv.org/abs/2608.30709v1) |

**📝 摘要概括：**

> 铁路异物检测（ RFOD ）对于铁路安全运行至关重要，但稀缺的真实阳性样本不完全代表对象规模、入侵关系、铁路场景、照明和恶劣天气等与任务相关的变化。现有的合成增强可以改善RFOD检测，但其增益缺乏对由生成数据补充的任务相关缺陷的明确说明。大量的实验表明， AP50--9…

</details>

<details>
<summary><b>18. An Agentic Retrobiosynthesis Framework with Learned Frontier Selection</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Philippe Meyer、Guillaume Gricourt、Thomas Duigou、Joan Hérisson、Jean-Loup Faulon |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-08-31T12:40:42Z |
| **关键词** | `Agentic` · `Benchmark` · `Fine-tuning` |
| **原文链接** | [http://arxiv.org/abs/2608.30702v1](http://arxiv.org/abs/2608.30702v1) |

**📝 摘要概括：**

> 大型语言模型越来越多地被用作多步逆合成的代理，这引发了一个问题，即他们的搜索策略在多大程度上独立于潜在的反应模型。我们通过基于规则的逆生物合成在生物环境中研究这个问题：确定性生化引擎为每种方法生成相同的验证转换，搜索终止于\ …

</details>

<details>
<summary><b>19. ATLAS: Dual-Horizon Diagnostic Evaluation for Industrial Tool-Use Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Wei Chen、Peilun Zhou、Zhaoyu Hu、Jiajun Chai、Zhongni Hou 等（共 11 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | Meituan、TRI |
| **发布时间** | 2026-08-31T12:25:24Z |
| **关键词** | `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2608.30685v1](http://arxiv.org/abs/2608.30685v1) |

**📝 摘要概括：**

> 大型语言模型（ LLM ）代理越来越多地部署在面向用户的服务中，这些服务需要在动态业务条件下使用迭代工具。可靠的评估对于持续改进至关重要：它必须揭示能力缺陷，告知优先事项并评估干预措施。离线实验评估诊断信号保真度和基于重播的策略改进，而在线A/B实验显示用户引擎同时获得收益……

</details>

<details>
<summary><b>20. MedAgent-R1: Faithfulness-Aware Reinforcement Learning for Evidence-Grounded Medical Reasoning</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Jiangwang Chen、Chenghao Zhang、Hengxing Cai |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-08-31T12:19:41Z |
| **关键词** | `Agentic` · `Reasoning` · `Reinforcement Learning` · `Retrieval` · `Memory` |
| **原文链接** | [http://arxiv.org/abs/2608.30676v1](http://arxiv.org/abs/2608.30676v1) |

**📝 摘要概括：**

> 当医疗人工智能系统对临床推理产生幻觉时，后果不仅仅是不正确的答案：表面上引用检索到的证据的捏造理由可能会误导临床医生做出不安全的治疗决策。因此，医学推理代理不仅必须提供正确的答案，而且还必须提供临床医生可以根据引用的证据进行验证的忠实理由。4.15 ）同时在总体准确度上保持低于GPT-4o ，

</details>

## 🗄️ 历史归档

| 日期 | 论文数 | 报告链接 |
|------|--------|----------|
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
| 2026-08-01 | 0 篇 | [2026-08-01.md](daily/2026-08-01.md) |
| 2026-07-31 | 20 篇 | [2026-07-31.md](daily/2026-07-31.md) |

## 🏛️ 顶级机构覆盖范围

覆盖超过 **70 个**顶级 AI 机构，包括：

- **科技公司：** Microsoft、Google DeepMind、OpenAI、Anthropic、Meta AI、NVIDIA、Baidu、Alibaba、ByteDance 等
- **北美顶级大学：** MIT、Stanford、CMU、UC Berkeley、Harvard、Princeton、Cornell、Caltech 等
- **中国顶级大学/机构：** 清华大学、北京大学、浙大、上交大、复旦、中科院、MSRA 等
- **欧洲/其他：** Oxford、Cambridge、ETH Zurich、Mila、NUS、KAIST 等

---

*由 [clawBot DailyFindings](https://github.com/Jacob-biu/clawBot) 自动维护 | 最后更新：2026-09-01 23:48 UTC*
