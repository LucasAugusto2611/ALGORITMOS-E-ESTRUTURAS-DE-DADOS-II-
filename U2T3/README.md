Unidade 2 - Trabalho 3

📚 Algoritmos Clássicos: Dijkstra e Kruskal

Objetivo Geral

Explorar e implementar os algoritmos clássicos de Dijkstra e Kruskal aplicados à cidade de Natal-RN, com foco na solução de problemas de infraestrutura e transporte de forma eficiente.

🚀 Parte 1: Dijkstra

📝 Problema

Avaliar o desempenho do algoritmo de Dijkstra utilizando:

Uma implementação com heap mínima.

A solução do algoritmo implementada na biblioteca networkx.

Os resultados serão visualizados em mapas da cidade de Natal-RN.

🔨 Passos Realizados

Escolha de 10 pares de pontos de interesse (PoIs):

Exemplos: Aeroporto → Rodoviária, Ponta Negra → Centro Histórico.

Uso do OSMnx para:

Obter o grafo viário de Natal-RN.

Visualizar as rotas encontradas.

Comparar o desempenho entre:

Implementação de Dijkstra com heap mínima (código presente em dijkstra_min_heap.ipynb).

Implementação do networkx.

Visualizar os resultados:

Gerar mapas e analisar caminhos mais curtos.

📊 Resultados e Visualizações

Mapas com as rotas mais curtas para cada par de pontos de interesse.

Comparativo de desempenho:

Tempo de execução.

Precisão dos caminhos encontrados.

⏱️ Complexidade

Implementação tradicional: O(V² + E).

Heap mínima: O((V + E) * log(V)).

📂 Arquivos

Notebook: dijkstra_min_heap.ipynb.

Mapas: Localizados na pasta figuras/dijkstra/.

🌐 Parte 2: Kruskal

📝 Problema

Aplicar o algoritmo de Kruskal para resolver problemas de infraestrutura em Natal-RN, gerando uma Árvore Geradora Mínima (MST).

📌 Cenários Analisados

Otimização de Infraestrutura:

Planejamento de redes de fibra óptica entre bairros de Natal.

Planejamento de Transporte:

Conectar grandes centros de transporte, como Aeroporto, Rodoviária, e estações de ônibus.

Rota Turística:

Criar rotas eficientes conectando principais atrações turísticas, como praias e museus.

🔨 Passos Realizados

Escolha de pontos de interesse (PoIs):

Exemplo: bairros, pontos turísticos, hubs de transporte.

Cálculo da MST utilizando Kruskal.

Visualização dos grafos:

Grafo original (todas as conexões).

Árvore Geradora Mínima (MST).

📊 Resultados e Visualizações

Comparativo entre a rede original e a MST.

Economia obtida em termos de custo total de conexões.

⏱️ Complexidade

Ordenação das arestas: O(E * log(E)).

Union-Find: O(E * α(V)), onde α(V) é o inverso da função de Ackermann.
