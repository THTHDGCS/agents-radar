# ArXiv AI Research Digest 2026-07-14

> Source: [ArXiv](https://arxiv.org/) (cs.RO, cs.AI, cs.LG, cs.CV) | 18 papers | Generated: 2026-07-14 01:19 UTC

---

# ArXiv AI Research Digest | 2026-07-14
---

## 1. Today's Highlights
Today’s batch of 18 ArXiv papers (crosslisted in cs.AI, cs.CL, cs.LG, and cs.RO) centers on bridging generative AI advances to real-world robotic deployment, with a heavy focus on safety, efficiency, and extreme-environment perception. A standout thread is the integration of diffusion models into core robotic pipelines, from multi-task manipulation policies to safe model predictive control, addressing longstanding gaps in constraint adherence for generative planning outputs. Researchers also introduced training-free controllability mechanisms for driving world models and cross-modal distillation pipelines to transfer vision foundation model capabilities to LiDAR systems, reducing the computational and annotation overhead of robotic perception development. Additional advances target robust deployment of robotic foundation models, including mitigation of shortcut learning and self-play fine-tuning for motion planning in rare safety-critical driving scenarios.

---

## 2. Key Papers
Organized by research theme:

### 🧠 Large Language Models (architecture, training, alignment, evaluation)
- [Traj-VLN: Learning Pixel-Space Interaction via Autoregressive Trajectory Generation](http://arxiv.org/abs/2607.10744v1)
  Authors: Changfei Fu et al.
  Leverages large language model-derived commonsense reasoning to enable pixel-space autoregressive trajectory generation for vision-language navigation, eliminating the need for intermediate symbolic scene representations to improve generalization across unseen indoor environments.
- [Dual-Process Atomic Skill Learning: Decoupling Semantic Reasoning and Real-Time Control](http://arxiv.org/abs/2607.10625v1)
  Authors: Jun Chen et al.
  Introduces a language-conditioned imitation learning framework that separates high-level natural language-aligned semantic reasoning from low-latency real-time control, enabling zero-shot generalization to multi-step compositional robotic tasks without the overhead of hierarchical policy architectures.

### 🤖 Agents & Reasoning (planning, tool use, multi-agent, chain-of-thought)
- [World Models as Adversaries: Multi-Agent Self-Play Fine-Tuning for Robust Motion Planning](http://arxiv.org/abs/2607.10630v1)
  Authors: Tong Nie et al.
  Leverages world models as adversarial agents in self-play fine-tuning for autonomous vehicle motion planning, generating rare safety-critical traffic scenarios without external scenario generators to improve robustness in dense, high-risk driving environments.
- [Coverage Path Planning: Classical Foundations, Recent Advances, and Future Directions](http://arxiv.org/abs/2607.10649v1)
  Authors: Zongyuan Shen et al.
  Presents a comprehensive survey of coverage path planning (CPP) for robots, synthesizing decades of classical work and modern learning-based advances to outline open challenges for CPP deployment in domains from agriculture to search and rescue.
- [SLIDER: Sparse History-Guided Aerial Robot Target Search using Sliding Local Maps](http://arxiv.org/abs/2607.10553v1)
  Authors: Xiaolei Hou et al.
  Introduces a lightweight, memory-efficient target search framework for aerial robots that uses sliding local maps and sparse historical perception data to enable efficient exploration of large-scale unknown environments without full global map construction.
- [Action Map Policy: Learning 3D Closed-loop Manipulation via Pixel Classification](http://arxiv.org/abs/2607.10706v1)
  Authors: Haojie Huang et al.
  Redefines robotic manipulation action representation as a pixel classification problem, eliminating the complexity of high-dimensional continuous action spaces to enable sample-efficient learning of closed-loop 3D manipulation tasks.

### 🔧 Methods & Frameworks (new techniques, benchmarks, efficiency improvements)
- [A Single Diffusion-Policy Controller for Multi-Task Block Pushing with Zero-Shot Sim-to-Real Transfer](http://arxiv.org/abs/2607.10892v1)
  Authors: Haitong Ma et al.
  Trains diffusion policies for multi-task robotic manipulation from scratch via reinforcement learning (instead of behavior cloning), achieving zero-shot sim-to-real transfer for block pushing tasks with a single unified controller and expanding the utility of diffusion policies beyond imitation learning settings.
- [D-SafeMPC: Diffusion-Driven Safe Model Predictive Control with Discrete-Time Control Barrier Functions](http://arxiv.org/abs/2607.10842v1)
  Authors: Erdi Sayar et al.
  Combines diffusion models with discrete-time control barrier functions to build a safe model predictive control framework, ensuring diffusion-generated robotic planning outputs adhere to hard dynamical and safety constraints without the computational overhead of prior hybrid MPC approaches.
- [TOLiD: Bridging the Architecture Gap in Vision Foundation Model to LiDAR Pretraining via Token Lifting for Distillation](http://arxiv.org/abs/2607.10762v1)
  Authors: Sutharsan Mahendran et al.
  Introduces a token lifting distillation strategy that transfers capabilities from large vision foundation models to LiDAR backbones, eliminating architecture mismatches in prior cross-modal distillation pipelines to reduce reliance on dense 3D point cloud annotations for 3D scene understanding.
- [Is Energy Guidance All You Need? Training-Free Norm Injection for Driving World Models](http://arxiv.org/abs/2607.10781v1)
  Authors: Xiyan Su et al.
  Demonstrates that energy guidance can inject traffic norms into diffusion-based driving world models without retraining the underlying video diffusion backbone or relying on hand-built scene layouts, drastically reducing the cost of aligning world models to real-world driving rules.
- [BucketKD: A Safety-Aware Bucket-Based Knowledge Distillation Framework for End-to-End Motion Planning](http://arxiv.org/abs/2607.10565v1)
  Authors: Md Nahidul Islam et al.
  Presents a safety-aware knowledge distillation framework for end-to-end autonomous driving motion planning models, reducing model size by 60% for resource-constrained deployment while preserving safety-critical planning performance better than standard distillation approaches.
- [Artificial Foveated Perception for Mitigating Shortcut Learning in Robotic Foundation Models](http://arxiv.org/abs/2607.10655v1)
  Authors: Xiatao Sun et al.
  Introduces a biologically inspired foveated perception mechanism for robotic foundation models that prioritizes processing of causally relevant visual inputs, reducing shortcut learning and improving cross-environment generalization for multi-task robotic control.

### 📊 Applications (domain-specific, multimodal, code generation)
- [Mapping Pamir: Multi-Session Visual-Inertial SLAM and 3D Reconstruction of an Underwater Shipwreck](http://arxiv.org/abs/2607.10925v1)
  Authors: Michalis Chatzispyrou et al.
  Develops a low-cost multi-session underwater SLAM framework using consumer action cameras and dive computer depth data to produce high-fidelity 3D reconstructions of underwater shipwrecks, enabling accessible marine archaeology and inspection without expensive specialized sensing hardware.
- [X-GuideAR: An Augmented Reality Framework to Mitigate Radiation Exposure during Fluoroscopic Guidance](http://arxiv.org/abs/2607.10873v1)
  Authors: Mingxu Liu et al.
  Introduces an augmented reality framework for orthopedic surgery that reduces "fluoro-hunting" X-ray radiation exposure for patients and surgical teams by providing real-time AR alignment guidance without repeated fluoroscopic scans during screw placement procedures.
- [Learning Roller-Skating Motions of Humanoid Robots Based on Adversarial Motion Priors](http://arxiv.org/abs/2607.10815v1)
  Authors: Yunkang Cheng et al.
  Introduces an adversarial motion prior-based reinforcement learning framework to learn two humanoid roller-skating gaits, coordinating whole-body balance, rolling contacts, and velocity-dependent posture for dynamic bipedal locomotion on wheels.

---

## 3. Research Trend Signal
A clear emerging trend across today’s submissions is the rapid integration of generative AI (most notably diffusion models) into core robotic control and planning pipelines, with an unprecedented focus on hard safety constraint enforcement to bridge the gap between generative outputs and real-world high-stakes deployment. Parallel to this, researchers are prioritizing reduction of development and deployment overhead for robotic AI systems: training-free norm injection for world models, cross-modal distillation to eliminate reliance on expensive 3D point cloud annotations, and safety-aware knowledge distillation for resource-constrained edge hardware all target key bottlenecks to scaling robotic systems. Finally, work is increasingly validated in extreme or high-stakes domains (underwater inspection, surgical guidance, autonomous driving safety) rather than controlled lab settings, signaling an industry-aligned shift toward production-ready robotic AI.

---

## 4. Worth Deep Reading
1. **[D-SafeMPC: Diffusion-Driven Safe Model Predictive Control with Discrete-Time Control Barrier Functions](http://arxiv.org/abs/2607.10842v1)**
   Reasoning: This paper addresses the most critical limitation of diffusion models for robotic planning—their lack of inherent safety guarantees—by integrating discrete-time control barrier functions into a diffusion-driven MPC framework. Unlike prior hybrid approaches that suffer from prohibitive computational overhead, this method balances the flexibility of generative trajectory generation with hard dynamical and safety constraints, offering a deployable solution for use cases from industrial manipulation to autonomous driving.
2. **[Is Energy Guidance All You Need? Training-Free Norm Injection for Driving World Models](http://arxiv.org/abs/2607.10781v1)**
   Reasoning: This work upends the prevailing assumption that aligning large diffusion-based world models to domain-specific rules (e.g., traffic laws) requires full backbone retraining or hand-engineered scene layouts. The training-free energy guidance approach cuts development costs by orders of magnitude while maintaining generation quality, with broad implications for autonomous driving simulation, robotic planning, and controllable video generation more broadly.
3. **[Coverage Path Planning: Classical Foundations, Recent Advances, and Future Directions](http://arxiv.org/abs/2607.10649v1)**
   Reasoning: As the only comprehensive survey in today’s batch, this paper synthesizes 30+ years of research across classical and learning-based coverage path planning paradigms, unifying terminology and benchmarking standards across domains from agricultural robotics to underwater inspection. Its clear roadmap of open research gaps makes it an essential reference for both new and experienced researchers in robotic motion planning.

---
*This digest is auto-generated by [agents-radar](https://github.com/THTHDGCS/agents-radar).*