![alt text](./images/image.png)


# Method 1

Yes. Let's solve **the exact same question using only the Weighted Average method**, without the Alligation shortcut.

### Question

* Rice = ₹450/kg
* Dal = ₹510/kg
* Mixture = ₹475/kg
* Find **Rice : Dal**

Let:

* Rice quantity = **x kg**
* Dal quantity = **y kg**

Since the mixture costs ₹475/kg, the **weighted average** must be ₹475:

\[
\frac{450x+510y}{x+y}=475
\]

Now multiply both sides by (x+y):

\[
450x+510y=475x+475y
\]

Bring similar terms together:

\[
510y-475y=475x-450x
\]

\[
35y=25x
\]

Therefore:

\[
\frac{x}{y}=\frac{35}{25}
\]

\[
\boxed{x:y=7:5}
\]

### ✅ Answer: **7 : 5**

---

### Now understand WHY this gives the same Alligation answer

Weighted average says:

\[
\frac{\text{Total Cost}}{\text{Total Quantity}}=\text{Mixture Price}
\]

So here:

\[
\frac{450x+510y}{x+y}=475
\]

When we solve it, we naturally get:

\[
25x=35y
\]

which means:

\[
x:y=35:25=7:5
\]

**Alligation is basically a shortcut that gets you to this ratio without doing all these algebra steps.**

So for your aptitude preparation:

| Method                 | What you do                                             |
| ---------------------- | ------------------------------------------------------- |
| **Weighted Average**   | Assume quantities (x,y) → make average equation → solve |
| **Alligation**         | Cross-subtract the prices → directly get ratio          |
| **Option elimination** | Check mixture range + which ingredient should be more   |

For **TCS/Cognizant MCQs**, I'd use **option elimination first → Alligation if needed**. Weighted average is more useful when the question gives you quantities or asks you to find the actual mixture price.



---
---
---
---
---



Yes — **this is the exact part you need to understand**, because once this clicks, weighted average becomes easy.

Let's forget the formula for a moment and build it from the question.

### The question says:

> Rice costs ₹450/kg and Dal costs ₹510/kg. They are mixed so that the **mixture costs ₹475/kg**.

Think about what is actually happening:

You have **two things**:

* Rice → ₹450 per kg
* Dal → ₹510 per kg

We don't know how much of each we're taking.

So we **give them variables**:

* Let Rice quantity = **x kg**
* Let Dal quantity = **y kg**

That's all. There is no special reason for x and y — they're simply names for the unknown quantities.

---

## Now the important part: Why is 475 the average?

Look at the wording:

> "so that the **mixture costs ₹475 per kg**"

This means:

### After mixing them, every 1 kg of the mixture has an average cost of ₹475.

For example, suppose we somehow mix:

**7 kg Rice + 5 kg Dal**

Total:

\[
7+5=12\text{ kg}
\]

Total cost:

\[
7(450)+5(510)
\]

\[
=3150+2550=5700
\]

So the average cost per kg is:

\[
\frac{5700}{12}=475
\]

That's why **475 is the average**.

It isn't something we calculated.

**The question TELLS us that the mixture's average price is ₹475/kg.**

---

## Now put this into the weighted-average formula

The basic idea is:

\[
\text{Average}=
\frac{\text{Total Cost}}{\text{Total Quantity}}
\]

### Rice

Rice costs ₹450/kg and we have **x kg**.

So its total cost is:

\[
450x
\]

### Dal

Dal costs ₹510/kg and we have **y kg**.

So its total cost is:

\[
510y
\]

### Together

Total cost:

\[
450x+510y
\]

Total quantity:

\[
x+y
\]

Therefore:

\[
\text{Average price}
=

\frac{450x+510y}{x+y}
\]

But the question tells us that the mixture's average price is **₹475**.

So:

\[
\boxed{\frac{450x+510y}{x+y}=475}
\]

That's where the equation comes from.

---

### Think of it visually

```text
                 MIXTURE
              Average = ₹475
                    ↑
          ┌─────────┴─────────┐
          │                   │
       RICE                  DAL
     ₹450/kg               ₹510/kg
       x kg                  y kg
```

The **₹450 and ₹510** are the prices.

The **x and y** are the quantities.

The **₹475** is the final average price because the question explicitly says the mixture costs ₹475/kg.

Then:

\[
\frac{450x+510y}{x+y}=475
\]

and solving gives:

\[
\boxed{x:y=7:5}
\]

### One very important rule

Whenever you see a mixture question like:

> A ₹A/kg item is mixed with a ₹B/kg item to make a mixture of ₹C/kg

you can think:

\[
\boxed{\text{Weighted average}=\frac{\text{total cost}}{\text{total quantity}}}
\]

The **mixture price is the average** because it tells you the cost **per kg of the final mixture**.




---
---
---
---
---


# Method 2 (the easiest one)

Yes! This is a **classic Alligation** question, and you can solve it very quickly using the method we just discussed.

### Given

* Rice = **₹450/kg** → cheaper
* Dal = **₹510/kg** → dearer
* Mixture = **₹475/kg**

Write it like this:

```text
        Rice             Dal
        ₹450             ₹510
           \             /
            \           /
             ₹475
```

Now take the **cross-differences**:

```text
        ₹450             ₹510
           \             /
            \           /
             ₹475
            /     \
      510-475     475-450
          35          25
```

So:

**Rice : Dal**

\[
=(510-475):(475-450)
\]

\[
=35:25
\]

Divide by 5:

\[
\boxed{7:5}
\]

### ✅ Final Answer: **D) 7 : 5**

---

### But WHY does this work?

This is the important part.

Suppose we actually take:

**7 kg Rice + 5 kg Dal**

Cost:

\[
7(450)+5(510)
\]

\[
=3150+2550=5700
\]

Total quantity:

\[
7+5=12
\]

Average price:

\[
\frac{5700}{12}=\boxed{475}
\]

Exactly what the question wanted! 🎯

So remember the shortcut:

> **Cheaper : Dearer = (Dearer − Mixture) : (Mixture − Cheaper)**

For this question:

\[
\boxed{450:510=7:5}
\]

The **cross-subtraction** is the main trick in Alligation.
