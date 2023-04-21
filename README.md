# User-Department-Spring

Este é um projeto básico para aprimorar estudos em que utiliza o framework Spring para gerenciar usuários e departamentos em uma organização. Ele fornece APIs RESTful para criar, atualizar, recuperar e excluir usuários e departamentos.

## Pré-requisitos
- JDK 8 ou superior
- Maven 3.6.0 ou superior


## API Endpoints
### Usuários
- GET /api/users: Retorna todos os usuários cadastrados.
- GET /api/users/{id}: Retorna um usuário específico com base em seu ID.
  POST /api/users: Cria um novo usuário.
- PUT /api/users/{id}: Atualiza um usuário existente com base em seu ID.
- DELETE /api/users/{id}: Exclui um usuário específico com base em seu ID.

### Departamentos
- GET /api/departments: Retorna todos os departamentos cadastrados.
- GET /api/departments/{id}: Retorna um departamento específico com base em seu ID.
- POST /api/departments: Cria um novo departamento.
- PUT /api/departments/{id}: Atualiza um departamento existente com base em seu ID.
- DELETE /api/departments/{id}: Exclui um departamento específico com base em seu ID.

## Tecnologias utilizadas
- Spring Boot
- Spring Data JPA
- H2 Database
- Maven
