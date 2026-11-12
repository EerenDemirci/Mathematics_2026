# Exercise 9. Composing Transformations

## Question

Let

$$
S=
\begin{pmatrix}
2 & 0 \\
0 & 1 \\
\end{pmatrix},\qquad R=
\begin{pmatrix}
0 & -1 \\
1 & 0 \\
\end{pmatrix}.
$$

The matrix $S$ describes nonuniform scaling, while $R$ describes a $90^\circ$ counterclockwise rotation.
For

$$
x=
\begin{pmatrix}
1 \\
2 \\
\end{pmatrix}
$$

compute $RSx$ and $SRx$. Compare the results and explain geometrically why the order of these transformations matters.

## Solution

$RSx$ means: first I use $S$, then I use $R$. I work from right to left:

$$
Sx=
\begin{pmatrix}
2 \\
2 \\
\end{pmatrix},\qquad RSx=R
\begin{pmatrix}
2 \\
2 \\
\end{pmatrix}=
\begin{pmatrix}
-2 \\
2 \\
\end{pmatrix}
$$

$SRx$ means: first $R$, then $S$:

$$
Rx=
\begin{pmatrix}
-2 \\
1 \\
\end{pmatrix},\qquad SRx=S
\begin{pmatrix}
-2 \\
1 \\
\end{pmatrix}=
\begin{pmatrix}
-4 \\
1 \\
\end{pmatrix}
$$

The results are different. $S$ makes only the horizontal part two times longer. In $RSx$ it stretches the first part of $x$. In $SRx$ the vector is rotated first, so the second part of $x$ moves to the horizontal direction and this part is stretched. That is why the order matters.

**Answer:** $RSx=(-2,2)^T$ and $SRx=(-4,1)^T$, so $RSx\neq SRx$.

**Check:** the lengths are different too: $|RSx|=\sqrt8$ and $|SRx|=\sqrt{17}$.
