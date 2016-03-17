# exercices-mockup-angularjs

Exercises involving mockup designing and coding javascript in Angular.js

[ESP]

## Descripción

Ejercicios para maquetar y programar en Angular.js

## Instalación

Hacer un fork de este repo y subir al mismo todos los ejercicios. Se puede acompañar si se desea con un fichero

## Ejercicios

Este proyecto se ha creado para realizar ejercicios para maquetar y programar en Javascript con Angular.js

El objetivo es intentar realizar el número de tareas mayor que se pueda. Si alguna no se puede o no se sabe hacer, se valorará intentar hacerlo de manera alternativa. Si no se especifica nada en concreto, se podrán realizar de la forma que más guste.

Los *lenguajes* deseados son: Gulp, Jade, SASS y Angular 1.5.

Tareas a realizar:

- Montar un `gulpfile.js` capaz de compilar SCSS, Jade.
- Montar un entorno usando Angular.js
- A ser posible usar jerarquía de componentes: `.component()`
- Maquetar el SVG `test.svg` de prueba utilizando Jade y SCSS.
- Adaptar a mobile.
- Menú de arriba `Why | Pricing | Help | Blog` enlaza a páginas tontas
- Formulario funcionando `Let's do it right now`
  - Errores en el formulario:
    - `age`: es un número.
    - `iwant`: es un texto seleccionado desde un desplegable.
  - El botón `submit` lanza un POST a http://private-deb0a-desiretestapi.apiary-mock.com/wishes, con el siguiente body
```json
// body
{
    "age": 45,
    "iwant": "a house"
}
```
  - Se puede ver la doc en : [Desire Test API Doc](http://docs.desiretestapi.apiary.io)
- Al pulsar `log in` sale un lightbox con un formulario para login.
- Al pulsar `Let's do it` sale un lightbox con un formulario para registro.
- Los formularios de registro y login:
  - El diseño no es importante, pueden ser planos.
  - Dos campos: `username` y `password`.
  - Pueden tener los dos los mismos campos.
  - Se tienen que distinguir al menos en el título del lightbox y en el texto del botón `submit`.


¡Gracias y a darle duro! :-)
