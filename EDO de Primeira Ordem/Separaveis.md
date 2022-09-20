# Solução de EDO's de Primeira Ordem Separáveis
Uma EDO é chamada de separável se tem a seguinte forma

$$
\frac{dy}{dt} = \frac{M'(t)}{N'(y)}
\Rightarrow
M'(t)dt - N'(y)dy = 0
\Rightarrow
M'(t) - N'(y)\frac{dy}{dt} = 0
$$

Pois, integrando dos dois lados, tem-se que

$$
\int\left( M'(t) - N'(y)\frac{dy}{dt} \right) dt = 0 
\Rightarrow
H_1(t)-H_2(y) = C
$$

A solução é dada de forma implícita por

$$
H_1(x) + H_2(y) = 0
$$

Em que

$$
\begin{cases}
\displaystyle \int M(t)dt = H_1(t)\\
\displaystyle \int N(y)dy = H_2(y)\\
\end{cases}
$$


