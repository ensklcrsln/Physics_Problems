## 6. Variable Velocity

Given velocity function:

v(t) = t^2 + 2t − 5

---

## 📌 Key idea

- Velocity gives position change over time
- To get position, we integrate velocity
- To get acceleration, we differentiate velocity

---

## 📊 Step-by-step summary

| Quantity        | Operation            | Formula Result                          |
|----------------|---------------------|------------------------------------------|
| Velocity v(t)   | Given               | t^2 + 2t − 5                            |
| Position x(t)   | Integration         | (1/3)t^3 + t^2 − 5t + C                |
| Initial value   | x(0) = 4            | C = 4                                   |
| Final position  | Substitute t = 3    | x(3) = 7                                |
| Acceleration a(t)| Derivative of v(t) | 2t + 2                                  |
| Acceleration at t=3 | Substitute       | a(3) = 8                                |

---

## 🧠 Step-by-step explanation

### 1. Position function

We integrate velocity because:

👉 position is the accumulation of velocity over time

x(t) = ∫(t^2 + 2t − 5) dt

x(t) = (1/3)t^3 + t^2 − 5t + C

---

### 2. Find constant C

We use initial condition:

x(0) = 4

So:

C = 4

---

### 3. Final position at t = 3

x(3) = (1/3)(27) + 9 − 15 + 4  
x(3) = 9 + 9 − 15 + 4  
x(3) = 7

---

### 4. Acceleration

We differentiate velocity:

a(t) = dv/dt = 2t + 2

At t = 3:

a(3) = 8
