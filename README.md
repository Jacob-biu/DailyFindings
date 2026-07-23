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

## 📅 今日论文 — 2026-07-23　　[→ 查看完整报告](daily/2026-07-23.md)

> 共筛选出 **6** 篇论文 | 更新于 2026-07-23 22:55 UTC

### 论文目录与概要

| # | 论文标题 | 核心概要 | 来源机构 | 第一作者 |
|---|---------|---------|---------|--------|
| 1 | [PoTRE: Test-Time Reasoning inspired by Cognitive Heterogenei…](http://arxiv.org/abs/2607.20268v1) | 虽然大型语言模型（ LLM ）在许多任务中表现出色，但它们经常难以进行需要长期规划和迭代纠错的复杂推理。此外，当模型遇到新颖的抽象或严格的领域约束时，标准的单流提示证明是脆弱的。我们证明，与…相比，这… | HIT、Mila | Anmol Kankariya |
| 2 | [The Ethics of Autonomous AI Agents for Offensive Security](http://arxiv.org/abs/2607.20255v1) | 由LLM驱动的自治代理正在重塑攻击性安全。与传统的渗透测试工具（确定性，范围狭窄，由训练有素的从业人员操作）不同，代理安全工具在三个独立的维度上表现出{不确定性}。我们还研究这项技术对利益相关者的影响… | TRI | Andreas Happe |
| 3 | [Small, Free, and Effective: Orchestrating Open-Weight Small …](http://arxiv.org/abs/2607.20216v1) | 恶意软件分析需要快速解读跨越文件系统、网络和流程行为的复杂引爆报告。虽然大型语言模型（ LLM ）展示了令人印象深刻的技术制品解释能力，但封闭权重前沿模型的不透明性和不断上升的API成本激发了对开放权… | HIT、TRI | Adel ElZemity |
| 4 | [Autonomous Collaborative Learning Among an Ensemble of Tsetl…](http://arxiv.org/abs/2607.20124v1) | Tsetlin Machine （ TM ）是一种基于规则的机器学习算法，由双动作Tsetlin自动机（ TA ）的集合组成，该集合通过随机反馈从布尔输入协同形成合取逻辑子句。尽管最近很少有研究检查T… | TRI | Yehuda Rudin |
| 5 | [PRO-LONG: Programmatic Memory Enables Long-Horizon Reasoning](http://arxiv.org/abs/2607.20064v1) | 长期任务需要持续的感知、推理和探索，这对大型语言模型（ LLM ）代理来说是一个持续的挑战。这种差距反映在他们在持续学习基准（如ARC-AGI-3 ）上的有限表现上，特别是在模型开箱即用时。相关代码和… | MIT、TRI | Alexis Fox |
| 6 | [EvoDRC: A Self-Evolving Agentic Framework for Automated DRC …](http://arxiv.org/abs/2607.20019v1) | 设计规则检查（ DRC ）封闭仍然是高级节点物理设计的主要瓶颈。虽然详细的路由器是规则感知的，但剩余设计规则违规（ DRV ）通常需要手动工程变更单迭代。对DAC26 DRC Benchmark的七个… | TRI | Bing-Yue Wu |

### 论文详情

<details>
<summary><b>1. PoTRE: Test-Time Reasoning inspired by Cognitive Heterogeneity</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Anmol Kankariya、Sercan Ö. Arık |
| **所属机构** | （详见原文） |
| **顶级机构标签** | HIT、Mila |
| **发布时间** | 2026-07-22T15:20:53Z |
| **关键词** | `Reasoning` · `Planning` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2607.20268v1](http://arxiv.org/abs/2607.20268v1) |

**📝 摘要概括：**

> 虽然大型语言模型（ LLM ）在许多任务中表现出色，但它们经常难以进行需要长期规划和迭代纠错的复杂推理。此外，当模型遇到新颖的抽象或严格的领域约束时，标准的单流提示证明是脆弱的。我们证明，与…相比，这种架构异构性使用相似或更少的推理令牌实现了改进的推理性能

</details>

<details>
<summary><b>2. The Ethics of Autonomous AI Agents for Offensive Security</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Andreas Happe、Jürgen Cito、Jasmin Wachter |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-07-22T15:13:15Z |
| **关键词** | `AI Agent` · `Agentic` |
| **原文链接** | [http://arxiv.org/abs/2607.20255v1](http://arxiv.org/abs/2607.20255v1) |

**📝 摘要概括：**

> 由LLM驱动的自治代理正在重塑攻击性安全。与传统的渗透测试工具（确定性，范围狭窄，由训练有素的从业人员操作）不同，代理安全工具在三个独立的维度上表现出{不确定性}。我们还研究这项技术对利益相关者的影响，并提供分层建议。

</details>

<details>
<summary><b>3. Small, Free, and Effective: Orchestrating Open-Weight Small Language Models to Outperform Single LLM for Malware Analysis</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Adel ElZemity、Shujun Li、Budi Arief |
| **所属机构** | （详见原文） |
| **顶级机构标签** | HIT、TRI |
| **发布时间** | 2026-07-22T14:36:10Z |
| **关键词** | `Multi-Agent` · `Reasoning` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2607.20216v1](http://arxiv.org/abs/2607.20216v1) |

**📝 摘要概括：**

> 恶意软件分析需要快速解读跨越文件系统、网络和流程行为的复杂引爆报告。虽然大型语言模型（ LLM ）展示了令人印象深刻的技术制品解释能力，但封闭权重前沿模型的不透明性和不断上升的API成本激发了对开放权重替代方案的探索。这些研究结果表明，以证据为基础的编排可以大大提高…

</details>

<details>
<summary><b>4. Autonomous Collaborative Learning Among an Ensemble of Tsetlin Machines with Consensus-Based Inference</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Yehuda Rudin、Osnat Keren、Michal Yemini、Alexander Fish |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-07-22T13:28:28Z |
| **关键词** | — |
| **原文链接** | [http://arxiv.org/abs/2607.20124v1](http://arxiv.org/abs/2607.20124v1) |

**📝 摘要概括：**

> Tsetlin Machine （ TM ）是一种基于规则的机器学习算法，由双动作Tsetlin自动机（ TA ）的集合组成，该集合通过随机反馈从布尔输入协同形成合取逻辑子句。尽管最近很少有研究检查TM联合学习，但更广泛的分布式和分散式TM学习领域在现有文献中没有受到太多关注，值得进一步探索。实验……

</details>

<details>
<summary><b>5. PRO-LONG: Programmatic Memory Enables Long-Horizon Reasoning</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Alexis Fox、Junlin Wang、Paul Rosu、Bhuwan Dhingra |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-07-22T12:11:51Z |
| **关键词** | `LLM Agent` · `Reasoning` · `RAG` · `Benchmark` · `Memory` |
| **原文链接** | [http://arxiv.org/abs/2607.20064v1](http://arxiv.org/abs/2607.20064v1) |

**📝 摘要概括：**

> 长期任务需要持续的感知、推理和探索，这对大型语言模型（ LLM ）代理来说是一个持续的挑战。这种差距反映在他们在持续学习基准（如ARC-AGI-3 ）上的有限表现上，特别是在模型开箱即用时。相关代码和日志可在https://github.com/alexisfox7/PRO-LONG上找到。

</details>

<details>
<summary><b>6. EvoDRC: A Self-Evolving Agentic Framework for Automated DRC Violation Repair</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Bing-Yue Wu、Chia-Tung Ho、Haoyu Yang、Brucek Khailany、Vidya A. Chhabria |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-07-22T10:59:46Z |
| **关键词** | `Agentic` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2607.20019v1](http://arxiv.org/abs/2607.20019v1) |

**📝 摘要概括：**

> 设计规则检查（ DRC ）封闭仍然是高级节点物理设计的主要瓶颈。虽然详细的路由器是规则感知的，但剩余设计规则违规（ DRV ）通常需要手动工程变更单迭代。对DAC26 DRC Benchmark的七个区块级设计的实验表明，与报告的基线相比， EvoDRC实现了73.5%的整体减排。

</details>

## 🗄️ 历史归档

| 日期 | 论文数 | 报告链接 |
|------|--------|----------|
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
| 2026-06-28 | 0 篇 | [2026-06-28.md](daily/2026-06-28.md) |
| 2026-06-27 | 0 篇 | [2026-06-27.md](daily/2026-06-27.md) |
| 2026-06-26 | 17 篇 | [2026-06-26.md](daily/2026-06-26.md) |
| 2026-06-25 | 11 篇 | [2026-06-25.md](daily/2026-06-25.md) |
| 2026-06-24 | 9 篇 | [2026-06-24.md](daily/2026-06-24.md) |
| 2026-06-23 | 15 篇 | [2026-06-23.md](daily/2026-06-23.md) |

## 🏛️ 顶级机构覆盖范围

覆盖超过 **70 个**顶级 AI 机构，包括：

- **科技公司：** Microsoft、Google DeepMind、OpenAI、Anthropic、Meta AI、NVIDIA、Baidu、Alibaba、ByteDance 等
- **北美顶级大学：** MIT、Stanford、CMU、UC Berkeley、Harvard、Princeton、Cornell、Caltech 等
- **中国顶级大学/机构：** 清华大学、北京大学、浙大、上交大、复旦、中科院、MSRA 等
- **欧洲/其他：** Oxford、Cambridge、ETH Zurich、Mila、NUS、KAIST 等

---

*由 [clawBot DailyFindings](https://github.com/Jacob-biu/clawBot) 自动维护 | 最后更新：2026-07-23 22:55 UTC*
