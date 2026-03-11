# CLAUDE.md

## Project

Frontend Mentor — Recipe Page challenge.
Reproduce the provided design using **HTML and CSS only**. No frameworks.

Design references: `/design/desktop-design.jpg` · `/design/mobile-design.jpg`
Design sizes: Mobile 375px · Desktop 1440px

---

## Project Structure

```
recipe-page/
├── assets/
│   ├── fonts/
│   │   ├── outfit/static/       ← Outfit-Regular, SemiBold, Bold
│   │   └── young-serif/         ← YoungSerif-Regular
│   └── images/
│       └── image-omelette.jpeg
├── index.html
└── style.css
```

---

## HTML Structure

```
body
 └ main
    └ article.recipe
        ├ figure.recipe__image
        ├ header.recipe__header
        ├ section.recipe__preparation
        ├ section.recipe__ingredients
        ├ section.recipe__instructions
        └ section.recipe__nutrition
```

Semantic elements: `main`, `article`, `section`, `figure`, `header`, `ul`, `ol`, `table`.
All images must include `alt` attributes.

---

## CSS Variables

```css
:root {
  /* Colors */
  --color-white:      hsl(0, 0%, 100%);
  --color-stone-100:  hsl(30, 54%, 90%);
  --color-stone-150:  hsl(30, 18%, 87%);
  --color-stone-600:  hsl(30, 10%, 34%);
  --color-stone-900:  hsl(24, 5%, 18%);
  --color-brown-800:  hsl(14, 45%, 36%);
  --color-rose-800:   hsl(332, 51%, 32%);
  --color-rose-50:    hsl(330, 100%, 98%);

  /* Typography */
  --font-serif:  'Young Serif', serif;
  --font-sans:   'Outfit', sans-serif;
  --text-base:   1rem;
}
```

---

## CSS File Structure

```
1. @font-face declarations
2. CSS reset
3. :root variables
4. body base styles
5. Layout (article.recipe)
6. Components (section by section)
7. Responsive (@media min-width: 768px, 1024px, 1440px)
```

---

## Naming Convention (BEM)

```
recipe
recipe__image
recipe__header
recipe__title
recipe__description
recipe__preparation
recipe__section-title
recipe__table
```

---

## Implementation Order

1. HTML structure (all sections, no CSS)
2. `@font-face` + CSS variables + reset + body
3. Layout: article card (white, border-radius, max-width, centered)
4. Components top-to-bottom: image → header → preparation → ingredients → instructions → nutrition
5. Responsive adjustments (desktop: image flush to card edges, wider padding)

---

## Rules

- Mobile-first. Base styles → `@media (min-width: 768px)` → `@media (min-width: 1440px)`
- Flexbox preferred. Grid only if needed.
- Units: `rem` for typography/spacing. Avoid fixed heights.
- Respond with **targeted snippets only**. Never regenerate full files.
- One problem per prompt.
