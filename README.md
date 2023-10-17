## 💻 Projeto do curso de Java da RocketSeat

O projeto é uma API de To Do List, onde o usuário poderá cadastrar, alterar e listar suas tarefas.

Foi utilizado as tecnologias:
- Java
- SpringBoot
- H2Database
- Lombok
- Maven
- Bcripty
- entre outros...


# Http Requests
### Create [POST  /users/]

+ Request (application/json)

    + Headers

            Authorization: Bearer [access_token]

    + Body

            {
	  "name":"Beatriz Medeiros",
	  "username": "bea.medeiros",
	  "password":"12345"
     		 }




### POST: Create Users
```md
http://localhost:8080/users/
```
+ Request
    + Body
      {
	  "name":"Beatriz Medeiros",
	  "username": "bea.medeiros",
	  "password":"12345"
      }

## POST: Create Tasks
```md
http://localhost:8080/tasks/
```

## GET: List Tasks
```md
http://localhost:8080/tasks/
```

## PUT: Update Tasks
```md
http://localhost:8080/tasks/{id}
```
