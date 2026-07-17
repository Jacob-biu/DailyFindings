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

## 📅 今日论文 — 2026-07-17　　[→ 查看完整报告](daily/2026-07-17.md)

> 共筛选出 **17** 篇论文 | 更新于 2026-07-17 22:48 UTC

### 论文目录与概要

| # | 论文标题 | 核心概要 | 来源机构 | 第一作者 |
|---|---------|---------|---------|--------|
| 1 | [SciDiagramEdit: Learning to Edit Scientific Diagrams from Pa…](http://arxiv.org/abs/2607.15272v1) | 编辑研究论文中的数字是日常研究实践的常规和耗时的部分：作者在修改手稿时重新标记组件、重新排列面板和重新设计视觉效果。然而，在自然语言指导下自动执行此编辑工作流程具有挑战性，因为科学人物是一个密集的信息… | MIT、NUS | Yasheng Sun |
| 2 | [Beyond Success Rate: Cost-Aware Evaluation of Offensive and …](http://arxiv.org/abs/2607.15263v1) | 安全代理评估通常在慷慨的推理预算下衡量峰值攻击能力，强调漏洞发现、漏洞开发、渗透测试和CTF完成。此类测量是有用的，但不完整：在运营安全方面，每个推理步骤、工具调用、遥测查询和浓缩请求都会消耗预算。我… | CAS | Paul Kassianik |
| 3 | [SearchOS-V1: Towards Robust Open-Domain Information-Seeking …](http://arxiv.org/abs/2607.15257v1) | 工具集成大型语言模型的最新进展使网络搜索成为信息搜索代理的核心功能。然而，随着互动历史记录的增长，客服代表越来越难以跟踪任务进度。在WideSearch和GISA上， SearchOS在评估的单代理和… | TRI | Yuyao Zhang |
| 4 | [AutoSynthesis: An agentic system for automated meta-analysis](http://arxiv.org/abs/2607.15247v1) | 证据综合对于将初级研究转化为科学、医学、教育和政策的可靠知识至关重要。然而，定量证据综合仍然在很大程度上是人工进行的，难以扩展。这些结果共同表明， AutoSynthesis可以使定量证据合成更具可扩… | Mila、TRI | Moein Taherinezhad |
| 5 | [MM-IssueLoc: A Controlled Benchmark for Evaluating Visual Ev…](http://arxiv.org/abs/2607.15205v1) | 实际的存储库问题通常包括屏幕截图、错误对话框、渲染的UI状态和日志等可视化证据，但存储库级别的问题本地化主要作为纯文本任务进行评估。现有的多模式SE基准评估端到端修复，将定位与补丁合成纠缠在一起，并模… | TRI | Shaoxiong Zhan |
| 6 | [Plover: Steering GUI Agents through Plan-Centric Interaction](http://arxiv.org/abs/2607.15193v1) | 图形用户界面(GUI)自动化在现实环境中仍然具有挑战性，动态布局、意外对话和不断变化的界面状态可能导致自治代理偏离用户意图。最近基于视觉的多式联运代理通过直接通过屏幕截图和自然语言指令操作来提高灵活性… | MIT、HIT | Madhumitha Venkatesan |
| 7 | [Scaling Behavior Foundation Model for Humanoid Robots](http://arxiv.org/abs/2607.15163v1) | 人形控制需要自然的全身协调，对控制信号的精确实时响应，以及在不同环境背景下的强大泛化，使其成为通才化身代理的基石。行为基础模型（ BFM ）最近已经成为一种有前途的解决方案，通过利用大规模行为数据来实… | HIT | Weishuai Zeng |
| 8 | [Concept-Guided Spatial Regularization for World Models in At…](http://arxiv.org/abs/2607.15142v1) | 世界模型通常被评估为基于模型的强化学习（ MBRL ）系统的组成部分，而世界模型本身很少被孤立地研究。我们检查了Atari Pong的五个代表性视觉世界模型代理： DreamerV3、DIAMOND、… | TRI | Yukuan Lu |
| 9 | [Digital Pantheon: Simulating and Auditing Coalition Formatio…](http://arxiv.org/abs/2607.15095v1) | 政治联盟的形成是由具体的政策目标和根深蒂固的意识形态信念驱动的复杂谈判。虽然大型语言模型（ LLM ）为计算政治学开辟了新的途径，但从人类反馈强化学习（ RLHF ）灌输的中立性和乐于助人的偏见使他们… | TRI | Dylan Van Mulders |
| 10 | [BrainPilot: Automating Brain Discovery with Agentic Research](http://arxiv.org/abs/2607.15079v1) | 了解大脑越来越依赖于整合跨尺度、模式和学科的证据。因此，解决单个研究问题需要协调一致的操作顺序，从调查先前的工作到根据领域知识执行分析和解释结果。在这些评估中，采用开源骨干模型的BrainPilot的… | CAS | Haoxuan Li |
| 11 | [ANet Patu-1: The Value of Connection in the Agent Network](http://arxiv.org/abs/2607.15053v1) | 互联网告诉我们，网络的价值取决于\ emph {如何}其节点连接：广播明星的规模为$ V\!\ propto\! N $ （ Sarnoff ） ，全连接网格为$ N ^ 2 $ （ Metcalfe… | CAS、TRI | Mu Yuan |
| 12 | [LQCDMaster: Agentic Scientific Computing for Lattice Quantum…](http://arxiv.org/abs/2607.15001v1) | 晶格量子色动力学（ LQCD ）为计算强子可观测性提供了一个第一原理框架，但其实际应用仍然受到将研究动机转化为可靠计算工作流程所需的大量专业知识的限制。在这里，我们介绍\ textsc {LQCDMa… | MIT、CAS | Haofei Gao |
| 13 | [OmniaBench: Benchmarking General AI Agents Across Diverse Sc…](http://arxiv.org/abs/2607.14989v1) | 大型语言模型越来越多地从文本生成器演变为能够理解用户请求、调用外部工具并通过交互完成复杂任务的通用代理。但是，现有的代理基准通常侧重于有限的场景、工具生态系统或交互格式，因此很难跨异构应用程序设置系统… | MIT、TRI | Chengyu Shen |
| 14 | [LongStraw: Long-Context RL Beyond 2M Tokens under a Fixed GP…](http://arxiv.org/abs/2607.14952v1) | 越来越大的差距将推理上下文长度与RL训练后分开：推理系统接近百万令牌上下文，而训练后工作负载通常保持在256K令牌或以下，并依赖于部署时的长度泛化。这一差距对人工智能代理尤其重要，他们的观察、工具输出… | HIT、TRI | Changhai Zhou |
| 15 | [StructureClaw: Traceable LLM Agents and an Executable Benchm…](http://arxiv.org/abs/2607.14896v1) | 解决结构工程请求需要不止一个答案；它需要一系列相互依赖的工件：解释需求、可计算模型、验证记录、求解器输出、代码检查记录和最终报告。以问答或脚本生成为中心的评估很少验证这个完整的证据链，因此即使底层工程… | MIT、CAS | Sizhong Qin |
| 16 | [Proof-or-Stop: Don't Trust the Agent, Trust the Evidence -- …](http://arxiv.org/abs/2607.14890v1) | 自主编码代理越来越多地执行多步骤软件工作，但除非有当前证据支持，否则审核、测试、完成和准备合并等生命周期状态仍然是声明。我们提出了证明或停止生命周期控制（ Proof-or-Stop Lifecycl… | MIT | Jek Huang |
| 17 | [Reachability-Aware Pretraining for Efficient Target-Oriented…](http://arxiv.org/abs/2607.14886v1) | 外推设置下的时间知识图（ TKG ）推理侧重于从时间知识图中的历史数据预测未来的时间戳事件（事实）。现有的方法，基于强化学习（ RL ）的多跳推理方法在TKG推理中很突出，因为它们通过显式多跳路径跟踪… | MIT、CAS | Chien-Liang Liu |

### 论文详情

<details>
<summary><b>1. SciDiagramEdit: Learning to Edit Scientific Diagrams from Paper Revisions</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Yasheng Sun、Zezi Zeng、Yifan Yang、Chong Luo、Wenyi Wang 等（共 7 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、NUS |
| **发布时间** | 2026-07-16T17:58:36Z |
| **关键词** | `Agentic` · `Benchmark` · `Workflow` |
| **原文链接** | [http://arxiv.org/abs/2607.15272v1](http://arxiv.org/abs/2607.15272v1) |

**📝 摘要概括：**

> 编辑研究论文中的数字是日常研究实践的常规和耗时的部分：作者在修改手稿时重新标记组件、重新排列面板和重新设计视觉效果。然而，在自然语言指导下自动执行此编辑工作流程具有挑战性，因为科学人物是一个密集的信息图表，其中包括原理图、图表、照片、标题和箭头等异构视觉元素……

</details>

<details>
<summary><b>2. Beyond Success Rate: Cost-Aware Evaluation of Offensive and Defensive Security Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Paul Kassianik、Blaine Nelson、Yaron Singer |
| **所属机构** | （详见原文） |
| **顶级机构标签** | CAS |
| **发布时间** | 2026-07-16T17:54:47Z |
| **关键词** | `Reasoning` · `Benchmark` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2607.15263v1](http://arxiv.org/abs/2607.15263v1) |

**📝 摘要概括：**

> 安全代理评估通常在慷慨的推理预算下衡量峰值攻击能力，强调漏洞发现、漏洞开发、渗透测试和CTF完成。此类测量是有用的，但不完整：在运营安全方面，每个推理步骤、工具调用、遥测查询和浓缩请求都会消耗预算。我们提供一个交互式网站，其中包含我们的结果https://evals.frontier.security。

</details>

<details>
<summary><b>3. SearchOS-V1: Towards Robust Open-Domain Information-Seeking Agent Collaboration</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Yuyao Zhang、Junjie Gao、Zhengxian Wu、Jiaming Fan、Jin Zhang 等（共 14 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-07-16T17:51:23Z |
| **关键词** | `Multi-Agent` · `RAG` · `Memory` |
| **原文链接** | [http://arxiv.org/abs/2607.15257v1](http://arxiv.org/abs/2607.15257v1) |

**📝 摘要概括：**

> 工具集成大型语言模型的最新进展使网络搜索成为信息搜索代理的核心功能。然而，随着互动历史记录的增长，客服代表越来越难以跟踪任务进度。在WideSearch和GISA上， SearchOS在评估的单代理和多代理基线中引领所有指标，为强大的信息搜索协作铺平了道路。

</details>

<details>
<summary><b>4. AutoSynthesis: An agentic system for automated meta-analysis</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Moein Taherinezhad、Sebastian Maier、Gerardo Vitagliano、Francesco Pierri、Stefan Feuerriegel |
| **所属机构** | （详见原文） |
| **顶级机构标签** | Mila、TRI |
| **发布时间** | 2026-07-16T17:45:27Z |
| **关键词** | `Multi-Agent` · `Agentic` |
| **原文链接** | [http://arxiv.org/abs/2607.15247v1](http://arxiv.org/abs/2607.15247v1) |

**📝 摘要概括：**

> 证据综合对于将初级研究转化为科学、医学、教育和政策的可靠知识至关重要。然而，定量证据综合仍然在很大程度上是人工进行的，难以扩展。这些结果共同表明， AutoSynthesis可以使定量证据合成更具可扩展性，从而支持跨学科的循证决策。

</details>

<details>
<summary><b>5. MM-IssueLoc: A Controlled Benchmark for Evaluating Visual Evidence in Multimodal Repository-Level Issue Localization</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Shaoxiong Zhan、Shi Hu、Boyu Feng、Hai Lin、Andrew Gong 等（共 10 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-07-16T17:02:25Z |
| **关键词** | `Retrieval` · `Benchmark` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2607.15205v1](http://arxiv.org/abs/2607.15205v1) |

**📝 摘要概括：**

> 实际的存储库问题通常包括屏幕截图、错误对话框、渲染的UI状态和日志等可视化证据，但存储库级别的问题本地化主要作为纯文本任务进行评估。现有的多模式SE基准评估端到端修复，将定位与补丁合成纠缠在一起，并模糊视觉输入是帮助、伤害还是被忽略。MM-IssueLoc将视觉证据转化为显式评估变量， en…

</details>

<details>
<summary><b>6. Plover: Steering GUI Agents through Plan-Centric Interaction</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Madhumitha Venkatesan、Shicheng Wen、Jiajing Guo、Jorge Piazentin Ono、Liu Ren 等（共 6 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、HIT、CAS |
| **发布时间** | 2026-07-16T16:48:39Z |
| **关键词** | `Planning` · `Benchmark` · `Workflow` |
| **原文链接** | [http://arxiv.org/abs/2607.15193v1](http://arxiv.org/abs/2607.15193v1) |

**📝 摘要概括：**

> 图形用户界面(GUI)自动化在现实环境中仍然具有挑战性，动态布局、意外对话和不断变化的界面状态可能导致自治代理偏离用户意图。最近基于视觉的多式联运代理通过直接通过屏幕截图和自然语言指令操作来提高灵活性，但规划和适应通常仍然是内部的，限制了用户检查、监督或……的能力。

</details>

<details>
<summary><b>7. Scaling Behavior Foundation Model for Humanoid Robots</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Weishuai Zeng、Kangning Yin、Xiaojie Niu、Shunlin Lu、Weixiang Zhong 等（共 18 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | HIT |
| **发布时间** | 2026-07-16T16:08:27Z |
| **关键词** | `RAG` · `Simulation` · `Embodied AI` |
| **原文链接** | [http://arxiv.org/abs/2607.15163v1](http://arxiv.org/abs/2607.15163v1) |

**📝 摘要概括：**

> 人形控制需要自然的全身协调，对控制信号的精确实时响应，以及在不同环境背景下的强大泛化，使其成为通才化身代理的基石。行为基础模型（ BFM ）最近已经成为一种有前途的解决方案，通过利用大规模行为数据来实现卓越的表现力、多功能性和概括性，以应对这些挑战。这些…

</details>

<details>
<summary><b>8. Concept-Guided Spatial Regularization for World Models in Atari Pong</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Yukuan Lu、Zaishuo Xia、Weyl Lu、Yubei Chen |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-07-16T15:46:44Z |
| **关键词** | `Reinforcement Learning` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2607.15142v1](http://arxiv.org/abs/2607.15142v1) |

**📝 摘要概括：**

> 世界模型通常被评估为基于模型的强化学习（ MBRL ）系统的组成部分，而世界模型本身很少被孤立地研究。我们检查了Atari Pong的五个代表性视觉世界模型代理： DreamerV3、DIAMOND、TWISTER、Simulus和STORM。其影响因其余模型和评估指标而异，表明CGSReg本身并不能解决所有世界模型的瓶颈。

</details>

<details>
<summary><b>9. Digital Pantheon: Simulating and Auditing Coalition Formation with LLM Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Dylan Van Mulders、Matthias Bogaert、Dirk Van den Poel |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-07-16T15:08:29Z |
| **关键词** | `Multi-Agent` · `LLM Agent` · `Reinforcement Learning` · `RAG` · `Retrieval` |
| **原文链接** | [http://arxiv.org/abs/2607.15095v1](http://arxiv.org/abs/2607.15095v1) |

**📝 摘要概括：**

> 政治联盟的形成是由具体的政策目标和根深蒂固的意识形态信念驱动的复杂谈判。虽然大型语言模型（ LLM ）为计算政治学开辟了新的途径，但从人类反馈强化学习（ RLHF ）灌输的中立性和乐于助人的偏见使他们无法维持坚定的党派行为。结果是一个透明、可扩展的测试平台，适用于……

</details>

<details>
<summary><b>10. BrainPilot: Automating Brain Discovery with Agentic Research</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Haoxuan Li、Tianci Gao、Jianhe Li、Yang Fan、Runze Shi 等（共 16 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | CAS |
| **发布时间** | 2026-07-16T14:49:25Z |
| **关键词** | `Multi-Agent` · `AI Agent` · `Agentic` · `Reasoning` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2607.15079v1](http://arxiv.org/abs/2607.15079v1) |

**📝 摘要概括：**

> 了解大脑越来越依赖于整合跨尺度、模式和学科的证据。因此，解决单个研究问题需要协调一致的操作顺序，从调查先前的工作到根据领域知识执行分析和解释结果。在这些评估中，采用开源骨干模型的BrainPilot的性能可与最先进的代理框架相媲美……

</details>

<details>
<summary><b>11. ANet Patu-1: The Value of Connection in the Agent Network</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Mu Yuan、Jinke Song、Zhaomeng Zhou、Lan Zhang |
| **所属机构** | （详见原文） |
| **顶级机构标签** | CAS、TRI |
| **发布时间** | 2026-07-16T14:31:15Z |
| **关键词** | `AI Agent` |
| **原文链接** | [http://arxiv.org/abs/2607.15053v1](http://arxiv.org/abs/2607.15053v1) |

**📝 摘要概括：**

> 互联网告诉我们，网络的价值取决于\ emph {如何}其节点连接：广播明星的规模为$ V\!\ propto\! N $ （ Sarnoff ） ，全连接网格为$ N ^ 2 $ （ Metcalfe ） ，组形成网络为$ 2 ^ {N} $ （ Reed ）。我们对人工智能代理的网络提出了类似的问题。(ii) ~反身性--一个异构网络，只给出了自己的问题，没有设计提示，它收敛于ANet Patu-1本身，重建了高维度……

</details>

<details>
<summary><b>12. LQCDMaster: Agentic Scientific Computing for Lattice Quantum Chromodynamics Research</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Haofei Gao、Tingjia Miao、Wenkai Jin、Muhua Zhang、Hanzhang Wang 等（共 15 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、CAS、NTU |
| **发布时间** | 2026-07-16T13:50:27Z |
| **关键词** | `Agentic` · `Planning` · `RAG` · `Benchmark` · `Code Generation` |
| **原文链接** | [http://arxiv.org/abs/2607.15001v1](http://arxiv.org/abs/2607.15001v1) |

**📝 摘要概括：**

> 晶格量子色动力学（ LQCD ）为计算强子可观测性提供了一个第一原理框架，但其实际应用仍然受到将研究动机转化为可靠计算工作流程所需的大量专业知识的限制。在这里，我们介绍\ textsc {LQCDMaster} ，这是一种工具增强、技能引导和专业领域的科学计算代理，可将自然语言LQCD研究任务转换为可执行的PyQUDA计算……

</details>

<details>
<summary><b>13. OmniaBench: Benchmarking General AI Agents Across Diverse Scenarios</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Chengyu Shen、Yujie Fu、Gangtao Xin、Yanheng Hou、Wenlong Fei 等（共 16 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-07-16T13:38:07Z |
| **关键词** | `AI Agent` · `Planning` · `Retrieval` · `Benchmark` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2607.14989v1](http://arxiv.org/abs/2607.14989v1) |

**📝 摘要概括：**

> 大型语言模型越来越多地从文本生成器演变为能够理解用户请求、调用外部工具并通过交互完成复杂任务的通用代理。但是，现有的代理基准通常侧重于有限的场景、工具生态系统或交互格式，因此很难跨异构应用程序设置系统地表征模型功能。OmniaBench提供了一个……

</details>

<details>
<summary><b>14. LongStraw: Long-Context RL Beyond 2M Tokens under a Fixed GPU Budget</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Changhai Zhou、Kieran Liu、Yuhua Zhou、Qian Qiao、Jun Gao 等（共 20 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | HIT、TRI |
| **发布时间** | 2026-07-16T13:00:32Z |
| **关键词** | `AI Agent` · `Memory` |
| **原文链接** | [http://arxiv.org/abs/2607.14952v1](http://arxiv.org/abs/2607.14952v1) |

**📝 摘要概括：**

> 越来越大的差距将推理上下文长度与RL训练后分开：推理系统接近百万令牌上下文，而训练后工作负载通常保持在256K令牌或以下，并依赖于部署时的长度泛化。这一差距对人工智能代理尤其重要，他们的观察、工具输出、文档和先前的决策都是在漫长的轨迹中积累的。这些实验建立了执行能力，而不是……

</details>

<details>
<summary><b>15. StructureClaw: Traceable LLM Agents and an Executable Benchmark for Structural Engineering Workflows</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Sizhong Qin、Yi Gu、Yao Jiang、Ao Cai、Changjian Zhou 等（共 16 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、CAS |
| **发布时间** | 2026-07-16T12:13:41Z |
| **关键词** | `LLM Agent` · `RAG` · `Benchmark` · `Evaluation` · `Workflow` |
| **原文链接** | [http://arxiv.org/abs/2607.14896v1](http://arxiv.org/abs/2607.14896v1) |

**📝 摘要概括：**

> 解决结构工程请求需要不止一个答案；它需要一系列相互依赖的工件：解释需求、可计算模型、验证记录、求解器输出、代码检查记录和最终报告。以问答或脚本生成为中心的评估很少验证这个完整的证据链，因此即使底层工程工作流程包含…… ，也可能会奖励流畅的输出。

</details>

<details>
<summary><b>16. Proof-or-Stop: Don't Trust the Agent, Trust the Evidence -- Loop Engineering for Verifiable Evidence-Gated Lifecycle Control</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Jek Huang、Jeffery Hsia、Jiayi Sun、Freddie Shi、Wei Huang 等（共 6 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT |
| **发布时间** | 2026-07-16T12:06:21Z |
| **关键词** | `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2607.14890v1](http://arxiv.org/abs/2607.14890v1) |

**📝 摘要概括：**

> 自主编码代理越来越多地执行多步骤软件工作，但除非有当前证据支持，否则审核、测试、完成和准备合并等生命周期状态仍然是声明。我们提出了证明或停止生命周期控制（ Proof-or-Stop Lifecycle Control ） ，该方法仅在新鲜、跟踪源状态绑定、机械可验证的证据满足相关门时才允许生命周期转换。评估仅限于一个模型家族， 24次消融……

</details>

<details>
<summary><b>17. Reachability-Aware Pretraining for Efficient Target-Oriented Path Exploration in Temporal Knowledge Graph Reasoning</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Chien-Liang Liu、Tsao-Lun Chen |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、CAS |
| **发布时间** | 2026-07-16T11:59:01Z |
| **关键词** | `Reasoning` · `Reinforcement Learning` · `Fine-tuning` |
| **原文链接** | [http://arxiv.org/abs/2607.14886v1](http://arxiv.org/abs/2607.14886v1) |

**📝 摘要概括：**

> 外推设置下的时间知识图（ TKG ）推理侧重于从时间知识图中的历史数据预测未来的时间戳事件（事实）。现有的方法，基于强化学习（ RL ）的多跳推理方法在TKG推理中很突出，因为它们通过显式多跳路径跟踪产生人工可解释的预测。ICEWS14、ICEWS05-15和ICEWS18数据的实验结果…

</details>

## 🗄️ 历史归档

| 日期 | 论文数 | 报告链接 |
|------|--------|----------|
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
| 2026-06-29 | 0 篇 | [2026-06-29.md](daily/2026-06-29.md) |
| 2026-06-28 | 0 篇 | [2026-06-28.md](daily/2026-06-28.md) |
| 2026-06-27 | 0 篇 | [2026-06-27.md](daily/2026-06-27.md) |
| 2026-06-26 | 17 篇 | [2026-06-26.md](daily/2026-06-26.md) |
| 2026-06-25 | 11 篇 | [2026-06-25.md](daily/2026-06-25.md) |
| 2026-06-24 | 9 篇 | [2026-06-24.md](daily/2026-06-24.md) |
| 2026-06-23 | 15 篇 | [2026-06-23.md](daily/2026-06-23.md) |
| 2026-06-22 | 0 篇 | [2026-06-22.md](daily/2026-06-22.md) |
| 2026-06-21 | 0 篇 | [2026-06-21.md](daily/2026-06-21.md) |
| 2026-06-20 | 0 篇 | [2026-06-20.md](daily/2026-06-20.md) |
| 2026-06-19 | 20 篇 | [2026-06-19.md](daily/2026-06-19.md) |
| 2026-06-18 | 11 篇 | [2026-06-18.md](daily/2026-06-18.md) |
| 2026-06-17 | 18 篇 | [2026-06-17.md](daily/2026-06-17.md) |

## 🏛️ 顶级机构覆盖范围

覆盖超过 **70 个**顶级 AI 机构，包括：

- **科技公司：** Microsoft、Google DeepMind、OpenAI、Anthropic、Meta AI、NVIDIA、Baidu、Alibaba、ByteDance 等
- **北美顶级大学：** MIT、Stanford、CMU、UC Berkeley、Harvard、Princeton、Cornell、Caltech 等
- **中国顶级大学/机构：** 清华大学、北京大学、浙大、上交大、复旦、中科院、MSRA 等
- **欧洲/其他：** Oxford、Cambridge、ETH Zurich、Mila、NUS、KAIST 等

---

*由 [clawBot DailyFindings](https://github.com/Jacob-biu/clawBot) 自动维护 | 最后更新：2026-07-17 22:48 UTC*
