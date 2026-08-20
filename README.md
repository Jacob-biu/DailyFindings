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

## 📅 今日论文 — 2026-08-20　　[→ 查看完整报告](daily/2026-08-20.md)

> 共筛选出 **13** 篇论文 | 更新于 2026-08-20 22:25 UTC

### 论文目录与概要

| # | 论文标题 | 核心概要 | 来源机构 | 第一作者 |
|---|---------|---------|---------|--------|
| 1 | [SPADE: Self-Play in Adaptive Synthetic Executable Environmen…](http://arxiv.org/abs/2608.19197v1) | 持续的自我提升需要不断扩大的自我生成、多样化、适应性强的目标库。对于语言代理，现有的培训环境池（手工策划、静态合成或冻结验证）将目标分布固定为学习者量表。通过使环境设计本身成为可学习的组成部分， SP… | OpenAI、TRI | Bo Liu |
| 2 | [Beyond the Transcript: Detecting Covert Co ordination in Lat…](http://arxiv.org/abs/2608.19161v1) | 语言模型代理可以通过在公共成绩单中不可见的连续隐藏状态进行沟通，从而为隐藏的有害协调创造机会。我们引入了可验证潜在对齐（ VLA ） ，这是一种激活感知框架，用于监控和引导这些私人通信渠道。总体而言，… | MIT、HIT | Ramneet Kaur |
| 3 | [Multi-Agent Off-Policy Deep Reinforcement Learning for Smart…](http://arxiv.org/abs/2608.19049v1) | 深度强化学习（ DRL ）因其在复杂优化问题中的实时适应性和有效性而受到广泛关注。本文研究了毫米波（ mmWave ）基站（ BS ）在逼真的非凸校园拓扑中的优化部署。最后，多智能体展示了密集场景与$… | FAIR | Omar Rady |
| 4 | [Eureka: Task-Conditioned Meta-Agent Orchestration for Scient…](http://arxiv.org/abs/2608.19047v1) | 我们提出了Eureka ，这是一种任务条件元代理架构，它将长时间任务编译成具有显式接受语义的动态义务图。在执行过程中， Eureka通过后退地平线规划、架构推广和最低限度的编译，形成具有专用状态、内存… | HIT、NTU | Alizer Wong |
| 5 | [Adaptive Memory and Reflection Multi-Agent System for Medica…](http://arxiv.org/abs/2608.19029v1) | 准确和负责任的医疗问答（ QA ）在医疗保健中很重要，因为复杂的案例需要事实知识和细致入微的推理。现有的医疗QA系统通常基于单代理架构和静态检索，通常缺乏适应性、持久内存和结构化决策。源代码可在htt… | HIT、CAS | Pradeep Murugesan |
| 6 | [Self-prompting and cross-model consensus enable reproducible…](http://arxiv.org/abs/2608.19025v1) | 从研究文章中准确地提取细致入微、情境化的数据既费力又耗时。在这里，我们研究了基于浏览器的前沿大型语言模型（ LLM ）的性能，以提取高度语境化的信息。这些发现共同定义了一个可审计的分工，其中专家指定证… | CAS | Valentin Romanov |
| 7 | [Harness Continual Learning: Continual Adaptation Beyond Mode…](http://arxiv.org/abs/2608.19013v1) | 持续学习在很大程度上是以模型为中心的，将模型参数视为随着连续经验而变化的状态。现代客服代表还可以通过提示、记忆、工具、技能和路由规则进行调整。组件烧蚀评估每个线束组件的贡献，而受控的保留扫描揭示了可测… | MIT、TRI | Borui Kang |
| 8 | [A Theory of Post-hoc Debate Judgement](http://arxiv.org/abs/2608.19002v1) | 最近出现了一些争论，这些争论是代理人工智能提高性能以及帮助可解释性和用户参与度的有用方法。例如， LLM授权的代理人可以在内部（与自己）和/或外部（与其他代理人）进行辩论。总体而言，我们的研究表明，辩… | Mila | Xiang Yin |
| 9 | [rEDMRec: Distilling Large Language Model Reasoning into an E…](http://arxiv.org/abs/2608.18952v1) | 大型语言模型可以通过明确推理用户历史记录和候选项目（例如，提取用户的偏好或解释为什么一个项目比另一个项目更适合）来提高推荐质量，而不是将历史记录直接映射到排名列表。然而，这种推理在每次排名请求中重复都… | Amazon、TRI | Minh Hoang Nguyen |
| 10 | [Training-Free Inference-Time Self-Reflection and Cost-Bounde…](http://arxiv.org/abs/2608.18884v1) | 推理LLM （例如GRPO ）的强化学习培训成本高昂，需要一个可控的环境，为完整的培训管道做出一切贡献。我们推荐EvoResearcher ，这是一种无需训练的推理时间协议，可为单个冻结的LLM骨干网… | MIT、TRI | Wei Yu |
| 11 | [DentAgent: Evidence-Centric Multi-Agent Coordination for Mul…](http://arxiv.org/abs/2608.18878v1) | 口腔疾病影响着全球数十亿人，这凸显了对准确可靠的牙科评估的迫切需求，该评估整合了来自领域知识、X光片、口腔内照片和3D牙科数据的异质证据。大多数现有的牙科人工智能系统仍然是特定于模式或任务的。在四个基… | MIT、TRI | Zijie Meng |
| 12 | [SkillGate: Training In-Policy Skill Selection in Long-Horizo…](http://arxiv.org/abs/2608.18852v1) | 代理框架越来越多地将程序知识打包为技能：代理按需阅读的指令文件，而公共图书馆现在拥有成千上万的指令文件。因此，要阅读的技能已成为政策本身在情节中间做出的决定，但没有现有的信号对其进行训练。在16名候选… | CAS、TRI | Qingyao Li |
| 13 | [Verifiable abstention makes AI leak diagnosis accountable in…](http://arxiv.org/abs/2608.18836v1) | 公用事业公司因泄漏而损失了大量处理过的水，但很少信任人工智能本地化人员来派遣工作人员：到处猜测都不能证明挖掘是合理的。差距在于问责制，而不是准确性：没有任何方法可以证明它何时不应该采取行动。负责任的弃… | CAS、TRI | Tianwei Mu |

### 论文详情

<details>
<summary><b>1. SPADE: Self-Play in Adaptive Synthetic Executable Environments</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Bo Liu、Simon Yu、Yiding Jiang、Ao Qu、Andrew Zhao 等（共 18 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | OpenAI、TRI |
| **发布时间** | 2026-08-19T17:58:56Z |
| **关键词** | `Agentic` · `Reasoning` · `RAG` · `Benchmark` · `Memory` |
| **原文链接** | [http://arxiv.org/abs/2608.19197v1](http://arxiv.org/abs/2608.19197v1) |

**📝 摘要概括：**

> 持续的自我提升需要不断扩大的自我生成、多样化、适应性强的目标库。对于语言代理，现有的培训环境池（手工策划、静态合成或冻结验证）将目标分布固定为学习者量表。通过使环境设计本身成为可学习的组成部分， SPADE朝着开放式自我提升迈出了具体的一步。

</details>

<details>
<summary><b>2. Beyond the Transcript: Detecting Covert Co ordination in Latent Multi-Agent Communication</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Ramneet Kaur、Pradyumna Chari、Ramesh Raskar、Jugad Singh、Sumit Kumar Jha 等（共 6 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、HIT、TRI |
| **发布时间** | 2026-08-19T17:43:22Z |
| **关键词** | `Multi-Agent` · `Benchmark` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2608.19161v1](http://arxiv.org/abs/2608.19161v1) |

**📝 摘要概括：**

> 语言模型代理可以通过在公共成绩单中不可见的连续隐藏状态进行沟通，从而为隐藏的有害协调创造机会。我们引入了可验证潜在对齐（ VLA ） ，这是一种激活感知框架，用于监控和引导这些私人通信渠道。总体而言，对照研究表明，评估的专用通道攻击可以在不对主监视器进行培训的情况下进行监控…

</details>

<details>
<summary><b>3. Multi-Agent Off-Policy Deep Reinforcement Learning for Smart Campus Coverage</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Omar Rady、Mohamed Ayman、Ali Arafa、Mohamed Shalma |
| **所属机构** | （详见原文） |
| **顶级机构标签** | FAIR |
| **发布时间** | 2026-08-19T15:41:32Z |
| **关键词** | `Multi-Agent` · `Reinforcement Learning` · `RAG` · `Benchmark` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2608.19049v1](http://arxiv.org/abs/2608.19049v1) |

**📝 摘要概括：**

> 深度强化学习（ DRL ）因其在复杂优化问题中的实时适应性和有效性而受到广泛关注。本文研究了毫米波（ mmWave ）基站（ BS ）在逼真的非凸校园拓扑中的优化部署。最后，多智能体展示了密集场景与$ 400 $用户的高效计算收敛。

</details>

<details>
<summary><b>4. Eureka: Task-Conditioned Meta-Agent Orchestration for Scientific Discovery</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Alizer Wong、Heng Cui、Yi Tan、Xiongchao Zhan、Liang Lin 等（共 9 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | HIT、NTU |
| **发布时间** | 2026-08-19T15:40:21Z |
| **关键词** | `Planning` · `Memory` |
| **原文链接** | [http://arxiv.org/abs/2608.19047v1](http://arxiv.org/abs/2608.19047v1) |

**📝 摘要概括：**

> 我们提出了Eureka ，这是一种任务条件元代理架构，它将长时间任务编译成具有显式接受语义的动态义务图。在执行过程中， Eureka通过后退地平线规划、架构推广和最低限度的编译，形成具有专用状态、内存、运算符、工具、验证器和本地拓扑的宏代理。这些结果表明，科学代理能力不仅取决于……

</details>

<details>
<summary><b>5. Adaptive Memory and Reflection Multi-Agent System for Medical Question Answering</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Pradeep Murugesan、Luoxiao Yang、Xueli Chen、Xinqi Fan |
| **所属机构** | （详见原文） |
| **顶级机构标签** | HIT、CAS、TRI |
| **发布时间** | 2026-08-19T15:24:18Z |
| **关键词** | `Multi-Agent` · `Agentic` · `Reasoning` · `Retrieval` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2608.19029v1](http://arxiv.org/abs/2608.19029v1) |

**📝 摘要概括：**

> 准确和负责任的医疗问答（ QA ）在医疗保健中很重要，因为复杂的案例需要事实知识和细致入微的推理。现有的医疗QA系统通常基于单代理架构和静态检索，通常缺乏适应性、持久内存和结构化决策。源代码可在https://github.com/mm-air/AMR-Agent上公开获得。

</details>

<details>
<summary><b>6. Self-prompting and cross-model consensus enable reproducible data extraction from scientific literature with large language models</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Valentin Romanov、Monique Bax、Steven Niederer |
| **所属机构** | （详见原文） |
| **顶级机构标签** | CAS |
| **发布时间** | 2026-08-19T15:20:11Z |
| **关键词** | `Workflow` |
| **原文链接** | [http://arxiv.org/abs/2608.19025v1](http://arxiv.org/abs/2608.19025v1) |

**📝 摘要概括：**

> 从研究文章中准确地提取细致入微、情境化的数据既费力又耗时。在这里，我们研究了基于浏览器的前沿大型语言模型（ LLM ）的性能，以提取高度语境化的信息。这些发现共同定义了一个可审计的分工，其中专家指定证据标准，模型交叉检查重复提取，研究人员解决有争议的案件，提供……

</details>

<details>
<summary><b>7. Harness Continual Learning: Continual Adaptation Beyond Model Parameters</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Borui Kang、Jinrui Gu、Junhan Lv、Wenbin Li、Lei Wang 等（共 6 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-08-19T15:12:31Z |
| **关键词** | `Reasoning` · `Memory` |
| **原文链接** | [http://arxiv.org/abs/2608.19013v1](http://arxiv.org/abs/2608.19013v1) |

**📝 摘要概括：**

> 持续学习在很大程度上是以模型为中心的，将模型参数视为随着连续经验而变化的状态。现代客服代表还可以通过提示、记忆、工具、技能和路由规则进行调整。组件烧蚀评估每个线束组件的贡献，而受控的保留扫描揭示了可测量的线束水平遗忘，并表明稳定性-塑性权衡可以明确地……

</details>

<details>
<summary><b>8. A Theory of Post-hoc Debate Judgement</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Xiang Yin、Adam Dejl、Antonio Rago、Lihu Chen、Francesca Toni |
| **所属机构** | （详见原文） |
| **顶级机构标签** | Mila |
| **发布时间** | 2026-08-19T15:03:44Z |
| **关键词** | `Agentic` |
| **原文链接** | [http://arxiv.org/abs/2608.19002v1](http://arxiv.org/abs/2608.19002v1) |

**📝 摘要概括：**

> 最近出现了一些争论，这些争论是代理人工智能提高性能以及帮助可解释性和用户参与度的有用方法。例如， LLM授权的代理人可以在内部（与自己）和/或外部（与其他代理人）进行辩论。总体而言，我们的研究表明，辩论语义学是辩论驱动型人工智能中有原则的法官的理想候选者。

</details>

<details>
<summary><b>9. rEDMRec: Distilling Large Language Model Reasoning into an Editable Experience Memory for Recommendation</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Minh Hoang Nguyen、Tung Le、Huy Tien Nguyen |
| **所属机构** | （详见原文） |
| **顶级机构标签** | Amazon、TRI |
| **发布时间** | 2026-08-19T14:17:34Z |
| **关键词** | `Reasoning` · `RAG` · `Memory` |
| **原文链接** | [http://arxiv.org/abs/2608.18952v1](http://arxiv.org/abs/2608.18952v1) |

**📝 摘要概括：**

> 大型语言模型可以通过明确推理用户历史记录和候选项目（例如，提取用户的偏好或解释为什么一个项目比另一个项目更适合）来提高推荐质量，而不是将历史记录直接映射到排名列表。然而，这种推理在每次排名请求中重复都是昂贵的，一旦产生，通常会消耗一次并丢弃，使其在未来不可重复使用……

</details>

<details>
<summary><b>10. Training-Free Inference-Time Self-Reflection and Cost-Bounded Early Stopping for Large Language Models</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Wei Yu、Suxing Liu、Minjie Yu、Jiahao Wang、Zhijian Zheng 等（共 7 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-08-19T13:09:57Z |
| **关键词** | `Multi-Agent` · `Reasoning` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2608.18884v1](http://arxiv.org/abs/2608.18884v1) |

**📝 摘要概括：**

> 推理LLM （例如GRPO ）的强化学习培训成本高昂，需要一个可控的环境，为完整的培训管道做出一切贡献。我们推荐EvoResearcher ，这是一种无需训练的推理时间协议，可为单个冻结的LLM骨干网添加成本受限的自我反射。在清洁BBH上，该方案不会将准确率提高到95% Wilson区间之外；其价值是有成本限制的自我验证，具有…

</details>

<details>
<summary><b>11. DentAgent: Evidence-Centric Multi-Agent Coordination for Multimodal Dental Reasoning</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Zijie Meng、Xiwei Dai、Yixuan Tang、Jin Hao、Yang Feng 等（共 9 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-08-19T12:58:03Z |
| **关键词** | `Multi-Agent` · `Agentic` · `Reasoning` · `RAG` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2608.18878v1](http://arxiv.org/abs/2608.18878v1) |

**📝 摘要概括：**

> 口腔疾病影响着全球数十亿人，这凸显了对准确可靠的牙科评估的迫切需求，该评估整合了来自领域知识、X光片、口腔内照片和3D牙科数据的异质证据。大多数现有的牙科人工智能系统仍然是特定于模式或任务的。在四个基准中， DentAgent表现出领先的表现，甚至在多方面超过高级专家17.3个百分点。

</details>

<details>
<summary><b>12. SkillGate: Training In-Policy Skill Selection in Long-Horizon Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Qingyao Li、Wenxiang Jiao、Shuai Shao、Kangning Zhang、Yuan Lu 等（共 9 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | CAS、TRI |
| **发布时间** | 2026-08-19T12:24:03Z |
| **关键词** | `Agentic` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2608.18852v1](http://arxiv.org/abs/2608.18852v1) |

**📝 摘要概括：**

> 代理框架越来越多地将程序知识打包为技能：代理按需阅读的指令文件，而公共图书馆现在拥有成千上万的指令文件。因此，要阅读的技能已成为政策本身在情节中间做出的决定，但没有现有的信号对其进行训练。在16名候选人名单下的五个代理基准上， SkillGate将9B政策从40.8%提高到53.2%的试用成功率，远远领先于相同的动向……

</details>

<details>
<summary><b>13. Verifiable abstention makes AI leak diagnosis accountable in water distribution networks</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Tianwei Mu、Yue Wang、Mingzhe Yuan、Manhong Huang、Wenhong Wang 等（共 11 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | CAS、TRI |
| **发布时间** | 2026-08-19T11:54:27Z |
| **关键词** | `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2608.18836v1](http://arxiv.org/abs/2608.18836v1) |

**📝 摘要概括：**

> 公用事业公司因泄漏而损失了大量处理过的水，但很少信任人工智能本地化人员来派遣工作人员：到处猜测都不能证明挖掘是合理的。差距在于问责制，而不是准确性：没有任何方法可以证明它何时不应该采取行动。负责任的弃权为自主水基础设施运营提供了一条可防御的途径。

</details>

## 🗄️ 历史归档

| 日期 | 论文数 | 报告链接 |
|------|--------|----------|
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

## 🏛️ 顶级机构覆盖范围

覆盖超过 **70 个**顶级 AI 机构，包括：

- **科技公司：** Microsoft、Google DeepMind、OpenAI、Anthropic、Meta AI、NVIDIA、Baidu、Alibaba、ByteDance 等
- **北美顶级大学：** MIT、Stanford、CMU、UC Berkeley、Harvard、Princeton、Cornell、Caltech 等
- **中国顶级大学/机构：** 清华大学、北京大学、浙大、上交大、复旦、中科院、MSRA 等
- **欧洲/其他：** Oxford、Cambridge、ETH Zurich、Mila、NUS、KAIST 等

---

*由 [clawBot DailyFindings](https://github.com/Jacob-biu/clawBot) 自动维护 | 最后更新：2026-08-20 22:25 UTC*
