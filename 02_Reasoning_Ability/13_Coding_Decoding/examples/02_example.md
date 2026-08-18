![alt text](./images/image-6.png)

OHH yes 😄 — this one is a **different type of Coding–Decoding**. Here we convert letters into their **alphabet positions**.

Let's do it from absolute zero.

## Given

> **SNOW → 7100**

Find:

> **WALL → ?**

Options:

* A. 5000
* B. 4700
* C. 4800
* D. 4000

---

# Step 1: Convert each letter into its alphabet position

Remember:

```text
A=1, B=2, C=3, ... Z=26
```

For **SNOW**:

```text
S = 19
N = 14
O = 15
W = 23
```

Now add them:

\[
19+14+15+23 = 71
\]

And the given code is:

```text
SNOW → 7100
```

So what happened?

```text
19 + 14 + 15 + 23
          ↓
         71
          ↓
        7100
```

The rule is:

> **Add the alphabet positions, then multiply by 100.**

---

# Step 2: Apply the same rule to WALL

Convert:

```text
W = 23
A = 1
L = 12
L = 12
```

Add:

\[
23+1+12+12
\]

\[
=48
\]

Now multiply by 100:

\[
48\times100=4800
\]

# ✅ Answer: **4800 — Option C**

---

## 🔥 But here's your shortcut: CHECK OPTIONS FIRST

You asked me to check the options first, so let's do that too.

All options are:

```text
5000
4700
4800
4000
```

They're all multiples of **100**.

That strongly suggests we're probably going to get something like:

> **alphabet-position sum × 100**

Then we verify it using SNOW.

```text
SNOW
19 + 14 + 15 + 23
= 71
→ 7100 ✅
```

So we're confident.

Then:

```text
WALL
23 + 1 + 12 + 12
= 48
→ 4800
```

### 🧠 Remember this pattern

Whenever you see something like:

**WORD → 7100**

Try:

### **Alphabet positions → Add → Apply the indicated number pattern**

For this question:

\[
\boxed{A=1,\ B=2,\ldots,Z=26}
\]

\[
\boxed{\text{Code}=(\text{sum of letter positions})\times100}
\]

So:

\[
\boxed{WALL=4800}
\]

**Option C.** 🎯
