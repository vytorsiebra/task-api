
# ✅ Task API

API RESTful para gerenciamento de tarefas, desenvolvida com **Java 17 + Spring Boot 3**, e deployada com sucesso no **Railway**. 🚀

## 🔗 Acesso online

🌍 [Acesse a API via Swagger](https://task-api-decola-tech.up.railway.app/swagger-ui/index.html)

---

## 🧰 Tecnologias utilizadas

- Java 17
- Spring Boot 3
- Spring Web
- Spring Data JPA
- H2 Database (em memória)
- Swagger/OpenAPI (Documentação)
- Maven/Gradle
- Railway (Deploy)
- Git e GitHub

---

## 📂 Funcionalidades

- Criar, listar, atualizar e excluir tarefas (CRUD completo)
- Buscar tarefa por ID
- Integração com banco de dados em memória (H2)
- Documentação automática via Swagger

---

## 🎯 Endpoints principais

| Método | Endpoint           | Descrição                  |
|--------|--------------------|----------------------------|
| GET    | `/tasks`           | Lista todas as tarefas     |
| GET    | `/tasks/{id}`      | Busca uma tarefa por ID    |
| POST   | `/tasks`           | Cria uma nova tarefa       |
| PUT    | `/tasks/{id}`      | Atualiza uma tarefa        |
| DELETE | `/tasks/{id}`      | Remove uma tarefa          |

---

## ⚙️ Como rodar localmente

### Pré-requisitos

- Java 17 instalado
- Git
- IDE (IntelliJ, VSCode, etc)

### Clonando o projeto

```bash
git clone https://github.com/vytorsiebra/task-api.git
cd task-api
```

### Rodando o projeto

```bash
./gradlew build
java -jar build/libs/task-api-0.0.1-SNAPSHOT.jar
```

Ou direto pela IDE (rodando `TaskApiApplication`).

---

## 🧪 Banco de dados em memória

A aplicação usa **H2**, que é resetado a cada reinicialização.

Você pode acessar o console em:

```
http://localhost:8080/h2-console
```

**Credenciais padrão**:
- JDBC URL: `jdbc:h2:mem:decolatech`
- Username: `decolatech`
- Password: *(vazio)*

---

## ☁️ Deploy na Nuvem

O projeto está hospedado no Railway, usando:

- Build command: `./gradlew build`
- Start command: `java -jar build/libs/task-api-0.0.1-SNAPSHOT.jar`

URL: https://task-api-decola-tech.up.railway.app

Swagger: https://task-api-decola-tech.up.railway.app/swagger-ui/index.html

H2: https://task-api-decola-tech.up.railway.app/h2-console

---

## ✍️ Autor

Desenvolvido com 🧡 por [João Vytor Siebra](https://github.com/vytorsiebra)  
Bootcamp Decola Tech Avanade - DIO & Avanade
---

## 📄 Licença

Este projeto está sob a licença MIT.
