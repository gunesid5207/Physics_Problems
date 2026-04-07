# Problem 9: Damped Oscillator

We consider the damped harmonic oscillator

$$
m\frac{d^2x}{dt^2} + b\frac{dx}{dt} + kx = 0
$$

where:
- $m$ is the mass,
- $b$ is the damping coefficient,
- $k$ is the spring constant.

## 1. General solution

Assume a solution of the form

$$
x(t) = e^{rt}
$$

Substituting into the equation gives the characteristic equation

$$
mr^2 + br + k = 0
$$

Its roots are

$$
r_{1,2} = \frac{-b \pm \sqrt{b^2 - 4mk}}{2m}
$$

The behavior depends on the discriminant

$$
\Delta = b^2 - 4mk
$$

## 2. Classification of cases

### Underdamped case

If

$$
b^2 < 4mk
$$

the roots are complex:

$$
r = -\frac{b}{2m} \pm i\omega_d
$$

where

$$
\omega_d = \sqrt{\frac{k}{m} - \frac{b^2}{4m^2}}
$$

The solution is

$$
x(t) = e^{-bt/(2m)}\left(C_1\cos(\omega_d t) + C_2\sin(\omega_d t)\right)
$$

This motion oscillates with an exponentially decreasing amplitude.

### Critically damped case

If

$$
b^2 = 4mk
$$

the system has one repeated root

$$
r = -\frac{b}{2m}
$$

and the solution is

$$
x(t) = (C_1 + C_2 t)e^{-bt/(2m)}
$$

This is the fastest return to equilibrium without oscillation.

### Overdamped case

If

$$
b^2 > 4mk
$$

the roots are real and distinct:

$$
r_{1,2} = \frac{-b \pm \sqrt{b^2 - 4mk}}{2m}
$$

and the solution is

$$
x(t) = C_1 e^{r_1 t} + C_2 e^{r_2 t}
$$

This motion does not oscillate and returns to equilibrium more slowly than the critically damped case.

## 3. Numerical solution

To study the system numerically, we rewrite the second-order equation as a system of two first-order equations:

$$
\frac{dx}{dt} = v
$$

$$
\frac{dv}{dt} = -\frac{b}{m}v - \frac{k}{m}x
$$

This system can be solved using the fourth-order Runge-Kutta (RK4) method.

## 4. Effect of parameter $b$

The parameter $b$ controls the damping strength:

- small $b$: oscillatory motion with slow decay,
- critical $b = 2\sqrt{mk}$: fastest non-oscillatory return,
- large $b$: non-oscillatory motion with slower return.

## 5. Graph of $x(t)$

The graph of $x(t)$ shows how the displacement changes with time.

- In the underdamped case, $x(t)$ oscillates and decays.
- In the critically damped case, $x(t)$ returns to zero without oscillation.
- In the overdamped case, $x(t)$ also returns without oscillation, but more slowly.

## 6. Phase portrait

The phase portrait is the graph of velocity versus displacement, that is, $(x,v)$.

- In the underdamped case, the trajectory spirals toward the origin.
- In the critically damped case, it approaches the origin without spiraling.
- In the overdamped case, it also approaches the origin without oscillation.

## Final Answer

The damped oscillator has three regimes determined by the value of $b$ relative to $2\sqrt{mk}$:

- **Underdamped:** $b < 2\sqrt{mk}$
- **Critically damped:** $b = 2\sqrt{mk}$
- **Overdamped:** $b > 2\sqrt{mk}$

The attached HTML animation solves the system numerically using RK4 and displays both the displacement $x(t)$ and the phase portrait while allowing interactive control of the damping parameter $b$.