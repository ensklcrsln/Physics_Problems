## 6. Variable Velocity

Given:

v(t) = t^2 + 2t − 5

---

## 📊 Summary Table

| Quantity        | Expression                          | Result |
|----------------|--------------------------------------|--------|
| Velocity       | v(t) = t^2 + 2t − 5                | Given |
| Position       | ∫ v(t) dt                          | (1/3)t^3 + t^2 − 5t + C |
| Initial value  | x(0) = 4                            | C = 4 |
| Position at t=3| x(3)                               | 7 |
| Acceleration   | dv/dt                              | 2t + 2 |
| Acceleration t=3 | a(3)                             | 8 |

---

## 🧠 Step-by-step explanation

### 1. Position from velocity

We integrate because:

👉 position = total accumulated motion

x(t) = ∫ (t^2 + 2t − 5) dt

x(t) = (1/3)t^3 + t^2 − 5t + C

---

### 2. Initial condition

x(0) = 4 → C = 4

So:

x(t) = (1/3)t^3 + t^2 − 5t + 4

---

### 3. Evaluate at t = 3

| Step | Calculation |
|------|-------------|
| (1/3)t^3 | (1/3)·27 = 9 |
| t^2 | 9 |
| −5t | −15 |
| Constant | +4 |
| **Total** | **7** |

---

### 4. Acceleration

a(t) = dv/dt = 2t + 2

At t = 3:

a(3) = 8

---

## 📈 Plot (VS Code compatible)

![Velocity & Acceleration Plot](velocity_acceleration_plots.png)

---

## 📌 Interpretation

- Position → cubic curve (grows faster over time)
- Velocity → quadratic curve
- Acceleration → linear function
