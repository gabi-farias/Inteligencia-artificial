# Inteligencia-artificial
Introdução a inteligência artificial com Python e R

ALGORITMOS DE BUSCA
*Elementos de um problema de busca
S: search space - conjunto finito de estados
I: conjunto finito de estados iniciais
O: conjunto finito de objetivos
FS: função que recebe o estado inicial e retorna os estados alcançáveis
FC: função de custo - recebe o estado atual e um possível próximo estado e retorna o custo

Algoritmos de busca
Hill climbing: inicia a busca em um único ponto, escolho um novo ponto na vizinhança. Se o novo ponto for uma solução melhor, passa a ser a solução, caso contrário escolhe um novo ponto na vizinhança até não ter mais como subir ou acabar o tempo. (Local optima)
Força bruta/Blind search: exploram todo o espaço de busca, encontra a global optima, sem otimização.
->Breath first: retorna de uma vizinhança a melhor solução - backtracking
->Depth first: explora uma vizinhança, retornando e tentando outras ramificações
->Best first: algoritmo de heuristica
Problema de caminho: só pode ser feito com força bruta pois precisa de um solução global e é díficil de ter uma noção de perfomace
Lee - Transforma caminho em grafos, nós e arestas
