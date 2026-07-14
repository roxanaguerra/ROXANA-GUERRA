# Portafolio — Roxana Guerra

Sitio web personal y portafolio de **Roxana Guerra Apaza**, desarrolladora Front-end. Presenta información profesional, habilidades técnicas, proyectos realizados y datos de contacto.

## Sobre el proyecto

Este repositorio contiene el código fuente del portafolio. Es un sitio estático construido con HTML, CSS y JavaScript, sin proceso de compilación ni dependencias de Node.js.

**Secciones principales:**
- Presentación y descarga de CV
- Acerca de mí
- Tech Skills
- Portafolio de proyectos
- Contacto

**Tecnologías utilizadas:**
- HTML5, CSS3 y JavaScript
- Librerías: Font Awesome, Animate.css, Owl Carousel, Lightbox, Typed.js, entre otras

## Requisitos

No se requiere instalación de dependencias. Solo necesitas:

- Un navegador web moderno (Chrome, Firefox, Edge, Safari)
- *(Opcional)* Un servidor HTTP local para una experiencia más cercana a producción

## Cómo levantarlo localmente

### Opción 1: Abrir directamente en el navegador

1. Clona o descarga el repositorio.
2. Abre el archivo `index.html` con tu navegador.

```bash
# Desde la raíz del proyecto (Windows)
start index.html
```

> En algunos casos, abrir el HTML directamente puede limitar ciertas funcionalidades. Se recomienda usar un servidor local.

### Opción 2: Servidor con Python (recomendado)

Si tienes [Python](https://www.python.org/) instalado:

```bash
# Python 3
python -m http.server 8000
```

Luego abre en el navegador: [http://localhost:8000](http://localhost:8000)

### Opción 3: Servidor con Node.js (sin instalar dependencias)

Si tienes [Node.js](https://nodejs.org/) instalado:

```bash
npx serve .
```

Sigue la URL que muestre la terminal (por ejemplo, `http://localhost:3000`).

### Opción 4: Live Server en VS Code / Cursor

1. Instala la extensión **Live Server**.
2. Abre la carpeta del proyecto.
3. Haz clic derecho en `index.html` → **Open with Live Server**.

## Publicar cambios en GitHub Pages

El sitio está publicado con [GitHub Pages](https://pages.github.com/) desde la rama `gh-pages`.

**URL del sitio:** [https://roxanaguerra.github.io/ROXANA-GUERRA/](https://roxanaguerra.github.io/ROXANA-GUERRA/)

### Flujo para cada modificación

Después de editar archivos localmente, sigue estos pasos para que los cambios se vean en el sitio publicado:

```bash
# 1. Guardar los cambios en git
git add .
git commit -m "Descripción breve del cambio"

# 2. Subir los cambios a la rama principal
git push origin master

# 3. Publicar en GitHub Pages (actualizar la rama gh-pages)
git push origin master:gh-pages
```

### Después del push

1. Espera **1–3 minutos** mientras GitHub Pages actualiza el sitio.
2. Verifica el estado en **GitHub → Settings → Pages** de tu repositorio.
3. Abre el sitio y recarga con caché limpia: `Ctrl + F5` (Windows) o `Ctrl + Shift + R`.

### Alternativa: merge manual en gh-pages

Si prefieres trabajar con la rama `gh-pages` localmente:

```bash
git checkout gh-pages
git merge master
git push origin gh-pages
git checkout master
```

> **Nota:** Los cambios en `master` no se publican solos. Siempre debes actualizar `gh-pages` para que el sitio en línea refleje las modificaciones.

## Estructura del proyecto

```
├── index.html          # Página principal
├── css/                # Estilos personalizados
├── js/                 # Scripts del sitio
├── img/                # Imágenes del portafolio
├── img-skills/         # Iconos de habilidades
├── doc/                # Documentos (CV)
└── lib/                # Librerías de terceros (Bootstrap, etc.)
```

## Autora

**Roxana Guerra Apaza** — Front-end Developer
