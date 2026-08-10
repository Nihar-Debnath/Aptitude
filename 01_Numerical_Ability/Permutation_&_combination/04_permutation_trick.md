Ahhh yes 😄 — **that's another important shortcut you haven't learned yet.** Let's add it properly.

The trick is:

\[
\boxed{{}^nP_r=n\times(n-1)\times(n-2)\times\cdots}
\]

You don't need to use the factorial formula every time.

---

## Why does this work?

Go back to the **10 people, 4 chairs** question.

```text
Chair 1   Chair 2   Chair 3   Chair 4
   _         _         _         _
```

### Chair 1

There are **10 people** available.

So:

\[
10
\]

choices.

### Chair 2

One person has already been used.

So **9 people** remain:

\[
9
\]

choices.

### Chair 3

Now 2 people have been used.

So:

\[
8
\]

choices.

### Chair 4

Now 3 people have been used.

So:

\[
7
\]

choices.

Therefore:

\[
10\times9\times8\times7
\]

That's why:

\[
{}^{10}P_4=10\times9\times8\times7
\]

\[
=\boxed{5040}
\]

---

# So what's the general trick?

If you have:

\[
{}^nP_r
\]

Start from **n** and multiply **r consecutive decreasing numbers**.

### Example:

\[
{}^8P_3
\]

Need **3 terms**:

\[
8\times7\times6
\]

\[
=\boxed{336}
\]

---

### Another:

\[
{}^{10}P_2
\]

Need **2 terms**:

\[
10\times9
\]

\[
=\boxed{90}
\]

---

### Another:

\[
{}^7P_5
\]

Need **5 terms**:

\[
7\times6\times5\times4\times3
\]

---

## 🔥 Why I like this method for aptitude

You don't even have to think about factorials.

Just remember:

### Combination

\[
{}^nC_r
\]

→ **choose**

### Permutation

\[
{}^nP_r
\]

→ **arrange**

And for quick calculation:

\[
\boxed{{}^nP_r=n(n-1)(n-2)\ldots}
\]

**Take exactly (r) numbers.**

So when you see:

\[
{}^{10}P_4
\]

your brain should immediately go:

> "Start at 10, need 4 numbers."

\[
10\rightarrow9\rightarrow8\rightarrow7
\]

\[
\boxed{10\times9\times8\times7}
\]

That's the shortcut you just learned.
