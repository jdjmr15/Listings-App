# Django Takeoff: Developing Modern Applications

Curso práctico de Django en el que se construye paso a paso una aplicación web de publicaciones (Listings). Cubre el flujo completo de desarrollo: desde la configuración inicial del proyecto hasta el despliegue en la nube.

## Contenidos principales
- Configuración del proyecto, base de datos y archivos multimedia.
- Modelos, vistas, URLs y plantillas de Django.
- Páginas para crear, consultar, editar y eliminar publicaciones.
- Gestión de usuarios y registro de cuentas.
- Relaciones entre modelos mediante claves foráneas.
- Carga y visualización de imágenes.
- Filtros y búsquedas de publicaciones.
- Estilos con Bootstrap y formularios con Django Crispy Forms.
- Integración con AWS —Amazon RDS y S3— y despliegue en Heroku.
- Proyecto complementario: generador de CV con Django.

## Objetivos de aprendizaje
Al finalizar, podrás crear una aplicación Django desde cero, estructurar sus modelos y páginas, implementar relaciones y formularios, y prepararla para su publicación en la nube.

## Stack
- Backend y automatización: Python 3.13 con Django; usa `uv` para la gestión del entorno y las dependencias cuando se incorpore su configuración. Usa `pytest` para las pruebas automatizadas y `ruff` para lint y formato cuando estén configurados.
- Base de datos: PostgreSQL o SQLite. Confirma la selección en los requisitos o configuración del proyecto antes de implementar dependencias o características específicas de una base de datos.
- Interfaz: HTML y Bootstrap.
- Automatización de navegador: Playwright con Python.
- Control de versiones y colaboración: GitHub; automatización CI/CD mediante GitHub Actions.