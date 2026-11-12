# Exercise 15. Classifying Three Systems

## Question

For each of the following systems, perform only as much elimination as necessary to recognize its type:

**System 1**

$$
\begin{cases}
x+y=2, \\
x-y=0,
\end{cases}
$$

**System 2**

$$
\begin{cases}
x+y=2, \\
2x+2y=4,
\end{cases}
$$

**System 3**

$$
\begin{cases}
x+y=2, \\
2x+2y=5.
\end{cases}
$$

For each, justify the classification: one solution, infinitely many solutions, or no solution.

## Solution

**System 1.** I do $R_2\leftarrow R_2-R_1$:

$$
\begin{pmatrix}
1 & 1 & \mid & 2 \\
0 & -2 & \mid & -2 \\
\end{pmatrix}
$$

There is a pivot in every column, so $y=1$ and then $x=1$. This system has exactly one solution.

**System 2.** I do $R_2\leftarrow R_2-2R_1$:

$$
\begin{pmatrix}
1 & 1 & \mid & 2 \\
0 & 0 & \mid & 0 \\
\end{pmatrix}
$$

The second row is $0=0$, so only one equation is left. There are infinitely many solutions: $x=2-s$, $y=s$.

**System 3.** I do $R_2\leftarrow R_2-2R_1$:

$$
\begin{pmatrix}
1 & 1 & \mid & 2 \\
0 & 0 & \mid & 1 \\
\end{pmatrix}
$$

The second row is $0=1$, which is not possible. There is no solution.

**Answer:** System 1: one solution $(1,1)$. System 2: infinitely many solutions. System 3: no solution.

**Check:** $(1,1)$ in system 1: $1+1=2$ and $1-1=0$. In system 2 and 3 the left sides are proportional: if the right sides are also proportional (system 2) we get infinitely many solutions; if not (system 3) we get no solution.
