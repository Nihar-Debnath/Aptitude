Perfect. These **5 topics are the heart of Number System**. Around **80–90% of Number System questions** in placement exams are built using one or more of these concepts.

We'll start from the basics and understand the **logic**, not just tricks.

---

# 1. Divisibility Rules ⭐⭐⭐⭐⭐

Instead of actually dividing a number, divisibility rules let you quickly determine whether a number is divisible by another.

For example:

Is **45678** divisible by 2?

You don't need long division.

Just look at the last digit.

Last digit = **8**

8 is even.

So **45678 is divisible by 2.**

---

## Rule of 2

A number is divisible by 2 if its last digit is

```text
0 2 4 6 8
```

Examples

```
1234 ✓

5678 ✓

1116 ✓

1235 ✗
```

---

## Rule of 3

Add all digits.

If the sum is divisible by 3,
the whole number is divisible by 3.

Example

```
357

3+5+7 = 15

15 divisible by 3

Therefore 357 divisible by 3.
```

Another

```
248

2+4+8 =14

14 not divisible by 3

So 248 is not divisible by 3.
```

### Why does this work?

Take

```
357

=3×100 +5×10 +7
```

Since

```
100 = 99+1

10 = 9+1
```

and **99 and 9 are multiples of 3**, only the extra **1s** matter.

So

```
357

behaves like

3+5+7
```

when checking divisibility by 3.

That's the mathematical reason.

---

## Rule of 4

Only check the **last two digits**.

Example

```
7312

Last two digits =12

12 divisible by4

Answer = Yes
```

Example

```
5418

18 not divisible by4

Answer = No
```

---

## Why only the last two digits?

Because

```
100

200

300

400
```

are already divisible by 4.

Only the remaining last two digits affect divisibility.

---

## Rule of 5

Last digit

```
0 or 5
```

Examples

```
125 ✓

430 ✓

432 ✗
```

---

## Rule of 6

Must satisfy

* divisible by 2
* divisible by 3

Both must be true.

Example

```
234

Last digit even ✓

2+3+4=9

9 divisible by3 ✓

Answer Yes
```

---

## Rule of 8

Check only last **three digits**.

Example

```
124000

Last three digits

000

Divisible by8

Answer Yes
```

---

## Rule of 9

Exactly like 3.

Add digits.

Example

```
729

7+2+9=18

18 divisible by9

Therefore Yes
```

---

## Rule of 10

Last digit must be

```
0
```

Easy.

---

## Rule of 11 ⭐⭐⭐

Difference between alternate digit sums.

Example

```
473

(4+3)-7

7-7=0

Divisible by11
```

Example

```
506

(5+6)-0

11

Divisible by11
```

---

# Memorize These

| Number | Rule                       |
| ------ | -------------------------- |
| 2      | Last digit even            |
| 3      | Sum of digits              |
| 4      | Last 2 digits              |
| 5      | Ends with 0 or 5           |
| 6      | 2 and 3 both               |
| 8      | Last 3 digits              |
| 9      | Sum of digits              |
| 10     | Ends with 0                |
| 11     | Alternate digit difference |

---

# 2. Prime Numbers & Prime Factorization ⭐⭐⭐⭐⭐

A prime number has exactly **2 factors**.

```
2

3

5

7

11

13

17

19
```

---

## Composite

More than 2 factors.

```
4

6

8

9

10

12
```

---

## Important Facts

Only even prime

```
2
```

Smallest prime

```
2
```

1 is

```
Neither prime nor composite
```

---

## Prime Factorization

Break every number into prime numbers.

Example

```
36
```

```
36

=2×18

=2×2×9

=2×2×3×3
```

Or

```
36=2²×3²
```

---

Another

```
60

=2×30

=2×2×15

=2×2×3×5
```

```
60=2²×3×5
```

---

Why is this important?

Because

* HCF
* LCM
* Number of factors
* Divisibility
* Remainders

all use prime factorization.

---

# 3. HCF & LCM ⭐⭐⭐⭐⭐

