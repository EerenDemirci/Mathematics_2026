# Exercise 9. Area and the Determinant

## Question

The vectors

$$
u=
\begin{pmatrix}
3 \\
1 \\
\end{pmatrix},\qquad v=
\begin{pmatrix}
1 \\
4 \\
\end{pmatrix}
$$

span a parallelogram. Compute its area using a determinant. Then reverse the order of the vectors and explain what changes in the determinant and what does not change in the area.

## Solution

I put the vectors $u$ and $v$ as the columns of a matrix and find the determinant:

$$
\det
\begin{pmatrix}
3 & 1 \\
1 & 4 \\
\end{pmatrix}=3\cdot4-1\cdot1=11
$$

The area of the parallelogram is the absolute value of this determinant, so the area is 11.

Now I change the order of the vectors:

$$
\det
\begin{pmatrix}
1 & 3 \\
4 & 1 \\
\end{pmatrix}=1\cdot1-3\cdot4=-11
$$

The determinant changes its sign, because I swapped two columns. The sign shows the direction (orientation) of the pair of vectors. The area does not change, because $|-11|=|11|=11$.

**Answer:** the area is 11. With the other order the determinant is $-11$, but the area is still 11.

**Check:** another formula for the area is $P^2=|u|^2|v|^2-(u\cdot v)^2=10\cdot17-7^2=121$, so $P=11$.
