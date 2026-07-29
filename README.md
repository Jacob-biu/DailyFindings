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

## 📅 今日论文 — 2026-07-29　　[→ 查看完整报告](daily/2026-07-29.md)

> 共筛选出 **16** 篇论文 | 更新于 2026-07-29 23:00 UTC

### 论文目录与概要

| # | 论文标题 | 核心概要 | 来源机构 | 第一作者 |
|---|---------|---------|---------|--------|
| 1 | [VetClaw: An Edge-Cloud Multimodal Agentic System for Veterin…](http://arxiv.org/abs/2607.26042v1) | 我们介绍VetClaw ，一种用于早期兽医疾病筛查的边缘云多峰代理系统。VetClaw使用摄像头模块作为边缘传感设备，并将捕获的图像以及可选的症状描述发送到服务器托管的视觉语言模型，以进行零点疾病分类… | MIT、CAS | Syed Mhamudul Hasan |
| 2 | [Pictura: Perspective-View Self-Play at Scale for Driving](http://arxiv.org/abs/2607.26005v1) | 模拟中的自我游戏可大规模生成强大的驾驶策略。这种行为的演示已经使用特权矢量化观测进行，例如精确的姿势和速度，即使对于被遮挡的药剂也是如此。项目页面： https://valeoai.github.io… | MIT、TRI | Yuan Yin |
| 3 | [MemLens: A Value-Aware Memory Management System with Interac…](http://arxiv.org/abs/2607.25992v1) | 最近，内存管理已成为基于LLM的代理的关键基础设施，因为它直接影响长远推理、个性化响应和知识重用。然而，现有的LLM内存系统通常采用粗粒度（实用程序不可知）方式，统一处理异构用户-LLM交互记录，导致… | TRI | Shuyue Wei |
| 4 | [Toward Standardized Cross-Vendor Agent Tool Trust Management…](http://arxiv.org/abs/2607.25914v1) | 自治网络级别4-5要求人工智能代理在没有人工监督的情况下跨越供应商边界调用工具，但现有的管理标准缺乏跨供应商信任可见性的标准化机制。当供应商B的工具受到损害时，供应商A的代理会继续调用它（未意识到信任… | CAS | Ravi Kant Sharma |
| 5 | [Interactive Reward Agent: GUI Task Evaluation via Environmen…](http://arxiv.org/abs/2607.25904v1) | 图形用户界面任务评估旨在确定GUI代理是否已成功完成用户指令。自动化GUI任务评估受到越来越多的关注，因为评估结果可以作为测试时间缩放和训练后的奖励信号。我们进一步将IRA应用于GUI代理的强化学习，… | NTU | Chenrui Shi |
| 6 | [Messier: A High-Resolution Corpus for Cross-Benchmark Agent …](http://arxiv.org/abs/2607.25891v1) | 在交互式环境中评估AI代理受到分散的任务、支架、验证器和评分规则的阻碍。现有的努力集中在狭窄的环境，规模仍然有限，或需要昂贵的重新运行，使大部分经验记录无与伦比。Messier为代理功能扩展、基准审核… | MIT、TRI | Stefan Krsteski |
| 7 | [Distributing Security Controls Through Harness Engineering](http://arxiv.org/abs/2607.25890v1) | 人工智能编码代理正在以历史性的速度被采用，但安全和风险问题仍然是跨组织扩展代理人工智能的主要障碍。编码代理的现有安全控制没有系统地分发给工程团队，供应商本地解决方案引入了可能不适合每个部署环境的生态系… | MIT、TRI | William Robert Gore |
| 8 | [Runtime Uncertainty Monitoring for LLM-Based Multi-Agent Sys…](http://arxiv.org/abs/2607.25877v1) | 本文研究了基于大型语言模型（ LLM ）的多智能体系统（ MAS ）如何支持精算风险建模，特别关注不确定性量化。精算工作流程是一种高风险的决策支持环境，其中不可靠的产出可能导致不正确的风险评估、不公平… | FAIR、TRI | Bart Custers |
| 9 | [HiSkill: Empowering LLM Agents with Hierarchical Skill Graph…](http://arxiv.org/abs/2607.25853v1) | 技能已成为大型语言模型（ LLM ）代理在长距离交互式任务中重用过去经验的重要抽象。然而，现有的技能轨迹方法通常会产生独立存储和检索的高级文本技能的平面集合，从而使技能关系未得到充分利用，并在高级技能… | TRI | Yu Hao |
| 10 | [Lowering the implementation barrier of neutral-atom quantum …](http://arxiv.org/abs/2607.25834v1) | 量子计算机正在从研究实验室转向可通过云访问并集成到高性能计算设施中的工业机器。然而，将理论量子协议转化为硬件实验仍然是一个主要瓶颈，需要协议设计、编译、模拟和云执行方面的专业知识。总之，这些结果表明，… | CAS、NTU | Constantin Dalyac |
| 11 | [Speculate While You Reason: Teaching Agents to Predict Their…](http://arxiv.org/abs/2607.25816v1) | 大型语言模型代理通常会花费大量的时间等待工具调用结果。如果预测与座席的最终工具调用匹配，工具调用推测可以通过预测和预执行座席的下一个工具调用来隐藏这种延迟，但现有的投机者通常是单独的草稿模型或缓存跟踪… | HIT、NTU | Jiabao Ji |
| 12 | [Shared Voxel-Map-Based Cooperative Indoor UAV Guidance with …](http://arxiv.org/abs/2607.25728v1) | 本文提出了一种将共享体素图世界模型与多智能体软行为批判（ MASAC ）控制器相结合的协作室内无人机制导框架。多架无人机将360度激光雷达观测融合到一个通用的世界框架占用图中，该占用图被转换为紧凑的鸟… | MIT | Thomas Hickling |
| 13 | [Tools Are Not Islands: Set-Level Tool Retrieval for LLM Agen…](http://arxiv.org/abs/2607.25718v1) | 大型语言模型（ LLM ）代理越来越依赖于调用外部工具来完成真实世界的任务。工具检索在代理采取行动之前从数千个工具库中选择一个小的任务相关子集，因此已成为LLM代理管道的关键组成部分。除了域内设置之外… | TRI | Xinyi Hong |
| 14 | [OrchBench: Evaluating Multi-Agent Orchestration Plans in Iso…](http://arxiv.org/abs/2607.25656v1) | 复杂任务通常分解为可并行但相互依赖的子任务，使得编排对多代理系统（ MAS ）的性能至关重要。现有评估通常依赖于端到端执行，这会将编排计划质量与工作人员能力、工具可靠性和环境噪音混为一谈。这些结果使O… | MIT | Zhenzhen Ren |
| 15 | [F(AI)2R: Who Did What, and Who Checked? Verifiable AI Proven…](http://arxiv.org/abs/2607.25637v1) | F (AI) 2R是AI在循环中的公平研究，两次： AI辅助创作通行证和每个人工制品的机器可读审计通行证。人工智能系统现在起草、重构和验证研究成果，但它们的贡献很少以人类或机器可以审计的形式记录。其生… | FAIR、CAS | Florian Krebs |
| 16 | [Beyond Epistemia: Epistemic Schizologia and Large Language M…](http://arxiv.org/abs/2607.25620v1) | Quattrociocchi及其同事警告说，大型语言模型的流畅输出可能允许语言合理性代替认识论评估，从而产生他们称之为“认识论”的病症：拥有知识而不进行通常需要判断的实践的经验。本文接受了这一诊断，但… | TRI | Federico Cabitza |

### 论文详情

<details>
<summary><b>1. VetClaw: An Edge-Cloud Multimodal Agentic System for Veterinary Disease Screening</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Syed Mhamudul Hasan、Anas AlSobeh、Hussein Zangoti、Abdur R. Shahid |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、CAS |
| **发布时间** | 2026-07-28T17:50:25Z |
| **关键词** | `Agentic` · `Workflow` |
| **原文链接** | [http://arxiv.org/abs/2607.26042v1](http://arxiv.org/abs/2607.26042v1) |

**📝 摘要概括：**

> 我们介绍VetClaw ，一种用于早期兽医疾病筛查的边缘云多峰代理系统。VetClaw使用摄像头模块作为边缘传感设备，并将捕获的图像以及可选的症状描述发送到服务器托管的视觉语言模型，以进行零点疾病分类。因此， VetClaw将静态预测模型转换为协调的安全感知系统，该系统可以使用工具、管理工作流程、处理故障……

</details>

<details>
<summary><b>2. Pictura: Perspective-View Self-Play at Scale for Driving</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Yuan Yin、Elias Ramzi、Marc Lafon、Valentin Charraut、Victor Bares 等（共 11 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-07-28T17:20:39Z |
| **关键词** | `Multi-Agent` · `Simulation` |
| **原文链接** | [http://arxiv.org/abs/2607.26005v1](http://arxiv.org/abs/2607.26005v1) |

**📝 摘要概括：**

> 模拟中的自我游戏可大规模生成强大的驾驶策略。这种行为的演示已经使用特权矢量化观测进行，例如精确的姿势和速度，即使对于被遮挡的药剂也是如此。项目页面： https://valeoai.github.io/Pictura/

</details>

<details>
<summary><b>3. MemLens: A Value-Aware Memory Management System with Interactive Analytics for LLM-based Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Shuyue Wei、Chang Liu、Zimu Zhou、Yongxin Tong、Lizhen Cui |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-07-28T17:08:56Z |
| **关键词** | `Reasoning` · `RAG` · `Retrieval` · `Evaluation` · `Memory` |
| **原文链接** | [http://arxiv.org/abs/2607.25992v1](http://arxiv.org/abs/2607.25992v1) |

**📝 摘要概括：**

> 最近，内存管理已成为基于LLM的代理的关键基础设施，因为它直接影响长远推理、个性化响应和知识重用。然而，现有的LLM内存系统通常采用粗粒度（实用程序不可知）方式，统一处理异构用户-LLM交互记录，导致冗余和低影响记录持续存在于内存存储库中。因此，我们的MemLens可以提供……

</details>

<details>
<summary><b>4. Toward Standardized Cross-Vendor Agent Tool Trust Management in Autonomous Networks</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Ravi Kant Sharma、Ashutosh Uttam、Ajay Kumar |
| **所属机构** | （详见原文） |
| **顶级机构标签** | CAS |
| **发布时间** | 2026-07-28T16:06:41Z |
| **关键词** | `AI Agent` · `RAG` · `Evaluation` · `Simulation` |
| **原文链接** | [http://arxiv.org/abs/2607.25914v1](http://arxiv.org/abs/2607.25914v1) |

**📝 摘要概括：**

> 自治网络级别4-5要求人工智能代理在没有人工监督的情况下跨越供应商边界调用工具，但现有的管理标准缺乏跨供应商信任可见性的标准化机制。当供应商B的工具受到损害时，供应商A的代理会继续调用它（未意识到信任降级） ，从而导致级联服务影响。该框架在现有的3GPP管理基础设施内运行，利用……

</details>

<details>
<summary><b>5. Interactive Reward Agent: GUI Task Evaluation via Environment-State Verification</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Chenrui Shi、Yuwei Wu、Yang Liu、Ruining Feng、Zirui Shang 等（共 8 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | NTU |
| **发布时间** | 2026-07-28T16:01:38Z |
| **关键词** | `Reinforcement Learning` · `Benchmark` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2607.25904v1](http://arxiv.org/abs/2607.25904v1) |

**📝 摘要概括：**

> 图形用户界面任务评估旨在确定GUI代理是否已成功完成用户指令。自动化GUI任务评估受到越来越多的关注，因为评估结果可以作为测试时间缩放和训练后的奖励信号。我们进一步将IRA应用于GUI代理的强化学习，实现了34.0 ％的OSWorld成功率，这表明IRA可以提供有效的REW...

</details>

<details>
<summary><b>6. Messier: A High-Resolution Corpus for Cross-Benchmark Agent Evaluation</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Stefan Krsteski、Charlotte Meyer、Guillaume Allegre、Tony O'Halloran、Alexandre Sallinen |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-07-28T15:50:19Z |
| **关键词** | `AI Agent` · `RAG` · `Benchmark` · `Evaluation` · `Workflow` |
| **原文链接** | [http://arxiv.org/abs/2607.25891v1](http://arxiv.org/abs/2607.25891v1) |

**📝 摘要概括：**

> 在交互式环境中评估AI代理受到分散的任务、支架、验证器和评分规则的阻碍。现有的努力集中在狭窄的环境，规模仍然有限，或需要昂贵的重新运行，使大部分经验记录无与伦比。Messier为代理功能扩展、基准审核和评估失败的精细分析提供了基础的可重用基础设施。

</details>

<details>
<summary><b>7. Distributing Security Controls Through Harness Engineering</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | William Robert Gore |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-07-28T15:50:16Z |
| **关键词** | `Agentic` |
| **原文链接** | [http://arxiv.org/abs/2607.25890v1](http://arxiv.org/abs/2607.25890v1) |

**📝 摘要概括：**

> 人工智能编码代理正在以历史性的速度被采用，但安全和风险问题仍然是跨组织扩展代理人工智能的主要障碍。编码代理的现有安全控制没有系统地分发给工程团队，供应商本地解决方案引入了可能不适合每个部署环境的生态系统依赖关系。提出了控制线束适应性框架的初始特征，以及……

</details>

<details>
<summary><b>8. Runtime Uncertainty Monitoring for LLM-Based Multi-Agent Systems Using Bayesian Networks</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Bart Custers、Koorosh Aslansefat |
| **所属机构** | （详见原文） |
| **顶级机构标签** | FAIR、TRI |
| **发布时间** | 2026-07-28T15:39:43Z |
| **关键词** | `Multi-Agent` · `Workflow` |
| **原文链接** | [http://arxiv.org/abs/2607.25877v1](http://arxiv.org/abs/2607.25877v1) |

**📝 摘要概括：**

> 本文研究了基于大型语言模型（ LLM ）的多智能体系统（ MAS ）如何支持精算风险建模，特别关注不确定性量化。精算工作流程是一种高风险的决策支持环境，其中不可靠的产出可能导致不正确的风险评估、不公平的定价和监管违规行为。结果表明，该框架重现了基线精算绩效，同时提供了……

</details>

<details>
<summary><b>9. HiSkill: Empowering LLM Agents with Hierarchical Skill Graphs</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Yu Hao、Jinxuan Cai、Qi Zhang、Yawen Li、Zhiqiang Zhang 等（共 7 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-07-28T15:25:47Z |
| **关键词** | `LLM Agent` |
| **原文链接** | [http://arxiv.org/abs/2607.25853v1](http://arxiv.org/abs/2607.25853v1) |

**📝 摘要概括：**

> 技能已成为大型语言模型（ LLM ）代理在长距离交互式任务中重用过去经验的重要抽象。然而，现有的技能轨迹方法通常会产生独立存储和检索的高级文本技能的平面集合，从而使技能关系未得到充分利用，并在高级技能和可执行操作之间保持差距。我们的数据和代码可在http…

</details>

<details>
<summary><b>10. Lowering the implementation barrier of neutral-atom quantum computing with agentic workflows</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Constantin Dalyac、Alexandre Dauphin、Loïc Henriet、Christophe Jurczak |
| **所属机构** | （详见原文） |
| **顶级机构标签** | CAS、NTU、TRI |
| **发布时间** | 2026-07-28T15:13:14Z |
| **关键词** | `Agentic` · `Simulation` · `Workflow` |
| **原文链接** | [http://arxiv.org/abs/2607.25834v1](http://arxiv.org/abs/2607.25834v1) |

**📝 摘要概括：**

> 量子计算机正在从研究实验室转向可通过云访问并集成到高性能计算设施中的工业机器。然而，将理论量子协议转化为硬件实验仍然是一个主要瓶颈，需要协议设计、编译、模拟和云执行方面的专业知识。总之，这些结果表明，代理工作流程在……之间提供了一个实用的桥梁

</details>

<details>
<summary><b>11. Speculate While You Reason: Teaching Agents to Predict Their Next Tool Call via Joint Agent-Speculator RL</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Jiabao Ji、Yujian Liu、Li An、Rohit Jain、Gungor Polatkan 等（共 7 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | HIT、NTU |
| **发布时间** | 2026-07-28T15:00:10Z |
| **关键词** | `Agentic` · `Reinforcement Learning` · `RAG` |
| **原文链接** | [http://arxiv.org/abs/2607.25816v1](http://arxiv.org/abs/2607.25816v1) |

**📝 摘要概括：**

> 大型语言模型代理通常会花费大量的时间等待工具调用结果。如果预测与座席的最终工具调用匹配，工具调用推测可以通过预测和预执行座席的下一个工具调用来隐藏这种延迟，但现有的投机者通常是单独的草稿模型或缓存跟踪，与部署的座席自身的行为不太一致。跨代理搜索QA和对话工具……

</details>

<details>
<summary><b>12. Shared Voxel-Map-Based Cooperative Indoor UAV Guidance with a Multi-Agent Soft Actor-Critic Controller</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Thomas Hickling、Dylan Wynne、Yu Su、Nabil Aouf |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT |
| **发布时间** | 2026-07-28T13:52:12Z |
| **关键词** | `Multi-Agent` · `Planning` · `Fine-tuning` · `Simulation` |
| **原文链接** | [http://arxiv.org/abs/2607.25728v1](http://arxiv.org/abs/2607.25728v1) |

**📝 摘要概括：**

> 本文提出了一种将共享体素图世界模型与多智能体软行为批判（ MASAC ）控制器相结合的协作室内无人机制导框架。多架无人机将360度激光雷达观测融合到一个通用的世界框架占用图中，该占用图被转换为紧凑的鸟瞰图（ BEV ）表示，并作为自我对齐的本地作物提供给每个代理。结果表明，共享的体素映射表示提供了有效的…

</details>

<details>
<summary><b>13. Tools Are Not Islands: Set-Level Tool Retrieval for LLM Agents via Query-Conditioned Hyperedge Prediction</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Xinyi Hong、Pinjun Dong、Xinyang Yu、Binyan Jiang |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-07-28T13:45:08Z |
| **关键词** | `LLM Agent` · `Retrieval` |
| **原文链接** | [http://arxiv.org/abs/2607.25718v1](http://arxiv.org/abs/2607.25718v1) |

**📝 摘要概括：**

> 大型语言模型（ LLM ）代理越来越依赖于调用外部工具来完成真实世界的任务。工具检索在代理采取行动之前从数千个工具库中选择一个小的任务相关子集，因此已成为LLM代理管道的关键组成部分。除了域内设置之外， HYSET还支持零拍/少拍传输，以最少的……推广到保留的工具/类别和看不见的域。

</details>

<details>
<summary><b>14. OrchBench: Evaluating Multi-Agent Orchestration Plans in Isolation via Deterministic Simulation</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Zhenzhen Ren、Jiyan He、Xinpeng Zhang、Zhenxing Qian、Ke Han 等（共 8 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT |
| **发布时间** | 2026-07-28T12:43:34Z |
| **关键词** | `Multi-Agent` · `Benchmark` · `Evaluation` · `Simulation` · `Workflow` |
| **原文链接** | [http://arxiv.org/abs/2607.25656v1](http://arxiv.org/abs/2607.25656v1) |

**📝 摘要概括：**

> 复杂任务通常分解为可并行但相互依赖的子任务，使得编排对多代理系统（ MAS ）的性能至关重要。现有评估通常依赖于端到端执行，这会将编排计划质量与工作人员能力、工具可靠性和环境噪音混为一谈。这些结果使OrchBench成为比较和诊断多药剂的有效和可解释的基准……

</details>

<details>
<summary><b>15. F(AI)2R: Who Did What, and Who Checked? Verifiable AI Provenance as an Executable Skill</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Florian Krebs |
| **所属机构** | （详见原文） |
| **顶级机构标签** | FAIR、CAS、TRI |
| **发布时间** | 2026-07-28T12:17:53Z |
| **关键词** | `AI Agent` |
| **原文链接** | [http://arxiv.org/abs/2607.25637v1](http://arxiv.org/abs/2607.25637v1) |

**📝 摘要概括：**

> F (AI) 2R是AI在循环中的公平研究，两次： AI辅助创作通行证和每个人工制品的机器可读审计通行证。人工智能系统现在起草、重构和验证研究成果，但它们的贡献很少以人类或机器可以审计的形式记录。其生产中的每个活动、索赔和来源都以两个不变量记录在存储库的来源图中：无无父索赔和验证……

</details>

<details>
<summary><b>16. Beyond Epistemia: Epistemic Schizologia and Large Language Models as Techno-Semiotic Machines</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Federico Cabitza、Gianluca Colombo |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-07-28T11:57:59Z |
| **关键词** | `Evaluation` · `Embodied AI` |
| **原文链接** | [http://arxiv.org/abs/2607.25620v1](http://arxiv.org/abs/2607.25620v1) |

**📝 摘要概括：**

> Quattrociocchi及其同事警告说，大型语言模型的流畅输出可能允许语言合理性代替认识论评估，从而产生他们称之为“认识论”的病症：拥有知识而不进行通常需要判断的实践的经验。本文接受了这一诊断，但挑战了其解释框架，该框架比较了具体化的、社会性的坐姿……

</details>

## 🗄️ 历史归档

| 日期 | 论文数 | 报告链接 |
|------|--------|----------|
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
| 2026-06-29 | 0 篇 | [2026-06-29.md](daily/2026-06-29.md) |

## 🏛️ 顶级机构覆盖范围

覆盖超过 **70 个**顶级 AI 机构，包括：

- **科技公司：** Microsoft、Google DeepMind、OpenAI、Anthropic、Meta AI、NVIDIA、Baidu、Alibaba、ByteDance 等
- **北美顶级大学：** MIT、Stanford、CMU、UC Berkeley、Harvard、Princeton、Cornell、Caltech 等
- **中国顶级大学/机构：** 清华大学、北京大学、浙大、上交大、复旦、中科院、MSRA 等
- **欧洲/其他：** Oxford、Cambridge、ETH Zurich、Mila、NUS、KAIST 等

---

*由 [clawBot DailyFindings](https://github.com/Jacob-biu/clawBot) 自动维护 | 最后更新：2026-07-29 23:00 UTC*
