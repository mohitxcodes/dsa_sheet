# Graph Mastery Sheet — LeetCode + GFG

## Level 1 — Foundations: Graph Representation & Basic Traversals

**Goal:** Understand adjacency list/matrix representations, and master DFS and BFS on graphs — the two fundamental traversals that every graph problem builds upon.

| Difficulty | Platform | Q.No | Question                                    | Link                                                                                |
| ---------- | -------- | ---- | ------------------------------------------- | ----------------------------------------------------------------------------------- |
| Easy       | GFG      | G1   | Graph Representation (Adjacency List)       | https://www.geeksforgeeks.org/problems/print-adjacency-list-1587115620/1            |
| Easy       | GFG      | G2   | BFS of Graph                                | https://www.geeksforgeeks.org/problems/bfs-traversal-of-graph/1                     |
| Easy       | GFG      | G3   | DFS of Graph                                | https://www.geeksforgeeks.org/problems/depth-first-traversal-for-a-graph/1          |
| Medium     | LeetCode | 133  | Clone Graph                                 | https://leetcode.com/problems/clone-graph/                                          |
| Medium     | LeetCode | 547  | Number of Provinces                         | https://leetcode.com/problems/number-of-provinces/                                  |
| Medium     | GFG      | G4   | Number of Provinces                         | https://www.geeksforgeeks.org/problems/number-of-provinces/1                        |
| Medium     | LeetCode | 200  | Number of Islands                           | https://leetcode.com/problems/number-of-islands/                                    |
| Medium     | GFG      | G5   | Find the Number of Islands                  | https://www.geeksforgeeks.org/problems/find-the-number-of-islands/1                 |
| Easy       | LeetCode | 733  | Flood Fill                                  | https://leetcode.com/problems/flood-fill/                                           |
| Medium     | LeetCode | 994  | Rotting Oranges                             | https://leetcode.com/problems/rotting-oranges/                                      |
| Medium     | GFG      | G6   | Rotten Oranges                              | https://www.geeksforgeeks.org/problems/rotten-oranges2536/1                         |
| Medium     | LeetCode | 542  | 01 Matrix                                   | https://leetcode.com/problems/01-matrix/                                            |
| Medium     | LeetCode | 130  | Surrounded Regions                          | https://leetcode.com/problems/surrounded-regions/                                   |
| Medium     | LeetCode | 1020 | Number of Enclaves                          | https://leetcode.com/problems/number-of-enclaves/                                   |

---

## Level 2 — Cycle Detection

**Goal:** Detecting cycles is a fundamental graph primitive — it's the basis for deadlock detection, dependency validation, and topological sorting. Learn cycle detection in both directed and undirected graphs using DFS and BFS (Kahn's).

