# Tabelas para utilizar de treino para comandos de SQL

# Site para criar tabelas e realizar consultas SQL:

<a href="https://www.programiz.com/sql/online-compiler/">SQL Online Compiler</a><br>

-- Criação da tabela contatos
CREATE TABLE contatos (
    id INT PRIMARY KEY,
    nome VARCHAR(255),
    telefone VARCHAR(20),
    email VARCHAR(255)
);

-- Inserção de dados na tabela contatos
INSERT INTO contatos (id, nome, telefone, email) VALUES
(1, 'Marcelo', '11 9888-4444', 'marcelo@email.com'),
(2, 'Juliana', '21 9888-4444', 'juliana@email.com'),
(3, 'Amanda', '31 9888-4444', 'amanda@email.com'),
(4, 'Gustavo', '41 9888-4444', 'gustavo@email.com');