# Api Rest CRUD Clientes em Java 
[![NPM](https://img.shields.io/npm/l/react)](https://github.com/mcarnelos/api-crud-clientes-bootcamp-devsuperior/blob/master/LICENSE) 

# Sobre o projeto

Projeto de uma Api Rest CRUD que faz cadastro de Clientes em Java, desenvolvido durante o Bootcamp Spring React da [DevSuperior](https://devsuperior.com "Site da DevSuperior").

## Modelo conceitual
![Modelo Conceitual](https://github.com/mcarnelos/assets/blob/master/crud/modelo%20conceitual.png)

## Features
- Cadastro de Clientes com verbo POST /clients
- Busca de Clientes com verbo GET /clients
- Busca de Clientes por id com verbo GET /clients/id
- Update de Clientes por id com verbo PUT /clients/id
- Deletar Clientes por id com verbo DELETE /clients/id

# Tecnologias utilizadas
## Back end
- Java
- Spring Boot
- JPA / Hibernate
- Maven

## Banco de Dados 
- H2

# Como executar o projeto

## Pré-requisitos
Antes de começar, você vai precisar ter instalado em sua máquina as seguintes ferramentas:

- IDE para desenvolvimento JAVA como Spring Tool Suite 4 ou IntelliJ IDEA
- Gerenciador de dependências Maven
- Postman para testar os verbos HTTP

## Back end

```bash
# clonar repositório
git clone https://github.com/mcarnelos/api-crud-clientes-bootcamp-devsuperior

# Importe o projeto na sua IDE

# Aguarde a sincronização das dependências do Maven

# Execute a aplicação (está no profile test)

# O servidor inciará na porta:8080 abra o Postman e execute os verbos HTTP na url <http://localhost:8080/clients>

# Faça os testes no banco de dados H2 na url <http://localhost:8080/h2-console>
```

# Autor

Murilo Carnelós

https://www.linkedin.com/in/murilo-carnel%C3%B3s/
