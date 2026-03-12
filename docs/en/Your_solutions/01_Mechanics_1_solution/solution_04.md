# Problem 4: Vector Calculus

The position of the object is given by

$$
\vec{r}(t) = (3t^2)\hat{i} + (5t - 8t^2)\hat{j}
$$

We find the velocity and acceleration by differentiating with respect to time.

## Velocity vector

Velocity is the derivative of position:

$$
\vec{v}(t) = \frac{d\vec{r}(t)}{dt}
$$

Differentiate each component:

$$
\frac{d}{dt}(3t^2) = 6t
$$

$$
\frac{d}{dt}(5t - 8t^2) = 5 - 16t
$$

Therefore,

$$
\vec{v}(t) = (6t)\hat{i} + (5 - 16t)\hat{j}
$$

## Acceleration vector

Acceleration is the derivative of velocity:

$$
\vec{a}(t) = \frac{d\vec{v}(t)}{dt}
$$

Differentiate each component again:

$$
\frac{d}{dt}(6t) = 6
$$

$$
\frac{d}{dt}(5 - 16t) = -16
$$

Therefore,

$$
\vec{a}(t) = 6\hat{i} - 16\hat{j}
$$

## Final answer

The velocity vector is

$$
\vec{v}(t) = (6t)\hat{i} + (5 - 16t)\hat{j}
$$

and the acceleration vector is

$$
\vec{a}(t) = 6\hat{i} - 16\hat{j}
$$