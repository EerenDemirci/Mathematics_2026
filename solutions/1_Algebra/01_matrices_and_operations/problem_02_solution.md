# Exercise 2. Addition and Scalar Multiplication

## Question

For

$$
A=
\begin{pmatrix}
1 & 2 \\
-1 & 3 \\
\end{pmatrix},\qquad B=
\begin{pmatrix}
4 & -2 \\
0 & 5 \\
\end{pmatrix}
$$

compute

$$
A+B,\qquad A-B,\qquad 3A-2B.
$$

Explain why matrix addition is possible only for matrices of the same size.

## Solution

I add and subtract number by number:

$$
A+B=
\begin{pmatrix}
5 & 0 \\
-1 & 8 \\
\end{pmatrix},\qquad A-B=
\begin{pmatrix}
-3 & 4 \\
-1 & -2 \\
\end{pmatrix}
$$

For $3A-2B$ I first multiply all numbers of $A$ by 3 and all numbers of $B$ by 2, and then I subtract:

$$
3A-2B=
\begin{pmatrix}
3-8 & 6+4 \\
-3-0 & 9-10 \\
\end{pmatrix}=
\begin{pmatrix}
-5 & 10 \\
-3 & -1 \\
\end{pmatrix}
$$

Addition is possible only for matrices of the same size, because every number in $A$ needs a number in the same place in $B$.
