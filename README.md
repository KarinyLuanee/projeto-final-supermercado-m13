# Análise de Preços e Descontos — Supermercado Chileno

## Objetivo

Este projeto faz parte do Módulo 13, com foco em fundamentos da descoberta de dados. O objetivo foi aplicar estatística básica e visualização de dados para analisar preços e descontos de produtos de um supermercado do Chile.

## Base utilizada

A base `MODULO7_PROJETOFINAL_BASE_SUPERMERCADO.csv` contém 1.107 produtos, distribuídos em 7 categorias.

Principais colunas:

- `title`: nome do produto
- `Marca`: marca do produto
- `Preco_Normal`: preço normal do produto
- `Preco_Desconto`: preço com desconto
- `Preco_Anterior`: preço anterior
- `Desconto`: valor do desconto aplicado
- `Categoria`: categoria do produto

## Bibliotecas usadas

- pandas
- numpy
- matplotlib
- plotly

## Análises realizadas

1. Leitura e verificação inicial da base.
2. Cálculo da média e mediana do preço normal por categoria.
3. Cálculo do desvio padrão por categoria.
4. Boxplot da categoria com maior variação de preço.
5. Gráfico de barras com a média de desconto por categoria.
6. Treemap interativo por categoria e marca.
7. Conclusão com principais insights da análise.

## Principais conclusões

- A categoria `lacteos` apresentou a maior variação de preços.
- Os outliers em `lacteos` parecem estar relacionados principalmente a embalagens maiores, como packs e leite em pó.
- `congelados` teve a maior média de desconto entre as categorias.
- `frutas`, `verduras` e `instantaneos-y-sopas` não apresentaram descontos na base analisada.

## Como executar

1. Baixe este repositório.
2. Mantenha o arquivo CSV na mesma pasta do notebook.
3. Instale as bibliotecas necessárias:

```bash
pip install -r requirements.txt
```

4. Abra o notebook `Profissao_Cientista_de_Dados_M13_Projeto.ipynb` no Jupyter Notebook, VS Code ou Google Colab.
5. Execute as células em ordem.

Observação: o treemap interativo também foi salvo no arquivo `treemap_desconto_categoria_marca.html`.
