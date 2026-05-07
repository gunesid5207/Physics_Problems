# 14. RLC Circuit

For a series RLC circuit, Kirchhoff’s voltage law gives:

$$
V(t) = V_R + V_L + V_C
$$

Using:

$$
V_R = RI
$$

$$
V_L = L\frac{dI}{dt}
$$

and

$$
I = C\frac{dV_C}{dt}
$$

the differential equation becomes:

$$
L\frac{d^2Q}{dt^2}
+
R\frac{dQ}{dt}
+
\frac{1}{C}Q
=
V(t)
$$

where:

$$
I = \frac{dQ}{dt}
$$

and $Q(t)$ is the charge on the capacitor.

---

## Comparison with a Damped Harmonic Oscillator

The equation of a damped harmonic oscillator is:

$$
m\frac{d^2x}{dt^2}
+
b\frac{dx}{dt}
+
kx
=
F(t)
$$

---

## Analogies Between the Terms

| RLC Circuit | Mechanical Oscillator |
|---|---|
| $L$ | Mass $m$ |
| $R$ | Damping coefficient $b$ |
| $\frac{1}{C}$ | Spring constant $k$ |
| Charge $Q$ | Displacement $x$ |
| Voltage $V(t)$ | External force $F(t)$ |

---

## Final Comment

An RLC circuit behaves mathematically like a damped harmonic oscillator.

Both systems can oscillate and lose energy due to damping.