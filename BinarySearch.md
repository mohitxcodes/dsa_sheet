# Binary Search Mastery Sheet — LeetCode + GFG

## Level 1 — Foundations: The Classic Binary Search Pattern

**Goal:** Nail the basic binary search template — `low`, `high`, `mid`, loop termination, and off-by-one handling. These problems are simple enough that the _search mechanics_, not the problem, is what you're learning.

| Difficulty | Platform | Q.No | Question                              | Link                                                                                     |
| ---------- | -------- | ---- | ------------------------------------- | ---------------------------------------------------------------------------------------- |
| Easy       | LeetCode | 704  | Binary Search                         | https://leetcode.com/problems/binary-search/                                             |
| Basic      | GFG      | G1   | Binary Search                         | https://www.geeksforgeeks.org/problems/binary-search-1587115620/1                        |
| Easy       | LeetCode | 35   | Search Insert Position                | https://leetcode.com/problems/search-insert-position/                                    |
| Easy       | GFG      | G2   | Floor in a Sorted Array               | https://www.geeksforgeeks.org/problems/floor-in-a-sorted-array-1587115620/1              |
| Easy       | GFG      | G3   | Ceil The Floor                        | https://www.geeksforgeeks.org/problems/ceil-the-floor2802/1                              |
| Easy       | LeetCode | 367  | Valid Perfect Square                   | https://leetcode.com/problems/valid-perfect-square/                                      |
| Easy       | LeetCode | 69   | Sqrt(x)                               | https://leetcode.com/problems/sqrtx/                                                     |
| Easy       | GFG      | G4   | Square Root of a Number               | https://www.geeksforgeeks.org/problems/square-root/1                                     |
| Easy       | LeetCode | 374  | Guess Number Higher or Lower          | https://leetcode.com/problems/guess-number-higher-or-lower/                              |
| Easy       | GFG      | G5   | Number of Occurrence                  | https://www.geeksforgeeks.org/problems/number-of-occurrence2259/1                        |
| Easy       | LeetCode | 278  | First Bad Version                     | https://leetcode.com/problems/first-bad-version/                                         |
| Easy       | GFG      | G6   | Implement Lower Bound                 | https://www.geeksforgeeks.org/problems/implement-lower-bound/1                           |
| Easy       | GFG      | G7   | Implement Upper Bound                 | https://www.geeksforgeeks.org/problems/implement-upper-bound/1                           |

---

## Level 2 — First & Last Occurrence / Boundary Search

**Goal:** Learn the two most important binary search variants — finding the _leftmost_ and _rightmost_ positions satisfying a condition. This "boundary-finding" pattern is the backbone of 80% of binary search problems.

| Difficulty | Platform | Q.No | Question                                     | Link                                                                                  |
| ---------- | -------- | ---- | -------------------------------------------- | ------------------------------------------------------------------------------------- |
| Medium     | LeetCode | 34   | Find First and Last Position in Sorted Array | https://leetcode.com/problems/find-first-and-last-position-of-element-in-sorted-array/ |
| Easy       | GFG      | G8   | First and Last Occurrences of X              | https://www.geeksforgeeks.org/problems/first-and-last-occurrences-of-x3116/1          |
| Easy       | LeetCode | 744  | Find Smallest Letter Greater Than Target     | https://leetcode.com/problems/find-smallest-letter-greater-than-target/               |
| Medium     | LeetCode | 2529 | Maximum Count of Positive and Negative Integer | https://leetcode.com/problems/maximum-count-of-positive-integer-and-negative-integer/ |
| Easy       | GFG      | G9   | Sorted Array Search                          | https://www.geeksforgeeks.org/problems/who-will-win-1587115621/1                      |
| Medium     | LeetCode | 441  | Arranging Coins                              | https://leetcode.com/problems/arranging-coins/                                        |
| Medium     | GFG      | G10  | Count 1s in a Sorted Binary Array            | https://www.geeksforgeeks.org/problems/count-1s-in-a-sorted-binary-array/1            |

---

## Level 3 — Binary Search on Rotated / Modified Arrays

**Goal:** When the array isn't perfectly sorted — it's rotated, or has duplicates — the search space still has enough structure for binary search. These problems teach you to identify _which half is sorted_ and decide accordingly.

