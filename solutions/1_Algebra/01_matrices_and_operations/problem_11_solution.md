# Exercise 11. When Do Matrices Commute?

## Question

Given

$$
A=
\begin{pmatrix}
1 & 1 \\
0 & 1 \\
\end{pmatrix},\qquad B=
\begin{pmatrix}
a & b \\
c & d \\
\end{pmatrix}.
$$

Find the conditions on $a,b,c,d$ under which $AB=BA$. Describe the general form of all such matrices $B$.

## Solution

I compute both products with the unknown matrix $B$:

$$
AB=
\begin{pmatrix}
a+c & b+d \\
c & d \\
\end{pmatrix},\qquad BA=
\begin{pmatrix}
a & a+b \\
c & c+d \\
\end{pmatrix}
$$

$AB=BA$ means that all entries are equal. From the first entry, $a+c=a$, so $c=0$. From the second entry, $b+d=a+b$, so $d=a$. The last entry gives $d=c+d$, so again $c=0$. The number $b$ can be any number.

So the matrix $B$ must look like this:

$$
B=
\begin{pmatrix}
a & b \\
0 & a \\
\end{pmatrix},\qquad a,b\in\mathbb{R}
$$

**Answer:** $AB=BA$ exactly when $c=0$ and $d=a$.

**Check:** I take $a=2$ and $b=3$. Then both products give the same matrix:

$$
AB=BA=
\begin{pmatrix}
2 & 5 \\
0 & 2 \\
\end{pmatrix}
$$
