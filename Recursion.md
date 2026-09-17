# Recursion Mastery Sheet — LeetCode + GFG

A level-wise, progressively harder question bank to build **rock-solid command over recursion** — from writing your first base case to backtracking on boards and bridging into Dynamic Programming.

> **Note on "Q.No":** LeetCode numbers are official LeetCode problem IDs. GFG does not publish official numbers, so GFG rows are labelled `G1, G2, G3…` as a running serial you can use to track progress.

---

## Level 1 — Foundations: Trusting the Base Case

**Goal:** Internalize base case + recursive case + how the call stack unwinds, on problems simple enough that the _recursion_, not the problem, is the thing you're learning.

| Difficulty | Platform | Q.No | Question                         | Link                                                                                 |
| ---------- | -------- | ---- | -------------------------------- | ------------------------------------------------------------------------------------ |
| Basic      | GFG      | G1   | Print 1 to N Without Using Loops | https://www.geeksforgeeks.org/problems/print-1-to-n-without-using-loops-1587115620/1 |
| Easy       | LeetCode | 509  | Fibonacci Number                 | https://leetcode.com/problems/fibonacci-number/                                      |
| Easy       | LeetCode | 70   | Climbing Stairs                  | https://leetcode.com/problems/climbing-stairs/                                       |
| Easy       | LeetCode | 231  | Power of Two                     | https://leetcode.com/problems/power-of-two/                                          |
| Easy       | LeetCode | 326  | Power of Three                   | https://leetcode.com/problems/power-of-three/                                        |
| Easy       | LeetCode | 342  | Power of Four                    | https://leetcode.com/problems/power-of-four/                                         |
| Medium     | LeetCode | 50   | Pow(x, n)                        | https://leetcode.com/problems/powx-n/                                                |
| Easy       | LeetCode | 344  | Reverse String                   | https://leetcode.com/problems/reverse-string/                                        |
| Medium     | GFG      | G2   | Tower of Hanoi                   | https://www.geeksforgeeks.org/problems/tower-of-hanoi-1587115621/1                   |

---

## Level 2 — Backtracking Fundamentals (Part A): Subsets & Permutations

**Goal:** Learn the universal backtracking template — `choose → explore → un-choose` — on the cleanest possible problems.

| Difficulty | Platform | Q.No | Question                       | Link                                                                               |
| ---------- | -------- | ---- | ------------------------------ | ---------------------------------------------------------------------------------- |
| Medium     | LeetCode | 78   | Subsets                        | https://leetcode.com/problems/subsets/                                             |
| Medium     | LeetCode | 90   | Subsets II                     | https://leetcode.com/problems/subsets-ii/                                          |
| Medium     | LeetCode | 46   | Permutations                   | https://leetcode.com/problems/permutations/                                        |
| Medium     | LeetCode | 47   | Permutations II                | https://leetcode.com/problems/permutations-ii/                                     |
| Medium     | GFG      | G3   | Permutations of a Given String | https://www.geeksforgeeks.org/problems/permutations-of-a-given-string-1587115620/1 |
| Medium     | LeetCode | 77   | Combinations                   | https://leetcode.com/problems/combinations/                                        |
| Medium     | LeetCode | 784  | Letter Case Permutation        | https://leetcode.com/problems/letter-case-permutation/                             |

---

## Level 3 — Backtracking Fundamentals (Part B): Combination-Sum Family & Parentheses

**Goal:** Add a _target/constraint_ to the choose-explore-unchoose template — this is the pattern behind most "generate all valid X" interview questions.

| Difficulty | Platform | Q.No | Question                              | Link                                                                 |
| ---------- | -------- | ---- | ------------------------------------- | -------------------------------------------------------------------- |
| Medium     | LeetCode | 39   | Combination Sum                       | https://leetcode.com/problems/combination-sum/                       |
| Medium     | LeetCode | 40   | Combination Sum II                    | https://leetcode.com/problems/combination-sum-ii/                    |
| Medium     | LeetCode | 216  | Combination Sum III                   | https://leetcode.com/problems/combination-sum-iii/                   |
| Medium     | GFG      | G4   | Combination Sum                       | https://www.geeksforgeeks.org/problems/combination-sum-1587115620/1  |
| Medium     | LeetCode | 22   | Generate Parentheses                  | https://leetcode.com/problems/generate-parentheses/                  |
| Medium     | LeetCode | 17   | Letter Combinations of a Phone Number | https://leetcode.com/problems/letter-combinations-of-a-phone-number/ |

---

## Level 4 — Recursion on Strings: Partitioning & Segmenting

**Goal:** Move from "generate all combinations" to "generate all valid _decompositions_ of a string" — a slightly harder shape of the same idea.

