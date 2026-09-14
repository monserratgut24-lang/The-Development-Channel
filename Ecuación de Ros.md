# The Development Channel

## Desarrollo de la ecuación del capítulo 3 de Jaime Ros

Partimos de la función de producción Cobb-Douglas:

$$y_t=A_tK_t^{\alpha}L_t^{1-\alpha}$$

donde:

- $y_t$ representa el nivel de producción.
- $A_t$ representa el nivel de productividad.
- $K_t$ representa el stock de capital.
- $L_t$ representa el nivel de empleo.
- $\alpha$ es la participación del capital en la producción.
- $1-\alpha$ es la participación del trabajo.

## 1. Condición de maximización de beneficios

Ros parte de la condición de maximización de beneficios de la empresa. El salario real debe ser igual al producto marginal del trabajo:

$$\frac{w_t}{p_t}=\frac{\partial y_t}{\partial L_t}$$

Derivando la función de producción con respecto al trabajo:

$$\frac{\partial y_t}{\partial L_t}=A_t(1-\alpha)K_t^{\alpha}L_t^{-\alpha}$$

Por lo tanto:

$$\frac{w_t}{p_t}=A_t(1-\alpha)K_t^{\alpha}L_t^{-\alpha}$$

## 2. Despeje del nivel de empleo

Multiplicamos ambos lados por $L_t^{\alpha}$:

$$\left(\frac{w_t}{p_t}\right)L_t^{\alpha}=A_t(1-\alpha)K_t^{\alpha}$$

Despejando $L_t^{\alpha}$:

$$L_t^{\alpha}=\frac{A_t(1-\alpha)}{w_t/p_t}K_t^{\alpha}$$

Elevando ambos lados a la potencia $1/\alpha$:

$$L_t=\left[\frac{A_t(1-\alpha)}{w_t/p_t}\right]^{1/\alpha}K_t$$

Esta es la expresión de demanda de trabajo utilizada por Ros.

## 3. Sustitución en la función de producción

Regresamos a la función de producción:

$$y_t=A_tK_t^{\alpha}L_t^{1-\alpha}$$

Sustituimos la expresión obtenida para $L_t$:

$$y_t=A_tK_t^{\alpha}\left[\left(\frac{A_t(1-\alpha)}{w_t/p_t}\right)^{1/\alpha}K_t\right]^{1-\alpha}$$

## 4. Distribución del exponente

Distribuyendo el exponente $1-\alpha$:

$$y_t=A_tK_t^{\alpha}\left(\frac{A_t(1-\alpha)}{w_t/p_t}\right)^{\frac{1-\alpha}{\alpha}}K_t^{1-\alpha}$$

Los términos correspondientes al capital pueden simplificarse:

$$K_t^{\alpha}K_t^{1-\alpha}=K_t^{\alpha+1-\alpha}=K_t$$

Por lo tanto:

$$y_t=A_t\left(\frac{A_t(1-\alpha)}{w_t/p_t}\right)^{\frac{1-\alpha}{\alpha}}K_t$$

## 5. Simplificación del término de productividad

Separamos $A_t$ dentro de la potencia:

$$y_t=A_tA_t^{\frac{1-\alpha}{\alpha}}\left(\frac{1-\alpha}{w_t/p_t}\right)^{\frac{1-\alpha}{\alpha}}K_t$$

Los exponentes de $A_t$ se suman:

$$1+\frac{1-\alpha}{\alpha}=\frac{\alpha}{\alpha}+\frac{1-\alpha}{\alpha}=\frac{1}{\alpha}$$

Por tanto:

$$A_tA_t^{\frac{1-\alpha}{\alpha}}=A_t^{1/\alpha}$$

Finalmente se obtiene:

$$\boxed{y_t=A_t^{1/\alpha}\left(\frac{1-\alpha}{w_t/p_t}\right)^{\frac{1-\alpha}{\alpha}}K_t}$$

Esta es la expresión a la que llega Ros a partir de la función de producción Cobb-Douglas y de la condición de maximización de beneficios.

## Modelo interactivo

El modelo interactivo correspondiente al capítulo 3 puede consultarse aquí:

[▶ Abrir modelo interactivo](https://monserratgut24-lang.github.io/The-Development-Channel/)

## Referencia

Ros, J. (2015). *Development Macroeconomics in Latin America and Mexico: Essays on Monetary, Exchange Rate, and Fiscal Policies*. Palgrave Macmillan. Capítulo 3.
