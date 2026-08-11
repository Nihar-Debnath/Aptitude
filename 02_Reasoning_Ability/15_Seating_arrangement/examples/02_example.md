# Type 2

![alt text](./images/image-9.png)

# This the just a setup to solve subproblems

---
---
---


# Now solve 

# 🟢 Point 1

I'll put the **boys on top** and **girls below**.

```text
BOYS
Position:   1    2    3    4    5
            _    _    _    _    _

GIRLS
Position:   1    2    3    4    5
            _    _    _    _    _
```

They are **facing each other**.

Let's assume:

```text
BOYS:   → → → → →  (actually facing DOWN)
                    ↓
GIRLS:  ↑ ↑ ↑ ↑ ↑  (facing UP)
```

The important thing is:

### Boys face South (important)

So their **right = our left**.

### Girls face North (important)

So their **right = our right**.


# Question

There are:

### Boys

* Ashwin
* Dipesh
* Eshan
* Chetan
* Bipin

### Girls

* Parul
* Komal
* Radha
* Savita
* Vimla

---


# 🟢 Point 2 — Eshan

> **Eshan is to the immediate right of Bipin and opposite to Parul. Eshan is not at any end.**

This is the first important clue.

Let's break it into pieces.

### First:

> Eshan is to the immediate right of Bipin.

Both are boys.

The boys are facing the girls.

So let's establish the physical direction.

```text
        BOYS
        ↓ ↓ ↓ ↓ ↓
        Eshan/Bipin

        ↑ ↑ ↑ ↑ ↑
       GIRLS
```

The boys are facing **downward**.

Therefore, from our viewpoint:

### A boy's RIGHT is our LEFT.

So if:

> Eshan is immediately RIGHT of Bipin

the physical arrangement from **our viewpoint** is:

```text
Eshan   Bipin
```

Not:

```text
Bipin   Eshan
```

This is a VERY important concept.

---

### Now use:

> Eshan is NOT at any end.

There are 5 positions:

```text
1   2   3   4   5
```

Eshan cannot be:

```text
1 ❌
5 ❌
```

So Eshan can only be:

```text
2, 3 or 4
```

Since Eshan must be immediately LEFT of Bipin:

### Possibility 1

```text
Eshan   Bipin
  2       3
```

### Possibility 2

```text
Eshan   Bipin
  3       4
```

### Possibility 3

```text
Eshan   Bipin
  4       5
```

So at this point:

```text
BOYS:

_   E   B   _   _
```

OR

```text
BOYS:

_   _   E   B   _
```

OR

```text
BOYS:

_   _   _   E   B
```

We **don't choose yet**.

---

### Now use the second part:

> Eshan is opposite Parul.

That means wherever Eshan is, **Parul goes directly underneath him**.

For example, if:

```text
BOYS:   _   E   B   _   _
             ↓
GIRLS:  _   P   _   _   _
```

So Parul occupies the **same position number** as Eshan.

But we still don't know whether Eshan is 2, 3 or 4.

So we keep the possibilities.

---

# 🟢 Point 3 — Radha

Now we move to the **next sentence**.

> **Radha, who is immediate to the right of Komal and opposite to Chetan, is at one of the ends.**

First:

> Radha is at one of the ends.

There are only two ends:

```text
1   2   3   4   5
↑               ↑
end             end
```

So:

**Radha = position 1 OR position 5**

---

### Radha is immediately right of Komal.

Radha cannot be position 1 because then Komal would have to be outside the row.

Therefore:

```text
Komal   Radha
   4      5
```

So:

**Komal = 4**
**Radha = 5**

---

### Radha is opposite Chetan.

Radha = position 5.

Therefore:

```text
BOYS:    _   _   _   _   Chetan
                         ↓
GIRLS:   _   _   _   Komal  Radha
```

So:

**Chetan = position 5.**

---

# 🟢 Now we can return to Point 2!

Remember our three Eshan possibilities:

### Possibility 1

```text
Eshan   Bipin
  2       3
```

This is still possible.

### Possibility 2

```text
Eshan   Bipin
  3       4
```

But position 4 is **Ashwin later**, not known yet. So still possible.

### Possibility 3

```text
Eshan   Bipin
  4       5
```

But wait!

We just discovered:

**Chetan = position 5.**

Therefore Bipin cannot be position 5.

❌ Possibility 3 eliminated.

So now:

```text
Eshan-Bipin
can only be:

_ E B _ C

OR

_ _ E B C
```

---

# 🟢 Point 4

> **Ashwin is opposite to Komal who is the third to the right of Savita.**

We already know:

**Komal = position 4.**

And:

> Komal is third to the right of Savita.

Girls face North.

So their right is our right.

Starting from Savita:

```text
Savita
   ↓
position 1 → 2 → 3 → 4
                       ↑
                     Komal
```

Therefore:

**Savita = position 1.**

So girls are now:

```text
Savita   _   _   Komal   Radha
   1     2   3     4       5
```

And:

> Ashwin is opposite Komal.

Komal = position 4.

Therefore:

**Ashwin = position 4.**

Boys:

```text
_   _   _   Ashwin   Chetan
1   2   3     4        5
```

---

# 🟢 Now return to Eshan again

Our remaining possibilities were:

### Option A

