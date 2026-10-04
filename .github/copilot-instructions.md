# Instrucciones para Copilot

## Estado actual del repositorio

- El snapshot actual solo contiene `.gitignore`; no hay código fuente, documentación del proyecto ni manifiestos de dependencias.
- El stack previsto para el proyecto está indicado abajo; la arquitectura y el comportamiento aún no pueden deducirse del código.

## Stack tecnológico previsto

El stack se declara para que los modelos ayuden al programador a avanzar más rápido en el desarrollo, evitando proponer tecnologías ajenas a él.

- Backend y automatización: Python 3.13 con Django; usa `uv` para la gestión del entorno y las dependencias cuando se incorpore su configuración. Usa `pytest` para las pruebas automatizadas y `ruff` para lint y formato cuando estén configurados.
- Base de datos: PostgreSQL o SQLite. Confirma la selección en los requisitos o configuración del proyecto antes de implementar dependencias o características específicas de una base de datos.
- Interfaz: HTML y Bootstrap.
- Automatización de navegador: Playwright con Python.
- Control de versiones y colaboración: GitHub; automatización CI/CD mediante GitHub Actions.

## Build, pruebas y lint

- No hay comandos de build, pruebas o lint definidos en el repositorio actual.
- Cuando estén disponibles, consulta los manifiestos, la configuración de `uv` y los workflows de GitHub Actions para obtener los comandos exactos. No inventes comandos ni supongas qué base de datos está seleccionada.

## Arquitectura

- El repositorio actual no incluye una aplicación cuya arquitectura pueda describirse.
- Cuando haya código, identifica sus puntos de entrada, límites entre componentes y flujo de datos a partir de los archivos relacionados antes de proponer cambios; el stack previsto no determina por sí solo estas decisiones.

## Convenciones del repositorio

- No hay convenciones de código establecidas en el snapshot actual. Sigue las convenciones existentes cuando se incorporen archivos de aplicación y actualiza estas instrucciones solo con patrones confirmados en el código o la documentación.
