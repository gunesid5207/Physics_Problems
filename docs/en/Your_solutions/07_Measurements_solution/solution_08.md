# 8. Mass-Spring Measurements

We simulate a mass attached to a spring and measure the time for 10 complete oscillations.

Assume the mass is exact:

$$
m = 0.50\,\mathrm{kg}
$$

The following measurements are obtained for 10 oscillations:

| Measurement | Time for 10 Oscillations (s) |
|---|---|
| 1 | 14.2 |
| 2 | 14.1 |
| 3 | 14.3 |
| 4 | 14.2 |
| 5 | 14.4 |
| 6 | 14.2 |
| 7 | 14.1 |
| 8 | 14.3 |
| 9 | 14.2 |
| 10 | 14.2 |

---

## Mean Time

Sum of measurements:

$$
142.2\,\mathrm{s}
$$

Mean time for 10 oscillations:

$$
\bar{t} = \frac{142.2}{10}
$$

$$
\bar{t} = 14.22\,\mathrm{s}
$$

---

## Mean Period

The period is the time for one oscillation:

$$
T = \frac{14.22}{10}
$$

$$
T = 1.422\,\mathrm{s}
$$

---

## Standard Deviation

Using the standard deviation formula:

$$
\sigma \approx 0.10\,\mathrm{s}
$$

For one oscillation:

$$
\sigma_T = \frac{0.10}{10}
$$

$$
\sigma_T = 0.010\,\mathrm{s}
$$

---

## Spring Constant

For a mass-spring system:

$$
T = 2\pi\sqrt{\frac{m}{k}}
$$

Rearranging:

$$
k = \frac{4\pi^2 m}{T^2}
$$

Substitute values:

$$
k =
\frac{4\pi^2(0.50)}{(1.422)^2}
$$

$$
k \approx 9.76\,\mathrm{N/m}
$$

---

## Uncertainty in k

Relative uncertainty:

$$
\frac{\Delta k}{k}
=
2\frac{\Delta T}{T}
$$

$$
\frac{\Delta k}{k}
=
2\frac{0.010}{1.422}
$$

$$
\frac{\Delta k}{k}
\approx 0.0141
$$

Absolute uncertainty:

$$
\Delta k = 0.0141 \times 9.76
$$

$$
\Delta k \approx 0.14\,\mathrm{N/m}
$$

---

## Final Answer

$$
\boxed{
T = (1.422 \pm 0.010)\,\mathrm{s}
}
$$

$$
\boxed{
k = (9.76 \pm 0.14)\,\mathrm{N/m}
}
$$