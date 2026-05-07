# 5. Kirchhoff's Laws

Given:

$$
R_1 = 20\,\Omega
$$

$$
R_2 = 10\,\Omega
$$

$$
r_w = 1\,\Omega
$$

$$
\mathcal{E}_1 = 4.5\,\mathrm{V}
$$

$$
\mathcal{E}_2 = 9\,\mathrm{V}
$$

Let the top node voltage relative to the bottom node be:

$$
V = V_{\text{top}} - V_{\text{bottom}}
$$

Assume currents are positive from top to bottom.

---

## Branch currents

Left branch:

$$
I_1 = \frac{V - 4.5}{20 + 1}
$$

$$
I_1 = \frac{V - 4.5}{21}
$$

Middle branch:

$$
I_2 = \frac{V}{10}
$$

Right branch:

$$
I_3 = \frac{V + 9}{1}
$$

---

## Kirchhoff's Current Law

At the top node:

$$
I_1 + I_2 + I_3 = 0
$$

$$
\frac{V - 4.5}{21} + \frac{V}{10} + (V + 9) = 0
$$

Solving:

$$
V \approx -7.66\,\mathrm{V}
$$

---

## Currents

$$
I_1 = \frac{-7.66 - 4.5}{21}
$$

$$
I_1 \approx -0.579\,\mathrm{A}
$$

$$
I_2 = \frac{-7.66}{10}
$$

$$
I_2 \approx -0.766\,\mathrm{A}
$$

$$
I_3 = -7.66 + 9
$$

$$
I_3 \approx 1.34\,\mathrm{A}
$$

---

## Final Answer

The negative signs mean the actual current direction is opposite to the assumed top-to-bottom direction.

$$
\boxed{I_1 \approx 0.579\,\mathrm{A}\ \text{upward}}
$$

$$
\boxed{I_2 \approx 0.766\,\mathrm{A}\ \text{upward}}
$$

$$
\boxed{I_3 \approx 1.34\,\mathrm{A}\ \text{downward}}
$$