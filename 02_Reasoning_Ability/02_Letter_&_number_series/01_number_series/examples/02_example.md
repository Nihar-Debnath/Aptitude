![](./images/image%20copy.png)

The biggest mistake beginners make is trying to guess the answer by looking at the numbers.

Instead, always follow the algorithm.

---

# Step 1: Write the series

```text
43, 38, 31, 22, 11, -2, ?
```

---

# Step 2: Find the differences

Subtract consecutive terms.

```text
38 - 43 = -5

31 - 38 = -7

22 - 31 = -9

11 - 22 = -11

-2 - 11 = -13
```

Let's write only the differences.

```text
-5, -7, -9, -11, -13
```

---

# Step 3: Look at the difference pattern

```text
-5
-7
-9
-11
-13
```

These are consecutive **odd numbers**.

Each time,

```text
-5 → -7  (-2)

-7 → -9  (-2)

-9 → -11 (-2)

-11 → -13 (-2)
```

So the next difference is

```text
-15
```

---

# Step 4: Find the next term

Current term

```text
-2
```

Next difference

```text
-15
```

So,

```text
-2 - 15 = -17
```

✅ **Answer = -17**

---

# How should your brain think?

Whenever you see a series,

don't immediately look for squares, cubes, primes, etc.

Instead, ask yourself these questions **in order**.

### Question 1

Can I subtract?

```
43
38
31
22
11
-2
```

↓

```
-5
-7
-9
-11
-13
```

Pattern found.

Done.

---

# Suppose no pattern appears.

Then your brain should automatically ask

> "Can I subtract the differences again?"

This is called the **second difference**.

Example

```
2
5
9
14
20
```

First difference

```
3
4
5
6
```

Second difference

```
1
1
1
```

Pattern found.

---

# If that also doesn't work

Your brain asks

```
Multiplication?
```

Example

```
3
6
12
24
48
```

Pattern

```
×2
```

---

Then

```
Division?
```

---

Then

```
Alternate terms?
```

---

Then

```
Squares?
```

---

Then

```
Cubes?
```

---

Then

```
Prime numbers?
```

---

Then

```
Combination?
```

---

# This is the exact flowchart I use

```text
Given Series
      │
      ▼
Find Difference
      │
      ├── Pattern Found ✔
      │        │
      │        ▼
      │     Answer
      │
      ▼
Second Difference
      │
      ├── Pattern Found ✔
      │        │
      │        ▼
      │     Answer
      │
      ▼
Multiplication / Division
      │
      ▼
Alternate Terms
      │
      ▼
Squares / Cubes / Primes
      │
      ▼
Combination Pattern
      │
      ▼
Special Series (Fibonacci, Factorial, etc.)
```

---

## One tip that will save you a lot of time

Notice these two questions you've solved:

```
2, 4, 8, 14, 22, 32
```

and

```
43, 38, 31, 22, 11, -2
```

Both were solved by **finding the differences first**.

That's why experienced aptitude solvers almost always **subtract consecutive terms before trying anything else**. It's the fastest way to uncover the hidden pattern in most placement exam series questions.





---
---
---
---
---
---











That's completely normal. The trick is that you're trying to **see the pattern in the numbers**, but you should instead **see the pattern in the changes**.

Let's go very slowly.

---

## Step 1: Write the numbers

```text
43, 38, 31, 22, 11, -2
```

Now ask:

> **"How did 43 become 38?"**

Calculate:

```text
38 - 43 = -5
```

So we write:

```text
43 --(-5)--> 38
```

---

Next:

> **"How did 38 become 31?"**

```text
31 - 38 = -7
```

Now we have

```text
43 --(-5)--> 38 --(-7)--> 31
```

---

Continue:

```text
22 - 31 = -9
```

```text
43 --(-5)--> 38 --(-7)--> 31 --(-9)--> 22
```

---

Next:

```text
11 - 22 = -11
```

```text
43 --(-5)--> 38 --(-7)--> 31 --(-9)--> 22 --(-11)--> 11
```

---

Next:

```text
-2 - 11 = -13
```

Now the complete picture is

```text
43 --(-5)--> 38 --(-7)--> 31 --(-9)--> 22 --(-11)--> 11 --(-13)--> -2
```

---

## Step 2: Ignore the original numbers

Now look **only** at the arrows (differences):

```text
-5
-7
-9
-11
-13
```

Forget the original series for a moment.

Ask yourself:

> **"What is happening here?"**

Notice:

```text
-5
-7
-9
-11
-13
```

Every time, we're subtracting **2 more**.

Or think of it as the odd numbers:

```text
5, 7, 9, 11, 13
```

The next odd number is

```text
15
```

So the next difference is

```text
-15
```

---

## Step 3: Go back to the last number

The last number is

```text
-2
```

Apply the next difference:

```text
-2 - 15 = -17
```

So the answer is

```text
-17
```

---

## Why do we subtract?

Because the series is **decreasing**.

Look:

```text
43
↓
38
↓
31
↓
22
↓
11
↓
-2
```

The numbers are getting smaller.

So naturally, the differences are negative.

---

## Here's a question for you

Can you solve this one yourself?

```text
10, 16, 24, 34, 46, ?
```

**Step 1:** Find the differences.

Don't try to guess the answer. Just tell me:

```
16 - 10 = ?
24 - 16 = ?
34 - 24 = ?
46 - 34 = ?
```

Once you tell me those four differences, we'll find the answer together. This is exactly how you'll build the habit needed for placement exams.
