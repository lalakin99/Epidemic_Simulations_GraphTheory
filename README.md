# Epidemic Dynamics and Coloring Algorithms 
## Network Dynamics and Learning Project 3

## 📜 Project Overview
This repository contains my work for the third individual project in the "Network Dynamics and Learning" course at Politecnico di Torino (2023/2024). The project explores **epidemic dynamics**, **graph coloring problems**, and **game theory applications** in networked systems.

The main areas of study include:
1. Simulating SIR and SIRV models on various graph structures.
2. Analyzing real-world epidemics, including the H1N1 pandemic in Sweden.
3. Solving graph coloring problems for line graphs and Wi-Fi router interference using anti-coordination game theory.

---

## 🔍 Problem Breakdown

### **1. Epidemic Dynamics**
#### 1.1 SIR Model on a Symmetric k-Regular Graph
- Simulate an epidemic on a symmetric k-regular undirected graph with 500 nodes.
- Analyze the infection, recovery, and susceptible trends over time.

#### 1.2 Preferential Attachment Model Without Vaccination
- Simulate the SIR model on a preferential attachment graph with 500 nodes.
- Compare epidemic trends with those observed in k-regular graphs.

#### 1.3 Preferential Attachment Model With Vaccination
- Introduce a vaccination state and analyze its effect on epidemic spread.
- Observe how vaccination slows infection after a portion of the population is vaccinated weekly.

#### 1.4 H1N1 Pandemic in Sweden Simulation
- Simulate the 2009 H1N1 pandemic in Sweden using a SIRV model.
- Perform grid search to optimize hyperparameters (\( k \), \( \beta \), \( \rho \)) for best Root Mean Square Error (RMSE).

---

### **2. Coloring Algorithms**
#### 2.1 Coloring Problem on a Line Graph
- Apply a graph coloring algorithm to a line graph with 10 nodes.
- Optimize the potential function such that adjacent nodes have different colors.

#### 2.2 Wi-Fi Router Channel Assignment
- Simulate an anti-coordination game to assign optimal Wi-Fi channels to routers.
- Minimize interference by assigning different channels (colors) to adjacent nodes.

---

## 📂 Repository Contents
- **`HW3_Report.pdf`**: Full report detailing the problem descriptions, methods, and results.
- **`HW3_LalAkin.ipynb`**: Jupyter Notebook with Python code for all simulations.

---

## 🛠️ Tools and Techniques
The following tools and techniques were used in this project:
- **Python**:
  - `NetworkX`: For graph creation and analysis.
  - `NumPy`: For matrix computations and parameter configurations.
  - `Matplotlib`: For plotting simulation results and graph states.
- **Optimization**:
  - Grid search for hyperparameter tuning in epidemic simulations.
  - Potential function minimization for coloring problems.
- **Game Theory**: Anti-coordination games for solving real-world interference issues.

---

## 📊 Key Results
- **Epidemic Simulations**:
  - Found distinct differences between k-regular and preferential attachment graphs in terms of infection spread dynamics.
  - Vaccination significantly reduced infection rates in preferential attachment models.

- **Graph Coloring**:
  - Achieved zero potential for line graphs, optimizing node states to avoid conflicts.
  - Optimized Wi-Fi channel assignment for routers with near-zero potential.
