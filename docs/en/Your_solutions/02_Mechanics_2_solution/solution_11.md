# Problem 11: Dynamics with a Time-Dependent Force

A particle of mass

$$
m = 3\ \text{kg}
$$

moves under the force

$$
\vec F(t) = (15t,\ 3t-12,\ -6t^2)\ \text{N}
$$

with initial conditions

$$
\vec r(0)=(5,\ 2,\ -3)\ \text{m}
$$

$$
\vec v(0)=(2,\ 0,\ 1)\ \text{m/s}
$$

We want to find the time dependence of the particle's velocity and position.

---

## 1. Acceleration

Using Newton's second law,

$$
\vec a(t)=\frac{\vec F(t)}{m}
$$

Since \(m=3\),

$$
\vec a(t)=\left(\frac{15t}{3},\ \frac{3t-12}{3},\ \frac{-6t^2}{3}\right)
$$

So,

$$
\vec a(t)=(5t,\ t-4,\ -2t^2)
$$

---

## 2. Velocity

Velocity is obtained by integrating acceleration.

### x-component

$$
a_x=5t
$$

$$
v_x(t)=\int 5t\,dt=\frac{5}{2}t^2+C_1
$$

Using \(v_x(0)=2\),

$$
C_1=2
$$

Thus,

$$
v_x(t)=\frac{5}{2}t^2+2
$$

### y-component

$$
a_y=t-4
$$

$$
v_y(t)=\int (t-4)\,dt=\frac{1}{2}t^2-4t+C_2
$$

Using \(v_y(0)=0\),

$$
C_2=0
$$

Thus,

$$
v_y(t)=\frac{1}{2}t^2-4t
$$

### z-component

$$
a_z=-2t^2
$$

$$
v_z(t)=\int -2t^2\,dt=-\frac{2}{3}t^3+C_3
$$

Using \(v_z(0)=1\),

$$
C_3=1
$$

Thus,

$$
v_z(t)=-\frac{2}{3}t^3+1
$$

Therefore, the velocity vector is

$$
\vec v(t)=\left(\frac{5}{2}t^2+2,\ \frac{1}{2}t^2-4t,\ -\frac{2}{3}t^3+1\right)
$$

---

## 3. Position

Position is obtained by integrating velocity.

### x-component

$$
x(t)=\int \left(\frac{5}{2}t^2+2\right)dt=\frac{5}{6}t^3+2t+C_4
$$

Using \(x(0)=5\),

$$
C_4=5
$$

Thus,

$$
x(t)=\frac{5}{6}t^3+2t+5
$$

### y-component

$$
y(t)=\int \left(\frac{1}{2}t^2-4t\right)dt=\frac{1}{6}t^3-2t^2+C_5
$$

Using \(y(0)=2\),

$$
C_5=2
$$

Thus,

$$
y(t)=\frac{1}{6}t^3-2t^2+2
$$

### z-component

$$
z(t)=\int \left(-\frac{2}{3}t^3+1\right)dt=-\frac{1}{6}t^4+t+C_6
$$

Using \(z(0)=-3\),

$$
C_6=-3
$$

Thus,

$$
z(t)=-\frac{1}{6}t^4+t-3
$$

Therefore, the position vector is

$$
\vec r(t)=\left(\frac{5}{6}t^3+2t+5,\ \frac{1}{6}t^3-2t^2+2,\ -\frac{1}{6}t^4+t-3\right)
$$

---

## Final answers

Acceleration:

$$
\vec a(t)=(5t,\ t-4,\ -2t^2)
$$

Velocity:

$$
\vec v(t)=\left(\frac{5}{2}t^2+2,\ \frac{1}{2}t^2-4t,\ -\frac{2}{3}t^3+1\right)
$$

Position:

$$
\vec r(t)=\left(\frac{5}{6}t^3+2t+5,\ \frac{1}{6}t^3-2t^2+2,\ -\frac{1}{6}t^4+t-3\right)
$$