| Difficulty | Platform | Q.No | Question                                       | Link                                                                                |
| ---------- | -------- | ---- | ---------------------------------------------- | ----------------------------------------------------------------------------------- |
| Medium     | LeetCode | 33   | Search in Rotated Sorted Array                 | https://leetcode.com/problems/search-in-rotated-sorted-array/                       |
| Medium     | LeetCode | 81   | Search in Rotated Sorted Array II _(dupes)_    | https://leetcode.com/problems/search-in-rotated-sorted-array-ii/                    |
| Medium     | GFG      | G11  | Search in Rotated Sorted Array                 | https://www.geeksforgeeks.org/problems/search-in-a-rotated-array4618/1              |
| Medium     | LeetCode | 153  | Find Minimum in Rotated Sorted Array           | https://leetcode.com/problems/find-minimum-in-rotated-sorted-array/                 |
| Hard       | LeetCode | 154  | Find Minimum in Rotated Sorted Array II        | https://leetcode.com/problems/find-minimum-in-rotated-sorted-array-ii/              |
| Medium     | GFG      | G12  | Minimum in a Sorted and Rotated Array          | https://www.geeksforgeeks.org/problems/minimum-element-in-a-sorted-and-rotated-array3611/1 |
| Medium     | GFG      | G13  | Rotation Count in Rotated Sorted Array         | https://www.geeksforgeeks.org/problems/rotation4723/1                               |
| Easy       | LeetCode | 852  | Peak Index in a Mountain Array                 | https://leetcode.com/problems/peak-index-in-a-mountain-array/                       |
| Medium     | LeetCode | 162  | Find Peak Element                              | https://leetcode.com/problems/find-peak-element/                                    |
| Medium     | GFG      | G14  | Peak Element                                   | https://www.geeksforgeeks.org/problems/peak-element/1                               |
| Easy       | LeetCode | 540  | Single Element in a Sorted Array               | https://leetcode.com/problems/single-element-in-a-sorted-array/                     |

---

## Level 4 — Binary Search on 2D Matrices

**Goal:** Extend binary search from 1D arrays to 2D matrices. The key insight: a sorted matrix can be "flattened" into a sorted 1D array, or you can binary search row-by-row with smart bounds.

| Difficulty | Platform | Q.No | Question                                | Link                                                                             |
| ---------- | -------- | ---- | --------------------------------------- | -------------------------------------------------------------------------------- |
| Medium     | LeetCode | 74   | Search a 2D Matrix                      | https://leetcode.com/problems/search-a-2d-matrix/                                |
| Medium     | LeetCode | 240  | Search a 2D Matrix II                   | https://leetcode.com/problems/search-a-2d-matrix-ii/                             |
| Medium     | GFG      | G15  | Search in a Row-Column Sorted Matrix    | https://www.geeksforgeeks.org/problems/search-in-a-matrix-1587115621/1           |
| Medium     | GFG      | G16  | Search in a Sorted Matrix               | https://www.geeksforgeeks.org/problems/search-in-a-matrix17201720/1              |
| Medium     | GFG      | G17  | Median in a Row-Wise Sorted Matrix      | https://www.geeksforgeeks.org/problems/median-in-a-row-wise-sorted-matrix1527/1  |
| Hard       | LeetCode | 378  | Kth Smallest Element in a Sorted Matrix | https://leetcode.com/problems/kth-smallest-element-in-a-sorted-matrix/           |
| Medium     | GFG      | G18  | Row with Maximum 1s                     | https://www.geeksforgeeks.org/problems/row-with-max-1s0023/1                     |

---

## Level 5 — Binary Search on Answer (Minimize Maximum / Maximize Minimum)

**Goal:** The most powerful binary search pattern — instead of searching _in_ an array, you binary search on the _answer space_. "Can we achieve result X?" becomes the predicate, and you binary search over X. This pattern dominates competitive programming and hard interview problems.

