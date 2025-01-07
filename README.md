##  **PROJETO**

Este projeto é um clone de [https://github.com/leoinfnet/trabalho_final_react_noite](https://github.com/leoinfnet/trabalho_final_react_noite).
Algumas pequenas alterações foram feitas para adequação ao projeto [react-spring-front](https://github.com/flavio-vicentini-poa/react-spring-front).

Créditos: [Professor Leonardo Glória](https://github.com/leoinfnet).

Link da API em produção no [Render](https://render.com/): [API-CAR](https://react-spring-back-car.onrender.com).

**Descrição Original do Projeto**

Este é um projeto de uma API RESTful construída com **Spring Boot** para gerenciar informações sobre **Carros**. A API permite realizar operações de CRUD (Criar, Ler, Atualizar, Deletar) para os carros. Além disso, também inclui a autenticação de usuários com senhas.

## 📦 **Tecnologias Utilizadas**

- [Spring Boot](https://spring.io/projects/spring-boot)
- [Spring Data JPA](https://spring.io/projects/spring-data)
- [H2 Database](https://www.h2database.com/html/main.html) (para fins de teste)
- [Docker](https://www.docker.com/)

## 🚀 **Como Rodar o Projeto**

### 1. **Pré-requisitos**

Certifique-se de ter as seguintes ferramentas instaladas:

- [Java 17 ou superior](https://adoptium.net/)
- [Maven](https://maven.apache.org/)
- [Docker](https://www.docker.com/get-started)

### 2. **Rodando Localmente**

#### Clonando o Repositório

```bash
git clone https://github.com/flavio-vicentini-poa/react-spring-back
cd react-spring-back
```

#### Contruindo com Maven
```bash
mvn clean install -Dmaven.test.skip
```
#### Rodando
```bash
mvn spring-boot:run
```

