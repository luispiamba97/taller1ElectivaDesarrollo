### taller1ElectivaDesarrollo

## *1. ¿Qué es HTML y cuál es su función en la web?*

Es el lenguaje de marcado estándar utilizado para crear y estructurar el contenido de las páginas web. Su función es definir el esqueleto del sitio mediante elementos que organizan textos, imágenes, enlaces, formularios y multimedia.

## *2. ¿Qué es una etiqueta HTML y menciona las más comunes?*

Una etiqueta es un fragmento de código delimitado por corchetes angulares (< >) que define un elemento HTML y le dice al navegador cómo interpretarlo, ejemplo:

- < html > : Contenedor raíz del documento.

- < head >: Contiene metadatos, títulos y enlaces a recursos externos.

- < body >: Alberga todo el contenido visible de la página.

- < h1 > a < h6 >: Encabezados o títulos jerárquicos.

- < p >: Define un párrafo de texto.

- < a >: Crea hipervínculos hacia otras páginas o recursos.

- < img >: Inserta imágenes.

- < div > y < span >: Contenedores genéricos de bloque y de línea.

- < ul >, < ol > y < li >: Listas desordenadas, ordenadas y sus elementos.

## *3. ¿Qué es un atributo de una etiqueta HTML y menciona los más comunes?*

Un atributo proporciona información adicional o configuraciones específicas a una etiqueta HTML; siempre se ubica dentro de la etiqueta de apertura, ejemplo:

- id: Identificador único para un elemento en el DOM.

- class: Asigna una o más clases para aplicar estilos CSS o seleccionar elementos mediante scripts.

- src: Especifica la ruta de un recurso usado en < img >, < script >.

- href: Define el enlace de destino en etiquetas < a > o enlaces a hojas de estilo en < link >.

- alt: Proporciona un texto alternativo para imágenes.

- style: Aplica estilos CSS en línea directos.

## *4. ¿Qué es CSS y cómo se utiliza para el diseño web?*

CSS (Cascading Style Sheets) es un lenguaje de diseño gráfico utilizado para definir la presentación visual de un documento HTML. Se aplica enlazando un archivo externo (.css), mediante la etiqueta < style > en el < head >, o usando estilos en línea con el atributo style. Permite controlar colores, tipografías, márgenes y la disposición de los elementos (layout).

## *5. ¿Qué es una propiedad en CSS y menciona las más comunes?*

Una propiedad es un aspecto visual o de comportamiento específico que se desea modificar en una regla de CSS, ejemplo:

- color: Define el color del texto.

- background-color: Define el color de fondo.

- font-size: Determina el tamaño de la tipografía.

- margin: Controla el espacio exterior alrededor de un elemento.

- padding: Controla el espacio interior entre el contenido y el borde del elemento.

- display: Define cómo se comporta la caja del elemento (block, inline, flex, grid).

- width / height: Ajustan el ancho y alto.

## *6. ¿Qué es un selector en CSS y cuáles tipos existen?*

Un selector identifica los elementos HTML a los cuales se aplicarán las reglas de estilo definidas, ejemplo:

- Universal (*): Aplica a todos los elementos del documento.

- De tipo o etiqueta (p, div): Selecciona elementos según su nombre de etiqueta HTML.

- De clase (.mi-clase): Selecciona elementos con un atributo class específico.

- De ID (#mi-id): Selecciona el elemento único con ese id.

- De atributo ([ type="text" ]): Selecciona según la presencia o valor de un atributo.

- Combinadores / Pseudo-clases / Pseudo-elementos: (div p, :hover, ::before).

## *7. ¿Qué es JavaScript y cómo añade la interactividad a las páginas web?*

JavaScript es un lenguaje de programación interpretado y de alto nivel. Añade interactividad al ejecutarse en el navegador y manipular el DOM (Document Object Model) en tiempo real, respondiendo a eventos del usuario (clicks, desplazamientos, entradas de texto), validando formularios dinámicamente y comunicándose con servidores mediante peticiones asíncronas (Fetch/AJAX).

## *8. ¿Cuáles son los tipos de datos primitivos en JavaScript?*

- String: Cadenas de texto ("Hola").

- Number: Valores numéricos enteros o decimales (42, 3.14).

- Boolean: Valores lógicos (true o false).

- Undefined: Variable declarada sin un valor asignado.

- Null: Ausencia explícita e intencional de valor.

- Symbol: Identificador único e inmutable (introducido en ES6).

- BigInt: Representa números enteros de precisión arbitraria.

## *9. ¿Cómo funcionan las estructuras de control de flujo como if, else, switch y bucles en JavaScript?*

Permiten alterar la secuencia lineal de ejecución del código según condiciones lógicas:

- if / else: Evalúa una condición booleana; si es verdadera ejecuta un bloque de código, de lo contrario ejecuta la alternativa.

- switch: Evalúa una expresión frente a múltiples casos (case) para ejecutar la coincidencia correspondiente de forma limpia.

- Bucles (for, while, do...while): Repiten un bloque de código mientras una condición dada se mantenga verdadera.

## *10. ¿Por qué es importante usar nombres significativos para variables y métodos?*

Mejora la legibilidad, mantenibilidad y autodocumentación del código. Permite que otros desarrolladores (o el autor en el futuro) entiendan el propósito de una variable o función sin requerir comentarios extensos, reduciendo errores durante la actualización o refactorización del software.

## *11. ¿Qué es una variable de entorno y por qué son importantes para Javascript o la programación en general?*

Una variable de entorno es un valor dinámico configurado fuera del código fuente, en el sistema operativo o en el entorno de ejecución. Son fundamentales para mantener la seguridad (evitando subir claves API o credenciales a repositorios públicos) y para adaptar el comportamiento del software según el entorno (desarrollo, pruebas, producción) sin modificar el código.

## *12. ¿Qué son las herramientas de desarrollo de Chrome y cómo se accede a ellas?*

Son un conjunto de utilidades integradas en el navegador Google Chrome para inspeccionar, depurar y optimizar código web en tiempo real. Se accede mediante la tecla F12, la combinación Ctrl + Shift + I (en Windows/Linux) o haciendo clic derecho sobre cualquier elemento de la página y seleccionando Inspeccionar.

## *13. ¿Qué se puede hacer en el panel "Elements" de las herramientas de desarrollo?*

Permite visualizar y editar de forma interactiva la estructura HTML y las reglas CSS aplicadas en la página actual. Facilita la prueba rápida de estilos, inspeccionar la caja de diseño (box model), verificar la accesibilidad y simular diferentes resoluciones de pantalla.

## *14. ¿Cómo se utiliza el panel "Console" de las herramientas de desarrollo y para qué es útil?*

Se utiliza para imprimir mensajes mediante console.log(), capturar errores de ejecución de JavaScript, advertencias del sistema y ejecutar snippets de código directamente sobre la sesión activa. Es la herramienta principal para la depuración (debugging) rápida.

## *15. ¿Qué información se puede obtener del panel "Network" y por qué es importante?*

Muestra todas las peticiones HTTP/HTTPS realizadas por la página (documentos, imágenes, scripts, APIs). Proporciona datos sobre códigos de respuesta (200, 404, 500), tiempos de carga, tamaño de archivos transferidos y encabezados de solicitud. Es vital para diagnosticar fallas de red, analizar el rendimiento de la aplicación y verificar la comunicación con servicios backend.