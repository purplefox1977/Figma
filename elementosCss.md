<h1> Box Model</h1>
<p>El box model, que es un patrón que define cómo se estructura un elemento HTML. El box model tiene cuatro partes:</p>
<ol>
<li>Contenido: El texto o imagen que se muestra dentro del elemento.</li>
<li>Padding: El espacio entre el contenido y el borde del elemento.</li>
<li>Borde: La línea que rodea el elemento.</li>
<li>Margen: El espacio entre el borde del elemento y otros elementos.</li>
</ol>
<p>También aprendimos que los navegadores web tienen estilos predefinidos para los elementos HTML, lo que puede causar que los elementos se vean diferentes en diferentes navegadores. Para evitar esto, podemos usar un Reset CSS, que es un archivo que establece estilos universales para todos los elementos HTML.</p>


<h1>Height y box-sizing</h1>
<p> La propiedad height, cómo usarla para que nuestro body ocupe toda la pantalla. 
La propiedad boxsizing, cómo usarla para evitar que los elementos hijos salgan de los elementos padres.</p>

<h3>La propiedad boxsizing tiene dos valores:</h3>
 <p> contentbox y borderbox.  </p> 

<ol>
<li>El valor contentbox es el valor predeterminado, y significa que el tamaño del elemento se calcula sumando el width, el padding y el border.</li>
<li>El valor borderbox significa que el tamaño del elemento se calcula sumando el width, el padding y el border, pero el padding y el border se incluyen dentro del tamaño del elemento.</li>
</ol>

<p>Para evitar que los elementos hijos salgan de los elementos padres, podemos usar el valor borderbox para la propiedad boxsizing. Esto significa que el padding y el border se incluirán dentro del tamaño del elemento, y el elemento hijo no saldrá del elemento padre.</p>

<a href="https://www.w3schools.com/css/css3_box-sizing.asp"></a>
<a href ="https://developer.mozilla.org/en-US/docs/Web/CSS/box-sizing"></a>

<h3>En el content-box sale el elmento hijo del elemento padre</h3>
<h3>En el border-box donde el elmento hijo no sale del elemento padre</h3>

<h1>Flexbox (posicionar elementos en la pantalla)</h1>

<p>Flexbox es una herramienta poderosa para posicionar elementos en HTML y CSS.

</p>

<ol type="I">
<li>Primero, identificamos nuestro contenedor, que es el elemento padre que contiene los elementos que queremos posicionar. Luego, aplicamos la propiedad display: flex al contenedor para activar Flexbox.</li>
<li>Después, exploramos la propiedad flexdirection, que controla la dirección en la que se colocan los elementos. Por defecto, es row, lo que significa que los elementos se colocan en una fila horizontal. Podemos cambiarlo a column para colocarlos en una columna vertical.</li>
<li>Finalmente, aprendimos sobre la propiedad alignitems, que nos permite alinear los elementos dentro del contenedor. La opción center centra los elementos verticalmente.</li>
</ol>

<a href="https://css-tricks.com/snippets/css/a-guide-to-flexbox/"></a>


<h1>Alineando el contenido</h1>

<p>
controlar el espacio alrededor de nuestros elementos HTML usando la propiedad margin en CSS.
</p>

<ol type="I">
<li> cómo usar la propiedad justifyContent con el valor spaceBetween para crear espacio entre elementos dentro de un contenedor Flexbox</li>

</ol>
<h1>Estilizando el texto</h1>
<p>Estilizar el texto en HTML y CSS.</p>   

<ol type="I">
<li> Primero, ajustamos el ancho de una sección usando la propiedad width en CSS.</li>
<li> Luego, modificamos el margen para mejorar el espacio entre los elementos.</li>
<li> Después, cambiamos el tamaño de la fuente del título y del párrafo usando la propiedad fontsize, tomando como referencia el diseño en Figma.</li>
</ol>


<h1>Importando las fuentes</h1>
<p>Importar fuentes de Google Fonts para usarlas en nuestro proyecto web. </p> 

<ol type="I">
<li>Primero, buscamos la fuente que queremos en Google Fonts y copiamos el código import que nos proporciona. </li>
<li>Luego, pegamos este código en nuestro archivo CSS para importar la fuente.</li>
<li>Finalmente, usamos la propiedad fontfamily en nuestro CSS para aplicar la fuente a los elementos HTML que queremos.</li>
</ol>

<a href="https://fonts.google.com/"></a>
<h1>Posicionando los botones</h1>

<ol type="A">
<li>Agrupar botones utilizando la etiqueta <-div>, que no es semántica, solo crea un agrupamiento. </li>
<li>También utilizamos la clase class para aplicar estilos a los botones.</li>
<li>Para separar los botones, usamos la propiedad justifycontent con el valor spacebetween dentro de un display flex.</li>
</ol>

<h1>Estilizando los botones</h1>
<p>Para estilizar botones en HTML y CSS.</p> 

<ol type="A">
<li>Primero, creamos una clase para cada botón en nuestro HTML. </li>
<li>Luego, en nuestro style.css, usamos la clase para aplicar estilos como ancho, color de fondo, alineación de texto, relleno (padding) y redondeo de bordes (borderradius).</li>
<li>También cambiamos la fuente, el tamaño de la fuente y el peso de la fuente para que coincida con el diseño de Fig.</li>
</ol>


<h1>El recurso Gap</h1>
<p>los espacios entre elementos en HTML y CSS usando Flexbox.
 Luego, exploramos la propiedad flexdirection para cambiar la orientación de los elementos en un contenedor Flexbox.</p>

<ol type="A">
<li>Primero, vimos cómo modificar el margen de un elemento para crear espacio alrededor de él. </li>
<li>Finalmente, aprendimos a utilizar la propiedad gap para crear un espacio uniforme entre los elementos dentro de un contenedor Flexbox..</li>
<li>Pasamos de una disposición en línea a una disposición en columna</li>
</ol>
