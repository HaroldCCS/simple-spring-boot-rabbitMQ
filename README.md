# simple-spring-boot-rabbitMQ


#TEST SEND JSON
POST http://localhost:8080/api/v1/publish
{
    "id": 1,
    "firstName": "Harold",
    "lastName": "Camargo"
}


#TEST SEND STRING
GET http://localhost:8080/api/v1/publish?message=HOLA
