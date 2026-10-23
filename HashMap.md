# HashMap Mastery Sheet — LeetCode + GFG

## Level 1 — Foundations: Frequency Counting, Direct Lookup & Hash Sets

**Goal:** Master the core principle of hashing — trading $O(N)$ extra space for $O(1)$ average time lookups. Learn frequency maps, existence checks, complement tracking (the Two Sum pattern), and direct addressing arrays.

| Difficulty | Platform | Q.No | Question                             | Link                                                                            |
| ---------- | -------- | ---- | ------------------------------------ | ------------------------------------------------------------------------------- |
| Easy       | LeetCode | 1    | Two Sum                              | https://leetcode.com/problems/two-sum/                                          |
| Easy       | GFG      | G1   | Key Pair (Two Sum)                   | https://www.geeksforgeeks.org/problems/key-pair5616/1                           |
| Easy       | LeetCode | 217  | Contains Duplicate                   | https://leetcode.com/problems/contains-duplicate/                               |
| Easy       | LeetCode | 242  | Valid Anagram                        | https://leetcode.com/problems/valid-anagram/                                    |
| Easy       | GFG      | G2   | Anagram                              | https://www.geeksforgeeks.org/problems/anagram-1587115620/1                     |
| Easy       | LeetCode | 387  | First Unique Character in a String   | https://leetcode.com/problems/first-unique-character-in-a-string/               |
| Easy       | GFG      | G3   | Non-Repeating Character              | https://www.geeksforgeeks.org/problems/non-repeating-character-1587115620/1         |
| Easy       | LeetCode | 383  | Ransom Note                          | https://leetcode.com/problems/ransom-note/                                      |
| Easy       | LeetCode | 169  | Majority Element                     | https://leetcode.com/problems/majority-element/                                 |
| Medium     | LeetCode | 229  | Majority Element II                  | https://leetcode.com/problems/majority-element-ii/                              |
| Easy       | GFG      | G4   | Majority Element                     | https://www.geeksforgeeks.org/problems/majority-element-1587115620/1            |
| Easy       | LeetCode | 349  | Intersection of Two Arrays           | https://leetcode.com/problems/intersection-of-two-arrays/                       |
| Easy       | LeetCode | 350  | Intersection of Two Arrays II        | https://leetcode.com/problems/intersection-of-two-arrays-ii/                    |
| Easy       | GFG      | G5   | Union of Two Arrays                  | https://www.geeksforgeeks.org/problems/union-of-two-arrays3538/1                |
| Easy       | LeetCode | 1207 | Unique Number of Occurrences         | https://leetcode.com/problems/unique-number-of-occurrences/                     |
| Easy       | LeetCode | 448  | Find All Numbers Disappeared in Array| https://leetcode.com/problems/find-all-numbers-disappeared-in-an-array/          |

---

## Level 2 — Grouping & Canonical Hash Keys (Anagrams, Patterns & Isomorphism)

**Goal:** Learn how to transform complex objects into canonical hash keys (sorted strings, character frequency tuples, normalized difference arrays) to group equivalent items together in $O(1)$ lookups.

| Difficulty | Platform | Q.No | Question                                         | Link                                                                                  |
| ---------- | -------- | ---- | ------------------------------------------------ | ------------------------------------------------------------------------------------- |
| Medium     | LeetCode | 49   | Group Anagrams                                   | https://leetcode.com/problems/group-anagrams/                                         |
| Medium     | GFG      | G6   | Print Anagrams Together                          | https://www.geeksforgeeks.org/problems/print-anagrams-together/1                      |
| Easy       | LeetCode | 205  | Isomorphic Strings                               | https://leetcode.com/problems/isomorphic-strings/                                     |
| Easy       | GFG      | G7   | Isomorphic Strings                               | https://www.geeksforgeeks.org/problems/isomorphic-strings-1587115620/1                |
| Easy       | LeetCode | 290  | Word Pattern                                     | https://leetcode.com/problems/word-pattern/                                           |
| Medium     | LeetCode | 890  | Find and Replace Pattern                         | https://leetcode.com/problems/find-and-replace-pattern/                               |
| Medium     | LeetCode | 249  | Group Shifted Strings                            | https://leetcode.com/problems/group-shifted-strings/                                  |
| Medium     | LeetCode | 1347 | Minimum Number of Steps to Make Two Strings Anagram | https://leetcode.com/problems/minimum-number-of-steps-to-make-two-strings-anagram/ |
| Medium     | LeetCode | 791  | Custom Sort String                               | https://leetcode.com/problems/custom-sort-string/                                     |
| Medium     | LeetCode | 451  | Sort Characters By Frequency                     | https://leetcode.com/problems/sort-characters-by-frequency/                           |
| Medium     | GFG      | G8   | Sorting Elements of an Array by Frequency        | https://www.geeksforgeeks.org/problems/sorting-elements-of-an-array-by-frequency-1587115620/1 |

