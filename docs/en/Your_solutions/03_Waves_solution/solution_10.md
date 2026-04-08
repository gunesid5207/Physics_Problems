# Problem 10: Animation: Wave Sources

We consider point sources located at positions $\mathbf{r}_{0}$ on a two-dimensional plane. Each source generates a wave of the form

$$
u(\mathbf{r},t) = \frac{A}{|\mathbf{r}-\mathbf{r}_0|^\alpha}\sin\left(k|\mathbf{r}-\mathbf{r}_0| - \omega t\right)
$$

where:
- $A$ is the amplitude,
- $\alpha \in [0,2]$ controls the decay with distance,
- $k = \frac{2\pi}{\lambda}$ is the wave number,
- $\omega = 2\pi f$ is the angular frequency,
- $\mathbf{r}$ is the observation point,
- $\mathbf{r}_0$ is the position of the source.

## 1. Superposition principle

If there are several sources, the total wave is the sum of all individual contributions:

$$
u_{\text{total}}(\mathbf{r},t) = \sum_i \frac{A}{|\mathbf{r}-\mathbf{r}_{0,i}|^\alpha}\sin\left(k|\mathbf{r}-\mathbf{r}_{0,i}| - \omega t\right)
$$

Thus, the observed displacement at each point is determined by the superposition of the waves emitted by all sources.

## 2. Numerical visualization

To visualize the wave field, the two-dimensional plane is represented by an HTML canvas.

At each animation frame:
- the position of every source is known,
- the distance from each pixel to each source is computed,
- the wave contributions are summed,
- the result is mapped to color.

The user can:
- click on the canvas to add new wave sources,
- change the decay parameter $\alpha$ in the interval $[0,2]$,
- observe the time-dependent superposition pattern in real time.

## 3. Effect of the parameter $\alpha$

The parameter $\alpha$ controls how fast the amplitude decreases with distance:

- for $\alpha = 0$, the amplitude does not decay with distance,
- for intermediate values of $\alpha$, the wave gradually weakens,
- for larger $\alpha$, the wave is strongly localized near the source.

Therefore, increasing $\alpha$ makes distant parts of the field less affected by each source.

## Final Answer

The total displacement is obtained by summing the contributions from all point sources:

$$
u_{\text{total}}(\mathbf{r},t) = \sum_i \frac{A}{|\mathbf{r}-\mathbf{r}_{0,i}|^\alpha}\sin\left(k|\mathbf{r}-\mathbf{r}_{0,i}| - \omega t\right)
$$

The accompanying HTML animation visualizes this superposition on a two-dimensional canvas. The user can place sources interactively and adjust the parameter $\alpha$ to study how the wave field changes.