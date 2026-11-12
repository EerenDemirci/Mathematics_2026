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

$S$ is a diagonal matrix, so its inverse has the reciprocal $\frac1d$ of each diagonal number $d$:

$$
S^{-1}=
\begin{pmatrix}
\frac12 & 0 \\
0 & 2 \\
\end{pmatrix}
$$

In geometry, $S$ makes the $x$ direction 2 times longer and the $y$ direction 2 times shorter. The inverse does the opposite: it makes the $x$ direction 2 times shorter and the $y$ direction 2 times longer. So $S^{-1}$ undoes $S$.

**Answer:** $S^{-1}=\mathrm{diag}\left(\frac12,2\right)$.

**Check:** I take the vector $v=(1,1)^T$:

$$
Sv=
\begin{pmatrix}
2 \\
\frac12 \\
\end{pmatrix},\qquad S^{-1}(Sv)=
\begin{pmatrix}
\frac12\cdot2 \\
2\cdot\frac12 \\
\end{pmatrix}=
\begin{pmatrix}
1 \\
1 \\
\end{pmatrix}=v
$$
