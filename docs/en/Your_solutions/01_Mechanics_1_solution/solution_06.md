## 6. Variable Velocity

### Given:

- Velocity: $v(t) = t^2 + 2t - 5$  
- Initial position: $x(0) = 4$  
- Find position and acceleration at $t = 3$  

---

### Step 1: Acceleration

$$
a(t) = \frac{dv}{dt} = 2t + 2
$$

At $t = 3$:

$$
a(3) = 8 \text{ m/s}^2
$$

---

### Step 2: Position function

Integrate velocity:

$$
x(t) = \int v(t) dt = \frac{t^3}{3} + t^2 - 5t + C
$$

Use initial condition $x(0) = 4$ → $C = 4$

$$
x(t) = \frac{t^3}{3} + t^2 - 5t + 4
$$

---

### Step 3: Position at $t = 3$

$$
x(3) = 7 \text{ m}
$$

---

### Explanation:

- Acceleration is derivative of velocity.  
- Position is integral of velocity plus initial condition.  
- Plug in t = 3 for numerical results.  

---

### Formula 1: Acceleration from velocity

$$
a(t) = \frac{dv}{dt}
$$

### Formula 2: Position from velocity

$$
x(t) = \int v(t) dt + x_0
$$