| Difficulty | Platform | Q.No | Question                                          | Link                                                                                |
| ---------- | -------- | ---- | ------------------------------------------------- | ----------------------------------------------------------------------------------- |
| Medium     | LeetCode | 875  | Koko Eating Bananas                               | https://leetcode.com/problems/koko-eating-bananas/                                  |
| Medium     | LeetCode | 1011 | Capacity To Ship Packages Within D Days           | https://leetcode.com/problems/capacity-to-ship-packages-within-d-days/              |
| Medium     | LeetCode | 1482 | Minimum Number of Days to Make m Bouquets         | https://leetcode.com/problems/minimum-number-of-days-to-make-m-bouquets/            |
| Medium     | LeetCode | 1283 | Find the Smallest Divisor Given a Threshold       | https://leetcode.com/problems/find-the-smallest-divisor-given-a-threshold/          |
| Hard       | LeetCode | 410  | Split Array Largest Sum                           | https://leetcode.com/problems/split-array-largest-sum/                              |
| Medium     | GFG      | G19  | Allocate Minimum Pages                            | https://www.geeksforgeeks.org/problems/allocate-minimum-number-of-pages0937/1       |
| Medium     | GFG      | G20  | The Painter's Partition Problem                   | https://www.geeksforgeeks.org/problems/the-painters-partition-problem1702/1         |
| Hard       | LeetCode | 774  | Minimize Max Distance to Gas Station              | https://leetcode.com/problems/minimize-max-distance-to-gas-station/                 |
| Medium     | GFG      | G21  | Aggressive Cows                                   | https://www.geeksforgeeks.org/problems/aggressive-cows/1                            |
| Medium     | LeetCode | 2226 | Maximum Candies Allocated to K Children           | https://leetcode.com/problems/maximum-candies-allocated-to-k-children/              |
| Medium     | LeetCode | 1552 | Magnetic Force Between Two Balls                  | https://leetcode.com/problems/magnetic-force-between-two-balls/                     |
| Medium     | GFG      | G22  | EKO – SPOJ (Wood Cutting)                         | https://www.geeksforgeeks.org/problems/eko-spoj/1                                   |
| Hard       | LeetCode | 668  | Kth Smallest Number in Multiplication Table       | https://leetcode.com/problems/kth-smallest-number-in-multiplication-table/          |

---

## Level 6 — Binary Search on Sorted Pairs / Merge Without Merging

**Goal:** Problems where you need to find the Kth element or median across sorted structures _without_ merging them — pure binary search on counts or partitions.

| Difficulty | Platform | Q.No | Question                                     | Link                                                                               |
| ---------- | -------- | ---- | -------------------------------------------- | ---------------------------------------------------------------------------------- |
| Hard       | LeetCode | 4    | Median of Two Sorted Arrays                  | https://leetcode.com/problems/median-of-two-sorted-arrays/                         |
| Medium     | GFG      | G23  | K-th Element of Two Sorted Arrays            | https://www.geeksforgeeks.org/problems/k-th-element-of-two-sorted-array0226/1      |
| Hard       | LeetCode | 719  | Find K-th Smallest Pair Distance             | https://leetcode.com/problems/find-k-th-smallest-pair-distance/                    |
| Medium     | LeetCode | 378  | Kth Smallest Element in a Sorted Matrix      | https://leetcode.com/problems/kth-smallest-element-in-a-sorted-matrix/             |
| Hard       | LeetCode | 786  | K-th Smallest Prime Fraction                 | https://leetcode.com/problems/k-th-smallest-prime-fraction/                        |
| Medium     | GFG      | G24  | Median of Two Sorted Arrays of Different Sizes | https://www.geeksforgeeks.org/problems/median-of-2-sorted-arrays-of-different-sizes/1 |

---

## Level 7 — Binary Search on Strings & Specialized Structures

**Goal:** Binary search isn't just for numbers — it works on strings (lexicographic order), time series, and custom comparators. These problems stretch your ability to define "sorted order" creatively.

| Difficulty | Platform | Q.No | Question                                          | Link                                                                          |
| ---------- | -------- | ---- | ------------------------------------------------- | ----------------------------------------------------------------------------- |
| Medium     | LeetCode | 1268 | Search Suggestions System                         | https://leetcode.com/problems/search-suggestions-system/                      |
| Easy       | LeetCode | 392  | Is Subsequence                                    | https://leetcode.com/problems/is-subsequence/                                 |
| Medium     | LeetCode | 981  | Time Based Key-Value Store                        | https://leetcode.com/problems/time-based-key-value-store/                     |
| Medium     | LeetCode | 528  | Random Pick with Weight                           | https://leetcode.com/problems/random-pick-with-weight/                        |
| Hard       | LeetCode | 710  | Random Pick with Blacklist                        | https://leetcode.com/problems/random-pick-with-blacklist/                     |
| Medium     | GFG      | G25  | Bishu and Soldiers                                | https://www.geeksforgeeks.org/problems/bishu-and-soldiers/1                   |
| Medium     | LeetCode | 436  | Find Right Interval                               | https://leetcode.com/problems/find-right-interval/                            |

