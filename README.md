# Desafio-Dio-Randstad-banco-de-dados-ecommerce-
## 🧠 Descrição do Projeto Lógico 
Este projeto apresenta o modelo lógico de um sistema de gestão de pedidos, produtos e fornecedores, voltado para operações comerciais que envolvem clientes (físicos e jurídicos), vendedores terceiros, fornecedores e controle de estoque. O banco de dados foi modelado para refletir o ciclo completo de uma transação comercial, desde o cadastro de clientes até a entrega e pagamento dos pedidos.

## 🎯 Objetivo
O objetivo principal é fornecer uma estrutura relacional robusta que permita:

* Gerenciar clientes e suas classificações (físico ou jurídico)

* Registrar pedidos e associá-los a produtos, entregas e pagamentos

* Controlar o estoque de produtos em diferentes locais

* Relacionar produtos a fornecedores e vendedores terceiros

* Simular cenários reais como atrasos, cancelamentos e reembolsos

## 🧱 Estrutura das Entidades
* **Cliente:** Armazena dados pessoais e comerciais, com especialização em pessoa física (cpf) e jurídica (cnpj).

* **Pedido:** Registra compras feitas por clientes, com status e valor total.

* **Produto:** Catálogo de itens disponíveis para venda, com descrição e preço.

* **Pedido_Produto:** Tabela de relacionamento que define quais produtos estão em cada pedido e suas quantidades.

* **Entrega:** Controla o envio dos pedidos, com rastreio, tipo de entrega e status logístico.

* **Pagamento:** Registra o status e método de pagamento (cartão, pix ou boleto).

* **Estoque:** Define os locais físicos onde os produtos estão armazenados.

* **Produto_Estoque:** Relaciona produtos aos estoques com controle de quantidade.

* **Fornecedor:** Empresas que fornecem os produtos, com dados comerciais.

* **Distribui_Produto:** Relaciona fornecedores aos produtos que distribuem.

* **Vendedor_Terceiro:** Representa vendedores externos que comercializam produtos.

* **Produto_Vendedor_Terceiro:** Relaciona produtos aos vendedores terceiros, com preço e quantidade específicos.

## 🔗 Relacionamentos

* Um cliente pode fazer vários pedidos.

* Cada pedido pode conter vários produtos.

* Cada produto pode estar em vários estoques e ser vendido por diferentes vendedores.

* Cada produto pode ser distribuído por um ou mais fornecedores.

* Cada pedido pode ter uma entrega e um pagamento associado.

  ## Link
  
  [Script SQL](https://github.com/marcelomoura85/Desafio-Dio-Randstad-banco-de-dados-ecommerce-/blob/main/Script%20banco%20de%20dados%20E-commerce%20desafio%20Dio-Randstad.pdf)

  [Dados de inserção no banco de dados:](https://github.com/marcelomoura85/Desafio-Dio-Randstad-banco-de-dados-ecommerce-/blob/main/Dados%20de%20insercao%20desafio%20banco%20de%20dados%20e-commerce%20Dio-Randstad.pdf)

 
 

