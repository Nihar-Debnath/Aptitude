Yes — this is the next important part of **Compound Interest**. The main thing is understanding **how often the interest gets added to the principal**.

## 1. What does "compounding" mean?

Suppose you invest ₹10,000 at **12% per annum**.

If it is compounded **yearly**, interest is added **once every year**.

If it is compounded **half-yearly**, interest is added **twice a year**.

If it is compounded **quarterly**, interest is added **4 times a year**.

And so on.

### The key rule

When compounding frequency changes:

> **Divide the annual rate by the number of times interest is compounded per year, and multiply the time by that same number.**

---

## 2. The whole table

| Compounding           | Times per year | Rate used each period | Number of periods |
| --------------------- | -------------: | --------------------: | ----------------: |
| **Yearly / Annually** |              1 |                   (R) |               (T) |
| **Half-yearly**       |              2 |                 (R/2) |              (2T) |
| **Quarterly**         |              4 |                 (R/4) |              (4T) |
| **Monthly**           |             12 |                (R/12) |             (12T) |
| **Weekly**            |             52 |                (R/52) |             (52T) |
| **Daily**             |            365 |               (R/365) |            (365T) |
| **Hourly**            |           8760 |              (R/8760) |           (8760T) |

For aptitude, the **most important ones** are yearly, half-yearly and quarterly. Monthly can also appear.

---

# 3. Yearly

Suppose:

[
P=₹10,000,\quad R=12%,\quad T=2
]

Compounded **yearly**.

There is **1 compounding period per year**.

So:

[
R=12%
]

and:

[
T=2
]

Formula:

[
A=P\left(1+\frac{R}{100}\right)^T
]

---

# 4. Half-yearly ⭐

**Half-yearly = every 6 months = 2 times per year.**

Suppose:

[
R=12%
]

Since there are 2 periods per year:

### Divide rate by 2

[
12\div2=6%
]

So each **6-month period** gets 6%.

### Multiply time by 2

For 2 years:

[
2\times2=4\text{ periods}
]

Therefore:

[
\boxed{A=P\left(1+\frac{6}{100}\right)^4}
]

### Remember:

**Half-yearly →**

[
\boxed{R\div2,\quad T\times2}
]

---

# 5. Quarterly ⭐

**Quarterly = every 3 months = 4 times per year.**

Suppose:

[
R=12%
]

Divide the rate by 4:

[
12\div4=3%
]

So every 3 months, interest is **3%**.

For 2 years:

[
2\times4=8\text{ periods}
]

Therefore:

[
\boxed{A=P(1.03)^8}
]

### Remember:

**Quarterly →**

[
\boxed{R\div4,\quad T\times4}
]

---

# 6. Monthly

Monthly means **12 times per year**.

If:

[
R=12%
]

then monthly rate:

[
12\div12=\boxed{1%}
]

For 2 years:

[
2\times12=24\text{ periods}
]

So:

[
\boxed{A=P(1.01)^{24}}
]

### Monthly:

[
\boxed{R\div12,\quad T\times12}
]

---

# 7. Weekly

Weekly means approximately **52 times per year**.

So:

[
\boxed{R\div52,\quad T\times52}
]

For example, 10% yearly:

[
\text{weekly rate}=\frac{10}{52}%
]

For 1 year:

[
52\text{ periods}
]

---

# 8. Daily

Daily means approximately **365 times per year**.

So:

[
\boxed{R\div365,\quad T\times365}
]

For 1 year:

[
365\text{ periods}
]

---

# 9. Hourly

One normal year has:

[
365\times24=8760\text{ hours}
]

So hourly compounding means:

[
\boxed{R\div8760}
]

and:

[
\boxed{T\times8760}
]

---

# 🧠 The ONE rule you need to memorize

Don't memorize seven separate formulas.

Just remember:

> **If interest is compounded (n) times per year:**

[
\boxed{\text{New Rate}=\frac{R}{n}}
]

and

[
\boxed{\text{New Time}=T\times n}
]

Then:

[
\boxed{A=P\left(1+\frac{R}{100n}\right)^{nT}}
]

---

### Example to make it crystal clear

**₹10,000 at 12% p.a. for 2 years, compounded quarterly**

Quarterly means:

[
n=4
]

Rate:

[
12/4=3%
]

Time:

[
2\times4=8
]

Therefore:

[
A=10000(1.03)^8
]

That's it.

---

### 🔥 Quick memory table

**Yearly** → `÷1, ×1`
**Half-yearly** → `÷2, ×2`
**Quarterly** → `÷4, ×4`
**Monthly** → `÷12, ×12`
**Weekly** → `÷52, ×52`
**Daily** → `÷365, ×365`
**Hourly** → `÷8760, ×8760`

The **rate goes down**, but the **number of compounding periods goes up**. That's the whole concept.
