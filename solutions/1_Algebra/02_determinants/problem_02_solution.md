# Exercise 2. Determinant of a 3×3 Matrix

## Question

For

$$
A=
\begin{pmatrix}
1 & 2 & -1 \\
0 & 3 & 4 \\
2 & 1 & 5 \\
\end{pmatrix}
$$

compute $\det A$ using Sarrus' rule. Then perform one simple check using a chosen property of the determinant.

## Solution

With Sarrus' rule:

$$
\det A=(15+16+0)-(-6+4+0)=31-(-2)=33
$$

Check: $R_3\leftarrow R_3-2R_1$ does not change the determinant and gives the row $(0,-3,7)$. Then I expand along the first column:

$$
\det A=1\cdot(3\cdot7-4\cdot(-3))=21+12=33
$$