```text
Eshan   Bipin   _   Ashwin   Chetan
  1?      2?      3     4       5
```

Wait — Eshan cannot be position 1 because the question explicitly says **Eshan is not at any end**.

So let's correctly write the two remaining possibilities:

### Option A

```text
_   Eshan   Bipin   Ashwin   Chetan
1     2       3       4        5
```

### Option B

```text
_   _   Eshan   Bipin   Ashwin
```

But this would put Chetan at position 5, while Bipin is position 4 — actually this clashes because **Ashwin is position 4**.

So:

```text
_   _   Eshan   Bipin   Chetan
```

would require Bipin = 4, but position 4 = Ashwin.

❌ Impossible.

Therefore:

# Eshan = 2

# Bipin = 3

And:

**Parul is opposite Eshan → Parul = 2.**

---

# 🟢 Point 5

> **Dipesh and Vimla are not opposite each other.**

We now have:

### Boys

```text
Dipesh   Eshan   Bipin   Ashwin   Chetan
   1       2       3       4        5
```

### Girls

```text
Savita   Parul   Vimla   Komal   Radha
   1       2       3      4       5
```

The only remaining boy is **Dipesh = 1**.

The only remaining girl is **Vimla = 3**.

And:

```text
Dipesh = 1
Vimla  = 3
```

They are **not opposite**.

✅ Final condition also works.

---

# 🎯 FINAL ANSWER

```text
             BOYS
       ↓      ↓      ↓      ↓      ↓

       Dipesh Eshan Bipin Ashwin Chetan
         1      2     3     4      5
         │      │     │     │      │
       Savita Parul Vimla Komal  Radha
         1      2     3     4      5

             GIRLS
       ↑      ↑      ↑      ↑      ↑
```

So the final arrangement is:

### Boys

**Dipesh → Eshan → Bipin → Ashwin → Chetan**

### Girls

**Savita → Parul → Vimla → Komal → Radha**

---
---
---
---
---
---
---





![alt text](./images/image-10.png)
![alt text](./images/image-11.png)



Exactly! **You got the structure now.** 🔥

What you showed is an important distinction:

## 🪑 Seating Arrangement has 2 parts

### 1. Arrangement data / puzzle

This is the **long paragraph** we just solved:

> Eshan is to the immediate right of Bipin...
> Radha is immediate right of Komal...
> Ashwin is opposite Komal... etc.

This gives us enough information to **build the arrangement**.

We got:

```text
BOYS
1        2       3       4        5
Dipesh   Eshan   Bipin   Ashwin   Chetan
  ↓        ↓       ↓       ↓        ↓
Savita   Parul   Vimla   Komal    Radha
1        2       3       4        5
GIRLS
```

---

# 2. Sub-questions

Then the exam doesn't necessarily ask:

> "Find the complete arrangement."

Instead, **the arrangement becomes the base information**, and they ask several small questions from it.

That's exactly what your screenshots show.

### (i) Who is in the middle of the row of boys?

There are 5 boys:

```text
Dipesh | Eshan | BIPIN | Ashwin | Chetan
                  ↑
               middle
```

Middle of 5 positions = **position 3**

### Answer: **Bipin** ✅

---

### (ii) Who is immediately to the right of Parul?

Parul is a **girl**, and girls are facing North.

Girls:

```text
Savita | PARUL | Vimla | Komal | Radha
                  ↑
               right
```

So immediately right of Parul = **Vimla**

### Answer: **Vimla** ✅

---

### (iii) Who is opposite Dipesh?

Dipesh is at position 1.

Look directly underneath:

```text
Dipesh
  ↕
Savita
```

### Answer: **Savita** ✅

---

### (iv) How many boys are between Ashwin and Bipin?

Boys:

```text
Dipesh | Eshan | Bipin | Ashwin | Chetan
                 ↑       ↑
               Bipin   Ashwin
```

Between Bipin and Ashwin:

**Nobody.**

They are immediately next to each other.

### Answer: **0** ✅

---

# 🎯 So YES — your understanding is correct

The **long paragraph is the main arrangement puzzle**.

Once you've solved it, the exam can give you:

```text
             ONE ARRANGEMENT
                    ↓
       ┌────────────┼────────────┐
       ↓            ↓            ↓
   Question 1   Question 2   Question 3
       ↓            ↓            ↓
    Question 4   Question 5   Question 6
```

These are called **sub-questions / questions based on the same arrangement**.

---

# 🚨 And this changes how you should approach the exam

Suppose a question has **5 sub-questions** based on one arrangement.

You should **not solve the arrangement separately for every question.**

You solve the arrangement **ONCE**.

Then keep your diagram:

```text
BOYS
1       2       3       4       5
Dipesh  Eshan   Bipin   Ashwin   Chetan

GIRLS
1       2       3       4       5
Savita  Parul   Vimla   Komal    Radha
```

Then answer all the sub-questions from this diagram.

That's much faster.

### This is actually good news for your exam.

A long arrangement may look like a huge question, but if it gives **4–5 sub-questions**, you spend your time **building the arrangement once** and then collect multiple answers from it.

So when we continue learning seating arrangement, I'll teach you:

**Arrangement → how to build it → how to handle the sub-questions → shortcuts for answering them quickly.**
