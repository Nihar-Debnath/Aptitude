Yes bro — these are **very common TCS/aptitude questions**, and they look complicated mainly because they mix several small concepts together.

The two questions in your image are basically from **two related topics**:

1. **Fractions + decimals + arithmetic operations**
2. **BODMAS / order of operations**

Let me break down exactly how to approach them.

---

# 1. Q18 — Fractions + Decimal + "of"

The question is essentially:

\[
\left[\left(11\frac57-8\frac3{14}\right)
\left(\frac58-\frac{19}{56}\right)\right]\text{ of }0.75
\]

### Step 1: Understand "of"

In aptitude, **"of" means multiplication**.

So:

\[
A\text{ of }B = A\times B
\]

Therefore:

\[
[\text{big expression}] \times 0.75
\]

---

### Step 2: Solve the first bracket

\[
11\frac57-8\frac3{14}
\]

Convert the fractions to the same denominator.

\[
\frac57=\frac{10}{14}
\]

So:

\[
11\frac{10}{14}-8\frac3{14}
\]

Subtract:

\[
(11-8)+\frac{10-3}{14}
\]

\[
=3+\frac7{14}
\]

\[
=3+\frac12
\]

\[
=\frac72
\]

---

### Step 3: Solve the second bracket

\[
\frac58-\frac{19}{56}
\]

LCM of 8 and 56 = 56.

\[
\frac58=\frac{35}{56}
\]

Therefore:

\[
\frac{35}{56}-\frac{19}{56}
=\frac{16}{56}
=\frac27
\]

---

### Step 4: Multiply

\[
\frac72\times\frac27
\]

Cancel:

\[
=1
\]

Therefore:

\[
1\times0.75=\boxed{0.75}
\]

So **answer = d. 0.75**

---

# 2. Q19 — BODMAS / Order of Operations

This is a slightly more advanced version.

The question gives:

![alt text](image.png)

And asks what **#** represents.

Options:

* OF
* DIVISION
* SUBTRACTION
* ADDITION

The key is that you **don't guess #**.

First calculate everything around it.

---

## Step 1: Powers first

BODMAS tells us:

**B**rackets
**O**rders (powers, roots)
**D**ivision
**M**ultiplication
**A**ddition
**S**ubtraction

So:

\[
2^6=64
\]

and

\[
3^3=27
\]

Therefore:

\[
\frac{2^6}{3^3}=\frac{64}{27}
\]

---

## Step 2: Deal with the mixed fraction

\[
1\frac{19}{27}
\]

means:

\[
1+\frac{19}{27}
=\frac{46}{27}
\]

Therefore:

\[
\frac{64}{27}-\frac{46}{27}
=\frac{18}{27}
=\frac23
\]

So the first part is:

\[
\boxed{\frac23}
\]

---

# Step 3: Solve the curly bracket

We have:

\[
\frac3{11}-\left(6\div\frac{22}{7}\right)
\]

Division comes before subtraction.

Remember:

\[
a\div\frac bc=a\times\frac cb
\]

Therefore:

\[
6\div\frac{22}{7}
=

6\times\frac7{22}
\]

\[
=\frac{42}{22}
=\frac{21}{11}
\]

So:

\[
\frac3{11}-\frac{21}{11}
=

-\frac{18}{11}
\]

Thus the second part is:

\[
\boxed{-\frac{18}{11}}
\]

---

# Step 4: Multiply the two parts

\[
\frac23\times-\frac{18}{11}
\]

\[
=-\frac{36}{33}
\]

\[
=-\frac{12}{11}
\]

So now the question becomes:

![alt text](image-1.png)

---

# Step 5: Understand the repeating decimal

The bar above 09 means:

\[
0.\overline{09}=0.09090909...
\]

For a repeating two-digit decimal:

\[
0.\overline{09}=\frac9{99}
\]

\[
=\frac1{11}
\]

So:

![alt text](image-2.png)
Now try the options.

### Addition:

\[
-\frac{12}{11}+\frac1{11}
=

-\frac{11}{11}
=-1
\]

Perfect.

Therefore:

\[
\boxed{\text{ADDITION}}
\]

---

# 🔥 The important rules you should remember

For your TCS exam, I'd memorize these rules very strongly.

## Rule 1 — BODMAS

Always follow:

