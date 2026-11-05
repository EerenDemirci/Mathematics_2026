# Exercise 13

**Answer:** $\det A=1$.

**Steps** (none of them changes $\det$)

$R_2\leftarrow R_2-2R_1$, $R_3\leftarrow R_3-R_1$:

$$
\begin{pmatrix}
1 & 2 & 3 \\
0 & 1 & 1 \\
0 & -2 & -1 \\
\end{pmatrix}
$$

$R_3\leftarrow R_3+2R_2$:

$$
\begin{pmatrix}
1 & 2 & 3 \\
0 & 1 & 1 \\
0 & 0 & 1 \\
\end{pmatrix},\qquad \det=1\cdot1\cdot1=1
$$

**Rule:** only $R_i\leftarrow R_i+cR_j$ was used, so no correction is needed.

**Check (Sarrus):** $(10+14+0)-(15+0+8)=24-23=1$.
