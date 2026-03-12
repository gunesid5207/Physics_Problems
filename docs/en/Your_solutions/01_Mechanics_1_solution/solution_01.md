# Problem 1: Projectile Motion

We consider a projectile launched from the ground with initial velocity

$$
v_0 = 100 \text{ m/s}
$$

at an angle

$$
\theta = 37^\circ
$$

above the horizontal, with no air resistance.

## Differential equations of motion

In the horizontal direction, there is no acceleration:

$$
\frac{d^2x}{dt^2} = 0
$$

In the vertical direction, the only acceleration is gravity:

$$
\frac{d^2y}{dt^2} = -g
$$

with

$$
g = 9.81 \text{ m/s}^2
$$

The initial velocity components are:

$$
v_{0x} = v_0 \cos\theta = 100\cos 37^\circ
$$

$$
v_{0y} = v_0 \sin\theta = 100\sin 37^\circ
$$

Using approximate values:

$$
\cos 37^\circ \approx 0.7986, \qquad \sin 37^\circ \approx 0.6018
$$

so

$$
v_{0x} \approx 79.86 \text{ m/s}
$$

$$
v_{0y} \approx 60.18 \text{ m/s}
$$

Thus the position equations are:

$$
x(t) = v_{0x} t
$$

$$
y(t) = v_{0y} t - \frac{1}{2}gt^2
$$

So:

$$
x(t) \approx 79.86 t
$$

$$
y(t) \approx 60.18 t - 4.905 t^2
$$

## Time of flight

The projectile returns to the ground when $y=0$.

$$
y(t) = 60.18 t - 4.905 t^2 = 0
$$

Factor out $t$:

$$
t(60.18 - 4.905 t)=0
$$

So the nonzero solution is

$$
t = \frac{60.18}{4.905} \approx 12.27 \text{ s}
$$

Therefore, the time of flight is:

$$
T \approx 12.27 \text{ s}
$$

## Maximum height

At maximum height, the vertical velocity is zero:

$$
v_y = v_{0y} - gt = 0
$$

So:

$$
t_{\text{top}} = \frac{v_{0y}}{g} = \frac{60.18}{9.81} \approx 6.13 \text{ s}
$$

Now substitute into the height formula:

$$
H = \frac{v_{0y}^2}{2g}
$$

$$
H = \frac{(60.18)^2}{2(9.81)} \approx 184.6 \text{ m}
$$

Therefore, the maximum height is:

$$
H \approx 184.6 \text{ m}
$$

## Range

The horizontal range is:

$$
R = v_{0x} \cdot T
$$

$$
R = 79.86 \times 12.27 \approx 979.9 \text{ m}
$$

Therefore, the range is:

$$
R \approx 980 \text{ m}
$$

## Final answers

- Horizontal equation of motion:

$$
\frac{d^2x}{dt^2}=0
$$

- Vertical equation of motion:

$$
\frac{d^2y}{dt^2}=-g
$$

- Time of flight:

$$
T \approx 12.27 \text{ s}
$$

- Maximum height:

$$
H \approx 184.6 \text{ m}
$$

- Range:

$$
R \approx 980 \text{ m}
$$