# API Gateway (`api-gateway`)

Spring Boot–based API Gateway built with **Spring Cloud Gateway (Server MVC)**. It serves as a single entry point for routing HTTP requests to downstream services in this repository (for example: `resource-server`, and potentially others).

## What this project is for

- Centralized **routing** to backend services
- A clean place for cross-cutting concerns (rate limiting, headers, auth integration, observability) as the system grows
- **Operational insight** via Spring Boot Actuator endpoints

## Tech stack

- **Java:** 25  
- **Build:** Maven (requires **3.9+**)  
- **Framework:** Spring Boot **4.0.2**
- **Gateway:** Spring Cloud **2025.1.1** (`spring-cloud-starter-gateway-server-webmvc`)
- **Ops:** Spring Boot Actuator

## Prerequisites

- JDK **25**
- Maven **3.9+** (or use the Maven Wrapper: `./mvnw`)
