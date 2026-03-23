# Section 0: Mathematical Foundations - Solution Manual

This document provides step-by-step solutions for vector algebra, calculus, and logical series problems.

---

## 1. Vector Algebra
Given: $\vec{a} = [2, 1, -3]$ and $\vec{b} = [4, -2, 1]$

* **a) Magnitudes:** Using $\|\vec{v}\| = \sqrt{x^2 + y^2 + z^2}$
    * $\|\vec{a}\| = \sqrt{2^2 + 1^2 + (-3)^2} = \sqrt{14} \approx 3.74$
    * $\|\vec{b}\| = \sqrt{4^2 + (-2)^2 + 1^2} = \sqrt{21} \approx 4.58$
* **b) Dot Product:** $\vec{a} \cdot \vec{b} = a_x b_x + a_y b_y + a_z b_z$
    * $\vec{a} \cdot \vec{b} = (2 \cdot 4) + (1 \cdot -2) + (-3 \cdot 1) = 8 - 2 - 3 = \mathbf{3}$
* **c) Cross Product:** $$\vec{a} \times \vec{b} = \begin{vmatrix} \mathbf{i} & \mathbf{j} & \mathbf{k} \\ 2 & 1 & -3 \\ 4 & -2 & 1 \end{vmatrix} = \mathbf{i}(1-6) - \mathbf{j}(2+12) + \mathbf{k}(-4-4) = \mathbf{[-5, -14, -8]}$$
* **d) Angle Between Vectors:** $\cos \theta = \frac{\vec{a} \cdot \vec{b}}{\|\vec{a}\|\|\vec{b}\|}$
    * $\cos \theta = \frac{3}{\sqrt{14}\sqrt{21}} \implies \theta \approx \mathbf{79.9^\circ}$

---
