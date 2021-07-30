# Funções e Limites

## Funções

Função é a relação binária entre dois conjuntos onde cada elemento do primeiro conjunto é associado a um elemento do segundo conjunto.  

_Desta forma, podemos pensar uma função como uma receita de bolo, onde os ingrediente como a farinha de trigo, os ovos e o açúcar correspondem aos valores de $x$, a receita ou modo de preparo seria a função $f(x)$ em si, e o bolo já pronto seria o elemento final, ou resultado da função. Assim, podemos pensar que _$f$(farinha,ovo,açúcar) = bolo_ onde $f$ é a receita do bolo._

<img src="../img/Function_machine2.svg"
     alt="Função maquina"
     style="float: left; margin-right: 10px;"
     />

Então basicamente funções pegam elementos do primeiro conjunto, normalmente chamado de domínio, e retornam elementos que pertencem ao segundo conjunto, chamado de contradomínio, e esses elementos que pertecem ao contradomínio e retornaram da função são chamados de imagem.

Dentre as notações mais usadas para funções temos a associação $y = f(x)$ onde lemos $y$ é igual a função de $x$, representando que o par $(x,y)$ representam os conjuntos de pares que definem a função $f$. E para X sendo o domínio da função temos
$\{(x,f(x))\mid x\in X\}$.

### Funções de primeiro e segundo grau

#### Funções de Primeiro Grau (Função Linear)

Funções Lineares são as funções em que o grafico em coordenadas cartesianas pode ser expresso através de uma linha. Descrita através da função polinomial $f(x)=ax+b$. Sendo considerada de primeira grau pois o $x$ está elevado a primeira potencia. P.S. $x^1 = x$.  

_Por exemplo, um carro com velocidade de $4m/s$ que precisa parar em uma sinaleira e mantém desaceleração constante de $2m/s^2$, tem sua velocidade $v$ representada por $v = 4 - 2t$, sendo $t$ o tempo decorrido em segundos. Logo, sabemos que a velocidade é uma função linear do tempo nesse caso._  

<img src="../img/Wiki_linearna_funkcija_eks1.png"
     alt="Função Linear"
     style="margin-right: 10px;"
     />

Na imagem acima temos o exemplo da função linear $y(x)=-2x+4$, onde podemos ver no gráfico que cada ponto da reta está posicionado de modo a ter um par de valores $(x,y)$, descrito pela função, comos os pontos $(0,4)$ e $(2,0)$.

#### Funções de Segundo Grau (Função quadrática)

Funções Quadraticas são as funções que possuem a sua variável de maior grau no segundo Grau, tal como a função polimonial, $f(x)=ax^{2}+bx+c,\quad a\neq 0$ que possuem apenas uma variável, e é representada graficamente através de uma parabola como no exemplo a seguir da função $f(x)=2x^{2}-x-2$.

<img src="../img/Tschirnhausen cubic.svg"
     alt="Parabola"
     style="margin-right: 10px;"
     />

_Fazendo um paralelo com o caso anterior, poderíamos querer representar o espaço $S$ percorrido em função do tempo, ao invés da velocidade. Por exemplo, para saber quantos metros o carro percorreu antes de parar. Para isso, sabemos que $S = So + Vo*t+{\frac {at^2}{2}}$, então $S = 4t - t^2$, já que $So = 0$, $Vo = 4$ e $a = -2$ como se trata de uma desaceleração. Então, sabemos que a posição varia quadráticamente com o tempo nesse caso._

### Domínio, Imagem e continuidade

Como mencionado anteriormente, o domínio de uma função é o conjunto de entradas na função, nos exemplos anteriores são os valores que podemos substituir o $x$ e a imagem da função é justamente o conjunto de saídas, sendo nos exemplos anteriores os valores que encontramos para o $y$ ao substituir o $x$ na função.

<img src="../img/250px-Codomain2.SVG.png"
     alt="dominio codominio e imagem."
     style="margin-right: 10px;"
/>

Na imagem acima, a área vermelha $X$ representa o dominio, enquanto a amarela $Y$ representa a imagem. Para funções de uma variável, cada membro do domínio estará assocaido a exatamente um membro da imagem. O elemento da imagem pode estar associado a um ou mais membros do domínio.

#### Funções Contínuas

Funções contínuas são aquelas que não possuem mudanças bruscas de valor, vulgo descontinuidades. Sendo preciso, a função é contínua quando uma pequena mudança na saída da função pode ser assegurada através da pequena mudança de sua entrada. Uma forma interessante de visualizar a função contínua é se você consegue desenhar sua função sem precisar tirar a caneta do papel em nenhum momento.

### Tipos de funções

#### Funções polinomiais

São funções que evaluem polinomios. Uma função $f$ será polinomial se dado o domínio ela possa ser expressa através da expressão ${\displaystyle a_{n}x^{n}+a_{n-1}x^{n-1}+\cdots +a_{2}x^{2}+a_{1}x+a_{0}}$, como são os casos das funções de primeiro e segundo grau.

#### Funções Fracionárias

São funções que podem ser presentadas através da fração de duas outras funções, $f(x)={\frac {P(x)}{Q(x)}}$, como o exemplo a seguir, $f(x)={\frac {x^{3}-2x}{2(x^{2}-5)}}$ onde $P(x) = x ^{3} - 2x$ e $Q(x) = 2(x^{2}-5)$ o qual racionando a função $f(x)$ representada pelo grafico abaixo

<img src="../img/300px-RationalDegree3.svg.png"
     alt="dominio codominio e imagem."
     style="margin-right: 10px;"
/>

#### Funções Exponenciais

Funções exponenciais são funções que podem ser expressas através da forma, ${f(x)=ab^{x},}$, como o exemplo da função exponencial $f(x) = e^{x}$.

<img src="../img/Exp.svg"
     alt="dominio codominio e imagem."
     style="margin-right: 10px;"
/>

## Limites
