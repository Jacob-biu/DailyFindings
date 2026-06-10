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

## 📅 今日论文 — 2026-06-10　　[→ 查看完整报告](daily/2026-06-10.md)

> 共筛选出 **19** 篇论文 | 更新于 2026-06-10 23:26 UTC

### 论文目录与概要

| # | 论文标题 | 核心概要 | 来源机构 | 第一作者 |
|---|---------|---------|---------|--------|
| 1 | [EEVEE: Towards Test-time Prompt Learning in the Real World f…](http://arxiv.org/abs/2606.11182v1) | 在本文中，我们提出了EEVEE ，这是第一个针对LLM代理的多数据集测试时提示学习框架，可在真实任务流下实现测试时提示学习。现有的方法主要是为单个数据集设置而设计的，而现实世界的应用程序需要模型来处理… | MIT、TRI | Weixian Xu |
| 2 | [ABC-Bench: An Agentic Bio-Capabilities Benchmark for Biosecu…](http://arxiv.org/abs/2606.11150v1) | 大型语言模型（ LLM ）正在迅速获得与生物研究相关的能力，从文献合成到实验数据的解释。LLM代理商还可以越来越多地执行以前需要经验丰富的人类生物学家的硅生物学任务。在三个湿实验室验证实验中，我们发现… | OpenAI | Andrew Bo Liu |
| 3 | [Monte Carlo Pass Search: Using Trajectory Generation for 3D …](http://arxiv.org/abs/2606.11120v1) | 我们将足球（足球）中的通过评估重塑为蒙特卡洛树搜索（ MCTS ）式的评估问题，其组成部分主要以不同的名称存在于文献中：价值模型（占有值）、世界模型（带有球相互作用的多智能体轨迹）和反事实行为策略（带… | MIT、CAS | Andrew Kang |
| 4 | [TRACE: A Unified Rollout Budget Allocation Framework for Eff…](http://arxiv.org/abs/2606.11119v1) | 具有可验证奖励的强化学习（ RLVR ）是增强大型语言模型中的推理和代理行为的一种有希望的方法。然而，推出密集型策略优化通常受到奖励对比度不足的限制，当过于简单或复杂的提示产生低方差反馈时，以及当仅结… | MIT | Heming Zou |
| 5 | [A History-Aware Visually Grounded Critic for Computer Use Ag…](http://arxiv.org/abs/2606.11078v1) | 已经开发了计算机使用代理（ CUA ）的各种测试时间干预措施，包括批评模型，以通过在复杂的图形用户界面（ GUI ）环境中进行执行前操作评估来提高性能。然而，现有的批评者受到两个主要限制：他们（ 1 … | MIT | Jaewoo Lee |
| 6 | [T1-Bench: Benchmarking Multi-Scenario Agents in Real-World D…](http://arxiv.org/abs/2606.11070v1) | 大型语言模型（ LLM ）的推理和工具调用能力的最新进展使代理系统的能力越来越强。然而，现有基准在任务复杂性、真实性和领域多样性方面仍然有限，并且通常无法捕捉跨越多个领域的交互，从而限制了他们在需要持… | MIT | Genta Indra Winata |
| 7 | [What Fits (Into Few Tokens) Doesn't Overfit: Compression and…](http://arxiv.org/abs/2606.11045v1) | 原则上，自适应地重复使用保留的基准应该会导致过拟合。然而，基准驱动的机器学习（ ML ）在实践中几乎没有产生过拟合。综上所述，我们的结果支持对基准驱动的机器学习中缺乏过拟合的描述长度解释：成功的策略占… | MIT | Martin Andres Bertran |
| 8 | [Workflow-GYM: Towards Long-Horizon Evaluation of Computer-us…](http://arxiv.org/abs/2606.11042v1) | 近年来，人工智能代理在处理日益复杂的现实世界任务方面迅速发展。但是，现有基准很少评估客服代表是否可以操作图形用户界面来完成跨不同领域的长期、高价值的专业工作流程。我们的研究结果为当前代理系统的局限性提… | MIT | Liya Zhu |
| 9 | [Understanding and mitigating the risks of OpenClaw for non-t…](http://arxiv.org/abs/2606.11007v1) | OpenClaw已迅速成为变革性的人工智能(AI)代理框架，其自主执行复杂、多步骤任务的能力吸引了不断增长和多样化的用户群。然而，这种能力带来了巨大的风险。通过这项工作，我们证明了防范智能代理的风险不… | TRI | Junchang Zheng |
| 10 | [Mind the Gap: Can Frontier LLMs Pass a Standardized Office P…](http://arxiv.org/abs/2606.10956v1) | 用于计算机自动化的大型语言模型（ LLM ）代理的部署正在加速，但它们在复杂的专业级生产力软件中的导航能力在很大程度上未经测试。我们认为， Office自动化是对文档自动化功能进行基准测试的理想环境，… | MIT | Tengchao Lv |
| 11 | [Frontier Coding Agents Use Metaprogramming to Adapt to Unfam…](http://arxiv.org/abs/2606.10933v1) | 基于LLM的编码代理通常在熟悉的软件设置中进行评估：主流语言、通用库和公共存储库。这些基准仍然很重要，但它们可以隐藏客服代表在语言本身不熟悉时的行为。元编程是最明显的情况，但更大的差距是构建和调试在目… | CAS | Aman Sharma |
| 12 | [Role-Agent: Bootstrapping LLM Agents via Dual-Role Evolution](http://arxiv.org/abs/2606.10917v1) | 尽管大型语言模型（ LLM ）代理在复杂任务上表现出强大的表现，但他们的学习往往受到低效的交互反馈和静态训练环境的限制，这阻碍了更广泛的泛化。为了解决这些局限性，本文介绍了Role-Agent ，\ … | MIT、Mila | Xucong Wang |
| 13 | [Moonshine: An Autonomous Mathematical Research Agent Centere…](http://arxiv.org/abs/2606.10806v1) | Moonshine是一种自主的代理，其核心目标是生成数学猜想。其核心能力是从经典问题中提取结构，提炼新概念，并制定具有数学意义的猜想。这项工作说明了Moonshine自主生成有意义的数学问题并在这些问… | CAS、TRI | Xiaoyang Chen |
| 14 | [Evaluating Research-Level Math Proofs via Strict Step-Level …](http://arxiv.org/abs/2606.10799v1) | 大型语言模型（ LLM ）难以严格验证复杂的数学证明。标准的全局评估方法存在“上下文中毒” ，其中表面上合理的陈述掩盖了微妙的逻辑缺陷，导致幻觉或过度怀疑。代码和提示可在GitHub上找到。 | TRI | Yifeng Sun |
| 15 | [READER: Robust Evidence-based Authorship Decoding via Extrac…](http://arxiv.org/abs/2606.10794v1) | 随着代理应用程序越来越多地通过官方和第三方LLM API路由用户任务，出处成为一个运营问题：哪个模型生成了给定的黑盒响应？我们研究动态黑盒LLM来源：从由查询变化的非预定义提示引发的世代中识别源LLM… | TRI | Jiaxu Liu |
| 16 | [AutoPDE: Reliable Agentic PDE Solving via Explicitly Represe…](http://arxiv.org/abs/2606.10752v1) | 偏微分方程（ PDE ）的数值求解器是科学和工程中的核心计算工具。构建可靠的PDE求解器不仅需要可执行代码，还需要数值求解器策略，一组与PDE结构匹配的关于离散化、稳定化、求解器配置和分辨率控制的决策… | MIT | Huanshuo Dong |
| 17 | [Toward Secure LLM Agents: Threat Surfaces, Attacks, Defenses…](http://arxiv.org/abs/2606.10749v1) | 大型语言模型（ LLM ）代理正在迅速从会话界面转向规划、调用工具、维护内存以及对外部环境采取行动的软件组件。这种转变改变了安全风险的性质。我们认为，安全的法学硕士代理需要明确的信任界限、有原则的特权… | MIT、TRI | Yuchen Ling |
| 18 | [The Arbiter Agent: Continually Monitoring Multi-Agent Conver…](http://arxiv.org/abs/2606.10747v1) | 随着由多种语言模型代理构建的人工智能系统变得越来越普遍，它们越来越多地被用来共同做出决策：讨论、协商和对共享任务采取行动。虽然个别客服代表在单独测试时可能看起来很一致，但他们之间的互动方式可能会出现问… | MIT | Filippo Tonini |
| 19 | [MemVenom: Triggered Poisoning of Multimodal Memories in Web …](http://arxiv.org/abs/2606.10742v1) | 外部记忆已成为现代Web代理的核心组成部分，通过检索过去的经验实现长视野推理。然而，这种范式引入了一个严重的漏洞：注入内存的恶意内容可以被持续召回并反复影响代理行为。跨多个Web代理框架和视觉语言模型… | HIT、TRI | Yv Zhang |

### 论文详情

<details>
<summary><b>1. EEVEE: Towards Test-time Prompt Learning in the Real World for Self-Improving Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Weixian Xu、Shilong Liu、Mengdi Wang |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-06-09T17:57:16Z |
| **关键词** | `LLM Agent` · `RAG` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2606.11182v1](http://arxiv.org/abs/2606.11182v1) |

**📝 摘要概括：**

> 在本文中，我们提出了EEVEE ，这是第一个针对LLM代理的多数据集测试时提示学习框架，可在真实任务流下实现测试时提示学习。现有的方法主要是为单个数据集设置而设计的，而现实世界的应用程序需要模型来处理从多个数据集、域和任务分布中提取的异构输入流，这限制了它们的实际适用性。具体来说， EEVEE im…

</details>

<details>
<summary><b>2. ABC-Bench: An Agentic Bio-Capabilities Benchmark for Biosecurity</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Andrew Bo Liu、Samira Nedungadi、Bryce Cai、Alex Kleinman、Harmon Bhasin 等（共 6 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | OpenAI |
| **发布时间** | 2026-06-09T17:35:37Z |
| **关键词** | `LLM Agent` · `Agentic` · `Reasoning` · `RAG` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2606.11150v1](http://arxiv.org/abs/2606.11150v1) |

**📝 摘要概括：**

> 大型语言模型（ LLM ）正在迅速获得与生物研究相关的能力，从文献合成到实验数据的解释。LLM代理商还可以越来越多地执行以前需要经验丰富的人类生物学家的硅生物学任务。在三个湿实验室验证实验中，我们发现OpenAI的o4-mini-high产生的脚本在OpenTrons液体处理机器人上运行时，成功地…

</details>

<details>
<summary><b>3. Monte Carlo Pass Search: Using Trajectory Generation for 3D Counterfactual Pass Evaluation in Football</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Andrew Kang、Priya Narasimhan |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、CAS、TRI |
| **发布时间** | 2026-06-09T17:16:30Z |
| **关键词** | `Multi-Agent` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2606.11120v1](http://arxiv.org/abs/2606.11120v1) |

**📝 摘要概括：**

> 我们将足球（足球）中的通过评估重塑为蒙特卡洛树搜索（ MCTS ）式的评估问题，其组成部分主要以不同的名称存在于文献中：价值模型（占有值）、世界模型（带有球相互作用的多智能体轨迹）和反事实行为策略（带有噪声的采样通道变体）。建立在第一个具有3D球轨迹的公共高保真跟踪数据集之上……

</details>

<details>
<summary><b>4. TRACE: A Unified Rollout Budget Allocation Framework for Efficient Agentic Reinforcement Learning</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Heming Zou、Qi Wang、Yun Qu、Yuhang Jiang、Lizhou Cai 等（共 12 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT |
| **发布时间** | 2026-06-09T17:16:03Z |
| **关键词** | `Agentic` · `Reasoning` · `Reinforcement Learning` · `RAG` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2606.11119v1](http://arxiv.org/abs/2606.11119v1) |

**📝 摘要概括：**

> 具有可验证奖励的强化学习（ RLVR ）是增强大型语言模型中的推理和代理行为的一种有希望的方法。然而，推出密集型策略优化通常受到奖励对比度不足的限制，当过于简单或复杂的提示产生低方差反馈时，以及当仅结果奖励将相同的终端评估分配给多轮推出中的每个决策时，就会出现这种情况。根据经验，跟踪……

</details>

<details>
<summary><b>5. A History-Aware Visually Grounded Critic for Computer Use Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Jaewoo Lee、Zaid Khan、Archiki Prasad、Justin Chih-Yao Chen、Supriyo Chakraborty 等（共 10 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT |
| **发布时间** | 2026-06-09T16:39:10Z |
| **关键词** | `Planning` · `RAG` · `Benchmark` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2606.11078v1](http://arxiv.org/abs/2606.11078v1) |

**📝 摘要概括：**

> 已经开发了计算机使用代理（ CUA ）的各种测试时间干预措施，包括批评模型，以通过在复杂的图形用户界面（ GUI ）环境中进行执行前操作评估来提高性能。然而，现有的批评者受到两个主要限制：他们（ 1 ）主要关注短视的决策循环（例如，忘记早期的行动）和（ 2 ）缺乏检测有缺陷的行动所需的视觉基础（例如……

</details>

<details>
<summary><b>6. T1-Bench: Benchmarking Multi-Scenario Agents in Real-World Domains</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Genta Indra Winata、Amartya Chakraborty、Yuzhen Lin、Swasthi P Rao、Shikhhar Siingh 等（共 15 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT |
| **发布时间** | 2026-06-09T16:32:14Z |
| **关键词** | `Agentic` · `Reasoning` · `RAG` · `Benchmark` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2606.11070v1](http://arxiv.org/abs/2606.11070v1) |

**📝 摘要概括：**

> 大型语言模型（ LLM ）的推理和工具调用能力的最新进展使代理系统的能力越来越强。然而，现有基准在任务复杂性、真实性和领域多样性方面仍然有限，并且通常无法捕捉跨越多个领域的交互，从而限制了他们在需要持续推理和协调的现实多步骤设置中评估代理的能力。为了促进未来……

</details>

<details>
<summary><b>7. What Fits (Into Few Tokens) Doesn't Overfit: Compression and Generalization in ML Research Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Martin Andres Bertran、Aaron Roth、Zhiwei Steven Wu |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT |
| **发布时间** | 2026-06-09T16:12:55Z |
| **关键词** | `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2606.11045v1](http://arxiv.org/abs/2606.11045v1) |

**📝 摘要概括：**

> 原则上，自适应地重复使用保留的基准应该会导致过拟合。然而，基准驱动的机器学习（ ML ）在实践中几乎没有产生过拟合。综上所述，我们的结果支持对基准驱动的机器学习中缺乏过拟合的描述长度解释：成功的策略占据了策略空间的低复杂度区域。

</details>

<details>
<summary><b>8. Workflow-GYM: Towards Long-Horizon Evaluation of Computer-use Agentic tasks in Real-World Professional Fields</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Liya Zhu、Jingzhe Ding、Jian Zhang、Jianbo Xue、Shihao Liang 等（共 57 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT |
| **发布时间** | 2026-06-09T16:10:16Z |
| **关键词** | `AI Agent` · `Agentic` · `Benchmark` · `Evaluation` · `Workflow` |
| **原文链接** | [http://arxiv.org/abs/2606.11042v1](http://arxiv.org/abs/2606.11042v1) |

**📝 摘要概括：**

> 近年来，人工智能代理在处理日益复杂的现实世界任务方面迅速发展。但是，现有基准很少评估客服代表是否可以操作图形用户界面来完成跨不同领域的长期、高价值的专业工作流程。我们的研究结果为当前代理系统的局限性提供了重要见解，并为下一代GUI代理提供了关键方向……

</details>

<details>
<summary><b>9. Understanding and mitigating the risks of OpenClaw for non-technical users: A practical guide with Skill</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Junchang Zheng、Junfeng Tan、Jialiang Lin |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-06-09T15:41:48Z |
| **关键词** | — |
| **原文链接** | [http://arxiv.org/abs/2606.11007v1](http://arxiv.org/abs/2606.11007v1) |

**📝 摘要概括：**

> OpenClaw已迅速成为变革性的人工智能(AI)代理框架，其自主执行复杂、多步骤任务的能力吸引了不断增长和多样化的用户群。然而，这种能力带来了巨大的风险。通过这项工作，我们证明了防范智能代理的风险不一定是安全专家的专属领域，非技术用户可以......

</details>

<details>
<summary><b>10. Mind the Gap: Can Frontier LLMs Pass a Standardized Office Proficiency Exam?</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Tengchao Lv、Dongdong Zhang、Jiayu Ding、Yilin Jia、Yuzhong Zhao 等（共 13 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT |
| **发布时间** | 2026-06-09T14:59:14Z |
| **关键词** | `Agentic` · `Reasoning` · `Planning` · `Benchmark` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2606.10956v1](http://arxiv.org/abs/2606.10956v1) |

**📝 摘要概括：**

> 用于计算机自动化的大型语言模型（ LLM ）代理的部署正在加速，但它们在复杂的专业级生产力软件中的导航能力在很大程度上未经测试。我们认为， Office自动化是对文档自动化功能进行基准测试的理想环境，因为它需要长期规划和推理、精确的参数配置和多应用程序集成。最终，我们的实验演示……

</details>

<details>
<summary><b>11. Frontier Coding Agents Use Metaprogramming to Adapt to Unfamiliar Programming Languages</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Aman Sharma、Sushrut Thorat、Paras Chopra |
| **所属机构** | （详见原文） |
| **顶级机构标签** | CAS |
| **发布时间** | 2026-06-09T14:44:43Z |
| **关键词** | `Agentic` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2606.10933v1](http://arxiv.org/abs/2606.10933v1) |

**📝 摘要概括：**

> 基于LLM的编码代理通常在熟悉的软件设置中进行评估：主流语言、通用库和公共存储库。这些基准仍然很重要，但它们可以隐藏客服代表在语言本身不熟悉时的行为。元编程是最明显的情况，但更大的差距是构建和调试在目标语言规则下工作的策略。

</details>

<details>
<summary><b>12. Role-Agent: Bootstrapping LLM Agents via Dual-Role Evolution</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Xucong Wang、Ziyu Ma、Shidong Yang、Tongwen Huang、Pengkun Wang 等（共 7 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、Mila、TRI |
| **发布时间** | 2026-06-09T14:28:07Z |
| **关键词** | `LLM Agent` · `Reasoning` · `RAG` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2606.10917v1](http://arxiv.org/abs/2606.10917v1) |

**📝 摘要概括：**

> 尽管大型语言模型（ LLM ）代理在复杂任务上表现出强大的表现，但他们的学习往往受到低效的交互反馈和静态训练环境的限制，这阻碍了更广泛的泛化。为了解决这些局限性，本文介绍了Role-Agent ，\ textcolor {black} {a framework} ，它利用单个LLM同时充当代理和环境，从而实现引导式协作…

</details>

<details>
<summary><b>13. Moonshine: An Autonomous Mathematical Research Agent Centered on Conjecture Generation</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Xiaoyang Chen、Xiang Jiang |
| **所属机构** | （详见原文） |
| **顶级机构标签** | CAS、TRI |
| **发布时间** | 2026-06-09T12:50:56Z |
| **关键词** | — |
| **原文链接** | [http://arxiv.org/abs/2606.10806v1](http://arxiv.org/abs/2606.10806v1) |

**📝 摘要概括：**

> Moonshine是一种自主的代理，其核心目标是生成数学猜想。其核心能力是从经典问题中提取结构，提炼新概念，并制定具有数学意义的猜想。这项工作说明了Moonshine自主生成有意义的数学问题并在这些问题上取得严格进展的能力。

</details>

<details>
<summary><b>14. Evaluating Research-Level Math Proofs via Strict Step-Level Verification</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Yifeng Sun |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-06-09T12:46:35Z |
| **关键词** | `Agentic` · `Reasoning` · `Benchmark` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2606.10799v1](http://arxiv.org/abs/2606.10799v1) |

**📝 摘要概括：**

> 大型语言模型（ LLM ）难以严格验证复杂的数学证明。标准的全局评估方法存在“上下文中毒” ，其中表面上合理的陈述掩盖了微妙的逻辑缺陷，导致幻觉或过度怀疑。代码和提示可在GitHub上找到。

</details>

<details>
<summary><b>15. READER: Robust Evidence-based Authorship Decoding via Extracted Representations</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Jiaxu Liu、Sunnan Mu、Dong Huang、Liuyin Wang、Jing Shao 等（共 6 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-06-09T12:43:49Z |
| **关键词** | `Agentic` · `RAG` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2606.10794v1](http://arxiv.org/abs/2606.10794v1) |

**📝 摘要概括：**

> 随着代理应用程序越来越多地通过官方和第三方LLM API路由用户任务，出处成为一个运营问题：哪个模型生成了给定的黑盒响应？我们研究动态黑盒LLM来源：从由查询变化的非预定义提示引发的世代中识别源LLM ，而不是固定的输入集或基准套件。扩展九个代理阅读器进一步表明，更强大的LLM曝光……

</details>

<details>
<summary><b>16. AutoPDE: Reliable Agentic PDE Solving via Explicitly Represented Solver Strategies</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Huanshuo Dong、Keyao Zhang、Hong Wang、Zhezheng Hao、Zhiwei Zhuang 等（共 9 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT |
| **发布时间** | 2026-06-09T12:02:58Z |
| **关键词** | `Agentic` |
| **原文链接** | [http://arxiv.org/abs/2606.10752v1](http://arxiv.org/abs/2606.10752v1) |

**📝 摘要概括：**

> 偏微分方程（ PDE ）的数值求解器是科学和工程中的核心计算工具。构建可靠的PDE求解器不仅需要可执行代码，还需要数值求解器策略，一组与PDE结构匹配的关于离散化、稳定化、求解器配置和分辨率控制的决策。我们在PDE Agent Bench上评估AutoPDE ，实验结果表明AutoPDE实现了…

</details>

<details>
<summary><b>17. Toward Secure LLM Agents: Threat Surfaces, Attacks, Defenses, and Evaluation</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Yuchen Ling、Shengcheng Yu、Zhenyu Chen、Chunrong Fang |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-06-09T12:01:07Z |
| **关键词** | `Multi-Agent` · `LLM Agent` · `Agentic` · `RAG` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2606.10749v1](http://arxiv.org/abs/2606.10749v1) |

**📝 摘要概括：**

> 大型语言模型（ LLM ）代理正在迅速从会话界面转向规划、调用工具、维护内存以及对外部环境采取行动的软件组件。这种转变改变了安全风险的性质。我们认为，安全的法学硕士代理需要明确的信任界限、有原则的特权控制、出处感知状态管理以及与现实操作设置一致的评估实践。

</details>

<details>
<summary><b>18. The Arbiter Agent: Continually Monitoring Multi-Agent Conversations to Detect Emergent Misalignment</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Filippo Tonini、Federico Torrielli、Anton Danholt Lautrup、Peter Schneider-Kamp、Mustafa Mert Çelikok 等（共 6 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT |
| **发布时间** | 2026-06-09T11:57:02Z |
| **关键词** | `Multi-Agent` · `Reasoning` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2606.10747v1](http://arxiv.org/abs/2606.10747v1) |

**📝 摘要概括：**

> 随着由多种语言模型代理构建的人工智能系统变得越来越普遍，它们越来越多地被用来共同做出决策：讨论、协商和对共享任务采取行动。虽然个别客服代表在单独测试时可能看起来很一致，但他们之间的互动方式可能会出现问题。该代码可在https://github.com/aisilab/arbiter上获得。

</details>

<details>
<summary><b>19. MemVenom: Triggered Poisoning of Multimodal Memories in Web Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Yv Zhang、Hao Sun、Hao Fang、Kuofeng Gao、Fan Mo 等（共 8 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | HIT、TRI |
| **发布时间** | 2026-06-09T11:53:25Z |
| **关键词** | `Reasoning` · `RAG` · `Retrieval` · `Web Agent` · `Memory` |
| **原文链接** | [http://arxiv.org/abs/2606.10742v1](http://arxiv.org/abs/2606.10742v1) |

**📝 摘要概括：**

> 外部记忆已成为现代Web代理的核心组成部分，通过检索过去的经验实现长视野推理。然而，这种范式引入了一个严重的漏洞：注入内存的恶意内容可以被持续召回并反复影响代理行为。跨多个Web代理框架和视觉语言模型的实验表明， MemVenom实现了强大的端到端攻击成功……

</details>

## 🗄️ 历史归档

| 日期 | 论文数 | 报告链接 |
|------|--------|----------|
| 2026-06-10 | 19 篇 | [2026-06-10.md](daily/2026-06-10.md) |
| 2026-06-09 | 20 篇 | [2026-06-09.md](daily/2026-06-09.md) |
| 2026-06-08 | 0 篇 | [2026-06-08.md](daily/2026-06-08.md) |
| 2026-06-07 | 0 篇 | [2026-06-07.md](daily/2026-06-07.md) |
| 2026-06-06 | 0 篇 | [2026-06-06.md](daily/2026-06-06.md) |
| 2026-06-05 | 20 篇 | [2026-06-05.md](daily/2026-06-05.md) |
| 2026-06-04 | 0 篇 | [2026-06-04.md](daily/2026-06-04.md) |
| 2026-06-03 | 20 篇 | [2026-06-03.md](daily/2026-06-03.md) |
| 2026-06-02 | 20 篇 | [2026-06-02.md](daily/2026-06-02.md) |
| 2026-06-01 | 0 篇 | [2026-06-01.md](daily/2026-06-01.md) |
| 2026-05-31 | 0 篇 | [2026-05-31.md](daily/2026-05-31.md) |
| 2026-05-30 | 0 篇 | [2026-05-30.md](daily/2026-05-30.md) |
| 2026-05-29 | 0 篇 | [2026-05-29.md](daily/2026-05-29.md) |
| 2026-05-28 | 0 篇 | [2026-05-28.md](daily/2026-05-28.md) |
| 2026-05-27 | 0 篇 | [2026-05-27.md](daily/2026-05-27.md) |
| 2026-05-26 | 0 篇 | [2026-05-26.md](daily/2026-05-26.md) |
| 2026-05-25 | 0 篇 | [2026-05-25.md](daily/2026-05-25.md) |
| 2026-05-24 | 0 篇 | [2026-05-24.md](daily/2026-05-24.md) |
| 2026-05-23 | 0 篇 | [2026-05-23.md](daily/2026-05-23.md) |
| 2026-05-22 | 20 篇 | [2026-05-22.md](daily/2026-05-22.md) |
| 2026-05-21 | 0 篇 | [2026-05-21.md](daily/2026-05-21.md) |
| 2026-05-20 | 16 篇 | [2026-05-20.md](daily/2026-05-20.md) |
| 2026-05-19 | 0 篇 | [2026-05-19.md](daily/2026-05-19.md) |
| 2026-05-17 | 0 篇 | [2026-05-17.md](daily/2026-05-17.md) |
| 2026-05-16 | 0 篇 | [2026-05-16.md](daily/2026-05-16.md) |
| 2026-05-15 | 20 篇 | [2026-05-15.md](daily/2026-05-15.md) |
| 2026-05-14 | 19 篇 | [2026-05-14.md](daily/2026-05-14.md) |
| 2026-05-13 | 20 篇 | [2026-05-13.md](daily/2026-05-13.md) |
| 2026-05-12 | 20 篇 | [2026-05-12.md](daily/2026-05-12.md) |
| 2026-05-11 | 0 篇 | [2026-05-11.md](daily/2026-05-11.md) |

## 🏛️ 顶级机构覆盖范围

覆盖超过 **70 个**顶级 AI 机构，包括：

- **科技公司：** Microsoft、Google DeepMind、OpenAI、Anthropic、Meta AI、NVIDIA、Baidu、Alibaba、ByteDance 等
- **北美顶级大学：** MIT、Stanford、CMU、UC Berkeley、Harvard、Princeton、Cornell、Caltech 等
- **中国顶级大学/机构：** 清华大学、北京大学、浙大、上交大、复旦、中科院、MSRA 等
- **欧洲/其他：** Oxford、Cambridge、ETH Zurich、Mila、NUS、KAIST 等

---

*由 [clawBot DailyFindings](https://github.com/Jacob-biu/clawBot) 自动维护 | 最后更新：2026-06-10 23:26 UTC*
