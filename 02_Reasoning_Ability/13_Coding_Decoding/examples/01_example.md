![alt text](./images/image.png)

![alt text](./images/image-1.png)


---

![alt text](./images/image-2.png)

![alt text](./images/image-3.png)


---

![alt text](./images/image-4.png)


![alt text](./images/image-5.png)






Yes! This one looks **weird at first**, because it's not a simple `+1` or `-1` coding. But once you spot the trick, it's actually very easy. 😎

We have:

> **COMPUTER → RFUVQNPC**

We need:

> **MEDICINE → ?**

Let's go **very slowly**.

---

# Step 1: Write COMPUTER

```text
C O M P U T E R
```

The code is:

```text
R F U V Q N P C
```

At first glance, the letters don't seem to match.

So **don't compare C→R, O→F, etc. immediately.**

Instead, check whether the **order has been changed**.

---

# Step 2: Reverse COMPUTER

Write COMPUTER backwards:

```text
COMPUTER
   ↓
RETUPMOC
```

So:

```text
Original:   C O M P U T E R
Reversed:   R E T U P M O C
```

Now compare the reversed word with the code:

```text
Reversed:   R E T U P M O C
Code:       R F U V Q N P C
```

Look at this carefully! 👀

```text
R → R       SAME
E → F       +1
T → U       +1
U → V       +1
P → Q       +1
M → N       +1
O → P       +1
C → C       SAME
```

🔥 **THERE IS THE RULE!**

---

# 🧠 The rule

### 1. Reverse the entire word.

### 2. Keep the FIRST and LAST letters unchanged.

### 3. Move every middle letter **one step forward**.

So:

```text
COMPUTER
   ↓ reverse
RETUPMOC
   ↓ middle letters +1
RFUVQNPC
```

Let's visually see it:

```text
R   E   T   U   P   M   O   C
|   ↓   ↓   ↓   ↓   ↓   ↓   |
R   F   U   V   Q   N   P   C
```

Therefore:

**COMPUTER → RFUVQNPC**

---

# Now solve MEDICINE

Write it:

```text
M E D I C I N E
```

## Step 1: Reverse it

```text
MEDICINE
   ↓
ENICIDEM
```

So:

```text
E N I C I D E M
```

---

# Step 2: Keep first and last unchanged

The first letter:

```text
E → E
```

The last:

```text
M → M
```

Don't touch them.

---

# Step 3: Move all middle letters +1

Our middle letters are:

```text
N I C I D E
```

Move each one alphabetically forward by 1:

```text
N → O
I → J
C → D
I → J
D → E
E → F
```

So:

```text
E N I C I D E M
↓
E O J D J E F M
```

Therefore:

# ✅ MEDICINE → EOJDJEFM

That's **Option B** in your image. ([Testbook][1])

---

# 🔥 Remember this question with a simple formula

Whenever you see something like:

**WORD → strange-looking code**

First check:

### **R + M+1**

Meaning:

> **R = Reverse the word**
> **M+1 = Move the middle letters one step forward**

For this particular question:

```text
MEDICINE
↓
REVERSE
ENICIDEM
↓
FIRST + MIDDLE + LAST
E + NICIDE + M
↓
E + OJDJEF + M
↓
EOJDJEFM
```

### ⭐ Final answer: **EOJDJEFM**

And honestly, **don't try to memorize this exact question**. Learn the process:

> **First check whether the word is reversed → then check whether the middle letters are shifted.**

That's the kind of pattern spotting you want for Coding–Decoding.

[1]: https://testbook.com/question-answer/in-a-certain-code-computer-is-written-as-rfuvqnpc--63b12f81398476bea51abf09?utm_source=chatgpt.com "[Solved] In a certain code, COMPUTER is written as RFUVQNPC. How is M"


---
---
---
---
---


# Options elimination

YES! 🔥 **That is an even faster way to attack this question.**
For aptitude exams, **check the options first** whenever the options can eliminate possibilities.

Let's apply your method here.

## Given

**COMPUTER → RFUVQNPC**

We need:

**MEDICINE → ?**

---

### Step 1: Look at the first and last letters of the original word

```text
MEDICINE
↑      ↑
M      E
```

So original:

**M ........ E**

Now look at the given example:

```text
COMPUTER
↑      ↑
C      R
```

Its code is:

```text
RFUVQNPC
↑      ↑
R      C
```

🔥 Notice!

The **first and last letters have been swapped**:

```text
COMPUTER
C      R
↓      ↓
R      C
```

So for **MEDICINE**:

```text
MEDICINE
M      E
↓      ↓
E      M
```

Therefore, the answer **must start with E and end with M**.

---

## Step 2: Check the options FIRST

Options:

```text
A. MFEDJJOE    → M ........ E ❌
B. EOJDJEFM    → E ........ M ✅
C. MFEDJDOE    → M ........ E ❌
D. EOJDJEFM    → E ........ M
```

So immediately:

**A and C are eliminated.**

Now only:

```text
B. EOJDJEFM
D. EOJDJEFM
```

Wait — in the image, **B and D actually appear extremely similar**, so let's carefully distinguish them.

The image shows:

* **B: EOJDEJFM**
* **D: EOJDJEFM**

So the middle arrangement matters.

---

# Step 3: Now find the middle pattern

From:

```text
COMPUTER
```

Reverse it:

```text
RETUPMOC
```

Then compare with:

```text
RFUVQNPC
```

```text
R E T U P M O C
R F U V Q N P C
```

The first and last stay the same.

Every **middle letter moves +1**:

```text
E → F
T → U
U → V
P → Q
M → N
O → P
```

So the rule is:

> **Reverse the word, then shift all middle letters +1.**

---

# Step 4: Apply to MEDICINE

Original:

```text
M E D I C I N E
```

Reverse:

```text
E N I C I D E M
```

Now middle letters +1:

```text
E N I C I D E M
  ↓ ↓ ↓ ↓ ↓ ↓
  O J D J E F
```

So:

```text
E O J D J E F M
```

# ✅ Answer: **EOJDJEFM**

**Option D.**

---

## 🧠 Your exam shortcut

You just discovered a **very useful elimination technique**:

### Before solving the whole coding rule:

**1. Check first letter.**
**2. Check last letter.**
**3. Eliminate options that don't match.**
**4. Then solve only the remaining options.**

For this question:

```text
MEDICINE
M      E

↓ swap first & last

E      M
```

So immediately:

```text
A ❌
B/D ✅
C ❌
```

Then solve the middle.

### 🔥 Remember:

> **OPTIONS FIRST → ELIMINATION → THEN PATTERN**

This can save a **lot of time** in TCS/Cognizant reasoning questions.
