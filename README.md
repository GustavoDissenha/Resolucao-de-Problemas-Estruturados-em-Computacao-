# Resolu-o-de-Problemas-Estruturados-em-Computa-o-Main.java: Contém a implementação das classes Pilha e Fila em Java e o método principal para execução dos exemplos.


Execute o Código

Após a compilação, execute o programa:

java Main

Exemplos Utilizados para Validação

PILHA:

Inserção dos elementos: 1, 2.

Impressão dos elementos da pilha (esperado: 2, 1).

Remoção do elemento do topo (esperado: 2).

Impressão dos elementos restantes da pilha (esperado: 1).

FILA:

Inserção dos elementos: 3, 4.

Impressão dos elementos da fila (esperado: 3, 4).

Remoção do elemento do início (esperado: 3).

Impressão dos elementos restantes da fila (esperado: 4).

Saída Esperada

Ao executar o programa, a saída será:

--- Pilha ---
Elemento 1 inserido na pilha.
Elemento 2 inserido na pilha.
Elementos da pilha:
2
1
Elemento 2 removido da pilha.
Elementos da pilha:
1

--- Fila ---
Elemento 3 inserido na fila.
Elemento 4 inserido na fila.
Elementos da fila:
3
4
Elemento 3 removido da fila.
Elementos da fila:
4



Modifique os valores nos métodos de inserção em Main.java para testar com outros dados.



MERGE:


Entrada e Funcionamento

O programa já possui dois exemplos de filas ordenadas inseridas no código:

FilaMerge A: Contém os elementos 12, 35, 52, 64.

FilaMerge B: Contém os elementos 5, 15, 23, 55, 75.

Durante a execução, o método mergeFilas será responsável por combinar essas filas em uma nova fila ordenada FilaMerge C.

Saída Esperada

Ao executar o programa, a seguinte saída será exibida:

Fila A:
12 35 52 64
Fila B:
5 15 23 55 75
Fila C (Resultado do Merge):
5 12 15 23 35 52 55 64 75

Para alterar os valores de entrada, edite as chamadas do método insere dentro do método main em Merge.java.
