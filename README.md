# Frontend Mentor — Recipe Page

![Vista previa del proyecto](./preview.jpg)

## Descripción

Solución al desafío [Recipe Page](https://www.frontendmentor.io/challenges/recipe-page-KiTsR8QQKm) de [Frontend Mentor](https://www.frontendmentor.io).

El objetivo es construir una página de receta estática que se ajuste lo más fielmente posible al diseño proporcionado, tanto en móvil como en escritorio.

---

## Enlaces

- **Repositorio:** [github.com/Buji-90/recipe-page](https://github.com/Buji-90/recipe-page)

---

## 🛠️ Tecnologías utilizadas

- HTML5 semántico
- CSS3 (variables personalizadas, Flexbox, diseño responsive)
- Fuentes locales: [Young Serif](https://fonts.google.com/specimen/Young+Serif) y [Outfit](https://fonts.google.com/specimen/Outfit)

---

## Estructura del proyecto

```
recipe-page/
├── assets/
│   ├── fonts/
│   │   ├── outfit/          # Fuente variable + pesos estáticos
│   │   └── young-serif/     # Fuente regular
│   └── images/
│       ├── favicon-32x32.png
│       └── image-omelette.jpeg
├── design/
│   ├── desktop-design.jpg
│   └── mobile-design.jpg
├── AGENTS.md
├── CLAUDE.md
├── index.html
├── style.css
├── style-guide.md
└── preview.jpg
```

---

## Guía de estilos

### Tipografía

| Fuente       | Pesos       | Uso                        |
|--------------|-------------|----------------------------|
| Young Serif  | 400         | Títulos principales        |
| Outfit       | 400, 600, 700 | Cuerpo de texto y subtítulos |

Tamaño base: `16px`

### Paleta de colores

| Token              | Valor HSL                  |
|--------------------|----------------------------|
| White              | `hsl(0, 0%, 100%)`         |
| Stone 100          | `hsl(20, 23%, 97%)`        |
| Stone 150          | `hsl(30, 18%, 87%)`        |
| Stone 600          | `hsl(37, 13%, 12%)`        |
| Stone 900          | `hsl(24, 5%, 18%)`         |
| Brown 800          | `hsl(14, 45%, 36%)`        |
| Rose 800           | `hsl(332, 51%, 32%)`       |
| Rose 50            | `hsl(329, 72%, 94%)`       |

### Breakpoints

| Dispositivo | Ancho   |
|-------------|---------|
| Móvil       | 375px   |
| Escritorio  | 768px+  |

---

## Lo que aprendí

- Estructura semántica con HTML5 (`<article>`, `<section>`, `<figure>`, `<header>`)
- Cómo cargar fuentes locales con `@font-face`
- Uso de variables CSS (custom properties) para mantener colores y tipografía centralizados
- Diseño responsive sin frameworks: mobile-first con una media query para escritorio
- El modelo de caja y cómo Flexbox ayuda a centrar contenido en la página

---

## Despliegue

Este proyecto puede desplegarse fácilmente en:

- [GitHub Pages](https://pages.github.com/)
- [Vercel](https://vercel.com/)
- [Netlify](https://www.netlify.com/)

---

## Autor

- Frontend Mentor — [@Buji-90](https://www.frontendmentor.io/profile/Buji-90)
- GitHub — [Buji-90](https://github.com/Buji-90)
