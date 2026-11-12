# Exercise 13. Undoing a Composite Transformation

## Question

The matrices

$$
S=
\begin{pmatrix}
2 & 0 \\
0 & 1 \\
\end{pmatrix},\qquad H=
\begin{pmatrix}
1 & 1 \\
0 & 1 \\
\end{pmatrix}
$$

describe nonuniform scaling and shear. For $T=HS$, find $T^{-1}$ in two ways:

1. first compute $T$, then its inverse,
2. use $(HS)^{-1}=S^{-1}H^{-1}$.

Compare the results. Additionally compute $H^{-1}S^{-1}$ and verify that the incorrect order gives a different matrix. Explain the rule: “when undoing a composition of operations, we undo them from the end.”

## Solution

**Way 1.** First I compute $T=HS$, then I use the $2\times2$ formula ($\det T=2$):

$$
T=HS=
\begin{pmatrix}
2 & 1 \\
0 & 1 \\
\end{pmatrix},\qquad T^{-1}=\frac12
\begin{pmatrix}
1 & -1 \\
0 & 2 \\
\end{pmatrix}=
\begin{pmatrix}
\frac12 & -\frac12 \\
0 & 1 \\
\end{pmatrix}
$$

**Way 2.** I find $S^{-1}$ and $H^{-1}$ and use $(HS)^{-1}=S^{-1}H^{-1}$:

$$
S^{-1}=
\begin{pmatrix}
\frac12 & 0 \\
0 & 1 \\
\end{pmatrix},\qquad H^{-1}=
\begin{pmatrix}
1 & -1 \\
0 & 1 \\
\end{pmatrix},\qquad S^{-1}H^{-1}=
\begin{pmatrix}
\frac12 & -\frac12 \\
0 & 1 \\
\end{pmatrix}
$$

Both ways give the same matrix.

**Wrong order.** If I multiply in the other order, I get a different matrix:

$$
H^{-1}S^{-1}=
\begin{pmatrix}
\frac12 & -1 \\
0 & 1 \\
\end{pmatrix}\neq T^{-1}
$$

$T=HS$ means: first scaling $S$, then shear $H$. To undo it, I must first undo the last operation $H$, and then undo $S$. So we undo operations from the end.

**Answer:** $T^{-1}=S^{-1}H^{-1}$ is the matrix above; $H^{-1}S^{-1}$ is different.

**Check:** $TT^{-1}$ has entries $2\cdot\frac12=1$, $2\cdot(-\frac12)+1=0$, $0$ and $1$, so $TT^{-1}=I$.
