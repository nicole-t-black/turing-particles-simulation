# Turing Patterns & Particle Dynamics

Simulated **pattern formation** and **particle dynamics** in Python.

## Problem 1: Two-Cell Turing System
- Implemented Turing’s two-cell model with coupled ODEs.
- Explored stability under different diffusion coefficients:
  - Low \(D_x\) → unstable, populations diverge.
  - High \(D_x\) → stable, populations converge.
- Visualized trajectories of \(X_1\) and \(X_2\).
- Compared **Turing vs French-flag mechanisms** for pattern formation.

## Problem 2: Particle Dynamics
- Simulated 10 particles tethered to origin with springs.
- Added **pairwise repulsion** to prevent overlaps.
- Plotted trajectories and animations of motion.
- Explored effects of **timestep**, integrators, and neighbor lists.
- Discussed computational limits for large-scale simulations like Hi-C.
