# Declarar una variable de solo lectura con la palabra clave const

La palabra clave **let** no es la única forma nueva de declarar variables. En **ES6**, también puede declarar variables usando la palabra clave **const**.

**const** tiene todas las increíbles características que permite tener, con la ventaja adicional de que las variables declaradas usando **const** son de solo lectura. Son un valor constante, lo que significa que una vez que se asigna una variable con **const**, no se puede reasignar:

~~~

const FAV_PET = "Gatos";
FAV_PET = "Perros";
La consola mostrará un error debido a la reasignación del valor de FAV_PET.

~~~

Siempre debe nombrar las variables que no desea reasignar usando la palabra clave **const**. Esto ayuda cuando accidentalmente intenta reasignar una variable que debe permanecer constante.

> **_NOTE:_** Nota: es común que los desarrolladores usen identificadores de variables en mayúsculas para valores inmutables y minúsculas o camelCase para valores mutables (objetos y matrices). Aprenderá más sobre objetos, matrices y valores inmutables y mutables en pasos posteriores. También en pasos posteriores, verá ejemplos de identificadores de variables en mayúsculas, minúsculas o camelCase.

### Ejercicios

1. En main.js Cambie el código para que todas las variables se declaren usando let o const. Use let cuando desee que la variable cambie y const cuando desee que la variable permanezca constante. Además, cambie el nombre de las variables declaradas con const para ajustarse a las prácticas comunes. No cambie las cadenas asignadas a las variables.