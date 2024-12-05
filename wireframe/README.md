# ESTRUCTURA BÁSICA DE HTML

> La estructura base de la página se divide en cabecera <header, cuerpo principal <main y pie de página <footer, siendo la división estándar para una web.
Para comentar y justificar el resto de etiquetas empleadas voy a apoyarme en los wireframe diseñados para el proyecto.

Comenzando con el header, lo he dividido entre un enlace, con título en su interior para volver al inicio al pulsar el nombre de la página, y un section como etiqueta global para agrupar tanto el navegador como el enlace con imagen que es el perfil del usuario.
Durante todo el proceso de elección he tenido en cuenta las posibilidades de edición que me permiten CSS, es decir, he elegido contenedores para poder distribuir y colocar los elementos en la página siguiendo el boceto creado. Dentro del navegador he empleado las
etiquetas de listas para ordenar los elementos, que en este caso son los enlaces que nos derivan a otras partes de la página.

En el main encontras, por un lado un formulario, que ha sido elegido por la función que va a tener al aplicarle (posteriormente) JavaScript, y un section, que recoge los distintos articles (etiqueta elegida para las partes independientes de la páginas). Dentro del formulario encontramos un fieldset que agrupa la leyenda y el input tipo texto que conforman la parte principal de la página de inicio. Encuanto a los articles empleados en el section, encontramos un enlace, que, a su vez, tienen una imagen y un título, y un párrafo.
  <details>
    
  <summary>Pulsa aquí para ver la imagen</summary>
  
![Inicio1](https://github.com/Lmrocio/Pipo/blob/main/wireframe/Captura%20de%20pantalla%202024-12-05%20112409.png)
</details>

Terminando con la página de inicio, tenemos el footer donde he empelado un section que agrupe los distintos títulos y enlaces sobre información de la página. He elegido esa etiqueta oprque tenía en mente añadir más secciones sobre información necesaria; no obstante, no he encontrado ideas para rellenarlo.

<details> <summary>Pulsa aquí para ver la imagen</summary>


![Inicio2](https://github.com/Lmrocio/Pipo/blob/main/wireframe/Captura%20de%20pantalla%202024-12-05%20112420.png?raw=true)
</details>


En la página para Iniciar sesión de usuario, podemos ver que la cabecera no contiene la misma estructura, sino que sólo presenta el enlace con el título de la página; esto se debe a que, por el objetivo de esta página, no vamos a navegar sino rellenar nuestros datos.
Para el main, y teniendo en cuenta cómo iba a implementar esta disposición con CSS, he dividido el espacio en dos etiquetas: un formulario, con sus correspondientes partes de button (con el cuál terminariamos el formulaio) e input con su label, y un enlace que nos deriva a
la página de registro. En cuanto al footer, se sigue la misma estructura ya mencionada.


<details><summary>Pulsa aquí para ver la imagen</summary>

  
![Iniciar sesión](https://github.com/Lmrocio/Pipo/blob/main/wireframe/Captura%20de%20pantalla%202024-12-05%20112435.png?raw=true)
</details>

Para la pa´gina de rgistro he empleado una disposición más compleja: primero he dividido el contenido en tres grandes grupos que se dispondrían en columna y, posteriormente, el último de estos contenedores lo he dividido en tres items que se dispondrían linealmente.
Encontramos primmero la etiqueta del título, seguido de la etiqueta button, con el que se finalizaría el formulario, y, por último, el formulario. Este último es dividido en tres fieldset que siguen la estructura de label e input, a excepción del último para el cual he 
empleado la etiqueta details y summary con la intención de implementar un desplegable que le proporcione dinamismo a la página.


<details><summary>Pulsa aquí para ver la imagen</summary>

  
![Registro](https://github.com/Lmrocio/Pipo/blob/main/wireframe/Captura%20de%20pantalla%202024-12-05%20112445.png?raw=true)
</details>
