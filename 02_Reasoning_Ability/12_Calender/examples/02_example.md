![alt text](./images/image-1.png)

Yep bro, let's solve it using the **same odd-days method**. This one is good practice because **1964 is a leap year**.

Question:

> **On what day does 22 October 1964 lie?**

---

## Step 1: Take completed years

We need the years **before 1964**:

\[
1964-1=1963
\]

Break it:

\[
1963=1600+300+63
\]

From the odd-day table:

\[
1600\rightarrow0
\]

\[
300\rightarrow1
\]

---

## Step 2: Find odd days of 63 years

First find leap years:

\[
63\div4=15\text{ remainder }3
\]

So there are **15 leap years**.

Ordinary years:

\[
63-15=48
\]

Now calculate odd days:

### Ordinary:

\[
48\times1=48
\]

### Leap:

\[
15\times2=30
\]

Total:

\[
48+30=78
\]

Reduce by 7:

\[
78=70+8
\]

\[
8=7+1
\]

So:

\[
\boxed{63\text{ years}=1\text{ odd day}}
\]

---

## Step 3: Total odd days from years

\[
0+1+1=\boxed{2}
\]

So the completed years contribute **2 odd days**.

---

# Step 4: Now deal with 1964

1964 is divisible by 4:

\[
1964\div4=491
\]

So **1964 is a leap year**.

That means February has **29 days**.

We need to reach **22 October**.

Completed months:

| Month     |      Odd days |
| --------- | ------------: |
| January   |             3 |
| February  | 1 ← leap year |
| March     |             3 |
| April     |             2 |
| May       |             3 |
| June      |             2 |
| July      |             3 |
| August    |             3 |
| September |             2 |

Add:

\[
3+1+3+2+3+2+3+3+2
\]

\[
=22
\]

Reduce:

\[
22-21=\boxed{1}
\]

So completed months = **1 odd day**.

---

## Step 5: Add 22 October

\[
22\div7
\]

Remainder:

\[
\boxed{1}
\]

So October 22 contributes **1 odd day**.

---

## Step 6: Add everything

Years:

\[
2
\]

Months:

\[
1
\]

Date:

\[
1
\]

Total:

\[
2+1+1=\boxed{4}
\]

Using the standard calendar reference:

| Odd days | Day          |
| -------: | ------------ |
|        0 | Sunday       |
|        1 | Monday       |
|        2 | Tuesday      |
|        3 | Wednesday    |
|    **4** | **Thursday** |
|        5 | Friday       |
|        6 | Saturday     |

# ✅ Answer: **Thursday**

### 🔥 Notice the important thing here

The **leap year matters** because February 1964 had **29 days**.

If you accidentally used February = 28:

\[
0\text{ odd days}
\]

instead of:

\[
1\text{ odd day}
\]

your answer would shift by one day.

So whenever you solve a calendar question, **first check whether the target year is a leap year.**



---
---
---
---
---


Ah yes bro — **this is a very important point**, and once you understand it, calendar questions become much clearer.

### Why did we take 1963 instead of 1964?

Because we are calculating the **completed years BEFORE the date we're looking for**.

The date is:

\[
\boxed{22\ October\ 1964}
\]

We haven't completed the year 1964 yet. We're **inside 1964**.

So first we calculate all the years that have completely passed:

\[
1,2,3,\ldots,1963
\]

That's:

\[
\boxed{1963\text{ completed years}}
\]

Then separately, we calculate the months and days that have passed **within 1964**.

---

### Think of it like your age 🎂

Suppose someone asks:

> How old are you on **22 October 1964**?

You wouldn't count the entire year 1964 as completed.

You'd say:

> **1963 full years + the part of 1964 that has passed.**

Same idea here.

```text
Years 1 ─────────────── 1963 | 1964
                         ↑      ↑
                  completed   target date
                    years
```

So:

\[
\boxed{1964-1=1963}
\]

---

### Then where does 1964 itself come in?

It absolutely **does** come in!

We handle it separately:

**Completed years:**

\[
1963
\]

**Then inside 1964:**

January + February + March + ... + September + 22 October

That's why we also had to check:

> Is **1964** a leap year?

Yes → February has 29 days.

---

### 🔥 The rule to remember

For a date:

\[
\boxed{\text{DD Month YYYY}}
\]

do:

### **1. Years = YYYY − 1**

### **2. Add months before the target month**

### **3. Add the target date**

So for:

**22 October 1964**

we use:

\[
\boxed{1963\text{ years} + Jan\text{–}Sep + 22\text{ days}}
\]

That's why **1963**, not 1964, was used in the first step.
