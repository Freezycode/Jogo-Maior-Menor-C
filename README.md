# Jogo: Maior ou Menor 

Este projeto consiste em um jogo de cartas desenvolvido em linguagem C, como parte de um trabalho em grupo da disciplina de Estrutura de Dados.

## Integrantes
- Mateus Vinicius
- Clara Maria
- Maxwell Lucas

## Regras do Jogo

O jogo é simples:  
- O jogador vê uma carta sorteada aleatoriamente do baralho.
- Em seguida, escolhe se a próxima carta será maior (x) ou menor (y).
- O programa sorteia uma nova carta e verifica se a resposta do jogador está correta.
- Ao final de cada rodada, o jogador decide se deseja jogar novamente (s ou n).

## Funcionalidades Implementadas

- Estruturas struct para representar cartas e listas encadeadas.
- Enum Naipe para definir os quatro naipes possíveis (Ouros, Paus, Copas, Espadas).
- Listas encadeadas para representar:
  - Baralho
  - Mão do jogador
  - Pilha de descarte
- Interface totalmente via terminal (texto).
- Registro automático da pontuação em um arquivo placar.txt.
- Leitura e exibição da pontuação anterior no início de cada jogo.
- Possibilidade de jogar várias rodadas seguidas, de forma interativa.

## Como compilar e executar
Se estiver usando gcc :
bash
gcc MaiorMenor.c -o jogo
./jogo  # ou jogo.exe

## Organização do Código

- **MaiorMenorFinal.c**: Código-fonte principal do jogo.
  - main() : Função principal com lógica do jogo e repetição por rodada.
  - criarBaralho() : Gera todas as cartas usando lista encadeada.
  - inserirCarta() : removerTopo(): Manipulam as listas de cartas.
  - imprimirCarta() : imprimirBaralho(): Mostram o jogo ao jogador.
  - liberarBaralho() : Libera memória usada pelas listas.
- placar.txt : Armazena a pontuação final após cada sessão de jogo.

