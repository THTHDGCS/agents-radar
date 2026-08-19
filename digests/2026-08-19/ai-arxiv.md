# ArXiv AI 研究日报 2026-08-19

> 数据来源: [ArXiv](https://arxiv.org/) (cs.RO, cs.AI, cs.LG, cs.CV) | 共 50 篇论文 | 生成时间: 2026-08-19 00:34 UTC

---

# ArXiv AI 研究日报
**日期：2026年8月19日**
**覆盖领域：cs.AI / cs.CL / cs.LG 共50篇最新投稿**

---

## 今日速览
今日ArXiv AI领域新投稿聚焦三大核心方向：一是长时序机器人操作与具身智能架构取得集中突破，多款分层VLA模型与神经符号智能体方案发布；二是大模型安全与可靠性研究持续深化，模型催眠攻击、具身智能体状态注入、合规检测器审计等新风险与验证方法接连涌现；三是基础算法与交叉研究获重要进展，AlphaEvolve助力刷新矩阵乘法指数最优边界、全自动符号回归系统AutoSR问世。此外，RAG接地性、视频世界模型物理校准等方向也推出了新的基准与解决方案。

---

## 重点论文
### 🧠 大语言模型（架构、训练、对齐、评估）
1. **[Model Hypnosis: Strong control of AI via additive subliminal effects](http://arxiv.org/abs/2608.16834v1)**
   作者: Enric Boix-Adsera 等
   一句话说明：发现大模型普遍存在“模型催眠”漏洞，多个弱相关的潜意识提示可叠加实现对模型行为的强控制，效应覆盖多架构多规模，对大模型对齐与安全防护提出全新挑战。

2. **[What Do Compliance Detectors Read? An Audit of Activation Probes and Guard Models](http://arxiv.org/abs/2608.16852v1)**
   作者: Saisab Sadhu 等
   一句话说明：系统审计当前大模型合规检测器的激活探针与防护模型，揭示其判决依据与书面规则的匹配偏差，为合规监控的可靠性验证提供了标准化框架。

3. **[Policy Iteration with Human Feedback: Bringing Post-Training RL to In-context Learning](http://arxiv.org/abs/2608.16831v1)**
   作者: Minh-Ha Nguyen 等
   一句话说明：提出带人类反馈的策略迭代（PIHF）框架，将后训练RL方法引入上下文学习场景，实现固定模型在任务执行中的动态行为适配，拓展了RLHF的应用边界。

4. **[Proteus: Incremental Memory Activation for Long-Context Sequence Modeling](http://arxiv.org/abs/2608.16844v1)**
   作者: Reza Bayat 等
   一句话说明：提出增量记忆激活的长上下文序列建模框架Proteus，突破传统静态记忆模型的局限，在降低计算成本的同时提升了长序列任务的性能。

---

### 🤖 智能体与推理（规划、工具使用、多智能体、思维链）
1. **[Don't Drop the BATON: Long-Horizon Robot Manipulation via Agentic Subtask Exploration and Transition-aware Memory](http://arxiv.org/abs/2608.16889v1)**
   作者: Bingxin Xu 等
   一句话说明：提出面向长时序机器人操作的BATON框架，通过智能体式子任务探索与转移感知记忆，解决VLA模型多阶段任务误差累积、子任务约束传递失效的核心痛点。

2. **[τ₀-VLA: a Hierarchical Robot Foundation Model with World-Model-Guided Test-Time Computation](http://arxiv.org/abs/2608.16885v1)**
   作者: Xiaowei Cai 等
   一句话说明：提出分层机器人基础模型τ₀-VLA，引入世界模型引导的测试时计算机制，突破传统VLA单次前向传播的决策局限，显著提升长时序操作的连贯性。

3. **[Neurosymbolic Embodied Agents](http://arxiv.org/abs/2608.16794v1)**
   作者: Mohammad Albinhassan 等
   一句话说明：提出神经符号具身智能体架构，将长时序家庭任务分解为任务导向的视觉探索与符号规划，从机制上保障了计划的可执行性与实体 grounding 准确性。

4. **[Security of Foundation-Model-Powered Embodied Agents: Attack Surfaces, Attacks, Defenses, and Evaluation](http://arxiv.org/abs/2608.16843v1)**
   作者: Jiawei Liu 等
   一句话说明：系统梳理大模型驱动具身智能体的全栈攻击面、攻击手段、防御方案与评估体系，填补了该领域安全研究的系统性综述空白，为后续研究提供了统一框架。

---

### 🔧 方法与框架（新技术、基准测试、效率优化）
1. **[Improving the matrix multiplication exponent with modern optimization and AlphaEvolve](http://arxiv.org/abs/2608.16884v1)**
   作者: Emilien Dupont 等
   一句话说明：结合现代优化方法与AlphaEvolve进化算法，改进激光法核心优化瓶颈，刷新矩阵乘法指数ω的最优边界，是AI赋能理论计算机科学的标志性突破。

2. **[AutoSR: Automatic Symbolic Regression by Searching Research States](http://arxiv.org/abs/2608.16876v1)**
   作者: Kejia Zhang 等
   一句话说明：提出全自动符号回归系统AutoSR，通过搜索科研状态空间而非孤立方程，解决了有限噪声数据下表达式物理一致性差的问题，大幅提升符号回归的实用价值。

3. **[CaliBench: Are the Stochastic Dynamics of Video World Models Physically Calibrated?](http://arxiv.org/abs/2608.16829v1)**
   作者: Jonathan Sadeghi 等
   一句话说明：提出视频世界模型随机动力学物理校准基准CaliBench，可细粒度测试模型对物理现象偶然不确定性的建模能力，填补了现有基准粗粒度评估的缺陷。

4. **[GRIP: Grounded Reasoning via Information-Restricted Premises](http://arxiv.org/abs/2608.16776v1)**
   作者: Lirui Teng 等
   一句话说明：提出信息受限前提的接地推理框架GRIP，解决RAG系统中“查询主导”导致检索证据失效的核心问题，显著提升生成内容的事实可靠性。

---

### 📊 应用（垂直领域、多模态、代码生成）
1. **[LAVA: Logic-Aware Validation and Augmentation Framework for Large-Scale Financial Document Auditing](http://arxiv.org/abs/2608.16763v1)**
   作者: Ruoqi Shu 等
   一句话说明：提出面向大规模财务文档审计的逻辑感知验证与增强框架LAVA，满足金融场景对准确性、一致性与可复现性的严苛要求，已具备落地条件。

2. **[Can Unsupervised Methods Outperform Supervised Deep Learning When Ground Truth Is Sparse? A Case Study of Bronchovascular Bundle Segmentation in Low-Dose CT](http://arxiv.org/abs/2608.16855v1)**
   作者: Anna Mrukwa 等
   一句话说明：在低剂量CT支气管血管束分割任务中验证，当标注稀疏时无监督方法性能可超越监督深度学习，为医疗影像小样本场景提供了全新的技术路径。

---

## 研究趋势信号
今日投稿显现三大新兴研究信号：一是具身智能安全研究快速深化，攻击面从传统prompt注入延伸至智能体内部状态与物理交互环节，系统性攻防框架与评估体系同步涌现；二是AI对基础研究的赋能从应用场景拓展至理论计算机核心问题，进化算法优化矩阵乘法指数、自动化符号回归等成果标志着AI科研助手进入深水区；三是长时序任务的VLA方案普遍转向分层架构+世界模型引导的测试时计算，记忆机制与子任务约束传递成为核心优化方向。（全文约190字）

---

## 值得精读
1. **[Improving the matrix multiplication exponent with modern optimization and AlphaEvolve](http://arxiv.org/abs/2608.16884v1)**
   理由：这是AI方法深度参与理论计算机科学核心问题的标志性突破——通过AlphaEvolve进化算法与现代优化技术结合，改进了激光法的核心优化瓶颈，刷新矩阵乘法指数ω的最优边界。该工作不仅具备重要的理论价值，更为AI辅助基础数学研究提供了可复制的范式，跨学科意义显著。

2. **[Model Hypnosis: Strong control of AI via additive subliminal effects](http://arxiv.org/abs/2608.16834v1)**
   理由：该研究提出的“模型催眠”是大模型对齐领域的全新风险类型：多个独立弱相关的潜意识提示可叠加实现对模型行为的强控制，且效应覆盖多种模型架构与规模。这一发现突破了传统对抗攻击的显性注入思路，对当前大模型的安全防护、对齐训练体系构成根本性挑战，是所有大模型研发与安全研究者的必读成果。

3. **[Don't Drop the BATON: Long-Horizon Robot Manipulation via Agentic Subtask Exploration and Transition-aware Memory](http://arxiv.org/abs/2608.16889v1)**
   理由：长时序多阶段操作是通用机器人落地的核心瓶颈，现有VLA模型普遍存在误差累积、子任务约束传递失效的问题。BATON框架提出的智能体式子任务探索与转移感知记忆机制，从架构层面解决了上述痛点，为VLA模型从单技能掌握迈向长链条复杂任务执行提供了全新思路，对具身智能领域的发展有重要指引作用。

---
*本日报由 [agents-radar](https://github.com/THTHDGCS/agents-radar) 自动生成。*