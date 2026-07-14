# ArXiv AI 研究日报 2026-07-14

> 数据来源: [ArXiv](https://arxiv.org/) (cs.RO, cs.AI, cs.LG, cs.CV) | 共 18 篇论文 | 生成时间: 2026-07-14 01:19 UTC

---

# ArXiv AI 研究日报（2026-07-14）

---

## 今日速览
2026年7月14日ArXiv更新的18篇AI相关研究以机器人领域技术落地为核心方向，覆盖水下测绘、运动规划、多任务操纵、自主探索等核心场景。扩散模型、世界模型、知识蒸馏等通用AI技术与机器人场景的深度结合成为突出亮点，多篇工作提出零样本Sim-to-Real、免训练可控性优化等方案，大幅降低技术落地门槛。此外还有覆盖路径规划方向的系统性综述，梳理该领域从经典方法到前沿进展的完整脉络，为研究者提供权威参考。跨模态蒸馏、仿生感知等方向也出现了面向3D场景理解、模型鲁棒性提升的创新方案。

---

## 重点论文
### 🧠 大语言模型（架构、训练、对齐、评估）
1. **[Traj-VLN: Learning Pixel-Space Interaction via Autoregressive Trajectory Generation](http://arxiv.org/abs/2607.10744v1)**
   作者：Changfei Fu 等
   一句话说明：将大语言模型的通用预训练先验引入视觉语言导航（VLN）任务，通过自回归轨迹生成范式学习像素空间交互，大幅提升跨场景泛化能力。

### 🤖 智能体与推理（规划、工具使用、多智能体、思维链）
1. **[World Models as Adversaries: Multi-Agent Self-Play Fine-Tuning for Robust Motion Planning](http://arxiv.org/abs/2607.10630v1)**
   作者：Tong Nie 等
   一句话说明：提出将世界模型作为对抗对手的多智能体自博弈微调范式，无需外部场景生成器即可生成稀有安全关键场景，提升自动驾驶运动规划鲁棒性。
2. **[Coverage Path Planning: Classical Foundations, Recent Advances, and Future Directions](http://arxiv.org/abs/2607.10649v1)**
   作者：Zongyuan Shen 等
   一句话说明：覆盖路径规划（CPP）领域的系统性综述，梳理经典理论基础、近年AI驱动进展与未来研究方向，为机器人覆盖任务研究提供完整参考框架。
3. **[Action Map Policy: Learning 3D Closed-loop Manipulation via Pixel Classification](http://arxiv.org/abs/2607.10706v1)**
   作者：Haojie Huang 等
   一句话说明：提出动作映射策略新范式，将3D闭环操纵任务转化为像素分类问题，有效破解机器人学习中高维动作空间的优化难题。
4. **[SLIDER: Sparse History-Guided Aerial Robot Target Search using Sliding Local Maps](http://arxiv.org/abs/2607.10553v1)**
   作者：Xiaolei Hou 等
   一句话说明：提出轻量内存高效的空中机器人目标搜索框架SLIDER，通过稀疏历史引导和滑动局部地图，解决大规模未知环境下的高效探索难题。
5. **[Dual-Process Atomic Skill Learning: Decoupling Semantic Reasoning and Real-Time Control](http://arxiv.org/abs/2607.10625v1)**
   作者：Jun Chen 等
   一句话说明：提出双过程原子技能学习框架，解耦语言条件机器人任务中的语义推理与实时控制，大幅提升多步骤组合任务的泛化能力。

### 🔧 方法与框架（新技术、基准测试、效率优化）
1. **[Is Energy Guidance All You Need? Training-Free Norm Injection for Driving World Models](http://arxiv.org/abs/2607.10781v1)**
   作者：Xiyan Su 等
   一句话说明：提出无需训练的驾驶世界模型范数注入方法，仅通过能量引导即可实现交通规则约束，避免大模型骨干的重新训练或手工布局条件。
2. **[D-SafeMPC: Diffusion-Driven Safe Model Predictive Control with Discrete-Time Control Barrier Functions](http://arxiv.org/abs/2607.10842v1)**
   作者：Erdi Sayar 等
   一句话说明：提出扩散驱动的安全模型预测控制框架D-SafeMPC，结合离散时间控制障碍函数，解决扩散模型在机器人规划中无法原生保证安全约束的痛点。
3. **[TOLiD: Bridging the Architecture Gap in Vision Foundation Model to LiDAR Pretraining via Token Lifting for Distillation](http://arxiv.org/abs/2607.10762v1)**
   作者：Sutharsan Mahendran 等
   一句话说明：提出Token提升蒸馏框架TOLiD，打通视觉基础模型到LiDAR骨干的预训练架构鸿沟，减少3D场景理解对密集点云标注的依赖。
4. **[BucketKD: A Safety-Aware Bucket-Based Knowledge Distillation Framework for End-to-End Motion Planning](http://arxiv.org/abs/2607.10565v1)**
   作者：Md Nahidul Islam 等
   一句话说明：提出安全感知的分桶式知识蒸馏框架BucketKD，在保证端到端自动驾驶运动规划性能与安全性的前提下，大幅压缩模型体积适配资源受限平台。
5. **[A Single Diffusion-Policy Controller for Multi-Task Block Pushing with Zero-Shot Sim-to-Real Transfer](http://arxiv.org/abs/2607.10892v1)**
   作者：Haitong Ma 等
   一句话说明：首次探索用强化学习从零训练扩散策略控制器，实现多任务推块的零样本Sim-to-Real迁移，突破行为克隆训练扩散策略的局限。

### 📊 应用（垂直领域、多模态、代码生成）
1. **[Mapping Pamir: Multi-Session Visual-Inertial SLAM and 3D Reconstruction of an Underwater Shipwreck](http://arxiv.org/abs/2607.10925v1)**
   作者：Michalis Chatzispyrou 等
   一句话说明：提出低成本多会话水下VI-SLAM框架，仅用消费级运动相机和潜水电脑深度数据，实现水下沉船的高精度3D重建，大幅降低水下测绘硬件门槛。
2. **[X-GuideAR: An Augmented Reality Framework to Mitigate Radiation Exposure during Fluoroscopic Guidance](http://arxiv.org/abs/2607.10873v1)**
   作者：Mingxu Liu 等
   一句话说明：提出骨科手术AR引导框架X-GuideAR，减少透视引导过程中的“透视搜寻”步骤，大幅降低患者与医护人员的X射线辐射暴露。
3. **[3D Scene Graph Prediction: Generating Hierarchical Models from Partially Observed Environments](http://arxiv.org/abs/2607.10879v1)**
   作者：Siyi H 等
   一句话说明：提出3D场景图预测方法，可从部分观测环境生成包含房间连接、物体层级的结构化场景模型，支撑机器人导航、室内设计等场景应用。
4. **[SensorPerch: Sense Wherever and Whenever it Matters](http://arxiv.org/abs/2607.10682v1)**
   作者：Zhanxin Wu 等
   一句话说明：提出可部署的移动感知系统SensorPerch，机器人可将传感器临时部署在环境中任意位置，获取任务最优视角，提升复杂场景感知能力。
5. **[Artificial Foveated Perception for Mitigating Shortcut Learning in Robotic Foundation Models](http://arxiv.org/abs/2607.10655v1)**
   作者：Xiatao Sun 等
   一句话说明：提出模拟人类视觉注意力的人工凹感知方法，有效缓解机器人基础模型的捷径学习问题，提升真实场景部署的鲁棒性。

---

## 研究趋势信号
今日投稿呈现三大明确趋势：一是通用AI技术与机器人场景深度绑定，扩散模型、世界模型、基础模型蒸馏不再局限于通用任务，而是针对机器人的安全约束、端侧部署需求做定制化改造；二是落地友好型技术成为热点，零样本Sim-to-Real、免训练优化、轻量高效框架的研究占比显著提升，瞄准资源受限场景的落地需求；三是垂直场景痛点解决优先，水下测绘、医疗手术、自动驾驶等领域的方案更注重实际场景问题，而非纯算法的理论创新。

---

## 值得精读
1. **《Coverage Path Planning: Classical Foundations, Recent Advances, and Future Directions》**：作为覆盖路径规划领域的权威综述，系统梳理了从经典几何方法到AI驱动方法的完整发展脉络，涵盖理论基础、应用场景与未来方向，是入门该领域的核心参考资料。
2. **《Is Energy Guidance All You Need? Training-Free Norm Injection for Driving World Models》**：提出免训练的世界模型可控性优化方案，突破了传统需要重训大模型或依赖手工条件的局限，对世界模型在自动驾驶等场景的落地具有重要启发意义。
3. **《World Models as Adversaries: Multi-Agent Self-Play Fine-Tuning for Robust Motion Planning》**：创新性地将世界模型作为对抗对手，无需外部场景生成器即可生成稀有安全关键场景，为自动驾驶鲁棒规划提供了全新的低成本技术路径。

---
*本日报由 [agents-radar](https://github.com/THTHDGCS/agents-radar) 自动生成。*