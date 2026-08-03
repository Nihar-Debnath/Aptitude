Excellent! The next topic is **Paper Cutting & Paper Folding**, one of the highest-scoring topics in non-verbal reasoning.

It is asked in **TCS, Cognizant, Infosys, Wipro, Capgemini, Accenture**, SSC, Bank, and many government exams.

---

# What is Paper Cutting?

A paper is:

1. **Folded** one or more times.
2. **Cuts (holes)** are made on the folded paper.
3. The paper is **unfolded**.
4. You must determine **where all the holes will appear**.

Think of folding a real sheet of paper, punching a hole, and then opening it.

---

# Basic Concept

Imagine a square paper.

```text
+---------+
|         |
|         |
|         |
+---------+
```

Now fold it once.

```text
+----+
|    |
|    |
+----+
```

Punch one hole.

```text
+----+
|  • |
|    |
+----+
```

Open the paper.

The hole appears in **two places** because the folded paper had two layers.

```text
+---------+
|  •   •  |
|         |
|         |
+---------+
```

---

# Golden Rule

> **Every fold doubles the number of layers.**

Therefore, every cut is copied onto every layer.

| Number of Folds | Number of Layers | One Hole Becomes |
| --------------- | ---------------: | ---------------: |
| 0               |                1 |           1 hole |
| 1               |                2 |          2 holes |
| 2               |                4 |          4 holes |
| 3               |                8 |          8 holes |
| 4               |               16 |         16 holes |

This is the **first thing** you should calculate.

---

# Types of Folds

There are mainly four types.

---

# Type 1: Vertical Fold

The paper folds left to right (or right to left).

Original

```text
+---------+
|         |
|         |
|         |
+---------+
```

Fold

```text
+----+
|    |
|    |
+----+
```

If you make one hole here

```text
•
```

After unfolding

```text
•       •
```

The hole appears as a **left-right mirror image**.

---

# Type 2: Horizontal Fold

Fold from bottom to top.

Original

```text
+---------+
|         |
|         |
|         |
+---------+
```

After folding

```text
---------
```

Punch one hole.

Open it.

Result

```text
•
|
|
•
```

The holes are mirrored vertically.

---

# Type 3: Diagonal Fold

Fold along a diagonal.

Example

```text
+------+
|\     |
| \    |
|  \   |
+------+
```

Punch one hole.

After opening,

the hole appears symmetrically across the diagonal.

Diagonal folds are slightly harder because the reflection happens across the diagonal line.

---

# Type 4: Multiple Folds

Example

First fold vertically.

Then fold horizontally.

Now the paper has

```text
4 layers
```

One punched hole becomes

```text
4 holes
```

---

# Example 1

One vertical fold.

One hole.

Question:

How many holes after opening?

Solution

One fold

↓

Two layers

↓

Two holes

Answer

```text
2
```

---

# Example 2

Vertical fold

↓

Horizontal fold

↓

One hole

How many holes?

Solution

Two folds

↓

Four layers

↓

Four holes

Answer

```text
4
```

---

# Example 3

Three folds.

One hole.

Solution

Three folds

↓

Eight layers

↓

Eight holes

Answer

```text
8
```

---

# Position Matters

Suppose the hole is punched near a corner.

Original folded paper

```text
+----+
|•   |
|    |
+----+
```

When opened,

all holes appear near the corresponding corners.

The **distance from the fold line is always preserved**.

---

# Center Hole

Suppose the hole is punched exactly on the fold line.

Example

Fold once.

Punch

```text
|
•
|
```

When opened,

it remains

```text
•
```

because the hole lies exactly on the fold line.

It is **not duplicated**.

This is a very common trick.

---

# Corner Hole

Punch near the folded corner.

After opening,

all holes appear in symmetrical corner positions.

---

# Shape of the Hole

If the cut is

```text
○
```

Every copied hole is also

```text
○
```

If the cut is

```text
△
```

Every copy is

```text
△
```

The **shape does not change**.

Only its **position** changes.

---

# Common Tricks Used in Exams

## Trick 1

Students count folds incorrectly.

Remember:

Every fold **doubles** the number of layers.

---

## Trick 2

Ignoring the fold direction.

Vertical fold

↓

Mirror horizontally

Horizontal fold

↓

Mirror vertically

---

## Trick 3

Center Hole

Hole exactly on the fold line

↓

Only one hole appears.

---

## Trick 4

Multiple Symmetries

Example

Vertical

↓

Horizontal

↓

Diagonal

Students often forget the third reflection.

---

# Shortcut Formula

If the hole is **not on any fold line**:

```text
Number of Holes = 2^(Number of Folds)
```

Examples

```text
1 Fold → 2 holes

2 Folds → 4 holes

3 Folds → 8 holes

4 Folds → 16 holes
```

---

# Step-by-Step Method

Whenever you solve a paper cutting question:

### Step 1

Count the number of folds.

---

### Step 2

Identify the fold direction.

* Vertical
* Horizontal
* Diagonal

---

### Step 3

Count the number of layers.

Remember:

Every fold doubles the layers.

---

### Step 4

Check where the hole is.

* Corner?
* Edge?
* Centre?
* On the fold line?

---

### Step 5

Mentally unfold the paper **one fold at a time**.

This is much easier than imagining all folds opening together.

For example:

```text
Fold 3

↓

Open Fold 3

↓

Open Fold 2

↓

Open Fold 1
```

---

# Example

Paper

↓

Fold vertically

↓

Fold horizontally

↓

Punch one hole near the top-right of the folded paper.

Open once

↓

2 holes

Open again

↓

4 holes

The four holes appear symmetrically in all four quadrants.

---

# Common Mistakes

❌ Forgetting that each fold doubles the layers.

❌ Opening all folds at once instead of one by one.

❌ Ignoring the fold direction.

❌ Forgetting that holes on the fold line are **not duplicated**.

❌ Confusing diagonal reflection with vertical reflection.

---

# Placement Exam Difficulty

### TCS

⭐⭐ Easy

Mostly one or two folds.

---

### Cognizant

⭐⭐ Easy to Moderate

One or two folds with corner holes.

---

### Infosys

⭐⭐⭐ Moderate

Multiple folds and diagonal folds.

---

### Capgemini

⭐⭐⭐ Moderate

Paper folding and cutting are often combined.

---

### Accenture

⭐⭐⭐ Moderate

Usually two or three folds with slightly trickier hole positions.

---

# Quick Solving Checklist

Whenever you see a Paper Cutting question, ask yourself:

1. ✅ How many times is the paper folded?
2. ✅ In which direction is each fold (vertical, horizontal, diagonal)?
3. ✅ How many layers are formed?
4. ✅ Is the hole on a fold line or away from it?
5. ✅ Unfold the paper **one fold at a time**, copying the hole symmetrically at each step.

---

## Paper Folding vs Paper Cutting

Students often confuse these two topics.

| Paper Folding                      | Paper Cutting                                     |
| ---------------------------------- | ------------------------------------------------- |
| Focuses on how the paper is folded | Focuses on the final hole pattern after unfolding |
| Shows the folding sequence         | Shows folds **plus** punched holes                |
| You predict the folded shape       | You predict the hole positions after opening      |

### The one habit that makes these questions easy

Don't try to imagine the fully opened paper immediately. Instead, **reverse the process**:

* Open the **last fold** first.
* Reflect the hole across that fold.
* Then open the previous fold.
* Repeat until the paper is completely open.

This one-step-at-a-time approach is how most experienced test-takers solve paper cutting questions quickly and accurately.
