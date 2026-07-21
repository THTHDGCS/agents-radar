# ArXiv AI 研究日报 2026-07-21

> 数据来源: [ArXiv](https://arxiv.org/) (cs.RO, cs.AI, cs.LG, cs.CV) | 共 22 篇论文 | 生成时间: 2026-07-21 01:26 UTC

---

# ArXiv AI 研究日报（2026年7月21日）

---

## 今日速览
2026年7月21日ArXiv更新的AI相关研究以计算机视觉交叉技术为核心，覆盖基础模型落地、多模态理解、生成式工业设计、AI安全四大核心方向。基础模型轻量化取得关键进展，单目深度估计等复杂视觉任务首次实现大模型能力向边缘端tiny模型的无损迁移。多类垂直场景基准数据集与评测体系得到补全，覆盖GUI状态转换理解、对抗攻击评测、小语种多模态内容检测等此前的空白领域。生成式AI的应用边界进一步拓展，首次实现中文矢量字体、参数化CAD B-Rep模型的端到端直接生成。

---

## 重点论文
### 🧠 大语言模型（架构、训练、对齐、评估）
1. **[VecFontLLM: Anchor-Guided Direct Synthesis of Chinese Vector Fonts](http://arxiv.org/abs/2607.17251v1)**
   作者: Hao Yuan et al.
   一句话说明: 提出锚点引导的矢量字体生成大模型，首次解决中文矢量字形复杂组件结构、锚点布局、贝塞尔曲线细节的端到端直接合成难题，填补了中文字体矢量生成的技术空白。
2. **[STBridge: Shared-Target Alignment for Bridging Understanding and Generation in UMMs](http://arxiv.org/abs/2607.17140v1)**
   作者: Ye Wang et al.
   一句话说明: 针对统一多模态模型“理解描述正确但生成内容不一致”的语义偏移问题，提出共享目标对齐框架STBridge，有效提升多模态大模型理解与生成任务的语义一致性。
3. **[Searching for Task-Specific Vision Paths: Evolutionary Block Pruning Across Vision-Language Models](http://arxiv.org/abs/2607.17052v1)**
   作者: Tarun Tomar et al.
   一句话说明: 提出视觉语言模型的任务特定路径进化剪枝方法，无需微调即可根据查询类型（OCR、计数、空间推理等）跳过冗余视觉计算块，在精度损失可忽略的前提下大幅降低推理成本。

### 🤖 智能体与推理（规划、工具使用、多智能体、思维链）
1. **[EvoGUI: An Evolution-Aware Benchmark for GUI State-Transition Understanding](http://arxiv.org/abs/2607.17050v1)**
   作者: Yaohan Yang et al.
   一句话说明: 提出首个专门评测GUI智能体状态转换推理能力的基准EvoGUI，将GUI轨迹拆解为三类视觉问答任务，实现对智能体核心推理能力的解耦评估，避免端到端指标的混淆问题。
2. **[DROID-ANCHOR: Odometry-Anchored Recurrent Metric Depth Estimation](http://arxiv.org/abs/2607.17058v1)**
   作者: Yuxuan Chen et al.
   一句话说明: 提出里程计锚定的循环度量深度估计框架DROID-ANCHOR，解决了传统单目SLAM系统的尺度模糊与长期漂移问题，为自主移动机器人提供高精度、鲁棒的环境感知能力。
3. **[PACE: Polar Axis-Conditioned Estimation for PairUAV Relative Localization](http://arxiv.org/abs/2607.17268v1)**
   作者: Ze Rong et al.
   一句话说明: 提出极轴条件估计方法PACE，解决了无人机对相对定位中航向与距离共享上下文但优化状态冲突的问题，大幅提升PairUAV系统的导航精度与鲁棒性。

### 🔧 方法与框架（新技术、基准测试、效率优化）
1. **[DepthART: Scaling Foundation Monocular Depth to Tiny Models](http://arxiv.org/abs/2607.17099v1)**
   作者: Feng Xue et al.
   一句话说明: 提出深度适配蒸馏框架DepthART，首次将单目深度估计基础模型的跨场景泛化能力与度量精度无损迁移到参数量仅数百万的tiny模型，为边缘端视觉应用提供了低成本方案。
2. **[ALLUDE: A Unified Evaluation System for Configurable Attacks in Differentiable Environments](http://arxiv.org/abs/2607.17077v1)**
   作者: Mansi Phute et al.
   一句话说明: 提出可配置对抗攻击统一评测系统ALLUDE，基于可微渲染实现端到端的攻击性能评估，解决了现有视觉模型对抗性评测场景受限、指标片面的问题。
3. **[BanClickThumb: A Multimodal Dataset and Transformer Fusion Benchmarks for Clickbait Detection in Bengali YouTube Videos](http://arxiv.org/abs/2607.17182v1)**
   作者: Md. Ariful Islam et al.
   一句话说明: 发布首个孟加拉语YouTube视频多模态标题党检测数据集BanClickThumb，并提供Transformer融合基准，填补了小语种多模态垃圾内容检测的数据集空白。
4. **[Denoising Models Develop Human-Like Perceptual Illusion Representations Across Architectures](http://arxiv.org/abs/2607.17138v1)**
   作者: Gautam Ranka et al.
   一句话说明: 首次在内部表征层面证实去噪模型跨架构都具备类人的视错觉感知能力，为探索深度神经网络的类人认知机制提供了新的核心证据。
5. **[The generator is the tracker: Multi-object tracking by painting persistent identity colours](http://arxiv.org/abs/2607.17120v1)**
   作者: Haiyu Yang et al.
   一句话说明: 提出“生成器即跟踪器”的多目标跟踪新范式，通过微调22B文生视频模型为每个目标生成持久的身份颜色，无需外部状态缓存即可实现长时稳定跟踪。

### 📊 应用（垂直领域、多模态、代码生成）
1. **[Induce to Empower: Improving Lightweight Baselines via Foundation Model Induction for Generalized Polyp Segmentation](http://arxiv.org/abs/2607.17208v1)**
   作者: Shivanshu Agnihotri et al.
   一句话说明: 提出基础模型诱导的轻量化息肉分割框架，解决了现有医学影像分割模型泛化性差、大模型难以落地临床的问题，在跨数据集测试中取得SOTA精度。
2. **[Autoregressive B-Rep Shape Generation with Parametric Surfaces](http://arxiv.org/abs/2607.17093v1)**
   作者: Dafei Qin et al.
   一句话说明: 提出基于参数曲面的自回归B-Rep形状生成方法，实现工业CAD模型原生边界表示的端到端生成，无需后续格式转换即可直接用于制造设计流程。
3. **[HarmoHOI: Harmonizing Appearance and 3D Motion for Multi-view Hand-Object Interaction Synthesis](http://arxiv.org/abs/2607.17097v1)**
   作者: Lingwei Dang et al.
   一句话说明: 提出多视角手物交互合成框架HarmoHOI，通过对齐外观与3D运动特征解决了视角不一致、遮挡导致的生成失真问题，可直接用于动画制作与具身AI仿真。
4. **[High-Capacity Robust Watermarking Technology for High-Resolution Images](http://arxiv.org/abs/2607.17056v1)**
   作者: Shaowu Wu et al.
   一句话说明: 提出面向高分辨率图像的大容量鲁棒水印技术，支持可变长度水印嵌入，抗压缩、裁剪攻击能力显著优于现有方案，适配AIGC时代的内容版权保护需求。

---

## 研究趋势信号
今日投稿呈现三大明确研究趋势：一是基础模型轻量化落地进入深水区，核心视觉任务已实现大模型能力向百万级参数量tiny模型的无损迁移，边缘端AI性能将迎来大幅提升；二是生成式AI加速向工业场景渗透，突破了矢量字体、参数化CAD等原生工业格式的端到端生成瓶颈，有望直接重构设计生产链路；三是智能体能力的解耦评测成为新热点，针对GUI推理、状态转换等核心能力的专项基准不断补全，推动智能体从“可用”向“可靠”演进。

---

## 值得精读
1. **[DepthART: Scaling Foundation Monocular Depth to Tiny Models](http://arxiv.org/abs/2607.17099v1)**
   理由：首次实现单目深度估计基础模型的能力向边缘端tiny模型的无损迁移，打破了“高精度=大参数量”的固有认知，其适配蒸馏框架可推广到各类视觉基础模型的轻量化，对边缘AI落地有极强的工程指导价值。
2. **[EvoGUI: An Evolution-Aware Benchmark for GUI State-Transition Understanding](http://arxiv.org/abs/2607.17050v1)**
   理由：针对当前GUI智能体评测“重结果、轻能力”的痛点，提出解耦式评测框架，将状态转换推理能力从端到端任务中剥离，为智能体的定向优化提供了可量化的评测标尺，是交互智能体领域的重要基础工作。
3. **[The generator is the tracker: Multi-object tracking by painting persistent identity colours](http://arxiv.org/abs/2607.17120v1)**
   理由：颠覆了多目标跟踪“检测+关联+外部状态缓存”的传统范式，证明生成模型的内部隐状态即可稳定存储目标身份信息，为感知任务的统一建模提供了全新的思路，具备极强的范式创新价值。

---
*本日报由 [agents-radar](https://github.com/THTHDGCS/agents-radar) 自动生成。*