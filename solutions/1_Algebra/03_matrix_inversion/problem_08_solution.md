# Exercise 8. Inverse of a Transformation

## Question

The matrix

$$
S=
\begin{pmatrix}
2 & 0 \\
0 & \frac12 \\
\end{pmatrix}
$$

describes a scaling of the plane. Find $S^{-1}$ and explain geometrically what the inverse transformation does. Check the action of the pair $S,S^{-1}$ on one simple vector.

## Solution

$S$ is diagonal, so I take $1$ divided by each number on the diagonal:

$$
S^{-1}=
\begin{pmatrix}
\frac12 & 0 \\
0 & 2 \\
\end{pmatrix}
$$

$S$ makes the $x$ direction 2 times longer and the $y$ direction 2 times shorter. $S^{-1}$ does the opposite, so it brings the plane back.

Check with $v=(1,1)^T$: $Sv=(2,\frac12)^T$ and $S^{-1}(2,\frac12)^T=(1,1)^T$.