---

## Level 3 — Prefix Sum + HashMap: Subarray Sums & Remainder Arithmetic

**Goal:** The `PrefixSum[j] - PrefixSum[i] = Target` equation is one of the most frequently tested hashmap interview patterns. Master storing cumulative sums, prefix parity, and remainder frequencies to find subarray counts, maximum lengths, and divisibility in $O(N)$ time.

| Difficulty | Platform | Q.No | Question                                                    | Link                                                                                      |
| ---------- | -------- | ---- | ----------------------------------------------------------- | ----------------------------------------------------------------------------------------- |
| Medium     | LeetCode | 560  | Subarray Sum Equals K                                       | https://leetcode.com/problems/subarray-sum-equals-k/                                       |
| Medium     | GFG      | G9   | Subarrays with sum K                                        | https://www.geeksforgeeks.org/problems/subarrays-with-sum-k/1                              |
| Medium     | LeetCode | 525  | Contiguous Array (Equal 0s and 1s)                          | https://leetcode.com/problems/contiguous-array/                                           |
| Medium     | GFG      | G10  | Largest Subarray of 0's and 1's                             | https://www.geeksforgeeks.org/problems/largest-subarray-of-0s-and-1s/1                     |
| Medium     | LeetCode | 974  | Subarray Sums Divisible by K                                | https://leetcode.com/problems/subarray-sums-divisible-by-k/                                |
| Easy       | GFG      | G11  | Subarray with 0 sum                                         | https://www.geeksforgeeks.org/problems/subarray-with-0-sum-1587115621/1                  |
| Medium     | GFG      | G12  | Largest Subarray with 0 Sum                                 | https://www.geeksforgeeks.org/problems/largest-subarray-with-0-sum/1                       |
| Medium     | GFG      | G13  | Zero Sum Subarrays (Count)                                  | https://www.geeksforgeeks.org/problems/zero-sum-subarrays1825/1                            |
| Medium     | GFG      | G14  | Longest Sub-Array with Sum K                                | https://www.geeksforgeeks.org/problems/longest-sub-array-with-sum-k0809/1                  |
| Medium     | LeetCode | 523  | Continuous Subarray Sum                                     | https://leetcode.com/problems/continuous-subarray-sum/                                     |
| Medium     | LeetCode | 1371 | Find Longest Substring Containing Vowels in Even Counts     | https://leetcode.com/problems/find-the-longest-substring-containing-vowels-in-even-counts/ |
| Medium     | LeetCode | 1590 | Make Sum Divisible by P                                     | https://leetcode.com/problems/make-sum-divisible-by-p/                                     |
| Medium     | GFG      | G15  | Count Subarrays with Given XOR                              | https://www.geeksforgeeks.org/problems/count-subarray-with-given-xor/1                     |

---

## Level 4 — Hash Set for Existence, Lookups & Consecutive Sequences

**Goal:** Hash sets provide $O(1)$ membership testing. Learn to establish sequence start points (checking `num - 1`), eliminate redundant work, detect cycles, and track visited elements in constant time.

| Difficulty | Platform | Q.No | Question                                     | Link                                                                             |
| ---------- | -------- | ---- | -------------------------------------------- | -------------------------------------------------------------------------------- |
| Medium     | LeetCode | 128  | Longest Consecutive Sequence                 | https://leetcode.com/problems/longest-consecutive-sequence/                       |
| Medium     | GFG      | G16  | Longest Consecutive Subsequence              | https://www.geeksforgeeks.org/problems/longest-consecutive-subsequence2449/1    |
| Easy       | LeetCode | 219  | Contains Duplicate II                        | https://leetcode.com/problems/contains-duplicate-ii/                             |
| Hard       | LeetCode | 220  | Contains Duplicate III _(Bucket Hashing)_     | https://leetcode.com/problems/contains-duplicate-iii/                            |
| Easy       | LeetCode | 202  | Happy Number                                 | https://leetcode.com/problems/happy-number/                                      |
| Medium     | LeetCode | 73   | Set Matrix Zeroes                            | https://leetcode.com/problems/set-matrix-zeroes/                                 |
| Hard       | LeetCode | 41   | First Missing Positive _(In-place Hashing)_  | https://leetcode.com/problems/first-missing-positive/                            |
| Medium     | LeetCode | 287  | Find the Duplicate Number                    | https://leetcode.com/problems/find-the-duplicate-number/                         |
| Easy       | LeetCode | 594  | Longest Harmonious Subsequence               | https://leetcode.com/problems/longest-harmonious-subsequence/                      |
| Easy       | LeetCode | 1496 | Path Crossing                                | https://leetcode.com/problems/path-crossing/                                     |
| Easy       | GFG      | G17  | Find All Pairs Whose Sum is X                | https://www.geeksforgeeks.org/problems/find-all-pairs-whose-sum-is-x5808/1        |

