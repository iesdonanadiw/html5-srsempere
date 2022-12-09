# HTML to HTML5

 #### **1. El código del fichero estructura_html.html está en HTML haciendo uso de elementos div para estructurarla. Crea un nuevo fichero llamado estructura_html5.html y realiza los cambios oportunos para que esté escrito en HTML5. Sigue las indicaciones de uso de estas etiquetas semánticas que se detallan a continuación:**

 ---
 **Etiquetas Semánticas HTML5**
 ```
 <header>   <footer>   <nav>   <figure>    <aside>   <section>   <article>
 ```

 **<div\/\> (en HTML5 orientado a SEO) :**
 La etiqueta div no ha muerto, sigue ahí y sigue significando lo que siempre ha significado: conjunto de elementos. Debemos usarla como ayuda a la estructura de página: como base para crear el layout de de nuestras páginas, siempre y cuando no exista otra etiqueta de conjunto que represente mejor este papel. En otras palabras, div es la herramienta para unir elementos cuando no podemos asociar significado semántico a este conjunto.

 **<header\/\> :** Nos permite identificar la cabecera de la página (que no forma parte del contenido único).

 **<footer\/\> :** Hace otro tanto con el footer (que tampoco forma parte del contenido único).

 **<nav\/\> :** Nos permite marcar conjunto de links como menús y por tanto ayudar a lo sbuscadores a detectar nuestra estructura web.

 **<figure\/\> :** Representa contenido independiente, a menudo con un título (figcaption). Si bien se relaciona con el flujo principal, su posición es independiente de éste. Por lo general, se trata de una imagen, una ilustración, un diagrama, un fragmento de código, o un esquema al que se hace referencia en el texto principal, pero que se puede mover a otra página o a un apéndice sin que afecte al flujo principal.

 **<section\/\> :** 
 El uso de seción es muy parecido al de div pero aportando la carga de significado mínima posible al contenido. Englobando distintos elmentos dentro de una etiqueta <section\/\> lo que estamos haciendo es declarar que todo su contenido está relacionado y forma parte de un mismo significado o elemento.

 La diferencia es sutil pero muy importante: cuando creamos bloques cuyo contenido forma un todo usaremos <section\/\>, cuando estos bloques responden más a diseño o a necesidades de estructura usaremos <div\/\>.

 **<article\/\> :** 
 Por último la etiqueta <article\/\> es el siguiente paso a la hora de declarar que un cojunto de elmentos en nuestra página tiene significado. En este caso el paso dado es el dar a entender que ese conjunto tiene significado claro incluso si lo sacamos totalmente de la página. Es decir, al incluir algo dentro dentro de la etiqueta <article\/\> lo que estamos diciéndole a los buscadores es que dentro de este article podrá encontrar contenidos únicos con su propio significado.

 Esto nos lleva casi siempre a que en páginas normales nuestro contenido será el único <article\/\> de la página y en páginas con listados de elementos tendremos un <article\/\> por cada elmento del listado.

 Idealmente, esta al ser un contenido con significado propio, podría contener en su interior etiquetas <header\/\>, <section\/\>, <aside\/\> y <footer\/\>.

 **<aside\/\> :**
 Por ultimo nos queda la etiqueta aside que viene a ser una etiqueta <section\/\> venida a menos. Y es que aside sirve para indicar que ese bloque es solo un añadido a los bloques que tiene al lado. Son datos extra sin lo que podríamos pasar perfectamente pero que hemos decidido añadir en el documento. Trata de contenido añadido por temas que no tienen nada que ver con el contenido de página (normalmetne esas columnas laterales llenas de tags y banners). Cuando lo incluimos dentro de un <article\/\> nos indica que esa información complementa el artículo pero no forma parte de él (listas de datos, testimoniales, banners relacionados, etc...).

 ---

 #### **2. Crea una página HTML (mi_form_html5.html) que contenga, al menos, cinco tipos de elementos posibles de formulario en HTML5. Todos los elementos deben tener un elemento label relacionado. Puedes consultar el fichero form_html5.html para extraer algunos de los elementos.**
