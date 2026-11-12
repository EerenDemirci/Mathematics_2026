# Exercise 15. Combining Determinant Properties

## Question

Let $A$ and $B$ be invertible $2\times2$ matrices with

$$
\det A=-2,\qquad \det B=3.
$$

Without finding the entries of the matrices, compute

$$
\det\left(B^{-1}A^TB\right).
$$

State the determinant properties you use in order and explain why the factors involving $B$ eventually cancel.

## Solution

I use three properties of the determinant, in this order:

1. the determinant of a product is the product of the determinants,
2. $\det(B^{-1})=\frac{1}{\det B}$,
3. $\det(A^T)=\det A$.

So I get:

$$
\det\left(B^{-1}A^TB\right)=\det(B^{-1})\cdot\det(A^T)\cdot\det B=\frac13\cdot(-2)\cdot3=-2
$$

The matrices $B^{-1}$ and $B$ cannot be removed from the matrix product, because matrices do not commute. But their determinants are just numbers. For numbers the order does not matter, and $\frac{1}{\det B}\cdot\det B=1$. So only $\det A=-2$ is left.

**Answer:** $\det\left(B^{-1}A^TB\right)=-2$.

**Check:** I take $A=\mathrm{diag}(-2,1)$ and $B=\mathrm{diag}(3,1)$. Then $B^{-1}A^TB=\mathrm{diag}(-2,1)$, and its determinant is $-2$.
