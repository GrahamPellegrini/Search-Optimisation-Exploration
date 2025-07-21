<h1 align="center">Search & Optimisation Exploration</h1>

<p align="center">
  <a href="https://www.um.edu.mt/courses/studyunit/CCE2503">
    <img src="https://img.shields.io/badge/University%20of%20Malta-CCE2503-blue?style=for-the-badge&logo=python&logoColor=white" alt="CCE2503 Course">
  </a>
  <a href="https://numpy.org/">
    <img src="https://img.shields.io/badge/Built%20with-NumPy-red?style=for-the-badge&logo=NumPy" alt="NumPy">
  </a>
  <a href="https://matplotlib.org/">
    <img src="https://img.shields.io/badge/Visualised%20with-Matplotlib-yellow?style=for-the-badge&logo=Plotly" alt="Matplotlib">
  </a>
</p>

<p align="center">
  Coursework for the study-unit <strong><a href="https://www.um.edu.mt/courses/studyunit/CCE2503">CCE2503 – Search and Optimisation</a></strong> at the University of Malta, supervised by <a href="https://www.um.edu.mt/profile/johannbriffa">Prof. Johann Briffa</a>.  
</p>

---

## 🚀 Overview

This repository explores **heuristic optimisation techniques** through the task of minimising the **Griewangk function**, a common test function in global optimisation with many local minima.

The notebook presents side-by-side implementations and evaluations of:

- **Gradient Descent**
- **Random Search**
- **Simulated Annealing**
- **Hybrid Methods**

The project aims to investigate:
- The comparative strengths and weaknesses of each algorithm
- Convergence speed and stability
- Visualisation of the search trajectory in 2D and 3D

---

## 📂 Repository Structure

```bash
.
├── labs/                      # Supplementary material and lab experiments
├── CCE2503_Assignment.ipynb   # Full exploration, implementation, analysis
├── CCE2503_Assignment.pdf     # Exported report of the notebook
└── README.md                  # This file
```

---

## 📊 Objective Function

The target function is the **Griewangk Function**:

\[
f(x) = 1 + \frac{1}{4000} \sum_{i=1}^{n} x_i^2 - \prod_{i=1}^{n} \cos\left(\frac{x_i}{\sqrt{i}}\right)
\]

- Global minimum at \( f(0,0,...,0) = 0 \)
- Known for its complex landscape and periodicity

---

## ⚙️ Tools Used

- Python 3.10+
- NumPy
- Matplotlib (for plotting search paths)
- Random module (custom implementations of randomness)

---

## 📊 Key Observations

- **Gradient Descent** converges rapidly near minima but is sensitive to local minima.
- **Random Search** provides diverse exploration but suffers from inefficiency.
- **Simulated Annealing** balances exploration and exploitation, with temperature tuning critical.
- **Hybrid Approaches** combining random and gradient-based steps showed superior convergence in some runs.

> 📌 Visualisations included demonstrate the strengths and pitfalls of each strategy.

---

## 📘 Report

The full technical report is available as a Jupyter notebook and exported PDF:
- [`CCE2503_Assignment.ipynb`](./CCE2503_Assignment.ipynb)
- [`CCE2503_Assignment.pdf`](./CCE2503_Assignment.pdf)

---

## 👨‍💼 Author

**Graham Pellegrini**  
B.Sc. (Hons.) Computer Engineering  
University of Malta  
GitHub: [@GrahamPellegrini](https://github.com/GrahamPellegrini)
