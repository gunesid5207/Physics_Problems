# Problem 6: Variable Velocity

The velocity of the object is

$$
v(t)=t^2+2t-5
$$

and the initial position is

$$
x(0)=4
$$

We want to find the position and acceleration at time \(t=3\).

---

## 1. Position

Velocity is the derivative of position:

$$
v(t)=\frac{dx}{dt}
$$

So,

$$
\frac{dx}{dt}=t^2+2t-5
$$

Integrate both sides:

$$
x(t)=\int (t^2+2t-5)\,dt
$$

Compute the integral term by term:

$$
\int t^2\,dt=\frac{t^3}{3},\qquad
\int 2t\,dt=t^2,\qquad
\int (-5)\,dt=-5t
$$

Thus,

$$
x(t)=\frac{t^3}{3}+t^2-5t+C
$$

Use the initial condition \(x(0)=4\):

$$
x(0)=\frac{0^3}{3}+0^2-5\cdot0+C=C=4
$$

So,

$$
x(t)=\frac{t^3}{3}+t^2-5t+4
$$

Now evaluate at \(t=3\):

$$
x(3)=\frac{3^3}{3}+3^2-5\cdot3+4
$$

$$
x(3)=\frac{27}{3}+9-15+4=9+9-15+4=7
$$

Therefore,

$$
x(3)=7
$$

---

## 2. Acceleration

Acceleration is the derivative of velocity:

$$
a(t)=\frac{dv}{dt}
$$

Differentiate:

$$
a(t)=2t+2
$$

Now evaluate at \(t=3\):

$$
a(3)=2\cdot3+2=8
$$

Therefore,

$$
a(3)=8
$$

---

## Final answers

Position at \(t=3\):

$$
x(3)=7
$$

Acceleration at \(t=3\):

$$
a(3)=8
$$

---

## Plot the velocity and acceleration

![Velocity and Acceleration Plots](velocity_acceleration_plots.png)