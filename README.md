
# Sistema de Gestión de Inventario de Vehículos Usados (SGIVU)

![Java](https://img.shields.io/badge/Java-17-blue) ![Spring Boot](https://img.shields.io/badge/Spring%20Boot-3-brightgreen) ![Spring Cloud](https://img.shields.io/badge/Spring%20Cloud-2025-brightgreen) ![Angular](https://img.shields.io/badge/Angular-20-red) ![Docker](https://img.shields.io/badge/Docker-ready-blue) ![AWS](https://img.shields.io/badge/AWS-ready-orange) ![MIT License](https://img.shields.io/badge/License-MIT-green.svg)

Este proyecto nació de una necesidad real observada en la microempresa Alquiler Doble AA SAS, donde todo el ciclo de vida de la compra y venta de motocicletas usadas se gestionaba de forma manual. Este método, aunque funcional, presentaba desafíos en cuanto a eficiencia, trazabilidad de la información y escalabilidad del negocio.

SGIVU es la respuesta a ese desafío. Se ha diseñado como una plataforma integral, construida sobre una arquitectura de microservicios resiliente y nativa de la nube, para automatizar y optimizar cada etapa del proceso: desde la adquisición y documentación de un vehículo hasta su mantenimiento, venta, generación de reportes estratégicos y predicción de demanda.

Más que un proyecto de grado, SGIVU es un caso de estudio sobre cómo aplicar las mejores prácticas de la ingeniería de software moderna para resolver problemas de negocio tangibles.

## Tabla de Contenidos

- [Tecnologías y Arquitectura](#tecnologías-y-arquitectura)
- [Requisitos Previos](#requisitos-previos)
- [Contribuciones](#contribuciones)
- [Licencia y Créditos](#licencia-y-créditos)
- [Contacto](#contacto)

## Tecnologías y Arquitectura

### Stack Tecnológico

#### Backend

- **Java:** 21
- **Spring Boot:** 3
- **Spring Cloud:** 2025
  - Config Server (Configuración centralizada)
  - Eureka (Descubrimiento de servicios)
  - OAuth2/JWT (Seguridad)
  - Authorization Server (Seguridad)
  - Gateway (Enrutamiento y balanceo)
- **Resilience4j:** Circuit breakers y tolerancia a fallos
- **Micrometer + Zipkin:** Trazabilidad distribuida
- **PostgreSQL:** Base de datos relacional
- **MySQL:** Base de datos relacional

#### Frontend

- **Angular:** 20
- **Bootstrap:** 5
- **Chart.js:** Visualización de datos
- **angular-oauth2-oidc:** Integración de autenticación

#### DevOps

- **Docker:** Contenedores y orquestación
- **AWS:** EC2, RDS, S3
- **Maven:** Gestión de dependencias y construcción

### Patrones Implementados

- **Arquitectura de Microservicios:** Servicios independientes con responsabilidades específicas
- **API Gateway:** Punto de entrada único para todas las peticiones de clientes
- **Service Discovery:** Registro y descubrimiento dinámico de servicios
- **Circuit Breaker:** Prevención de fallos en cascada
- **Externalized Configuration:** Configuración centralizada y externalizada
- **OAuth2/JWT:** Autenticación y autorización segura
- **Single Page Application (SPA):** Frontend Angular con carga dinámica
- **Modelo-Vista-Controlador (MVC):** Separación de responsabilidades en el backend

## Requisitos Previos

### Requisitos

- **Java:**
- **Node.js:**
- **PostgreSQL:**
- **MYSQL:**
- **Maven:**
- **Docker**

### Enlaces a los repositorios

1. [sgivu-config-repo](https://github.com/stevenrq/sgivu-config-repo)
2. [sgivu-config](https://github.com/stevenrq/sgivu-config)
3. [sgivu-discovery](https://github.com/stevenrq/sgivu-discovery)
4. [sgivu-auth](https://github.com/stevenrq/sgivu-auth)
5. [sgivu-user](https://github.com/stevenrq/sgivu-user)
6. [sgivu-gateway](https://github.com/stevenrq/sgivu-gateway)

### Clonar el Repositorio

```bash
git clone https://github.com/stevenrq/nombre-repo.git
cd nombre-repo
```

## Contribuciones

### Guía de Estilo de Commits

El proyecto sigue el estándar de [Conventional Commits](https://www.conventionalcommits.org/):

```markdown
<tipo>(<alcance>): <descripción>

[cuerpo opcional]

[pie opcional]
```

Tipos comunes:

- `feat`: Nueva funcionalidad
- `fix`: Corrección de errores
- `docs`: Cambios en documentación
- `style`: Cambios de formato
- `refactor`: Refactorización de código
- `test`: Adición o corrección de pruebas
- `chore`: Tareas de mantenimiento

### Modelo de Ramas

- `main`: Código en producción
- `develop`: Código en desarrollo
- `feature/*`: Nuevas funcionalidades
- `bugfix/*`: Correcciones de errores
- `release/*`: Preparación para releases
- `hotfix/*`: Correción de errores en producción

## Licencia y Créditos

### Licencia

Este proyecto está licenciado bajo la Licencia MIT.

### Autor

- Steven Ricardo Quiñones

## Contacto

Para consultas o soporte:

- **Email:** [stevenrq8@gmail.com](mailto:stevenrq8@gmail.com)
- **LinkedIn:** [Steven Ricardo Quiñones](https://www.linkedin.com/in/steven-ricardo-quiñones/)
- **GitHub:** [stevenrq](https://github.com/stevenrq)

---

© 2025 Equipo SGIVU. Todos los derechos reservados.
