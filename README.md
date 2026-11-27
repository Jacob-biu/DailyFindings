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

## 📅 今日论文 — 2026-11-27　　[→ 查看完整报告](daily/2026-11-27.md)

> 共筛选出 **14** 篇论文 | 更新于 2026-11-27 03:58 UTC

### 论文目录与概要

| # | 论文标题 | 核心概要 | 来源机构 | 第一作者 |
|---|---------|---------|---------|--------|
| 1 | [Attack Policy Selection can Mislead Monitor Evaluators](http://arxiv.org/abs/2611.34934v1) | AI 监视器（即标记 AI 代理危险行为的分类器）通常会根据攻击策略生成的转录记录进行评估，这些转录记录在部署中充当危险行为的代理。我们以一个曾用于生产环境的OpenAI监视器作为案例研究对象进行评估… | OpenAI、CAS | Charlie Griffin |
| 2 | [$μ$-Bench: Benchmarking Multi-User Task Completion in Shared…](http://arxiv.org/abs/2611.34920v1) | 共享空间中的语音代理必须满足相互关联的多用户请求，同时维护每个用户的权限、隐私和任务限制。当参与者在整个会话过程中做出反应时，现有评估的覆盖范围有限。通过将反应式多用户模拟与可验证的会话级结果相结合，… | MIT、CAS | Qihao Lin |
| 3 | [How Much Do Coding Agents Over-Edit, and Why? An Empirical S…](http://arxiv.org/abs/2611.34875v1) | Agent的补丁比开发人员的补丁大，这被普遍认为是过度编辑。但补丁大小并不能说明是否需要额外的编辑、这些编辑是什么，或者它们来自哪里。我们建议基准在解决率旁边报告代码的必要性，并通过模型训练和Harn… | TRI | Aakash Goel |
| 4 | [Shape-Aware Three-Way Merge for RDF Knowledge Graphs: The sc…](http://arxiv.org/abs/2611.34870v1) | 合并 RDF 序列化会产生排序冲突，并错过语义冲突。我们描述并评估了一种三向合并，其中模式定义了一个冲突：集合代数将规范三元组组合在一起，并且只有在 SHACL 形状限制其基数且双方的更改都无法在该限… | MIT、CAS | Steve Brown |
| 5 | [DRBench Pro: A Knowledge-Centric Benchmark for Professional …](http://arxiv.org/abs/2611.34852v1) | 深度研究代理从多个来源收集信息，并将其综合成关于复杂、开放式问题的报告。现有基准从多个维度评估报告质量，但缺乏专门的以知识为中心的评估，即报告涵盖哪些研究方向以及对这些方向的深入程度。评分细则的判断与… | CAS、TRI | Han Huang |
| 6 | [Provably Efficient Offline Discounted Reinforcement Learning…](http://arxiv.org/abs/2611.34840v1) | 我们研究了有限折扣无限时域马尔可夫决策过程中的风险敏感型强化学习，该过程采用递归熵风险度量（ERM），参数为$β\neq 0$。我们同时考虑了风险规避（$β>0$）和风险偏好（$β<0$）的设置。所提… | CAS | Amirparsa Bahrami |
| 7 | [Deep Reinforcement Learning for Multi-UAV Data Harvesting Un…](http://arxiv.org/abs/2611.34818v1) | 当有限的通信基础设施阻碍无线传感器卸载测量数据时，从这些传感器收集数据可能具有挑战性。在这种情况下，无人驾驶飞行器（UAV）可以利用其机动性在本地采集数据，而协调的UAV编队则可以为偏远地区提供高效且… | MIT | Thiago de Souza Lamenza |
| 8 | [TASK Memory: Beyond Text-Only Memory with Activation Steerin…](http://arxiv.org/abs/2611.34762v1) | LLM 代理越来越依赖外部记忆，但它们仍然会对所记忆的内容产生幻觉。通常，正确的记忆会被检索出来并放入提示中，但答案与记忆相矛盾，或者记忆被应用于错误的问题。在 23 次跨模型比较（80 亿至 270… | TRI | Jinkun Zhao |
| 9 | [Collect for Coverage, Replay with Evidence: Adaptive and Eff…](http://arxiv.org/abs/2611.34756v1) | 对于长视域智能体来说，全在线策略内蒸馏（OPD）的成本很高，因为每次更新都依赖于新的环境 rollout。前缀重放通过从存储的历史记录中采样当前学生响应，提供了一种高效的替代方案，从而减少了长尾rol… | MIT | Haowen Hou |
| 10 | [Maco-RL: Scaling Agent Capabilities with Mixed-Task Reinforc…](http://arxiv.org/abs/2611.34703v1) | 混合任务强化学习（MixRL）直接跨域训练一个统一的策略，以持续扩展智能体的能力，而无需训练独立的专家模型，也无需额外的蒸馏阶段。尽管 MixRL 具有吸引力，但在实现稳定高效的混合任务学习、有效分配… | MIT、TRI | Jiacheng Zhang |
| 11 | [RoboEvo$^2$: Recursive Robot Self-Improvement via Harness-Po…](http://arxiv.org/abs/2611.34675v1) | 机器人应能够适应陌生的环境，并通过互动来习得新技能，然后通过实践高效地运用这些技能。视觉-语言-行动策略可提供高效的控制，但通常需要额外的人类示范来处理不熟悉的环境；推理智能体可以利用广泛的先验知识和… | Mila | Chenzhi Liu |
| 12 | [Do We Still Need Reinforcement Learning When We Can Read the…](http://arxiv.org/abs/2611.34656v1) | 强化学习在序贯决策方面取得了显著的成功，但学习有效的策略通常需要大量的互动经验。基于模型的强化学习通过利用世界模型来减轻这种依赖性，世界模型通常用于支持规划或策略优化。这些研究结果表明，直接策略合成可… | TRI | Mingchao Zhang |
| 13 | [LatentRL-QAS: Transfer via Latent Reinforcement Learning for…](http://arxiv.org/abs/2611.34634v1) | 强化学习（RL）已成为量子架构搜索（QAS）——即量子电路的自动化设计——的一种重要方法。然而，将智能体从一个量子比特数所学到的知识迁移到另一个量子比特数仍未得到充分探索：最先进的RL-QAS智能体的… | HIT、NTU | Maria Ilektra Plakitsi |
| 14 | [VisualMontage: Manipulating the Beliefs of Vision-Language A…](http://arxiv.org/abs/2611.34603v1) | 随着基于视觉-语言模型（VLM）的代理越来越多地解读社交媒体内容，其分析中的错误可能会使谣言显得可信，并助长谣言的传播。本文研究了视觉认知串通问题，在这种情况下，协调一致的帖子将真实图像与局部忠实的文… | CAS | Jinwei Hu |

### 论文详情

<details>
<summary><b>1. Attack Policy Selection can Mislead Monitor Evaluators</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Charlie Griffin、Oliver Makins、Asa Cooper Stickland、Alessandro Abate、Yarin Gal 等（共 7 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | OpenAI、CAS |
| **发布时间** | 2026-11-25T18:59:28Z |
| **关键词** | `AI Agent` · `Reasoning` · `Reinforcement Learning` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2611.34934v1](http://arxiv.org/abs/2611.34934v1) |

**📝 摘要概括：**

> AI 监视器（即标记 AI 代理危险行为的分类器）通常会根据攻击策略生成的转录记录进行评估，这些转录记录在部署中充当危险行为的代理。我们以一个曾用于生产环境的OpenAI监视器作为案例研究对象进行评估，发现所测得的漏报率对生成攻击策略的方法以及在该方法中应用的优化水平都非常敏感。提出有说服力的论点……

</details>

<details>
<summary><b>2. $μ$-Bench: Benchmarking Multi-User Task Completion in Shared Interaction Voice Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Qihao Lin、Guanxu Chen、Shuhang Zheng、Xiaoya Lu、Jingyi Yang 等（共 10 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、CAS、TRI |
| **发布时间** | 2026-11-25T18:58:42Z |
| **关键词** | `RAG` · `Benchmark` · `Evaluation` · `Simulation` |
| **原文链接** | [http://arxiv.org/abs/2611.34920v1](http://arxiv.org/abs/2611.34920v1) |

**📝 摘要概括：**

> 共享空间中的语音代理必须满足相互关联的多用户请求，同时维护每个用户的权限、隐私和任务限制。当参与者在整个会话过程中做出反应时，现有评估的覆盖范围有限。通过将反应式多用户模拟与可验证的会话级结果相结合，$μ$-Bench为共享语音代理提供了一个严谨的测试平台。

</details>

<details>
<summary><b>3. How Much Do Coding Agents Over-Edit, and Why? An Empirical Study of Unneeded Edits in Repository-Level Agent Patches</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Aakash Goel、Benjamin Steenhoek、Yu Hu |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-11-25T18:37:06Z |
| **关键词** | `RAG` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2611.34875v1](http://arxiv.org/abs/2611.34875v1) |

**📝 摘要概括：**

> Agent的补丁比开发人员的补丁大，这被普遍认为是过度编辑。但补丁大小并不能说明是否需要额外的编辑、这些编辑是什么，或者它们来自哪里。我们建议基准在解决率旁边报告代码的必要性，并通过模型训练和Harness层面的剪枝来解决过度编辑问题。

</details>

<details>
<summary><b>4. Shape-Aware Three-Way Merge for RDF Knowledge Graphs: The schema defines the conflict: an implementation and evaluation</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Steve Brown |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、CAS、TRI |
| **发布时间** | 2026-11-25T18:34:46Z |
| **关键词** | `Multi-Agent` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2611.34870v1](http://arxiv.org/abs/2611.34870v1) |

**📝 摘要概括：**

> 合并 RDF 序列化会产生排序冲突，并错过语义冲突。我们描述并评估了一种三向合并，其中模式定义了一个冲突：集合代数将规范三元组组合在一起，并且只有在 SHACL 形状限制其基数且双方的更改都无法在该限制范围内存在时，才会发生槽位冲突。所支持的主张是，在一次部署中，对于基数冲突，人为决策更少，且不会悄然丢失任何内容，n……

</details>

<details>
<summary><b>5. DRBench Pro: A Knowledge-Centric Benchmark for Professional Deep Research Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Han Huang、Yuchen Yan、Xingyu Wu、Yijun Li、Chao Deng 等（共 8 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | CAS、TRI |
| **发布时间** | 2026-11-25T18:25:30Z |
| **关键词** | `RAG` · `Benchmark` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2611.34852v1](http://arxiv.org/abs/2611.34852v1) |

**📝 摘要概括：**

> 深度研究代理从多个来源收集信息，并将其综合成关于复杂、开放式问题的报告。现有基准从多个维度评估报告质量，但缺乏专门的以知识为中心的评估，即报告涵盖哪些研究方向以及对这些方向的深入程度。评分细则的判断与人工标注高度一致，且在所测试的各项指标配置中，智能体的排名保持稳定……

</details>

<details>
<summary><b>6. Provably Efficient Offline Discounted Reinforcement Learning under Recursive Entropic Risk</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Amirparsa Bahrami、Oliver Mortensen、Mohammad Sadegh Talebi |
| **所属机构** | （详见原文） |
| **顶级机构标签** | CAS |
| **发布时间** | 2026-11-25T18:18:53Z |
| **关键词** | `Reinforcement Learning` |
| **原文链接** | [http://arxiv.org/abs/2611.34840v1](http://arxiv.org/abs/2611.34840v1) |

**📝 摘要概括：**

> 我们研究了有限折扣无限时域马尔可夫决策过程中的风险敏感型强化学习，该过程采用递归熵风险度量（ERM），参数为$β\neq 0$。我们同时考虑了风险规避（$β>0$）和风险偏好（$β<0$）的设置。所提出的界限为在风险规避和风险偏好两种模式下，递归ERM下的离线强化学习提供了首个严格的样本复杂度保证。

</details>

<details>
<summary><b>7. Deep Reinforcement Learning for Multi-UAV Data Harvesting Under Variable Team Sizes and Agent Loss</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Thiago de Souza Lamenza、Bruno José Olivieri de Souza、Markus Endler |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT |
| **发布时间** | 2026-11-25T18:03:00Z |
| **关键词** | `Multi-Agent` · `Reinforcement Learning` · `RAG` |
| **原文链接** | [http://arxiv.org/abs/2611.34818v1](http://arxiv.org/abs/2611.34818v1) |

**📝 摘要概括：**

> 当有限的通信基础设施阻碍无线传感器卸载测量数据时，从这些传感器收集数据可能具有挑战性。在这种情况下，无人驾驶飞行器（UAV）可以利用其机动性在本地采集数据，而协调的UAV编队则可以为偏远地区提供高效且冗余的覆盖。结果表明，F-MADDPG 在所评估的群体规模范围内都能进行学习，完成任务的速度比……更快。

</details>

<details>
<summary><b>8. TASK Memory: Beyond Text-Only Memory with Activation Steering and Knowledge Editing against Memory Hallucination</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Jinkun Zhao、Wenjun Wu |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-11-25T17:30:37Z |
| **关键词** | `LLM Agent` · `RAG` · `Retrieval` · `Memory` |
| **原文链接** | [http://arxiv.org/abs/2611.34762v1](http://arxiv.org/abs/2611.34762v1) |

**📝 摘要概括：**

> LLM 代理越来越依赖外部记忆，但它们仍然会对所记忆的内容产生幻觉。通常，正确的记忆会被检索出来并放入提示中，但答案与记忆相矛盾，或者记忆被应用于错误的问题。在 23 次跨模型比较（80 亿至 270 亿参数，四个系列）中，有 21 次具有显著性，TASK 在 10 个模型-数据集单元中的 9 个单元中优于三种最新的上下文引导方法。

</details>

<details>
<summary><b>9. Collect for Coverage, Replay with Evidence: Adaptive and Efficient On-Policy Distillation for Long-Horizon Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Haowen Hou、Gen Li、Ruilin Li、Yicheng Liu、Zhen Huang 等（共 14 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT |
| **发布时间** | 2026-11-25T17:27:31Z |
| **关键词** | `RAG` |
| **原文链接** | [http://arxiv.org/abs/2611.34756v1](http://arxiv.org/abs/2611.34756v1) |

**📝 摘要概括：**

> 对于长视域智能体来说，全在线策略内蒸馏（OPD）的成本很高，因为每次更新都依赖于新的环境 rollout。前缀重放通过从存储的历史记录中采样当前学生响应，提供了一种高效的替代方案，从而减少了长尾rollout的空闲时间，并使每个收集的轨迹都能支持多次更新。在 SWE-bench Verified 上，它将任务成功率提高至 59.5%，同时将端到端训练时间缩短了……

</details>

<details>
<summary><b>10. Maco-RL: Scaling Agent Capabilities with Mixed-Task Reinforcement Learning</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Jiacheng Zhang、Qixing Zhou、Haiyang Wang、Qipeng Gu、Shuzhe Wu 等（共 9 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-11-25T16:59:27Z |
| **关键词** | `Reinforcement Learning` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2611.34703v1](http://arxiv.org/abs/2611.34703v1) |

**📝 摘要概括：**

> 混合任务强化学习（MixRL）直接跨域训练一个统一的策略，以持续扩展智能体的能力，而无需训练独立的专家模型，也无需额外的蒸馏阶段。尽管 MixRL 具有吸引力，但在实现稳定高效的混合任务学习、有效分配 rollout 计算以及支持持续的领域扩展方面，MixRL 的扩展仍面临重大挑战。这些结果支持将 MixRL 作为一种……

</details>

<details>
<summary><b>11. RoboEvo$^2$: Recursive Robot Self-Improvement via Harness-Policy Co-Evolution</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Chenzhi Liu、Jiehong Lin、Wei Huang、Xuzhao Huang、Haoyuan Li 等（共 12 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | Mila |
| **发布时间** | 2026-11-25T16:39:10Z |
| **关键词** | `Agentic` · `Reasoning` · `Memory` |
| **原文链接** | [http://arxiv.org/abs/2611.34675v1](http://arxiv.org/abs/2611.34675v1) |

**📝 摘要概括：**

> 机器人应能够适应陌生的环境，并通过互动来习得新技能，然后通过实践高效地运用这些技能。视觉-语言-行动策略可提供高效的控制，但通常需要额外的人类示范来处理不熟悉的环境；推理智能体可以利用广泛的先验知识和机器人控制API来发现解决方案，但反复的思考和修正成本高昂。我们的模型和代码将……

</details>

<details>
<summary><b>12. Do We Still Need Reinforcement Learning When We Can Read the World Model?</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Mingchao Zhang、Miduo Cui、Kangze He、Yuanjun Li、Dapeng Li 等（共 13 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-11-25T16:29:37Z |
| **关键词** | `Reasoning` · `Planning` · `Reinforcement Learning` · `RAG` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2611.34656v1](http://arxiv.org/abs/2611.34656v1) |

**📝 摘要概括：**

> 强化学习在序贯决策方面取得了显著的成功，但学习有效的策略通常需要大量的互动经验。基于模型的强化学习通过利用世界模型来减轻这种依赖性，世界模型通常用于支持规划或策略优化。这些研究结果表明，直接策略合成可以减少对试错的依赖，从而对……的必要性提出质疑。

</details>

<details>
<summary><b>13. LatentRL-QAS: Transfer via Latent Reinforcement Learning for Quantum Architecture Search</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Maria Ilektra Plakitsi、Sebastian Feld、Akash Kundu |
| **所属机构** | （详见原文） |
| **顶级机构标签** | HIT、NTU |
| **发布时间** | 2026-11-25T16:20:02Z |
| **关键词** | `Reinforcement Learning` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2611.34634v1](http://arxiv.org/abs/2611.34634v1) |

**📝 摘要概括：**

> 强化学习（RL）已成为量子架构搜索（QAS）——即量子电路的自动化设计——的一种重要方法。然而，将智能体从一个量子比特数所学到的知识迁移到另一个量子比特数仍未得到充分探索：最先进的RL-QAS智能体的状态、动作空间和神经网络都随着量子比特数的增加而增加，这使得跨量子比特数的迁移学习变得难以实现。通过解耦……

</details>

<details>
<summary><b>14. VisualMontage: Manipulating the Beliefs of Vision-Language Agents with Authentic Image Sequences</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Jinwei Hu、Lai Wei、Zhuoyun Li、Youcheng Sun、Yi Dong 等（共 6 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | CAS |
| **发布时间** | 2026-11-25T15:57:55Z |
| **关键词** | `Multi-Agent` · `Reasoning` · `Planning` · `Benchmark` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2611.34603v1](http://arxiv.org/abs/2611.34603v1) |

**📝 摘要概括：**

> 随着基于视觉-语言模型（VLM）的代理越来越多地解读社交媒体内容，其分析中的错误可能会使谣言显得可信，并助长谣言的传播。本文研究了视觉认知串通问题，在这种情况下，协调一致的帖子将真实图像与局部忠实的文字说明相结合，诱使 VLM 智能体通过自身的推理来推断并接受攻击者选定的目标主张。这些发现共同……

</details>

## 🗄️ 历史归档

| 日期 | 论文数 | 报告链接 |
|------|--------|----------|
| 2026-11-27 | 14 篇 | [2026-11-27.md](daily/2026-11-27.md) |
| 2026-11-26 | 20 篇 | [2026-11-26.md](daily/2026-11-26.md) |
| 2026-11-25 | 20 篇 | [2026-11-25.md](daily/2026-11-25.md) |
| 2026-11-24 | 20 篇 | [2026-11-24.md](daily/2026-11-24.md) |
| 2026-11-23 | 0 篇 | [2026-11-23.md](daily/2026-11-23.md) |
| 2026-11-22 | 0 篇 | [2026-11-22.md](daily/2026-11-22.md) |
| 2026-11-21 | 16 篇 | [2026-11-21.md](daily/2026-11-21.md) |
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

## 🏛️ 顶级机构覆盖范围

覆盖超过 **70 个**顶级 AI 机构，包括：

- **科技公司：** Microsoft、Google DeepMind、OpenAI、Anthropic、Meta AI、NVIDIA、Baidu、Alibaba、ByteDance 等
- **北美顶级大学：** MIT、Stanford、CMU、UC Berkeley、Harvard、Princeton、Cornell、Caltech 等
- **中国顶级大学/机构：** 清华大学、北京大学、浙大、上交大、复旦、中科院、MSRA 等
- **欧洲/其他：** Oxford、Cambridge、ETH Zurich、Mila、NUS、KAIST 等

---

*由 [clawBot DailyFindings](https://github.com/Jacob-biu/clawBot) 自动维护 | 最后更新：2026-11-27 03:58 UTC*
