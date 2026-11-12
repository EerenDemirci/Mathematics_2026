# Exercise 6. Solving a System Using the Inverse

## Question

Solve

$$
Ax=b,
$$

where

$$
A=
\begin{pmatrix}
2 & 1 \\
1 & 3 \\
\end{pmatrix},\qquad b=
\begin{pmatrix}
5 \\
7 \\
\end{pmatrix},
$$

using $x=A^{-1}b$. Then substitute the resulting vector back into the equation and check the result.

## Solution

First I find $A^{-1}$ with the $2\times2$ formula. The determinant is $2\cdot3-1\cdot1=5$:

$$
A^{-1}=\frac15
\begin{pmatrix}
3 & -1 \\
-1 & 2 \\
\end{pmatrix}
$$

Then I multiply $A^{-1}$ by $b$:

$$
x=A^{-1}b=\frac15
\begin{pmatrix}
3\cdot5-1\cdot7 \\
-1\cdot5+2\cdot7 \\
\end{pmatrix}=\frac15
\begin{pmatrix}
8 \\
9 \\
\end{pmatrix}=
\begin{pmatrix}
\frac85 \\
\frac95 \\
\end{pmatrix}
$$

**Answer:** $x=\left(\frac85,\frac95\right)^T$.

**Check:** I put $x$ back into $Ax$:

$$
Ax=
\begin{pmatrix}
2\cdot\frac85+\frac95 \\
\frac85+3\cdot\frac95 \\
\end{pmatrix}=
\begin{pmatrix}
\frac{25}{5} \\
\frac{35}{5} \\
\end{pmatrix}=
\begin{pmatrix}
5 \\
7 \\
\end{pmatrix}=b
$$
