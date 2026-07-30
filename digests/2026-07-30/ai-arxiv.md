# ArXiv AI 研究日报 2026-07-30

> 数据来源: [ArXiv](https://arxiv.org/) (cs.RO, cs.AI, cs.LG, cs.CV) | 共 50 篇论文 | 生成时间: 2026-07-30 01:18 UTC

---

# ArXiv AI 研究日报（2026-07-30）

## 今日速览
2026年7月30日ArXiv AI领域投稿集中于具身智能与机器人技术方向，视觉语言动作（VLA）模型、潜世界模型的性能与落地性取得多项关键突破。同时出现了多个面向自动驾驶、生物医疗等垂直场景的开源基准与数据集，推动领域研究的标准化与可复现性。此外，大模型高效微调、可信AI评估等方向的创新也为AI从仿真环境走向真实物理世界提供了重要支撑。

## 重点论文
### 🧠 大语言模型（架构、训练、对齐、评估）
- **[Pass the Baton: Trajectory-Relayed On-Policy Distillation](http://arxiv.org/abs/2607.26057v1)**
  作者：Haolei Xu 等
  一句话说明：针对大模型on-policy蒸馏中常见的前缀失败问题，提出轨迹接力的蒸馏机制，避免学生模型因早期推理偏差产生无效监督，显著提升蒸馏后的模型推理准确性。

### 🤖 智能体与推理（规划、工具使用、多智能体、思维链）
- **[From Passive Video to Editable Experience: Physically Grounded Experience Synthesis for Embodied Intelligence](http://arxiv.org/abs/2607.26903v1)**
  作者：Jia Luo 等
  一句话说明：提出Pegasus框架，将网上海量的人类操作视频转化为机器人可直接学习的物理锚定经验，解决具身AI的核心数据瓶颈，无需大量真实机器人采集数据。
- **[What Can Latent World Models Know? Physical Parameter Identifiability in Multimodal Predictive Representations](http://arxiv.org/abs/2607.27017v1)**
  作者：Kaizhen Tan 等
  一句话说明：通过POKEWORLD可控干预实验，系统回答了潜世界模型能编码哪些物理参数、哪些因素决定编码能力，为世界模型的可解释性与优化提供核心依据。
- **[INTACT: Isomorphic Intent-to-Action Learning for Search-Free World Models](http://arxiv.org/abs/2607.26056v1)**
  作者：Junhan Sun 等
  一句话说明：提出端到端的意图到动作映射框架，让世界模型无需昂贵的测试时搜索即可直接从目标意图生成对应动作，大幅提升具身规划的推理效率。
- **[ActSWM: Action-Sensitive World Models for Long-Horizon Planning in Open-World Games](http://arxiv.org/abs/2607.26712v1)**
  作者：Zhenfeng Gan 等
  一句话说明：提出动作敏感的世界模型，解决现有潜世界模型长时序滚动不稳定、预测精度与规划效果脱钩的问题，显著提升开放世界长程任务的规划成功率。
- **[Embodied Agents Take Control: Minimal-Interface Zero-Shot Agents Rival Industrial-Scale Policies in Vision-and-Language Navigation](http://arxiv.org/abs/2607.26148v1)**
  作者：Jian Zhou 等
  一句话说明：提出最小接口的零样本具身控制范式，无需任务特定微调或定制化工作流，即可在视觉语言导航任务上达到工业级专用策略的性能。

### 🔧 方法与框架（新技术、基准测试、效率优化）
- **[Spend Experts Where You Are Unsure: Confidence-Adaptive Routing for Mixture-of-Experts LoRA](http://arxiv.org/abs/2607.26052v1)**
  作者：Tom Saliencro 等
  一句话说明：提出置信度自适应的MoE LoRA路由机制，根据token的不确定性动态分配专家数量，避免资源浪费在简单token上，同时提升困难样本的处理效果。
- **[RL²-VLA: Adaptive RL Latent Compositional Steering with Test-Time Scaling for Vision-Language-Action Models](http://arxiv.org/abs/2607.26991v1)**
  作者：Derek Ming Siang Tan 等
  一句话说明：提出VLA模型的测试时缩放与潜层组合引导方法，无需额外数据收集和重新训练，即可显著提升VLA在困难、分布外任务上的性能。
- **[NeoRacer: An Open, Standardized 1:12 Scale Autonomous Race Car for Benchmarking and Education](http://arxiv.org/abs/2607.26855v1)**
  作者：Koneshka Bandyopadhyay 等
  一句话说明：开源标准化的1:12比例自主赛车平台，填补了自主系统研究缺乏通用硬件基准的空白，可用于算法验证、可复现性研究与教学。
- **[Towards Trustworthy Embodied Intelligence: A Systems Framework and Graded Trustworthiness Levels](http://arxiv.org/abs/2607.26121v1)**
  作者：Xinyu Yang 等
  一句话说明：首次提出具身智能的可信性分级标准与系统设计框架，针对具身智能的物理交互风险建立了系统化的评估准则，为落地安全提供支撑。
- **[Desktop-Delta Bench: Do Computer-Use Models Understand Desktop GUI Transitions?](http://arxiv.org/abs/2607.26041v1)**
  作者：Abhishek Pillai 等
  一句话说明：提出首个专门评估计算机使用模型对GUI状态转换因果理解的基准，弥补了现有评估只关注端任务成功率、忽略核心推理能力的缺陷。

### 📊 应用（垂直领域、多模态、代码生成）
- **[Controlled Experiments on Lane Changing by Transitional Autonomous Vehicle: Dataset and Behavioral Insights](http://arxiv.org/abs/2607.27085v1)**
  作者：Abhinav Sharma 等
  一句话说明：发布NC-tALC过渡性自动驾驶换道数据集，量化了自动驾驶汽车强制换道过程中的前后车距演化规律，为自动驾驶换道策略开发提供真实数据支撑。
- **[BioVLN: A Simulation Platform for Visual Language Navigation in Biomedical Laboratories](http://arxiv.org/abs/2607.26914v1)**
  作者：Zhe Liu 等
  一句话说明：推出首个面向生物医疗实验室场景的视觉语言导航仿真平台，针对实验室仪器的精准停靠需求定制化设计，助力实验室服务机器人开发。
- **[VetClaw: An Edge-Cloud Multimodal Agentic System for Veterinary Disease Screening](http://arxiv.org/abs/2607.26042v1)**
  作者：Syed Mhamudul Hasan 等
  一句话说明：开发边云协同的多模态兽医疾病筛查系统，通过边缘端采集图像与症状描述，云端VLM实现零样本疾病分类，适合基层畜牧场景的快速筛查。

## 研究趋势信号
本期投稿显示具身智能已成为AI领域核心攻坚方向，世界模型与视觉语言动作（VLA）模型的优化重点已从实验室性能转向真实场景落地：一方面大量研究聚焦解决长时序规划不稳定、sim2real差距、推理效率低等落地痛点；另一方面面向垂直场景的开源基准与标准化平台快速涌现，大模型的高效微调、路由技术也开始向具身领域渗透，推动具身AI从探索阶段向工业级应用过渡。

## 值得精读
1. **《From Passive Video to Editable Experience: Physically Grounded Experience Synthesis for Embodied Intelligence》**
   理由：具身AI的核心瓶颈一直是训练数据不足，该论文提出的Pegasus框架可将互联网上海量的人类操作视频转化为机器人可直接学习的物理锚定经验，无需大量真实机器人数据采集，是具身AI数据范式的重要突破，对降低具身智能的训练成本、加速通用化进程有重大意义。
2. **《What Can Latent World Models Know? Physical Parameter Identifiability in Multimodal Predictive Representations》**
   理由：世界模型是具身智能与通用AI的核心组件，但其可解释性一直是领域难题。该论文通过可控实验系统回答了“世界模型到底学到了什么物理知识”这一核心问题，为后续世界模型的架构优化、能力评估提供了科学依据，是世界模型领域的基础性研究。
3. **《Embodied Agents Take Control: Minimal-Interface Zero-Shot Agents Rival Industrial-Scale Policies in Vision-and-Language Navigation》**
   理由：该论文证明了仅用最小接口的通用零样本智能体，无需任务特定微调或定制化工作流，即可达到工业级专用策略的性能，打破了“具身任务必须定制化开发”的固有认知，为通用具身智能的实现提供了新的可行路径。

---
*本日报由 [agents-radar](https://github.com/THTHDGCS/agents-radar) 自动生成。*