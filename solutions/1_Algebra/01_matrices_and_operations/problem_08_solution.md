# Exercise 8

**Steps**

$R_2\leftarrow R_2-2R_1$:

$$
\begin{pmatrix}
1 & 2 & -1 \\
0 & 0 & 3 \\
-1 & 1 & 3 \\
\end{pmatrix}
$$

$R_3\leftarrow R_3+R_1$:

$$
\begin{pmatrix}
1 & 2 & -1 \\
0 & 0 & 3 \\
0 & 3 & 2 \\
\end{pmatrix}
$$

$R_2\leftrightarrow R_3$:

$$
\begin{pmatrix}
1 & 2 & -1 \\
0 & 3 & 2 \\
0 & 0 & 3 \\
\end{pmatrix}
$$

**Reverse operations:** $R_2\leftarrow R_2+2R_1$; $R_3\leftarrow R_3-R_1$; $R_2\leftrightarrow R_3$ again.

**Rule:** every row operation can be undone, so no information is lost.

**Check:** $\det A=11-14-6=-9$; the final matrix has $\det=1\cdot3\cdot3=9$, and one swap changes the sign: $-9$.
