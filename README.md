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

## 📅 今日论文 — 2026-06-11　　[→ 查看完整报告](daily/2026-06-11.md)

> 共筛选出 **19** 篇论文 | 更新于 2026-06-11 23:22 UTC

### 论文目录与概要

| # | 论文标题 | 核心概要 | 来源机构 | 第一作者 |
|---|---------|---------|---------|--------|
| 1 | [Context-Driven Incremental Compression for Multi-Turn Dialog…](http://arxiv.org/abs/2606.12411v1) | 现代对话代理在每个转折点都依赖于不断增长的对话历史记录，这会产生多余的注意力和编码成本，这些成本会随着对话时间的长短而增加。朴素的截断或摘要会降低保真度，而现有的上下文压缩器缺乏交叉转换内存共享或修订… | TRI | Yeongseo Jung |
| 2 | [DIRECT: When and Where Should You Allocate Test-Time Compute…](http://arxiv.org/abs/2606.12402v1) | 视觉语言模型（ VLM ）越来越多地被部署为具体代理的高级规划器，其新兴策略是扩展测试时间计算以提高能力。然而，我们观察到，这样做会增加延迟、令牌使用率和FLOP ，同时产生不均匀，通常会减少下游成功… | MIT | Jadelynn Dao |
| 3 | [TAHOE: Text-to-SQL with Automated Hint Optimization from Exp…](http://arxiv.org/abs/2606.12387v1) | 大型语言模型（ LLM ）通过Text-to-SQL实现了数据库访问的民主化，但从原型到生产仍然很困难。真正的部署必须处理严格的SQL方言、大规模模式和不断变化的用户偏好，而受监督的微调成本高昂且严格… | TRI | Zhiyi Chen |
| 4 | [ATLAS: Active Theory Learning for Automated Science](http://arxiv.org/abs/2606.12386v1) | 通过机械建模推进科学理解需要提出正确的实验问题，以产生最大限度的信息数据。为了在认知科学中实现这一追求的自动化，我们引入了ATLAS （自动化科学的主动理论学习） ，这是一种用于数据驱动的可解释行为模… | CAS、Mila | Noémi Éltető |
| 5 | [APPO: Agentic Procedural Policy Optimization](http://arxiv.org/abs/2606.12384v1) | 代理强化学习（ RL ）的最新进展大大提高了大型语言模型代理的多圈工具使用能力。然而，大多数现有方法都将功劳分配给粗略的启发式单元，例如工具调用边界或固定工作流程，因此很难确定哪些中间决策会影响下游结… | TRI | Xucong Wang |
| 6 | [UniIntervene: Agentic Intervention for Efficient Real-World …](http://arxiv.org/abs/2606.12372v1) | 人类在环强化学习（ HiL-RL ）已成为现实世界机器人操纵的有效范例，在人类指导下实现在线政策改进。然而，目前的HiL-RL框架仍然是干预密集型的，依靠频繁的人工纠正来将政策从非生产性探索中重定向，… | MIT、TRI | Haoyuan Deng |
| 7 | [Breaking Entropy Bounds: Accelerating RL Training via MTP wi…](http://arxiv.org/abs/2606.12370v1) | 强化学习（ RL ）已成为现代大型语言模型的关键组成部分，但推出阶段仍然是RL培训管道的关键瓶颈。尽管多令牌预测（ MTP ）提供了一种通过投机解码加速推出的自然解决方案，但许多研究发现， MTP接受… | MIT | Yucheng Li |
| 8 | [Claw-SWE-Bench: A Benchmark for Evaluating OpenClaw-style Ag…](http://arxiv.org/abs/2606.12344v1) | OpenClaw等通用代理越来越多地被用作自主工具用户，但它们的编码能力在SWE-bench下难以衡量：通用代理本身并不满足评分所需的干净的Docker工作空间、补丁和预测合约。我们推出了Claw-S… | FAIR、MIT | Mengyu Zheng |
| 9 | [Fourier Features Let Agents Learn High Precision Policies wi…](http://arxiv.org/abs/2606.12334v1) | 高精度机器人操作需要精细的空间推理，由于深度模糊和透视尺度问题，仅使用RGB策略通常很难实现。直接利用3D信息的策略（例如基于点云的策略）提供了比纯粹基于图像的策略更强的几何优先级，但其性能仍然高度依… | MIT、HIT | Balázs Gyenes |
| 10 | [A Five-Plane Reference Architecture for Runtime Governance o…](http://arxiv.org/abs/2606.12320v1) | 企业安全旨在管理数据边界：受保护的表面是静态和传输中的数据，而控制（访问控制、数据丢失预防、周边检查）则管理该边界的跨越。生产AI代理打破了这一假设。我们明确规定了范围：架构管理委派的操作，而不是模型… | MIT、HIT | Krti Tallam |
| 11 | [CCKS: Consensus-based Communication and Knowledge Sharing](http://arxiv.org/abs/2606.12281v1) | 在合作多智能体强化学习（ MARL ）的去中心化培训和去中心化执行（ DTDE ）中，基于行动建议的知识共享促进了智能体之间可解释和可扩展的合作。然而，目前的行动建议方法往往过多地遵循教师的指导，而没… | Google Research、Google | Jinyuan Zu |
| 12 | [Intelligent Automation for Embodied Benchmark Construction: …](http://arxiv.org/abs/2606.12207v1) | 具体的智能现在涵盖导航、家庭辅助、操纵、自动驾驶、空中代理和多模式大型模型控制。这种扩张使基准建设成为可靠评估的核心瓶颈。因此，具体评估的进展不仅取决于更大的基准套件，还取决于可诊断、可审计和可负责任… | TRI | Jinshan Lai |
| 13 | [Implicit Neural Representations of Individual Behavior](http://arxiv.org/abs/2606.12200v1) | 我们研究从未标记的多政策行为数据中学习的政策表示。每个剧集都由固定策略生成，但策略标签不可用。我们发布代码和检查点。 | TRI | Andrew Kang |
| 14 | [Agentic Environment Engineering for Large Language Models: A…](http://arxiv.org/abs/2606.12191v1) | 环境作为基于大型语言模型（ LLM ）的代理在不同场景中的交互式系统，在推动模型功能的持续演变中发挥着至关重要的作用。尽管如此重要，现有的工作缺乏系统的分类和深入的分析。最后，讨论了几个有前途的未来方… | TRI | Jiachun Li |
| 15 | [Automating Geometry-Intensive Compliance Checking in BIM: Gr…](http://arxiv.org/abs/2606.12065v1) | 自动化几何密集型法规的合规性检查仍然是建筑信息建模（ BIM ）的一个重大技术瓶颈，主要是由于高级监管逻辑和结构化IFC数据之间的语义差异。现有方法通常依赖于静态规则模板，难以遍历多跳推理链或解决多个… | HIT、TRI | Zixuan Xiao |
| 16 | [A Lightweight Multi-Agent Framework for Automated Concrete B…](http://arxiv.org/abs/2606.12040v1) | 钢筋混凝土高速公路路障的设计是一个安全关键的过程，需要严格遵守监管规定，如AASHTO-LRFD桥梁设计指南。当前的工程实践严重依赖手动、迭代和启发式计算来满足复杂的非线性材料和力学约束。关键词：结构… | MIT、TRI | Wanting Wang |
| 17 | [Human-Enhanced Loop Modeling (HELM): Agent-Based Finite Elem…](http://arxiv.org/abs/2606.12025v1) | 安全关键基础设施（如桥梁障碍物）的有限元（ FE ）建模需要高保真非线性动态分析，但目前的FE建模过程仍然是劳动密集型的，缺乏自动化。本文提出了人-增强循环建模（ HELM ）框架，这是一种协作的人-… | MIT、CAS | Quankai Wang |
| 18 | [MODF-SIR: A Multi-agent Omni-modal Distilled Framework for S…](http://arxiv.org/abs/2606.12018v1) | 我们提出了一个建立在轻量级多模态大型语言模型（ MLLM ）上的多智能体协作框架，专门为社会智能推理而设计。我们方法的一个关键特征是通过知识蒸馏来增强训练和推理阶段。代码可在https://githu… | HIT | Shang Ma |
| 19 | [Exploration Structure in LLM Agents for Multi-File Change Lo…](http://arxiv.org/abs/2606.11976v1) | 软件工程工具越来越依赖基于LLM的代理来本地化要更改的文件，以解决软件问题。大多数AI代理会线性探索存储库，即每步访问一个目录或文件。最后，强制多代理商咨询不会带来可衡量的帮助，并大幅提高代币成本。 | MIT | Akeela Darryl Fattha |

### 论文详情

<details>
<summary><b>1. Context-Driven Incremental Compression for Multi-Turn Dialogue Generation</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Yeongseo Jung、Jaehyeok Kim、Eunseo Jung、Jiachuan Wang、Yongqi Zhang 等（共 8 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-06-10T17:59:54Z |
| **关键词** | `RAG` · `Benchmark` · `Memory` |
| **原文链接** | [http://arxiv.org/abs/2606.12411v1](http://arxiv.org/abs/2606.12411v1) |

**📝 摘要概括：**

> 现代对话代理在每个转折点都依赖于不断增长的对话历史记录，这会产生多余的注意力和编码成本，这些成本会随着对话时间的长短而增加。朴素的截断或摘要会降低保真度，而现有的上下文压缩器缺乏交叉转换内存共享或修订，导致长对话中的信息丢失和复合错误。在长对话基准上的广泛实验证明了优异的…

</details>

<details>
<summary><b>2. DIRECT: When and Where Should You Allocate Test-Time Compute in Embodied Planners?</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Jadelynn Dao、Milan Ganai、Yasmina Abukhadra、Ajay Sridhar、Mozhgan Nasr Azadani 等（共 10 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT |
| **发布时间** | 2026-06-10T17:58:49Z |
| **关键词** | `Planning` · `RAG` · `Chain-of-Thought` · `Embodied AI` · `Memory` |
| **原文链接** | [http://arxiv.org/abs/2606.12402v1](http://arxiv.org/abs/2606.12402v1) |

**📝 摘要概括：**

> 视觉语言模型（ VLM ）越来越多地被部署为具体代理的高级规划器，其新兴策略是扩展测试时间计算以提高能力。然而，我们观察到，这样做会增加延迟、令牌使用率和FLOP ，同时产生不均匀，通常会减少下游成功的收益，从而限制了可以部署具体代理的地方。项目页面可在jadee-dao.github.io/direct/上找到。

</details>

<details>
<summary><b>3. TAHOE: Text-to-SQL with Automated Hint Optimization from Experience</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Zhiyi Chen、Jie Song、Peng Li |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-06-10T17:52:15Z |
| **关键词** | `Agentic` · `Planning` · `RAG` · `Fine-tuning` · `Workflow` |
| **原文链接** | [http://arxiv.org/abs/2606.12387v1](http://arxiv.org/abs/2606.12387v1) |

**📝 摘要概括：**

> 大型语言模型（ LLM ）通过Text-to-SQL实现了数据库访问的民主化，但从原型到生产仍然很困难。真正的部署必须处理严格的SQL方言、大规模模式和不断变化的用户偏好，而受监督的微调成本高昂且严格，而代理测试时间扩展成本高昂。同样的提示银行也向较弱的骨干转移，包括Doubao-2的通过率提高19.7个百分点……

</details>

<details>
<summary><b>4. ATLAS: Active Theory Learning for Automated Science</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Noémi Éltető、Nathaniel D. Daw、Kimberly L. Stachenfeld、Kevin J. Miller |
| **所属机构** | （详见原文） |
| **顶级机构标签** | CAS、Mila、TRI |
| **发布时间** | 2026-06-10T17:52:03Z |
| **关键词** | `Reinforcement Learning` |
| **原文链接** | [http://arxiv.org/abs/2606.12386v1](http://arxiv.org/abs/2606.12386v1) |

**📝 摘要概括：**

> 通过机械建模推进科学理解需要提出正确的实验问题，以产生最大限度的信息数据。为了在认知科学中实现这一追求的自动化，我们引入了ATLAS （自动化科学的主动理论学习） ，这是一种用于数据驱动的可解释行为模型发现的主动学习框架。这些电子版结果展示了ATLAS在……方面加速人类可解释性的潜力

</details>

<details>
<summary><b>5. APPO: Agentic Procedural Policy Optimization</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Xucong Wang、Ziyu Ma、Yong Wang、Yuxiang Ji、Shidong Yang 等（共 8 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-06-10T17:47:07Z |
| **关键词** | `Agentic` · `Reinforcement Learning` · `Benchmark` · `Workflow` |
| **原文链接** | [http://arxiv.org/abs/2606.12384v1](http://arxiv.org/abs/2606.12384v1) |

**📝 摘要概括：**

> 代理强化学习（ RL ）的最新进展大大提高了大型语言模型代理的多圈工具使用能力。然而，大多数现有方法都将功劳分配给粗略的启发式单元，例如工具调用边界或固定工作流程，因此很难确定哪些中间决策会影响下游结果。13个基准的实验表明， APPO不断提高强大的代理RL…

</details>

<details>
<summary><b>6. UniIntervene: Agentic Intervention for Efficient Real-World Reinforcement Learning</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Haoyuan Deng、Yitong Gao、Yudong Lin、Haichao Liu、Zhenyu Wu 等（共 6 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-06-10T17:38:24Z |
| **关键词** | `Agentic` · `Reinforcement Learning` · `RAG` · `Memory` |
| **原文链接** | [http://arxiv.org/abs/2606.12372v1](http://arxiv.org/abs/2606.12372v1) |

**📝 摘要概括：**

> 人类在环强化学习（ HiL-RL ）已成为现实世界机器人操纵的有效范例，在人类指导下实现在线政策改进。然而，目前的HiL-RL框架仍然是干预密集型的，依靠频繁的人工纠正来将政策从非生产性探索中重定向，这会导致高劳动力成本并限制现实世界的可扩展性。对多样化的现实世界机器人进行广泛的实验……

</details>

<details>
<summary><b>7. Breaking Entropy Bounds: Accelerating RL Training via MTP with Rejection Sampling</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Yucheng Li、Huiqiang Jiang、Yang Xu、Jianxin Yang、Yi Zhang 等（共 17 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT |
| **发布时间** | 2026-06-10T17:36:45Z |
| **关键词** | `Agentic` · `Reasoning` · `Reinforcement Learning` · `Code Generation` |
| **原文链接** | [http://arxiv.org/abs/2606.12370v1](http://arxiv.org/abs/2606.12370v1) |

**📝 摘要概括：**

> 强化学习（ RL ）已成为现代大型语言模型的关键组成部分，但推出阶段仍然是RL培训管道的关键瓶颈。尽管多令牌预测（ MTP ）提供了一种通过投机解码加速推出的自然解决方案，但许多研究发现， MTP接受率在RL培训期间显着下降，导致加速性能有限。实验结果表明，我们的方法……

</details>

<details>
<summary><b>8. Claw-SWE-Bench: A Benchmark for Evaluating OpenClaw-style Agent Harnesses on Coding Tasks</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Mengyu Zheng、Kai Han、Boxun Li、Haiyang Xu、Yuchuan Tian 等（共 16 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | FAIR、MIT、Mila |
| **发布时间** | 2026-06-10T17:16:23Z |
| **关键词** | `Benchmark` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2606.12344v1](http://arxiv.org/abs/2606.12344v1) |

**📝 摘要概括：**

> OpenClaw等通用代理越来越多地被用作自主工具用户，但它们的编码能力在SWE-bench下难以衡量：通用代理本身并不满足评分所需的干净的Docker工作空间、补丁和预测合约。我们推出了Claw-SWE-Bench ，这是一种多语言SWE-bench风格的基准和适配器协议，使异构代理线束或CLAWS在公平环境中具有可比性……

</details>

<details>
<summary><b>9. Fourier Features Let Agents Learn High Precision Policies with Imitation Learning</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Balázs Gyenes、Emiliyan Gospodinov、Jan Frieling、Enrico Krohmer、Nicolas Schreiber 等（共 8 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、HIT、CAS |
| **发布时间** | 2026-06-10T17:05:50Z |
| **关键词** | `Reasoning` · `RAG` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2606.12334v1](http://arxiv.org/abs/2606.12334v1) |

**📝 摘要概括：**

> 高精度机器人操作需要精细的空间推理，由于深度模糊和透视尺度问题，仅使用RGB策略通常很难实现。直接利用3D信息的策略（例如基于点云的策略）提供了比纯粹基于图像的策略更强的几何优先级，但其性能仍然高度依赖于任务。我们在项目页面上提供源代码和视频： https:/…

</details>

<details>
<summary><b>10. A Five-Plane Reference Architecture for Runtime Governance of Production AI Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Krti Tallam |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、HIT、TRI |
| **发布时间** | 2026-06-10T16:54:47Z |
| **关键词** | `AI Agent` · `Agentic` · `Reasoning` · `Benchmark` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2606.12320v1](http://arxiv.org/abs/2606.12320v1) |

**📝 摘要概括：**

> 企业安全旨在管理数据边界：受保护的表面是静态和传输中的数据，而控制（访问控制、数据丢失预防、周边检查）则管理该边界的跨越。生产AI代理打破了这一假设。我们明确规定了范围：架构管理委派的操作，而不是模型行为，下一步是根据实时代理基准进行全系统评估……

</details>

<details>
<summary><b>11. CCKS: Consensus-based Communication and Knowledge Sharing</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Jinyuan Zu、Xiaowei Lv、Yongcai Wang、Deying Li、Yunjun Han 等（共 8 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | Google Research、Google |
| **发布时间** | 2026-06-10T16:20:18Z |
| **关键词** | `Multi-Agent` · `Reinforcement Learning` |
| **原文链接** | [http://arxiv.org/abs/2606.12281v1](http://arxiv.org/abs/2606.12281v1) |

**📝 摘要概括：**

> 在合作多智能体强化学习（ MARL ）的去中心化培训和去中心化执行（ DTDE ）中，基于行动建议的知识共享促进了智能体之间可解释和可扩展的合作。然而，目前的行动建议方法往往过多地遵循教师的指导，而没有评估师生兼容性，这会导致建议过多、次优稳定性和绩效下降。

</details>

<details>
<summary><b>12. Intelligent Automation for Embodied Benchmark Construction: Pipelines, Embodiments, Simulators, and Trends</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Jinshan Lai、Jianwei Hu、Baoyang Jiang、Fengchun Zhang、Leyuan Wang 等（共 10 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-06-10T15:25:02Z |
| **关键词** | `Agentic` · `Benchmark` · `Evaluation` · `Simulation` · `Embodied AI` |
| **原文链接** | [http://arxiv.org/abs/2606.12207v1](http://arxiv.org/abs/2606.12207v1) |

**📝 摘要概括：**

> 具体的智能现在涵盖导航、家庭辅助、操纵、自动驾驶、空中代理和多模式大型模型控制。这种扩张使基准建设成为可靠评估的核心瓶颈。因此，具体评估的进展不仅取决于更大的基准套件，还取决于可诊断、可审计和可负责任地更新的施工管道。

</details>

<details>
<summary><b>13. Implicit Neural Representations of Individual Behavior</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Andrew Kang、Priya Narasimhan |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-06-10T15:19:41Z |
| **关键词** | `Robotics` |
| **原文链接** | [http://arxiv.org/abs/2606.12200v1](http://arxiv.org/abs/2606.12200v1) |

**📝 摘要概括：**

> 我们研究从未标记的多政策行为数据中学习的政策表示。每个剧集都由固定策略生成，但策略标签不可用。我们发布代码和检查点。

</details>

<details>
<summary><b>14. Agentic Environment Engineering for Large Language Models: A Survey of Environment Modeling, Synthesis, Evaluation, and Application</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Jiachun Li、Zhuoran Jin、Tianyi Men、Yupu Hao、Kejian Zhu 等（共 15 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-06-10T15:15:01Z |
| **关键词** | `Multi-Agent` · `Agentic` · `Evaluation` · `Memory` · `Workflow` |
| **原文链接** | [http://arxiv.org/abs/2606.12191v1](http://arxiv.org/abs/2606.12191v1) |

**📝 摘要概括：**

> 环境作为基于大型语言模型（ LLM ）的代理在不同场景中的交互式系统，在推动模型功能的持续演变中发挥着至关重要的作用。尽管如此重要，现有的工作缺乏系统的分类和深入的分析。最后，讨论了几个有前途的未来方向，包括环境即服务、多代理环境和神经符号环境。

</details>

<details>
<summary><b>15. Automating Geometry-Intensive Compliance Checking in BIM: Graph-Based Semantic Reasoning Framework</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Zixuan Xiao、Pei Troh Koh、Jun Ma、Jack C. P. Cheng |
| **所属机构** | （详见原文） |
| **顶级机构标签** | HIT、TRI |
| **发布时间** | 2026-06-10T13:31:43Z |
| **关键词** | `Reasoning` · `Workflow` |
| **原文链接** | [http://arxiv.org/abs/2606.12065v1](http://arxiv.org/abs/2606.12065v1) |

**📝 摘要概括：**

> 自动化几何密集型法规的合规性检查仍然是建筑信息建模（ BIM ）的一个重大技术瓶颈，主要是由于高级监管逻辑和结构化IFC数据之间的语义差异。现有方法通常依赖于静态规则模板，难以遍历多跳推理链或解决多个建筑物实体之间的潜在空间依赖关系。这项研究提供了……

</details>

<details>
<summary><b>16. A Lightweight Multi-Agent Framework for Automated Concrete Barrier Design</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Wanting Wang、Xiye Ma、Yuyang He、Minghui Cheng、Ran Cao |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-06-10T13:06:11Z |
| **关键词** | `Multi-Agent` · `Agentic` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2606.12040v1](http://arxiv.org/abs/2606.12040v1) |

**📝 摘要概括：**

> 钢筋混凝土高速公路路障的设计是一个安全关键的过程，需要严格遵守监管规定，如AASHTO-LRFD桥梁设计指南。当前的工程实践严重依赖手动、迭代和启发式计算来满足复杂的非线性材料和力学约束。关键词：结构工程；多Agent系统；大型语言模型；混凝土屏障设计； ……

</details>

<details>
<summary><b>17. Human-Enhanced Loop Modeling (HELM): Agent-Based Finite Element Modeling of Concrete Bridge Barriers</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Quankai Wang、Yulin Xie、Tongfei Yang、Minghui Cheng、Ran Cao |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、CAS、TRI |
| **发布时间** | 2026-06-10T12:48:27Z |
| **关键词** | `Reasoning` |
| **原文链接** | [http://arxiv.org/abs/2606.12025v1](http://arxiv.org/abs/2606.12025v1) |

**📝 摘要概括：**

> 安全关键基础设施（如桥梁障碍物）的有限元（ FE ）建模需要高保真非线性动态分析，但目前的FE建模过程仍然是劳动密集型的，缺乏自动化。本文提出了人-增强循环建模（ HELM ）框架，这是一种协作的人-代理协议，将长序列有限元建模分解为跨几何生成的离散、可视验证的检查点…

</details>

<details>
<summary><b>18. MODF-SIR: A Multi-agent Omni-modal Distilled Framework for Social Intelligence Reasoning</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Shang Ma、Jisheng Dang、Wencan Zhang、Yifan Zhang、Bimei Wang 等（共 9 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | HIT |
| **发布时间** | 2026-06-10T12:44:02Z |
| **关键词** | `Multi-Agent` · `Reasoning` · `Benchmark` · `Evaluation` · `Chain-of-Thought` |
| **原文链接** | [http://arxiv.org/abs/2606.12018v1](http://arxiv.org/abs/2606.12018v1) |

**📝 摘要概括：**

> 我们提出了一个建立在轻量级多模态大型语言模型（ MLLM ）上的多智能体协作框架，专门为社会智能推理而设计。我们方法的一个关键特征是通过知识蒸馏来增强训练和推理阶段。代码可在https://github.com/eeee-sys/MODF-SIR上获得，演示可在https://huggingface.co/spaces/Harry-1234/MODF-SIR上获得， LoRA可在https: …

</details>

<details>
<summary><b>19. Exploration Structure in LLM Agents for Multi-File Change Localization</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Akeela Darryl Fattha、Kia Ying Chua、Lingxiao Jiang、Laura Wynter |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT |
| **发布时间** | 2026-06-10T11:54:14Z |
| **关键词** | `Multi-Agent` · `LLM Agent` · `AI Agent` · `Agentic` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2606.11976v1](http://arxiv.org/abs/2606.11976v1) |

**📝 摘要概括：**

> 软件工程工具越来越依赖基于LLM的代理来本地化要更改的文件，以解决软件问题。大多数AI代理会线性探索存储库，即每步访问一个目录或文件。最后，强制多代理商咨询不会带来可衡量的帮助，并大幅提高代币成本。

</details>

## 🗄️ 历史归档

| 日期 | 论文数 | 报告链接 |
|------|--------|----------|
| 2026-06-11 | 19 篇 | [2026-06-11.md](daily/2026-06-11.md) |
| 2026-06-10 | 19 篇 | [2026-06-10.md](daily/2026-06-10.md) |
| 2026-06-09 | 20 篇 | [2026-06-09.md](daily/2026-06-09.md) |
| 2026-06-08 | 0 篇 | [2026-06-08.md](daily/2026-06-08.md) |
| 2026-06-07 | 0 篇 | [2026-06-07.md](daily/2026-06-07.md) |
| 2026-06-06 | 0 篇 | [2026-06-06.md](daily/2026-06-06.md) |
| 2026-06-05 | 20 篇 | [2026-06-05.md](daily/2026-06-05.md) |
| 2026-06-04 | 0 篇 | [2026-06-04.md](daily/2026-06-04.md) |
| 2026-06-03 | 20 篇 | [2026-06-03.md](daily/2026-06-03.md) |
| 2026-06-02 | 20 篇 | [2026-06-02.md](daily/2026-06-02.md) |
| 2026-06-01 | 0 篇 | [2026-06-01.md](daily/2026-06-01.md) |
| 2026-05-31 | 0 篇 | [2026-05-31.md](daily/2026-05-31.md) |
| 2026-05-30 | 0 篇 | [2026-05-30.md](daily/2026-05-30.md) |
| 2026-05-29 | 0 篇 | [2026-05-29.md](daily/2026-05-29.md) |
| 2026-05-28 | 0 篇 | [2026-05-28.md](daily/2026-05-28.md) |
| 2026-05-27 | 0 篇 | [2026-05-27.md](daily/2026-05-27.md) |
| 2026-05-26 | 0 篇 | [2026-05-26.md](daily/2026-05-26.md) |
| 2026-05-25 | 0 篇 | [2026-05-25.md](daily/2026-05-25.md) |
| 2026-05-24 | 0 篇 | [2026-05-24.md](daily/2026-05-24.md) |
| 2026-05-23 | 0 篇 | [2026-05-23.md](daily/2026-05-23.md) |
| 2026-05-22 | 20 篇 | [2026-05-22.md](daily/2026-05-22.md) |
| 2026-05-21 | 0 篇 | [2026-05-21.md](daily/2026-05-21.md) |
| 2026-05-20 | 16 篇 | [2026-05-20.md](daily/2026-05-20.md) |
| 2026-05-19 | 0 篇 | [2026-05-19.md](daily/2026-05-19.md) |
| 2026-05-17 | 0 篇 | [2026-05-17.md](daily/2026-05-17.md) |
| 2026-05-16 | 0 篇 | [2026-05-16.md](daily/2026-05-16.md) |
| 2026-05-15 | 20 篇 | [2026-05-15.md](daily/2026-05-15.md) |
| 2026-05-14 | 19 篇 | [2026-05-14.md](daily/2026-05-14.md) |
| 2026-05-13 | 20 篇 | [2026-05-13.md](daily/2026-05-13.md) |
| 2026-05-12 | 20 篇 | [2026-05-12.md](daily/2026-05-12.md) |

## 🏛️ 顶级机构覆盖范围

覆盖超过 **70 个**顶级 AI 机构，包括：

- **科技公司：** Microsoft、Google DeepMind、OpenAI、Anthropic、Meta AI、NVIDIA、Baidu、Alibaba、ByteDance 等
- **北美顶级大学：** MIT、Stanford、CMU、UC Berkeley、Harvard、Princeton、Cornell、Caltech 等
- **中国顶级大学/机构：** 清华大学、北京大学、浙大、上交大、复旦、中科院、MSRA 等
- **欧洲/其他：** Oxford、Cambridge、ETH Zurich、Mila、NUS、KAIST 等

---

*由 [clawBot DailyFindings](https://github.com/Jacob-biu/clawBot) 自动维护 | 最后更新：2026-06-11 23:22 UTC*
