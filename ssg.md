# Generador de Sitios Estáticos (SSG)

## ¿Qué es un SSG?

Un **SSG (Static Site Generator)** es una herramienta que genera las páginas de un sitio web como archivos HTML estáticos antes de que los usuarios accedan a ellas. Para crear el sitio se pueden utilizar archivos de contenido, como Markdown, y plantillas.

## Jekyll

**Jekyll** es un generador de sitios estáticos desarrollado con **Ruby**. Permite escribir contenido en Markdown y utilizar plantillas **Liquid**. Es especialmente utilizado para blogs y sitios de contenido.

## Hugo

**Hugo** es un generador de sitios estáticos desarrollado con **Go**. Permite utilizar Markdown para crear contenido y utiliza plantillas de Go. Destaca especialmente por su rapidez a la hora de generar los sitios web.

## Astro

**Astro** es un framework orientado a crear sitios web rápidos y basados en contenido. Permite utilizar Markdown y componentes, y puede generar el sitio como HTML estático durante el proceso de compilación. También permite utilizar componentes de tecnologías como React, Vue o Svelte cuando son necesarios.

## Comparación entre Jekyll, Hugo y Astro

| Aspecto que Investigar | Jekyll | Hugo | Astro |
| --- | --- | --- | --- |
| Tecnología o lenguaje principal | Ruby/Liquid | Go | JS/TS |
| Formato utilizado para el contenido | Markdown | Markdown | Markdown |
| Necesidad de instalación | Si, Ruby | Si, Hugo | Si, Node.js |
| Funcionamiento básico | Contenido en Markdown, plantillas con Liquid. Jekyll genera el HTML | Contenido en Markdown y Hugo genera el HTML | Solo carga JavaScript en los componentes interactivos necesarios. |
| Usos habituales | Blogs, documentación | Blogs, webs | Blogs, portfolios |
| Ventajas | Uso sencillo | Destaca por su velocidad. | Destaca por su velocidad y modernidad. |
| Inconvenientes | Depende de Ruby, puede ser complicado de instalar. | Requiere mayor aprendizaje | Requiere conocer Node.js y conceptos de JavaScript. |
| Posibilidad de publicarlo en GitHub Pages | Si | Si | Si | 

![imagen CMS](/gestoresContenido/imagen_ssg.png)

### Diferencias principales

- **Jekyll** es una opción sencilla para crear blogs y sitios de contenido utilizando Markdown y Liquid.
- **Hugo** destaca por su velocidad de generación y es adecuado para sitios con muchas páginas.
- **Astro** ofrece un sistema basado en componentes y permite añadir interactividad utilizando diferentes frameworks.

En conclusión, los tres permiten crear sitios estáticos, pero cada uno está orientado a diferentes necesidades. **Jekyll** destaca por su sencillez, **Hugo** por su velocidad y **Astro** por su flexibilidad y uso de componentes.

## Video sobre SSG

[Ver vídeo](https://www.youtube.com/watch?v=osWfEtbP_sk)

---
---

[Ir al documento sobre CMS](cms.md)
