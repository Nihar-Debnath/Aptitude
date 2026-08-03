Excellent! The next topic is **Shape Construction**, also known as **Figure Formation**, **Figure Construction**, or **Formation of Figures**.

This topic appears in **TCS, Cognizant, Infosys, Wipro, Capgemini, Accenture**, SSC, Bank, and many government exams.

---

# What is Shape Construction?

In Shape Construction, you are given **2, 3, or more small pieces (parts)**.

Your task is to determine:

> **Which complete figure can be formed by combining all the given pieces?**

Think of it like solving a **jigsaw puzzle**.

Example

```text
Piece 1        Piece 2

┌──            ──┐
│                 │
```

When combined correctly

```text
┌────┐
│    │
└────┘
```

A square is formed.

---

# Objective

You are given

```text
Small Parts
        ↓
Combine them
        ↓
Choose the correct complete figure
```

---

# Basic Rules

Every piece must be used.

✔ Use all pieces.

❌ Don't leave any piece unused.

---

No piece can overlap another.

Wrong

```text
△
△
```

They cannot occupy the same space.

---

Pieces cannot be stretched.

Wrong

```text
Small triangle

↓

Large triangle
```

Size never changes.

---

Rotation is allowed.

Example

```text
L
```

can become

```text
┐
```

by rotating.

---

Mirror image is usually **NOT** allowed.

Unless the question specifically says so.

---

# Example 1

Pieces

```text
┌

┐

└

┘
```

Together they form

```text
┌──┐
│  │
└──┘
```

Answer

Square

---

# Example 2

Pieces

```text
△

△
```

Can form

```text
◇
```

if placed together.

---

# Example 3

Pieces

```text
○

Half Circle
```

Cannot become

```text
Square
```

Impossible.

---

# Types of Shape Construction

---

# Type 1: Line Construction

Example

Pieces

```text
|

—

/
```

Combine

↓

Triangle

---

# Type 2: Geometric Shapes

Pieces

```text
Two triangles
```

Can form

```text
Square

Diamond

Parallelogram
```

depending on the arrangement.

---

# Type 3: Curved Figures

Example

```text
Half Circle

Half Circle
```

↓

Circle

---

# Type 4: Mixed Pieces

Example

```text
Triangle

Rectangle

Circle
```

You may need to form a house-like figure.

---

# Most Common Patterns

---

## Pattern 1

Corner Matching

Every open corner should connect with another open corner.

Example

```text
┌

┘
```

Cannot connect directly.

But

```text
┌

┐
```

can.

---

## Pattern 2

Straight Line Matching

Small straight lines combine into one longer line.

---

## Pattern 3

Curves

Two semicircles become one circle.

---

## Pattern 4

Triangles

Two identical right triangles often become

* Rectangle
* Square
* Larger triangle

---

# Example

Pieces

```text
◢

◣
```

Together become

```text
▲
```

---

# Counting Technique

Suppose the pieces contain

```text
2 Curves

5 Straight Lines

3 Corners
```

The final figure must also contain exactly

```text
2 Curves

5 Straight Lines

3 Corners
```

Nothing disappears.

Nothing is created.

---

# Rotation Technique

Suppose the piece is

```text
L
```

Rotate

90°

```text
└
```

Rotate

180°

```text
⅃
```

Rotate

270°

```text
┐
```

Always try all four rotations mentally.

---

# Elimination Technique

Instead of finding the answer,

eliminate impossible options.

Example

Pieces contain

```text
3 Curves
```

Option A

```text
Only 2 Curves
```

Impossible.

Reject immediately.

---

# Common Tricks Used in Exams

---

## Trick 1

Wrong Rotation

Students forget to rotate pieces.

---

## Trick 2

Mirror Image

A mirror image is not the same as a rotation.

---

## Trick 3

Missing Piece

One option may not use every piece.

Reject it.

---

## Trick 4

Extra Corner

The completed figure has one extra corner.

Impossible.

---

## Trick 5

Curve Direction

A curved piece must connect naturally.

It cannot bend differently.

---

# Step-by-Step Method

Whenever you solve Shape Construction:

### Step 1

Count

* Lines
* Curves
* Corners

---

### Step 2

Look for unique pieces.

Example

A single curved edge.

Find where it can fit.

---

### Step 3

Rotate every piece mentally.

Try

* 90°
* 180°
* 270°

---

### Step 4

See whether all edges connect.

---

### Step 5

Check whether every piece is used exactly once.

---

# Example

Pieces

```text
◣

◢
```

Options

Triangle

Square

Circle

Star

Only Triangle can be formed.

---

# Placement Exam Difficulty

### TCS

⭐⭐ Easy

Basic geometric shapes.

---

### Cognizant

⭐⭐ Easy to Moderate

Rotation-based questions.

---

### Infosys

⭐⭐⭐ Moderate

Multiple pieces.

---

### Capgemini

⭐⭐⭐ Moderate

Combination of curves and straight lines.

---

### Accenture

⭐⭐⭐ Moderate

Requires visualization.

---

# Quick Solving Checklist

Whenever you see a Shape Construction question, check these in order:

1. ✅ Count the number of pieces.
2. ✅ Count lines, curves, and corners.
3. ✅ Rotate the pieces mentally (90°, 180°, 270°).
4. ✅ Ensure every piece is used exactly once.
5. ✅ Check that edges fit perfectly.
6. ✅ Reject options with extra or missing parts.
7. ✅ Remember: **rotation is allowed, mirror images usually are not.**

---

# Shape Construction vs Embedded Images vs Paper Cutting

| Topic                  | What You Do                                              |
| ---------------------- | -------------------------------------------------------- |
| **Shape Construction** | Combine small pieces to make one complete figure.        |
| **Embedded Images**    | Find a small figure hidden inside a larger figure.       |
| **Paper Cutting**      | Predict the hole pattern after unfolding a folded paper. |

### Final Strategy (Most Important)

For almost every Shape Construction question, follow this sequence:

1. **Count** (lines, curves, corners).
2. **Rotate** the pieces mentally.
3. **Match** edges and corners.
4. **Eliminate** impossible options.

This systematic method is much faster and more accurate than trying to visualize the final figure immediately, especially under placement exam time pressure.
