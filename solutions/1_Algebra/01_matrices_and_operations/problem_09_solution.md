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

$RSx$ means first $S$, then $R$:

$$
Sx=
\begin{pmatrix}
2 \\
2 \\
\end{pmatrix},\qquad RSx=
\begin{pmatrix}
-2 \\
2 \\
\end{pmatrix}
$$

$SRx$ means first $R$, then $S$:

$$
Rx=
\begin{pmatrix}
-2 \\
1 \\
\end{pmatrix},\qquad SRx=
\begin{pmatrix}
-4 \\
1 \\
\end{pmatrix}
$$

The results are different. $S$ stretches only the horizontal direction. If I rotate first, a different part of the vector is in the horizontal direction, so a different part gets stretched. That is why the order matters.
