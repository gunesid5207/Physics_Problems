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

The behavior of the system depends on the discriminant

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

To solve the equation numerically, we rewrite the second-order equation as a system of two first-order equations:

$$
\frac{dx}{dt} = v
$$

$$
\frac{dv}{dt} = -\frac{b}{m}v - \frac{k}{m}x
$$

We solve this system using the fourth-order Runge-Kutta (RK4) method.

### Numerical setup

In the animation, we use:
- $x(0) = 1$
- $v(0) = 0$
- time step $\Delta t = 0.01$
- time interval $t \in [0, 10]$

These values are sufficient to clearly compare the underdamped, critically damped, and overdamped regimes.

## 4. Effect of parameter $b$

The parameter $b$ determines the strength of damping:

- for small $b$, the motion is oscillatory and slowly decays,
- for $b^2 = 4mk$, the system is critically damped and returns to equilibrium as fast as possible without oscillation,
- for large $b$, the system is overdamped and returns to equilibrium without oscillation, but more slowly.

Thus, increasing $b$ suppresses oscillations and changes the shape of both the displacement graph and the phase portrait.

## 5. Graph of $x(t)$

The graph of $x(t)$ shows the displacement as a function of time.

- In the underdamped case, the graph oscillates with decreasing amplitude.
- In the critically damped case, the displacement returns to zero without oscillation and does so in the shortest possible time.
- In the overdamped case, the displacement also returns to zero without oscillation, but more slowly.

## 6. Phase portrait

The phase portrait is the graph in the $(x,v)$ plane, where $v = dx/dt$.

- In the underdamped case, the trajectory spirals toward the origin.
- In the critically damped case, the trajectory approaches the origin without spiraling.
- In the overdamped case, the trajectory also approaches the origin without oscillation.

The origin $(0,0)$ represents the equilibrium state.

## Final Answer

The damped harmonic oscillator has three regimes determined by the sign of

$$
b^2 - 4mk
$$

- **Underdamped:** $b^2 < 4mk$
- **Critically damped:** $b^2 = 4mk$
- **Overdamped:** $b^2 > 4mk$

The equation can be rewritten as a first-order system and solved numerically using RK4. The interactive HTML animation should allow the user to change the damping coefficient $b$ and observe both the displacement graph $x(t)$ and the phase portrait $(x,v)$ for all three regimes.