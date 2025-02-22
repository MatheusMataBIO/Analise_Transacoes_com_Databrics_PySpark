# 📦 Projeto de ETL e Análise de Transações Financeiras

## 📌 Descrição
Este projeto tem como objetivo realizar um processo de **ETL (Extract, Transform, Load)** e análise de um dataset de transações financeiras utilizando **Databricks** e **PySpark**. O foco principal é extrair, limpar e transformar os dados para, posteriormente, calcular o gasto total por cliente e identificar os 3 clientes com maiores gastos.

## Conteúdo do Projeto

- 📂 **Dataset:**  
  Um arquivo CSV contendo 100 linhas e 6 colunas, com os seguintes campos:
  - `transaction_id`: ID da transação.
  - `date`: Data da transação.
  - `customer_id`: ID do cliente.
  - `amount`: Valor da transação.
  - `category`: Categoria da transação (ex.: Alimentação, Transporte, Lazer, Educação, Saúde).
  - `payment_method`: Método de pagamento (ex.: Cartão de Crédito, Cartão de Débito, Dinheiro, Pix).

- 🚀 **Problema Proposto:**  
  1. Carregar e tratar o dataset utilizando PySpark.
  2. Realizar a limpeza dos dados (verificação de formatação, valores nulos, duplicatas).
  3. Calcular o total gasto por cada cliente e formatar o resultado com 2 casas decimais.
  4. Identificar os 3 clientes com maior gasto.
  
## Tecnologias Utilizadas

- **Databricks:** Plataforma para análise de dados e execução de notebooks.
- **PySpark:** Framework para processamento distribuído de dados.
- **Pandas:** Utilizado inicialmente para a criação do dataset.

## 📈 Conclusão

Este projeto demonstra a aplicação de técnicas de ETL e análise de dados utilizando Databricks e PySpark, desde a ingestão e validação dos dados até a execução de análises financeiras. 
