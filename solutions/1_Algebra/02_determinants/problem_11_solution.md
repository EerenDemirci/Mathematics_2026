# Exercise 11. Shortening the Calculation with Row Operations

## Question

Compute

$$
\det
\begin{pmatrix}
1 & 2 & 3 \\
1 & 3 & 4 \\
1 & 4 & 6 \\
\end{pmatrix}
$$

by first performing row operations that create as many zeros as possible. State which operations do not change the determinant.

## Solution

The first column has only ones, so I subtract the first row from the other rows. This gives two zeros at once. These operations do not change the determinant:

$$
R_2\leftarrow R_2-R_1,\quad R_3\leftarrow R_3-R_1:\qquad
\begin{pmatrix}
1 & 2 & 3 \\
0 & 1 & 1 \\
0 & 2 & 3 \\
\end{pmatrix}
$$

Then $R_3\leftarrow R_3-2R_2$, which also does not change the determinant:

$$
\begin{pmatrix}
1 & 2 & 3 \\
0 & 1 & 1 \\
0 & 0 & 1 \\
\end{pmatrix}
$$

Now the matrix is triangular, so the determinant is $1\cdot1\cdot1=1$.

The operations that do not change the determinant are: adding a multiple of one row to another row. A row swap changes the sign, and multiplying a row by $c$ multiplies the determinant by $c$. I did not use these.

**Answer:** $\det=1$.

**Check:** Sarrus' rule for the start matrix gives $(18+8+12)-(9+16+12)=38-37=1$.
