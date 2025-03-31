# Planner - Gerenciador de Tarefas

Este projeto é um **Planner** desenvolvido em **Spring Boot**, projetado para gerenciar atividades de forma eficiente.

## Tecnologias Utilizadas

- **Java 17**
- **Spring Boot**
  - Spring Data JPA
  - Spring Web
  - Flyway para controle de versões do banco de dados
- **H2 Database** (banco de dados em memória para testes)
- **Lombok** (para redução de código boilerplate)

## Funcionalidades

- Cadastro de atividades
- Atualização e exclusão de atividades
- Listagem de atividades
- Banco de dados gerenciado via Flyway

## Como Executar o Projeto

### Pré-requisitos
- Ter o **Java 17+** instalado
- Ter o **Maven** configurado no sistema

### Passos
1. Clone o repositório:
   ```sh
   git clone https://github.com/FelipeZelent/Planner.git
   ```
2. Acesse a pasta do projeto:
   ```sh
   cd Planner
   ```
3. Execute o seguinte comando para rodar a aplicação:
   ```sh
   ./mvnw spring-boot:run  # Linux/Mac
   mvnw.cmd spring-boot:run # Windows
   ```
4. A API estará disponível em `http://localhost:8080`

## Estrutura do Projeto

```
Planner
│── src/
│   ├── main/java/com/planner/planner/
│   │   ├── activity/            # Pacote para operações de atividades
│   │   ├── config/              # Configurações do projeto
│   │   ├── PlannerApplication.java  # Classe principal
│── pom.xml                      # Gerenciamento de dependências
│── .gitignore
│── README.md
```
