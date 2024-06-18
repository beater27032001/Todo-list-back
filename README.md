# Todo List Back-end

Este repositório contém o código-fonte de um aplicativo back-end simples para uma lista de tarefas (Todo List). Ele fornece uma API RESTful para gerenciar tarefas.

## Propósito

O propósito deste aplicativo é fornecer endpoints para operações básicas em uma lista de tarefas, incluindo adicionar, atualizar e excluir tarefas.

## Dependências

- Java 11 ou superior
- Spring Boot 3.x
- H2 Database (embedded)
- SpringDoc
- Lombok
- SpringWeb
- Spring Boot Dev Tools

## Como Rodar

Para rodar este aplicativo localmente, siga as etapas abaixo:

1. **Clone o repositório:**

   ```bash
   git clone https://github.com/beater27032001/Todo-list-back.git
   cd todo-list-back

2. **Acesso à documentação da API (Swagger - opcional):**

    Após iniciar o aplicativo, você pode acessar a documentação da API no Swagger UI:
  
    http://localhost:8080/swagger-ui/index.html
  
    Isso abrirá a interface do Swagger UI, onde você pode visualizar e testar os endpoints da API.

## Endpoints Disponíveis

- **GET** /todos: Retorna todas as tarefas cadastradas.
- **POST** /todos: Cria uma nova tarefa.
- **PUT** /todos/{id}: Atualiza uma tarefa existente pelo ID.
- **DELETE** /todos/{id}: Exclui uma tarefa pelo ID.
