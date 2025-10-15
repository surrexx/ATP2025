# TPC4

### Autor: Maria Surreira, a112341,![Screenshot_20250920_114406_Instagram](https://github.com/user-attachments/assets/151788e3-218c-4c92-a633-dc62cbfab866)

#### Resumo:

Este código é um pequeno programa em Python que simula um sistema de bilheteira de cinema, onde o utilizador pode escolher filmes, verificar lugares e comprar bilhetes.

No início, o programa apresenta um menu com várias opções, como mostrar os filmes em exibição, ver lugares ocupados, comprar bilhetes, consultar quantos lugares ainda estão disponíveis e listar as salas de cinema. O utilizador deve escolher uma dessas opções escrevendo o número correspondente.

São inseridas duas salas no cinema1 (que é uma lista que representa o conjunto de todas as salas do cinema mas no início encontra-se vazia), previamente criadas, cada uma com uma capacidade máxima de lugares, uma lista de lugares ocupados (inicialmente vazia).

Há uma função que mostra os filmes em exibição, outra que verifica se um filme existe no cinema e uma que confirma se o lugar escolhido é válido, isto é, se o número do lugar está dentro do limite da sala.

Existe outra função que serve para verificar se um lugar está livre — ela percorre as salas e vê se o número do lugar já foi vendido ou não. Se o lugar estiver livre, o programa permite a compra através de uma função que vende o bilhete, guardando o número do lugar na lista de lugares ocupados dessa sala.

Existe também uma função que mostra quantos lugares ainda estão disponíveis em cada filme, calculando a diferença entre a capacidade total da sala e o número de lugares já ocupados.

Por fim, há um ciclo principal que mantém o programa a funcionar até o utilizador escolher a opção de sair. Nesse ciclo, o programa lê a opção escolhida, executa a ação correspondente (mostrar filmes, verificar lugares, comprar bilhete, etc.) e valida sempre se o filme e o lugar indicados são válidos antes de avançar.

Em resumo, este código cria uma aplicação simples de gestão de bilhetes de cinema, permitindo ao utilizador consultar filmes, verificar e comprar lugares de forma interativa, assegurando que não há erros ou repetições na reserva

#### Lista de resultados: 
[tpc4.py](https://github.com/user-attachments/files/22934119/tpc4.py)

