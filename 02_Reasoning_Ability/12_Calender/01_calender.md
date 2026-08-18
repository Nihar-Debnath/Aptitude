
## 1. What does Calendar reasoning ask?

Usually questions like:

* What day was **15 August 1947**?
* What day will be **26 January 2030**?
* If today is Monday, what day will it be after 45 days?
* How many odd days are there?
* Which day was a particular date?

The main thing we're finding is:

> **Which day of the week corresponds to a particular date?**

---

## 2. The most important concept: 7 days repeat

The week is:

**Mon → Tue → Wed → Thu → Fri → Sat → Sun → Mon...**

After **7 days**, you're back to the same day.

So:

\[
7 \text{ days}=0\text{ change in day}
\]

For example:

If today is **Monday**:

* +1 day → Tuesday
* +2 → Wednesday
* +3 → Thursday
* +7 → Monday again
* +10 → Thursday

Why?

Because:

\[
10\div7=1\text{ remainder }3
\]

So we only care about the **remainder**.

---

# 3. This remainder is called "Odd Days"

This is the MOST important concept in calendar questions.

Suppose you have:

\[
10\text{ days}
\]

Divide by 7:

\[
10=7+3
\]

The **3** is called the **odd days**.

So:

\[
\boxed{10\text{ days}=3\text{ odd days}}
\]

Similarly:

| Days | Odd days |
| ---: | -------: |
|    7 |        0 |
|    8 |        1 |
|   10 |        3 |
|   14 |        0 |
|   15 |        1 |
|   20 |        6 |
|   21 |        0 |

Basically:

> **Odd days = remainder after dividing by 7.**

---

# 4. Why months matter

Different months have different numbers of days:

| Month     |  Days |
| --------- | ----: |
| January   |    31 |
| February  | 28/29 |
| March     |    31 |
| April     |    30 |
| May       |    31 |
| June      |    30 |
| July      |    31 |
| August    |    31 |
| September |    30 |
| October   |    31 |
| November  |    30 |
| December  |    31 |

And we convert these into odd days.

### 31-day month:

\[
31\div7=4\text{ remainder }3
\]

So:

\[
\boxed{31\text{ days}=3\text{ odd days}}
\]

### 30-day month:

\[
30\div7=4\text{ remainder }2
\]

So:

\[
\boxed{30\text{ days}=2\text{ odd days}}
\]

### February:

Normal year:

\[
28\div7=0
\]

So:

\[
\boxed{0\text{ odd days}}
\]

Leap year:

\[
29\div7=1
\]

So:

\[
\boxed{1\text{ odd day}}
\]

---

# 5. Leap year — very important ⚠️

A year is generally a **leap year if it is divisible by 4**.

Examples:

2024 → leap year ✅
2028 → leap year ✅
2030 → not leap year ❌

But century years have an exception:

**1900** → not leap year ❌
**2000** → leap year ✅

Because century years must be divisible by **400**.

---

## 🧠 So your basic Calendar toolkit is:

### Remember these 5 things:

**1. Week = 7 days**

**2. Odd days = remainder after ÷7**

**3. 31 days → 3 odd days**

**4. 30 days → 2 odd days**

**5. February → 0 odd days normally, 1 in leap year**

Once these are clear, we can start solving actual TCS calendar questions.

Send me the **first calendar question from your material**, and I'll solve it **from zero, step-by-step, including the fastest exam trick**.
