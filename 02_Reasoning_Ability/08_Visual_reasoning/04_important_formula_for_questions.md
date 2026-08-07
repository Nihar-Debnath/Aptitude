![alt text](./images/image-3.png)

This formula is **only for an n × n square grid** (same number of rows and columns).

The formula is:

\[
1^2+2^2+3^2+\cdots+n^2=\frac{n(n+1)(2n+1)}{6}
\]

It directly gives the **total number of squares**.

### Example 1: 3 × 3 grid

\[
\frac{3(3+1)(2\times3+1)}{6}
=

\frac{3\times4\times7}{6}
=14
\]

Or manually:

```text
1×1 = 9
2×2 = 4
3×3 = 1
-----------
Total = 14
```

---

### Example 2: 4 × 4 grid

\[
\frac{4(5)(9)}{6}
=

30
\]

Or manually:

```text
4×4 = 16
3×3 = 9
2×2 = 4
1×1 = 1
-----------
Total = 30
```

Notice:

```text
16 + 9 + 4 + 1
= 4² + 3² + 2² + 1²
= 30
```

---

### Example 3: 5 × 5 grid

\[
\frac{5(6)(11)}{6}
=55
\]

or

```text
25 + 16 + 9 + 4 + 1
=55
```

---

## Memory Trick

For an **n × n** grid:

```text
Total Squares = 1² + 2² + 3² + ... + n²
```

or directly,

\[
\boxed{\frac{n(n+1)(2n+1)}{6}}
\]

### Important

* ✅ Use this formula only when the grid is **n × n** (e.g., 3×3, 4×4, 5×5).
* ❌ For **m × n** grids (like 3×4 or 4×6), this formula **does not work**. Use the shortcut you learned:

```text
m×n
(m−1)×(n−1)
(m−2)×(n−2)
...
until one becomes 0
```

That is the fastest method for rectangular grids.
