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

## 📅 今日论文 — 2026-05-07　　[→ 查看完整报告](daily/2026-05-07.md)

> 共筛选出 **13** 篇论文 | 更新于 2026-05-07 23:03 UTC

### 论文目录与概要

| # | 论文标题 | 核心概要 | 来源机构 | 第一作者 |
|---|---------|---------|---------|--------|
| 1 | [Design Conductor 2.0: An agent builds a TurboQuant inference…](http://arxiv.org/abs/2605.05170v1) | 在线束和基础模型的快速共同发展的推动下， LLM代理商正在以令人眼花缭乱的速度进步。在我们之前的工作中（在12月进行。最后，我们分析了Design Conductor的代币使用和其他经验特征，包括其局… | MIT | The Verkor Team |
| 2 | [Rollout Pass-Rate Control: Steering Binary-Reward RL Toward …](http://arxiv.org/abs/2605.05112v1) | SWE-bench风格的代理强化学习依赖于昂贵的有状态轨迹，但大量计算浪费在具有偏斜通过率的抽样推出组上，其中二进制奖励提供微弱的对比信号。我们将这种低效率视为合格率控制问题，并表明50%的合格率是最… | TRI | Tianshu Zhu |
| 3 | [Graph-SND: Sparse Aggregation for Behavioral Diversity in Mu…](http://arxiv.org/abs/2605.05020v1) | 系统神经多样性（ SND ）通过对所有$\ binom {n} {2} $座席对的成对距离进行平均来衡量多座席强化学习中的行为异质性，使每个呼叫在团队规模上呈二次型。我们引入了Graph-SND ，它… | TRI | Shawn Ray |
| 4 | [Uno-Orchestra: Parsimonious Agent Routing via Selective Dele…](http://arxiv.org/abs/2605.05007v1) | 大型语言模型（ LLM ）多智能体系统通常依赖于僵化的编排，致力于平坦的每个查询路由或手工设计的任务分解，因此分解深度、工作者选择和推理预算不会在一个目标下联合优化。我们引入了Uno-Orchestr… | MIT | Zhiqing Cui |
| 5 | [Agentic Vulnerability Reasoning on Windows COM Binaries](http://arxiv.org/abs/2605.05000v1) | Windows组件对象模型(COM)服务以升级权限运行，并可供经过身份验证的用户广泛访问，这使得这些二进制文件中的竞争条件成为本地权限提升的关键表面。我们展示了SLYP ，这是一个端到端的代理流水线，… | Microsoft、CAS | Hwiwon Lee |
| 6 | [Adaptivity Under Realizability Constraints: Comparing In-Con…](http://arxiv.org/abs/2605.04995v1) | 我们将上下文学习与固定查询进行比较，并将代理学习与自适应查询进行比较，以实现任务族的统一逼近。我们考虑两种设置：不受限制的制度，其中查询和逼近是任意函数，以及可实现的制度，其中我们要求这些操作由ReL… | TRI | Anastasis Kratsios |
| 7 | [Self-Induced Outcome Potential: Turn-Level Credit Assignment…](http://arxiv.org/abs/2605.04984v1) | 长期LLM代理依赖于中间信息收集轮次，但培训反馈通常仅在最终答案中观察到，因为流程级别的奖励需要高质量的人工注释。现有的回合级塑造方法奖励增加金牌答案可能性的回合，但它们需要答案监督或稳定的特定任务验… | MIT、CAS | Senkang Hu |
| 8 | [Architectural Constraints Alignment in AI-assisted, Platform…](http://arxiv.org/abs/2605.04973v1) | 人工智能辅助开发工具可实现服务的快速原型设计，但往往缺乏对生产环境中所需的架构约束、基础设施依赖性和组织标准的认识。因此，生成的伪影可能表现出脆性行为和有限的可部署性。评估表明，与通用AI代码生成工作… | MIT、HIT | Julius Irion |
| 9 | [Modular Reinforcement Learning For Cooperative Swarms](http://arxiv.org/abs/2605.04939v1) | 协作机器人群是具有共同目标的计算受限机器人的集合。每个机器人只能与其同行的一小部分进行交互，而不知道这会如何影响集体效用。我们在许多模拟机器人群进行觅食的实验中证明了该方法的有效性。 | MIT、TRI | Erel Shtossel |
| 10 | [Evolving Idea Graphs with Learnable Edits-and-Commits for Mu…](http://arxiv.org/abs/2605.04922v1) | 法学硕士授权的多代理系统通过产生新颖的研究理念，为加速科学发现提供了新的潜力。但是，现有方法通常通过临时文本（如草稿或聊天日志）协调客服代表；很难确定生成的创意中的弱点以及客服代表如何完善它们。消融进… | MIT、TRI | Jiangwen Dong |
| 11 | [Storage Is Not Memory: A Retrieval-Centered Architecture for…](http://arxiv.org/abs/2605.04897v1) | 对于代理内存而言，摄取时的提取是错误的原语：在已知查询之前丢弃的内容无法在检索时恢复。我们提出了True Memory ，这是一种六层架构，可将系统的中心从存储架构转移到逐字保留事件的多级检索管道。5… | MIT、HIT | Joshua Adler |
| 12 | [To Fuse or to Drop? Dual-Path Learning for Resolving Modalit…](http://arxiv.org/abs/2605.04877v1) | 多模态情感识别（ MER ）受益于文本、音频和视觉的组合，但当模态冲突时，标准融合通常会失败。至关重要的是，冲突的可解决性各不相同：良性冲突源于缺失、弱或模棱两可的线索，可以通过跨模式校准来缓解，而严… | MIT、CAS | Yangchen Yu |
| 13 | [DecodingTrust-Agent Platform (DTap): A Controllable and Inte…](http://arxiv.org/abs/2605.04808v1) | 人工智能代理越来越多地部署在不同的领域，通过长期和高风险的操作执行来自动化复杂的工作流程。由于其高能力和灵活性，此类代理商引发了重大的安全和安保问题。通过DTap ，我们对基于各种骨干模型、跨越安全策… | Google | Zhaorun Chen |

### 论文详情

<details>
<summary><b>1. Design Conductor 2.0: An agent builds a TurboQuant inference accelerator in 80 hours</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | The Verkor Team、Ravi Krishna、Suresh Krishna、David Chin |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT |
| **发布时间** | 2026-05-06T17:40:03Z |
| **关键词** | `Multi-Agent` · `LLM Agent` |
| **原文链接** | [http://arxiv.org/abs/2605.05170v1](http://arxiv.org/abs/2605.05170v1) |

**📝 摘要概括：**

> 在线束和基础模型的快速共同发展的推动下， LLM代理商正在以令人眼花缭乱的速度进步。在我们之前的工作中（在12月进行。最后，我们分析了Design Conductor的代币使用和其他经验特征，包括其局限性。

</details>

<details>
<summary><b>2. Rollout Pass-Rate Control: Steering Binary-Reward RL Toward Its Most Informative Regime</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Tianshu Zhu、Wenyu Zhang、Xiaoying Zuo、Lun Tian、Haotian Zhao 等（共 11 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-05-06T16:44:38Z |
| **关键词** | `Agentic` · `Reasoning` · `Reinforcement Learning` · `RAG` |
| **原文链接** | [http://arxiv.org/abs/2605.05112v1](http://arxiv.org/abs/2605.05112v1) |

**📝 摘要概括：**

> SWE-bench风格的代理强化学习依赖于昂贵的有状态轨迹，但大量计算浪费在具有偏斜通过率的抽样推出组上，其中二进制奖励提供微弱的对比信号。我们将这种低效率视为合格率控制问题，并表明50%的合格率是最具信息性的操作点：它最大化了奖励熵、幸存组过滤的概率、RLOO优势……

</details>

<details>
<summary><b>3. Graph-SND: Sparse Aggregation for Behavioral Diversity in Multi-Agent Reinforcement Learning</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Shawn Ray |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-05-06T15:18:42Z |
| **关键词** | `Multi-Agent` · `Reinforcement Learning` · `RAG` |
| **原文链接** | [http://arxiv.org/abs/2605.05020v1](http://arxiv.org/abs/2605.05020v1) |

**📝 摘要概括：**

> 系统神经多样性（ SND ）通过对所有$\ binom {n} {2} $座席对的成对距离进行平均来衡量多座席强化学习中的行为异质性，使每个呼叫在团队规模上呈二次型。我们引入了Graph-SND ，它在任意图$ G $的边上用加权平均值代替了这个完全图平均值。总之，这些结果表明，在不改变度量的情况下，可以消除SND聚合瓶颈。

</details>

<details>
<summary><b>4. Uno-Orchestra: Parsimonious Agent Routing via Selective Delegation</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Zhiqing Cui、Haotong Xie、Jiahao Yuan、Cheng Yang、Hanqing Wang 等（共 14 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT |
| **发布时间** | 2026-05-06T15:07:14Z |
| **关键词** | `Multi-Agent` · `Agentic` · `Benchmark` · `Workflow` |
| **原文链接** | [http://arxiv.org/abs/2605.05007v1](http://arxiv.org/abs/2605.05007v1) |

**📝 摘要概括：**

> 大型语言模型（ LLM ）多智能体系统通常依赖于僵化的编排，致力于平坦的每个查询路由或手工设计的任务分解，因此分解深度、工作者选择和推理预算不会在一个目标下联合优化。我们引入了Uno-Orchestra ，这是一种统一的编排策略，可以选择性地分解任务，并将每个子任务分配给可接受的（模型，原始）对，并具有以下功能：

</details>

<details>
<summary><b>5. Agentic Vulnerability Reasoning on Windows COM Binaries</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Hwiwon Lee、Jongseong Kim、Lingming Zhang |
| **所属机构** | （详见原文） |
| **顶级机构标签** | Microsoft、CAS |
| **发布时间** | 2026-05-06T15:00:52Z |
| **关键词** | `Agentic` · `Reasoning` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2605.05000v1](http://arxiv.org/abs/2605.05000v1) |

**📝 摘要概括：**

> Windows组件对象模型(COM)服务以升级权限运行，并可供经过身份验证的用户广泛访问，这使得这些二进制文件中的竞争条件成为本地权限提升的关键表面。我们展示了SLYP ，这是一个端到端的代理流水线，可以发现COM二进制文件中的竞争条件漏洞，并生成调试器验证的概念验证（ PoC ）代码。此外， SLYP的设计采用了可推广的二元分析……

</details>

<details>
<summary><b>6. Adaptivity Under Realizability Constraints: Comparing In-Context and Agentic Learning</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Anastasis Kratsios、A. Martina Neuman、Philipp Petersen |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-05-06T14:53:55Z |
| **关键词** | `Agentic` |
| **原文链接** | [http://arxiv.org/abs/2605.04995v1](http://arxiv.org/abs/2605.04995v1) |

**📝 摘要概括：**

> 我们将上下文学习与固定查询进行比较，并将代理学习与自适应查询进行比较，以实现任务族的统一逼近。我们考虑两种设置：不受限制的制度，其中查询和逼近是任意函数，以及可实现的制度，其中我们要求这些操作由ReLU神经网络实现。这表明表征约束与适应性的影响有着深刻的相互作用。

</details>

<details>
<summary><b>7. Self-Induced Outcome Potential: Turn-Level Credit Assignment for Agents without Verifiers</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Senkang Hu、Yong Dai、Xudong Han、Zhengru Fang、Yuzhi Zhao 等（共 7 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、CAS、TRI |
| **发布时间** | 2026-05-06T14:38:48Z |
| **关键词** | `LLM Agent` · `Agentic` · `Reasoning` · `RAG` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2605.04984v1](http://arxiv.org/abs/2605.04984v1) |

**📝 摘要概括：**

> 长期LLM代理依赖于中间信息收集轮次，但培训反馈通常仅在最终答案中观察到，因为流程级别的奖励需要高质量的人工注释。现有的回合级塑造方法奖励增加金牌答案可能性的回合，但它们需要答案监督或稳定的特定任务验证器。优惠码可在https://github.com/dl-m9/SIOP.git上获得。

</details>

<details>
<summary><b>8. Architectural Constraints Alignment in AI-assisted, Platform-based Service Development</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Julius Irion、Moritz Leugers、Paul Hartwig、Simon Kling、Tachmyrat Annayev 等（共 8 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、HIT、TRI |
| **发布时间** | 2026-05-06T14:28:28Z |
| **关键词** | `Agentic` · `Retrieval` · `Evaluation` · `Code Generation` · `Workflow` |
| **原文链接** | [http://arxiv.org/abs/2605.04973v1](http://arxiv.org/abs/2605.04973v1) |

**📝 摘要概括：**

> 人工智能辅助开发工具可实现服务的快速原型设计，但往往缺乏对生产环境中所需的架构约束、基础设施依赖性和组织标准的认识。因此，生成的伪影可能表现出脆性行为和有限的可部署性。评估表明，与通用AI代码生成工作流相比，架构一致性和可部署性有所改善，这表明……

</details>

<details>
<summary><b>9. Modular Reinforcement Learning For Cooperative Swarms</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Erel Shtossel、Gal A. Kaminka |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-05-06T14:05:36Z |
| **关键词** | `Multi-Agent` · `Reinforcement Learning` · `RAG` · `Memory` |
| **原文链接** | [http://arxiv.org/abs/2605.04939v1](http://arxiv.org/abs/2605.04939v1) |

**📝 摘要概括：**

> 协作机器人群是具有共同目标的计算受限机器人的集合。每个机器人只能与其同行的一小部分进行交互，而不知道这会如何影响集体效用。我们在许多模拟机器人群进行觅食的实验中证明了该方法的有效性。

</details>

<details>
<summary><b>10. Evolving Idea Graphs with Learnable Edits-and-Commits for Multi-Agent Scientific Ideation</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Jiangwen Dong、Bo Li、Wanyu Lin |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-05-06T13:50:40Z |
| **关键词** | `Multi-Agent` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2605.04922v1](http://arxiv.org/abs/2605.04922v1) |

**📝 摘要概括：**

> 法学硕士授权的多代理系统通过产生新颖的研究理念，为加速科学发现提供了新的潜力。但是，现有方法通常通过临时文本（如草稿或聊天日志）协调客服代表；很难确定生成的创意中的弱点以及客服代表如何完善它们。消融进一步表明，显式图形状态提供了主要的性能提升，并学会了编辑和提交控制…

</details>

<details>
<summary><b>11. Storage Is Not Memory: A Retrieval-Centered Architecture for Agent Recall</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Joshua Adler、Guy Zehavi |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、HIT、TRI |
| **发布时间** | 2026-05-06T13:27:41Z |
| **关键词** | `RAG` · `Retrieval` · `Memory` |
| **原文链接** | [http://arxiv.org/abs/2605.04897v1](http://arxiv.org/abs/2605.04897v1) |

**📝 摘要概括：**

> 对于代理内存而言，摄取时的提取是错误的原语：在已知查询之前丢弃的内容无法在检索时恢复。我们提出了True Memory ，这是一种六层架构，可将系统的中心从存储架构转移到逐字保留事件的多级检索管道。56次配置消融显示，在性能最佳的配置家族中，分布为1.3个百分点。

</details>

<details>
<summary><b>12. To Fuse or to Drop? Dual-Path Learning for Resolving Modality Conflicts in Multimodal Emotion Recognition</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Yangchen Yu、Qian Chen、Jia Li、Zhenzhen Hu、Jinpeng Hu 等（共 8 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、CAS、TRI |
| **发布时间** | 2026-05-06T13:11:33Z |
| **关键词** | `Benchmark` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2605.04877v1](http://arxiv.org/abs/2605.04877v1) |

**📝 摘要概括：**

> 多模态情感识别（ MER ）受益于文本、音频和视觉的组合，但当模态冲突时，标准融合通常会失败。至关重要的是，冲突的可解决性各不相同：良性冲突源于缺失、弱或模棱两可的线索，可以通过跨模式校准来缓解，而严重冲突则源于内在矛盾（例如讽刺）或误导性信号，强制融合可能会放大错误。进一步……

</details>

<details>
<summary><b>13. DecodingTrust-Agent Platform (DTap): A Controllable and Interactive Red-Teaming Platform for AI Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Zhaorun Chen、Xun Liu、Haibo Tong、Chengquan Guo、Yuzhou Nie 等（共 17 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | Google |
| **发布时间** | 2026-05-06T11:59:48Z |
| **关键词** | `AI Agent` · `Evaluation` · `Simulation` · `Workflow` |
| **原文链接** | [http://arxiv.org/abs/2605.04808v1](http://arxiv.org/abs/2605.04808v1) |

**📝 摘要概括：**

> 人工智能代理越来越多地部署在不同的领域，通过长期和高风险的操作执行来自动化复杂的工作流程。由于其高能力和灵活性，此类代理商引发了重大的安全和安保问题。通过DTap ，我们对基于各种骨干模型、跨越安全策略、风险类别和攻击策略的流行AI代理进行了大规模评估，揭示了系统漏洞……

</details>

## 🗄️ 历史归档

| 日期 | 论文数 | 报告链接 |
|------|--------|----------|
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

*由 [clawBot DailyFindings](https://github.com/Jacob-biu/clawBot) 自动维护 | 最后更新：2026-05-07 23:03 UTC*
