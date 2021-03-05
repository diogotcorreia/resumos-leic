---
description: Enunciado e resolução dos exercícios do Laboratório 2 de IAED
---

# Lab 02

[[toc]]

## Exercício 1

_(Maior de Três)_ Escreva um programa que determine e imprima o maior de três números inteiros dados pelo utilizador.

::: details Resolução
<code-group>
<code-block title="CONDICIONAIS">
<<< @/src/iaed/labs/lab02/ex01.c
</code-block>

<code-block title="CICLOS">
<<< @/src/iaed/labs/lab02/ex01_2.c
</code-block>
</code-group>
:::

## Exercício 2

_(Ordena 2)_ Escreva um programa que leia dois inteiros `N`, `M` e imprima o menor deles na primeira linha e o maior na segunda.

::: details Resolução
<<< @/src/iaed/labs/lab02/ex02.c
:::

## Exercício 3

_(Divisor)_ Escreva um programa que leia dois inteiros positivos `N`, `M` e imprima `"yes"` se `M` é um divisor de `N`. Caso contrário, imprima `"no"`.

::: details Resolução
<<< @/src/iaed/labs/lab02/ex03.c
:::

## Exercício 4

_(Ordena 3)_ Escreva um programa que leia três inteiros e imprima-os por ordem na mesma linha separados por um espaço em branco. O menor dos números deve aparecer como primeiro.

::: details Resolução
<<< @/src/iaed/labs/lab02/ex04.c
:::

## Exercício 5

_(Ciclo)_ Escreva um programa que leia um inteiro positivo `N` e imprima os números `1..N`, um por linha.

::: details Resolução
<<< @/src/iaed/labs/lab02/ex05.c
:::

## Exercício 6

_(Maior e Menor)_ Escreva um programa que determine o maior e o menor número de `N` números reais dados pelo utilizador. Considere que `N` é um valor pedido ao utilizador. O resultado deve ser impresso com o comando `printf("min: %f, max: %f\n", min, max);`.

_Sugestão:_ inicialize o maior e o menor com o primeiro valor lido.

::: details Resolução
<<< @/src/iaed/labs/lab02/ex06.c
:::

## Exercício 7

_(Divisores)_ Escreva um programa que pede ao utilizador um inteiro positivo `N` e imprima o número de divisores de `N`. Recorde que os números primos têm 2 divisores.

::: details Resolução
<<< @/src/iaed/labs/lab02/ex07.c
:::

## Exercício 8

_(Média)_ Escreva um programa que calcule e imprima a média de `N` números reais dados pelo utilizador. O programa deverá primeiro pedir ao utilizador um inteiro `N`, representando a quantidade de números que vão ser introduzidos. Os números reais devem ser representados pelo tipo `float`.
O resultado deve ser impresso com o comando `printf("%.2f\n", media);`.

::: details Resolução
<<< @/src/iaed/labs/lab02/ex08.c
:::

## Exercício 9

_(Conversão)_ Escreva um programa que pede ao utilizador um valor `N` correspondente a um certo período de tempo em segundos. O programa deverá apresentar no output esse período de tempo no formato `HH:MM:SS`.

_Sugestão:_ utilize o operador que calcula o resto da divisão (`%`).

::: details Resolução
<<< @/src/iaed/labs/lab02/ex09.c
:::

## Exercício 10

_(Dígitos)_ Escreva um programa que pede ao utilizador um valor positivo `N`. No output, deverá mostrar o número de dígitos que compõem `N` (na primeira linha), assim como a soma dos dígitos de `N` (na segunda linha). Por exemplo, o número `12345` tem `5` dígitos e a soma desses dígitos é `15`.

::: details Resolução
<<< @/src/iaed/labs/lab02/ex10.c
:::