---

## Level 5 — HashMap + Sliding Window (Dynamic Windows & Frequency Tracking)

**Goal:** Combine sliding window two-pointer bounds with a frequency map to dynamically expand and shrink intervals. Track character deficits, distinct counts, and exact matching states in $O(N)$ linear time.

| Difficulty | Platform | Q.No | Question                                                | Link                                                                                                    |
| ---------- | -------- | ---- | ------------------------------------------------------- | ------------------------------------------------------------------------------------------------------- |
| Medium     | LeetCode | 3    | Longest Substring Without Repeating Characters          | https://leetcode.com/problems/longest-substring-without-repeating-characters/                           |
| Medium     | GFG      | G18  | Longest Distinct Characters in String                   | https://www.geeksforgeeks.org/problems/longest-distinct-characters-in-string5848/1                      |
| Hard       | LeetCode | 76   | Minimum Window Substring                                | https://leetcode.com/problems/minimum-window-substring/                                                |
| Hard       | GFG      | G19  | Smallest Window in a String Containing All Characters   | https://www.geeksforgeeks.org/problems/smallest-window-in-a-string-containing-all-the-characters-of-another-string-1587115621/1 |
| Medium     | LeetCode | 438  | Find All Anagrams in a String                           | https://leetcode.com/problems/find-all-anagrams-in-a-string/                                           |
| Medium     | LeetCode | 567  | Permutation in String                                   | https://leetcode.com/problems/permutation-in-string/                                                   |
| Medium     | LeetCode | 424  | Longest Repeating Character Replacement                 | https://leetcode.com/problems/longest-repeating-character-replacement/                                 |
| Medium     | GFG      | G20  | Count Distinct Elements in Every Window                 | https://www.geeksforgeeks.org/problems/count-distinct-elements-in-every-window/1                         |
| Hard       | LeetCode | 992  | Subarrays with K Different Integers                     | https://leetcode.com/problems/subarrays-with-k-different-integers/                                     |
| Medium     | LeetCode | 2799 | Count Complete Subarrays in an Array                    | https://leetcode.com/problems/count-complete-subarrays-in-an-array/                                    |
| Medium     | LeetCode | 904  | Fruit Into Baskets                                      | https://leetcode.com/problems/fruit-into-baskets/                                                       |
| Medium     | LeetCode | 1004 | Max Consecutive Ones III                                | https://leetcode.com/problems/max-consecutive-ones-iii/                                                |

---

## Level 6 — Multi-Dimensional Keys, Coordinates & Geometry Hashing

**Goal:** Learn to hash non-primitive structures: 2D coordinates, normalized slope fractions `(dy, dx)` using GCD, and subgrid indices. Avoid floating-point inaccuracies by storing reduced integer ratios.

| Difficulty | Platform | Q.No | Question                                    | Link                                                                        |
| ---------- | -------- | ---- | ------------------------------------------- | --------------------------------------------------------------------------- |
| Medium     | LeetCode | 36   | Valid Sudoku                                | https://leetcode.com/problems/valid-sudoku/                                 |
| Hard       | LeetCode | 149  | Max Points on a Line                        | https://leetcode.com/problems/max-points-on-a-line/                         |
| Hard       | GFG      | G21  | Max points on the same line                 | https://www.geeksforgeeks.org/problems/max-points-on-the-same-line/1          |
| Medium     | LeetCode | 454  | 4Sum II                                     | https://leetcode.com/problems/4sum-ii/                                      |
| Medium     | LeetCode | 1726 | Tuple with Same Product                     | https://leetcode.com/problems/tuple-with-same-product/                      |
| Medium     | LeetCode | 939  | Minimum Area Rectangle                      | https://leetcode.com/problems/minimum-area-rectangle/                       |
| Medium     | LeetCode | 447  | Number of Boomerangs                        | https://leetcode.com/problems/number-of-boomerangs/                         |
| Medium     | LeetCode | 2352 | Equal Row and Column Pairs                  | https://leetcode.com/problems/equal-row-and-column-pairs/                   |
| Medium     | LeetCode | 1814 | Count Nice Pairs in an Array                | https://leetcode.com/problems/count-nice-pairs-in-an-array/                 |

