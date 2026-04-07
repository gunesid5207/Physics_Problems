# Problem 10: Animation: Wave Sources

We consider wave sources located at positions $\mathbf{r}_0$ on a two-dimensional plane. Each source generates a wave of the form

$$
u(\mathbf{r},t) = \frac{A}{|\mathbf{r}-\mathbf{r}_0|^\alpha}\sin\left(k|\mathbf{r}-\mathbf{r}_0| - \omega t\right)
$$

where:

- $A$ is the amplitude,
- $\alpha \in [0,2]$ controls the decay with distance,
- $k = \frac{2\pi}{\lambda}$ is the wave number,
- $\omega = 2\pi f$ is the angular frequency,
- $\mathbf{r}$ is the observation point,
- $\mathbf{r}_0$ is the source position.

## Superposition principle

If there are many sources, the total wave is the sum of the contributions from all of them:

$$
u_{\text{total}}(\mathbf{r},t) = \sum_i \frac{A}{|\mathbf{r}-\mathbf{r}_{0,i}|^\alpha}\sin\left(k|\mathbf{r}-\mathbf{r}_{0,i}| - \omega t\right)
$$

## Numerical visualization

The HTML animation represents the wave field on a 2D canvas.

- The user can click on the canvas to add wave sources.
- Each source contributes to the total displacement.
- The parameter $\alpha$ can be adjusted in the interval $[0,2]$.
- The animation updates the superposed wave field in real time.

## Final Answer

The attached HTML file implements an interactive simulation of multiple wave sources. It visualizes the superposition of waves emitted by user-defined point sources and allows the distance-decay parameter $\alpha$ to be changed interactively.