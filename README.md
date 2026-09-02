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

## 📅 今日论文 — 2026-09-02　　[→ 查看完整报告](daily/2026-09-02.md)

> 共筛选出 **20** 篇论文 | 更新于 2026-09-02 23:52 UTC

### 论文目录与概要

| # | 论文标题 | 核心概要 | 来源机构 | 第一作者 |
|---|---------|---------|---------|--------|
| 1 | [Efficient SWE Agent Benchmarking via Trajectory-Aware Evalua…](http://arxiv.org/abs/2609.01603v1) | 在现实的基准上评估软件工程代理是昂贵的，因为每个任务可能需要多步代码探索、修改和测试执行。现有的有效评估方法选择代表性子集来评估完整基准性能，但主要是结果：它们符合历史通过/失败响应矩阵或静态任务语义… | TRI | Kefeng Duan |
| 2 | [CordisBench: Can Language Models Reason About Component Life…](http://arxiv.org/abs/2609.01600v1) | 动态代理利用让语言模型改变塑造其自身执行的软件。这种灵活性带来了新的推理负担：本地插件更改可以通过依赖关系和清理进行传播。对于这些受控实例，这种成本是可以避免的：独立的有限参考语义与用于对所有528个… | TRI | Damien Sileo |
| 3 | [Mechanism Design for Alignment and Control](http://arxiv.org/abs/2609.01595v1) | 我们开发了一个与AI代理进行机制设计的框架，其一致性（偏好）和能力（可行的行动和信息）是未知的。我们希望这些代理代表我们行事，因此机制必须激励诚实和服从。我们将我们的框架应用于以下风格化的示例： （ … | MIT | Dirk Bergemann |
| 4 | [Retrieved but not ranked: surface-form bias in structural re…](http://arxiv.org/abs/2609.01556v1) | 我们评估了有意将表面形式和含义分开的嵌入式检索：在一个协议下的两个不相关的领域中检索共享基础结构但不具有措辞的项目，即竞争数学（ MathNet-Retrieve ； 500个查询， 117,088个… | HIT、Mila | Nabira Rashid |
| 5 | [NashDreamer: Model-Based Reinforcement Learning for Zero-Sum…](http://arxiv.org/abs/2609.01549v1) | 基于模型的强化学习（ MBRL ）在单智能体领域取得了显着成果，但其扩展到竞争性不完善信息游戏（ IIG ）方面仍未得到充分探索。在多智能体环境中，对手诱导的非平稳性使学习过程复杂化，分散式模型学习面… | HIT | Tomáš Holeček |
| 6 | [EvoSCM: Scientific Belief Revision Through Causal Model Evol…](http://arxiv.org/abs/2609.01526v1) | 科学代理人不仅要学会如何推理，还要学会相信什么。然而，现有的LLM代理通常以自由格式文本表达科学假设，使他们的信念隐含且难以测试或修改。EvoSCM在基线基础上不断改进科学发现，产生更准确的解释和预测… | MIT | Qing Zhao |
| 7 | [When Guardrails Look Effective: Construct Validity Failures …](http://arxiv.org/abs/2609.01519v1) | 交互式模拟越来越多地评估由语言模型代理商填充的市场中的策略。他们的产出看起来很经济--价格、利润、消费者剩余和福利--而无需实例化索赔中提到的行为。个案并未表明护栏无效；它表明在模拟药物和方案通过这些… | CAS、TRI | Peiying Zhu |
| 8 | [Parsing the Stream: A Live Trace Model for Long-Horizon Agen…](http://arxiv.org/abs/2609.01466v1) | 长视野代理的跟踪超出了其消费者：监视运行的人类观察者和代理本身，必须将跟踪折叠回其有界上下文。我们提出了一个实时跟踪模型，这是一个仅追加的事件分类账，逐渐折叠成类型化的运行状态，并编译成每位消费者的视… | MIT、TRI | Egor Pakhomov |
| 9 | [TRIAGE: Three-level Routing and Intelligent Agent Guidance f…](http://arxiv.org/abs/2609.01428v1) | 基于ReAct范式的大型语言模型（ LLM ）代理在工具使用和任务执行方面表现出非凡的能力。然而， ReAct面临着一个基本的效率问题：每个查询都会从头开始触发一个完整的推理循环，并且类似的查询重复相… | HIT、Mila | Ruocan Wei |
| 10 | [Provably Safe Sim-to-Real Transfer](http://arxiv.org/abs/2609.01418v1) | 为了缓解现实世界强化学习（ RL ）的样本复杂性，一种常见的做法是首先在样本便宜的模拟器中训练策略，然后在现实世界中部署学习策略，希望它能有效地推广。这种直接的模拟到真实传输并不能保证成功：由于模拟到… | MIT | Tingting Ni |
| 11 | [EdiTikZ: Scientific Figure Editing from Revision Trajectorie…](http://arxiv.org/abs/2609.01409v1) | 视觉语言模型（ VLM ）在从文本或图像生成科学数字方面表现出色。然而，制作可供出版的数据需要迭代改进，这使得科学数据编辑成为一项重要但基本上尚未探索的任务。模型和数据集将被释放。 | TRI | Christian Greisinger |
| 12 | [Evaluating Multimodal LLMs as Generalist Vision-Language-Act…](http://arxiv.org/abs/2609.01404v1) | 多模态大型语言模型（ MLLM ）是图像和视频的强大感知者。我们询问延伸到表演的程度：将MLLM直接放入无人机的控制回路中，其整个动作空间仅在提示符中声明。公开的问题是以机载计算成本缩小这一差距--产… | MIT、HIT | Jaewoo Park |
| 13 | [EDGE: Error Dependency Graph-Guided Multi-Error Attribution …](http://arxiv.org/abs/2609.01360v1) | 大型语言模型（ LLM ）代理故障通常包含多个相关错误，而不是单个错误。现有的归因方法通常识别负责的代理、步骤或根本原因，但没有明确地对错误之间的依赖关系进行建模。这些结果表明，除了孤立的根本原因预测… | TRI | Jun Hou |
| 14 | [LEAP: Likelihood Elicitation and Aggregation for LLM-based P…](http://arxiv.org/abs/2609.01337v1) | 基于法学硕士的预测系统在金融市场和体育结果等现实任务上有所改进，主要是通过更强大的搜索和工具使用。许多系统仍然要求法学硕士一起阅读所有收集的证据并生成最终预测。鉴于同样的证据， LEAP改进了模型中的… | CAS、TRI | Yufei Chen |
| 15 | [Bandits in Prod: Hyperparameter Optimization at Inference Ti…](http://arxiv.org/abs/2609.01335v1) | 许多生产系统只能通过在实时请求上使用配置并观察噪音反馈来评估配置。现代智能体系统就是一个突出的例子，具有模型选择、检索深度、提示策略和解码温度等推理时间选择，但通常没有代表性的验证数据。IMABO在各… | CAS、TRI | Louis Abraham |
| 16 | [Analog-DB: An Agent-First Analog Integrated Circuit Database…](http://arxiv.org/abs/2609.01286v1) | 共享模拟集成电路设计仍然很困难：代工厂保密协议限制了设计所依赖的工艺细节，并且发布结果背后的测试台很少发布。我们展示了analog-db ，这是一个基于可共享设计表示的开源、版本化的数据库。该数据库拥… | CAS、TRI | Danial Noori Zadeh |
| 17 | [Dual Process Motion Planning](http://arxiv.org/abs/2609.01260v1) | 机器人系统深深植根于工业和日常生活中，它们有望以快速、精确和可靠的方式发挥作用。长期以来，经典的控制和规划方法提供了强有力的保证，但往往以计算效率和适应性为代价。结果表明，将学习与结构化推理紧密耦合，… | MIT、HIT | Jiayi Yan |
| 18 | [Explore More, Drift Less: Outcome-Only Reinforcement Learnin…](http://arxiv.org/abs/2609.01245v1) | 强化学习是针对仅通过任务结束验证来判断的长期交互式任务对LLM代理进行后期培训的自然方式，但一个共同的信念是，只有结果的强化学习很快就会在小型开放模型上达到上限。因此，最近的工作通过更密集的奖励、SF… | Alibaba、HIT | Liming Pu |
| 19 | [MutMem-V2: Cryptographically Authorized Mutation in Persiste…](http://arxiv.org/abs/2609.01235v1) | MutMem V1引入了永久代理内存的保留，加密授权突变，但没有提供完整的便携式验证合同或干净安装复制路径。MutMem V2在不引入第二个内存引擎的情况下缩小了发布差距。MutMem V2支持在所述… | MIT、CAS | Walid Saidi |
| 20 | [Autonomous discovery of new structure-plausibility laws for …](http://arxiv.org/abs/2609.01209v1) | 晶体发生器和工具使用剂提出的结构比密度泛函理论（ DFT ）能量更快，声子计算或实验可以评估它们。因此，决定哪些候选人值得进行昂贵的评估是瓶颈，但大多数屏幕在原子重叠之外几乎没有测试，也没有给出失败的… | TRI | Zhilong Song |

### 论文详情

<details>
<summary><b>1. Efficient SWE Agent Benchmarking via Trajectory-Aware Evaluation</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Kefeng Duan、Dewu Zheng、Yanlin Wang、Xiwen Wang、Ensheng Shi 等（共 10 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-09-01T17:59:46Z |
| **关键词** | `Benchmark` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2609.01603v1](http://arxiv.org/abs/2609.01603v1) |

**📝 摘要概括：**

> 在现实的基准上评估软件工程代理是昂贵的，因为每个任务可能需要多步代码探索、修改和测试执行。现有的有效评估方法选择代表性子集来评估完整基准性能，但主要是结果：它们符合历史通过/失败响应矩阵或静态任务语义，丢弃代理解决问题的方式。代码和数据是公开的……

</details>

<details>
<summary><b>2. CordisBench: Can Language Models Reason About Component Lifecycles in Dynamic Agent Harnesses?</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Damien Sileo、Dimitri Kachler |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-09-01T17:59:13Z |
| **关键词** | `Reasoning` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2609.01600v1](http://arxiv.org/abs/2609.01600v1) |

**📝 摘要概括：**

> 动态代理利用让语言模型改变塑造其自身执行的软件。这种灵活性带来了新的推理负担：本地插件更改可以通过依赖关系和清理进行传播。对于这些受控实例，这种成本是可以避免的：独立的有限参考语义与用于对所有528个可执行问题进行评分的每个观察和操作结果的Cordis执行一致。

</details>

<details>
<summary><b>3. Mechanism Design for Alignment and Control</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Dirk Bergemann、Andrew Koh、Stephen Morris |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT |
| **发布时间** | 2026-09-01T17:57:50Z |
| **关键词** | `AI Agent` |
| **原文链接** | [http://arxiv.org/abs/2609.01595v1](http://arxiv.org/abs/2609.01595v1) |

**📝 摘要概括：**

> 我们开发了一个与AI代理进行机制设计的框架，其一致性（偏好）和能力（可行的行动和信息）是未知的。我们希望这些代理代表我们行事，因此机制必须激励诚实和服从。我们将我们的框架应用于以下风格化的示例： （ i ）沙袋，其中更有能力的代理人假装能力较低； （ ii ）一致性-可解释性权衡，其中两者是替代品……

</details>

<details>
<summary><b>4. Retrieved but not ranked: surface-form bias in structural retrieval, from mathematics to agent trajectories</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Nabira Rashid、Manolis Kellis |
| **所属机构** | （详见原文） |
| **顶级机构标签** | HIT、Mila、TRI |
| **发布时间** | 2026-09-01T17:19:57Z |
| **关键词** | `Retrieval` · `Benchmark` · `Embodied AI` |
| **原文链接** | [http://arxiv.org/abs/2609.01556v1](http://arxiv.org/abs/2609.01556v1) |

**📝 摘要概括：**

> 我们评估了有意将表面形式和含义分开的嵌入式检索：在一个协议下的两个不相关的领域中检索共享基础结构但不具有措辞的项目，即竞争数学（ MathNet-Retrieve ； 500个查询， 117,088个项目语料库）和具体化代理轨迹（ ALFWorld派生； 118个查询， 336个轨迹）。在数学中，失败是完全的：最重伪装层的严格命中@ 1为0…

</details>

<details>
<summary><b>5. NashDreamer: Model-Based Reinforcement Learning for Zero-Sum Imperfect-Information Games</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Tomáš Holeček、Viliam Lisý |
| **所属机构** | （详见原文） |
| **顶级机构标签** | HIT |
| **发布时间** | 2026-09-01T17:15:41Z |
| **关键词** | `Multi-Agent` · `Reinforcement Learning` · `Benchmark` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2609.01549v1](http://arxiv.org/abs/2609.01549v1) |

**📝 摘要概括：**

> 基于模型的强化学习（ MBRL ）在单智能体领域取得了显着成果，但其扩展到竞争性不完善信息游戏（ IIG ）方面仍未得到充分探索。在多智能体环境中，对手诱导的非平稳性使学习过程复杂化，分散式模型学习面临严重的可识别性障碍，我们认为这使得集中式模型学习成为数学必要性。我们把它作为一个开放的……

</details>

<details>
<summary><b>6. EvoSCM: Scientific Belief Revision Through Causal Model Evolution and Experimentation</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Qing Zhao、Haowei Li、Weijian Deng、Pengxu Wei、Liang Lin |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT |
| **发布时间** | 2026-09-01T16:55:56Z |
| **关键词** | `LLM Agent` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2609.01526v1](http://arxiv.org/abs/2609.01526v1) |

**📝 摘要概括：**

> 科学代理人不仅要学会如何推理，还要学会相信什么。然而，现有的LLM代理通常以自由格式文本表达科学假设，使他们的信念隐含且难以测试或修改。EvoSCM在基线基础上不断改进科学发现，产生更准确的解释和预测，同时更有效地利用实验相互作用。

</details>

<details>
<summary><b>7. When Guardrails Look Effective: Construct Validity Failures in LLM Agent Commerce Evaluation</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Peiying Zhu、Sidi Chang |
| **所属机构** | （详见原文） |
| **顶级机构标签** | CAS、TRI |
| **发布时间** | 2026-09-01T16:48:13Z |
| **关键词** | `LLM Agent` · `RAG` · `Evaluation` · `Simulation` |
| **原文链接** | [http://arxiv.org/abs/2609.01519v1](http://arxiv.org/abs/2609.01519v1) |

**📝 摘要概括：**

> 交互式模拟越来越多地评估由语言模型代理商填充的市场中的策略。他们的产出看起来很经济--价格、利润、消费者剩余和福利--而无需实例化索赔中提到的行为。个案并未表明护栏无效；它表明在模拟药物和方案通过这些检查之前，其表观价值无法识别。

</details>

<details>
<summary><b>8. Parsing the Stream: A Live Trace Model for Long-Horizon Agents and Their Observers</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Egor Pakhomov、Erik Nijkamp |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-09-01T16:03:54Z |
| **关键词** | `RAG` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2609.01466v1](http://arxiv.org/abs/2609.01466v1) |

**📝 摘要概括：**

> 长视野代理的跟踪超出了其消费者：监视运行的人类观察者和代理本身，必须将跟踪折叠回其有界上下文。我们提出了一个实时跟踪模型，这是一个仅追加的事件分类账，逐渐折叠成类型化的运行状态，并编译成每位消费者的视图，并对照确定性的事实对两位消费者进行评估。代码、基准、可再生的合成语料库，以及所有这些……

</details>

<details>
<summary><b>9. TRIAGE: Three-level Routing and Intelligent Agent Guidance for Efficient Execution</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Ruocan Wei |
| **所属机构** | （详见原文） |
| **顶级机构标签** | HIT、Mila、TRI |
| **发布时间** | 2026-09-01T15:40:09Z |
| **关键词** | `Reasoning` · `RAG` |
| **原文链接** | [http://arxiv.org/abs/2609.01428v1](http://arxiv.org/abs/2609.01428v1) |

**📝 摘要概括：**

> 基于ReAct范式的大型语言模型（ LLM ）代理在工具使用和任务执行方面表现出非凡的能力。然而， ReAct面临着一个基本的效率问题：每个查询都会从头开始触发一个完整的推理循环，并且类似的查询重复相同的步骤而不利用历史经验。我们还提出了一种自动技能提取机制，可以提取高频轨迹模式…

</details>

<details>
<summary><b>10. Provably Safe Sim-to-Real Transfer</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Tingting Ni、Maryam Kamgarpour |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT |
| **发布时间** | 2026-09-01T15:34:57Z |
| **关键词** | `Reinforcement Learning` · `Robotics` |
| **原文链接** | [http://arxiv.org/abs/2609.01418v1](http://arxiv.org/abs/2609.01418v1) |

**📝 摘要概括：**

> 为了缓解现实世界强化学习（ RL ）的样本复杂性，一种常见的做法是首先在样本便宜的模拟器中训练策略，然后在现实世界中部署学习策略，希望它能有效地推广。这种直接的模拟到真实传输并不能保证成功：由于模拟到真实不匹配，模拟器训练的策略在现实世界中可能次优。我们真实世界的样本复杂性……

</details>

<details>
<summary><b>11. EdiTikZ: Scientific Figure Editing from Revision Trajectories</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Christian Greisinger、Zhixue Zhao、Steffen Eger |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-09-01T15:29:52Z |
| **关键词** | `Agentic` · `Reinforcement Learning` · `RAG` · `Benchmark` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2609.01409v1](http://arxiv.org/abs/2609.01409v1) |

**📝 摘要概括：**

> 视觉语言模型（ VLM ）在从文本或图像生成科学数字方面表现出色。然而，制作可供出版的数据需要迭代改进，这使得科学数据编辑成为一项重要但基本上尚未探索的任务。模型和数据集将被释放。

</details>

<details>
<summary><b>12. Evaluating Multimodal LLMs as Generalist Vision-Language-Action Agents for Drone Control: Commanding, Approaching, Tracking and Searching</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Jaewoo Park、Minyoung Lee、Sukmin Seo、Moonbin Yim、Hyunwook Yoon 等（共 14 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、HIT |
| **发布时间** | 2026-09-01T15:27:43Z |
| **关键词** | `Benchmark` · `Fine-tuning` · `Embodied AI` |
| **原文链接** | [http://arxiv.org/abs/2609.01404v1](http://arxiv.org/abs/2609.01404v1) |

**📝 摘要概括：**

> 多模态大型语言模型（ MLLM ）是图像和视频的强大感知者。我们询问延伸到表演的程度：将MLLM直接放入无人机的控制回路中，其整个动作空间仅在提示符中声明。公开的问题是以机载计算成本缩小这一差距--产生一个持续计划并准确知道何时完成的快速模型--而DroneCATS就是为了测量这一距离而构建的。

</details>

<details>
<summary><b>13. EDGE: Error Dependency Graph-Guided Multi-Error Attribution in Multi-Agent LLM Systems</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Jun Hou、Priya Pitre、Yi Fang、Xuan Wang |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-09-01T15:00:54Z |
| **关键词** | `Multi-Agent` |
| **原文链接** | [http://arxiv.org/abs/2609.01360v1](http://arxiv.org/abs/2609.01360v1) |

**📝 摘要概括：**

> 大型语言模型（ LLM ）代理故障通常包含多个相关错误，而不是单个错误。现有的归因方法通常识别负责的代理、步骤或根本原因，但没有明确地对错误之间的依赖关系进行建模。这些结果表明，除了孤立的根本原因预测之外，依赖关系结构对于代理故障是一种有用的先验诊断。

</details>

<details>
<summary><b>14. LEAP: Likelihood Elicitation and Aggregation for LLM-based Probabilistic Forecasting</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Yufei Chen、Yiran Zhao、Xiaogang Xu、Qipeng Xie、Jiafei Wu 等（共 6 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | CAS、TRI |
| **发布时间** | 2026-09-01T14:49:19Z |
| **关键词** | `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2609.01337v1](http://arxiv.org/abs/2609.01337v1) |

**📝 摘要概括：**

> 基于法学硕士的预测系统在金融市场和体育结果等现实任务上有所改进，主要是通过更强大的搜索和工具使用。许多系统仍然要求法学硕士一起阅读所有收集的证据并生成最终预测。鉴于同样的证据， LEAP改进了模型中的大多数预测和校准指标，并且在先前访问、推断预算和聚合的受控比较下仍然更强大……

</details>

<details>
<summary><b>15. Bandits in Prod: Hyperparameter Optimization at Inference Time</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Louis Abraham、Tuan-Anh Nguyen、Nicolas Devatine |
| **所属机构** | （详见原文） |
| **顶级机构标签** | CAS、TRI |
| **发布时间** | 2026-09-01T14:48:08Z |
| **关键词** | `Agentic` · `Retrieval` |
| **原文链接** | [http://arxiv.org/abs/2609.01335v1](http://arxiv.org/abs/2609.01335v1) |

**📝 摘要概括：**

> 许多生产系统只能通过在实时请求上使用配置并观察噪音反馈来评估配置。现代智能体系统就是一个突出的例子，具有模型选择、检索深度、提示策略和解码温度等推理时间选择，但通常没有代表性的验证数据。IMABO在各种OHPO设置中获得最低的累积遗憾，从调整经典机器学习模型到……

</details>

<details>
<summary><b>16. Analog-DB: An Agent-First Analog Integrated Circuit Database, From Blocks to Systems</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Danial Noori Zadeh、Mohamed B. Elamien |
| **所属机构** | （详见原文） |
| **顶级机构标签** | CAS、TRI |
| **发布时间** | 2026-09-01T14:22:37Z |
| **关键词** | — |
| **原文链接** | [http://arxiv.org/abs/2609.01286v1](http://arxiv.org/abs/2609.01286v1) |

**📝 摘要概括：**

> 共享模拟集成电路设计仍然很困难：代工厂保密协议限制了设计所依赖的工艺细节，并且发布结果背后的测试台很少发布。我们展示了analog-db ，这是一个基于可共享设计表示的开源、版本化的数据库。该数据库拥有16个类别的68个电路，可在原理图级别上通过分层线束进行验证，并在电源/性能上进行跟踪……

</details>

<details>
<summary><b>17. Dual Process Motion Planning</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Jiayi Yan、Francesco Fabiano、Alessandro Abate |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、HIT、NTU |
| **发布时间** | 2026-09-01T13:52:12Z |
| **关键词** | `Reasoning` · `Planning` · `RAG` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2609.01260v1](http://arxiv.org/abs/2609.01260v1) |

**📝 摘要概括：**

> 机器人系统深深植根于工业和日常生活中，它们有望以快速、精确和可靠的方式发挥作用。长期以来，经典的控制和规划方法提供了强有力的保证，但往往以计算效率和适应性为代价。结果表明，将学习与结构化推理紧密耦合，为更强大和自适应的机器人系统提供了一条可扩展的路径。

</details>

<details>
<summary><b>18. Explore More, Drift Less: Outcome-Only Reinforcement Learning Can Suffice for Long-Horizon Interactive Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Liming Pu、Xiaoxia Li、Yifu Liu、Teng Cao、Bin Yang |
| **所属机构** | （详见原文） |
| **顶级机构标签** | Alibaba、HIT、CAS |
| **发布时间** | 2026-09-01T13:44:40Z |
| **关键词** | `Multi-Agent` · `LLM Agent` · `Agentic` · `Reinforcement Learning` · `RAG` |
| **原文链接** | [http://arxiv.org/abs/2609.01245v1](http://arxiv.org/abs/2609.01245v1) |

**📝 摘要概括：**

> 强化学习是针对仅通过任务结束验证来判断的长期交互式任务对LLM代理进行后期培训的自然方式，但一个共同的信念是，只有结果的强化学习很快就会在小型开放模型上达到上限。因此，最近的工作通过更密集的奖励、SFT先验、技能库、精心策划的记忆或多代理编排来补偿培训。仅Agentic RL就直接在……中内化了长视野能力

</details>

<details>
<summary><b>19. MutMem-V2: Cryptographically Authorized Mutation in Persistent Agent Memory Portable Verification and Reproducible Evidence</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Walid Saidi |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、CAS |
| **发布时间** | 2026-09-01T13:34:44Z |
| **关键词** | `Memory` |
| **原文链接** | [http://arxiv.org/abs/2609.01235v1](http://arxiv.org/abs/2609.01235v1) |

**📝 摘要概括：**

> MutMem V1引入了永久代理内存的保留，加密授权突变，但没有提供完整的便携式验证合同或干净安装复制路径。MutMem V2在不引入第二个内存引擎的情况下缩小了发布差距。MutMem V2支持在所述假设下关于便携式完整性、授权、可追溯性、一致性和可重现性的主张；它不建立……

</details>

<details>
<summary><b>20. Autonomous discovery of new structure-plausibility laws for explainable and rapid crystal diagnosis and screening</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Zhilong Song、Lixue Cheng |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-09-01T13:14:52Z |
| **关键词** | — |
| **原文链接** | [http://arxiv.org/abs/2609.01209v1](http://arxiv.org/abs/2609.01209v1) |

**📝 摘要概括：**

> 晶体发生器和工具使用剂提出的结构比密度泛函理论（ DFT ）能量更快，声子计算或实验可以评估它们。因此，决定哪些候选人值得进行昂贵的评估是瓶颈，但大多数屏幕在原子重叠之外几乎没有测试，也没有给出失败的化学原因。PRIS将筛选从通过或失败的判决转移到失败的化学原因，表明自主AG...

</details>

## 🗄️ 历史归档

| 日期 | 论文数 | 报告链接 |
|------|--------|----------|
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
| 2026-08-01 | 0 篇 | [2026-08-01.md](daily/2026-08-01.md) |

## 🏛️ 顶级机构覆盖范围

覆盖超过 **70 个**顶级 AI 机构，包括：

- **科技公司：** Microsoft、Google DeepMind、OpenAI、Anthropic、Meta AI、NVIDIA、Baidu、Alibaba、ByteDance 等
- **北美顶级大学：** MIT、Stanford、CMU、UC Berkeley、Harvard、Princeton、Cornell、Caltech 等
- **中国顶级大学/机构：** 清华大学、北京大学、浙大、上交大、复旦、中科院、MSRA 等
- **欧洲/其他：** Oxford、Cambridge、ETH Zurich、Mila、NUS、KAIST 等

---

*由 [clawBot DailyFindings](https://github.com/Jacob-biu/clawBot) 自动维护 | 最后更新：2026-09-02 23:52 UTC*
