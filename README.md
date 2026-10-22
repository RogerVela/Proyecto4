# Proyecto 4 — Big Data urbano (Valencia)

## Descripción

Proyecto del módulo de Big Data Aplicado orientado al tratamiento y
análisis de datos urbanos de Valencia.

Este repositorio contiene la estructura inicial para organizar los
procesos de obtención, transformación y visualización de datos.

## Objetivo

Preparar un entorno de trabajo para analizar datos urbanos de Valencia
y presentar los resultados mediante visualizaciones.

En esta primera fase se prepara el repositorio Git y su documentación.
Los conjuntos de datos, las herramientas y los análisis concretos
se definirán en el bloque correspondiente.

## Arquitectura

El siguiente diagrama representa una propuesta inicial del flujo de
datos. Los componentes todavía no están implementados.

```mermaid
flowchart LR
    A["Fuentes de datos urbanos de Valencia"] --> B["Ingesta"]
    B --> C["ETL: transformación y preparación"]
    C --> D["Datos preparados para el análisis"]
    D --> E["Dashboard: análisis y visualización"]
```

## Estructura del repositorio

```text
Proyecto4/
├── ingesta/
├── etl/
├── dashboard/
├── .gitignore
└── README.md
```

- `ingesta/`: futuros procesos de obtención de datos urbanos.
- `etl/`: futuros procesos de extracción, transformación y carga.
- `dashboard/`: futura visualización de los resultados.
- `.gitignore`: reglas para excluir datos, credenciales y archivos locales.
- `README.md`: documentación principal del proyecto.

## Entorno base del módulo

- Git y cuenta en GitHub.
- Docker Desktop y Docker Compose.
- Python 3.10 o superior y pip.
- Editor de código, como Visual Studio Code.

## Estado actual

Repositorio en fase de preparación inicial.

Las fuentes de datos concretas y los procesos de ingesta, ETL y
dashboard están pendientes de definición y desarrollo.