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

## 📅 今日论文 — 2026-11-04　　[→ 查看完整报告](daily/2026-11-04.md)

> 共筛选出 **20** 篇论文 | 更新于 2026-11-04 01:55 UTC

### 论文目录与概要

| # | 论文标题 | 核心概要 | 来源机构 | 第一作者 |
|---|---------|---------|---------|--------|
| 1 | [WebHarbor: Docking Real Websites for Evolving GUI Agent Envi…](http://arxiv.org/abs/2611.03634v1) | GUI Web代理需要在评估和培训期间保持稳定的真实和交互式环境。实时网站评估存在内容不断变化、访问限制和经过身份验证的工作流覆盖范围有限等问题，而现有的培训合成环境往往缺乏功能深度和视觉保真度。代码… | MIT、TRI | Zhaoyang Wang |
| 2 | [Strategist: Evolving Reasoning with Agents](http://arxiv.org/abs/2611.03618v1) | 模型只是人工智能代理系统的一半。另一半是推理策略：将模型调用转化为响应的推理过程。人工智能系统本身没有得到改进的部分现在已经得到了改进。 | TRI | Taiming Lu |
| 3 | [Four Bridges: Measuring Deception Propensity in a Multi-Agen…](http://arxiv.org/abs/2611.03600v1) | 人工智能代理越来越多地部署在与其他代理进行交互和协调的环境中，但诚实度主要通过单回合、单代理基准来衡量，这些基准会迫使模型进行欺骗。我们研究多智能体互动中出现的欺骗，没有任何欺骗指令。平台和游戏为衡量… | TRI | Raphael Casey |
| 4 | [Should We Combine Our Data? Algorithms and Limits for Privat…](http://arxiv.org/abs/2611.03599v1) | 在本文中，我们研究了双方何时应该汇集数据来训练机器学习模型。两个智能体， Alice和Bob ，每个都持有一个敏感的标签数据集，并希望从给定的假设类$\ mathcal {H} $中训练分类器。对于$… | MIT | Mahdi Haghifam |
| 5 | [Spacetime Emergence in the Memory of a Learning Agent](http://arxiv.org/abs/2611.03596v1) | 我们证明了时空的因果结构可以在学习代理执行量子信息任务的记忆中出现。我们训练基于模型的强化学习代理，以最大化与闵可夫斯基时空中的量子场相互作用的局部量子探针之间的量子互信息，而无需直接向其提供有关时空… | NTU、TRI | Philip A. LeMaitre |
| 6 | [MCP Tool Poisoning in Agentic AI Frameworks: A Cross-Framewo…](http://arxiv.org/abs/2611.03555v1) | 模型上下文协议(MCP)允许代理AI框架将语言模型连接到外部工具提供商，但它将攻击者控制的内容（工具描述、架构字段和响应数据）带入模型上下文，而无需验证。先前的基准在不确认真实执行的情况下测量模型对有… | MIT、CAS | Farooq Shaikh |
| 7 | [Can LLM Agents Be Forward-Deployed Engineers? Requirement Di…](http://arxiv.org/abs/2611.03551v1) | LLM编码代理可以越来越多地实现模型培训后的自动化，但他们是否可以充当前向部署工程师（ FDE ）代理，发现客户需求并将其转化为部署决策，目前尚不清楚。我们在真实的企业文本到SQL项目上研究这一点：模… | CAS | Marianne Menglin Liu |
| 8 | [Can LLM Agents Improve Imperfect Earth System Model Paramete…](http://arxiv.org/abs/2611.03543v1) | 地球系统模型（ ESM ）依靠参数化来表示未解决的过程，如对流、云微物理和湍流。然而，将物理理解的进步转化为稳定、经过验证的参数化并将其集成到ESM中通常需要数年时间。重新调整的物理方案以极低的计算成… | CAS | Kara D. Lamb |
| 9 | [An Agentic Framework for Automated Power System Studies and …](http://arxiv.org/abs/2611.03534v1) | 将新一代和需求连接到电网取决于两项稀缺技能：根据不断变化的大型监管机构检查应用程序，以及运行决定项目连接位置和方式的网络研究。我们展示了网格代理，这是一个将两者结合在一起的人工智能系统，以及我们用来评… | TRI | MaoXun Huang |
| 10 | [DistDebug-Bench: Can LLM Agents Diagnose Bugs in Distributed…](http://arxiv.org/abs/2611.03523v1) | LLM代理在竞争性编程和代码合成等软件工程任务中表现出强大的潜力。然而，现有的基准主要集中在小规模的设置上，例如自包含的Python模块，而分布式系统是一类基本的生产软件，未得到充分的审查。基准和评估… | TRI | Yuxuan Jiang |
| 11 | [VIAS: Value-Isolating Activation Steering for Multi-Value Al…](http://arxiv.org/abs/2611.03518v1) | 组织越来越多地部署必须遵循组织价值观的大型语言模型代理。我们检查激活转向（在生成过程中向模型的内部激活添加矢量而不改变其权重）是否可以提高合规性，而不仅仅是提示。结合提示， VIAS符合Qwen2.5… | MIT | Avni Mittal |
| 12 | [Ask, Don't Equip: Question-Driven Coding Agents for Deep Ker…](http://arxiv.org/abs/2611.03517v1) | GPU内核优化的LLM代理位于结构自由折衷的两端。脚本化代理通过学习策略、优化菜单或固定角色来修复模型在每个步骤中的作用，并且在应用配方时具有样本效率，在未应用配方时停止。我们发布内核、线束、问题库和… | MIT、HIT | Gabriele Oliaro |
| 13 | [Harder Than the Task: From Technical to Organizational Diffi…](http://arxiv.org/abs/2611.03494v1) | 人工智能基准在衡量人工智能系统执行日益苛刻的认知和技术任务的能力方面取得了显着进展。然而，其中许多基准将技术任务视为分析单元，而许多具有经济价值的工作发生在组织内部，其中任务嵌入到关系系统中。因此，我… | MIT、TRI | Victor Barres |
| 14 | [Optimize the Harness, Not the Model: Fitting a Minimal Agent…](http://arxiv.org/abs/2611.03434v1) | 政府情报团队需要能够分析大型、混乱的证据收集的LLM代理，但安全和成本限制通常排除托管的前沿模型和广泛、难以审计的工具表面。我们报告了CLEO ：环境优化的约束循环，这是一种将最小代理线束拟合到固定的… | MIT | Shai Nahum Gefen |
| 15 | [DeliverBench: Benchmarking AI Agents on Delivering Realistic…](http://arxiv.org/abs/2611.03412v1) | LLM客服代表的评判标准是交付的内容，而在专业工作中，交付的内容是一个项目，而不是一项任务。只有当整个包装保持不变时，项目才会有回报，一个薄弱的部分可以限制其余部分的价值。总而言之，这些结果表明，任务… | MIT | Yumou Liu |
| 16 | [From Reactive to Agentic Resilience: Multi-Timescale AI-RAN …](http://arxiv.org/abs/2611.03406v1) | 下一代开放式无线电接入网络（ Open RAN ）和AI-RAN部署将RAN转变为一个分解的计算感知平台，其服务连续性取决于在不同时间尺度上运行的许多控制回路。在这种情况下，弹性最好被视为涵盖预期、吸… | MIT | Sotiris Chatzimiltis |
| 17 | [Can We Stop the Backtest Yet? Anytime-Valid Promotion Tests …](http://arxiv.org/abs/2611.03384v1) | 金融研究代理可以比人类更快地生成和监控交易规则，从而记录最终的选择过程。候选人出现在数据依赖的时候，弱规则被放弃，有前途的规则被监视，直到他们超过报告门槛。对于此预打印版本， Codex协助LaTeX… | OpenAI、MIT | Eric Benhamou |
| 18 | [Characterizing When Language Models Take Harmful Actions to …](http://arxiv.org/abs/2611.03374v1) | 最近的语言模型（ LM ）安全故障在很大程度上被研究为不同的现象。在agentic misalignment中，模型敲诈高管以避免被替换。我们的工作为研究LM如何解决此类价值冲突以及以比安全评估中通常… | TRI | Brandon Jaipersaud |
| 19 | [The SIMPLE Law for Energy Cost of LLM Inference](http://arxiv.org/abs/2611.03330v1) | 生成式AI按代币计费，但代币并不同样昂贵。每个令牌都进入KV缓存，并提高了后续令牌的成本，因此能量沿着令牌看起来相同的序列非线性增长。与非代理服务相比，代理服务将每个请求的能量提高了13.0倍，这得益… | NVIDIA、HIT | Hiari Pizzini Cavagna |
| 20 | [From FAIR to AI-FAIR Metadata-First Infrastructure for AI-En…](http://arxiv.org/abs/2611.03327v1) | 人工智能（ AI ）技术及其能力在过去几年中迅速发展，导致对生物和生态科学的广泛兴趣和采用。然而，为生态学和生物多样性科学中的人工智能工作流程提供基础的数据基础设施和计算资源仍然是分散的。通过这种方法… | FAIR、TRI | Elizabeth G. Campolongo |

### 论文详情

<details>
<summary><b>1. WebHarbor: Docking Real Websites for Evolving GUI Agent Environments</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Zhaoyang Wang、Qianhui Wu、Boyu Gou、Demi Wang、Jiacheng Zhang 等（共 57 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-11-02T18:57:36Z |
| **关键词** | `Reinforcement Learning` · `RAG` · `Benchmark` · `Evaluation` · `Web Agent` |
| **原文链接** | [http://arxiv.org/abs/2611.03634v1](http://arxiv.org/abs/2611.03634v1) |

**📝 摘要概括：**

> GUI Web代理需要在评估和培训期间保持稳定的真实和交互式环境。实时网站评估存在内容不断变化、访问限制和经过身份验证的工作流覆盖范围有限等问题，而现有的培训合成环境往往缺乏功能深度和视觉保真度。代码和数据可在https://github.com/aiming-lab/WebHarbor上公开获得。

</details>

<details>
<summary><b>2. Strategist: Evolving Reasoning with Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Taiming Lu、Qi Xu、Zhigang Hua、Zhuang Liu |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-11-02T18:51:04Z |
| **关键词** | `AI Agent` · `Reasoning` · `RAG` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2611.03618v1](http://arxiv.org/abs/2611.03618v1) |

**📝 摘要概括：**

> 模型只是人工智能代理系统的一半。另一半是推理策略：将模型调用转化为响应的推理过程。人工智能系统本身没有得到改进的部分现在已经得到了改进。

</details>

<details>
<summary><b>3. Four Bridges: Measuring Deception Propensity in a Multi-Agent Game</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Raphael Casey、Michael Simeone、Alberto Tosato、Florian Ernst、Kemal El Moujahid 等（共 7 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-11-02T18:40:47Z |
| **关键词** | `Multi-Agent` · `AI Agent` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2611.03600v1](http://arxiv.org/abs/2611.03600v1) |

**📝 摘要概括：**

> 人工智能代理越来越多地部署在与其他代理进行交互和协调的环境中，但诚实度主要通过单回合、单代理基准来衡量，这些基准会迫使模型进行欺骗。我们研究多智能体互动中出现的欺骗，没有任何欺骗指令。平台和游戏为衡量欺骗行为和比较干预措施提供了一个测试平台。

</details>

<details>
<summary><b>4. Should We Combine Our Data? Algorithms and Limits for Privately Assessing Data Sharing</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Mahdi Haghifam、Kumar Kshitij Patel、Avrim Blum、Giulia Fanti、Juba Ziani |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT |
| **发布时间** | 2026-11-02T18:40:38Z |
| **关键词** | — |
| **原文链接** | [http://arxiv.org/abs/2611.03599v1](http://arxiv.org/abs/2611.03599v1) |

**📝 摘要概括：**

> 在本文中，我们研究了双方何时应该汇集数据来训练机器学习模型。两个智能体， Alice和Bob ，每个都持有一个敏感的标签数据集，并希望从给定的假设类$\ mathcal {H} $中训练分类器。对于$\ mathbb {R} ^ d $中的半空间，对$ m $的依赖跳转到$\ log (m) $ ：我们给出一个$ t =\ tilde {O} (d ^ 3\ log m/\ varepsilon) $的协议，并证明一些域需要$ t = Ω (d\ log (m/d)/\ varepsilon) $。

</details>

<details>
<summary><b>5. Spacetime Emergence in the Memory of a Learning Agent</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Philip A. LeMaitre、T. Rick Perche |
| **所属机构** | （详见原文） |
| **顶级机构标签** | NTU、TRI |
| **发布时间** | 2026-11-02T18:39:52Z |
| **关键词** | `Memory` |
| **原文链接** | [http://arxiv.org/abs/2611.03596v1](http://arxiv.org/abs/2611.03596v1) |

**📝 摘要概括：**

> 我们证明了时空的因果结构可以在学习代理执行量子信息任务的记忆中出现。我们训练基于模型的强化学习代理，以最大化与闵可夫斯基时空中的量子场相互作用的局部量子探针之间的量子互信息，而无需直接向其提供有关时空度量或因果结构的信息。在此任务中，时空地理……

</details>

<details>
<summary><b>6. MCP Tool Poisoning in Agentic AI Frameworks: A Cross-Framework Measurement Study</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Farooq Shaikh、Biagio Montaruli |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、CAS、TRI |
| **发布时间** | 2026-11-02T18:17:08Z |
| **关键词** | `Agentic` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2611.03555v1](http://arxiv.org/abs/2611.03555v1) |

**📝 摘要概括：**

> 模型上下文协议(MCP)允许代理AI框架将语言模型连接到外部工具提供商，但它将攻击者控制的内容（工具描述、架构字段和响应数据）带入模型上下文，而无需验证。先前的基准在不确认真实执行的情况下测量模型对有毒指令的依从性。代码级审计发现，在12个框架中没有故意防御，所有五个框架都协调……

</details>

<details>
<summary><b>7. Can LLM Agents Be Forward-Deployed Engineers? Requirement Discovery and Delivery for Enterprise Text-to-SQL</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Marianne Menglin Liu、Rongguang Wang、Zheng Wang、Yewen Wang、Leonid Boytsov 等（共 8 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | CAS |
| **发布时间** | 2026-11-02T18:13:38Z |
| **关键词** | `LLM Agent` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2611.03551v1](http://arxiv.org/abs/2611.03551v1) |

**📝 摘要概括：**

> LLM编码代理可以越来越多地实现模型培训后的自动化，但他们是否可以充当前向部署工程师（ FDE ）代理，发现客户需求并将其转化为部署决策，目前尚不清楚。我们在真实的企业文本到SQL项目上研究这一点：模拟客户，基于真实用例的要求，从模糊的请求开始。我们建议对发现的要求进行人工审查，监控……

</details>

<details>
<summary><b>8. Can LLM Agents Improve Imperfect Earth System Model Parameterizations?</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Kara D. Lamb |
| **所属机构** | （详见原文） |
| **顶级机构标签** | CAS |
| **发布时间** | 2026-11-02T18:05:04Z |
| **关键词** | `LLM Agent` · `Agentic` · `Simulation` |
| **原文链接** | [http://arxiv.org/abs/2611.03543v1](http://arxiv.org/abs/2611.03543v1) |

**📝 摘要概括：**

> 地球系统模型（ ESM ）依靠参数化来表示未解决的过程，如对流、云微物理和湍流。然而，将物理理解的进步转化为稳定、经过验证的参数化并将其集成到ESM中通常需要数年时间。重新调整的物理方案以极低的计算成本匹配或优于许多学习的参数化，但100个无人值守的代理生成器中有两个……

</details>

<details>
<summary><b>9. An Agentic Framework for Automated Power System Studies and Grid Connection Assessment</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | MaoXun Huang、Kshitij Kapoor、Eli Louise |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-11-02T18:00:52Z |
| **关键词** | `Agentic` · `RAG` · `Retrieval` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2611.03534v1](http://arxiv.org/abs/2611.03534v1) |

**📝 摘要概括：**

> 将新一代和需求连接到电网取决于两项稀缺技能：根据不断变化的大型监管机构检查应用程序，以及运行决定项目连接位置和方式的网络研究。我们展示了网格代理，这是一个将两者结合在一起的人工智能系统，以及我们用来评估它的方法。在循环中使用优化器的情况下，其加固包的平均成本比代理设计的平均成本低33-67 ％ ……

</details>

<details>
<summary><b>10. DistDebug-Bench: Can LLM Agents Diagnose Bugs in Distributed Systems?</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Yuxuan Jiang、Chenglin Liu、John Rose、Mason Miller、Ruthesh Thavamani 等（共 9 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-11-02T17:56:28Z |
| **关键词** | `LLM Agent` · `Reasoning` · `Benchmark` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2611.03523v1](http://arxiv.org/abs/2611.03523v1) |

**📝 摘要概括：**

> LLM代理在竞争性编程和代码合成等软件工程任务中表现出强大的潜力。然而，现有的基准主要集中在小规模的设置上，例如自包含的Python模块，而分布式系统是一类基本的生产软件，未得到充分的审查。基准和评估器可在https://github.com/OrderLab/distdebug-bench上找到，代理跟踪和排行榜位于https://dis…

</details>

<details>
<summary><b>11. VIAS: Value-Isolating Activation Steering for Multi-Value Alignment and Compliance for Organisations</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Avni Mittal、Avinash Anand、Dikshant Kukreja、Erik Cambria、Rajiv Ratn Shah 等（共 6 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT |
| **发布时间** | 2026-11-02T17:53:26Z |
| **关键词** | — |
| **原文链接** | [http://arxiv.org/abs/2611.03518v1](http://arxiv.org/abs/2611.03518v1) |

**📝 摘要概括：**

> 组织越来越多地部署必须遵循组织价值观的大型语言模型代理。我们检查激活转向（在生成过程中向模型的内部激活添加矢量而不改变其权重）是否可以提高合规性，而不仅仅是提示。结合提示， VIAS符合Qwen2.5-7B 69.6%、Mistral-7B 75.2%和Phi-3.5-mini 72.6%的每个标记值，优于……

</details>

<details>
<summary><b>12. Ask, Don't Equip: Question-Driven Coding Agents for Deep Kernel Optimization</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Gabriele Oliaro、Jaeseong Lee、Zhaoyuan Su、Sreeram Vennam、Zhihao Jia 等（共 6 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、HIT、TRI |
| **发布时间** | 2026-11-02T17:51:58Z |
| **关键词** | `LLM Agent` · `Retrieval` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2611.03517v1](http://arxiv.org/abs/2611.03517v1) |

**📝 摘要概括：**

> GPU内核优化的LLM代理位于结构自由折衷的两端。脚本化代理通过学习策略、优化菜单或固定角色来修复模型在每个步骤中的作用，并且在应用配方时具有样本效率，在未应用配方时停止。我们发布内核、线束、问题库和所有跟踪。

</details>

<details>
<summary><b>13. Harder Than the Task: From Technical to Organizational Difficulty in AI Benchmarking</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Victor Barres、Aden Barton、Nicolai J. Foss、Henrik M. Nielsen |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-11-02T17:36:52Z |
| **关键词** | `AI Agent` · `RAG` · `Benchmark` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2611.03494v1](http://arxiv.org/abs/2611.03494v1) |

**📝 摘要概括：**

> 人工智能基准在衡量人工智能系统执行日益苛刻的认知和技术任务的能力方面取得了显着进展。然而，其中许多基准将技术任务视为分析单元，而许多具有经济价值的工作发生在组织内部，其中任务嵌入到关系系统中。因此，我们认为，人工智能基准应该越来越多地超越技术指标的评估。

</details>

<details>
<summary><b>14. Optimize the Harness, Not the Model: Fitting a Minimal Agent to a Self-Hostable LLM for Investigative Analysis</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Shai Nahum Gefen、Vered Chassida、Dmitry Basin、Guy Feigenblat |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT |
| **发布时间** | 2026-11-02T16:53:29Z |
| **关键词** | `LLM Agent` · `Memory` |
| **原文链接** | [http://arxiv.org/abs/2611.03434v1](http://arxiv.org/abs/2611.03434v1) |

**📝 摘要概括：**

> 政府情报团队需要能够分析大型、混乱的证据收集的LLM代理，但安全和成本限制通常排除托管的前沿模型和广泛、难以审计的工具表面。我们报告了CLEO ：环境优化的约束循环，这是一种将最小代理线束拟合到固定的自托管LLM的方法。在我们保留的数据集上， CLEO线束的合格率达到83.8% ，在强……的1.2个百分点内

</details>

<details>
<summary><b>15. DeliverBench: Benchmarking AI Agents on Delivering Realistic Multi-Stage Professional Projects</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Yumou Liu、Mingju Chen、Zhoufutu Wen、Qianyu Yang、Zijie Wang 等（共 21 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT |
| **发布时间** | 2026-11-02T16:37:40Z |
| **关键词** | `LLM Agent` · `AI Agent` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2611.03412v1](http://arxiv.org/abs/2611.03412v1) |

**📝 摘要概括：**

> LLM客服代表的评判标准是交付的内容，而在专业工作中，交付的内容是一个项目，而不是一项任务。只有当整个包装保持不变时，项目才会有回报，一个薄弱的部分可以限制其余部分的价值。总而言之，这些结果表明，任务级能力并不仅仅构成交付，这也取决于保持工作的连贯性。

</details>

<details>
<summary><b>16. From Reactive to Agentic Resilience: Multi-Timescale AI-RAN Orchestration Under Signaling Storms</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Sotiris Chatzimiltis、Mahdi Boloursaz Mashhadi、Mohammad Shojafar、Rahim Tafazolli |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT |
| **发布时间** | 2026-11-02T16:34:13Z |
| **关键词** | `Agentic` · `Reasoning` |
| **原文链接** | [http://arxiv.org/abs/2611.03406v1](http://arxiv.org/abs/2611.03406v1) |

**📝 摘要概括：**

> 下一代开放式无线电接入网络（ Open RAN ）和AI-RAN部署将RAN转变为一个分解的计算感知平台，其服务连续性取决于在不同时间尺度上运行的许多控制回路。在这种情况下，弹性最好被视为涵盖预期、吸收、适应、恢复和演变的生命周期。补充材料为预期视野下的导出定理提供了分析证明，以及……

</details>

<details>
<summary><b>17. Can We Stop the Backtest Yet? Anytime-Valid Promotion Tests for Adaptive Financial Research Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Eric Benhamou、Jean-Jacques Ohana、Beatrice Guez、Ethan Setrouk、Chamyl Saadi 等（共 6 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | OpenAI、MIT、NUS |
| **发布时间** | 2026-11-02T16:24:43Z |
| **关键词** | — |
| **原文链接** | [http://arxiv.org/abs/2611.03384v1](http://arxiv.org/abs/2611.03384v1) |

**📝 摘要概括：**

> 金融研究代理可以比人类更快地生成和监控交易规则，从而记录最终的选择过程。候选人出现在数据依赖的时候，弱规则被放弃，有前途的规则被监视，直到他们超过报告门槛。对于此预打印版本， Codex协助LaTeX编辑、作者和场地元数据、编译和布局检查。

</details>

<details>
<summary><b>18. Characterizing When Language Models Take Harmful Actions to Protect Their Assigned Goals</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Brandon Jaipersaud、Elliot Creager |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-11-02T16:17:54Z |
| **关键词** | `Agentic` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2611.03374v1](http://arxiv.org/abs/2611.03374v1) |

**📝 摘要概括：**

> 最近的语言模型（ LM ）安全故障在很大程度上被研究为不同的现象。在agentic misalignment中，模型敲诈高管以避免被替换。我们的工作为研究LM如何解决此类价值冲突以及以比安全评估中通常报告的总伤害率更精细的粒度估计低概率有害行为提供了一个描述性框架。

</details>

<details>
<summary><b>19. The SIMPLE Law for Energy Cost of LLM Inference</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Hiari Pizzini Cavagna、Andrea Proia、Daniele Cesarini、Zeynep Kiziltan、Andrea Bartolini |
| **所属机构** | （详见原文） |
| **顶级机构标签** | NVIDIA、HIT |
| **发布时间** | 2026-11-02T15:51:46Z |
| **关键词** | `Agentic` · `Reasoning` · `Memory` |
| **原文链接** | [http://arxiv.org/abs/2611.03330v1](http://arxiv.org/abs/2611.03330v1) |

**📝 摘要概括：**

> 生成式AI按代币计费，但代币并不同样昂贵。每个令牌都进入KV缓存，并提高了后续令牌的成本，因此能量沿着令牌看起来相同的序列非线性增长。与非代理服务相比，代理服务将每个请求的能量提高了13.0倍，这得益于预填充和具有输入长度的KV缓存项的增长；而前缀缓存则消除了大部分预填充成本（ -93% ） ， ……

</details>

<details>
<summary><b>20. From FAIR to AI-FAIR Metadata-First Infrastructure for AI-Enabled Science</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Elizabeth G. Campolongo、Eric R. Sokol、Marty Downs、Gina Glenne、Gregory E. Maurer 等（共 12 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | FAIR、TRI |
| **发布时间** | 2026-11-02T15:49:34Z |
| **关键词** | `Agentic` · `RAG` · `Evaluation` · `Workflow` |
| **原文链接** | [http://arxiv.org/abs/2611.03327v1](http://arxiv.org/abs/2611.03327v1) |

**📝 摘要概括：**

> 人工智能（ AI ）技术及其能力在过去几年中迅速发展，导致对生物和生态科学的广泛兴趣和采用。然而，为生态学和生物多样性科学中的人工智能工作流程提供基础的数据基础设施和计算资源仍然是分散的。通过这种方法，我们的目标是创建一个社区知情系统来关闭模型数据……

</details>

## 🗄️ 历史归档

| 日期 | 论文数 | 报告链接 |
|------|--------|----------|
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
| 2026-10-05 | 0 篇 | [2026-10-05.md](daily/2026-10-05.md) |
| 2026-10-04 | 0 篇 | [2026-10-04.md](daily/2026-10-04.md) |

## 🏛️ 顶级机构覆盖范围

覆盖超过 **70 个**顶级 AI 机构，包括：

- **科技公司：** Microsoft、Google DeepMind、OpenAI、Anthropic、Meta AI、NVIDIA、Baidu、Alibaba、ByteDance 等
- **北美顶级大学：** MIT、Stanford、CMU、UC Berkeley、Harvard、Princeton、Cornell、Caltech 等
- **中国顶级大学/机构：** 清华大学、北京大学、浙大、上交大、复旦、中科院、MSRA 等
- **欧洲/其他：** Oxford、Cambridge、ETH Zurich、Mila、NUS、KAIST 等

---

*由 [clawBot DailyFindings](https://github.com/Jacob-biu/clawBot) 自动维护 | 最后更新：2026-11-04 01:55 UTC*
