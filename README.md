# P I P O

La aplicación web puede ser definida como una *enciclopedia de creadores de contenido* cuyo propósito es ayudar a los usuarios a modificar y elegir, en la medida de lo posible, su experiencia
dentro de las redes sociales, es decir, la idea base de este proyecto es facilitar a los usuarios la búsqueda de nuevos perfiles para poder acercarse a ese contenido sin necesitar que el
algoritmo te publicite dichas temáticas. Por ello, la información que debe contener la página son breves descripciones de las temáticas, imágenes de dicha temática y los correspondientes 
enlaces a los distintos perfiles que suben contenido sobre esa temática en concreto.

> Ejemplo: Para la temática *videojuegos* encontraríamos las subcategorias 'ESports', 'Gameplay', 'Streamers', 'Novedades', etc., así como una descripción de la temática. En todas las subcategorías encontraríamos una imagen que refleja el contenido con su descripción breve y, por supuestos, los enlaces de los creadores de contenido que pertenecen a esa subcategoría.

<br></br>
## REQUISITOS
### Funcionales:

1. Registrarse en la página creando una cuenta para poder seguir las categorías y/o subcategorías de tu interés.
2. Iniciar sesión en tu cuenta.
3. Buscar categorías en el navegador de la página de Inicio.
4. Explorar todas las categorías existentes en la página Categorías.
5. Encontrar subcategorías dentro de las categorías para especificar más el contenido que estas buscando.
6. Buscar creadores de contenido por su nombre en el navegador y/o en la página Creadores.
7. Comentar en los foros correspondientes de las categorías o subcategorías.
8. Crear tus propias Comunidades añadiendo las categorías o subcategorías que consideres bajo el nombre, imagen y descripción que eligas.
9. ¡Encontrar los enlaces necesarios para poder comenzar a seguir y disfrutar del contenido que te interesa!
<br></br>  
### No funcionales:

1. Compatibilidad con distintos tamaños de dispositivo, implementando un diseño *responsive*.
2. Soporte en diferentes navegadores.
3. Implementar un tema o modo 'oscuro' y 'claro' para mejorar la experiencia del usuario.
4. Mantener una buena legibilidad del contenido.
5. Diseñar un flujo o recorrido por la página que sea lógico, coherente y accesible.
6. Presentar el contenido de forma clara y evidente, manteniendo la accesibilidad de la página.
7. Elegir aspectos estéticos que favorezcan a una mejor experiencia de usuario, sin interferir en la accesibilidad del contenido.

<br></br>
## TECNOLOGÍAS EMPLEADAS

````
Entre las tecnologías empleadas destacan los lenguajes de marcas, los cuales son sistemas que utilizan
etiquetas para estructurar, organizar o describir contenido dentro de los documentos; es decir, dichas
etiquetas o marcas proporcionan instrucciones sobre cómo se presenta la información dentro de la página.
Una vez que hemos definido el contenido y estructura que quermeos mostrar en la página, el siguiente
paso es elegir las etiquetas que nos permiten llevar a cabo dicha estructura. No se trata sólo de ordenar
los contenidos, sino de dotar la página de personalidad, dinamismo y funcionalidad.
````
### HTML
HTML es el lenguaje de marca más extendido para la estructuración de contenido web por su amplio soporte en navegadores, siendo uno de los requisitos no funcionales detallados en el principio del documento, y su fácil aprendizaje. En este caso, estoy empleando la versión HTML5 por las siguientes ventajas:

 - Presenta una `semántica mejorada` con respecto a versiones anteriores: contiene nuevas etiquetas que mejoran la estructura
y significado al contenido, siendo importante para la estructuración del contenido de una página. Me ha permitido encontrar una gran variedad de etquetas que se adaptaban a las necesidades del diseño que he elegido realizar.
  - `Multimedia integrada`: podemos implementar audios y videos sin necesidad de plugins externos, nos ayuda a integrar una mayor variedad de contenido en nuestra página.
  - `Gráficos` y `efectos visuales` para dotar de más 'vida' o una sensación más dinámica a la página.
  - `Formularios` mejorados con nuevos tipos de entradas y validaciones.
  - `APIs` y `funcionalidades avanzadas` como geolocalización, almacenamiento local entre otros.

 
### CSS
Entre las desventajas del lenguaje HTML se encuentra la dependencia del empleo de CSS para la presentación de los 
contenidos, por ello he usado este lenguaje en su versión CSS3. La elección de esta versión se basa en las siguientes ventajas:

  - `Modularidad`: esta versión de CSS se divide en módulos facilitando su uso y comprensión.
  - `Nuevas propiedades`: que permiten efectos visuales avanzados como animaciones, lo cual es algo positivo para dotar de dinamismo a la página.
  - `Responsive Design`: facilita la creación de sitios web que se adaptan a diferentes tamaños de pantalla.
  - Mejoras en el `diseño`: contiene nuevas herramientras como *Flexbox* y *Grid Layout* para layouts más complejos y flexibles.
    
### MARKDOWN
Es un lenguaje de marca ligero, de fácil uso y comprensión. Este lenguaje lo he empleado para la documentación del proyecto ya que, apesar de no contar con una estructuración muy compleja,
sí me permite ordenar, colocar y remarcar las diferentes partes del documento, mejorando la legibilidad de este, así como el acceso a los contenidos.

<br></br>
````
Entornos de desarrollo son aplicacionies informáticas que permiten la creación, edición y ejecución de códigos a través
de diferentes lenguajes de codificación.
````
### WEBSTORM
Es un IDEs que ofrece amplias prestaciones para lenguajes como HTML y CSS. La elección de este entorno se ha debido a dos ventajas:

- Trabajar con un IDE que no conocía, para poder adquirir más experiencia con distintas tecnologías.
- Al ser un entorno diseñado para los lenguajes que voy a emplear en este proyecto, no necesito instalar plugins ni herramientas externas para trabajar. Además, WebStorm incluye una herramienta que me permite realizar una 'validación' del código. Esto último no me exime de
 realizar esta prueba, pero supone una ayuda a la hora de escribir el código y tener una cierta orientación. 


