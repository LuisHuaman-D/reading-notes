# READ 03: Introducción a CSS
## ¿Cuál es el propósito de CSS?
El css nos sirve para darle estilos al html, los css nos permite cambiar de color a los textos, reducir o aumentar el tamaño de textos, imagenes, agregar espacios dentro y fuera de contenedores incluso podemos utilizar css para crear algunos efectos de animación en textos, imagenes o entre otros archivos en formato svg.

## ¿Qué analogía NO técnica usarías para explicar la responsabilidad de HTML vs. CSS?
Vamos a imaginar que el html es una persona desnuda, bien el CSS es el responsable de que la persona se vea bien vestida convinando los colores de su ropa a utilizar.

## ¿Cuáles son las tres formas de insertar CSS en tu proyecto?
- La primera forma es insertar el css mediante un archivo externo dentro de un elemento link que va en el html (dentro del head)
- La segunda forma es insertar los css mediente el elemento <style> </style> del css directamente en el html dentro de la sección <head></head>
- La tercera forma es insertar el estilo en línea para aplicarlo a un elemento único, puedes agregar el atributo style en elementos como <p  style="color:red"> <section  style=""> <div style="">

Escribe un ejemplo de una regla CSS que daría texto rojo a todos los elementos <p>.
Bien imagina que tienes tu archivo html y a los parrafos quieres especicarle un color entonces puedes utilizar un archivo externo (style.css) y decirle que p {color: red;} con eso se aplica a todos tus parrafos el color rojo.