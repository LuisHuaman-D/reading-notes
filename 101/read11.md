# Read 11: Introducción al DOM y Proyectos

## ¿Qué es el DOM?
El DOM es una representación orientada al objeto de la página web, El DOM facilita la estructura de documentos como HTML y XML así mismo define de que manera los programas pueden acceder con el fin de modificar tanto la estructura, estilos y contenido, esto puede ser moficado con javascript.

## Describe brevemente la relación entre el DOM y JavaScript.
El DOM no es un lenguaje de programación pero sin él, el lenguaje JavaScript no tiene ningún modelo o noción de las páginas web, de la páginas XML ni de los elementos con los cuales es usualmente relacionado.
En el comienzo, JavaScript y el DOM estaban herméticamente enlazados, pero después se desarrollaron como entidades separadas.


## ¿Qué método usarías para seleccionar un elemento del DOM por su ID y cómo se utiliza?
Para seleccionar un ID del DOM puedes utilizar el siguiente código. 

```document.getElementId(Id)``` 

Luego esto lo guardas en una variable 

```let seleccionarId = document.getElementId(nuevoId)``` 

y utilizando la variable ```seleccionarId``` puedes aplicar modificaciones.


## ¿Qué método utilizarías para cambiar el color de fondo de un elemento en el DOM y cómo se implementaría? 
En este caso podriamos aplicarlo directamente utilizando el siguiente código: 

```document.body.style.backgroundColor = "red";``` 

Esto nos permite seleccionar directamente el body del html y cambiar de fondo.

El siguiente código nos permite seleccionar un id y cambiarlo de fondo. 

```let cambiarFondo = document.getElementById("pruebas");``` 
```cambiarFondo.style.backgroundColor = "red";``` 
 

 [Readme](../README.md)