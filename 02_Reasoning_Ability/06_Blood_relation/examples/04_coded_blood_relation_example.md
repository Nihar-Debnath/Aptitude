![alt text](./images/image-12.png)

This is actually the **biggest mistake** students make. They **draw all 4 options**, which is very slow.

For **TCS Ignite, Smart, Infosys, Wipro, Cognizant**, you should **NOT draw every option completely**.

Instead, use what I call the **"Target Relation Method."**

---

# Step 0: Understand the question

Given:

> **P is husband of S.**

So first draw only this.

```text
P (♂) ───── S (♀)
      Husband Wife
```

Now keep this fixed.

---

# Step 1: Learn the codes

```
+  = Father
-  = Mother
*  = Brother
/  = Sister
@  = Daughter
```

Don't think.

Just translate.

---

# Step 2: Read the question

Usually they ask something like

> Which option is TRUE?

Don't draw the whole family.

Just see whether the option agrees with

```text
P (♂) ─── S (♀)
```

---

# Option A

```
S * P + R - Q
```

Translate only.

```
S is brother of P
```

STOP.

Immediately wrong.

Why?

Because S is wife of P.

A wife cannot be brother.

❌ Eliminate.

Time taken = 3 seconds.

---

# Option B

```
Q - P - R @ S
```

Translate.

```
Q is mother of P
```

Good.

Next

```
P is mother of R
```

STOP.

Impossible.

P is husband.

Male.

Cannot be mother.

❌ Eliminate.

Again 5 seconds.

---

# Option C

```
P + R * Q @ S
```

Translate.

```
P is father of R
```

Possible.

Continue.

```
R is brother of Q
```

Possible.

Continue.

```
Q is daughter of S
```

Good.

Draw only this.

```text
        P ───── S
         │
         R ─── Q
```

Since Q is daughter of S,

and R is brother of Q,

R is also child of S.

Since P is father of R,

everything matches.

✅ Possible.

Keep.

---

# Option D

```
P + Q - S / R
```

Translate.

```
P is father of Q
```

Good.

Next.

```
Q is mother of S
```

STOP.

Q is child of P.

S is wife of P.

That means daughter becomes mother of S.

Impossible.

❌ Eliminate.

---

Only one option survives.

Answer = **C**

---

# The Secret Shortcut

Notice something?

I never drew options A, B or D.

Because I eliminated them after reading only **one or two relations.**

---

## Rule 1

Whenever you see

```
P is husband of S
```

Immediately remember

```
P = Male

S = Female
```

Now use this everywhere.

---

## Rule 2

If a male becomes

* Mother ❌
* Sister ❌
* Daughter ❌

Immediately eliminate.

---

If a female becomes

* Father ❌
* Brother ❌
* Son ❌
* Husband ❌

Immediately eliminate.

---

# Rule 3

Only draw the option that survives.

Don't waste time drawing impossible ones.

---

# The 5-second elimination table

| If you see...          | Eliminate immediately |
| ---------------------- | --------------------- |
| Male becomes Mother    | ❌                     |
| Male becomes Sister    | ❌                     |
| Male becomes Daughter  | ❌                     |
| Female becomes Father  | ❌                     |
| Female becomes Brother | ❌                     |
| Female becomes Son     | ❌                     |
| Husband becomes Wife   | ❌                     |
| Wife becomes Husband   | ❌                     |

---

## TCS Trick (Very Important)

In coding-decoding blood relations, **80–90% of the options can usually be rejected within the first two symbols** because they create an impossible gender or relationship.

Only **one option usually needs a complete diagram**.

That's why good aptitude teachers don't draw four family trees—they eliminate first, then draw just the surviving option.

---

### For your TCS Ignite preparation, this is the order you should follow:

1. **Fix the given relation** (e.g., `P = Male`, `S = Female`).
2. **Translate one symbol at a time** into plain English.
3. **Check for gender contradictions immediately.**
4. **Eliminate impossible options without drawing.**
5. **Draw only the last remaining possible option.**

This approach is much faster and is exactly what helps you finish these questions within the exam time limit.