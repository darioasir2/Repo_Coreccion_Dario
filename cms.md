# Sistemas de Gestión de Contenidos (CMS)

## ¿Qué es un CMS?

Un **CMS (Content Management System o sistema de gestión de contenidos)** es un programa que permite crear, editar, organizar y publicar contenido de una página web sin necesidad de programar todas sus partes manualmente.

## ¿Cómo funciona un CMS?

Los contenidos se administran mediante un panel de control. Desde ese panel se pueden añadir imágenes, vídeos, textos y páginas, además de modificar y organizar la información. Una vez terminado el proceso, el contenido se puede publicar para que aparezca en la web.

Muchos CMS utilizan una base de datos para almacenar el contenido y un sistema que genera las páginas cuando los usuarios las solicitan. Sin embargo, existen diferentes arquitecturas y no todos funcionan exactamente de la misma manera.

## Tipos de CMS

Los CMS se pueden clasificar según la utilidad que se les dé:

1. **Gestión de contenidos y blogs:** WordPress, Joomla y Blogger.
2. **Comercio electrónico:** Shopify y Magento (Adobe Commerce).
3. **Foros y comunidades:** phpBB.
4. **Sitios de información colaborativa:** MediaWiki.
5. **Gestión del aprendizaje (LMS):** Moodle y Canvas LMS.

### Clasificación según su arquitectura

- **CMS monolíticos o acoplados:** el sistema de gestión del contenido y la parte que presenta la web están integrados en una misma aplicación. WordPress es un ejemplo habitual de este modelo.
- **CMS desacoplados (decoupled):** la gestión del contenido está separada de la capa de presentación, aunque el sistema puede proporcionar mecanismos propios para entregar el contenido.
- **CMS headless:** gestiona el contenido y lo distribuye mediante una API a distintos clientes, como una web, una aplicación móvil u otros dispositivos. No impone una interfaz de presentación concreta.

**Nota:** Canvas LMS es una plataforma de gestión del aprendizaje. No debe confundirse con Canva, una herramienta de diseño gráfico.

![Tipos de CMS](gestoresContenido/imagen_tipos_CMS.png)

## Ejemplos de CMS

Algunos ejemplos de CMS son:

- **WordPress:** creación de blogs y páginas web.
- **Joomla:** gestión de sitios web y portales.
- **Shopify:** creación y administración de tiendas en línea.
- **Wix:** creación de páginas web mediante herramientas visuales.
- **Squarespace:** creación de sitios web y tiendas en línea.

## Top 5 de CMS y estadísticas de mercado

Para comparar la popularidad de los CMS es importante utilizar una fuente estadística que indique qué se está midiendo y cuándo se han recogido los datos.

Una fuente de referencia es [W3Techs — Usage statistics of content management systems](https://w3techs.com/technologies/overview/content_management). Este sitio publica estadísticas sobre el uso de tecnologías web, incluidos los sistemas de gestión de contenidos.

El ranking debe elaborarse a partir de los datos publicados por la fuente en la fecha de consulta. No se deben mezclar porcentajes de distintas fuentes ni presentar datos sin indicar su periodo de referencia.

| Posición | CMS | Uso principal | Dato de mercado |
|---|---|---|---|
| 1 | WordPress | Sitios web, blogs y portales | Consultar el porcentaje publicado por W3Techs en la fecha de consulta. |
| 2 | Shopify | Comercio electrónico | Consultar el porcentaje publicado por W3Techs en la fecha de consulta. |
| 3 | Wix | Creación de páginas web | Consultar el porcentaje publicado por W3Techs en la fecha de consulta. |
| 4 | Squarespace | Sitios web y tiendas en línea | Consultar el porcentaje publicado por W3Techs en la fecha de consulta. |
| 5 | Joomla | Sitios web y portales | Consultar el porcentaje publicado por W3Techs en la fecha de consulta. |

**Fuente:** [W3Techs, estadísticas de uso de CMS](https://w3techs.com/technologies/overview/content_management).

**Fecha de consulta:** [añadir la fecha en la que se comprueben los datos].

**Interpretación:** el ranking y los porcentajes deben reflejar los datos de la fuente en la fecha indicada. La cuota de uso de un CMS entre todos los sitios web no equivale a su cuota entre los sitios que utilizan exclusivamente un CMS.

## Comparación entre CMS dinámico y generador de sitios estáticos

| Aspecto | CMS dinámico | Generador de sitios estáticos (SSG) |
|---|---|---|
| Forma de crear contenidos | Se crean y editan mediante un panel de control. | Se crean mediante archivos, contenido y plantillas. |
| Base de datos | Es habitual que utilice una base de datos. | No necesita una base de datos en tiempo de ejecución para servir las páginas estáticas. |
| Generación del HTML | Normalmente se genera cuando se solicita una página. | Se genera durante el proceso de compilación. |
| Servidor necesario | Puede requerir un servidor que ejecute la aplicación y una base de datos. | Puede publicarse mediante un servidor web sencillo o una CDN. |
| Panel de administración | Es habitual que incluya uno. | No suele incluir uno de forma predeterminada. |
| Conocimientos técnicos | El panel facilita la gestión del contenido. | Puede requerir conocimientos de archivos, plantillas y herramientas de compilación. |
| Seguridad | La aplicación, sus complementos y la base de datos requieren mantenimiento y protección. | Servir páginas estáticas reduce la superficie de ataque del servidor de publicación, aunque el proceso de construcción y otros servicios también deben protegerse. |
| Rendimiento | Depende de la aplicación, la caché y el servidor. | Puede ofrecer un rendimiento elevado porque sirve archivos ya generados. |
| Actualización del contenido | Normalmente se actualiza desde el panel y la aplicación publica los cambios. | Hay que volver a generar y desplegar el sitio cuando cambia el contenido. |
| Publicación | Se despliega la aplicación y su infraestructura. | Se despliegan los archivos resultantes de la compilación. |
| Ejemplos | WordPress y Joomla. | Hugo, Jekyll y Eleventy. |

## Conclusión

Los CMS permiten gestionar contenidos de forma cómoda, especialmente cuando se necesita actualizar una web con frecuencia o cuando varias personas participan en su mantenimiento. Los generadores de sitios estáticos, por su parte, permiten generar páginas que se pueden servir con una infraestructura sencilla.

La elección depende del tipo de proyecto, de la frecuencia de actualización, de las necesidades de administración y de los conocimientos técnicos disponibles.

## Vídeo sobre CMS

[Ver vídeo sobre CMS](https://www.youtube.com/watch?v=sSh5AAmItN0)

---

[Ir al documento sobre SSG](ssg.md)
