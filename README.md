# Relacionamento_Classes
![GitHub](https://img.shields.io/github/license/MuriloVieiraCruz/Relacionamento_Classes)

# Sobre o projeto

O projeto "TreinoWebServices" é uma aplicação web desenvolvida com o objetivo principal de aprimorar as habilidades em desenvolvimento 
de serviços web utilizando as tecnologias Spring Boot, JPA e Hibernate. A ideia por trás do projeto é construir uma API RESTful capaz de 
gerenciar uma lista de tarefas.

O desenvolvimento do projeto é realizado em etapas, começando com a configuração básica do Spring Boot e a criação das entidades JPA que representam as tarefas. 
Em seguida, são implementados os controladores REST para gerenciar as requisições HTTP, utilizando os métodos adequados para criar, recuperar, atualizar e excluir as tarefas.

Possuindo também tratamento de exceções caso o usuário se equivoque em uma requisição 

## Modelo de Domínio
![Captura de tela 2023-08-03 145109](https://github.com/MuriloVieiraCruz/Relacionamento_Classes/assets/113257963/cae5a468-e029-4bcf-8c88-71aba6e39374)

## Instancia de Domínio
![Captura de tela 2023-08-03 145209](https://github.com/MuriloVieiraCruz/Relacionamento_Classes/assets/113257963/3d96b5d5-aae0-43bc-9371-4822e0171239)

# Tecnologias utilizadas
## Back end
- Java
- Spring Boot
- JPA / Hibernate
- Maven

```bash
# Rodar Banco de dados local
- Criar uma dataBase a sua escolha
- Entrar na pasta de arquivo: src/main/resources/application-dev.properties
- Colocar o nome do seu banco aqui: spring.datasource.url=jdbc:postgresql://localhost:5432/"Nome do seu banco"
- Rodar a aplicação que o JPA irá gerar as classes no banco
```
```bash
# Rodar Banco H2
- Criar uma dataBase a sua escolha
- Entrar na pasta de arquivo: src/main/resources/application.properties
- Alterar o nome do perfil ativo para "test": spring.profiles.active=test
- Rodar a aplicação
- Colocar na sua url web: localhost:8080/h2-console
```
```bash
# Caso opte por rodar o script no banco
- Localizar o arquivo create.SQL
- Copiar o script e rodar no banco 
```

# Autores

[<img src="https://avatars.githubusercontent.com/u/113257963?v=4" width=115><br><sub>Murilo Vieira Cruz</sub>](https://github.com/MuriloVieiraCruz)