---

## Level 7 — Top-K, Frequency Buckets & Counting Reductions

**Goal:** Master sorting elements by frequency using HashMaps combined with Bucket Sort (achieving $O(N)$ linear time) or Min-Heaps ($O(N \log K)$). Understand how frequency maps guide greedy schedules and pair counts.

| Difficulty | Platform | Q.No | Question                                            | Link                                                                                |
| ---------- | -------- | ---- | --------------------------------------------------- | ----------------------------------------------------------------------------------- |
| Medium     | LeetCode | 347  | Top K Frequent Elements                             | https://leetcode.com/problems/top-k-frequent-elements/                             |
| Medium     | GFG      | G22  | Top K Frequent Elements in Array                    | https://www.geeksforgeeks.org/problems/top-k-frequent-elements-in-array/1          |
| Medium     | LeetCode | 692  | Top K Frequent Words                                | https://leetcode.com/problems/top-k-frequent-words/                                |
| Medium     | LeetCode | 621  | Task Scheduler                                      | https://leetcode.com/problems/task-scheduler/                                      |
| Medium     | LeetCode | 767  | Reorganize String                                   | https://leetcode.com/problems/reorganize-string/                                   |
| Medium     | LeetCode | 1481 | Least Number of Unique Integers after K Removals    | https://leetcode.com/problems/least-number-of-unique-integers-after-k-removals/    |
| Medium     | LeetCode | 1010 | Pairs of Songs With Total Durations Divisible by 60 | https://leetcode.com/problems/pairs-of-songs-with-total-durations-divisible-by-60/ |
| Medium     | GFG      | G23  | Array Pair Sum Divisibility Problem                 | https://www.geeksforgeeks.org/problems/array-pair-sum-divisibility-problem3257/1   |
| Medium     | LeetCode | 846  | Hand of Straights                                   | https://leetcode.com/problems/hand-of-straights/                                   |
| Medium     | LeetCode | 1296 | Divide Array in Sets of K Consecutive Numbers       | https://leetcode.com/problems/divide-array-in-sets-of-k-consecutive-numbers/       |

---

## Level 8 — Design Data Structures with HashMaps

**Goal:** Build production-grade data structures combining HashMaps with Doubly Linked Lists, Dynamic Arrays, and Timestamp trees to achieve $O(1)$ operations across all APIs.

