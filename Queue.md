# Queue Mastery Sheet — LeetCode + GFG

## Level 1 — Foundations: Basic Queue Operations & Variants

**Goal:** Understand FIFO behavior, implement queues from scratch (array, linked list, circular), and learn the key variants — Deque, Circular Queue, and Priority Queue. These are the building blocks for everything that follows.

| Difficulty | Platform | Q.No | Question                                 | Link                                                                              |
| ---------- | -------- | ---- | ---------------------------------------- | --------------------------------------------------------------------------------- |
| Easy       | GFG      | G1   | Implement Queue Using Array              | https://www.geeksforgeeks.org/problems/implement-queue-using-array/1               |
| Easy       | GFG      | G2   | Implement Queue Using Linked List        | https://www.geeksforgeeks.org/problems/implement-queue-using-linked-list/1         |
| Easy       | LeetCode | 232  | Implement Queue Using Stacks             | https://leetcode.com/problems/implement-queue-using-stacks/                       |
| Easy       | GFG      | G3   | Queue Using Two Stacks                   | https://www.geeksforgeeks.org/problems/queue-using-two-stacks/1                   |
| Medium     | LeetCode | 622  | Design Circular Queue                    | https://leetcode.com/problems/design-circular-queue/                              |
| Medium     | LeetCode | 641  | Design Circular Deque                    | https://leetcode.com/problems/design-circular-deque/                              |
| Easy       | GFG      | G4   | Reverse a Queue                          | https://www.geeksforgeeks.org/problems/queue-reversal/1                           |
| Easy       | GFG      | G5   | Reverse First K Elements of Queue        | https://www.geeksforgeeks.org/problems/reverse-first-k-elements-of-queue/1        |
| Easy       | GFG      | G6   | Generate Binary Numbers from 1 to N      | https://www.geeksforgeeks.org/problems/generate-binary-numbers-1587115620/1       |
| Easy       | LeetCode | 933  | Number of Recent Calls                   | https://leetcode.com/problems/number-of-recent-calls/                             |
| Medium     | GFG      | G7   | Interleave the First Half with Second    | https://www.geeksforgeeks.org/problems/interleave-the-first-half-of-the-queue-with-second-half/1 |

---

## Level 2 — BFS (Breadth-First Search) Using Queue

**Goal:** BFS is _the_ canonical application of queues. Every level-order traversal, shortest path in unweighted graph, and flood-fill uses a queue. This is where queues become a serious problem-solving tool.

| Difficulty | Platform | Q.No | Question                                    | Link                                                                               |
| ---------- | -------- | ---- | ------------------------------------------- | ---------------------------------------------------------------------------------- |
| Easy       | LeetCode | 733  | Flood Fill                                  | https://leetcode.com/problems/flood-fill/                                          |
| Easy       | GFG      | G8   | Flood Fill Algorithm                        | https://www.geeksforgeeks.org/problems/flood-fill-algorithm1856/1                  |
| Medium     | LeetCode | 994  | Rotting Oranges                             | https://leetcode.com/problems/rotting-oranges/                                     |
| Medium     | GFG      | G9   | Rotten Oranges                              | https://www.geeksforgeeks.org/problems/rotten-oranges2536/1                        |
| Medium     | LeetCode | 542  | 01 Matrix                                   | https://leetcode.com/problems/01-matrix/                                           |
| Medium     | LeetCode | 1091 | Shortest Path in Binary Matrix              | https://leetcode.com/problems/shortest-path-in-binary-matrix/                      |
| Medium     | LeetCode | 286  | Walls and Gates                             | https://leetcode.com/problems/walls-and-gates/                                     |
| Medium     | LeetCode | 200  | Number of Islands                           | https://leetcode.com/problems/number-of-islands/                                   |
| Medium     | GFG      | G10  | Number of Islands                           | https://www.geeksforgeeks.org/problems/find-the-number-of-islands/1                |
| Medium     | LeetCode | 130  | Surrounded Regions                          | https://leetcode.com/problems/surrounded-regions/                                  |
| Medium     | LeetCode | 1162 | As Far from Land as Possible                | https://leetcode.com/problems/as-far-from-land-as-possible/                        |
| Hard       | LeetCode | 127  | Word Ladder                                 | https://leetcode.com/problems/word-ladder/                                         |
| Hard       | GFG      | G11  | Word Ladder                                 | https://www.geeksforgeeks.org/problems/word-ladder/1                               |
| Hard       | LeetCode | 126  | Word Ladder II                              | https://leetcode.com/problems/word-ladder-ii/                                      |

