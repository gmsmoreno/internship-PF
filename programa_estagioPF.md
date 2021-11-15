# -*- coding: utf-8 -*-
"""
Created on Mon Nov 15 16:51:03 2021

@author: Gabriel
"""
# Multiples of 3 or 5

## Descrição do Problema 1

If we list all the natural numbers below 10 that are multiples of 3 or 5, we get 3, 5, 6 and 9. The sum of these multiples is 23.

Find the sum of all the multiples of 3 or 5 below 1000.

## Descrição da resolução:
    
Entende-se que números múltiplos de algum número em questão terão seus restos divisíveis igual a 0. 
Então os restos da divisão por 3 ou 5 devem dar o valor de 0.
O que foi realizado nessa estrutura de repetição em for foi um range de valores de 0 a 998 com o 999 separado, para não ter o final com vírgula.
O programa encontrará cada valor com seu respectivo resto de divisão igual a zero em condição de operadores lógicos em OR. Ou seja, determina-se possibilidades de identificar valores tanto referenstes aos múltiplos de 3 ou 5.

## Algoritmo de resolução:

for c in range(0, 998):

    c += 1

    if c == 1:

       print(f'{c},', end='')

    if c % 3 == 0 or c % 5 == 0:

        print(f'{c},', end='')

if 999 % 3 == 0:

    print(999)
        

        
        
        
        
    