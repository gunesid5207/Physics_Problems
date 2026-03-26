# Problem 4: Vector Calculus

The position vector is given by

$$
\vec{r}(t) = (3t^2)\hat{i} + (5t - 8t^2)\hat{j}
$$

We want to find the velocity and acceleration vectors.

---

## 1. Velocity vector

Velocity is the derivative of position:

$$
\vec{v}(t) = \frac{d\vec{r}}{dt}
$$

Differentiate each component:

$$
\frac{d}{dt}(3t^2) = 6t
$$

$$
\frac{d}{dt}(5t - 8t^2) = 5 - 16t
$$

So,

$$
\vec{v}(t) = (6t)\hat{i} + (5 - 16t)\hat{j}
$$

---

## 2. Acceleration vector

Acceleration is the derivative of velocity:

$$
\vec{a}(t) = \frac{d\vec{v}}{dt}
$$

Differentiate again:

$$
\frac{d}{dt}(6t) = 6
$$

$$
\frac{d}{dt}(5 - 16t) = -16
$$

So,

$$
\vec{a}(t) = 6\hat{i} - 16\hat{j}
$$

---

## Final answers

Velocity:

$$
\vec{v}(t) = (6t)\hat{i} + (5 - 16t)\hat{j}
$$

Acceleration:

$$
\vec{a}(t) = 6\hat{i} - 16\hat{j}
$$