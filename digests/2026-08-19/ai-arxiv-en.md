# ArXiv AI Research Digest 2026-08-19

> Source: [ArXiv](https://arxiv.org/) (cs.RO, cs.AI, cs.LG, cs.CV) | 50 papers | Generated: 2026-08-19 00:34 UTC

---

# ArXiv AI Research Digest | 2026-08-19
---
## 1. Today's Highlights
Today’s arXiv submissions mark notable advances across embodied AI, large language model (LLM) security, and foundational AI optimization. Long-horizon robot manipulation sees two parallel breakthroughs: a transition-aware memory framework for agentic subtask chaining and a hierarchical vision-language-action (VLA) model with world-model-guided test-time computation, both addressing the critical problem of error compounding in multi-stage contact-rich tasks. On the LLM security front, researchers identify a widespread “model hypnosis” vulnerability where individually weak, seemingly irrelevant prompt cues combine to exert strong systematic control over model behavior, alongside rigorous audits of compliance detector reliability and state-level attack surfaces for embodied agents. Foundational AI also advances, with AlphaEvolve-powered optimization tightening the matrix multiplication exponent bound and a fully automated symbolic regression system that searches persistent research states rather than isolated equations to produce more generalizable scientific insights.
---
## 2. Key Papers
### 🧠 Large Language Models (architecture, training, alignment, evaluation)
- **[Model Hypnosis: Strong control of AI via additive subliminal effects](http://arxiv.org/abs/2608.16834v1)**  
  Authors: Enric Boix-Adsera, Benedict Tessler  
  Demonstrates a cross-model "model hypnosis" vulnerability where individually weak, irrelevant prompt cues combine to exert strong, systematic control over LLM behavior, revealing a critical unaddressed risk for deployed AI alignment and security.
- **[What Do Compliance Detectors Read? An Audit of Activation Probes and Guard Models](http://arxiv.org/abs/2608.16852v1)**  
  Authors: Saisab Sadhu et al.  
  Audits state-of-the-art LLM compliance detectors (activation probes and guard models) to reveal inconsistent rule violation detection across regulatory domains, providing actionable insights for strengthening deployed AI governance controls.
- **[Proteus: Incremental Memory Activation for Long-Context Sequence Modeling](http://arxiv.org/abs/2608.16844v1)**  
  Authors: Reza Bayat et al.  
  Introduces a dynamic memory activation framework for long-context sequence models that incrementally activates memory tokens based on context relevance, reducing computational cost while outperforming static memory approaches on long-document and reasoning tasks.
### 🤖 Agents & Reasoning (planning, tool use, multi-agent, chain-of-thought)
- **[Don't Drop the BATON: Long-Horizon Robot Manipulation via Agentic Subtask Exploration and Transition-aware Memory](http://arxiv.org/abs/2608.16889v1)**  
  Authors: Bingxin Xu et al.  
  Proposes an agentic subtask exploration and transition-aware memory framework for long-horizon robot manipulation that mitigates error compounding and cross-subtask constraint propagation, significantly improving success rates on multi-stage contact-rich tasks.
- **[$\tau_0$-VLA: a Hierarchical Robot Foundation Model with World-Model-Guided Test-Time Computation](http://arxiv.org/abs/2608.16885v1)**  
  Authors: Xiaowei Cai et al.  
  Introduces a hierarchical VLA foundation model that allocates variable test-time compute guided by an internal world model, enabling more robust long-horizon task sequencing and skill execution than single-forward-pass VLA baselines.
- **[HAF: Adapting Generalist VLAs to Humanoid Whole-Body Loco-manipulation via Hierarchical Action Flow and Spectral Latent RL](http://arxiv.org/abs/2608.16837v1)**  
  Authors: Langzhe Gu et al.  
  Presents a hierarchical action flow and spectral latent reinforcement learning framework to adapt generalist VLAs to humanoid whole-body loco-manipulation, addressing the high dimensionality and interdependence of humanoid motion that limits off-the-shelf VLA performance.
- **[Security of Foundation-Model-Powered Embodied Agents: Attack Surfaces, Attacks, Defenses, and Evaluation](http://arxiv.org/abs/2608.16843v1)**  
  Authors: Jiawei Liu et al.  
  Delivers a comprehensive taxonomy of security threats for foundation-model-powered embodied agents, mapping attack surfaces from digital prompt injection to physical action exploitation and outlining standardized evaluation protocols for agent security.
- **[When State Becomes an Attack Surface: State-Semantic Injection in LLM-Driven Embodied Agents](http://arxiv.org/abs/2608.16806v1)**  
  Authors: Jiawei Liu et al.  
  Identifies a novel state-semantic injection attack vector targeting LLM-driven embodied agents, where adversaries manipulate perceived environment state semantics to hijack agent planning and action execution without modifying explicit prompts.
- **[When Agents Coordinate: Measuring Coordination in Multi-Agent AI Coding](http://arxiv.org/abs/2608.16801v1)**  
  Authors: Giuseppe Destefanis, Tomaso Aste  
  Introduces a standardized measurement instrument for quantifying coordination efficiency in multi-agent AI coding teams, filling a critical gap in current agent evaluation that focuses only on task completion and cost.
### 🔧 Methods & Frameworks (new techniques, benchmarks, efficiency improvements)
- **[Improving the matrix multiplication exponent with modern optimization and AlphaEvolve](http://arxiv.org/abs/2608.16884v1)**  
  Authors: Emilien Dupont et al.  
  Leverages modern optimization techniques and the AlphaEvolve evolutionary framework to refine the laser method, achieving a tighter bound on the matrix multiplication exponent $\omega$ with implications for accelerating core computational workloads across AI and theoretical computer science.
- **[AutoSR: Automatic Symbolic Regression by Searching Research States](http://arxiv.org/abs/2608.16876v1)**  
  Authors: Kejia Zhang et al.  
  Presents a fully automated symbolic regression system that searches persistent scientific investigation states rather than isolated equations, producing more physically consistent and generalizable expressions from noisy, limited data than traditional methods.
- **[Q-based Variational Inverse Reinforcement Learning](http://arxiv.org/abs/2608.16888v1)**  
  Authors: Ondrej Bajgar et al.  
  Proposes a Q-function-based variational inverse reinforcement learning framework that efficiently infers human preferences from demonstrations without explicit reward function engineering, advancing safe, human-aligned AI system development.
- **[CaliBench: Are the Stochastic Dynamics of Video World Models Physically Calibrated?](http://arxiv.org/abs/2608.16829v1)**  
  Authors: Jonathan Sadeghi et al.  
  Introduces a benchmark for fine-grained evaluation of stochastic dynamics calibration in video world models, measuring aleatoric uncertainty alignment with physical reality rather than just aggregate generation quality.
### 📊 Applications (domain-specific, multimodal, code generation)
- **[LAVA: Logic-Aware Validation and Augmentation Framework for Large-Scale Financial Document Auditing](http://arxiv.org/abs/2608.16763v1)**  
  Authors: Ruoqi Shu et al.  
  Develops a logic-aware validation and augmentation framework for financial document auditing that ensures high accuracy, consistency, and reproducibility across heterogeneous document layouts, meeting strict enterprise compliance requirements for payroll, tax, and loan use cases.
- **[Data-Efficient and Interpretable Classification of Circulating Tumor Cell Phenotypes in Microfluidic Devices via Deep Learning](http://arxiv.org/abs/2608.16870v1)**  
  Authors: Serena Su et al.  
  Introduces a data-efficient, interpretable deep learning pipeline for classifying circulating tumor cell phenotypes from label-free microfluidic device data, enabling low-cost, non-invasive assessment of cancer metastatic potential.
---
## 3. Research Trend Signal
Today’s submissions signal three rapidly accelerating research shifts. First, embodied agent security has emerged as a critical standalone subfield, moving beyond digital prompt injection to characterize state-level attack surfaces, physical action exploit chains, and standardized security evaluation protocols for foundation-model-powered robots. Second, long-horizon VLA systems are shifting from static, single-forward-pass architectures to dynamic, hierarchical designs that allocate variable test-time compute, leverage transition-aware memory, and integrate internal world models to mitigate error compounding across multi-step tasks. Third, rigor and governance for deployed AI are expanding beyond raw performance metrics, with new work on compliance detector auditing, computational provenance for generated text, and fine-grained physical calibration benchmarks for video world models. These trends reflect the field’s maturation as AI systems move from controlled digital settings to high-stakes physical and enterprise deployments.
---
## 4. Worth Deep Reading
1. **[Model Hypnosis: Strong control of AI via additive subliminal effects](http://arxiv.org/abs/2608.16834v1)**  
   This work identifies a novel, cross-cutting vulnerability that challenges core assumptions about LLM robustness to subtle input perturbations. Unlike well-studied jailbreaks or prompt injection, model hypnosis uses individually irrelevant, subliminal cues that are nearly undetectable to human auditors, making it a uniquely dangerous threat for deployed AI systems. The paper’s systematic evaluation across model families and scales provides a rigorous foundation for future work on guardrail hardening and alignment against distributed adversarial signals.
2. **[Improving the matrix multiplication exponent with modern optimization and AlphaEvolve](http://arxiv.org/abs/2608.16884v1)**  
   This paper demonstrates the power of AI-driven evolutionary optimization to advance one of the most fundamental open problems in theoretical computer science, with potential transformative impacts on everything from LLM training to scientific computing. The application of AlphaEvolve to refine the laser method’s core optimization problem highlights a growing paradigm of AI as a tool for foundational mathematical discovery, making it essential reading for researchers across AI theory and applied systems.
3. **[Don't Drop the BATON: Long-Horizon Robot Manipulation via Agentic Subtask Exploration and Transition-aware Memory](http://arxiv.org/abs/2608.16889v1)**  
   Long-horizon task failure due to error compounding and cross-subtask constraint propagation is the primary bottleneck preventing generalist VLA models from being deployed in real-world robotic settings. This work’s agentic subtask exploration and transition-aware memory framework is a generalizable solution that can be integrated with existing VLA foundation models, offering a clear path to unlocking multi-stage robot manipulation for industrial and household use cases.

---
*This digest is auto-generated by [agents-radar](https://github.com/THTHDGCS/agents-radar).*