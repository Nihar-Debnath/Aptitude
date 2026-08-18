![alt text](image-1.png)

😂 Okay, fair. I jumped straight into the solution without first explaining **what the hell the question is actually asking**.

Let's start from **absolute zero**.

# What does "digit" mean?

A **digit** is just one symbol from 0 to 9.

There are only **10 digits**:

[
\boxed{0,1,2,3,4,5,6,7,8,9}
]

Numbers are made using digits.

For example:

[
\boxed{247}
]

has **3 digits**:

* 2
* 4
* 7

And:

[
\boxed{522}
]

has:

* 5
* 2
* 2

Notice that **2 appears twice** in 522.

---

# Now what is this question asking?

The question says:

> How many times does the digit **2** appear in the integers from **112 to 375**?

Forget the scary wording.

It's simply asking:

> **If I write every number from 112 to 375, how many individual 2's will I see?**

That's it.

For example, imagine we only had:

### From 112 to 115:

```text
112
113
114
115
```

Look for the digit **2**.

### 112

There are **two 2s**:

```text
1 2 2
  ↑ ↑
```

So that's **2 occurrences**.

### 113

```text
1 1 3
```

No 2 → **0**

### 114

No 2 → **0**

### 115

No 2 → **0**

So from 112 to 115, the digit 2 appears:

[
\boxed{2\text{ times}}
]

---

# Now imagine the FULL range

The question wants you to write:

```text
112
113
114
115
116
117
118
119
120
121
122
123
...
375
```

and count every **2**.

Obviously, writing 264 numbers and manually counting 2's would be stupid.

So we develop a **shortcut**.

---

# First, understand the positions

Take a number like:

[
\boxed{247}
]

It has three positions:

| Hundreds | Tens | Units |
| -------- | ---- | ----- |
| 2        | 4    | 7     |

So:

* **2** is in the hundreds position
* **4** is in the tens position
* **7** is in the units position

Another number:

[
\boxed{322}
]

| Hundreds | Tens | Units |
| -------- | ---- | ----- |
| 3        | 2    | 2     |

Here, the digit **2 appears twice**.

One in the tens position.

One in the units position.

---

# That's the trick!

Instead of looking at every number individually, we count:

### How many 2s are in the:

**Hundreds position?**

*

**Tens position?**

*

**Units position?**

Then add them.

---

# Let's do ONLY the hundreds position first

Our numbers are:

[
112\rightarrow375
]

Look at the hundreds digit.

We want the hundreds digit to be **2**.

Which numbers have 2 in the hundreds position?

```text
200
201
202
203
204
...
299
```

Every number from:

[
200\text{ to }299
]

has a **2 in the hundreds place**.

How many numbers?

[
299-200+1=100
]

So there are:

[
\boxed{100}
]

2s in the hundreds position.

---

# Now tens position

We want the **middle digit** to be 2.

Look at:

```text
120
121
122
123
...
129
```

That's 10 numbers.

Then:

```text
220
221
222
...
229
```

Another 10.

Then:

```text
320
321
322
...
329
```

Another 10.

Therefore:

[
10+10+10=30
]

So there are:

[
\boxed{30}
]

2s in the tens position.

---

# Finally, units position

We want the **last digit** to be 2.

For example:

```text
112
122
132
142
152
...
```

All these end in 2.

Then:

```text
202
212
222
232
...
```

And:

```text
302
312
322
...
```

Counting them gives:

[
\boxed{27}
]

---

# Now combine them

Hundreds:

[
100
]

Tens:

[
30
]

Units:

[
27
]

Therefore:

[
100+30+27
]

[
\boxed{157}
]

So the digit **2 appears 157 times**.

---

# 🧠 But don't worry about the shortcut yet

For now, I want you to understand the **concept**:

### A number has positions:

[
\boxed{\text{Hundreds | Tens | Units}}
]

Example:

[
\boxed{3|2|7}
]

means:

* 3 hundreds
* 2 tens
* 7 units

And when a question asks:

> "How many times does digit 2 appear?"

we count every position where **2 occurs**.

For example:

### 222

```text
2 | 2 | 2
↑   ↑   ↑
```

That's **3 occurrences**.

### 205

```text
2 | 0 | 5
↑
```

That's **1 occurrence**.

### 120

```text
1 | 2 | 0
    ↑
```

That's **1 occurrence**.

### 111

```text
1 | 1 | 1
```

That's **0 occurrences**.

---

## 🔥 So this is NOT really a difficult mathematical concept.

It's basically:

> **"Count how many times a particular digit appears when a range of numbers is written."**

The shortcut comes **after** you understand what you're counting.

And for your TCS prep, I'd learn this from the ground up with a few tiny examples first, because once the concept clicks, the shortcut becomes almost mechanical.



---
---
---
---
---
---
---




Exactly — **the units place is the only slightly tricky part** because our range starts at **112** and ends at **375**.

Let's do it slowly. No shortcut yet.

We want numbers whose **last digit is 2**.

---

## 1. Start from 112

Look at the numbers:

```text
112  ← ends in 2 ✅
113
114
115
116
117
118
119
120
121
122  ← ends in 2 ✅
123
...
```

So the first number in our range ending in 2 is:

[
\boxed{112}
]

Then every **10 numbers**, another number ends in 2:

[
112,\ 122,\ 132,\ 142,\ 152,\ldots
]

Why every 10?

Because the last digit cycles:

```text
112
113
114
115
116
117
118
119
120
121
122  ← next 2
```

---

# 2. Continue until 199

The numbers ending in 2 are:

[
112,122,132,142,152,162,172,182,192
]

Count them:

[
\boxed{9}
]

So from **112 to 199**, there are **9** occurrences.

---

# 3. Now 200 to 299

Here it's easier because we're starting from 200.

Numbers ending in 2:

[
202,212,222,232,242,252,262,272,282,292
]

Count them:

[
\boxed{10}
]

Why exactly 10?

Because from 200 to 299 there are 100 numbers, and **one out of every 10** ends in 2.

---

# 4. Now 300 to 375

Again, look at numbers ending in 2:

[
302,312,322,332,342,352,362,372
]

Then:

[
382
]

would be next, BUT...

🚨 Our range stops at **375**.

So 382 is outside the range.

Therefore we have:

[
\boxed{8}
]

---

# 5. Add the three sections

### 112–199:

[
9
]

### 200–299:

[
10
]

### 300–375:

[
8
]

Therefore:

[
9+10+8
]

[
\boxed{27}
]

So there are **27 occurrences of 2 in the units position**.

---

## 🧠 The pattern you should remember

For **units digit**, just look at the numbers ending in that digit.

For digit 2:

```text
...2
...12
...22
...32
...42
...52
...62
...72
...82
...92
```

They appear **every 10 numbers**.

That's why counting the units digit is basically:

> **Find the first number ending in 2 → keep adding 10 → stop when you pass the upper limit.**

For this question:

[
112,\ 122,\ 132,\ldots,372
]

That's your sequence. ❤️
