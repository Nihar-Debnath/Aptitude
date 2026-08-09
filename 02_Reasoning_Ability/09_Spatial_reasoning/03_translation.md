OH 😂 okay bro, **NOW I understand the problem.** You don't need the solution yet — you need to know **what "translation" even means**.

Forget the question for 30 seconds.

## What is Translation?

In coordinate geometry, **translation simply means moving a shape from one place to another without changing its shape or size.**

That's it.

Imagine this triangle:

```text
      A
     / \
    /   \
   /_____\
```

Now imagine you **pick up the entire triangle** and move it 5 steps to the left:

```text
   A
  / \
 /   \
/_____\
```

The triangle is still:

* same size ✅
* same shape ✅
* same orientation ✅

You just **moved it**.

That movement is called **TRANSLATION**.

---

## There are only 4 possible movements

### 1. Move RIGHT

```text
●  → → →  ●
```

That's:

\[
x+
\]

For example, 3 steps right:

\[
(x+3,y)
\]

---

### 2. Move LEFT

```text
●  ← ← ←  ●
```

That's:

\[
x-
\]

3 steps left:

\[
(x-3,y)
\]

---

### 3. Move UP

```text
    ●
    ↑
    ↑
    ●
```

That's:

\[
y+
\]

2 steps up:

\[
(x,y+2)
\]

---

### 4. Move DOWN

```text
    ●
    ↓
    ↓
    ●
```

That's:

\[
y-
\]

2 steps down:

\[
(x,y-2)
\]

---

# Now come back to YOUR question

The blue triangle is the **original**.

The green triangle is the **same triangle after being moved**.

So the question is basically asking:

> **"How was the blue triangle moved to become the green triangle?"**

That's all.

Look at point **A** on the blue triangle.

It is here:

\[
A=(2,-1)
\]

Its corresponding point on the green triangle is:

\[
A'=(-4,1)
\]

So physically:

### From A → A′

**2 → -4**

That's **6 steps LEFT**.

And:

**-1 → 1**

That's **2 steps UP**.

So the triangle was:

> **moved 6 left and 2 up.**

Therefore the translation is:

\[
\boxed{(x-6,\ y+2)}
\]

### 🧠 The one thing you need to remember

**Translation = MOVE the whole shape.**

| Movement | Coordinate change |
| -------- | ----------------- |
| Right    | (x+)              |
| Left     | (x-)              |
| Up       | (y+)              |
| Down     | (y-)              |

So whenever TCS gives you a **translation question**, don't think about some scary formula.

Just ask:

> **"Where did the shape move?"**

Then count **left/right/up/down**. That's it.