| Difficulty | Platform | Q.No | Question                                     | Link                                                                                |
| ---------- | -------- | ---- | -------------------------------------------- | ----------------------------------------------------------------------------------- |
| Medium     | GFG      | G7   | Detect Cycle in an Undirected Graph (BFS)    | https://www.geeksforgeeks.org/problems/detect-cycle-in-an-undirected-graph/1        |
| Medium     | GFG      | G8   | Detect Cycle in an Undirected Graph (DFS)    | https://www.geeksforgeeks.org/problems/detect-cycle-in-an-undirected-graph/1        |
| Medium     | LeetCode | 684  | Redundant Connection                         | https://leetcode.com/problems/redundant-connection/                                 |
| Medium     | GFG      | G9   | Detect Cycle in a Directed Graph (DFS)       | https://www.geeksforgeeks.org/problems/detect-cycle-in-a-directed-graph/1           |
| Medium     | GFG      | G10  | Detect Cycle in a Directed Graph (BFS/Kahn's) | https://www.geeksforgeeks.org/problems/detect-cycle-in-a-directed-graph/1         |
| Medium     | LeetCode | 207  | Course Schedule                              | https://leetcode.com/problems/course-schedule/                                      |
| Medium     | LeetCode | 802  | Find Eventual Safe States                    | https://leetcode.com/problems/find-eventual-safe-states/                            |
| Medium     | GFG      | G11  | Find Eventual Safe States                    | https://www.geeksforgeeks.org/problems/eventual-safe-states/1                       |

---

## Level 3 — Topological Sort

**Goal:** Topological sort orders nodes so that every directed edge goes from earlier to later — essential for task scheduling, build systems, and prerequisite chains. Master both DFS (reverse postorder) and BFS (Kahn's algorithm).

| Difficulty | Platform | Q.No | Question                                    | Link                                                                             |
| ---------- | -------- | ---- | ------------------------------------------- | -------------------------------------------------------------------------------- |
| Medium     | GFG      | G12  | Topological Sort (DFS)                      | https://www.geeksforgeeks.org/problems/topological-sort/1                        |
| Medium     | GFG      | G13  | Topological Sort (BFS — Kahn's Algorithm)   | https://www.geeksforgeeks.org/problems/topological-sort/1                        |
| Medium     | LeetCode | 210  | Course Schedule II                          | https://leetcode.com/problems/course-schedule-ii/                                |
| Medium     | GFG      | G14  | Course Schedule                             | https://www.geeksforgeeks.org/problems/course-schedule/1                         |
| Hard       | LeetCode | 269  | Alien Dictionary                            | https://leetcode.com/problems/alien-dictionary/                                  |
| Hard       | GFG      | G15  | Alien Dictionary                            | https://www.geeksforgeeks.org/problems/alien-dictionary/1                        |
| Medium     | LeetCode | 1557 | Minimum Number of Vertices to Reach All     | https://leetcode.com/problems/minimum-number-of-vertices-to-reach-all-nodes/     |
| Hard       | LeetCode | 2115 | Find All Possible Recipes from Given Supplies | https://leetcode.com/problems/find-all-possible-recipes-from-given-supplies/   |
| Medium     | LeetCode | 310  | Minimum Height Trees                        | https://leetcode.com/problems/minimum-height-trees/                              |

---

## Level 4 — Shortest Path Algorithms

**Goal:** Master the four core shortest-path algorithms — BFS (unweighted), Dijkstra (non-negative weights), Bellman-Ford (negative weights), and Floyd-Warshall (all-pairs). Each has its sweet spot.

| Difficulty | Platform | Q.No | Question                                              | Link                                                                                      |
| ---------- | -------- | ---- | ----------------------------------------------------- | ----------------------------------------------------------------------------------------- |
| Medium     | LeetCode | 1091 | Shortest Path in Binary Matrix _(BFS)_                | https://leetcode.com/problems/shortest-path-in-binary-matrix/                             |
| Medium     | GFG      | G16  | Shortest Path in Undirected Graph (Unit Weights)      | https://www.geeksforgeeks.org/problems/shortest-path-in-undirected-graph-having-unit-distance/1 |
| Medium     | GFG      | G17  | Shortest Path in DAG                                  | https://www.geeksforgeeks.org/problems/shortest-path-in-undirected-graph/1                |
| Medium     | GFG      | G18  | Dijkstra's Algorithm                                  | https://www.geeksforgeeks.org/problems/implementing-dijkstra-set-1-adjacency-matrix/1     |
| Medium     | LeetCode | 743  | Network Delay Time _(Dijkstra)_                       | https://leetcode.com/problems/network-delay-time/                                         |
| Medium     | LeetCode | 1631 | Path With Minimum Effort                              | https://leetcode.com/problems/path-with-minimum-effort/                                   |
| Medium     | LeetCode | 787  | Cheapest Flights Within K Stops                       | https://leetcode.com/problems/cheapest-flights-within-k-stops/                            |
| Medium     | GFG      | G19  | Bellman-Ford Algorithm                                | https://www.geeksforgeeks.org/problems/distance-from-the-source-bellman-ford-algorithm/1  |
| Medium     | LeetCode | 1514 | Path with Maximum Probability                         | https://leetcode.com/problems/path-with-maximum-probability/                              |
| Medium     | GFG      | G20  | Floyd Warshall Algorithm                              | https://www.geeksforgeeks.org/problems/implementing-floyd-warshall2042/1                  |
| Hard       | LeetCode | 778  | Swim in Rising Water                                  | https://leetcode.com/problems/swim-in-rising-water/                                       |
| Hard       | LeetCode | 1293 | Shortest Path in Grid with Obstacles Elimination      | https://leetcode.com/problems/shortest-path-in-a-grid-with-obstacles-elimination/         |
| Medium     | LeetCode | 1334 | Find the City With Smallest Number of Neighbors       | https://leetcode.com/problems/find-the-city-with-the-smallest-number-of-neighbors-at-a-threshold-distance/ |
| Hard       | LeetCode | 2290 | Minimum Obstacle Removal to Reach Corner              | https://leetcode.com/problems/minimum-obstacle-removal-to-reach-corner/                   |

---

## Level 5 — Disjoint Set Union (Union-Find)

**Goal:** Union-Find is the fastest way to handle dynamic connectivity queries — "are these two nodes connected?" and "merge these two groups." It powers Kruskal's MST, accounts merge, and redundant connection detection.

| Difficulty | Platform | Q.No | Question                                          | Link                                                                                |
| ---------- | -------- | ---- | ------------------------------------------------- | ----------------------------------------------------------------------------------- |
| Medium     | GFG      | G21  | Disjoint Set (Union-Find)                         | https://www.geeksforgeeks.org/problems/disjoint-set-union-find/1                    |
| Medium     | LeetCode | 684  | Redundant Connection                              | https://leetcode.com/problems/redundant-connection/                                 |
| Medium     | LeetCode | 547  | Number of Provinces _(Union-Find)_                | https://leetcode.com/problems/number-of-provinces/                                  |
| Medium     | LeetCode | 721  | Accounts Merge                                    | https://leetcode.com/problems/accounts-merge/                                       |
| Medium     | LeetCode | 1319 | Number of Operations to Make Network Connected    | https://leetcode.com/problems/number-of-operations-to-make-network-connected/       |
| Medium     | GFG      | G22  | Number of Operations to Make Network Connected    | https://www.geeksforgeeks.org/problems/connecting-the-graph/1                       |
| Hard       | LeetCode | 128  | Longest Consecutive Sequence _(Union-Find)_       | https://leetcode.com/problems/longest-consecutive-sequence/                         |
| Hard       | LeetCode | 839  | Similar String Groups                             | https://leetcode.com/problems/similar-string-groups/                                |
| Medium     | LeetCode | 990  | Satisfiability of Equality Equations              | https://leetcode.com/problems/satisfiability-of-equality-equations/                 |
| Hard       | LeetCode | 1632 | Rank Transform of a Matrix                        | https://leetcode.com/problems/rank-transform-of-a-matrix/                           |
| Medium     | LeetCode | 1061 | Lexicographically Smallest Equivalent String      | https://leetcode.com/problems/lexicographically-smallest-equivalent-string/         |

---

## Level 6 — Minimum Spanning Tree (MST)

**Goal:** MST finds the cheapest way to connect all nodes. Master both Kruskal's (Union-Find based, sort edges) and Prim's (priority queue based, grow tree).

| Difficulty | Platform | Q.No | Question                                     | Link                                                                             |
| ---------- | -------- | ---- | -------------------------------------------- | -------------------------------------------------------------------------------- |
| Medium     | GFG      | G23  | Minimum Spanning Tree (Prim's)               | https://www.geeksforgeeks.org/problems/minimum-spanning-tree/1                   |
| Medium     | GFG      | G24  | Minimum Spanning Tree (Kruskal's)            | https://www.geeksforgeeks.org/problems/minimum-spanning-tree/1                   |
| Medium     | LeetCode | 1584 | Min Cost to Connect All Points               | https://leetcode.com/problems/min-cost-to-connect-all-points/                    |
| Hard       | LeetCode | 1489 | Find Critical and Pseudo-Critical Edges in MST | https://leetcode.com/problems/find-critical-and-pseudo-critical-edges-in-minimum-spanning-tree/ |
| Hard       | LeetCode | 1135 | Connecting Cities With Minimum Cost          | https://leetcode.com/problems/connecting-cities-with-minimum-cost/               |
| Medium     | GFG      | G25  | Number of Islands _(Union-Find / MST)_       | https://www.geeksforgeeks.org/problems/number-of-islands/1                       |

---

## Level 7 — Bipartite Graph & Graph Coloring

**Goal:** Bipartite checking (2-coloring) is a clean application of BFS/DFS. It appears in matching problems, scheduling, and conflict detection.

| Difficulty | Platform | Q.No | Question                                  | Link                                                                         |
| ---------- | -------- | ---- | ----------------------------------------- | ---------------------------------------------------------------------------- |
| Medium     | LeetCode | 785  | Is Graph Bipartite?                       | https://leetcode.com/problems/is-graph-bipartite/                            |
| Medium     | GFG      | G26  | Bipartite Graph                           | https://www.geeksforgeeks.org/problems/bipartite-graph/1                     |
| Medium     | LeetCode | 886  | Possible Bipartition                      | https://leetcode.com/problems/possible-bipartition/                          |
| Medium     | GFG      | G27  | M-Coloring Problem                        | https://www.geeksforgeeks.org/problems/m-coloring-problem-1587115620/1       |
| Hard       | LeetCode | 1203 | Sort Items by Groups Respecting Dependencies | https://leetcode.com/problems/sort-items-by-groups-respecting-dependencies/ |

---

## Level 8 — Strongly Connected Components & Bridges

**Goal:** Advanced graph decomposition — find SCCs (Kosaraju's/Tarjan's), bridges, and articulation points. These are crucial for understanding graph structure and network reliability.

| Difficulty | Platform | Q.No | Question                                       | Link                                                                                |
| ---------- | -------- | ---- | ---------------------------------------------- | ----------------------------------------------------------------------------------- |
| Medium     | GFG      | G28  | Kosaraju's Algorithm (SCC)                     | https://www.geeksforgeeks.org/problems/strongly-connected-components-kosarajus-algo/1 |
| Hard       | LeetCode | 1192 | Critical Connections in a Network _(Bridges)_  | https://leetcode.com/problems/critical-connections-in-a-network/                    |
| Medium     | GFG      | G29  | Bridges in a Graph                             | https://www.geeksforgeeks.org/problems/bridge-edge-in-graph/1                       |
| Medium     | GFG      | G30  | Articulation Point                             | https://www.geeksforgeeks.org/problems/articulation-point-1/1                       |
| Hard       | LeetCode | 928  | Minimize Malware Spread II                     | https://leetcode.com/problems/minimize-malware-spread-ii/                           |
| Medium     | GFG      | G31  | Tarjan's Algorithm (SCC)                       | https://www.geeksforgeeks.org/problems/strongly-connected-component-tarjans-algo-1587115621/1 |

---

## Level 9 — Euler & Hamiltonian Paths, Advanced Problems

**Goal:** Eulerian paths visit every _edge_ once; Hamiltonian paths visit every _node_ once. These are niche but appear in puzzle-style interview problems and competitive programming.

| Difficulty | Platform | Q.No | Question                                   | Link                                                                                   |
| ---------- | -------- | ---- | ------------------------------------------ | -------------------------------------------------------------------------------------- |
| Hard       | LeetCode | 332  | Reconstruct Itinerary _(Euler path)_       | https://leetcode.com/problems/reconstruct-itinerary/                                   |
| Medium     | GFG      | G32  | Euler Circuit and Path                     | https://www.geeksforgeeks.org/problems/euler-circuit-and-path/1                        |
| Hard       | LeetCode | 753  | Cracking the Safe                          | https://leetcode.com/problems/cracking-the-safe/                                       |
| Hard       | LeetCode | 2097 | Valid Arrangement of Pairs                 | https://leetcode.com/problems/valid-arrangement-of-pairs/                              |

---

## Level 10 — Multi-Source BFS, 0-1 BFS & Advanced Shortest Path

**Goal:** Advanced BFS patterns — multi-source BFS starts from multiple nodes simultaneously, 0-1 BFS handles binary-weight graphs with a deque, and state-space BFS encodes complex states.

| Difficulty | Platform | Q.No | Question                                          | Link                                                                                      |
| ---------- | -------- | ---- | ------------------------------------------------- | ----------------------------------------------------------------------------------------- |
| Medium     | LeetCode | 1162 | As Far from Land as Possible _(multi-source)_     | https://leetcode.com/problems/as-far-from-land-as-possible/                               |
| Hard       | LeetCode | 127  | Word Ladder _(BFS state-space)_                   | https://leetcode.com/problems/word-ladder/                                                |
| Hard       | LeetCode | 847  | Shortest Path Visiting All Nodes _(bitmask BFS)_  | https://leetcode.com/problems/shortest-path-visiting-all-nodes/                           |
| Hard       | LeetCode | 864  | Shortest Path to Get All Keys                     | https://leetcode.com/problems/shortest-path-to-get-all-keys/                              |
| Hard       | LeetCode | 1263 | Minimum Moves to Move a Box to Target             | https://leetcode.com/problems/minimum-moves-to-move-a-box-to-their-target-location/       |
| Hard       | GFG      | G33  | Word Ladder II                                    | https://www.geeksforgeeks.org/problems/word-ladder-ii/1                                   |
| Hard       | LeetCode | 1210 | Minimum Moves to Reach Target with Rotations      | https://leetcode.com/problems/minimum-moves-to-reach-target-with-rotations/               |

---

## Level 11 — Graph DP & Hard / Expert Problems

**Goal:** The hardest graph problems — combining graph traversal with dynamic programming, bitmask DP, or advanced optimization. These are the ceiling for graph problems in interviews and competitive programming.

| Difficulty | Platform | Q.No | Question                                          | Link                                                                                |
| ---------- | -------- | ---- | ------------------------------------------------- | ----------------------------------------------------------------------------------- |
| Hard       | LeetCode | 943  | Find the Shortest Superstring _(bitmask DP)_      | https://leetcode.com/problems/find-the-shortest-superstring/                        |
| Hard       | LeetCode | 1494 | Parallel Courses II _(bitmask DP)_                | https://leetcode.com/problems/parallel-courses-ii/                                  |
| Hard       | LeetCode | 834  | Sum of Distances in Tree _(re-rooting DP)_        | https://leetcode.com/problems/sum-of-distances-in-tree/                             |
| Medium     | LeetCode | 1466 | Reorder Routes to Make All Paths Lead to City Zero | https://leetcode.com/problems/reorder-routes-to-make-all-paths-lead-to-the-city-zero/ |
| Hard       | LeetCode | 2246 | Longest Path With Different Adjacent Characters   | https://leetcode.com/problems/longest-path-with-different-adjacent-characters/       |
| Hard       | LeetCode | 1349 | Maximum Students Taking Exam                      | https://leetcode.com/problems/maximum-students-taking-exam/                         |
| Hard       | GFG      | G34  | Longest Path in a DAG                             | https://www.geeksforgeeks.org/problems/longest-path-in-a-dag/1                      |
| Medium     | LeetCode | 399  | Evaluate Division                                 | https://leetcode.com/problems/evaluate-division/                                    |
| Hard       | LeetCode | 329  | Longest Increasing Path in a Matrix               | https://leetcode.com/problems/longest-increasing-path-in-a-matrix/                  |
| Hard       | GFG      | G35  | Negative Weight Cycle Detection                   | https://www.geeksforgeeks.org/problems/negative-weight-cycle3504/1                  |

---

_This is a curated, hand-picked progression rather than a literal "every question that exists" list — the goal is depth and pattern-recognition, not volume. Mastering everything above will comfortably cover Graphs for interviews at any level._
