# Exercise 3. When Can Matrices Be Multiplied?

## Question

The matrix sizes are

$$
A_{2\times3},\qquad B_{3\times4},\qquad C_{4\times2},\qquad D_{2\times2}.
$$

For the products

$$
AB,\ BA,\ BC,\ CB,\ AC,\ CA,\ AD,\ DA
$$

determine whether they are defined. If so, state the size of the result. Justify each decision using the dimension compatibility condition.

## Solution

A product $XY$ exists only if the number of columns of $X$ is the same as the number of rows of $Y$. The result has the rows of $X$ and the columns of $Y$.

| Product | Sizes | Result |
|---|---|---|
| $AB$ | $(2\times3)(3\times4)$ | $2\times4$ |
| $BA$ | $(3\times4)(2\times3)$ | not defined, $4\neq2$ |
| $BC$ | $(3\times4)(4\times2)$ | $3\times2$ |
| $CB$ | $(4\times2)(3\times4)$ | not defined, $2\neq3$ |
| $AC$ | $(2\times3)(4\times2)$ | not defined, $3\neq4$ |
| $CA$ | $(4\times2)(2\times3)$ | $4\times3$ |
| $AD$ | $(2\times3)(2\times2)$ | not defined, $3\neq2$ |
| $DA$ | $(2\times2)(2\times3)$ | $2\times3$ |
