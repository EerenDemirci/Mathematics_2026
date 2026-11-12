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

I compare the numbers. From $a+c=a$ I get $c=0$. From $b+d=a+b$ I get $d=a$. The number $b$ can be anything.

So $AB=BA$ only for matrices of this form:

$$
B=
\begin{pmatrix}
a & b \\
0 & a \\
\end{pmatrix}
$$
