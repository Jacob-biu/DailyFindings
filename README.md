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

## 📅 今日论文 — 2026-08-12　　[→ 查看完整报告](daily/2026-08-12.md)

> 共筛选出 **13** 篇论文 | 更新于 2026-08-12 22:39 UTC

### 论文目录与概要

| # | 论文标题 | 核心概要 | 来源机构 | 第一作者 |
|---|---------|---------|---------|--------|
| 1 | [Long-Horizon AI Research for Grothendieck Constant: A Case S…](http://arxiv.org/abs/2608.11195v1) | 人工智能代理越来越多地用于数学研究，但通常不清楚如何有效地使用它们。为此，我们提出了一个广泛的案例研究，研究如何使用人工智能来改善Grothendieck常数$ K_G $的界限，该常数捕捉了组合问题… | CAS | Alan Li |
| 2 | [Test-Time Self-Evolving GUI Visual Grounding via Reflection-…](http://arxiv.org/abs/2608.11191v1) | GUI可视化接地是GUI代理的基本功能。现有模型通常在部署后冻结其参数，限制其适应看不见的接口的能力。该代码将被释放。 | MIT | Shiyu Xuan |
| 3 | [Scheduling Mixed RL Rollouts Beyond Prefix Locality](http://arxiv.org/abs/2608.11152v1) | 大型语言模型（ LLM ）的现代强化学习（ RL ）训练后管道越来越多地将跨多个域和反馈范式的部署工作负载结合起来。前缀感知路由通过缓存重用和负载平衡提高了推理效率，但它不能控制异构部署会话如何竞争K… | HIT | Zetao Hong |
| 4 | [Why Does CLAUDE.md Keep Growing? Catastrophic Remembering in…](http://arxiv.org/abs/2608.11095v1) | 像CLAUDE.md这样的代理编码README在实际存储库中不受限制地生长，只有在存储库退出或有人批发重写文件时才会停止。我们将其追溯到不完美的回忆：追加指令总是很便宜，但一旦指令的理由消失，在不冒正… | MIT、TRI | Kushal Chakrabarti |
| 5 | [SkillZip: Evaluation-Free Skill Compression for Self-Evolvin…](http://arxiv.org/abs/2608.11079v1) | 自我进化代理通过附加成功的程序和故障修复来积累可重复使用的技能。随着时间的推移，相同的要求通常会在几个分支、示例和警告中重复陈述，而常见的操作序列则被复制而不是重复使用。通过全面的实验评估，我们证明了… | NTU、TRI | Xiaofan Bai |
| 6 | [R4DSG: Relative 4D Scene Graph Memory for Object-Centric Que…](http://arxiv.org/abs/2608.11017v1) | 长视野的自我中心视频是可穿戴式AI助手的丰富基板，但以对象为中心的问题，例如物品移动的位置、最后一次更改状态的时间或为什么重新定位仍然很困难，因为基于字幕和转录的记忆很少保留持久的对象身份或结构化的空… | TRI | Ke Ma |
| 7 | [IO Factory: Simulating AI-Enabled Influence Campaigns at Sca…](http://arxiv.org/abs/2608.10920v1) | 我们推出了IO Factory ，这是一个人工智能驱动的框架，用于将信息和影响活动模拟为完全集成、可追溯的流程。数字操纵的威胁现在已经超越了从单个语言模型到人工智能群体的说服性文本，即适应平台反馈并将… | HIT | Lukasz Olejnik |
| 8 | [ComBodied Agents: a New Paradigm of Human-Centric Agentic AI](http://arxiv.org/abs/2608.10915v1) | 老年人错过药物剂量后，软件代理可以发送另一个提醒，具体代理可以携带药物。然而，既不能解释这个人是否忘记、困惑、有副作用或故意拒绝，也不能解释什么样的支持是合适的。组合智能体将智能体AI从外部任务完成转… | TRI | Qianggang Ding |
| 9 | [GitSkills: A Dataset of Agent Skills on GitHub](http://arxiv.org/abs/2608.10906v1) | 代理技能是包含SKILL.md文件的文件夹，其中包含语言模型代理的说明，可选择伴随脚本和参考文件。当座席判断任务与技能描述匹配时，会加载技能。单个自包含的SQLite文件支持对代理技能的采用、重用、结… | Anthropic、MIT | Giuseppe Destefanis |
| 10 | [Partially Observable Learning for Multi-Platform Dispatch Op…](http://arxiv.org/abs/2608.10897v1) | 即时派送平台已成为城市物流的重要组成部分，越来越依赖众包派送员来完成高度动态的订单。在现实世界中，由于隐私和运营限制，派送员并不局限于单个平台，可以同时为多个平台提供服务，而每个平台只能观察自己的订单… | MIT | Fengming Yao |
| 11 | [VibeLifeBench: Can Your Life Agent Be Proactive and Persiste…](http://arxiv.org/abs/2608.10875v1) | 大型语言模型（ LLM ）代理越来越多地被部署为个人助理。然而，现有的评估大多在静态环境中使用简短、自包含的请求。我们将开源所有任务、环境和评估框架。 | TRI | Xiaohongshu Inc |
| 12 | [MIRA: Medical Image Reflection for Agentic Diagnosis](http://arxiv.org/abs/2608.10827v1) | 医学视觉代理可以使用工具来检查图像和检索外部知识，但不分青红皂白地使用工具可能会引入嘈杂或误导性的证据。因此，可靠的诊断不仅需要获得额外的观察结果，还需要验证工具操作是否必要，以及由此产生的证据是否支… | CAS、TRI | Shengzhi Wang |
| 13 | [ChemWorld: Programmable Chemical Worlds for Controlled and R…](http://arxiv.org/abs/2608.10792v1) | 自主化学越来越依赖于主体可以反复行动、观察和适应的环境。物理实验室提供了必要的实物证据，但重复成本高昂，难以用于紧密匹配的干预措施，而大多数数字环境在很大程度上保持了基础实验世界的固定。我们推出了Ch… | CAS | Jiangjie Qiu |

### 论文详情

<details>
<summary><b>1. Long-Horizon AI Research for Grothendieck Constant: A Case Study in Human-AI Mathematical Collaboration</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Alan Li、Rahul Saha、Anton Xue、Swarat Chaudhuri、Adam Klivans 等（共 7 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | CAS |
| **发布时间** | 2026-08-11T17:53:48Z |
| **关键词** | `AI Agent` |
| **原文链接** | [http://arxiv.org/abs/2608.11195v1](http://arxiv.org/abs/2608.11195v1) |

**📝 摘要概括：**

> 人工智能代理越来越多地用于数学研究，但通常不清楚如何有效地使用它们。为此，我们提出了一个广泛的案例研究，研究如何使用人工智能来改善Grothendieck常数$ K_G $的界限，该常数捕捉了组合问题与其连续松弛之间的硬度。我们详细讨论了将人工智能用于数学研究的经验，特别是其优势……

</details>

<details>
<summary><b>2. Test-Time Self-Evolving GUI Visual Grounding via Reflection-Guided On-Policy Self-Distillation</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Shiyu Xuan、Zechao Li |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT |
| **发布时间** | 2026-08-11T17:50:25Z |
| **关键词** | `Reasoning` · `Reinforcement Learning` · `RAG` · `Benchmark` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2608.11191v1](http://arxiv.org/abs/2608.11191v1) |

**📝 摘要概括：**

> GUI可视化接地是GUI代理的基本功能。现有模型通常在部署后冻结其参数，限制其适应看不见的接口的能力。该代码将被释放。

</details>

<details>
<summary><b>3. Scheduling Mixed RL Rollouts Beyond Prefix Locality</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Zetao Hong、Song Yuan、Yuanhao Ding、Yibo Zhu、Daxin Jiang 等（共 7 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | HIT |
| **发布时间** | 2026-08-11T17:10:50Z |
| **关键词** | `Agentic` · `Reinforcement Learning` |
| **原文链接** | [http://arxiv.org/abs/2608.11152v1](http://arxiv.org/abs/2608.11152v1) |

**📝 摘要概括：**

> 大型语言模型（ LLM ）的现代强化学习（ RL ）训练后管道越来越多地将跨多个域和反馈范式的部署工作负载结合起来。前缀感知路由通过缓存重用和负载平衡提高了推理效率，但它不能控制异构部署会话如何竞争KV缓存容量。在相匹配的50次迭代Step3.7实验中，它将推出吞吐量提高了35.6% ，并且……

</details>

<details>
<summary><b>4. Why Does CLAUDE.md Keep Growing? Catastrophic Remembering in Agentic Coding</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Kushal Chakrabarti |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-08-11T16:00:55Z |
| **关键词** | `Agentic` · `Reasoning` |
| **原文链接** | [http://arxiv.org/abs/2608.11095v1](http://arxiv.org/abs/2608.11095v1) |

**📝 摘要概括：**

> 像CLAUDE.md这样的代理编码README在实际存储库中不受限制地生长，只有在存储库退出或有人批发重写文件时才会停止。我们将其追溯到不完美的回忆：追加指令总是很便宜，但一旦指令的理由消失，在不冒正确性回归风险的情况下删除指令就会在| D |指令的提示中花费O (2 ^ | D |)。如果英语是新代码，为什么我们还没有评论？

</details>

<details>
<summary><b>5. SkillZip: Evaluation-Free Skill Compression for Self-Evolving Agents by Discovering Reusable Structure</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Xiaofan Bai、Hongqiang Lin、Chao Liu、Yantao Zhang、Xuan Jin 等（共 7 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | NTU、TRI |
| **发布时间** | 2026-08-11T15:41:19Z |
| **关键词** | `RAG` · `Evaluation` · `Workflow` |
| **原文链接** | [http://arxiv.org/abs/2608.11079v1](http://arxiv.org/abs/2608.11079v1) |

**📝 摘要概括：**

> 自我进化代理通过附加成功的程序和故障修复来积累可重复使用的技能。随着时间的推移，相同的要求通常会在几个分支、示例和警告中重复陈述，而常见的操作序列则被复制而不是重复使用。通过全面的实验评估，我们证明了SkillZip在压缩性能、可推广性和成本开销方面的有效性和优越性。

</details>

<details>
<summary><b>6. R4DSG: Relative 4D Scene Graph Memory for Object-Centric Question Answering in Long Egocentric Video</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Ke Ma、Yamin Mao、Weiming Li、Shuai Tan、Yijie Zhong 等（共 8 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-08-11T15:00:15Z |
| **关键词** | `RAG` · `Retrieval` · `Evaluation` · `Embodied AI` · `Memory` |
| **原文链接** | [http://arxiv.org/abs/2608.11017v1](http://arxiv.org/abs/2608.11017v1) |

**📝 摘要概括：**

> 长视野的自我中心视频是可穿戴式AI助手的丰富基板，但以对象为中心的问题，例如物品移动的位置、最后一次更改状态的时间或为什么重新定位仍然很困难，因为基于字幕和转录的记忆很少保留持久的对象身份或结构化的空间变化。现有的长视频QA方法主要强调时间接地和剪辑检索，而现有的3D场景图方法……

</details>

<details>
<summary><b>7. IO Factory: Simulating AI-Enabled Influence Campaigns at Scale</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Lukasz Olejnik、Wenchao Dong、Jonas R. Kunst、Signe Riemer-Sørensen、Tobias Herb 等（共 7 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | HIT |
| **发布时间** | 2026-08-11T13:43:48Z |
| **关键词** | `Planning` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2608.10920v1](http://arxiv.org/abs/2608.10920v1) |

**📝 摘要概括：**

> 我们推出了IO Factory ，这是一个人工智能驱动的框架，用于将信息和影响活动模拟为完全集成、可追溯的流程。数字操纵的威胁现在已经超越了从单个语言模型到人工智能群体的说服性文本，即适应平台反馈并将有组织的活动伪装成普通的社交互动的持续的协调代理群体。通过记录演员、目标、行动构造……

</details>

<details>
<summary><b>8. ComBodied Agents: a New Paradigm of Human-Centric Agentic AI</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Qianggang Ding、Xingyao Wang、Rui Feng、Zhibin Wang、Feixiang Wang 等（共 22 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-08-11T13:35:58Z |
| **关键词** | `Agentic` · `RAG` · `Benchmark` · `Evaluation` · `Embodied AI` |
| **原文链接** | [http://arxiv.org/abs/2608.10915v1](http://arxiv.org/abs/2608.10915v1) |

**📝 摘要概括：**

> 老年人错过药物剂量后，软件代理可以发送另一个提醒，具体代理可以携带药物。然而，既不能解释这个人是否忘记、困惑、有副作用或故意拒绝，也不能解释什么样的支持是合适的。组合智能体将智能体AI从外部任务完成转变为持续的人类利益。

</details>

<details>
<summary><b>9. GitSkills: A Dataset of Agent Skills on GitHub</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Giuseppe Destefanis、Daniel Graziotin、Matteo Vaccargiu、Marco Ortu |
| **所属机构** | （详见原文） |
| **顶级机构标签** | Anthropic、MIT |
| **发布时间** | 2026-08-11T13:28:27Z |
| **关键词** | — |
| **原文链接** | [http://arxiv.org/abs/2608.10906v1](http://arxiv.org/abs/2608.10906v1) |

**📝 摘要概括：**

> 代理技能是包含SKILL.md文件的文件夹，其中包含语言模型代理的说明，可选择伴随脚本和参考文件。当座席判断任务与技能描述匹配时，会加载技能。单个自包含的SQLite文件支持对代理技能的采用、重用、结构、作者身份、维护和安全性的研究。

</details>

<details>
<summary><b>10. Partially Observable Learning for Multi-Platform Dispatch Optimization</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Fengming Yao、Man Luo |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT |
| **发布时间** | 2026-08-11T13:20:12Z |
| **关键词** | `Multi-Agent` · `Reinforcement Learning` |
| **原文链接** | [http://arxiv.org/abs/2608.10897v1](http://arxiv.org/abs/2608.10897v1) |

**📝 摘要概括：**

> 即时派送平台已成为城市物流的重要组成部分，越来越依赖众包派送员来完成高度动态的订单。在现实世界中，由于隐私和运营限制，派送员并不局限于单个平台，可以同时为多个平台提供服务，而每个平台只能观察自己的订单和派送员的互动。广泛的实验表明， POLO consi……

</details>

<details>
<summary><b>11. VibeLifeBench: Can Your Life Agent Be Proactive and Persistent in a Living World?</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Xiaohongshu Inc |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-08-11T12:52:38Z |
| **关键词** | `Benchmark` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2608.10875v1](http://arxiv.org/abs/2608.10875v1) |

**📝 摘要概括：**

> 大型语言模型（ LLM ）代理越来越多地被部署为个人助理。然而，现有的评估大多在静态环境中使用简短、自包含的请求。我们将开源所有任务、环境和评估框架。

</details>

<details>
<summary><b>12. MIRA: Medical Image Reflection for Agentic Diagnosis</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Shengzhi Wang、Jun Yang、Kai Wu、Xiaozhong Ji、Yiwen Ye 等（共 14 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | CAS、TRI |
| **发布时间** | 2026-08-11T11:57:27Z |
| **关键词** | `Agentic` · `Reasoning` · `Reinforcement Learning` · `RAG` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2608.10827v1](http://arxiv.org/abs/2608.10827v1) |

**📝 摘要概括：**

> 医学视觉代理可以使用工具来检查图像和检索外部知识，但不分青红皂白地使用工具可能会引入嘈杂或误导性的证据。因此，可靠的诊断不仅需要获得额外的观察结果，还需要验证工具操作是否必要，以及由此产生的证据是否支持当前的假设。项目页面： https://MIRA-VL.github.io/

</details>

<details>
<summary><b>13. ChemWorld: Programmable Chemical Worlds for Controlled and Replayable Agent Experimentation</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Jiangjie Qiu、Yijun Li、Xiaonan Wang |
| **所属机构** | （详见原文） |
| **顶级机构标签** | CAS |
| **发布时间** | 2026-08-11T10:53:39Z |
| **关键词** | — |
| **原文链接** | [http://arxiv.org/abs/2608.10792v1](http://arxiv.org/abs/2608.10792v1) |

**📝 摘要概括：**

> 自主化学越来越依赖于主体可以反复行动、观察和适应的环境。物理实验室提供了必要的实物证据，但重复成本高昂，难以用于紧密匹配的干预措施，而大多数数字环境在很大程度上保持了基础实验世界的固定。我们推出了ChemWorld ，这是一种可编程的化学环境，其中可重复使用的工艺和观测组件……

</details>

## 🗄️ 历史归档

| 日期 | 论文数 | 报告链接 |
|------|--------|----------|
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
| 2026-07-12 | 0 篇 | [2026-07-12.md](daily/2026-07-12.md) |

## 🏛️ 顶级机构覆盖范围

覆盖超过 **70 个**顶级 AI 机构，包括：

- **科技公司：** Microsoft、Google DeepMind、OpenAI、Anthropic、Meta AI、NVIDIA、Baidu、Alibaba、ByteDance 等
- **北美顶级大学：** MIT、Stanford、CMU、UC Berkeley、Harvard、Princeton、Cornell、Caltech 等
- **中国顶级大学/机构：** 清华大学、北京大学、浙大、上交大、复旦、中科院、MSRA 等
- **欧洲/其他：** Oxford、Cambridge、ETH Zurich、Mila、NUS、KAIST 等

---

*由 [clawBot DailyFindings](https://github.com/Jacob-biu/clawBot) 自动维护 | 最后更新：2026-08-12 22:39 UTC*
