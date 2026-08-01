![](./images/image%20copy%204.png)


Let's solve it the way you like—**look for the pattern first**, not by trying random formulas.

### Question

Series:

```text
1, 3, 8, 20, 42
```

One term is wrong.

Options:

* A) 3
* B) 8
* C) 42
* D) 20

---

## Method 1 (Fastest)

Look at how each term is generated.

Try multiplying by 2:

```text
1 × 2 = 2
Need 3
+1
```

```text
3 × 2 = 6
Need 8
+2
```

```text
8 × 2 = 16
Need 20
+4
```

Notice the added numbers:

```text
+1
+2
+4
```

These are powers of 2:

```text
2⁰ = 1
2¹ = 2
2² = 4
```

So the next addition should be:

```text
2³ = 8
```

Therefore,

```text
20 × 2 + 8
= 40 + 8
= 48
```

But the series has **42**.

So **42 is the erroneous term.**

✅ **Answer: C) 42**

---

## Pattern

The correct series should be:

```text
1
3   = 1×2 + 1
8   = 3×2 + 2
20  = 8×2 + 4
48  = 20×2 + 8
```

---

## Exam Trick

Whenever you see a series like:

```text
1, 3, 8, 20, ...
```

Check these common patterns in order:

1. ✅ Difference
2. ✅ Difference of differences
3. ✅ ×2, ×3, ×4...
4. ✅ ×2 ± powers of 2 (**this question**)
5. ✅ Squares/Cubes
6. ✅ Prime numbers/Fibonacci

Since this is an **error detection** question, you don't have to find the next term—you only need to identify **which existing term breaks the pattern**.

**Answer: \(\boxed{42}\)** ✅



---
---
---
---
---
---
---




Excellent question.

**You should NOT get this logic immediately.** This is exactly what aptitude examiners want—to make you think, *"How was I supposed to know that?"*

The real skill is knowing **which patterns to test**.

Let me show you my thinking process.

---

# Given

```text
1, 3, 8, 20, 42
```

## Step 1: Check differences (Always first)

```text
3-1 = 2

8-3 = 5

20-8 = 12

42-20 = 22
```

Differences:

```text
2, 5, 12, 22
```

No obvious pattern.

---

## Step 2: Check second differences

```text
5-2 = 3

12-5 = 7

22-12 = 10
```

```text
3, 7, 10
```

Again, no obvious pattern.

❌ Move on.

---

## Step 3: Check multiplication

This is the next thing experienced aptitude solvers do.

Ask yourself:

> Is every term approximately 2 times the previous one?

Let's see.

```
1 → 3
```

3 is close to 2.

```
3 → 8
```

8 is close to 6.

```
8 → 20
```

20 is close to 16.

```
20 → 42
```

42 is close to 40.

Notice something?

Every next number is **a little bigger than double**.

So write it like this:

| Previous | ×2 | Actual | Extra |
| -------- | -- | ------ | ----- |
| 1        | 2  | 3      | +1    |
| 3        | 6  | 8      | +2    |
| 8        | 16 | 20     | +4    |
| 20       | 40 | 42     | +2    |

Now look only at the **Extra** column.

```text
+1
+2
+4
+2
```

Immediately you notice

```
1
2
4
```

These are

```
2⁰
2¹
2²
```

The next should be

```
2³ = 8
```

But instead we got **+2**.

Therefore

```
20×2+8

=48
```

not

```
42
```

So **42** is wrong.

---

# But how did I think of checking ×2?

This comes from experience.

Whenever numbers are increasing quickly, check:

```
×2

×3

×4

×2±1

×2±2

×2+increasing

×3−1
```

These are **very common aptitude patterns**.

---

# Think of it like a checklist

Whenever you see a series, don't randomly guess.

Go through this order.

### Level 1

```
✓ + constant

✓ - constant
```

Example

```
2 5 8 11
```

---

### Level 2

```
✓ +2 +4 +6

✓ +3 +6 +9
```

Example

```
3 5 9 15
```

---

### Level 3

```
✓ Difference of differences
```

---

### Level 4

```
✓ ×2

✓ ×3

✓ ×2+1

✓ ×2−1

✓ ×2+2

✓ ×2+powers
```

---

### Level 5

```
✓ Squares

✓ Cubes

✓ Prime numbers

✓ Fibonacci
```

---

# This is why coaching teachers solve these so fast.

They are **not discovering the pattern from scratch** each time.

They mentally test a small set of common patterns:

```
Addition?
↓

Differences?
↓

Multiplication?
↓

Squares/Cubes?
↓

Prime/Fibonacci?
↓

Alternating pattern?
```

As soon as one fits, they stop.

---

## For TCS, Cognizant, Wipro, Accenture

I can also give you a **master list of about 40–50 number series patterns**. These cover **95%+** of the number series questions asked in placement aptitude tests. Once you know that checklist, you'll know exactly what to test first instead of feeling like the pattern came out of nowhere.
