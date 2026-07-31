![](./images/image%20copy.png)



Let's solve it exactly the way you should solve it in the exam.

---

# Step 1: Decode the symbols

| Symbol | Meaning |
| ------ | ------- |
| ^      | >       |
| @      | ≤       |
| !      | =       |
| *      | ≥       |
| &      | <       |

---

# Step 2: Convert the statements

Given:

```
A * B
C ! A
C * E
```

becomes

```
A ≥ B
C = A
C ≥ E
```

---

# Step 3: Replace equal values

This is the biggest trick.

Since

```
C = A
```

we can replace **A with C** everywhere.

So

```
A ≥ B
```

becomes

```
C ≥ B
```

Now we have

```
C ≥ B
C ≥ E
```

Draw it like this

```
      C
     / \
   ≥     ≥
  B       E
```

Notice something important.

There is **no relation between B and E**.

---

# Step 4: Check Conclusion 1

Conclusion:

```
C * B
```

means

```
C ≥ B
```

Do we already know this?

YES.

From the statements,

```
A ≥ B

C = A

⇒ C ≥ B
```

✅ Conclusion 1 follows.

---

# Step 5: Check Conclusion 2

Conclusion:

```
B @ E
```

means

```
B ≤ E
```

Can we prove this?

We know

```
C ≥ B

and

C ≥ E
```

That only tells us both B and E are less than or equal to C.

It tells us nothing about B vs E.

Let's test.

### Case 1

```
C=10

B=7

E=9
```

Then

```
7≤9

True
```

---

### Case 2

```
C=10

B=9

E=6
```

Then

```
9≤6

False
```

Both are possible.

❌ Conclusion 2 does not follow.

---

# Final Answer

Only Conclusion 1 follows.

✅ **Option A**

---

# The Shortcut (30-second method)

## Step 1

Convert symbols.

```
* → ≥

! → =

@ → ≤
```

---

## Step 2

Whenever you see "=", immediately substitute.

Here

```
C=A
```

Replace A by C.

---

## Step 3

Draw the chain.

```
      C
     / \
   ≥     ≥
  B       E
```

---

## Step 4

Compare only what the conclusion asks.

### Conclusion 1

```
C≥B
```

Already present.

✔ True

---

### Conclusion 2

```
B≤E
```

No direct relation.

✔ Cannot conclude.

---

# Golden Rule for Inequality Questions

Whenever you have a diagram like this:

```
      X
     / \
    A   B
```

or

```
A < X > B
```

You **cannot compare A and B**.

Because both are related to **X**, but **not to each other**.

Example:

```
Rahul is shorter than Amit.
Rohit is shorter than Amit.
```

Can you say Rahul is shorter than Rohit?

❌ No.

Rahul = 5'7"

Rohit = 5'5"

or

Rahul = 5'5"

Rohit = 5'7"

Both satisfy the statements.

---

This is one of the most common tricks used in **TCS, Cognizant, Accenture, Capgemini, Infosys, and Wipro** inequality questions.

Once you master:

* symbol conversion,
* equality substitution (`=`),
* chain drawing,

you'll be able to solve most of these questions in **20–30 seconds**.
