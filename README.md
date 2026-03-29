# 🚚 AI Vehicle Routing Optimization System

An AI-based optimization system designed to solve the Vehicle Routing Problem (VRP) for package delivery using advanced search algorithms.

---

## 📌 Overview
This project focuses on optimizing delivery routes for a fleet of vehicles by minimizing total travel distance while respecting constraints such as vehicle capacity and delivery priorities.

The system applies two powerful optimization techniques:
- Simulated Annealing
- Genetic Algorithm

---

## 🎯 Objectives
- Minimize total distance traveled by all vehicles
- Handle real-world constraints (vehicle capacity, package priority)
- Generate efficient and near-optimal delivery routes
- Compare performance between optimization algorithms

---

## 🧠 Key Features
- Custom fitness function combining:
  - Total Euclidean distance
  - Priority violation penalties
- Constraint handling:
  - Vehicle capacity limits
  - Unique package assignment
  - Soft priority enforcement
- Visualization of delivery routes using Matplotlib
- Support for multiple vehicles and large datasets

---

## ⚙️ Technologies Used
- Python
- Matplotlib
- Algorithms:
  - Simulated Annealing
  - Genetic Algorithm

---

## 📊 Results
The system achieved significant optimization improvements:

- Distance reduced from **5424 km → 3286 km**
- Penalty reduced from **612 → 53**

These results demonstrate the effectiveness of heuristic optimization in solving complex routing problems.

---

## 🧪 Example Output
- Optimized vehicle assignments
- Total distance and penalty calculation
- Graphical visualization of routes

---

## ▶️ How to Run
1. Prepare input file `packages.txt`
2. Run the script:
```bash
python main.py
