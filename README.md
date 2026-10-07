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

## 📅 今日论文 — 2026-10-07　　[→ 查看完整报告](daily/2026-10-07.md)

> 共筛选出 **20** 篇论文 | 更新于 2026-10-07 01:20 UTC

### 论文目录与概要

| # | 论文标题 | 核心概要 | 来源机构 | 第一作者 |
|---|---------|---------|---------|--------|
| 1 | [Partially Observable Zero-shot coordination by Predicting In…](http://arxiv.org/abs/2610.08142v1) | 具体环境中的零拍摄协调需要在合作伙伴间歇性地离开视线时采取行动，从而使现有方法具有模糊的合作伙伴表示和隐藏的合作伙伴状态的不确定性。我们建议预测合作伙伴的意图(PIP) ，以共同应对这些挑战。人体评估… | MIT、TRI | Jinnyeong Yang |
| 2 | [Test-Time Agent Evolution for Long-Horizon Legal Reasoning](http://arxiv.org/abs/2610.08138v1) | 法律情报旨在支持跨越涉及不断变化的案件状态和多重角色的长期法律程序的可靠决策。然而，现实世界的法律部署在事实、证据和程序背景下表现出实质性的案例异质性，暴露了静态代理策略的局限性。消融和案例研究进一步… | MIT、CAS | Haotian Chen |
| 3 | [Beyond Waypoint Regression: Query-Based Cost Learning over R…](http://arxiv.org/abs/2610.08123v1) | 基于航点回归的端到端规划器实现了强大的开环精度，但他们主要学习模仿专家几何，并且仍然难以适应部署时间的安全约束。我们提出了一种基于查询的成本学习框架，用于估计动态可达的自我轨迹查询的有限成本，而不是密… | NUS | Ahmed Abouelazm |
| 4 | [DSV-Mem: Evaluating Multimodal Memory in Professional Workfl…](http://arxiv.org/abs/2610.08102v1) | 从人工智能研究和工程设计到产品管理和业务运营，会话式传销代理越来越多地被期望协助专业工作流程。然而，这种能力仍未得到充分发掘：现有的基准主要侧重于非正式的日常互动和个人生活场景，包括摄影自然图像、孤立… | MIT、TRI | Jike Zhong |
| 5 | [Beyond Corrected Memory: Execution Consistency in Multi-Agen…](http://arxiv.org/abs/2610.08101v1) | 共享内存协调代理的操作，但正确的记录不能确定这些操作满足任务要求。内存治理和故障诊断规范或检查记录的信息；它们本身并不能确定是否足以判断任务职责。这些发现确定了代理内存和执行接口应保留的执行证据，以便… | MIT | Zhe Yu |
| 6 | [Surviving the Router: Optimizing Skill Injections for Retrie…](http://arxiv.org/abs/2610.08098v1) | 人工智能代理越来越依赖于由技能路由器动态选择的模块化第三方“技能”来执行复杂的任务。虽然最近的研究强调了这些技能中嵌入的即时注射的威胁，但现有的评估通常假设已经选择了恶意技能来执行。我们的实验表明，与… | MIT、HIT | Haneen Najjar |
| 7 | [When Tools Lie: Reliability of Mathematical Agents Under Cor…](http://arxiv.org/abs/2610.08097v1) | 数学问题解决通常需要确定性的计算步骤，这些步骤由代理委托给工具并隐式信任。然而，工具可能会默默失败，返回合理但不正确的结果。强制性政策强制执行验证，而可选政策取决于模型自己选择调用它。 | CAS | Kavienan Jegatheesan |
| 8 | [Self-Retrospection Distillation: Turning Post-hoc Experience…](http://arxiv.org/abs/2610.08077v1) | 具有可验证奖励的强化学习（ RLVR ）主要通过交互后的标量结果奖励将座席体验转化为学习信号。然而，对于与团队相关的目标，当所有推出都获得相同的奖励时，这个信号就会消失，即使它们的轨迹可能会揭示有关任… | NTU | Haoxiang Zhang |
| 9 | [Same Feedback, Different Answer: Measuring Run-to-Run Instab…](http://arxiv.org/abs/2610.08036v1) | 人工智能代理越来越多地被编程为在大量非结构化数据集合上实现知识工作的自动化。这种自动化需要可重复性：当基础证据不变时，客服代表的类别、优先级和计数不应在运行之间发生重大变化，即使每个单独的答案似乎都是… | TRI | Viraj Bagal |
| 10 | [Learning in Dreams, Winning in Reality: A Continuous Dyna Lo…](http://arxiv.org/abs/2610.08033v1) | 世界模型通常从内部来判断：通过预测损失，通过政策在想象中获得的回报，或者通过其框架的令人信服的程度来判断。我们从外面判断一个。我们发布了WORLD模型、DREAM-PPO线束、WORLD模型调试器、评… | CAS、TRI | Jordy Kieto |
| 11 | [Learning from Revision Consequences: Hindsight Meta-Experien…](http://arxiv.org/abs/2610.07979v1) | 随着座席通过生成和修改技能不断改进，发现和完善这些技能的过程本身就变成了一个可学习的对象。任务技能直接作用于任务执行，而元技能则控制代理如何发现和改进未来的技能；因此，它们的价值通过它们诱导的后续搜索… | TRI | Qianhan Feng |
| 12 | [DecepEval: A Benchmark for Evaluating Deception in LLM Agent…](http://arxiv.org/abs/2610.07967v1) | 随着大型语言模型（ LLM ）代理变得越来越自主，他们可能会通过欺骗来追求任务绩效，从而引发对其可靠部署的担忧。现有评估表明， LLM专员可以欺骗，但通常会检查孤立的场景或狭义定义的条件，从而限制了对… | MIT | Yiming Xu |
| 13 | [Confidence Reasoning Graphs: Structured Confidence Estimatio…](http://arxiv.org/abs/2610.07948v1) | 在相应的领域中使用LLM代理时，是否信任其输出或进行干预的明智决定需要对代理的成功充满信心。客服代表的信心估计很困难，因为关于成功的证据分布在客服代表轨迹的异构、相互依赖的步骤中。最后， CRG暴露了… | MIT、HIT | Brendan King |
| 14 | [SIGMA: Self-Improving Alignment Generalization from a Model …](http://arxiv.org/abs/2610.07935v1) | 法学硕士代理越来越有能力执行复杂的任务，并在软件工程和数学等易于验证的目标上进行递归改进。由于对齐很难验证，因此在没有适当的安全对齐的情况下，能力增加的风险越来越大，特别是随着能力扩展到自动研究和网络… | TRI | Jingyu Zhang |
| 15 | [ShanLiangRen: A Nutrition Agent for Personalized Daily Meal …](http://arxiv.org/abs/2610.07886v1) | 饮食营养计划在慢性病管理和维持身体健康方面发挥着重要作用。在应用中，必须同时满足个性化约束和合理的多维营养目标。可在https://www.youtube.com/watch?v=652OtY5VlG… | TRI | Miao Xie |
| 16 | [Self-Referenced Social Preferences: Cooperation without Obse…](http://arxiv.org/abs/2610.07881v1) | 社交偏好可以促进多智能体强化学习方面的合作，但现有方法通常要求智能体观察同行的回报。然而，在许多真实世界的互动中，代理可以像人类一样观察他人的行为和结果，而无需访问他们的私人奖励信号。这些结果表明，显… | TRI | Mohamed Ayman Mohamed |
| 17 | [ReFold: Training-Free Reversible Inter-Turn Context Folding …](http://arxiv.org/abs/2610.07863v1) | 长时间LLM代理根据仅追加的交互历史记录进行操作，该历史记录在每个步骤中都会重新发送到模型，因此上下文及其成本会随着步骤的增加而增加，直到会话超过上下文窗口。现有方法通过上下文需求预测来管理上下文，依… | MIT、TRI | Yupeng Su |
| 18 | [WorkflowOps: Learning Agent Collaboration Priors for Multi-A…](http://arxiv.org/abs/2610.07860v1) | 多代理系统越来越多地部署用于复杂的知识工作，但其编排层在很大程度上仍然是无记忆的：每个新任务都从头开始分解、分配和执行，而不会从之前的成功执行中获益。我们推出了WorkflowOps ，这是一个多代理… | CAS、TRI | Qi Cheng |
| 19 | [RA-MoWE: Workflow-Affinity Embeddings for Query Clustering a…](http://arxiv.org/abs/2610.07851v1) | 客服工作流程使大型语言模型（ LLM ）能够通过协调推理、工具使用和验证来解决复杂的任务。但是，针对整个任务集合优化的工作流可能会忽略单个查询所需的推理策略的差异，同时为每个查询搜索新的工作流会重复代… | Mila | Qi Cheng |
| 20 | [DHCG: Dynamic Construction of Hierarchical Collaboration Gra…](http://arxiv.org/abs/2610.07835v1) | 基于LLM的多智能体系统（ MAS ）在解决不同领域的复杂问题方面表现出强大的能力。近年来，智能体系统的动态编排已成为重要的研究方向。其他实验进一步证明了它在不同Planner骨干和看不见的Worke… | MIT、TRI | Jie Ren |

### 论文详情

<details>
<summary><b>1. Partially Observable Zero-shot coordination by Predicting Intention of Partner</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Jinnyeong Yang、Yuhwan Jeong、Hoyong Kwon、Minseok Kim、Jihun Kim 等（共 6 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-10-06T10:55:06Z |
| **关键词** | `Benchmark` · `Evaluation` · `Embodied AI` |
| **原文链接** | [http://arxiv.org/abs/2610.08142v1](http://arxiv.org/abs/2610.08142v1) |

**📝 摘要概括：**

> 具体环境中的零拍摄协调需要在合作伙伴间歇性地离开视线时采取行动，从而使现有方法具有模糊的合作伙伴表示和隐藏的合作伙伴状态的不确定性。我们建议预测合作伙伴的意图(PIP) ，以共同应对这些挑战。人体评估和诊断分析进一步支持与看不见的合作伙伴的协调以及合作伙伴的两个组成部分的贡献。

</details>

<details>
<summary><b>2. Test-Time Agent Evolution for Long-Horizon Legal Reasoning</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Haotian Chen、Shuaicheng Niu、Haocong Rao、Kaisong Song、Jun Lin 等（共 8 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、CAS、TRI |
| **发布时间** | 2026-10-06T10:53:25Z |
| **关键词** | `Reasoning` · `Memory` |
| **原文链接** | [http://arxiv.org/abs/2610.08138v1](http://arxiv.org/abs/2610.08138v1) |

**📝 摘要概括：**

> 法律情报旨在支持跨越涉及不断变化的案件状态和多重角色的长期法律程序的可靠决策。然而，现实世界的法律部署在事实、证据和程序背景下表现出实质性的案例异质性，暴露了静态代理策略的局限性。消融和案例研究进一步表明，这两个组成部分在经验适应和交叉方面提供了互补的好处。

</details>

<details>
<summary><b>3. Beyond Waypoint Regression: Query-Based Cost Learning over Reachable Ego Futures for End-to-End Driving</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Ahmed Abouelazm、Rupert Polley、Qingyuan Zhang、Yin Wu、Philip Schörner 等（共 7 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | NUS |
| **发布时间** | 2026-10-06T10:43:13Z |
| **关键词** | `Fine-tuning` |
| **原文链接** | [http://arxiv.org/abs/2610.08123v1](http://arxiv.org/abs/2610.08123v1) |

**📝 摘要概括：**

> 基于航点回归的端到端规划器实现了强大的开环精度，但他们主要学习模仿专家几何，并且仍然难以适应部署时间的安全约束。我们提出了一种基于查询的成本学习框架，用于估计动态可达的自我轨迹查询的有限成本，而不是密集的BEV单元或小的回归轨迹集。在现实世界的驾驶日志上，拟议的规划器减少了……

</details>

<details>
<summary><b>4. DSV-Mem: Evaluating Multimodal Memory in Professional Workflows for MLLM Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Jike Zhong、Ritwick Chaudhry、Xuanbai Chen、Tianchen Zhao、Linghan Xu 等（共 7 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-10-06T10:30:14Z |
| **关键词** | `LLM Agent` · `Reasoning` · `Benchmark` · `Evaluation` · `Memory` |
| **原文链接** | [http://arxiv.org/abs/2610.08102v1](http://arxiv.org/abs/2610.08102v1) |

**📝 摘要概括：**

> 从人工智能研究和工程设计到产品管理和业务运营，会话式传销代理越来越多地被期望协助专业工作流程。然而，这种能力仍未得到充分发掘：现有的基准主要侧重于非正式的日常互动和个人生活场景，包括摄影自然图像、孤立的静态文物和以召回为导向的问题。基准和代码将被发布……

</details>

<details>
<summary><b>5. Beyond Corrected Memory: Execution Consistency in Multi-Agent Systems</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Zhe Yu、Zixuan Wang、Peidong Wang、Hehai Lin、Ruochen Zhao 等（共 6 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT |
| **发布时间** | 2026-10-06T10:29:41Z |
| **关键词** | `Multi-Agent` · `Benchmark` · `Memory` |
| **原文链接** | [http://arxiv.org/abs/2610.08101v1](http://arxiv.org/abs/2610.08101v1) |

**📝 摘要概括：**

> 共享内存协调代理的操作，但正确的记录不能确定这些操作满足任务要求。内存治理和故障诊断规范或检查记录的信息；它们本身并不能确定是否足以判断任务职责。这些发现确定了代理内存和执行接口应保留的执行证据，以便进行可靠的判断。

</details>

<details>
<summary><b>6. Surviving the Router: Optimizing Skill Injections for Retrieval and Execution</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Haneen Najjar、Luca Scionis、Haritz Puerto、Sahar Abdelnabi |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、HIT、TRI |
| **发布时间** | 2026-10-06T10:28:27Z |
| **关键词** | `AI Agent` · `Retrieval` · `Benchmark` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2610.08098v1](http://arxiv.org/abs/2610.08098v1) |

**📝 摘要概括：**

> 人工智能代理越来越依赖于由技能路由器动态选择的模块化第三方“技能”来执行复杂的任务。虽然最近的研究强调了这些技能中嵌入的即时注射的威胁，但现有的评估通常假设已经选择了恶意技能来执行。我们的实验表明，与现有的技能伤害相比， CORSA大大提高了检索和端到端攻击的成功率……

</details>

<details>
<summary><b>7. When Tools Lie: Reliability of Mathematical Agents Under Corrupted Tool Feedback</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Kavienan Jegatheesan、Gayathri Lihinikaduarachchi |
| **所属机构** | （详见原文） |
| **顶级机构标签** | CAS |
| **发布时间** | 2026-10-06T10:28:19Z |
| **关键词** | — |
| **原文链接** | [http://arxiv.org/abs/2610.08097v1](http://arxiv.org/abs/2610.08097v1) |

**📝 摘要概括：**

> 数学问题解决通常需要确定性的计算步骤，这些步骤由代理委托给工具并隐式信任。然而，工具可能会默默失败，返回合理但不正确的结果。强制性政策强制执行验证，而可选政策取决于模型自己选择调用它。

</details>

<details>
<summary><b>8. Self-Retrospection Distillation: Turning Post-hoc Experiences into Prior Foresight</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Haoxiang Zhang、Qinglin Chen、Hiroaki Hayashi、Zhuofeng Li、Siming Zhang 等（共 12 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | NTU |
| **发布时间** | 2026-10-06T10:06:47Z |
| **关键词** | `Agentic` · `Reasoning` · `Reinforcement Learning` |
| **原文链接** | [http://arxiv.org/abs/2610.08077v1](http://arxiv.org/abs/2610.08077v1) |

**📝 摘要概括：**

> 具有可验证奖励的强化学习（ RLVR ）主要通过交互后的标量结果奖励将座席体验转化为学习信号。然而，对于与团队相关的目标，当所有推出都获得相同的奖励时，这个信号就会消失，即使它们的轨迹可能会揭示有关任务需要什么以及座席如何失败的有用信息。我们的研究结果表明，事后代理体验不仅对……有用

</details>

<details>
<summary><b>9. Same Feedback, Different Answer: Measuring Run-to-Run Instability in Frontier-Model Customer Feedback Analysis</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Viraj Bagal、Raviraja Ganta、Prabhath Chellingi |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-10-06T09:29:25Z |
| **关键词** | `AI Agent` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2610.08036v1](http://arxiv.org/abs/2610.08036v1) |

**📝 摘要概括：**

> 人工智能代理越来越多地被编程为在大量非结构化数据集合上实现知识工作的自动化。这种自动化需要可重复性：当基础证据不变时，客服代表的类别、优先级和计数不应在运行之间发生重大变化，即使每个单独的答案似乎都是合理的。总体而言，这些结果表明，分类接地为复发产生了更一致和可重复的输出……

</details>

<details>
<summary><b>10. Learning in Dreams, Winning in Reality: A Continuous Dyna Loop for a Ten-Hero MOBA</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Jordy Kieto |
| **所属机构** | （详见原文） |
| **顶级机构标签** | CAS、TRI |
| **发布时间** | 2026-10-06T09:26:48Z |
| **关键词** | `Multi-Agent` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2610.08033v1](http://arxiv.org/abs/2610.08033v1) |

**📝 摘要概括：**

> 世界模型通常从内部来判断：通过预测损失，通过政策在想象中获得的回报，或者通过其框架的令人信服的程度来判断。我们从外面判断一个。我们发布了WORLD模型、DREAM-PPO线束、WORLD模型调试器、评估协议以及每个策略和日志。

</details>

<details>
<summary><b>11. Learning from Revision Consequences: Hindsight Meta-Experience Distillation for Self-Improving Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Qianhan Feng、Zhongzhen Huang、Yakun Zhu、Xiaofan Zhang、Qi Dou |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-10-06T08:43:43Z |
| **关键词** | `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2610.07979v1](http://arxiv.org/abs/2610.07979v1) |

**📝 摘要概括：**

> 随着座席通过生成和修改技能不断改进，发现和完善这些技能的过程本身就变成了一个可学习的对象。任务技能直接作用于任务执行，而元技能则控制代理如何发现和改进未来的技能；因此，它们的价值通过它们诱导的后续搜索过程出现。跨越三个交互式代理基准以及开源和闭源模型……

</details>

<details>
<summary><b>12. DecepEval: A Benchmark for Evaluating Deception in LLM Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Yiming Xu、Hongyue Yu、Beihua Yang、Zihan Chen、Yixin Liu 等（共 11 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT |
| **发布时间** | 2026-10-06T08:33:43Z |
| **关键词** | `LLM Agent` · `Benchmark` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2610.07967v1](http://arxiv.org/abs/2610.07967v1) |

**📝 摘要概括：**

> 随着大型语言模型（ LLM ）代理变得越来越自主，他们可能会通过欺骗来追求任务绩效，从而引发对其可靠部署的担忧。现有评估表明， LLM专员可以欺骗，但通常会检查孤立的场景或狭义定义的条件，从而限制了对欺骗何时更有可能发生的系统了解。DecepEval使这些漏洞可衡量，为……提供了一个共同的基准

</details>

<details>
<summary><b>13. Confidence Reasoning Graphs: Structured Confidence Estimation for LLM Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Brendan King、Farima Fatahi Bayat、Jean-Flavien Bussotti、Pouya Pezeshkpour、Estevam Hruschka |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、HIT、TRI |
| **发布时间** | 2026-10-06T08:22:14Z |
| **关键词** | `LLM Agent` · `Agentic` · `Reasoning` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2610.07948v1](http://arxiv.org/abs/2610.07948v1) |

**📝 摘要概括：**

> 在相应的领域中使用LLM代理时，是否信任其输出或进行干预的明智决定需要对代理的成功充满信心。客服代表的信心估计很困难，因为关于成功的证据分布在客服代表轨迹的异构、相互依赖的步骤中。最后， CRG暴露了每个置信度估计背后的索赔和轨迹证据，使其能够……

</details>

<details>
<summary><b>14. SIGMA: Self-Improving Alignment Generalization from a Model Spec</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Jingyu Zhang、Shruti Palaskar、Daniel Khashabi、Benjamin Van Durme、Leon A. Gatys 等（共 6 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-10-06T08:09:56Z |
| **关键词** | `LLM Agent` · `Agentic` · `Reasoning` · `Reinforcement Learning` · `RAG` |
| **原文链接** | [http://arxiv.org/abs/2610.07935v1](http://arxiv.org/abs/2610.07935v1) |

**📝 摘要概括：**

> 法学硕士代理越来越有能力执行复杂的任务，并在软件工程和数学等易于验证的目标上进行递归改进。由于对齐很难验证，因此在没有适当的安全对齐的情况下，能力增加的风险越来越大，特别是随着能力扩展到自动研究和网络安全。分析表明，平衡无害性和有用性的模型规格……

</details>

<details>
<summary><b>15. ShanLiangRen: A Nutrition Agent for Personalized Daily Meal Planning</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Miao Xie、Xiao Zhang、Yuan Wang、Ruixin Zhu、Chunli Lv |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-10-06T07:32:50Z |
| **关键词** | `Planning` · `Retrieval` |
| **原文链接** | [http://arxiv.org/abs/2610.07886v1](http://arxiv.org/abs/2610.07886v1) |

**📝 摘要概括：**

> 饮食营养计划在慢性病管理和维持身体健康方面发挥着重要作用。在应用中，必须同时满足个性化约束和合理的多维营养目标。可在https://www.youtube.com/watch?v=652OtY5VlGA上观看演示视频。

</details>

<details>
<summary><b>16. Self-Referenced Social Preferences: Cooperation without Observing Others Rewards</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Mohamed Ayman Mohamed、Harshil Kotamreddy、Marcos Menon Jose |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-10-06T07:29:38Z |
| **关键词** | `Multi-Agent` · `Reinforcement Learning` |
| **原文链接** | [http://arxiv.org/abs/2610.07881v1](http://arxiv.org/abs/2610.07881v1) |

**📝 摘要概括：**

> 社交偏好可以促进多智能体强化学习方面的合作，但现有方法通常要求智能体观察同行的回报。然而，在许多真实世界的互动中，代理可以像人类一样观察他人的行为和结果，而无需访问他们的私人奖励信号。这些结果表明，显式访问其他座席的奖励信号对于学习合作行为不是必需的：社会……

</details>

<details>
<summary><b>17. ReFold: Training-Free Reversible Inter-Turn Context Folding for Long-Horizon Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Yupeng Su、Jiayi Tian、Zheng Zhang、Souvik Kundu |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-10-06T07:09:54Z |
| **关键词** | `LLM Agent` · `Benchmark` · `Evaluation` · `Memory` |
| **原文链接** | [http://arxiv.org/abs/2610.07863v1](http://arxiv.org/abs/2610.07863v1) |

**📝 摘要概括：**

> 长时间LLM代理根据仅追加的交互历史记录进行操作，该历史记录在每个步骤中都会重新发送到模型，因此上下文及其成本会随着步骤的增加而增加，直到会话超过上下文窗口。现有方法通过上下文需求预测来管理上下文，依赖于其他模型调用、启发式规则或经过训练的策略。在并发服务工作负载下，它将请求队列延迟减少了高达100% ，加快了信息传输速度。

</details>

<details>
<summary><b>18. WorkflowOps: Learning Agent Collaboration Priors for Multi-Agent Workflow Orchestration</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Qi Cheng、Shengyu Chen、Wei Cheng、Zhengzhang Chen、Xiaowei Jia 等（共 7 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | CAS、TRI |
| **发布时间** | 2026-10-06T07:01:38Z |
| **关键词** | `Multi-Agent` · `Memory` · `Workflow` |
| **原文链接** | [http://arxiv.org/abs/2610.07860v1](http://arxiv.org/abs/2610.07860v1) |

**📝 摘要概括：**

> 多代理系统越来越多地部署用于复杂的知识工作，但其编排层在很大程度上仍然是无记忆的：每个新任务都从头开始分解、分配和执行，而不会从之前的成功执行中获益。我们推出了WorkflowOps ，这是一个多代理工作流程编排框架，可从历史工作流程中学习代理协作先验，并按需扩展其代理池，以涵盖新的功能需求……

</details>

<details>
<summary><b>19. RA-MoWE: Workflow-Affinity Embeddings for Query Clustering and Agentic Workflow Generation</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Qi Cheng、Shengyu Chen、Wei Cheng、Yiqun Xie、Haoyu Wang 等（共 7 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | Mila |
| **发布时间** | 2026-10-06T06:58:16Z |
| **关键词** | `Agentic` · `Reasoning` · `RAG` · `Benchmark` · `Workflow` |
| **原文链接** | [http://arxiv.org/abs/2610.07851v1](http://arxiv.org/abs/2610.07851v1) |

**📝 摘要概括：**

> 客服工作流程使大型语言模型（ LLM ）能够通过协调推理、工具使用和验证来解决复杂的任务。但是，针对整个任务集合优化的工作流可能会忽略单个查询所需的推理策略的差异，同时为每个查询搜索新的工作流会重复代价高昂的优化。在一个包含300个查询的测试集上，从跨越数学、科学和程序的四个基准中抽取……

</details>

<details>
<summary><b>20. DHCG: Dynamic Construction of Hierarchical Collaboration Graphs for LLM-Based Multi-Agent Reasoning</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Jie Ren、Jiakang Yuan、Chenyu Huang、Hezeer Ma、Jiayuan Fan 等（共 6 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-10-06T06:33:40Z |
| **关键词** | `Multi-Agent` · `Reasoning` · `RAG` · `Benchmark` · `Code Generation` |
| **原文链接** | [http://arxiv.org/abs/2610.07835v1](http://arxiv.org/abs/2610.07835v1) |

**📝 摘要概括：**

> 基于LLM的多智能体系统（ MAS ）在解决不同领域的复杂问题方面表现出强大的能力。近年来，智能体系统的动态编排已成为重要的研究方向。其他实验进一步证明了它在不同Planner骨干和看不见的Worker模型上的泛化。

</details>

## 🗄️ 历史归档

| 日期 | 论文数 | 报告链接 |
|------|--------|----------|
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
| 2026-09-01 | 20 篇 | [2026-09-01.md](daily/2026-09-01.md) |
| 2026-08-31 | 0 篇 | [2026-08-31.md](daily/2026-08-31.md) |
| 2026-08-29 | 0 篇 | [2026-08-29.md](daily/2026-08-29.md) |
| 2026-08-28 | 20 篇 | [2026-08-28.md](daily/2026-08-28.md) |
| 2026-08-27 | 20 篇 | [2026-08-27.md](daily/2026-08-27.md) |
| 2026-08-25 | 12 篇 | [2026-08-25.md](daily/2026-08-25.md) |
| 2026-08-24 | 0 篇 | [2026-08-24.md](daily/2026-08-24.md) |
| 2026-08-23 | 0 篇 | [2026-08-23.md](daily/2026-08-23.md) |

## 🏛️ 顶级机构覆盖范围

覆盖超过 **70 个**顶级 AI 机构，包括：

- **科技公司：** Microsoft、Google DeepMind、OpenAI、Anthropic、Meta AI、NVIDIA、Baidu、Alibaba、ByteDance 等
- **北美顶级大学：** MIT、Stanford、CMU、UC Berkeley、Harvard、Princeton、Cornell、Caltech 等
- **中国顶级大学/机构：** 清华大学、北京大学、浙大、上交大、复旦、中科院、MSRA 等
- **欧洲/其他：** Oxford、Cambridge、ETH Zurich、Mila、NUS、KAIST 等

---

*由 [clawBot DailyFindings](https://github.com/Jacob-biu/clawBot) 自动维护 | 最后更新：2026-10-07 01:20 UTC*
