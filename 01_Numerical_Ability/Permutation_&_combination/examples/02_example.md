![alt text](./images/image-1.png)

Yep! This is a **Permutation** question, and the key is to notice the words **“starting with a”** and **“ending with z.”**

Let's go step by step.

### Question

> In how many ways can we form a **5-letter word**, with **no repetition**, starting with **a** and ending with **z**?

---

### Step 1: Make the 5 positions

```text
Position:   1     2     3     4     5
            _     _     _     _     _
```

The question says:

**Starting with `a`** → position 1 is fixed.

**Ending with `z`** → position 5 is fixed.

So:

```text
Position:   1     2     3     4     5
            a     _     _     _     z
```

We don't have to choose `a` or `z`. They are already fixed.

---

### Step 2: How many letters are left?

English alphabet has **26 letters**.

We've already used:

* `a`
* `z`

So:

\[
26-2=24
\]

There are **24 letters available** for the middle 3 positions.

```text
a     _     _     _     z
      ↑     ↑     ↑
     24    23    22
```

---

### Step 3: Fill the middle positions

For the first empty position:

\[
24\text{ choices}
\]

After choosing one letter, because **no repetition**:

\[
23\text{ choices}
\]

Then:

\[
22\text{ choices}
\]

So:

\[
24\times23\times22
\]

\[
=\boxed{12144}
\]

### ✅ Answer: **12,144**

---

## But WHY is this Permutation?

This is important.

Suppose we choose:

**b, c, d**

For the middle:

```text
a b c d z
```

is different from:

```text
a c b d z
```

because they form different words.

So **order matters**.

Therefore → **Permutation**.

We are arranging 3 letters selected from 24:

\[
{}^{24}P_3
\]

And using your permutation shortcut:

\[
{}^{24}P_3
=
24\times23\times22
\]

\[
\boxed{12144}
\]

### 🔥 Exam thought process

Whenever you see:

> **starting with X / ending with Y / fixed position**

**First fix those positions.**

Then ask:

> How many positions are left?

Then:

> How many letters/items are available?

Then use **Permutation** if the remaining things are being arranged.

Here:

**5 positions → 2 fixed → 3 positions left**

**26 letters → 2 used → 24 available**

So:

\[
\boxed{{}^{24}P_3=24\times23\times22=12144}
\]
