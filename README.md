# Microservicio DevOps Demo

## Descripción

Repositorio de microservicio desarrollado como demostración de prácticas DevOps utilizando Node.js, Docker y GitHub Actions.

El proyecto implementa:
- Integración continua (CI)
- Contenedorización con Docker
- Orquestación con Docker Compose
- Testing automatizado
- Estrategia GitFlow
- Automatización mediante GitHub Actions

---

# Tecnologías utilizadas

- Node.js
- Express
- Docker
- Docker Compose
- GitHub Actions
- Jest
- Git
- GitFlow

---

# Estrategia de ramas

Se utiliza GitFlow.

## Ramas principales

- `main`
- `develop`

## Ramas de apoyo

- `feature/*`
- `hotfix/*`

---

# Flujo de trabajo

```text
feature → develop
develop → main
hotfix → main
