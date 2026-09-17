# ArXiv AI 研究日报 2026-09-17

> 数据来源: [ArXiv](https://arxiv.org/) (cs.RO, cs.AI, cs.LG, cs.CV) | 共 50 篇论文 | 生成时间: 2026-09-17 02:13 UTC

---

# ArXiv AI 研究日报（2026-09-17）

---

## 今日速览
今日ArXiv共更新50篇AI领域相关论文，覆盖大模型架构、对齐、智能体、理论方法及垂直应用等核心方向。大模型领域涌现零阶偏好对齐、高阶MoE专家剪枝、实时权重生成的无限参数范式等突破，推动架构与对齐技术的路径创新。智能体研究聚焦长程任务能力提升与风险治理，双过程认知扩展、组合式政策违规等成果为落地场景的效能与安全提供支撑。理论层面首次基于统计力学将双下降现象与最小作用量原理关联，为深度学习泛化性研究提供了全新视角。

---

## 重点论文

### 🧠 大语言模型（架构、训练、对齐、评估）
1. **[A Zeroth-Order Paradigm for LLM Preference Alignment](http://arxiv.org/abs/2609.19144v1)**  
   作者: Peter Chen et al.  
   一句话说明：提出大模型偏好对齐的零阶优化新范式，解决了小似然边距偏好对的信息提取难题，突破了现有DPO类方法的固有局限。

2. **[Higher-order pruning of experts in mixture-of-experts language models](http://arxiv.org/abs/2609.18916v1)**  
   作者: Alex M. Tseng et al.  
   一句话说明：提出MoE语言模型的高阶专家剪枝方法，打破了现有独立剪枝单专家的假设，显著降低内存瓶颈的同时更好保留模型性能。

3. **[Infinite-Parameter LLMs: Generating and Adapting Weights from Live Data](http://arxiv.org/abs/2609.18842v1)**  
   作者: Jinli Hu et al.  
   一句话说明：提出“无限参数大模型”新范式，无需预存海量参数，而是从实时数据生成并适配权重，挑战了现有MoE架构的scaling路径。

4. **[Rethinking Critic Learning in PPO: Understanding and Mitigating Value Flattening](http://arxiv.org/abs/2609.18708v1)**  
   作者: Yizhuo Li et al.  
   一句话说明：发现PPO对齐中批评家的“价值平坦化”系统性失败模式，揭示了状态值估计同质化导致的政策更新方差问题，并提出缓解方案。

5. **[Beyond Truncation: Rethinking LLM Decoding as Ensemble Pruning](http://arxiv.org/abs/2609.18723v1)**  
   作者: Dunyao Xue et al.  
   一句话说明：提出马氏集成解码（ME-Decoding）新框架，将token选择重构为集成剪枝问题，利用语义几何关系提升解码质量，突破了传统标量概率的局限。

---

### 🤖 智能体与推理（规划、工具使用、多智能体、思维链）
1. **[Cognitive Extensions for Dual-Process Language Agents: Memory and Self-Reflection in Interactive Environments](http://arxiv.org/abs/2609.19128v1)**  
   作者: João Meneses dos Santos et al.  
   一句话说明：为双过程语言代理SwiftSage新增记忆与自反思两个认知模块，显著提升了交互环境下的长程状态跟踪、错误恢复与任务成功率。

2. **[Compositional Policy Violations: When Step-Level Compliance Fails In Agentic AI Workflows](http://arxiv.org/abs/2609.18820v1)**  
   作者: Ashwini Kurady et al.  
   一句话说明：首次系统提出智能体工作流的“组合式政策违规”问题，揭示了单步步合规但整体违规的隐忧，为智能体治理提供了全新的风险视角。

3. **[CERA-MoA: Co-Evolving Routing Mechanisms with Continually Learning LLM Agents](http://arxiv.org/abs/2609.18779v1)**  
   作者: Jiaxuan Jiang et al.  
   一句话说明：提出路由机制与持续学习智能体共同进化的MoA框架，解决了现有混合智能体架构中路由与代理能力演化脱节的问题，提升了动态场景下的响应效率。

4. **[Clueing up LLMs with Tool-Augmented Deductive Reasoning](http://arxiv.org/abs/2609.18736v1)**  
   作者: Rebecca Ansell et al.  
   一句话说明：提出工具增强的演绎推理框架，解决了LLM长推理链中一致性差、信念更新困难的问题，提升了复杂逻辑任务的表现。

---

### 🔧 方法与框架（新技术、基准测试、效率优化）
1. **[Objective vs. Search: Decomposing What Makes a Good Tokeniser](http://arxiv.org/abs/2609.19145v1)**  
   作者: Ahmetcan Yavuz et al.  
   一句话说明：将BPE与Unigram两种主流tokenizer的差异拆解为优化目标与搜索过程两个正交维度，澄清了过往对比中的混淆变量，为tokenizer设计提供了系统性指导。

2. **[ASLEval: Measuring Privacy Exposure Displacement in LLM Agent Sessions](http://arxiv.org/abs/2609.18864v1)**  
   作者: Guosen Wu et al.  
   一句话说明：提出面向LLM智能体会话的隐私暴露位移评估框架ASLEval，解决了现有局部隐私评估漏检多步会话中隐私泄露的问题，提供了统一的评测基准。

3. **[Double descent is the principle of least action](http://arxiv.org/abs/2609.19076v1)**  
   作者: Congzhou M Sha  
   一句话说明：基于统计力学首次将深度学习的双下降现象与最小作用量原理关联，从优化轨迹的能量视角解释了泛化误差的非单调变化，为深度学习理论提供了全新框架。

---

### 📊 应用（垂直领域、多模态、代码生成）
1. **[rMuscle: Robotic Muscle Memory for Efficient Vision-Language-Action Model Inference](http://arxiv.org/abs/2609.19104v1)**  
   作者: Kaijun Zhou et al.  
   一句话说明：提出机器人“肌肉记忆”机制，通过缓存重复任务的动作序列加速VLA模型推理，显著降低了工厂等结构化场景下的推理延迟与计算成本。

2. **[Interpretable Multi-Instance Learning Enables Early Prediction of Key Molecular Alterations from Routine Flow Cytometry in Acute Myeloid Leukemia](http://arxiv.org/abs/2609.18825v1)**  
   作者: Jonathan Legrand et al.  
   一句话说明：提出可解释多示例学习方法，可从常规流式细胞术数据中提前预测AML的NPM1和FLT3-ITD突变，将原本需要数周的基因检测缩短至小时级，具备重要临床价值。

3. **[MUSE: Benchmarking Large Vision-Language Models on Multi-Modal Understanding in Situated Education](http://arxiv.org/abs/2609.19088v1)**  
   作者: Luyao Zhu et al.  
   一句话说明：推出面向情境教育场景的多模态理解基准MUSE，覆盖艺术意象、情感文化内涵等教育场景特有需求，填补了教育领域多模态模型评测的空白。

---

## 研究趋势信号
今日投稿呈现三大核心趋势：一是智能体治理从单步输入输出的浅层合规，转向多步骤工作流的组合式风险防控，精准匹配落地场景中的复杂政策要求；二是大模型架构开始突破MoE“预存参数+动态激活”的路径依赖，探索从实时数据生成适配权重的无限参数新范式；三是对齐领域涌现零阶优化等新路径，试图解决小似然边距偏好对的信息提取难题，为RLHF之外的轻量对齐方案提供新思路。

---

## 值得精读
1. **[《Objective vs. Search: Decomposing What Makes a Good Tokeniser》](http://arxiv.org/abs/2609.19145v1)**  
   理由：tokenizer是大模型的核心基础组件，直接影响下游所有任务的性能，但长期以来BPE与Unigram的优劣对比始终混淆了优化目标和搜索过程两个关键变量。本文通过正交分解的实验设计，系统澄清了两类算法的核心差异与适用场景，对后续tokenizer的设计与选型有极强的基础性指导意义，实验严谨、结论普适。

2. **[《Double descent is the principle of least action》](http://arxiv.org/abs/2609.19076v1)**  
   理由：双下降是深度学习中普遍存在却缺乏统一理论解释的关键现象，直接关系到对模型泛化性的底层认知。本文从统计力学视角出发，将随机梯度下降的训练轨迹与最小作用量原理关联，为双下降的非单调泛化误差提供了简洁且自洽的理论解释，是深度学习理论领域的突破性进展，可能推动后续一系列相关研究。

3. **[《Compositional Policy Violations: When Step-Level Compliance Fails In Agentic AI Workflows》](http://arxiv.org/abs/2609.18820v1)**  
   理由：智能体落地的核心瓶颈之一是合规性，当前业界几乎所有的智能体安全方案都聚焦单步输入输出的内容检查。本文首次系统提出“组合式政策违规”的概念，揭示了“步步合规但整体违规”的隐性风险，直接击中了当前智能体治理的盲区，对产业界的智能体风险管控有极强的现实指导意义，会带动后续大量相关研究与技术落地。

---
*本日报由 [agents-radar](https://github.com/THTHDGCS/agents-radar) 自动生成。*