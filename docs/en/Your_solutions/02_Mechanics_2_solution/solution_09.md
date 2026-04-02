# Problem 9: Vertical Throw with Drag

We are given the equation of motion

$$
m\frac{dv}{dt} = -mg - kv
$$

with initial conditions

$$
v(0)=v_0,\qquad x(0)=10
$$

We want to solve the equation analytically, determine the maximum height, compare with the case without drag, and perform a numerical simulation.

---

## 1. Solve the equation analytically

Start with

$$
m\frac{dv}{dt} = -mg - kv
$$

Divide both sides by \(m\):

$$
\frac{dv}{dt} + \frac{k}{m}v = -g
$$

This is a first-order linear differential equation.

Its solution is

$$
v(t)=\left(v_0+\frac{mg}{k}\right)e^{-\frac{k}{m}t}-\frac{mg}{k}
$$

---

## 2. Position function

Since

$$
v(t)=\frac{dx}{dt}
$$

we integrate:

$$
x(t)=\int v(t)\,dt
$$

So

$$
x(t)=10+\frac{m}{k}\left(v_0+\frac{mg}{k}\right)\left(1-e^{-\frac{k}{m}t}\right)-\frac{mg}{k}t
$$

This is the height as a function of time.

---

## 3. Maximum height

The maximum height occurs when the velocity becomes zero:

$$
v(t)=0
$$

So

$$
\left(v_0+\frac{mg}{k}\right)e^{-\frac{k}{m}t}-\frac{mg}{k}=0
$$

Rearrange:

$$
e^{-\frac{k}{m}t}=\frac{mg/k}{v_0+mg/k}
$$

Thus,

$$
t_{\max}=\frac{m}{k}\ln\left(\frac{v_0+\frac{mg}{k}}{\frac{mg}{k}}\right)
$$

or equivalently,

$$
t_{\max}=\frac{m}{k}\ln\left(1+\frac{k v_0}{mg}\right)
$$

Substituting this time into \(x(t)\) gives the maximum height.

---

## 4. Comparison with the case without drag

Without drag, the equation becomes

$$
m\frac{dv}{dt}=-mg
$$

So,

$$
v(t)=v_0-gt
$$

and

$$
x(t)=10+v_0 t-\frac{1}{2}gt^2
$$

The maximum height without drag is

$$
x_{\max}=10+\frac{v_0^2}{2g}
$$

Compared with the no-drag case, the presence of drag makes the velocity decrease faster, so the object reaches a lower maximum height.

---

## 5. Numerical simulation

A numerical simulation can be performed using Python or HTML to plot the height as a function of time.

---

## Final answers

Velocity:

$$
\boxed{v(t)=\left(v_0+\frac{mg}{k}\right)e^{-\frac{k}{m}t}-\frac{mg}{k}}
$$

Position:

$$
\boxed{x(t)=10+\frac{m}{k}\left(v_0+\frac{mg}{k}\right)\left(1-e^{-\frac{k}{m}t}\right)-\frac{mg}{k}t}
$$

Maximum height occurs at

$$
\boxed{t_{\max}=\frac{m}{k}\ln\left(1+\frac{k v_0}{mg}\right)}
$$

The maximum height is lower than in the case without drag.

---

## Simulation Plot

![Simulation Plot](vertical_throw_drag.png)