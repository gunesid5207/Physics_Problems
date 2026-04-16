## 9. Vector Lorentz Force

**Given**

- Proton charge:

$$
q = 1.60 \times 10^{-19}\,\mathrm{C}
$$

- Velocity:

$$
\vec v = (2\hat{i} - 4\hat{j} + \hat{k})\,\mathrm{m/s}
$$

- Magnetic field:

$$
\vec B = (\hat{i} + 2\hat{j} - \hat{k})\,\mathrm{T}
$$

**Analysis**

The magnetic force is

$$
\vec F = q\,\vec v \times \vec B
$$

First compute the cross product:

$$
\vec v \times \vec B =
\begin{vmatrix}
\hat{i} & \hat{j} & \hat{k} \\
2 & -4 & 1 \\
1 & 2 & -1
\end{vmatrix}
$$

Expand the determinant:

$$
\vec v \times \vec B
=
\hat{i}[(-4)(-1) - (1)(2)]
-\hat{j}[(2)(-1) - (1)(1)]
+\hat{k}[(2)(2) - (-4)(1)]
$$

$$
\vec v \times \vec B
=
\hat{i}(4-2)
-\hat{j}(-2-1)
+\hat{k}(4+4)
$$

$$
\vec v \times \vec B
=
2\hat{i} + 3\hat{j} + 8\hat{k}
$$

So the force vector is

$$
\vec F = q(2\hat{i} + 3\hat{j} + 8\hat{k})
$$

Its magnitude is

$$
|\vec F| = q\sqrt{2^2 + 3^2 + 8^2}
= q\sqrt{77}
$$

Substitute $q = 1.60 \times 10^{-19}\,\mathrm{C}$:

$$
|\vec F| = (1.60 \times 10^{-19})\sqrt{77}
$$

$$
|\vec F| \approx 1.40 \times 10^{-18}\,\mathrm{N}
$$

**Result**

$$
\boxed{\vec v \times \vec B = 2\hat{i} + 3\hat{j} + 8\hat{k}}
$$

$$
\boxed{|\vec F| \approx 1.40 \times 10^{-18}\,\mathrm{N}}
$$

**Check**

The result must come from a cross product, not a dot product.  
If you get a scalar before multiplying by $q$, it is wrong.