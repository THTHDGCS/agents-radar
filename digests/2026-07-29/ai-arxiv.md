# ArXiv AI 研究日报 2026-07-29

> 数据来源: [ArXiv](https://arxiv.org/) (cs.RO, cs.AI, cs.LG, cs.CV) | 共 50 篇论文 | 生成时间: 2026-07-29 01:25 UTC

---

# ArXiv AI 研究日报 | 2026-07-29
---
## 今日速览
今日ArXiv AI领域共更新50篇相关论文，覆盖机器人学、大模型、多模态、强化学习等核心方向。其中具身智能成果密集，打通了从机器人本体设计、多模态感知到人机交互的全链路优化；大模型研究从规模扩张转向精细化治理，同时加速向量子计算、医疗等垂直领域渗透；持续强化学习、扩散模型等基础方法也出现了突破长期痛点的优化方案。

---
## 重点论文
### 🧠 大语言模型（架构、训练、对齐、评估）
1. **[DataOrchestra: Learning to Orchestrate Per-Example Curation of Pretraining Data](http://arxiv.org/abs/2607.24717v1)**
   作者：Zhen Huang 等
   一句话说明：提出逐例自适应的预训练数据编排框架，打破传统统一处理规则的限制，可针对性优化不同样本的预处理流程，为LLM预训练质量提升提供了新的精细化方向。

2. **[Beyond Scale and Generation: Understanding Language Model-based Entity Matching](http://arxiv.org/abs/2607.24688v1)**
   作者：Zeyu Zhang 等
   一句话说明：拆解了LLM用于实体匹配的三类架构、模型大小、训练策略等变量的实际影响，纠正了“规模越大效果越好”的误区，为实体匹配场景的LLM落地提供了可操作的指导。

---
### 🤖 智能体与推理（规划、工具使用、多智能体、思维链）
1. **[The Physics of Multi-Turn Long-Horizon Planning: From Pre-training to Post-training via Single- and Multi-Teacher On-Policy Agentic Distillation](http://arxiv.org/abs/2607.24720v1)**
   作者：Tianyi Men 等
   一句话说明：提出基于单/多教师on-policy蒸馏的智能体训练范式，首次可控地拆解了大模型长程规划能力的形成过程，摆脱了对不透明互联网预训练数据的依赖。

2. **[Transformer Transformer: A Unified Model for Motion-Conditioned Robot Co-design](http://arxiv.org/abs/2607.25798v1)**
   作者：Huy Ha 等
   一句话说明：提出统一的双Transformer架构，可根据人类演示的末端执行器轨迹自动生成适配的完整机器人本体设计，打通了机器人硬件设计与运动控制的壁垒。

3. **[Cooperative Multi-UAV Navigation in Complex Environments via Systematic Multi-Agent Deep Reinforcement Learning](http://arxiv.org/abs/2607.25754v1)**
   作者：Yu Su 等
   一句话说明：提出系统化的多智能体深度强化学习框架，解决了复杂环境下多无人机协同导航的局部最优、稀疏奖励、泛化性差等核心痛点，可直接适配真实场景。

4. **[Belief-Aware Influence and Trust (BAIT): Shaping Human Belief During Repeated Human-Robot Interaction](http://arxiv.org/abs/2607.25327v1)**
   作者：Ye-Ji Mun 等
   一句话说明：提出信念感知的人机交互框架，可在重复交互中主动塑造人类对机器人的信任与认知，解决了传统交互框架将每次交互孤立处理导致的长期性能衰减问题。

---
### 🔧 方法与框架（新技术、基准测试、效率优化）
1. **[Calibrated Partial Resets: Preventing Policy Collapse in Continual Reinforcement Learning](http://arxiv.org/abs/2607.24996v1)**
   作者：Luc McCutcheon 等
   一句话说明：提出校准的部分神经元重置机制，解决了持续强化学习中神经元休眠、梯度消失导致的策略崩溃问题，无需改动现有训练pipeline即可大幅提升持续学习稳定性。

2. **[Rethinking Classifier-Free Guidance in On-Policy Diffusion Distillation](http://arxiv.org/abs/2607.24731v1)**
   作者：Bingnan Li 等
   一句话说明：厘清了on-policy扩散蒸馏中分类器自由引导（CFG）的作用机制，提出适配的优化方案，解决了传统方法结合CFG后性能下降的痛点，提升了扩散模型蒸馏的效率与质量。

3. **[P3: Probabilistic Policy Propagation for Stable VAE-Based Robot Learning](http://arxiv.org/abs/2607.25541v1)**
   作者：Liyun Yan 等
   一句话说明：提出概率策略传播方法，解决了VAE的随机隐层分布与PPO算法不适配的核心问题，大幅提升了基于VAE的高维观测机器人学习的稳定性与性能。

4. **[ERUnderstand: Evaluating Vision-Language Models on Structured ER Diagrams](http://arxiv.org/abs/2607.24707v1)**
   作者：Ali Ansari 等
   一句话说明：发布首个大规模ER图结构化理解基准，覆盖1000+真实数据库的实体关系图，可系统评估多模态模型对专业工程图表的理解能力，填补了垂直领域多模态评估的空白。

---
### 📊 应用（垂直领域、多模态、代码生成）
1. **[ClinFusion: A Vision-Centric Multimodal LLM System for Holistic Medical Understanding](http://arxiv.org/abs/2607.24743v1)**
   作者：Hangjie Yuan 等
   一句话说明：提出视觉为中心的多模态医疗大模型，支持2D/3D医学影像、病历文本等多源数据的融合理解，评估协议完全对齐临床需求，为医疗AI的落地提供了统一的系统框架。

2. **[KANEx: Translating Kolmogorov-Arnold Networks' Interpretability to Medical Explainability](http://arxiv.org/abs/2607.24730v1)**
   作者：Krithi Shailya 等
   一句话说明：提出将Kolmogorov-Arnold网络（KAN）的固有可解释性迁移到医学影像诊断的框架，可生成符合临床规范的自然语言解释，有效解决医疗AI的黑盒信任问题。

3. **[Efficient LLM-Generated Shuttling Compilers for Complex Trapped-Ion Architectures](http://arxiv.org/abs/2607.24714v1)**
   作者：Fabian Kreppel 等
   一句话说明：首次实现用前沿大语言模型端到端生成并迭代优化离子阱量子计算机的穿梭编译器，编译效果接近人工优化的专业方案，大幅降低了量子硬件的开发门槛。

---
## 研究趋势信号
今日投稿显现三大新兴趋势：一是具身智能研究从单模块优化向全链路打通演进，覆盖机器人设计、感知、控制、交互全流程，加速向医疗、工业等真实场景落地；二是大模型研究从规模竞赛转向精细化治理与垂直深度适配，预训练数据处理从统一规则转向逐例自适应，同时向量子计算、数据库工程等交叉领域渗透；三是可解释AI与新型网络架构（如KAN）结合，向医疗等强监管场景落地，破解黑盒模型的信任难题。

---
## 值得精读
1. **《The Physics of Multi-Turn Long-Horizon Planning: From Pre-training to Post-training via Single- and Multi-Teacher On-Policy Agentic Distillation》**（http://arxiv.org/abs/2607.24720v1）
   理由：长程规划能力是当前通用智能体落地的核心瓶颈，该工作首次通过可控的蒸馏范式拆解了规划能力的形成与演化过程，摆脱了对不透明互联网预训练数据的依赖，为智能体能力的可解释性分析与定向优化提供了里程碑式的框架。

2. **《Transformer Transformer: A Unified Model for Motion-Conditioned Robot Co-design》**（http://arxiv.org/abs/2607.25798v1）
   理由：该工作打破了机器人硬件设计与运动控制的传统学科壁垒，首次用统一模型实现了根据人类演示的任务轨迹自动生成适配的完整机器人本体设计，将大幅降低具身智能的硬件定制门槛，为机器人的规模化、场景化落地提供了全新路径。

3. **《Calibrated Partial Resets: Preventing Policy Collapse in Continual Reinforcement Learning》**（http://arxiv.org/abs/2607.24996v1）
   理由：持续强化学习的策略崩溃是长期困扰具身智能、自动驾驶等领域的核心痛点，该工作提出的校准部分神经元重置方法简单高效，无需大幅改动现有训练流程即可大幅提升持续学习的稳定性，具有极高的工业落地价值。

---
*本日报由 [agents-radar](https://github.com/THTHDGCS/agents-radar) 自动生成。*