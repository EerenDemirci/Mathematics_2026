# Exercise 13

**Answer**

$$
F^2=
\begin{pmatrix}
2 & 1 \\
1 & 1 \\
\end{pmatrix},\quad F^3=
\begin{pmatrix}
3 & 2 \\
2 & 1 \\
\end{pmatrix},\quad F^4=
\begin{pmatrix}
5 & 3 \\
3 & 2 \\
\end{pmatrix},\quad F^5=
\begin{pmatrix}
8 & 5 \\
5 & 3 \\
\end{pmatrix}
$$

**Relationship:** the entries are Fibonacci numbers $0,1,1,2,3,5,8,\ldots$; $F^n$ contains three consecutive terms.

**One step:**

$$
F
\begin{pmatrix}
a \\
b \\
\end{pmatrix}=
\begin{pmatrix}
a+b \\
a \\
\end{pmatrix}
$$

The first entry is the sum (the next term), the second entry keeps $a$ for the next step.

**Check:** $\det F^5=8\cdot3-5\cdot5=-1=(\det F)^5$.
