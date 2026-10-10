![alt text](./images/image-1.png)

Let's understand exactly what that board is doing.

---

# 1. The basic idea

Suppose:

* Principal = ₹100
* Rate = 10% per year
* Time = 3 years

In CI, **each year's interest gets added to the principal**, so the next year's interest is calculated on a bigger amount.

Instead of repeatedly calculating:

> Year 1 → Year 2 → Year 3

we can use these **year-coefficient ratios**.

### For 2 years:

\[
\boxed{2:1}
\]

### For 3 years:

\[
\boxed{3:3:1}
\]

### For 4 years:

\[
\boxed{4:6:4:1}
\]

Just remember the patterns.

---

# 2. Why does 3 years give `3 : 3 : 1`?

Let's use ₹100 and 10%.

Imagine the interest components.

### First year

10% of ₹100 = ₹10

### Second year

The previous ₹10 also earns interest.

So there are interest components:

* ₹10 from the first year
* ₹10 from the second year's effect
* ₹1 interest on the previous ₹10

### Third year

The contributions ultimately form:

\[
10\times3 + 1\times3 + 0.1\times1
\]

That's exactly what the board is doing:

```text
10 × 3 = 30
1 × 3  = 3
0.1 × 1 = 0.1

Total = 33.1
```

So:

\[
\boxed{CI=33.1}
\]

for ₹100 at 10% for 3 years.

And therefore:

\[
A=100+33.1=\boxed{133.1}
\]

---

# 3. The vertical line on the board

This is actually the **most important part to understand**.

The teacher starts with:

```text
₹100
 ↓ 10%
 ₹10
 ↓ 10%
 ₹1
 ↓ 10%
 ₹0.1
```

So the numbers are:

\[
100,\ 10,\ 1,\ 0.1
\]

These represent the **different levels of interest generated**.

Then we use the appropriate year ratio.

For **3 years**, ratio is:

\[
\boxed{3:3:1}
\]

So:

```text
10 × 3 = 30
1 × 3  = 3
0.1 × 1 = 0.1
```

Add them:

\[
30+3+0.1=\boxed{33.1}
\]

That's the **CI directly**.
