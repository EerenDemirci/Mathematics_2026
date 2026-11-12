# Exercise 3. Inconsistent System

## Question

Solve or show that the system is inconsistent:

$$
\begin{cases}
x+2y=3, \\
2x+4y=7.
\end{cases}
$$

Show how the contradiction appears in the matrix after elimination and interpret it in terms of equations.

## Solution

I write the augmented matrix and do $R_2\leftarrow R_2-2R_1$:

$$
\begin{pmatrix}
1 & 2 & \mid & 3 \\
2 & 4 & \mid & 7 \\
\end{pmatrix}\ \longrightarrow\
\begin{pmatrix}
1 & 2 & \mid & 3 \\
0 & 0 & \mid & 1 \\
\end{pmatrix}
$$

The second row now means $0\cdot x+0\cdot y=1$, so $0=1$. This is not possible. So the system has no solution (it is inconsistent).

In words: if I multiply the first equation by 2, I get $2x+4y=6$. But the second equation says $2x+4y=7$. The same expression cannot be 6 and 7 at the same time. In geometry, the two equations are two parallel lines, and parallel lines do not meet.

**Answer:** the system is inconsistent, it has no solution.

**Check:** the left sides are proportional ($2x+4y=2(x+2y)$), but the right sides are not ($7\neq2\cdot3$). This always means no solution.
