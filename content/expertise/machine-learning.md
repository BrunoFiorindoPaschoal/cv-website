---
title: Machine Learning
weight: 2
image: images/Machine.png
papers:
  - title: Task Learning with Mechanical Neural Networks
    file: papers/Paper_TO_MNN_Bruno_Paschoal1.pdf
  - title: Classification with Hydraulic Neural Networks
    file: papers/Paper_TO_MNN_Bruno_Paschoal_Hidraulic.pdf
---
I am interested in machine learning both as a tool for engineering and as something that can be built into physical matter.

### Physical neural networks
In my FAPESP-funded research I developed neural networks that compute with physics instead of electronics:

- a **hydraulic neural network**, in which pipe cross-sections are the trainable weights, inputs set the boundary conditions and the steady-state flow encodes the class; validated on the Iris dataset in COMSOL Multiphysics;
- a **mechanical neural network** on nonlinear trusses, in which beam stiffnesses are the learnable parameters, external loads are the inputs and nodal displacements the outputs.

Both were trained end-to-end with gradient-based optimization using adjoint sensitivities (COMSOL LiveLink for MATLAB), with applications in mind such as smart structures and soft robotics.

### ML for engineering
At TUM LPL I build **surrogate models** that replace expensive finite element simulations inside design optimization loops.

### LLMs, agents & reinforcement learning
- **AI voice tutor for German** (personal project): a real-time speech-to-speech LLM pipeline (Pipecat, Gemini Live API) with role-play scenarios, live error correction and a SQLite long-term memory filled by end-of-session LLM summaries.
- **Hugging Face certifications** (2026): Deep Reinforcement Learning with a Certificate of Excellence (DQN/PPO agents incl. robotic-arm control in Panda-Gym), AI Agents (smolagents, LangGraph, LlamaIndex, evaluated on GAIA) and Model Context Protocol.

### Related coursework
Physics-Informed Machine Learning, Machine Learning and Optimization (TUM) · Machine Learning and Pattern Recognition with Prof. Dr. Fabio Gagliardi Cozman, covering the numerical theory behind learning and the implementation of classification algorithms (USP).
