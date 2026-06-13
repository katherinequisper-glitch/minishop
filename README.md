# MiniShop REST API

![CI Pipeline](https://github.com/katherinequisper-glitch/minishop/actions/workflows/ci.yml/badge.svg)

## Descripción
API REST para gestión de productos desarrollada con Spring Boot como parte del curso de Construcción y Pruebas de Software - Tecsup.

## Tecnologías
- Java 17
- Spring Boot 3.x
- Spring Data JPA
- H2 (base de datos en memoria para pruebas)
- JUnit 5
- Maven

## Ejecutar el proyecto
```bash
mvn spring-boot:run
```

## Ejecutar las pruebas
```bash
mvn clean verify
```

## Estructura de pruebas
- `ProductServiceIntegrationTest` — pruebas del servicio
- `ProductRepositoryIntegrationTest` — pruebas del repositorio
- `ProductControllerIntegrationTest` — pruebas del controlador

## CI/CD
Este proyecto usa GitHub Actions para integración continua. Cada push a `main` ejecuta automáticamente el build y todas las pruebas.