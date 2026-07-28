![](./images/image%20copy.png)


For **TCS, Cognizant, Infosys, Accenture**, you are **very unlikely** to get a question where you have to manually calculate the Standard Deviation of 10 numbers like this.

If such a question appears, it is usually:

* calculator-based,
* or asks only the concept,
* or gives simpler numbers.

Let's still solve it so you understand the process.

---

## Given Data

```
50, 55, 60, 65, 70, 72, 75, 80, 84, 89
```

Number of observations

```
N = 10
```

---

## Step 1: Find the Mean

Sum

```
50+55+60+65+70+72+75+80+84+89 = 700
```

Mean

```
=700/10
=70
```

---

## Step 2: Make a Table

|  x | x−70 | (x−70)² |
| -: | ---: | ------: |
| 50 |  -20 |     400 |
| 55 |  -15 |     225 |
| 60 |  -10 |     100 |
| 65 |   -5 |      25 |
| 70 |    0 |       0 |
| 72 |    2 |       4 |
| 75 |    5 |      25 |
| 80 |   10 |     100 |
| 84 |   14 |     196 |
| 89 |   19 |     361 |

---

## Step 3: Add the Squares

```
400
+225
+100
+25
+0
+4
+25
+100
+196
+361
---------
1436
```

---

## Step 4: Find Variance

Population Variance

```
1436/10
=143.6
```

---

## Step 5: Take Square Root

```
√143.6
≈11.983
```

✅ Answer = **Option B (11.983)**

---

# Memory Trick

Whenever you see Standard Deviation:

```
Mean
   ↓
Subtract Mean
   ↓
Square
   ↓
Add
   ↓
Divide by N
   ↓
Square Root
```

Remember this flow:

```
Mean
 ↓
Difference
 ↓
Square
 ↓
Average
 ↓
Root
```

---

# Shortcut for Placements

Most aptitude exams **do not expect** you to calculate a square root like √143.6 manually.

Instead:

1. Find the mean.
2. Compute the squared differences.
3. Divide by **N** (or **N−1** if the question specifies sample standard deviation).
4. Compare with the options.

For this question:

```
Variance = 143.6
```

Now compare the options by squaring them approximately:

```
13.751² ≈ 189
11.983² ≈ 144  ✅
9.432² ≈ 89
5.754² ≈ 33
```

Since the variance is **143.6**, the only matching option is:

✅ **11.983**

---

### Is this important for TCS Ignite?

**Not much.** If you're preparing for **TCS Ignite**, it's usually enough to know:

* Mean
* Median
* Mode
* Weighted Average
* The concept of Standard Deviation (small SD vs. large SD)

Full SD calculations like this are relatively uncommon in entry-level placement aptitude tests.





---
---
---
---


😂 That's a fair question. The confusion comes from **mixing two different things**:

1. **Understanding what Standard Deviation means (the concept).**
2. **Calculating Standard Deviation (the math).**

They're related, but not the same.

---

# Level 1: Understanding the Concept

Suppose two classes have the same average marks.

## Class A

```
49 50 50 51 50
```

Mean = 50

Everyone scored almost the same.

➡️ **Small Standard Deviation**

---

## Class B

```
10 50 90 30 70
```

Mean = 50

Marks are all over the place.

➡️ **Large Standard Deviation**

This is **what SD tells us**.

It answers only one question:

> **"How spread out is the data?"**

---

# Level 2: Calculating the Value

Now suppose the exam asks:

> **"What is the Standard Deviation?"**

Now you can't simply say "small" or "large."

The examiner wants the **exact numerical value**.

So you calculate it.

```
Find Mean
      ↓
Subtract Mean
      ↓
Square
      ↓
Average
      ↓
Square Root
```

The answer becomes something like:

```
SD = 11.983
```

---

# Think of it like Height

Imagine I ask:

### Question 1

> Is this person tall or short?

You answer:

> Tall.

That's enough.

---

### Question 2

Now I ask:

> Exactly how tall?

Now you answer:

> **182 cm**

Same person.

Same height.

Different question.

---

Standard Deviation works exactly the same way.

Question:

> Is the spread large or small?

Answer:

> Large.

Question:

> What is the Standard Deviation?

Answer:

> 11.983

---

# Another Example

Suppose

```
A = 1 2 3 4 5
```

Mean = 3

Spread is small.

Suppose

```
B = -100 3 106
```

Mean is also 3.

Spread is huge.

Instead of saying

> "A little spread"

or

> "Very large spread"

