# Modelo de Jaime Ros — Capítulo 3

## Desarrollo de la ecuación

A partir de la función de producción Cobb-Douglas:

$$
y_t=A_tK_t^\alpha L_t^{1-\alpha}
$$

La condición de maximización de beneficios implica que el
salario real es igual al producto marginal del trabajo:

$$
\frac{w_t}{p_t}
=
A_t(1-\alpha)K_t^\alpha L_t^{-\alpha}
$$

Despejando el nivel de empleo:

$$
L_t=
\left[
\frac{A_t(1-\alpha)}
{w_t/p_t}
\right]^{1/\alpha}K_t
$$

Sustituyendo esta expresión en la función de producción:

$$
y_t=
A_tK_t^\alpha
\left[
\left(
\frac{A_t(1-\alpha)}
{w_t/p_t}
\right)^{1/\alpha}
K_t
\right]^{1-\alpha}
$$

Distribuyendo el exponente:

$$
y_t=
A_tK_t^\alpha
\left(
\frac{A_t(1-\alpha)}
{w_t/p_t}
\right)^{\frac{1-\alpha}{\alpha}}
K_t^{1-\alpha}
$$

Como:

$$
K_t^\alpha K_t^{1-\alpha}=K_t
$$

se obtiene:

$$
y_t=
A_t
A_t^{\frac{1-\alpha}{\alpha}}
\left(
\frac{1-\alpha}
{w_t/p_t}
\right)^{\frac{1-\alpha}{\alpha}}
K_t
$$

Finalmente:

$$
1+\frac{1-\alpha}{\alpha}
=
\frac{1}{\alpha}
$$

por lo que:

$$
\boxed{
y_t=
A_t^{1/\alpha}
\left(
\frac{1-\alpha}{w_t/p_t}
\right)^{\frac{1-\alpha}{\alpha}}
K_t
}
$$

## Fuente

Ros, J. (2015). *Development Macroeconomics in Latin America
and Mexico: Essays on Monetary, Exchange Rate, and Fiscal
Policies*. Palgrave Macmillan. Capítulo 3.

