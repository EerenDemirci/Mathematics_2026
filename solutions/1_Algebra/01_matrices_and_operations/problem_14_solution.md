# Exercise 14

**Steps**

$$
R(\alpha)R(\beta)=
\begin{pmatrix}
\cos\alpha\cos\beta-\sin\alpha\sin\beta & -(\sin\alpha\cos\beta+\cos\alpha\sin\beta) \\
\sin\alpha\cos\beta+\cos\alpha\sin\beta & \cos\alpha\cos\beta-\sin\alpha\sin\beta \\
\end{pmatrix}
$$

With $\cos(\alpha+\beta)=\cos\alpha\cos\beta-\sin\alpha\sin\beta$ and $\sin(\alpha+\beta)=\sin\alpha\cos\beta+\cos\alpha\sin\beta$:

$$
R(\alpha)R(\beta)=
\begin{pmatrix}
\cos(\alpha+\beta) & -\sin(\alpha+\beta) \\
\sin(\alpha+\beta) & \cos(\alpha+\beta) \\
\end{pmatrix}=R(\alpha+\beta)
$$

**Geometry:** rotating by $\beta$ and then by $\alpha$ is one rotation by $\alpha+\beta$.

**Check:**

$$
R(90^\circ)^2=
\begin{pmatrix}
0 & -1 \\
1 & 0 \\
\end{pmatrix}^2=
\begin{pmatrix}
-1 & 0 \\
0 & -1 \\
\end{pmatrix}=R(180^\circ)
$$
