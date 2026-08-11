![alt text](./images/image-12.png)

YES! 🔥 **Now you've got the proper exam approach.** And I agree: **Method 1 is better** because it uses the options more aggressively and avoids unnecessary decoding.

Let's organize it cleanly so you can remember it.

# Coding–Decoding Q10

Given:

**RADAR → `*?*?#`**
**DOOR → `?%%#`**

Find **DAM**.

---

## 🥇 Method 1 — Frequency + Options ⭐ BEST

### Step 1: Look at RADAR

```text
R A D A R
```

Frequency:

```text
R → 2 times
A → 2 times
D → 1 time
```

Code:

```text
* ? * ? #
```

Frequency:

```text
* → 2 times
? → 2 times
# → 1 time
```

Therefore:

> **D = #**

We don't care about the position.

### Step 2: DAM must contain `#`

Because:

```text
D = #
```

Check options:

```text
A. ?#%  → contains # ✅
B. *#?  → contains # ✅
C. *#/  → contains # ✅
D. ??#  → contains # ✅
```

So not enough yet.

---

### Step 3: Use DOOR

```text
D O O R
```

We already know:

```text
D = #
```

O occurs **twice**, and in the code:

```text
? % % #
```

So:

```text
O = %
```

Therefore:

```text
D = #
O = %
```

R gets the remaining `?`.

So:

```text
R = ?
```

Now our target is:

```text
D A M
```

It contains:

* D → `#`
* A → unknown here
* M → unknown

But importantly, **DAM does NOT contain R or O**.

So eliminate options containing their codes:

```text
A. ?#%   → ? = R, % = O ❌
B. *#?   → ? = R ❌
D. ??#   → ? = R ❌
```

Only:

```text
C. *#/
```

remains.

# ✅ Answer = C. `*#/`

---

# 🥈 Method 2 — Direct Decoding

From RADAR:

```text
D = #
```

From the pattern:

```text
R A D A R
? * # * ?
```

So:

```text
A = *
```

Therefore:

```text
D A = # *
```

Now **M is a new/unique letter**, so its symbol should be the remaining new symbol in the answer.

```text
DAM → # * /
```

Depending on the coding convention/options, the corresponding option is **C: `*#/`**.

---

# 🧠 Why Method 1 is better

You're absolutely right about this.

### Method 1:

```text
Frequency
   ↓
D = #
   ↓
DOOR
   ↓
O = %
R = ?
   ↓
Eliminate options
   ↓
C
```

You **don't need to determine A or M at all**.

### Method 2:

```text
D = #
A = *
M = ?
   ↓
Check options
```

You have to decode more information.

---

## 🔥 Your Coding–Decoding strategy from now on

When options are given:

### **1. Look for frequency/repetition first**

Especially when symbols are involved.

### **2. Find only the letters relevant to eliminating options.**

### **3. Use the options aggressively.**

### **4. Don't decode letters you don't need.**

Your rule is basically:

> **"Don't solve the whole code. Solve only enough to kill the wrong options."** 😎

That's exactly the kind of approach you want in a timed TCS/Cognizant reasoning exam.