> **B → O → D → M → A → S**

### Example:

\[
5+3\times2
\]

Don't do:

\[
(5+3)\times2
\]

Multiplication first:

\[
5+6=11
\]

---

# Rule 2 — Brackets have priority

If you see:

\[
[ \{ ( ) \} ]
\]

work from the **innermost bracket outward**.

For example:

\[
5+{3\times(4+2)}
\]

First:

\[
4+2=6
\]

then:

\[
3\times6=18
\]

then:

\[
5+18=23
\]

---

# Rule 3 — Division and multiplication have the same priority

This is VERY important.

People often think:

> Division always comes before multiplication.

That's not exactly correct.

**D and M have equal priority**, so solve them **from left to right**.

Example:

\[
20\div5\times2
\]

Go left to right:

\[
20\div5=4
\]

then:

\[
4\times2=8
\]

Answer:

\[
\boxed8
\]

---

# Rule 4 — Addition and subtraction also have equal priority

Again, go **left to right**.

Example:

\[
20-5+3
\]

First:

\[
20-5=15
\]

then:

\[
15+3=18
\]

Not 12.

---

# Rule 5 — "of" means multiplication

This is extremely common in aptitude.

\[
\frac25\text{ of }100
\]

means:

\[
\frac25\times100=40
\]

So whenever you see:

> **x% of y**

think:

\[
x%\times y
\]

---

# Rule 6 — Mixed fractions

If you see:

\[
3\frac25
\]

convert it to an improper fraction:

\[
\frac{3\times5+2}{5}
=

\frac{17}{5}
\]

### Shortcut:

\[
a\frac bc=\frac{ac+b}{c}
\]

For example:

\[
4\frac37
=

\frac{4(7)+3}{7}
=
\frac{31}{7}
\]

---

# Rule 7 — Dividing fractions

This one is **VERY important**.

Whenever you divide by a fraction:

\[
\frac ab\div\frac cd
\]

**flip the second fraction and multiply**:

\[
\frac ab\times\frac dc
\]

Example:

\[
\frac35\div\frac27
\]

becomes:

\[
\frac35\times\frac72
\]

\[
=\frac{21}{10}
\]

### Remember:

> **Division → Flip the second fraction → Multiply**

---

# Rule 8 — Subtracting fractions

You need the **same denominator**.

Example:

\[
\frac34-\frac25
\]

LCM = 20.

\[
\frac{15}{20}-\frac8{20}
==

\frac7{20}
\]

Don't subtract numerator and denominator separately.

❌

\[
\frac{3-2}{4-5}
\]

is completely wrong.

---

# Rule 9 — Repeating decimals

You should know a few common ones.

\[
0.\overline3=\frac13
\]

\[
0.\overline6=\frac23
\]

\[
0.\overline9=1
\]

\[
0.\overline{09}=\frac9{99}=\frac1{11}
\]

\[
0.\overline{27}=\frac{27}{99}=\frac3{11}
\]

For **two repeating digits**:

\[
0.\overline{ab}=\frac{ab}{99}
\]

For example:

\[
0.\overline{45}=\frac{45}{99}=\frac5{11}
\]

---

# What type of questions should you expect?

For TCS, this entire area can appear as:

### 1. Direct BODMAS

\[
5+3\times2-4
\]

### 2. Fractions

\[
\frac35+\frac27
\]

### 3. Mixed fractions

\[
2\frac34-1\frac25
\]

### 4. Fractions + decimals

\[
\frac35\times0.75
\]

### 5. "Of" questions

\[
\frac25\text{ of }150
\]
![alt text](image-3.png)
### 8. Repeating decimals

\[
0.\overline3,\quad0.\overline{27},\quad0.\overline{09}
\]

---

## 🧠 Your exam approach

When you see a scary expression like these, **don't try to solve the whole thing in your head**.

Use this sequence:

**1. Brackets → 2. Powers → 3. Division/Multiplication → 4. Addition/Subtraction → 5. "of" = multiplication**

And for fractions:

**Same denominator for +/−**

**Flip second fraction for ÷**

**Convert mixed fraction → improper fraction**

**Convert repeating decimal → fraction**

That's basically the whole game.

And honestly, **Q18 and Q19 are exactly the kind of questions where knowing these rules can turn a scary-looking 1-minute question into a 20–30 second question.**
