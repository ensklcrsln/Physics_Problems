# 10. Kinematics

Given:

r(t) = (a cos(ωt), b sin(ωt), bt)

---

## 📊 Summary Table

| Quantity | Expression | Result |
|----------|------------|--------|
| x(t) | a cos(ωt) | Given |
| y(t) | b sin(ωt) | Given |
| z(t) | bt | Given |
| Trajectory | eliminate t | ellipse + linear z |
| Shape | 3D motion | Helix |

---

## 🧠 Step-by-step explanation

### a) Trajectory

x = a cos(ωt)  
y = b sin(ωt)

Divide:

(x/a)² + (y/b)² = 1

This is an ellipse.

Since:

z = bt → increases linearly

➡ Combined motion = helix

---

### b) Path length

Velocity:

dx/dt = -aω sin(ωt)  
dy/dt = bω cos(ωt)  
dz/dt = b  

Speed:

|v| = sqrt(a²ω² sin²(ωt) + b²ω² cos²(ωt) + b²)

Path length:

s = ∫ |v(t)| dt from 0 to t₀

(Note: no simple closed form generally)

---

### c) Plot (Python)

```python
import numpy as np
import matplotlib.pyplot as plt

t = np.linspace(0, 10, 1000)

a = 2
b = 1
w = 1

x = a * np.cos(w * t)
y = b * np.sin(w * t)
z = b * t

fig = plt.figure()
ax = fig.add_subplot(projection='3d')

ax.plot(x, y, z)
ax.set_title("Helical Motion")

plt.show()
