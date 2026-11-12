# Exercise 10. Detecting Dependence

## Question

Without carrying out a full determinant calculation, explain why

$$
\det
\begin{pmatrix}
1 & 2 & 3 \\
2 & 4 & 6 \\
0 & 1 & 5 \\
\end{pmatrix}=0.
$$

Identify a specific dependence between the rows and connect it with noninvertibility of the matrix.

## Solution

The second row is two times the first row:

$$
(2,4,6)=2\cdot(1,2,3)
$$

So $R_2-2R_1=0$. If I do this row operation, the determinant stays the same and the second row becomes all zeros. A matrix with a zero row has determinant 0.

Because the rows are dependent and the determinant is 0, the matrix is not invertible.
