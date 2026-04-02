# Problem 1: Gravitational Dependence

For a simple pendulum, the period is given by

$$
T = 2\pi \sqrt{\frac{L}{g}}
$$

where:

- \(T\) is the period,
- \(L\) is the length of the pendulum,
- \(g\) is the gravitational acceleration.

---

## 1. Period on the Moon

We are told that the pendulum has period

$$
T_E = 4\ \text{s}
$$

on Earth.

On the Moon, gravity is approximately

$$
g_M = \frac{g_E}{6}
$$

Since the period is proportional to \(1/\sqrt{g}\),

$$
T_M = T_E \sqrt{\frac{g_E}{g_M}}
$$

Substitute \(g_M = g_E/6\):

$$
T_M = 4\sqrt{\frac{g_E}{g_E/6}}
$$

$$
T_M = 4\sqrt{6}
$$

Numerically,

$$
T_M \approx 4 \times 2.449 = 9.80\ \text{s}
$$

So the pendulum period on the Moon is

$$
\boxed{T_M \approx 9.8\ \text{s}}
$$

---

## 2. Length for a period of 1 second on Earth

We want a pendulum with

$$
T = 1\ \text{s}
$$

on Earth.

From

$$
T = 2\pi \sqrt{\frac{L}{g}}
$$

solve for \(L\):

$$
\frac{T}{2\pi} = \sqrt{\frac{L}{g}}
$$

Square both sides:

$$
\frac{T^2}{4\pi^2} = \frac{L}{g}
$$

Thus,

$$
L = g\frac{T^2}{4\pi^2}
$$

Substitute \(g=9.81\ \text{m/s}^2\) and \(T=1\ \text{s}\):

$$
L = \frac{9.81}{4\pi^2}
$$

Numerically,

$$
L \approx \frac{9.81}{39.48} \approx 0.248\ \text{m}
$$

So the required length is

$$
\boxed{L \approx 0.248\ \text{m}}
$$

---

## Final answers

The period on the Moon is

$$
\boxed{T_M \approx 9.8\ \text{s}}
$$

The length needed for a 1-second pendulum on Earth is

$$
\boxed{L \approx 0.248\ \text{m}}
$$