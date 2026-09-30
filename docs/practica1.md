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

## Capturas

![ProperDocs en funcionamiento: `properdocs.yml` abierto en VS Code, `properdocs serve` en la terminal y el sitio visible en `127.0.0.1:8000`.](img/practica01/captura01.png)

*Captura 01: ProperDocs en funcionamiento: `properdocs.yml` abierto en VS Code, `properdocs serve` en la terminal y el sitio visible en `127.0.0.1:8000`.*

![Configuración de Git: comandos `git config` y listado con el usuario y el email.](img/practica01/captura02.png)

*Captura 02: Configuración de Git: comandos `git config` y listado con el usuario y el email.*

![Comprobación de la sesión de GitHub con `gh auth status`.](img/practica01/captura03.png)

*Captura 03: Comprobación de la sesión de GitHub con `gh auth status`.*

![Comprobación de la instalación de Herd con `herd --version` (1.30.1).](img/practica01/captura04.png)

*Captura 04: Comprobación de la instalación de Herd con `herd --version` (1.30.1).*

![Carpeta personal en Finder con `Herd`, `docs`, `proyecto2627` y `properdocs.yml`.](img/practica01/captura05.png)

*Captura 05: Carpeta personal en Finder con `Herd`, `docs`, `proyecto2627` y `properdocs.yml`.*

![Herd, sección Sites: sitio `misitio.test` con PHP 8.4 y ruta `~/Herd/misitio/`.](img/practica01/captura06.png)

*Captura 06: Herd, sección Sites: sitio `misitio.test` con PHP 8.4 y ruta `~/Herd/misitio/`.*
