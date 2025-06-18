# Jogo "Maior ou Menor" em C

Este projeto é um jogo simples desenvolvido na linguagem C chamado **"Maior ou Menor"**, onde o jogador precisa adivinhar se a próxima carta sorteada será maior ou menor que a carta atual.

## Integrantes
- Mateus Vinicius
- Clara Maria
- Maxwell Lucas

## Como funciona o jogo

- O baralho é criado dinamicamente com listas encadeadas.
- Uma carta inicial é sorteada e exibida ao jogador.
- O jogador escolhe se acredita que a próxima carta será **maior** (`x`) ou **menor** (`y`).
- Uma nova carta é sorteada e comparada com a anterior.
- O jogo informa se o jogador acertou ou errou.
- Após cada rodada, o jogador pode escolher se deseja jogar novamente (`s` para sim, `n` para não).

## Estruturas utilizadas

- **Structs**: Para representar as cartas e os nós da lista.
- **Enum**: Para os naipes do baralho (Ouros, Paus, Copas, Espadas).
- **Listas encadeadas**: Utilizadas para representar o baralho, a mão do jogador e a pilha de descarte.
- **Função auxiliar**: `removerTopo()` permite manipular as listas caso desejado no futuro.
