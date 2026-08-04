# LeetCode Solutions in Pure C 🚀

Welcome to my repository containing solutions to **LeetCode algorithm problems**, written entirely in **pure C language**. This project focuses on building deep understandings of memory management, low-level optimization, and manual data structure implementations.

---

## 💡 About LeetCode
[LeetCode](https://leetcode.com) is a premier online platform designed to help software engineers practice coding skills, prepare for technical interviews, and master data structures and algorithms. 

### Why Use LeetCode?
* **Interview Preparation**: It mirrors the technical assessment environments used by major tech companies like Google, Meta, Apple, and Amazon.
* **Massive Problem Library**: Offers over 3,000 algorithmic questions across three distinct difficulty tiers: **Easy**, **Medium**, and **Hard**.
* **Instant Feedback**: Validates your code against extensive, hidden test suites to measure execution speed (runtime percentile) and memory efficiency.

### The C Language Advantage on LeetCode
While many developers use high-level languages like Python or Java, solving LeetCode problems in C offers unique engineering insights:
* **No Abstractions**: You do not have built-in collections like `std::vector`, `std::map`, or automatic garbage collection. Every hash map, stack, and queue must be designed by hand.
* **Manual Memory Tracking**: You gain a deep mastery over the stack and the heap by manually implementing `malloc()`, `calloc()`, and managing memory lifetimes with `free()`.
* **Bare-Metal Speed**: C programs regularly score in the **Top 95%+ for runtime speed** on the LeetCode leaderboard due to minimal runtime overhead and rapid pointer arithmetic.

---

## 📊 Progress Tracker

| # | Title | Solution | Difficulty | Time | Space | Tags |
|---|---|:---:|:---:|:---:|:---:|---|
| 0001 | [Two Sum](https://leetcode.comproblems/two-sum/) | [C](./Problems/0001-Two-Sum/solution.c) | Easy | $O(N)$ | $O(N)$ | Array, Hash Table |
| 0002 | [Add Two Numbers](https://leetcode.comproblems/add-two-numbers/) | [C](./Problems/0002-Add-Two-Numbers/solution.c) | Medium | $O(\max(M,N))$ | $O(1)$ | Linked List, Math |
| 0003 | [Longest Substring Without Repeating Characters](https://leetcode.comproblems/longest-substring-without-repeating-characters/) | [C](./Problems/0003-Longest-Substring-Without-Repeating-Characters/solution.c) | Medium | $O(N)$ | $O(1)$ | Hash Table, String, Sliding Window |
| 0004 | [Median of Two Sorted Arrays](https://leetcode.comproblems/median-of-two-sorted-arrays/) | [C](./Problems/0004-Median-of-Two-Sorted-Arrays/solution.c) | Hard | $O(\log(M+N))$ | $O(1)$ | Array, Binary Search |

---

## 🛠️ Compilation & Testing

You can easily compile and test these solutions on your local machine using standard compilers like GCC.

### Prerequisites
Make sure you have GCC and GNU Make installed:
* **Linux/Ubuntu**: `sudo apt install build-essential`
* **macOS**: `xcode-select --install`
* **Windows**: Install MinGW GCC and GNU Make

### Run a Solution
Navigate to any problem subdirectory to compile and run your custom local test harness:
```bash
gcc solution.c -o solution -Wall -O2
./solution
```

---

## 📜 License
This repository is licensed under the [MIT License](LICENSE). Feel free to fork, learn, and use the code snippets for your personal preparation!

---
*Keep coding, optimized down to the bare metal!* 💻
