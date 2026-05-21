# 4. Geostationary Orbit

A geostationary satellite must stay above the same point on Earth.

Therefore, its orbital period must equal Earth's rotation period:

$$
T = 24\,\mathrm{h}
$$

$$
T = 86400\,\mathrm{s}
$$

For a circular orbit:

$$
T = 2\pi \sqrt{\frac{r^3}{GM_E}}
$$

Solve for \(r\):

$$
r^3 = GM_E\left(\frac{T}{2\pi}\right)^2
$$

$$
r =
\left[
GM_E\left(\frac{T}{2\pi}\right)^2
\right]^{1/3}
$$

Given:

$$
G = 6.67 \times 10^{-11}\,\mathrm{N\,m^2/kg^2}
$$

$$
M_E = 5.97 \times 10^{24}\,\mathrm{kg}
$$

Substitute:

$$
r =
\left[
(6.67 \times 10^{-11})(5.97 \times 10^{24})
\left(\frac{86400}{2\pi}\right)^2
\right]^{1/3}
$$

$$
r \approx 4.224 \times 10^7\,\mathrm{m}
$$

Convert to kilometers:

$$
r \approx 42236\,\mathrm{km}
$$

This is the distance from Earth's center. The altitude above Earth's surface is:

$$
h = r - R_E
$$

$$
h = 42236 - 6378
$$

$$
h \approx 35858\,\mathrm{km}
$$

---

## Final Answer

$$
\boxed{
T = 24\,\mathrm{h}
}
$$

$$
\boxed{
h \approx 3.59 \times 10^4\,\mathrm{km}
}
$$

So the geostationary altitude is approximately:

$$
\boxed{
35800\,\mathrm{km}
}
$$
