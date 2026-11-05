# Exercise 12

**Answer**

$$
A^2=
\begin{pmatrix}
1 & 2 \\
0 & 1 \\
\end{pmatrix},\quad A^3=
\begin{pmatrix}
1 & 3 \\
0 & 1 \\
\end{pmatrix},\quad A^4=
\begin{pmatrix}
1 & 4 \\
0 & 1 \\
\end{pmatrix},\quad A^n=
\begin{pmatrix}
1 & n \\
0 & 1 \\
\end{pmatrix}
$$

**Proof (from $n$ to $n+1$):**

$$
A^nA=
\begin{pmatrix}
1 & n \\
0 & 1 \\
\end{pmatrix}
\begin{pmatrix}
1 & 1 \\
0 & 1 \\
\end{pmatrix}=
\begin{pmatrix}
1 & n+1 \\
0 & 1 \\
\end{pmatrix}=A^{n+1}
$$

**Rule:** mathematical induction: true for $n=1$, and true for $n$ implies true for $n+1$.

**Check:** $n=4$ gives the computed $A^4$.
