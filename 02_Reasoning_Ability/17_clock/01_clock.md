In **Reasoning Ability**, **Clock** is a topic where you solve questions involving the **positions of the hour and minute hands of a clock**.

It is basically **mathematics + angles**.

Don't worry — the concept is actually quite small once you understand the clock.

## 1. The basic idea

A clock has **12 numbers**:

```text
             12
        11        1

     10              2

   9                    3

     8              4

        7        5
             6
```

A complete circle = **360°**

There are 12 equal divisions.

So the angle between two consecutive numbers is:

\[
\frac{360°}{12} = 30°
\]

Therefore:

> **Each number gap = 30°**

For example:

* 12 → 1 = 30°
* 12 → 2 = 60°
* 12 → 3 = 90°
* 12 → 6 = 180°

---

# 2. What type of questions come?

You'll usually see questions like:

### Type 1 — Find the angle

> What is the angle between the hands at **3:00**?

At 3:00:

* Minute hand → 12
* Hour hand → 3

There are 3 gaps.

\[
3 \times 30° = 90°
\]

Answer = **90°**

---

### Type 2 — Find the angle at a particular time

For example:

> Find the angle between the hands at **4:30**.

This is where it gets interesting because the **hour hand doesn't stay exactly on the number**.

At 4:30:

Minute hand → 6.

But the hour hand has moved **halfway from 4 toward 5**.

So you can't simply say:

\[
4 \times 30 = 120°
\]

That's a common mistake.

---

# 3. The most important thing to understand

### Minute hand

The minute hand completes:

\[
360° \text{ in 60 minutes}
\]

Therefore:

\[
\boxed{6° \text{ per minute}}
\]

So at 30 minutes:

\[
30 \times 6 = 180°
\]

---

### Hour hand

The hour hand completes:

\[
360° \text{ in 12 hours}
\]

Therefore:

\[
30° \text{ per hour}
\]

But it also moves gradually.

In 60 minutes it moves 30°.

Therefore:

\[
\frac{30}{60} = \boxed{0.5° \text{ per minute}}
\]

This **0.5° per minute** is extremely important.

---

# 4. The formula you'll eventually learn

For a time:

> **H : M**

The positions are:

### Minute hand

\[
\boxed{6M}
\]

### Hour hand

\[
\boxed{30H + 0.5M}
\]

Therefore the angle between them is:

\[
\boxed{|30H - 5.5M|}
\]

And because a clock has two angles between the hands, the smaller angle is:

\[
\boxed{\min(\theta,360-\theta)}
\]

where

\[
\theta=|30H-5.5M|
\]

---

## But don't memorize the formula yet.

Since you're **new to these reasoning topics**, first understand **WHY** the hands move the way they do.

The entire Clock topic is basically built from these four facts:

| Fact                 |           Value |
| -------------------- | --------------: |
| Full clock           |            360° |
| 12 number gaps       |              12 |
| Each number gap      |         **30°** |
| Minute hand movement |   **6°/minute** |
| Hour hand movement   | **0.5°/minute** |

Once these are clear, questions like:

* Find angle at 5:20
* When will hands coincide?
* When will hands be opposite?
* When will they be at right angles?
* How many times do hands overlap?
* Find the time when angle is 60°

all become variations of the **same basic concept**.
