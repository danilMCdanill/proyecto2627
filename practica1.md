## Resumen de elementos y plugin de ReadtheDocs

- **ProperDocs**: generador de sitios estáticos que convierte archivos Markdown
  en una web de documentación. Se configura con `properdocs.yml`.
- **Tema `readthedocs`**: tema con barra lateral de navegación, diseño
  adaptable y buscador integrado.

| Elemento | Descripción |
|---|---|
| `properdocs.yml` | Configuración: nombre del sitio, tema, navegación y plugins |
| Carpeta `docs/` | Páginas de la documentación en Markdown |
| `nav` | Define el menú lateral y el orden de las páginas |
| Carpeta `site/` | HTML estático generado con `properdocs build` |

| Plugin | Función |
|---|---|
| `search` | Añade el buscador al sitio |