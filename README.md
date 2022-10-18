# Estrutura-de-Dados-e-Algoritmos


## Análise Assintótica
```
Análise assintótica leva em consideração grandes entradas para tornar relevante apenas a ordem de crescimento das 
funções de tempo de execução. Na prática, ignoramos as constantes e os expoentes de menor magnitude. Usamos análise
assintótica para simplificar a comparação entre funções
```
## Selection Sort / Ordenação por Seleção
```
A ordenação  por seleção  (do inglês, selection sort) é  um algoritmo de ordenação baseado em se passar sempre
o menor valor do vetor para a primeira posição (ou o maior dependendo da ordem requerida), depois o de segundo
menor  valor para  a segunda  posição, e  assim é feito  sucessivamente com os n-1 elementos restantes, até os
últimos dois elementos.
```
![Selection Sort](https://github.com/lramon2001/Algoritmos/blob/main/Selection-Sort-Animation.gif)
## Merge Sort / Ordenação por Junção
``` Merge Sort é um algoritmo eficiente de ordenação por divisão e conquista. Se nossa missão é ordenar um array
comparando seus elementos, do ponto de vista assintótico, n∗logn é o nosso limite inferior. Ou seja, nenhum algoritmo
de ordenação por comparação é mais veloz do que n∗logn. Formalmente, todos são Ω(n∗logn).
No caso do Merge Sort, uma característica importante é que sua eficiência é n∗logn para o melhor, pior e para o caso médio.
Ou seja, ele não é somente Ω(n∗logn), mas é Θ(n∗logn). Isso nos dá uma garantia de que, independente da disposição dos dados
em um array, a ordenação será eficiente.
O funcionamento do Merge Sort baseia-se em uma rotina fundamental cujo nome é merge. Primeiro vamos entender como ele funciona e depois vamos ver como sucessivas execuções de merge ordena um array.
```
## Quick Sort / Ordenação rápida

```
Quick Sort é um algoritmo eficiente de ordenação por divisão e conquista. Apesar de ser da mesma classe de complexidade do Merge Sort e do Heap Sort, o Quick Sort é na prática o mais veloz deles, pois suas constantes são menores. Contudo, é importante destacar de antemão que, em seu pior caso, o Quick Sort é O(n2), enquanto que o Merge Sort e o Heap Sort garantem n∗logn para todos os casos. A boa notícia é que há estratégias simples com as quais podemos minimizar as chances de ocorrência do pior caso.
O funcionamento do Quick Sort baseia-se em uma rotina fundamental cujo nome é particionamento. Particionar significa escolher um número qualquer presente no array, chamado de pivot, e colocá-lo em uma posição tal que todos os elementos à esquerda são menores ou iguais e todos os elementos à direita são maiores.
```

### Shell Sort
```
Shell sort é o mais eficiente algoritmo de classificação dentre os de complexidade quadrática. É um refinamento do método de inserção direta.[2] O algoritmo difere do método de inserção direta pelo fato de no lugar de considerar o array a ser ordenado como um único segmento, ele considera vários segmentos sendo aplicado o método de inserção direta em cada um deles.[3] Basicamente o algoritmo passa várias vezes pela lista dividindo o grupo maior em menores. Nos grupos menores é aplicado o método da ordenação por inserção.
```
## Linear Search / Busca Linear
```
Na área de informática, ou Ciência da Computação, costuma-se usar o termo busca linear (ou busca sequencial)
para expressar um tipo de pesquisa em vetores ou listas de modo sequencial, i. e., elemento por elemento, de
modo que a  função  do tempo em relação ao número de  elementos é linear, ou seja, cresce proporcionalmente. 
Num vetor ordenado, essa não é a pesquisa  mais eficiente, a  pesquisa (ou busca) binária, por exemplo, é um
tipo de pesquisa com o gráfico de tempo logarítmo.
```
![Linear Search](https://github.com/lramon2001/Algoritmos/blob/main/linear_search.gif)
## Binary Search / Busca Binária
```
A pesquisa ou busca binária (em inglês binary search algorithm ou binary chop) é um algoritmo de busca emvetores
que segue o paradigma de  divisão e conquista. Ela  parte do pressuposto de que  o vetor está ordenado e realiza 
sucessivas divisões do  espaço de busca comparando o elemento buscado (chave)  com o elemento  no meio do vetor. 
Se o elemento do  meio do vetor for a chave, a busca termina com sucesso. Caso contrário,  se o elemento do meio 
vier antes do elemento buscado, então a busca continua na metade posterior do vetor. E finalmente, se o elemento
do meio vier depois da chave, a busca continua na metade anterior do vetor.

```
![Binary Search](https://github.com/lramon2001/Algoritmos/blob/main/binary-search.gif)

## Arrays / Vetores
![imagem](https://github.com/lramon2001/EstruturaDeDados1/blob/main/arrayok.png)
```
Um array é uma estrutura de dados que armazena uma coleção de elementos de tal forma que cada um dos elementos possa ser 
identificado por, pelo menos, um índice ou uma chave. Essa estrutura de dados também é conhecida como variável indexada,
vetor (para arranjos unidimensionais) e matriz (para arranjos bidimensionais). Os arranjos mantêm uma série de elementos 
de dados, geralmente do mesmo tamanho e tipo de dados. Elementos individuais são acessados por sua posição no arranjo. A 
posição é dada por um índice, também chamado de subscrição. O índice geralmente utiliza uma sequência de números inteiros,
mas o índice pode ter qualquer valor ordinal. Os arranjos podem ser multidimensionais, significando que eles são indexados
por um número fixo de números inteiros, por exemplo, por uma sequência (ou sucessão) finita de quatro números inteiros.
Geralmente, arranjos unidimensionais e bidimensionais são os mais comuns. Os arrays podem ser considerados como as 
estruturas de dados mais simples. Têm a vantagem de que os seus elementos são acessíveis de forma rápida mas têm uma 
notável limitação: são de tamanho fixo, mas podem ser incrementados ou diminuídos com determinados algoritmos, geralmente
envolvendo a cópia de elementos de um arranjo para outro e reiniciar o original com a nova dimensão. 
```
## Linked Lists / Listas Ligadas
![gif](https://github.com/lramon2001/EstruturaDeDados1/blob/main/listasLigadas.gif)
```
Uma lista encadeada ou lista ligada é uma estrutura de dados linear e dinâmica. Ela é composta por várias células que estão
interligadas através de ponteiros, ou seja, cada célula possui um ponteiro que aponta para o endereço de memória da próxima 
célula. Desse modo, as células da estrutura não precisam estar em posições contíguas da memória. Isso faz com que a estrutura
se torne dinâmica, pois há qualquer momento, é possível alocar uma nova célula e mudar os ponteiros das células já 
existentes, de modo que a nova célula seja inserida na estrutura com êxito, na posição desejada pelo programador.
```
## Doubly Linked Lists / Listas Duplamente Ligada
![gif](https://github.com/lramon2001/EstruturaDeDados1/blob/main/listaDuplamenteLigadas.gif)
```
Em ciência da computação, uma lista duplamente ligada (ou lista duplamente encadeada) é uma estrutura de dados ligada que 
consiste de um conjunto de registros sequencialmente ligados chamados de nós e é uma extensão da lista simplesmente ligada
(ou lista simplesmente encadeada). Cada nó contem dois campos, chamados de links ou enlaces, que são referências para o nó
anterior e para o nó posterior na sequência de nós. Os links anteriores e posteriores dos nós inicial e final, respectivamente,
apontam para algum tipo de terminador, tipicamente um nó sentinela ou nulo, para facilitar o percorrimento da lista. Se houver 
apenas um nó sentinela, a lista será vinculada circularmente através do nó sentinela. Ele pode ser conceituado como duas listas
unicamente vinculadas formadas a partir dos mesmos itens de dados, mas em ordens sequenciais opostas.

```
## Stacks / Pilhas
![gif](https://github.com/lramon2001/EstruturaDeDados1/blob/main/stack.gif)
```
Pilha ou stack é um tipo especial de lista linear em que todas as operações de inserção e remoção são realizadas pela mesma 
extremidade chamada topo. Os elementos são removidos na ordem do programa inversa daquela em que foram inseridos de modo que
o último elemento que entra é sempre o primeiro ser executado , por isto este tipo de estrutura é chamada LIFO (Last In - First Out)
ou FILO (First In - Last Out).
"O exemplo mais prático que costuma utilizar-se para entender o processo de pilha é como uma pilha de livros ou pilha de pratos, no qual
ao se colocar diversos elementos uns sobre os outros, se quisermos pegar o livro mais abaixo deveremos tirar todos os livros que estiverem 
sobre ele."

Uma pilha geralmente suporta 4 operações básicas:
-TOP: acessa-se o elemento posicionado no topo da pilha;
-PUSH: insere um novo elemento no topo da pilha;
-POP: remove o elemento do topo da pilha.
-PULL:altera o elemento posicionado no topo da pilha;
```
## Queues / Filas
![gif](https://github.com/lramon2001/EstruturaDeDados1/blob/main/fila.gif)
```
A Fila é uma estrutura de dados bastante usada em computação. Na estrutura de fila, os acessos aos elementos também seguem uma regra. 
O que diferencia a fila da pilha é a ordem de saída dos elementos: enquanto na pilha “o último que entra é o primeiro que sai”, na fila 
“o primeiro que entra é o primeiro que sai” (a sigla FIFO – first in, first out – é usada para descrever essa estratégia).
A ideia fundamental da fila é que só podemos inserir um novo elemento no final da fila e só podemos retirar o elemento do início.
A estrutura de fila é uma analogia natural com o conceito de fila que usamos no nosso dia a dia: quem primeiro entra numa fila é o primeiro
a ser atendido (a sair da fila). Um exemplo de utilização em computação é a implementação de uma fila de impressão, fila de atendimento, etc. 
Se uma impressora é compartilhada por várias máquinas, deve-se adotar uma estratégia para determinar que documento será impresso primeiro. 
A estratégia mais simples é tratar todas as requisições com a mesma prioridade e imprimir os documentos na ordem em que foram submetidos – 
o primeiro submetido é o primeiro a ser impresso. 
Para implementar uma fila, devemos ser capazes de inserir novos elementos em uma extremidade, o fim, e retirar elementos da outra extremidade,
o início. Ou seja, sempre inserimos novos elementos no fim da fila e quando removemos u um elemento ele é retirado do início da fila.

```
## Sets / Conjuntos
```
Sets são estruturas de dados que agem como se fossem listas ligadas ou listas duplamente ligadas, porém elas possuem uma característica
importante: elas não permitem elementos duplicados.Quando os sets recebem um elemento duplicado para ser inserido, o conteúdo do set 
não é modificado e nenhuma exceção é lançada.Há uma variedade de estratégias para verificação de duplicidade dos itens em um set. A 
abordagem pode ser mais simples, como em uma busca linear (algoritmo mais dispendioso) até uma verificação baseada no hash code dos 
objetos.
```
## HashTables / Tabelas de Espalhamento
![gif](https://github.com/lramon2001/EstruturaDeDados2/blob/main/hashtable.gif)
```
Em ciência da computação, uma tabela de dispersão (também conhecida por tabela de espalhamento ou tabela hash, do inglês hash) é uma 
estrutura de dados especial, que associa chaves de pesquisa a valores. Seu objetivo é, a partir de uma chave simples, fazer uma busca
rápida e obter o valor desejado. É algumas vezes traduzida como tabela de escrutínio.
```
## Maps / Mapas
![gif](https://github.com/lramon2001/EstruturaDeDados2/blob/main/map.gif)
```
Os mapas são estruturas de dados que são chamadas de estruturas associativas. Estas estruturas possuem esse nome pois permitem associar
um valor de acesso a um determinado elemento.
Você pode imaginar os mapas como sendo um dicionário. Se você quiser saber o significado de uma palavra, você procura a palavra desejada 
no dicionário. Após localizar a palavra, você conseguirá o acesso ao seu significado.
Veja que no exemplo acima temos a demonstração clássica de uma estrutura associativa no estilo de um mapa. Você tem uma chave, que é a 
palavra desejada, e um valor associado, no caso, o significado da palavra. Perceba também o fato de que uma palavra não aparece de maneira 
repetida em um dicionário. Essa mesma regra vale para os mapas: as chaves em um mapa não podem ser duplicadas.
```
## Binary Tree / Árvore Binária
![gif](https://github.com/lramon2001/EstruturaDeDados2/blob/main/binaryTree.gif)

```
Árvores binárias são estruturas de dados hierárquicas que armazenam os elementos de maneira classificada.Árvores binárias são constituídas
por um enlace de outra estrutura: os nós. Os nós são caracterizados por duas informações: o valor, que corresponde ao elemento a ser 
armazenado, e o peso. O peso do nó é utilizado para categorizar e direcionar o nó dentro da árvore binária.
```

[MIT License](https://github.com/lramon2001/Algoritmos/blob/main/LICENSE) © [Lucas Ramon](https://github.com/lramon2001)
