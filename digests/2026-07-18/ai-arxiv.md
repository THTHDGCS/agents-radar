# ArXiv AI 研究日报 2026-07-18

> 数据来源: [ArXiv](https://arxiv.org/) (cs.RO, cs.AI, cs.LG, cs.CV) | 共 50 篇论文 | 生成时间: 2026-07-18 01:20 UTC

---

# ArXiv AI 研究日报（2026-07-18）
---

## 今日速览
今日ArXiv AI领域投稿覆盖了从基础架构创新到产业落地安全的全链条研究：具身智能领域迎来突破性进展，RoboTTT将机器人策略的上下文长度提升三个数量级至8K步；大模型安全研究出现新的警示性成果，研究者首次揭示了利用计算宣传污染预训练语料的隐蔽投毒路径；多模态场景理解实现了视、音、语三类模态的语义与3D空间联合对齐；此外，医疗AI评估、科研智能体自动化、基础模型评估范式也均有重要突破。

---

## 重点论文
### 🧠 大语言模型（架构、训练、对齐、评估）
1. **[Pretraining Data Can Be Poisoned through Computational Propaganda](http://arxiv.org/abs/2607.15267v1)**
   作者：Graf 等
   一句话说明：首次揭示了利用大规模计算宣传内容污染预训练语料的新型投毒路径，攻击隐蔽性更强、影响范围更广，为大模型供应链安全研究提出了全新挑战。
2. **[In-Place Tokenizer Expansion for Pre-trained LLMs](http://arxiv.org/abs/2607.15232v1)**
   作者：Smith 等
   一句话说明：提出无需重新预训练的原地词表扩展方法，有效解决了部署阶段新增低资源语言时token拆分过细、延迟和算力成本上升的痛点。
3. **[Mask-Aware Policy Gradients for Diffusion Language Models](http://arxiv.org/abs/2607.15200v1)**
   作者：Raajesh 等
   一句话说明：提出掩码感知策略梯度方法，解决了掩码扩散语言模型（MDLM）RL对齐时对数似然难以计算的核心难题，为扩散大模型的性能对齐提供了可行路径。
4. **[Can We Trust Item Response Theory for AI Evaluation?](http://arxiv.org/abs/2607.15190v1)**
   作者：Jiang 等
   一句话说明：指出现有AI基准广泛使用的项目反应理论（IRT）不符合AI测试的数据特性，其评估结果存在系统性偏差，挑战了当前主流的大模型能力评估范式。

### 🤖 智能体与推理（规划、工具使用、多智能体、思维链）
1. **[RoboTTT: Context Scaling for Robot Policies](http://arxiv.org/abs/2607.15275v1)**
   作者：Jiang 等
   一句话说明：提出测试时训练的机器人策略架构，将视觉运动上下文长度扩展至8K步，较现有SOTA提升三个数量级，为长周期复杂机器人任务提供了核心支撑。
2. **[SearchOS-V1: Towards Robust Open-Domain Information-Seeking Agent Collaboration](http://arxiv.org/abs/2607.15257v1)**
   作者：Zhang 等
   一句话说明：提出面向开放域信息检索的多智能体协作框架，解决了长交互场景下智能体任务进度跟踪难、搜索失败后无法有效恢复的痛点。
3. **[AutoSynthesis: An agentic system for automated meta-analysis](http://arxiv.org/abs/2607.15247v1)**
   作者：Taherinezhad 等
   一句话说明：首个端到端的多智能体元分析系统，可自动完成文献检索、数据提取、效应量合并等全流程工作，大幅提升科研证据合成的效率。
4. **[Plover: Steering GUI Agents through Plan-Centric Interaction](http://arxiv.org/abs/2607.15193v1)**
   作者：Venkatesan 等
   一句话说明：提出以计划为中心的GUI智能体交互机制，解决了动态界面、意外弹窗场景下智能体容易偏离用户意图的问题，提升了GUI自动化的鲁棒性。
5. **[When Words Are Safe But Actions Kill: Probing Physical Danger Beyond Text Safety in Hidden-State Risk Space](http://arxiv.org/abs/2607.15218v1)**
   作者：Wang 等
   一句话说明：提出隐状态风险空间探测方法，发现LLM作为具身智能体规划器时，文本层面安全的指令可能在物理落地后产生危险，填补了具身智能安全评估的空白。

### 🔧 方法与框架（新技术、基准测试、效率优化）
1. **[SceneBind: Binding What and Where Across Vision, Audio and Language](http://arxiv.org/abs/2607.15265v1)**
   作者：Chen 等
   一句话说明：提出跨视、音、语的全模态场景表示框架，首次实现了语义信息与3D空间信息的联合对齐，解决了现有多模态编码器缺乏空间结构理解的痛点。
2. **[MeanFlowNFT: Bringing Forward-Process RL to Average-Velocity Generators](http://arxiv.org/abs/2607.15273v1)**
   作者：Huang 等
   一句话说明：首次将前向过程RL引入平均速度生成器（MeanFlow），在保留其少步快速采样优势的同时，实现了与人类偏好和任务目标的有效对齐。
3. **[Subjective Risk Decomposition: A New View for Uncertainty Quantification](http://arxiv.org/abs/2607.15196v1)**
   作者：Alamri 等
   一句话说明：提出主观风险分解的不确定性量化新范式，从高层建模决策出发推导认知与随机不确定性，重构了UQ领域的基础逻辑。

### 📊 应用（垂直领域、多模态、科研自动化）
1. **[SciDiagramEdit: Learning to Edit Scientific Diagrams from Paper Revisions](http://arxiv.org/abs/2607.15272v1)**
   作者：Sun 等
   一句话说明：利用科研论文的修订历史训练图表编辑模型，可根据自然语言指令完成组件重标记、面板重排、样式调整等操作，大幅降低科研作图的重复性劳动。
2. **[MedFailBench: A Clinician-Built Open-Source Benchmark for Medical AI Safety Boundary Inspection](http://arxiv.org/abs/2607.15166v1)**
   作者：Ozkan 等
   一句话说明：首个由临床专家构建的医疗AI安全边界基准，按严重程度和错误类型对模型故障分级标注，改变了传统医疗AI只测准确率的评估范式。
3. **[Benchmarking Multimodal Large Language Models for Scientific Visualization Literacy](http://arxiv.org/abs/2607.15176v1)**
   作者：Do 等
   一句话说明：首次系统评估MLLM的科学可视化理解能力，覆盖多领域专业科研图表的解读任务，填补了多模态模型专业能力评估的空白。

---

## 研究趋势信号
今日投稿显现三大新兴研究趋势：一是机器人基础模型的上下文缩放成为核心热点，从短视程任务向长周期全任务记忆扩展，测试时训练架构成为重要技术路径；二是大模型安全边界持续外扩，从传统文本内容安全延伸至预训练供应链安全、具身落地的物理安全等新场景；三是科研场景AI工具从单点辅助向全流程智能体演进，自动元分析、科研图表编辑等应用大幅降低科研重复性劳动成本。

---

## 值得精读
1. **[RoboTTT: Context Scaling for Robot Policies](http://arxiv.org/abs/2607.15275v1)**
   理由：具身智能领域的里程碑式工作，通过测试时训练的创新架构将机器人视觉运动策略的上下文长度提升三个数量级，同时保持推理效率，为长周期复杂机器人任务提供了核心支撑，其设计思路对通用具身基础模型的发展有重要指导意义。
2. **[Pretraining Data Can Be Poisoned through Computational Propaganda](http://arxiv.org/abs/2607.15267v1)**
   理由：大模型安全领域的重要警示性研究，首次提出利用计算宣传生成的大规模异构内容污染预训练语料的新型投毒方式，攻击隐蔽性更强、成本更低、影响范围更广，对大模型训练的数据源治理和供应链安全建设有重大实践价值。
3. **[MedFailBench: A Clinician-Built Open-Source Benchmark for Medical AI Safety Boundary Inspection](http://arxiv.org/abs/2607.15166v1)**
   理由：医疗AI落地的核心支撑性基准，打破了传统医疗AI仅评估准确率的范式，从临床安全角度对模型错误分级标注，由临床专家构建的数据集更贴近真实诊疗场景，对推动医疗AI的合规落地、降低临床应用风险有重要实用价值。

---
*本日报由 [agents-radar](https://github.com/THTHDGCS/agents-radar) 自动生成。*