# Problem 10: Force Field and Power

The motion of a particle of mass

$$
m = 0.5\ \text{kg}
$$

is described by

$$
x = 5t^2 - t,\qquad y = 2t^3,\qquad z = -3t + 2
$$

We want to find the time dependence of the velocity, momentum, acceleration, force, and power.

---

## 1. Velocity

Velocity is the derivative of position:

$$
v_x = \frac{dx}{dt} = 10t - 1
$$

$$
v_y = \frac{dy}{dt} = 6t^2
$$

$$
v_z = \frac{dz}{dt} = -3
$$

So the velocity vector is

$$
\vec{v}(t) = (10t-1,\ 6t^2,\ -3)
$$

---

## 2. Momentum

Momentum is

$$
\vec{p}(t)=m\vec{v}(t)
$$

Since \(m=0.5\ \text{kg}\),

$$
\vec{p}(t)=0.5(10t-1,\ 6t^2,\ -3)
$$

Thus,

$$
\vec{p}(t)=(5t-0.5,\ 3t^2,\ -1.5)
$$

---

## 3. Acceleration

Acceleration is the derivative of velocity:

$$
a_x = \frac{d}{dt}(10t-1)=10
$$

$$
a_y = \frac{d}{dt}(6t^2)=12t
$$

$$
a_z = \frac{d}{dt}(-3)=0
$$

So,

$$
\vec{a}(t)=(10,\ 12t,\ 0)
$$

---

## 4. Force

Using Newton's second law,

$$
\vec{F}(t)=m\vec{a}(t)
$$

So,

$$
\vec{F}(t)=0.5(10,\ 12t,\ 0)
$$

Thus,

$$
\vec{F}(t)=(5,\ 6t,\ 0)
$$

---

## 5. Power

Power is

$$
P(t)=\vec{F}(t)\cdot\vec{v}(t)
$$

Substitute the vectors:

$$
P(t)=(5,\ 6t,\ 0)\cdot(10t-1,\ 6t^2,\ -3)
$$

Compute the dot product:

$$
P(t)=5(10t-1)+6t(6t^2)+0(-3)
$$

$$
P(t)=50t-5+36t^3
$$

So,

$$
P(t)=36t^3+50t-5
$$

---

## Final answers

Velocity:

$$
\vec{v}(t)=(10t-1,\ 6t^2,\ -3)
$$

Momentum:

$$
\vec{p}(t)=(5t-0.5,\ 3t^2,\ -1.5)
$$

Acceleration:

$$
\vec{a}(t)=(10,\ 12t,\ 0)
$$

Force:

$$
\vec{F}(t)=(5,\ 6t,\ 0)
$$

Power:

$$
P(t)=36t^3+50t-5
$$