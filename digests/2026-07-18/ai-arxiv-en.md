# ArXiv AI Research Digest 2026-07-18

> Source: [ArXiv](https://arxiv.org/) (cs.RO, cs.AI, cs.LG, cs.CV) | 50 papers | Generated: 2026-07-18 01:20 UTC

---

# ArXiv AI Research Digest | 2026-07-18
---

## 1. Today's Highlights
Today’s ArXiv AI submissions center on breakthroughs in embodied AI scalability, agent system specialization, and rigorous AI safety and evaluation for real-world deployment. Leading work in robotics pushes context windows for visuomotor policies three orders of magnitude beyond state-of-the-art, while new behavior foundation models target generalizable whole-body control for humanoid robots. Safety research surfaces critical unaddressed risks: vulnerabilities of LLM pretraining pipelines to computational propaganda poisoning, and mismatches between text-level LLM safety guardrails and physical danger when models act as embodied planners. The batch also delivers a suite of domain-specific benchmarks and agent tools tailored for high-impact use cases including automated research meta-analysis, medical AI safety boundary testing, and scientific diagram editing.

---

## 2. Key Papers
### 🧠 Large Language Models (architecture, training, alignment, evaluation)
1. **[Pretraining Data Can Be Poisoned through Computational Propaganda](http://arxiv.org/abs/2607.15267v1)**  
   Authors: Victoria Graf et al.  
   Demonstrates that LLM pretraining corpora are vulnerable to scalable, hard-to-detect poisoning via computational propaganda campaigns that exploit the heterogeneity of unvetted web training data, exposing a critical unaddressed vulnerability in foundation model supply chains.
2. **[In-Place Tokenizer Expansion for Pre-trained LLMs](http://arxiv.org/abs/2607.15232v1)**  
   Authors: Jimmy T. H. Smith et al.  
   Introduces a post-deployment method to expand fixed pre-trained LLM tokenizers without full retraining, reducing tokenization overhead for newly prioritized languages or niche domains, and cutting latency, compute, and energy costs for under-served use cases.
3. **[Can We Trust Item Response Theory for AI Evaluation?](http://arxiv.org/abs/2607.15190v1)**  
   Authors: Han Jiang et al.  
   Identifies systematic deviations between AI benchmark data and human testing regimes that undermine the validity of item response theory (IRT)—a widely adopted method for ranking model capabilities and curating benchmarks—calling for revised statistical frameworks tailored to AI evaluation.
4. **[When Words Are Safe But Actions Kill: Probing Physical Danger Beyond Text Safety in Hidden-State Risk Space](http://arxiv.org/abs/2607.15218v1)**  
   Authors: Weimeng Wang et al.  
   Proves that text-level LLM safety guardrails fail to detect physically harmful instructions when models act as embodied planners, introducing a hidden-state risk space framework to measure this unaddressed safety gap for real-world embodied deployment.

### 🤖 Agents & Reasoning (planning, tool use, multi-agent, chain-of-thought)
1. **[RoboTTT: Context Scaling for Robot Policies](http://arxiv.org/abs/2607.15275v1)**  
   Authors: Yunfan Jiang et al.  
   Scales visuomotor context for robot policies to 8K timesteps (three orders of magnitude beyond prior work) via a test-time-training recipe, enabling long-horizon robot task execution in unstructured environments without sacrificing inference efficiency.
2. **[Scaling Behavior Foundation Model for Humanoid Robots](http://arxiv.org/abs/2607.15163v1)**  
   Authors: Weishuai Zeng et al.  
   Demonstrates scaling laws for behavior foundation models (BFMs) for humanoid robots, showing that larger models and diverse whole-body motion datasets deliver improved generalization across environmental contexts and control tasks, laying a roadmap for generalist embodied agents.
3. **[SearchOS-V1: Towards Robust Open-Domain Information-Seeking Agent Collaboration](http://arxiv.org/abs/2607.15257v1)**  
   Authors: Yuyao Zhang et al.  
   Introduces a multi-agent framework for open-domain information seeking that addresses context drift and failed search attempts in long interaction histories, outperforming single-agent baselines on complex research and fact-checking tasks.
4. **[AutoSynthesis: An agentic system for automated meta-analysis](http://arxiv.org/abs/2607.15247v1)**  
   Authors: Moein Taherinezhad et al.  
   Presents an end-to-end multi-agent system that automates quantitative meta-analysis across scientific domains, reducing manual labor and scaling evidence synthesis for medicine, policy, and cumulative research applications.
5. **[Plover: Steering GUI Agents through Plan-Centric Interaction](http://arxiv.org/abs/2607.15193v1)**  
   Authors: Madhumitha Venkatesan et al.  
   Introduces a plan-centric interaction framework for GUI automation agents that reduces drift from user intent in dynamic interface environments, enabling reliable autonomous operation on complex real-world enterprise and consumer workflows.

### 🔧 Methods & Frameworks (new techniques, benchmarks, efficiency improvements)
1. **[T^2MLR: Transformer with Temporal Middle-Layer Recurrence](http://arxiv.org/abs/2607.15178v1)**  
   Authors: Ziyang Cai et al.  
   Adds temporal middle-layer recurrence to transformers to preserve intermediate reasoning states across autoregressive decoding steps, improving long-context reasoning performance without the overhead of full context window expansion.
2. **[Mask-Aware Policy Gradients for Diffusion Language Models](http://arxiv.org/abs/2607.15200v1)**  
   Authors: Haran Raajesh et al.  
   Resolves the log-likelihood intractability barrier to applying reinforcement learning to Masked Diffusion Language Models, enabling RL alignment of diffusion-based LLMs for improved reasoning and human preference alignment.
3. **[Symbal: Detecting Systematic Misalignments in Model-Generated Captions](http://arxiv.org/abs/2607.15216v1)**  
   Authors: Maya Varma et al.  
   Introduces a method to detect recurring systematic misalignments between MLLM-generated captions and input images, addressing a pervasive failure mode that erodes trust in multimodal model outputs for clinical and enterprise use cases.

### 📊 Applications (domain-specific, multimodal, code generation)
1. **[SciDiagramEdit: Learning to Edit Scientific Diagrams from Paper Revisions](http://arxiv.org/abs/2607.15272v1)**  
   Authors: Yasheng Sun et al.  
   Trains a multimodal model to edit scientific diagrams according to natural language instructions by learning from real paper revision workflows, automating a time-consuming routine task for academic and industrial researchers.
2. **[MedFailBench: A Clinician-Built Open-Source Benchmark for Medical AI Safety Boundary Inspection](http://arxiv.org/abs/2607.15166v1)**  
   Authors: Goktug Ozkan et al.  
   Presents a clinician-curated benchmark that evaluates medical AI models on safety boundary failures (rather than just accuracy) with severity-labeled error cases, enabling more rigorous safety testing for clinical AI deployment.
3. **[Benchmarking Multimodal Large Language Models for Scientific Visualization Literacy](http://arxiv.org/abs/2607.15176v1)**  
   Authors: Patrick Phuoc Do et al.  
   Benchmarks six leading MLLMs on scientific visualization literacy beyond basic chart understanding, revealing large gaps in model ability to interpret domain-specific SciVis content for research and education applications.

---

## 3. Research Trend Signal
A clear emerging trend across today’s submissions is the expansion of context scaling paradigms beyond text-only LLMs to embodied visuomotor systems, with robot policies now reaching 8K timestep context windows to enable long-horizon task execution. Concurrently, research is shifting from narrow inference-time LLM safety to end-to-end foundation model supply chain and deployment risk: work highlights scalable pretraining poisoning via computational propaganda, and dangerous mismatches between text safety guardrails and physical world risk for embodied planners. Finally, there is a growing rejection of one-size-fits-all accuracy benchmarks in favor of domain-specific, safety- and failure-focused evaluation frameworks for medical AI, multimodal systems, and agent tools, reflecting a push to mature AI for real-world high-stakes use.

---

## 4. Worth Deep Reading
1. **[Pretraining Data Can Be Poisoned through Computational Propaganda](http://arxiv.org/abs/2607.15267v1)**  
   This work exposes a fundamental, scalable vulnerability in the global foundation model supply chain that prior poisoning research has overlooked. Unlike targeted attacks on curated sources like Wikipedia, computational propaganda can be injected at scale into the unvetted heterogeneous web corpora that most modern LLMs are trained on, with long-lasting, hard-to-mitigate harms to model reliability, political neutrality, and safety. It is required reading for LLM developers, safety researchers, and policymakers.
2. **[RoboTTT: Context Scaling for Robot Policies](http://arxiv.org/abs/2607.15275v1)**  
   This paper represents a step change in embodied AI capability, solving a core bottleneck for long-horizon robot task execution by scaling visuomotor context three orders of magnitude beyond prior work without sacrificing efficiency. Its test-time-training recipe provides a viable blueprint for generalist robot policies that can operate in unstructured real-world environments for extended periods, a critical milestone for commercial and industrial robotics deployment.
3. **[AutoSynthesis: An agentic system for automated meta-analysis](http://arxiv.org/abs/2607.15247v1)**  
   This work delivers one of the first end-to-end agent systems that directly addresses a major bottleneck in scientific progress: the slow, labor-intensive process of quantitative meta-analysis. By automating evidence synthesis at scale, it has immediate transformative potential for medical research, policy-making, and cumulative science, while also demonstrating a viable blueprint for specialized multi-agent systems that outperform generalist models on high-stakes domain-specific tasks.

---
*This digest is auto-generated by [agents-radar](https://github.com/THTHDGCS/agents-radar).*