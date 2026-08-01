![](./images/image%20copy%202.png)

This is one of the **most common logical mistakes** in Data Sufficiency.

You are thinking:

> "Jethalal goes to the temple today, so today must be a festival."

That sounds reasonable, **but it's not what the statement says.**

Let's analyze it carefully.

---

# Given Information

The question says:

```text
Jethalal visits the temple on every festival day.
```

Let's convert it into logic.

```
Festival Day
      ↓
 Goes to Temple
```

This means:

> **If it's a festival, then Jethalal definitely goes to the temple.**

In logical notation:

```
Festival  →  Temple
```

---

# Very Important

Does this sentence say:

> "Jethalal goes to the temple ONLY on festival days"?

❌ No.

It only says:

> "On every festival day, he goes."

Maybe he also goes:

* Every Monday
* Every Sunday
* When he is happy
* Every morning

The question never says he goes **only** on festivals.

---

# Think of a Real-Life Example

Suppose I say:

> **"I drink coffee every Monday."**

Does that mean I drink coffee **only** on Mondays?

❌ No.

I might also drink coffee on Tuesday, Wednesday, Friday...

So if you see me drinking coffee today,

Can you conclude today is Monday?

❌ No.

Exactly the same logic applies here.

---

# Now Solve Statement A

Statement A:

```text
Jethalal went to the temple today.
```

We know:

```
Festival → Temple
```

But we are given:

```
Temple
```

Can we conclude:

```
Festival
```

❌ No.

Because there may be many other reasons he went.

So Statement A is **NOT sufficient**.

---

# A Small Diagram

Given:

```
Festival Days
     │
     ▼
Temple Visits
```

Temple visits are a **bigger set**.

Example:

```
Temple Visits
┌─────────────────────┐
│ Sunday              │
│ Monday              │
│ Festival Day        │
│ Birthday            │
│ Personal Prayer     │
└─────────────────────┘
```

Festival days are only one reason for visiting the temple.

---

# Statement B

```
He does not go to the temple if he is very busy.
```

This means:

```
Busy
   ↓
No Temple
```

Does this tell us whether today is a festival?

❌ No.

---

# Both Together

Statement A:

```
Temple Today
```

Statement B:

```
Busy → No Temple
```

Can we determine if today is a festival?

No.

Maybe:

* Today is a festival, and he wasn't busy.
* Today isn't a festival, but he wanted to pray.
* Today isn't a festival, but he visited for another reason.

Still impossible.

So the answer is:

✅ **Option D**

> The question cannot be answered even if both statements are taken together.

---

# The Rule You Need to Learn

This is a famous logical concept.

Suppose someone says:

```
If A happens,
then B happens.
```

```
A → B
```

Then:

If you know **A**, you can conclude **B**.

✅ Correct.

Example:

```
Festival → Temple
```

Festival?

✅ Then Temple.

---

But if you know **B**,

Can you conclude **A**?

❌ No.

Temple?

Doesn't necessarily mean Festival.

---

# One More Example

Suppose I tell you:

```
If it rains,
the road becomes wet.
```

```
Rain → Wet Road
```

Now you see:

```
Road is wet.
```

Can you say:

```
It rained.
```

❌ No.

Maybe:

* Someone washed the road.
* A water tanker spilled water.
* A pipe burst.

The road can be wet for many reasons.

---

## This is exactly the same question.

```
Festival → Temple
```

You know:

```
Temple
```

You **cannot** conclude:

```
Festival
```

---

## This logical pattern appears very frequently in TCS aptitude.

Whenever you see statements like:

* "Every..."
* "All..."
* "If... then..."
* "Whenever..."

always write them as an arrow:

```
Condition  →  Result
```

Then remember:

* ✅ **Condition → Result** is valid.
* ❌ **Result → Condition** is **not** valid unless the question explicitly says "**if and only if**" or "**only**". This single idea will help you avoid many logical mistakes in Data Sufficiency and Reasoning.
