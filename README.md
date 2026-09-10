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

## 📅 今日论文 — 2026-09-10　　[→ 查看完整报告](daily/2026-09-10.md)

> 共筛选出 **8** 篇论文 | 更新于 2026-09-10 23:43 UTC

### 论文目录与概要

| # | 论文标题 | 核心概要 | 来源机构 | 第一作者 |
|---|---------|---------|---------|--------|
| 1 | [JarvisGUI: Towards Cross-Device GUI Agents with Dynamic Task…](http://arxiv.org/abs/2609.10451v1) | 真实世界的GUI使用通常涉及跨多个设备和平台的工作流，需要传输中间结果、维护共享状态以及跨异构环境的协调。然而，现有的GUI基准压倒性地评估了单个设备上的代理，静态定义的任务，因此这种跨设备功能在很大… | NTU | Zixiang Chen |
| 2 | [TRACE: Training Reasoning Agents for Causal Exploration with…](http://arxiv.org/abs/2609.10315v1) | 具有可验证奖励的强化学习（ RLVR ）在数学和代码等领域具有先进的语言模型推理，在这些领域中，客观答案的检查成本较低。复杂数据的诊断推理缺乏这一优势：确定异常的真正原因通常需要昂贵的专家调查，并且在… | TRI | Rui Sun |
| 3 | [GANDR: Claim Auditing for Verifiable Legal Answer Generation](http://arxiv.org/abs/2609.10293v1) | 在法律实践等高风险领域，语言模型答案只有在读者可以针对系统引用的来源验证每项索赔时才有用。当前的接地发电管道作为一个整体对答案进行评分，因此正确的结论可以建立在捏造或松散匹配的引用上，并且仍然得分很高… | MIT、TRI | Chen Qian |
| 4 | [What Should an Agent Forget? Separating What Is Stored from …](http://arxiv.org/abs/2609.10263v1) | 持久的语言代理需要存储的经验，以便随时保持可用，而每个答案都需要适合特定问题的证据。被取代的事实可能会误导当前状态的答案，并且对于历史查询仍然是必不可少的。保留历史记录，同时有选择地控制其使用，为适应… | TRI | Yuhang Li |
| 5 | [Can AI Agents Deliver Verifiable Network-Wide Outcomes Acros…](http://arxiv.org/abs/2609.10181v1) | 人工智能代理越来越多地参与网络自动化，他们可以通过中介操作界面启动配置更改并评估结果状态。尽管如此，运营网络通常跨越许多设备和管理域。对照干预措施进一步表明，当其他令人满意的观察结果来源错误、已被替换… | MIT | Tianzhu Zhang |
| 6 | [Kernel-Managed Shared Memory for System-Wide Personalization](http://arxiv.org/abs/2609.10144v1) | 当人工智能系统能够适应使用它们的人时，它们会变得更有用，但在多智能体系统中，一个智能体学习的有用上下文通常对其他人不可用。我们提出了内核管理的共享内存，这是一种系统级抽象，其中专业代理编写结构化的标记… | Mila、TRI | Ryan Lum |
| 7 | [Agent-Based ML-LLM Fusion with Self-Optimizing Prompts for P…](http://arxiv.org/abs/2609.10135v1) | 为了解决旅游气象服务中情境化不足、泛化能力弱、情景适应性差等问题，我们提出了SmartWeatherAgent--一种将意图识别、危害预测和推理增强生成相结合的统一三阶段架构。该系统将基于规则的方法与… | HIT | Shuai Yan |
| 8 | [RAP: Research Attention Prediction Reveals Target-Conditione…](http://arxiv.org/abs/2609.10092v1) | 大型语言模型（ LLM ）越来越多地充当研究代理，但由于评论和研究想法缺乏唯一可验证的结果，因此难以评估其跟踪研究注意力转移的能力。我们引入了研究注意力预测（ RAP ） ，这是一个滚动基准，涵盖27… | MIT、CAS | Yingqian Wu |

### 论文详情

<details>
<summary><b>1. JarvisGUI: Towards Cross-Device GUI Agents with Dynamic Task Composition</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Zixiang Chen、Yuheng Lu、Zihao Cheng、Zeming Liu、Jizeng Bai 等（共 11 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | NTU |
| **发布时间** | 2026-09-09T16:59:59Z |
| **关键词** | `Reasoning` · `Benchmark` · `Workflow` |
| **原文链接** | [http://arxiv.org/abs/2609.10451v1](http://arxiv.org/abs/2609.10451v1) |

**📝 摘要概括：**

> 真实世界的GUI使用通常涉及跨多个设备和平台的工作流，需要传输中间结果、维护共享状态以及跨异构环境的协调。然而，现有的GUI基准压倒性地评估了单个设备上的代理，静态定义的任务，因此这种跨设备功能在很大程度上没有经过审查，导致对代理的评估过于乐观……

</details>

<details>
<summary><b>2. TRACE: Training Reasoning Agents for Causal Exploration with Synthesized Rewards</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Rui Sun、Zhan Shi、Bing He |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-09-09T15:21:47Z |
| **关键词** | `Reasoning` · `Reinforcement Learning` · `Fine-tuning` · `Simulation` |
| **原文链接** | [http://arxiv.org/abs/2609.10315v1](http://arxiv.org/abs/2609.10315v1) |

**📝 摘要概括：**

> 具有可验证奖励的强化学习（ RLVR ）在数学和代码等领域具有先进的语言模型推理，在这些领域中，客观答案的检查成本较低。复杂数据的诊断推理缺乏这一优势：确定异常的真正原因通常需要昂贵的专家调查，并且在事后可能仍然模棱两可。更广泛地说，基于模拟的验证可以做出其他模糊的诊断……

</details>

<details>
<summary><b>3. GANDR: Claim Auditing for Verifiable Legal Answer Generation</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Chen Qian、Yimeng Wang、Yu Chen、Lingfei Wu、Andreas Stathopoulos |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-09-09T15:08:09Z |
| **关键词** | `Reasoning` · `Retrieval` · `Benchmark` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2609.10293v1](http://arxiv.org/abs/2609.10293v1) |

**📝 摘要概括：**

> 在法律实践等高风险领域，语言模型答案只有在读者可以针对系统引用的来源验证每项索赔时才有用。当前的接地发电管道作为一个整体对答案进行评分，因此正确的结论可以建立在捏造或松散匹配的引用上，并且仍然得分很高。如有需要，可提供代码。

</details>

<details>
<summary><b>4. What Should an Agent Forget? Separating What Is Stored from What Is Used</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Yuhang Li、Yuchen Li |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-09-09T14:48:09Z |
| **关键词** | `Reasoning` · `Retrieval` · `Memory` |
| **原文链接** | [http://arxiv.org/abs/2609.10263v1](http://arxiv.org/abs/2609.10263v1) |

**📝 摘要概括：**

> 持久的语言代理需要存储的经验，以便随时保持可用，而每个答案都需要适合特定问题的证据。被取代的事实可能会误导当前状态的答案，并且对于历史查询仍然是必不可少的。保留历史记录，同时有选择地控制其使用，为适应不断变化的事实和未来问题提供了一种实用的方法。

</details>

<details>
<summary><b>5. Can AI Agents Deliver Verifiable Network-Wide Outcomes Across Authority Boundaries?</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Tianzhu Zhang、Chih-Kai Huang、Meikang Qiu |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT |
| **发布时间** | 2026-09-09T13:51:15Z |
| **关键词** | `AI Agent` · `RAG` |
| **原文链接** | [http://arxiv.org/abs/2609.10181v1](http://arxiv.org/abs/2609.10181v1) |

**📝 摘要概括：**

> 人工智能代理越来越多地参与网络自动化，他们可以通过中介操作界面启动配置更改并评估结果状态。尽管如此，运营网络通常跨越许多设备和管理域。对照干预措施进一步表明，当其他令人满意的观察结果来源错误、已被替换或陈旧时， EvidenceNet拒绝完成。

</details>

<details>
<summary><b>6. Kernel-Managed Shared Memory for System-Wide Personalization</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Ryan Lum、Yongfeng Zhang |
| **所属机构** | （详见原文） |
| **顶级机构标签** | Mila、TRI |
| **发布时间** | 2026-09-09T13:20:47Z |
| **关键词** | `Multi-Agent` · `RAG` · `Retrieval` · `Memory` |
| **原文链接** | [http://arxiv.org/abs/2609.10144v1](http://arxiv.org/abs/2609.10144v1) |

**📝 摘要概括：**

> 当人工智能系统能够适应使用它们的人时，它们会变得更有用，但在多智能体系统中，一个智能体学习的有用上下文通常对其他人不可用。我们提出了内核管理的共享内存，这是一种系统级抽象，其中专业代理编写结构化的标记内存，而代理系统内核而不是单个代理管理检索、隐私强制和提示注入。这些结果表明……

</details>

<details>
<summary><b>7. Agent-Based ML-LLM Fusion with Self-Optimizing Prompts for Plateau Weather Alerts</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Shuai Yan、Yang Xu、Shan He |
| **所属机构** | （详见原文） |
| **顶级机构标签** | HIT |
| **发布时间** | 2026-09-09T13:15:46Z |
| **关键词** | `Reasoning` · `RAG` |
| **原文链接** | [http://arxiv.org/abs/2609.10135v1](http://arxiv.org/abs/2609.10135v1) |

**📝 摘要概括：**

> 为了解决旅游气象服务中情境化不足、泛化能力弱、情景适应性差等问题，我们提出了SmartWeatherAgent--一种将意图识别、危害预测和推理增强生成相结合的统一三阶段架构。该系统将基于规则的方法与大型语言模型融合在一起，在多个粒度上解析查询，并采用了丰富了高地特定功能的LightGBM模型……

</details>

<details>
<summary><b>8. RAP: Research Attention Prediction Reveals Target-Conditioned Evidence Acquisition Biases</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Yingqian Wu、Jingcong Liang、Siyuan Wang、Zhenfei Yin、Philip Torr 等（共 7 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、CAS、TRI |
| **发布时间** | 2026-09-09T12:15:14Z |
| **关键词** | `LLM Agent` · `RAG` · `Benchmark` · `Fine-tuning` |
| **原文链接** | [http://arxiv.org/abs/2609.10092v1](http://arxiv.org/abs/2609.10092v1) |

**📝 摘要概括：**

> 大型语言模型（ LLM ）越来越多地充当研究代理，但由于评论和研究想法缺乏唯一可验证的结果，因此难以评估其跟踪研究注意力转移的能力。我们引入了研究注意力预测（ RAP ） ，这是一个滚动基准，涵盖278个AI/ML领域和1,390个情节。对已实现结果的微调将Qwen3-4B的预测Spearman相关性提高了0.105 ，用于LAT...

</details>

## 🗄️ 历史归档

| 日期 | 论文数 | 报告链接 |
|------|--------|----------|
| 2026-09-10 | 8 篇 | [2026-09-10.md](daily/2026-09-10.md) |
| 2026-09-09 | 12 篇 | [2026-09-09.md](daily/2026-09-09.md) |
| 2026-09-08 | 0 篇 | [2026-09-08.md](daily/2026-09-08.md) |
| 2026-09-07 | 0 篇 | [2026-09-07.md](daily/2026-09-07.md) |
| 2026-09-06 | 0 篇 | [2026-09-06.md](daily/2026-09-06.md) |
| 2026-09-05 | 0 篇 | [2026-09-05.md](daily/2026-09-05.md) |
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

## 🏛️ 顶级机构覆盖范围

覆盖超过 **70 个**顶级 AI 机构，包括：

- **科技公司：** Microsoft、Google DeepMind、OpenAI、Anthropic、Meta AI、NVIDIA、Baidu、Alibaba、ByteDance 等
- **北美顶级大学：** MIT、Stanford、CMU、UC Berkeley、Harvard、Princeton、Cornell、Caltech 等
- **中国顶级大学/机构：** 清华大学、北京大学、浙大、上交大、复旦、中科院、MSRA 等
- **欧洲/其他：** Oxford、Cambridge、ETH Zurich、Mila、NUS、KAIST 等

---

*由 [clawBot DailyFindings](https://github.com/Jacob-biu/clawBot) 自动维护 | 最后更新：2026-09-10 23:43 UTC*
