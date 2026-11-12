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

$$
\begin{pmatrix}
1 & 1 & 1 & \mid & 6 \\
2 & -1 & 1 & \mid & 3 \\
1 & 2 & -1 & \mid & 2 \\
\end{pmatrix}
$$

$R_2\leftarrow R_2-2R_1$ and $R_3\leftarrow R_3-R_1$, then I swap $R_2$ and $R_3$ and do $R_3\leftarrow R_3+3R_2$:

$$
\begin{pmatrix}
1 & 1 & 1 & \mid & 6 \\
0 & 1 & -2 & \mid & -4 \\
0 & 0 & -7 & \mid & -21 \\
\end{pmatrix}
$$

From the bottom: $z=3$, then $y-6=-4$ so $y=2$, then $x+2+3=6$ so $x=1$.

Check: $1+2+3=6$, $2-2+3=3$, $1+4-3=2$.
