# Documentação do Projeto: Autenticação e Autorização com .NET

## Introdução
Este repositório contém um projeto que explora os fundamentos de uma Web Api, além disso explora conceitos de relacionamento de entidades usando o EF Core

## Tecnologias Utilizadas
- **ASP.NET Core**: Framework para desenvolvimento de aplicativos web e APIs.
- **Entity Framework Core**: ORM (Object-Relational Mapping) para acesso a banco de dados.
- **MySql**

## Funcionalidades
1. **CRUD**:
   - Registros, edição, leitura e exclusão de Filmes, Cinemas e Endereços.

2. **Armazenar informações em um banco de dados**:
   - Criação da base de dados que contém Filmes, Cinemas e seus respectivos Endereços



## Configuração
1. **Clonando o Repositório**:

git clone https://github.com/heroshg/FilmesApi.git


2. **Configurando o Banco de Dados**:
- Configure a conexão com o banco de dados no arquivo `appsettings.json`.
- Execute as migrações para criar as tabelas de usuário e roles:
  ```
  dotnet ef database update OU
  Update-Database
  ```

3. **Executando o Projeto**:

dotnet run OU
CTRL + F5
