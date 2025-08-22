# Análise Exploratória de Dados em Linguagem Python Para a Área de Varejo

Este projeto contém um notebook Jupyter (`DSA_Projeto02.ipynb`) que realiza uma análise exploratória de dados (EDA - Exploratory Data Analysis) para um conjunto de dados de varejo. O objetivo é responder a uma série de perguntas de negócio usando a linguagem Python e suas bibliotecas de ciência de dados.

## Sobre o Projeto

O projeto foi desenvolvido como parte do curso "Fundamentos de Linguagem Python Para Análise de Dados e Data Science" da Data Science Academy. Ele demonstra a aplicação de técnicas de EDA para extrair insights valiosos de um dataset de vendas.

## Conjunto de Dados

O conjunto de dados utilizado está em formato CSV e se chama `dataset.csv`. Ele contém informações sobre pedidos de vendas, incluindo:

-   **ID_Pedido**: Identificador único do pedido.
-   **Data_Pedido**: Data em que o pedido foi realizado.
-   **ID_Cliente**: Identificador do cliente.
-   **Segmento**: Segmento do cliente (ex: Consumer, Corporate, Home Office).
-   **Pais**: País do pedido.
-   **Cidade**: Cidade do pedido.
-   **Estado**: Estado do pedido.
-   **ID_Produto**: Identificador do produto.
-   **Categoria**: Categoria do produto (ex: Furniture, Office Supplies, Technology).
-   **SubCategoria**: Subcategoria do produto.
-   **Valor_Venda**: Valor total da venda.

## Perguntas de Negócio Respondidas

O notebook explora e responde às seguintes perguntas de negócio, utilizando visualizações de dados para melhor compreensão:

1.  **Qual Cidade com Maior Valor de Venda de Produtos da Categoria 'Office Supplies'?**
    -   Essa análise identifica a cidade que mais contribui para a receita de uma categoria específica.

2.  **Qual o Total de Vendas Por Data do Pedido?**
    -   O resultado é demonstrado através de um gráfico de barras que mostra a evolução das vendas ao longo do tempo.

3.  **Qual o Total de Vendas Por Estado?**
    -   Um gráfico de barras visualiza o desempenho de vendas por estado.

4.  **Quais São as 10 Cidades com Maior Total de Vendas?**
    -   Um ranking das 10 cidades mais lucrativas é apresentado em um gráfico de barras.

5.  **Qual Segmento Teve o Maior Total de Vendas?**
    -   A distribuição das vendas entre os segmentos de clientes é mostrada em um gráfico de pizza.

6.  **Qual o Total de Vendas Por Segmento e Por Ano?**
    -   Um gráfico de barras agrupadas ilustra a performance de cada segmento por ano.

7.  **Quantas Vendas Receberiam 15% de Desconto?**
    -   Uma análise de simulação de desconto é realizada para responder a esta pergunta.

8.  **Qual Seria a Média do Valor de Venda Antes e Depois do Desconto de 15%?**
    -   Os resultados são comparados visualmente através de um gráfico de barras.

9.  **Qual a Média de Vendas Por Segmento, Por Ano e Por Mês?**
    -   Um gráfico de linha mostra a tendência mensal das vendas para cada segmento ao longo dos anos.

10. **Qual o Total de Vendas Por Categoria e SubCategoria, Considerando Somente as Top 12 SubCategorias?**
    -   A análise é apresentada em um gráfico de pizza aninhado, mostrando a relação entre categorias e subcategorias.

## Tecnologias Utilizadas

-   **Python 3.9.13**
-   **Jupyter Notebook**
-   **Pandas**: Para manipulação e análise de dados.
-   **NumPy**: Para operações numéricas.
-   **Matplotlib**: Para a criação de gráficos e visualizações.
-   **Seaborn**: Para visualizações estatísticas mais atraentes.

## Como Executar o Projeto

1.  Certifique-se de ter o Jupyter Notebook e as bibliotecas necessárias instaladas.
2.  Baixe ou clone este repositório.
3.  Abra o arquivo `DSA_Projeto02.ipynb` em seu Jupyter Notebook.
4.  Execute as células do notebook sequencialmente para replicar a análise.

Este projeto é um excelente exemplo de como a análise exploratória de dados pode ser aplicada em um cenário de negócio real para tomar decisões informadas.
