![alt text](./images/image.png)


Yes! This is a **shortcut for calculating combinations without writing the full factorial formula**.

The image is showing:

\[
{}^nC_r 
= 
\frac{\text{r terms}}{\text{r terms}}
=
\frac{n\times(n-1)\times(n-2)\times\cdots}{1\times2\times3\times\cdots}
\]

More precisely:

\[
\boxed{{}^nC_r=
\frac{n(n-1)(n-2)\cdots}{1\times2\times3\cdots r}}
\]

You only take **r terms** in the numerator and denominator.

---

## Example 1: \( ^8C_3 \)

Normally:

\[
{}^8C_3=\frac{8!}{3!5!}
\]

But the shortcut says:

### Take 3 terms from 8 downward:

\[
8\times7\times6
\]

### Take 3 terms from 1 upward:

\[
1\times2\times3
\]

Therefore:

\[
{}^8C_3=
\frac{8\times7\times6}{1\times2\times3}
\]

Cancel:

\[
=\frac{8\times7}{1}
\]

\[
=\boxed{56}
\]

Much faster.

---

## Example 2: \( ^{10}C_2 \)

Take **2 terms**.

Numerator:

\[
10\times9
\]

Denominator:

\[
1\times2
\]

Therefore:

\[
{}^{10}C_2
=

\frac{10\times9}{1\times2}
\]

\[
=45
\]

\[
\boxed{45}
\]

---

## BUT there is an even better trick 🔥

Always check whether **r is bigger than n/2**.

Because:

\[
{}^nC_r={}^nC_{n-r}
\]

For example:

\[
{}^{10}C_8
\]

Instead of calculating 8 terms, use:

\[
{}^{10}C_8={} ^{10}C_2
\]

Now only 2 terms:

\[
\frac{10\times9}{1\times2}
=45
\]

So:

\[
\boxed{{}^{10}C_8=45}
\]

### Remember this for exams:

**Step 1:** Look at (nCr).

**Step 2:** Choose the smaller of (r) and (n-r).

**Step 3:** Use that number of terms.

For example:

\[
{}^{15}C_{12}
\]

Since:

\[
15-12=3
\]

use:

\[
{}^{15}C_{12}={} ^{15}C_3
\]

Then:

\[
\frac{15\times14\times13}{1\times2\times3}
\]

That's the real **fast-calculation trick** behind the image.
