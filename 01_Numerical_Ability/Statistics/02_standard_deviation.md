**Standard Deviation (SD)** tells us **how spread out the data is from the average (mean).**

Think of it like this:

> **Mean tells you the center.**
> **Standard Deviation tells you how far the values are from that center.**

$$\sigma = \sqrt{\frac{1}{N}\sum_{i=1}^{N}(x_i-\mu)^2}$$

---

# Example 1: Small Standard Deviation

Suppose the marks are:

**48, 49, 50, 51, 52**

Mean = **50**

Distance from the mean:

* 48 → 2 away
* 49 → 1 away
* 50 → 0 away
* 51 → 1 away
* 52 → 2 away

All the marks are very close to the average.

✅ **Standard Deviation is small.**

---

# Example 2: Large Standard Deviation

Now consider:

**10, 30, 50, 70, 90**

Mean = **50**

Distance from the mean:

* 10 → 40 away
* 30 → 20 away
* 50 → 0 away
* 70 → 20 away
* 90 → 40 away

The marks are spread out over a much wider range.

✅ **Standard Deviation is large.**

---

# Real-Life Example

Imagine two students.

### Student A

Marks:

80, 81, 79, 82, 78

Average = 80

The marks stay close to 80 every time.

➡️ Small Standard Deviation

---

### Student B

Marks:

30, 95, 60, 100, 15

Average = 60

The average looks okay, but the marks vary a lot.

➡️ Large Standard Deviation

---

# Easy Analogy

Imagine five friends standing in a line.

### Case 1

```
49 50 50 51 50
```

Everyone is standing close together.

➡️ Small Standard Deviation

---

### Case 2

```
10         50         90
```

People are standing far apart.

➡️ Large Standard Deviation

---

# Formula (for understanding)

\[
SD=\sqrt{\frac{\sum (x-\text{Mean})^2}{N}}
\]

Don't worry if this looks complicated.

The computer (or calculator) does the calculations. The important idea is:

1. Find the mean.
2. Measure how far each value is from the mean.
3. Square those distances.
4. Average them.
5. Take the square root.

The result is the **Standard Deviation**.

---

# Difference Between Range and Standard Deviation

| Range                                     | Standard Deviation                        |
| ----------------------------------------- | ----------------------------------------- |
| Uses only the smallest and largest values | Uses **every** value                      |
| Very simple                               | More accurate                             |
| Formula = Max − Min                       | Measures the average spread from the mean |

---

# Placement Exam Tip (TCS/Cognizant)

For most fresher aptitude exams, you usually only need to know:

* **Small SD** → Data is consistent and close to the mean.
* **Large SD** → Data is scattered and far from the mean.
* **SD = 0** → Every value is exactly the same.

Questions requiring full SD calculations are uncommon in entry-level placement tests; they more often test the concept than the computation.
