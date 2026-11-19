# La Carbonería — sitio web

Sitio publicado en **https://lacarboneriacl.cl** (GitHub Pages, rama `main`).

## Estructura

```
index.html   → la página completa (textos, precios, estilos)
CNAME        → dominio lacarboneriacl.cl — NO borrar ni editar
img/         → imágenes del sitio
404.html     → página que se muestra cuando una dirección no existe
favicon.svg  → ícono de la pestaña del navegador
sitemap.xml  → lista de páginas para Google y Bing (agregar aquí cada página nueva)
robots.txt   → permisos para buscadores; apunta al sitemap
llms.txt     → resumen de la empresa para asistentes de IA
```

**Formulario de contacto:** envía las consultas por Formspree (formspree.io) al correo comercial. El código del formulario va en `index.html`, en `data-formspree-id="..."` de la etiqueta `<form>`. Si ese campo queda vacío, el botón "Enviar consulta" abre el correo del visitante en vez de enviar.

**Si cambia un precio, la capacidad o un dato de contacto**, hay que actualizarlo en tres lugares: el texto visible de `index.html`, el bloque `application/ld+json` al inicio de `index.html` y `llms.txt`.

| Imagen | Dónde se usa |
|---|---|
| `img/hero.jpg` | Fondo de la portada |
| `img/fondo-capacidad.jpg` | Fondo de la sección de capacidad (320T) |
| `img/qb-blanco-2_5kg.jpg` | Producto QB Blanco 2,5 kg |
| `img/qb-colorado-2_5kg.jpg` | Producto QB Colorado 2,5 kg |
| `img/qb-colorado-2kg.jpg` | Producto QB Colorado 2 kg |
| `img/saco-qb-blanco-15kg.jpg` | Producto Saco QB Blanco 15 kg |
| `img/qb-colorado-granel.jpg` | Producto QB Colorado Granel y sección "Nosotros" |

## Cómo editar y publicar (desde cualquier computador)

1. Instalar **GitHub Desktop** (desktop.github.com) e iniciar sesión con la cuenta `gfmingo-jpg`.
2. La primera vez: *File → Clone repository → gfmingo-jpg/lacarboneria*.
3. Antes de editar: botón **Fetch origin / Pull origin** (para tener la última versión).
4. Editar `index.html` (o reemplazar una imagen en `img/` **con el mismo nombre**).
5. En GitHub Desktop: escribir un resumen del cambio → **Commit to main** → **Push origin**.
6. Esperar 1–3 minutos y revisar lacarboneriacl.cl en ventana de incógnito (Cmd+Shift+R).

### Reglas para mantenerlo ordenado
- Editar siempre **este** `index.html`; no subir copias como `index (3).html`.
- Imágenes nuevas van en `img/`, con nombres en minúscula y sin espacios (ej. `qb-blanco-5kg.jpg`).
- Si se agrega una imagen nueva, actualizar la tabla de arriba.
