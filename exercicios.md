## AdventureWorks – CRUD Exercises (SQLite)

Este material contém 20 exercícios práticos de CRUD (Create, Read, Update, Delete) utilizando o banco AdventureWorks em SQLite.

Objetivo: treinar manipulação de dados utilizando SQL em um banco relacional realista.

Estrutura utilizada

Principais tabelas usadas nos exercícios:

Product

Customer

SalesOrderHeader

SalesOrderDetail

### Parte 1 — READ (Consultas)
Exercício 1

Liste todos os registros da tabela Product.

Exercício 2

Liste apenas as seguintes colunas da tabela Product:

Name

ProductNumber

ListPrice

Exercício 3

Liste os 10 produtos mais caros.

Ordene pelo preço (ListPrice) do maior para o menor.

Exercício 4

Liste todos os produtos com preço maior que 1000.

Mostre:

Name

ListPrice

Exercício 5

Liste todos os clientes da tabela Customer.

Mostre:

FirstName

LastName

EmailAddress

### Parte 2 — CREATE (Inserção de dados)
Exercício 6

Insira um novo produto na tabela Product com os seguintes valores:

Name: Training Bike
ProductNumber: TR-001
ListPrice: 1200
Exercício 7

Insira um segundo produto:

Name: Training Helmet
ProductNumber: TR-002
ListPrice: 150
Exercício 8

Insira um terceiro produto:

Name: Training Gloves
ProductNumber: TR-003
ListPrice: 45
Exercício 9

Insira um novo cliente fictício na tabela Customer.

Use:

FirstName: Ana
LastName: Silva
EmailAddress: ana.silva@empresa.com
Exercício 10

Insira outro cliente fictício:

FirstName: Carlos
LastName: Pereira
EmailAddress: carlos.pereira@empresa.com

### Parte 3 — UPDATE (Atualização)
Exercício 11

Atualize o preço do produto Training Bike para:

1300
Exercício 12

Atualize o preço do produto Training Helmet para:

180
Exercício 13

Atualize o preço do produto Training Gloves para:

60
Exercício 14

Atualize o email do cliente Ana Silva para:

ana.silva@training.com
Exercício 15

Aumente o preço de todos os produtos em 10%.

### Parte 4 — DELETE (Remoção)
Exercício 16

Remova o produto:

Training Gloves
Exercício 17

Remova o cliente:

Carlos Pereira
Exercício 18

Remova todos os produtos com preço maior que 5000.

Exercício 19

Remova todos os produtos cujo ProductNumber começa com:

TR-
Exercício 20

Remova todos os clientes cujo email termina com:

@training.com
Boas práticas (importante)

Antes de executar UPDATE ou DELETE, sempre verifique os registros afetados:

SELECT *
FROM tabela
WHERE condição;

Isso evita alterar ou remover dados incorretamente.