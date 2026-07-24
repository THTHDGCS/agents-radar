# ArXiv AI 研究日报 2026-07-24

> 数据来源: [ArXiv](https://arxiv.org/) (cs.RO, cs.AI, cs.LG, cs.CV) | 共 50 篇论文 | 生成时间: 2026-07-24 01:29 UTC

---

# ArXiv AI 研究日报 | 2026年7月24日
（覆盖cs.AI、cs.CL、cs.LG领域共50篇最新投稿）

---

## 今日速览
今日ArXiv AI领域投稿聚焦三大核心方向。一是多模态大模型的专项能力优化与评测，涵盖幻觉诊断、空间推理校正、合规遗忘、高效压缩等落地核心痛点。二是生成式AI的实用化技术突破，扩散模型的测试时调优、低比特量化、高效反演等技术大幅提升编辑、生成任务的可用性。三是垂直领域AI的落地进展，自动驾驶、医疗、机器人等场景的方案更强调鲁棒性与领域适配性，多个细分任务的标准化基准同步发布，推动技术的可复现与公平对比。

---

## 重点论文
### 🧠 大语言模型（架构、训练、对齐、评估）
1. **[HalluScope: Fine-grained Hallucination Diagnosis for Multimodal Large Language Models](http://arxiv.org/abs/2607.21105v1)**
   作者：Jin W等
   一句话说明：提出细粒度MLLM幻觉诊断框架，可区分视觉不符、文本矛盾、常识违背三类幻觉来源，突破了过往粗粒度评估的局限，为MLLM对齐优化提供精准依据。

2. **[Geo3R: Mitigating Spatial Reasoning Hallucination in Multimodal Large Language Models](http://arxiv.org/abs/2607.21085v1)**
   作者：Wang M等
   一句话说明：针对MLLM空间关系推理不符合真实3D结构的共性问题，提出空间推理幻觉缓解方案，提升多模态模型的物理场景认知可靠性。

3. **[C-PTQ: Fisher-weighted Channel-wise Sensitivity for Post-training Quantization of MLLMs](http://arxiv.org/abs/2607.21076v1)**
   作者：Li J等
   一句话说明：提出基于Fisher加权通道敏感度的MLLM后训练量化方法，在4-8比特量化下大幅保留模型精度，为大模型端侧部署提供高效压缩方案。

4. **[Unlearning Under Imbalance: Benchmarking Fairness in Multimodal LLM Unlearning](http://arxiv.org/abs/2607.21300v1)**
   作者：Orsingher L等
   一句话说明：首次建立不平衡数据下MLLM机器遗忘的公平性评估基准，为符合全球AI数据合规要求的遗忘技术提供标准化测评体系。

---

### 🤖 智能体与推理（规划、工具使用、多智能体、思维链）
1. **[GS-Agent: Creating 4D Physical Worlds With Generative Simulation](http://arxiv.org/abs/2607.21522v1)**
   作者：Zhang H等
   一句话说明：提出基于自然语言描述生成符合物理规则的4D动态世界的智能体框架，替代传统手工CG制作流程，大幅降低虚拟场景、机器人仿真的构建成本。

2. **[Compact Latent Coordination for Autonomous Vehicles at Unsignalized Intersections](http://arxiv.org/abs/2607.21488v1)**
   作者：Lifshits G等
   一句话说明：提出紧凑隐式协调的多智能体方案，解决无信号路口自动驾驶动作空间爆炸、依赖特权信息的痛点，提升复杂路口通行效率与安全性。

3. **[FORGE-plus: Force-Budgeted Recovery for Contact-Rich Assembly with a Frozen LLM Supervisor](http://arxiv.org/abs/2607.21227v1)**
   作者：Rah K J等
   一句话说明：提出两层机器人框架，用冻结大模型作为高层监督器，实现力约束下的工业装配故障自动恢复，无需微调大模型即可适配多类装配任务。

---

### 🔧 方法与框架（新技术、基准测试、效率优化）
1. **[ElasticTTT: Prior-Preserving Test-Time Tuning for Video Editing](http://arxiv.org/abs/2607.21529v1)**
   作者：Liu Y等
   一句话说明：提出保留预训练先验的测试时调优框架，解决扩散模型视频编辑中生成分布映射与单样本优化的底层矛盾，大幅提升视频编辑的时序一致性与内容保真度。

2. **[KroQuant: Kronecker-Structured Block Transforms for Efficient Post-Training Quantization of Diffusion Transformers](http://arxiv.org/abs/2607.21446v1)**
   作者：Bouquet Y等
   一句话说明：提出基于克罗内克结构变换的扩散Transformer（DiT）W4A4后训练量化方法，解决激活离群点导致的量化质量崩溃问题，推动大尺寸生成模型的端侧落地。

3. **[T-STAR: A Large-Scale Benchmark for Spatio-Temporal Panoptic Scene Graph Generation in Satellite Video](http://arxiv.org/abs/2607.21228v1)**
   作者：Wang L等
   一句话说明：发布首个大规模卫星视频时空全景场景图生成基准，推动遥感影像分析从目标检测向高层动态场景认知升级，支撑国土监测、灾害响应等应用。

---

### 📊 应用（垂直领域、多模态、代码生成）
1. **[Boosting Robustness for All-Weather Self-Supervised Depth Estimation in Autonomous Driving](http://arxiv.org/abs/2607.21526v1)**
   作者：Qi M等
   一句话说明：针对雨雾雪等恶劣天气下自动驾驶传感器感知退化的问题，提出鲁棒自监督深度估计方案，支撑全天候自动驾驶的安全落地。

2. **[ASTRA-Net: Anatomy-Specific Transfer and Representation Alignment for Drug-Induced Sleep Endoscopy Segmentation](http://arxiv.org/abs/2607.21370v1)**
   作者：Sun S等
   一句话说明：提出解剖特异性迁移的医学影像分割模型，解决睡眠内镜标注稀缺的痛点，实现气道病变的自动化定量评估，助力睡眠呼吸暂停诊疗。

3. **[GLAM-SLAM: Real-time Gaussian Large-scale Mapping via Flow Densification and Spatial Decomposition](http://arxiv.org/abs/2607.21416v1)**
   作者：Mermigkas P等
   一句话说明：提出实时大规模高斯建图SLAM系统，解决现有高斯SLAM显存占用高、无法处理长序列的问题，支撑机器人长周期导航、AR场景建模等应用。

---

## 研究趋势信号
今日投稿显现三大明确趋势：一是多模态大模型（MLLM）的研究从通用能力建设转向细粒度专项能力优化，幻觉诊断、空间推理校正、遗忘公平性等落地瓶颈问题成为热点；二是扩散类生成模型加速向实用化演进，低比特量化、高效反演、测试时调优的技术密集涌现；三是垂直领域AI更强调领域先验融合，自动驾驶、医疗、机器人场景的方案普遍贴合真实落地约束。

---

## 值得精读
1. **[ElasticTTT: Prior-Preserving Test-Time Tuning for Video Editing](http://arxiv.org/abs/2607.21529v1)**
   理由：该工作从底层揭示了扩散模型测试时调优的核心矛盾——生成模型的分布映射特性与单样本优化的不匹配，提出的先验保留调优框架不仅可直接提升视频编辑效果，对所有基于扩散的生成式编辑任务都具有底层方法论价值，实验设计严谨，结论普适性强。

2. **[HalluScope: Fine-grained Hallucination Diagnosis for Multimodal Large Language Models](http://arxiv.org/abs/2607.21105v1)**
   理由：MLLM幻觉是当前产业落地的核心瓶颈，该工作首次实现了细粒度、多来源的幻觉分类与诊断，可精准定位幻觉源于视觉感知、文本上下文还是常识偏差，为后续MLLM对齐、评测提供了统一的工具框架，兼具学术与产业价值。

3. **[GS-Agent: Creating 4D Physical Worlds With Generative Simulation](http://arxiv.org/abs/2607.21522v1)**
   理由：4D物理世界生成是AIGC从静态内容向动态交互场景演进的核心方向，该工作首次实现了通过自然语言描述生成符合物理规则的4D动态世界，为元宇宙内容创作、机器人仿真训练、数字孪生构建等领域提供了全新的技术路径。

---
*本日报由 [agents-radar](https://github.com/THTHDGCS/agents-radar) 自动生成。*