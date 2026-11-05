# Exercise 12

**Answer:** not invertible for $t=6$.

**Steps**

$R_2\leftarrow R_2-2R_1$ gives row 2 $=(0,0,t-6)$:

$$
\begin{pmatrix}
1 & 2 & 3 \\
0 & 0 & t-6 \\
0 & 1 & 1 \\
\end{pmatrix}
$$

Swap $R_2\leftrightarrow R_3$ (sign changes), then the matrix is triangular:

$$
\det A(t)=-(1\cdot1\cdot(t-6))=6-t
$$

$6-t=0$ gives $t=6$.

**What happens at $t=6$:** row 2 becomes $(0,0,0)$, i.e. $(2,4,6)=2\cdot(1,2,3)$; the rows are dependent.

**Check:** first-row expansion: $(4-t)-2\cdot2+3\cdot2=6-t$.
