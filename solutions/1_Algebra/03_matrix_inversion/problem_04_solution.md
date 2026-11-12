# Exercise 4. Gauss–Jordan

## Question

Find $A^{-1}$ using the Gauss–Jordan method for

$$
A=
\begin{pmatrix}
1 & 2 \\
3 & 5 \\
\end{pmatrix}.
$$

Show the augmented matrix $[A\mid I]$ after successive operations and explain why obtaining $I$ on the left gives the inverse on the right.

## Solution

I write the augmented matrix $[A\mid I]$ and use row operations until the left side is $I$:

$$
\begin{pmatrix}
1 & 2 & \mid & 1 & 0 \\
3 & 5 & \mid & 0 & 1 \\
\end{pmatrix}
$$

$R_2\leftarrow R_2-3R_1$:

$$
\begin{pmatrix}
1 & 2 & \mid & 1 & 0 \\
0 & -1 & \mid & -3 & 1 \\
\end{pmatrix}
$$

$R_2\leftarrow -R_2$:

$$
\begin{pmatrix}
1 & 2 & \mid & 1 & 0 \\
0 & 1 & \mid & 3 & -1 \\
\end{pmatrix}
$$

$R_1\leftarrow R_1-2R_2$:

$$
\begin{pmatrix}
1 & 0 & \mid & -5 & 2 \\
0 & 1 & \mid & 3 & -1 \\
\end{pmatrix}
$$

Now the left side is $I$, so the right side is $A^{-1}$.

Why does this work? Every row operation is the same as multiplying from the left by some matrix. All operations together are one matrix $E$. On the left side we get $EA=I$, so $E=A^{-1}$. On the right side the same operations give $EI=E=A^{-1}$.

**Answer:**

$$
A^{-1}=
\begin{pmatrix}
-5 & 2 \\
3 & -1 \\
\end{pmatrix}
$$

**Check:** $AA^{-1}$ has entries $1\cdot(-5)+2\cdot3=1$, $1\cdot2+2\cdot(-1)=0$, $3\cdot(-5)+5\cdot3=0$, $3\cdot2+5\cdot(-1)=1$, so $AA^{-1}=I$.
