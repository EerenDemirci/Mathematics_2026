# Exercise 15

**Answer**

$$
\det(B^{-1}A^TB)=\det(B^{-1})\cdot\det(A^T)\cdot\det B=\frac13\cdot(-2)\cdot3=-2
$$

**Rules (in order):** $\det(XYZ)=\det X\det Y\det Z$; $\det(B^{-1})=\frac{1}{\det B}$; $\det(A^T)=\det A$.

**Why $B$ cancels:** the determinants are numbers, and $\frac{1}{\det B}\cdot\det B=1$.

**Check:** $A=\mathrm{diag}(-2,1)$, $B=\mathrm{diag}(3,1)$: $B^{-1}A^TB=\mathrm{diag}(-2,1)$, $\det=-2$.
