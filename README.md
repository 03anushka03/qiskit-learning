# Quantum Computing with Qiskit: Algorithms, Noise, and VQE

## Overview

This repository documents a self-driven exploration of **quantum computing using Qiskit**, carried out during the winter break of the third year of a B.Tech program in Engineering Physics.

The primary objective of this work was to build **practical, software-oriented skills** in quantum computing, progressing from basic circuit construction to **noise-aware variational quantum algorithms**. The repository reflects a learning trajectory that culminates in a focused study of the **Variational Quantum Eigensolver (VQE)** under realistic noise models.

---

## Motivation

Quantum technologies are a core academic interest of mine, particularly at the intersection of:
- quantum algorithms
- near-term (NISQ) devices
- noise and robustness of variational methods

This project was undertaken to:
- bridge the gap between theoretical coursework and practical implementation
- gain hands-on experience with Qiskit
- understand how noise impacts quantum algorithms in realistic settings

---

## Repository Structure

The work is organized week-wise to reflect a natural progression of concepts and skills:


Each folder contains:
- a detailed README explaining the scope and outcomes
- one or more Jupyter notebooks implementing the corresponding concepts

---

## Summary of Work

### Week 1: Qiskit Fundamentals
- Quantum circuit construction
- Single- and multi-qubit gates
- Measurement and visualization
- Circuit transpilation and basic backend usage

### Week 2: Quantum Algorithms and Variational Methods
- Deutsch–Jozsa algorithm
- Grover’s search
- Quantum Fourier Transform (QFT)
- Quantum teleportation and superdense coding

### Week 3: Noise-Aware VQE (Core Project)
- VQE applied to a small Hamiltonian with known exact ground-state energy
- Ideal vs noisy simulations
- Depolarizing noise models
- Quantitative error analysis and visualization

---

## Key Outcomes

- Developed hands-on fluency with Qiskit and quantum circuit design
- Gained practical understanding of hybrid quantum–classical algorithms
- Studied the effect of noise on VQE performance
- Built a complete, reproducible simulation workflow suitable for extension into a semester project

---

## Limitations

- Simulations restricted to small system sizes
- Simplified noise models
- No error mitigation techniques applied

These limitations were intentional and chosen to prioritize clarity and conceptual understanding.

---

## Future Directions

Planned extensions include:
- error mitigation techniques (e.g., measurement mitigation, ZNE)
- larger Hamiltonians (e.g., Ising models)
- comparison of different ansätze under identical noise conditions
- benchmarking against QAOA

---

## Tools and Libraries

- Qiskit
- NumPy
- Matplotlib

---

## Author

**Anushka Chauhan**  
B.Tech Engineering Physics  
Indian Institute of Technology Mandi

---

## Note

This repository is intended as a learning and exploration project and serves as a foundation for guided research in quantum technologies.
