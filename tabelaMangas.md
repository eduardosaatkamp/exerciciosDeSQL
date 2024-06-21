# Tabelas para utilizar de treino para comandos de SQL

# Site para criar tabelas e realizar consultas SQL:

<a href="https://www.programiz.com/sql/online-compiler/">SQL Online Compiler</a><br>

-- Criação da tabela mangas
CREATE TABLE mangas (
    id INT PRIMARY KEY,
    titulo VARCHAR(255),
    estoque INT
);

-- Inserção de dados na tabela mangas
INSERT INTO mangas (id, titulo, estoque) VALUES
(1, 'Naruto', 1),
(2, 'One Piece', 0),
(3, 'Nisekoi', 0),
(4, 'Kis x Sis', 1);