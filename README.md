# API REST com Java Spring Boot

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=spring-boot&logoColor=white)
![Maven](https://img.shields.io/badge/Maven-C71A36?style=for-the-badge&logo=apache-maven&logoColor=white)
![H2 Database](https://img.shields.io/badge/H2-Blue?style=for-the-badge&logo=h2&logoColor=white)

## Descrição do Projeto

Este projeto consiste em uma API REST desenvolvida com Java e Spring Boot, focada em demonstrar boas práticas de desenvolvimento, arquitetura em camadas e uso de banco de dados relacional. A API permite operações básicas de CRUD (Create, Read, Update e Delete).

## Tecnologias Utilizadas

- **Java 17**
- **Spring Boot** (Spring Web, Spring Data JPA)
- **Banco de Dados H2** (para ambiente de desenvolvimento)
- **Maven** (gerenciador de dependências)

## Funcionalidades

- Cadastro de entidades
- Consulta de registros
- Atualização de informações
- Exclusão de registros

## Como Executar o Projeto

### Pré-requisitos

Certifique-se de ter instalado na sua máquina:
- **JDK 17** ou superior
- **Maven**

### Passos para execução

1. Clone o repositório:
   ```sh
   git clone https://github.com/victor-luduvice/ApiRest-JavaSpring.git
   ```

2. Acesse a pasta do projeto:
   ```sh
   cd ApiRest-JavaSpring
   ```

3. Compile e execute o projeto:
   ```sh
   mvn spring-boot:run
   ```

4. A API estará disponível em `http://localhost:8080`

## Endpoints Disponíveis

| Método | Endpoint        | Descrição                      |
|--------|---------------|--------------------------------|
| GET    | `/api/items`  | Retorna todos os itens         |
| GET    | `/api/items/{id}` | Retorna um item por ID       |
| POST   | `/api/items`  | Cria um novo item              |
| PUT    | `/api/items/{id}` | Atualiza um item por ID      |
| DELETE | `/api/items/{id}` | Remove um item por ID       |


