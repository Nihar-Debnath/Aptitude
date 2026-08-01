![](./images/image%20copy%203.png)


This is a **Coding-Decoding / Mixed Series (Number + Letter)** question.

These are very common in **TCS, Cognizant, Accenture, Wipro**, etc.

The trick is:

> **Never assume the letter is an alphabet pattern first.**
>
> Check whether the letter represents **something else** like:
>
> * Months
> * Days
> * Roman numerals
> * Directions (N, E, S, W)
> * Shapes
> * Colors
> * Alphabets

---

## Let's solve the question

Series:

```text
3M   5M   7J   ?   11N
```

---

## Step 1: Check the numbers

Numbers are

```text
3 5 7 ? 11
```

Pattern

```text
+2
+2
+2
+2
```

So

```text
?
=
9
```

Now we have

```text
9 ?
```

---

## Step 2: Check the letters

Letters are

```text
M M J ? N
```

This is **not** an alphabet series.

Ask yourself:

> **What can M, J, N represent?**

Look for common abbreviations.

### Months

```text
1 Jan
2 Feb
3 Mar
4 Apr
5 May
6 Jun
7 Jul
8 Aug
9 Sep
10 Oct
11 Nov
12 Dec
```

Now compare

| Number | Month     |     |
| ------ | --------- | --- |
| 3      | March     | M ✅ |
| 5      | May       | M ✅ |
| 7      | July      | J ✅ |
| 9      | September | S ✅ |
| 11     | November  | N ✅ |

Perfect match.

So

```text
9 = September = S
```

Answer

```text
9S
```

✅ Correct.

---

# Why is this asked?

The examiner is hiding the pattern.

Instead of writing

```text
March
May
July
September
November
```

they only write

```text
M
M
J
S
N
```

to confuse you.

---

# Another Example

```text
2T
4T
6S
8?
10O
```

Numbers

```text
2
4
6
8
10
```

Now think

What are

```text
T T S O
```

Months?

No.

Days?

No.

Even numbers?

No.

Look at months

```text
2 February

No
```

Think of **English spelling**

```text
2 → Two → T

4 → Four → F
```

Not matching.

Think of **weekdays**

No.

Think of **months**

No.

Sometimes you'll need to try a few possibilities before the pattern clicks.

---

# Another Common Example

```text
1M
3W
5F
7?
```

Numbers

```text
1
3
5
7
```

Letters

```text
M
W
F
?
```

These are **weekdays**.

| Day No. | Day       |   |
| ------- | --------- | - |
| 1       | Monday    | M |
| 2       | Tuesday   | T |
| 3       | Wednesday | W |
| 4       | Thursday  | T |
| 5       | Friday    | F |
| 6       | Saturday  | S |
| 7       | Sunday    | S |

So

```text
7 = Sunday

Answer = S
```

---

# Another Example

```text
2E
4W
6?
8N
```

Letters

```text
E
W
?
N
```

Think

Directions?

```text
North
South
East
West
```

or perhaps compass points in another pattern. Always check if the letters are abbreviations before assuming an alphabet pattern.

---

# How to Solve These Questions (My Method)

Whenever you see a **Number + Letter** series:

## Step 1

Find the number pattern.

```text
3 5 7 ? 11

↓

+2
```

---

## Step 2

Ask:

**What does the letter represent?**

Check in this order:

### ① Months ⭐⭐⭐⭐⭐

```text
Jan
Feb
Mar
Apr
May
Jun
Jul
Aug
Sep
Oct
Nov
Dec
```

---

### ② Weekdays ⭐⭐⭐⭐⭐

```text
Monday
Tuesday
Wednesday
Thursday
Friday
Saturday
Sunday
```

---

### ③ Alphabet Position ⭐⭐⭐⭐

```text
1=A

2=B

3=C
```

---

### ④ Directions ⭐⭐⭐

```text
N
S
E
W
```

---

### ⑤ Roman Numerals ⭐⭐

```text
I
V
X
L
C
D
M
```

---

### ⑥ Number Spellings ⭐⭐

```text
One

Two

Three
```

---

### ⑦ Shapes/Colors/Other Abbreviations ⭐

Rare in exams.

---

# Things You Should Memorize for Aptitude

These are used again and again:

### Months

| No. | Month |
| --- | ----- |
| 1   | Jan   |
| 2   | Feb   |
| 3   | Mar   |
| 4   | Apr   |
| 5   | May   |
| 6   | Jun   |
| 7   | Jul   |
| 8   | Aug   |
| 9   | Sep   |
| 10  | Oct   |
| 11  | Nov   |
| 12  | Dec   |

---

### Days

| No. | Day |
| --- | --- |
| 1   | Mon |
| 2   | Tue |
| 3   | Wed |
| 4   | Thu |
| 5   | Fri |
| 6   | Sat |
| 7   | Sun |

---

### My advice

Don't think of this as an "Alphabet Series" question. Think of it as a **Mixed Series (Number + Letter)** where the letters are often **codes or abbreviations**.

Once you memorize **Months, Days, Alphabet Positions, and Directions**, you'll be able to solve **80–90%** of these questions in TCS, Cognizant, Wipro, and Accenture within a few seconds.