Suppose

```
12

18
```

Prime factors

```
12

=2²×3
```

```
18

=2×3²
```

---

## HCF

Take **common primes** with the **smallest power**.

```
2¹

3¹
```

Answer

```
2×3=6
```

---

## LCM

Take **all primes** with the **largest power**.

```
2²

3²
```

Answer

```
4×9=36
```

---

Another Example

```
24

36
```

Prime factors

```
24=2³×3
```

```
36=2²×3²
```

HCF

```
2²×3

=12
```

LCM

```
2³×3²

=72
```

---

### Shortcut Formula

For two numbers

```
HCF × LCM

=

Product of numbers
```

Example

```
12

18
```

```
6×36

216
```

```
12×18

216
```

Always true.

---

# 4. Remainders ⭐⭐⭐⭐⭐

The remainder is what's left after division.

Example

```
17÷5
```

```
5×3=15

Remainder=2
```

---

Another

```
28÷6
```

```
6×4=24

Remainder=4
```

---

### Big Numbers

```
999÷8
```

Nearest multiple

```
8×124=992
```

```
999−992=7
```

Answer

```
7
```

---

## Modular Arithmetic

Instead of saying

```
999 leaves remainder7
```

we write

```
999≡7(mod8)
```

It means exactly the same thing.

---

### Why is this useful?

Example

Find the remainder of

```
2^100

divided by3
```

Notice

```
2¹=2

2²=4→1

2³=2

2⁴=1

2⁵=2
```

Pattern

```
2

1

2

1

...
```

100 is even.

Even positions give

```
1
```

Answer

```
1
```

No calculator needed.

---

# 5. Unit Digit ⭐⭐⭐⭐⭐

Suppose

```
7^100
```

No one calculates it.

Instead, look only at the **unit digits**.

---

Example

```
7¹=7

7²=49→9

7³=343→3

7⁴→1

7⁵→7
```

Pattern

```
7

9

3

1

7

9

3

1
```

Cycle length

```
4
```

---

Find unit digit of

```
7^100
```

Divide exponent by cycle length.

```
100÷4

Remainder=0
```

Remainder **0** means take the **last value** in the cycle.

Cycle

```
7

9

3

1
```

Answer

```
1
```

---

Another Example

Find unit digit

```
3^27
```

Pattern

```
3

9

7

1
```

Cycle = 4

```
27÷4

Remainder=3
```

Third value

```
7
```

Answer

```
7
```

---

# Unit-Digit Cycles You Should Memorize

| Base | Unit Digit Pattern | Cycle Length |
| ---- | ------------------ | -----------: |
| 0    | 0                  |            1 |
| 1    | 1                  |            1 |
| 2    | 2 → 4 → 8 → 6      |            4 |
| 3    | 3 → 9 → 7 → 1      |            4 |
| 4    | 4 → 6              |            2 |
| 5    | 5                  |            1 |
| 6    | 6                  |            1 |
| 7    | 7 → 9 → 3 → 1      |            4 |
| 8    | 8 → 4 → 2 → 6      |            4 |
| 9    | 9 → 1              |            2 |

---

# How These Topics Connect

Think of these as building blocks:

```
Prime Numbers
        │
        ▼
Prime Factorization
        │
        ▼
HCF & LCM
        │
        ▼
Divisibility Questions
        │
        ▼
Remainder Questions
        │
        ▼
Unit Digit Questions
```

Most placement questions combine **two or more** of these ideas. For example:

* Find the HCF by first doing **prime factorization**.
* Check if a large number is divisible using **divisibility rules**.
* Find the remainder of a huge power by recognizing a **unit-digit or remainder cycle**.

## How we'll learn these from now on

I know you prefer understanding the logic rather than memorizing shortcuts. So for each future topic, we'll follow this pattern:

1. **Understand why the rule works.**
2. **Learn the quick trick.**
3. **Solve easy examples.**
4. **Solve placement-level questions using logical elimination.**
