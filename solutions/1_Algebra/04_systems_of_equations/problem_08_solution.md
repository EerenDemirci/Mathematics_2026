# Exercise 8. Two Systems with the Same Coefficient Matrix

## Question

Solve by elimination the two systems

$$
\begin{cases}
2x+y=5, \\
x-y=1,
\end{cases}
$$

$$
\begin{cases}
2x+y=1, \\
x-y=4.
\end{cases}
$$

Compare the successive elimination steps. Which part of the calculation is the same in both cases, and why?

## Solution

Both systems have the same left side, so I can write both right sides in one matrix:

$$
\begin{pmatrix}
2 & 1 & \mid & 5 & 1 \\
1 & -1 & \mid & 1 & 4 \\
\end{pmatrix}
$$

$R_2\leftarrow 2R_2-R_1$:

$$
\begin{pmatrix}
2 & 1 & \mid & 5 & 1 \\
0 & -3 & \mid & -3 & 7 \\
\end{pmatrix}
$$

First system: $y=1$, $x=2$. Second system: $y=-\frac73$, $x=\frac53$.

The elimination steps are the same in both cases, because they depend only on the coefficient matrix. Only the right side numbers change.
