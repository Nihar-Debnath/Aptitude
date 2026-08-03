![](./images/image%20copy%2011.png)


The easiest way to solve a **Figure Matrix** is to **look for one changing property at a time**, instead of looking at the whole figure.

Let's solve this together.

---

# Step 1: Observe the head shape

There are **3 different head shapes**:

* ○ Circle
* ▽ Inverted Triangle
* ⬡ Octagon

Write only the heads:

```text
Row 1 :  ○   ▽   ⬡

Row 2 :  ▽   ⬡   ○

Row 3 :  ⬡   ○   ?
```

Can you see the pattern?

Each row is just the previous row shifted left.

```text
○  ▽  ⬡
▽  ⬡  ○
⬡  ○  ▽
```

So the missing head **must be an inverted triangle (▽).**

Now only **Options (1), (3), and (4)** remain.

---

# Step 2: Observe the arm position

There are **3 arm styles**.

Let's name them:

### Style A (Arms Up)

```text
 \ /
  |
```

### Style B (Arms Down)

```text
/ \
 |
```

### Style C (No Arms)

```text
—
|
```

Now write only the arm styles.

```text
Row 1 :  A   B   C

Row 2 :  C   A   B

Row 3 :  B   C   ?
```

Again, it's the same shifting pattern.

So the missing figure must have **Style A (arms up).**

Now check the remaining options.

* Option 1 → No ❌
* Option 3 → Arms down ❌
* Option 4 → Arms up ✅

---

# Step 3: Check the base (for confirmation)

The base pattern also follows the same cycle, and **Option 4** matches it.

---

# Final Answer

✅ **Option (4)**

---

# The General Method for Every Figure Matrix Question

Whenever you see a figure matrix, **don't try to understand the entire figure at once.**

Break it into separate properties.

For example:

```
✓ Shape
✓ Size
✓ Number of dots
✓ Arms
✓ Head
✓ Base
✓ Rotation
✓ Shading
✓ Direction
```

Then make a small table like this:

| Property | Row 1 | Row 2 | Row 3 |
| -------- | ----- | ----- | ----- |
| Head     | ○ ▽ ⬡ | ▽ ⬡ ○ | ⬡ ○ ▽ |
| Arms     | A B C | C A B | B C A |

Once you identify the pattern for each property separately, the answer usually becomes obvious.

This "break the figure into independent features" technique is how experienced test-takers solve Figure Matrix questions quickly, and it's the approach you should use in placement exams like TCS, Cognizant, Infosys, Wipro, and Capgemini.
