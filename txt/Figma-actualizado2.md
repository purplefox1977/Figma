<h1>Navegando entre paginas</h1>

 <ol>

<li>Creamos una nueva página web llamada "about.html" y a vincularla a nuestra página principal "index.html"</li>
    <li>También aprendimos a organizar nuestros archivos CSS en una carpeta llamada "Style C" para mantener nuestro proyecto ordenado.</li>
    <li> Hicimos algunos ajustes al estilo de nuestra página, como cambiar el padding del header y eliminar la decoración de texto del menú.</li>
 </ol>

<h1>Desarrollando la nueva pagina</h1>

<p>Creamos una nueva página web, "Sobre mí", utilizando el código HTML y CSS.</p>

 <ol>

<li>Primero, copiamos las secciones del encabezado y pie de página de la página de inicio para mantener la consistencia en el diseño. Luego, creamos el contenido principal de la página "Sobre mí" con un título H1, dos párrafos y una imagen.</li>
    <li>Para aplicar el estilo a la nueva página, en lugar de crear una nueva hoja de estilo, reutilizamos las clases CSS de la página de inicio. Esto nos permitió mantener la coherencia visual entre las dos páginas.</li>
    <li>Al final, revisamos el resultado en el navegador y vimos cómo la página "Sobre mí" se estilizó correctamente.</li>
 </ol>




<h1>Creamos una nueva página web, "Sobre mí", utilizando el código HTML y CSS.</h1>

 <ol>

<li>Estilizando el encabezado con CSS de la página de acuerdo con las especificaciones proporcionadas. Utiliza el archivo style.css para aplicar las propiedades CSS en el encabezado.</li>
    <li>Ajustando el espaciado del contenido de la página para que se alinee correctamente con el encabezado.</li>
    <li>Creando y navegando a la página "Sobre mí", debes crear un nuevo archivo HTML llamado about.html y configurar un enlace en el menú de navegación de tu sitio principal (index.html) para redirigir a esta nueva página. Además, ajusta el encabezado de la página about.html para que el título de la pestaña sea "Sobre mí" y agrega un <-h1> con el texto "Sobre mí" en el cuerpo de la nueva página. Asegúrate de que la navegación entre la página principal y la página "Sobre mí" funcione correctamente.</li>
    <li>Ajustando el estilo después de reorganizar archivos después de mover el archivo styles.css a una nueva carpeta llamada "styles", se perdió el estilo de tu sitio. Para corregir esto, debes actualizar la ruta del archivo CSS en tu archivo index.html. Además, en el archivo styles.css, debes eliminar la subrayado de los enlaces en el encabezado del sitio. Después de estas correcciones, verifica si el estilo se aplicó correctamente y si los enlaces del encabezado ya no están subrayados.</li>
    <li>Estructurando la página "Sobre mí", reutilizando el encabezado y el pie de página de la página inicial (index.html). Primero, copia el <-header> y el <-footer> de index.html y pégalos en el archivo about.html. Luego, agrega una sección <-main> vacía entre el <-header> y el <-footer>. Por último, verifica si la estructura copiada funciona correctamente en el navegador, con los enlaces de navegación y el texto del pie de página mostrándose.</li>
    <li>Importando y corrigiendo la ruta del archivo CSS en la página "Sobre mí", corregir la ruta del archivo para reflejar la estructura de carpetas actual. En el archivo about.html, agrega la etiqueta <-link> para importar styles.css. Recuerda que el archivo CSS se movió a una carpeta llamada "styles", por lo que la ruta de href en la etiqueta <-link> debe actualizarse a "./styles/styles.css". Después de esta corrección, guarda el archivo y recarga la página en el navegador para verificar si los estilos se aplicaron correctamente.</li>

 </ol>

 

<h1>Variables CSS</h1>

<h3>Las variables CSS y cómo usarlas para optimizar nuestro código.</h3>

<p>Las variables CSS nos permiten declarar colores, fuentes y otros estilos en un solo lugar, y luego usarlos en todo nuestro proyecto. Esto nos ayuda a:</p>
 <ol>

<li>Mantener nuestro código organizado: En lugar de repetir los mismos estilos en diferentes partes del código, podemos usar variables para referirnos a ellos.</li>
    <li>Facilitar la edición: Si necesitamos cambiar un color o una fuente, solo necesitamos modificar la variable una vez, y el cambio se aplicará en todo el proyecto.</li>
    <li>Para declarar una variable CSS, usamos la sintaxis nombredelavariable.</li>
    <li>En la clase, también vimos cómo usar la clase root para aplicar variables a todos los elementos de nuestro proyecto</li>
   
 </ol>
https://developer.mozilla.org/en-US/docs/Web/CSS/Using_CSS_custom_properties

<p> La clase root haceun cambio en todos los elmentos de mi proyecto</p>

img root

<p>Para saber si has aplicado correctamente los conceptos de la clase, puedes hacer lo siguiente:</p>
 <ol type='A'>

<li>Revisa tu código: ¿Has declarado las variables CSS correctamente? ¿Estás usando la sintaxis correcta para declararlas? ¿Estás usando la clase root para aplicar las variables a todos los elementos de tu proyecto?.</li>
    <li>Prueba tu código: ¿Funcionan las variables CSS como esperas? ¿Se aplican los colores y las fuentes correctamente en todo tu proyecto?</li>
    <li>Compara tu código con el ejemplo de la clase: ¿Has seguido la misma estructura y sintaxis que se mostró en la clase? ¿Has usado los mismos nombres de variables?</li>
    <li>Busca errores: Si tu código no funciona como esperas, busca errores en la consola del navegador. ¿Hay algún mensaje de error que te indique dónde está el problema?</li>
    <li>Pregunta a la comunidad: Si no puedes encontrar la solución por tu cuenta, no dudes en preguntar a la comunidad.</li>

 </ol>

 <h1> Aplicando las variables CSS</h1>
<p>cómo utilizar las variables CSS para optimizar nuestro código.</p>

 <ol>
<li>Primero, vimos cómo declarar las variables en el archivo CSS utilizando la sintaxis nombrevariable: valor;. Luego, aprendimos a aplicar estas variables en nuestro código HTML utilizando la función var(nombrevariable).</li>
    <li>Para ilustrar esto, cambiamos los colores y fuentes de nuestro proyecto utilizando variables. ¡Esto nos permitió cambiar el diseño de nuestro sitio web con solo modificar las variables en un solo lugar!</li>
    <li>También aprendimos a utilizar una herramienta llamada Color Hub para encontrar paletas de colores que nos inspiren y nos ayuden a crear diseños más armoniosos.</li>
    <li></li>
   
 </ol>
 <ol type='A'>

<li> Revisa tu código: Asegúrate de que has declarado las variables CSS correctamente en el archivo CSS.Recuerda que la sintaxis es nombrevariable: valor;. </li>
    <li>Aplica las variables: Verifica que estás utilizando la función var(nombrevariable) en tu código HTML para aplicar las variables a los elementos que deseas.</li>
    <li>Prueba diferentes valores: Cambia los valores de tus variables CSS y observa cómo se actualiza el diseño de tu página web. Esto te ayudará a comprender cómo funcionan las variables y cómo puedes usarlas para crear diferentes estilos.</li>
    <li>Crea un nuevo proyecto: Intenta crear un nuevo proyecto simple y aplicar las variables CSS que has aprendido. Esto te ayudará a consolidar tus conocimientos y a practicar la aplicación de las variables en un contexto real.</li>

 </ol>

<h3>Paleta decolores que podemos utilizar</h3>
https://colorhunt.co/

https://color.adobe.com/pt/create/color-wheel

