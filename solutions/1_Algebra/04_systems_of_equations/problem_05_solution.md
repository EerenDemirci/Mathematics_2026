# Exercise 5. Row Echelon Form and Number of Solutions

## Question

For the augmented matrix

$$
\begin{pmatrix}
1 & 2 & -1 & \mid & 3 \\
0 & 1 & 2 & \mid & 1 \\
0 & 0 & 0 & \mid & 0 \\
\end{pmatrix}
$$

determine the number of solutions and write them in parametric form. Explain how you know how many variables may be chosen freely.

## Solution

The last row is $0=0$, so there is no contradiction. There are 3 unknowns and only 2 pivots, so 1 variable is free and there are infinitely many solutions.

I take $x_3=t$. The second row gives $x_2=1-2t$. The first row gives $x_1=3-2(1-2t)+t=1+5t$:

$$
x_1=1+5t,\qquad x_2=1-2t,\qquad x_3=t
$$

The number of free variables is the number of unknowns minus the number of pivots: $3-2=1$.
