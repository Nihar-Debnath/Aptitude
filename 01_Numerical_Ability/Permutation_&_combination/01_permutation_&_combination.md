Perfect. **Permutation & Combination (P&C)** is a very important Numerical Ability chapter, and the biggest thing is **not to memorize formulas first**. We should understand the difference between the two.

## 1. The basic idea

Suppose you have 3 people:

**A, B, C**

You want to arrange them in 3 seats:

```text
_   _   _
```

Possible arrangements include:

* ABC
* ACB
* BAC
* BCA
* CAB
* CBA

There are **6 different arrangements**.

This is **Permutation** because **order matters**.

For example:

> ABC and BAC

are different arrangements.

---

## 2. Combination

Now suppose you have the same 3 people:

**A, B, C**

But instead of arranging them, you simply want to **choose 2 people**.

Possible groups:

* AB
* AC
* BC

That's it.

Here:

> AB and BA are the **same group**.

Because we're only selecting people, not arranging them.

This is **Combination** because **order does NOT matter**.

---

## The golden rule 🔥

Before using any formula, ask:

> **"Does order matter?"**

### If YES → Permutation

Examples:

* Arrange people in seats
* Arrange letters
* Make a password
* Give 1st, 2nd and 3rd positions
* Arrange books on a shelf

### If NO → Combination

Examples:

* Select a team
* Choose 3 students
* Select 5 questions
* Choose committee members
* Select fruits/items

---

## 3. The formulas

### Permutation

Selecting and arranging **r objects from n objects**:

\[
\boxed{{}^nP_r=\frac{n!}{(n-r)!}}
\]

### Combination

Selecting **r objects from n objects**:

\[
\boxed{{}^nC_r=\frac{n!}{r!(n-r)!}}
\]

And notice something important:

\[
\boxed{{}^nP_r={}^nC_r\times r!}
\]

Why?

Because after choosing the (r) objects, you can arrange those (r) objects in:

\[
r!
\]

ways.

---

### Let's take one tiny example

There are **5 students**: A, B, C, D, E.

You need to select **2 students**.

Since we're just selecting:

\[
{}^5C_2
\]

\[
=\frac{5!}{2!3!}
\]

\[
=\boxed{10}
\]

But if you need to select **captain and vice-captain**, order/position matters.

A-B is different from B-A.

So:

\[
{}^5P_2
\]

\[
=\frac{5!}{3!}
\]

\[
=5\times4
\]

\[
=\boxed{20}
\]

That's the **core difference**.

> **Combination = choose**
> **Permutation = choose + arrange**

We'll build the chapter from this basic idea rather than jumping straight into complicated formulas.














---
---
---


Ahh yes — **this is much easier if you forget the formula for a moment.** Let's understand why

\[
\boxed{{}^nP_r={}^nC_r\times r!}
\]

using a real-life example.

## Imagine 5 people and 2 chairs

There are 5 people:

**A, B, C, D, E**

And you have **2 chairs**:

```text
Chair 1    Chair 2
  _          _
```

You want to put **2 people** into these chairs.

---

### Step 1: First, CHOOSE 2 people

Suppose you choose:

**A and B**

That's a **combination**.

Why?

Because at this stage, you're only asking:

> "Which 2 people are going to sit?"

The answer is **A and B**.

It doesn't matter whether you write:

* AB
* BA

They're the same two people.

So we're doing:

\[
{}^5C_2
\]

---

### Step 2: Now ARRANGE those 2 people

You have chosen:

**A and B**

But there are two chairs:

```text
Chair 1    Chair 2
   A          B
```

OR

```text
Chair 1    Chair 2
   B          A
```

These are **two different arrangements**.

So the 2 selected people can be arranged in:

\[
2!=2\times1=2
\]

ways.

Therefore:

\[
{}^5P_2={}^5C_2\times2!
\]

---

## Let's actually count everything

First choose 2 people from 5:

\[
{}^5C_2=10
\]

There are 10 possible pairs.

For **each pair**, there are **2 ways to arrange them**.

So:

\[
10\times2=20
\]

Therefore:

\[
{}^5P_2=20
\]

---

# The whole concept in one sentence

### Combination:

**First choose the people.**

### Permutation:

**Choose the people + arrange them.**

That's why:

\[
\boxed{\text{Permutation}=\text{Combination}\times\text{arrangements}}
\]

And the number of ways to arrange (r) selected things is:

\[
r!
\]

So:

\[
\boxed{{}^nP_r={}^nC_r\times r!}
\]

---

## Another very real example: Captain & Vice-Captain

Suppose there are **5 students** and you need:

> 1 Captain + 1 Vice-Captain

### First choose 2 students

Maybe you choose:

**A and B**

That's:

\[
{}^5C_2
\]

But now there are **2 possible assignments**:

**A = Captain, B = Vice-Captain**

or

**B = Captain, A = Vice-Captain**

So:

\[
2!=2
\]

Therefore:

\[
{}^5P_2={}^5C_2\times2!
\]

### The key difference:

If the question says:

> **Choose 2 students for a team**

→ **Combination**

Because A+B and B+A are the same team.

If it says:

> **Choose a Captain and Vice-Captain**

→ **Permutation**

Because A as captain/B as vice-captain is different from B as captain/A as vice-captain.

**That's the concept. Don't worry about memorizing the formula yet — just remember:**

> 🟢 **Combination = SELECT**
> 🔵 **Permutation = SELECT + ARRANGE**
