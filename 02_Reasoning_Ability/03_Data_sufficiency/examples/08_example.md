![](./images/image%20copy%203.png)

This is actually a **Ranking & Ordering + Data Sufficiency** question.

The English looks scary, but the logic is simple.

Let's first understand the **question**, not the statements.

---

# What is the question asking?

It says:

```text
Who among P, Q, R, S, and T,
each having a different weight,
is the lightest?
```

Let's simplify it.

There are **5 people**:

```text
P
Q
R
S
T
```

All have **different weights**.

The question is asking:

> **Who is the lightest person?**

That's it.

Think of it like this:

| Person | Weight |
| ------ | ------ |
| P      | ?      |
| Q      | ?      |
| R      | ?      |
| S      | ?      |
| T      | ?      |

We want to know

```text
Who has the minimum weight?
```

---

# Now let's read Statement I

```text
R is heavier than P.
```

Translate it into symbols.

```text
R > P
```

(> means heavier)

or

```text
P < R
```

Diagram:

```text
P -------- R
lighter   heavier
```

Can we tell who is the lightest?

No.

Because we know nothing about

```text
Q

S

T
```

So

❌ Statement I is NOT sufficient.

---

# Statement II

```text
S is lighter than T and Q.
```

Translate it.

```text
S < T

S < Q
```

Diagram

```text
S ------ T

S ------ Q
```

Does this mean S is the lightest?

No.

Because we don't know about

```text
P

R
```

Maybe

```text
P
```

is even lighter.

So

❌ Statement II is NOT sufficient.

---

# Now combine them

Statement I

```text
P < R
```

Statement II

```text
S < T

S < Q
```

Draw everything.

```text
P < R

S < T

S < Q
```

Notice something.

There are **two separate groups**.

Group 1

```text
P < R
```

Group 2

```text
S < T

S < Q
```

There is **no connection** between them.

We still don't know

* Is P lighter than S?
* Is S lighter than P?

Both are possible.

---

### Possibility 1

```text
P
S
Q
T
R
```

Lightest = P

---

### Possibility 2

```text
S
P
Q
T
R
```

Lightest = S

---

Both satisfy all the statements.

Since two different answers are possible,

❌ We cannot determine the lightest person.

---

# Final Answer

| Statement | Sufficient? |
| --------- | ----------- |
| I         | ❌ No        |
| II        | ❌ No        |
| Together  | ❌ No        |

Answer

✅ **Option E**

---

# The Trick for Ranking Data Sufficiency

Whenever you see words like

```text
heavier

lighter

taller

shorter

older

younger

faster
```

**Never solve them mentally.**

Draw a small diagram.

Example

```text
A is taller than B
```

Draw

```text
B ---- A
```

Example

```text
X is younger than Y
```

Draw

```text
X ---- Y
```

Example

```text
P is heavier than R
```

Draw

```text
R ---- P
```

---

# One More Important Concept

The question asks:

```text
Who is the lightest?
```

To answer this, **every person must somehow be connected**.

For example, if the statements were:

```text
P < Q

Q < R

R < S

S < T
```

Then you can combine them:

```text
P < Q < R < S < T
```

Now it's obvious.

✅ Lightest = **P**

But in your question, the information is split into two disconnected groups:

```text
P < R

S < T

S < Q
```

Since there's **no link between P and S**, you can never decide who is the lightest.

---

### A shortcut for these questions

Whenever you see **heavier/lighter, taller/shorter, older/younger**:

1. Convert each statement into an inequality (`<` or `>`).
2. Draw a simple chain.
3. Check whether **all people are connected** into one chain.

* If everyone is connected, you may have enough information.
* If there are separate groups (like in this question), you almost certainly **do not** have enough information. This visual approach makes these questions much easier than trying to keep everything in your head.
