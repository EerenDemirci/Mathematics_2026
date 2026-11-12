# Exercise 8. Determinant of a Product

## Question

Let $A,B$ be square matrices such that $\det A=3$ and $\det B=-5$. Compute $\det(AB)$, $\det(BA)$ and, if it exists, $\det(A^{-1}B)$. Explain why the first two results are equal even though usually $AB\neq BA$.

## Solution

$$
\det(AB)=\det A\cdot\det B=3\cdot(-5)=-15,\qquad \det(BA)=(-5)\cdot3=-15
$$

$A^{-1}$ exists because $\det A\neq0$, and $\det(A^{-1})=\frac13$:

$$
\det(A^{-1}B)=\frac13\cdot(-5)=-\frac53
$$

$AB$ and $BA$ can be different matrices, but their determinants are products of the same two numbers, and for numbers the order does not matter.
