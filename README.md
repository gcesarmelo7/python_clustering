<img align="right" width="100" height="110" src="images/icon_python.png"/>

<img align="right" width="70" height="70" src="images/icon_seaborn.png"/>

# Criando um modelo para a análise das métricas RFM em Python
<sub> Elaborando um modelo com algoritmo de clusterização </sub>

> Você deverá utilizar um modelo de Clustering para criar um sistema de agrupamento de perfis de clientes para um e-commerce. Deverá analisar o modelo mais eficiente, capaz de tornar as análises mais simplificadas para a empresa.

## 1. Contexto

Você foi contratado por uma empresa de e-commerce que está buscando entender
melhor o comportamento de seus clientes para personalizar as suas campanhas de
marketing. Para isso, a empresa disponibilizou uma base de dados em csv contendo dados sobre clientes, produtos e transações da loja realizadas entre os anos de 2010 e 2011.

Com base nesses dados, ***você precisa agrupar os clientes em clusters com base em
seu comportamento de compra.*** Isso irá permitir identificar padrões e características em
comum entre os clientes, como:

- [X] Clientes que compram os mesmos produtos;
- [X] Clientes que possuem a mesma frequência de compras;
- [X] Clientes que gastam mais dinheiro em suas compras.

A partir desses clusters, gere insights para que a empresa possa segmentar melhor a
sua base de clientes e personalizar as suas campanhas de marketing, ***direcionando
promoções e ofertas aos clientes com base no comportamento de compras.***

## 2. Sobre os dados

Acesse os dados aqui: [link](https://www.kaggle.com/datasets/carrie1/ecommerce-data)

Os dados fornecidos possuem informações de **transações de compras de uma loja de
e-commerce em 38 países e territórios, com mais de 4.000 clientes únicos e mais de 540.000 transações.**

Abaixo o dicionário e uma breve descrição dos dados:

| Coluna       | Descrição                                | Tipo     |
|--------------|------------------------------------------|----------|
| InvoiceNo    | Identificação da transação               | Int      |
| StockCode    | Código de estoque do produto             | String   |
| Description  | Descrição do produto                     | String   |
| Quantity     | Quantidade de produtos por transação     | Int      |
| InvoiceDate  | Data da transação                        | Datetime |
| UnitPrice    | Preço unitário do produto                | Float    |
| CustomerID   | Identificação do cliente                 | Int      |
| Country      | País de origem da transação              | String   |

Dessa forma, desenvolva um modelo de clusterização que seja capaz de agrupar os clientes
conforme o seu comportamento de compras levando em consideração a métrica RFM.
Analise os clusters obtidos para identificar o perfil de cliente, como padrões e
características em comum para determinar o seu comportamento de compra. Utilize
gráficos e visualizações para auxiliar na análise.

*É essencial informar os insights obtidos e as recomendações de ações futuras para que a
empresa possa colocá-los em prática.*

## 3. Etapas do desenvolvimento

:pencil2: ***Etapa 01) Análise exploratória dos dados***

- a. Carregue a base de dados;
- b. Realize uma descrição estatística dos dados;
- c. Visualize as distribuições e identifique a relevância das colunas para a análise;
- d. Verifique a presença de dados nulos, duplicados, outliers e demais inconsistências
nos dados.

:pencil2: ***Etapa 02) Pré-processamento dos dados***

- a. Realize a normalização dos dados;
- b. Faça uma seleção das variáveis mais relevantes para o modelo;
- c. Remova os dados nulos, duplicados, outliers e inconsistentes.

:pencil2:***Etapa 03) Selecione um algoritmo de clusterização***

- a. Escolha um algoritmo adequado para base de dados, como o K0Means, DBSCAN,
Hierarquia ou Mean Shift;
- b. Encontre a quantidade ideal de clusters através dos métodos de Elbow ou
Silhouette Score;
- c. Implemente o algoritmo escolhido.

:pencil2: ***Etapa 04) Analise os clusters obtidos***

- a. Identifique os padrões e características em comum entre os clientes;
- b. Plote gráficos para auxiliar na análise.

:pencil2: ***Etapa 05) Interpretação dos resultados obtidos***

- a. Descreva o perfil de compras dos clientes de cada cluster;
- b. Justifique como essa análise pode ser útil para empresa para segmentação de seus clientes e personalização das campanhas de marketing;
- c. Sugira ações possíveis com base nas ações realizadas.


