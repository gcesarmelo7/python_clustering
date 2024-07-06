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

Os dados fornecidos possuem informações de transações de compras de uma loja de
e-commerce em 38 países e territórios, com mais de 4.000 clientes únicos e mais de 540.000 transações.

**Atenção:** as datas estão no formato MM/DD/YYYY HH:mm:ss; existem dados nulos que
precisam ser tratados antes da realização da análise; por mais que os códigos de
identificação sejam numéricos, o modelo não pode considerá-los como grandezas
numéricas.

