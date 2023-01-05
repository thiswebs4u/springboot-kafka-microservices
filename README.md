## Kafka Docker Setup
https://www.baeldung.com/ops/kafka-docker-setup

## Event Driven Micro Services
https://www.javaguides.net/2022/07/event-driven-microservices-using-spring-boot-and-apache-kafka.html



### Payload
```JSON
{
    "name": "Book Order",
    "qty": 5,
    "price": 10000
}
```

### The request body is provided in place

```JSON
POST http://localhost:8080/api/v1/orders HTTP/1.1
Content-Type: application/json
Cookie: key=test-cookie

{
"name": "Book Order",
"qty": 5,
"price": 10000
}
```

### Exploring Http Client Markup
https://www.jetbrains.com/help/idea/exploring-http-syntax.html