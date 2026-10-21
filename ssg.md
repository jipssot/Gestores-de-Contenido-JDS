> # Generadores de sitios web estáticos #

Los generadores de sitios estáticos (SSG) son herramientas especializadas que optimizan el proceso de creación de sitios web estáticos; son es­tru­c­tu­ras pre­de­fi­ni­das de código sobre las que se pueden crear páginas. Los generadores de páginas estáticas crean los archivos HTML de una página a partir de un script basado en datos de entrada, que están almacenados en un sistema de archivos. Estos generadores permiten crear sitios web rápidos, seguros y fáciles sin necesidad de consultar una base de datos o ejecutar código en el servidor en cada petición. 

Como punto de partida los generadores utilizan contenido en formato ligero como Markdown, plantillas de diseño y archivos de estilo y scripts. 

-------------------------------------

### Para saber más sobre SSG: ###

[Generadores de sitios estáticos | ¿Qué son?](https://www.youtube.com/watch?v=3INXQ_4W42g)

-------------------------------------

## Tabla comparativa **Jekyll, Hugo y Astro** ##

| Aspecto que investigar | Jekyll | Hugo | Astro |
| ---- | ---- | ---- | ---- |
| Tecnología o lenguaje principal | Ruby | Go (Golang) | JavaScript/TypeScript |
| Formato utilizado para el contenido | Markdown, HTML, YAML | Markdown, HTML, YAML/TOML  | Markdown, MDX, HTML|
| Funcionamiento básico | Lee archivos Markdown y plantillas Liquid, los procesa con el motor de Ruby y genera páginas HTML estáticas en una carpeta de salida| Lee los archivos de contenido y plantillas Go HTML, los procesa a velocidad rápida mediante su ejecutable y genera el sitio estático en la carpeta /public | Astro elimina todo el JavaScript innecesario del cliente al compilar, y utiliza una arquitectura que permite aislar los elementos interactivos de una página (Islands Architecture). Convierte los componentes en HTML y CSS puro antes de enviarlos. |
| Usos habituales | Páginas personales, blogs clásicos, proyectos pequeños. | Proyectos grandes o complejos, blogs con miles de páginas, portafolios y web corporativas. | Páginas corporativas y de aterrizaje, blogs peronales y profesionales, portafolios en línea, ecommerce, sitios de documentación. | 
| Ventajas | Este sistema ofrece una alta seguridad y excelente velocidad al utilizar únicamente archivos estáticos, reduciendo las vulnerabilidades y los tiempos de carga. Además, permite alojar y desplegar el sitio gratuitamente mediante GitHub Pages, sin necesidad de mantener infraestructura, bases de datos ni aplicar parches de seguridad. Por último, facilita la gestión del contenido gracias al uso de Markdown, haciendo que la creación y edición de páginas sea sencilla. | Este sistema destaca por su gran velocidad, ya que permite compilar miles de páginas en muy poco tiempo, y por su alta seguridad al no depender de bases de datos ni plugins vulnerables. Además, facilita la creación y edición de contenido mediante archivos de texto en Markdown y ofrece un proceso de instalación sencillo. | Este sistema ofrece una gran velocidad y seguridad al generar páginas estáticas sin depender de servidores, bases de datos ni JavaScript innecesario. Además, permite un hosting gratuito o económico, favorece un excelente posicionamiento SEO gracias a su contenido en texto plano y utiliza una arquitectura de islas que permite añadir componentes interactivos de React, Vue o Svelte únicamente cuando son necesarios. | 
| Desventajas | Este sistema puede presentar dificultades en sitios web muy grandes, ya que los tiempos de compilación pueden aumentar considerablemente. Además, requiere ciertos conocimientos técnicos de terminal, Markdown y Ruby, y no dispone de un panel de administración visual, por lo que el contenido se gestiona mediante archivos locales. Por último, tiene limitaciones para crear sitios dinámicos con contenido en tiempo real, usuarios registrados o comentarios sin utilizar servicios externos. | Este sistema presenta algunas limitaciones, como la falta de dinamismo nativo para sitios que necesitan actualizar datos en tiempo real, por ejemplo, chats o grandes tiendas online. Además, su sistema de plantillas y configuración puede tener una curva de aprendizaje inicial, y cualquier cambio en el contenido requiere recompilar y volver a subir el sitio estático. | Este sistema puede presentar tiempos de compilación largos en sitios con miles de páginas, ya que cada cambio requiere reconstruir todo el sitio. Además, no está pensado para aplicaciones con contenido dinámico complejo o datos que cambian constantemente sin utilizar soluciones híbridas como SSR. Por último, no dispone de un panel visual nativo, por lo que la edición de contenido requiere modificar el código o integrar un CMS headless. |


























