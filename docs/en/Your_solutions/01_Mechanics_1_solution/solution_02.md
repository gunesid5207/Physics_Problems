# Problem 2: Range Optimization

For projectile motion, the range is given by

$$
R(\theta)=\frac{v_0^2\sin(2\theta)}{g}
$$

where:

- \(v_0\) is the initial velocity,
- \(\theta\) is the launch angle,
- \(g\) is gravitational acceleration.

## Goal

We want to find the angle \(\theta\) that maximizes the range.

## Analysis

Since \(v_0^2/g\) is constant for a fixed launch speed, maximizing \(R(\theta)\) is equivalent to maximizing

$$
\sin(2\theta)
$$

The maximum value of the sine function is

$$
\sin(2\theta)=1
$$

This occurs when

$$
2\theta=90^\circ
$$

Therefore,

$$
\theta=45^\circ
$$

## Conclusion

The range is maximum when the launch angle is

$$
\boxed{45^\circ}
$$

The corresponding maximum range is

$$
R_{\max}=\frac{v_0^2}{g}
$$