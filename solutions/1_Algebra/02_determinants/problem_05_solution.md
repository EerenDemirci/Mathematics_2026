# Exercise 5

**Answer:** $\det A=21$.

**Steps**

$R_2\leftarrow R_2-2R_1$, $R_3\leftarrow R_3+R_1$ ($\det$ unchanged):

$$
\begin{pmatrix}
1 & 2 & 3 \\
0 & -3 & -6 \\
0 & 6 & 5 \\
\end{pmatrix}
$$

$R_3\leftarrow R_3+2R_2$ ($\det$ unchanged):

$$
\begin{pmatrix}
1 & 2 & 3 \\
0 & -3 & -6 \\
0 & 0 & -7 \\
\end{pmatrix}
$$

$$
\det A=1\cdot(-3)\cdot(-7)=21
$$

**Rule:** adding a multiple of a row does not change $\det$; a swap changes the sign; multiplying a row by $c$ multiplies $\det$ by $c$.

**Check:** first-row expansion: $1\cdot2-2\cdot4+3\cdot9=21$.
