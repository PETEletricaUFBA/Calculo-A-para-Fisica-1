# Derivadas 
O conceito de derivadas é intimamente associado à taxa de variação de uma dada função num dado ponto. Temos então que a taxa de variação, ou seja, a derivada de uma função **f** em um número qualquer **a**, denotada por **f’(a)**, pode ser expressa matematicamente como:
$$
f'(a)=\lim_{h \to 0} \frac{f(a+h)-f(a)}{h}
$$
## Interpretação geométrica: Reta tangente
![](https://i.imgur.com/FyNC1N8.png) 
Consideremos uma curva C dada pela equação y=f(x). Se desejarmos encontrar a reta tangente a C num ponto P (a,f(a)) muito próximo de Q(x,f(x)), para x≠a, podemos calcular a inclinação da reta secante PQ do seguinte modo:
$$
m=\frac{f\left(x\right)-f\left(a\right)}{x-a}
$$
Daí então, podemos aproximar o ponto Q ao ponto P ao longo da curva, de modo que x→a. Logo, obteremos a reta tangente t desejada, cuja inclinação é m. O limite dessa equação que define a inclinação m aparece em muitas situações nas quais são desejadas calcular a taxa de variação em qualquer ramo das ciências ou engenharia. Portanto, devido à ampla ocorrência desse limite em questão, ele recebe um nome e uma notação diferente, derivada e f’(a), respectivamente.
> #### A reta tangente a y=f(x) em um dado ponto P é a reta que passa nesse ponto P, cuja inclinação é igual a f’(a), a derivada de f em a.

## Regras de Derivação
* **Funções Constantes:** Seja a função constante f(x)=c. Essa função é graficamente descrita por uma reta horizontal e, portanto, sua inclinação é 0. Logo,
$$
f'(x)= \frac{d}{dx}(c)=0.
$$ 
> #### Observe que para n=1, gráfico de f(x)= x corresponde a reta y=x, cuja inclinação é 1.
* **Funções Potências:** Sejam as funções do tipo
$$ 
f(x)=x^n,
$$ para todo n inteiro e positivo. Então, a derivada dessas funções é dada por
$$
f'(x)= \frac{d}{dx}(x^{n})=nx^{n-1}.
$$  
* **Derivadas de funções a partir da derivada de funções conhecidas:** 
   * **A partir da multiplicação por uma constante:** Seja f uma função derivável conhecida e c uma dada constante. Logo,  
   $$
   \frac{d}{dx}[cf(x)]=c\frac{d}{dx}f(x).
   $$
   * **A partir da soma de duas funções - Regra da Soma:** Sejam as funções f e g conhecidas e deriváveis. Para uma função p, que seja a soma de f e g, temos: 
   $$
   p'(x)= \frac{d}{dx}[f(x)+g(x)]=\frac{d}{dx}f(x)+\frac{d}{dx}g(x).
   $$
   * **A partir da subtração de duas funções - Regra da Subtração:** Sejam as funções f e g conhecidas e deriváveis. Para uma função p, que seja a subtração de f por g, temos: 
   $$
   p'(x)= \frac{d}{dx}[f(x)-g(x)]=\frac{d}{dx}f(x)-\frac{d}{dx}g(x).
   $$
   * **A partir do produto de duas funções - Regra do Produto:** Sejam as funções f e g deriváveis, temos que se p é o produto de f e g: 
   $$
   p'(x)= \frac{d}{dx}[f(x).g(x)]=g(x)\frac{d}{dx}f(x)+f(x)\frac{d}{dx}g(x).
$$
   * **A partir do quociente de duas funções - Regra do Quociente:** Sejam duas funções conhecidas e deriváveis f e g. Para p(x)=f(x)/g(x), temos: 
   $$
   p'(x)= \frac{d}{dx}\frac{f(x)}{g(x)}=\frac{g(x).\frac{d}{dx}f(x)-f(x).\frac{d}{dx}g(x)}{[g(x)]^2}.
   $$ 
* **Funções exponenciais:** Seja a função exponencial $$f(x)= \mathrm{a}^\mathrm{x} .$$ A derivada da função f(x) é tal que: 
$$
f'(x)= \frac{d}{dx}(a^x)=a^x\ln a.
$$
   * **Função exponencial natural:**  Seja a função exponencial $$f(x)= \mathrm{e}^\mathrm{x}  .$$ A derivada f’(x) é dada da seguinte maneira: 
   $$
   f'(x)= \frac{d}{dx}(e^x)=e^x .
   $$
* **Funções Logarítmicas:** Consideremos a função logarítmica 
$$
f(x)={\mathrm{log}}_\mathrm{a}{\mathrm{x}}. 
$$ A derivada dessa função é dada por: 
$$
f'(x)= \frac{d}{dx}(\ log _ {a}  x)=\frac{1}{x.\ln a}.
$$
   * **Função Logarítmica Natural:** Para a função logarítmica natural 
   $$
   f(x)=\ln x,  
   $$a derivada é dada como se segue: 
   $$
   f'(x)=\frac{d}{dx}(\ln x)=\frac{1}{x}.
   $$
* **Funções Compostas - Regra da Cadeia:** Consideremos duas funções f e g e que a função g é derivável em x. Então, a função composta F=f(g(x)) é derivável em x e sua derivada é dada do seguinte modo:
$$
F'(x)=f'(g(x)).g'(x).
$$