Mathematicians invented a number.

That number is called **Standard Deviation**.

For example,

```
Dataset A

SD = 1.41
```

```
Dataset B

SD = 83.27
```

Now you can compare datasets precisely.

---

# So why do we calculate it?

Because **"small"** and **"large"** are just descriptions.

The formula gives us an **exact measurement** of the spread.

Think of it this way:

| What you want to know         | Answer                                  |
| ----------------------------- | --------------------------------------- |
| Is the spread small or large? | Concept (qualitative)                   |
| How much is the spread?       | Standard Deviation value (quantitative) |

---

## For TCS Ignite

This is what you should remember:

* If the exam asks **conceptual questions**, think:

  * Small SD → values are close to the mean.
  * Large SD → values are far from the mean.

* If the exam asks **numerical questions**, use the formula to calculate the exact SD.

So I wasn't changing the meaning—I was answering two different kinds of questions:

* **What does SD represent?** → Concept.
* **What is the SD for this dataset?** → Calculation.



---
---
---
---
---
---




This is actually the **best question** you could ask. Once you understand what each symbol means, the formula becomes very simple.

The formula is:

$$\sigma = \sqrt{\frac{1}{N}\sum_{i=1}^{N}(x_i-\mu)^2}$$

Let's match **every symbol** with the question we solved.

---

## Question

```text
50, 55, 60, 65, 70, 72, 75, 80, 84, 89
```

---

## Step 1: What is **N**?

`N` = Number of observations.

How many salaries are there?

```text
50
55
60
65
70
72
75
80
84
89
```

There are **10** numbers.

So,

```text
N = 10
```

---

## Step 2: What is **μ (mu)**?

`μ` means **Mean (Average)**.

We calculated it earlier.

```text
Mean = 700/10 = 70
```

So,

```text
μ = 70
```

---

## Step 3: What is **x**?

`x` means **one observation (one data value)**.

Each salary is an `x`.

Like this:

```text
x₁ = 50
x₂ = 55
x₃ = 60
...
x₁₀ = 89
```

---

## Step 4: What is **(x − μ)**?

This means

> **Distance of each value from the mean.**

Example:

For the first salary,

```text
x = 50
μ = 70

x−μ

=50−70

=-20
```

Second salary

```text
55−70=-15
```

Third

```text
60−70=-10
```

Keep doing this.

---

## Step 5: Why **square** it?

Because some differences are negative.

Example

```text
50−70=-20
89−70=19
```

If we simply added them,

```text
-20+19=-1
```

They cancel each other.

We don't want that.

So we square them.

```text
(-20)²=400

19²=361
```

Now every value becomes positive.

---

## Step 6: What does **Σ (Sigma)** mean?

This confuses almost everyone initially.

**Σ simply means "ADD EVERYTHING."**

In our question,

```text
400
225
100
25
0
4
25
100
196
361
```

Σ means

```text
400+225+100+25+0+4+25+100+196+361
```

which equals

```text
1436
```

That's all Sigma means.

> **Σ = Sum of all the values.**

---

## Step 7: Divide by N

```text
1436/10

=143.6
```

This value is called the **Variance**.

---

## Step 8: Take Square Root

```text
√143.6

≈11.983
```

Done!

---

# Now replace every symbol with the values from the question

Instead of

```text
σ = √[(1/N) Σ(x−μ)²]
```

write

```text
σ = √[(1/10) × Σ(x−70)²]
```

Now expand Sigma

```text
σ = √[(1/10) ×
(
(50−70)²
+
(55−70)²
+
(60−70)²
+
...
+
(89−70)²
)]
```

Now calculate

```text
σ = √[(1/10) × 1436]
```

```text
σ = √143.6
```

```text
σ ≈11.983
```

---

# Meaning of Every Symbol

| Symbol     | Meaning                     | In this question |
| ---------- | --------------------------- | ---------------- |
| **σ**      | Standard Deviation (Answer) | **11.983**       |
| **N**      | Number of observations      | **10**           |
| **μ**      | Mean (Average)              | **70**           |
| **x**      | One data value              | 50, 55, 60...    |
| **x−μ**    | Distance from mean          | -20, -15...      |
| **(x−μ)²** | Squared distance            | 400, 225...      |
| **Σ**      | Add all squared distances   | **1436**         |

## One thing to remember forever

A very easy way to read the formula in plain English is:

> **Standard Deviation = Square root of the average of the squared distances of all values from the mean.**

That's literally what the formula is saying—just written with mathematical symbols.
