![alt text](image-1.png)



Yes! This looks scary, but there’s a **very quick factorization trick**.

Given:

\[
(76-a)(76-b)(76-c)(76-d)(76-e)=1127
\]

### Step 1: Factorize 1127

\[
1127=49\times23=7\times7\times23
\]

We need **5 distinct integer factors**. We can write:

\[
1127=23\times7\times1\times(-1)\times(-7)
\]

Notice all 5 are distinct.

### Step 2: Use ascending order

Given:

\[
a<b<c<d<e
\]

Therefore:

\[
76-a>76-b>76-c>76-d>76-e
\]

So assign them in descending order:

\[
23,\quad7,\quad1,\quad-1,\quad-7
\]

Thus:

\[
76-a=23\Rightarrow a=53
\]

\[
76-b=7\Rightarrow b=69
\]

\[
76-c=1\Rightarrow c=75
\]

\[
76-d=-1\Rightarrow d=77
\]

\[
76-e=-7\Rightarrow e=83
\]

### Step 3: Asked (a+b+c+d)

\[
53+69+75+77=\boxed{274}
\]

✅ **Answer: B. 274**

**Shortcut to remember:** When they ask for **distinct integer factors** and you don't have enough positive factors, think about **(1,-1)** and negative factor pairs.



---
---
---
---


Good! Step 2 is actually the most important part. Let's go very slowly.

We know:

\[
a<b<c<d<e
\]

This means **a is the smallest** and **e is the largest**.

Now look at the expression:

\[
76-a,;76-b,;76-c,;76-d,;76-e
\]

When you **subtract a larger number from 76, the result becomes smaller.**

### Example

Suppose

\[
a=10,;b=20,;c=30
\]

Then

\[
76-10=66
\]

\[
76-20=56
\]

\[
76-30=46
\]

Notice:

\[
10<20<30
\]

but

\[
66>56>46
\]

The order gets **reversed**.

---

### So in our question

We found the five values must be

\[
23,;7,;1,;-1,;-7
\]

Since

\[
76-a>76-b>76-c>76-d>76-e
\]

we **must** arrange them from **largest to smallest**:

\[
76-a=23
\]

\[
76-b=7
\]

\[
76-c=1
\]

\[
76-d=-1
\]

\[
76-e=-7
\]

Then solve each one:

* \(76-a=23 \Rightarrow a=53\)
* \(76-b=7 \Rightarrow b=69\)
* \(76-c=1 \Rightarrow c=75\)
* \(76-d=-1 \Rightarrow d=77\)
* \(76-e=-7 \Rightarrow e=83\)

Now check:

\[
53<69<75<77<83
\]

which matches the condition.

---

### ⭐ Trick for exams

Whenever you see:

\[
k-a,;k-b,;k-c
\]

and

\[
a<b<c,
\]

**always remember:**

\[
k-a>k-b>k-c
\]

👉 **Subtracting from the same number reverses the order.**

This single trick appears quite often in TCS aptitude.
