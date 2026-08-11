![alt text](./images/image-8.png)

Yep! 😄 This one is **very similar to the previous question**, but there's a small twist.

We have:

> **CAP → 61**

Find:

> **PEN → ?**

Options:

```text
A. 40
B. 66
C. 80
D. 46
```

## Step 1: Try normal alphabet positions

Remember:

```text
A=1, B=2, C=3, ... Z=26
```

For **CAP**:

```text
C = 3
A = 1
P = 16
```

Add:

\[
3+1+16=20
\]

But given code is **61**.

❌ So this is **NOT normal alphabet positions**.

---

# Step 2: Try reverse alphabet positions 🔥

Remember the reverse alphabet:

```text
A = 26
B = 25
C = 24
D = 23
...
X = 3
Y = 2
Z = 1
```

Or use the shortcut:

\[
\boxed{\text{Reverse position}=27-\text{normal position}}
\]

For **CAP**:

### C

Normal position = 3

\[
27-3=24
\]

So:

**C = 24**

### A

\[
27-1=26
\]

So:

**A = 26**

### P

Normal position = 16

\[
27-16=11
\]

So:

**P = 11**

Now add:

\[
24+26+11=61
\]

🎯 Exactly the given code!

So we've discovered the rule:

> **Convert each letter to its reverse alphabet position and ADD them.**

---

# Step 3: Now solve PEN

### P

Normal position = 16

\[
27-16=11
\]

### E

Normal position = 5

\[
27-5=22
\]

### N

Normal position = 14

\[
27-14=13
\]

Now add:

\[
11+22+13
\]

\[
=46
\]

# ✅ Answer = **46**

### **Option D**

---

## 🧠 The important lesson

When you see:

> **CAP is coded as 61**

Don't immediately assume:

```text
A=1, B=2, C=3...
```

### Test it!

```text
CAP
3 + 1 + 16 = 20 ❌
```

Then try reverse:

```text
C = 24
A = 26
P = 11

24 + 26 + 11 = 61 ✅
```

So the rule is confirmed.

---

### 🔥 And remember your shortcut

For reverse alphabet:

\[
\boxed{27-\text{normal position}}
\]

So for **PEN**:

```text
P = 27 - 16 = 11
E = 27 - 5  = 22
N = 27 - 14 = 13

11 + 22 + 13 = 46
```

**Final: 46 (D)** 🎯
