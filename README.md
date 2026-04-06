# 🌐 Spring Microservices Study

[![Java 21](https://img.shields.io/badge/Java-21-orange?style=flat-square&logo=openjdk)](https://openjdk.org/)
[![Spring Boot 3](https://img.shields.io/badge/Spring_Boot-3.0+-6db33f?style=flat-square&logo=spring)](https://spring.io/projects/spring-boot)
[![Docker](https://img.shields.io/badge/Docker-blue?style=flat-square&logo=docker&logoColor=white)](https://www.docker.com/)

Este repositório é dedicado ao estudo e implementação de uma arquitetura de **Microsserviços** utilizando o ecossistema Spring. O foco principal é a criação de serviços desacoplados, escaláveis e prontos para ambientes de nuvem.

## 🏗️ Arquitetura do Projeto

O projeto explora os principais padrões (patterns) de sistemas distribuídos:

* **Microservices:** Serviços independentes focados em domínios específicos.
* **Service Discovery:** Registro e localização automática de instâncias.
* **API Gateway:** Ponto de entrada único para o ecossistema.
* **Config Server:** Centralização de configurações de ambiente.
* **Communication:** Comunicação síncrona (Feign/RestTemplate).

## 🚀 Tecnologias Utilizadas

- **Java 21** (Linguagem principal)
- **Spring Boot 3** (Framework base)
- **Spring Cloud** (Netflix Eureka, Config, Gateway, OpenFeign)
- **Docker & Docker Compose** (Containerização e Orquestração local)
- **GitHub Actions** (CI/CD Pipeline em desenvolvimento)
- **MySQL** (Persistência de dados)

## ⚙️ Como Executar o Projeto

### Pré-requisitos
- JDK 21
- Maven 3.0.5
- Docker e Docker Compose

### Passo a Passo
1. Clone o repositório:
   ```bash
   git clone [https://github.com/jvictorvale/microservice-spring-study.git](https://github.com/jvictorvale/microservice-spring-study.git)
