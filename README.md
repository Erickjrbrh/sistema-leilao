# Sistema de Leilão

Este projeto é um sistema de leilões desenvolvido em Java, com banco de dados MySQL. Ele permite o controle de produtos disponíveis para leilão, seus valores e status (vendido ou à venda). A aplicação foi criada com foco em automatizar e organizar os processos de uma casa de leilões.

## Funcionalidades

- Cadastro de produtos para leilão
- Visualização dos itens com seus valores e status
- Controle sobre produtos vendidos e disponíveis

## Banco de Dados

O banco de dados utilizado se chama `uc11` e possui a tabela `produtos`, com os seguintes campos:

- `id` (identificador único, auto-incremento)
- `nome` (nome do produto)
- `valor` (valor do produto)
- `status` (Vendido / A Venda)

Exemplo de dados iniciais:
- PS4 – R$1500 – Vendido
- Xbox 360 – R$800 – Vendido
- iPhone 12 – R$4800 – Vendido
- PS2 – R$400 – A Venda

## Tecnologias utilizadas

- Java (IDE NetBeans)
- MySQL (phpMyAdmin / MariaDB)
- JDBC para conexão com o banco
- Git & GitHub para versionamento
