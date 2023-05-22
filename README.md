```
 ___   ___   ___
|K  | |2  | |6  |
| ♦ | | ♥ | | ♠ |
|__K| |__2| |__6|

```

> A CLI game built with Python

# Jogo de Cartas em Python

Este script Python implementa um simples jogo de cartas baseado no Blackjack, também conhecido como 21, que é jogado entre vários jogadores e um dealer (neste caso, o computador). O jogo é jogado com um baralho padrão de 52 cartas e a pontuação dos jogadores é calculada com base no valor de suas cartas.

## Requisitos

O script utiliza as seguintes bibliotecas:

requests
json
datetime

## Instalação

Instale-as seguindo a instrução (json e datetime são bibliotecas padrão do Python):

```
pip install -r requirements.txt

```

## Como executar

```
python3 jogo.py

```

## Instruções de Uso

1 - Certifique-se de ter as bibliotecas necessárias instaladas.
2 - Execute o script Python.
3 - Quando solicitado, insira o número de jogadores (máximo 4).
4 - Cada jogador será solicitado a comprar mais cartas ou parar.
5 - Depois que todos os jogadores tiverem terminado, os vencedores serão anunciados e o jogo será registrado.
6 - Você pode optar por jogar novamente ou parar.

## Funcionamento do Jogo

Quando o jogo começa, um número especificado de jogadores é adicionado ao jogo. Cada jogador e o dealer recebem cartas, e os jogadores decidem se querem continuar a comprar cartas até que sua pontuação seja igual ou superior a 21 ou até que eles decidam parar. O dealer também compra cartas até que sua pontuação seja de pelo menos 17.

Em seguida, os vencedores são determinados com base na pontuação dos jogadores e do dealer. Se um jogador tem uma pontuação superior à do dealer e não ultrapassou 21, ele vence. Se um jogador ultrapassa 21, ele perde. Se o dealer ultrapassa 21, todos os jogadores restantes vencem.

O jogo também salva um log após cada jogo, contendo as mãos finais dos jogadores e do dealer e os vencedores do jogo.
