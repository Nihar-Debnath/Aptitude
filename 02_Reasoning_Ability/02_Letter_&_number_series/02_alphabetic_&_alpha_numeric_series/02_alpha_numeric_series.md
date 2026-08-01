Great! This is the **next logical topic** after Number Series and Alphabet Series.

# What is an Alphanumeric Series?

The word itself tells you:

* **Alpha** = Alphabets (A, B, C...)
* **Numeric** = Numbers (1, 2, 3...)

So an **Alphanumeric Series** is a series where **letters and numbers are mixed together**.

Example:

```text
A1 B2 C3 D4 E5
```

or

```text
A2 C4 E6 G8
```

or

```text
2A 4C 6E 8G
```

Here, you have to find the missing term by observing **both the number pattern and the alphabet pattern simultaneously.**

---

# How to Solve (Golden Rule)

Whenever you see an alphanumeric series:

## Step 1: Separate the letters and numbers.

Example:

```text
A2  C4  E6  G8  ?
```

Separate them.

Letters

```text
A C E G
```

Numbers

```text
2 4 6 8
```

Now solve each independently.

Letters

```text
A C E G

+2 +2 +2
```

Next = **I**

Numbers

```text
2 4 6 8

+2
```

Next = **10**

Answer

```text
I10
```

---

# Type 1: Both Increase Normally

Example

```text
A1 B2 C3 D4 ?
```

Letters

```text
A B C D
```

↓

E

Numbers

```text
1 2 3 4
```

↓

5

Answer

```text
E5
```

---

# Type 2: Different Jumps

Example

```text
A2 C4 E6 G8 ?
```

Letters

```text
A C E G

+2
```

↓

I

Numbers

```text
2 4 6 8

+2
```

↓

10

Answer

```text
I10
```

---

# Type 3: Letters Increase, Numbers Double

Example

```text
A2 B4 C8 D16 ?
```

Letters

```text
A B C D
```

↓

E

Numbers

```text
2

4

8

16
```

↓

32

Answer

```text
E32
```

---

# Type 4: Numbers Increase, Letters Skip

Example

```text
A5 C7 E9 G11 ?
```

Letters

```text
A C E G

+2
```

↓

I

Numbers

```text
5 7 9 11

+2
```

↓

13

Answer

```text
I13
```

---

# Type 5: Reverse Alphabet

Example

```text
Z1 Y2 X3 W4 ?
```

Letters

```text
Z Y X W
```

↓

V

Numbers

```text
1 2 3 4
```

↓

5

Answer

```text
V5
```

---

# Type 6: Opposite Direction

Example

```text
A10 C8 E6 G4 ?
```

Letters

```text
A C E G

+2
```

↓

I

Numbers

```text
10 8 6 4

-2
```

↓

2

Answer

```text
I2
```

---

# Type 7: Alternate Series

Example

```text
A1 D5 C3 F7 E5 ?
```

Don't panic.

Split into **odd** and **even** positions.

### Odd positions

```text
A1

C3

E5
```

Letters

```text
A C E
```

↓

G

Numbers

```text
1 3 5
```

↓

7

---

### Even positions

```text
D5

F7

?
```

Letters

```text
D F
```

↓

H

Numbers

```text
5 7
```

↓

9

Now check which position is missing.

---

# Type 8: Letter Position Used as Number

Example

```text
A1 C3 E5 G7 ?
```

Notice

```text
A = 1

C = 3

E = 5

G = 7
```

The number equals the alphabet position.

Next

```text
I = 9
```

Answer

```text
I9
```

---

# Type 9: Number Represents Month

Example

```text
1J 3M 5M 7J ?
```

Numbers

```text
1

3

5

7
```

Odd numbers.

Letters

```text
J

M

M

J
```

These are months.

```text
1 January

3 March

5 May

7 July
```

Next

```text
9 September
```

Answer

```text
9S
```

This is exactly the type of question you asked earlier.

---

# Type 10: Number Represents Weekday

Example

```text
1M 3W 5F ?
```

Numbers

```text
1

3

5

7
```

Days

```text
1 Monday

3 Wednesday

5 Friday

7 Sunday
```

Answer

```text
7S
```

---

# Shortcut (Always Follow This)

Whenever you see an alphanumeric series:

### Step 1

Separate it.

Example

```text
C5 F8 I11 ?
```

Letters

```text
C

F

I
```

Numbers

```text
5

8

11
```

---

### Step 2

Find each pattern separately.

Letters

```text
+3
```

↓

L

Numbers

```text
+3
```

↓

14

Answer

```text
L14
```

---

# Topics You Should Know Before Solving Alphanumeric Series

* ✅ Alphabet positions (A = 1 to Z = 26)
* ✅ Reverse alphabet
* ✅ Months
* ✅ Weekdays
* ✅ Number series patterns
* ✅ Odd and even position splitting

---

# What TCS Usually Asks

These are the most common patterns:

1. **Separate letters and numbers** (⭐⭐⭐⭐⭐)
2. **Odd-even (alternate) series** (⭐⭐⭐⭐⭐)
3. **Alphabet position = number** (⭐⭐⭐⭐)
4. **Months & weekdays** (⭐⭐⭐⭐)
5. **Reverse alphabet** (⭐⭐⭐)

---

## One Important Tip

Unlike **Number Series**, **Alphanumeric Series is almost never solved as one single pattern**.

The biggest mistake beginners make is trying to find one rule for the whole sequence.

Instead, train yourself to immediately think:

> **"Let me separate the letters and the numbers first."**

About **90% of TCS alphanumeric series questions become much easier once you do that.
