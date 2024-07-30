<h1>Media queries o query</h1>
<h2>Diseño responsivo</h2>
<p>Por ejempo esta propiedad hace que, cuando la pestaña este en una determinada medida la imagen cambie de lugar.</p>

![media](https://github.com/user-attachments/assets/2a83c258-a865-4bc7-b127-80e9c00b3e91)


https://developer.mozilla.org/es/docs/Web/CSS/CSS_media_queries/Using_media_queries

https://www.w3schools.com/css/css_rwd_mediaqueries.asp

<p>Cuando nuestra pantalla tenga de maximo de 1200px tenga un detrminado comportamiento, que cambie para el modo Mobile que se creo en figma.En nuestro trabjo tenemos un Display-flex,y en nuestra estructura hay 2 elementos, no definimos un Flex-direction entonces por defecto  este flex -direction es una linea.Es por eso que la imagen y lostextos estan uno alado del otro </p>

![media2](https://github.com/user-attachments/assets/ddb6d3a7-bf8d-4b92-8c14-0b99fe670e14)


<p>Las Media Queries, una herramienta fundamental para crear diseños web responsivos.</p>

![responsi](https://github.com/user-attachments/assets/c85e3ed1-48ef-4c86-9413-3bf0f68a4756)

<ol type="A">
<li>Las Media Queries nos permiten aplicar estilos específicos a nuestro sitio web dependiendo del tamaño de la pantalla del usuario. En este caso, vimos cómo usarlas para cambiar la disposición de los elementos en una página web cuando la pantalla tiene un ancho máximo de 1200 píxeles.</li>

<li>Para lograr esto, usamos la propiedad @media y dentro de ella, especificamos el tamaño máximo de pantalla con maxwidth: 1200px. Luego, dentro de las llaves, definimos los estilos que queremos aplicar a nuestro diseño.</li>

<li>En el ejemplo, cambiamos la propiedad flexdirection de la clase .presentación a columnreverse para que la imagen se mostrara en la parte superior de la columna, en lugar de la inferior.</li>
</ol>

<p>Recuerda que es importante probar tus diseños en diferentes tamaños de pantalla para asegurarte de que se vean correctamente en todos los dispositivos.</p>

<ol >

<li>Prueba en diferentes dispositivos: Abre tu proyecto web en diferentes navegadores y ajusta el tamaño de la ventana para simular diferentes dispositivos. Observa si el diseño se adapta correctamente a cada tamaño de pantalla.</li>

<li>Utiliza las herramientas de desarrollo: En tu navegador, abre las herramientas de desarrollo (generalmente presionando F12). En la pestaña "Elementos" puedes ver el código HTML y CSS de tu página. Busca la sección de @media y verifica que los estilos se apliquen correctamente a los elementos que quieres modificar.</li>

<li>Compara con el diseño original: Revisa el diseño original en Figma o la herramienta que estés utilizando. Asegúrate de que el diseño responsivo que has creado se ajusta a las especificaciones del diseño original.</li>
</ol>

<p>Recuerda que la práctica es fundamental para dominar los conceptos de responsividad. </p>

<h1>Encabezado responsivo</h1>

<p>Mirando nuestro diseño lo siguiente a ajustar es nuestro heder, colocando un espacio en la parte superior y tambien centralizarlo . Miramos como esta la clase heder en nuestro destok. </p>
<p>Verificamos las medidas de nuestro heder y vamos a @media, a agregar un heder con los cambio deseados, para obtener el espasio del padding. </p>
<p>Para centrar el heder utilizamos la clase heder_menu, esta clase ya tiene un display:flex ya que la clase lo tiene no nesecitamos agregarlo en la vercion del querie,vamos a media y ahi agregamos las modificaciones</p>
<ol type='I'>

<li>Primero, ajustamos el padding del encabezado en la versión de escritorio, reduciéndolo a un 10% en todos los lados.</li>

<li>Luego, creamos una media query para ajustar el padding del encabezado en dispositivos más pequeños.</li>

<li>Para centrar el encabezado horizontalmente, utilizamos la clase header menu que ya tenía un display flex y le agregamos la propiedad justify content: center</li>
</ol>

<ol >
<li>¿Has ajustado el padding del encabezado en la versión de escritorio? Asegúrate de que el padding sea del 10% en todos los lados.</li>

<li>¿Has creado una media query para ajustar el padding del encabezado en dispositivos más pequeños? La media query debe estar ubicada encima de la presentación y debe aplicar un padding del 10% al encabezado.</li>

<li>¿Has utilizado la clase header menu para centrar el encabezado horizontalmente? Asegúrate de que la clase header menu ya tenga un display flex y que le hayas agregado la propiedad justify content: center.</li>

</ol>