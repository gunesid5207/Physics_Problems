# Problem 3: Path Intersection

Alice moves along the path

$$
A(t) = (2+t,\ 8-3t)
$$

and Bob moves along the path

$$
B(t) = (2t-1,\ 2t+2)
$$

We want to determine whether their paths intersect, and if so, when and where they collide.

---

## 1. Condition for collision

For a collision, both position coordinates must be equal at the same time \(t\):

$$
2+t = 2t-1
$$

and

$$
8-3t = 2t+2
$$

---

## 2. Solve the first equation

$$
2+t = 2t-1
$$

Subtract \(t\) from both sides:

$$
2 = t-1
$$

Add 1 to both sides:

$$
t = 3
$$

---

## 3. Check the second equation

Substitute \(t=3\):

Left-hand side:

$$
8 - 3(3) = 8 - 9 = -1
$$

Right-hand side:

$$
2(3) + 2 = 6 + 2 = 8
$$

Since

$$
-1 \ne 8
$$

the second equation is not satisfied.

---

## 4. Conclusion

The two position vectors are not equal at the same time, so Alice and Bob do **not** collide.

Therefore, their paths do **not** intersect at the same instant of time.

## Final answer

Alice and Bob do not collide, because there is no value of \(t\) that satisfies both coordinate equations simultaneously.