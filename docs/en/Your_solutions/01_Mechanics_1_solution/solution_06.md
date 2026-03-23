## 6. Variable Velocity

Given:

v(t) = t^2 + 2t − 5

---

## 📊 Summary Table (Render Safe)

| Quantity        | Expression (safe format)        | Result |
|----------------|----------------------------------|--------|
| Velocity       | v(t) = t^2 + 2t - 5            | Given |
| Position       | integral of v(t)                | (1/3)t^3 + t^2 - 5t + C |
| Initial value  | x(0) = 4                        | C = 4 |
| Position t=3   | substitute t = 3                | 7 |
| Acceleration   | derivative of v(t)              | 2t + 2 |
| Acceleration t=3 | substitute t = 3              | 8 |

---

## 🧠 Step-by-step explanation

### 1. Why integration?

Position is obtained by adding all small changes in velocity:

→ so we use integration

x(t) = integral of (t^2 + 2t - 5)

---

### 2. Integration result

We integrate term by term:

t^2   → (1/3)t^3  
2t    → t^2  
-5    → -5t  

So:

x(t) = (1/3)t^3 + t^2 - 5t + C

---

### 3. Initial condition

x(0) = 4

So constant:

C = 4

Final:

x(t) = (1/3)t^3 + t^2 - 5t + 4

---

### 4. Evaluate at t = 3

Step table:

- t^3 = 27 → (1/3)*27 = 9
- t^2 = 9
- -5t = -15
- +4 = +4

Total:

x(3) = 9 + 9 - 15 + 4 = 7

---

### 5. Acceleration

Acceleration is derivative of velocity:

v(t) = t^2 + 2t - 5

So:

a(t) = 2t + 2

At t = 3:

a(3) = 2*3 + 2 = 8

---

## 📈 Plot section (safe Markdown)

![Velocity vs Acceleration](velocity_acceleration_plots.png)

---

## ⚠️ Why this version will NOT break

✔ No LaTeX `$...$`  
✔ No risky `\cdot`  
✔ No `×` symbol  
✔ No YAML triggers  
✔ No markdown parsing conflicts  
✔ Only plain math text + safe powers (`t^2`)

---

## 📌 Key insight

- Velocity → quadratic growth  
- Position → cubic growth  
- Acceleration → linear growth  
