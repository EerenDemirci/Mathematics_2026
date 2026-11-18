# Exercise 11. Decomposition into Parallel and Perpendicular Components

## Question

Decompose $u=(3,4)$ into components parallel and perpendicular to $v=(1,2)$. Check

$$
u=u_{\parallel}+u_{\perp},\qquad u_{\perp}\cdot v=0.
$$

Explain why these are two independent checks of correctness.

## Solution

The parallel part is the projection of $u$ onto $v$:

$$
u_{\parallel}=\frac{u\cdot v}{v\cdot v}\,v=\frac{3+8}{1+4}(1,2)=\left(\frac{11}{5},\frac{22}{5}\right)
$$

The perpendicular part is the rest:

$$
u_{\perp}=u-u_{\parallel}=\left(3-\frac{11}{5},\ 4-\frac{22}{5}\right)=\left(\frac45,-\frac25\right)
$$

Check 1: $u_{\parallel}+u_{\perp}=\left(\frac{15}{5},\frac{20}{5}\right)=(3,4)=u$.

Check 2: $u_{\perp}\cdot v=\frac45-\frac45=0$.

These are two different checks. The first one only says that the two parts add up to $u$, which is true for many splits. The second one says that the second part is really perpendicular to $v$. Only with both conditions the split is the correct one.
