# Estrutura-de-Dados-e-Algoritmos

## Ementa
### Vetores / Arrays
- Entendendo melhor o que são arrays;
- Lendo dados a partir de arrays;
### Algoritmos de ordenção
- Algoritmos de ordenação: entendendo e implementando o selection sort.
### Algoritmos de Busca
- Algoritmos de busca: entendendo e implementando a busca linear;
- Algoritmos de busca: entendendo e implementando a busca binária.
### Análise Assintótica
- Como mensurar a eficiência de um algoritmo?
- Como prever o comportamento de um algoritmo com a evolução do tempo e da massa de dados?
- Entendendo a notação de Bachmann–Landau (O-grande).

## Vetores
```
O vetor é uma estrutura de dados indexada, que pode armazenar uma determinada quantidade de valores do mesmo tipo. 
Os dados armazenados em um vetor são chamados de itens do vetor. Para localizar a posição de um item em um vetor 
usamos um número inteiro denominado índice do vetor.
```
## Selection Sort / Ordenação por Seleção
```
A ordenação  por seleção  (do inglês, selection sort) é  um algoritmo de ordenação baseado em se passar sempre
o menor valor do vetor para a primeira posição (ou o maior dependendo da ordem requerida), depois o de segundo
menor  valor para  a segunda  posição, e  assim é feito  sucessivamente com os n-1 elementos restantes, até os
últimos dois elementos.
```
![Selection Sort](https://github.com/lramon2001/Algoritmos/blob/main/Selection-Sort-Animation.gif)
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


[MIT License](https://github.com/lramon2001/Algoritmos/blob/main/LICENSE) © [Lucas Ramon](https://github.com/lramon2001)
