---
title: Optimization
weight: 1
image: images/Topologic.png
papers:
  - title: Topology Optimization of Electric Machines
    file: papers/Paper_TO___Electric_Machines.pdf
---
Numerical optimization is the common thread of my work: letting an algorithm, rather than intuition alone, decide how a system should be shaped.

### Topology optimization
Topology optimization changes the distribution of material inside a design domain to maximize the performance of a system. As a FAPESP-funded researcher at USP's Multiphysics Systems Optimization Laboratory (MSOL), I developed my own algorithm to optimize **switched reluctance motors**:

- thermo-magnetic finite element models built on the open-source **FEniCS** platform, with **dolfin-adjoint** for sensitivities and **IPOPT** as the optimizer;
- significant material reduction together with measurable efficiency gains;
- an extension to **discrete multi-material optimization** with TOBS, validated against commercial software.

### Design optimization at TUM
At the TUM Laboratory for Product Development and Lightweight Design (LPL), I work on **Multidisciplinary Design Optimization** and the **Solution Space** method, which finds ranges of good designs instead of a single optimum. I build surrogate models that replace expensive finite element analyses and maintain the lab's Optimization Toolbox. With a Bavarian industry partner, we applied the method to a soil-compaction motor hammer, improving its performance and worker safety.

### Related coursework
Multidisciplinary Design Optimization, Optimal Control and Decision Making, Machine Learning and Optimization, Numerical Methods for Conservation Laws (TUM) · Numerical Methods and Applications, Computational Mechanics for Mechatronics (USP).
