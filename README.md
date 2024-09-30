# POD-Galerkin reduced order method for 1D Burgers Equation

$$
\frac{\partial u}{\partial t} + u \frac{\partial u}{\partial x} = \nu\frac{\partial^2 u}{\partial x^2}
$$

$$
\frac{\partial a_k}{\partial t}  = \nu \sum_{j=1}^{r} \alpha_{jk} a_j - \sum_{i=1}^{r}  \sum_{j=1}^{r} \beta_{ijk} a_ia_j - \sum_{j=1}^{r} \bar{\alpha}_{jk} a_j
$$

