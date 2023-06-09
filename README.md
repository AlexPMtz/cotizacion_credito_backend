# cotizacion_credito

## Herramientas tecnológicas

* **Express:** Es un framework web, escrito en JavaScript y alojado dentro del entorno de ejecución NodeJS. Ofrece el sistema de enrutamiento y características simplificadas para ampliar el framework con componentes y partes más potentes en función de los casos de uso de tu aplicación.
  * **Node.js:** Es un entorno que trabaja en tiempo de ejecución, que permite a los desarrolladores crear toda clase de herramientas de lado servidor y aplicaciones en JavaScript.
  * **MONGO DB:** Es una base de datos NoSQL orientada a documentos. A diferencia de una base de datos relacional SQL tradicional, MongoDB no se basa en tablas y columnas. Los datos se almacenan como colecciones y documentos.

## API REST 

API que funciona como sistema de cotización de créditos, en base a un producto seleccionado.

La API tiene distintos endpoints:

* Credit
  * **createQuote:** Crea una una cotización de crédito, en la cual debemos de mandar el plazo, la tasa normal y puntual, precio del producto y el id del porducto.
  * **getQuote:** Devuelve una lista en formato JSON de las cotizaciones de crédito existentes.
* Deadline
  * **createDeadline:** Da de alta una cotización de intereses en base a un plazo (semanas) seleccionadas.
  * **getDeadlines:** Devuelve una lista en formato JSON de las cotizaciones de intereses existentes.
* Product
  * **createProduct:** Crea un producto, pasándole nombre y precio del producto, el SKU se genera de manera aleatoria en el servidor.
  * **getProducts:** Devuelve una lista en formato JSON de los productos existentes.
  * **patchProduct:** Actualiza un elemento en la Base de datos, pasándole el ID del producto y los campos que queremos editar.
  * **deleteProduct:** Elimina un elemento en la Base de datos, pasándole el ID del producto.


## Ejercicios bonus

Existe un archivo llamado **Bonus.js** en el cual tengo los ejercicios que se pidieron en la prueba. Basta con clonar el repositorio y ejecutar el comando **node** y el nombre del archivo (Bonus.js)
