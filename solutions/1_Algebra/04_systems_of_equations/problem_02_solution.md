# Exercise 2. Gaussian Elimination — One Solution

## Question

Solve using Gaussian elimination:

$$
\begin{cases}
x+y+z=6, \\
2x-y+z=3, \\
x+2y-z=2.
\end{cases}
$$

After solving, substitute the result into all equations and check consistency.

## Solution

I write the augmented matrix $[A\mid b]$:

$$
\begin{pmatrix}
1 & 1 & 1 & \mid & 6 \\
2 & -1 & 1 & \mid & 3 \\
1 & 2 & -1 & \mid & 2 \\
\end{pmatrix}
$$

I make zeros under the first 1 with $R_2\leftarrow R_2-2R_1$ and $R_3\leftarrow R_3-R_1$:

$$
\begin{pmatrix}
1 & 1 & 1 & \mid & 6 \\
0 & -3 & -1 & \mid & -9 \\
0 & 1 & -2 & \mid & -4 \\
\end{pmatrix}
$$

I swap $R_2$ and $R_3$, and then I do $R_3\leftarrow R_3+3R_2$:

$$
\begin{pmatrix}
1 & 1 & 1 & \mid & 6 \\
0 & 1 & -2 & \mid & -4 \\
0 & 0 & -7 & \mid & -21 \\
\end{pmatrix}
$$

Now I solve from the bottom (back substitution). The last row gives $-7z=-21$, so $z=3$. The second row gives $y-2\cdot3=-4$, so $y=2$. The first row gives $x+2+3=6$, so $x=1$.

**Answer:** $x=1$, $y=2$, $z=3$.

**Check:** I put the numbers into all three equations: $1+2+3=6$, $2-2+3=3$, $1+4-3=2$. All three are true.
