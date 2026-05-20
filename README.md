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

## 📅 今日论文 — 2026-05-20　　[→ 查看完整报告](daily/2026-05-20.md)

> 共筛选出 **16** 篇论文 | 更新于 2026-05-20 23:12 UTC

### 论文目录与概要

| # | 论文标题 | 核心概要 | 来源机构 | 第一作者 |
|---|---------|---------|---------|--------|
| 1 | [A Methodology for Selecting and Composing Runtime Architectu…](http://arxiv.org/abs/2605.20173v1) | 生产LLM代理将随机模型输出与确定性软件系统相结合，但两者之间的边界很少被视为一流的架构对象。本文将该边界命名为随机确定性边界（ SDB ） ：提议者、验证者、提交步骤和拒绝信号之间的四部分合约，指定… | MIT、HIT | Vasundra Srinivasan |
| 2 | [CopT: Contrastive On-Policy Thinking with Continuous Spaces …](http://arxiv.org/abs/2605.20075v1) | 思维链（ CoT ）是从大型语言模型（ LLM ）中引出推理能力的标准方法。然而，常见的CoT范式将思维视为回答的先决条件，即使模型能够在扩展思维之前识别出答案，也会延迟获得合理的答案并产生不必要的代… | MIT、CAS | Dachuan Shi |
| 3 | [Probing Embodied LLMs: When Higher Observation Fidelity Hurt…](http://arxiv.org/abs/2605.20072v1) | 大型语言模型越来越多地被提出作为机器人系统的认知组件，但其不透明的决策过程使得在闭环具体任务中难以解释成功或失败。遵循经验人工智能方法，我们通过改变代理可用的信息并测量由此产生的行为变化来研究行为上体… | NTU | Oussama Zenkri |
| 4 | [Towards LLM-Assisted Architecture Recovery for Real-World RO…](http://arxiv.org/abs/2605.20055v1) | 显式软件架构模型是通信、分析和发展复杂软件密集型系统的重要工具。然而，在基于ROS ~ 2的机器人系统中，结构（去）组合和集成语义通常仅在源代码和启动文件等分布式工件之间隐式编码，这使得层次结构的恢复… | MIT、HIT | Dominique Briechle |
| 5 | [When Critics Disagree: Adaptive Reward Poisoning Attacks in …](http://arxiv.org/abs/2605.20037v1) | 奖励中毒攻击为基于学习的无线控制系统带来了重大风险。鉴于此，我们建议对软行动者-批评者（ SAC ）代理进行分歧引导奖励中毒（ DGRP ）自适应攻击。与定期定时和勘探触发的基线相比， DGRP持续造… | MIT、TRI | Deemah H. Tashman |
| 6 | [When Skills Don't Help: A Negative Result on Procedural Know…](http://arxiv.org/abs/2605.20023v1) | 代理技能，即在推断时加载到LLM代理中的程序知识的结构化包，被广泛报道可以将不同领域的任务通过率平均提高16.2~个百分点。然而，同样的基准显示出很大的差异，在引入技能时， 84项任务中有16项遭受负… | MIT、CAS | Samuel Jacob Chacko |
| 7 | [A Case for Agentic Tuning: From Documentation to Action in P…](http://arxiv.org/abs/2605.19988v1) | 长期以来，文档通过将专业知识提炼成每个参数的建议来指导计算机系统的调整。然而，这些指南只捕捉到专家的结论，而忽略了他们的推理方式。该工具可在https://github.com/ISCAS-OSLab… | CAS | Hongyu Lin |
| 8 | [PEEK: Context Map as an Orientation Cache for Long-Context L…](http://arxiv.org/abs/2605.19932v1) | 大型语言模型（ LLM ）代理越来越多地在漫长而反复出现的外部环境中运行，例如文档语料库和代码存储库。在整个调用过程中，现有方法保留了agent的轨迹、对原材料的被动访问或任务级策略。总之，这些结果表… | OpenAI、HIT | Zhuohan Gu |
| 9 | [A Closed-loop, State-centric, Multi-agent Framework for Pass…](http://arxiv.org/abs/2605.19834v1) | 为了支持运营和面向乘客的服务，运输机构需要可靠的乘客负荷轨迹。目前，负荷估计通常是从不完美的传感系统推断出来的，而不是完全被观察到的，现代自动乘客计数（ APC ）系统的准确性仍然因车站布局、流量强度… | HIT、TRI | Yiyao Xu |
| 10 | [From Prompts to Pavement Through Time: Temporal Grounding in…](http://arxiv.org/abs/2605.19824v1) | 最近使用大型语言模型（ LLM ）和大型多模态模型（ LMM ）集成支持自动驾驶汽车（ AV ）的高级场景解释和规划的尝试继续将时间视为次要属性。缺乏时间基础导致对持续行动的推理不一致，破坏了安全性和… | MIT、HIT | Ahmed Y. Gado |
| 11 | [Distribution-Free Uncertainty Quantification for Continuous …](http://arxiv.org/abs/2605.19779v1) | 我们将分裂共形预测和自适应共形推理（ ACI ）应用于连续AI代理评估，为预测质量分数提供无分布覆盖保证。在24小时内，适形间隔在所有标称水平上实现低于0.02的校准误差，而ACI在药物释放后将间隔正… | CAS、TRI | Yuxuan Gao |
| 12 | [Synthesis and Evaluation of Long-term History-aware Medical …](http://arxiv.org/abs/2605.19766v1) | 有效的医疗保健代理人必须能够回忆和推理患者的纵向病史。然而，缺乏具有现实的长期对话时间表的数据集限制了系统评估。这些研究结果强调了基准的适用性，并强调需要量身定制的方法来推进医疗保健代理商。 | MIT、TRI | Hebin Hu |
| 13 | [Memory-Augmented Reinforcement Learning Agent for CAD Genera…](http://arxiv.org/abs/2605.19748v1) | 自动生成计算机辅助设计（ CAD ）模型是在先进制造业中实现智能的核心技术。现有的基于大型语言模型（ LLMs ）的生成方法在处理复杂的CAD模型时往往存在不足，这些CAD模型的特点是操作序列长、操作… | CAS、Mila | Yin Xiaolong |
| 14 | [EngiAI: A Multi-Agent Framework and Benchmark Suite for LLM-…](http://arxiv.org/abs/2605.19743v1) | 大型语言模型（ LLM ）代理越来越多地应用于工程设计任务，但现有的评估框架无法充分解决结合模拟、检索和制造准备的多代理系统。我们引入了一个具有三个评估维度的基准套件： （ 1 ）具有七种针对不同认知… | HIT、TRI | Gioele Molinari |
| 15 | [Measuring Safety Alignment Effects in Autonomous Security Ag…](http://arxiv.org/abs/2605.19722v1) | 当作为自主安全代理运行时，与股票安全一致的语言模型及其未经审查或被删除的衍生物的行为是否不同？一次性拒绝基准无法回答这个问题：安全代理必须检查存储库，调用工具，并在授权的沙箱中生成漏洞证据。这些结果表… | TRI | Isaac David |
| 16 | [Projecting Latent RL Actions: Towards Generalizable and Scal…](http://arxiv.org/abs/2605.19721v1) | 图组合优化（ GCO ）引起了越来越多的兴趣，因为许多NP难问题自然承认图公式，但它们的组合爆炸使精确方法在计算上变得棘手。强化学习（ RL ）与图神经网络（ GNN ）相结合的最新进展显著改善了基于… | INRIA | Franco Terranova |

### 论文详情

<details>
<summary><b>1. A Methodology for Selecting and Composing Runtime Architecture Patterns for Production LLM Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Vasundra Srinivasan |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、HIT、NTU |
| **发布时间** | 2026-05-19T17:54:21Z |
| **关键词** | `LLM Agent` |
| **原文链接** | [http://arxiv.org/abs/2605.20173v1](http://arxiv.org/abs/2605.20173v1) |

**📝 摘要概括：**

> 生产LLM代理将随机模型输出与确定性软件系统相结合，但两者之间的边界很少被视为一流的架构对象。本文将该边界命名为随机确定性边界（ SDB ） ：提议者、验证者、提交步骤和拒绝信号之间的四部分合约，指定LLM输出如何成为系统动作。我们将该方法应用于五个工作负载，并提供……

</details>

<details>
<summary><b>2. CopT: Contrastive On-Policy Thinking with Continuous Spaces for General and Agentic Reasoning</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Dachuan Shi、Hanlin Zhu、Xiangchi Yuan、Wanjia Zhao、Kejing Xia 等（共 7 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、CAS |
| **发布时间** | 2026-05-19T16:28:53Z |
| **关键词** | `Agentic` · `Reasoning` · `Chain-of-Thought` |
| **原文链接** | [http://arxiv.org/abs/2605.20075v1](http://arxiv.org/abs/2605.20075v1) |

**📝 摘要概括：**

> 思维链（ CoT ）是从大型语言模型（ LLM ）中引出推理能力的标准方法。然而，常见的CoT范式将思维视为回答的先决条件，即使模型能够在扩展思维之前识别出答案，也会延迟获得合理的答案并产生不必要的代币成本，这种行为称为执行推理。该代码可在https://github.com/sdc17/Co上获得……

</details>

<details>
<summary><b>3. Probing Embodied LLMs: When Higher Observation Fidelity Hurts Problem Solving</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Oussama Zenkri、Oliver Brock |
| **所属机构** | （详见原文） |
| **顶级机构标签** | NTU |
| **发布时间** | 2026-05-19T16:27:00Z |
| **关键词** | `LLM Agent` · `Reasoning` · `Simulation` · `Embodied AI` |
| **原文链接** | [http://arxiv.org/abs/2605.20072v1](http://arxiv.org/abs/2605.20072v1) |

**📝 摘要概括：**

> 大型语言模型越来越多地被提出作为机器人系统的认知组件，但其不透明的决策过程使得在闭环具体任务中难以解释成功或失败。遵循经验人工智能方法，我们通过改变代理可用的信息并测量由此产生的行为变化来研究行为上体现的LLM代理。这些发现表明，仅有成功率是不够的……

</details>

<details>
<summary><b>4. Towards LLM-Assisted Architecture Recovery for Real-World ROS~2 Systems: An Agent-Based Multi-Level Approach to Hierarchical Structural Architecture Reconstruction</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Dominique Briechle、Raj Chanchad、Tobias Geger、Ruidi He、Dhruv Jajadiya 等（共 8 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、HIT、CAS |
| **发布时间** | 2026-05-19T16:14:33Z |
| **关键词** | — |
| **原文链接** | [http://arxiv.org/abs/2605.20055v1](http://arxiv.org/abs/2605.20055v1) |

**📝 摘要概括：**

> 显式软件架构模型是通信、分析和发展复杂软件密集型系统的重要工具。然而，在基于ROS ~ 2的机器人系统中，结构（去）组合和集成语义通常仅在源代码和启动文件等分布式工件之间隐式编码，这使得层次结构的恢复特别困难。结果表明，改进的结构…

</details>

<details>
<summary><b>5. When Critics Disagree: Adaptive Reward Poisoning Attacks in RIS-Aided Wireless Control System</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Deemah H. Tashman、Soumaya Cherkaoui |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-05-19T15:59:43Z |
| **关键词** | `Reinforcement Learning` · `RAG` |
| **原文链接** | [http://arxiv.org/abs/2605.20037v1](http://arxiv.org/abs/2605.20037v1) |

**📝 摘要概括：**

> 奖励中毒攻击为基于学习的无线控制系统带来了重大风险。鉴于此，我们建议对软行动者-批评者（ SAC ）代理进行分歧引导奖励中毒（ DGRP ）自适应攻击。与定期定时和勘探触发的基线相比， DGRP持续造成更大的损害，突出了在评估深度加固的鲁棒性时考虑分歧意识威胁的必要性……

</details>

<details>
<summary><b>6. When Skills Don't Help: A Negative Result on Procedural Knowledge for Tool-Grounded Agents in Offensive Cybersecurity</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Samuel Jacob Chacko、James Hugglestone、Chashi Mahiul Islam、Xiuwen Liu |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、CAS、TRI |
| **发布时间** | 2026-05-19T15:48:35Z |
| **关键词** | `LLM Agent` · `RAG` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2605.20023v1](http://arxiv.org/abs/2605.20023v1) |

**📝 摘要概括：**

> 代理技能，即在推断时加载到LLM代理中的程序知识的结构化包，被广泛报道可以将不同领域的任务通过率平均提高16.2~个百分点。然而，同样的基准显示出很大的差异，在引入技能时， 84项任务中有16项遭受负增量。我们阐述了一个可证伪的假设，概述了它对复合人工智能系统的设计影响，并将发布……

</details>

<details>
<summary><b>7. A Case for Agentic Tuning: From Documentation to Action in PostgreSQL</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Hongyu Lin、Mingyu Li、Weichen Zhang、Yihang Lou、Mingjie Xing 等（共 7 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | CAS |
| **发布时间** | 2026-05-19T15:26:28Z |
| **关键词** | `Agentic` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2605.19988v1](http://arxiv.org/abs/2605.19988v1) |

**📝 摘要概括：**

> 长期以来，文档通过将专业知识提炼成每个参数的建议来指导计算机系统的调整。然而，这些指南只捕捉到专家的结论，而忽略了他们的推理方式。该工具可在https://github.com/ISCAS-OSLab/PerfEvolve上找到。

</details>

<details>
<summary><b>8. PEEK: Context Map as an Orientation Cache for Long-Context LLM Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Zhuohan Gu、Qizheng Zhang、Omar Khattab、Samuel Madden |
| **所属机构** | （详见原文） |
| **顶级机构标签** | OpenAI、HIT |
| **发布时间** | 2026-05-19T14:51:32Z |
| **关键词** | `LLM Agent` · `Reasoning` |
| **原文链接** | [http://arxiv.org/abs/2605.19932v1](http://arxiv.org/abs/2605.19932v1) |

**📝 摘要概括：**

> 大型语言模型（ LLM ）代理越来越多地在漫长而反复出现的外部环境中运行，例如文档语料库和代码存储库。在整个调用过程中，现有方法保留了agent的轨迹、对原材料的被动访问或任务级策略。总之，这些结果表明，上下文映射有助于长上下文LLM代理更准确有效地与反复出现的外部上下文进行交互。

</details>

<details>
<summary><b>9. A Closed-loop, State-centric, Multi-agent Framework for Passenger Load Estimation from Heterogeneous Data Streams</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Yiyao Xu、Hao Zhou、Yuhang Wang、Jingran Sun |
| **所属机构** | （详见原文） |
| **顶级机构标签** | HIT、TRI |
| **发布时间** | 2026-05-19T13:26:59Z |
| **关键词** | `Multi-Agent` |
| **原文链接** | [http://arxiv.org/abs/2605.19834v1](http://arxiv.org/abs/2605.19834v1) |

**📝 摘要概括：**

> 为了支持运营和面向乘客的服务，运输机构需要可靠的乘客负荷轨迹。目前，负荷估计通常是从不完美的传感系统推断出来的，而不是完全被观察到的，现代自动乘客计数（ APC ）系统的准确性仍然因车站布局、流量强度和运行条件而异。该架构由一个统一的停止事件主干、一个耦合的感知--P…

</details>

<details>
<summary><b>10. From Prompts to Pavement Through Time: Temporal Grounding in Agentic Scene-to-Plan Reasoning</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Ahmed Y. Gado、Omar Y. Goba、Alaa Hassanein、Catherine M. Elias、Ahmed Hussein |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、HIT、TRI |
| **发布时间** | 2026-05-19T13:18:35Z |
| **关键词** | `Agentic` · `Reasoning` · `Planning` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2605.19824v1](http://arxiv.org/abs/2605.19824v1) |

**📝 摘要概括：**

> 最近使用大型语言模型（ LLM ）和大型多模态模型（ LMM ）集成支持自动驾驶汽车（ AV ）的高级场景解释和规划的尝试继续将时间视为次要属性。缺乏时间基础导致对持续行动的推理不一致，破坏了安全性和可解释性。这些发现澄清了基于提示的时间接地和EST的局限性……

</details>

<details>
<summary><b>11. Distribution-Free Uncertainty Quantification for Continuous AI Agent Evaluation</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Yuxuan Gao、Megan Wang、Yi Ling Yu |
| **所属机构** | （详见原文） |
| **顶级机构标签** | CAS、TRI |
| **发布时间** | 2026-05-19T12:47:21Z |
| **关键词** | `Multi-Agent` · `AI Agent` · `RAG` · `Benchmark` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2605.19779v1](http://arxiv.org/abs/2605.19779v1) |

**📝 摘要概括：**

> 我们将分裂共形预测和自适应共形推理（ ACI ）应用于连续AI代理评估，为预测质量分数提供无分布覆盖保证。在24小时内，适形间隔在所有标称水平上实现低于0.02的校准误差，而ACI在药物释放后将间隔正确地扩大了35% ，然后再收敛。代码和数据根据CC BY 4.0发布。

</details>

<details>
<summary><b>12. Synthesis and Evaluation of Long-term History-aware Medical Dialogue</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Hebin Hu、Renke Dai、Ah-Hwee Tan、Yilin Kang |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-05-19T12:38:41Z |
| **关键词** | `Reasoning` · `Benchmark` · `Evaluation` · `Memory` |
| **原文链接** | [http://arxiv.org/abs/2605.19766v1](http://arxiv.org/abs/2605.19766v1) |

**📝 摘要概括：**

> 有效的医疗保健代理人必须能够回忆和推理患者的纵向病史。然而，缺乏具有现实的长期对话时间表的数据集限制了系统评估。这些研究结果强调了基准的适用性，并强调需要量身定制的方法来推进医疗保健代理商。

</details>

<details>
<summary><b>13. Memory-Augmented Reinforcement Learning Agent for CAD Generation</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Yin Xiaolong、Liu Yu、Shen Jiahang、Lu Xingyu、Ni Jingzhe 等（共 7 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | CAS、Mila、TRI |
| **发布时间** | 2026-05-19T12:16:31Z |
| **关键词** | `Reasoning` · `Planning` · `Reinforcement Learning` · `Retrieval` · `Memory` |
| **原文链接** | [http://arxiv.org/abs/2605.19748v1](http://arxiv.org/abs/2605.19748v1) |

**📝 摘要概括：**

> 自动生成计算机辅助设计（ CAD ）模型是在先进制造业中实现智能的核心技术。现有的基于大型语言模型（ LLMs ）的生成方法在处理复杂的CAD模型时往往存在不足，这些CAD模型的特点是操作序列长、操作类型多样、几何约束强，这主要是因为缺乏推理链断裂和有效的纠错机制。

</details>

<details>
<summary><b>14. EngiAI: A Multi-Agent Framework and Benchmark Suite for LLM-Driven Engineering Design</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Gioele Molinari、Florian Felten、Soheyl Massoudi、Mark Fuge |
| **所属机构** | （详见原文） |
| **顶级机构标签** | HIT、TRI |
| **发布时间** | 2026-05-19T12:12:09Z |
| **关键词** | `Multi-Agent` · `RAG` · `Retrieval` · `Benchmark` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2605.19743v1](http://arxiv.org/abs/2605.19743v1) |

**📝 摘要概括：**

> 大型语言模型（ LLM ）代理越来越多地应用于工程设计任务，但现有的评估框架无法充分解决结合模拟、检索和制造准备的多代理系统。我们引入了一个具有三个评估维度的基准套件： （ 1 ）具有七种针对不同认知需求的提示样式的工作流程基准-包括直接使用工具，语义消歧义，条件...

</details>

<details>
<summary><b>15. Measuring Safety Alignment Effects in Autonomous Security Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Isaac David、Arthur Gervais |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-05-19T11:55:54Z |
| **关键词** | `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2605.19722v1](http://arxiv.org/abs/2605.19722v1) |

**📝 摘要概括：**

> 当作为自主安全代理运行时，与股票安全一致的语言模型及其未经审查或被删除的衍生物的行为是否不同？一次性拒绝基准无法回答这个问题：安全代理必须检查存储库，调用工具，并在授权的沙箱中生成漏洞证据。这些结果表明，自主安全代理的安全对齐效果应该在系统层面上进行测量，分...

</details>

<details>
<summary><b>16. Projecting Latent RL Actions: Towards Generalizable and Scalable Graph Combinatorial Optimization</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Franco Terranova、Guillermo Bernardez、Albert Cabellos-Aparicio、Nina Miolane、Abdelkader Lahmadi |
| **所属机构** | UL, LORIA, Inria；UC Santa Barbara；UPC |
| **顶级机构标签** | INRIA |
| **发布时间** | 2026-05-19T11:55:44Z |
| **关键词** | `Reinforcement Learning` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2605.19721v1](http://arxiv.org/abs/2605.19721v1) |

**📝 摘要概括：**

> 图组合优化（ GCO ）引起了越来越多的兴趣，因为许多NP难问题自然承认图公式，但它们的组合爆炸使精确方法在计算上变得棘手。强化学习（ RL ）与图神经网络（ GNN ）相结合的最新进展显著改善了基于学习的GCO求解器。最后，我们发布了LaGCO-RL ，这是一个自动化潜在动作空间常量的Python库……

</details>

## 🗄️ 历史归档

| 日期 | 论文数 | 报告链接 |
|------|--------|----------|
| 2026-05-20 | 16 篇 | [2026-05-20.md](daily/2026-05-20.md) |
| 2026-05-19 | 0 篇 | [2026-05-19.md](daily/2026-05-19.md) |
| 2026-05-17 | 0 篇 | [2026-05-17.md](daily/2026-05-17.md) |
| 2026-05-16 | 0 篇 | [2026-05-16.md](daily/2026-05-16.md) |
| 2026-05-15 | 20 篇 | [2026-05-15.md](daily/2026-05-15.md) |
| 2026-05-14 | 19 篇 | [2026-05-14.md](daily/2026-05-14.md) |
| 2026-05-13 | 20 篇 | [2026-05-13.md](daily/2026-05-13.md) |
| 2026-05-12 | 20 篇 | [2026-05-12.md](daily/2026-05-12.md) |
| 2026-05-11 | 0 篇 | [2026-05-11.md](daily/2026-05-11.md) |
| 2026-05-10 | 0 篇 | [2026-05-10.md](daily/2026-05-10.md) |
| 2026-05-09 | 0 篇 | [2026-05-09.md](daily/2026-05-09.md) |
| 2026-05-08 | 0 篇 | [2026-05-08.md](daily/2026-05-08.md) |
| 2026-05-07 | 13 篇 | [2026-05-07.md](daily/2026-05-07.md) |
| 2026-05-06 | 19 篇 | [2026-05-06.md](daily/2026-05-06.md) |
| 2026-05-05 | 20 篇 | [2026-05-05.md](daily/2026-05-05.md) |

## 🏛️ 顶级机构覆盖范围

覆盖超过 **70 个**顶级 AI 机构，包括：

- **科技公司：** Microsoft、Google DeepMind、OpenAI、Anthropic、Meta AI、NVIDIA、Baidu、Alibaba、ByteDance 等
- **北美顶级大学：** MIT、Stanford、CMU、UC Berkeley、Harvard、Princeton、Cornell、Caltech 等
- **中国顶级大学/机构：** 清华大学、北京大学、浙大、上交大、复旦、中科院、MSRA 等
- **欧洲/其他：** Oxford、Cambridge、ETH Zurich、Mila、NUS、KAIST 等

---

*由 [clawBot DailyFindings](https://github.com/Jacob-biu/clawBot) 自动维护 | 最后更新：2026-05-20 23:12 UTC*
