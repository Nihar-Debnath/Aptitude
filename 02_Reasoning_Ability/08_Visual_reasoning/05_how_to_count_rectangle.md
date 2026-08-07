# Method 1


Good question.

For **rectangles**, remember one important thing:

> **A square is also a rectangle.**

So if the question says **"Count Rectangles"**, you count:

* ✅ All rectangles
* ✅ All squares (because every square is a rectangle)

---

# Fast Formula

For an **m × n grid**:

\[
\boxed{\text{Rectangles}=\frac{m(m+1)\times n(n+1)}{4}}
\]

where:

* **m** = rows
* **n** = columns

---

## Example 1: 3 × 4 grid

Rows = 4, Columns = 3

\[
\frac{4\times5\times3\times4}{4}
=

60
\]

✅ **Total rectangles = 60**

Out of these:

* Squares = 20
* Non-square rectangles = 60 − 20 = **40**

---

## Example 2: 2 × 2 grid

\[
\frac{2\times3\times2\times3}{4}
=

9
\]

Rectangles are:

* 4 small squares
* 2 horizontal rectangles
* 2 vertical rectangles
* 1 big square

Total = **9**

---

# Memory Trick 🚀

### Count Squares

```
Reduce both by 1
Multiply
Add
```

Example:

```
4×3
3×2
2×1
1×0
```

---

### Count Rectangles

Just remember one formula:

\[
\boxed{\frac{m(m+1)\times n(n+1)}{4}}
\]

No repeated multiplication trick is needed.

---

### TCS Tip

If the figure is a **perfect grid**, the examiner usually asks one of these:

* **Count Squares** → Use the reduce-by-1 trick.
* **Count Rectangles** → Use the rectangle formula.
* **Count Rectangles excluding Squares** → **Rectangles − Squares**.




---
---
---
---
---


# Method 2 (this one is good and chosen one)

Yes! This is another **very popular shortcut** for counting rectangles in a **perfect grid**, and many teachers prefer it because it's easier than remembering the formula.

### The Trick

For each side of the grid, add the numbers from **1 up to the number of divisions**.

Then multiply the two sums.

---

### Example: 2 × 2 Grid

Rows = 2

```text
1 + 2 = 3
```

Columns = 2

```text
1 + 2 = 3
```

Multiply:

```text
3 × 3 = 9
```

✅ Total rectangles = **9**

---

### Example: 3 × 4 Grid

Rows = 4

```text
1 + 2 + 3 + 4 = 10
```

Columns = 3

```text
1 + 2 + 3 = 6
```

Multiply:

```text
10 × 6 = 60
```

✅ Total rectangles = **60**

---

### Why does it work?

Because:

\[
1+2+\cdots+n=\frac{n(n+1)}{2}
\]

So this shortcut is exactly the same as the rectangle formula:

\[
\frac{m(m+1)}{2}\times\frac{n(n+1)}{2}
=

\frac{m(m+1)\times n(n+1)}{4}
\]

It's just easier to calculate mentally.

---

## Which method should you use?

### Squares ✅

```text
Reduce both by 1
Multiply
Add
```

### Rectangles ✅

```text
Add 1+2+...+rows
×
Add 1+2+...+columns
```

I recommend using **this sum method** in exams because it's very fast and you don't need to memorize the rectangle formula separately.