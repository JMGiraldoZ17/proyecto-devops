# Proyecto DevOps

Este proyecto demuestra un flujo completo de CI/CD.

## Tecnologías
- Java (Quarkus)
- Maven
- Docker
- GitHub Actions
- GitHub Container Registry

## Flujo CI/CD

### CI
- Se ejecuta en Pull Requests
- Compila el proyecto con Maven
- Construye la imagen Docker
- Evita merges si el build falla

### CD Dev
- Se ejecuta automáticamente al hacer merge en `dev`
- Simula el despliegue al ambiente de desarrollo

### CD Prod
- Se ejecuta al hacer merge en `master`
- Requiere aprobación manual
- Simula el despliegue a producción

## Estrategia de ramas
- `feature/*` → desarrollo
- `dev` → integración
- `master` → producción

## Objetivo
Simular un pipeline profesional separando CI y CD, con control de calidad y despliegue por ambientes.
