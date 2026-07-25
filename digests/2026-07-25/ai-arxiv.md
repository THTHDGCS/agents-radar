# ArXiv AI 研究日报 2026-07-25

> 数据来源: [ArXiv](https://arxiv.org/) (cs.RO, cs.AI, cs.LG, cs.CV) | 共 50 篇论文 | 生成时间: 2026-07-25 01:29 UTC

---

# ArXiv AI 研究日报（2026-07-25）
数据来源：ArXiv cs.AI、cs.CL、cs.LG 领域2026-07-25收录的50篇最新论文

---

## 今日速览
今日ArXiv AI领域研究核心聚焦跨模态空间感知突破、智能体架构与落地优化、生成式模型效率升级、大模型深层对齐四大方向。其中，视觉语言模型首次通过融合隐式与显式几何实现3D推理能力跃升，生产级智能体的上下文管理、训练范式等落地痛点得到系统性解决，扩散模型的推理时缩放、长序列视频生成等技术的落地性显著增强，同时大模型对齐从单维度反奉承转向结构化道德能力构建，多个子领域出现关键技术迭代。

---

## 重点论文
### 🧠 大语言模型（架构、训练、对齐、评估）
1. **[Beyond Sycophancy: Structured Resistance and Compliance in LLM Moral Reasoning](http://arxiv.org/abs/2607.21558v1)**
   作者：Baihui Wang et al.
   一句话说明：跳出单维度“反奉承”优化框架，提出LLM道德推理的结构化合规/抵抗能力评估体系，为构建社会校准的通用大模型提供新的对齐范式。
2. **[Windowed-MTP: Removing the Full-Context Draft-KV Tax at Million-Token Context](http://arxiv.org/abs/2607.21535v1)**
   作者：Alagappan Valliappan
   一句话说明：针对百万token长上下文场景下投机解码的KV缓存冗余问题，提出窗口化多token预测方案，大幅降低长文本生成的推理成本。
3. **[Error Certificates for KV-Cache Eviction via Randomized Design](http://arxiv.org/abs/2607.21475v1)**
   作者：Peng Xie
   一句话说明：证明确定性KV缓存驱逐方案无法感知删除内容带来的误差，提出基于随机设计的误差可证明KV驱逐机制，为长上下文推理的可靠性提供理论保障。
4. **[Artificial Epanorthosis: Why large language models overuse a classical rhetorical figure, and how to mitigate it](http://arxiv.org/abs/2607.21498v1)**
   作者：Federico Boggia
   一句话说明：首次系统发现LLM普遍过度使用“自我修正”古典修辞格的现象，揭示其训练数据偏差根源并提出缓解方案，为LLM生成风格校准提供新视角。

### 🤖 智能体与推理（规划、工具使用、多智能体、思维链）
1. **[AREX: Towards a Recursively Self-Improving Agent for Deep Research](http://arxiv.org/abs/2607.21461v1)**
   作者：Shuqi Lu et al.
   一句话说明：基于“发现成本高、验证成本低”的研究任务特性，提出可递归自改进的深度研究智能体框架，为科研辅助类智能体设计提供新范式。
2. **[OpenForgeRL: Train Harness-native Agents in Any Environment](http://arxiv.org/abs/2607.21557v1)**
   作者：Xiao Yu et al.
   一句话说明：突破现有智能体推理harness无法端到端训练的瓶颈，提出兼容任意环境的harness原生智能体训练框架，降低智能体规模化落地的技术门槛。
3. **[Agentic Context Management: Solving Agent Memory and Cost by Treating Them as Lifecycle and Architecture Problems](http://arxiv.org/abs/2607.21503v1)**
   作者：Gaurav Dadhich
   一句话说明：从生命周期和架构设计视角重构生产级智能体的上下文管理机制，系统性解决智能体历史上下文膨胀、推理成本过高的行业共性痛点。
4. **[AXIS: A Growable Community-Driven Data Engine for Scalable Robot Manipulation](http://arxiv.org/abs/2607.21588v1)**
   作者：Mengfei Zhao et al.
   一句话说明：提出首个可扩展的社区驱动机器人操纵数据引擎，摆脱传统数据管道对专用硬件、中心化运营的依赖，为通用机器人政策训练提供规模化数据支撑。

### 🔧 方法与框架（新技术、基准测试、效率优化）
1. **[3D-Aware VLMs with Implicit and Explicit Geometries](http://arxiv.org/abs/2607.21595v1)**
   作者：Wenhao Li et al.
   一句话说明：提出统一框架VLM-IE3D，同时融合隐式与显式几何信息增强VLM的3D空间感知能力，显著提升细粒度空间推理类3D任务的性能。
2. **[Inference-Time Scaling of Diffusion Models via Progressive Seed Pruning](http://arxiv.org/abs/2607.21591v1)**
   作者：Rogerio Guimaraes et al.
   一句话说明：填补扩散模型推理时缩放技术的空白，提出渐进式种子剪枝方案，在不损失生成质量的前提下大幅降低扩散模型的推理计算开销。
3. **[SANA-Video 2.0: Hybrid Linear Attention with Attention Residuals for Efficient Video Generation](http://arxiv.org/abs/2607.21553v1)**
   作者：Junsong Chen et al.
   一句话说明：提出混合线性注意力+注意力残差的视频扩散架构，实现单GPU生成720p高质量视频，性能比肩全注意力视频DiT的同时保留长序列效率优势。
4. **[Beyond Sufficiency: Time Series Explanation with Counterfactual Necessity](http://arxiv.org/abs/2607.21573v1)**
   作者：Hongnan Ma et al.
   一句话说明：突破现有时间序列解释方法仅关注特征充分性的局限，引入反事实必要性框架，有效识别伪相关特征，大幅提升时间序列分类器解释的可信度。

### 📊 应用（垂直领域、多模态、代码生成）
1. **[UnDA: Unpaired Domain Alignment for Cross-Modal Knowledge Transfer in Medical Imaging](http://arxiv.org/abs/2607.21546v1)**
   作者：Rafsan Jany et al.
   一句话说明：提出无配对域对齐框架，无需配对临床数据即可实现医疗影像跨模态知识迁移，大幅降低多模态医疗AI落地的数据门槛。
2. **[Detecting LLM-Generated Tokens in Human--LLM Coauthored Text](http://arxiv.org/abs/2607.21458v1)**
   作者：Yangjun Lu et al.
   一句话说明：提出token级的人机共写文本AI生成内容检测方法，突破现有方案仅支持文档级分类的局限，为AI时代的内容版权与治理提供细粒度技术支撑。
3. **[Synthetic data generation framework for quality control automation in gravure printing](http://arxiv.org/abs/2607.21577v1)**
   作者：Korota Arsène Coulibaly et al.
   一句话说明：针对凹版印刷质检数据稀缺、标注成本高的痛点，提出专用合成数据生成框架，为印刷行业的自动化质量检测提供可落地的AI方案。

---

## 研究趋势信号
今日投稿显现四大新兴研究方向：一是跨模态模型从2D语义理解向3D空间感知升级，融合几何先验成为VLM迭代的核心方向；二是智能体研究从算法能力验证转向生产级落地优化，上下文生命周期管理、推理harness原生训练成为行业共性需求；三是生成式模型效率优化从训练侧延伸至推理侧，扩散模型推理缩放、长序列可证明KV缓存技术受到关注；四是LLM对齐从单维度行为修正转向结构化能力构建，道德判断、生成风格校准等深层对齐问题成为研究热点。

---

## 值得精读
1. **[3D-Aware VLMs with Implicit and Explicit Geometries](http://arxiv.org/abs/2607.21595v1)**
   理由：这是VLM领域首次系统性融合隐式与显式几何信息解决3D任务短板的工作，打破了传统2D预训练VLM的空间感知瓶颈，为下一代多模态大模型的通用空间推理能力构建提供了核心技术路线，学术和产业价值极高。
2. **[AREX: Towards a Recursively Self-Improving Agent for Deep Research](http://arxiv.org/abs/2607.21461v1)**
   理由：该工作抓住了科研类任务“发现难、验证易”的核心不对称性，提出的递归自改进框架突破了现有智能体依赖外部反馈迭代的局限，为通用自改进智能体的设计提供了可落地的范式，是智能体领域的重要方向探索。
3. **[Beyond Sycophancy: Structured Resistance and Compliance in LLM Moral Reasoning](http://arxiv.org/abs/2607.21558v1)**
   理由：该工作跳出了主流对齐研究“反奉承=安全”的单维度认知，首次提出结构化的道德推理能力评估与对齐框架，为构建真正符合人类社会规范的通用大模型提供了全新的理论视角，对LLM对齐领域有重要的引领作用。

---
*本日报由 [agents-radar](https://github.com/THTHDGCS/agents-radar) 自动生成。*