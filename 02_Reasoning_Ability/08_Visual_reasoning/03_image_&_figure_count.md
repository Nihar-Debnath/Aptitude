![alt text](./images/image-1.png)

![alt text](./images/image-2.png)


### Shortcut

1. Find **Rows × Columns**.
2. Multiply them.
3. Reduce **both by 1**.
4. Multiply again.
5. Repeat until one becomes **0**.
6. Add all the products.

### Example (4 × 3)

```text
4 × 3 = 12
3 × 2 = 6
2 × 1 = 2
1 × 0 = 0
------------
Total = 20
```

**Memory Trick:**
**Multiply → Reduce both by 1 → Repeat → Add all products.** ✅

> **Works only for complete/perfect square grids**, not for irregular figures.




---
---
---
---

# If you dont understood what happened then this is the offical explanation


This is the **first topic: Counting Squares**.

The figure is simply a **3 × 4 grid**.

* **3 columns**
* **4 rows**

The biggest mistake beginners make is trying to count randomly. Instead, follow a **fixed-size method**.

---

# Step 1: Count all 1×1 squares

There are:

* 3 columns
* 4 rows

So,

```text
3 × 4 = 12
```

✅ **12 squares**

---

# Step 2: Count all 2×2 squares

A 2×2 square can start only where there is room.

Across:

* 3 columns → possible starting positions = 2

Down:

* 4 rows → possible starting positions = 3

So,

```text
2 × 3 = 6
```

✅ **6 squares**

---

# Step 3: Count all 3×3 squares

Across:

* 3 columns → 1 position

Down:

* 4 rows → 2 positions

So,

```text
1 × 2 = 2
```

✅ **2 squares**

---

# Step 4: Count 4×4 squares?

Impossible.

The grid has only **3 columns**, so a 4×4 square cannot fit.

✅ **0**

---

# Total

| Square Size |  Count |
| ----------- | -----: |
| 1×1         |     12 |
| 2×2         |      6 |
| 3×3         |      2 |
| **Total**   | **20** |

✅ **Answer = 20**

---

# The Formula (Very Important)

For an **m × n grid**:

To count **k × k** squares:

\[
(m-k+1)\times(n-k+1)
\]

where:

* (m) = number of columns
* (n) = number of rows
* (k) = size of the square

For this question:

* Columns = **3**
* Rows = **4**

So:

| Size | Formula        |    Count |
| ---- | -------------- | -------: |
| 1×1  | (3−1+1)(4−1+1) | 3×4 = 12 |
| 2×2  | (3−2+1)(4−2+1) |  2×3 = 6 |
| 3×3  | (3−3+1)(4−3+1) |  1×2 = 2 |

Total = **12 + 6 + 2 = 20**

---

## TCS Exam Trick 🚀

Whenever the figure is a **perfect grid** (all equal squares), **never count manually**.

Just remember:

1. Count all **1×1** squares.
2. Count all **2×2** squares.
3. Count all **3×3** squares.
4. Stop when the square no longer fits.

This method takes **10–15 seconds** in the exam.

> **Note:** This shortcut works **only for perfect grids** like this one. In later questions, TCS may give incomplete figures, overlapping squares, or extra lines. Those require different counting tricks, which we'll learn one by one.
