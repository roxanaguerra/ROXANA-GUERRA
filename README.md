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
