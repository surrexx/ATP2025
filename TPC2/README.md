# TPC2
### Autor: Maria Surreira, a112341,![Screenshot_20250920_114406_Instagram](https://github.com/user-attachments/assets/151788e3-218c-4c92-a633-dc62cbfab866)

#### Resumo:
Jogo do "Adivinha o número"

- Para a primeira modalidade do jogo do adivinha coloquei o computador a gerar um número aleatório entre (0, 100) com o comando random. De seguida defini as variáveis "tries" e "guess", igualando cada uma delas a 0. Criei, também, um ciclo com o comando "while" onde afirmava que enquanto a variável "guess" fosse diferente do número gerado repetiria-se a string, como inteiro, "Guess the number: " e ao número de tentativas era sempre somado +1. Por fim criei umas condições de forma a que o computador nos desse informações sobre o número, isto é, se "guess" > n o computador iria imprimir que o número gerado era menor, se "guess" < n o computador iria imprimir que o número gerado era maior, e se "guess" == n o computador imprimira "Acertou" bem como o número de tentativas utilizadas.
- Já para a segunda modalidade o utilizador é que gera um número entre 0 e 100 e o computador tenta adivinhar. Para isso utilizei novamente o comando random e defini uma variável n como um número inteiro. Em seguida reutilizei as variáveis "tries" e "guess", contudo defini a váriável mín = 0 e a variável max = 100. Recorri, novamente, ao comando cíclico "while" sendo que a variável "guess" era agora o número que em cada ciclo iria ser gerado, de forma aleatótia, até chegar número definido. Por fim, tal como na 1ª modalidade defini duas condições: uma seria se "guess" > n e a outra se "guess" < n. Para cada condição defini novos limites do ciclo, isto é, para "guess" > n o novo limite era: max = guess - 1, e para "guess" < n o novo limite era: min = guess + 1. Para concluir o código, ou seja, quando o computador adivinhasse o meu número este iria imprimir o número de tentativas que utilizou bem como o número em que pensei.
"JOGO DOS 21 FÓSFOROS"

- Estrutura Geral do jogo: O jogo começa com 21 fósforos (F = 21).O utilizador escolhe se quer ser o 1º ou o 2º jogador com input().As variáveis n1 e n2 guardam os valores jogados em cada turno.
- Modo Jogador 1 (o utilizador joga primeiro): O computador começa com uma jogada aleatória (random.randint(1, 4)). O utilizador joga de seguida (n1 = int(input(...))) e os fósforos são atualizados. O computador repete a sua jogada inicial a cada ronda (erro lógico: n2 devia ser recalculado).O jogo termina quando sobrar apenas 1 fósforo: se o utilizador deixa 1 fósforo após a sua jogada, o computador ganha.Se o número restante for menor ou igual a n2 + 1, o computador perde (interpretação algo confusa do fim de jogo).
- Modo jogador 2 (o utilizador joga em segundo): O computador começa com uma jogada aleatória. O utilizador joga de seguida (embora o input() esteja ausente no código — outro erro). O computador aplica a estratégia ideal: força que a soma das jogadas dos dois jogadores seja sempre 5 (n2 = 5 - n1). Esta estratégia garante que o computador controla o ritmo do jogo e vence — a menos que o utilizador quebre o padrão, o que aqui nem é possível, já que não há input() neste modo. O jogo termina com a mensagem "O 2 ganha!" se sobrarem apenas 1 fósforo após a jogada do computador.




#### Lista de Resultados:
"Adivinha o jogo":
- Modalidade 1 [CProgram FilesWindowsAppsPythonSoftwareFoundation.Python.3.13_3.13.2032.0_x64__qbz5n2kfra8p0python3.13.exe.txt](https://github.com/user-attachments/files/22581923/CProgram.FilesWindowsAppsPythonSoftwareFoundation.Python.3.13_3.13.2032.0_x64__qbz5n2kfra8p0python3.13.exe.txt)

- Modalidade 2 [CProgram FilesWindowsAppsPythonSoftwareFoundation.Python.3.13_3.13.2032.0_x64__qbz5n2kfra8p0python3.13.exe Modalidade 2.txt](https://github.com/user-attachments/files/22581935/CProgram.FilesWindowsAppsPythonSoftwareFoundation.Python.3.13_3.13.2032.0_x64__qbz5n2kfra8p0python3.13.exe.Modalidade.2.txt)

"Jogo dos Fósforos"  
[CProgram FilesWindowsAppsPythonSoftwareFoundation.Python.3.13_3.13.2032.0_x64__qbz5n2kfra8p0python3.13.exe jogo dos fósforos.txt](https://github.com/user-attachments/files/22583513/CProgram.FilesWindowsAppsPythonSoftwareFoundation.Python.3.13_3.13.2032.0_x64__qbz5n2kfra8p0python3.13.exe.jogo.dos.fosforos.txt)



