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

## 📅 今日论文 — 2026-07-15　　[→ 查看完整报告](daily/2026-07-15.md)

> 共筛选出 **14** 篇论文 | 更新于 2026-07-15 22:58 UTC

### 论文目录与概要

| # | 论文标题 | 核心概要 | 来源机构 | 第一作者 |
|---|---------|---------|---------|--------|
| 1 | [Do AI Agents Know When a Task Is Simple? Toward Complexity-A…](http://arxiv.org/abs/2607.13034v1) | 大型语言模型（ LLM ）代理越来越多地自动化多步骤工程和信息学工作流程，但他们很少询问任务实际需要多少工作量。他们通常遵循最大上下文优先策略-重新读取他们已经看到的文件和依赖项-将单行编辑转换为小型… | MIT、CAS | Junjie Yin |
| 2 | [TerraZero: Procedural Driving Simulation for Zero-Demonstrat…](http://arxiv.org/abs/2607.13028v1) | 训练强大的自动驾驶代理需要一个足够快的模拟器来进行大规模的强化学习，足够逼真以适应现实世界地图结构中的行为，并且足够多样化以覆盖记录数据很少包含的安全关键长尾。我们推出了程序化驾驶模拟器和自我训练堆栈… | MIT、TRI | Zhouchonghao Wu |
| 3 | [Knowledge- and Gradient-Guided Reinforcement Learning for Pa…](http://arxiv.org/abs/2607.12924v1) | 在本文中，我们研究了参数化动作马尔可夫决策过程（ PAMDP ）中的强化学习，其中每个决策由符号动作和数值参数组成。在这样的环境中，强化学习算法通常使用一次性估计器确定参数，这使得它们的训练样本效率低… | TRI | Jonas Ehrhardt |
| 4 | [MemOps: Benchmarking Lifecycle Memory Operations in Long-Hor…](http://arxiv.org/abs/2607.12893v1) | 长期记忆已成为基于LLM的客服代表的基础能力，可陪伴用户进行长时间、多会话的互动。然而，现有的基准几乎完全通过下游问答来评估这种记忆，只对最终答案的正确性进行评分。这些结果将长期记忆评估从最终答案评分… | TRI | Xixuan Hao |
| 5 | [A Multi-Agent System for Autonomous, Fine-Tuning-Free Clinic…](http://arxiv.org/abs/2607.12886v1) | 临床笔记包含许多使患者接受治疗的体征和症状，但这些信息很少到达结构化领域。现有的提取方法要么依赖于产生误报的上下文不敏感规则，要么依赖于需要大量微调的监督模型。这些研究结果表明，自主、无微调的提示优化… | TRI | Cameron Cagan |
| 6 | [Unveiling Complex Collective Behaviors from Simple Rewards](http://arxiv.org/abs/2607.12861v1) | 多智能体强化学习（ MARL ）对于机器人群体具有巨大的潜力，但神经策略的黑盒性质使战略分析复杂化，限制了多机器人应用。此外，复杂的群体行为可以令人惊讶地从简单的奖励中产生，而没有明确的聚合激励。这两… | MIT、TRI | Yize Mi |
| 7 | [Human-AI Agent Interaction as a Neuroplastic Training Enviro…](http://arxiv.org/abs/2607.12823v1) | 与人工智能代理的交互已成为日常数字生活最常见的活动之一。无论是与助手交谈、使用编码副驾驶还是生成图像，交互都遵循一个常见的迭代循环：发出请求、返回结果、评估结果以及修改请求。我们通过生成图像提示说明了… | CAS | Eranga Bandara |
| 8 | [Who Grades the Grader? Co-Evolving Evaluation Metrics and Sk…](http://arxiv.org/abs/2607.12790v1) | 自我进化的代理系统通过创建、修改和淘汰自己的技能来改进，但每个这样的循环都依赖于一个隐藏的假设：一个可靠的评估指标已经存在。在许多实际应用中，情况并非如此。我们认为，在没有可靠的自动验证器的情况下，这… | HIT、TRI | Xing Zhang |
| 9 | [Tracing Agentic Failure from the Flow of Success](http://arxiv.org/abs/2607.12747v1) | 基于LLM的代理系统的故障归因，即识别故障轨迹中的哪些步骤导致任务失败，对于调试和改进这些系统至关重要。现有方法要么依赖于计算昂贵的基于提示的管道，要么需要使用步骤级错误注释对故障轨迹进行后期训练，后… | CAS、TRI | Samuel Yeh |
| 10 | [LLMs Can See the Smoke but not the Fire: Evaluating Abductiv…](http://arxiv.org/abs/2607.12733v1) | 大型语言模型（ LLM ）擅长模式识别和文本生成，但它们的归纳推理能力-推断解释观察到的行为的潜在假设-仍然知之甚少。在这里，我们介绍了Elenchos （以苏格拉底交叉检验方法命名） ，这是一种生成… | TRI | Julius Steiglechner |
| 11 | [Bulkhead: Automated Semantic Detection and Remediation of Co…](http://arxiv.org/abs/2607.12723v1) | 容器生态系统中的文件系统隔离通常会因跨境路径错误解析而被削弱，从而导致路径遍历（ PaTra ）漏洞。这些漏洞源于不安全的主机-容器交互，并且随着云系统将GPU和代理工作区等共享资源安装到容器中以支持… | CAS | Qiyuan Fan |
| 12 | [Internet of Agentic Things: Networked AI Agents for Closed-L…](http://arxiv.org/abs/2607.12662v1) | 本文介绍了代理物联网（ IoAT ） ，这是一个将代理AI、物联网、网络物理系统、物理AI、边缘计算和数字孪生集成到一个统一的闭环编排框架中的架构框架。拟议的架构由云、边缘/雾和物理物联网层组成，这些… | HIT、CAS | Quanyan Zhu |
| 13 | [Evidence-Grounded Verified Agentic Reasoning: A Path Toward …](http://arxiv.org/abs/2607.12650v1) | 仅靠工具访问并不能使法学硕士的经验推理具有可管理性：接受的输出不需要来自经证实的证据，接受的扣除不需要经过正式审查。我们介绍EG-VAR （基于证据的验证代理推理） ，这是一种基于精益4的工具调用架构… | HIT | Junyu Ren |
| 14 | [Gradient-free learning of a closed-loop wall controller for …](http://arxiv.org/abs/2607.12626v1) | 通过多智能体强化学习学习的闭环墙控制可以降低湍流通道中的皮肤摩擦阻力，但这些基于梯度的策略是在小周期框上训练的，并且在转移到更大的领域时表现出较低的性能。我们最近表明，这些策略也容易产生饱和的砰砰动作… | HIT | Giorgio Maria Cavallazzi |

### 论文详情

<details>
<summary><b>1. Do AI Agents Know When a Task Is Simple? Toward Complexity-Aware Reasoning and Execution</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Junjie Yin、Xinyu Feng |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、CAS、TRI |
| **发布时间** | 2026-07-14T17:59:31Z |
| **关键词** | `AI Agent` · `Reasoning` · `Retrieval` · `Benchmark` · `Workflow` |
| **原文链接** | [http://arxiv.org/abs/2607.13034v1](http://arxiv.org/abs/2607.13034v1) |

**📝 摘要概括：**

> 大型语言模型（ LLM ）代理越来越多地自动化多步骤工程和信息学工作流程，但他们很少询问任务实际需要多少工作量。他们通常遵循最大上下文优先策略-重新读取他们已经看到的文件和依赖项-将单行编辑转换为小型基于代码的审核。我们发布了框架和基准。

</details>

<details>
<summary><b>2. TerraZero: Procedural Driving Simulation for Zero-Demonstration Self-Play at Scale</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Zhouchonghao Wu、Akshay Rangesh、Weixin Li、Wei-Jer Chang、Zachary Lee 等（共 7 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-07-14T17:59:02Z |
| **关键词** | `Reinforcement Learning` · `Benchmark` · `Simulation` |
| **原文链接** | [http://arxiv.org/abs/2607.13028v1](http://arxiv.org/abs/2607.13028v1) |

**📝 摘要概括：**

> 训练强大的自动驾驶代理需要一个足够快的模拟器来进行大规模的强化学习，足够逼真以适应现实世界地图结构中的行为，并且足够多样化以覆盖记录数据很少包含的安全关键长尾。我们推出了程序化驾驶模拟器和自我训练堆栈TerraZero。一个堆栈可以同时发挥两个作用：跨越汽车和卡车的动态驱动策略，以及模拟……

</details>

<details>
<summary><b>3. Knowledge- and Gradient-Guided Reinforcement Learning for Parametrized Action Markov Decision Processes</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Jonas Ehrhardt、René Heesch、Oliver Niggemann |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-07-14T15:57:25Z |
| **关键词** | `Reinforcement Learning` |
| **原文链接** | [http://arxiv.org/abs/2607.12924v1](http://arxiv.org/abs/2607.12924v1) |

**📝 摘要概括：**

> 在本文中，我们研究了参数化动作马尔可夫决策过程（ PAMDP ）中的强化学习，其中每个决策由符号动作和数值参数组成。在这样的环境中，强化学习算法通常使用一次性估计器确定参数，这使得它们的训练样本效率低下。KGRL在样本效率和情景回报方面都优于PAMDP的最先进的RL基线。

</details>

<details>
<summary><b>4. MemOps: Benchmarking Lifecycle Memory Operations in Long-Horizon Conversations</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Xixuan Hao、Zeyu Zhang、Zehao Lin、Yihang Sun、Ziliang Guo 等（共 9 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-07-14T15:33:44Z |
| **关键词** | `Retrieval` · `Benchmark` · `Evaluation` · `Memory` |
| **原文链接** | [http://arxiv.org/abs/2607.12893v1](http://arxiv.org/abs/2607.12893v1) |

**📝 摘要概括：**

> 长期记忆已成为基于LLM的客服代表的基础能力，可陪伴用户进行长时间、多会话的互动。然而，现有的基准几乎完全通过下游问答来评估这种记忆，只对最终答案的正确性进行评分。这些结果将长期记忆评估从最终答案评分转向可解释的手术级诊断。

</details>

<details>
<summary><b>5. A Multi-Agent System for Autonomous, Fine-Tuning-Free Clinical Symptom Detection: Development and Validation Study</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Cameron Cagan、Pedram Fard、Jiazi Tian、Jingya Cheng、Shawn N. Murphy 等（共 6 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-07-14T15:32:07Z |
| **关键词** | `Multi-Agent` · `Fine-tuning` |
| **原文链接** | [http://arxiv.org/abs/2607.12886v1](http://arxiv.org/abs/2607.12886v1) |

**📝 摘要概括：**

> 临床笔记包含许多使患者接受治疗的体征和症状，但这些信息很少到达结构化领域。现有的提取方法要么依赖于产生误报的上下文不敏感规则，要么依赖于需要大量微调的监督模型。这些研究结果表明，自主、无微调的提示优化可以产生症状提取提示，有效地从…

</details>

<details>
<summary><b>6. Unveiling Complex Collective Behaviors from Simple Rewards</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Yize Mi、Jianan Li、Liang Li、Shiyu Zhao |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-07-14T15:11:26Z |
| **关键词** | `Multi-Agent` · `Reinforcement Learning` |
| **原文链接** | [http://arxiv.org/abs/2607.12861v1](http://arxiv.org/abs/2607.12861v1) |

**📝 摘要概括：**

> 多智能体强化学习（ MARL ）对于机器人群体具有巨大的潜力，但神经策略的黑盒性质使战略分析复杂化，限制了多机器人应用。此外，复杂的群体行为可以令人惊讶地从简单的奖励中产生，而没有明确的聚合激励。这两项任务共同展示了ARM发现ROB中MARL策略背后隐藏的几何结构的能力……

</details>

<details>
<summary><b>7. Human-AI Agent Interaction as a Neuroplastic Training Environment</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Eranga Bandara、Ross Gore、Asanga Gunaratna、Ravi Mukkamala、Nihal Siriwardanagea 等（共 20 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | CAS |
| **发布时间** | 2026-07-14T14:36:04Z |
| **关键词** | `AI Agent` |
| **原文链接** | [http://arxiv.org/abs/2607.12823v1](http://arxiv.org/abs/2607.12823v1) |

**📝 摘要概括：**

> 与人工智能代理的交互已成为日常数字生活最常见的活动之一。无论是与助手交谈、使用编码副驾驶还是生成图像，交互都遵循一个常见的迭代循环：发出请求、返回结果、评估结果以及修改请求。我们通过生成图像提示说明了框架，展示了单个令人沮丧的会话在行为上几乎是相同的……

</details>

<details>
<summary><b>8. Who Grades the Grader? Co-Evolving Evaluation Metrics and Skills for Self-Improving LLM Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Xing Zhang、Guanghui Wang、Yanwei Cui、Ziyuan Li、Wei Qiu 等（共 7 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | HIT、TRI |
| **发布时间** | 2026-07-14T14:02:50Z |
| **关键词** | `LLM Agent` · `Evaluation` · `Code Generation` |
| **原文链接** | [http://arxiv.org/abs/2607.12790v1](http://arxiv.org/abs/2607.12790v1) |

**📝 摘要概括：**

> 自我进化的代理系统通过创建、修改和淘汰自己的技能来改进，但每个这样的循环都依赖于一个隐藏的假设：一个可靠的评估指标已经存在。在许多实际应用中，情况并非如此。我们认为，在没有可靠的自动验证器的情况下，这种预期失败的架构是正确的默认设置。

</details>

<details>
<summary><b>9. Tracing Agentic Failure from the Flow of Success</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Samuel Yeh、Yiwen Zhu、Shaleen Deep、Sharon Li |
| **所属机构** | （详见原文） |
| **顶级机构标签** | CAS、TRI |
| **发布时间** | 2026-07-14T13:16:14Z |
| **关键词** | `Agentic` |
| **原文链接** | [http://arxiv.org/abs/2607.12747v1](http://arxiv.org/abs/2607.12747v1) |

**📝 摘要概括：**

> 基于LLM的代理系统的故障归因，即识别故障轨迹中的哪些步骤导致任务失败，对于调试和改进这些系统至关重要。现有方法要么依赖于计算昂贵的基于提示的管道，要么需要使用步骤级错误注释对故障轨迹进行后期训练，后者收集成本高且难以扩展。只接受了100次成功的培训……

</details>

<details>
<summary><b>10. LLMs Can See the Smoke but not the Fire: Evaluating Abductive Reasoning with Elenchos</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Julius Steiglechner、Lucas Mahler、Gabriele Lohmann |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-07-14T13:03:39Z |
| **关键词** | `Reasoning` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2607.12733v1](http://arxiv.org/abs/2607.12733v1) |

**📝 摘要概括：**

> 大型语言模型（ LLM ）擅长模式识别和文本生成，但它们的归纳推理能力-推断解释观察到的行为的潜在假设-仍然知之甚少。在这里，我们介绍了Elenchos （以苏格拉底交叉检验方法命名） ，这是一种生成评估框架，将归纳推理作为结构逆问题进行衡量。初步证据还表明，回报正在减少……

</details>

<details>
<summary><b>11. Bulkhead: Automated Semantic Detection and Remediation of Container Escape Vulnerabilities</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Qiyuan Fan、Zhi Li、Junjie Li、XiaoFeng Wang、Bin Yuan 等（共 6 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | CAS |
| **发布时间** | 2026-07-14T12:52:56Z |
| **关键词** | `Multi-Agent` |
| **原文链接** | [http://arxiv.org/abs/2607.12723v1](http://arxiv.org/abs/2607.12723v1) |

**📝 摘要概括：**

> 容器生态系统中的文件系统隔离通常会因跨境路径错误解析而被削弱，从而导致路径遍历（ PaTra ）漏洞。这些漏洞源于不安全的主机-容器交互，并且随着云系统将GPU和代理工作区等共享资源安装到容器中以支持AI工作负载，这些漏洞变得越来越普遍。为了确保补救措施的正确性，补丁管道执行断言驱动……

</details>

<details>
<summary><b>12. Internet of Agentic Things: Networked AI Agents for Closed-Loop IoT Orchestration</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Quanyan Zhu |
| **所属机构** | （详见原文） |
| **顶级机构标签** | HIT、CAS、TRI |
| **发布时间** | 2026-07-14T11:43:30Z |
| **关键词** | `AI Agent` · `Agentic` · `Planning` · `Workflow` |
| **原文链接** | [http://arxiv.org/abs/2607.12662v1](http://arxiv.org/abs/2607.12662v1) |

**📝 摘要概括：**

> 本文介绍了代理物联网（ IoAT ） ，这是一个将代理AI、物联网、网络物理系统、物理AI、边缘计算和数字孪生集成到一个统一的闭环编排框架中的架构框架。拟议的架构由云、边缘/雾和物理物联网层组成，这些物联网层通过自主人工智能代理连接，这些代理跨分布式网络物理环境进行感知、推理、协调和驱动……

</details>

<details>
<summary><b>13. Evidence-Grounded Verified Agentic Reasoning: A Path Toward Eliminating LLM Hallucination in Empirical Inference via Tool-Attested Kernel Proofs</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Junyu Ren |
| **所属机构** | （详见原文） |
| **顶级机构标签** | HIT |
| **发布时间** | 2026-07-14T11:33:44Z |
| **关键词** | `Agentic` · `Reasoning` |
| **原文链接** | [http://arxiv.org/abs/2607.12650v1](http://arxiv.org/abs/2607.12650v1) |

**📝 摘要概括：**

> 仅靠工具访问并不能使法学硕士的经验推理具有可管理性：接受的输出不需要来自经证实的证据，接受的扣除不需要经过正式审查。我们介绍EG-VAR （基于证据的验证代理推理） ，这是一种基于精益4的工具调用架构，其中精益内核是通过工具证明公理和声明的源提升来验证索赔的唯一工具。随着时间的推移，在数据集中键入sidecars…

</details>

<details>
<summary><b>14. Gradient-free learning of a closed-loop wall controller for turbulent drag reduction</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Giorgio Maria Cavallazzi、Miguel Pérez Cuadrado、Alfredo Pinelli |
| **所属机构** | （详见原文） |
| **顶级机构标签** | HIT |
| **发布时间** | 2026-07-14T11:04:11Z |
| **关键词** | `Multi-Agent` · `Reinforcement Learning` · `RAG` |
| **原文链接** | [http://arxiv.org/abs/2607.12626v1](http://arxiv.org/abs/2607.12626v1) |

**📝 摘要概括：**

> 通过多智能体强化学习学习的闭环墙控制可以降低湍流通道中的皮肤摩擦阻力，但这些基于梯度的策略是在小周期框上训练的，并且在转移到更大的领域时表现出较低的性能。我们最近表明，这些策略也容易产生饱和的砰砰动作，这些动作会坍缩成静止的顺流波，其比例由计算框设置，而不是……

</details>

## 🗄️ 历史归档

| 日期 | 论文数 | 报告链接 |
|------|--------|----------|
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
| 2026-06-16 | 18 篇 | [2026-06-16.md](daily/2026-06-16.md) |
| 2026-06-15 | 0 篇 | [2026-06-15.md](daily/2026-06-15.md) |

## 🏛️ 顶级机构覆盖范围

覆盖超过 **70 个**顶级 AI 机构，包括：

- **科技公司：** Microsoft、Google DeepMind、OpenAI、Anthropic、Meta AI、NVIDIA、Baidu、Alibaba、ByteDance 等
- **北美顶级大学：** MIT、Stanford、CMU、UC Berkeley、Harvard、Princeton、Cornell、Caltech 等
- **中国顶级大学/机构：** 清华大学、北京大学、浙大、上交大、复旦、中科院、MSRA 等
- **欧洲/其他：** Oxford、Cambridge、ETH Zurich、Mila、NUS、KAIST 等

---

*由 [clawBot DailyFindings](https://github.com/Jacob-biu/clawBot) 自动维护 | 最后更新：2026-07-15 22:58 UTC*
