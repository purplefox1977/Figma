<h1>Figma del proyecto actualizado </h1>

![pantallaSobreMi](https://github.com/user-attachments/assets/e07a7f14-4f12-4f9a-8969-cbd112291244)

![pantallaInicial](https://github.com/user-attachments/assets/e3a839fa-fe91-4734-a2ee-ac80071a5734)

<p>nuestro proyecto de portafolio ha sido actualizado en Figma. 
</p>
<h3>El diseñador nos dio un nuevo diseño con cambios importantes:</h3>
<ol>
<li>Botones reubicados: Los botones ahora tienen una posición diferente.</li>
<li>Pie de página: Ahora tenemos un pie de página completo, no solo las etiquetas.</li>
<li>Encabezado: Se agregó un encabezado con dos enlaces: "Inicio" y "Sobre mí".</li>
<li>Página "Sobre mí": Se agregó una nueva página con una descripción de quiénes somos.</li>
<li>Lorem Ipsum: Se utilizó un texto de marcador de posición llamado "Lorem Ipsum" para ocupar el espacio del texto que se colocará más adelante.</li>
</ol>

<h1> Posicionando los enlaces</h1>

<p> Algunos pasos que tenemos que teneren cuanta al posicionar los botones</p>
<ol type="I">

<li>Revisa el código: Asegúrate de que la propiedad Flex Direction esté configurada como Column en el contenedor de tus botones. Esto hará que los botones se apilen verticalmente</li>
<li>Verifica el centrado: La propiedad Align Items debe estar configurada como center para que los botones se centren verticalmente dentro del contenedor. </li>
<li>Observa el espacio: La propiedad Gap debe tener un valor que coincida con el espacio que deseas entre los botones. Puedes usar px o em para definir el espacio.</li>
<li>Prueba en el navegador: Abre tu página web en un navegador y observa el resultado. Los botones deben estar alineados verticalmente, centrados y con el espacio deseado entre ellos.</li>
</ol>

<ol type="A">
<li>Posicionamos los botones de forma vertical utilizando la propiedad Flex Direction en CSS </li>
<li>También vimos cómo centrar los botones verticalmente con la propiedad Align Items. </li>
<li>Finalmente, aprendimos a crear espacio entre los botones utilizando la propiedad Gap.</li>
</ol>

![container](https://github.com/user-attachments/assets/7726b597-0d55-4512-85f9-2b72632588cb)

https://www.w3schools.com/css/css_border.asp
 
 <h1> Estilizando los enlaces</h1>

<p> Estilizamos los enlaces de nuestro proyecto web usando CSS llamado border para añadir el borde alrededor de los botones. Esta propiedad se utiliza para definir los valores de ancho del borde, estilo del borde y color del borde.
</p>
<ol type="I">
<li>Empezamos por ajustar el estilo del subtítulo, usando las propiedades fontfamily, fontsize y fontweight.</li>
<li> Quitamos el color de fondo de los enlaces y cambiamos el color del texto a un gris claro.</li>
<li>Agregamos un borde a los enlaces usando la propiedad border, especificando el tamaño, el estilo (Solid) y el color. </li>
<li>Exploramos otros estilos de borde, como Dotted, en la documentación de CSS.</li>
<li>Finalmente, ajustamos el ancho de los enlaces y el redondeo de las esquinas para que coincidan con el diseño de Figma.</li>
</ol>

https://www.w3schools.com/css/css_border.asp

<h3>Lo que hecho</h3>
<p>
Funciona la actualización del diseño de un proyecto en Figma;
Posicionar los botones según el nuevo diseño mediante display: flex;
Realiza la estilización de los botones según el nuevo diseño.</p>

<h1>Iconos de las redes sociales</h1>


<p>Aregar iconos a nuestros botones utilizando imágenes.</p>
<ol>
<li>Primero, creamos una carpeta llamada Assets para guardar todas nuestras imágenes. Luego, colocamos las imágenes de los iconos dentro de esta carpeta.</li>

<li>Para agregar un icono a un botón, usamos la etiqueta <img> y la propiedad src para indicar la ruta de la imagen.</li>
</ol>
<p>La ruta de la imagen se compone de la carpeta Assets, el nombre del archivo de la imagen y la extensión del archivo (por ejemplo, .png).</p>

 ![img](https://github.com/user-attachments/assets/625cc238-5d9f-4aba-802b-9ad6725d752a)

 <h1>Posicionando los iconos</h1>

 <p>Convertimos los enlaces en contenedores al colocar la etiqueta IMG dentro de ellos.</p>

 <ol>

 <li>Usando la clase Link y la propiedad display: flex, alineamos los botones en una sola línea.</li>

<li>Para centrar el contenido dentro de los botones, utilizamos la propiedad justifycontent: center.</li>
<li>Finalmente, agregamos un espacio entre los iconos y las palabras usando un padding de 10px en la clase Link..</li>
</ol>

<h1>Hover(cambia decolor al ponerse el cursor)</h1>

![hover](https://github.com/user-attachments/assets/d3800f2f-bb33-4041-bc9f-a0b5f0ea97b0)

https://www.w3schools.com/cssref/sel_hover.php

<p> Los botones que cambian de color cuando el cursor se coloca sobre ellos. Esto se logra utilizando la propiedad hover en CSS.</p>
<ol type='A'>
<li>Primero, vimos un ejemplo de cómo aplicar hover a una etiqueta.</li>
<li>Luego, aprendimos a aplicarlo a una clase, lo que nos permite cambiar el color de fondo de un botón cuando el cursor está sobre él.</li>
 </ol>

![figmaBotones](https://github.com/user-attachments/assets/abbc142e-e506-48e6-9b50-88a68ed82e48)

 <h1>Desarrollando el footer</h1>

 <p>Creamos un footer para nuestra página web. </p>
 
 <ol>

<li>Primero, agregamos una etiqueta <-footer> a nuestro HTML y dentro de ella, un párrafo <-p> con el texto "Desarrollo por Alura Latente".</li>
    <li>Luego, creamos una clase llamada "footer" para la etiqueta <-footer> y le aplicamos un color de fondo y un padding.</li>
    <li> Para centrar el texto del footer y cambiar su color y fuente, usamos las propiedades CSS textalign, color y fontfamily, fontsize y fontweight.</li>
    <li>Finalmente, quitamos la propiedad height: 100vh del body para que el footer se mostrara correctamente. </li>
 </ol>
  

   <h1>Desarrollando el header</h1>

 <p>crear el header (encabezado) de nuestra página web. Para ello, utilizamos la etiqueta nav para la navegación y la etiqueta a para crear los enlaces "Home" y "Sobre mí". </p>
 <ol>

<li> Tienes una etiqueta <-header> en tu archivo HTML.</li>
<li>Dentro de la etiqueta <-header>, tienes una etiqueta <-nav> para la navegación.</li>
<li>Dentro de la etiqueta <-nav>, tienes dos etiquetas <-a> para los enlaces "Home" y "Sobre mí".</li>
<li>Cada etiqueta <-a> tiene el atributo href con el enlace correspondiente.</li>

<li>Las etiquetas <-header>, <-nav> y <-a> tienen las clases correctas: </li>
<li>header para la etiqueta <-header></li>
<li>header_menu para la etiqueta <-nav></li>
<li>header__menu__link para las etiquetas <-a></li>
 </ol>
 <h1> Repaso general</h1>
 
 <ol>
 <li> - Personalizando el pie de página de tu sitio web

Imagina que estás desarrollando un sitio web y ha llegado el momento de personalizar el pie de página. El desafío es crear un pie de página estilizado con las siguientes características: debe tener un fondo azul claro (#22D4FD), texto en negro (#000000), y el texto debe estar centrado y utilizar la fuente 'Montserrat', tamaño 24px y peso 400. Además, el pie de página debe tener un padding de 24px. Utiliza el HTML y CSS proporcionados como base y aplica las modificaciones necesarias.</li>

<li> - Ajustando el espaciado interno de la presentación

Te han encargado ajustar el diseño de una sección de presentación en un sitio web. Actualmente, los elementos están demasiado cerca de los bordes, lo que afecta la estética del sitio. Tu tarea es reemplazar la propiedad margin por padding en la clase .presentación del CSS, probando valores de porcentaje para encontrar el espaciado ideal. Comienza con un 5% y ajusta según sea necesario para obtener un aspecto equilibrado.</li>

<li> - Eliminando el height para adaptar el diseño

Tu sitio web está experimentando un problema de diseño: la propiedad height: 100vh en el body está impidiendo que el contenido se ajuste correctamente en la pantalla, especialmente con la adición de nuevos elementos como un pie de página. Tu misión es comentar la línea que define height: 100vh en el CSS y verificar el impacto de este cambio en el diseño del sitio. Observa cómo el contenido y el pie de página se adaptan a la nueva configuración.</li>

<li> - Estilizando el encabezado con CSS

Estás creando un sitio web y ha llegado el momento de estilizar el encabezado para que sea visible y atractivo, similar al proyecto en Figma. Necesitas agregar estilo al encabezado en el archivo style.css, de modo que los enlaces "Home" y "Sobre mí" estén alineados horizontalmente y tengan un aspecto moderno. Considera usar propiedades como font-size, color, margin, padding y display. Intenta también agregar un hover para cambiar el color de los enlaces cuando el ratón pase sobre ellos.</li>

<li> - Ajustando el espaciado interno de los enlaces

Basándonos en el estilo actual del encabezado, parece que los enlaces pueden estar muy cerca uno del otro o del borde del encabezado, lo que puede afectar la legibilidad y la estética del sitio. Tu tarea es ajustar el espaciado interno (padding) de los enlaces "Home" y "Sobre mí" para asegurarte de que tengan un espaciado adecuado alrededor del texto. Esto hará que el encabezado sea más atractivo y fácil de usar.</li>

</ol>

<h1>Estilizando el encabezado</h1>

https://www.w3schools.com/css/css_padding.asp

<p>estilizar el encabezado de nuestra página web.  </p>
 <ol>

<li>Primero, organizamos el código CSS para que coincida con el orden del HTML.</li>
<li>Luego, creamos las clases CSS para el encabezado, el menú y los enlaces.</li>
<li>Cambiamos la fuente, el tamaño y el peso de la fuente de los enlaces. </li>
    <li>También agregamos un color a los enlaces y un espacio entre el contenido y el borde del encabezado.</li>
    <li>Utilizamos la propiedad padding para crear espacio dentro del encabezado y la propiedad gap de flexbox para crear espacio entre los enlaces. </li>
    <li>Finalmente, ajustamos el espacio entre el encabezado y el contenido principal utilizando la propiedad padding en la clase de presentación.</li>
 </ol>

