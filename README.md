# qBraid Annealing Prototype

A proof‑of‑concept demonstrating how to integrate a quantum‑annealing workflow into a qBraid‑style cloud IDE.

---

## Why It Matters

- **Unlocks New Problem Classes**  
  Many real‑world challenges—portfolio optimization, scheduling, routing, Max‑Cut and beyond—map naturally to annealing/Ising formulations. Gate‑model alone can’t address them as directly.
- **Differentiates the Platform**  
  By adding annealing support alongside circuit‑based workflows, qBraid can claim true “all‑of‑quantum” coverage, standing out from competitors.
- **Seamless User Experience**  
  Users get one IDE, one account, and one Jobs panel for both circuit and annealing work. No context‑switching, no separate credentials.

---

## Demo Notebook

1. **Problem Definition** — build a graph (Max‑Cut example)  
2. **BQM Construction** — formulate as a Binary Quadratic Model  
3. **Job Submission** — run on a local (or real) annealer via D‑Wave Ocean SDK  
4. **Result Tracking & Visualization** — fetch the best solution and plot the cut  

<p align="center">
  <img src="https://raw.githubusercontent.com/mohitraosatya/qbraid-annealing-prototype/main/assets/demo.png" alt="Max‑Cut Demo" width="400"/>
</p>

---

## Getting Started

1. **Clone the repo**  
   ```bash
   git clone https://github.com/mohitraosatya/qbraid-annealing-prototype.git
   cd qbraid-annealing-prototype
