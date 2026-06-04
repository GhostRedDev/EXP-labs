# EXP Labs — Portfolio de estudio de desarrollo web

Sitio web de portfolio de una sola página para una empresa de desarrollo web,
inspirado en estéticas modernas y audaces (estilo trucknroll.com): tipografía
grande, colores vibrantes con acentos cálidos, secciones oscuras y animaciones
suaves al hacer scroll.

## Características

- **Sin dependencias ni build** — HTML, CSS y JS puro. Abre `index.html` y listo.
- **Responsive** — diseño mobile-first con menú hamburguesa.
- **Animaciones** — reveal al hacer scroll, contadores animados, marquee de
  tecnologías, glow que sigue el cursor y micro-interacciones en hover.
- **Secciones**: Hero, Stats, Servicios, Trabajo/Portfolio, Proceso,
  Testimonios, Nosotros, CTA con formulario de contacto y Footer.
- **Accesibilidad** — respeta `prefers-reduced-motion`, HTML semántico.

## Estructura

```
index.html    # Marcado y contenido
styles.css    # Estilos, tokens de diseño y responsive
script.js     # Interacciones (scroll, menú, contadores, form demo)
```

## Uso

Abre `index.html` en el navegador, o sírvelo localmente:

```bash
python3 -m http.server 8000
# luego visita http://localhost:8000
```

## Personalización

- Colores y tokens: variables CSS en `:root` dentro de `styles.css`.
- Color de acento principal: `--accent` (`#ff5f3a`).
- Tipografías: Space Grotesk (títulos) + Inter (texto), vía Google Fonts.
- Contenido (textos, proyectos, testimonios): editable directamente en `index.html`.

> El formulario de contacto es una demo en front-end. Para producción, conéctalo
> a un servicio (Formspree, un endpoint propio, etc.).