---

## Level 8 — Advanced Binary Search Techniques

**Goal:** Combine binary search with other paradigms — greedy, sliding window, prefix sums, or even binary search within binary search. These are interview-ceiling problems.

| Difficulty | Platform | Q.No | Question                                           | Link                                                                                  |
| ---------- | -------- | ---- | -------------------------------------------------- | ------------------------------------------------------------------------------------- |
| Medium     | LeetCode | 209  | Minimum Size Subarray Sum                          | https://leetcode.com/problems/minimum-size-subarray-sum/                              |
| Medium     | LeetCode | 658  | Find K Closest Elements                            | https://leetcode.com/problems/find-k-closest-elements/                                |
| Hard       | LeetCode | 354  | Russian Doll Envelopes _(BS + LIS)_               | https://leetcode.com/problems/russian-doll-envelopes/                                 |
| Hard       | LeetCode | 1201 | Ugly Number III                                    | https://leetcode.com/problems/ugly-number-iii/                                        |
| Hard       | LeetCode | 878  | Nth Magical Number                                 | https://leetcode.com/problems/nth-magical-number/                                     |
| Medium     | LeetCode | 1498 | Number of Subsequences That Satisfy Given Sum      | https://leetcode.com/problems/number-of-subsequences-that-satisfy-the-given-sum-condition/ |
| Hard       | LeetCode | 2141 | Maximum Running Time of N Computers                | https://leetcode.com/problems/maximum-running-time-of-n-computers/                    |
| Hard       | GFG      | G26  | Smallest Positive Missing Number _(BS approach)_   | https://www.geeksforgeeks.org/problems/smallest-positive-missing-number-1587115621/1  |
| Medium     | LeetCode | 1300 | Sum of Mutated Array Closest to Target             | https://leetcode.com/problems/sum-of-mutated-array-closest-to-target/                 |

---

## Level 9 — Hard / Expert Binary Search (Interview Ceiling)

**Goal:** The hardest binary search problems — they require combining binary search with complex predicates, mathematical reasoning, or multi-dimensional thinking. Solving these means binary search has become second nature.

| Difficulty | Platform | Q.No | Question                                            | Link                                                                                     |
| ---------- | -------- | ---- | --------------------------------------------------- | ---------------------------------------------------------------------------------------- |
| Hard       | LeetCode | 4    | Median of Two Sorted Arrays                         | https://leetcode.com/problems/median-of-two-sorted-arrays/                               |
| Hard       | LeetCode | 887  | Super Egg Drop                                      | https://leetcode.com/problems/super-egg-drop/                                            |
| Hard       | GFG      | G27  | Egg Dropping Puzzle                                 | https://www.geeksforgeeks.org/problems/egg-dropping-puzzle-1587115620/1                  |
| Hard       | LeetCode | 1231 | Divide Chocolate                                    | https://leetcode.com/problems/divide-chocolate/                                          |
| Hard       | LeetCode | 1439 | Find the Kth Smallest Sum of a Matrix With Sorted Rows | https://leetcode.com/problems/find-the-kth-smallest-sum-of-a-matrix-with-sorted-rows/ |
| Hard       | LeetCode | 2528 | Maximize the Minimum Powered City                   | https://leetcode.com/problems/maximize-the-minimum-powered-city/                         |
| Hard       | LeetCode | 2560 | House Robber IV                                     | https://leetcode.com/problems/house-robber-iv/                                           |
| Hard       | LeetCode | 2616 | Minimize the Maximum Difference of Pairs            | https://leetcode.com/problems/minimize-the-maximum-difference-of-pairs/                  |
| Hard       | GFG      | G28  | Matrix Median                                       | https://www.geeksforgeeks.org/problems/median-in-a-row-wise-sorted-matrix1527/1          |
| Hard       | LeetCode | 2064 | Minimized Maximum of Products Distributed to Any Store | https://leetcode.com/problems/minimized-maximum-of-products-distributed-to-any-store/ |

---

_This is a curated, hand-picked progression rather than a literal "every question that exists" list — the goal is depth and pattern-recognition, not volume. Mastering everything above will comfortably cover binary search for interviews at any level._
