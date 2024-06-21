# Tabelas para utilizar de treino para comandos de SQL

# Site para criar tabelas e realizar consultas SQL:

<a href="https://www.programiz.com/sql/online-compiler/">SQL Online Compiler</a><br>

```SQL 
-- Criação da tabela montadoras
CREATE TABLE montadoras (
    id INT PRIMARY KEY,
    nome VARCHAR(255),
    pais VARCHAR(255)
);

-- Inserção de dados na tabela
INSERT INTO montadoras (id, nome, pais) VALUES
(1, 'Fiat', 'Itália'),
(2, 'Chrysler', 'EUA'),
(3, 'BMW', 'Alemanha'),
(4, 'Nissan', 'Japão');