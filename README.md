# Modeling of Adaptive Transport Networks in Biology 🩸🕸️ (ongoing)

ODE model and numerical simulation of networks system that carry materials and adapt their structure. The goals is to justify the typical 'branching tree' shape of vascular systems in plants and animals in terms of biological principles.

---

## Overview

- Research shows that the typical 'braching tree' structure of vascualar systems is highly energy efficient and damage resilient (#add sources). However, the *process* bringing up this specific shape is debated. In [this article](https://doi.org/10.1103/PhysRevLett.111.138701) the authors show how such a structure can be a direct consecuence of wall shear stress adaptation in vessels and energy optimization
- We aim to implement their numerical solution and reproduce their figures using the `NetworkX` Python library

---

## System's description

- We start with a fine grid representing the possible places a vessel can take. Nodes stand for random flow sources and sinks.
- An ODE system for the blood flow based on convention (#add source) and a novel penalty term describes the dynamics.
- We start the model on a fully connected grid and expect the system to be reduced to a hierarchical structure with loops after a few iterations.

---

## Methods

- Modeling approaches
- Algorithms used
- Statistical methods
- Validation strategy

---

## Project Structure

```text
project/
│
├── data/
├── notebooks/
├── src/
├── results/
├── docs/
└── README.md
