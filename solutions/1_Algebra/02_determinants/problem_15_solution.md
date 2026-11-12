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

I use $\det(XYZ)=\det X\det Y\det Z$, then $\det(B^{-1})=\frac{1}{\det B}$ and $\det(A^T)=\det A$:

$$
\det\left(B^{-1}A^TB\right)=\frac13\cdot(-2)\cdot3=-2
$$

The factors with $B$ cancel because determinants are just numbers: $\frac{1}{\det B}\cdot\det B=1$.
