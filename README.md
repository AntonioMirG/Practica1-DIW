# Practica1-DIW

 Pregunta 1.
  
 * Explica cuál es la función del lenguaje HTML y del lenguaje CSS en la creación de una página web.

    HTML: Se utiliza para programar la estructura de la página web a través del uso de etiquetas, en resumen, sirve para estructurar elementos de la página, como imagenes, títulos, párrafos o tablas.

    CSS: Es un lenguaje de estilo, por ende, se usa para programar la estética de la página. Con este lenguaje se puede utilizar de diferentes formas, escribiendolo dentro del html o en un archivo externo y linkeandolo a este.

* ¿Por qué se recomienda el uso de los dos lenguajes? Di al menos 3 ventajas si lo usamos.

  Se recomienda el uso de html y css porque permite separar el contenido del diseño, haciendo que el codigo sea más fácil de entender y mantener, además separando el html y el css, podemos reutilizar el mismo css en varios hmtl si fuera necesario


* ¿Es recomendable usar estilos CSS incrustados en el código HTML, o dentro de la página HTML? ¿Por qué?

  El aplicar esta práctica presenta una serie de ventajas e inconvenientes, por una parte es recomendable hacerlo si se necesita aplicar estilos únicos a un elemento puntual y no se repite en otros lugares, pero presenta varios inconvenientes como la dificultad de mantenimiento del código, ya que se tendría que ir elemento por elemento.
   
Pregunta 2
 
  * A partir del siguiente fragmento de código HTML, Indica el nombre de las partes y describe su función. 

     `<p> </p>`: Se trata de la etiqueta correspondiente a párrafo, lo que esté dentro de esta etiqueta se mostrará como una línea de texto.

     `class="Cursiva"`: Se trata de una clase, en el archivo css en ".Cursiva" se especificará como está diseñana este párrafo.

      `id=verde`: Se trata de un identificador, el uso es bastante parecido a la class anterior con la diferencia principal de que el.

      `Texto`: Se trata de lo que mostrará la etiqueta, si escribes hola, el párrafo solo mostrará ese texto.

Pregunta 3 

 
* Explica la diferencia entre elementos en bloque y elementos en línea. A continuación, describe los siguientes elementos HTML y especifica si son en bloque o en línea:

  Elementos en bloque:

  Las caracteristicas principales son: ocupan todo el ancho disponible de su contenedor, comienzan en una nueva línea y desplazan el contenido hacia abajo.
Ejemplos comunes: `<div>, <p>, <h1>`

  Elementos en línea:

  Las caracteristicas princiaples son: ocupan solo el ancho necesario de su contenedor, no interrumpe el flujo del texto, pudiendo estar dentro de la misma línea con otros elementos.

  Ejemplos comunes: `<span>, <a>, <strong>` 


  `p`: Define un párrafo y es de tipo bloque.


   `span`:  Agrupa textos o elementos para aplicarles estilos y es de tipo línea


   `h2`:  Define un encabezado de nivel 2 y es de tipo bloque.

  `cite`:  Define citas, se utiliza para referenciar titulos y es de tipo línea

  `q`:   Define una cita corta dentro de un texto y es de tipo línea

   `header`: Define la cabecera de la página y es de tipo bloque

  

Pregunta 4  

* Explica qué es una regla de estilo y de qué elementos está formada. Pon un ejemplo indicando el 
nombre de cada elemento:

  En CSS una regla de estilo indica qué elementos se ven afectados y qué propiedades visuales se aplicarán a esos elementos.
Por ejemplo:
 `p {
    color: white;
    margin: 15px;
    font-size: 20px;
}`  


  En este ejemplo encontramos las cuatro partes que componen la regla de estilos, se divide en: 

  Selector`p`: Indica que el estilo se aplicará a todos los p (párrafos)

  Propiedad`color`,`margin`,`font-size`: Las cosas que se están modificando, en este caso el color, el margen y el tamaño del párrafo

  Valor`white`,`15px`,`20px`: El valor que se le aplicara a los cambios, en este caso el color blanco y el tamaño del margen y la fuente


Pregunta 5

* Utiliza Codepen ( codepen.io ) o Cssdeck ( cssdeck.com ) para hacer las pruebas y la captura de 
imagen del resultado.

Aquí tienes la lista de selectores:  
• h1+p  
• p > em  
• p em  
• p:lang(en)  

![image](https://github.com/user-attachments/assets/5ee1db72-ea76-4c58-9949-4166aeebeac7)

