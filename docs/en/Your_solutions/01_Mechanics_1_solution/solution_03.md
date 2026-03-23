## 3. Path Intersection (Alice & Bob)

---

## 🎯 Problem idea

Two people (Alice and Bob) move along paths.

We want to determine:

- Do they meet at the same point?
- If yes → when and where?
- If not → why not?

---

## 📌 Step 1: Position functions

Alice position:

A(t) = (2 + t, 8 − 3t)

Bob position:

B(t) = (2t − 1, 2t + 2)

---

## 🧠 Why do we compare coordinates?

Two objects are at the same position only if:

- x-coordinates are equal
- y-coordinates are equal

So we solve both equations at the same time.

---

## 📌 Step 2: Set equations equal

We compare x-components:

2 + t = 2t − 1

Now compare y-components:

8 − 3t = 2t + 2

---

## 📌 Step 3: Solve x-equation

2 + t = 2t − 1

Move terms:

2 + 1 = 2t − t

3 = t

So:

t = 3

---

## 📌 Step 4: Check y-equation

Substitute t = 3:

Left side:
8 − 3(3) = 8 − 9 = −1

Right side:
2(3) + 2 = 6 + 2 = 8

---

## ❌ Step 5: Compare results

We get:

- Left = −1
- Right = 8

They are NOT equal.

---

## 🎯 Final conclusion

The paths do NOT intersect.

So:

- No collision occurs
- They never meet at the same point
