# 🚀 Análise de Desempenho de Algoritmos: `solver_closest` vs. `solver_kth_largest`

## 🎯 Objetivo

Este projeto tem como objetivo avaliar o desempenho de dois algoritmos de busca em listas grandes, **`solver_closest`** e **`solver_kth_largest`**, por meio da medição do **tempo de execução** em diferentes tamanhos de entrada. A análise compara os tempos médios de execução, considerando **intervalos de confiança** e gerando gráficos para visualização do desempenho.

## 📊 Metodologia

### Passos do Processo:

1. **Instrumentação dos Códigos**:  
   - Adição de medições de tempo utilizando o módulo `time` do Python para medir a execução de cada algoritmo.
   
2. **Execução com Tamanhos Variados de Vetores**:  
   - Testes realizados com vetores de tamanhos variados, desde pequenos (10) até grandes vetores (até \( 10^6 \)).

3. **Execuções Repetidas**:  
   - Cada experimento foi repetido **50 vezes** para garantir resultados confiáveis. O tempo médio de execução e o intervalo de confiança de 95% foram calculados para cada tamanho de vetor.

4. **Geração de Gráficos**:  
   - Gráficos foram gerados para mostrar a relação entre o **tamanho do vetor** e o **tempo de execução**, com **intervalos de confiança** representados por **barras de erro**.

## 🛠️ Como Executar

### Requisitos

Para rodar este projeto, você precisa de:

- Python 3.x
- Bibliotecas: `numpy`, `scipy`, `matplotlib`

Instale as dependências com o comando:

```bash
pip install numpy scipy matplotlib
