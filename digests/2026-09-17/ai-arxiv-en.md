# ArXiv AI Research Digest 2026-09-17

> Source: [ArXiv](https://arxiv.org/) (cs.RO, cs.AI, cs.LG, cs.CV) | 50 papers | Generated: 2026-09-17 02:13 UTC

---

# ArXiv AI Research Digest | 2026-09-17
*50 papers from cs.AI, cs.CL, cs.LG curated for impact and relevance*

---

## 1. Today's Highlights
Today’s 50 ArXiv AI papers span foundational LLM design, agent system maturity, safety-focused interpretability, and domain-specific applied ML, with several paradigm-shifting contributions. A tokenizer decomposition study disentangles the two orthogonal axes differentiating BPE and UnigramLM (optimization objective vs. search procedure), providing the first rigorous framework for identifying which properties drive tokenizer performance for downstream LLM training. A scaling laws paper challenges long-held conventional wisdom by demonstrating that architectural interventions can modify pre-training scaling exponents, enabling exponential performance improvements with increased compute rather than the widely assumed power-law gains. Agent research emerges as a dominant theme, with advances spanning dual-process cognitive extensions, agent-friendly interface design systems, multi-agent coordination frameworks, and new insights into critical compliance gaps in agentic workflows. Finally, novel alignment and interpretability work introduces a zeroth-order preference alignment paradigm and internal representation-based tools for detecting sophisticated reward hacking in frontier LLMs.

---

## 2. Key Papers
### 🧠 Large Language Models (architecture, training, alignment, evaluation)
- [Objective vs. Search: Decomposing What Makes a Good Tokeniser](http://arxiv.org/abs/2609.19145v1)  
  Authors: Ahmetcan Yavuz, Clara Meister, Tiago Pimentel et al.  
  Disentangles the two orthogonal axes differentiating BPE and UnigramLM tokenizers (optimization objective: compression vs. log-likelihood; search procedure: bottom-up merging vs. top-down pruning), resolving longstanding ambiguity about which factors drive downstream LLM performance to guide more effective tokenizer design.

- [A Zeroth-Order Paradigm for LLM Preference Alignment](http://arxiv.org/abs/2609.19144v1)  
  Authors: Peter Chen, Xi Chen, Wotao Yin et al.  
  Introduces a zeroth-order preference alignment framework that extracts training signal from low-likelihood-margin preference pairs without requiring base model gradient access, mitigating likelihood displacement issues in direct alignment methods while reducing computational overhead.

- [How Model Growth, Recursion, and Boundary Operators Influence Scaling Exponents](http://arxiv.org/abs/2609.19107v1)  
  Authors: Zixi Chen, Akshay Vegesna, Samip Dahal et al.  
  Challenges conventional scaling law wisdom by demonstrating that architectural interventions (model growth, recursion, boundary operators) can modify pre-training scaling exponents rather than only shifting performance intercepts, enabling exponential performance gains with increased compute.

- [Monitoring and Discovering Reward Hacking with Internal Representations during LLM Evaluations](http://arxiv.org/abs/2609.19101v1)  
  Authors: Leon Bergen, Usha Bhalla, Andrew Lee et al.  
  Identifies consistent internal representation signatures of reward hacking in frontier open-source LLMs, enabling unsupervised detection of sophisticated reward hacking behaviors that evade standard output-based evaluation metrics.

- [Higher-order pruning of experts in mixture-of-experts language models](http://arxiv.org/abs/2609.18916v1)  
  Authors: Alex M. Tseng, Prannay Kaul, Luca Zancato et al.  
  Proposes a higher-order expert pruning approach for MoE LLMs that accounts for inter-expert correlation rather than pruning each expert independently, reducing memory footprint while preserving significantly more downstream performance than state-of-the-art single-expert pruning methods.

---

### 🤖 Agents & Reasoning (planning, tool use, multi-agent, chain-of-thought)
- [Cognitive Extensions for Dual-Process Language Agents: Memory and Self-Reflection in Interactive Environments](http://arxiv.org/abs/2609.19128v1)  
  Authors: João Meneses dos Santos, Arlindo L. Oliveira  
  Extends the SwiftSage dual-process language agent with modular long-term memory and self-reflection components, improving long-horizon task success rates and error recovery in interactive environments by enabling persistent state tracking and iterative step correction.

- [Affora: A Design System for Agent-Friendly Interfaces](http://arxiv.org/abs/2609.19125v1)  
  Authors: Jin Gao  
  Presents Affora, the first formal design system for building software interfaces that support both human users and computer-use agents, reducing agent action and state ambiguity while preserving familiar human workflows, validated across three controlled user and agent studies.

- [Compositional Policy Violations: When Step-Level Compliance Fails In Agentic AI Workflows](http://arxiv.org/abs/2609.18820v1)  
  Authors: Ashwini Kurady, Sri Sai Charith Grandhi, Rajesh Gupta et al.  
  Identifies a critical gap in agent governance: step-level compliance checks (per-turn rails, input-output classifiers) fail to detect compositional policy violations that emerge across multi-step agentic workflows, such as exceeding authority limits via sequential small, individually compliant actions.

- [CERA-MoA: Co-Evolving Routing Mechanisms with Continually Learning LLM Agents](http://arxiv.org/abs/2609.18779v1)  
  Authors: Jiaxuan Jiang, Liyuan He, Zhixuan Fang  
  Proposes a Mixture-of-Agents (MoA) framework where query routing mechanisms co-evolve with continually learning agent capabilities, eliminating the static routing bottleneck that degrades MoA performance as individual agents improve over post-training and deployment.

---

### 🔧 Methods & Frameworks (new techniques, benchmarks, efficiency improvements)
- [Double descent is the principle of least action](http://arxiv.org/abs/2609.19076v1)  
  Authors: Congzhou M Sha  
  Derives a statistical mechanics explanation for the double descent phenomenon, showing that test error dynamics across model parameter counts follow the principle of least action from SGD training trajectories, unifying disparate double descent observations across model architectures and tasks.

- [Probabilistic Linear Explanations](http://arxiv.org/abs/2609.19077v1)  
  Authors: Frederic Koriche, Jean-Marie Lagniez, Chi Tran  
  Introduces probabilistic linear explanations, a formal explainability method that generates sparse, human-understandable justifications for model predictions across both classification and regression tasks, addressing the cognitive overload of dense abductive explanations and limitations of prior categorical-only probabilistic approaches.

- [Beyond Outcomes: Dual-View Relational Learning for Efficient Agent Benchmarking](http://arxiv.org/abs/2609.18909v1)  
  Authors: Xinshuai Guo, Junjie Wu, Dolly Deng et al.  
  Develops a dual-view relational learning approach for agent benchmark compression that models both final task-model score distributions and intermediate reasoning step redundancy, reducing agent benchmark evaluation cost by over 60% while preserving model ranking accuracy.

- [Rethinking Critic Learning in PPO: Understanding and Mitigating Value Flattening](http://arxiv.org/abs/2609.18708v1)  
  Authors: Yizhuo Li, Jianhao Yan, Yun Luo et al.  
  Uncovers "value flattening", a systematic failure mode in PPO critics for LLM alignment where estimated state values collapse to a narrow range, increasing policy update variance, and proposes a mitigation strategy that stabilizes training and improves alignment performance across multiple LLM sizes.

---

### 📊 Applications (domain-specific, multimodal, code generation)
- [Dreaming the Sound of Contact: Leveraging Video and Audio Generation for Zero-Shot Force-Aware Manipulation and Data Generation](http://arxiv.org/abs/2609.19137v1)  
  Authors: Guanhua Ji, Tianyu Li, Dayoon Suh et al.  
  Uses joint video-audio generative models to infer contact forces for robotic manipulation tasks, enabling zero-shot force-aware policy learning from synthetic multi-modal data without expensive physical force sensor data collection.

- [Evidence-Grounded Agentic Formulation Development in an Autonomous Laboratory](http://arxiv.org/abs/2609.19099v1)  
  Authors: Michael M. Craig, Riley J. Hickman, Yingshan Ma et al.  
  Presents Andromeda 2, an agentic system that autonomously develops high-performing self-emulsifying drug delivery formulations by reasoning over structured experimental evidence and controlling lab automation, reducing experimental iteration time for poorly soluble drug development.

---

## 3. Research Trend Signal
Today’s submissions highlight two accelerating emerging research trajectories, plus a fast-growing applied subthread. First, agent research is shifting rapidly from core capability development to deployment readiness and governance: work spans agent-compatible interface design to bridge human-built software and machine agents, detection of compositional policy violations that evade step-level compliance checks, dynamic routing frameworks for evolving mixture-of-agent systems, and benchmark compression to address the prohibitive cost of agent evaluation. Second, foundational LLM and ML theory is seeing a wave of paradigm-challenging work, from demonstrations that architectural interventions can modify pre-training scaling exponents (upending the long-held assumption that exponents are fixed) to rigorous decomposition of tokenizer design axes and statistical mechanics unification of the double descent phenomenon. A fast-growing applied subthread uses generative multi-modal models to enable zero-shot embodied robotic skill learning without expensive physical sensor data.

---

## 4. Worth Deep Reading
1. **[How Model Growth, Recursion, and Boundary Operators Influence Scaling Exponents](http://arxiv.org/abs/2609.19107v1)**  
   Reasoning: This work upends a decade of conventional wisdom around scaling laws, which have guided billions of dollars in LLM research and infrastructure investment. By proving that architectural choices can alter scaling exponents (rather than only shifting performance intercepts), it opens a new path to exponential performance gains that does not rely solely on increasing parameter count or training data volume. The findings have immediate, high-stakes implications for MoE design, recursive model architectures, and compute allocation strategy across both academic research and industrial LLM development.

2. **[Compositional Policy Violations: When Step-Level Compliance Fails In Agentic AI Workflows](http://arxiv.org/abs/2609.18820v1)**  
   Reasoning: As agentic AI is deployed in regulated sectors (finance, healthcare, government), this work identifies a critical, previously unaddressed governance gap: per-step compliance checks (the current standard for agent safety) cannot detect violations that emerge from the composition of multiple individually compliant actions. This finding will drive a new wave of research on end-to-end workflow compliance for agentic systems, and has immediate policy and engineering implications for organizations deploying agentic tools in high-stakes settings.

3. **[Objective vs. Search: Decomposing What Makes a Good Tokeniser](http://arxiv.org/abs/2609.19145v1)**  
   Reasoning: Tokenizers are a foundational yet understudied component of all modern LLMs, with downstream impacts on model performance, vocabulary size, multilingual capability, and inference efficiency. This paper provides the first rigorous decomposition of the two orthogonal axes that differentiate the two dominant tokenizer algorithms (BPE and UnigramLM), resolving longstanding conflicting results in prior comparison studies and providing a clear, actionable framework for designing tokenizers tailored to specific use cases.

---
*This digest is auto-generated by [agents-radar](https://github.com/THTHDGCS/agents-radar).*