---

## Level 3 — Sliding Window Maximum (Deque)

**Goal:** The monotonic deque is the queue equivalent of the monotonic stack. It solves "maximum/minimum in a sliding window" in O(n) — a critical pattern for stream processing and subarray problems.

| Difficulty | Platform | Q.No | Question                                      | Link                                                                               |
| ---------- | -------- | ---- | --------------------------------------------- | ---------------------------------------------------------------------------------- |
| Hard       | LeetCode | 239  | Sliding Window Maximum                        | https://leetcode.com/problems/sliding-window-maximum/                              |
| Medium     | GFG      | G12  | Maximum of All Subarrays of Size K            | https://www.geeksforgeeks.org/problems/maximum-of-all-subarrays-of-size-k3101/1    |
| Medium     | GFG      | G13  | First Negative in Every Window of Size K      | https://www.geeksforgeeks.org/problems/first-negative-integer-in-every-window-of-size-k3345/1 |
| Hard       | LeetCode | 862  | Shortest Subarray with Sum at Least K         | https://leetcode.com/problems/shortest-subarray-with-sum-at-least-k/               |
| Hard       | LeetCode | 1425 | Constrained Subsequence Sum                   | https://leetcode.com/problems/constrained-subsequence-sum/                         |
| Medium     | LeetCode | 1438 | Longest Continuous Subarray With Abs Diff ≤ K | https://leetcode.com/problems/longest-continuous-subarray-with-absolute-diff-less-than-or-equal-to-limit/ |
| Hard       | LeetCode | 2398 | Maximum Number of Robots Within Budget        | https://leetcode.com/problems/maximum-number-of-robots-within-budget/              |

---

## Level 4 — Priority Queue / Heap-Based Queue Problems

**Goal:** A priority queue (implemented via heaps) is a queue where elements dequeue by priority, not insertion order. It's essential for greedy algorithms, scheduling, and merge-k patterns.

| Difficulty | Platform | Q.No | Question                                     | Link                                                                                |
| ---------- | -------- | ---- | -------------------------------------------- | ----------------------------------------------------------------------------------- |
| Easy       | LeetCode | 703  | Kth Largest Element in a Stream              | https://leetcode.com/problems/kth-largest-element-in-a-stream/                      |
| Medium     | LeetCode | 215  | Kth Largest Element in an Array              | https://leetcode.com/problems/kth-largest-element-in-an-array/                      |
| Medium     | GFG      | G14  | Kth Largest Element                          | https://www.geeksforgeeks.org/problems/kth-largest-element3736/1                    |
| Medium     | LeetCode | 347  | Top K Frequent Elements                      | https://leetcode.com/problems/top-k-frequent-elements/                              |
| Medium     | GFG      | G15  | Top K Frequent Elements in Array             | https://www.geeksforgeeks.org/problems/top-k-frequent-elements-in-array/1           |
| Medium     | LeetCode | 692  | Top K Frequent Words                         | https://leetcode.com/problems/top-k-frequent-words/                                 |
| Hard       | LeetCode | 23   | Merge K Sorted Lists                         | https://leetcode.com/problems/merge-k-sorted-lists/                                 |
| Medium     | GFG      | G16  | Merge K Sorted Lists                         | https://www.geeksforgeeks.org/problems/merge-k-sorted-linked-lists/1                |
| Medium     | LeetCode | 973  | K Closest Points to Origin                   | https://leetcode.com/problems/k-closest-points-to-origin/                           |
| Medium     | LeetCode | 1046 | Last Stone Weight                            | https://leetcode.com/problems/last-stone-weight/                                    |
| Medium     | LeetCode | 621  | Task Scheduler                               | https://leetcode.com/problems/task-scheduler/                                       |
| Hard       | LeetCode | 295  | Find Median from Data Stream                 | https://leetcode.com/problems/find-median-from-data-stream/                         |
| Hard       | GFG      | G17  | Find Median in a Stream                      | https://www.geeksforgeeks.org/problems/find-median-in-a-stream-1587115620/1         |
| Medium     | LeetCode | 1845 | Seat Reservation Manager                     | https://leetcode.com/problems/seat-reservation-manager/                             |

