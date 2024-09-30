# Documentação das bases de dados

Para este estudo, foram utilizadas duas bases de dados: uma para dados de vendas ("dados_vendas.csv") e outra com informações dos clientes ("dados_clientes.csv"). Ambas possuem um ID único para cada cliente, permitindo que ambas tenham uma chave comum de relacionamento. As bases foram geradas a partir de modificações de bases de dados públicos encontradas no site Kaggle. Abaixo, temos os links para as bases originais.

[Dados Transacionais](https://www.kaggle.com/datasets/ilkeryildiz/online-retail-listing)

[Dados dos Clientes](https://www.kaggle.com/datasets/mohdshahnawazaadil/sales-prediction-dataset/data)

## Dados Vendas

A base de dados de vendas possui as seguintes informações:

-   **Invoice:** Número que identifica unicamente cada transação, ID de transação.

-   **StockCode**: Número que identifica unicamente cada produto, ID do produto.

-   **Description:** Nome do produto.

-   **Quantity**: Quantidade de cada produto por transação

-   **InvoiceDate:** Data da transação.

-   **Customer ID**: Id que identifica unicamente cada usuário(cliente).

## Dados dos Clientes

A base de dados dos clientes possui informações dos clientes que realizaram transações naquele período.

-   **customer.name:** Nome do usuário.

-   **customer.e.mail:** E-mail do usuário.

-   **country:** País do usuário.

-   **gender:** Gênero do usuário, onde 1 é masculino e 0 feminino.

-   **age:** Idade em anos.

-   **annual.Salary:** Salário Anual.

-   **credit.card.bebt:** Divída do cartão de crédito.

-   **net.worth:** Patrimônio

-   **client_id:** Id que identifica unicamente cada usuário(cliente).
