# Teaching — Data Structures & Algorithms (Python)

A cohesive, teaching-oriented repository for **Data Structures & Algorithms (DSA)** with Python.
The focus is on clean implementations, complexity analysis, and problem-solving patterns that translate to research and real applications.

> Prerequisite: basic Python (see [`teaching-python-programming`](https://github.com/JiashuoZh/teaching-python-programming)).

---

## 🎯 Learning Objectives
- Understand **core data structures** (arrays, linked lists, stacks, queues, hash tables, trees, graphs).
- Analyze **time & space complexity** and reason about trade-offs.
- Apply **algorithm design paradigms** (divide-and-conquer, greedy, dynamic programming, backtracking).
- Implement and benchmark **searching** and **sorting** routines.
- Solve real problems with readable, well-tested code.

---

## 📦 Repository Structure

> Click a module to jump to its folder (you can create folders as you go).

- **[01_dsa_intro/](./01_dsa_intro/)** — course overview, problem-solving mindset, Big-O/Ω/Θ, benchmarking conventions  
- **[02_linear_structures/](./02_linear_structures/)** — arrays, singly/doubly/circular linked lists, stacks, queues  
- **[03_strings_arrays/](./03_strings_arrays/)** — string manipulation, sliding window, two pointers, prefix sums  
- **[04_hash_tables/](./04_hash_tables/)** — hashing, Python dict/set internals, collision strategies  
- **[05_trees_binarytrees/](./05_trees_binarytrees/)** — tree basics, traversals (DFS/BFS), BST, height/balance  
- **[06_graphs/](./06_graphs/)** — graph representations, BFS/DFS, shortest-path (unweighted)  
- **[07_recursion_backtracking/](./07_recursion_backtracking/)** — recursion patterns, backtracking templates  
- **[08_sorting_searching/](./08_sorting_searching/)** — bubble/selection/insertion, merge/quick/heap sort; linear/binary search  
- **[09_advanced_structures/](./09_advanced_structures/)** — heaps & priority queues, tries, union-find/DSU  
- **[10_algorithm_design/](./10_algorithm_design/)** — greedy, dynamic programming, divide-and-conquer, memoization  
- **[11_case_studies/](./11_case_studies/)** — small projects: scheduling, pathfinding on grids, matching, mini-search engine

---

## 🧭 Module Map (teaching-first)

| Module | Key Outcomes | Primary Outputs |
|---|---|---|
| 01 Intro & Complexity | Express problems precisely; reason about Big-O; set up benchmarks | Intro notebook, complexity cheatsheet |
| 02 Linear Structures | Choose the right linear DS; implement and test | Implementations + unit tests |
| 03 Strings & Arrays | Master common patterns (sliding window, two pointers) | Pattern notebooks + practice set |
| 04 Hash Tables | Use/set up hashing; handle collisions; analyze avg/worst cases | Dict/set demos + perf comparison |
| 05 Trees & BST | Traverse trees; build/validate BST; reason about balance | Traversal visualizations |
| 06 Graphs | Model graphs; run BFS/DFS; reason about connectivity | Graph utilities + examples |
| 07 Recursion & Backtracking | Convert recursion to iteration; prune search space | Problem templates + solutions |
| 08 Sorting & Searching | Compare sort families; stability/in-place trade-offs | Timing harness + comparison table |
| 09 Advanced Structures | Apply heaps, tries, DSU to typical tasks | Implementations + use cases |
| 10 Design Paradigms | Greedy vs DP vs D&C; when and why | Worked examples + pseudocode |
| 11 Case Studies | Integrate DSA in end-to-end mini problems | Mini-projects with reports |

> Internally you can keep a private note mapping chapters from different books to these modules, but we **don’t expose book TOCs** here to keep the teaching logic clean.

---

## 🗂️ File Convention

Each module contains:
- `README.md` — goals, key ideas, pitfalls, and references  
- `*.py` and/or `*.ipynb` — implementations and demos  
- `tests/` — minimal `pytest` unit tests (where applicable)  
- `assets/` — small diagrams or visuals (optional)

Notebook pattern: **Objective → Approach → Implementation → Complexity → Tests → Reflection**.

---

## 🧪 Suggested Exercises (samples)

- Implement **singly & doubly linked lists** with iterators; compare operations vs Python list.  
- Build a **min-heap priority queue** and solve “merge k sorted lists”.  
- Write a **trie** and implement autocomplete with frequency ranking.  
- Compare **merge vs quicksort** on synthetic data; explain results beyond Big-O.  
- Implement **union-find (DSU)** and solve dynamic connectivity on a grid.  
- Use **sliding window** to find longest substring without repetition (string pattern mastery).  

---

## 🔬 Research/Teaching Hooks

- **Benchmarking**: micro-bench vs asymptotics (when Big-O hides constants).  
- **Data structure choice**: cache locality, Python object overhead, memory trade-offs.  
- **Fair comparison**: identical workloads, warm-ups, multiple trials, variance reporting.  
- **From DSA to ML**: heaps for top-k, tries for tokenization, graphs for BFS labeling, DP for sequence tasks.

---

## 🚀 How to Use

1. Read **01** for conventions and complexity.  
2. Work through **02 → 05 → 06** to cover core structures.  
3. Add **07 → 08 → 09** for algorithms and advanced DS.  
4. Consolidate in **10** (design paradigms) and **11** (case studies).  
5. Prefer **small, tested implementations** over large monoliths.

---

## 🔗 Cross-Repository Links

- Python fundamentals: [`teaching-python-programming`](https://github.com/JiashuoZh/teaching-python-programming)  
- Data analysis pipeline: [`teaching-data-analysis`](https://github.com/JiashuoZh/teaching-data-analysis)  
- Applied projects (EdX/Kaggle): [`applied-data-science`](https://github.com/JiashuoZh/applied-data-science)  
- Research drafts / preprints: [`research-preprints`](https://github.com/JiashuoZh/research-preprints)

---

## 📜 License

MIT License — academic and personal use permitted.

---

### Mini README template for each module (optional)

Create a `README.md` inside each module with:

```markdown
# Module <num>: <Title>

## Goals
- …

## Key Ideas
- …

## Implementation
- Files and brief notes

## Complexity
- Time / Space with short justification

## Tests
- How to run `pytest` or simple checks

## Reflection
- Pitfalls found, design choices, next steps
