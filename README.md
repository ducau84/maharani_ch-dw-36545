# *<h2 align=center>**Maharani Indumentaria**</h2>*

## **Descripción del repositorio**:
*Repositorio del Proyecto **"Maharani Indumentaria"**, para el curso de Desarrollo Web, Comisión 36.545 de **Coder House**.*

## **Historial del Versiones**:

### Versión 1.70 ( 28/04/2022 )
- Creación de la pagina para mostrar en caso que se produzca el **"Error 404"**.

### Versión 1.65 ( 27/04/2022 )
- Corrección de tamaño de caja de texto en la sección ***Quienes Somos*** para que permita la visibilidad total del texto en vista ***mobile***, la cual se truncaba con el cambio de fuente introducido en la **Versión 1.60**.
- Cambio de propiedad de fondo para que cubra el total de la pantalla en tamaños mayores a la vista ***desktop*** (**>1400px**).
- Se agregó un borde inferior a la ***navbar***, espejando al utilizado en el ***footer***.
- Se implementaron animaciones para el despliegue del submenú ***Galeria*** y para el ***"Menú Hamburguesa"***.
- Se reemplazo el link vacío al hacer click en el logo, por un redireccionamiento al ***index.html***. .

### Versión 1.60 ( 26/04/2022 )
- Cambio de formato de archivos de la galería ***Camisetas de Polo*** de **PNG** a **JPG** como el resto de las galerías.
- Introducción de comentarios descriptivos dentro de cada archivo **HTML**.
- Cambio de fuentes en ***títulos*** y sección ***"¿Quiénes Somos?"***.
    - Creación del archivo partial en el subdirectorio **sass** ***_fonts.scss***, importando fuentes de **Google Fonts** con el comando ***@import***.
- Modificación del botón ***Adjuntar Archivos...*** del formulario ***Presupuesto*** cambio de clase ***button*** a ***input type=file*** y dandole estilo para que coincida con el resto de los botones del sitio.
- Correcciónes del formulario de ***Contacto***.

### Versión 1.50 ( 22/04/2022 )
- Optimización del tamaño de las imágenes desde el sitio ***"Optimizilla"*** ( https://imagecompressor.com/es/ ).
- Introducción de función ***mixin*** en archivo ***_mixins.scss*** (utilización del mismo en botones de formularios de *Contacto* y *Presupuesto*).
- Introducción de Mapas y la función each en el archivo ***_maps.scss***:
    - Utilización de ***@each*** en la propiedad hover de los íconos de redes sociales y de WhatsApp del footer.
    - Definir el mapa ***$colores_fondo*** y posterior utilización de la función ***map-get*** para los fondos de *Quienes Somos*, *Presupuesto* y *Contacto*.
- Modificación del footer:
    - Colores de íconos de redes sociales ( al hacer ***hover*** sobre los mismos ).
    - Se introdujeron los datos postales debajo del texto de Copyright.
- Introducción del tamaño ***mobilexs*** en las media queries, necesario para acomodar la sección Presupuesto en vista mobile en ciertos dispositivos.
- Aplicacion de SEO:
    - Introducción de etiquetas ***meta*** ( ***description*** y ***keywords*** ), dentro de la sección ***header***, específicas para cada archivo html, basadas en su contenido.
    - Verificación de sitio en **Google** y posterior introducción de la etiqueta generada en la sección ***header***.
    - Archivo ***sitemap.xml*** agregado al raiz del sitio, el mismo fue generado desde **"XML-Sitemaps.com"** ( https://www.xml-sitemaps.com/ ). 

### Versión 1.21 ( 18/04/2022 )
- Depuración de código mediante la extensión de Visual Studio Code **"W3C Web Validator"** (https://marketplace.visualstudio.com/items?itemName=CelianRiboulet.webvalidator).
    - Se aplicaron las correcciones necesarias a cada archivo.

### Versión 1.20 ( 17/04/2022 )
- Unificación de la rama ***aplico_bootstrap*** con la rama principal (***main***).
- Aplación de SASS.
    - Creación del subdirectorio ***sass*** dentro de la carpeta RAIZ.
    - *Traducción* del archivo ***style.css*** original a los distintos archivos **SCSS**, generando un archivo de variables y un archivo SCSS por sección.
    - Compilado automático de los archivos SCSS por parte del **Visual Studio Code**, mediante la extensión **"Live SASS Compiler"** ( https://marketplace.visualstudio.com/items?itemName=ritwickdey.live-sass).

### Versión 1.12 ( 16/04/2022 )
- Corrección de valores de ***overflow*** que no permitian el scroll vertical en vista "***mobile*** apaisado" y ***"tablet"***.
- Ajuste de tamaño de fuentes en footer para vistas "***mobile*** apaisado" y ***"tablet"***.
- Corrección de etiqueta de clase en botón "enviar" del formulario de contacto. 

### Versión 1.11 ( 15/04/2022 )
- Ajuste de animaciones en transcisiones de página, efecto ***hover*** en imágenes del ***footer***.
- Ajuste de tamaño de los contendores de imágen de las galerias en desktop a un ancho máximo del 75% ( 325 px ).
- Corrección de error en formulario de contacto con el link para enviar mensajes por WhatsApp.

### Versión 1.10 ( 14/04/2022 )
- Creación de la Rama ***"aplico_bootstrap"***.
- Reemplazo de la barra de navegación previa, por una de BS, ajustando su estilo al propio del sitio.
- Reemplazo del ***slider*** previo, por un ***carousel*** de BS, ajustando estilo transiciones y texto overlay para que se condiga con el sitio.
- Reemplazo del Layout por ***Grid System*** de BS en todas las secciones menos las Galerias, donde se mantiene ***GRID***.
- Introducción de animaciones a todos los títulos, transcisiones entre páginas, y secciones del ***index***.
- Se cambio completamente el ***footer***, incluyendo ahora datos de Redes sociales, formas de pago, envío y teléfono de contacto ( los ultimos 3 se ocultan en la versión "***mobile***").
- Ajustes en la sintaxis del archivo ***style.css*** para permitir mejor lectura del mismo.
- Reemplazo de fondos de imágenes **PNG** a archivos **SVG** generados desde **"SVG Backgrounds"** ( https://www.svgbackgrounds.com/ ).

### Versión 1.02 ( 10/04/2022 )
- Unificación de la rama "***animaciones_test***" con la rama "***main***".

### Versión 1.01 ( 10/04/2022 )
- Creación de la Rama "***animaciones_test***"
- Introducción de animaciones y transiciones en menúes desplegables.
- Introducción de animaciones, usando la libreria **AOS** ( https://michalsnik.github.io/aos/ ).

### Versión 1.00 ( 10/04/2022 )
- Sitio migrado a repositorio local en **GIT**, para la posterior carga a **GitHub**.
- Creación de este archivo **README**.
