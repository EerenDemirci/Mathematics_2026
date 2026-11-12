# Exercise 14. Rotation Matrices

## Question

The matrix for a rotation through an angle $\theta$ is

$$
R(\theta)=
\begin{pmatrix}
\cos\theta & -\sin\theta \\
\sin\theta & \cos\theta \\
\end{pmatrix}.
$$

Compute $R(\alpha)R(\beta)$ and, using the angle-sum formulas for sine and cosine, show that

$$
R(\alpha)R(\beta)=R(\alpha+\beta).
$$

Explain the result geometrically.

## Solution

I multiply the two rotation matrices, row times column:

$$
R(\alpha)R(\beta)=
\begin{pmatrix}
\cos\alpha\cos\beta-\sin\alpha\sin\beta & -(\sin\alpha\cos\beta+\cos\alpha\sin\beta) \\
\sin\alpha\cos\beta+\cos\alpha\sin\beta & \cos\alpha\cos\beta-\sin\alpha\sin\beta \\
\end{pmatrix}
$$

Now I use the angle-sum formulas:

$$
\cos(\alpha+\beta)=\cos\alpha\cos\beta-\sin\alpha\sin\beta,\qquad \sin(\alpha+\beta)=\sin\alpha\cos\beta+\cos\alpha\sin\beta
$$

When I put them into the matrix, I get the rotation matrix for the angle $\alpha+\beta$:

$$
R(\alpha)R(\beta)=
\begin{pmatrix}
\cos(\alpha+\beta) & -\sin(\alpha+\beta) \\
\sin(\alpha+\beta) & \cos(\alpha+\beta) \\
\end{pmatrix}=R(\alpha+\beta)
$$

In geometry this means: if I rotate by $\beta$ and then by $\alpha$, it is the same as one rotation by $\alpha+\beta$.

**Answer:** $R(\alpha)R(\beta)=R(\alpha+\beta)$.

**Check:** two rotations by $90^\circ$ must give a rotation by $180^\circ$:

$$
R(90^\circ)^2=
\begin{pmatrix}
0 & -1 \\
1 & 0 \\
\end{pmatrix}
\begin{pmatrix}
0 & -1 \\
1 & 0 \\
\end{pmatrix}=
\begin{pmatrix}
-1 & 0 \\
0 & -1 \\
\end{pmatrix}=R(180^\circ)
$$
