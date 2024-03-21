# Exercícios PHP utilizando formulários

Estes exercícios tem como objetivo reforçar o entendimento do uso de formulários em PHP.

## Scripts em arquivos separados

Estes exercícios deverão utilizar 2 arquivos separados, um formulário em HTML e um script em PHP.

1. Criar um formulário que contenha 2 campos de texto e inputs do tipo radio, cada um com uma operação (soma, subtração, multiplicação e divisão) e um botão para enviar o formulário. Ao enviar o formulário, devemos exibir uma mensagem contento os operandos, o operador, o resultado da operação e um botão para retornar à página anterior.

2. Criar um formulário que contenha 2 campos de texto e inputs do tipo adequado para o peso, altura e um botão para enviar o formulário. Ao enviar o formulário, devemos exibir uma mensagem contento o IMC calaculado e uma pequena descrição sobre o resultado.

> Vocês podem definir os inputs, o visual e a apresentação dos esxerçicios abaico.

3. Crie um formulário em HTML com dois campos de texto para ler os valores do lado de um retângulo e um botão submit. Crie uma página em PHP que receba os  ados e exiba o valor da área e do
perímetro do retângulo. 

4. Crie um formulário em HTML com dois campos (um campo de texto para o nome do usuário e um campo password para a senha) e um botão submit. Crie uma página PHP que receba os dados através do método POST e imprima a mensagem Autenticação realizada com sucesso” caso o nome do usuário seja igual a “maria” e a senha igual a “12345”. Caso contrário, exiba a mensagem “Você não
tem permissão de visualizar essa página”.

5. Baseado na tabela de Cálculo de Imposto de Renda **abaixo após do exercício 5**, crie um programa que receba o valor do salário bruto do usuário e informe a alíquota aplicada e o valor da parcela a deduzir do Imposto de Renda para o valor inserido.

6. Lembra do `Jokenpo` ou famoso `Papel, Tesoura ou Pedra`? Sua missão é criar um site que simula uma jogada entre o usuário e o computador. O site deve informar as opções de escolha para que o usuário possa escolher uma das opções como a jogada do usuario, o `computador` deve escolher um numero aleatorio entre 1 e 3 representando as opções escolhidas. Após a submissão do formulário, o site  deve exibir o resultado da partida e a regra aplicada para o resultado, como exemplo o usuario escolheu pedra e o computador tesoura; o resultado seria `Ganhou! Pedra quebra a tesoura!`. 

### Tabela Exercício 5

BASE DE CÁLCULO MENSAL | ALÍQUOTA | PARCELA A DEDUZIR DO IR
-- | -- | --
Até 1.903,98	| Isento	| —
De 1.903,99 até 2.826,65	| 7,5% |	R$142,8
De 2.826,66 até 3.751,05	| 15%	| R$354,8
De 3.751,06 até 4.664,68	| 22,5%	| R$636,13
Acima de 4.664,68 | 	27,5% |	R$869,36