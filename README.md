# clustering-olist
# Projeto de Segmentação de Clientes da Olist para definição de política comercial e de ações de marketing

O objetivo do trabalho é encontrar a melhor forma de agrupamento dos clientes da Olist (vendedores de marketplaces) para estabelecer política comercial e ações de marketing diferenciadas para cada grupo, visando aumentar o faturamento e melhorar o resultado da empresa.

# Contextualização do Problema

A Olist é uma empresa que auxilia vendedores a anunciar seus produtos nos principais marketplaces da internet (Amazon, Mercado Livre, Americanas, Carrefour, Submarino, Via Varejo, Casas Bahia, B2W Digital, Extra, Shoptime, Ponto Frio, Madeira Madeira e Zoom), fornecendo de forma centralizada ferramentas para cadastro e gestão de produtos e estoques; gestão de vendas, finanças e estratégia; gestão da logística de entregas; e melhoria das posições nos sites de venda com a alta reputação da Olist.

Atualmente, a empresa possui 3 planos comerciais:
* Olist lite: faturamento de até R$3.000,00, sem mensalidade, comissão de 21% por pedido.
* Olist pro: faturamento de R$3.000,00 a R$20.000,00, mensalidade de R$79,90, comissão de 19% por pedido.
* Olist Premium: faturamento acima de R$20.000,00, condições específicas para cada cliente.

A empresa gostaria de saber se essa divisão de clientes por faixas de faturamento é a mais adequada para estabelecer sua política comercial, além de obter insights para ações de marketing personalizadas de acordo com os perfis dos clientes, para aumentar seu faturamento e melhorar seu resultado.

# Bases de Dados

A Olist possui um conjunto de dados público disponível no kaggle . O conjunto de dados Brazilian E Commerce Public Dataset by Olist consiste de transações de clientes nos mais diversos marketplaces brasileiros. https://www.kaggle.com/olistbr/brazilian-ecommerce

A base principal é composta de uma série histórica de vendas com 99.441 pedidos emitidos entre setembro de 2016 e outubro de 2018.

Além desta, há bases auxiliares com detalhes sobre os produtos vendidos e os produtos de cada pedido, sobre os vendedores, sobre os compradores e os reviews dos compradores, sobre os pagamentos, e sobre dados de geolocalização. As duas últimas não serão utilizados em nosso estudo.

# Notebooks
Os notebooks do projeto foram criados em Spark no ambiente Databricks (https://community.cloud.databricks.com).
