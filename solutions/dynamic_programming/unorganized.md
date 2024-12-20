# LeetCode skills
## Binary tree unified stack iteration
`boolean mark` solution.

## Dynamic programming
- [647. Palindromic Substrings](https://leetcode.cn/problems/palindromic-substrings/)
- [516. Longest Palindromic Subsequence](https://leetcode.cn/problems/longest-palindromic-subsequence/)
For solving the above two issues, we can use two-dimensional array. Remember the `magic word`: **回文串，用一半，内环反**.

The principle of `dynamic programming` is **from top to bottom, from left to right, from less to more, from near to far, from known to unknown**
and **take turns being the boss**.

## Monotonic stack
* Push indies one by one.
* Only the useful indies are kept in the stack. Useless indices are popped (or eaten by followed larger (or smaller) index).

## Graph theory
The principle of traversal (DFS or BFS) between `undirected graph` or `directed graph` are similar.
* First rule: don't visited nodes again. This rule make starting from a node to traverse the `undirected graph` have a direction.
* The adjacent nodes of `undirected graph` are its non-visited neighbors.
* The adjacent nodes of `directed graph` are its targeted nodes.
