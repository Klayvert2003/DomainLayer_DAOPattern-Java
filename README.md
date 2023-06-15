# DomainLayer_DAOPattern-Java

Este projeto consiste em uma aplicação Java que permite o registro de contatos e sua exibição em listas, onde é possível visualizar o nome e o seu email ao executar os métodos.

## Tecnologias Utilizadas:
- Java
- DAO

## Funcionalidades
- Cadastro de contatos com nome e email;
- Exibição de todas as presenças cadastradas em uma lista via shell;

## Como executar o projeto

Para executar o projeto, siga os seguintes passos:

1. Clone o repositório:
git clone https://github.com/Klayvert2003/DomainLayer_DAOPattern-Java.git

2. Crie a base de dados com nome 'fatec' e crie a tabela com o seguinte script:
CREATE TABLE contato (
    id INT PRIMARY KEY AUTO_INCREMENT,
    nome VARCHAR(100) NOT NULL,
    email VARCHAR(100) NOT NULL
);

5. Abra o projeto no Visual Studio Code(com as extensões presentes no pacote Extension Pack for Java para compilar o java).

4. Clique no botão Run Java:

Remova os comentários dos métodos presentes na classe Playground.java para utilizá-los.