# Exercise 14. A Matrix That Is Its Own Inverse

## Question

Assume that a square matrix $A$ satisfies

$$
A^2=I.
$$

Show that

$$
A^{-1}=A.
$$

Then give an example of a $2\times2$ matrix different from $I$ and $-I$ that satisfies this condition, and verify it by multiplication.

## Solution

The inverse of $A$ is the matrix that gives $I$ when we multiply it with $A$ from both sides. We know $A^2=I$, which means:

$$
A\cdot A=I
$$

So the matrix $A$ itself has this property. By the definition of the inverse, $A^{-1}=A$.

Example: the matrix that swaps the two coordinates:

$$
A=
\begin{pmatrix}
0 & 1 \\
1 & 0 \\
\end{pmatrix}
$$

It is not $I$ and not $-I$. If we swap the coordinates two times, we get back to the start.

**Answer:** $A^2=I$ means $A\cdot A=I$, so $A^{-1}=A$. Example: the swap matrix above.

**Check:**

$$
A^2=
\begin{pmatrix}
0\cdot0+1\cdot1 & 0\cdot1+1\cdot0 \\
1\cdot0+0\cdot1 & 1\cdot1+0\cdot0 \\
\end{pmatrix}=
\begin{pmatrix}
1 & 0 \\
0 & 1 \\
\end{pmatrix}=I
$$
