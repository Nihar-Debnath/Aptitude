![alt text](./images/image.png)


Yes — **before calculating, the most important thing is deciding whether this is Permutation or Combination.** Let's do that first.

## Question

> If we have **10 people and 4 chairs**, what are the number of ways to seat them?

### Step 1: Ask: "What is happening?"

We have:

**10 people**

but only

**4 chairs**

So we need to:

1. **Choose 4 people** from the 10.
2. **Arrange those 4 people** in the 4 chairs.

And because the chairs have positions, **order matters**.

For example:

```text
Chair 1   Chair 2   Chair 3   Chair 4
   A         B         C         D
```

is different from:

```text
Chair 1   Chair 2   Chair 3   Chair 4
   B         A         C         D
```

So this is a **Permutation**.

---

# Why not Combination?

Combination would be used if the question were:

> "Choose 4 people from 10 people."

Then:

[
{}^{10}C_4
]

because we only care **which 4 people** were chosen.

But here it says **"seat them"**.

Once we choose the 4 people, we have to decide:

> Who sits in Chair 1?
> Who sits in Chair 2?
> Who sits in Chair 3?
> Who sits in Chair 4?

So **order matters → Permutation.**

---

# Now solve it

We have:

[
n=10
]

people and

[
r=4
]

chairs.

So:

[
{}^{10}P_4
]

Using:

[
{}^nP_r=n(n-1)(n-2)\cdots
]

Take **4 terms**:

[
10\times9\times8\times7
]

Calculate:

[
10\times9=90
]

[
8\times7=56
]

[
90\times56=\boxed{5040}
]

### ✅ Answer: **A) 5040**

---

## But understand it without the formula

Imagine the 4 chairs:

```text
Chair 1    Chair 2    Chair 3    Chair 4
   _          _          _          _
```

### Chair 1

You have **10 choices**.

### Chair 2

One person is already seated, so **9 choices** remain.

### Chair 3

Now **8 choices** remain.

### Chair 4

Now **7 choices** remain.

Therefore:

[
10\times9\times8\times7
]

[
=\boxed{5040}
]

---

### 🔥 The decision-making trick

Whenever you see a P&C question, **don't immediately look for a formula.**

Ask:

**1. Am I only selecting?**

→ Combination (C)

**2. Am I selecting AND arranging/assigning positions?**

→ Permutation (P)

Here:

> **10 people → only 4 can sit → choose 4 + arrange them in chairs**

Therefore:

[
\boxed{{}^{10}P_4=5040}
]

And notice this connects directly to what we learned earlier:

[
\boxed{{}^{10}P_4={}^{10}C_4\times4!}
]

**Choose 4 people first, then arrange those 4 people in 4 chairs.** That's exactly why permutation = combination × arrangement.
