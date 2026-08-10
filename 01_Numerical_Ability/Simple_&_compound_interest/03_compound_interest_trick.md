![alt text](./images/image-1.png)


Yes! This is a **very useful Compound Interest shortcut**, and the left side of the board is actually showing the pattern behind it.

Let's break it down slowly. The key idea is:

> Instead of calculating the amount year-by-year, we can directly break **compound interest into parts**.

---

# 1. The example on the board

They take:

\[
P=100
\]

\[
R=10%
\]

\[
T=3\text{ years}
\]

So let's understand what happens.

### Year 1

10% of ₹100:

\[
10
\]

Amount becomes:

\[
110
\]

### Year 2

10% of ₹110:

\[
11
\]

Amount:

\[
121
\]

### Year 3

10% of ₹121:

\[
12.1
\]

Amount:

\[
133.1
\]

Therefore:

\[
CI=133.1-100
\]

\[
\boxed{CI=33.1}
\]

That's the normal method.

But the teacher is showing you a **shortcut to get 33.1 directly**.

---

# 2. Where does 30 + 3 + 0.1 come from?

Look at the board:

\[
30+3+0.1=33.1
\]

Why?

Because the compound-interest expansion for 3 years is:

\[
\boxed{3r+3r^2+r^3}
\]

where (r) is the rate written as a decimal.

Here:

\[
r=10%=0.1
\]

So:

\[
3(0.1)+3(0.1)^2+(0.1)^3
\]

\[
=0.3+0.03+0.001
\]

Since (P=100):

\[
100(0.3+0.03+0.001)
\]

\[
=30+3+0.1
\]

\[
=\boxed{33.1}
\]

That's exactly what your teacher is doing.

---

# 3. But what does the left-side pattern mean?

This is the important part.

Your teacher wrote:

### 2 years

\[
\boxed{2:1}
\]

### 3 years

\[
\boxed{3:3:1}
\]

### 4 years

\[
\boxed{4:6:4:1}
\]

These are the **binomial coefficients**.

They come from expanding:

\[
(1+r)^T
\]

For example:

### 2 years

\[
(1+r)^2
\]

becomes:

\[
1+2r+r^2
\]

So CI is:

\[
\boxed{2r+r^2}
\]

That's why:

\[
\boxed{2:1}
\]

---

### 3 years

\[
(1+r)^3
\]

becomes:

\[
1+3r+3r^2+r^3
\]

Remove the initial (1), because that's the original principal.

So CI contains:

\[
\boxed{3:3:1}
\]

That's exactly what's on your board.

---

### 4 years

\[
(1+r)^4
\]

becomes:

\[
1+4r+6r^2+4r^3+r^4
\]

Remove the first (1):

\[
\boxed{4:6:4:1}
\]

---

# 4. Now apply it to the teacher's question

We have:

\[
P=100,\quad R=10%,\quad T=3
\]

For **3 years**, remember:

\[
\boxed{3:3:1}
\]

Now calculate each part.

### First part

\[
10\times3=30
\]

### Second part

Since:

\[
10%\text{ of }10=1
\]

we get:

\[
1\times3=3
\]

### Third part

\[
10%\text{ of }1=0.1
\]

So:

\[
0.1\times1=0.1
\]

Add:

\[
30+3+0.1
\]

\[
\boxed{CI=33.1}
\]

---

# 🔥 The easiest way to remember the pattern

For compound interest:

| Time    | Pattern                 |
| ------- | ----------------------- |
| 2 years | **2 : 1**               |
| 3 years | **3 : 3 : 1**           |
| 4 years | **4 : 6 : 4 : 1**       |
| 5 years | **5 : 10 : 10 : 5 : 1** |

These are basically the coefficients from **Pascal's Triangle**.

So if you see **3 years**, immediately think:

\[
\boxed{3:3:1}
\]

If you see **4 years**:

\[
\boxed{4:6:4:1}
\]

---

## One VERY important thing

This shortcut is especially nice when the **rate is a simple percentage**, like 10%, 5%, 20%, etc.

But don't think:

> "CI = rate × this ratio"

The ratio tells you the **multipliers of successive powers of the rate**.

For 3 years:

\[
\boxed{CI=P\left[3r+3r^2+r^3\right]}
\]

where (r=R/100).

For your example:

\[
100[3(.1)+3(.1)^2+(.1)^3]
\]

\[
=100[.3+.03+.001]
\]

\[
=\boxed{33.1}
\]

So the **3 : 3 : 1 trick is really a shortcut for the expansion of compound interest**. That's why your teacher first wrote those patterns on the left.
