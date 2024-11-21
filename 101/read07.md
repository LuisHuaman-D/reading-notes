# Read 07: Control de Versiones
## ¿Qué es el control de versiones?
Es un sistema que nos permite controlar y registrar los cambios de archivos, con esto registros podemos recuperar versiones estables pasadas del código en caso tengamos una nueva modicación mal echa.  

## ¿Qué es “clone” en Git?
Este comando nos permite copiar un repositorio a nuestro y así poder trabajar de forma local. 

## ¿Cuál es el comando para agregar los archivos modificados a la zona de preparación?
Podemos utilizar estos comandos 

    git add . (Para añadir todos los archivos modificados)
    git add prueba.md   (Para añadir arhivos especificos )

## ¿Cuál es el comando para enviar la captura de los archivos modificados a Github?

El comando que debomos utilizar es:
    
    git push origin main

Pero antes de aplicar ese comando debemos utilizar el comando:
    
    git commit -m "nuevos cambios aplicados"

