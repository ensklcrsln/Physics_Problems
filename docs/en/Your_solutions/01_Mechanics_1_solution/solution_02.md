## 2. Range Optimization

### Given:

- Projectile motion with initial speed $v_0$  
- Gravitational acceleration $g$  
- Launch angle $\theta$  
- Range formula: $R(\theta) = \frac{v_0^2 \sin(2\theta)}{g}$  

---

### Step 1: Find derivative of range with respect to angle

To maximize range, take derivative of $R(\theta)$ with respect to $\theta$:

$$
\frac{dR}{d\theta} = \frac{v_0^2}{g} \cdot 2 \cos(2\theta) = \frac{2 v_0^2 \cos(2\theta)}{g}
$$

Set derivative equal to zero for maximum:

$$
2 \frac{v_0^2}{g} \cos(2\theta) = 0
$$

$$
\cos(2\theta) = 0
$$

---

### Step 2: Solve for optimal angle

$$
2\theta = 90^\circ \quad \Rightarrow \quad \theta = 45^\circ
$$

---

### Step 3: Confirm maximum

Second derivative test:

$$
\frac{d^2R}{d\theta^2} = -\frac{4 v_0^2 \sin(2\theta)}{g}
$$

At $\theta = 45^\circ$:

$$
\frac{d^2R}{d\theta^2} = -\frac{4 v_0^2}{g} < 0
$$

This confirms a maximum.  

---

### Explanation:

- Maximum range occurs when derivative of range with respect to angle is zero.  
- Solving $\cos(2\theta) = 0$ gives $\theta = 45^\circ$.  
- Second derivative is negative, confirming a maximum.  

---

### Formula 1: Range of projectile

$$
R(\theta) = \frac{v_0^2 \sin(2\theta)}{g}
$$

### Formula 2: Derivative for maximum

$$
\frac{dR}{d\theta} = 0 \quad \Rightarrow \quad \cos(2\theta) = 0
$$

### Formula 3: Second derivative test

$$
\frac{d^2R}{d\theta^2} < 0 \text{ confirms maximum}
$$
