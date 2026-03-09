# AdventureWorks SQL Training

![SQL](https://img.shields.io/badge/SQL-training-blue)
![SQLite](https://img.shields.io/badge/database-SQLite-green)
![VSCode](https://img.shields.io/badge/editor-VSCode-blue)

Projeto criado para treinamento prático de **SQL** utilizando o banco de
dados **AdventureWorks** em **SQLite**.

Este repositório permite praticar consultas SQL em um banco relacional
realista usado amplamente em treinamentos de **Data Analytics**, **Data
Engineering** e **Business Intelligence**.

------------------------------------------------------------------------

# Visão Geral

O objetivo deste projeto é fornecer:

-   Um banco AdventureWorks convertido para SQLite
-   Exercícios progressivos de SQL
-   Um ambiente simples para treinamento utilizando VSCode
-   Simulação de problemas comuns de análise de dados

Este material é ideal para:

-   Data Analysts
-   Data Engineers iniciantes
-   Estudantes de SQL
-   Treinamentos internos em empresas

------------------------------------------------------------------------

# Estrutura do Projeto

    adventureworks-sql-training
    │
    ├── database
    │   └── adventureworks.db
    │
    ├── exercises
    │   └── exercises.md
    │
    ├── images
    │   ├── schema.png
    │   ├── vscode_connection.png
    │   └── query_example.png
    │
    └── README.md

------------------------------------------------------------------------

# Database Schema

![Database](images/AdventureWorksLT.png)


O banco simula um sistema de vendas contendo tabelas como:

-   Customer
-   Product
-   SalesOrderHeader
-   SalesOrderDetail

Esse modelo representa um cenário típico de **e-commerce** ou **ERP
corporativo**.

------------------------------------------------------------------------

# Instalação

## 1. Instalar Visual Studio Code

Baixe o editor:

https://code.visualstudio.com/

------------------------------------------------------------------------

## 2. Instalar extensão Database Client

1.  Abra o VSCode
2.  Pressione **Ctrl + Shift + X**
3.  Pesquise por **Database Client**
4.  Instale a extensão

------------------------------------------------------------------------

# Conectando ao Banco SQLite

Após instalar a extensão:

1.  Abra o painel **Database**
2.  Clique em **Create Connection**
3.  Escolha o tipo **SQLite**
4.  Selecione o arquivo:


    database/adventureworks.db

5.  Clique em **Connect**

------------------------------------------------------------------------

# Conexão no VSCode

![Extensão Database Client](images/Database_Client_Extension.png)
![Conecando no Banco](images/sqlite_path.png)
------------------------------------------------------------------------

# Executando Queries

Crie um arquivo `.sql` e execute consultas diretamente no VSCode.

Exemplo:

``` sql
SELECT
    Name,
    ListPrice
FROM Product
ORDER BY ListPrice DESC
LIMIT 10;
```

------------------------------------------------------------------------

# Exercícios

Os exercícios estão disponíveis em:

    exercises/exercises.md

Os exercícios incluem:

-   CRUD
-   JOIN
-   Agregações
-   Análise de vendas
-   Problemas de negócio


------------------------------------------------------------------------

# Objetivos de Aprendizado

Após completar os exercícios você será capaz de:

-   escrever consultas SQL complexas
-   trabalhar com JOINs
-   realizar agregações
-   analisar dados de vendas
-   compreender modelagem relacional

------------------------------------------------------------------------
