# Explore las diferencias entre las palabras clave var y let

Uno de los mayores problemas con la declaración de variables con la palabra clave **var** es que puede sobrescribirse fácilmente:

~~~

var campista = "James";
var campista = "David";
consola.log(campista);

~~~

En el código anterior, la variable **campista** se declara originalmente como **James** y luego se anula para que sea **David**. Luego, la consola muestra el string **David**.

En una aplicación pequeña, es posible que no se encuentre con este tipo de problema. Pero a medida que su base de código se vuelve más grande, puede sobrescribir accidentalmente una variable que no tenía la intención de sobrescribir. Debido a que este comportamiento no arroja un error, la búsqueda y corrección de errores se vuelve más difícil.

Se introdujo una palabra clave llamada **let** en **ES6**, una importante actualización de JavaScript, para resolver este posible problema con la palabra clave **var**. Aprenderá sobre otras características de **ES6** en pasos posteriores.

Si reemplaza **var** con **let** en el código anterior, se produce un error:

~~~

let campista = "James";
let campista = "David";
El error se puede ver en la consola de su navegador.

~~~

Entonces, a diferencia de var, cuando usa let, una variable con el mismo nombre solo se puede declarar una vez.

### Ejercicios

1. Actualice el código en main.js para que solo use la palabra clave let.