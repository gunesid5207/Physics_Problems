# Problem 5: Relative Velocity

A river flows east at

$$
2 \text{ m/s}
$$

A boat can travel at

$$
5 \text{ m/s}
$$

in still water and wants to go directly north across the river.

## Step 1: Choose velocity components

Let east be the positive \(x\)-direction and north be the positive \(y\)-direction.

The river velocity is

$$
\vec{v}_r = (2,0)
$$

Let the boat head at an angle \(\theta\) west of north. Then its velocity relative to the water is

$$
\vec{v}_{b/r} = (-5\sin\theta, 5\cos\theta)
$$

The actual velocity of the boat relative to the ground is

$$
\vec{v}_{b/g} = \vec{v}_{b/r} + \vec{v}_r
$$

Since the boat wants to go directly north, the horizontal component must be zero:

$$
-5\sin\theta + 2 = 0
$$

So,

$$
5\sin\theta = 2
$$

$$
\sin\theta = \frac{2}{5}
$$

$$
\theta = \sin^{-1}\left(\frac{2}{5}\right) \approx 23.6^\circ
$$

Therefore, the boat must head

$$
23.6^\circ
$$

west of north.

## Step 2: Find the northward speed

The northward component is

$$
v_y = 5\cos\theta
$$

Using

$$
\cos\theta = \sqrt{1-\sin^2\theta} = \sqrt{1-\left(\frac{2}{5}\right)^2}
= \sqrt{\frac{21}{25}} = \frac{\sqrt{21}}{5}
$$

we get

$$
v_y = 5 \cdot \frac{\sqrt{21}}{5} = \sqrt{21} \approx 4.58 \text{ m/s}
$$

## Step 3: Find the crossing time

The river is 200 m wide, so

$$
t = \frac{200}{4.58} \approx 43.6 \text{ s}
$$

## Final answer

The boat should head

$$
\boxed{23.6^\circ \text{ west of north}}
$$

and the time to cross the river is

$$
\boxed{43.6 \text{ s}}
$$