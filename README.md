# Hamiltonian engineering and quantum-walk dynamics in a four-qubit superconducting concentric-transmon device

This repository contains the computational workflow, simulation data, analysis scripts, and supporting files associated with the manuscript:

**“Hamiltonian engineering and quantum-walk dynamics in a four-qubit superconducting concentric-transmon device”**

The work presents a device-aware computational framework connecting a proposed four-qubit superconducting concentric-transmon architecture with three-dimensional finite-element electromagnetic simulation, energy participation ratio (EPR) analysis, effective multimode Hamiltonian modeling, graph-Hamiltonian embedding, and continuous-time quantum-walk (CTQW) simulations.

---

## 1. Overview

The workflow developed in this work connects the physical device geometry to its effective Hamiltonian and subsequent graph-based quantum dynamics:

```text
Device layout
     │
     ▼
Four-qubit concentric-transmon architecture
     │
     ▼
3-D finite-element electromagnetic simulation
(PALACE)
     │
     ▼
Eigenmode analysis
     │
     ▼
Energy Participation Ratio (EPR) analysis
     │
     ▼
Device-specific multimode Hamiltonian
     │
     ├── Qubit-like modes: Q1–Q4
     │
     └── Resonator-like modes
     │
     ▼
C4 graph embedding
     │
     ├── Adjacency Hamiltonian
     └── Laplacian Hamiltonian
     │
     ▼
Single-excitation CTQW
     │
     ▼
QuTiP numerical time evolution
