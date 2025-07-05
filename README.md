# Coloring-Graph

# Operational Research – Lab Reports 1 to 4

This repository contains the implementation and analysis of four core combinatorial optimization problems, solved using Integer Linear Programming (ILP) in **Mosel (FICO Xpress)**.

Authors:
- Ehsan Soltanmohammadloo – ID: 327039  
- Fatemeh Sangin – ID: 329999  

## 📘 Included Labs

### 🟢 Lab 1: Graph Coloring
- Objective: Assign the minimum number of colors to graph nodes so that adjacent nodes have different colors.
- Applications: Scheduling, register allocation, wireless frequency planning.
- Implementation: ILP model using binary variables for color assignment, tested on random graphs with varying edge densities.

### 🔵 Lab 2: Maximum Clique
- Objective: Identify the largest subset of mutually connected vertices (clique).
- Applications: Social networks, bioinformatics, clustering.
- Implementation: Binary ILP model tested across multiple random graphs (N=20–60, p=0.1–0.5), with comparison to theoretical expectations.

### 🟡 Lab 3: Maximum Weighted Independent Set (MWIS)
- Objective: Select a set of non-adjacent nodes with maximum total weight.
- Applications: Network design, facility placement, scheduling.
- Features: Comparison of random vs. uniform weights, and analysis of edge probability and graph size effects.

### 🔴 Lab 4: Frequency Assignment Problem (FAP)
- Objective: Assign frequencies to transmitter nodes to avoid interference, while minimizing spectrum width.
- Constraints: Adjacent nodes must use frequencies differing by at least 2.
- Analysis: Original vs. enhanced implementation with randomized graphs (N=20–60), edge probability p=0.2/0.4.

## 🧠 Tools & Environment
- Language: [Mosel](https://www.fico.com/en/products/fico-xpress-optimization) (FICO Xpress)
- Approach: Integer Linear Programming (ILP)
- Test Cases: Randomly generated graphs with parameterized control

## 📊 Key Outcomes
- Validation of theoretical expectations through empirical results
- Use of advanced ILP modeling techniques in Mosel
- Demonstration of how graph parameters affect solution quality and complexity

## 📁 File Structure
- `lab1,2,3,4.pdf`: Full report with problem formulations, Mosel code, results, and analysis.
- `mosel_code/`: (Optional) If you add raw `.mos` source files here.
- `figures/`: (Optional) Graph screenshots or plots used in the report.

---

> This repository showcases practical applications of OR theory using real modeling and solution environments. Ideal for students and researchers interested in combinatorial optimization and ILP modeling.
