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

## 📅 今日论文 — 2026-09-15　　[→ 查看完整报告](daily/2026-09-15.md)

> 共筛选出 **16** 篇论文 | 更新于 2026-09-16 00:00 UTC

### 论文目录与概要

| # | 论文标题 | 核心概要 | 来源机构 | 第一作者 |
|---|---------|---------|---------|--------|
| 1 | [Corrupt Plans, Clean Traces: Evading Chain-of-Thought Monito…](http://arxiv.org/abs/2609.15989v1) | 思维链（ CoT ）监控是一种安全策略，其中大型语言模型“参与者”的推理由“监视器” （通常是另一种语言模型）检查是否存在不安全的计划、欺骗或错位的迹象。我们发现，在演员的背景下种植有害但听起来温和的… | CAS、TRI | Keertana Chidambaram |
| 2 | [Stellar Colosseum: A Many-Agent Harness for Long-Horizon Res…](http://arxiv.org/abs/2609.15983v1) | 语言模型可以产生合理的短证明，但在长期研究问题上可能仍然不可靠，这些问题的进展取决于一系列不确定和相互依存的决策。我们介绍了Stellar Colosseum ，这是一种与模型无关的线束，用于在数学和… | Google | Honghao Lin |
| 3 | [The Router Within: Eliciting Native Skill Routing from a Fro…](http://arxiv.org/abs/2609.15982v1) | 技能将LLM代理扩展到其参数知识之外，他们承诺的收益取决于选择正确的知识。Deployed通过将每个技能的元数据预加载到上下文中来利用路由，从而分散座席的注意力并限制库大小。路由精度随着骨干网的提高而… | TRI | Ruishuo Chen |
| 4 | [Safe Meta-Reinforcement Learning via Information Space Reach…](http://arxiv.org/abs/2609.15915v1) | 元强化学习（ meta-RL ）使代理能够适应经验有限的看不见的任务。尽管有前途，但meta-RL在现实任务中的应用受到安全要求的阻碍，这些要求在之前的工作中未得到充分探索。在meta-RL基准测试上… | MIT | Zeyang Li |
| 5 | [AlgoEvo: Self-Evolving Agentic Search for Automated Algorith…](http://arxiv.org/abs/2609.15820v1) | 大型语言模型通过合成可执行代码实现了先进的自动算法发现，但现有框架将其困在具有预定义控制流的刚性搜索管道中。这种限制限制了自适应推理，阻止了跨范式的转移，并丢弃了有价值的执行反馈。在六项具有代表性的基… | MIT、TRI | Junhao Qiu |
| 6 | [Atria Dawn: The Dawn of Agentic Superintelligence](http://arxiv.org/abs/2609.15818v1) | 随着人工智能代理成为其继任者发展的参与者，它们重塑了智能的产生和人类研究人员的角色。我们推出了Atria Dawn Preview ，这是一种专为科学研究和工程工作流程设计的基础代理语言模型，旨在拓展… | CAS、TRI | Honglin Guo |
| 7 | [Delegating Authorization to Misaligned Agents: Coalitional A…](http://arxiv.org/abs/2609.15803v1) | 长期运行的人工智能代理会产生一个控制问题：他们采取的每个行动都会改变状态，从而影响未来行动的轨迹。如果客服代表没有完全达成一致，那么为了保证安全，需要先批准相应的行动，然后才能执行这些行动。对现有审核… | MIT | Natalie Collina |
| 8 | [Navigating Sparse Evidence: Agentic Visual RAG via Explicit …](http://arxiv.org/abs/2609.15800v1) | 视觉检索增强生成(VRAG)使模型能够通过检索相关页面图像作为视觉证据并推理其内容来导航和回答有关视觉丰富文档的查询。然而，有效利用这种视觉证据通常受到两个主要挑战的阻碍。为了实现这种统一部署的端到端… | TRI | Yucheng Shen |
| 9 | [EvoOntology: A Self-Evolving Ontology Layer for Data Agents](http://arxiv.org/abs/2609.15779v1) | 数据代理旨在实现对异构数据（包括表、文件和数据库）的自然语言指令。但是，数据代理面临着具有挑战性的代理-数据差距：异构数据驻留在代理之外，而代理只能通过通用工具访问它（例如，列名称和文件路径）。代码：… | TRI | Meiduo Chong |
| 10 | [Assembling the CREW: A Collaborative Multi-agent Reinforceme…](http://arxiv.org/abs/2609.15721v1) | 自动相关工作生成（ RWG ）显著减少了撰写研究论文的相关工作部分（ RWS ）所需的时间和精力。但是，先前利用多客服代表大型语言模型（ LLM ）的方法通常依赖于预定义的工作流程，其中每个客服代表负… | MIT、TRI | Hai-Dang Dang |
| 11 | [NoteVQA: Benchmarking VLMs on Real-Life Questions from Human…](http://arxiv.org/abs/2609.15695v1) | 视觉语言模型（ VLM ）越来越多地支持面向消费者的人工智能搜索，但在日常视觉问题的多样性方面评估它们仍然具有挑战性。现有的基准通常针对预定义的功能，例如多跳检索或长形合成，而用户则会问跨越日常场景长… | TRI | Haonan Jiang |
| 12 | [Kaininja: Extending Native 3D Generators to the Part Level](http://arxiv.org/abs/2609.15659v1) | 原生3D生成器将一个图像转换为单个网格。TRELLIS.2及其同行使用材料提供高保真非水密几何形状，但输出是一个融合对象，而编辑、索具和模拟等下游工作则在部分级别资产上运行。针对不同范式的零件生成管线… | TRI | Ruihan Yu |
| 13 | [VideoScout: Learning Agentic Active Exploration with Adaptiv…](http://arxiv.org/abs/2609.15606v1) | 多模态大型语言模型（ MLLM ）在短视频理解方面取得了显着进展，但由于视觉上下文窗口有限，对长视频的理解仍然有限。流行的方法依赖于均匀帧采样或最近的粗细代理缩放，这两种方法都难以在足够长的视频中定位… | MIT | Weixin Xu |
| 14 | [Big Brains and Changing Environments: Cause or Consequence?](http://arxiv.org/abs/2609.15569v1) | 大脑的代谢成本很高，与不断变化的环境的联系并不意味着它们在那里进化，正如认知缓冲区假说（ CBH ）所暗示的那样。相反，它们可能在稳定的条件下进化，后来促进了不断变化的环境的殖民化。我们的结果挑战了严… | TRI | Sian Heesom-Green |
| 15 | [Automating Attack Graph Construction for Agentic Pentesting.…](http://arxiv.org/abs/2609.15523v1) | 基于扫描仪输出的逻辑攻击图提供了基于LLM的代理缺乏的明确和可审计的攻击路径推理。然而，将MulVAL等符号框架集成到当代安全工作流或代理管道中，需要将扫描仪证据转化为初始事实，并创建特定领域的规则。… | MIT、CAS | Oliver Stevanovic |
| 16 | [The Troy Moment of AI: Why SomeWill Cheat and SomeWill Follo…](http://arxiv.org/abs/2609.15494v1) | 最近对2026年7月OpenAI--Hugging Face事件的调查引发了两个关于任务失败情况下客服代表行为的问题：当分配的任务变得不可能时，客服代表是否会停止或升级，以及观察其他客服代表的行为是否… | OpenAI、TRI | Ivy Zhang |

### 论文详情

<details>
<summary><b>1. Corrupt Plans, Clean Traces: Evading Chain-of-Thought Monitoring with Plan Injection</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Keertana Chidambaram、Andrew Ilyas、Vasilis Syrgkanis |
| **所属机构** | （详见原文） |
| **顶级机构标签** | CAS、TRI |
| **发布时间** | 2026-09-14T18:33:27Z |
| **关键词** | `Reasoning` · `Planning` · `Benchmark` · `Chain-of-Thought` |
| **原文链接** | [http://arxiv.org/abs/2609.15989v1](http://arxiv.org/abs/2609.15989v1) |

**📝 摘要概括：**

> 思维链（ CoT ）监控是一种安全策略，其中大型语言模型“参与者”的推理由“监视器” （通常是另一种语言模型）检查是否存在不安全的计划、欺骗或错位的迹象。我们发现，在演员的背景下种植有害但听起来温和的推理可以引导它在逃避监视器的同时执行对抗性行动，这是我们称之为“计划注入”的攻击。最后，我们发现额外月份……

</details>

<details>
<summary><b>2. Stellar Colosseum: A Many-Agent Harness for Long-Horizon Research in Mathematics and Theoretical Computer Science</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Honghao Lin、David P. Woodruff、Yuan Deng、Jieming Mao、Song Zuo 等（共 6 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | Google |
| **发布时间** | 2026-09-14T17:58:55Z |
| **关键词** | `Benchmark` · `Evaluation` · `Workflow` |
| **原文链接** | [http://arxiv.org/abs/2609.15983v1](http://arxiv.org/abs/2609.15983v1) |

**📝 摘要概括：**

> 语言模型可以产生合理的短证明，但在长期研究问题上可能仍然不可靠，这些问题的进展取决于一系列不确定和相互依存的决策。我们介绍了Stellar Colosseum ，这是一种与模型无关的线束，用于在数学和理论计算机科学的研究中分配推理。在使用Gemini 3.1 Pro的单独Codeforces评估中，具有执行feedbac的面向证明的管道……

</details>

<details>
<summary><b>3. The Router Within: Eliciting Native Skill Routing from a Frozen LLM</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Ruishuo Chen、Xun Wang、Yu Chen、Zhuoran Li、Longbo Huang |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-09-14T17:58:27Z |
| **关键词** | `LLM Agent` · `Retrieval` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2609.15982v1](http://arxiv.org/abs/2609.15982v1) |

**📝 摘要概括：**

> 技能将LLM代理扩展到其参数知识之外，他们承诺的收益取决于选择正确的知识。Deployed通过将每个技能的元数据预加载到上下文中来利用路由，从而分散座席的注意力并限制库大小。路由精度随着骨干网的提高而提高，在bash-agent利用中，相同的32B会触发正确的技能--比在Code中运行的大得多的前沿模型更频繁地使用……

</details>

<details>
<summary><b>4. Safe Meta-Reinforcement Learning via Information Space Reachability</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Zeyang Li、Sunbochen Tang、Navid Azizan |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT |
| **发布时间** | 2026-09-14T17:27:11Z |
| **关键词** | `Reinforcement Learning` · `RAG` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2609.15915v1](http://arxiv.org/abs/2609.15915v1) |

**📝 摘要概括：**

> 元强化学习（ meta-RL ）使代理能够适应经验有限的看不见的任务。尽管有前途，但meta-RL在现实任务中的应用受到安全要求的阻碍，这些要求在之前的工作中未得到充分探索。在meta-RL基准测试上的实验证明了所提出方法的有效性。

</details>

<details>
<summary><b>5. AlgoEvo: Self-Evolving Agentic Search for Automated Algorithm Discovery</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Junhao Qiu、Qinglong Hu、Xialiang Tong、Mingxuan Yuan、Liyong Lin 等（共 6 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-09-14T16:24:27Z |
| **关键词** | `Agentic` · `Reasoning` · `Benchmark` · `Evaluation` · `Workflow` |
| **原文链接** | [http://arxiv.org/abs/2609.15820v1](http://arxiv.org/abs/2609.15820v1) |

**📝 摘要概括：**

> 大型语言模型通过合成可执行代码实现了先进的自动算法发现，但现有框架将其困在具有预定义控制流的刚性搜索管道中。这种限制限制了自适应推理，阻止了跨范式的转移，并丢弃了有价值的执行反馈。在六项具有代表性的基准任务中， AlgoEvo以极少的评估次数匹配或超越了专业方法，并减少了……

</details>

<details>
<summary><b>6. Atria Dawn: The Dawn of Agentic Superintelligence</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Honglin Guo、Tao Gui、Yicheng Chen、Guanting Dong、Qiming Ge 等（共 143 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | CAS、TRI |
| **发布时间** | 2026-09-14T16:22:30Z |
| **关键词** | `AI Agent` · `Agentic` · `Benchmark` · `Workflow` |
| **原文链接** | [http://arxiv.org/abs/2609.15818v1](http://arxiv.org/abs/2609.15818v1) |

**📝 摘要概括：**

> 随着人工智能代理成为其继任者发展的参与者，它们重塑了智能的产生和人类研究人员的角色。我们推出了Atria Dawn Preview ，这是一种专为科学研究和工程工作流程设计的基础代理语言模型，旨在拓展现实世界中代理生产力的前沿。因此，在更自主的人工智能研究方面取得的进展必须推动……

</details>

<details>
<summary><b>7. Delegating Authorization to Misaligned Agents: Coalitional Alignment and Safe Control</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Natalie Collina、Surbhi Goel、Aaron Roth、Sikata Bela Sengupta |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT |
| **发布时间** | 2026-09-14T16:12:41Z |
| **关键词** | `AI Agent` · `RAG` |
| **原文链接** | [http://arxiv.org/abs/2609.15803v1](http://arxiv.org/abs/2609.15803v1) |

**📝 摘要概括：**

> 长期运行的人工智能代理会产生一个控制问题：他们采取的每个行动都会改变状态，从而影响未来行动的轨迹。如果客服代表没有完全达成一致，那么为了保证安全，需要先批准相应的行动，然后才能执行这些行动。对现有审核人模型的实验表明，即使容忍某些反对意见，集体审核也可以在没有一致的个人的情况下保持合理。

</details>

<details>
<summary><b>8. Navigating Sparse Evidence: Agentic Visual RAG via Explicit Context Selection and Consolidation</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Yucheng Shen、Lingyong Yan、Jiulong Wu、Shuaiqiang Wang、Jianmin WU 等（共 7 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-09-14T16:11:35Z |
| **关键词** | `Agentic` · `Reasoning` · `Reinforcement Learning` · `RAG` · `Retrieval` |
| **原文链接** | [http://arxiv.org/abs/2609.15800v1](http://arxiv.org/abs/2609.15800v1) |

**📝 摘要概括：**

> 视觉检索增强生成(VRAG)使模型能够通过检索相关页面图像作为视觉证据并推理其内容来导航和回答有关视觉丰富文档的查询。然而，有效利用这种视觉证据通常受到两个主要挑战的阻碍。为了实现这种统一部署的端到端优化，我们的培训范例将过滤的冷启动轨迹蒸馏与证据相结合……

</details>

<details>
<summary><b>9. EvoOntology: A Self-Evolving Ontology Layer for Data Agents</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Meiduo Chong、Shaolei Zhang、Ju Fan、Xiaoyong Du |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-09-14T15:59:24Z |
| **关键词** | `Benchmark` · `Evaluation` |
| **原文链接** | [http://arxiv.org/abs/2609.15779v1](http://arxiv.org/abs/2609.15779v1) |

**📝 摘要概括：**

> 数据代理旨在实现对异构数据（包括表、文件和数据库）的自然语言指令。但是，数据代理面临着具有挑战性的代理-数据差距：异构数据驻留在代理之外，而代理只能通过通用工具访问它（例如，列名称和文件路径）。代码： https://github.com/ruc-datalab/EvoOntology

</details>

<details>
<summary><b>10. Assembling the CREW: A Collaborative Multi-agent Reinforcement Learning Framework for Automated Related Work Generation</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Hai-Dang Dang、Bao-Yen Pham、Bao Nguyen、Tran Thi Huong、Huynh Thi Thanh Binh |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、TRI |
| **发布时间** | 2026-09-14T15:20:29Z |
| **关键词** | `Multi-Agent` · `LLM Agent` · `Reinforcement Learning` · `RAG` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2609.15721v1](http://arxiv.org/abs/2609.15721v1) |

**📝 摘要概括：**

> 自动相关工作生成（ RWG ）显著减少了撰写研究论文的相关工作部分（ RWS ）所需的时间和精力。但是，先前利用多客服代表大型语言模型（ LLM ）的方法通常依赖于预定义的工作流程，其中每个客服代表负责整个流程中的特定步骤。代码可在https://github.com/YenPBao/CREW-Collaborative-MARL.git上获得

</details>

<details>
<summary><b>11. NoteVQA: Benchmarking VLMs on Real-Life Questions from Human Communities</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Haonan Jiang、Guojian Zhan、Jiancong Xie、Shijun Wan、Dongiia Zhao 等（共 9 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-09-14T15:01:10Z |
| **关键词** | `Agentic` · `Retrieval` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2609.15695v1](http://arxiv.org/abs/2609.15695v1) |

**📝 摘要概括：**

> 视觉语言模型（ VLM ）越来越多地支持面向消费者的人工智能搜索，但在日常视觉问题的多样性方面评估它们仍然具有挑战性。现有的基准通常针对预定义的功能，例如多跳检索或长形合成，而用户则会问跨越日常场景长尾的照片问题。这些结果凸显了日常视觉问题对当前VLM带来的挑战……

</details>

<details>
<summary><b>12. Kaininja: Extending Native 3D Generators to the Part Level</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Ruihan Yu、Lian Fu、Muyao Niu、Zheng-hui Huang、Yu-Ju Tsai 等（共 12 人） |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-09-14T14:40:52Z |
| **关键词** | `Simulation` |
| **原文链接** | [http://arxiv.org/abs/2609.15659v1](http://arxiv.org/abs/2609.15659v1) |

**📝 摘要概括：**

> 原生3D生成器将一个图像转换为单个网格。TRELLIS.2及其同行使用材料提供高保真非水密几何形状，但输出是一个融合对象，而编辑、索具和模拟等下游工作则在部分级别资产上运行。针对不同范式的零件生成管线，它将全物体倒角距离降低了40% ，并将严格的零件F得分提高了16%。

</details>

<details>
<summary><b>13. VideoScout: Learning Agentic Active Exploration with Adaptive Reasoning Pacing for Long Video Understanding</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Weixin Xu、Zhenyu Yang、Bing Wang、Shengsheng Qian、Changsheng Xu |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT |
| **发布时间** | 2026-09-14T14:04:03Z |
| **关键词** | `Agentic` · `Reasoning` · `Reinforcement Learning` · `Benchmark` · `Fine-tuning` |
| **原文链接** | [http://arxiv.org/abs/2609.15606v1](http://arxiv.org/abs/2609.15606v1) |

**📝 摘要概括：**

> 多模态大型语言模型（ MLLM ）在短视频理解方面取得了显着进展，但由于视觉上下文窗口有限，对长视频的理解仍然有限。流行的方法依赖于均匀帧采样或最近的粗细代理缩放，这两种方法都难以在足够长的视频中定位稀疏的决定性证据。长视频理解和推理基准的广泛实验证明……

</details>

<details>
<summary><b>14. Big Brains and Changing Environments: Cause or Consequence?</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Sian Heesom-Green、Jonathan Shock、Geoff Nitschke |
| **所属机构** | （详见原文） |
| **顶级机构标签** | TRI |
| **发布时间** | 2026-09-14T13:46:05Z |
| **关键词** | `RAG` |
| **原文链接** | [http://arxiv.org/abs/2609.15569v1](http://arxiv.org/abs/2609.15569v1) |

**📝 摘要概括：**

> 大脑的代谢成本很高，与不断变化的环境的联系并不意味着它们在那里进化，正如认知缓冲区假说（ CBH ）所暗示的那样。相反，它们可能在稳定的条件下进化，后来促进了不断变化的环境的殖民化。我们的结果挑战了严格的CBH预测，为基于殖民化的账户提供基于代理的（计算）支持，并突出了进化历史在……中的作用

</details>

<details>
<summary><b>15. Automating Attack Graph Construction for Agentic Pentesting. Towards Neuro-Symbolic Vulnerability Hunting</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Oliver Stevanovic、Jasmin Wachter |
| **所属机构** | （详见原文） |
| **顶级机构标签** | MIT、CAS、TRI |
| **发布时间** | 2026-09-14T13:13:54Z |
| **关键词** | `Agentic` · `Reasoning` · `RAG` · `Workflow` |
| **原文链接** | [http://arxiv.org/abs/2609.15523v1](http://arxiv.org/abs/2609.15523v1) |

**📝 摘要概括：**

> 基于扫描仪输出的逻辑攻击图提供了基于LLM的代理缺乏的明确和可审计的攻击路径推理。然而，将MulVAL等符号框架集成到当代安全工作流或代理管道中，需要将扫描仪证据转化为初始事实，并创建特定领域的规则。接下来的步骤包括语义规则验证和代理级别的比较，用于图形引导的pentesting。

</details>

<details>
<summary><b>16. The Troy Moment of AI: Why SomeWill Cheat and SomeWill Follow?</b></summary>

| 字段 | 内容 |
|------|------|
| **作者** | Ivy Zhang |
| **所属机构** | （详见原文） |
| **顶级机构标签** | OpenAI、TRI |
| **发布时间** | 2026-09-14T12:46:45Z |
| **关键词** | `Multi-Agent` · `Benchmark` |
| **原文链接** | [http://arxiv.org/abs/2609.15494v1](http://arxiv.org/abs/2609.15494v1) |

**📝 摘要概括：**

> 最近对2026年7月OpenAI--Hugging Face事件的调查引发了两个关于任务失败情况下客服代表行为的问题：当分配的任务变得不可能时，客服代表是否会停止或升级，以及观察其他客服代表的行为是否会改变这一决定？我们使用GPT-5.6 Sol、Claude Fable 5.1和Gemini 3.8 Flash在单人和三代理设置中使用七个ImpossibleBench任务来研究这些问题。这些结果表明， …

</details>

## 🗄️ 历史归档

| 日期 | 论文数 | 报告链接 |
|------|--------|----------|
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

## 🏛️ 顶级机构覆盖范围

覆盖超过 **70 个**顶级 AI 机构，包括：

- **科技公司：** Microsoft、Google DeepMind、OpenAI、Anthropic、Meta AI、NVIDIA、Baidu、Alibaba、ByteDance 等
- **北美顶级大学：** MIT、Stanford、CMU、UC Berkeley、Harvard、Princeton、Cornell、Caltech 等
- **中国顶级大学/机构：** 清华大学、北京大学、浙大、上交大、复旦、中科院、MSRA 等
- **欧洲/其他：** Oxford、Cambridge、ETH Zurich、Mila、NUS、KAIST 等

---

*由 [clawBot DailyFindings](https://github.com/Jacob-biu/clawBot) 自动维护 | 最后更新：2026-09-16 00:00 UTC*
