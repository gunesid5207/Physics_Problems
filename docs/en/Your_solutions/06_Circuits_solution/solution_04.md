# 4. Mixed Circuit

All resistors have:

$$
R = 10\,\Omega
$$

---

## Step 1: Upper Branch

The upper branch contains two resistors in series:

$$
R_{\text{upper}} = 10 + 10
$$

$$
R_{\text{upper}} = 20\,\Omega
$$

---

## Step 2: Lower Branch

The lower branch first has one resistor:

$$
10\,\Omega
$$

Then two resistors in parallel:

$$
R_{\text{parallel}} =
\frac{10 \times 10}{10 + 10}
$$

$$
R_{\text{parallel}} =
\frac{100}{20}
$$

$$
R_{\text{parallel}} = 5\,\Omega
$$

So the lower branch becomes:

$$
R_{\text{lower}} = 10 + 5
$$

$$
R_{\text{lower}} = 15\,\Omega
$$

---

## Step 3: Combine Upper and Lower Branches

Now we have:

$$
20\,\Omega
$$

in parallel with:

$$
15\,\Omega
$$

So:

$$
R_{\text{middle}} =
\frac{20 \times 15}{20 + 15}
$$

$$
R_{\text{middle}} =
\frac{300}{35}
$$

$$
R_{\text{middle}} \approx 8.57\,\Omega
$$

---

## Step 4: Final Series Resistor

There is one more resistor in series on the right:

$$
R_{\text{eq}} = 8.57 + 10
$$

$$
R_{\text{eq}} \approx 18.57\,\Omega
$$

---

## Final Answer

$$
\boxed{R_{\text{eq}} \approx 18.6\,\Omega}
$$