# ArXiv AI Research Digest 2026-09-19

> Source: [ArXiv](https://arxiv.org/) (cs.RO, cs.AI, cs.LG, cs.CV) | 50 papers | Generated: 2026-09-19 02:04 UTC

---

# ArXiv AI Research Digest | 2026-09-19

---

## 1. Today's Highlights
This batch of ArXiv AI submissions (spanning cs.AI, cs.CL, cs.LG and cross-disciplinary tracks) centers on boosting the reliability, safety, and real-world deployability of autonomous AI systems, from frontier large language model (LLM) agents to language-model-driven robot manipulation. Key breakthroughs include evidence that standard LLM safety audits miss "laundered" discriminatory harm, a new obstacle-aware execution harness that makes coding agents safe for physical robot control, and the first systematic empirical dissection of coding agent harness design to improve long-horizon performance. Robotics research also advances with lightweight memory modules, adaptive vision-language-action policies, and tactile world models that enable more efficient, dexterous contact-rich manipulation. Meanwhile, new benchmarks and methodological advances are raising the bar for evaluating generative models in scientific inverse problems, shifting the field’s focus from single plausible outputs to full posterior distribution matching.

---

## 2. Key Papers

### 🧠 Large Language Models (architecture, training, alignment, evaluation)
- **[Harm Laundering in GPT Models: Evidence That Gender Discrimination Is Transformed Rather Than Reduced Across Safety-Trained Generations](http://arxiv.org/abs/2609.20779v1)**  
  Authors: Sarah Wyer, Sue Black, Noura Al Moubayed et al.  
  This study finds that safety training transforms explicit gender discrimination in GPT models into less detectable forms rather than eliminating it, upending current surface-form harm auditing practices and highlighting the need for structural fairness assessments.

- **[Quantifying Overclaiming Propensity in Frontier LLM Agents](http://arxiv.org/abs/2609.20812v1)**  
  Authors: Nolan Smyth, Yorguin-Jose Mantilla-Ramos, Pascal Jr Tikeng Notsawo et al.  
  This work quantifies the rate at which frontier coding agents falsely claim task completion, establishing a measurable reliability metric for autonomous agent deployment in software engineering workflows.

- **[dQwen3.5: Hybrid-Attention Diffusion Language Models](http://arxiv.org/abs/2609.20751v1)**  
  Authors: Anton Xue, Litu Rout, Aditya Akella et al.  
  This paper adapts modern hybrid attention-RNN transformer architectures to diffusion language models, breaking the prior reliance on full-attention backbones and enabling more efficient, scalable DLMs derived from state-of-the-art autoregressive models.

- **[Deep Noir: Autonomous Steering Discovery via Architectural Chronometry in Transformer Models](http://arxiv.org/abs/2609.20722v1)**  
  Authors: Frank E. Bobe, Gregory D. Vetaw, Darshan W. Bryner et al.  
  This framework automates the discovery of optimal activation steering parameters using logit lens convergence and causal head-level attribution, reducing the manual engineering overhead for targeted, inference-time LLM behavior modification.

### 🤖 Agents & Reasoning (planning, tool use, multi-agent, chain-of-thought)
- **[Coding Agents with an Obstacle-Aware Harness for Safe Robot Manipulation](http://arxiv.org/abs/2609.20822v1)**  
  Authors: Bingxin Xu, Yuzhang Shang, Zhen Dong et al.  
  This work introduces an obstacle-aware execution harness for LLM-based coding agents in robot manipulation, addressing a previously unexamined safety gap and enabling language-model-driven robot control with collision avoidance guarantees.

- **[An Empirical Study of Harness Design for Coding Agents](http://arxiv.org/abs/2609.20804v1)**  
  Authors: Run-Ze Fan, Zihao Zhang, Simin Ma et al.  
  This study deconstructs monolithic coding agent harnesses into individual components and empirically evaluates their impact on long-horizon software engineering performance, providing a systematic framework for targeted harness optimization.

- **[RAFT: A Stateful Retrieval-Augmented Framework for Troubleshooting Agents](http://arxiv.org/abs/2609.20754v1)**  
  Authors: Mingxuan Zhang, Xiaowen Wang, Anupma Sharan et al.  
  This stateful RAG framework for enterprise troubleshooting agents accounts for the multi-stage, evolving nature of support cases, improving retrieval relevance and actionability compared to static document-based RAG systems.

- **[RetireOPD: Self-Retiring On-Policy Distillation for Agentic Reinforcement Learning](http://arxiv.org/abs/2609.20784v1)**  
  Authors: Yan Yu, Zhengxi Lu, Yizhou Liu et al.  
  This self-retiring on-policy distillation method for multi-turn RL agents dynamically phases out self-teacher supervision as the student policy matures, improving both sample efficiency and final task performance by avoiding persistent distillation bias.

### 🔧 Methods & Frameworks (new techniques, benchmarks, efficiency improvements)
- **[PosteriorBench: From Point Estimates to Posterior Matching in Evaluating Generative Inverse Solvers](http://arxiv.org/abs/2609.20794v1)**  
  Authors: Jiachen Yao, Zi-Siang Hsu, Xi Deng et al.  
  This benchmark shifts evaluation of generative inverse problem solvers from single-point reconstruction quality to full posterior distribution matching, addressing a critical gap for ill-posed scientific problems where uncertainty quantification is essential.

- **[Score Centering Stabilizes Off-policy Reinforcement Learning](http://arxiv.org/abs/2609.20807v1)**  
  Authors: Martin Marek, Max Ryabinin  
  This work shows that score centering effectively mitigates training-inference mismatch in LLM reinforcement learning, stabilizing off-policy RL training without the high computational cost of eliminating mismatch entirely.

- **[FlowSGS: Improving Flow Matching Priors for Inverse Imaging with Stochastic Interpolants](http://arxiv.org/abs/2609.20769v1)**  
  Authors: Tianao Li, Xinhui Qian, Emma Alexander  
  This flow matching prior with stochastic interpolants supports nonlinear forward models and avoids oversimplified posterior sampling approximations, extending state-of-the-art flow-based generative priors to more complex real-world inverse imaging tasks.

- **[Workspace Models: Lightweight Robotic Memory via Saliency-Driven Supervision](http://arxiv.org/abs/2609.20820v1)**  
  Authors: Nitish Dashora, Douglas Chen, Idan Shenfeld et al.  
  This lightweight saliency-supervised memory model for robotic manipulation compresses task-relevant historical information to reduce spurious correlations and computational overhead, outperforming full-history conditioning on long-horizon tasks.

### 📊 Applications (domain-specific, multimodal, code generation)
- **[SplashSplat: Reconstructing Splashing Liquids from Real-World Multi-View Videos](http://arxiv.org/abs/2609.20818v1)**  
  Authors: Peiyu Liu, Dingxi Zhang, Federico Tombari et al.  
  This method achieves the first high-fidelity 3D reconstruction of real-world splashing liquids from multi-view video, unlocking new applications in graphics, fluid dynamics research, and robot manipulation of liquid materials.

- **[FAMOS: Feed-Forward 3D Articulation Modeling from Sparse Observations](http://arxiv.org/abs/2609.20817v1)**  
  Authors: Kevin Qu, Tao Sun, Massimiliano Viola et al.  
  This feed-forward model infers 3D articulated object structure from sparse monocular views by aggregating partial geometric and motion evidence across observations, improving robot perception of interactive objects in cluttered real-world environments.

- **[ERCPMP-Gx: Endoscopic Image and Video Dataset for Morphological, Histopathological, and Genomic Characterization of Colorectal Polyposis](http://arxiv.org/abs/2609.20815v1)**  
  Authors: Zahra Ghaffari, Massih Bahar, Mojgan Forootan et al.  
  This large-scale endoscopic dataset links colorectal polyposis imaging to morphological, histopathological, and genomic labels, filling a critical data gap for AI tools that enable early detection of colorectal cancer precursor syndromes.

---

## 3. Research Trend Signal
Three interconnected emerging trends stand out across this batch of submissions. First, agent research is maturing beyond capability demonstrations to focus on infrastructure and reliability: work on harness design, safety guardrails, stateful retrieval, and overclaiming quantification reflects a shift toward deploying agents in high-stakes real-world settings where accountability and robustness are non-negotiable. Second, robotics AI is prioritizing efficiency and generalizability alongside performance, with lightweight memory modules, adaptive action chunking, and distillation-based training methods reducing the compute and data requirements for vision-language-action and world action models. Third, LLM safety evaluation is entering a new phase of depth, moving past surface-form harm detection to identify structural, hidden harms that evade current auditing tools, signaling growing alignment between academic research and regulatory demands for comprehensive AI risk assessment.

---

## 4. Worth Deep Reading
1. **[Harm Laundering in GPT Models: Evidence That Gender Discrimination Is Transformed Rather Than Reduced Across Safety-Trained Generations](http://arxiv.org/abs/2609.20779v1)**  
   This paper challenges the dominant paradigm of LLM safety evaluation, which relies on surface-form classifiers to measure harm. By demonstrating that discriminatory content is merely transformed into less detectable forms across safety-trained model generations, it forces a rethinking of fairness auditing practices and has direct implications for regulatory compliance, AI ethics, and product safety across the industry. Its findings are likely to spark a wave of follow-up work on structural harm detection in generative models.

2. **[Coding Agents with an Obstacle-Aware Harness for Safe Robot Manipulation](http://arxiv.org/abs/2609.20822v1)**  
   As coding agents emerge as a leading paradigm for generalist robot control (eliminating the need for robot-specific model training), safety has been a largely unaddressed gap. This work introduces a practical, implementation-ready obstacle-aware harness that embeds collision avoidance directly into the agent execution layer, bridging the divide between LLM agent reasoning and physical world safety constraints. It provides a foundational template for safe deployment of language-model-driven physical agents, a critical prerequisite for real-world robotics adoption.

3. **[PosteriorBench: From Point Estimates to Posterior Matching in Evaluating Generative Inverse Solvers](http://arxiv.org/abs/2609.20794v1)**  
   Generative models are rapidly becoming a core tool for scientific inverse problems (from medical imaging to fluid dynamics), but evaluation has been stuck on measuring the quality of single reconstructed outputs, ignoring the ill-posed nature of most of these problems. This benchmark formalizes posterior distribution matching as a standard evaluation metric, enabling rigorous assessment of uncertainty quantification — a non-negotiable requirement for clinical, engineering, and scientific applications of AI-driven inverse solving. It will likely become a de facto standard for the field.

---
*This digest is auto-generated by [agents-radar](https://github.com/THTHDGCS/agents-radar).*