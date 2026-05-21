# 9. Size and Distance of the Sun

Given:

$$
\theta = 89.85^\circ
$$

$$
\alpha = 0.53^\circ
$$

$$
d_{EM} = 3.84 \times 10^5\,\mathrm{km}
$$

At half-Moon, the triangle Earth-Moon-Sun is a right triangle with the right angle at the Moon.

From Earth:

$$
\cos\theta = \frac{d_{EM}}{d_{ES}}
$$

So:

$$
d_{ES} = \frac{d_{EM}}{\cos\theta}
$$

---

## 1. Earth-Sun Distance

Substitute:

$$
d_{ES}
=
\frac{3.84 \times 10^5}{\cos(89.85^\circ)}
$$

$$
d_{ES} \approx 1.47 \times 10^8\,\mathrm{km}
$$

---

## 2. True Diameter of the Sun

Convert angular diameter to radians:

$$
\alpha =
0.53^\circ \times \frac{\pi}{180}
$$

$$
\alpha \approx 0.00925\,\mathrm{rad}
$$

Using the small-angle approximation:

$$
\alpha \approx \frac{D_S}{d_{ES}}
$$

So:

$$
D_S \approx \alpha d_{ES}
$$

Substitute:

$$
D_S \approx (0.00925)(1.47 \times 10^8)
$$

$$
D_S \approx 1.36 \times 10^6\,\mathrm{km}
$$

---

## 3. Ratio of True Diameters

Since the Sun and Moon have approximately the same apparent angular diameter:

$$
\frac{D_M}{D_S}
=
\frac{d_{EM}}{d_{ES}}
$$

Substitute:

$$
\frac{D_M}{D_S}
=
\frac{3.84 \times 10^5}{1.47 \times 10^8}
$$

$$
\frac{D_M}{D_S}
\approx 0.00262
$$

So:

$$
\frac{D_S}{D_M}
\approx 382
$$

---

## 4. Using \(\theta = 89.75^\circ\)

Now:

$$
d_{ES}
=
\frac{3.84 \times 10^5}{\cos(89.75^\circ)}
$$

$$
d_{ES} \approx 8.80 \times 10^7\,\mathrm{km}
$$

The change is:

$$
\Delta d
=
8.80 \times 10^7 - 1.47 \times 10^8
$$

$$
\Delta d
\approx -5.87 \times 10^7\,\mathrm{km}
$$

The percentage change is:

$$
\frac{\Delta d}{d}
\times 100
\approx
-40.0\%
$$

---

## Comment

The result is extremely sensitive to the measured angle because \(\theta\) is very close to \(90^\circ\). Near \(90^\circ\), a tiny change in angle causes a large change in \(\cos\theta\), and therefore a large change in:

$$
d_{ES} = \frac{d_{EM}}{\cos\theta}
$$

This means Aristarchus' method was geometrically clever, but very difficult to apply accurately with ancient observational instruments.

---

## Final Answer

$$
\boxed{
d_{ES} \approx 1.47 \times 10^8\,\mathrm{km}
}
$$

$$
\boxed{
D_S \approx 1.36 \times 10^6\,\mathrm{km}
}
$$

$$
\boxed{
\frac{D_M}{D_S} \approx 0.00262
}
$$

Using \(89.75^\circ\):

$$
\boxed{
d_{ES} \approx 8.80 \times 10^7\,\mathrm{km}
}
$$

The distance decreases by about:

$$
\boxed{
5.87 \times 10^7\,\mathrm{km}
}
$$
