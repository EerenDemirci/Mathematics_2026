# Exercise 12. A Parameter Revealed by a Row Operation

## Question

For

$$
A(t)=
\begin{pmatrix}
1 & 2 & 3 \\
2 & 4 & t \\
0 & 1 & 1 \\
\end{pmatrix}
$$

find the values of $t$ for which the matrix is not invertible.

Before computing the determinant, perform the operation

$$
R_2\leftarrow R_2-2R_1
$$

and use the resulting structure. At the end, explain what special thing happens to the rows for the value of the parameter you found.

## Solution

First I do $R_2\leftarrow R_2-2R_1$. This does not change the determinant. The new second row is $(2-2,\ 4-4,\ t-6)=(0,0,t-6)$:

$$
\begin{pmatrix}
1 & 2 & 3 \\
0 & 0 & t-6 \\
0 & 1 & 1 \\
\end{pmatrix}
$$

Then I swap $R_2$ and $R_3$. A swap changes the sign of the determinant. Now the matrix is triangular:

$$
\begin{pmatrix}
1 & 2 & 3 \\
0 & 1 & 1 \\
0 & 0 & t-6 \\
\end{pmatrix}
$$

Its determinant is $1\cdot1\cdot(t-6)=t-6$. Because of the swap, the determinant of $A(t)$ is:

$$
\det A(t)=-(t-6)=6-t
$$

The matrix is not invertible when $6-t=0$, so $t=6$.

What happens for $t=6$: the second row of $A(6)$ is $(2,4,6)$, which is two times the first row $(1,2,3)$. The rows are dependent, so the determinant is 0.

**Answer:** $A(t)$ is not invertible only for $t=6$.

**Check:** expansion along the first row gives $(4-t)-2\cdot2+3\cdot2=6-t$. This is the same result.
