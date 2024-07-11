# ForumHub

## Descrição
O ForumHub é uma aplicação de gerenciamento de tópicos de fórum, desenvolvida em Spring Boot, que permite criar, listar, atualizar e excluir tópicos. A aplicação utiliza autenticação JWT para segurança nas operações e segue o padrão RESTful para suas APIs.

## Funcionalidades
- CRUD (Criar, Ler, Atualizar, Excluir) de tópicos de fórum.
- Autenticação de usuários com JWT.
- Segurança nas operações utilizando Spring Security.
- APIs RESTful para interação com os tópicos.

## Tecnologias Utilizadas
- Java
- Spring Boot
- Spring Security
- JWT (JSON Web Token)
- Hibernate
- PostgreSQL
- Maven

## Pré-requisitos
- JDK 11 ou superior instalado
- PostgreSQL instalado e configurado localmente
- Maven para compilação e gerenciamento de dependências

## Instalação
1. Clone o repositório: `https://github.com/DaviLima1234/Forumhub.git`
2. Configure o banco de dados PostgreSQL criando um banco de dados chamado `forumhub`.
3. Confira e atualize as configurações de conexão no arquivo `src/main/resources/application.properties`.
4. Execute o projeto usando Maven: `mvn spring-boot:run`
5. Acesse a API através de `http://localhost:8080`
