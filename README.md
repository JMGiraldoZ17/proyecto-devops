# Proyecto DevOps

Este repositorio se utiliza para prácticas de DevOps enfocadas en integración continua (CI) y despliegue continuo (CD).

## Estrategia de ramas

- master → Producción (solo merges vía PR)
- dev → Integración
- feature/* → Desarrollo de funcionalidades

## Reglas de trabajo

- No se permiten commits directos a `master` ni `dev`
- Todos los cambios deben realizarse mediante Pull Request
- Los PR deben ser aprobados antes de merge
- Hotfix solo desde ramas dedicadas (hotfix/*)
\