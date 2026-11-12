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

1. The matrix is triangular, so I use back substitution. From $4y=8$ I get $y=2$. Then $2x-2=3$, so $x=\frac52$.
2. $A^{-1}$ is already known, so I just compute $x_i=A^{-1}b_i$ for the three vectors. The inverse is used again for each $b_i$, so the hard part is done only once.
3. For one system without $A^{-1}$, I use Gaussian elimination on $[A\mid b]$. Computing the inverse would be extra work that I do not need.
