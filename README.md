# Banco Dados E-Commerce: Desafio Bootcamp Suzano - Refinando o Banco de Dados
Modelagem de Banco de Dados para um E_Commerce - Ministrado por Juliana Mascarenhas

# Design do Projeto Elaborado no MySql Workbench

# 1) Esquema do Cenário a ser Modelado
## 1.1) Clientes
- Clientes realizam pedidos
- Clientes podem ser Pessoa Física (Clientes) ou Pessoa Jurídica (Fornecedores e Vendedores Terceiros )
    - EER: Superclasses e Subclasses
  -   Atributos da Superclasse
  -   Atributos das Subclasses
    
- Criação de Entidade: Formas de pagamento
  - Cartão de Crédito e Boleto Bancário: Atributos diferentes   

## 1.2) Produtos
- Produtos estão contidos no estoque
- Produtos fornecidos por: fornecedores ou vendedores (terceiro)
- Produtos estão no estoque do fornecedor
- Produtos estão em categorias de produtos
- Produto tem valor

## 1.3) Pedidos
- Status do Pedido
- Valor Total do Pedido
- Quantidade de Cada produto

## 1.4) Informação Geográfica
- Data Type: geometry (poligon)
- Geospacializar as informações de vendas de produtos, clientes e fornecedores
- Utilização de geocódigo do IBGE para relacionar com tabelas de dados sociodemográficos do IBGE

# 2) Modelo Do Banco de Dados - MySql Workhbench

Segue abaixo o link para o modelo:


https://github.com/AndLSantos/Banco_Dados_ECommerce/blob/main/ECommerce_Bootcamp_Suzano.png

















