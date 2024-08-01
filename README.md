# Análise Livros de Ciência de Dados

## Descrição

Este projeto tem como objetivo analisar os livros relacionados à ciência de dados disponíveis na Amazon. O projeto envolve a coleta de dados usando técnicas de web scraping e a análise desses dados para entender as ~~tendências de vendas~~, preços, classificações e número de reviews. A análise busca identificar quais fatores influenciam a popularidade e o sucesso dos livros sobre ciência de dados.

## Objetivos

- Coletar dados de livros sobre ciência de dados na Amazon, incluindo título, autor, preço, classificação média, número de reviews e posição no ranking de mais vendidos.
- Realizar a limpeza e o processamento dos dados coletados.
- Analisar a distribuição de preços, classificações e número de reviews.
- Explorar correlações entre preço, classificação e popularidade dos livros.
- Visualizar os resultados da análise para obter insights significativos.

## Estrutura do Repositório
```markdown
├── data
│   ├── raw
│   ├── processed
├── notebooks
│   ├── 01_data_collection.ipynb
│   ├── 02_data_cleaning.ipynb
│   ├── 03_data_analysis.ipynb
│   ├── 04_data_visualization.ipynb
├── src
│   ├── data_collection.py
│   ├── data_cleaning.py
│   ├── data_analysis.py
│   ├── data_visualization.py
├── README.md
└── requirements.txt