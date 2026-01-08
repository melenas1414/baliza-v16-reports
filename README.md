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

## 🔄 Actualización

Los reportes se generan automáticamente cuando ejecutas:

```bash
npm run report
```

Para generar y hacer commit automáticamente:

```bash
npm run report:full
```

## 📈 Contenido de los Reportes

- **Resumen Ejecutivo**: Métricas clave y período de datos
- **Análisis Histórico**: Distribución de tiempo activo y ciclos
- **Rankings**: Top balizas más activas y con mayor tiempo activo
- **Análisis por Ubicación**: Estadísticas por comunidad, provincia y carretera
- **Análisis Temporal**: Patrones por hora del día (media diaria) y día de la semana
- **Estado Actual**: Distribución de balizas activas/perdidas
- **Glosario**: Definiciones de términos técnicos

## 🌐 Ver Reportes Online

Para publicar en GitHub Pages:

1. Sube este repositorio a GitHub
2. Ve a Settings → Pages
3. Selecciona la rama `main` como source
4. Los reportes estarán disponibles en: `https://tuusuario.github.io/balizav16-reports/`

## 🌐 Repositorio Principal

Este es un sub-repositorio. El código fuente principal está en: **balizav16-data**

---

*Generado automáticamente por Balizas V16 Data Fetcher*
