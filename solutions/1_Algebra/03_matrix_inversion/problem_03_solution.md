# Exercise 3. When Does the Inverse Not Exist?

## Question

For

$$
A=
\begin{pmatrix}
2 & 4 \\
1 & 2 \\
\end{pmatrix}
$$

explain in two ways why $A^{-1}$ does not exist: using the determinant and using dependence between the rows.

## Solution

**Way 1: the determinant.**

$$
\det A=2\cdot2-4\cdot1=0
$$

The inverse formula divides by the determinant, and we cannot divide by 0. A matrix has an inverse only when $\det A\neq0$, so $A^{-1}$ does not exist.

**Way 2: the rows.** The first row is two times the second row:

$$
(2,4)=2\cdot(1,2)
$$

So the rows are dependent. The matrix sends many different vectors to the same vector, for example $A(2,-1)^T=(0,0)^T=A(0,0)^T$. Then we cannot go back in a unique way, so there is no inverse.

The two ways are connected: dependent rows always give determinant 0.

**Answer:** $A^{-1}$ does not exist, because $\det A=0$ and the rows are dependent.

**Check:** $A(2,-1)^T=(4-4,\ 2-2)^T=(0,0)^T$, so a nonzero vector goes to zero.
