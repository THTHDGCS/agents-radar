# ArXiv AI 研究日报 2026-09-04

> 数据来源: [ArXiv](https://arxiv.org/) (cs.RO, cs.AI, cs.LG, cs.CV) | 共 50 篇论文 | 生成时间: 2026-09-04 01:48 UTC

---

# ArXiv AI 研究日报
**日期：2026-09-04**
**覆盖领域：cs.AI / cs.CL / cs.LG**
**共收录论文：50篇**

---

## 今日速览
今日ArXiv AI领域共更新50篇新论文，核心突破集中在大模型训练推理效率、智能体安全与场景落地、多模态3D推理三大方向。大模型基础研究端，GRPO后训练的回放控制新范式大幅降低推理模型RL训练成本，无状态伯努利水印实现推理速度级的内容溯源，“免费暂停token”在不增加序列长度的前提下提升预测性能，从训练、安全、性能三个维度夯实基础能力。智能体领域则聚焦真实场景痛点，既解决了会议代理场景感知不足的落地问题，又首次披露生命周期钩子带来的新型攻击面，推动智能体从“可用”向“可靠、可信”演进。此外，3D世界建模、多模态空间推理、垂直领域基础模型的研究持续推进，进一步拓展生成式AI的应用边界。

---

## 重点论文
### 🧠 大语言模型（架构、训练、对齐、评估）
1. **[Headroom-Drift Replay: A Primitive for Principled Replay Control in GRPO](http://arxiv.org/abs/2609.03941v1)**
   - 作者：Hyun Bin Park 等
   - 一句话说明：提出有理论依据的GRPO回放控制机制，通过复用历史轨迹大幅降低推理模型RL后训练的rollout生成成本，尤其适用于环境交互占主导的智能体场景，显著压缩训练墙钟时间。

2. **[Flip, Don't Shuffle: Watermarking LLMs at the Speed of Inference](http://arxiv.org/abs/2609.03844v1)**
   - 作者：Simone Ceppi 等
   - 一句话说明：提出无状态伯努利水印（SBW），通过逐token独立伯努利试验确定绿名单，仅需单次比较即可完成水印生成与检测，速度达到推理级，解决现有大模型水印方案开销高、影响推理效率的痛点。

3. **[Free Pause Tokens](http://arxiv.org/abs/2609.03807v1)**
   - 作者：John Langford 等
   - 一句话说明：提出“免费暂停token”机制，通过权重共享的并行预测流为模型提供额外计算量，无需在序列中增加额外思考token即可提升下一词预测性能，突破传统思考token拉长序列、增加推理延迟的局限。

4. **[Beyond Endpoint Scores: Time- and Capacity-Conditioned Evaluation of Continual Knowledge Updating](http://arxiv.org/abs/2609.03900v1)**
   - 作者：Heejin Choi 等
   - 一句话说明：指出现有持续知识更新方法仅依赖单一最终检查点和常规适配器秩的评估方式存在缺陷，提出时间与容量条件化的评估框架，更准确地识别模型最优运行点。

---

### 🤖 智能体与推理（规划、工具使用、多智能体、思维链）
1. **[Speak for Me: Giving LLMs the Situational Awareness to Participate in a Meeting](http://arxiv.org/abs/2609.03923v1)**
   - 作者：Muneeb Khan 等
   - 一句话说明：针对会议代理LLM缺乏场景感知、错过发言时机的痛点，提出立场-覆盖-发言权跟踪机制，将AMI语料上缺席参与者发言机会的沉默率从51.4%大幅降低，推动会议智能体落地。

2. **[A Blind Trust, the Bloody Thrust: When Attacker-Controlled Hook Updates Steer AI Agent Harnesses towards Malicious Behaviors](http://arxiv.org/abs/2609.03884v1)**
   - 作者：Pengxun Li 等
   - 一句话说明：首次系统披露AI智能体框架中生命周期钩子的新型攻击面，攻击者可通过控制钩子更新引导智能体执行恶意行为且LLM无法感知，填补了智能体安全研究的空白。

3. **[Value-Preserving Architectures for Agentic AI Systems](http://arxiv.org/abs/2609.03920v1)**
   - 作者：Alessandro Pesare 等
   - 一句话说明：针对多智能体系统中隐私、公平、安全等人类核心价值难以保留的问题，提出价值保持的智能体系统架构范式，为Agentic AI的可信落地提供架构层面的指导。

4. **[Towards Numerical TOHTN Planning with SMT-based HTN-SAT Encoding](http://arxiv.org/abs/2609.03938v1)**
   - 作者：Gaspard Quenard 等
   - 一句话说明：将SMT求解引入HTN规划的SAT编码，实现数值全序HTN规划，填补了HTN规划在数值推理支持上的不足，拓展了智能体规划在复杂数值场景的适用范围。

---

### 🔧 方法与框架（新技术、基准测试、效率优化）
1. **[RATL: Learning from Retrieved Residuals for Robust Multivariate Time-Series Forecasting](http://arxiv.org/abs/2609.03937v1)**
   - 作者：Yuchen He 等
   - 一句话说明：将检索增强思想引入连续回归任务，通过学习检索残差而非直接复用目标值，解决时间序列预测中样本差异导致的鲁棒性问题，为检索增强回归提供新范式。

2. **[STAIR (STructure Aware Information Retriever): A novel dataset and LLM based retriever for document structure augmentation](http://arxiv.org/abs/2609.03874v1)**
   - 作者：Vineet Kumar 等
   - 一句话说明：提出结构感知的信息检索器STAIR及配套数据集，利用文档结构提升RAG检索精度，缓解大模型长上下文“中间丢失”问题，提升生成准确性。

3. **[Differentiable Interval Bottlenecks for Interpretable Anomaly Detection in Numerical Data](http://arxiv.org/abs/2609.03878v1)**
   - 作者：Lamine Diop 等
   - 一句话说明：提出DIFFINT可解释异常检测方法，将自编码器潜在瓶颈结构化为可学习的轴对齐区间成员集，直接输出异常相关特征范围，解决重构类检测器可解释性差的痛点。

---

### 📊 应用（垂直领域、多模态、代码生成）
1. **[OctWorld: Long-Range World-Consistent Video Generation with Octree-Based 3D Mapping](http://arxiv.org/abs/2609.03919v1)**
   - 作者：Zelong Lv 等
   - 一句话说明：提出基于八叉树3D映射的视频扩散框架，支持单图输入下沿用户指定相机轨迹生成长程世界一致视频，突破现有视频生成世界一致性差、长程不稳定的问题。

2. **[GraFT: A Training-Free Framework for Spatial Reasoning in Multimodal Large Language Models via 3D Scene Graphs](http://arxiv.org/abs/2609.03892v1)**
   - 作者：Junqing Du 等
   - 一句话说明：提出无需训练的GraFT框架，通过3D场景图增强多模态大模型的空间推理能力，解决现有MLLM在几何测量、视角转换、细粒度语义锚定上的不可靠问题。

3. **[VisCAD: A Foundation Model Suite with Multimodal Industrial CAD Intelligence](http://arxiv.org/abs/2609.03811v1)**
   - 作者：JoyIndustrial VisCAD Team 等
   - 一句话说明：推出工业CAD多模态基础模型套件，覆盖零件级多模态生成、装配级推理两大核心场景，推动工业设计领域生成式AI的落地应用。

---

## 研究趋势信号
今日投稿呈现三大新兴趋势：一是大模型效率优化从训练、推理两端协同推进，GRPO回放降本、推理级水印、免费暂停token等工作突破单点优化局限，同时“并行计算替代序列拉长”的性能提升范式开始显现；二是智能体研究进入场景落地与安全风险并行阶段，会议、零售供应链、生物信息等垂直场景智能体密集出现，新型生命周期钩子攻击的披露也推动安全研究前置；三是多模态与3D世界建模深度融合，空间推理、世界一致生成成为多模态模型落地物理世界的核心抓手。

---

## 值得精读
1. **[Headroom-Drift Replay: A Primitive for Principled Replay Control in GRPO](http://arxiv.org/abs/2609.03941v1)**
   理由：针对当前推理模型RL后训练rollout生成成本过高的核心痛点，提出了有理论依据的回放控制范式，可大幅降低智能体场景下的训练墙钟成本，对GRPO类训练方法的落地具有普适性指导意义，方法严谨且场景价值高。

2. **[A Blind Trust, the Bloody Thrust: When Attacker-Controlled Hook Updates Steer AI Agent Harnesses towards Malicious Behaviors](http://arxiv.org/abs/2609.03884v1)**
   理由：首次系统披露了AI智能体框架中生命周期钩子的新型攻击面，攻击隐蔽性强、影响范围广，填补了当前智能体安全研究的空白，对智能体框架的安全设计具有重要的警示和指导价值。

3. **[Free Pause Tokens](http://arxiv.org/abs/2609.03807v1)**
   理由：由John Langford团队提出的并行暂停token机制，打破了传统思考token需要拉长序列、增加推理延迟的局限，为大模型推理性能提升提供了全新思路，实现简单且收益明确，具有很高的实用价值和启发性。

---
*本日报由 [agents-radar](https://github.com/THTHDGCS/agents-radar) 自动生成。*