# Portafolio Profesional - Sitio Web con HTML y CSS

Sitio web personal de 5 vistas desarrollado con HTML5 y CSS3, como práctica integradora de la asignatura Programación Web.

## Descripción

Portafolio profesional de Ernesto, desarrollador web Full Stack. El sitio presenta información sobre su experiencia, servicios ofrecidos, formulario de contacto y acceso de inicio de sesión.

## Estructura del proyecto

```
/
├── index.html          # Vista 1 - Inicio
├── about.html          # Vista 2 - Sobre mí
├── services.html       # Vista 3 - Servicios
├── contact.html        # Vista 4 - Contacto
├── login.html          # Vista 5 - Iniciar sesión
├── estilos.css         # Hoja de estilos única
├── script.js           # Toggle de tema claro/oscuro
└── README.md           # Este archivo
```

## Características

- **5 vistas enlazadas** con navegación funcional
- **Diseño responsivo** (desktop, tablet, móvil)
- **Tema claro/oscuro** con persistencia en localStorage
- **Estructura semántica** completa (header, nav, main, footer, section, article)
- **Metaetiquetas SEO** en cada vista
- **Animaciones CSS** de entrada en la página de inicio
- **Transiciones suaves** en tarjetas de servicios
- **Formularios con validación** nativa HTML5
- **Accesibilidad**: contraste adecuado, `prefers-reduced-motion`, focus visible

## Requisitos técnicos cumplidos

| Requisito | Implementación |
|-----------|----------------|
| Header/nav con Flexbox | Presente en las 5 vistas |
| Un solo archivo CSS | `estilos.css` enlazado desde todas las páginas |
| Estructura semántica | header, nav, main, footer, section, article |
| SEO básico | meta description, keywords, author, Open Graph |
| Responsive | Media queries en 1024px, 768px, 480px |
| Tema claro/oscuro | Toggle con `data-theme` y variables CSS |
| Animación de entrada | `@keyframes fadeIn` y `slideUp` en hero |
| Grid 2 columnas | Sección "Sobre mí" con `grid-template-columns` |
| Tarjetas con hover | 6 tarjetas con `transition` y `transform` |
| Formulario 4+ campos | texto, email, teléfono, select, textarea, checkbox |
| Validación HTML5 | `required`, `minlength`, `type="email"`, `pattern` |
| Modelo de caja | `box-sizing: border-box`, padding, margin, border |

## Cómo usar

1. Clonar el repositorio:
   ```bash
   git clone https://github.com/tu-usuario/portafolio-web.git
   ```

2. Abrir `index.html` en el navegador, o usar un servidor local:
   ```bash
   # Python 3
   python -m http.server 8000

   # Node.js
   npx serve .
   ```

3. Navegar entre las vistas usando el menú de navegación.

## Tecnologías

- HTML5 (semántico)
- CSS3 (Flexbox, Grid, animaciones, transiciones, variables CSS)
- JavaScript (tema claro/oscuro)
- Google Fonts (Inter)

## Autor

**Ernesto** - Desarrollador Web Full Stack

## Licencia

© 2026 Ernesto. Todos los derechos reservados.
