# Exercise 8. Row Operations and Their Reversibility

## Question

For

$$
A=
\begin{pmatrix}
1 & 2 & -1 \\
2 & 4 & 1 \\
-1 & 1 & 3 \\
\end{pmatrix}
$$

perform, in order:

1. $R_2\leftarrow R_2-2R_1$,
2. $R_3\leftarrow R_3+R_1$,
3. interchange $R_2$ and $R_3$.

Write the matrix after each step. Then, for each of the three operations, state an operation that reverses it.

## Solution

I do the three operations in order and write the matrix after each step.

Step 1, $R_2\leftarrow R_2-2R_1$. The new second row is $(2,4,1)-2(1,2,-1)=(0,0,3)$:

$$
\begin{pmatrix}
1 & 2 & -1 \\
0 & 0 & 3 \\
-1 & 1 & 3 \\
\end{pmatrix}
$$

Step 2, $R_3\leftarrow R_3+R_1$. The new third row is $(-1,1,3)+(1,2,-1)=(0,3,2)$:

$$
\begin{pmatrix}
1 & 2 & -1 \\
0 & 0 & 3 \\
0 & 3 & 2 \\
\end{pmatrix}
$$

Step 3, I swap $R_2$ and $R_3$:

$$
\begin{pmatrix}
1 & 2 & -1 \\
0 & 3 & 2 \\
0 & 0 & 3 \\
\end{pmatrix}
$$

Every row operation can be undone:

| Operation | Reverse operation |
|---|---|
| $R_2\leftarrow R_2-2R_1$ | $R_2\leftarrow R_2+2R_1$ |
| $R_3\leftarrow R_3+R_1$ | $R_3\leftarrow R_3-R_1$ |
| $R_2\leftrightarrow R_3$ | $R_2\leftrightarrow R_3$ again |

**Answer:** the matrices after the three steps are shown above, and the reverse operations are in the table.

**Check:** I use the determinant. For the start matrix, $\det A=11-14-6=-9$. The last matrix is triangular, so its determinant is $1\cdot3\cdot3=9$. Steps 1 and 2 do not change the determinant, and the swap changes the sign, so $-9$ becomes $9$. This is correct.
