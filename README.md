# ⚛️ Quantum Hydrogen Simulation (VQE vs Classical)

Hybrid quantum-classical simulation of molecular hydrogen (H₂) using the Variational Quantum Eigensolver (VQE), with direct comparison to classical electronic structure methods.
<img src="assets/hydrogen_big_clean(1).gif" width="800">


## 🚀 Overview

This project investigates how **quantum algorithms can approximate the ground-state energy of hydrogen**, one of the most fundamental problems in quantum chemistry and energy science.

We combine:

- Classical electronic structure methods (Hartree–Fock)
- Variational quantum algorithms (VQE)
- Scientific visualization of convergence dynamics
- Conceptual connection to hydrogen evolution reaction (HER)

---

## 🔬 Scientific Motivation

Hydrogen is a key element in clean energy technologies, especially in:

- Hydrogen production (HER)
- Fuel cells
- Catalytic systems

Understanding the **electronic energy of H₂** is essential for modeling:

> H* + H* → H₂

This project bridges **quantum computing and catalysis**, providing a visual and computational interpretation of this process.

---

## ⚛️ Methodology

### Classical Reference
- Hartree–Fock (HF)
- Implemented via **PySCF**

### Quantum Approach
- Variational Quantum Eigensolver (VQE)
- Implemented using **PennyLane**
- Ansatz: `StronglyEntanglingLayers`
- Optimizer: Adam

### Simulation Pipeline

1. Define molecular system (H₂)
2. Compute classical ground-state energy (HF)
3. Construct quantum Hamiltonian
4. Optimize quantum circuit parameters (VQE)
5. Compare convergence behavior

---

## 📊 Key Results

- Quantum energy converges toward classical ground-state energy
- Error decreases across iterations
- Visual correlation between:
  - Molecular formation (H₂)
  - Energy minimization

---

## 🎬 Example Output

<p align="center">
  <img src="assets/preview.gif" width="700">
</p>

---

## 🧠 Key Insight

> Classical methods define the energy landscape.  
> Quantum algorithms learn it variationally.

---

## 📁 Project Structure
