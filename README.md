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

## 📅 今日论文 — 2026-11-20　　[→ 查看完整报告](daily/2026-11-20.md)

> 共筛选出 **20** 篇论文 | 更新于 2026-11-20 02:52 UTC

### 论文目录与概要

| # | 论文标题 | 核心概要 | 来源机构 | 第一作者 |
|---|---------|---------|---------|--------|
| 1 | [When Should a Voice Agent Speak? End-of-Turn Detection in Tu…](http://arxiv.org/abs/2611.25489v1) | 如果语音代理在回复前等待一段固定的沉默时间，则要么会打断在说话过程中暂停的用户，要么会延迟回复已说完话的用户。本研究使用从土耳其双人视频通话的Real-TurnTurk语料库中提取的轮流结束和轮流内部… | Mila、NTU | Ahmet Tuğrul Bayrak |
| 2 | [A Wolf in Sheep's Pixels: Visual Camouflage Attacks via HDR …](http://arxiv.org/abs/2611.25469v1) | 图像可以通过自动化安全检查，同时向人类观看者显示有害内容。我们推出了 DRJanus，这是一种视觉伪装攻击，它利用了标准动态范围 (SDR) 处理与高动态范围 (HDR) 显示之间的差异。演示版可在此… | MIT、CAS | Qi Shen |
| 3 | [ChainAgent: Automated Chainable Vulnerability Discovery in P…](http://arxiv.org/abs/2611.25412v1) | 针对PHP Web应用程序的高影响攻击通常会将有限功能的漏洞与其他缺陷或预期行为串联起来。要发现这些链条，需要识别漏洞以及使能力组合成为可能的依赖关系。对30个真实世界的PHP应用程序进行的额外评估发… | MIT | Xinyi Wang |
| 4 | [Falsifiable Compositional Reasoning in Time Series Forecasti…](http://arxiv.org/abs/2611.25388v1) | 时间序列基础模型以及语言引导的分析代理在标准时间基准上实现了很高的准确性。然而，在历史验证分割中排名最高的模型，在非平稳状态转换中往往会表现出性能下降。因此，我们建议围绕可证伪的组合假设来制定时间序列… | MIT、HIT | Hao Xue |
| 5 | [Beyond Weight Updates: Evolving Agent Harnesses for Domain S…](http://arxiv.org/abs/2611.25380v1) | LLM 智能体的领域专业化通常被归结为一个权重更新问题：收集轨迹，运行强化学习（RL）或有监督微调（SFT），然后部署一个新的检查点。我们研究了一个互补的维度：在保持策略不变的情况下，演进\textb… | CAS | BoHao Chen |
| 6 | [Stop Going in Circles:Loop-Triggered Routing for System 1 De…](http://arxiv.org/abs/2611.25363v1) | 系统 1 决策模型（以 Jev 为代表）提供快速、低成本的行动选择，但现有的智能体集成并不能可靠地将这些局部优势转化为任务的完成。在执行过程中的某些时刻，智能体可能会反复选择相同的行动，而未能在实现目… | MIT | Zeming Yu |
| 7 | [AppSci-Bench: Can LLMs Build AI Agents and Make Them Better?](http://arxiv.org/abs/2611.25360v1) | 大型语言模型（LLM）越来越多地被用于驱动人工智能代理，也被用于构建人工智能代理。虽然许多基准测试评估了由大语言模型（LLM）驱动的智能体的质量，但很少有基准测试确定LLM在构建这些智能体方面的表现如… | CAS | Sanjari Srivastava |
| 8 | [FPGA-GEN: Target-Aware RTL Generation via HLS](http://arxiv.org/abs/2611.25351v1) | C/C++ 编译成功并不保证经过高层次综合 (HLS) 后的 FPGA 硬件是正确或高效的。FPGA-GEN 是一种自主 HLS-C 生成工作流，它将规范、就绪性、选择、修复和准入规则编码在显式任务合… | MIT | Luke Ztz Hu |
| 9 | [From FIPS to FPGA with LLM Agents: Measuring What Tests and …](http://arxiv.org/abs/2611.25339v1) | 随着LLM代理越来越多地生成RTL，并同时进行验证RTL的测试和审核，自我生成的证据对于值得信赖的硬件来说是一个薄弱的基础。我们介绍了我们的七阶段验证门控工作流程，该流程是在后量子设计移植过程中演变而… | MIT、CAS | Jungmin Park |
| 10 | [ReLay: Bidirectional Layout-Code Translation and Library Evo…](http://arxiv.org/abs/2611.25328v1) | 模拟布局生成器为设计重用和工艺迁移提供了可编程接口，但其覆盖范围受到手工库的限制。嵌入在完整布局中的设计者知识仍然隐含在其几何形状中，因此难以在可重用生成器库中捕捉到。Frontier LLM 代理使… | MIT、TRI | Minxing Chu |
| 11 | [Pandora's Toolbox Or Why Agent Safety Cannot Be Verified](http://arxiv.org/abs/2611.25325v1) | 目前的人工智能代理是通过将固定的语言模型与通用计算设备耦合起来构建的。我们表明，这种耦合使得安全性不可判定。我们还讨论了可以在实践中使用的宽松的安全概念。 | HIT | Mario Franco |
| 12 | [Keel: A Frontier Model Teaches a Vision-Language Model by Re…](http://arxiv.org/abs/2611.25257v1) | 前沿模型能否通过重写权重来修复视觉-语言模型（VLM）？Qwen3.5 等小型推理 VLM 需要进行此类修复：在思考模式下，它们会在许多图像问题上陷入循环，不断重复自己，直到达到令牌上限，耗尽所有预算… | MIT | Jiajun Fan |
| 13 | [From FAIR to AWARE: Data Readiness for Agentic AI in the Ear…](http://arxiv.org/abs/2611.25209v1) | 人工智能在地球科学领域正开始发挥作用：原型代理已经能够搜索档案、运行模拟和起草分析。科学数据是为具备专家判断力的研究人员整理的；不能假定自主代理能够提供这种判断力。我们概述了一条分阶段、可衡量的采用路… | FAIR | Ivan Kuznetsov |
| 14 | [When AI Analysts Disagree: Agentic Multiverse Analysis and t…](http://arxiv.org/abs/2611.25198v1) | 对观测数据的每项实证分析都基于数十个站得住脚的分析选择（“分叉”），而这些选择是读者看不到的。我们开发了一种自主多重宇宙分析（AMA）框架，使结论对这些选择的敏感性在大规模上变得可见，并将该框架定位为… | MIT、CAS | Ruijiang Gao |
| 15 | [From Self-Play RL to Constrained Control: Distilling DiffMPC…](http://arxiv.org/abs/2611.25197v1) | 自博弈强化学习（RL）可以产生强大的驾驶策略，但这些策略很难验证或解释。可微模型预测控制（DiffMPC）可以强制执行显式约束，但通常是通过模仿记录的数据或使用成本高昂的强化学习（RL）来进行训练。其… | MIT、TRI | Luca M. Hartmann |
| 16 | [EverydayBench: Evaluating Satisfactory Completion of Live Us…](http://arxiv.org/abs/2611.25146v1) | 从选择产品和规划行程到开展研究和创作作品，日常的数字任务都需要人工智能代理提供有用的结果，而不仅仅是检索网络信息。然而，在实时网络上评估这些结果具有挑战性，因为单个请求可能会得到多个有效结果，并且随着… | MIT、TRI | Fangrui Huang |
| 17 | [Forget Freely, Grep Later: Lossless, Index-Free Memory for L…](http://arxiv.org/abs/2611.25123v1) | 长时程LLM代理通常会超出其上下文窗口，迫使它们丢弃稍后可能需要的信息。现有的上下文管理策略依赖于摘要、掩码或结构化记忆，需要在知道未来需求之前就决定保留哪些内容或如何检索这些内容。我们的结果表明，纯… | MIT、TRI | Ziyan Yang |
| 18 | [DSFlow: A Neuro-Symbolic Data Workflow Agent with Statistica…](http://arxiv.org/abs/2611.25111v1) | 数据科学工作流程通常需要使用一些工具，而这些工具需要具备相当高的技术知识。大型语言模型（LLM）降低了这一障碍，但灵活的通用代理与统计控制的管道之间仍然存在差距。回归和聚类案例研究展示了 DSFlow… | CAS、TRI | Junfeng Nie |
| 19 | [BuggyMLE: Scaling Machine Learning Engineering Difficulty wi…](http://arxiv.org/abs/2611.25088v1) | 要使人工智能系统能够自主改进人工智能模型，就需要具备执行机器学习工程 (MLE) 能力的代理。在实践中，设计、训练和评估复杂模型需要修改多文件存储库，以重现结果、调试训练运行、集成数据集和移植框架。我… | MIT、TRI | John Wu |
| 20 | [FinVeriQA: Financial Research Agents for Question Answering:…](http://arxiv.org/abs/2611.25071v1) | 大型语言模型（LLM）能够撰写流畅的财务分析，但会误算比率、引用过时的价格，并以很高的置信度将问题导向错误的工具。我们探讨了在金融问答助手当中，哪个组件应该负责哪项工作，并使用 FinVeriQA 对… | NVIDIA、HIT | Meenakshi Rajpurohit |

### 论文详情

<details>
<summary><b>1. When Should a Voice Agent Speak? End-of-Turn Detection in Turkish</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Ahmet Tuğrul Bayrak、Fatma Nur Korkmaz、Mustafa Sertaç Türkel、Nur Yağmur Tuncer |
| **所属机构** | （详见原文） |
| **顶级机构标签** | Mila、NTU |
| **发布时间** | 2026-11-19T04:26:13Z |
| **关键词** | `Evaluation` · `Simulation` |
| **原文链接** | [http://arxiv.org/abs/2611.25489v1](http://arxiv.org/abs/2611.25489v1) |

**📝 摘要概括：**

> 如果语音代理在回复前等待一段固定的沉默时间，则要么会打断在说话过程中暂停的用户，要么会延迟回复已说完话的用户。本研究使用从土耳其双人视频通话的Real-TurnTurk语料库中提取的轮流结束和轮流内部停顿，来考察在沉默开始时的决策。在自动Whisper转录中，经过微调的模型仍比零样本模型更具优势。

</details>

<details>
<summary><b>2. A Wolf in Sheep's Pixels: Visual Camouflage Attacks via HDR Gain Maps</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Qi Shen、Yujia Gong、Yue Zhao、Tong Liu |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、CAS、NUS |
| **发布时间** | 2026-11-19T03:55:38Z |
| **关键词** | `RAG` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2611.25469v1](http://arxiv.org/abs/2611.25469v1) |

**📝 摘要概括：**

> 图像可以通过自动化安全检查，同时向人类观看者显示有害内容。我们推出了 DRJanus，这是一种视觉伪装攻击，它利用了标准动态范围 (SDR) 处理与高动态范围 (HDR) 显示之间的差异。演示版可在此处查看： https://qshen0629.github.io/DRJanus/

</details>

<details>
<summary><b>3. ChainAgent: Automated Chainable Vulnerability Discovery in PHP Web Applications</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Xinyi Wang、Yeting Li、Shizhe Cui、Jiaming Guo、Qin Mai 等（共 12 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT |
| **发布时间** | 2026-11-19T02:52:06Z |
| **关键词** | `Planning` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2611.25412v1](http://arxiv.org/abs/2611.25412v1) |

**📝 摘要概括：**

> 针对PHP Web应用程序的高影响攻击通常会将有限功能的漏洞与其他缺陷或预期行为串联起来。要发现这些链条，需要识别漏洞以及使能力组合成为可能的依赖关系。对30个真实世界的PHP应用程序进行的额外评估发现了20个漏洞和13条漏洞利用链，其中9条实现了远程代码执行（RCE）。

</details>

<details>
<summary><b>4. Falsifiable Compositional Reasoning in Time Series Forecasting</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Hao Xue |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、HIT、CAS |
| **发布时间** | 2026-11-19T02:34:09Z |
| **关键词** | `Reasoning` · `Benchmark` · `Chain-of-Thought` |
| **原文链接** | [http://arxiv.org/abs/2611.25388v1](http://arxiv.org/abs/2611.25388v1) |

**📝 摘要概括：**

> 时间序列基础模型以及语言引导的分析代理在标准时间基准上实现了很高的准确性。然而，在历史验证分割中排名最高的模型，在非平稳状态转换中往往会表现出性能下降。因此，我们建议围绕可证伪的组合假设来制定时间序列预测和推理方法，这些假设将神经元基元编码器、显式耦合约束以及……结合起来。

</details>

<details>
<summary><b>5. Beyond Weight Updates: Evolving Agent Harnesses for Domain Specialization</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | BoHao Chen |
| **所属机构** | （详见原文） |
| **顶级机构标签** | CAS |
| **发布时间** | 2026-11-19T02:20:06Z |
| **关键词** | `LLM Agent` · `Reasoning` · `Planning` · `Reinforcement Learning` · `Fine-tuning` |
| **原文链接** | [http://arxiv.org/abs/2611.25380v1](http://arxiv.org/abs/2611.25380v1) |

**📝 摘要概括：**

> LLM 智能体的领域专业化通常被归结为一个权重更新问题：收集轨迹，运行强化学习（RL）或有监督微调（SFT），然后部署一个新的检查点。我们研究了一个互补的维度：在保持策略不变的情况下，演进\textbf{agent harness}——系统提示、工具架构、技能库和规划脚手架。我们的结果将框架演进定位为一种实用、非破坏性的……

</details>

<details>
<summary><b>6. Stop Going in Circles:Loop-Triggered Routing for System 1 Decision Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Zeming Yu、Huamin Ma、Yingyu Chen、Yuan Sun、Peng Hu 等（共 6 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT |
| **发布时间** | 2026-11-19T02:01:59Z |
| **关键词** | `Reasoning` · `Planning` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2611.25363v1](http://arxiv.org/abs/2611.25363v1) |

**📝 摘要概括：**

> 系统 1 决策模型（以 Jev 为代表）提供快速、低成本的行动选择，但现有的智能体集成并不能可靠地将这些局部优势转化为任务的完成。在执行过程中的某些时刻，智能体可能会反复选择相同的行动，而未能在实现目标方面取得进展。同样的规则也提高了六个冻结决策模型的成功率。

</details>

<details>
<summary><b>7. AppSci-Bench: Can LLMs Build AI Agents and Make Them Better?</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Sanjari Srivastava、Manpreet Kaur、Cheng Chang、Sofía Ramós Anton、Oumaima Essamadi 等（共 10 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | CAS |
| **发布时间** | 2026-11-19T01:58:31Z |
| **关键词** | `AI Agent` · `Benchmark` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2611.25360v1](http://arxiv.org/abs/2611.25360v1) |

**📝 摘要概括：**

> 大型语言模型（LLM）越来越多地被用于驱动人工智能代理，也被用于构建人工智能代理。虽然许多基准测试评估了由大语言模型（LLM）驱动的智能体的质量，但很少有基准测试确定LLM在构建这些智能体方面的表现如何。基准代码可在此处获取： https://github.com/sanjari-orb/appsci-bench。

</details>

<details>
<summary><b>8. FPGA-GEN: Target-Aware RTL Generation via HLS</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Luke Ztz Hu、Zhihan Xiao、Zhe Zhao、John Imoleayo Adebisi、Han Gao 等（共 7 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT |
| **发布时间** | 2026-11-19T01:48:21Z |
| **关键词** | `Agentic` · `Simulation` · `Workflow` |
| **原文链接** | [http://arxiv.org/abs/2611.25351v1](http://arxiv.org/abs/2611.25351v1) |

**📝 摘要概括：**

> C/C++ 编译成功并不保证经过高层次综合 (HLS) 后的 FPGA 硬件是正确或高效的。FPGA-GEN 是一种自主 HLS-C 生成工作流，它将规范、就绪性、选择、修复和准入规则编码在显式任务合约和有界工具反馈循环中，用于候选级决策。在有针对性的 TensorCore 筛选中，选定的候选方案 3 的 CSynth 周期比 ge… 少 73.7%，LUT 少 14.6%。

</details>

<details>
<summary><b>9. From FIPS to FPGA with LLM Agents: Measuring What Tests and Reviews Miss in Post-Quantum Cryptographic Hardware</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Jungmin Park、Eunha Kim、Wooseop Kim、Seongjoon Cho、Byungho Cha |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、CAS、NTU |
| **发布时间** | 2026-11-19T01:25:35Z |
| **关键词** | `LLM Agent` · `Agentic` · `Simulation` · `Workflow` |
| **原文链接** | [http://arxiv.org/abs/2611.25339v1](http://arxiv.org/abs/2611.25339v1) |

**📝 摘要概括：**

> 随着LLM代理越来越多地生成RTL，并同时进行验证RTL的测试和审核，自我生成的证据对于值得信赖的硬件来说是一个薄弱的基础。我们介绍了我们的七阶段验证门控工作流程，该流程是在后量子设计移植过程中演变而来的。在这个流程中，只有在门控被证明能够在阴性对照和故障突变上失败时，该门控才会被计入，并且审核代理在提交之前会对工作进行审核。在本研究中，值得信赖的智能体硬件需要……

</details>

<details>
<summary><b>10. ReLay: Bidirectional Layout-Code Translation and Library Evolution for Reusable and Process-Portable Analog Design</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Minxing Chu、Quan Cheng、Anhang Li、Martins Atilla、Junyi Luo 等（共 8 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-11-19T01:02:41Z |
| **关键词** | `LLM Agent` · `RAG` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2611.25328v1](http://arxiv.org/abs/2611.25328v1) |

**📝 摘要概括：**

> 模拟布局生成器为设计重用和工艺迁移提供了可编程接口，但其覆盖范围受到手工库的限制。嵌入在完整布局中的设计者知识仍然隐含在其几何形状中，因此难以在可重用生成器库中捕捉到。Frontier LLM 代理使用 ReLay 生成新布局，与直接几何生成相比，每项已完成任务的 API 成本降低了 64-77%，且……

</details>

<details>
<summary><b>11. Pandora's Toolbox Or Why Agent Safety Cannot Be Verified</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Mario Franco、Carlos Gershenson |
| **所属机构** | （详见原文） |
| **顶级机构标签** | HIT |
| **发布时间** | 2026-11-19T01:00:38Z |
| **关键词** | — |
| **原文链接** | [http://arxiv.org/abs/2611.25325v1](http://arxiv.org/abs/2611.25325v1) |

**📝 摘要概括：**

> 目前的人工智能代理是通过将固定的语言模型与通用计算设备耦合起来构建的。我们表明，这种耦合使得安全性不可判定。我们还讨论了可以在实践中使用的宽松的安全概念。

</details>

<details>
<summary><b>12. Keel: A Frontier Model Teaches a Vision-Language Model by Rewriting Its Weights</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Jiajun Fan、Neil He、Bangji Yang、Qinglong Zheng、Ziwen Wang 等（共 9 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT |
| **发布时间** | 2026-11-18T22:41:26Z |
| **关键词** | `Agentic` · `Reasoning` · `RAG` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2611.25257v1](http://arxiv.org/abs/2611.25257v1) |

**📝 摘要概括：**

> 前沿模型能否通过重写权重来修复视觉-语言模型（VLM）？Qwen3.5 等小型推理 VLM 需要进行此类修复：在思考模式下，它们会在许多图像问题上陷入循环，不断重复自己，直到达到令牌上限，耗尽所有预算并失去答案。由于修复存在于权重中，因此它与预算强制相结合，在留出问题有利于它的情况下：在可用的最佳权重上，Keel具有……

</details>

<details>
<summary><b>13. From FAIR to AWARE: Data Readiness for Agentic AI in the Earth Sciences</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Ivan Kuznetsov、Dmitrii Pantiukhin、Sonja Hänzelmann、Fabian Wachsmann、Jonas Sølvsteen 等（共 8 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | FAIR |
| **发布时间** | 2026-11-18T21:36:17Z |
| **关键词** | `Agentic` · `Simulation` |
| **原文链接** | [http://arxiv.org/abs/2611.25209v1](http://arxiv.org/abs/2611.25209v1) |

**📝 摘要概括：**

> 人工智能在地球科学领域正开始发挥作用：原型代理已经能够搜索档案、运行模拟和起草分析。科学数据是为具备专家判断力的研究人员整理的；不能假定自主代理能够提供这种判断力。我们概述了一条分阶段、可衡量的采用路径，旨在减少隐性错误。

</details>

<details>
<summary><b>14. When AI Analysts Disagree: Agentic Multiverse Analysis and the Robustness of Empirical Research</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Ruijiang Gao、Steven Chong Xiao |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、CAS、TRI |
| **发布时间** | 2026-11-18T21:17:37Z |
| **关键词** | `Agentic` |
| **原文链接** | [http://arxiv.org/abs/2611.25198v1](http://arxiv.org/abs/2611.25198v1) |

**📝 摘要概括：**

> 对观测数据的每项实证分析都基于数十个站得住脚的分析选择（“分叉”），而这些选择是读者看不到的。我们开发了一种自主多重宇宙分析（AMA）框架，使结论对这些选择的敏感性在大规模上变得可见，并将该框架定位为人类专家的决策支持工具。我们讨论了该框架对信息系统中的复制政策和人工智能辅助同行评审的影响。

</details>

<details>
<summary><b>15. From Self-Play RL to Constrained Control: Distilling DiffMPC Students with DAgger</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Luca M. Hartmann、Parinaz Naghizadeh |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-11-18T21:17:04Z |
| **关键词** | `Reinforcement Learning` |
| **原文链接** | [http://arxiv.org/abs/2611.25197v1](http://arxiv.org/abs/2611.25197v1) |

**📝 摘要概括：**

> 自博弈强化学习（RL）可以产生强大的驾驶策略，但这些策略很难验证或解释。可微模型预测控制（DiffMPC）可以强制执行显式约束，但通常是通过模仿记录的数据或使用成本高昂的强化学习（RL）来进行训练。其蒸馏所用时间不超过教师训练时间的 30%。

</details>

<details>
<summary><b>16. EverydayBench: Evaluating Satisfactory Completion of Live User-Facing Digital Work</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Fangrui Huang、Bingyang Wang、Chuhan Li、Yijiang Li、Arpandeep Khatua 等（共 17 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-11-18T20:25:44Z |
| **关键词** | `AI Agent` · `Planning` · `Benchmark` · `Evaluation` · `Workflow` |
| **原文链接** | [http://arxiv.org/abs/2611.25146v1](http://arxiv.org/abs/2611.25146v1) |

**📝 摘要概括：**

> 从选择产品和规划行程到开展研究和创作作品，日常的数字任务都需要人工智能代理提供有用的结果，而不仅仅是检索网络信息。然而，在实时网络上评估这些结果具有挑战性，因为单个请求可能会得到多个有效结果，并且随着时间的推移，不断变化的网络信息可能会改变哪些结果仍然有效。这些发现共同凸显了……的难度。

</details>

<details>
<summary><b>17. Forget Freely, Grep Later: Lossless, Index-Free Memory for Long-Horizon LLM Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Ziyan Yang、Taiwei Shi、Jieyu Zhao |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-11-18T20:02:57Z |
| **关键词** | `LLM Agent` · `Reinforcement Learning` · `Retrieval` · `Evaluation` · `Memory` |
| **原文链接** | [http://arxiv.org/abs/2611.25123v1](http://arxiv.org/abs/2611.25123v1) |

**📝 摘要概括：**

> 长时程LLM代理通常会超出其上下文窗口，迫使它们丢弃稍后可能需要的信息。现有的上下文管理策略依赖于摘要、掩码或结构化记忆，需要在知道未来需求之前就决定保留哪些内容或如何检索这些内容。我们的结果表明，纯文本日志和grep提供了一种简单但具有竞争力的长时程代理记忆方法，无需……

</details>

<details>
<summary><b>18. DSFlow: A Neuro-Symbolic Data Workflow Agent with Statistical Diagnostic Guardrails</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Junfeng Nie、Xiaohui Chen |
| **所属机构** | （详见原文） |
| **顶级机构标签** | CAS、TRI |
| **发布时间** | 2026-11-18T19:48:14Z |
| **关键词** | `Planning` · `Workflow` |
| **原文链接** | [http://arxiv.org/abs/2611.25111v1](http://arxiv.org/abs/2611.25111v1) |

**📝 摘要概括：**

> 数据科学工作流程通常需要使用一些工具，而这些工具需要具备相当高的技术知识。大型语言模型（LLM）降低了这一障碍，但灵活的通用代理与统计控制的管道之间仍然存在差距。回归和聚类案例研究展示了 DSFlow 如何使用诊断证据来纠正方法选择，并将这些决策记录在可审计的报告中。

</details>

<details>
<summary><b>19. BuggyMLE: Scaling Machine Learning Engineering Difficulty with Bug Injection</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | John Wu、Rushi Qiang、Yuchen Zhuang、Guowang Li、Girish Narayanswamy 等（共 13 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-11-18T19:26:15Z |
| **关键词** | `RAG` · `Benchmark` · `Fine-tuning` |
| **原文链接** | [http://arxiv.org/abs/2611.25088v1](http://arxiv.org/abs/2611.25088v1) |

**📝 摘要概括：**

> 要使人工智能系统能够自主改进人工智能模型，就需要具备执行机器学习工程 (MLE) 能力的代理。在实践中，设计、训练和评估复杂模型需要修改多文件存储库，以重现结果、调试训练运行、集成数据集和移植框架。我们训练的模型实现了超越机器学习的迁移，使其 SWE-bench Lite 的解决率从 24% 提高到 33%，LiveCodeBench v6 的 pass@1 从……

</details>

<details>
<summary><b>20. FinVeriQA: Financial Research Agents for Question Answering: Routing, Retrieval, MCP Tool Use, and Provenance-Aware Evidence Verification</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Meenakshi Rajpurohit、Anna Phan、Ravikumar Komandur Narayanan、Gunanidhi Ramakrishnan、Nathan Howland |
| **所属机构** | （详见原文） |
| **顶级机构标签** | NVIDIA、HIT、CAS |
| **发布时间** | 2026-11-18T19:13:45Z |
| **关键词** | `Multi-Agent` · `Retrieval` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2611.25071v1](http://arxiv.org/abs/2611.25071v1) |

**📝 摘要概括：**

> 大型语言模型（LLM）能够撰写流畅的财务分析，但会误算比率、引用过时的价格，并以很高的置信度将问题导向错误的工具。我们探讨了在金融问答助手当中，哪个组件应该负责哪项工作，并使用 FinVeriQA 对此进行了研究。FinVeriQA 是一个基于 SEC 备案文件和实时市场数据的开源多智能体研究原型：一个紧凑的类型化决策模型（Laya）负责将每个问题分派到相应组件，并筛除……

</details>

## 🗄️ 历史归档

| 日期 | 论文数 | 报告链接 |
|------|--------|----------|
| 2026-11-20 | 20 篇 | [2026-11-20.md](daily/2026-11-20.md) |
| 2026-11-05 | 13 篇 | [2026-11-05.md](daily/2026-11-05.md) |
| 2026-11-04 | 20 篇 | [2026-11-04.md](daily/2026-11-04.md) |
| 2026-11-03 | 0 篇 | [2026-11-03.md](daily/2026-11-03.md) |
| 2026-11-02 | 0 篇 | [2026-11-02.md](daily/2026-11-02.md) |
| 2026-11-01 | 0 篇 | [2026-11-01.md](daily/2026-11-01.md) |
| 2026-10-31 | 17 篇 | [2026-10-31.md](daily/2026-10-31.md) |
| 2026-10-30 | 0 篇 | [2026-10-30.md](daily/2026-10-30.md) |
| 2026-10-29 | 20 篇 | [2026-10-29.md](daily/2026-10-29.md) |
| 2026-10-28 | 20 篇 | [2026-10-28.md](daily/2026-10-28.md) |
| 2026-10-27 | 0 篇 | [2026-10-27.md](daily/2026-10-27.md) |
| 2026-10-25 | 0 篇 | [2026-10-25.md](daily/2026-10-25.md) |
| 2026-10-24 | 0 篇 | [2026-10-24.md](daily/2026-10-24.md) |
| 2026-10-23 | 20 篇 | [2026-10-23.md](daily/2026-10-23.md) |
| 2026-10-22 | 20 篇 | [2026-10-22.md](daily/2026-10-22.md) |
| 2026-10-21 | 20 篇 | [2026-10-21.md](daily/2026-10-21.md) |
| 2026-10-20 | 0 篇 | [2026-10-20.md](daily/2026-10-20.md) |
| 2026-10-18 | 0 篇 | [2026-10-18.md](daily/2026-10-18.md) |
| 2026-10-17 | 0 篇 | [2026-10-17.md](daily/2026-10-17.md) |
| 2026-10-16 | 8 篇 | [2026-10-16.md](daily/2026-10-16.md) |
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

## 🏛️ 顶级机构覆盖范围

覆盖超过 **70 个**顶级 AI 机构，包括：

- **科技公司：** Microsoft、Google DeepMind、OpenAI、Anthropic、Meta AI、NVIDIA、Baidu、Alibaba、ByteDance 等
- **北美顶级大学：** MIT、Stanford、CMU、UC Berkeley、Harvard、Princeton、Cornell、Caltech 等
- **中国顶级大学/机构：** 清华大学、北京大学、浙大、上交大、复旦、中科院、MSRA 等
- **欧洲/其他：** Oxford、Cambridge、ETH Zurich、Mila、NUS、KAIST 等

---

*由 [clawBot DailyFindings](https://github.com/Jacob-biu/clawBot) 自动维护 | 最后更新：2026-11-20 02:52 UTC*
