# 🛒 API Produtos - Sistema de Gestão de Produtos

![Java](https://img.shields.io/badge/Java-21-blue?logo=java)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-4.x-brightgreen?logo=springboot)
![Maven](https://img.shields.io/badge/Maven-Build-red?logo=apachemaven)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-Database-blue?logo=postgresql)
![Docker](https://img.shields.io/badge/Docker-Container-blue?logo=docker)
![Status](https://img.shields.io/badge/build-passing-brightgreen)
![License](https://img.shields.io/badge/license-Academic-lightgrey)

---

API REST desenvolvida com **Java + Spring Boot** para gerenciamento completo de produtos, incluindo operações de CRUD, persistência em banco de dados PostgreSQL, testes automatizados e ambiente containerizado com Docker.

---

## 🚀 Tecnologias Utilizadas

- Java 21  
- Spring Boot  
- Spring Web MVC  
- Spring Data JPA  
- PostgreSQL  
- H2 Database (testes)  
- Docker & Docker Compose  
- Swagger / OpenAPI 3  
- JUnit 5  
- MockMvc  
- Maven  

---

## 📌 Funcionalidades

- Cadastro de produtos  
- Atualização de produtos  
- Exclusão de produtos  
- Consulta de todos os produtos  
- Consulta por ID  
- Cálculo automático do valor total (preço × quantidade)  
- Validação de dados  
- Tratamento de exceções customizadas  
- Testes automatizados de API  
- Documentação interativa via Swagger  

---

## 🏗️ Arquitetura do Projeto

- Controller → API REST  
- Service → regras de negócio  
- Repository → acesso ao banco de dados  
- DTOs → transferência de dados  
- Entity → modelagem do banco  
- Exception → tratamento de erros  
- Configuration → configurações gerais  

---

## 📂 Estrutura do Projeto

src/main/java/br/com/cotiinformatica/api_produtos

controllers  
services  
repositories  
entities  
dtos  
enums  
exceptions  
configurations  
factories  
sql  

---

## ⚙️ Banco de Dados

- PostgreSQL (produção)  
- H2 (testes automatizados)  

---

## 🧪 Testes Automatizados

mvn test

Testes cobrem:
- CRUD completo
- Validações
- Integração com API

---

## 🐳 Executando com Docker

docker-compose up --build

A aplicação ficará disponível em:

http://localhost:8086

---

## 📚 Swagger (Documentação da API)

http://localhost:8086/swagger-ui.html

---

## 🔗 Endpoints

POST    /api/v1/produtos  
GET     /api/v1/produtos  
GET     /api/v1/produtos/{id}  
PUT     /api/v1/produtos/{id}  
DELETE  /api/v1/produtos/{id}  

---

## 💡 Diferenciais Técnicos

- Arquitetura em camadas bem definida  
- Uso de DTOs para desacoplamento  
- Tratamento de exceções customizadas  
- Integração com Docker  
- Testes automatizados com MockMvc  
- Documentação Swagger  
- Boas práticas REST  

---

## 👩‍💻 Autora

**Beatriz Lima**  
Desenvolvedora Java Full Stack em formação, focada em backend e arquitetura de APIs.

---

## 📌 Observação

Projeto acadêmico com foco em evolução para nível júnior backend developer.
