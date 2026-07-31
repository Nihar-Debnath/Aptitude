![](./images/image%20copy%202.png)

This one is slightly trickier because it introduces **"not less than"** and **"not greater than."** Once you understand these two terms, the rest is easy.

---

# Step 1: Decode the symbols

| Symbol | Meaning          | Mathematical Symbol |
| ------ | ---------------- | ------------------- |
| +      | Less than        | <                   |
| -      | Greater than     | >                   |
| *      | Not less than    | ≥                   |
| /      | Not greater than | ≤                   |
| %      | Equal to         | =                   |
| $      | Not equal to     | ≠                   |

---

# Step 2: Convert the statements

Given:

```
P % Q
R / S
Q * R
```

Convert each one.

### Statement 1

```
P % Q
```

↓

```
P = Q
```

---

### Statement 2

```
R / S
```

"/" means **not greater than**

So

```
R ≤ S
```

---

### Statement 3

```
Q * R
```

"*" means **not less than**

So

```
Q ≥ R
```

---

Now we have

```
P = Q
Q ≥ R
R ≤ S
```

Notice that

```
R ≤ S
```

is the same as

```
S ≥ R
```

---

# Step 3: Draw the chain

Replace P with Q because they are equal.

```
P = Q ≥ R

S ≥ R
```

Or visually,

```
      P = Q
        │
       ≥
        │
        R
       ≤
        │
        S
```

Now let's check the conclusions.

---

# Conclusion 1

```
P % S
```

means

```
P = S
```

Can we prove that?

We know

```
P = Q
Q ≥ R
S ≥ R
```

There is **no relationship** between **P (or Q)** and **S**.

Let's test.

### Case 1

```
P=Q=10
R=8
S=9
```

Everything satisfies:

```
10≥8
9≥8
```

Is

```
P=S ?

10=9

False
```

---

### Case 2

```
P=Q=10
R=8
S=10
```

Now

```
10=10

True
```

Both are possible.

❌ Conclusion 1 does **not** follow.

---

# Conclusion 2

```
Q - R
```

"-" means

```
Q > R
```

But from the statement we only know

```
Q ≥ R
```

That means either

```
Q > R
```

or

```
Q = R
```

Let's test.

### Case 1

```
Q=10
R=8
```

True.

---

### Case 2

```
Q=10
R=10
```

False.

Again,

both are possible.

❌ Conclusion 2 also does **not** follow.

---

# Final Answer

* Conclusion 1 ❌
* Conclusion 2 ❌

Therefore, **neither conclusion follows**.

However, notice something important:

The options shown in your image are only:

* A. Only conclusion 1 follows
* B. Only conclusion 2 follows
* C. Both follow
* D. Either 1 or 2 follows

There is **no "Neither follows" option**, which is unusual for inequality questions.

Based on the statements you've shared, **none of A, B, C, or D is logically correct**. This strongly suggests **there is either a typo in the image or the options are incomplete** (normally there should be an **Option E: Neither follows**).

---

# Exam Shortcut

### Step 1

Convert symbols.

```
< > = ≥ ≤
```

---

### Step 2

Replace equal values.

```
P=Q
```

↓

Treat P and Q as the same variable.

---

### Step 3

Draw the chain.

```
P=Q≥R≤S
```

---

### Step 4

For every conclusion, ask:

> **Is it always true?**

* Yes → Follows ✅
* No → Does not follow ❌

---

## One Concept You Must Remember

Many students make this mistake:

```
Q ≥ R
```

and conclude

```
Q > R
```

This is **wrong**.

Why?

Because **≥** includes **two possibilities**:

```
Q > R
```

or

```
Q = R
```

Unless the statement **forces** `Q > R`, you cannot conclude it.

---

If you're preparing for TCS, I can also teach you the **5 standard inequality tricks** (transitive chains, equality substitution, "not" operators, either-or cases, and impossible comparisons) that solve **95% of TCS inequality questions** in under 30 seconds.




---
---
---
---
---
---



Excellent question! This is **the most important concept in deductive reasoning**.

You're asking:

> **"If one possibility makes the conclusion true, why don't we accept it?"**

The answer is:

> **Because in deductive reasoning, a conclusion must be true in EVERY possible case, not just one.**

---

Let's use the previous example.

We had:

```text
Q ≥ R
```

The conclusion was:

```text
Q > R
```

Now let's see all possibilities.

### Possibility 1

```text
Q = 10
R = 8
```

Then

```text
Q > R
```

✅ True

---

### Possibility 2

```text
Q = 10
R = 10
```

Then

```text
Q > R
```

❌ False

---

So what happened?

The statement

```text
Q ≥ R
```

allows **both** cases:

* Q > R ✅
* Q = R ✅

Since the conclusion is **not true in every allowed case**, it **does not follow**.

---

## Think like a judge

Imagine I tell you:

> Rahul is **at least** 18 years old.

Can you conclude:

> Rahul is **20 years old**?

No.

Because he could be:

* 18 ✅
* 19 ✅
* 20 ✅
* 25 ✅

Just because **20 is possible** doesn't mean it's **certain**.

---

### Another example

Statement:

```text
Age ≥ 18
```

Conclusion:

```text
Age = 18
```

Is this correct?

No.

Why?

Because:

* Age = 18 ✅
* Age = 19 ✅
* Age = 25 ✅

The conclusion isn't guaranteed.

---

## Rule for Deductive Reasoning

A conclusion follows **only if it is 100% guaranteed** by the statements.

| Situation                              | Result            |
| -------------------------------------- | ----------------- |
| True in every possible case            | ✅ Follows         |
| True in some cases but false in others | ❌ Does not follow |
| Never true                             | ❌ Does not follow |

---

### Shortcut

Whenever you're unsure, ask yourself:

> **"Can I create another valid example where this conclusion becomes false?"**

* If **Yes** → ❌ Does not follow.
* If **No** → ✅ Follows.

This single question will help you solve almost all statement–conclusion and inequality questions correctly.