---

## Level 5 — Advanced Queue Design & Scheduling

**Goal:** Design problems that use queues creatively — LRU Cache, task scheduling, and streaming data. These combine queues with hashmaps, linked lists, or heaps.

| Difficulty | Platform | Q.No | Question                                     | Link                                                                          |
| ---------- | -------- | ---- | -------------------------------------------- | ----------------------------------------------------------------------------- |
| Medium     | LeetCode | 146  | LRU Cache                                    | https://leetcode.com/problems/lru-cache/                                      |
| Hard       | LeetCode | 460  | LFU Cache                                    | https://leetcode.com/problems/lfu-cache/                                      |
| Medium     | GFG      | G18  | LRU Cache                                    | https://www.geeksforgeeks.org/problems/lru-cache/1                            |
| Medium     | LeetCode | 362  | Design Hit Counter                           | https://leetcode.com/problems/design-hit-counter/                             |
| Medium     | LeetCode | 353  | Design Snake Game                            | https://leetcode.com/problems/design-snake-game/                              |
| Medium     | LeetCode | 649  | Dota2 Senate                                 | https://leetcode.com/problems/dota2-senate/                                   |
| Medium     | LeetCode | 950  | Reveal Cards In Increasing Order             | https://leetcode.com/problems/reveal-cards-in-increasing-order/               |
| Hard       | LeetCode | 1670 | Design Front Middle Back Queue               | https://leetcode.com/problems/design-front-middle-back-queue/                 |

---

## Level 6 — Hard / Expert Queue Problems

**Goal:** The hardest queue problems — they often combine BFS with state-space search, multi-source BFS, or priority queue with complex greedy logic.

| Difficulty | Platform | Q.No | Question                                        | Link                                                                                  |
| ---------- | -------- | ---- | ----------------------------------------------- | ------------------------------------------------------------------------------------- |
| Hard       | LeetCode | 407  | Trapping Rain Water II                          | https://leetcode.com/problems/trapping-rain-water-ii/                                 |
| Hard       | LeetCode | 778  | Swim in Rising Water                            | https://leetcode.com/problems/swim-in-rising-water/                                   |
| Hard       | LeetCode | 1293 | Shortest Path in a Grid with Obstacles          | https://leetcode.com/problems/shortest-path-in-a-grid-with-obstacles-elimination/     |
| Hard       | LeetCode | 847  | Shortest Path Visiting All Nodes                | https://leetcode.com/problems/shortest-path-visiting-all-nodes/                       |
| Hard       | LeetCode | 1696 | Jump Game VI                                    | https://leetcode.com/problems/jump-game-vi/                                           |
| Hard       | GFG      | G19  | Distance of Nearest Cell Having 1               | https://www.geeksforgeeks.org/problems/distance-of-nearest-cell-having-1-1587115620/1 |
| Hard       | LeetCode | 2290 | Minimum Obstacle Removal to Reach Corner        | https://leetcode.com/problems/minimum-obstacle-removal-to-reach-corner/               |
| Hard       | LeetCode | 1263 | Minimum Moves to Move a Box to Target           | https://leetcode.com/problems/minimum-moves-to-move-a-box-to-their-target-location/   |

---

_This is a curated, hand-picked progression rather than a literal "every question that exists" list — the goal is depth and pattern-recognition, not volume. Mastering everything above will comfortably cover Queue, Deque, and Priority Queue for interviews at any level._
