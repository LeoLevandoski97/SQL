# SQL
CREATE DATABASE exercicios_mysql;

DROP DATABASE exercicios_mysql;

ALTER TABLE usuario ADD senha VARCHAR (255);

ALTER TABLE usuario DROP COLUMN senha;

INSERT INTO usuario (nome) VALUES ("Leo");

SELECT * FROM usuario;

UPDATE usuario SET nome = "Levandoski" WHERE nome = "Leo"



CREATE TABLE produtos (produtos VARCHAR (225),nome VARCHAR(225),idproduto VARCHAR (225),preco VARCHAR(225),codigo VARCHAR(225))

INSERT INTO produtos (produtos,nome,idproduto,preco,codigo) VALUES ("Legumes","Batata",0001,3.00,5432);

INSERT INTO produtos (produtos,nome,idproduto,preco,codigo) VALUES ("Doces","Chocolate",0002,5.00,0432);

INSERT INTO produtos (produtos,nome,idproduto,preco,codigo) VALUES ("Frutas","Maça",0003,2.00,3478);

INSERT INTO produtos (produtos,nome,idproduto,preco,codigo) VALUES ("Massas","Macarrão",0004,4.00,9888);

INSERT INTO produtos (produtos,nome,idproduto,preco,codigo) VALUES ("Frutas","Morango",0005,8.00,9008);

INSERT INTO produtos (produtos,nome,idproduto,preco,codigo) VALUES ("Doces","Doce de leite",0006,2.00,2344);

INSERT INTO produtos (produtos,nome,idproduto,preco,codigo) VALUES ("Alimentos","Arroz",0007,20.00,6547);

INSERT INTO produtos (produtos,nome,idproduto,preco,codigo) VALUES ("Alimentos","Feijão",0008,7.90,8766);

INSERT INTO produtos (produtos,nome,idproduto,preco,codigo) VALUES ("Temperos","Ajinomoto",0009,3.00,9865);

INSERT INTO produtos (produtos,nome,idproduto,preco,codigo) VALUES ("Frutas","Tomate",0010,4.00,4325);
