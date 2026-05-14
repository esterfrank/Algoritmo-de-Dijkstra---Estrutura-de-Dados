# Algoritmo de Dijkstra em Python

Implementação do algoritmo de Dijkstra desenvolvida manualmente em Python, sem uso de bibliotecas prontas para grafos ou filas de prioridade.
Desenvolvida durante as aulas de Estruturas de Dados, ministrada pelo professor Thyerri Mezzari na UniSATC.

## Objetivo

Encontrar o menor caminho entre capitais europeias utilizando o algoritmo de Dijkstra.
A origem do percurso é fixa em:
```text
Zurique

O algoritmo:
1. Define o vértice inicial com custo 0;
2. Inicializa os demais vértices com custo infinito;
3. Explora sempre o vértice de menor custo;
4. Atualiza os menores caminhos possíveis;
5. Reconstrói o caminho final.
