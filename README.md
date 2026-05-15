# estrutura-de-dados-trabalho

## Fibonacci Recursiva sem Otimização
Implementação recursiva direta. Caso base: n = 0 ou 1.
Cada chamada gera duas novas chamadas causando crescimento exponencial.
Foi contabilizado o número total de chamadas recursivas.

## Fibonacci com Memoização
Utiliza vetor alocado dinamicamente para armazenar resultados já calculados.
Evita recomputação de subproblemas.
Comparação mostra grande redução no número de chamadas.

## Torres de Hanoi
Problema resolvido recursivamente.
Caso base: 1 disco.
Cada passo move n-1 discos para auxiliar, depois move o disco principal e repete.
Foi contabilizado o número total de movimentos.

## Compilação
gcc fibonacci_ingenuo.c -o fib1  
gcc fibonacci_memo.c -o fib2  
gcc hanoi.c -o hanoi
