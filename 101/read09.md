# Read 09: Introducción a Javascript

## 1. ¿Cuáles son los diferentes tipos de datos que se pueden utilizar en JavaScript y cómo se diferencian entre sí?
Segun el último estándar ECMAScript define 8 tipos de datos. 
* Los cuales 7 de ellos son llamados   **primitivos**
    
    * 1. **Boolenao.** Son los true y false.

    * 2. **null.** Este denota un valor nulo, tomar en cuenta que null no es lo mismo que Null o NULL.

    * 3. **undefined.** Cuando un valor no esta definido.
    * 4. **Number.** Indica un número entero o un número con coma flotante.
    * 5. **BigInt.** Indica un número entero con precisión arbitraria ejemplo. 9007199254740992n
    * 6. **String.** Representa un valor de tipo texto.
    * 7. **Symbol.** Cuando sus datos son únicas e inmutables.

    y por ultimo tenemos a **Object**.

Aunque estos tipos de datos son una cantidad relativamente pequeña, permiten realizar funciones útiles con tus aplicaciones. Los otros elementos fundamentales en el lenguaje son los Objetos y las funciones. Puedes pensar en objetos como contenedores con nombre para los valores, y las funciones como procedimientos que puedes programar en tu aplicación.

## 2. ¿Cómo se utilizan las estructuras condicionales if y else en JavaScript, y qué propósito cumplen dentro de un programa?

Esta estructura de condicionales nos permite ejecutar bloques de código en función a si una condición es verdadera o falsa. Teniendo así un proposito para la toma de decisiones de un programa.

## 3. ¿Cuáles son los diferentes tipos de operadores en JavaScript y cómo se utilizan los operadores aritméticos para realizar cálculos?

Existen diferentes tipos de operadores en js: 
* Operadores aritméticos
* Operadores de asignación
* Operadores de comparación
* Operadores de cadena
* Operadores lógicos
* Operadores bit a bit
* Operadores ternarios
* Operadores de tipo

### Operadores aritméticos para realizar cálculos.
Tenemos un ejemplo: 

    let a = 3;
    let x = (100 + 50) * a;

    Este tomaria los valores 

    100 + 50 = 150
    150 * 3 = 450  
    
    Valor de x = 450

## 4. ¿Cómo se declara una variable en JavaScript y cuáles son las diferencias entre var, let y const en cuanto a su alcance y mutabilidad?

Podemos declarar variables:

 Con la palabra clave var. Por ejemplo, var x = 42. Esta sintaxis se puede utilizar para declarar variables locales y globales, dependiendo del contexto de ejecución.

Con la palabra clave const o let. Por ejemplo, let y = 13. Esta sintaxis se puede utilizar para declarar una variable local con ámbito de bloque.

Si utilizas: 
    
    var a = "Luis"
    var a = "Juan"
Es no te dara ningun error y hoy no es recomendable utilizar var.


    let a = "Luis"
    a = "Juan"
Con esto podemos cambiar el valor de forma dinamica. 

con 

    const a = 45

No puedes declarar una constante con el mismo nombre que una función o una variable en el mismo ámbito.


[Readme](../README.md)