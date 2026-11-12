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

I look at the rows. The second row is two times the first row:

$$
(2,4,6)=2\cdot(1,2,3)
$$

So the rows are dependent: $2R_1-R_2=0$. If I do $R_2\leftarrow R_2-2R_1$, the determinant does not change, and the second row becomes $(0,0,0)$. A matrix with a row of zeros has determinant 0. So the determinant is 0 without a full calculation.

Because the determinant is 0, the matrix is not invertible. This means there is a vector $x\neq0$ with $Mx=0$.

**Answer:** $\det=0$, because $R_2=2R_1$. The matrix is not invertible.

**Check:** I find such a vector. The third row gives $x_2=-5x_3$ and the first row gives $x_1=7x_3$. For $x_3=1$:

$$
x=
\begin{pmatrix}
7 \\
-5 \\
1 \\
\end{pmatrix},\qquad Mx=
\begin{pmatrix}
7-10+3 \\
14-20+6 \\
0-5+5 \\
\end{pmatrix}=
\begin{pmatrix}
0 \\
0 \\
0 \\
\end{pmatrix}
$$
