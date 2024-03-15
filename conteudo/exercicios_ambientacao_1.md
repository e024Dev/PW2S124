# Exercícios Estruturas de Decisão

> O objetivo dos sexercícios abaixo é criar afinidade com a sintaxe da Linguagem PHP, minimizando a curva de aprendizagem para com as estruturas básicas da linguagem.

## Resolução de situação-problema utilizando expressões e estruturas de decisão

1. Receber um valor e exibir se ele é par ou impar. 
2. Receber um valor e exibir se é divisível por 2 e 3. 
3. Receber três valores distintos, definir e exibir o menor valor. 
4. Receber três valores distintos e exibi-los em ordem crescente. 
5. Receber três valores, informar se estes formam um triângulo. A regra para definir se os três valores referentes aos lados do triângulo é, cada um dos  três lados deve ser menor que a soma dos dois lados adjacentes. Caso formem um triângulo, exibir o tipo, equilátero (três lados iguais), isósceles  (dois dos três lados iguais) ou escaleno(três lados diferentes). Exibir uma mensagem caso não forme triângulo. 

6. Receber o nome e as 4 notas de um aluno e a quantidade de faltas e então, calcule a sua média e defina o seu status mediante as seguintes regras. Para estar aprovado o aluno deve ter uma media maior que 7, ou igual. Para estar em exame, a média tem que estar entre 5 e ser menor que 7. Para estar reprovado o aluno deve ter a média menor que 5. O aluno que tiver mais do que 60 faltas estará reprovado, independente de sua média. Exibir o nome, a quantidade de faltas e o status do aluno.

7. Crie um algoritmo que, dada uma temperatura em graus celsius, exiba uma mensagem informando o tipo do clima, de acordo com as seguintes condições: se a temperatura estiver até 18 graus, o clima é frio; se a temperatura estiver entre 19 e 23 graus, o clima é agradável; se a temperatura estiver entre 23 e 35 graus, o clima é quente; se a temperatura estiver acima de 35 graus, o clima é muito quente. 

8.  Receber o nome e as 4 notas de um aluno e a quantidade de faltas e então, calcule a sua média ponderada com os pesos 1, 3, 2 e 4, respectivamente.  Defina e exiba sua nota, mediante as seguintes regras:
a. Média entre 9.1 e 10: “A”;
b. Média entre 6.1 e 9: "B”;
c. Média entre 4.1 e 6: “C”  ';
d. Média entre 3.1 e 4: “D”;
e. Média entre 0 e 3: “E";

## Estruturas de Repetição

> O objetivo do desafio abaixo é assimilar as estruturas de repetição em PHP auxiliando a redução da curva de aprendizagem.

### Desafio I - Quebra Vidraças

Este algoritmo tem por objetivo gerar a reflexão sobre o uso das 3 estruturas discutidas em sala de aula e suas principais características.

Neste exemplo infame, o algoritmo deve lançar pedras numa vidraça e verificar se a vidraça foi quebrada.

Você deve executar o algorimo e depois realizar uma alteração.

```code
Algoritmo "quebra_janelas_enquanto"
// Disciplina   : [Linguagem e Lógica de Programação]
// Professor   : Esdras Bezerra da Silva
// Data atual  : 05/08/2023
Var
   // Seção de Declarações das variáveis
   janela_esta_quebrada: logico
   resposta: caractere
   pedras_lancadas: inteiro

Inicio
   // Seção de Comandos, procedimento, funções, operadores, etc...

   janela_esta_quebrada <- falso

   enquanto (nao janela_esta_quebrada) faca
      pedras_lancadas <- pedras_lancadas + 1
      escreval("Atirei a ", pedras_lancadas, "ª")

      escreval("A janela esta quebrada?")
      leia(resposta)

      se (minusc(resposta) = "s") entao
         janela_esta_quebrada <- verdadeiro
      fimse
   fimenquanto
   
   escreval("Foram lancadas ", pedras_lancadas, " para quebrar a janela.")

Fimalgoritmo
```

Com base no algoritmo acima, após executá-lo; altere o valor da variável janela_esta_quebrada para verdadeiro, supondo que a vidraça já estava quebrada antes de executar o algoritmo.

Execute-o novamente.

Com base no resultado; altere sua estrutura para o Repita-Até e Para-Faça; nós discutiremos o resultado na próxima aula.
