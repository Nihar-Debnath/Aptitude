![alt text](./images/image-9.png)

# always check the options first to eliminate

Ahhh, this one has a **hidden pattern**, but we can crack it systematically. 🔥

Given:

> **5 + 3 + 2 = 151022**
> **9 + 2 + 4 = 183652**
> **8 + 6 + 3 = 482466**
> **5 + 4 + 5 = 202541**

Find:

> **7 + 2 + 5 = ?**

Options:

* A. **143547**
* B. 132234
* C. 2577224
* D. 112321

---

# Step 1: Don't treat `151022` as one number

This is the BIG clue.

Break it into **three parts**:

```text
5 + 3 + 2 → 15 | 10 | 22
```

Now see if these parts come from the three numbers.

### First example

```text
5, 3, 2

5 × 3 = 15
5 × 2 = 10
```

So we have:

```text
15 | 10 | 22
```

We found the first two:

**5 × 3 = 15**

**5 × 2 = 10**

Now we need to figure out where **22** comes from.

---

# Step 2: Look at the other examples

### Example 2

```text
9 + 2 + 4 → 18 | 36 | 52
```

First:

```text
9 × 2 = 18 ✅
```

Second:

```text
9 × 4 = 36 ✅
```

Now look at the third:

```text
18 + 36 = 54
```

But the answer is **52**.

What's the difference?

```text
54 - 52 = 2
```

And **2 is the middle number!**

So:

[
18+36-2=52
]

---

# Step 3: Check with the other examples

This is important — **never accept a pattern after checking only one example.**

### Example 3

```text
8 + 6 + 3 → 48 | 24 | 66
```

First:

```text
8 × 6 = 48
```

Second:

```text
8 × 3 = 24
```

Third:

```text
48 + 24 - 6
= 66
```

✅ Perfect!

---

### Example 4

```text
5 + 4 + 5 → 20 | 25 | 41
```

First:

```text
5 × 4 = 20
```

Second:

```text
5 × 5 = 25
```

Third:

```text
20 + 25 - 4
= 41
```

✅ Perfect again!

So we've confirmed the rule.

---

# 🧠 The rule

For:

```text
A + B + C
```

The code is:

### Part 1

[
A\times B
]

### Part 2

[
A\times C
]

### Part 3

[
(A\times B)+(A\times C)-B
]

---

# Step 4: Now solve 7 + 2 + 5

We have:

```text
A = 7
B = 2
C = 5
```

### First part

[
7\times2=14
]

### Second part

[
7\times5=35
]

### Third part

[
14+35-2=47
]

Therefore:

```text
14 | 35 | 47
```

Join them:

# 🎯 **143547**

### ✅ Answer: **A. 143547**

---

## 🔥 And here's a very useful exam habit

When you see a long number like:

**151022**

Don't immediately try to calculate with the whole thing.

Look for **chunks**:

```text
151022
 ↓
15 | 10 | 22
```

Then compare those chunks with the original numbers.

Here:

```text
5 + 3 + 2
↓   ↓   ↓

5×3 = 15
5×2 = 10
15+10-3 = 22
```

So:

[
\boxed{15|10|22}
]

And that's the whole trick.

**Your final answer = 143547 (A).** 🎯
