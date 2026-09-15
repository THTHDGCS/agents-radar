# ArXiv AI 研究日报 2026-09-15

> 数据来源: [ArXiv](https://arxiv.org/) (cs.RO, cs.AI, cs.LG, cs.CV) | 共 16 篇论文 | 生成时间: 2026-09-15 02:16 UTC

---

# ArXiv AI 研究日报
2026年9月15日

---

## 📌 今日速览
今日ArXiv更新的AI研究集中在多模态大模型垂直适配、可信AI体系构建、边缘AI效率优化三大核心方向。多模态大模型领域，医疗、教育、创意等场景的定制化方法持续涌现，两阶段MoLoRA框架有效破解了医疗VLM多任务联合训练的梯度冲突痛点。可信AI方向成果密集，覆盖多模态越狱防御、科学文本引文归因、AIGC图像跨生成器检测等子领域，为AI系统可靠性落地提供了技术支撑。此外，边缘端模型精度-延迟权衡、低秩张量补全等底层方法研究也有新进展，为资源受限场景的AI部署提供了新思路。

---

## 🔍 重点论文

### 🧠 大语言模型（架构、训练、对齐、评估）
1. **[SPARK: Representation-Level KV Memory Alignment for Safer Vision-Language Models](http://arxiv.org/abs/2609.14258v1)**
   作者：Mohd Azfar et al.
   一句话说明：提出在多模态KV内存层面进行表征对齐的SPARK框架，可缓解VLM的多模态越狱问题，为多模态大模型安全对齐提供了底层新范式。

2. **[ATTRICITE: Training an Open 4B Model for Citation Recovery toward Faithful Attribution](http://arxiv.org/abs/2609.14248v1)**
   作者：Yee Man Choi et al.
   一句话说明：训练了开源4B参数的引文恢复模型ATTRICITE，针对科学论断的源文献识别任务，为大模型忠实归因能力构建提供了基础模型与评估基准。

3. **[The Attribution-Compression Frontier in Retrieval-Augmented Generation](http://arxiv.org/abs/2609.14245v1)**
   作者：Deepanshu Mody
   一句话说明：系统评估了RAG系统中不同上下文压缩方法对引文归因质量的影响，首次刻画了归因效果与压缩率的权衡边界，为RAG系统可信优化提供了量化依据。

---

### 🤖 智能体与推理（规划、工具使用、多智能体、思维链）
1. **[Biquaternionic Space with Complex-valued Attention for Temporal Knowledge Graph Completion](http://arxiv.org/abs/2609.14279v1)**
   作者：Rushan Geng et al.
   一句话说明：提出基于双四元数空间与复值注意力的时序知识图谱补全方法，可更好建模动态实体与多样关系模式，显著提升了时序知识推理的准确性。

---

### 🔧 方法与框架（新技术、基准测试、效率优化）
1. **[Learning Continuous Source Responses For Generalizable AI-Generated Image Detection](http://arxiv.org/abs/2609.14316v1)**
   作者：Manni Cui et al.
   一句话说明：提出学习连续源响应的AIGC图像检测框架，突破了现有检测器跨生成器泛化性差的瓶颈，对未知生成模型的合成图像检测能力显著提升。

2. **[Sparsity-Adaptive Sharpness-Aware Minimization](http://arxiv.org/abs/2609.14274v1)**
   作者：Shiryu Ueno et al.
   一句话说明：提出稀疏自适应的锐度感知优化方法，解决了高稀疏度剪枝模型鲁棒性下降的问题，同时兼顾了模型的紧凑性与抗干扰能力。

3. **[Robust low-rank tensor completion via factorized weighted tensor schatten-p norm minimization](http://arxiv.org/abs/2609.14307v1)**
   作者：Binghao Wang et al.
   一句话说明：提出基于分解加权张量Schatten-p范数最小化的鲁棒低秩张量补全方法，缓解了传统谱正则化对主导低秩分量的过度衰减问题，提升了多维数据补全效果。

---

### 📊 应用（垂直领域、多模态、代码生成）
1. **[Two-Stage Mixture-of-LoRA for Multi-Task Medical Vision-Language Learning](http://arxiv.org/abs/2609.14350v1)**
   作者：Zhanghao Chen et al.
   一句话说明：提出两阶段Mixture-of-LoRA框架，解决了医疗多任务VLM联合训练中异构输出、梯度冲突、数据不平衡的痛点，为医疗视觉语言模型的多任务适配提供了新路径。

2. **[S3-Tracker: Self-Supervised Surgical Tissue Tracking With Contrastive Random Walks](http://arxiv.org/abs/2609.14313v1)**
   作者：Jiaming Zhang et al.
   一句话说明：提出基于对比随机游走的自监督手术组织跟踪方法S3-Tracker，无需大规模标注数据即可实现内镜视频鲁棒点跟踪，为计算机辅助手术与机器人手术提供了关键感知技术。

3. **[DTI-Guided Volumetric Spherical Harmonics Regression for Single-to-Multi-Shell dMRI Synthesis](http://arxiv.org/abs/2609.14312v1)**
   作者：Binghua Li et al.
   一句话说明：提出DTI引导的体球面谐波回归方法，实现单壳扩散MRI到多壳的高精度合成，大幅缩短多壳dMRI采集时间，为临床大规模队列研究与急症场景应用提供了可能。

4. **[SpermYOLO: A Coordinated YOLO-Based Detector for Accurate and Efficient Sperm and Impurity Detection in Microscopic Images](http://arxiv.org/abs/2609.14278v1)**
   作者：Shengqi Chen et al.
   一句话说明：提出基于YOLOv11改进的协同检测框架SpermYOLO，解决了显微图像中精子密集、杂质相似导致的检测不准问题，为计算机辅助精液分析提供了高效准确的工具。

5. **[Mobile CT Services for Rural, Regional, and Remote Areas: Current Practice and Future Integration with Telehealth and Regulatory-Authorised AI](http://arxiv.org/abs/2609.14347v1)**
   作者：Zhicheng Lu et al.
   一句话说明：综述了农村及偏远地区移动CT服务的现状，探讨了其与远程医疗、监管获批AI技术的整合路径，为资源受限场景的影像诊疗落地提供了实践参考。

6. **[Vision-Language Models for Criterion-Level Grading of Handwritten Examinations in Outcome-Based Education](http://arxiv.org/abs/2609.14284v1)**
   作者：Md Khalid Syfullah et al.
   一句话说明：从准确性、人类一致性等五个维度系统评估了VLM在成果导向教育下的手写考试标准分级任务表现，验证了VLM替代人工评分的潜力，为教育评估自动化提供了依据。

7. **[AURA: Unified Multimodal Framework for Conversational Music Editing](http://arxiv.org/abs/2609.14344v1)**
   作者：Quoc-Huy Trinh et al.
   一句话说明：提出统一多模态对话式音乐编辑框架AURA，支持用户通过多轮交互渐进式优化音轨，突破了传统指令式音乐编辑器单轮独立处理的局限。

8. **[What Input Resolution Is Required for Bird Species Identification, and What Is Its Latency Cost on an Edge Device? A Study of 14 Input Resolutions and Six Architectures with On-Device Measurements](http://arxiv.org/abs/2609.14247v1)**
   作者：Takeshi Nishikawa
   一句话说明：系统性研究了14种输入分辨率与6种架构在边缘设备上的鸟类识别精度与延迟权衡，为风电场鸟击防控场景的边缘AI模型选型提供了量化参考。

---

## 📈 研究趋势信号
今日投稿呈现三大明确趋势：一是多模态大模型安全对齐开始向中间层渗透，SPARK框架从KV内存层面防御多模态越狱，突破了传统输入/输出端对齐的局限。二是可信AI的评价核心从答案质量向归因质量延伸，RAG归因-压缩边界、引文恢复模型的密集出现，标志着忠实性成为大模型落地的核心指标。三是垂直领域AI正从单任务模型向统一多任务架构演进，医疗、教育等场景的VLM适配研究增多，且更关注资源受限场景的落地性。

---

## ⭐ 值得精读
1. **[SPARK: Representation-Level KV Memory Alignment for Safer Vision-Language Models](http://arxiv.org/abs/2609.14258v1)**
   理由：该工作首次将多模态大模型的安全对齐从输入/输出层下沉到中间KV内存层面，提出的表征级对齐思路突破了传统防御方法的局限，对多模态大模型安全研究具有很强的启发性，代表了VLM安全的新方向。

2. **[The Attribution-Compression Frontier in Retrieval-Augmented Generation](http://arxiv.org/abs/2609.14245v1)**
   理由：RAG是当前大模型落地的核心技术，但现有研究多关注答案质量，忽略了压缩对归因可靠性的影响。该工作首次系统刻画了归因效果与压缩率的权衡边界，对实际RAG系统的可信优化具有直接的指导意义。

3. **[Two-Stage Mixture-of-LoRA for Multi-Task Medical Vision-Language Learning](http://arxiv.org/abs/2609.14350v1)**
   理由：医疗VLM是垂直AI领域的热点方向，但多任务联合训练的梯度冲突、异构输出等痛点一直未得到很好解决。该工作提出的两阶段MoLoRA框架兼具效率与效果，对医疗多模态模型的落地应用有重要的参考价值。

---
*本日报由 [agents-radar](https://github.com/THTHDGCS/agents-radar) 自动生成。*