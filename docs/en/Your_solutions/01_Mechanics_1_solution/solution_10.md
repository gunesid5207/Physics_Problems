# Problem 10: Kinematics

The position vector is

$$
\vec{r}(t) = (a\cos(\omega t),\, b\sin(\omega t),\, bt)
$$

where \(a, b, \omega\) are positive constants.

---

## a) Equation of the trajectory

We have

$$
x(t)=a\cos(\omega t),\qquad y(t)=b\sin(\omega t),\qquad z(t)=bt
$$

From the first two:

$$
\cos(\omega t)=\frac{x}{a},\qquad \sin(\omega t)=\frac{y}{b}
$$

Using

$$
\cos^2(\omega t)+\sin^2(\omega t)=1
$$

we obtain

$$
\frac{x^2}{a^2}+\frac{y^2}{b^2}=1
$$

Thus, the motion in the \(xy\)-plane is an ellipse.

Since

$$
z=bt \Rightarrow t=\frac{z}{b}
$$

we can write

$$
x=a\cos\left(\omega \frac{z}{b}\right),\qquad
y=b\sin\left(\omega \frac{z}{b}\right)
$$

Therefore, the trajectory is an **elliptical helix**.

---

## b) Path length

Velocity is

$$
\vec{v}(t)=\frac{d\vec{r}}{dt}
$$

Differentiate:

$$
\vec{v}(t)=(-a\omega \sin(\omega t),\, b\omega \cos(\omega t),\, b)
$$

The speed is

$$
|\vec{v}(t)|=\sqrt{a^2\omega^2\sin^2(\omega t)+b^2\omega^2\cos^2(\omega t)+b^2}
$$

The path length from \(0\) to \(t_0\) is

$$
L=\int_0^{t_0} |\vec{v}(t)|\,dt
$$

---

## c) Special cases

### Case 1: \(a=b\)

$$
x^2+y^2=a^2
$$

The motion becomes a **circular helix**.

### Case 2: \(\omega=0\)

$$
x=a,\qquad y=0,\qquad z=bt
$$

This is straight-line motion along the \(z\)-axis.

### Case 3: \(b=0\)

$$
y=0,\qquad z=0
$$

$$
x=a\cos(\omega t)
$$

This is one-dimensional motion along the \(x\)-axis.

---

## Final answer

The trajectory satisfies

$$
\frac{x^2}{a^2}+\frac{y^2}{b^2}=1
$$

with

$$
z=bt
$$

so it is an **elliptical helix**.

---

## Trajectory Plot

![Trajectory Plot](trajectory_10.png)