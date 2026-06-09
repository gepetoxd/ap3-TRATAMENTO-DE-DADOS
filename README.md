# Ap3-TRATAMENTO-DE-DADOS
# Dashboard Analítico de E-commerce Olist

## Descrição do Projeto

Este projeto foi desenvolvido para a disciplina de Tratamento e Análise de Dados do curso de Análise e Desenvolvimento de Sistemas da Faculdade Princesa do Oeste (FPO).

O objetivo principal foi construir um dashboard analítico utilizando Power BI para analisar dados do marketplace Olist, permitindo a visualização de métricas de vendas, desempenho geográfico, categorias de produtos, vendedores e indicadores operacionais.

## Equipe 
-João Pedro Mota Saldanha De Freitas 
-Pedro Caike Marinho Feitosa

O projeto contempla:
- Tratamento e modelagem de dados
- Construção de esquema estrela
- Criação de medidas DAX
- Desenvolvimento de dashboards interativos
- Análise visual e geográfica de dados

---

## Tecnologias Utilizadas

- Power BI
- Power Query
- DAX
- GitHub

---

## Fontes de Dados

### Kaggle
Dataset principal utilizado no projeto:

https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce

### IBGE
Dados auxiliares para análise geográfica:

https://www.ibge.gov.br/cidades-e-estados

---

## Estrutura do Repositório

dados/
├── Dim_CategoriaTraducao.csv
├── Dim_Clientes.csv
├── Dim_Geolocalizacao.csv
├── Dim_Produtos.csv
├── Dim_Vendedores.csv
├── Fac_OrderItems.csv
├── Fac_Orders.csv
├── Fac_Pagamentos.csv
└── Fac_Reviews.csv

dashboard/
└── Analise_Ecommerce_Olist.pbix

scripts/
└── tratamento_powerquery.txt

apresentacao/
└── Documentacao_Projeto.pdf
