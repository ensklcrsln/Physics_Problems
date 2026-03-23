---

## 1. Vector Algebra
Given: $\vec{a} = [2, 1, -3]$ and $\vec{b} = [4, -2, 1]$

* **a) Magnitudes:** Using $\|\vec{v}\| = \sqrt{x^2 + y^2 + z^2}$
    * $\|\vec{a}\| = \sqrt{2^2 + 1^2 + (-3)^2} = \sqrt{14} \approx 3.74$
    * $\|\vec{b}\| = \sqrt{4^2 + (-2)^2 + 1^2} = \sqrt{21} \approx 4.58$
* **b) Dot Product:** $\vec{a} \cdot \vec{b} = a_x b_x + a_y b_y + a_z b_z$
    * $\vec{a} \cdot \vec{b} = (2 \cdot 4) + (1 \cdot -2) + (-3 \cdot 1) = 8 - 2 - 3 = \mathbf{3}$
* **c) Cross Product (Corrected):** $$\vec{a} \times \vec{b} = \begin{vmatrix} \mathbf{i} & \mathbf{j} & \mathbf{k} \\ 2 & 1 & -3 \\ 4 & -2 & 1 \end{vmatrix}$$
    * $\mathbf{i}: (1 \cdot 1) - (-3 \cdot -2) = 1 - 6 = -5$
    * $\mathbf{j}: -[(2 \cdot 1) - (-3 \cdot 4)] = -[2 + 12] = -14$
    * $\mathbf{k}: (2 \cdot -2) - (1 \cdot 4) = -4 - 4 = -8$
    * **Result:** $\vec{a} \times \vec{b} = \mathbf{[-5, -14, -8]}$
    *(Note: The previous calculation was verified, the result stays $[-5, -14, -8]$ but let's ensure the steps are crystal clear for your repo.)*

* **d) Angle Between Vectors:** $\cos \theta = \frac{3}{\sqrt{14}\sqrt{21}} \implies \theta \approx \mathbf{79.9^\circ}$

---
