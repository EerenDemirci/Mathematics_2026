# Exercise 3

**Rule:** $X_{m\times n}Y_{p\times q}$ is defined only if $n=p$; the result is $m\times q$.

| Product | Defined? | Size |
|---|---|---|
| $AB$ | yes ($3=3$) | $2\times4$ |
| $BA$ | no ($4\neq2$) | — |
| $BC$ | yes ($4=4$) | $3\times2$ |
| $CB$ | no ($2\neq3$) | — |
| $AC$ | no ($3\neq4$) | — |
| $CA$ | yes ($2=2$) | $4\times3$ |
| $AD$ | no ($3\neq2$) | — |
| $DA$ | yes ($2=2$) | $2\times3$ |

**Check:** a row of the left matrix must have as many numbers as a column of the right matrix.
