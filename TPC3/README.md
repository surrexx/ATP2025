# TPC3
### Autor: Maria Surreira, a112341,![Screenshot_20250920_114406_Instagram](https://github.com/user-attachments/assets/151788e3-218c-4c92-a633-dc62cbfab866)

#### Resumo:
O programa apresentado é um menu interativo em Python que permite ao utilizador criar, manipular e analisar listas de números inteiros. A estrutura principal baseia-se numa função chamada `menu()`, que apresenta ao utilizador várias opções numeradas e devolve a escolha inserida. Em seguida, o programa entra num ciclo `while True`, que mantém o menu ativo até que o utilizador escolha a opção “0” para sair.

Quando o utilizador seleciona a opção **1**, o programa cria automaticamente uma lista de tamanho aleatório (entre 1 e 40 elementos) com números também aleatórios entre 1 e 100. Esta lista é então mostrada no ecrã. Já a opção **2** permite ao utilizador criar manualmente uma lista, escolhendo quantos elementos deseja inserir e introduzindo cada número um a um.

As opções seguintes realizam diferentes operações sobre a lista. A opção **3** calcula a soma de todos os elementos, utilizando uma função interna chamada `soma(lista)`. A opção **4** tenta calcular a média dos valores, mas a implementação contém um pequeno erro lógico, pois a divisão é feita por cada elemento em vez do total de elementos. A opção **5** devolve o maior valor da lista, enquanto a **6** devolve o menor, ambas através de funções internas que percorrem a lista e comparam os seus elementos.

A opção **7** verifica se a lista está ordenada por ordem crescente. Caso não esteja, o programa ordena-a automaticamente e informa o utilizador. De forma semelhante, a opção **8** verifica se a lista está por ordem decrescente e, se não estiver, também a reorganiza nesse formato. A opção **9** permite procurar um elemento específico dentro da lista, indicando a posição onde se encontra ou devolvendo “-1” caso não exista.

Em todas as operações (da 3 à 9), o programa verifica primeiro se já existe uma lista definida. Caso contrário, apresenta uma mensagem de erro a indicar que o utilizador deve criar uma lista antes de prosseguir. Finalmente, ao selecionar a opção **0**, o programa exibe uma mensagem de despedida e termina a execução do ciclo, encerrando o programa.

#### Lista de Resultados:
[TPC3.ipynb](https://github.com/user-attachments/files/22742698/TPC3.ipynb)
