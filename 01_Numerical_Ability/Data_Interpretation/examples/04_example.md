![](./images/Screenshot%202026-07-30%20220757.png)
![](./images/image%20copy%207.png)
![](./images/image%20copy%206.png)


Perfect. This is exactly how I want to teach DI.

**Don't think about calculations first.**
First, understand **what the question is asking**.

This question combines **Bar Graph + Pie Chart + Percentages**, so beginners often get overwhelmed.

Let's decode it step by step.

---

# Step 1: Read the question like a story

The question says:

> The bar graph shows the proportion of male and female **illiterates** in 2001 and 2011.

Translation:

The graph tells us:

> **What percentage of males cannot read/write?**

and

> **What percentage of females cannot read/write?**

---

Then it says

> The proportions of males and females in 2001 and 2011 are given in Panel (b) and (c).

Translation:

The pie chart tells us

> **Out of the total population, how many are males and how many are females?**

---

Then it says

> Total population did not change.

Translation:

This is VERY IMPORTANT.

```text
Population in 2001 = Population in 2011
```

Since the population is the same,

we can assume

```text
Total Population = 100
```

Why 100?

Because percentages become very easy.

This is the biggest trick in DI.

---

# Step 2: Understand every graph

## Panel (b)

2001

```text
Male = 60%

Female = 40%
```

If total population is 100

then

```text
Male =60

Female =40
```

Simple.

---

## Panel (c)

2011

```text
Male=50%

Female=50%
```

Again assume total =100

```text
Male=50

Female=50
```

---

# Step 3: Understand the Bar Graph

Many students misunderstand this graph.

It DOES NOT show

> Percentage of males

It shows

> Percentage of **illiterates**

Read carefully.

---

For 2001

Female

```text
60%
```

means

> **60% of females are illiterate.**

NOT

60% of total population.

---

Similarly

Male

```text
50%
```

means

> **50% of males are illiterate.**

---

For 2011

Female

```text
40%
```

means

40% females are illiterate.

Male

```text
40%
```

means

40% males are illiterate.

---

# Step 4: Draw the picture

This is what your teacher did.

Instead of remembering percentages,

he converted everything into people.

---

## 2001

Population =100

Male

```text
60
```

Female

```text
40
```

Now look at males.

50% illiterate.

```text
60
```

Half of 60

```text
30
```

Illiterate

Remaining

```text
30
```

Literate

Teacher writes

```text
60 male

↙      ↘

30(I) 30(L)
```

I = Illiterate

L = Literate

---

Now females.

Population

```text
40
```

Illiterate

60%

60% of 40

```text
24
```

Literate

```text
16
```

Teacher writes

```text
40 female

↙        ↘

24(I)   16(L)
```

---

Now total literates

```text
Male literates

30

+

Female literates

16

=

46
```

That is exactly why he wrote

```text
Total Literates

46
```

---

# Step 5: Do the same for 2011

Population

```text
100
```

Male

```text
50
```

Female

```text
50
```

---

Male

Illiterate =40%

40% of50

```text
20
```

Therefore

Literate

```text
30
```

---

Female

Illiterate =40%

40% of50

```text
20
```

Literate

```text
30
```

---

Total literates

```text
30+30

=

60
```

Teacher wrote

```text
Total Literates=60
```

---

# Step 6: Read the last line of the question

Now finally understand the English.

Question says

> Percentage increase in total literates from 2001 to2011.

Translate it.

It is asking

```text
Old Literates

↓

46

New Literates

↓

60

How much % increase?
```

This is just a Percentage chapter question.

Formula

\[
\frac{\text{New}-\text{Old}}{\text{Old}}\times100
\]

---


\[
\frac{60-46}{46}\times100
=
\frac{14}{46}\times100
\]

The trick is to choose a **nearby denominator that makes the fraction easy**.

Here:

* Numerator = **14**
* Denominator = **46**

A nearby number divisible by 14 is:

\[
42=14\times3
\]

So,

\[
\frac{14}{42}=\frac13=33.33%
\]

Now compare the denominators:

* Approximation used: **42**
* Actual denominator: **46**

Since **46 > 42**,

\[
\frac{14}{46} < \frac{14}{42}
\]

So the actual percentage is **less than 33.33%**.

Now look at the options:

* 35.43% ❌ (greater than 33.33%)
* 33.43% ❌ (also greater than 33.33%)
* 30.43% ✅ (less than 33.33%)
* 34.43% ❌ (greater than 33.33%)

Therefore, the correct choice is:

\[
\boxed{30.43}
\]

My earlier conclusion ("closest to 33.33%") was incorrect because I didn't apply the inequality to eliminate options above 33.33%.

---

## The shortcut rule (your observation)

This is a very useful placement-exam trick:

1. Keep the **numerator unchanged**.
2. Replace the denominator with a **nearby convenient multiple of the numerator**.
3. Compute the easy fraction.
4. Compare the actual denominator with the approximate denominator:

   * **Actual denominator is larger** ⟶ actual value is **smaller**.
   * **Actual denominator is smaller** ⟶ actual value is **larger**.
5. Choose the option on the correct side of the approximate value.

### Example 1

\[
\frac{18}{58}
\]

Take (54 = 18 \times 3):

\[
\frac{18}{54}=\frac13=33.33%
\]

Since (58 > 54),

\[
\frac{18}{58}<33.33%
\]

Choose an option **below 33.33%**.

---

### Example 2

\[
\frac{18}{52}
\]

Again use (54):

\[
\frac{18}{54}=33.33%
\]

But now (52 < 54), so

\[
\frac{18}{52}>33.33%
\]

Choose an option **above 33.33%**.

---

This shortcut is especially useful in placement exams like TCS, Cognizant, and Accenture because the options are usually spaced far enough apart that you can eliminate three choices without doing full division.