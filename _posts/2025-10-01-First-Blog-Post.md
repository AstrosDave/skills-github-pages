---
title: "When Classical Meets Quantum: Simulating Spin Dynamics on IBM Quantum"
date: 2025-10-01
author: "David Menezes"
tags: [Quantum Computing, Physics, Simulation, Research, UConn]
---

### ⚛️ Background

During my undergraduate research with **Dr. Lea F. Santos** at the **University of Connecticut**, I explored an exciting question:  
How well can we simulate **quantum dynamics** on both **classical** and **quantum** computers?

The system of interest was a **spin-½ chain** — a one-dimensional model where particles interact magnetically.  
Though simple in theory, its dynamics quickly become computationally intensive as the number of spins increases.

---

### 💻 The Project

We began by implementing the spin chain’s time evolution on classical computers using **Python**.  
This involved solving Schrödinger’s equation numerically, analyzing how excitations (spin flips) propagate through the lattice.

Next, we ported the same simulation to the **IBM Quantum** platform, using quantum circuits to represent the spin interactions.  
By comparing results from both platforms, we could visualize how **quantum noise, gate fidelity, and decoherence** affect accuracy.

---

### 🧠 Key Insights

- **Classical simulations** are more precise for small systems but scale exponentially in cost.  
- **Quantum simulations** are inherently noisy but **scale linearly**, making them promising for larger, more complex systems.  
- The transition from one to the other isn’t just a hardware shift — it’s a **paradigm shift** in how we compute.

Working on this project gave me hands-on experience with:

- **Quantum circuit design** on IBM Quantum  
- **Time evolution operators** and matrix exponentiation  
- Comparing **numerical vs. experimental quantum results**  

---

### 🔮 Reflections

This project bridged my interests in **theoretical physics and computational methods**.  
It taught me that the future of science lies not only in discovering new equations but in **teaching machines how to understand them**.

Our results were later included in the publication:  
> *Santos, L. F., et al. (2023). “Quantum Dynamics on Classical and Quantum Computers.”*

---

*“To simulate the quantum world is to understand its rules — and to stretch the limits of what computation can mean.”*
