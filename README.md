# Evaluación final Verónica Enamorado

¡Hola! Este es mi ejercicio de evaluación final del primer módulo de Adalab.

## Para usarlo...

Necesitarás instalar Node.js y Gulp, después sigue estos pasos:
1. Clona el repositorio
2. Instala las dependencias locales con $ npm install
3. Arranca con $ gulp

## Al principio... 

En cada ordenador que usemos, al principio y solo una vez instalaremos node y el comando de gulp de forma global para poder usarlo desde cualquier carpeta usando npm install -- global gulp-cli

## Cada vez que estemos trabajando con el código...

Desde la terminal ejecutamos el comando gulp para que realice la tarea por defecto, que en el caso del gulpfile.js en este proyecto estará pendiente de los archivos Sass, html y JavaScript y los compilará, minificará y/o recargará el servidor cada vez que hagamos un cambio. 

## Estructura del proyecto
Esta es la estructura de carpetas que vas a encontrar aquí:

```
/
`- _src
   |- assets
   |  |- icons
   |  |- images
   |  |- js
   |  `- scss
   |     `- core
   |
   `- templates
      `- partials
```

### HTML: 
Viene incluído el paquete gulp-html-partial que permiter tener un sistema de plantillas html

### Imágenes e iconos
En _src/ hay una carpeta para las imágenes del proyecto y una para los iconos.

### CSS
Viene incluído el paquete gulp-combine-mq que agrupa todas las mediaqueries al final del documento css.

### ¿Cómo actualizo si tengo una versión anterior?
En principio puedes descargar todos los archivos fuera de _src/ y sustituir los de tu proyecto. Además deberías replicar la estructura de carpetas dentro de _src/.



Si tienes alguna duda o problema, comunícate conmigo a través de los Issues ;) ¡Gracias por pasarte!