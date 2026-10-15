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

## 📅 今日论文 — 2026-10-15　　[→ 查看完整报告](daily/2026-10-15.md)

> 共筛选出 **20** 篇论文 | 更新于 2026-10-15 00:18 UTC

### 论文目录与概要

| # | 论文标题 | 核心概要 | 来源机构 | 第一作者 |
|---|---------|---------|---------|--------|
| 1 | [ChunkAct: Action Chunking for Agentic Robotics](http://arxiv.org/abs/2610.18874v1) | Agentic机器人在机器人控制循环中放置一个大型语言模型（ LLM ）代理，它在记忆的指导下组合感知、运动和视觉-语言-动作（ VLA ）工具，从而在不重新训练的情况下推广到新任务。这种普遍性在效率… | MIT | Bingxin Xu |
| 2 | [Tev: Scaling Long-Horizon Agentic Environments with Dense Pr…](http://arxiv.org/abs/2610.18868v1) | 长期代理因其能够自主工作（从几小时到几天）执行具有经济价值的任务的能力而受到越来越多的关注，这是自动发现和递归自我改进（ RSI ）所必需的能力。然而，开源模型仍然在长期任务上苦苦挣扎，主要是因为缺乏… | TRI | Wenbo Hu |
| 3 | [Hybrid Reasoning Agents](http://arxiv.org/abs/2610.18861v1) | 我们如何构建一个超越人类语言的思维，同时在外部环境中仍然通过人类语言行事的代理？现代LLM代理仍然通过文本进行推理和交互，而潜在推理提供了一种有效的内部媒介，但缺乏本机工具访问和推理透明度。代码和数据… | HIT | Jiaru Zou |
| 4 | [Self-Evolving Agent Harness](http://arxiv.org/abs/2610.18813v1) | 利用自我进化来修改客服代表的软件支架，包括提示、内存、工作流程和可执行组件，同时保持模型权重固定。我们正式制定了一个反馈驱动的流程，其中接受的修订在整个运行中持续存在。我们提供全面的66页讨论，涉及相… | CAS、TRI | Chuyang Wei |
| 5 | [SkillScaffold: Scaffolding Agentic Reinforcement Learning wi…](http://arxiv.org/abs/2610.18807v1) | 代理强化学习（ RL ）使大型语言模型（ LLM ）能够从具有可验证结果的多回合交互中学习。文本技能可以通过将先前的互动提炼成可重用的指导来改善探索。我们的代码可在https://github.com… | MIT | Wenlin Zhong |
| 6 | [BLADE: Auditing Information Use for Failure Attribution in L…](http://arxiv.org/abs/2610.18780v1) | 大型语言模型多代理系统通过跨专业角色、工具和工作流的协作来扩展单个代理的能力。然而，协作使失败更难诊断：一位客服代表可能会误解正确的结果，而另一位客服代表可能会继续犯错误。明确责任证据提供了一条通往更… | TRI | Xiaoguang Guo |
| 7 | [Beyond the Verdict: Agentic Code Judging with Verifiable Fee…](http://arxiv.org/abs/2610.18760v1) | 大型语言模型（ LLM ）的测试时间缩放可能涉及生成多个候选解决方案以供选择或修改较早的尝试。为了指导选择和修改，我们需要一个可以评估候选人正确性并提供失败证据的验证者。在IOI 2026案例研究中，… | MIT、CAS | Zheye Deng |
| 8 | [Knowing the User Is Not Knowing What We Established: Groundi…](http://arxiv.org/abs/2610.18684v1) | 个人座席记忆主要集中在了解用户知道、喜欢和想要什么。但是，了解用户并不一定意味着了解用户和代理共同建立了什么。最后，我们引入了Grounding Layer ，这是一个轻量级、无需训练的扩展，可以明确… | TRI | Jiajun Chen |
| 9 | [ProAS: A Progress-Aware Advantage Shaping Framework for Mult…](http://arxiv.org/abs/2610.18683v1) | 强化学习（ RL ）已成为优化大型语言模型（ LLM ）代理的主要范例，但高效的无批评算法（例如GRPO ）面临着基本的统一信用分配困境，即对所有行动平等地广播轨迹级优势。我们的分析显示，这种一致性本… | MIT、CAS | Bowen Ding |
| 10 | [Knowledge Graphs as Files: An Agent Harness Where Tool Creat…](http://arxiv.org/abs/2610.18616v1) | 搜索文本丰富的知识图表需要在检查文本证据时遵循关系。预定义的图形接口限制了证据代理可以访问的内容，即使他们编写代码来组合工具调用或处理检索到的子图。我们的代码和数据可在https://github.c… | HIT、TRI | Yuyang Bai |
| 11 | [Can an Agent Learn to Predict Its Own Failure? Outcome-Groun…](http://arxiv.org/abs/2610.18614v1) | 控制代理LLM代理意味着在长远任务的每个步骤中，决定是信任其下一个动作、弃权还是移交给人类。该决策需要每步的置信度信号，以预测当前的推出是否最终会成功。我们还引入了一种评估方案，将情节深度、任务难度和… | NTU | Ashutosh Hathidara |
| 12 | [AgentStripes: An Evidence-Graded Maturity Model for AI Agent…](http://arxiv.org/abs/2610.18603v1) | 基准报告人工智能(AI)代理可以在任务套件上执行的操作，但不能报告一个发布的版本是否已经设计了使其可靠、安全和可观察的控件，或者显示的强度。本文提出了AgentStripes ，这是一种针对AI ag… | MIT、TRI | Nutan Kumar Naik |
| 13 | [Auditing Future-Memory Use in Point-in-Time Language Agents](http://arxiv.org/abs/2610.18602v1) | 时间点（ PIT ）客服代表可以召回截止时间后的事实，即使他们的外部证据涉及历史截止时间。我们检查此访问是否预测在48个历史公司比较任务中收集的证据。这些发现支持对内存可访问性、搜索分配和最终输出的单… | TRI | Rongtian Ye |
| 14 | [Autonomous Cyber Operations Gym for Training and Evaluating …](http://arxiv.org/abs/2610.18594v1) | 本文提出了一个自主网络运营（ ACO ）健身房，这是一个集高保真网络仿真、针对良性网络流量和对抗性配置文件的现实用户行为建模以及通过开放工具包生成网络安全场景的统一框架。通过在数据包和流量级别支持实时… | TRI | Tobias Hürten |
| 15 | [LLM Agents for Automated Post-Training via Structured Recipe…](http://arxiv.org/abs/2610.18572v1) | 自动训练后，在有限的实验预算下，通过自动构建和优化数据源、数据处理、跨域组合和训练配置的耦合决策配方，将预训练的大型语言模型（ LLM ）转换为能够处理不同领域的模型。现有的自动化要么搜索预定义的配方… | MIT、TRI | Ruohong Liu |
| 16 | [On Symmetry for Characterizing Agent Heterogeneity in Multi-…](http://arxiv.org/abs/2610.18538v1) | 了解代理异构性可以为共享和特定代理策略表示的设计提供信息，但现有标准未提供统一的结构测试。我们研究有限地平线POSG ，并将类型兼容转换定义为策略评估对称性，当完整的政策评估与每个分散的行为策略通勤时… | TRI | Jianhong Wang |
| 17 | [Lost in Implicit Routing: How LLM Agents Fail to Load Releva…](http://arxiv.org/abs/2610.18522v1) | 可重用技能允许LLM代理按需加载特定于任务的指令，但它们使执行依赖于技能元数据的隐式路由。我们通过保持SkillsBench任务及其黄金技能固定，同时添加无关技能来测试此设计是否可扩展。我们的分析为技… | MIT | Jinlin Liu |
| 18 | [A Global View of How LLMs Value Human Time](http://arxiv.org/abs/2610.18515v1) | 大型语言模型（ LLM ）越来越多地充当个人助理；然而，人们对它们如何在全球范围内捕捉国家层面的偏好知之甚少。鉴于“时间”是一个普遍且具有代表性的概念，我们通过仅改变用户所在国家/地区来检查LLM的时… | TRI | Yifan He |
| 19 | [ReTerm: Recovery Training for Self-Improving Terminal Agents](http://arxiv.org/abs/2610.18484v1) | 终端代理在复杂的编码任务中显示出很强的能力。然而，它们通常难以从长期运行期间的错误中恢复（例如，命令错误、错误的实现） ，最终导致任务失败。所有代码、数据和模型均在https://github.com… | NTU | Wei Xie |
| 20 | [MemoryVLN: From Ego-Aware Memory Representation to Cross-Con…](http://arxiv.org/abs/2610.18478v1) | 大型视觉语言模型（ LVLM ）在具体化的视觉语言导航（ VLN ）方面显示出巨大的潜力，但由于上下文长度限制、冗余的历史观测和时间上不稳定的空间对齐，它们在长视野轨迹上的性能会下降。这些问题使得既难… | MIT、TRI | Xueyao Wei |

### 论文详情

<details>
<summary><b>1. ChunkAct: Action Chunking for Agentic Robotics</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Bingxin Xu、Wenrui Bao、Xinxin Liu、Jiawei Zhou、Yuzhang Shang 等（共 6 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT |
| **发布时间** | 2026-10-13T17:59:57Z |
| **关键词** | `Agentic` · `Reasoning` · `Robotics` · `Memory` |
| **原文链接** | [http://arxiv.org/abs/2610.18874v1](http://arxiv.org/abs/2610.18874v1) |

**📝 摘要概括：**

> Agentic机器人在机器人控制循环中放置一个大型语言模型（ LLM ）代理，它在记忆的指导下组合感知、运动和视觉-语言-动作（ VLA ）工具，从而在不重新训练的情况下推广到新任务。这种普遍性在效率上付出了高昂的代价。在LIBERO-Pro上， ChunkAct比最先进的代理机器人技术将任务成功率提高了5.0分，同时需要的LLM调用减少了2.9倍， 4…

</details>

<details>
<summary><b>2. Tev: Scaling Long-Horizon Agentic Environments with Dense Progress Rewards</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Wenbo Hu、Shraman Pramanick、Krishna Kumar Singh、Nanyun Peng、Kai-Wei Chang 等（共 6 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-10-13T17:59:51Z |
| **关键词** | `Agentic` · `Workflow` |
| **原文链接** | [http://arxiv.org/abs/2610.18868v1](http://arxiv.org/abs/2610.18868v1) |

**📝 摘要概括：**

> 长期代理因其能够自主工作（从几小时到几天）执行具有经济价值的任务的能力而受到越来越多的关注，这是自动发现和递归自我改进（ RSI ）所必需的能力。然而，开源模型仍然在长期任务上苦苦挣扎，主要是因为缺乏训练数据和工作配方，两者都很难扩展：漫长而复杂的任务很难策划和验证，它们的回报……

</details>

<details>
<summary><b>3. Hybrid Reasoning Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Jiaru Zou、Yunzhe Qi、Sirui Chen、Federico Bianchi、Shang Zhu 等（共 8 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | HIT |
| **发布时间** | 2026-10-13T17:59:31Z |
| **关键词** | `LLM Agent` · `Agentic` · `Reasoning` · `Benchmark` · `Memory` |
| **原文链接** | [http://arxiv.org/abs/2610.18861v1](http://arxiv.org/abs/2610.18861v1) |

**📝 摘要概括：**

> 我们如何构建一个超越人类语言的思维，同时在外部环境中仍然通过人类语言行事的代理？现代LLM代理仍然通过文本进行推理和交互，而潜在推理提供了一种有效的内部媒介，但缺乏本机工具访问和推理透明度。代码和数据可在https://github.com/togethercomputer/HybridAgent上获得。

</details>

<details>
<summary><b>4. Self-Evolving Agent Harness</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Chuyang Wei、Haoxiang Guan、Minghang Zhu、Kexin Zhou、Jiyan He 等（共 8 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | CAS、TRI |
| **发布时间** | 2026-10-13T17:48:49Z |
| **关键词** | `Evaluation` · `Memory` · `Workflow` |
| **原文链接** | [http://arxiv.org/abs/2610.18813v1](http://arxiv.org/abs/2610.18813v1) |

**📝 摘要概括：**

> 利用自我进化来修改客服代表的软件支架，包括提示、内存、工作流程和可执行组件，同时保持模型权重固定。我们正式制定了一个反馈驱动的流程，其中接受的修订在整个运行中持续存在。我们提供全面的66页讨论，涉及相关工作、理论、算法、评估、应用和线束RSI的更广泛影响，以及不断更新的代码和补充……

</details>

<details>
<summary><b>5. SkillScaffold: Scaffolding Agentic Reinforcement Learning with Policy-Adaptive Skill Credit Assignment and Selective Injection</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Wenlin Zhong、Hao Wang、Kun Yuan、Fan Yang、Jinluan Yang 等（共 9 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT |
| **发布时间** | 2026-10-13T17:46:25Z |
| **关键词** | `Agentic` · `Reinforcement Learning` · `RAG` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2610.18807v1](http://arxiv.org/abs/2610.18807v1) |

**📝 摘要概括：**

> 代理强化学习（ RL ）使大型语言模型（ LLM ）能够从具有可验证结果的多回合交互中学习。文本技能可以通过将先前的互动提炼成可重用的指导来改善探索。我们的代码可在https://github.com/Vaidurya00/SkillScaffold上找到。

</details>

<details>
<summary><b>6. BLADE: Auditing Information Use for Failure Attribution in LLM Multi-Agent Systems</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Xiaoguang Guo、Yaohao Long、Chuxu Zhang |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-10-13T17:34:34Z |
| **关键词** | `Multi-Agent` · `Agentic` · `Workflow` |
| **原文链接** | [http://arxiv.org/abs/2610.18780v1](http://arxiv.org/abs/2610.18780v1) |

**📝 摘要概括：**

> 大型语言模型多代理系统通过跨专业角色、工具和工作流的协作来扩展单个代理的能力。然而，协作使失败更难诊断：一位客服代表可能会误解正确的结果，而另一位客服代表可能会继续犯错误。明确责任证据提供了一条通往更具可解释性和可靠性的代理系统的道路。

</details>

<details>
<summary><b>7. Beyond the Verdict: Agentic Code Judging with Verifiable Feedback</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Zheye Deng、Sha Li、Changlong Yu、Xin Liu、Qin Lu 等（共 7 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、CAS |
| **发布时间** | 2026-10-13T17:22:58Z |
| **关键词** | `Agentic` · `Reinforcement Learning` |
| **原文链接** | [http://arxiv.org/abs/2610.18760v1](http://arxiv.org/abs/2610.18760v1) |

**📝 摘要概括：**

> 大型语言模型（ LLM ）的测试时间缩放可能涉及生成多个候选解决方案以供选择或修改较早的尝试。为了指导选择和修改，我们需要一个可以评估候选人正确性并提供失败证据的验证者。在IOI 2026案例研究中， ARBITER引导的细化将GPT-OSS-120B的预期分数提高到官方提交限制下的金牌阈值以上。

</details>

<details>
<summary><b>8. Knowing the User Is Not Knowing What We Established: Grounding Awareness in Personal Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Jiajun Chen、Xinyue Chen、Yicheng Jiang、Hua Shen |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-10-13T16:39:59Z |
| **关键词** | `Retrieval` · `Benchmark` · `Memory` |
| **原文链接** | [http://arxiv.org/abs/2610.18684v1](http://arxiv.org/abs/2610.18684v1) |

**📝 摘要概括：**

> 个人座席记忆主要集中在了解用户知道、喜欢和想要什么。但是，了解用户并不一定意味着了解用户和代理共同建立了什么。最后，我们引入了Grounding Layer ，这是一个轻量级、无需训练的扩展，可以明确跟踪接地状态并检查相应的操作，从而在不修改模型或内存系统的情况下显著改善代理行为。

</details>

<details>
<summary><b>9. ProAS: A Progress-Aware Advantage Shaping Framework for Multi-Turn Agentic Reinforcement Learning</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Bowen Ding、Mingda Wan、Yuhan Chen、Jiyao Yuan、Qi Zhu 等（共 10 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、CAS、TRI |
| **发布时间** | 2026-10-13T16:39:38Z |
| **关键词** | `Agentic` · `Reinforcement Learning` · `RAG` |
| **原文链接** | [http://arxiv.org/abs/2610.18683v1](http://arxiv.org/abs/2610.18683v1) |

**📝 摘要概括：**

> 强化学习（ RL ）已成为优化大型语言模型（ LLM ）代理的主要范例，但高效的无批评算法（例如GRPO ）面临着基本的统一信用分配困境，即对所有行动平等地广播轨迹级优势。我们的分析显示，这种一致性本质上强化了首选轨迹中的结构无效动作，而忽略了……中的下游级联

</details>

<details>
<summary><b>10. Knowledge Graphs as Files: An Agent Harness Where Tool Creation and Tool Use Co-Evolve</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Yuyang Bai、Yu Wang、Yu Zhang |
| **所属机构** | （详见原文） |
| **顶级机构标签** | HIT、TRI |
| **发布时间** | 2026-10-13T16:00:50Z |
| **关键词** | `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2610.18616v1](http://arxiv.org/abs/2610.18616v1) |

**📝 摘要概括：**

> 搜索文本丰富的知识图表需要在检查文本证据时遵循关系。预定义的图形接口限制了证据代理可以访问的内容，即使他们编写代码来组合工具调用或处理检索到的子图。我们的代码和数据可在https://github.com/leopoldwhite/DKGI上获得。

</details>

<details>
<summary><b>11. Can an Agent Learn to Predict Its Own Failure? Outcome-Grounded Confidence Calibration in LLM Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Ashutosh Hathidara |
| **所属机构** | （详见原文） |
| **顶级机构标签** | NTU |
| **发布时间** | 2026-10-13T16:00:01Z |
| **关键词** | `LLM Agent` · `Reinforcement Learning` · `RAG` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2610.18614v1](http://arxiv.org/abs/2610.18614v1) |

**📝 摘要概括：**

> 控制代理LLM代理意味着在长远任务的每个步骤中，决定是信任其下一个动作、弃权还是移交给人类。该决策需要每步的置信度信号，以预测当前的推出是否最终会成功。我们还引入了一种评估方案，将情节深度、任务难度和尝试级预见性分开，显示了收益所在：受过训练的代理从...

</details>

<details>
<summary><b>12. AgentStripes: An Evidence-Graded Maturity Model for AI Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Nutan Kumar Naik、Vijay Prasad Poudel、Aditya Kumar Saroj、Saurav Samantray、Abhishek Patel |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-10-13T15:57:28Z |
| **关键词** | `AI Agent` · `Benchmark` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2610.18603v1](http://arxiv.org/abs/2610.18603v1) |

**📝 摘要概括：**

> 基准报告人工智能(AI)代理可以在任务套件上执行的操作，但不能报告一个发布的版本是否已经设计了使其可靠、安全和可观察的控件，或者显示的强度。本文提出了AgentStripes ，这是一种针对AI agent的证据分级成熟度模型。这些参数是没有基于结果的校准的专家约定，并且条纹尚未被证明可以预测可靠性……

</details>

<details>
<summary><b>13. Auditing Future-Memory Use in Point-in-Time Language Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Rongtian Ye |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-10-13T15:56:58Z |
| **关键词** | `Memory` |
| **原文链接** | [http://arxiv.org/abs/2610.18602v1](http://arxiv.org/abs/2610.18602v1) |

**📝 摘要概括：**

> 时间点（ PIT ）客服代表可以召回截止时间后的事实，即使他们的外部证据涉及历史截止时间。我们检查此访问是否预测在48个历史公司比较任务中收集的证据。这些发现支持对内存可访问性、搜索分配和最终输出的单独评估，以及对外部证据的截止检查。

</details>

<details>
<summary><b>14. Autonomous Cyber Operations Gym for Training and Evaluating AI Models for Defence</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Tobias Hürten、Johannes F. Loevenich、Florian Spelter、Erik Adler、Laurin Holz 等（共 8 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-10-13T15:52:47Z |
| **关键词** | `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2610.18594v1](http://arxiv.org/abs/2610.18594v1) |

**📝 摘要概括：**

> 本文提出了一个自主网络运营（ ACO ）健身房，这是一个集高保真网络仿真、针对良性网络流量和对抗性配置文件的现实用户行为建模以及通过开放工具包生成网络安全场景的统一框架。通过在数据包和流量级别支持实时和延迟特征提取，健身房有助于创建用于训练Deep Ne的标签合成数据集……

</details>

<details>
<summary><b>15. LLM Agents for Automated Post-Training via Structured Recipe Optimization</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Ruohong Liu、Bohan Tang、Lekang Jiang、Jack Umenberger、Yiwen Guo |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-10-13T15:39:34Z |
| **关键词** | `LLM Agent` · `RAG` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2610.18572v1](http://arxiv.org/abs/2610.18572v1) |

**📝 摘要概括：**

> 自动训练后，在有限的实验预算下，通过自动构建和优化数据源、数据处理、跨域组合和训练配置的耦合决策配方，将预训练的大型语言模型（ LLM ）转换为能够处理不同领域的模型。现有的自动化要么搜索预定义的配方空间，以实现系统优化，但保持固定，而不是……

</details>

<details>
<summary><b>16. On Symmetry for Characterizing Agent Heterogeneity in Multi-Agent Systems</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Jianhong Wang、Jonathan Lawry |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-10-13T15:19:59Z |
| **关键词** | `Multi-Agent` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2610.18538v1](http://arxiv.org/abs/2610.18538v1) |

**📝 摘要概括：**

> 了解代理异构性可以为共享和特定代理策略表示的设计提供信息，但现有标准未提供统一的结构测试。我们研究有限地平线POSG ，并将类型兼容转换定义为策略评估对称性，当完整的政策评估与每个分散的行为策略通勤时。最后，我们给出了重复模型分解的充分条件……

</details>

<details>
<summary><b>17. Lost in Implicit Routing: How LLM Agents Fail to Load Relevant Skills at Scale</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Jinlin Liu、Wei Chen、Xiaojin Zhang |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT |
| **发布时间** | 2026-10-13T15:12:12Z |
| **关键词** | `LLM Agent` · `RAG` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2610.18522v1](http://arxiv.org/abs/2610.18522v1) |

**📝 摘要概括：**

> 可重用技能允许LLM代理按需加载特定于任务的指令，但它们使执行依赖于技能元数据的隐式路由。我们通过保持SkillsBench任务及其黄金技能固定，同时添加无关技能来测试此设计是否可扩展。我们的分析为技能库不断增长的客服代表提供技能协议和评估信息。

</details>

<details>
<summary><b>18. A Global View of How LLMs Value Human Time</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Yifan He、Sofie Goethals、Manon Reusens、David Martens |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-10-13T15:08:38Z |
| **关键词** | `Agentic` |
| **原文链接** | [http://arxiv.org/abs/2610.18515v1](http://arxiv.org/abs/2610.18515v1) |

**📝 摘要概括：**

> 大型语言模型（ LLM ）越来越多地充当个人助理；然而，人们对它们如何在全球范围内捕捉国家层面的偏好知之甚少。鉴于“时间”是一个普遍且具有代表性的概念，我们通过仅改变用户所在国家/地区来检查LLM的时间偏好，并衡量LLM认为适合60分钟预约延迟的薪酬。这些发现表明， LLM中嵌入了地理模式……

</details>

<details>
<summary><b>19. ReTerm: Recovery Training for Self-Improving Terminal Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Wei Xie、Kaituo Feng、Shiming Fu、Yong Liu、Xiangyu Yue 等（共 6 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | NTU |
| **发布时间** | 2026-10-13T14:44:24Z |
| **关键词** | — |
| **原文链接** | [http://arxiv.org/abs/2610.18484v1](http://arxiv.org/abs/2610.18484v1) |

**📝 摘要概括：**

> 终端代理在复杂的编码任务中显示出很强的能力。然而，它们通常难以从长期运行期间的错误中恢复（例如，命令错误、错误的实现） ，最终导致任务失败。所有代码、数据和模型均在https://github.com/twothsnd/ReTerm上发布。

</details>

<details>
<summary><b>20. MemoryVLN: From Ego-Aware Memory Representation to Cross-Context Memory Reuse in Vision-Language Navigation</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Xueyao Wei、Yifei Wang、Delun Li、Shaoan Wang、Junzhi Yu 等（共 7 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-10-13T14:40:04Z |
| **关键词** | `Embodied AI` · `Memory` |
| **原文链接** | [http://arxiv.org/abs/2610.18478v1](http://arxiv.org/abs/2610.18478v1) |

**📝 摘要概括：**

> 大型视觉语言模型（ LVLM ）在具体化的视觉语言导航（ VLN ）方面显示出巨大的潜力，但由于上下文长度限制、冗余的历史观测和时间上不稳定的空间对齐，它们在长视野轨迹上的性能会下降。这些问题使得既难以压缩漫长的导航历史记录，也难以可靠地重用过去的空间体验。在R2R-CE和RxR-CE上进行的大量实验证明……

</details>

## 🗄️ 历史归档

| 日期 | 论文数 | 报告链接 |
|------|--------|----------|
| 2026-10-15 | 20 篇 | [2026-10-15.md](daily/2026-10-15.md) |
| 2026-10-14 | 0 篇 | [2026-10-14.md](daily/2026-10-14.md) |
| 2026-10-13 | 0 篇 | [2026-10-13.md](daily/2026-10-13.md) |
| 2026-10-12 | 0 篇 | [2026-10-12.md](daily/2026-10-12.md) |
| 2026-10-11 | 0 篇 | [2026-10-11.md](daily/2026-10-11.md) |
| 2026-10-10 | 20 篇 | [2026-10-10.md](daily/2026-10-10.md) |
| 2026-10-09 | 20 篇 | [2026-10-09.md](daily/2026-10-09.md) |
| 2026-10-08 | 20 篇 | [2026-10-08.md](daily/2026-10-08.md) |
| 2026-10-07 | 20 篇 | [2026-10-07.md](daily/2026-10-07.md) |
| 2026-10-06 | 0 篇 | [2026-10-06.md](daily/2026-10-06.md) |
| 2026-10-05 | 0 篇 | [2026-10-05.md](daily/2026-10-05.md) |
| 2026-10-04 | 0 篇 | [2026-10-04.md](daily/2026-10-04.md) |
| 2026-10-03 | 20 篇 | [2026-10-03.md](daily/2026-10-03.md) |
| 2026-10-02 | 15 篇 | [2026-10-02.md](daily/2026-10-02.md) |
| 2026-10-01 | 20 篇 | [2026-10-01.md](daily/2026-10-01.md) |
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

## 🏛️ 顶级机构覆盖范围

覆盖超过 **70 个**顶级 AI 机构，包括：

- **科技公司：** Microsoft、Google DeepMind、OpenAI、Anthropic、Meta AI、NVIDIA、Baidu、Alibaba、ByteDance 等
- **北美顶级大学：** MIT、Stanford、CMU、UC Berkeley、Harvard、Princeton、Cornell、Caltech 等
- **中国顶级大学/机构：** 清华大学、北京大学、浙大、上交大、复旦、中科院、MSRA 等
- **欧洲/其他：** Oxford、Cambridge、ETH Zurich、Mila、NUS、KAIST 等

---

*由 [clawBot DailyFindings](https://github.com/Jacob-biu/clawBot) 自动维护 | 最后更新：2026-10-15 00:18 UTC*
