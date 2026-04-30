# smart-root-planner
 Smart Route Planner

 Project Description

The **Smart Route Planner** is a C-based project that demonstrates the use of two important algorithm design techniques:

* Greedy Algorithm** → Dijkstra’s Algorithm
* Dynamic Programming (DP)** → Floyd Warshall Algorithm

The project helps in finding the **shortest path between cities/nodes** in a graph.


 Objectives

* To understand and implement **Greedy and Dynamic Programming algorithms**
* To compare **single-source vs all-pairs shortest path**
* To build a simple and efficient **menu-driven application**

 Algorithms Used

 1. Dijkstra Algorithm (Greedy)

* Finds shortest path from a **single source**
* Selects the nearest node at each step
* Time Complexity: **O(V²)**

2. Floyd Warshall Algorithm (Dynamic Programming)

* Finds shortest paths between **all pairs of vertices**
* Uses intermediate nodes for optimization
* Time Complexity: **O(V³)**

 Features

* Menu-driven program
* User input for graph (adjacency matrix)
* Supports both algorithms in a single program
* Displays shortest distances clearly

Folder Structure

Smart-Route-Planner/
│
├── src/
│   └── main.c
│
├── input/
├── output/
└── README.md


 How to Run

 Step 1: Open terminal in `src` folder

```bash
cd src
```

Step 2: Compile

```bash
gcc main.c -o main
```

Step 3: Run

```bash
.\main.exe
```

Sample Input

4
0 5 0 10
0 0 3 0
0 0 0 1
0 0 0 0


 Sample Output
===== MENU =====
1. Dijkstra (Greedy)
2. Floyd Warshall (DP)
3. Exit

Comparison

| Feature    | Dijkstra (Greedy) | Floyd Warshall (DP) |
| ---------- | ----------------- | ------------------- |
| Type       | Greedy            | Dynamic Programming |
| Output     | Single Source     | All Pairs           |
| Complexity | O(V²)             | O(V³)               |

 
 Applications
* GPS Navigation Systems
* Network Routing
* Traffic Management Systems

 Conclusion

This project successfully demonstrates how different algorithmic approaches can be used to solve shortest path problems efficiently.


