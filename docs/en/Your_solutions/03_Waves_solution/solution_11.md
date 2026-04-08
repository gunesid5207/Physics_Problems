# Problem 11: Two-Slit Interference

We consider two coherent point sources located at positions $\mathbf{r}_1$ and $\mathbf{r}_2$. Each source emits a wave of the form

$$
u(\mathbf{r},t) = \frac{A}{|\mathbf{r}-\mathbf{r}_1|}\sin\left(k|\mathbf{r}-\mathbf{r}_1| - \omega t\right) + \frac{A}{|\mathbf{r}-\mathbf{r}_2|}\sin\left(k|\mathbf{r}-\mathbf{r}_2| - \omega t\right)
$$

where:
- $A$ is the amplitude,
- $k = \frac{2\pi}{\lambda}$ is the wave number,
- $\omega = 2\pi f$ is the angular frequency,
- $\mathbf{r}_1$ and $\mathbf{r}_2$ are the positions of the slits.

## Interference principle

The total wave is the sum of the contributions from both sources. The resulting pattern depends on the path difference:

$$
\Delta r = |\mathbf{r}-\mathbf{r}_1| - |\mathbf{r}-\mathbf{r}_2|
$$

- constructive interference occurs when $\Delta r = n\lambda$,
- destructive interference occurs when $\Delta r = \left(n+\frac{1}{2}\right)\lambda$.

## Parameters

The interference pattern depends on:

- slit distance $d = |\mathbf{r}_1 - \mathbf{r}_2|$
- wavelength $\lambda$

Changing:
- $d$ modifies the spacing between fringes,
- $\lambda$ changes the overall pattern scale.

## Numerical visualization

The wave field is visualized on a two-dimensional HTML canvas.

In the simulation:
- two fixed sources represent the slits,
- the displacement is computed at each point,
- the resulting interference pattern is displayed using color,
- the user can change $d$ and $\lambda$ in real time.

## Final Answer

The total wave is the superposition of two coherent sources:

$$
u(\mathbf{r},t) = \frac{A}{|\mathbf{r}-\mathbf{r}_1|}\sin(k|\mathbf{r}-\mathbf{r}_1| - \omega t) + \frac{A}{|\mathbf{r}-\mathbf{r}_2|}\sin(k|\mathbf{r}-\mathbf{r}_2| - \omega t)
$$

The HTML animation visualizes the resulting interference pattern and allows interactive control of the slit distance $d$ and wavelength $\lambda$.