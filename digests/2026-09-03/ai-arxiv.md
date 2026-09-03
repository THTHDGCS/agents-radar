# ArXiv AI 研究日报 2026-09-03

> 数据来源: [ArXiv](https://arxiv.org/) (cs.RO, cs.AI, cs.LG, cs.CV) | 共 50 篇论文 | 生成时间: 2026-09-03 01:54 UTC

---

# ArXiv AI 研究日报（2026-09-03）

---

## 今日速览
今日ArXiv AI领域研究呈现「基础机制突破+场景落地深化+基准体系完善」的三线并行特征。基础研究层面，稀疏MoE模型跨层路由的共享几何规律、LLM作为经济主体的市场行为特性等成果，拓展了对大模型内在机制与社会属性的认知边界。应用层面，跨具身VLA迁移、脑肿瘤精准诊断、人形机器人复杂地形运动等技术，在机器人、医疗、区块链安全等垂直领域实现性能推进。同时，长时序智能体、多模态交错输入评估、零样本图异常检测等方向推出一批新基准与方法框架，为领域后续研究提供了重要参照。

---

## 重点论文

### 🧠 大语言模型（架构、训练、对齐、评估）
1. **Evidence for Shared Routing Geometry and Dynamics in Sparse Mixture-of-Experts**  
   链接: http://arxiv.org/abs/2609.02404v1  
   作者: Kirill Labzin et al.  
   一句话说明: 首次证实稀疏MoE模型不同层的路由决策存在共享的几何结构与动态规律，打破了各层路由独立的传统认知，为MoE架构优化与可解释性研究提供了全新理论依据。

2. **Competitive Market Behavior of LLMs**  
   链接: http://arxiv.org/abs/2609.02580v1  
   作者: Pawel Struski et al.  
   一句话说明: 系统研究了LLM作为经济主体在竞争市场机制中的行为表现，验证了LLM参与人类市场机制的可行性与潜在偏差，为LLM的经济场景落地与风险评估提供了实证基础。

3. **Before the Script, Set the Stage: How Worldview Simulation Amplifies Psychologically Grounded Persuasion in Multi-Turn Jailbreaking**  
   链接: http://arxiv.org/abs/2609.02414v1  
   作者: Siyu Chen et al.  
   一句话说明: 提出BLUEPRINT多轮越狱安全评估框架，将社会影响策略与世界观模拟解耦，揭示了多轮对话中说服机制对越狱效果的放大作用，为大模型对齐与安全防护提供了新的研究视角。

4. **Learn from Whoever Is Right: Answer-Verified Multi-Teacher Distillation for Multi-Domain LLMs**  
   链接: http://arxiv.org/abs/2609.02548v1  
   作者: Xixiang He et al.  
   一句话说明: 提出基于答案验证的多教师蒸馏方法，无需预先匹配领域路由，直接选择输出正确的教师模型进行蒸馏，有效提升了单模型整合多领域能力的效果。

---

### 🤖 智能体与推理（规划、工具使用、多智能体、思维链）
1. **CivBench: A Long-Horizon Benchmark for Tool-Mediated Agents in Civilization VI**  
   链接: http://arxiv.org/abs/2609.02459v1  
   作者: Austin Tudor David Andrews et al.  
   一句话说明: 基于《文明6》构建长时序工具介导智能体基准，单集交互超300轮、包含数千次工具调用，全面覆盖长期规划、资源管理、状态追踪等核心能力，为长周期智能体研究提供了标准化评测平台。

2. **ZETA: A Controlled Study of Zero-Shot Cross-Embodiment VLA Transfer for Tabletop Manipulation**  
   链接: http://arxiv.org/abs/2609.02546v1  
   作者: Mi Yan et al.  
   一句话说明: 针对桌面操作场景开展跨具身VLA零样本迁移的受控研究，统一了评估协议与实验设置，系统揭示了当前VLA模型跨具身泛化的能力边界与影响因素。

3. **Coverage, Not Targeting: A Structural Regime in Multi-Turn Agent Credit Assignment**  
   链接: http://arxiv.org/abs/2609.02417v1  
   作者: Chenyu Zhou et al.  
   一句话说明: 提出验证信息密度（V_d）指标来刻画多轮智能体信用分配的结构特性，证明在低信息密度场景下覆盖式信用分配优于靶向式，为多轮智能体的RL训练提供了理论指导。

---

### 🔧 方法与框架（新技术、基准测试、效率优化）
1. **Deeply Interleaved Text-Image Contexts for Multimodal LLMs Assessment**  
   链接: http://arxiv.org/abs/2609.02573v1  
   作者: Zihao Wang et al.  
   一句话说明: 指出现有多模态LLM评估忽略了文本-图像深度交错的真实场景，提出了对应的评测范式与数据集，填补了多模态模型在复杂 interleaved 输入下的能力评估空白。

2. **RINSE: Robust Target-Time Normality Estimation for Zero-Shot Graph Anomaly Detection**  
   链接: http://arxiv.org/abs/2609.02497v1  
   作者: Taufikur Rahman Fuad et al.  
   一句话说明: 提出无梯度的目标域正态性自估计框架RINSE，通过迭代更新源域正态性假设来缓解域偏移问题，显著提升了零样本图异常检测的鲁棒性。

3. **ViSAR: Training-Free Adaptive-$k$ Retrieval for Visual Document Question Answering**  
   链接: http://arxiv.org/abs/2609.02486v1  
   作者: Adrien Mialland et al.  
   一句话说明: 提出免训练的自适应检索数量方法ViSAR，可根据查询难度动态调整DocVQA任务的检索页数，无需额外训练即可显著提升RAG系统的回答准确率。

4. **Scalable Kronecker-Fisher Approximation: Efficient Hessian Analysis for Billion-Parameter Language Models Compression**  
   链接: http://arxiv.org/abs/2609.02451v1  
   作者: Viacheslav Yusupov et al.  
   一句话说明: 提出可扩展的Kronecker-Fisher近似方法，无需存储完整Fisher矩阵即可捕捉跨层交互，首次实现了十亿参数级大模型的高效Hessian分析，为大模型压缩与脆弱性分析提供了实用工具。

---

### 📊 应用（垂直领域、多模态、代码生成）
1. **ProbeMatchDTI: Probe-Driven Multi-Scale Biochemical Pattern Matching for Drug-Target Interaction Prediction**  
   链接: http://arxiv.org/abs/2609.02549v1  
   作者: Quan Hao et al.  
   一句话说明: 提出探针驱动的多尺度生化模式匹配框架ProbeMatchDTI，有效解决了传统方法中弱结合相关模式被抑制的问题，显著提升了药物-靶点相互作用预测的精度。

2. **World-Model-Augmented Visual Locomotion for Humanoids on Foothold-Constrained Terrain**  
   链接: http://arxiv.org/abs/2609.02542v1  
   作者: Yuxi Liu et al.  
   一句话说明: 将世界模型引入人形机器人视觉运动控制，通过前瞻预测足点可行性提升复杂地形下的运动鲁棒性，在踏脚石、窄楼梯等足点约束场景下实现了性能突破。

3. **The Diagnosis a Reporter Leaves Unspoken: Surfacing Frozen Tumor Features for Brain-Tumor MRI Reporting**  
   链接: http://arxiv.org/abs/2609.02411v1  
   作者: Khawaja Murad ul Hassan et al.  
   一句话说明: 揭示了当前脑肿瘤MRI报告生成模型存在「诊断沉默」问题（罕见肿瘤召回率极低），通过挖掘模型冻结的肿瘤特征将诊断召回率提升数倍，为医学报告生成的临床落地提供了优化方向。

4. **Automated Vulnerability Injection in Smart Contracts Using Large Language Models**  
   链接: http://arxiv.org/abs/2609.02624v1  
   作者: Luca Migliaccio et al.  
   一句话说明: 提出基于LLM的智能合约漏洞自动注入方法，可高效生成带已知漏洞的Solidity合约数据集，解决了智能合约漏洞检测工具评估数据稀缺的行业痛点。

---

## 研究趋势信号
今日投稿呈现三大新兴趋势：一是长时序智能体评估向复杂开放世界场景延伸，单轮交互任务基准逐步被300+轮的工具介导长周期基准替代，更贴合真实智能体的落地需求；二是大模型研究从「性能优先」转向「机制与社会属性并行」，MoE路由规律、LLM经济行为等基础问题受到更多关注；三是零样本泛化技术覆盖更多子领域，跨具身VLA、零样本图异常检测、自适应检索等方向均推出新方案，旨在降低模型对场景特定数据的依赖。

---

## 值得精读
1. **CivBench: A Long-Horizon Benchmark for Tool-Mediated Agents in Civilization VI**（链接: http://arxiv.org/abs/2609.02459v1）  
   理由：长周期、工具介导的开放世界智能体是当前AGI研究的核心前沿，但长期缺乏统一的高质量评估基准。该工作基于经典策略游戏《文明6》构建的评测框架，覆盖300+轮交互、数千次工具调用，全面考察智能体的长期规划、资源管理、工具协同等核心能力，且完全开源，有望成为该领域的标准评测平台，参考价值极高。

2. **Evidence for Shared Routing Geometry and Dynamics in Sparse Mixture-of-Experts**（链接: http://arxiv.org/abs/2609.02404v1）  
   理由：稀疏MoE是下一代大模型规模化的核心架构方向，但目前学界对其路由机制的理解仍停留在表层，普遍假设各层路由相互独立。该研究首次证实不同层的路由决策存在共享的几何结构与动态规律，颠覆了传统认知，为MoE的路由优化、效率提升、可解释性研究提供了全新的理论视角，具有重要的奠基性意义。

3. **World-Model-Augmented Visual Locomotion for Humanoids on Foothold-Constrained Terrain**（链接: http://arxiv.org/abs/2609.02542v1）  
   理由：足点约束地形的运动控制是人形机器人落地的核心技术难点，传统方法依赖精确的环境建模，泛化性差。该工作将世界模型引入人形机器人视觉运动控制流程，通过前瞻预测足点可行性大幅提升复杂地形下的运动鲁棒性，为踏脚石、窄楼梯等场景的人形机器人运动控制提供了新的技术路径，应用价值突出。

---
*本日报由 [agents-radar](https://github.com/THTHDGCS/agents-radar) 自动生成。*