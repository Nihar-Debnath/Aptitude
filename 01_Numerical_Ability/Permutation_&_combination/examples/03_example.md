!\[alt text](image-2.png)

T\his one is **Combination**, not Permutation. The key word is **“committee”**.

### Question

> Form a committee of **4 men and 2 women** from **6 men and 5 women**.

### Step 1: Ask whether order matters

Does it matter who is chosen first?

For example, a committee containing:

**A, B, C, D**

is exactly the same committee as:

**D, C, B, A**.

There are no positions like captain, secretary, chairman, etc.

So **order does NOT matter** → **Combination (C)**.

---

### Step 2: Choose 4 men from 6

We have:

\[
{}^6C_4
\]

Using your shortcut:

\[
{}^6C_4={}^6C_{6-4}={}^6C_2
\]

Now calculate:

\[
{}^6C_2=\frac{6\times5}{1\times2}
\]

\[
=15
\]

So there are **15 ways to choose the men**.

---

### Step 3: Choose 2 women from 5

\[
{}^5C_2
\]

Using the shortcut:

\[
\frac{5\times4}{1\times2}=10
\]

So there are **10 ways to choose the women**.

---

### Step 4: Combine the two choices

For **each** way of choosing the 4 men, we can choose the 2 women in 10 ways.

Therefore:

\[
15\times10
\]

\[
=\boxed{150}
\]

### ✅ Answer: **C) 150**

---

### The important pattern to learn 🔥

Whenever a question says:

> **"A committee/team/group consisting of X men and Y women..."**

Usually you do:

\[
\boxed{{}^{\text{men available}}C_{\text{men needed}}
\times
{}^{\text{women available}}C_{\text{women needed}}}
\]

Here:

\[
\boxed{{}^6C_4\times{}^5C_2}
\]

\[
=15\times10
\]

\[
=\boxed{150}
\]

**Why multiply?** Because you're making **two independent selections**: choose the men **AND** choose the women.
