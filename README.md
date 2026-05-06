# mini_trabalho_daa

**2.2. Conectividade**

Os métodos `num_components()` e `largest_component()` foram implementados com base em BFS, tendo complexidade temporal O(n + m). Aplicando-os aos datasets got_book1.csv e got_full.csv, verificou-se que ambos os grafos são conexos, ou seja, têm apenas **1 componente conexa**. A maior componente tem ordem **187** no got_book1.csv e **796** no got_full.csv, pelo que, nestes casos, a maior componente coincide com o grafo completo.

Em termos narrativos, isto mostra que as redes de personagens estão totalmente ligadas dentro de cada dataset. Comparando os dois livros, a rede torna-se mais extensa e mais integrada em got_full.csv, indicando um aumento da conectividade ao longo da saga.


“Escolheram-se dois personagens do grafo e verificou-se, através de BFS, que estão conectados. O caminho mínimo entre eles é a sequência de vértices: ['Gorne', 'Jon-Snow', 'Theon-Greyjoy', 'Euron-Greyjoy', 'Nute']
