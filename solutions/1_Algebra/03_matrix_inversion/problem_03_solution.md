# Exercise 3. When Does the Inverse Not Exist?

## Question

For

$$
A=
\begin{pmatrix}
2 & 4 \\
1 & 2 \\
\end{pmatrix}
$$

explain in two ways why $A^{-1}$ does not exist: using the determinant and using dependence between the rows.

## Solution

With the determinant:

$$
\det A=2\cdot2-4\cdot1=0
$$

A matrix with determinant 0 has no inverse (the formula would divide by 0).

With the rows: the first row is two times the second row, $(2,4)=2\cdot(1,2)$. The rows are dependent, so the matrix is not invertible. Both reasons say the same thing, because dependent rows always give determinant 0.