| Difficulty | Platform | Q.No | Question                                                 | Link                                                                                          |
| ---------- | -------- | ---- | -------------------------------------------------------- | --------------------------------------------------------------------------------------------- |
| Easy       | LeetCode | 706  | Design HashMap                                           | https://leetcode.com/problems/design-hashmap/                                                 |
| Easy       | LeetCode | 705  | Design HashSet                                           | https://leetcode.com/problems/design-hashset/                                                 |
| Medium     | LeetCode | 146  | LRU Cache                                                | https://leetcode.com/problems/lru-cache/                                                      |
| Medium     | GFG      | G24  | LRU Cache                                                | https://www.geeksforgeeks.org/problems/lru-cache/1                                             |
| Hard       | LeetCode | 460  | LFU Cache                                                | https://leetcode.com/problems/lfu-cache/                                                      |
| Hard       | GFG      | G25  | LFU Cache                                                | https://www.geeksforgeeks.org/problems/lfu-cache-1665050355/1                                  |
| Medium     | LeetCode | 380  | Insert Delete GetRandom O(1)                             | https://leetcode.com/problems/insert-delete-getrandom-o1/                                     |
| Hard       | LeetCode | 381  | Insert Delete GetRandom O(1) - Duplicates allowed        | https://leetcode.com/problems/insert-delete-getrandom-o1-duplicates-allowed/                  |
| Hard       | LeetCode | 432  | All O`one Data Structure                                 | https://leetcode.com/problems/all-oone-data-structure/                                        |
| Medium     | LeetCode | 981  | Time Based Key-Value Store                               | https://leetcode.com/problems/time-based-key-value-store/                                     |
| Medium     | LeetCode | 355  | Design Twitter                                           | https://leetcode.com/problems/design-twitter/                                                 |
| Hard       | LeetCode | 895  | Maximum Frequency Stack                                  | https://leetcode.com/problems/maximum-frequency-stack/                                        |
| Medium     | GFG      | G26  | First Non-Repeating Character in a Stream                | https://www.geeksforgeeks.org/problems/first-non-repeating-character-in-a-stream1216/1        |

---

## Level 9 — String Hashing, Rolling Hash & Rabin-Karp

**Goal:** Understand polynomial rolling hash functions to compute string hashes in $O(1)$ time upon window shifts. This turns $O(N \cdot M)$ string matching into expected $O(N)$ time with minimal hash collisions.

| Difficulty | Platform | Q.No | Question                                                 | Link                                                                                          |
| ---------- | -------- | ---- | -------------------------------------------------------- | --------------------------------------------------------------------------------------------- |
| Easy       | LeetCode | 28   | Find the Index of the First Occurrence in a String       | https://leetcode.com/problems/find-the-index-of-the-first-occurrence-in-a-string/             |
| Medium     | GFG      | G27  | Search Pattern (Rabin-Karp Algorithm)                    | https://www.geeksforgeeks.org/problems/search-pattern-rabin-karp-algorithm--141631/1          |
| Medium     | LeetCode | 187  | Repeated DNA Sequences                                   | https://leetcode.com/problems/repeated-dna-sequences/                                         |
| Hard       | LeetCode | 1044 | Longest Duplicate Substring                              | https://leetcode.com/problems/longest-duplicate-substring/                                    |
| Hard       | LeetCode | 1316 | Distinct Echo Substrings                                 | https://leetcode.com/problems/distinct-echo-substrings/                                       |
| Hard       | LeetCode | 214  | Shortest Palindrome                                      | https://leetcode.com/problems/shortest-palindrome/                                            |
| Medium     | LeetCode | 718  | Maximum Length of Repeated Subarray                      | https://leetcode.com/problems/maximum-length-of-repeated-subarray/                            |

---

## Level 10 — State Hashing, Graph Hashing & Advanced Hard Problems

**Goal:** Tackle top-tier interview problems involving serialized state hashing, bidirectional BFS search with hash sets, remainder cycle tracking, and combinatorial substring matching.

| Difficulty | Platform | Q.No | Question                                                 | Link                                                                                          |
| ---------- | -------- | ---- | -------------------------------------------------------- | --------------------------------------------------------------------------------------------- |
| Hard       | LeetCode | 127  | Word Ladder                                              | https://leetcode.com/problems/word-ladder/                                                    |
| Hard       | LeetCode | 126  | Word Ladder II                                           | https://leetcode.com/problems/word-ladder-ii/                                                 |
| Hard       | LeetCode | 30   | Substring with Concatenation of All Words                | https://leetcode.com/problems/substring-with-concatenation-of-all-words/                      |
| Medium     | LeetCode | 166  | Fraction to Recurring Decimal                            | https://leetcode.com/problems/fraction-to-recurring-decimal/                                  |
| Medium     | LeetCode | 535  | Encode and Decode TinyURL                                | https://leetcode.com/problems/encode-and-decode-tinyurl/                                      |
| Medium     | LeetCode | 554  | Brick Wall                                               | https://leetcode.com/problems/brick-wall/                                                     |
| Hard       | LeetCode | 727  | Minimum Window Subsequence                               | https://leetcode.com/problems/minimum-window-subsequence/                                     |
| Hard       | LeetCode | 710  | Random Pick with Blacklist                               | https://leetcode.com/problems/random-pick-with-blacklist/                                    |
| Hard       | LeetCode | 65   | Valid Number                                             | https://leetcode.com/problems/valid-number/                                                   |
| Hard       | LeetCode | 1368 | Minimum Cost to Make at Least One Valid Path in a Grid   | https://leetcode.com/problems/minimum-cost-to-make-at-least-one-valid-path-in-a-grid/         |

---

_This is a curated, hand-picked progression rather than a literal "every question that exists" list — the goal is depth and pattern-recognition, not volume. Mastering everything above will comfortably cover Hash Maps, Hash Sets, Prefix Sum Hashing, Sliding Window Frequencies, Rolling Hash, and HashMap Design for interviews at any level._
