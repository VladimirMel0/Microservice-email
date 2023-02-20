# Projeto Microsservice de Email
Projeto de um microsservices para envio de email, meu foco foi aprimorar minhas habilidades no Java para Back-end.

## How To Use

1. Clonar projeto.
2. Instalar as dependências do maven.
3. Criar banco de dados com o nome "ms_email"

``` docker 
spring.datasource.url=jdbc:mysql://${MYSQL_HOST:localhost}:3306/ms_email
```
4. Chamar os Endpoints

## Libs
- [Spring Validation](https://spring.io/guides/gs/validating-form-input/) : Fazer a validação dos dados de entrada.
- [Spring Boot](https://spring.io/projects/spring-boot) : Framework para criar aplicação web.
- [Spring Security](https://spring.io/projects/spring-security): Fazer a criptografia de dados sensiveis 
- [Maven](https://maven.apache.org/) : Para gerenciar dependências de objetos.
- [Git](https://git-scm.com/) : Gerenciar versionamento do projeto.
