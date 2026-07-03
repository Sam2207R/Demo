# Buscador Público

Buscador público inspirado en el entorno visual de [www.gob.pe](https://www.gob.pe), la Plataforma Digital del Estado Peruano.

## Tecnologías

- **HTML5** semántico y accesible
- **Tailwind CSS v4** vía CDN (`@tailwindcss/browser`)
- **JavaScript vanilla** sin dependencias
- Tipografía **Inter** (Google Fonts)

## Paleta de colores (gob.pe)

| Color | Hex | Uso |
|---|---|---|
| Gob 800 | `#BF0909` | Header, botones, hover links |
| Gob 700 | `#DC362E` | Hover alternativo |
| Gob 200 | `#FCEEEE` | Fondos suaves, badges, tags |
| Texto | `#0B0C0C` | Texto principal |

## Funcionalidades

- **Búsqueda en tiempo real** por título, descripción y etiquetas
- **Filtros laterales**: categoría (checkboxes), tipo (checkboxes), rango de fecha, ordenamiento
- **Resultados en grid** de 3 columnas (responsive: 1 col móvil, 2 tablet, 3 escritorio)
- **Paginación** configurable (5/10/20 items por página)
- **Tags de filtros activos** visibles sobre los resultados
- **Estado vacío** con sugerencia de limpiar filtros
- **Sidebar colapsable** en móvil con overlay y botón flotante
- **Ejemplos de búsqueda rápida**: DNI electrónico, brevete, salud
- **Animaciones** de entrada en los resultados

## Archivos

- `index.html` — aplicación completa (507 líneas)
- `README.md` — este archivo

## Uso

Abrir `index.html` en cualquier navegador moderno.
