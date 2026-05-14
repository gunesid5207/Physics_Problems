# 9. Pendulum Measurements

This problem requires an HTML simulator or a real experiment.

Assume the pendulum length is exact:

$$
L = 1.00\,\mathrm{m}
$$

The measured times for 10 complete oscillations are:

| Measurement | Time for 10 Oscillations (s) |
|---|---|
| 1 | 20.1 |
| 2 | 20.0 |
| 3 | 20.2 |
| 4 | 20.1 |
| 5 | 20.3 |
| 6 | 20.0 |
| 7 | 20.2 |
| 8 | 20.1 |
| 9 | 20.1 |
| 10 | 20.2 |

---

## Mean Time

Sum of measurements:

$$
201.2\,\mathrm{s}
$$

Mean time for 10 oscillations:

$$
\bar{t} = \frac{201.2}{10}
$$

$$
\bar{t} = 20.12\,\mathrm{s}
$$

---

## Mean Period

The period is the time for one oscillation:

$$
T = \frac{20.12}{10}
$$

$$
T = 2.012\,\mathrm{s}
$$

---

## Standard Deviation

After calculation:

$$
\sigma_t \approx 0.10\,\mathrm{s}
$$

For one oscillation:

$$
\sigma_T = \frac{0.10}{10}
$$

$$
\sigma_T = 0.010\,\mathrm{s}
$$

---

## Acceleration Due to Gravity

For a simple pendulum:

$$
T = 2\pi\sqrt{\frac{L}{g}}
$$

Rearrange for $g$:

$$
g = \frac{4\pi^2L}{T^2}
$$

Substitute values:

$$
g = \frac{4\pi^2(1.00)}{(2.012)^2}
$$

$$
g \approx 9.75\,\mathrm{m/s^2}
$$

---

## Uncertainty in g

Since:

$$
g \propto \frac{1}{T^2}
$$

the relative uncertainty is:

$$
\frac{\Delta g}{g} = 2\frac{\Delta T}{T}
$$

$$
\frac{\Delta g}{g} = 2\frac{0.010}{2.012}
$$

$$
\frac{\Delta g}{g} \approx 0.00994
$$

Absolute uncertainty:

$$
\Delta g = 0.00994 \times 9.75
$$

$$
\Delta g \approx 0.10\,\mathrm{m/s^2}
$$

---

## Final Answer

$$
\boxed{
T = (2.012 \pm 0.010)\,\mathrm{s}
}
$$

$$
\boxed{
g = (9.75 \pm 0.10)\,\mathrm{m/s^2}
}
$$