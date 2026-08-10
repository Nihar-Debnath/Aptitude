![alt text](./images/image.png)

Yes — this page is basically teaching you a **shortcut for finding the average and sum of the first (n) numbers** without actually adding all of them.

The important thing is to understand **where these formulas come from and when to use them**. Let's go slowly.

---

# 1. First understand what (n) means

Here, **(n) simply means the number of terms/numbers**.

For example:

* First 5 odd numbers → (n=5)
* First 10 even numbers → (n=10)
* First 20 natural numbers → (n=20)

---

# 2. First (n) ODD numbers

The odd numbers are:

[
1,3,5,7,9,11,\dots
]

If we take the **first (n) odd numbers**, the average is:

[
\boxed{n}
]

### Example: First 5 odd numbers

[
1,3,5,7,9
]

Average:

[
\frac{1+3+5+7+9}{5}
=\frac{25}{5}
=\boxed{5}
]

And (n=5), so:

[
\boxed{\text{Average}=n}
]

### Why?

The numbers are evenly spaced:

[
1,\ 3,\ 5,\ 7,\ 9
]

For equally spaced numbers:

[
\boxed{\text{Average}=\frac{\text{First}+\text{Last}}{2}}
]

So:

[
\frac{1+9}{2}=5
]

And for the first (n) odd numbers, the last number is:

[
2n-1
]

Therefore:

[
\frac{1+(2n-1)}{2}
=\frac{2n}{2}
=\boxed n
]

---

# 3. First (n) EVEN numbers

Even numbers:

[
2,4,6,8,10,\dots
]

The average of the first (n) even numbers is:

[
\boxed{n+1}
]

### Example: First 5 even numbers

[
2,4,6,8,10
]

Average:

[
\frac{2+4+6+8+10}{5}
=\frac{30}{5}
=\boxed6
]

Since (n=5):

[
n+1=5+1=\boxed6
]

Again, because they're equally spaced:

[
\frac{\text{First}+\text{Last}}2
]

First = 2

Last = (2n)

So:

[
\frac{2+2n}{2}
=\boxed{n+1}
]

---

# 4. First (n) NATURAL numbers

Natural numbers:

[
1,2,3,4,5,\dots
]

The average of the first (n) natural numbers is:

[
\boxed{\frac{n+1}{2}}
]

### Example: First 5 natural numbers

[
1,2,3,4,5
]

Average:

[
\frac{1+2+3+4+5}{5}
=\frac{15}{5}
=\boxed3
]

Formula:

[
\frac{n+1}{2}
=============

# \frac{5+1}{2}

\boxed3
]

---

# 5. Now the SUM formulas

This is the **really useful part**.

Remember our basic formula:

[
\boxed{\text{Sum}=\text{Average}\times\text{Number of terms}}
]

So if we already know the average, we can instantly find the sum.

---

### First (n) odd numbers

Average:

[
n
]

Number of terms:

[
n
]

Therefore:

[
\text{Sum}=n\times n
]

[
\boxed{\text{Sum}=n^2}
]

Example:

First 10 odd numbers.

[
\text{Sum}=10^2=\boxed{100}
]

Instead of:

[
1+3+5+7+9+11+13+15+17+19
]

---

### First (n) even numbers

Average:

[
n+1
]

Number of terms:

[
n
]

Therefore:

[
\boxed{\text{Sum}=n(n+1)}
]

Example:

First 10 even numbers:

[
\text{Sum}=10(11)=\boxed{110}
]

---

### First (n) natural numbers

Average:

[
\frac{n+1}{2}
]

Number of terms:

[
n
]

Therefore:

[
\boxed{\text{Sum}=\frac{n(n+1)}2}
]

Example:

First 10 natural numbers:

[
\text{Sum}=\frac{10(11)}2
=\boxed{55}
]

---

# 🔥 So what is the point of learning all this?

Because aptitude questions often **hide a huge calculation** behind these patterns.

Imagine they ask:

> Find the average of the first 101 odd numbers.

You don't need to write:

[
1+3+5+7+\cdots+201
]

You immediately know:

[
\boxed{\text{Average}=n}
]

So:

[
\boxed{101}
]

---

Or:

> Find the sum of the first 50 even numbers.

Immediately:

[
n(n+1)
]

[
=50(51)
]

[
=\boxed{2550}
]

---

Or:

> Find the average of the first 100 natural numbers.

Immediately:

[
\frac{n+1}{2}
]

[
=\frac{101}{2}
]

[
\boxed{50.5}
]

---

# 🧠 Memorize this table

| Numbers                    |    Average of first (n) |         Sum of first (n) |
| -------------------------- | ----------------------: | -----------------------: |
| **Odd**: (1,3,5,\dots)     |              (\boxed n) |            (\boxed{n^2}) |
| **Even**: (2,4,6,\dots)    |           (\boxed{n+1}) |         (\boxed{n(n+1)}) |
| **Natural**: (1,2,3,\dots) | (\boxed{\frac{n+1}{2}}) | (\boxed{\frac{n(n+1)}2}) |

### The main idea:

You **don't learn these formulas randomly**.

They come from:

[
\boxed{\text{Average}=\frac{\text{Sum}}{\text{Number of terms}}}
]

and

[
\boxed{\text{Sum}=\text{Average}\times\text{Number of terms}}
]

So if you understand that, these formulas become logical rather than something you have to blindly memorize.

**For your aptitude exam, these are worth memorizing**, because they let you solve many Average questions in a few seconds.
