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



Insight 1 — Concentração de vendas em São Paulo
<img width="1464" height="830" alt="image" src="https://github.com/user-attachments/assets/f96fd7fb-2417-41e7-8057-e4ca48d57ef0" />
As análises demonstraram que o estado de São Paulo concentra o maior volume de vendas do marketplace Olist, seguido por RJ e MG.


Insight 2 — Categorias com maior faturamento
<img width="1139" height="535" alt="image" src="https://github.com/user-attachments/assets/a2325c1b-23b6-4057-9314-22def5693772" />
As categorias beleza_saude e relogios_presentes apresentaram os maiores volumes de vendas dentro do dataset analisado.

Insight 3 — Concentração de vendas em poucos vendedores
<img width="1464" height="445" alt="image" src="https://github.com/user-attachments/assets/c04f3df3-f3f7-42f0-b93d-4ec56265391f" />
Foi identificado que poucos vendedores concentram grande parte do faturamento total da plataforma.
