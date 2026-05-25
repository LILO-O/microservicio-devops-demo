# microservicio-devops-demo

## Descripción
Repositorio de microservicio preparado para pipeline DevOps.

## Estrategia de ramificación
Se utiliza GitFlow.

Ramas principales:
- main
- develop

Ramas de apoyo:
- feature/*
- hotfix/*

## Justificación
Permite trabajo colaborativo ordenado, trazabilidad y control de versiones.

## Flujo de trabajo
- feature → develop
- develop → main
- hotfix → main

## Convenciones

### Naming de ramas
- feature/nombre
- hotfix/nombre

### Commits
- feat: nueva funcionalidad
- fix: corrección
- docs: documentación

## Automatización
Se utiliza GitHub Actions para ejecutar un pipeline en cada push a develop y pull request a main.
