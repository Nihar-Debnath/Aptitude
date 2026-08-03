![alt text](./related_images/image-11.png)


These **3 rules are the foundation of solving every syllogism question**. If you understand them, you won't need to memorize answers.

Let's go one by one.

---

# Rule 1: Draw the basic diagram first with minimum overlap

This is the most confusing sentence, but it's actually simple.

**Minimum overlap** means:

> **Don't assume any extra relationship unless the statement forces you to.**

### Example 1

Statement:

```text
Some A are B
```

Possible diagrams are:

```text
Case 1              Case 2

  A      B            B
 ( )##( )         +--------+
                  |  A     |
                  +--------+
```

Both are correct.

But when solving questions, we first draw the **simplest** one:

```text
     A       B

    ( )##( )
```

Just a small overlap.

Why?

Because the statement only says:

> Some A are B.

It never says:

> All A are B.

So we should not assume that.

---

### Another example

Statement:

```text
Some Students are Engineers.
```

Don't draw

```text
All Students are Engineers
```

Draw

```text
Students     Engineers

   ( )##( )
```

This is called **minimum overlap**.

---

# Rule 2

> If a conclusion is FALSE in even ONE possible diagram, then it DOES NOT FOLLOW.

This is the golden rule.

Let's understand.

---

### Statements

```text
Some Cats are Animals.
```

Question

```text
All Cats are Animals.
```

Now think.

Can I draw a diagram where

```text
Some Cats are Animals
```

is true,

but

```text
All Cats are Animals
```

is false?

Yes.

```text
Animals

      _________
     /         \
    /   ###     \
   /________     \
            \     \
             \_____\
              Cats
```

Some cats are animals.

Some cats are outside.

So

```text
All Cats are Animals
```

is false.

Because **one valid diagram** makes the conclusion false,

the conclusion

❌ **Does not follow.**

You don't need to check other diagrams anymore.

---

# Rule 3

> A conclusion follows only if it is TRUE in ALL possible diagrams.

Example

Statement

```text
All Dogs are Animals.
```

Possible diagram

```text
Animals

+------------------+
|                  |
|   Dogs           |
|                  |
+------------------+
```

Question

```text
Some Dogs are Animals.
```

Could there be another valid diagram?

No.

Whenever all dogs are animals,

every possible diagram will have dogs inside animals.

Therefore,

```text
Some Dogs are Animals
```

is true in every diagram.

So

✅ It follows.

---

# Let's Compare Rule 2 and Rule 3

Suppose

Statement

```text
Some Boys are Students.
```

Conclusion

```text
All Boys are Students.
```

Possible Diagram 1

```text
Boys overlap Students
```

Conclusion

❌ False

Possible Diagram 2

```text
All Boys inside Students
```

Conclusion

✅ True

One diagram says True.

One diagram says False.

What do we do?

We follow Rule 2.

Since there is **at least one valid diagram where the conclusion is false**,

the conclusion

❌ Does not follow.

---

Now another question.

Statement

```text
All Roses are Flowers.
```

Conclusion

```text
Some Roses are Flowers.
```

Possible Diagram 1

```text
Flowers

+--------------+
|   Roses      |
+--------------+
```

Conclusion

✅ True

Possible Diagram 2?

There isn't any other arrangement.

Every valid diagram will always have Roses inside Flowers.

So

Conclusion

✅ Follows.

---

# Easy Memory Trick

Think like a judge in court.

For a conclusion to pass,

it must survive **every possible situation**.

If you find even **one legal diagram** where the conclusion fails,

the conclusion is rejected.

---

# The Three Rules in One Line

### Rule 1

Don't assume extra information.

Draw the simplest (minimum-overlap) diagram first.

---

### Rule 2

**One counterexample is enough to reject a conclusion.**

```text
1 False Diagram
        ↓
Conclusion DOES NOT FOLLOW
```

---

### Rule 3

**Every possible diagram must support the conclusion.**

```text
All Possible Diagrams = True
             ↓
Conclusion FOLLOWS
```

---

## One Important Clarification

The phrase **"draw the basic diagram with minimum overlap"** is just a **starting point** for visualization. It **does not mean you solve the whole question using only that one diagram**.

You should think like this:

1. Draw the minimum-overlap diagram first.
2. Ask yourself, **"Can any other valid diagram exist?"**
3. If another valid diagram changes the conclusion, then the conclusion **does not follow**.
4. If **every** valid diagram gives the same conclusion, then it **follows**.

This is the exact reasoning used in TCS, Cognizant, Infosys, Capgemini, Wipro, and most placement exams. Once you master this idea, the rest of syllogism becomes much easier.
