# Generador de Sitios Estáticos (SSG)

## ¿Qué es un SSG?

Un **SSG (Static Site Generator o generador de sitios estáticos)** es una herramienta que genera las páginas de un sitio web como archivos HTML antes de que los usuarios accedan a ellas. Para construir el sitio se pueden utilizar archivos de contenido, como Markdown, plantillas y componentes.

Una vez generado el sitio, los archivos resultantes pueden publicarse en un servidor web o en una CDN, sin necesidad de generar cada página desde cero cuando un usuario la solicita.

## Jekyll

**Jekyll** es un generador de sitios estáticos desarrollado con **Ruby**. Permite escribir contenido en Markdown y utilizar plantillas **Liquid**. Se utiliza habitualmente para blogs, documentación y sitios de contenido.

## Hugo

**Hugo** es un generador de sitios estáticos desarrollado con **Go**. Permite utilizar Markdown para crear contenido y emplea su propio sistema de plantillas. Destaca por su rapidez a la hora de generar sitios web, incluso cuando contienen muchas páginas.

## Astro

**Astro** es un framework orientado a crear sitios web rápidos y basados en contenido. Permite utilizar Markdown, MDX y componentes. Durante la compilación puede generar páginas HTML estáticas.

Astro también permite integrar componentes de tecnologías como React, Vue o Svelte. En su arquitectura habitual, intenta reducir la cantidad de JavaScript que se envía al navegador y permite añadir interactividad únicamente a los componentes que la necesitan.

Por tanto, Astro no significa que todo el sitio tenga que ejecutarse como una aplicación JavaScript en el navegador: puede generar HTML estático y añadir interactividad donde sea necesaria.

## Comparación entre Jekyll, Hugo y Astro

| Aspecto | Jekyll | Hugo | Astro |
|---|---|---|---|
| Tecnología principal | Ruby | Go | JavaScript y TypeScript |
| Formato de contenido | Markdown y otros formatos compatibles | Markdown y otros formatos compatibles | Markdown, MDX y componentes |
| Necesidad de instalación | Requiere Ruby y Jekyll | Requiere Hugo | Requiere Node.js y las dependencias del proyecto |
| Funcionamiento básico | Combina contenido con plantillas Liquid para generar HTML | Combina contenido con plantillas para generar HTML | Genera páginas HTML y permite utilizar componentes interactivos |
| Usos habituales | Blogs, documentación y sitios de contenido | Blogs, documentación y webs con muchas páginas | Blogs, portfolios y sitios basados en componentes |
| Ventajas | Integración con GitHub Pages y sistema de plantillas sencillo | Generación rápida de páginas | Flexibilidad, componentes y posibilidad de reducir el JavaScript enviado al navegador |
| Inconvenientes | Requiere familiarizarse con Ruby y su entorno | Hay que aprender su sistema de plantillas | Requiere conocer Node.js y la estructura de un proyecto Astro |
| Publicación en GitHub Pages | Compatible mediante la configuración admitida por GitHub Pages | Puede publicarse generando primero los archivos estáticos | Puede publicarse generando la salida estática y configurando el despliegue |

## Comparación entre un SSG y la creación manual de páginas HTML

Un sitio web se puede crear escribiendo directamente los archivos HTML o utilizando un generador de sitios estáticos. Ambos métodos producen archivos que el navegador puede interpretar, pero el proceso de creación y mantenimiento es diferente.

| Aspecto | HTML manual | Generador de sitios estáticos (SSG) |
|---|---|---|
| Creación de páginas | Se escribe el HTML de cada página directamente. | Se utilizan contenido, plantillas y herramientas que generan las páginas. |
| Reutilización | Hay que organizar manualmente los elementos comunes o utilizar herramientas adicionales. | Las plantillas y los componentes permiten reutilizar cabeceras, pies de página y estructuras. |
| Actualización | Los cambios comunes pueden requerir editar varios archivos. | Un cambio en una plantilla puede aplicarse a todas las páginas que la utilizan al volver a generar el sitio. |
| Conocimientos necesarios | Conviene conocer HTML y, según el proyecto, CSS y JavaScript. | Hay que aprender la herramienta, su configuración y su sistema de plantillas, además de los formatos utilizados. |
| Número de páginas | Es sencillo empezar con pocas páginas, pero mantener muchas puede resultar repetitivo. | Facilita generar y mantener un gran número de páginas a partir de contenido estructurado. |
| Proceso de publicación | Se publican los archivos creados manualmente. | Primero se ejecuta la compilación y después se publican los archivos generados. |
| Rendimiento | Puede ser muy alto si las páginas están bien construidas. | También puede ser muy alto porque las páginas se generan antes de que se soliciten. |
| Uso recomendado | Sitios pequeños o páginas que requieren una estructura sencilla y específica. | Sitios con muchas páginas, contenido repetitivo, plantillas compartidas o procesos de generación automatizados. |

**Conclusión de la comparación:** para una web pequeña, escribir HTML manualmente puede ser suficiente y sencillo. Cuando el sitio crece y muchas páginas comparten la misma estructura, un SSG facilita la reutilización de plantillas y el mantenimiento. El rendimiento final depende también de los recursos, el código y la infraestructura de publicación, no únicamente del método utilizado.

## Publicación en GitHub Pages

GitHub Pages permite publicar sitios web estáticos desde un repositorio de GitHub. En un proyecto con un SSG, normalmente se genera primero el sitio y después se despliegan los archivos resultantes.

- **Jekyll:** GitHub Pages ofrece compatibilidad integrada con Jekyll para las configuraciones y dependencias admitidas por la plataforma.
- **Hugo:** normalmente se configura un proceso de compilación que genera el sitio antes de publicarlo.
- **Astro:** puede publicarse configurando el proceso de compilación y desplegando su salida estática. Si el proyecto utiliza una dirección de repositorio como `usuario.github.io/nombre-repositorio/`, hay que configurar correctamente la ruta base del sitio.

La configuración exacta depende del repositorio, de la herramienta y del método de despliegue. No basta con subir los archivos fuente: el proceso de publicación debe generar y servir la salida correcta.

## Diferencias principales

- **Jekyll** es una opción habitual para crear blogs y sitios de contenido utilizando Markdown y Liquid.
- **Hugo** destaca por su rapidez de generación y es adecuado para sitios con muchas páginas.
- **Astro** ofrece un sistema basado en componentes y permite añadir interactividad cuando es necesaria.
- **HTML manual** permite controlar directamente cada página, mientras que un SSG facilita reutilizar plantillas y generar muchas páginas de forma coherente.

En conclusión, los tres generadores permiten crear sitios estáticos, pero cada uno tiene sus propias herramientas y características. La elección depende de las necesidades del proyecto, de la experiencia del desarrollador y del proceso de publicación.

## Vídeo sobre SSG

[Ver vídeo sobre SSG](https://www.youtube.com/watch?v=osWfEtbP_sk)

---

[Ir al documento sobre CMS](cms.md)