| Difficulty | Platform | Q.No | Question                   | Link                                                      |
| ---------- | -------- | ---- | -------------------------- | --------------------------------------------------------- |
| Medium     | LeetCode | 131  | Palindrome Partitioning    | https://leetcode.com/problems/palindrome-partitioning/    |
| Medium     | LeetCode | 93   | Restore IP Addresses       | https://leetcode.com/problems/restore-ip-addresses/       |
| Medium     | GFG      | G5   | Word Break                 | https://www.geeksforgeeks.org/problems/word-break1352/1   |
| Medium     | LeetCode | 139  | Word Break                 | https://leetcode.com/problems/word-break/                 |
| Hard       | LeetCode | 140  | Word Break II              | https://leetcode.com/problems/word-break-ii/              |
| Hard       | LeetCode | 301  | Remove Invalid Parentheses | https://leetcode.com/problems/remove-invalid-parentheses/ |
| Hard       | LeetCode | 282  | Expression Add Operators   | https://leetcode.com/problems/expression-add-operators/   |

---

## Level 5 — Backtracking on Grids & Boards (Constraint Satisfaction)

**Goal:** Apply backtracking to 2D state spaces — this is where "recursion + a `visited`/`board` mutation + undo" clicks into a reusable pattern for maze/board problems.

| Difficulty | Platform | Q.No | Question             | Link                                                                   |
| ---------- | -------- | ---- | -------------------- | ---------------------------------------------------------------------- |
| Easy       | LeetCode | 733  | Flood Fill           | https://leetcode.com/problems/flood-fill/                              |
| Easy       | GFG      | G7   | Flood Fill Algorithm | https://www.geeksforgeeks.org/problems/flood-fill-algorithm1856/1      |
| Medium     | GFG      | G6   | Rat in a Maze        | https://www.geeksforgeeks.org/problems/rat-in-a-maze-problem/1         |
| Medium     | LeetCode | 79   | Word Search          | https://leetcode.com/problems/word-search/                             |
| Hard       | LeetCode | 212  | Word Search II       | https://leetcode.com/problems/word-search-ii/                          |
| Medium     | LeetCode | 494  | Target Sum           | https://leetcode.com/problems/target-sum/                              |
| Hard       | GFG      | G8   | N-Queen Problem      | https://www.geeksforgeeks.org/problems/n-queen-problem0315/1           |
| Hard       | LeetCode | 51   | N-Queens             | https://leetcode.com/problems/n-queens/                                |
| Hard       | LeetCode | 52   | N-Queens II          | https://leetcode.com/problems/n-queens-ii/                             |
| Hard       | GFG      | G9   | Solve the Sudoku     | https://www.geeksforgeeks.org/problems/solve-the-sudoku-1587115621/1   |
| Hard       | LeetCode | 37   | Sudoku Solver        | https://leetcode.com/problems/sudoku-solver/                           |
| Medium     | GFG      | G10  | M-Coloring Problem   | https://www.geeksforgeeks.org/problems/m-coloring-problem-1587115620/1 |

---

## Level 6 — Recursion on Linked Lists

**Goal:** See recursion as the natural way to express "do something to the rest of the list, then fix up the head" — a different flavor from backtracking.

| Difficulty | Platform | Q.No | Question                 | Link                                                    |
| ---------- | -------- | ---- | ------------------------ | ------------------------------------------------------- |
| Easy       | LeetCode | 206  | Reverse Linked List      | https://leetcode.com/problems/reverse-linked-list/      |
| Easy       | LeetCode | 21   | Merge Two Sorted Lists   | https://leetcode.com/problems/merge-two-sorted-lists/   |
| Easy       | LeetCode | 234  | Palindrome Linked List   | https://leetcode.com/problems/palindrome-linked-list/   |
| Medium     | LeetCode | 24   | Swap Nodes in Pairs      | https://leetcode.com/problems/swap-nodes-in-pairs/      |
| Hard       | LeetCode | 25   | Reverse Nodes in k-Group | https://leetcode.com/problems/reverse-nodes-in-k-group/ |

---

## Level 7 — Recursion on Trees

**Goal:** Trees are recursion's most natural home — every subtree problem is "solve it for children, combine at the root."

