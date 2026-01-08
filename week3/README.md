# 📘 Week 3: Noise-Aware VQE and Hamiltonian Simulation

## Overview

Week 3 focused on studying the impact of noise on **variational quantum algorithms**, with particular emphasis on the **Variational Quantum Eigensolver (VQE)** applied to a small Hamiltonian system.

The goal was to move beyond idealized simulations and incorporate realistic noise models to analyze algorithm robustness. This week forms the **core contribution** of the project.

---

## Problem Studied

- Hamiltonian: Two-qubit Hamiltonian with known exact ground-state energy  
- Objective: Quantitatively compare  
  - Exact ground-state energy  
  - Ideal (noise-free) VQE results  
  - Noisy VQE results  

---

## Methodology

### Ansatz Design

- A hardware-efficient, parameterized ansatz was used  
- Circuit depth was intentionally kept shallow to reduce noise sensitivity  

---

### Simulation Backends

- Ideal simulator (noise-free)  
- Noisy simulator using depolarizing noise channels  

Noise parameters were varied systematically to study error trends.

---

### Error and Performance Analysis

- Absolute energy error computed with respect to the exact solution  
- Generated visualizations:  
  - Bar plots comparing exact, ideal, and noisy energies  
  - Error growth plots as a function of increasing noise probabilities  

These analyses provide quantitative insight into how noise degrades VQE performance.

---

## Results

Representative results obtained:

- Exact Energy: −2.2360679  
- Ideal VQE Error: ~10⁻⁹  
- Noisy VQE Error: ~10⁻⁹ to 10⁻⁸ (depending on noise strength)  

Although the system size is small, the results clearly demonstrate:
- increasing error with increasing noise  
- relative robustness of shallow ansätze under mild noise  

---

## Limitations

- System size limited to two qubits  
- Simplified noise models (primarily depolarizing channels)  
- No error mitigation techniques applied  

These choices were made intentionally to maintain clarity and computational feasibility.

---

## Future Extensions

- Apply error mitigation techniques (e.g., measurement error mitigation, ZNE)  
- Extend analysis to larger Hamiltonians (e.g., Ising models)  
- Compare different ansatz structures under identical noise conditions  
- Benchmark against QAOA for similar problem sizes  

---

## Key Takeaways

- Gained hands-on experience with noise-aware quantum simulations  
- Developed intuition about VQE robustness on NISQ devices  
- Built a reproducible workflow combining theory, simulation, and analysis  
