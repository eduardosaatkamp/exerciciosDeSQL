# Tabelas para utilizar de treino para comandos de SQL

# Site para criar tabelas e realizar consultas SQL:

<a href="https://www.programiz.com/sql/online-compiler/">SQL Online Compiler</a><br>

-- Criação da tabela produtos
CREATE TABLE produtos (
    id INT PRIMARY KEY,
    nome VARCHAR(255),
    preco DECIMAL(10, 2)
);

-- Inserção de dados na tabela
INSERT INTO produtos (id, nome, preco) VALUES
(1, 'Xbox Series X', 4599),
(2, 'PlayStation 5', 4699),
(3, 'Nintendo Switch', 2999);