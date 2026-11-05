# Exercise 6

**Answer**

$$
A^T=
\begin{pmatrix}
1 & 4 \\
2 & 5 \\
3 & 6 \\
\end{pmatrix},\quad B^T=
\begin{pmatrix}
1 & 2 & -1 \\
0 & 1 & 3 \\
\end{pmatrix},\quad AB=
\begin{pmatrix}
2 & 11 \\
8 & 23 \\
\end{pmatrix}
$$

**Steps:** $(AB)_{11}=1+4-3=2$, $(AB)_{12}=0+2+9=11$, $(AB)_{21}=4+10-6=8$, $(AB)_{22}=0+5+18=23$.

$$
(AB)^T=
\begin{pmatrix}
2 & 8 \\
11 & 23 \\
\end{pmatrix},\qquad B^TA^T=
\begin{pmatrix}
1+4-3 & 4+10-6 \\
0+2+9 & 0+5+18 \\
\end{pmatrix}=
\begin{pmatrix}
2 & 8 \\
11 & 23 \\
\end{pmatrix}
$$

**Rule:** transpose swaps rows and columns; $(AB)^T=B^TA^T$ (order reverses).

**Check:** both sides are equal.
