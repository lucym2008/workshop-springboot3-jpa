# API REST com Spring Boot 3 e JPA - Projeto de Estudo de E-commerce

[![Java](https://img.shields.io/badge/Java-17%2B-blue)](https://www.oracle.com/java/)
[![Spring Boot](https://img.shields.io/badge/Spring%20Boot-3.0-brightgreen)](https://spring.io/projects/spring-boot)
[![JPA / Hibernate](https://img.shields.io/badge/JPA-Hibernate-yellow)](https://hibernate.org/)
[![Banco de Dados](https://img.shields.io/badge/DB-H2%20%7C%20PostgreSQL-blueviolet)](https://www.postgresql.org/)

## 📋 Sobre o Projeto

Este projeto é uma API REST desenvolvida durante o curso "Java COMPLETO 2023 Programação Orientada a Objetos" do professor Nélio Alves (Udemy). O objetivo principal foi construir um backend completo para um domínio de e-commerce, aplicando na prática os conceitos mais importantes do ecossistema Spring.

A API gerencia usuários, pedidos, produtos, categorias e pagamentos, com todas as operações de CRUD e relacionamentos complexos entre as entidades. Foi uma excelente oportunidade para consolidar conhecimentos em modelagem de dados, camadas de serviços, tratamento de exceções e boas práticas de desenvolvimento.

## 🚀 Funcionalidades

*   **Cadastro e Gestão de Usuários:** Criar, listar, atualizar e deletar usuários.
*   **Gestão de Pedidos:** Cada pedido está associado a um usuário e possui um status (Aguardando pagamento, Pago, Enviado, etc.).
*   **Catálogo de Produtos:** Produtos organizados por categorias e associados a pedidos.
*   **Itens de Pedido:** Suporte para itens individuais dentro de um pedido, com quantidade e subtotal calculado automaticamente.
*   **Pagamento:** Associação de um pagamento a um pedido (relacionamento one-to-one).
*   **Tratamento de Exceções:** Manipulação personalizada de erros, retornando respostas HTTP apropriadas (como 404 para recurso não encontrado e 400 para requisições inválidas).

## 🛠️ Tecnologias e Conceitos Utilizados

*   **Java 17:** Utilização dos recursos mais modernos da linguagem.
*   **Spring Boot 3:** Para criação rápida e configuração da aplicação.
*   **Spring MVC:** Implementação dos endpoints REST e manipulação das requisições HTTP.
*   **Spring Data JPA / Hibernate:** Mapeamento objeto-relacional (ORM), persistência de dados e criação de repositórios.
*   **Banco de Dados:**
    *   **H2 Database:** Banco de dados em memória utilizado durante o desenvolvimento e testes.
    *   **PostgreSQL:** Banco de dados utilizado em produção, com deploy realizado no Heroku.
*   **Maven:** Gerenciamento de dependências e build da aplicação.
*   **Tratamento de Exceções:** Implementação de handlers personalizados com `@ControllerAdvice`.
*   **Padrão de Camadas:** Separação clara entre as camadas de Recurso (Controller), Serviço (Service) e Repositório (Repository).
*   **Modelagem de Dados:** Criação de relacionamentos complexos (One-to-Many, Many-to-One, Many-to-Many com dados extras).

## ⚙️ Como Executar o Projeto Localmente

### Pré-requisitos
*   Java 17 ou superior instalado.
*   Maven instalado.
*   Git instalado (para clonar o repositório).

### Passos

1.  **Clone o repositório:**
    ```bash
    git clone https://github.com/lucym2008/workshop-springboot3-jpa.git 
