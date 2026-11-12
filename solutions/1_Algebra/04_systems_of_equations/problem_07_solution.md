# Exercise 7. Choosing a Method Deliberately

## Question

Do not solve all of the following systems completely. For each situation, choose the method that best uses its structure and justify your choice:

1. one system with a triangular coefficient matrix

$$
\begin{cases}
2x-y=3, \\
4y=8;
\end{cases}
$$

2. three systems $Ax=b_i$ with the same invertible matrix $A$, when $A^{-1}$ is already known;
3. one $3\times3$ system for which the inverse matrix is not given and the goal is only to find one solution vector.

For case 1, carry out the chosen method completely. For cases 2 and 3, describe the plan and indicate which part of the computation would be reusable or unnecessary. Do not judge a method by its name alone — refer to the number of right-hand sides and the structure of the matrix.

## Solution

**Case 1.** The matrix is triangular, so the best method is back substitution. I start with the last equation:

$$
4y=8\quad\Longrightarrow\quad y=2
$$

Then I put $y=2$ into the first equation:

$$
2x-2=3\quad\Longrightarrow\quad x=\frac52
$$

No elimination is needed, because the matrix is already triangular.

**Case 2.** $A^{-1}$ is already known, and there are three right-hand sides. So the best plan is $x_i=A^{-1}b_i$ for $i=1,2,3$. This is only three matrix-times-vector products. The hard part, finding $A^{-1}$, is already done and I can use it again for every $b_i$.

**Case 3.** The inverse is not given and I need only one solution. The best plan is Gaussian elimination on the augmented matrix $[A\mid b]$ and then back substitution. Computing $A^{-1}$ first would be extra work, because I need it for only one right-hand side.

**Answer:** case 1: back substitution, $x=\frac52$, $y=2$; case 2: multiply by the known $A^{-1}$; case 3: Gaussian elimination.

**Check:** for case 1, $2\cdot\frac52-2=3$ and $4\cdot2=8$. Both equations are true.
