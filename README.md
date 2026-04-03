# MK — Portafolio Personal

## Descripción del Proyecto

Este sitio es el **Trabajo Práctico N°1 (PFO1)** de la materia de Desarrollo Web(Front END). Consiste en una landing page de portafolio personal construida únicamente con **HTML semántico y CSS puro**, sin frameworks ni librerías externas (salvo Google Fonts). El objetivo es presentarme a mi, MK: intereses, habilidades, proyectos y formas de contacto.

**URL publicada en GitHub Pages**
https://maiklaus.github.io/PFO1-FrontEnd-MK/

**URL de Vercel**
https://pfo-1-front-end-mk.vercel.app/
---

## Checklist — Práctica Formativa Obligatoria 1

### Estructura del Proyecto

- [x] Archivo `index.html` ubicado en la raíz.
- [x] Carpeta `css` que contenga el archivo `styles.css`.
- [x] (Opcional) Las imágenes se referencian desde URLs externas (Unsplash / DiceBear). Se puede agregar carpeta `img` en una etapa posterior.
- [x] Archivo `README.md` creado, con descripción del TP y este checklist.

### Repositorio y Publicación

- [x] Repositorio en GitHub creado.
- [x] Proyecto subido al repositorio.
- [x] Proyecto publicado utilizando Vercel.
- [x] En el `README.md` se indica la URL de Vercel.

### Uso de Google Fonts

- [x] Enlace a Google Fonts incluido en la sección `<head>` del HTML (Poppins + DM Mono).
- [x] La tipografía importada se aplica en todo el sitio mediante `font-family: var(--ff-head)`.
- [x] **¿Por qué elegiste esa fuente?**
  > Elegí **Poppins** porque me parece algo moderno, lindo pero que se puede leer fácilmente. La combiné con **DM Mono** para tags y labels, para generar un contraste, creo que quedan bien ambas.

### HTML

- [x] El documento inicia con `<!DOCTYPE html>` y usa `lang="es"`.
- [x] Metaetiquetas `charset` y `viewport` presentes.
- [x] Título descriptivo: `MK — Portafolio Personal`.
- [x] CSS vinculado correctamente en `css/styles.css`.
- [x] Enlace a Google Fonts en el `<head>`.
- [x] **Secciones obligatorias en `<main>`:**
  - [x] `id="sobre-mi"` — Presentación personal con imagen y párrafo.
  - [x] `id="tarjetas"` — 3 tarjetas con imagen y texto organizadas con CSS Grid.
  - [x] `id="habilidades"` — Lista de habilidades actuales, a aprender y tabla de hobbies.
  - [x] `id="contacto"` — Formulario con Nombre, Apellido, Email, Teléfono y botón submit.
  - [x] `id="peliculas"` — 3 películas favoritas con imagen, título y descripción.
- [x] Barra de navegación (`<nav>`) con al menos 3 enlaces.
- [x] Al menos 4 comentarios explicativos en el HTML.

### CSS

- [x] Archivo `styles.css` con estilos personalizados.
- [x] Se usan selectores por clases (`.card`, `.btn`, `.hero-name`) e IDs (`#sobre-mi`, `#contacto`).
- [x] Poppins y DM Mono se aplican correctamente en todos los elementos via variables CSS.
- [x] **Layout y Organización:**
  - [x] Sección `#tarjetas`: CSS Grid con `grid-template-columns: repeat(auto-fill, minmax(...))`.
  - [x] Sección `#habilidades`: CSS Grid responsive.
  - [x] Sección `#sobre-mi` (mk): Flexbox.
  - [x] **¿Qué ventajas encontraste al usar Flexbox o Grid?**
    > Grid me permitió crear columnas que se adaptan solas al ancho disponible (`auto-fill` + `minmax`). Flexbox para el mk, donde necesitaba alinear texto e imagen en el eje principal y centrarlos verticalmente.
- [x] Estilos personalizados en tablas (`hobbies-table`), botones (`.btn`), enlaces (`<a>`) y formulario (`.contact-form`).
- [x] Unidades relativas usadas: `rem`, `%`, `vw`, `clamp()`, `min()` en imágenes y contenedores.
- [x] **Animaciones y transiciones:**
  - [x] Se ha implementado al menos una animación o transición.
  - [x] **¿Qué animación implementaste y por qué?**
    > Implementé varias, como el `hover`, o los círculos flotando en la parte superior. Principalmente el hover lo dejé porque queda lindo que se muevan las tarjetas, los círculos fue un agregado que me gustó.

### Consideraciones Adicionales

- [x] El diseño es responsivo: en mobile el hero pasa a columna vertical y las grids se adaptan.
- [x] Buenas prácticas de accesibilidad: atributo `alt` descriptivo en todas las imágenes, `aria-label` en links de footer y nav, `lang="es"` en el HTML.
- [x] Comentarios adicionales en el código HTML describiendo decisiones de diseño y mejoras futuras.
