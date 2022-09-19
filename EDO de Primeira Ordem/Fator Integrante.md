# Solução de EDO's de Primeira Ordem pelo Método do Fator Integrante

Se a EDO tem a forma

$$
y' + f(t)y = g(t)
$$

Então pode ser resolvida pelo método dos fator integrante. Esse método consiste em multiplicar a equação por uma função $\mu(x)$, tal que, o lado esquedo da equação se torne a derivada de um produto de duas funções.

### Demonstração
Seja $f$ e $g$ funcões dadas, e $\mu$ uma função conveniente. Então

$$
y' + f(t)y = g(t)
\Rightarrow
\mu(t)y' + \mu(t)f(t)y = \mu(t)g(t)
$$

Para que $\mu(t)y' + \mu(t)f(t)y$ seja a deriviada de um produto, é necessário que

$$
\mu'(t) = \mu(t)f(t)
$$

Supondo que $\mu(t)> 0$ e interando dos dois lados

$$
\frac{\mu'(t)}{\mu(t)} = f(t)
\Rightarrow
\int\frac{\mu'(t)}{\mu(t)}dt = \int f(t)dt
\Rightarrow
\ln(|\mu(t)|) = \int f(t)dt
\Rightarrow
\mu(t) = \exp\left(\int f(t)dt\right)
\blacksquare
$$