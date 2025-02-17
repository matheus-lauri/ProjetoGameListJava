# DSList - API REST com Spring Boot

Descrição

Este é um projeto backend desenvolvido com Spring Boot, fornecendo uma API REST para gerenciamento de uma lista de jogos.

Tecnologias Utilizadas

Java 17

Spring Boot

Hibernate

Banco de Dados (H2, MySQL ou PostgreSQL)

Instalação e Execução

Requisitos

Java 17 ou superior instalado

Maven

Banco de dados configurado

Passos para rodar o projeto

Clone o repositório:

git clone https://github.com/seu-usuario/dslist.git

Acesse a pasta do projeto:

cd dslist

Configure o banco de dados no application.properties ou application.yml:

spring.datasource.url=jdbc:h2:mem:testdb
spring.datasource.username=sa
spring.datasource.password=

Compile e execute a aplicação:

mvn spring-boot:run

A API estará disponível em:

http://localhost:8080

Estrutura do Projeto

/src
  /main/java/com/devsuperior/dslist
    /controller  # Controllers da API
    /service     # Lógica de negócio
    /repository  # Camada de acesso a dados
    /dto         # Objetos de Transferência de Dados (DTOs)
    /entities    # Modelos de dados (Entidades)

Funcionalidades Implementadas

Listagem de jogos

Reordenação da Lista de Jogos

Demonstração de Dados específicos através dos DTOs

Contribuição

Fork este repositório.

Crie uma branch:

git checkout -b minha-feature

Faça suas alterações e commit:

git commit -m "Adicionando uma nova feature"

Envie para o repositório remoto:

git push origin minha-feature

Abra um Pull Request.
