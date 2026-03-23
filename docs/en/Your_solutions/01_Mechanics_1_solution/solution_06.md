## 6. Variable Velocity

Given velocity function:

v(t) = t^2 + 2t − 5

---

## 📌 Step 1: Position (Integration)

We integrate velocity because position is accumulated motion over time.

∫ v(t) dt = ∫ (t^2 + 2t − 5) dt

Now integrate term by term:

- ∫ t^2 dt = (1/3)t^3
- ∫ 2t dt = t^2
- ∫ −5 dt = −5t

So:

x(t) = (1/3)t^3 + t^2 − 5t + C

---

## 📌 Step 2: Initial condition

We are given:

x(0) = 4

Substitute:

x(0) = 0 + 0 − 0 + C = 4

So:

C = 4

Final position function:

x(t) = (1/3)t^3 + t^2 − 5t + 4

---

## 📌 Step 3: Position at t = 3

Compute step by step:

- (1/3) * 3^3 = (1/3) * 27 = 9
- 3^2 = 9
- −5 * 3 = −15

So:

x(3) = 9 + 9 − 15 + 4

x(3) = 7

---

## 📌 Step 4: Acceleration

Acceleration is derivative of velocity:

v(t) = t^2 + 2t − 5

a(t) = 2t + 2

At t = 3:

a(3) = 2(3) + 2 = 8

---

# 📊 GRAPHICAL INTERPRETATION

## 1. ASCII sketch (position growth idea)

Position x(t) behaves like a cubic curve:

t →
|
|        *
|      *
|    *
|  *
| *
|____________________

(Non-linear growth due to t^3 term)

---

## 2. Python graph (recommended for real plot)

import numpy as np
import matplotlib.pyplot as plt

t = np.linspace(0, 5, 100)

x = (1/3)*t**3 + t**2 - 5*t + 4
v = t**2 + 2*t - 5
a = 2*t + 2

plt.plot(t, x, label="Position x(t)")
plt.plot(t, v, label="Velocity v(t)")
plt.plot(t, a, label="Acceleration a(t)")

plt.title("Motion Analysis")
plt.legend()
plt.grid()
plt.show()

---

## 📌 Key insight

- Position grows non-linearly (cubic)
- Velocity is quadratic
- Acceleration is linear
