# Exercise 7. Using Properties Instead of Recomputing

## Question

Suppose that for a $3\times3$ matrix, $\det A=-4$. Compute

$$
\det(2A),\qquad \det(A^T),\qquad \det(A^2),\qquad \det(-A).
$$

Justify each answer using the appropriate property.

## Solution

$A$ is $3\times3$, so $n=3$.

$$
\det(2A)=2^3\det A=8\cdot(-4)=-32
$$

because each of the 3 rows is multiplied by 2.

$$
\det(A^T)=\det A=-4
$$

because the transpose does not change the determinant.

$$
\det(A^2)=\det A\cdot\det A=16
$$

because the determinant of a product is the product of the determinants.

$$
\det(-A)=(-1)^3\det A=4
$$

because each row is multiplied by $-1$.
