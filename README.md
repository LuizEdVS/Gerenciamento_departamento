# Gerenciamento de Departamento

API REST simples para cadastro e consulta de departamentos usando Spring Boot e H2.

## Tecnologias

- Java 17
- Spring Boot
- Spring Data JPA
- H2 Database

## Como executar

1. Garanta que o Maven esteja instalado e no `PATH`.
2. Execute:

```bash
mvn spring-boot:run
```

3. A API sobe por padrão em `http://localhost:8080`.

## Console H2

- URL: `http://localhost:8080/h2-console`
- JDBC URL: `jdbc:h2:mem:testdb`
- User: `sa`
- Password: vazio
