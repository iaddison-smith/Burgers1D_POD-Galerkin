# POD-Galerking reduced order method for 1D Burgers Equation

$$
\frac{\partial u}{\partial t} + u \frac{\partial u}{\partial x} = \nu\frac{\partial^2 u}{\partial x^2}
$$

$$
\frac{\partial a_k}{\partial t}  = \nu \sum_{j=1}^{r} \alpha_{jk} a_j - \sum_{i=1}^{r}  \sum_{j=1}^{r} \beta_{ijk} a_ia_j - \sum_{j=1}^{r} \bar{\alpha}_{jk} a_j
$$


$$
\alpha_{jk} = \langle \frac{\partial^2 \phi_j}{\partial x^2}, \phi_k \rangle \\
\bar{\alpha}_{jk} = \langle \bar{u} \frac{\partial \phi_j}{\partial x}(x) + \frac{\partial \bar{u}}{\partial x} \phi_{j}(x) , \phi_k \rangle \\
\beta_{ijk} = \langle \phi_i \frac{\partial \phi_j}{\partial x}, \phi_k  \rangle 
$$
