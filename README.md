# Explorando Design Patterns com Spring Boot

Foi desenvolvido uma API RESTful para explorar os design patterns, dos quais foram utilizados: Singleton, Strategy e Facade.

- [Ferramentas Usadas](#ferramentas-usadas)
- [Como executar](#como-executar)

## Ferramentas Usadas

- IDE de Desenvolvimento: [IntelliJ IDEA Community Edition (2022.1.4) Openjdk "11.0.15"](https://www.jetbrains.com/pt-br/idea/download)
- Gerenciador de Dependências: [Maven 3.8.6](https://maven.apache.org/)
- Framework para desenvolvimento da API: [Spring Boot 2.7.2](https://spring.io/projects/spring-boot)
- Servidor de Aplicação: [Apache Tomcat 9.0](http://tomcat.apache.org/)
- Testes da API RESTful: [Postman](https://www.getpostman.com/) 
- Banco de dados: [H2](https://www.h2database.com/html/main.html)
	
	*Aplicação rodando
	URL Base: http://localhost:8080/h2-console/

- Documentação API com Swagger [Guia de documentação básica da API](http://localhost:8080/swagger-ui.html#/)

	*Aplicação rodando
	URL Base: http://localhost:8080/swagger-ui.html#/
  
  ## Como Executar

- Instalar a IDE [IntelliJ IDEA Community Edition (2022.1.4) Openjdk "11.0.15"](https://www.eclipse.org/)
- Importar projeto
- Aguardar o download das depedências 
- A cada start/restart da aplicação o banco é recriado em memoria (H2).
- Após a aplicação subir acessar acessar o [Swagger](http://localhost:8080/swagger-ui.html#/)
