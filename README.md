Documentação
Introdução
Este documento descreve o código SQL para criar um banco de dados que atenda aos requisitos de um sistema de gerenciamento de compras e vendas. O sistema inclui cadastros de usuários, pessoas físicas e jurídicas, produtos e registros de movimentações de compra e venda.

Estrutura do Banco de Dados
O banco de dados é composto por seis tabelas:

Usuarios: Armazena informações sobre os usuários do sistema, como nome de usuário, senha e tipo de usuário (por exemplo, operador, administrador).
Pessoas: Contém dados comuns a todas as pessoas, como nome, tipo (física ou jurídica), endereço, telefone e email.
Produtos: Registra informações sobre os produtos disponíveis para compra e venda, como nome, quantidade em estoque e preço de venda.
MovimentosCompra: Registra as compras realizadas, incluindo detalhes como o produto comprado, a quantidade, o preço unitário e o fornecedor (pessoa jurídica).
MovimentosVenda: Registra as vendas efetuadas, incluindo detalhes como o produto vendido, a quantidade e o comprador (pessoa física).
PessoasFisicas e PessoasJuridicas: São tabelas auxiliares que armazenam os detalhes específicos de pessoas físicas (CPF) e jurídicas (CNPJ).
Funcionalidades do Código
O código SQL inclui as seguintes funcionalidades:

Criação das tabelas necessárias para armazenar os dados do sistema.
Inserção de dados básicos de usuários, pessoas (físicas e jurídicas) e produtos.
Consultas sobre os dados inseridos, fornecendo informações como detalhes das pessoas físicas e jurídicas, movimentações de entrada e saída, valores totais de entradas e saídas por produto, operadores sem movimentações de entrada, valores totais de entrada e saída agrupados por operador e valor médio de venda por produto.
Utilização
Este código SQL pode ser executado em um ambiente de gerenciamento de banco de dados compatível com SQL Server, como o SQL Server Management Studio. Após a execução do código, o banco de dados estará pronto para uso pelo sistema de gerenciamento de compras e vendas.
