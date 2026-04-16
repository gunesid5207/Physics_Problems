## 6. Field at a Point from a System of Charges

**Given**

- Charge $+q$ at $(-a,0)$
- Charge $+2q$ at $(a,0)$

We calculate the electric field at a general point $(x,y)$.

**Analysis**

For a point charge,

$$
\vec E = kq \frac{\vec r}{r^3}
$$

where $\vec r$ is the vector from the charge to the field point.

---

### 1. General field $\vec E(x,y)$

For the charge at $(-a,0)$,

$$
\vec r_1 = (x+a)\hat{i} + y\hat{j}
$$

$$
r_1 = \sqrt{(x+a)^2 + y^2}
$$

So,

$$
\vec E_1 = kq \frac{(x+a)\hat{i} + y\hat{j}}{\left[(x+a)^2+y^2\right]^{3/2}}
$$

For the charge at $(a,0)$,

$$
\vec r_2 = (x-a)\hat{i} + y\hat{j}
$$

$$
r_2 = \sqrt{(x-a)^2 + y^2}
$$

So,

$$
\vec E_2 = k(2q) \frac{(x-a)\hat{i} + y\hat{j}}{\left[(x-a)^2+y^2\right]^{3/2}}
$$

Therefore,

$$
\boxed{
\vec E(x,y)
=
kq \frac{(x+a)\hat{i} + y\hat{j}}{\left[(x+a)^2+y^2\right]^{3/2}}
+
2kq \frac{(x-a)\hat{i} + y\hat{j}}{\left[(x-a)^2+y^2\right]^{3/2}}
}
$$

So the components are

$$
\boxed{
E_x =
kq\frac{x+a}{\left[(x+a)^2+y^2\right]^{3/2}}
+
2kq\frac{x-a}{\left[(x-a)^2+y^2\right]^{3/2}}
}
$$

$$
\boxed{
E_y =
kq\frac{y}{\left[(x+a)^2+y^2\right]^{3/2}}
+
2kq\frac{y}{\left[(x-a)^2+y^2\right]^{3/2}}
}
$$

---

### 2. Field on the line $(0,y)$

Set $x=0$:

$$
E_x(0,y)
=
kq\frac{a}{(a^2+y^2)^{3/2}}
+
2kq\frac{-a}{(a^2+y^2)^{3/2}}
=
-\frac{kqa}{(a^2+y^2)^{3/2}}
$$

$$
E_y(0,y)
=
kq\frac{y}{(a^2+y^2)^{3/2}}
+
2kq\frac{y}{(a^2+y^2)^{3/2}}
=
\frac{3kqy}{(a^2+y^2)^{3/2}}
$$

Thus,

$$
\boxed{
\vec E(0,y)=
-\frac{kqa}{(a^2+y^2)^{3/2}}\hat{i}
+
\frac{3kqy}{(a^2+y^2)^{3/2}}\hat{j}
}
$$

---

### 3. Field on the line $(x,0)$

Set $y=0$:

$$
\boxed{
\vec E(x,0)=
\left[
kq\frac{x+a}{|x+a|^3}
+
2kq\frac{x-a}{|x-a|^3}
\right]\hat{i}
}
$$

and

$$
\boxed{E_y(x,0)=0}
$$

---

### 4. Conditions for $E_x=0$, $E_y=0$, and $\vec E=0$

From the expression for $E_y$,

$$
E_y =
kq\,y\left[
\frac{1}{\left((x+a)^2+y^2\right)^{3/2}}
+
\frac{2}{\left((x-a)^2+y^2\right)^{3/2}}
\right]
$$

The bracket is always positive, so

$$
\boxed{E_y=0 \iff y=0}
$$

For $E_x=0$,

$$
\boxed{
\frac{x+a}{\left[(x+a)^2+y^2\right]^{3/2}}
+
2\frac{x-a}{\left[(x-a)^2+y^2\right]^{3/2}}
=0
}
$$

For the total field to be zero, both components must vanish. Since $E_y=0$ requires $y=0$, the zero field point must lie on the $x$-axis.

For $-a < x < a$,

$$
kq\frac{1}{(x+a)^2}
=
2kq\frac{1}{(a-x)^2}
$$

$$
\frac{1}{(x+a)^2}=\frac{2}{(a-x)^2}
$$

Taking square roots,

$$
\frac{1}{x+a}=\frac{\sqrt{2}}{a-x}
$$

$$
a-x=\sqrt{2}(x+a)
$$

$$
a-x=\sqrt{2}x+\sqrt{2}a
$$

$$
a(1-\sqrt{2})=x(1+\sqrt{2})
$$

$$
x=a\frac{1-\sqrt{2}}{1+\sqrt{2}}
$$

Rationalizing,

$$
x=a(\sqrt{2}-1)^2=a(3-2\sqrt{2})
$$

So,

$$
\boxed{
\vec E=0 \text{ at } (\,a(3-2\sqrt{2}),\,0\,)
}
$$

This point lies between the charges and is closer to the smaller charge $+q$.

---

### 5. Numerical value for $a=0.2\,\mathrm{m}$, $y=0.3\,\mathrm{m}$, $q=2\,\mu\mathrm{C}$

Use the result for $(0,y)$:

$$
\vec E(0,y)=
-\frac{kqa}{(a^2+y^2)^{3/2}}\hat{i}
+
\frac{3kqy}{(a^2+y^2)^{3/2}}\hat{j}
$$

Given:

$$
a=0.2\,\mathrm{m},\quad y=0.3\,\mathrm{m},\quad q=2\times 10^{-6}\,\mathrm{C}
$$

$$
a^2+y^2=0.04+0.09=0.13
$$

$$
(0.13)^{3/2}\approx 0.0469
$$

Using $k=8.99\times10^9\,\mathrm{N\,m^2/C^2}$,

$$
E_x \approx -7.67\times10^4\,\mathrm{N/C}
$$

$$
E_y \approx 3.45\times10^5\,\mathrm{N/C}
$$

Therefore,

$$
\boxed{
\vec E(0,0.3)\approx
(-7.67\times10^4\,\hat{i}+3.45\times10^5\,\hat{j})\,\mathrm{N/C}
}
$$

Its magnitude is

$$
|\vec E|=\sqrt{E_x^2+E_y^2}\approx 3.53\times10^5\,\mathrm{N/C}
$$

So,

$$
\boxed{
|\vec E|\approx 3.53\times10^5\,\mathrm{N/C}
}
$$

---

### 6. Limit $y \gg a$

For large $y$, use

$$
(a^2+y^2)^{3/2}\approx y^3
$$

Then

$$
E_x(0,y)\approx -\frac{kqa}{y^3}
$$

$$
E_y(0,y)\approx \frac{3kq}{y^2}
$$

So,

$$
\boxed{
\vec E(0,y)\approx -\frac{kqa}{y^3}\hat{i}+\frac{3kq}{y^2}\hat{j}
}
$$

The dominant term is the $y$-component, therefore at large distance

$$
\boxed{
\vec E(0,y)\approx \frac{3kq}{y^2}\hat{j}
}
$$

**Check**

At large distance, the system behaves like a total charge $q+2q=3q$, so the leading term must scale as

$$
\frac{k(3q)}{y^2}
$$

which matches the result.