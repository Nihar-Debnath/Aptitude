![alt text](image-1.png)
Yes! 😄 For these questions, there is a **very easy trick**: **split the range into clean blocks** instead of checking every number.

We need:

> How many times does digit **2** appear from **112 to 375**?

### 🔥 Easiest method: Split into 3 blocks

Break it into:

**112–199 | 200–299 | 300–375**

---

### ① 112–199

Look at the **tens place**:

20–29 → **10 times**

But our range starts at 112, so tens = 2 occurs in:

120–129 → **10**

Now the **units place**:

112, 122, 132, 142, ..., 192

That's **9 times**.

So:

\[
10+9=\boxed{19}
\]

---

### ② 200–299

This is the easiest block.

Every number starts with **2**.

There are 100 numbers:

\[
\boxed{100}
\]

Then there are additional 2s:

* Tens place: 220–229 → **10**
* Units place: 202, 212, ..., 292 → **10**

So:

\[
100+10+10=\boxed{120}
\]

---

### ③ 300–375

Hundreds place → no 2.

**Tens place:**

320–329 → **10**

**Units place:**

302, 312, 322, 332, 342, 352, 362, 372

→ **8**

So:

\[
10+8=\boxed{18}
\]

---

### 🎯 Final answer

\[
19+120+18=\boxed{157}
\]

## The trick to remember

For digit-occurrence questions, **don't count number by number**.

Think:

> **Split → Hundreds → Tens → Units**

And look for blocks like:

* `200–299` → hundreds digit contributes **100**
* `220–229` → tens digit contributes **10**
* `202, 212, ...` → units digit contributes according to the range

So for exams, your mental structure should be:

**112–199 → 19**
**200–299 → 120**
**300–375 → 18**

**Answer = 157.** ✅
