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

## 📅 今日论文 — 2026-08-13　　[→ 查看完整报告](daily/2026-08-13.md)

> 共筛选出 **19** 篇论文 | 更新于 2026-08-13 22:39 UTC

### 论文目录与概要

| # | 论文标题 | 核心概要 | 来源机构 | 第一作者 |
|---|---------|---------|---------|--------|
| 1 | [DreamFly: Causal Memory and Receding-Horizon Diffusion Plann…](http://arxiv.org/abs/2608.12308v1) | 空中视觉语言导航（ VLN ）要求具体的代理随着时间的推移集成视觉证据，计划未来的行动，并确定它何时达到部分可观测性的导航目标。虽然最近的VLA模型提供了一个有希望的感知到行动范式，但由于历史背景有限… | MIT、TRI | Yan Deng |
| 2 | [Beyond Trial-and-Error: Agentic Optimization for Image-to-Vi…](http://arxiv.org/abs/2608.12290v1) | 现代黑盒图像到视频（ I2V ）模型在自动内容创建方面提供了强大的功能，但它们缺乏精细的控制和可靠性，这给专业工作流程带来了重大挑战。它们固有的随机性导致文本提示或超参数的微小变化，从而产生截然不同的… | MIT、TRI | Aman Tyagi |
| 3 | [VAKRA: Evaluating Multi-Hop Reasoning Across APIs and Retrie…](http://arxiv.org/abs/2608.12282v1) | 部署在企业设置中的代理必须跨结构化API和文档集合进行推理，但现有基准会孤立地评估这些功能。我们引入了VAKRA （ e\ textbf {V} aluating\ textbf {A} PI和\ t… | HIT、TRI | Ankita Rajaram Naik |
| 4 | [Convergent Detour Hijacking: Task-Preserving Resource Amplif…](http://arxiv.org/abs/2608.12273v1) | 法学硕士代理越来越依赖于第三方技能，使用自然语言描述进行选择，使用教学机构进行规划。这种渐进式披露设计将两个连续的控制点暴露给不受信任的发布者：静态技能可能会将原本正确的任务引导到不必要的昂贵轨道上。… | HIT | Junliang Liu |
| 5 | [Diagram-MMU: A Multi-Modal Benchmark for Scientific Diagrams](http://arxiv.org/abs/2608.12262v1) | 多模态大型语言模型（ MLLM ）一直在提高科学写作和协作的能力。例如， OpenAI Prism是科学写作和协作的免费工作空间。项目页面： https://vi-ocean.github.io/pr… | OpenAI | Weihao Bo |
| 6 | [One Frozen Simulator Is Not Enough: Simulator Collapse in Mu…](http://arxiv.org/abs/2608.12253v1) | 用于人工智能交互的多智能体强化学习通常依赖于单个大型语言模型来模拟用户行为。我们表明，这种方法无法系统地推广，并追踪模拟器崩溃的故障：由于模拟器LLM是模式崩溃的，因此针对其训练的LLM策略过度拟合利… | Mila、TRI | Simon Yu |
| 7 | [An Agentic Workflow for Legacy HPC Modernization: Converting…](http://arxiv.org/abs/2608.12249v1) | 现代化遗留的Fortran是一个数量问题：转换是单独的例行公事，但代码库可能是巨大的，并且在许多计算科学中，这项工作根本无法完成。我们提出了一个代理工作流程，在生产规模上开展这项工作，我们着手衡量这种… | CAS、NTU | Yuzhong Shen |
| 8 | [VICBench: A Multi-Language Benchmark for Code Vulnerability …](http://arxiv.org/abs/2608.12246v1) | 评估安全漏洞检测工具需要具有漏洞诱导提交（ VIC ）的基准数据集-首先将漏洞引入代码库的提交。VIC对于确定所有易受攻击的软件版本至关重要。VICBench能够对漏洞检测方法进行稳健评估。 | MIT、TRI | Jin Lu |
| 9 | [GUIDE: Governed Unified Intelligence for Document-to-Artifac…](http://arxiv.org/abs/2608.12133v1) | 企业指南文档是异构、多模式的，结合了叙事文本、复杂表格和嵌入式图像。现有的LLM和VLM系统面临幻觉内容、表格结构退化以及缺乏从提取到验证和伪影生成的受管控工作流程。GUIDE对120份真实世界的企业… | HIT | Shivali Dalmia |
| 10 | [Do LLMs Take Care of Their Own? Similarity Signals Can Induc…](http://arxiv.org/abs/2608.12125v1) | 随着具有用户指导目标的基于LLM的代理越来越广泛地部署，他们越来越多地在战略互动中遇到彼此，并面临着寻找互利结果的挑战。先前的文献认为，在代理人知道他们遵循非常相似的决策模式的情况下，例如在单一文化的… | Mila | Akash Kundu |
| 11 | [Ready Cohorts: Bounding GPU Opportunity and Avoiding Host Ro…](http://arxiv.org/abs/2608.12123v1) | LLM-agent服务在模型和工具调用之间反复执行小的确定性转换：路由结果、更新状态并发出下一个效果。我们询问此控制路径何时为GPU执行提供足够的并发工作，以及当GPU计算的路由决策保留在设备上时会发… | MIT | Josef Liyanjun Chen |
| 12 | [No One to Blame: A Framework of Constitutive AI Unaccountabi…](http://arxiv.org/abs/2608.12104v1) | 自主、代理人工智能系统的日益增加的部署挑战了传统的问责机制。现有研究主要将人工智能问责制差距视为可以通过更好的标准、透明度和机构改革来克服的障碍。我们将人工智能不负责任重新构建为社会技术系统的组成属性… | TRI | Long Hoang Nguyen |
| 13 | [Better Slots, Better Worlds: Representation Quality & Robust…](http://arxiv.org/abs/2608.12078v1) | 从离线轨迹学习世界模型使客服代表能够通过规划完成不同的任务。以对象为中心（ OC ）的表示，将场景分解为一组绑定到其对象的槽，已被提出作为更具样本效率和更好泛化的世界模型的归纳偏差。我们发现（ i ）… | Mila、TRI | Shukrullo Nazirjonov |
| 14 | [Learning Loco-Manipulation From SMPC Demonstrations With Spa…](http://arxiv.org/abs/2608.12063v1) | 集成运动和操纵对机器人自主性至关重要，但将标准强化学习（ RL ）扩展到复杂任务受到密集奖励塑造的缓慢手动过程的严重瓶颈。为了绕过这一限制，我们在模拟中完全利用基于样本的模型预测控制（ SMPC ）作… | MIT、TRI | Martin Schuck |
| 15 | [Preference Tree Optimization: Enhancing Goal-Oriented Dialog…](http://arxiv.org/abs/2608.12062v1) | 开发能够进行多轮、以目标为导向的对话的对话系统仍然是一项重大挑战，特别是在数据有限的专业领域。本研究提出了一种名为偏好树优化（ PTO ）的新框架，旨在通过使用一种名为带有前瞻的偏好树的方法生成偏好数… | MIT、TRI | Lior Baruch |
| 16 | [Mechanist: AI as a Scientific Instrument for Discovering the…](http://arxiv.org/abs/2608.12036v1) | 人工智能模型在不同领域取得了显着的成功，但其能力背后的机制及其可能构成的风险仍然知之甚少。随着人工智能开发的速度越来越快，自动化程度越来越高，机械探索在很大程度上仍然是手动的，这扩大了模型可以做什么与… | NTU | Mengru Wang |
| 17 | [CTBench: Evaluating Troubleshooting Capabilities of AI Agent…](http://arxiv.org/abs/2608.12002v1) | 代理商越来越多地被考虑用于自动化网络运营和维护，工程师必须在严格限制下诊断网络故障、优化配置以增强服务并降低运营成本。然而，现有的评估未能准确地模拟真实的网络特性，或在具有不同供应商、设备、协议和接口… | TRI | Xingyu Yan |
| 18 | [Retry, Switch, or Abstain? Learning Strategy-Aware Tool-Use …](http://arxiv.org/abs/2608.11977v1) | 使用工具的LLM代理通常在工具调用可靠的环境中进行培训和评估，但部署的工具可能会暂时、持续或静默地失败。因此，强大的恢复需要的不仅仅是重复重试：代理可能需要重试相同的路径，切换到替代方案，或者认识到没… | TRI | Chaoran Chen |
| 19 | [LoongReflect: Boosting Long-Horizon Reflection in Search Age…](http://arxiv.org/abs/2608.11967v1) | 大型语言模型代理越来越依赖长距离推理来解决涉及规划、工具使用和内存的复杂任务。在这种情况下，一种关键能力是反思：评估轨迹进展，识别缺失的证据和不可靠的中间状态，并决定是否继续、修改或放弃当前的分支机构… | TRI | Zhixin Zhang |

### 论文详情

<details>
<summary><b>1. DreamFly: Causal Memory and Receding-Horizon Diffusion Planning for Aerial Vision-Language Navigation</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Yan Deng、Fei Xu |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-08-12T17:54:33Z |
| **关键词** | `Reasoning` · `Planning` · `Benchmark` · `Embodied AI` · `Memory` |
| **原文链接** | [http://arxiv.org/abs/2608.12308v1](http://arxiv.org/abs/2608.12308v1) |

**📝 摘要概括：**

> 空中视觉语言导航（ VLN ）要求具体的代理随着时间的推移集成视觉证据，计划未来的行动，并确定它何时达到部分可观测性的导航目标。虽然最近的VLA模型提供了一个有希望的感知到行动范式，但由于历史背景有限，规划视野短，以及不可靠的隐式终止，使它们适应空中导航仍然具有挑战性。这些结果......

</details>

<details>
<summary><b>2. Beyond Trial-and-Error: Agentic Optimization for Image-to-Video Adherence</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Aman Tyagi、Hemanth Boinpally、Jonathan Chen、Douglas Gebert、Steven Hickson |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-08-12T17:35:16Z |
| **关键词** | `Agentic` · `Evaluation` · `Workflow` |
| **原文链接** | [http://arxiv.org/abs/2608.12290v1](http://arxiv.org/abs/2608.12290v1) |

**📝 摘要概括：**

> 现代黑盒图像到视频（ I2V ）模型在自动内容创建方面提供了强大的功能，但它们缺乏精细的控制和可靠性，这给专业工作流程带来了重大挑战。它们固有的随机性导致文本提示或超参数的微小变化，从而产生截然不同的输出，通常需要低效的蛮力试错过程。这项工作提供了一个实用的……

</details>

<details>
<summary><b>3. VAKRA: Evaluating Multi-Hop Reasoning Across APIs and Retrieval Under Tool-Use Policies</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Ankita Rajaram Naik、Anupama Murthi、Benjamin Elder、Siyu Huo、Raavi Gupta 等（共 9 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | HIT、TRI |
| **发布时间** | 2026-08-12T17:27:27Z |
| **关键词** | `Reasoning` · `Retrieval` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2608.12282v1](http://arxiv.org/abs/2608.12282v1) |

**📝 摘要概括：**

> 部署在企业设置中的代理必须跨结构化API和文档集合进行推理，但现有基准会孤立地评估这些功能。我们引入了VAKRA （ e\ textbf {V} aluating\ textbf {A} PI和\ textbf {K} nowledge\ textbf {R} etrieval\ textbf {A} gents ） ，这是一个跨$ 62 $域的超过$ 8 {,} 000 $可执行API的基准，其任务跨越了三个难度增加的设置：多样化的API交互风格，多跳re...

</details>

<details>
<summary><b>4. Convergent Detour Hijacking: Task-Preserving Resource Amplification in Skill-Based LLM Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Junliang Liu、Ruoyu Li、Wenxin Tang、Jingyu Xiao、Zhenyu Liu 等（共 7 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | HIT |
| **发布时间** | 2026-08-12T17:12:49Z |
| **关键词** | `LLM Agent` · `Planning` |
| **原文链接** | [http://arxiv.org/abs/2608.12273v1](http://arxiv.org/abs/2608.12273v1) |

**📝 摘要概括：**

> 法学硕士代理越来越依赖于第三方技能，使用自然语言描述进行选择，使用教学机构进行规划。这种渐进式披露设计将两个连续的控制点暴露给不受信任的发布者：静态技能可能会将原本正确的任务引导到不必要的昂贵轨道上。因此，正确的结果并不能保证轨迹完整性或成本安全。

</details>

<details>
<summary><b>5. Diagram-MMU: A Multi-Modal Benchmark for Scientific Diagrams</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Weihao Bo、Shan Zhang、Yanpeng Sun、Jie Liu、Yongke Yao 等（共 10 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | OpenAI |
| **发布时间** | 2026-08-12T17:04:13Z |
| **关键词** | `Agentic` · `Benchmark` · `Evaluation` · `Code Generation` |
| **原文链接** | [http://arxiv.org/abs/2608.12262v1](http://arxiv.org/abs/2608.12262v1) |

**📝 摘要概括：**

> 多模态大型语言模型（ MLLM ）一直在提高科学写作和协作的能力。例如， OpenAI Prism是科学写作和协作的免费工作空间。项目页面： https://vi-ocean.github.io/projects/diagram-mmu。

</details>

<details>
<summary><b>6. One Frozen Simulator Is Not Enough: Simulator Collapse in Multi-Agent RL</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Simon Yu、Nicholas Tomlin、Marwa Abdulhai、Ximing Lu、Derek Chong 等（共 10 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | Mila、TRI |
| **发布时间** | 2026-08-12T16:55:50Z |
| **关键词** | `Multi-Agent` · `Reinforcement Learning` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2608.12253v1](http://arxiv.org/abs/2608.12253v1) |

**📝 摘要概括：**

> 用于人工智能交互的多智能体强化学习通常依赖于单个大型语言模型来模拟用户行为。我们表明，这种方法无法系统地推广，并追踪模拟器崩溃的故障：由于模拟器LLM是模式崩溃的，因此针对其训练的LLM策略过度拟合利用模拟器的主导模式的狭隘策略，并且这种策略很难转移到看不见的模拟中……

</details>

<details>
<summary><b>7. An Agentic Workflow for Legacy HPC Modernization: Converting the Two-Electron-Integral Core of GAMESS</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Yuzhong Shen、Masha Sosonkina、Peng Xu、Mark S. Gordon |
| **所属机构** | （详见原文） |
| **顶级机构标签** | CAS、NTU |
| **发布时间** | 2026-08-12T16:48:47Z |
| **关键词** | `Agentic` · `Workflow` |
| **原文链接** | [http://arxiv.org/abs/2608.12249v1](http://arxiv.org/abs/2608.12249v1) |

**📝 摘要概括：**

> 现代化遗留的Fortran是一个数量问题：转换是单独的例行公事，但代码库可能是巨大的，并且在许多计算科学中，这项工作根本无法完成。我们提出了一个代理工作流程，在生产规模上开展这项工作，我们着手衡量这种委托可以达到多远。所有十二个源文件都通过了51次测试验证电池，包括49次标准GAMESS测试和两次添加……

</details>

<details>
<summary><b>8. VICBench: A Multi-Language Benchmark for Code Vulnerability Detection</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Jin Lu、Xuening Han、Yang Zhong、Lin Tan、Kevin Luo 等（共 7 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-08-12T16:45:49Z |
| **关键词** | `Agentic` · `RAG` · `Benchmark` · `Evaluation` · `Workflow` |
| **原文链接** | [http://arxiv.org/abs/2608.12246v1](http://arxiv.org/abs/2608.12246v1) |

**📝 摘要概括：**

> 评估安全漏洞检测工具需要具有漏洞诱导提交（ VIC ）的基准数据集-首先将漏洞引入代码库的提交。VIC对于确定所有易受攻击的软件版本至关重要。VICBench能够对漏洞检测方法进行稳健评估。

</details>

<details>
<summary><b>9. GUIDE: Governed Unified Intelligence for Document-to-Artifact Generation in Enterprise Settings</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Shivali Dalmia、Sumukha Thoppanahalli、Mohammadreza Sediqin、Abhishek Mukherji |
| **所属机构** | （详见原文） |
| **顶级机构标签** | HIT |
| **发布时间** | 2026-08-12T14:52:33Z |
| **关键词** | `Multi-Agent` · `Evaluation` · `Workflow` |
| **原文链接** | [http://arxiv.org/abs/2608.12133v1](http://arxiv.org/abs/2608.12133v1) |

**📝 摘要概括：**

> 企业指南文档是异构、多模式的，结合了叙事文本、复杂表格和嵌入式图像。现有的LLM和VLM系统面临幻觉内容、表格结构退化以及缺乏从提取到验证和伪影生成的受管控工作流程。GUIDE对120份真实世界的企业指南文档进行了评估，取得了96%的文档成功率，提取了3,896条规则，其中71.4%为自动批准……

</details>

<details>
<summary><b>10. Do LLMs Take Care of Their Own? Similarity Signals Can Induce Cooperation</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Akash Kundu、Emanuel Tewolde、Ratip Emin Berker、Samuel F. Brown、Vincent Conitzer |
| **所属机构** | （详见原文） |
| **顶级机构标签** | Mila |
| **发布时间** | 2026-08-12T14:47:15Z |
| **关键词** | `Reasoning` · `Chain-of-Thought` |
| **原文链接** | [http://arxiv.org/abs/2608.12125v1](http://arxiv.org/abs/2608.12125v1) |

**📝 摘要概括：**

> 随着具有用户指导目标的基于LLM的代理越来越广泛地部署，他们越来越多地在战略互动中遇到彼此，并面临着寻找互利结果的挑战。先前的文献认为，在代理人知道他们遵循非常相似的决策模式的情况下，例如在单一文化的人工智能生态系统中，囚犯困境等合作问题是可以解决的。最后，我们开发……

</details>

<details>
<summary><b>11. Ready Cohorts: Bounding GPU Opportunity and Avoiding Host Round Trips in LLM-Agent Control</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Josef Liyanjun Chen |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT |
| **发布时间** | 2026-08-12T14:42:15Z |
| **关键词** | — |
| **原文链接** | [http://arxiv.org/abs/2608.12123v1](http://arxiv.org/abs/2608.12123v1) |

**📝 摘要概括：**

> LLM-agent服务在模型和工具调用之间反复执行小的确定性转换：路由结果、更新状态并发出下一个效果。我们询问此控制路径何时为GPU执行提供足够的并发工作，以及当GPU计算的路由决策保留在设备上时会发生什么变化。需要联接的有限在线运行时来衡量A、CPU位移和服务级别优势。

</details>

<details>
<summary><b>12. No One to Blame: A Framework of Constitutive AI Unaccountability</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Long Hoang Nguyen、Eva Späthe、Sebastian Lins、Ali Sunyaev |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-08-12T14:25:05Z |
| **关键词** | `AI Agent` · `Agentic` |
| **原文链接** | [http://arxiv.org/abs/2608.12104v1](http://arxiv.org/abs/2608.12104v1) |

**📝 摘要概括：**

> 自主、代理人工智能系统的日益增加的部署挑战了传统的问责机制。现有研究主要将人工智能问责制差距视为可以通过更好的标准、透明度和机构改革来克服的障碍。我们将人工智能不负责任重新构建为社会技术系统的组成属性，扩展了问责制的四个障碍，并提供了实用的指导……

</details>

<details>
<summary><b>13. Better Slots, Better Worlds: Representation Quality & Robustness in Object-Centric World Models</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Shukrullo Nazirjonov、Sai Prasanna、Anna Manasyan、Georg Martius |
| **所属机构** | （详见原文） |
| **顶级机构标签** | Mila、TRI |
| **发布时间** | 2026-08-12T14:02:36Z |
| **关键词** | `Planning` |
| **原文链接** | [http://arxiv.org/abs/2608.12078v1](http://arxiv.org/abs/2608.12078v1) |

**📝 摘要概括：**

> 从离线轨迹学习世界模型使客服代表能够通过规划完成不同的任务。以对象为中心（ OC ）的表示，将场景分解为一组绑定到其对象的槽，已被提出作为更具样本效率和更好泛化的世界模型的归纳偏差。我们发现（ i ）规划成功与无监督时隙质量指标（ FG-ARI ， MBO ）呈正相关，尽管......

</details>

<details>
<summary><b>14. Learning Loco-Manipulation From SMPC Demonstrations With Sparse Offline-to-Online RL</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Martin Schuck、Maks Sorokin、Simone Manni、Duy Ta、Angela P. Schoellig 等（共 8 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-08-12T13:48:56Z |
| **关键词** | `Reinforcement Learning` · `RAG` · `Simulation` |
| **原文链接** | [http://arxiv.org/abs/2608.12063v1](http://arxiv.org/abs/2608.12063v1) |

**📝 摘要概括：**

> 集成运动和操纵对机器人自主性至关重要，但将标准强化学习（ RL ）扩展到复杂任务受到密集奖励塑造的缓慢手动过程的严重瓶颈。为了绕过这一限制，我们在模拟中完全利用基于样本的模型预测控制（ SMPC ）作为自动化、快速可调的专家来生成大量离线数据集。我们验证了这个sim-to-real f的稳健性……

</details>

<details>
<summary><b>15. Preference Tree Optimization: Enhancing Goal-Oriented Dialogue with Look-Ahead Simulations</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Lior Baruch、Moshe Butman、Kfir Bar、Doron Friedman |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-08-12T13:48:30Z |
| **关键词** | `Planning` · `RAG` · `Evaluation` · `Simulation` |
| **原文链接** | [http://arxiv.org/abs/2608.12062v1](http://arxiv.org/abs/2608.12062v1) |

**📝 摘要概括：**

> 开发能够进行多轮、以目标为导向的对话的对话系统仍然是一项重大挑战，特别是在数据有限的专业领域。本研究提出了一种名为偏好树优化（ PTO ）的新框架，旨在通过使用一种名为带有前瞻的偏好树的方法生成偏好数据来迭代改进此类对话系统中的Agent模型。此外，融入外观……

</details>

<details>
<summary><b>16. Mechanist: AI as a Scientific Instrument for Discovering the Mechanisms of Intelligence</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Mengru Wang、Junfeng Fang、Shuofei Qiao、Zhenqian Xu、Haoming Xu 等（共 19 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | NTU |
| **发布时间** | 2026-08-12T13:19:42Z |
| **关键词** | `Agentic` |
| **原文链接** | [http://arxiv.org/abs/2608.12036v1](http://arxiv.org/abs/2608.12036v1) |

**📝 摘要概括：**

> 人工智能模型在不同领域取得了显着的成功，但其能力背后的机制及其可能构成的风险仍然知之甚少。随着人工智能开发的速度越来越快，自动化程度越来越高，机械探索在很大程度上仍然是手动的，这扩大了模型可以做什么与我们理解和控制它们的能力之间的差距。最后， Mechanist将这些机械的见解转化为实际的间隔……

</details>

<details>
<summary><b>17. CTBench: Evaluating Troubleshooting Capabilities of AI Agents in Realistic Telecom Network Operations</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Xingyu Yan、Tingting Dai、Antonio De Domenico、Mohamed Sana、Nicola Piovesan 等（共 19 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-08-12T12:37:02Z |
| **关键词** | `AI Agent` · `Benchmark` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2608.12002v1](http://arxiv.org/abs/2608.12002v1) |

**📝 摘要概括：**

> 代理商越来越多地被考虑用于自动化网络运营和维护，工程师必须在严格限制下诊断网络故障、优化配置以增强服务并降低运营成本。然而，现有的评估未能准确地模拟真实的网络特性，或在具有不同供应商、设备、协议和接口的部分可观察到的电信环境中评估代理……

</details>

<details>
<summary><b>18. Retry, Switch, or Abstain? Learning Strategy-Aware Tool-Use Policies via Controlled Error Injection</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Chaoran Chen、Vy Nguyen、Ziji Zhang、Abhinav Gullapalli、Ziyi Wang 等（共 10 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-08-12T12:08:39Z |
| **关键词** | `LLM Agent` · `Reinforcement Learning` · `Benchmark` · `Memory` |
| **原文链接** | [http://arxiv.org/abs/2608.11977v1](http://arxiv.org/abs/2608.11977v1) |

**📝 摘要概括：**

> 使用工具的LLM代理通常在工具调用可靠的环境中进行培训和评估，但部署的工具可能会暂时、持续或静默地失败。因此，强大的恢复需要的不仅仅是重复重试：代理可能需要重试相同的路径，切换到替代方案，或者认识到没有可行的路径。这些结果表明，强大的工具使用结合特定环境的恢复知识的好处……

</details>

<details>
<summary><b>19. LoongReflect: Boosting Long-Horizon Reflection in Search Agents via Global Perspective Distillation</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Zhixin Zhang、Xinke Jiang、Zhibang Yang、Weixuan Xu、Guohong Qiu 等（共 8 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-08-12T11:56:03Z |
| **关键词** | `Reasoning` · `Planning` · `Reinforcement Learning` · `RAG` · `Retrieval` |
| **原文链接** | [http://arxiv.org/abs/2608.11967v1](http://arxiv.org/abs/2608.11967v1) |

**📝 摘要概括：**

> 大型语言模型代理越来越依赖长距离推理来解决涉及规划、工具使用和内存的复杂任务。在这种情况下，一种关键能力是反思：评估轨迹进展，识别缺失的证据和不可靠的中间状态，并决定是否继续、修改或放弃当前的分支机构。多跳检索增强生成和数学推理基准实验…

</details>

## 🗄️ 历史归档

| 日期 | 论文数 | 报告链接 |
|------|--------|----------|
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
| 2026-07-31 | 20 篇 | [2026-07-31.md](daily/2026-07-31.md) |
| 2026-07-30 | 16 篇 | [2026-07-30.md](daily/2026-07-30.md) |
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

## 🏛️ 顶级机构覆盖范围

覆盖超过 **70 个**顶级 AI 机构，包括：

- **科技公司：** Microsoft、Google DeepMind、OpenAI、Anthropic、Meta AI、NVIDIA、Baidu、Alibaba、ByteDance 等
- **北美顶级大学：** MIT、Stanford、CMU、UC Berkeley、Harvard、Princeton、Cornell、Caltech 等
- **中国顶级大学/机构：** 清华大学、北京大学、浙大、上交大、复旦、中科院、MSRA 等
- **欧洲/其他：** Oxford、Cambridge、ETH Zurich、Mila、NUS、KAIST 等

---

*由 [clawBot DailyFindings](https://github.com/Jacob-biu/clawBot) 自动维护 | 最后更新：2026-08-13 22:39 UTC*
