# Estrutura de Dados em Java: Lista


Uma Lista é uma estrutura de dados dinâmica, onde o número de nós de uma lista pode variar consideravelmente à medida que são inseridos e removidos os elementos. Cada elemento de uma lista encadeada (nó) é constituído de dois campos: valor e próximo elemento. Conforme foi apresentado na semana 4 a estrutura de dados, lista, e uma lista dinâmica de números inteiros em Java. A lista deverá possuir um objeto Nó (classe No) e ter os métodos listados abaixo:

###### boolean vazia()
###### void inserePrimeiro(int info)
###### void insereDepois(No no, int info)
###### void insereUltimo(int info)
###### No removePrimeiro()
###### No removeUltimo()
###### No remove(No no)
###### void mostrar()

Nó:  
* Deverá possuir uma variável inteira e um objeto do mesmo tipo da classe, além dos métodos de get, set e próximo elemento.

Lista:
* Deverá ter um objeto com o endereço do primeiro elemento da lista.
* Método vazia: deverá verificar se a lista está vazia ou não.
* Método inserePrimeiro: deverá inserir um valor no início da lista.
* Método insereDepois: deverá inserir um valor depois de um nó específico da lista, deverá passar este nó como parâmetro na chamada do método.
* Método insereUltimo: deverá inserir um valor no fim da lista.
* Método removePrimeiro: deverá remover o primeiro nó da lista.
* Método removeUltimo: deverá remover o último nó da lista.
* Método remove: deverá remover qualquer nó da lista, deverá passar este nó como parâmetro na chamada do método.
* Método mostrar: deverá mostrar no console todos os itens da lista.



![giphy](https://github.com/Giovanacarmazio/Estrutura_de_Dados/blob/6d0a1c71ab33a119b89e36264a310c5982f8dd22/y2meta.com%20-%20PUCPR%20-%20Estrutura%20de%20Dados.gif)
