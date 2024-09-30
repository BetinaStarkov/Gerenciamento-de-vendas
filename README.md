# Sistema de Gerenciamento de Vendas

## Descrição
Este projeto é um sistema básico de gerenciamento de vendas para uma loja. O sistema foi implementado em SQL e permite a administração de informações sobre clientes, produtos e vendas realizadas.

O sistema inclui funcionalidades para:

- Cadastro de clientes e produtos
- Registro de vendas
- Atualização de estoque
- Consultas detalhadas sobre vendas e clientes
- Atualização e remoção de dados

## Estrutura do Banco de Dados
### Tabelas Criadas
- **Clientes**: Armazena informações sobre os clientes da loja (ID, nome, e-mail e telefone).
- **Produtos**: Armazena informações sobre os produtos disponíveis (ID, nome, preço e quantidade em estoque).
- **Vendas**: Registra as transações de vendas realizadas (ID da venda, ID do cliente, ID do produto, quantidade e data).

### Relacionamentos
- A tabela **Vendas** faz referência às tabelas **Clientes** e **Produtos**, utilizando chaves estrangeiras para associar cada venda a um cliente e um produto específico.

## Comandos SQL Utilizados
- `CREATE DATABASE`: Para criar o banco de dados.
- `CREATE TABLE`: Para criar as tabelas de clientes, produtos e vendas.
- `INSERT INTO`: Para inserir dados de clientes, produtos e vendas.
- `SELECT`: Para realizar consultas ao banco de dados.
- `JOIN`: Para unir dados de tabelas diferentes em uma única consulta.
- `UPDATE`: Para atualizar dados, como a quantidade em estoque após uma venda ou informações de um cliente.
- `DELETE`: Para remover vendas do banco de dados.

## Funcionalidades Implementadas

1. **Criação de Banco de Dados e Tabelas**: Estruturação das tabelas necessárias para armazenar os dados dos clientes, produtos e vendas.
   
2. **Inserção de Dados**:
   - 3 clientes
   - 3 produtos
   - 5 registros de vendas

3. **Consultas**:
   - Todas as vendas realizadas, com nomes de clientes e produtos.
   - Todas as compras realizadas por um cliente específico.
   - Total de vendas realizadas por produto.

4. **Atualizações**:
   - Atualização de estoque após uma venda.
   - Atualização de informações de um cliente.

5. **Deleção**:
   - Deleção de uma venda específica.

## Como Utilizar

1. **Executar o Script SQL**:
   - O arquivo `sistema_vendas.sql` contém todos os comandos necessários para criar o banco de dados e tabelas, inserir os dados e realizar as operações.
   - Basta rodar o script no seu ambiente de banco de dados MySQL ou MariaDB.

2. **Consultas e Operações**:
   - Após a criação das tabelas e a inserção de dados, as consultas e operações de atualização/deleção podem ser realizadas conforme descrito no arquivo SQL.

## Pré-requisitos

- **MySQL** ou **MariaDB** instalado no seu ambiente de desenvolvimento.
- Um cliente de banco de dados (ex: MySQL Workbench, DBeaver) para executar os comandos SQL.

## Estrutura do Projeto
