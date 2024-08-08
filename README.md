# Desafio de programação

## Desafio 1

> Nível dificuldade: 2

Dado que exista uma matriz M x N de inteiros, checar se os números de cada item da matriz se repetem em todos os itens.

| Teste   | Matriz                      | Retorno esperado | 
|---------|-----------------------------|------------------|
|       1 | [[1,2,3], [3,1,2], [2,3,1]] | true             |
|       2 | [[3,22,5], [22,3,5]]        | true             |
|       3 | [[3,2,1], [5,3,2]]          | false            |
|       4 | [[3,22,5], [22,5]]          | false            |

## Desafio 2

> Nível dificuldade: 2

Dado que exista um matriz de n elementos, remova os itens duplicados e informa a quantidade de itens que sobrou.

| Teste | Matriz      | Retorno esperado | 
|-------|-------------|------------------|
|     1 | [1,2,4,2,5] |                3 |
|     2 | [1,2,4,3,5] |                5 |
|     3 | [1,1,1,1,5] |                1 |

## Desafio 3

> Nível dificuldade: 3

Ordene a matriz de forma diferente. O itens em posições pares deve ser ordenados em ordem crescente e os em posições ímpares devem ser ordenados em ordem decrescente.

| Teste | Matriz        | Retorno esperado | 
|-------|---------------|------------------|
|     1 | [1,4,2,5]     | [1,5,2,4]        |         
|     2 | [4,4,7,5]     | [4,5,7,4]        |         
|     3 | [5,6,3,1,7,3] | [3,6,5,3,7,1]    |             

## Desafio 4
> Nível dificuldade 2

Implementar um algoritmo onde ele possa detectar palimdromos (palavras que tem o mesmo som de traz para frente): Ex: radar, renner, arara, reviver

| Teste | Palavra | Retorno esperado | 
|-------|---------|------------------|
|     2 | salas   | true             |
|     3 | palavra | false            |
|     4 | reviver | true             |
|     5 | memoria | false            |
