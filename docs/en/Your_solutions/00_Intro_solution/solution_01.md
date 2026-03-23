# Section 0: Mathematical Foundations - Solution Manual

This repository contains the step-by-step solutions for the Mathematical Foundations problem set, covering vector algebra, calculus, and logical series.

---

## 1. Vector Algebra
**Given:** $\vec{a} = [2, 1, -3]$ and $\vec{b} = [4, -2, 1]$

### a) Magnitudes
The magnitude of a vector $\vec{v} = [x, y, z]$ is given by $\|\vec{v}\| = \sqrt{x^2 + y^2 + z^2}$.

* $\|\vec{a}\| = \sqrt{2^2 + 1^2 + (-3)^2} = \sqrt{14} \approx 3.74$
* $\|\vec{b}\| = \sqrt{4^2 + (-2)^2 + 1^2} = \sqrt{21} \approx 4.58$

### b) Dot Product
$\vec{a} \cdot \vec{b} = (a_x b_x) + (a_y b_y) + (a_z b_z)$

* $\vec{a} \cdot \vec{b} = (2 \cdot 4) + (1 \cdot -2) + (-3 \cdot 1) = 8 - 2 - 3 = 3$

### c) Cross Product
$$
\vec{a} \times \vec{b} =
\begin{vmatrix}
\mathbf{i} & \mathbf{j} & \mathbf{k} \\
2 & 1 & -3 \\
4 & -2 & 1
\end{vmatrix}
$$

* **i component:** $(1 \cdot 1) - (-3 \cdot -2) = 1 - 6 = -5$
* **j component:** $-[(2 \cdot 1) - (-3 \cdot 4)] = -[2 + 12] = -14$
* **k component:** $(2 \cdot -2) - (1 \cdot 4) = -4 - 4 = -8$

* **Result:** $\vec{a} \times \vec{b} = [-5, -14, -8]$

### d) Angle Between Vectors
Using the formula $\cos \theta = \frac{\vec{a} \cdot \vec{b}}{\|\vec{a}\|\|\vec{b}\|}$:

* $\cos \theta = \frac{3}{\sqrt{14} \cdot \sqrt{21}} = \frac{3}{\sqrt{294}} \approx 0.1749$
* $\theta \approx 79.9^\circ$

---
