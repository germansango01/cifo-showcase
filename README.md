# CIFO Violeta Showcase 🎓✨

Plataforma de portafolios institucionales dinámica para el **CIFO La Violeta** (Barcelona).
Este proyecto sirve como un repositorio visual al estilo Semplice o Behance, permitiendo explorar los proyectos finales de los alumnos filtrando por año, área, docente y curso.

---

## 🛠 Stack Técnico

Este proyecto está construido con tecnologías web estándar y está diseñado para ser integrado posteriormente como un tema/template en **Laravel Blade**.

| Tecnología        | Detalles                                                                   |
| :---------------- | :------------------------------------------------------------------------- |
| **HTML**          | HTML5 semántico (`<article>`, `<section>`, `<nav>`, `<aside>`).            |
| **CSS**           | Vanilla CSS (Grid + Flexbox). Arquitectura semántica, sin preprocesadores. |
| **JavaScript**    | Vanilla ES6+. Sin dependencias ni librerías externas.                      |
| **Integración**   | Preparado para motor de plantillas Laravel Blade.                          |
| **Tipografía**    | Google Fonts (Plus Jakarta Sans).                                          |
| **Accesibilidad** | Estándar WCAG 2.1 AA mínimo. Uso correcto de etiquetas ARIA y semántica.   |

---

## 🎨 Filosofía de Diseño

El diseño de la plataforma pone el trabajo del alumno en el centro: **la UI se subordina al contenido**.

- **Inspiración:** Semplice (tarjetas grandes, tipografía bold), Webflow Made In (masonry, transiciones fluidas), Pixpa (espacios generosos).
- **Look & Feel:** Superficies elevadas, microinteracciones sutiles, espaciado amplio y diseño _Mobile First_.
- **Identidad Visual:** Paleta basada en el **violeta institucional** con acentos en **dorado**. Uso de tipografía _display_ para títulos y _sans-serif_ de alta legibilidad para cuerpos de texto.

---

## 📁 Estructura de Páginas

El template consta de las siguientes vistas principales:

| Archivo               | Página              | Descripción                                                                                        |
| :-------------------- | :------------------ | :------------------------------------------------------------------------------------------------- |
| `index.html`          | **Home**            | Estilo editorial: hero section, proyectos destacados, estadísticas y CTA.                          |
| `projects.html`       | **Proyectos**       | Grid completo tipo masonry con filtros select, paginador y botón _back-to-top_.                    |
| `project-detail.html` | **Detalle**         | Vista inmersiva de un proyecto individual completo.                                                |
| `about.html`          | **Sobre el centro** | Layout alternado (imagen/texto) detallando la misión, ciclos formativos y estadísticas del centro. |

---

**CIFO La Violeta**
