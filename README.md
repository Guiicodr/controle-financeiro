# Financial Control API

REST API for personal financial management, developed with Java and Spring Boot.

##  Features

* Create transactions (POST /transacoes)
* List transactions (GET /transacoes)
* Calculate balance (GET /transacoes/saldo)

##  Technologies

* Java
* Spring Boot
* Spring Data JPA
* H2 Database

## Request Example

POST /transacoes

```json
{
  "descricao": "Almoco",
  "valor": 30,
  "tipo": "SAIDA",
  "data": "2026-05-02"
}
```

## How to Run the Project

1. Clone the repository
2. Open it in your IDE (IntelliJ or VS Code)
3. Run the Spring Boot application
4. Access: http://localhost:8080

##  Endpoints

| Method | Route             | Description        |
| ------ | ----------------- | ------------------ |
| POST   | /transacoes       | Create transaction |
| GET    | /transacoes       | List transactions  |
| GET    | /transacoes/saldo | Calculate balance  |

## 📌 Status

 In development
