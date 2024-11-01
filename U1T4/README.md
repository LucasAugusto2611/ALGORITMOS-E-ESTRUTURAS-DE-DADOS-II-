# Análise das Paradas de Ônibus em Natal-RN

## Objetivo
Este projeto visa analisar a rede de paradas de ônibus em Natal-RN e identificar as paradas mais próxima e mais distante da Universidade Federal do Rio Grande do Norte (UFRN).

## Dados Utilizados
- **Fonte**: Dados do OpenStreetMap (OSM)
- **Localização**: Paradas de ônibus em Natal-RN
- **Referência**: Coordenadas da UFRN

## Obtenção das Paradas de Ônibus
As paradas de ônibus foram extraídas utilizando a biblioteca [OSMnx](https://osmnx.readthedocs.io/), que permite acessar dados geoespaciais do OpenStreetMap.

## Cálculo da Distância
A distância entre as paradas de ônibus e a UFRN foi calculada usando a biblioteca [Shapely](https://shapely.readthedocs.io/), que fornece funções geométricas para medir distâncias.

## Resultados
- **Parada de Ônibus Mais Próxima da UFRN**: 
  - Nome: [incluir nome]
  - Coordenadas: [incluir coordenadas]

- **Parada de Ônibus Mais Distante da UFRN**: 
  - Nome: [incluir nome]
  - Coordenadas: [incluir coordenadas]

## Visualização
Os resultados foram visualizados em um gráfico que mostra a localização das paradas de ônibus em relação à UFRN, destacando as paradas mais próxima e mais distante.

![Gráfico das Paradas de Ônibus](U1T4/paradas%20ufrn.png) <!-- Substitua pelo caminho da imagem gerada -->

## Ferramentas e Bibliotecas Utilizadas
- [OSMnx](https://osmnx.readthedocs.io/)
- [Geopandas](https://geopandas.org/)
- [Matplotlib](https://matplotlib.org/)
- [Shapely](https://shapely.readthedocs.io/)

## Como Executar o Código
1. Clone este repositório:
   ```bash
   git clone https://github.com/seu_usuario/seu_repositorio.git
