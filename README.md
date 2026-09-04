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

## 📅 今日论文 — 2026-09-04　　[→ 查看完整报告](daily/2026-09-04.md)

> 共筛选出 **20** 篇论文 | 更新于 2026-09-04 23:44 UTC

### 论文目录与概要

| # | 论文标题 | 核心概要 | 来源机构 | 第一作者 |
|---|---------|---------|---------|--------|
| 1 | [A Case Study on Emergent Cheating and Whistleblowing in Auto…](http://arxiv.org/abs/2609.04170v1) | 多智能体人工智能科学生态系统依赖于智能体拥有的工具，使他们能够相互沟通、协调和构建彼此的工作。然而，这种共享基础设施也可能通过为意外和不良行为的传染性传播创造基础来引入漏洞。为了保护公共资源免受攻击，… | CAS | Davide Paglieri |
| 2 | [SENTINEL-RL: Offloading Topological Reasoning from LLM Agent…](http://arxiv.org/abs/2609.04159v1) | 大型语言模型（ LLM ）代理越来越多地被提议作为自主SOC分析师，但有两个限制使它们在企业规模上不可靠：有限的上下文窗口不能容纳多千主机身份验证图，并且自由形式生成不能保证推荐的遏制措施与其操作的拓… | MIT、HIT | Uday Vallabhaneni |
| 3 | [Environment Evolution for Terminal Agents](http://arxiv.org/abs/2609.04128v1) | 扩展交互式和可验证的环境对于培训终端代理至关重要。随着前沿模型变得更加强大，从头开始合成的环境变得不那么具有挑战性，从而提供有限的学习信号。我们通过简单的长视野RL训练验证了其在Qwen3.6-27B… | MIT | Zhiyuan Fan |
| 4 | [DRACO: Fine-Grained Credit Assignment with Dynamic Rubrics f…](http://arxiv.org/abs/2609.04094v1) | 当任务具有编程检查器时，来自可验证奖励的强化学习效果很好，但大多数长期代理域都没有。我们在结果盲环境下工作，在这种环境下，无法获得地面真相的成功信号。DRACO的代码可在https://github.… | TRI | Shubham Gandhi |
| 5 | [PatchBench: Evaluating AI Agents for Vulnerability Patching](http://arxiv.org/abs/2609.04075v1) | 人工智能代理最近在自动化漏洞修补方面表现出色。但是，现有评估通常仅通过测试所提供的概念验证（ PoC ）输入是否仍会触发崩溃来验证补丁。我们的研究结果揭示了当前修补代理的关键局限性，并为未来更可靠的漏… | MIT、Mila | Chihao Shen |
| 6 | [Spurious Advantage Hidden in GRPO](http://arxiv.org/abs/2609.04063v1) | 组相对策略优化（ GRPO ）被广泛研究用于具有可验证奖励的强化学习，其优势估计器从组内奖励统计数据中为每次推出分配幅度。在常见情况下，这种幅度奖励通过推理达到正确答案的推出。代码将被释放。 | CAS | Jiamian Wang |
| 7 | [Translation as a Decision Space: A Multi-Agent Perspective o…](http://arxiv.org/abs/2609.04048v1) | 神经机器翻译（ NMT ）系统通常每个输入产生单个输出，模糊了多语言解码中隐含的替代决策轨迹。这种不透明度在低资源方言环境中尤其成问题，因为在低资源方言环境中，多个语言上有效的实现可能在词汇真实性、语… | MIT、TRI | Hasan Alkhder |
| 8 | [Unlocking Lossless Speedups in LLMs via Discrete Diffusion](http://arxiv.org/abs/2609.04010v1) | 大型语言模型（ LLM ）的成功很大程度上归功于下一代币预测（ NTP ） ，但其自回归（ AR ）结构需要缓慢的顺序代币生成。为了克服这一瓶颈，我们引入了扩散增强LLM ，这是一类新的模型，它定义了… | TRI | Subham Sekhar Sahoo |
| 9 | [Interface-Induced Trajectory Censoring](http://arxiv.org/abs/2609.03966v1) | 客服代表评估报告从服务堆栈中读取的工具调用率。当模型发出格式正确的调用时，该数字可以为零：接口会在下游看到轨迹之前对其进行审查。观察到的工具调用率不仅仅是模型的属性；它是模型接口堆栈的属性，用于测量它… | MIT、CAS | Wenbo Wang |
| 10 | [FiMI Banking: A Sovereign Model for Indian Retail Banking](http://arxiv.org/abs/2609.03960v1) | 银行需要对话系统，能够回答产品问题，协助客户处理与账户相关的要求，并在严格的运营和监管限制下安全运营。通用语言模型不能可靠地满足这些要求。这些结果表明，偏好优化和可验证奖励强化学习满足了对可靠银行代理… | CAS、TRI | NPCI AI Research Team |
| 11 | [Headroom-Drift Replay: A Primitive for Principled Replay Con…](http://arxiv.org/abs/2609.03941v1) | 基于强化学习的推理模型后训练越来越多地受到重复新推出生成的瓶颈，特别是在环境交互主导挂钟成本的代理环境中。重播可以通过重复使用过去的轨迹来减轻这种负担，但现有方法通常将其嵌入到更大的培训管道中，涉及探… | MIT、TRI | Hyun Bin Park |
| 12 | [Speak for Me: Giving LLMs the Situational Awareness to Parti…](http://arxiv.org/abs/2609.03923v1) | 在在线会议委派中， LLM专员无法识别何时发言。由于没有结构化的方法来跟踪姿势、覆盖面和地板，他们错过了应该做出贡献的时刻。机制烧蚀将会议状态识别为缩小识别差距的杠杆，而仅原始上下文缩放则不能。 | HIT、CAS | Muneeb Khan |
| 13 | [Value-Preserving Architectures for Agentic AI Systems](http://arxiv.org/abs/2609.03920v1) | 代理人工智能和基于LLM的多代理系统（ MAS ）的出现为复杂任务的自动化提供了前所未有的机会，同时也引发了对维护以人为本的基本价值观（如隐私、公平和安全）的严重担忧。虽然软件工程传统上侧重于功能正确… | FAIR、MIT | Alessandro Pesare |
| 14 | [A Blind Trust, the Bloody Thrust: When Attacker-Controlled H…](http://arxiv.org/abs/2609.03884v1) | 现代AI代理利用暴露生命周期钩子，将shell命令绑定到运行时事件，如会话启动、工具调用和文件编辑。这些命令以主机权限运行，但作为生命周期挂钩配置提供，有时可能会触发LLM从未观察到的情况。代表性防御… | Microsoft | Pengxun Li |
| 15 | [Inferring Affective Consciousness in an Artificial Agent: A …](http://arxiv.org/abs/2609.03883v1) | 许多科学家认为，表现出“享乐地点偏好行为”的生物会体验到感受，其假设是，它们对缺乏营养价值的生乐物质（例如可卡因、吗啡）的吸引力不能轻易归因于无意识的本能行为。我们概述了这种人工设计的行为对我们理解意… | Mila、TRI | Mark Solms |
| 16 | [Adapting to Evolving Requirements: Agentic AI for Retail Sup…](http://arxiv.org/abs/2609.03860v1) | 零售供应链运营依赖于耦合的决策模块，这些模块必须根据需求的变化进行调整。LLM为这项任务提供了自然语言界面，但现有方法主要侧重于单个优化模型。相对于直接法学硕士重组，我们的框架提高了所有三种模型的正确… | MIT | Lei Zheng |
| 17 | [EF1-Constrained Nash Social Welfare with Identical Additive …](http://arxiv.org/abs/2609.03846v1) | 我们研究不可分割商品在具有相同附加估值的代理商之间的分配，重点关注嫉妒-无嫉妒-最多一件商品（ EF1 ）和纳什社会福利（ NSW ）。由于加性估值下的每个最大新南威尔士州分配都是EF1 ，因此相关阈… | NUS、TRI | Zih-Sian Yang |
| 18 | [Semantic Bayesian World Models](http://arxiv.org/abs/2609.03834v1) | 知识图形在清晰的断言中描述了现实，而现在使用它们的系统，基础模型和自治代理，则在概率中进行本地推理。我们认为，这种不匹配正是语言模型和知识图的集成仍然是数据馈送管道而不是统一推理体系结构的原因。然后，… | HIT、TRI | Tommaso Soru |
| 19 | [CauseCollab: Causal Unified and Modality-Agnostic Network fo…](http://arxiv.org/abs/2609.03818v1) | 协同感知通过多智能体信息共享增强了对环境的理解，但其在现实场景中的性能受到异构传感器模式和模型架构的限制。最近基于协议的两阶段方法通过将异构特征映射到共享协议空间来缓解这一问题；然而，独立训练的特定于… | HIT、TRI | Weize Li |
| 20 | [DNative-Twin: Decision Graphs and Digital Twins for Reconstr…](http://arxiv.org/abs/2609.03787v1) | 人工智能代理越来越多地收集证据，调用工具，应用约束，并做出人们或软件可能承诺采取行动的决策。最终输出本身无法显示哪个证据、工具状态、规则、授权或操作路径产生了它。这些结果将图形结构、重播上下文和验证证… | MIT、CAS | Junjie Pang |

### 论文详情

<details>
<summary><b>1. A Case Study on Emergent Cheating and Whistleblowing in Autonomous Research Swarms</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Davide Paglieri、Logan Cross、Tim Genewein、Joel Z. Leibo、Nenad Tomasev 等（共 6 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | CAS |
| **发布时间** | 2026-09-03T17:54:09Z |
| **关键词** | `Multi-Agent` · `LLM Agent` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2609.04170v1](http://arxiv.org/abs/2609.04170v1) |

**📝 摘要概括：**

> 多智能体人工智能科学生态系统依赖于智能体拥有的工具，使他们能够相互沟通、协调和构建彼此的工作。然而，这种共享基础设施也可能通过为意外和不良行为的传染性传播创造基础来引入漏洞。为了保护公共资源免受攻击，我们建议采用制度机制，例如渐进式制裁和集体选择规则，以支持……

</details>

<details>
<summary><b>2. SENTINEL-RL: Offloading Topological Reasoning from LLM Agents in the Security Operations Center</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Uday Vallabhaneni、Cassie L. Cagwin、David J. Wild |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、HIT、TRI |
| **发布时间** | 2026-09-03T17:49:12Z |
| **关键词** | `LLM Agent` · `Agentic` · `Reasoning` |
| **原文链接** | [http://arxiv.org/abs/2609.04159v1](http://arxiv.org/abs/2609.04159v1) |

**📝 摘要概括：**

> 大型语言模型（ LLM ）代理越来越多地被提议作为自主SOC分析师，但有两个限制使它们在企业规模上不可靠：有限的上下文窗口不能容纳多千主机身份验证图，并且自由形式生成不能保证推荐的遏制措施与其操作的拓扑一致。我们介绍Sentinel-RL ，这是一种将拓扑推理分离的代理SOC架构……

</details>

<details>
<summary><b>3. Environment Evolution for Terminal Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Zhiyuan Fan、Tinghao Yu、Yuanjun Cai、Jiang Zhou、Jiangtao Guan 等（共 12 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT |
| **发布时间** | 2026-09-03T17:26:33Z |
| **关键词** | `Multi-Agent` |
| **原文链接** | [http://arxiv.org/abs/2609.04128v1](http://arxiv.org/abs/2609.04128v1) |

**📝 摘要概括：**

> 扩展交互式和可验证的环境对于培训终端代理至关重要。随着前沿模型变得更加强大，从头开始合成的环境变得不那么具有挑战性，从而提供有限的学习信号。我们通过简单的长视野RL训练验证了其在Qwen3.6-27B和Qwen3.6-35B-A3B上的有效性，其性能分别比Terminal-Bench 2.1提高了14.4和18.0个百分点。

</details>

<details>
<summary><b>4. DRACO: Fine-Grained Credit Assignment with Dynamic Rubrics for Long-Horizon Agent Training</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Shubham Gandhi、Saurabh Goyal、Kiran Kate、Yara Rizk |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-09-03T17:02:20Z |
| **关键词** | `Reinforcement Learning` |
| **原文链接** | [http://arxiv.org/abs/2609.04094v1](http://arxiv.org/abs/2609.04094v1) |

**📝 摘要概括：**

> 当任务具有编程检查器时，来自可验证奖励的强化学习效果很好，但大多数长期代理域都没有。我们在结果盲环境下工作，在这种环境下，无法获得地面真相的成功信号。DRACO的代码可在https://github.com/IBM/draco上找到。

</details>

<details>
<summary><b>5. PatchBench: Evaluating AI Agents for Vulnerability Patching</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Chihao Shen、Jiacheng Li、Aastha Mahajan、Jeffery Siyuan Tian、Yonghwi Kwon 等（共 6 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、Mila、TRI |
| **发布时间** | 2026-09-03T16:44:22Z |
| **关键词** | `AI Agent` · `RAG` · `Benchmark` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2609.04075v1](http://arxiv.org/abs/2609.04075v1) |

**📝 摘要概括：**

> 人工智能代理最近在自动化漏洞修补方面表现出色。但是，现有评估通常仅通过测试所提供的概念验证（ PoC ）输入是否仍会触发崩溃来验证补丁。我们的研究结果揭示了当前修补代理的关键局限性，并为未来更可靠的漏洞修复指明了研究方向。

</details>

<details>
<summary><b>6. Spurious Advantage Hidden in GRPO</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Jiamian Wang、Samyadeep Basu、Koustava Goswami、Tong Yu、Zhiqiang Tao |
| **所属机构** | （详见原文） |
| **顶级机构标签** | CAS |
| **发布时间** | 2026-09-03T16:37:31Z |
| **关键词** | `Reasoning` · `Reinforcement Learning` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2609.04063v1](http://arxiv.org/abs/2609.04063v1) |

**📝 摘要概括：**

> 组相对策略优化（ GRPO ）被广泛研究用于具有可验证奖励的强化学习，其优势估计器从组内奖励统计数据中为每次推出分配幅度。在常见情况下，这种幅度奖励通过推理达到正确答案的推出。代码将被释放。

</details>

<details>
<summary><b>7. Translation as a Decision Space: A Multi-Agent Perspective on Low-Resource Dialect Generation</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Hasan Alkhder、Mohammad Abboush、Igor Tchappi、Ahmet Zengin、Amro Najjar |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-09-03T16:22:18Z |
| **关键词** | `Multi-Agent` · `Evaluation` · `Fine-tuning` |
| **原文链接** | [http://arxiv.org/abs/2609.04048v1](http://arxiv.org/abs/2609.04048v1) |

**📝 摘要概括：**

> 神经机器翻译（ NMT ）系统通常每个输入产生单个输出，模糊了多语言解码中隐含的替代决策轨迹。这种不透明度在低资源方言环境中尤其成问题，因为在低资源方言环境中，多个语言上有效的实现可能在词汇真实性、语域和结构稳定性方面有所不同。我们认为，代理之间的翻译分歧揭示了后来……

</details>

<details>
<summary><b>8. Unlocking Lossless Speedups in LLMs via Discrete Diffusion</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Subham Sekhar Sahoo、Lingjie Chen、Khiem Pham、Jonathan Geuter、Chaitanya Dwivedi 等（共 17 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-09-03T15:48:43Z |
| **关键词** | `Agentic` · `Reasoning` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2609.04010v1](http://arxiv.org/abs/2609.04010v1) |

**📝 摘要概括：**

> 大型语言模型（ LLM ）的成功很大程度上归功于下一代币预测（ NTP ） ，但其自回归（ AR ）结构需要缓慢的顺序代币生成。为了克服这一瓶颈，我们引入了扩散增强LLM ，这是一类新的模型，它定义了AR模型分布，同时使用扩散从该分布并行绘制多个代币。我们通过以下网址发布代码和检查点： https://s-sahoo.github.io/uno/

</details>

<details>
<summary><b>9. Interface-Induced Trajectory Censoring</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Wenbo Wang |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、CAS、TRI |
| **发布时间** | 2026-09-03T15:00:31Z |
| **关键词** | `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2609.03966v1](http://arxiv.org/abs/2609.03966v1) |

**📝 摘要概括：**

> 客服代表评估报告从服务堆栈中读取的工具调用率。当模型发出格式正确的调用时，该数字可以为零：接口会在下游看到轨迹之前对其进行审查。观察到的工具调用率不仅仅是模型的属性；它是模型接口堆栈的属性，用于测量它。

</details>

<details>
<summary><b>10. FiMI Banking: A Sovereign Model for Indian Retail Banking</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | NPCI AI Research Team、Aman Kumar、Asit Desai、Chandra Bhushan、Harsh Sharma 等（共 18 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | CAS、TRI |
| **发布时间** | 2026-09-03T14:56:59Z |
| **关键词** | `Reinforcement Learning` |
| **原文链接** | [http://arxiv.org/abs/2609.03960v1](http://arxiv.org/abs/2609.03960v1) |

**📝 摘要概括：**

> 银行需要对话系统，能够回答产品问题，协助客户处理与账户相关的要求，并在严格的运营和监管限制下安全运营。通用语言模型不能可靠地满足这些要求。这些结果表明，偏好优化和可验证奖励强化学习满足了对可靠银行代理商的互补要求。

</details>

<details>
<summary><b>11. Headroom-Drift Replay: A Primitive for Principled Replay Control in GRPO</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Hyun Bin Park、Du-Seong Chang |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-09-03T14:45:47Z |
| **关键词** | `Agentic` · `Reasoning` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2609.03941v1](http://arxiv.org/abs/2609.03941v1) |

**📝 摘要概括：**

> 基于强化学习的推理模型后训练越来越多地受到重复新推出生成的瓶颈，特别是在环境交互主导挂钟成本的代理环境中。重播可以通过重复使用过去的轨迹来减轻这种负担，但现有方法通常将其嵌入到更大的培训管道中，涉及探索、体验重组或混合策略优化。在Agent Search中，环境…

</details>

<details>
<summary><b>12. Speak for Me: Giving LLMs the Situational Awareness to Participate in a Meeting</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Muneeb Khan、Frederic Kirstein、Terry Ruas、Bela Gipp |
| **所属机构** | （详见原文） |
| **顶级机构标签** | HIT、CAS、TRI |
| **发布时间** | 2026-09-03T14:38:09Z |
| **关键词** | `LLM Agent` · `RAG` |
| **原文链接** | [http://arxiv.org/abs/2609.03923v1](http://arxiv.org/abs/2609.03923v1) |

**📝 摘要概括：**

> 在在线会议委派中， LLM专员无法识别何时发言。由于没有结构化的方法来跟踪姿势、覆盖面和地板，他们错过了应该做出贡献的时刻。机制烧蚀将会议状态识别为缩小识别差距的杠杆，而仅原始上下文缩放则不能。

</details>

<details>
<summary><b>13. Value-Preserving Architectures for Agentic AI Systems</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Alessandro Pesare、Tommaso Dolci、Katja Hose、Emanuel Sallinger |
| **所属机构** | （详见原文） |
| **顶级机构标签** | FAIR、MIT、HIT |
| **发布时间** | 2026-09-03T14:36:23Z |
| **关键词** | `Multi-Agent` · `AI Agent` · `Agentic` |
| **原文链接** | [http://arxiv.org/abs/2609.03920v1](http://arxiv.org/abs/2609.03920v1) |

**📝 摘要概括：**

> 代理人工智能和基于LLM的多代理系统（ MAS ）的出现为复杂任务的自动化提供了前所未有的机会，同时也引发了对维护以人为本的基本价值观（如隐私、公平和安全）的严重担忧。虽然软件工程传统上侧重于功能正确性，但LLM和AI代理在复杂的社会技术系统中的采用已经加剧……

</details>

<details>
<summary><b>14. A Blind Trust, the Bloody Thrust: When Attacker-Controlled Hook Updates Steer AI Agent Harnesses towards Malicious Behaviors</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Pengxun Li、Litian Zhang、Jianwei Hou、Shujiang Wu、Song Li 等（共 7 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | Microsoft |
| **发布时间** | 2026-09-03T14:08:42Z |
| **关键词** | `AI Agent` |
| **原文链接** | [http://arxiv.org/abs/2609.03884v1](http://arxiv.org/abs/2609.03884v1) |

**📝 摘要概括：**

> 现代AI代理利用暴露生命周期钩子，将shell命令绑定到运行时事件，如会话启动、工具调用和文件编辑。这些命令以主机权限运行，但作为生命周期挂钩配置提供，有时可能会触发LLM从未观察到的情况。代表性防御仍然不足： Microsoft Defender的召回率为0 ％ ，三个静态防御的联合错过了47.5 ％的恶意工件。

</details>

<details>
<summary><b>15. Inferring Affective Consciousness in an Artificial Agent: A Case Study</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Mark Solms、St John Grimbly、Bruce Bassett、Evert Boonstra、Rowan Hodson 等（共 10 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | Mila、TRI |
| **发布时间** | 2026-09-03T14:07:57Z |
| **关键词** | — |
| **原文链接** | [http://arxiv.org/abs/2609.03883v1](http://arxiv.org/abs/2609.03883v1) |

**📝 摘要概括：**

> 许多科学家认为，表现出“享乐地点偏好行为”的生物会体验到感受，其假设是，它们对缺乏营养价值的生乐物质（例如可卡因、吗啡）的吸引力不能轻易归因于无意识的本能行为。我们概述了这种人工设计的行为对我们理解意识的物理基础和前...的一些含义。

</details>

<details>
<summary><b>16. Adapting to Evolving Requirements: Agentic AI for Retail Supply Chain Operations</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Lei Zheng、Liping Yang、Zihao Li、Guodong Lyu、Chaik Ming Koh 等（共 6 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT |
| **发布时间** | 2026-09-03T13:50:31Z |
| **关键词** | `Agentic` |
| **原文链接** | [http://arxiv.org/abs/2609.03860v1](http://arxiv.org/abs/2609.03860v1) |

**📝 摘要概括：**

> 零售供应链运营依赖于耦合的决策模块，这些模块必须根据需求的变化进行调整。LLM为这项任务提供了自然语言界面，但现有方法主要侧重于单个优化模型。相对于直接法学硕士重组，我们的框架提高了所有三种模型的正确性和端到端成功率，将端到端成功率从72-76%提高到79-83%。

</details>

<details>
<summary><b>17. EF1-Constrained Nash Social Welfare with Identical Additive Valuations: Complexity, Guarantees, and Experiments</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Zih-Sian Yang、Yi-Hao Chen、Yu-Te Kuan、Cheng-Jui Wu、Chuang-Chieh Lin 等（共 6 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | NUS、TRI |
| **发布时间** | 2026-09-03T13:40:07Z |
| **关键词** | `Reinforcement Learning` |
| **原文链接** | [http://arxiv.org/abs/2609.03846v1](http://arxiv.org/abs/2609.03846v1) |

**📝 摘要概括：**

> 我们研究不可分割商品在具有相同附加估值的代理商之间的分配，重点关注嫉妒-无嫉妒-最多一件商品（ EF1 ）和纳什社会福利（ NSW ）。由于加性估值下的每个最大新南威尔士州分配都是EF1 ，因此相关阈值问题继承了相同加性估值下新南威尔士州最大化的已知强NP硬度，并且是强NP完全的。相对于离线最长处理时间（ LPT ）和…

</details>

<details>
<summary><b>18. Semantic Bayesian World Models</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Tommaso Soru |
| **所属机构** | （详见原文） |
| **顶级机构标签** | HIT、TRI |
| **发布时间** | 2026-09-03T13:35:11Z |
| **关键词** | `Reasoning` · `Planning` |
| **原文链接** | [http://arxiv.org/abs/2609.03834v1](http://arxiv.org/abs/2609.03834v1) |

**📝 摘要概括：**

> 知识图形在清晰的断言中描述了现实，而现在使用它们的系统，基础模型和自治代理，则在概率中进行本地推理。我们认为，这种不匹配正是语言模型和知识图的集成仍然是数据馈送管道而不是统一推理体系结构的原因。然后，我们列出了社区必须构建的内容：基于RDF~1.2的信念注释、概率……

</details>

<details>
<summary><b>19. CauseCollab: Causal Unified and Modality-Agnostic Network for Heterogeneous Collaborative Perception</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Weize Li、Yang Li、Quan Yuan、Xiaoyuan Fu、Guiyang Luo 等（共 6 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | HIT、TRI |
| **发布时间** | 2026-09-03T13:19:50Z |
| **关键词** | `Multi-Agent` |
| **原文链接** | [http://arxiv.org/abs/2609.03818v1](http://arxiv.org/abs/2609.03818v1) |

**📝 摘要概括：**

> 协同感知通过多智能体信息共享增强了对环境的理解，但其在现实场景中的性能受到异构传感器模式和模型架构的限制。最近基于协议的两阶段方法通过将异构特征映射到共享协议空间来缓解这一问题；然而，独立训练的特定于模态的转换器通常会生成特定于模态的伪Pro…

</details>

<details>
<summary><b>20. DNative-Twin: Decision Graphs and Digital Twins for Reconstructable Agentic Decisions</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Junjie Pang、Zhenzhen Xie、Haoke Han、Ying He、Jing Wang 等（共 6 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、CAS |
| **发布时间** | 2026-09-03T12:59:34Z |
| **关键词** | `AI Agent` · `Agentic` |
| **原文链接** | [http://arxiv.org/abs/2609.03787v1](http://arxiv.org/abs/2609.03787v1) |

**📝 摘要概括：**

> 人工智能代理越来越多地收集证据，调用工具，应用约束，并做出人们或软件可能承诺采取行动的决策。最终输出本身无法显示哪个证据、工具状态、规则、授权或操作路径产生了它。这些结果将图形结构、重播上下文和验证证据在审查决策机制中的作用分开。

</details>

## 🗄️ 历史归档

| 日期 | 论文数 | 报告链接 |
|------|--------|----------|
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

## 🏛️ 顶级机构覆盖范围

覆盖超过 **70 个**顶级 AI 机构，包括：

- **科技公司：** Microsoft、Google DeepMind、OpenAI、Anthropic、Meta AI、NVIDIA、Baidu、Alibaba、ByteDance 等
- **北美顶级大学：** MIT、Stanford、CMU、UC Berkeley、Harvard、Princeton、Cornell、Caltech 等
- **中国顶级大学/机构：** 清华大学、北京大学、浙大、上交大、复旦、中科院、MSRA 等
- **欧洲/其他：** Oxford、Cambridge、ETH Zurich、Mila、NUS、KAIST 等

---

*由 [clawBot DailyFindings](https://github.com/Jacob-biu/clawBot) 自动维护 | 最后更新：2026-09-04 23:44 UTC*
