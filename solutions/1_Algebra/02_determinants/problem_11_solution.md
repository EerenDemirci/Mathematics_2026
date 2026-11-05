# Exercise 11

**Answer:** $\det=1$.

**Steps**

$R_2\leftarrow R_2-R_1$, $R_3\leftarrow R_3-R_1$, then $R_3\leftarrow R_3-2R_2$:

$$
\begin{pmatrix}
1 & 2 & 3 \\
0 & 1 & 1 \\
0 & 0 & 1 \\
\end{pmatrix},\qquad \det=1\cdot1\cdot1=1
$$

**Rule:** $R_i\leftarrow R_i+cR_j$ does not change the determinant.

**Check (Sarrus):** $(18+8+12)-(9+16+12)=38-37=1$.
