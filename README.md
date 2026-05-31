# 🚀 CP-CF-Journey

Welcome to my competitive programming repository! This is a dedicated space where I archive my solutions, track my performance consistency, and document core algorithmic patterns as I tackle problems on Codeforces and LeetCode.

---

## 📊 Current Progress

* **Codeforces (Div. 4 / Div. 3/ Div. 2):**
  * 🔹 **900 Rated Problems:** 2 Solved
    * `1837B` - Comparison String (Strings / Greedy)
    * `1807D` - Odd Queries (Prefix Sums / Range Queries)

---

## 🧠 Key Patterns Mastered

### 1. Prefix Sum Arrays (`O(1)` Range Queries)
* **Problem Focus:** `1807D - Odd Queries`
* **The Takeaway:** Learned to completely avoid an $O(n \cdot q)$ Time Limit Exceeded (TLE) brute force. By precomputing a 1-indexed prefix sum array of size `n + 1`, any subarray range sum can be calculated instantly in constant time.

$$\text{Range Sum} = \text{pre}[r] - \text{pre}[l - 1]$$

* **Gotcha Fixed:** Mastered the 1-based index shifting trick to permanently prevent "out of bounds" runtime errors.
