# 🏥 Clínica Voll Med - API de Gestão e Segurança

![Java](https://img.shields.io/badge/Java-17+-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-3.0+-6DB33F?style=for-the-badge&logo=spring-boot&logoColor=white)
![Maven](https://img.shields.io/badge/Apache_Maven-C71A36?style=for-the-badge&logo=apache-maven&logoColor=white)

Este projeto é uma API RESTful desenvolvida para a gestão de uma clínica médica (Clinica Voll Med). O foco principal do projeto é a implementação de **boas práticas de segurança**, controle de acesso e gestão de dados de médicos, pacientes e consultas.

## 🚀 Tecnologias Utilizadas

*   **Java 17+**
*   **Spring Boot 3**
*   **Spring Security** (Autenticação e Autorização via JWT)
*   **Spring Data JPA** (Persistência de dados)
*   **Maven** (Gerenciamento de dependências)
*   **MySQL / H2 Database** (Banco de dados)

## ⚙️ Funcionalidades Principais

- [x] **Autenticação Segura:** Login com validação de usuário e senha, geração e validação de tokens JWT.
- [x] **Controle de Acesso:** Restrição de endpoints baseada em perfis de usuário (ex: ADMIN, USER).
- [x] **CRUD de Médicos:** Cadastro, listagem, atualização e exclusão (lógica) de médicos.
- [x] **CRUD de Pacientes:** Cadastro e gestão de dados dos pacientes.
- [x] **Gestão de Consultas:** Agendamento e cancelamento de consultas médicas com regras de negócio.
- [x] **Documentação da API:** Integração com Swagger/OpenAPI (se aplicável).

## 🛠️ Como Executar o Projeto

### Pré-requisitos
Antes de começar, você vai precisar ter instalado em sua máquina:
*   [Git](https://git-scm.com)
*   [Java JDK 17 ou superior](https://www.oracle.com/java/technologies/javase/jdk17-archive-downloads.html)
*   [Maven](https://maven.apache.org/) (ou use o wrapper `mvnw` incluso no projeto)

### Passo a Passo

1. Clone este repositório:
```bash
git clone https://github.com/LeandroAmaralC/Clinica_Voll_Med.git
