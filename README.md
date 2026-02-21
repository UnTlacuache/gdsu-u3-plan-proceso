# gdsu-u3-plan-proceso

## Plan del Proceso de Desarrollo de Software III  
Implementación de un pipeline CI/CD con GitHub Actions.


## Descripción del proyecto

Este repositorio contiene la implementación práctica de un pipeline de Integración Continua (CI) y Entrega Continua (CD) utilizando GitHub Actions.

El objetivo es automatizar el proceso de:

- Construcción del proyecto
- Ejecución de pruebas
- Validación
- Empaquetado
- Generación automática de Releases
- Documentación automática con Release Drafter


## Tecnologías utilizadas

- GitHub Actions
- Makefile
- Release Drafter
- Flujo basado en Pull Requests
- Control de versiones con Git


## Flujo del Pipeline

El pipeline ejecuta automáticamente los siguientes pasos:

1. Checkout del código
2. Instalación de herramientas
3. Lint
4. Build
5. Unit Tests
6. Validación
7. Integration Tests
8. Empaquetado
9. Creación automática de GitHub Release


## Releases automáticas

Cada vez que se hace merge a la rama `main`, el workflow:

- Genera el artefacto `.zip`
- Crea una nueva versión
- Publica automáticamente el release en GitHub


## Estructura del repositorio

.github/workflows/ # Workflows de GitHub Actions
u3_tarea0/
u3_tarea1/
u3_tarea2/
README.md



## 👩‍💻 Autora

Andrea González  
TSU en Desarrollo de Software de Código Abierto
