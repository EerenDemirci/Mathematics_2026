# Exercise 7. Using Properties Instead of Recomputing

## Question

Suppose that for a $3\times3$ matrix, $\det A=-4$. Compute

$$
\det(2A),\qquad \det(A^T),\qquad \det(A^2),\qquad \det(-A).
$$

Justify each answer using the appropriate property.

## Solution

$A$ is a $3\times3$ matrix, so $n=3$. I use the properties of the determinant.

If we multiply the matrix by a number $c$, every row is multiplied by $c$, so $\det(cA)=c^n\det A$:

$$
\det(2A)=2^3\cdot(-4)=-32
$$

The transpose does not change the determinant:

$$
\det(A^T)=\det A=-4
$$

The determinant of a product is the product of the determinants:

$$
\det(A^2)=\det A\cdot\det A=(-4)^2=16
$$

$-A$ is the case $c=-1$:

$$
\det(-A)=(-1)^3\cdot(-4)=4
$$

**Answer:** $\det(2A)=-32$, $\det(A^T)=-4$, $\det(A^2)=16$, $\det(-A)=4$.

**Check:** I take an example matrix with $\det A=-4$, the diagonal matrix with $-4,1,1$ on the diagonal. Then $2A$ has $-8,2,2$ on the diagonal and its determinant is $-32$, as above.
