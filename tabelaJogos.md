# Tabelas para utilizar de treino para comandos de SQL

# Site para criar tabelas e realizar consultas SQL:

<a href="https://www.programiz.com/sql/online-compiler/">SQL Online Compiler</a><br>

-- Criação da tabela
CREATE TABLE jogos (
    id INT PRIMARY KEY,
    titulo VARCHAR(255),
    classificacao VARCHAR(2)
);

-- Inserção de dados na tabela
INSERT INTO jogos (id, titulo, classificacao) VALUES
(1, 'Assassins Creed Valhalla', '18'),
(2, 'Watch Dogs Legion', '18'),
(3, 'Dirt 5', '10'),
(4, 'Super Mario 3D World', 'L'),
(5, 'Super Lucky''s Tale', 'L'),
(6, 'Super Mario 3D World', 'L');

-- comandos 
SELECT * FROM jogos WHERE classificacao = '18';
DELETE FROM jogos WHERE id = 6;
SELECT * FROM jogos;