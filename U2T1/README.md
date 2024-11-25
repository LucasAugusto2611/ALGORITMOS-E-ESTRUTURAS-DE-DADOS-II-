# Análise de Rede de Co-Autoria - PPgEEC

Este repositório contém o código utilizado para a análise da rede de co-autoria dos professores permanentes do Programa de Pós-Graduação em Engenharia Elétrica e de Computação (PPgEEC), conforme os requisitos do trabalho de Unidade 2.

## Objetivo
O objetivo deste trabalho é aplicar os conhecimentos de análise de redes para construir e analisar a rede de co-autoria dos professores do PPgEEC, utilizando o **Gephi** e técnicas de análise de redes, como centralidade, k-core, k-shell, e critérios de comunidade. 

### Requisitos
O trabalho foi dividido em três partes:

#### Requisito #01:
- Construção da rede de co-autoria.
- Geração de visualizações no **Gephi** com:
  - Vértices de tamanho proporcional à quantidade de vizinhos ou outra métrica relevante.
  - Cores baseadas em **Closeness Centrality**, **Betweenness Centrality**, ou **Eigenvector Centrality**.
  - Layout adequado para destacar a diferença nas cores dos vértices.
  
#### Requisito #02:
- Geração de uma figura destacando o **k-core** e **k-shell** da rede.
- Vértices com tamanho proporcional à métrica **degree**.

#### Requisito #03:
- Identificação de comunidades na rede.
- As cores dos vértices devem ser relacionadas a um critério de comunidade.
- O tamanho dos vértices deve ser proporcional a uma métrica de livre escolha.

## Estrutura do Repositório
- `notebooks/`: Contém os notebooks Jupyter usados para gerar e analisar os dados da rede.
- `scripts/`: Contém os scripts Python utilizados para processar os dados e gerar as análises.
- `data/`: Contém os arquivos de entrada (como o arquivo de co-autoria dos professores) e os resultados das análises (como os arquivos GEXF e CSV).
- `output/`: Contém os arquivos de saída gerados pelo **Gephi**, como as imagens das visualizações.

## Como Rodar o Código
1. **Clone este repositório** para sua máquina local:
   ```bash
   git clone https://github.com/seu-usuario/analise-rede-coautoria-ppgeec.git

