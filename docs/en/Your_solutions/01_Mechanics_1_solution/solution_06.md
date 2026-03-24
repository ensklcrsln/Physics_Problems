# 6. Variable Velocity

## 📊 Summary Table

| Quantity        | Expression                          | Result |
|----------------|--------------------------------------|--------|
| Velocity       | v(t) = t<sup>2</sup> + 2t - 5        | Given |
| Position       | ∫ v(t) dt                            | (1/3)t<sup>3</sup> + t<sup>2</sup> - 5t + C |
| Initial value  | x(0) = 4                             | C = 4 |
| Position t=3   | x(3)                                 | 7 |
| Acceleration   | a(t) = dv/dt                         | 2t + 2 |
| Acceleration t=3 | a(3)                               | 8 |

---

## 🧠 Step-by-step explanation

### 1. Why integration?

Position is obtained by accumulating velocity over time.

So we compute:

x(t) = ∫ (t<sup>2</sup> + 2t - 5) dt

---

### 2. Integration result

Integrate term by term:

- t<sup>2</sup> → (1/3)t<sup>3</sup>  
- 2t → t<sup>2</sup>  
- -5 → -5t  

So:

x(t) = (1/3)t<sup>3</sup> + t<sup>2</sup> - 5t + C

---

### 3. Initial condition

Given:

x(0) = 4

So:

C = 4

Final position function:

x(t) = (1/3)t<sup>3</sup> + t<sup>2</sup> - 5t + 4

---

### 4. Evaluate at t = 3

Step-by-step:

- t<sup>3</sup> = 27 → (1/3) × 27 = 9  
- t<sup>2</sup> = 9  
- -5t = -15  
- +4 = 4  

Total:

x(3) = 9 + 9 - 15 + 4 = 7

---

### 5. Acceleration

Acceleration is the derivative of velocity.

Given:

v(t) = t<sup>2</sup> + 2t - 5

So:

a(t) = 2t + 2

At t = 3:

a(3) = 2 × 3 + 2 = 8

---

## 📈 Plot (optional)

If you include an image in your repo:
![Velocity vs Acceleration](velocity_acceleration_plots.png)

---

## 📌 Key insight

- Velocity → quadratic growth  
- Position → cubic growth  
- Acceleration → linear growth
