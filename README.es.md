Available in: [English](README.md)

# Pawtastic – Página de Inicio de la Tienda de Mascotas

## Descripción del Proyecto
**Pawtastic** es una página de inicio pre-lanzamiento para una tienda de mascotas en línea. El proyecto se centra en **diseño web responsivo, semántico y accesible**, implementado únicamente con HTML, CSS y Sass. Este proyecto demuestra una atención cuidadosa a **diseño Pixel Perfect, layouts adaptativos, optimización y buenas prácticas de front-end**.

Este proyecto se desarrolló como parte de un curso profesional de desarrollo web, incluyendo trabajo con listas de errores, revisiones de código por el líder del equipo y requisitos del cliente.

---

## Tecnologías y Herramientas
- **HTML5** – estructura semántica usando `<main>`, `<section>`, `<form>` y otras etiquetas semánticas  
- **CSS3 & Sass (SCSS)** – estilos modulares con variables para colores y tipografías  
- **Metodología BEM** – nombres de clases organizados y mantenibles  
- **Flexbox & CSS Grid** – para layouts y diseño adaptativo  
- **Transiciones CSS & Efectos Hover** – estados interactivos para botones, enlaces y animaciones del logo  
- **Diseño Responsivo** – probado en anchos de pantalla de 360px a 4000px  
- **Buenas Prácticas de Accesibilidad** – `aria-labels`, estados de foco, campos requeridos, áreas interactivas predecibles  
- **Optimización** – imágenes rasterizadas preparadas para pantallas 2x, optimizadas con Squoosh, lazy loading para imágenes de contenido  
- **Favicon & Web App Manifest** – `site.webmanifest` incluido y fuentes precargadas  

---

## Aspectos Destacados del Proyecto
- **Layout Pixel Perfect**: Coincide con el diseño de Figma con tolerancia de ±10px  
- **Diseño Adaptativo y Elástico**: Totalmente responsivo desde móvil (360px) hasta pantallas grandes (4000px)  
- **Corrección de Errores & Implementación de Revisiones**: Se aplicaron correcciones de la lista de errores y recomendaciones del líder del equipo, incluyendo:  
  - Campos de input y botones correctamente anidados en formularios  
  - Estados hover/focus correctos para todos los elementos interactivos  
  - Eliminación de CSS `!important`  
  - Pointer-events deshabilitado para elementos decorativos  
  - Padding adecuado en contenedores para layouts responsivos  
- **Elementos Interactivos & Animaciones**:  
  - Animación hover del logo: cambio de color y transición animada de orejas de gato a orejas de perro  
  - Animación hover del bloque de suscripción: efecto de línea de fondo y ajuste de brillo de la imagen  
- **Imágenes & Gráficos**:  
  - Imágenes rasterizadas optimizadas para pantallas retina  
  - Imágenes vectoriales añadidas a un sprite  
  - Todas las imágenes tienen atributos de ancho y alto para evitar cambios de layout  
- **Tipografía & Fuentes**:  
  - Fuentes precargadas para mejorar el rendimiento  
  - Variables de color en SCSS para un estilo consistente  
- **Accesibilidad & Semántica**:  
  - Todos los formularios usan atributos `required` y `name/id` correctos  
  - Encabezados ocultos añadidos donde es necesario  
  - Todos los enlaces y botones tienen texto claro o etiquetas ocultas  
- **Calidad de Código & Buenas Prácticas**:  
  - Estructura modular SCSS  
  - Metodología BEM  
  - Estructura semántica HTML5  
  - Validado con HTML y BEM validators  
- **Logotipo SVG y Animaciones**:  
  - Logotipo principal completo mantenido en línea para conservar las animaciones al pasar el cursor (cambio de color + cambio de orejas de gato/perro)

---

## Cómo Ver / Ejecutar
Dado que este es un proyecto estático, no se requiere configuración de build o JavaScript. **Sass debe compilarse a CSS** para que los estilos se vean correctamente:

1. Clona el repositorio:
   ```bash
   git clone https://github.com/Alyona-K/pawtastic
   ```

2. Abre la carpeta del proyecto en VS Code.

3. Inicia Live Sass Compiler (o cualquier watcher de Sass) para compilar SCSS a CSS

4. Asegúrate de que el CSS compilado se guarde en /css/style.css.

5. Abre index.html en cualquier navegador moderno (se recomienda Chrome).

6. Opcionalmente, usa la extensión Live Server de VS Code para refresco en tiempo real:

Haz clic derecho en index.html → "Open with Live Server"

## Rendimiento y Accesibilidad
Este proyecto alcanza **puntuaciones perfectas en Lighthouse (100/100)** en Performance, Accessibility, Best Practices y SEO.  

Factores clave que contribuyen a este resultado:
- Fuentes precargadas para evitar cambios de diseño (layout shifts)  
- Atributos `width` y `height` definidos en todas las imágenes  
- Imágenes rasterizadas optimizadas con Squoosh (incluyendo versiones 2x)  
- Uso correcto de HTML semántico y etiquetas ARIA  
- Sin CSS ni JavaScript innecesarios  

![Lighthouse score](lighthouse-report.jpg)
