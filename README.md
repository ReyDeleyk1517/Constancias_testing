# Constancias_testing

Sistema web desarrollado en **Django** para la gestión y generación de constancias laborales de personal docente (promoción vertical/horizontal, admisión, horas adicionales, cambios de centro de trabajo, reconocimiento, basificación, etc.).

El proyecto incluye autenticación de usuarios, captura de datos del docente y su plaza, generación de constancias en PDF (con soporte de logo y código QR), consulta y filtrado de constancias, activación/desactivación por tipo de constancia, y una suite de **pruebas unitarias y de comportamiento (Behave)**.

## Estructura

- `Constancias/` – código del sistema (Django, `manage.py`, Dockerfile, `docker-compose.yml`, `requirements.txt`).
- `Constancias/app/constancias/agregar_constancia/` – aplicación principal: modelos, vistas, formularios, plantillas y pruebas.

## Fecha de creación

El proyecto se creó el **23 de noviembre de 2024**. 

> Aclaración: el proyecto fue creado originalmente en esa fecha y posteriormente migrado a este nuevo repositorio el **22 de octubre de 2026**. Por eso las fechas que muestra el sistema de archivos corresponden al momento de la migración y no a la fecha original de creación.
