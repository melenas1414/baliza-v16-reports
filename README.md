# 📊 Balizas V16 - Reportes Generados

Este repositorio contiene los reportes generados automáticamente por el sistema de análisis de Balizas V16.

## 📁 Estructura de Archivos

Cada reporte se genera con un timestamp único en formato `report-YYYY-MM-DDTHH-MM-SS`:

```
reports/
├── report-2026-01-08T17-56-47.json  # Datos estructurados
├── report-2026-01-08T17-56-47.html  # Visualización web
└── report-2026-01-08T17-56-47.md    # Documentación
```

## 📊 Formatos Disponibles

### JSON
Datos crudos y estructurados para análisis programático.

### HTML
Reporte visual interactivo con gráficos y tablas.
- Abre con cualquier navegador web
- Incluye gráfico de líneas con media diaria de activaciones por hora
- Diseño responsive

### Markdown
Documentación legible para GitHub/GitLab.
- Compatible con wikis y documentación
- Incluye todos los análisis y rankings

## � Contenido de los Reportes

- **Resumen Ejecutivo**: Métricas clave y período de datos
- **Análisis Histórico**: Distribución de tiempo activo y ciclos
- **Rankings**: Top balizas más activas y con mayor tiempo activo
- **Análisis por Ubicación**: Estadísticas por comunidad, provincia y carretera
- **Análisis Temporal**: Patrones por hora del día (media diaria) y día de la semana
- **Estado Actual**: Distribución de balizas activas/perdidas
- **Glosario**: Definiciones de términos técnicos

## 🌐 Ver Reportes Online

Reportes disponibles en GitHub Pages: **https://melenas1414.github.io/baliza-v16-reports/**

---

*Generado automáticamente por Balizas V16 Data Fetcher*
