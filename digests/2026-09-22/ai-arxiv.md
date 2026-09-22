# ArXiv AI 研究日报 2026-09-22

> 数据来源: [ArXiv](https://arxiv.org/) (cs.RO, cs.AI, cs.LG, cs.CV) | 共 50 篇论文 | 生成时间: 2026-09-22 02:14 UTC

---

# ArXiv AI 研究日报（2026-09-22）

---

## 今日速览
今日ArXiv cs.AI、cs.CL、cs.LG领域共更新50篇AI相关论文，核心聚焦**模型合并的基础理论与效率优化**、**具身多模态与智能体落地**两大主线。大模型方向涌现出合并对涌现能力的影响、KV缓存架构创新、小样本蒸馏效率提升等多项进展。应用侧覆盖医疗影像、能源预测、隐私保护、粮食安全等垂直场景，AI安全与可靠性研究持续深化。机制解释性领域则针对状态空间模型、视觉Transformer的概念形成规律提出了新的实证结论。

---

## 重点论文
### 🧠 大语言模型（架构、训练、对齐、评估）
1. **[On Emergent Capabilities and Model Merging](http://arxiv.org/abs/2609.24504v1)**
   作者：Luca Zhou 等
   一句话说明：首次系统研究模型合并操作对大模型涌现能力的作用规律，揭示了权重算术组装多能力模型时的能力增益与损耗机制，填补了该领域的理论空白。

2. **[ARM: Attention with Routed-Memory for Learnable Sparse Control](http://arxiv.org/abs/2609.24417v1)**
   作者：Qiuhao Zeng 等
   一句话说明：提出带可学习路由内存的稀疏注意力架构ARM，替代传统KV缓存机制，在长上下文推理中兼顾信息完整性与计算效率，为LLM长序列优化提供了新方案。

3. **[1% of Tokens Can Be Enough: On Gradient Estimation in On-Policy Distillation](http://arxiv.org/abs/2609.24432v1)**
   作者：Huanxin Sheng 等
   一句话说明：实证发现仅需1%的token即可完成on-policy蒸馏的有效梯度估计，大幅降低大模型蒸馏的计算成本，为小样本高效蒸馏提供了理论支撑。

---

### 🤖 智能体与推理（规划、工具使用、多智能体、思维链）
1. **[ME-VLM:A Unified VLM for Embodied Cognition and Agent Coordination](http://arxiv.org/abs/2609.24526v1)**
   作者：Li Auto Inc 等
   一句话说明：推出面向具身认知与多智能体协同的统一视觉语言模型ME-VLM（4B/35B两个版本），打通了视觉语言理解与真实世界环境交互的能力边界，是物理AI的重要基座模型进展。

2. **[AgentSTAR: Agentic Shape Tracking and Reconstruction from Monocular Videos](http://arxiv.org/abs/2609.24487v1)**
   作者：Kirill Mazur 等
   一句话说明：提出基于智能体分析-合成范式的单目视频3D形状追踪重建方法AgentSTAR，替代传统先做像素对应再恢复运动的流程，实现更鲁棒的结构化3D物体建模。

3. **[Dissecting Agentic Forensics: The Role of Triage, Prompting, and Evidence Arbitration in Open-World Fake Image Detection](http://arxiv.org/abs/2609.24359v1)**
   作者：Xianlong Li 等
   一句话说明：拆解了智能体图像取证系统的核心组件（分诊、提示、证据仲裁）的作用，为开放世界下多类型伪造图像的检测提供了可落地的智能体框架。

---

### 🔧 方法与框架（新技术、基准测试、效率优化）
1. **[Not All Task Vectors Need Equal Rank: Energy-Proportional Allocation for Model Merging](http://arxiv.org/abs/2609.24517v1)**
   作者：Hyunjoong Cho 等
   一句话说明：提出能量比例的任务向量秩分配方法，打破了现有谱合并方法对所有任务分配相等秩的限制，在更低计算成本下实现了更优的多任务模型合并效果。

2. **[Identifying Representational Biases in Datasets Using PCA: A Max-Disparity Partition Framework](http://arxiv.org/abs/2609.24556v1)**
   作者：Arjun KM 等
   一句话说明：提出基于PCA的最大差异划分框架，无需群体标签即可识别数据集中的表征偏差，解决了传统公平PCA需要标注的痛点，为数据集偏见检测提供了无监督新工具。

3. **[Comparing Latent Concept Formation in State Space Models and Transformers via Sparse Autoencoders](http://arxiv.org/abs/2609.24440v1)**
   作者：Rithin Nagaraj 等
   一句话说明：利用稀疏自编码器对比了状态空间模型（SSM）与Transformer的潜在概念形成机制，首次实证揭示了SSM信息瓶颈对概念表征的影响规律，为机制解释性研究提供了新发现。

4. **[WPBench: A Comprehensive Benchmark for Wind Power Forecasting](http://arxiv.org/abs/2609.24444v1)**
   作者：Yuhan Zhu 等
   一句话说明：推出风电预测领域的全面基准WPBench，覆盖多场景、多评估维度，解决了现有基准场景单一的问题，为风电预测AI模型的落地验证提供了统一标尺。

5. **[LIBERO-VPro: Benchmarking Closed-Loop Visual Robustness of Robotic Foundation Models](http://arxiv.org/abs/2609.24350v1)**
   作者：Huiqiong Li 等
   一句话说明：提出机器人基础模型的闭环视觉鲁棒性基准LIBERO-VPro，填补了现有评估忽略观测噪声、延迟等真实场景干扰的空白，更贴近实际部署需求。

---

### 📊 应用（垂直领域、多模态、代码生成）
1. **[Preoperative Prediction of Microvascular Invasion in Hepatocellular Carcinoma by Integrating Multimodal Ultrasound and Clinical Data: A Multicenter Study](http://arxiv.org/abs/2609.24524v1)**
   作者：Jun Cheng 等
   一句话说明：开发了整合多模态超声与临床数据的肝细胞癌微血管侵犯术前预测模型，多中心验证显示出优异的诊断性能，为肝癌术前风险评估提供了无创新工具。

2. **[MIRAGE: Full-Body Bystander Privacy for Smart Glasses with Consent-Based Restoration](http://arxiv.org/abs/2609.24537v1)**
   作者：Muhammad Umair 等
   一句话说明：提出智能眼镜场景下的全身旁观者隐私保护框架MIRAGE，三层架构可实现步态、体型等全身生物特征的脱敏，并支持基于同意的恢复，解决了传统人脸脱敏无法防护全身ReID的问题。

3. **[Fathom-Vaidya: Advancing Medical Reasoning with Rubric-Based Rewards](http://arxiv.org/abs/2609.24480v1)**
   作者：Kalash Shah 等
   一句话说明：提出基于评分规则奖励的医疗推理大模型Fathom-Vaidya，在诊断推理与临床决策两类任务上均取得显著提升，为医疗LLM的对齐提供了新的奖励设计思路。

4. **[Climate Variability Modulates the Impact of Price Spikes on Food Insecurity](http://arxiv.org/abs/2609.24394v1)**
   作者：Jordi Cerdà-Bautista 等
   一句话说明：通过机器学习框架揭示了气候变率对粮食价格冲击引发粮食不安全的调节作用，为粮食安全早期预警系统纳入气候信号提供了科学依据。

---

## 研究趋势信号
今日投稿显现三大明确趋势：一是**模型合并研究从工程技巧向基础理论深化**，既涌现出合并对涌现能力影响的系统性探究，也诞生了能量比例秩分配等效率优化方案；二是**智能体范式向垂直技术场景渗透**，3D重建、开放世界图像取证等领域开始采用agent化的分析-合成或多组件协同架构；三是**基础模型的落地导向评估兴起**，机器人、风电预测等场景均推出贴近真实部署的鲁棒性基准，AI可靠性研究持续走热。（全文约180字）

---

## 值得精读
1. **[《On Emergent Capabilities and Model Merging》](http://arxiv.org/abs/2609.24504v1)**
   理由：模型合并是当前大模型低成本组装多能力的核心技术，但学界此前对其如何影响涌现能力缺乏系统性认知。该研究首次系统探究了权重算术操作对大模型隐式涌现能力的作用规律，对指导模型合并的实际应用、避免能力隐式损耗有重要理论价值。

2. **[《ME-VLM:A Unified VLM for Embodied Cognition and Agent Coordination》](http://arxiv.org/abs/2609.24526v1)**
   理由：具身智能是当前AI产业与研究的核心方向，而统一的多模态基座是具身智能落地的关键支撑。该模型同时支持具身认知与多智能体协同，提供4B/35B两个参数版本，对物理AI的技术研发与落地应用有很强的参考意义。

3. **[《Comparing Latent Concept Formation in State Space Models and Transformers via Sparse Autoencoders》](http://arxiv.org/abs/2609.24440v1)**
   理由：状态空间模型（SSM）作为Transformer的有力替代架构，其内部表征与概念形成机制一直缺乏深入的机制解释。该研究首次用稀疏自编码器对比了两类架构的潜在概念形成规律，为理解SSM的信息瓶颈效应、优化下一代模型架构提供了关键实证依据。

---
*本日报由 [agents-radar](https://github.com/THTHDGCS/agents-radar) 自动生成。*