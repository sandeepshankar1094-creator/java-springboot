# java-springboot

A minimal Spring Boot application using Java 17, Spring Web, Actuator, and
Micrometer's Prometheus registry.

## Run

Start the application with Maven:

```shell
mvn spring-boot:run
```

The sample endpoint is available at `http://localhost:8080/api/`. Health
information is available at `http://localhost:8080/api/actuator/health`, and
Micrometer metrics in Prometheus format are available at
`http://localhost:8080/api/actuator/prometheus`.