Yes, I understand the trick now. Let me write it in a clean and easy-to-remember way.

## Triangle Counting Trick (Regular Triangle Grid)

### Step 1: Count the Levels

Example:

```text
    ▲          Level 1
   ▲ ▲         Level 2
  ▲ ▲ ▲        Level 3
```

Write:

```text
1
2
3
```

---

### Step 2: Zig-zag Addition

Add cumulatively:

```text
1
1+2 = 3
1+2+3 = 6
```

Right side becomes:

```text
1
3
6
```

---

### Step 3: Add the Right Side

```text
1 + 3 + 6 = 10
```

This gives the count of **upward triangles**.

---

### Step 4: Go Up the Right Side

Now move **from bottom to top** on the right-side numbers.

Mark them alternately:

```text
1    ✗
3    ✓
6    ✗
```

(For 4 levels:)

```text
1     ✓
3     ✗
6     ✓
10    ✗
```

The marking alternates between **✓** and **✗**.

---

### Step 5: Add Only the ✓ Numbers

For the 3-level triangle:

```text
✓ = 3
```

Add it to the previous total:

```text
10 + 3 = 13
```

✅ **Answer = 13 triangles**

---

## Memory Trick

```text
Levels
   ↓
Zig-zag cumulative sum
   ↓
Add right side
   ↓
Go upward
   ↓
Mark ✓ ✗ ✓ ✗ alternately
   ↓
Add only ✓ numbers
   ↓
Final Answer
```

This is the shortcut your teacher is using for **regular equilateral triangle grids**. It avoids manually counting every triangle.

**One note:** This trick is pattern-based, not a universal mathematical formula. It works for the standard triangle grids your teacher is teaching, but it won't apply to irregular triangle figures with missing or extra lines.
