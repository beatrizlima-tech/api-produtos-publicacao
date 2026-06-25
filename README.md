# 📦 API Produtos

![Java](https://img.shields.io/badge/Java-21-red?style=for-the-badge\&logo=openjdk)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-4.0.x-green?style=for-the-badge\&logo=springboot)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-Database-blue?style=for-the-badge\&logo=postgresql)
![Swagger](https://img.shields.io/badge/Swagger-OpenAPI-green?style=for-the-badge\&logo=swagger)
![Build](https://img.shields.io/badge/build-passing-brightgreen?style=for-the-badge)
![License](https://img.shields.io/badge/license-MIT-lightgrey?style=for-the-badge)

---

# 📌 Sobre o projeto

A **API Produtos** é uma aplicação backend desenvolvida em **Java com Spring Boot** para gerenciamento de produtos através de uma API REST.

O projeto foi desenvolvido para consolidar conhecimentos em construção de APIs, organização em camadas, integração com banco de dados PostgreSQL utilizando JDBC e documentação com Swagger/OpenAPI.

---

# 🚀 Funcionalidades

* Cadastro de produtos
* Consulta de produtos por nome
* Atualização de produtos *(em desenvolvimento)*
* Exclusão de produtos *(em desenvolvimento)*
* Cálculo automático do valor total (preço × quantidade)
* Integração com PostgreSQL
* Documentação da API com Swagger

---

# 🧱 Tecnologias utilizadas

* Java 21
* Spring Boot
* Spring Web MVC
* JDBC
* PostgreSQL
* Swagger / OpenAPI
* Maven

---

# 🏗️ Estrutura do projeto

```
src/main/java/br/com/cotiinformatica/produtos_api

├── configurations
├── controllers
├── dtos
├── entities
├── factories
└── repositories
```

---

# 🔗 Endpoints

| Método | Endpoint                 | Descrição                                |
| ------ | ------------------------ | ---------------------------------------- |
| POST   | /api/v1/produtos/criar   | Cadastrar produto                        |
| GET    | /api/v1/produtos/listar  | Consultar produtos                       |
| PUT    | /api/v1/produtos/alterar | Atualizar produto *(em desenvolvimento)* |
| DELETE | /api/v1/produtos/excluir | Excluir produto *(em desenvolvimento)*   |

---

# ⚙️ Como executar o projeto

### Clone o repositório

```bash
git clone https://github.com/beatrizlima-tech/produtos-api.git
```

### Configure o banco PostgreSQL

Crie o banco de dados e execute o script SQL disponível no projeto.

Configure a conexão na classe **ConnectionFactory**.

### Execute a aplicação

```bash
mvn spring-boot:run
```

---

# 📚 Documentação

Após iniciar a aplicação, acesse:

```
http://localhost:8081/swagger-ui.html
```

---

# 📊 Arquitetura

Controller

↓

DTO

↓

Repository

↓

JDBC

↓

PostgreSQL

---

# 📌 Melhorias futuras

* Implementar atualização completa de produtos
* Implementar exclusão lógica
* Adicionar camada de Service
* Migrar para Spring Data JPA
* Adicionar Bean Validation
* Criar testes automatizados
* Dockerizar a aplicação

---

# 👩‍💻 Autora

Desenvolvido por **Beatriz Lima**

* GitHub: https://github.com/beatrizlima-tech
* LinkedIn: https://www.linkedin.com/in/beatrizlima-tech
