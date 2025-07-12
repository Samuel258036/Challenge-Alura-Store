# Análise de Desempenho das Lojas do Sr. João

Este projeto realiza uma análise detalhada do desempenho de quatro lojas fictícias pertencentes ao Sr. João. O objetivo é avaliar diversas métricas de negócio para auxiliar na tomada de decisão estratégica, especificamente na identificação de oportunidades de melhoria e na justificativa para a venda de uma das lojas.

## Dados

Os dados utilizados neste projeto são provenientes de arquivos CSV hospedados no GitHub, representando informações de vendas de cada uma das quatro lojas:

- Loja 1: ["https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science/refs/heads/main/base-de-dados-challenge-1/loja_1.csv"]
- Loja 2: ["https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science/refs/heads/main/base-de-dados-challenge-1/loja_2.csv"]
- Loja 3: ["https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science/refs/heads/main/base-de-dados-challenge-1/loja_3.csv"]
- Loja 4: ["https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science/refs/heads/main/base-de-dados-challenge-1/loja_4.csv"]

Cada arquivo CSV contém as seguintes colunas:

- **Produto:** Nome do produto vendido.
- **Categoria do Produto:** Categoria à qual o produto pertence.
- **Preço:** Preço unitário do produto.
- **Frete:** Custo do frete para a entrega.
- **Data da Compra:** Data em que a compra foi realizada.
- **Vendedor:** Nome do vendedor que realizou a venda.
- **Local da compra:** Estado onde a compra foi realizada.
- **Avaliação da compra:** Avaliação dada pelo cliente para a compra (de 1 a 5).
- **Tipo de pagamento:** Método de pagamento utilizado (cartão de crédito, boleto, etc.).
- **Quantidade de parcelas:** Número de parcelas no caso de pagamento parcelado.
- **lat:** Latitude do local da compra.
- **lon:** Longitude do local da compra.

## Análise Realizada

A análise exploratória e as métricas calculadas incluem:

1.  **Faturamento Total por Loja:** Cálculo da soma total dos preços dos produtos vendidos em cada loja.
2.  **Vendas por Categoria de Produto:** Contagem da quantidade de vendas para cada categoria de produto em cada loja e no total.
3.  **Média de Avaliação da Compra por Loja:** Cálculo da média das avaliações dos clientes para cada loja.
4.  **Produtos Mais e Menos Vendidos:** Identificação dos produtos com maior e menor volume de vendas em cada loja.
5.  **Frete Médio por Loja:** Cálculo do custo médio do frete por loja.

## Visualizações

O notebook inclui as seguintes visualizações para facilitar a compreensão dos dados:

- **Gráfico de Barras do Faturamento por Loja:** Compara o faturamento total de cada uma das quatro lojas.
- **Gráficos de Pizza da Porcentagem de Vendas por Categoria (Individual e Total):** Mostram a distribuição percentual das vendas entre as diferentes categorias de produto para cada loja e para o conjunto total de vendas.
- **Gráfico de Dispersão da Média de Avaliação por Loja:** Visualiza a média de avaliação dos clientes para cada loja.

## Relatório e Conclusão

Com base nas métricas analisadas (faturamento, avaliação média e frete médio), o relatório aponta que a Loja 4 apresenta o menor faturamento e a segunda menor avaliação, embora tenha a melhor média de frete.

A **conclusão** sugere a venda da Loja 4 devido ao seu desempenho inferior em faturamento e avaliação. No entanto, ressalta a importância de investigar a logística eficiente da Loja 4 (evidenciada pelo menor frete médio) para replicar essas práticas nas outras lojas antes de tomar a decisão final.

Este README fornece um resumo conciso do projeto e suas principais descobertas. Para detalhes completos do código e da análise, consulte o notebook Python.
