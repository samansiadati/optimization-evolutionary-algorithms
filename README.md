# Optimization Techniques and Evolutionary Algorithms

## Companion Repository

This repository is a **study companion and practical implementation guide** for the book ***Optimization Techniques and Evolutionary Algorithms***.

The goal of this project is to bridge the gap between **optimization theory** and **practical algorithm implementation** by providing:

* Clear explanations of classical and modern optimization techniques
* Step-by-step derivations and pseudocode
* Python implementations from first principles
* Visualizations to understand convergence and behavior
* Original exercises with worked solutions

> 📌 **Important note**: This repository does **not** contain the book itself, nor does it reproduce copyrighted content. All explanations, code, and exercises are original and written as a learning aid.

---

## 🎯 Who This Repository Is For

This repo is designed for:

* Students learning **optimization, computational intelligence, or AI**
* Practitioners who want to **strengthen algorithmic and optimization foundations**
* Engineers preparing for **AI / ML algorithm-focused interviews**
* Researchers who want quick, runnable optimization algorithms and experiments

If you have ever thought *“I know models, but I want to understand how optimization works under the hood”*, this repository is for you.

---

## 🧠 Core Topics Covered

The repository follows a structure aligned with optimization and evolutionary algorithm curricula:

* **Classical Optimization** (gradient-based methods, convex optimization, linear/quadratic programming)
* **Derivative-Free Optimization** (hill climbing, Nelder–Mead, simulated annealing)
* **Evolutionary Algorithms** (genetic algorithms, genetic programming, differential evolution)
* **Swarm Intelligence** (particle swarm optimization, ant colony optimization)
* **Constraint Handling Techniques** (penalty methods, feasibility rules)
* **Performance Analysis & Benchmarking** (convergence plots, runtime analysis)

Each topic is treated with:

* Algorithmic rigor
* Computational intuition
* Practical relevance for real-world optimization problems

---

## 📂 Repository Structure

```text
optimization-evolutionary-algorithms/
│
├── README.md
├── LICENSE
├── requirements.txt
│
├── 01-classical-optimization/
│   ├── README.md
│   ├── gradient_descent.ipynb
│   ├── convex_optimization.ipynb
│   └── exercises.md
│
├── 02-derivative-free-optimization/
│   ├── hill_climbing.ipynb
│   ├── nelder_mead.ipynb
│   └── simulated_annealing.ipynb
│
├── 03-evolutionary-algorithms/
│   ├── genetic_algorithm.ipynb
│   ├── genetic_programming.ipynb
│   └── differential_evolution.ipynb
│
├── 04-swarm-intelligence/
│   ├── particle_swarm.ipynb
│   └── ant_colony.ipynb
│
├── 05-constraint-handling/
│   ├── penalty_methods.ipynb
│   └── feasibility_rules.ipynb
│
├── 06-performance-benchmarking/
│   ├── convergence_analysis.ipynb
│   └── runtime_analysis.ipynb
│
└── utils/
    └── plotting.py