| Difficulty | Platform | Q.No | Question                                   | Link                                                                      |
| ---------- | -------- | ---- | ------------------------------------------ | ------------------------------------------------------------------------- |
| Easy       | LeetCode | 104  | Maximum Depth of Binary Tree               | https://leetcode.com/problems/maximum-depth-of-binary-tree/               |
| Easy       | LeetCode | 226  | Invert Binary Tree                         | https://leetcode.com/problems/invert-binary-tree/                         |
| Easy       | LeetCode | 100  | Same Tree                                  | https://leetcode.com/problems/same-tree/                                  |
| Easy       | LeetCode | 101  | Symmetric Tree                             | https://leetcode.com/problems/symmetric-tree/                             |
| Easy       | LeetCode | 543  | Diameter of Binary Tree                    | https://leetcode.com/problems/diameter-of-binary-tree/                    |
| Easy       | LeetCode | 112  | Path Sum                                   | https://leetcode.com/problems/path-sum/                                   |
| Medium     | LeetCode | 113  | Path Sum II                                | https://leetcode.com/problems/path-sum-ii/                                |
| Easy       | LeetCode | 108  | Convert Sorted Array to Binary Search Tree | https://leetcode.com/problems/convert-sorted-array-to-binary-search-tree/ |
| Medium     | LeetCode | 98   | Validate Binary Search Tree                | https://leetcode.com/problems/validate-binary-search-tree/                |
| Medium     | LeetCode | 236  | Lowest Common Ancestor of a Binary Tree    | https://leetcode.com/problems/lowest-common-ancestor-of-a-binary-tree/    |

---

## Level 8 — Divide and Conquer

**Goal:** A distinct recursion flavor: split the problem into independent halves, solve each, then combine — the backbone of merge sort, quicksort, and fast exponentiation.

| Difficulty | Platform | Q.No | Question                                            | Link                                                             |
| ---------- | -------- | ---- | --------------------------------------------------- | ---------------------------------------------------------------- |
| Medium     | LeetCode | 912  | Sort an Array _(implement Merge Sort & Quick Sort)_ | https://leetcode.com/problems/sort-an-array/                     |
| Medium     | LeetCode | 241  | Different Ways to Add Parentheses                   | https://leetcode.com/problems/different-ways-to-add-parentheses/ |
| Hard       | LeetCode | 23   | Merge k Sorted Lists                                | https://leetcode.com/problems/merge-k-sorted-lists/              |
| Medium     | GFG      | G11  | Josephus Problem                                    | https://www.geeksforgeeks.org/problems/josephus-problem/1        |

---

## Level 9 — Hard / Expert Recursion (Interview Ceiling Problems)

**Goal:** Problems where recursion alone becomes exponential and you must _feel_ why memoization is about to become mandatory — the bridge to the final level.

| Difficulty | Platform | Q.No | Question                            | Link                                                               |
| ---------- | -------- | ---- | ----------------------------------- | ------------------------------------------------------------------ |
| Hard       | LeetCode | 10   | Regular Expression Matching         | https://leetcode.com/problems/regular-expression-matching/         |
| Hard       | LeetCode | 44   | Wildcard Matching                   | https://leetcode.com/problems/wildcard-matching/                   |
| Hard       | LeetCode | 329  | Longest Increasing Path in a Matrix | https://leetcode.com/problems/longest-increasing-path-in-a-matrix/ |

---

## Follow-Up Level — Bridging Recursion into Dynamic Programming

**Goal:** This is the payoff. Every problem here is solved with the _exact same recursive thinking_ as above — the only new skill is caching repeated subproblems (top-down memoization), which is the natural next step after recursion, not a separate topic.

| Difficulty | Platform | Q.No | Question                                   | Link                                                          |
| ---------- | -------- | ---- | ------------------------------------------ | ------------------------------------------------------------- |
| Easy       | LeetCode | 70   | Climbing Stairs _(redo with memoization)_  | https://leetcode.com/problems/climbing-stairs/                |
| Easy       | LeetCode | 509  | Fibonacci Number _(redo with memoization)_ | https://leetcode.com/problems/fibonacci-number/               |
| Medium     | LeetCode | 322  | Coin Change                                | https://leetcode.com/problems/coin-change/                    |
| Medium     | LeetCode | 300  | Longest Increasing Subsequence             | https://leetcode.com/problems/longest-increasing-subsequence/ |
| Medium     | LeetCode | 62   | Unique Paths                               | https://leetcode.com/problems/unique-paths/                   |
| Medium     | LeetCode | 64   | Minimum Path Sum                           | https://leetcode.com/problems/minimum-path-sum/               |
| Medium     | LeetCode | 198  | House Robber                               | https://leetcode.com/problems/house-robber/                   |
| Medium     | LeetCode | 5    | Longest Palindromic Substring              | https://leetcode.com/problems/longest-palindromic-substring/  |
| Medium     | LeetCode | 1143 | Longest Common Subsequence                 | https://leetcode.com/problems/longest-common-subsequence/     |
| Hard       | LeetCode | 72   | Edit Distance                              | https://leetcode.com/problems/edit-distance/                  |

---

_This is a curated, hand-picked progression rather than a literal "every question that exists" list — the goal is depth and pattern-recognition, not volume. Mastering everything above will comfortably cover recursion + backtracking for interviews at any level._
