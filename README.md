# 🛒 Shopping List Optimization Agent

A cost-aware shopping optimization tool that finds the cheapest way to fulfill a shopping list from multiple stores, minimizing both **product prices** and **travel expenses**. Built with a synthetic dataset simulating Ankara’s retail environment.

## ✅ Features

- Takes a **shopping list** and **starting location**
- Selects optimal stores for each item
- Calculates the **cheapest route**
- Visualizes the result with interactive graphs
- Implements four algorithms:
  - Genetic Algorithm (GA)
  - Simulated Annealing (SA)
  - Ant Colony Optimization (ACO)
  - A* Search

## 📦 Dataset

- 250 stores across 5 categories: Food, Electronics, Clothing, Cosmetics, Household
- ~450 unique products
- Prices and store locations randomly generated on a 100x100 grid

## 📊 Results Summary

| Algorithm | Total Cost (TL) | Product Cost | Travel Cost |
|-----------|------------------|--------------|-------------|
| GA        | **1978.26**      | 1583.98      | 394.28      |
| SA        | 2291.45          | 1814.39      | 477.06      |
| ACO       | 2343.19          | 1699.00      | 644.19      |
| A*        | 2809.45          | 1643.38      | 1166.07     |

→ **Genetic Algorithm (GA)** achieved the best cost optimization overall.

## 🖥 Demo

- GitHub: [ozgeisklar/yap441-proje](https://github.com/ozgeisklar/yap441-proje)
- YouTube: [Watch Demo Video](https://www.youtube.com/watch?v=WLLtAEICA1c)

---

© Özge Işıklar – TOBB ETU – YAP441 Final Project
