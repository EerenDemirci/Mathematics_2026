# Exercise 13. Determinant by Elimination

## Question

Compute the determinant

$$
A=
\begin{pmatrix}
1 & 2 & 3 \\
2 & 5 & 7 \\
1 & 0 & 2 \\
\end{pmatrix}
$$

using elimination. Record the effect of every row operation used on the value of the determinant.

## Solution

I use elimination. I only add multiples of rows to other rows, so the determinant never changes.

Step 1: $R_2\leftarrow R_2-2R_1$ and $R_3\leftarrow R_3-R_1$ (no change of the determinant):

$$
\begin{pmatrix}
1 & 2 & 3 \\
0 & 1 & 1 \\
0 & -2 & -1 \\
\end{pmatrix}
$$

Step 2: $R_3\leftarrow R_3+2R_2$ (no change of the determinant):

$$
\begin{pmatrix}
1 & 2 & 3 \\
0 & 1 & 1 \\
0 & 0 & 1 \\
\end{pmatrix}
$$

Step 3: the matrix is triangular, so I multiply the diagonal:

$$
\det A=1\cdot1\cdot1=1
$$

**Answer:** $\det A=1$.

**Check:** Sarrus' rule for the start matrix gives $(10+14+0)-(15+0+8)=24-23=1$.
