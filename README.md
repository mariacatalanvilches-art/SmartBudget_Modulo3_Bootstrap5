# SmartBudget - Proyecto Módulo 3

## Descripción

SmartBudget es una landing page desarrollada como maqueta funcional para una aplicación web de finanzas personales.

El objetivo del sitio es mostrar una interfaz moderna, responsiva y organizada, que permita presentar las principales funciones de la aplicación.

## Tecnologías utilizadas

- HTML5
- CSS3
- SASS / SCSS
- Bootstrap 5
- Flexbox
- CSS Grid
- Metodología BEM
- Diseño responsive

## Metodología CSS

Se utilizó la metodología **BEM** porque permite organizar las clases de forma clara y fácil de mantener.

Ejemplo:

```html
<section class="hero">
  <h1 class="hero__title">Organiza tus finanzas con SmartBudget</h1>
  <p class="hero__text">Landing page para una aplicación web.</p>
</section>
```

En este ejemplo:

- `hero` es el bloque.
- `hero__title` es un elemento del bloque.
- `hero__text` es otro elemento del bloque.

## Uso de SASS

El proyecto incluye una estructura SASS basada en el patrón 7-1:

```text
scss/
├── abstracts/
├── base/
├── components/
├── layout/
├── pages/
├── themes/
├── vendors/
└── style.scss
```

Esta estructura ayuda a dividir los estilos en archivos más pequeños y ordenados.

## Uso de Bootstrap 5

Se integró Bootstrap 5 mediante CDN.

Componentes utilizados:

- Navbar
- Cards
- Botones
- Modal
- Formulario
- Sistema de grillas

## Diseño responsive

El sitio se adapta a escritorio, tablet y dispositivos móviles mediante:

- Grilla de Bootstrap
- Flexbox
- CSS Grid
- Media Queries

## Estructura del proyecto

```text
SmartBudget_Modulo3_Bootstrap5/
├── index.html
├── README.md
├── css/
│   └── style.css
├── scss/
│   ├── abstracts/
│   ├── base/
│   ├── components/
│   ├── layout/
│   ├── pages/
│   ├── themes/
│   ├── vendors/
│   └── style.scss
├── assets/
│   └── img/
├── capturas/
└── docs/
```

## Reflexión

Este proyecto permitió aplicar buenas prácticas de desarrollo Front-End, usando HTML semántico, SASS, Bootstrap 5, metodología BEM y diseño responsive.

También se trabajó el modelo de cajas, el uso de componentes reutilizables y la organización modular del código.

## Autor

María Catalán  
Curso Desarrollo Front-End  
Proyecto Módulo 3

## Repositorio GitHub

https://github.com/mariacatalanvilches-art/SmartBudget_Modulo3_Bootstrap5

