# Integral

Na matematica integral é o processo de associar funções de modo a descrever sua area, volume e outros conceitos que surgem a partir de combinações infinitesimais.

A notação mais comum usada para descrever a integral de uma função $f(x)$ ao do intervalo $a$ e $b$ é:

$I = \int _{a}^{b}f(x)\,dx$

## Integral definida e indefinida

A integral definida é a integral de um intervalo definido da função, calculando no caso de uma curva num plano a area da curva no intervalo, nesse caso temos tanto os valores de $a$ e $b$ da notação anterior bem definidos.

A integral indefinida é o processo de integração de um intervalo indefinido da curva, em geral resultando numa função que é a antiderivativa da função, nesse caso a integração pode ir de um valor $a$ a uma variavel $x$, $F(x) = \int _{a}^{x}f(t)\,dt$

### Teorema Fundamental do calculo

O teorema fundamental do calculo, relaciona as duas operações de integração e derivação como sendo inversas, ou seja, se uma função continua é integrada e em seguida derivada temos novamenta a função, tal que:

$F(x)=\int _{a}^{x}f(t)\,dt$

e

$\frac{\mathrm{d} F(x)}{\mathrm{d} x} = F'(x)=f(x)$

e por consequente temos o que é chamado de segundo teorema fundamental do calculo,

$f(x)=F'(x) = \frac{\mathrm{d} F(x)}{\mathrm{d} x}$

e

$\int _{a}^{b}f(x)\,dx=F(b)-F(a)$

## Propriedades da integração

|Propriedade| descrição|
|-----|----|
| Somas | $ \int _{a}^{b}f(x) + g(x)\,dx = \int_{a}^{b}f(x)\,dx + \int _{a}^{b}g(x)\,dx$ |
| Subtração | $ \int _{a}^{b}f(x) - g(x)\,dx = \int_{a}^{b}f(x)\,dx - \int _{a}^{b}g(x)\,dx$ |
| Multiplicação por uma constante | $ \int _{a}^{b} k * f(x)\,dx = k \int_{a}^{b}f(x)\,dx$ |
| Inverso do intervalo | $ \int _{a}^{b} f(x)\,dx = -\int_{b}^{a}f(x)\,dx$ |
| Intervalo de tamanho 0 | $ \int _{a}^{a} f(x)\,dx = 0$ |
| Soma de intervalos  | $ \int_{a}^{c}f(x)\,dx + \int_{c}^{b}f(x)\,dx = \int_{a}^{b}f(x)\,dx$ |

## Regras de integração

|Regra| Função| Integral|
|-----|----|----|
|Constante|$\int _{}^{}k\,dx$|$kx + c$|
|Variavel|$\int _{}^{}x\,dx$|$\frac{x^{2}}{2} + c$|
|Regra da Potencia|$\int _{}^{}x^{n}\,dx$|$\frac{x^{n+1}}{n+1} + c$|
|Reciprocal|$\int _{}^{}\frac{1}{x}\,dx$|$ln\left \|x  \right \|+ c$|
|Exponencial|$\int _{}^{}e^{x}dx$|$e^{x} + c$|
||$\int _{}^{}a^{x}dx$|$\frac{a^{x}}{ln(a)} + c$|
||$\int _{}^{}ln(x)dx$|$xln(x) - x + c$|
|Trigonometry|$\int _{}^{}cos(x)dx$|$sin(x) + c$|
||$\int _{}^{}sin(x)dx$|$-cos(x) + c$|
||$\int _{}^{}sec^{2}(x)dx$|$tan(x) + c$|

## Integral por partes

No calculo integração por partes é o processo de encontrar a integral de um produto de funções através de da integral do produto de suas derivadas, sendo realizada através da operação inversa a regra dos produtos, ${\dfrac {d}{dx}}(u(x)\cdot v(x))={\dfrac {du(x)}{dx}}\cdot v(x)+u(x)\cdot {\dfrac {dv(x)}{dx}}$, onde temos:

$\int _{a}^{b}u(x)v'(x)\,dx=u(b)v(b)-u(a)v(a)-\int_{a}^{b}u'(x)v(x)\,dx$
