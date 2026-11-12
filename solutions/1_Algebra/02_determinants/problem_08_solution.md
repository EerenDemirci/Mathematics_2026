# Exercise 8. Determinant of a Product

## Question

Let $A,B$ be square matrices such that $\det A=3$ and $\det B=-5$. Compute $\det(AB)$, $\det(BA)$ and, if it exists, $\det(A^{-1}B)$. Explain why the first two results are equal even though usually $AB\neq BA$.

## Solution

I use the rule $\det(XY)=\det X\cdot\det Y$:

$$
\det(AB)=3\cdot(-5)=-15,\qquad \det(BA)=(-5)\cdot3=-15
$$

$\det A=3$ is not 0, so $A^{-1}$ exists. From $AA^{-1}=I$ we get $\det A\cdot\det(A^{-1})=1$, so $\det(A^{-1})=\frac13$. Then:

$$
\det(A^{-1}B)=\frac13\cdot(-5)=-\frac53
$$

The matrices $AB$ and $BA$ are usually different. But their determinants are products of the same two numbers, and for numbers the order does not matter. That is why $\det(AB)=\det(BA)$.

**Answer:** $\det(AB)=-15$, $\det(BA)=-15$, $\det(A^{-1}B)=-\frac53$.

**Check:** with the diagonal matrices $A=\mathrm{diag}(3,1)$ and $B=\mathrm{diag}(-5,1)$ we get $AB=\mathrm{diag}(-15,1)$, and its determinant is $-15$.
