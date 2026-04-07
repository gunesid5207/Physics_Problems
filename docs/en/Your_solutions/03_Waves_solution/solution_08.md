# Problem 8: Waves

A function describes a traveling wave if it can be written in the form

$$
y(x,t) = f(x-vt)
\quad \text{or} \quad
y(x,t) = g(x+vt)
$$

Such functions satisfy the wave equation

$$
\frac{\partial^2 y}{\partial x^2} = \frac{1}{v^2}\frac{\partial^2 y}{\partial t^2}
$$

We now examine each case.

## a) $y(x,t) = A\cos(kx^2 - \omega t)$

This function depends on $x^2$ and $t$ in the combination $kx^2 - \omega t$, not in the form $x \pm vt$.

Therefore, it is **not** a traveling wave.

## b) $y(x,t) = A(x-vt)^2$

This function is explicitly of the form

$$
y(x,t) = f(x-vt)
$$

with

$$
f(u) = Au^2
$$

Therefore, it represents a traveling wave moving in the positive $x$-direction with speed $v$.

## c) $y(x,t) = A\log(x+vt)$

This function is explicitly of the form

$$
y(x,t) = g(x+vt)
$$

Therefore, it represents a traveling wave moving in the negative $x$-direction with speed $v$.

## Final Answer

- **a)** Not a traveling wave
- **b)** Traveling wave
- **c)** Traveling wave