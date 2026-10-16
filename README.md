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

## 📅 今日论文 — 2026-10-16　　[→ 查看完整报告](daily/2026-10-16.md)

> 共筛选出 **8** 篇论文 | 更新于 2026-10-16 00:06 UTC

### 论文目录与概要

| # | 论文标题 | 核心概要 | 来源机构 | 第一作者 |
|---|---------|---------|---------|--------|
| 1 | [Co-Evolving Acting and Forecasting for Language Agents](http://arxiv.org/abs/2610.20597v1) | 培训语言代理受到长期推出的高成本的瓶颈，但标准的代理强化学习（ RL ）仅从终端标量奖励中学习，使得中间步骤的监督基本上没有使用。之前的工作通过估算每个步骤成功概率的价值目标或适合环境响应的观察目标来… | UIUC、CAS | Haofei Yu |
| 2 | [Price of Anarchy of First-Price Auctions in Agentic Markets](http://arxiv.org/abs/2610.20587v1) | 代理市场是一个去中心化的服务时间市场，人工智能代理商竞标要求每个用户提示。座席的出价基于其对提示的期望值，即对其响应的奖励减去其推断成本的期望值。我们使用在EmbedLLM提示路由数据集上模拟的战略出… | MIT、CAS | Shubhendu Trivedi |
| 3 | [Player-1: Learning to Play from Synthetic Experience](http://arxiv.org/abs/2610.20584v1) | 计算机使用代理在解释屏幕和执行键盘和鼠标操作方面表现出强大的能力。然而，游戏凭借其丰富的视觉世界和多样化的机制，仍然具有挑战性，并为通用数字控制提供了苛刻的下一步。我们证明，从合成经验中学习大大改善了… | MIT | Mingyu Ouyang |
| 4 | [One Task, Many Interfaces: Simple Cross-Interface Consistenc…](http://arxiv.org/abs/2610.20576v1) | 培训后将LLM代理的能力与其培训的接口绑定在一起。语义-保留该界面的扰动，例如重命名操作或更改符号，使底层任务保持不变，但使代理更糟糕。在agentic函数调用时，保留的接口扰动使训练后的agent的… | TRI | Artin Tajdini |
| 5 | [Scaling Discovery Requires Forgetting](http://arxiv.org/abs/2610.20563v1) | LLM代理的自动化研究在各个领域都取得了可喜的成果。通过迭代细化和评分验证， LLM代理能够发现新的想法。我们的研究结果表明，对于开放式发现，智能体被允许记住的内容与它被给予的计算量一样重要。 | NTU | Shangyin Tan |
| 6 | [PhySGA: A Physics-Space Grounded Agentic Framework for Gener…](http://arxiv.org/abs/2610.20560v1) | 3D对象组合对于数字内容创建和机器人模拟至关重要，同时也是基础模型中物理智能的关键测试平台。以前的方法要么利用大型语言模型直接预测物体坐标，要么利用生成扩散先验合成复合图像进行视觉对齐，这两种方法都依… | MIT、HIT | Weichen Lyu |
| 7 | [ActiveEvidence: Decision-Focused Evidence Graphs with Verifi…](http://arxiv.org/abs/2610.20532v1) | 多式联运代理必须决定是否值得获取视觉证据，查询哪个候选人或解决方案，以及进一步的互动何时不能再改变其决定。我们在严格的自由元数据/付费观察边界、随机向量成本和冻结执行跟踪下研究这个问题，并将其视为决策… | CAS、TRI | Miaobo Hu |
| 8 | [The Wealth of Agents: Scaling Agentic AI Across Developers](http://arxiv.org/abs/2610.20518v1) | 当今的代理系统通常由单个开发人员设计、构建和部署，并完全控制所有参与代理。虽然这简化了开发，但它限制了代理系统的潜在规模。综上所述，我们的研究结果初步证明了MDA是一种新的扩展轴，它使具有不同能力和资… | MIT、CAS | Austin W. Hanjie |

### 论文详情

<details>
<summary><b>1. Co-Evolving Acting and Forecasting for Language Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Haofei Yu、Yixing Chen、Yining Zhao、Xuyan Ye、Yuxiang Liu 等（共 9 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | UIUC、CAS、NUS |
| **发布时间** | 2026-10-14T17:59:28Z |
| **关键词** | `Agentic` · `Reinforcement Learning` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2610.20597v1](http://arxiv.org/abs/2610.20597v1) |

**📝 摘要概括：**

> 培训语言代理受到长期推出的高成本的瓶颈，但标准的代理强化学习（ RL ）仅从终端标量奖励中学习，使得中间步骤的监督基本上没有使用。之前的工作通过估算每个步骤成功概率的价值目标或适合环境响应的观察目标来利用这种监督。代码库可在https://github.com/ulab-u上获得……

</details>

<details>
<summary><b>2. Price of Anarchy of First-Price Auctions in Agentic Markets</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Shubhendu Trivedi、Jacob Eisenstein、Alekh Agarwal、Ian Gemp、Michael Kaisers 等（共 6 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、CAS、Mila |
| **发布时间** | 2026-10-14T17:57:57Z |
| **关键词** | `AI Agent` · `Agentic` |
| **原文链接** | [http://arxiv.org/abs/2610.20587v1](http://arxiv.org/abs/2610.20587v1) |

**📝 摘要概括：**

> 代理市场是一个去中心化的服务时间市场，人工智能代理商竞标要求每个用户提示。座席的出价基于其对提示的期望值，即对其响应的奖励减去其推断成本的期望值。我们使用在EmbedLLM提示路由数据集上模拟的战略出价人的拍卖来经验性地验证这些结果。

</details>

<details>
<summary><b>3. Player-1: Learning to Play from Synthetic Experience</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Mingyu Ouyang、Yiran Wang、Siyuan Hu、Xingyilang Yin、Huiqiang Sun 等（共 12 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT |
| **发布时间** | 2026-10-14T17:57:12Z |
| **关键词** | `Reasoning` · `Reinforcement Learning` · `RAG` |
| **原文链接** | [http://arxiv.org/abs/2610.20584v1](http://arxiv.org/abs/2610.20584v1) |

**📝 摘要概括：**

> 计算机使用代理在解释屏幕和执行键盘和鼠标操作方面表现出强大的能力。然而，游戏凭借其丰富的视觉世界和多样化的机制，仍然具有挑战性，并为通用数字控制提供了苛刻的下一步。我们证明，从合成经验中学习大大改善了超出监督初始化的游戏控制，其增益超越了RL训练……

</details>

<details>
<summary><b>4. One Task, Many Interfaces: Simple Cross-Interface Consistency Training Improves LLM Agent Robustness</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Artin Tajdini、Manpreet Kaur、Peng Qi |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-10-14T17:56:06Z |
| **关键词** | `LLM Agent` · `Agentic` |
| **原文链接** | [http://arxiv.org/abs/2610.20576v1](http://arxiv.org/abs/2610.20576v1) |

**📝 摘要概括：**

> 培训后将LLM代理的能力与其培训的接口绑定在一起。语义-保留该界面的扰动，例如重命名操作或更改符号，使底层任务保持不变，但使代理更糟糕。在agentic函数调用时，保留的接口扰动使训练后的agent的准确性降低了近25% ， CIPR恢复了10.5% ，同时保持了int的准确性不变……

</details>

<details>
<summary><b>5. Scaling Discovery Requires Forgetting</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Shangyin Tan、Ben Zhou、Lakshya A Agrawal、Jialin Zhang、Yilin Chen 等（共 11 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | NTU |
| **发布时间** | 2026-10-14T17:49:37Z |
| **关键词** | `LLM Agent` |
| **原文链接** | [http://arxiv.org/abs/2610.20563v1](http://arxiv.org/abs/2610.20563v1) |

**📝 摘要概括：**

> LLM代理的自动化研究在各个领域都取得了可喜的成果。通过迭代细化和评分验证， LLM代理能够发现新的想法。我们的研究结果表明，对于开放式发现，智能体被允许记住的内容与它被给予的计算量一样重要。

</details>

<details>
<summary><b>6. PhySGA: A Physics-Space Grounded Agentic Framework for Generalizable and Interactive 3D Composition</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Weichen Lyu、Chong Xia、Mingyu Dong、Long Xu、Shengjun Zhang 等（共 6 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、HIT、TRI |
| **发布时间** | 2026-10-14T17:47:24Z |
| **关键词** | `Agentic` · `Reasoning` · `Planning` · `RAG` · `Simulation` |
| **原文链接** | [http://arxiv.org/abs/2610.20560v1](http://arxiv.org/abs/2610.20560v1) |

**📝 摘要概括：**

> 3D对象组合对于数字内容创建和机器人模拟至关重要，同时也是基础模型中物理智能的关键测试平台。以前的方法要么利用大型语言模型直接预测物体坐标，要么利用生成扩散先验合成复合图像进行视觉对齐，这两种方法都依赖于数字空间中的静态先验。在Isaac S内部进行了广泛的实验……

</details>

<details>
<summary><b>7. ActiveEvidence: Decision-Focused Evidence Graphs with Verifiable Acquisition Gaps</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Miaobo Hu、Shuhao Hu、Xiaobo Guo、Xin Wang、Bokun Wang 等（共 8 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | CAS、TRI |
| **发布时间** | 2026-10-14T17:29:06Z |
| **关键词** | — |
| **原文链接** | [http://arxiv.org/abs/2610.20532v1](http://arxiv.org/abs/2610.20532v1) |

**📝 摘要概括：**

> 多式联运代理必须决定是否值得获取视觉证据，查询哪个候选人或解决方案，以及进一步的互动何时不能再改变其决定。我们在严格的自由元数据/付费观察边界、随机向量成本和冻结执行跟踪下研究这个问题，并将其视为决策认证的主动证据获取。已颁发证书的密集回放显示0.992行动协议和0…

</details>

<details>
<summary><b>8. The Wealth of Agents: Scaling Agentic AI Across Developers</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Austin W. Hanjie、Carlos E. Jimenez、Zirui Wang、Karthik Narasimhan |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、CAS |
| **发布时间** | 2026-10-14T17:19:11Z |
| **关键词** | `Agentic` · `RAG` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2610.20518v1](http://arxiv.org/abs/2610.20518v1) |

**📝 摘要概括：**

> 当今的代理系统通常由单个开发人员设计、构建和部署，并完全控制所有参与代理。虽然这简化了开发，但它限制了代理系统的潜在规模。综上所述，我们的研究结果初步证明了MDA是一种新的扩展轴，它使具有不同能力和资源的开发人员能够协同推进代理AI。

</details>

## 🗄️ 历史归档

| 日期 | 论文数 | 报告链接 |
|------|--------|----------|
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
| 2026-10-05 | 0 篇 | [2026-10-05.md](daily/2026-10-05.md) |
| 2026-10-04 | 0 篇 | [2026-10-04.md](daily/2026-10-04.md) |
| 2026-10-03 | 20 篇 | [2026-10-03.md](daily/2026-10-03.md) |
| 2026-10-02 | 15 篇 | [2026-10-02.md](daily/2026-10-02.md) |
| 2026-10-01 | 20 篇 | [2026-10-01.md](daily/2026-10-01.md) |
| 2026-09-30 | 8 篇 | [2026-09-30.md](daily/2026-09-30.md) |
| 2026-09-29 | 0 篇 | [2026-09-29.md](daily/2026-09-29.md) |
| 2026-09-15 | 16 篇 | [2026-09-15.md](daily/2026-09-15.md) |
| 2026-09-13 | 0 篇 | [2026-09-13.md](daily/2026-09-13.md) |
| 2026-09-12 | 0 篇 | [2026-09-12.md](daily/2026-09-12.md) |
| 2026-09-11 | 0 篇 | [2026-09-11.md](daily/2026-09-11.md) |
| 2026-09-10 | 8 篇 | [2026-09-10.md](daily/2026-09-10.md) |
| 2026-09-09 | 12 篇 | [2026-09-09.md](daily/2026-09-09.md) |
| 2026-09-08 | 0 篇 | [2026-09-08.md](daily/2026-09-08.md) |
| 2026-09-07 | 0 篇 | [2026-09-07.md](daily/2026-09-07.md) |
| 2026-09-06 | 0 篇 | [2026-09-06.md](daily/2026-09-06.md) |
| 2026-09-05 | 0 篇 | [2026-09-05.md](daily/2026-09-05.md) |
| 2026-09-04 | 20 篇 | [2026-09-04.md](daily/2026-09-04.md) |
| 2026-09-03 | 6 篇 | [2026-09-03.md](daily/2026-09-03.md) |

## 🏛️ 顶级机构覆盖范围

覆盖超过 **70 个**顶级 AI 机构，包括：

- **科技公司：** Microsoft、Google DeepMind、OpenAI、Anthropic、Meta AI、NVIDIA、Baidu、Alibaba、ByteDance 等
- **北美顶级大学：** MIT、Stanford、CMU、UC Berkeley、Harvard、Princeton、Cornell、Caltech 等
- **中国顶级大学/机构：** 清华大学、北京大学、浙大、上交大、复旦、中科院、MSRA 等
- **欧洲/其他：** Oxford、Cambridge、ETH Zurich、Mila、NUS、KAIST 等

---

*由 [clawBot DailyFindings](https://github.com/Jacob-biu/clawBot) 自动维护 | 最后更新：2026-10-16 00:06 UTC*
