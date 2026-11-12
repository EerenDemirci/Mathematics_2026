# Exercise 1. Matrix Size and Entries

## Question

Given

$$
A=
\begin{pmatrix}
2 & -1 & 3 \\
0 & 4 & 5 \\
\end{pmatrix},\qquad B=
\begin{pmatrix}
1 & 0 \\
-2 & 3 \\
4 & 1 \\
\end{pmatrix}.
$$

1. State the sizes of matrices $A$ and $B$.
2. Read off the entries $a_{12}$, $a_{23}$, $b_{21}$, and $b_{32}$.
3. Write the second row of $A$ and the first column of $B$ as vectors.

## Solution

The size of a matrix is the number of rows times the number of columns. $A$ has 2 rows and 3 columns, so $A$ is $2\times3$. $B$ has 3 rows and 2 columns, so $B$ is $3\times2$.

The entry $a_{ij}$ is in row $i$ and column $j$. So I read the entries directly from the matrices:

$$
a_{12}=-1,\qquad a_{23}=5,\qquad b_{21}=-2,\qquad b_{32}=1
$$

The second row of $A$ is a row vector. The first column of $B$ is a column vector:

$$
r_2=
\begin{pmatrix}
0 & 4 & 5 \\
\end{pmatrix},\qquad c_1=
\begin{pmatrix}
1 \\
-2 \\
4 \\
\end{pmatrix}
$$

**Answer:** $A$ is $2\times3$, $B$ is $3\times2$; $a_{12}=-1$, $a_{23}=5$, $b_{21}=-2$, $b_{32}=1$; the second row of $A$ is $(0,4,5)$ and the first column of $B$ is $(1,-2,4)^T$.

**Check:** $A$ has $2\cdot3=6$ numbers and $B$ has $3\cdot2=6$ numbers. This matches the matrices.
