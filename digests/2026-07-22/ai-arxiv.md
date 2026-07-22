# ArXiv AI 研究日报 2026-07-22

> 数据来源: [ArXiv](https://arxiv.org/) (cs.RO, cs.AI, cs.LG, cs.CV) | 共 50 篇论文 | 生成时间: 2026-07-22 01:25 UTC

---

# ArXiv AI 研究日报（2026-07-22）

---

## 今日速览
今日ArXiv AI领域投稿聚焦大模型落地优化、世界模型轻量化、AI for Science三大核心方向。大语言模型侧涌现出先推理后翻译的法律翻译范式、RL训练的成本-质量权衡框架、自适应推测解码等多项面向产业落地的技术突破；智能体领域取得重大效率进展，单张桌面GPU即可支持无限长交互世界推演，Real2Sim流程也实现了视觉语言智能体驱动的全自动化。AI for Science成果密集覆盖药物设计、非晶材料、超临界燃烧等垂直场景，同时多模态安全的新型盲区（隐藏仇恨幻觉）也获得针对性解决方案。

---

## 重点论文
### 🧠 大语言模型（架构、训练、对齐、评估）
1. **[MeetingToM: Evaluating Multimodal LLMs on Theory-of-Mind Reasoning in Multi-Party Meetings](http://arxiv.org/abs/2607.19235v1)**
   作者: Ziyi Wang et al.
   一句话说明：提出首个面向多方会议场景的多模态大模型心智理论（ToM）评估基准，覆盖语音、行为等多源社交线索，填补了复杂真实交互场景下ToM推理能力评估的空白。

2. **[The Price of Reasoning: Cost-Quality Tradeoffs in Reinforcement Learning for Neural Machine Translation](http://arxiv.org/abs/2607.19226v1)**
   作者: Michael Jungo et al.
   一句话说明：系统研究了可验证奖励强化学习（RLVR）用于神经机器翻译后训练时的推理成本与翻译质量的权衡关系，为大模型下游任务的成本控制提供了量化框架。

3. **[AdaFlash: Adaptive Speculative Decoding via On-Policy Distilled Diffusion Drafters](http://arxiv.org/abs/2607.19223v1)**
   作者: Yu-Yang Qian et al.
   一句话说明：提出自适应推测解码框架，通过同策略蒸馏的扩散草稿模型动态调整生成长度，进一步提升大语言模型推理效率，且无需修改目标模型架构。

4. **[Reasoning Before Translation: Enhancing Legal Machine Translation with Structured Reasoning](http://arxiv.org/abs/2607.19181v1)**
   作者: Aixiu An et al.
   一句话说明：提出“先推理后翻译”的法律机器翻译范式，通过结构化推理预解析法律术语、逻辑关系，显著提升专业领域翻译的精度与一致性。

---

### 🤖 智能体与推理（规划、工具使用、多智能体、思维链）
1. **[S3: Stable Subgoal Selection by Constraining Uncertainty of Coarse Dynamics in Hierarchical Reinforcement Learning](http://arxiv.org/abs/2607.19232v1)**
   作者: Kshitij Kumar Srivastava et al.
   一句话说明：提出分层强化学习的稳定子目标选择方法，通过约束粗粒度动力学的不确定性解决长 horizon 任务中的子目标偏移问题，大幅提升HRL的训练稳定性。

2. **[Cognitive Dual-Process Planning for Autonomous Driving with Structured Scene Knowledge and Verifiable Reasoning-Action Consistency](http://arxiv.org/abs/2607.19194v1)**
   作者: Zhongyao Yang et al.
   一句话说明：提出面向自动驾驶的双认知规划框架，结合结构化场景知识与视觉语言模型实现可验证的推理-动作一致性，为端到端自动驾驶的可解释性提供了新方案。

3. **[ABot-World-0: Infinite Interactive World Rollout on a Single Desktop GPU](http://arxiv.org/abs/2607.19191v1)**
   作者: Fan Jiang et al.
   一句话说明：发布首个可在单张桌面GPU上运行的无限长闭环交互世界模型，融合游戏、仿真、互联网视频等多源数据训练可控动力学，支持智能体驱动的开放世界探索。

4. **[Agentic Real2Sim: Physics-based World Modeling with Vision-Language Agents](http://arxiv.org/abs/2607.19190v1)**
   作者: Guanxiong Chen et al.
   一句话说明：提出视觉语言智能体驱动的Real2Sim流程，可自动还原场景几何、物体状态与物理参数，实现端到端的真实场景到仿真环境的迁移，大幅降低机器人仿真部署的人工成本。

---

### 🔧 方法与框架（新技术、基准测试、效率优化）
1. **[Point Ladder Tuning: Parameter-Efficient Hierarchical Adaptation for 3D Point Cloud Understanding](http://arxiv.org/abs/2607.19171v1)**
   作者: Junlin Chang et al.
   一句话说明：提出面向3D点云的参数高效微调方法，通过分层适配保留细粒度几何特征，相比全参数微调降低70%以上的计算开销，同时取得更优的下游任务性能。

2. **[One Model, Many Graphs: Learning over Attributed Graphs across Heterogeneous Modalities with Vision-Language Models](http://arxiv.org/abs/2607.19128v1)**
   作者: Jiayi Yang et al.
   一句话说明：首次将视觉语言模型作为通用骨干用于异质模态属性图学习，支持文本、图像等不同模态的图数据统一建模，大幅提升跨域图任务的泛化能力。

3. **[Where Should Optimizer State Live? Tiered State Allocation for Memory-Efficient Mixture-of-Experts Training](http://arxiv.org/abs/2607.19058v1)**
   作者: Nuemaan Malik
   一句话说明：针对MoE大模型训练中优化器状态占内存过高的痛点，提出分层状态分配机制SkewAdam，可将6.78B参数MoE的优化器内存占用降低超过40%，大幅提升大模型训练效率。

4. **[Spectral Higher-Order Neural Networks Have Sharp Expressivity Bounds](http://arxiv.org/abs/2607.19042v1)**
   作者: Gianluca Peri et al.
   一句话说明：从理论上证明了谱参数化高阶神经网络的清晰表达界，解决了传统超图神经网络参数爆炸的核心问题，为高阶图模型的落地提供了理论支撑。

---

### 📊 应用（垂直领域、多模态、代码生成）
1. **[DBMol: Design of High-Affinity, Target-Specific Small Molecules through Structure Prediction Models](http://arxiv.org/abs/2607.19237v1)**
   作者: Yiming Qin et al.
   一句话说明：突破性地将AlphaFold3等高精度结构预测模型整合到小分子设计流程，直接基于靶点口袋的动态结构优化分子亲和力，实现高亲和力、靶点特异性的小分子从头设计。

2. **[ATLAS: A Foundation Neural Sampler for Amorphous Materials](http://arxiv.org/abs/2607.19198v1)**
   作者: Mouyang Cheng et al.
   一句话说明：提出面向非晶材料的基础神经采样器ATLAS，解决了玻璃化转变温度以下传统分子动力学/蒙特卡洛方法采样效率极低的痛点，可高效探索非晶材料的复杂能量景观。

3. **[Now You See the Hate: Adaptive View Retrieval for Hidden Hateful Illusions](http://arxiv.org/abs/2607.19061v1)**
   作者: Qianpu Chen et al.
   一句话说明：针对现有多模态安全系统无法检测隐藏式仇恨光学幻觉的重大漏洞，提出自适应视图检索框架，将仇恨幻觉检测准确率从不足25%提升至85%以上，填补了内容审核的核心盲区。

---

## 研究趋势信号
今日投稿呈现三大明确趋势：一是大模型研究从“追效果”转向“控成本”，推理效率、训练内存优化、成本-质量权衡成为产业落地阶段的核心热点；二是世界模型与智能体的可及性大幅提升，消费级硬件即可支持复杂交互仿真，预示机器人智能体的训练门槛将显著降低；三是多模态AI的安全边界被持续拓展，针对隐藏式攻击、新型幻觉的检测方案开始涌现，成为AI治理的重要技术支撑。

---

## 值得精读
1. **[ABot-World-0: Infinite Interactive World Rollout on a Single Desktop GPU](http://arxiv.org/abs/2607.19191v1)**
   理由：世界模型是通用智能体的核心基础设施，此前的交互世界模型多需大规模算力支持，本工作首次实现单消费级GPU即可运行的无限长闭环世界推演，结合多源跨域数据训练的可控动力学，为智能体训练、机器人仿真落地提供了可及性极高的工具，具有范式级影响。

2. **[DBMol: Design of High-Affinity, Target-Specific Small Molecules through Structure Prediction Models](http://arxiv.org/abs/2607.19237v1)**
   理由：本工作突破性地将AlphaFold3等高精度蛋白结构预测能力端到端整合到小分子设计流程，直接基于靶点口袋的动态结构优化分子亲和力，突破了传统药物设计依赖固定靶点结构的瓶颈，为AI驱动的first-in-class药物发现开辟了新路径。

3. **[Now You See the Hate: Adaptive View Retrieval for Hidden Hateful Illusions](http://arxiv.org/abs/2607.19061v1)**
   理由：多模态大模型的安全漏洞是当前AI治理的核心盲区，本工作首次针对隐藏式仇恨光学幻觉提出有效检测方案，填补了现有内容审核系统的重大短板，对多模态AI的大规模安全部署具有重要的实践指导意义。

---
*本日报由 [agents-radar](https://github.com/THTHDGCS/agents-radar) 自动生成。*