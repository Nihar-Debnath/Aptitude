Exactly. 👍 **The (n-r) shortcut you learned for Combination does NOT work in the same way for Permutation.**

### Combination has this special property:

\[
\boxed{{}^nC_r={}^nC_{n-r}}
\]

So:

\[
{}^{10}C_8={} ^{10}C_2
\]

That means you can turn **8 into 2**, making the calculation much easier.

---

### Permutation does NOT have that property

You **cannot** say:

\[
{}^{10}P_8={} ^{10}P_2
\]

❌ Wrong.

In fact:

\[
{}^{10}P_8=1,814,400
\]

while:

\[
{}^{10}P_2=90
\]

Obviously, they're completely different.

### Why?

Because in Combination:

> Choosing 8 people from 10 is equivalent to choosing the **2 people left out**.

But in Permutation:

> Arranging 8 people is **not** equivalent to arranging the 2 people left out.

The **order of the 8 people matters**, so you can't use that symmetry trick.

---

### So keep your tricks separate 🧠

**COMBINATION (nCr):**

\[
\boxed{{}^nC_r={}^nC_{n-r}}
\]

✅ Use (n-r) to make (r) smaller.

**PERMUTATION (nPr):**

\[
\boxed{{}^nP_r=n(n-1)(n-2)\cdots}
\]

✅ Take exactly **r terms**.

For example:

\[
{}^{10}P_8
\]

→ 8 terms:

\[
10\times9\times8\times7\times6\times5\times4\times3
\]

That's the rule.
