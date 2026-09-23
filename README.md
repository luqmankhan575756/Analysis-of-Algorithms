# Analysis-of-Algorithms : 

A comprehensive repository dedicated to the design, implementation, and asymptotic complexity analysis of fundamental computer science algorithms and data structures.

---------

## 📌 Repository Overview

This repository contains clean, modular implementations of core algorithmic paradigms, complete with mathematical breakdowns, recurrence relations, and empirical runtime comparisons.

**Key areas covered:**

- **Asymptotic Analysis** — Big-O (O), Big-Omega (Ω), and Big-Theta (Θ) characterizations
- **Divide and Conquer** — Breaking problems into independent subproblems
- **Dynamic Programming** — Optimal substructure and overlapping subproblems
- **Greedy Algorithms** — Locally optimal choices leading to global solutions
- **Graph Algorithms** — Traversals, shortest paths, and minimum spanning trees
- **Backtracking & Branch-and-Bound** — Systematic search space exploration

---

## 📂 Directory Structure

```text
├── 01-divide-and-conquer/
│   ├── merge_sort/
│   ├── quick_sort/
│   └── binary_search/
├── 02-dynamic-programming/
│   ├── 01_knapsack/
│   ├── longest_common_subsequence/
│   └── matrix_chain_multiplication/
├── 03-greedy-methods/
│   ├── fractional_knapsack/
│   ├── huffman_coding/
│   └── activity_selection/
├── 04-graph-algorithms/
│   ├── bfs_dfs/
│   ├── dijkstra/
│   ├── bellman_ford/
│   ├── kruskal_mst/
│   └── prim_mst/
├── 05-backtracking/
│   ├── n_queens/
│   └── subset_sum/
├── benchmarks/
│   └── runtime_comparison.py
├── docs/
│   └── complexity_cheatsheet.md
├── LICENSE
└── README.md
```

---

## 🚀 Getting Started

### Prerequisites

- Python 3.9+ (or your language of choice, if implementations are ported)
- `pip` for dependency management

### Installation

```bash
git clone https://github.com/<your-username>/analysis-of-algorithms.git
cd analysis-of-algorithms
pip install -r requirements.txt
```

### Running an Algorithm

```bash
python 01-divide-and-conquer/merge_sort/merge_sort.py
```

### Running Benchmarks

```bash
python benchmarks/runtime_comparison.py
```

---

## 📊 Complexity Reference

| Algorithm | Best Case | Average Case | Worst Case | Space |
|---|---|---|---|---|
| Merge Sort | Ω(n log n) | Θ(n log n) | O(n log n) | O(n) |
| Quick Sort | Ω(n log n) | Θ(n log n) | O(n²) | O(log n) |
| Binary Search | Ω(1) | Θ(log n) | O(log n) | O(1) |
| 0/1 Knapsack (DP) | — | Θ(nW) | O(nW) | O(nW) |
| Dijkstra (Min-Heap) | — | Θ((V+E) log V) | O((V+E) log V) | O(V) |
| Bellman-Ford | — | Θ(VE) | O(VE) | O(V) |
| Kruskal's MST | — | Θ(E log E) | O(E log E) | O(V) |
| N-Queens (Backtracking) | — | — | O(N!) | O(N) |

> See [`docs/complexity_cheatsheet.md`](docs/complexity_cheatsheet.md) for full derivations and recurrence relations.

---

## 🧩 Topics Breakdown

<details>
<summary><b>01. Divide and Conquer</b></summary>

- Merge Sort
- Quick Sort
- Binary Search

</details>

<details>
<summary><b>02. Dynamic Programming</b></summary>

- 0/1 Knapsack
- Longest Common Subsequence (LCS)
- Matrix Chain Multiplication

</details>

<details>
<summary><b>03. Greedy Methods</b></summary>

- Fractional Knapsack
- Huffman Coding
- Activity Selection

</details>

<details>
<summary><b>04. Graph Algorithms</b></summary>

- BFS / DFS Traversals
- Dijkstra's Shortest Path
- Bellman-Ford Algorithm
- Kruskal's Minimum Spanning Tree
- Prim's Minimum Spanning Tree

</details>

<details>
<summary><b>05. Backtracking</b></summary>

- N-Queens Problem
- Subset Sum Problem

</details>

---

## 🤝 Contributing

Contributions are welcome! To contribute:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/algorithm-name`)
3. Commit your changes with clear messages
4. Push to your branch and open a Pull Request

Please ensure new algorithms include:
- A clean, commented implementation
- A short complexity analysis (time & space)
- Test cases where applicable

---

## 📄 License

This project is licensed under the terms of the [LICENSE](LICENSE) file included in this repository.

---

## ⭐ Acknowledgements

Built as a study companion for coursework in the **Design and Analysis of Algorithms (DAA)**, consolidating theory with practical, runnable code.
