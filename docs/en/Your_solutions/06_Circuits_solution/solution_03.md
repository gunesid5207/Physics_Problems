# 3. Mixed Circuit

All resistors have:

$$
R = 5\,\Omega
$$

From the figure, the bottom resistor is directly between the two terminals.

So one branch is:

$$
R_1 = 5\,\Omega
$$

---

The upper network has two paths from the left node to the top node.

First path:

$$
5 + 5 = 10\,\Omega
$$

Second path:

$$
5 + 5 + 5 = 15\,\Omega
$$

These two paths are in parallel:

$$
R_{\text{parallel}} =
\frac{10 \times 15}{10 + 15}
$$

$$
R_{\text{parallel}} =
\frac{150}{25}
$$

$$
R_{\text{parallel}} = 6\,\Omega
$$

This is in series with the right branch:

$$
R_{\text{upper}} = 6 + 5 + 5
$$

$$
R_{\text{upper}} = 16\,\Omega
$$

---

Now the total circuit has:

$$
5\,\Omega
$$

in parallel with:

$$
16\,\Omega
$$

So:

$$
R_{\text{eq}} =
\frac{5 \times 16}{5 + 16}
$$

$$
R_{\text{eq}} =
\frac{80}{21}
$$

$$
R_{\text{eq}} \approx 3.81\,\Omega
$$

**Answer:**

$$
\boxed{R_{\text{eq}} \approx 3.81\,\Omega}
$$