# REVIEW DEL CURSO DE FRONT-END WEB DEVELOPER

## Día 1- 22 ABR

Páginas Web: Contenido de distinto tipo; imágenes, texto, vídeo, sonido, ... mostrado a través de un **navegador**.
Las páginas web para ser visualizadas de forma pública tienen que estar alojadas en un **servidor web**

Las webs son **texto** están desarrolladas en un lenguaje de marcas: **HTML**

```html
  <!DOCTYPE html>
  <html>
    <head>INFORMACION QUE NO SE VISUALIZA EN LA PAGINA</head>
    <body></body>
  </html>
```

Imagen: `<img>`
Titulo: `<h1>`
Lista desordenada: `<ul><li>`
Lista ordenada: `<ol><li>`
Hipervínculo: `<a></a>`
Texto: `<p>`

[página del curso](https://bcncodes-academy.web.app)

[MDN: La biblia del desarrollo web](mdn.com)

## Día 2 - 23 Abril

Elementos de bloque vs en linea

Elementos de bloque: div, p, h1, h2, main, header, footer,...
Elementos de línea: img, a, span, strong, i, em,...

Elementos semánticos:
header: contenido es la cabecera de la página
footer: contenido que va al pie de página
nav: barra navegación

strong, ul, table, ...

Comenzamos el ejercicio del [blog Anden27](http://anden-27.blogspot.com/2018/03/museo-de-los-vikingos-en-oslo.html)

## Día 3 - 26 Abril

Inicio CSS:
formato de una regla CSS
concepto de herencia de estilos
selectores de id y de clase

Ejercicio con selectores de clase
Recepta de la iaia. EJercicio entregable

## Día 4 - 27 Abril

Selectores avanzados: Según la posición en el árbol podemos seleccionarlos
Ej.: 

```css
selección de descendientes:
header a{ }
body nav{ }
selección hijos directos:
body > nav { }
header > nav { }
selección por agrupación:
p, h2{ }
selección por un atributo: img[src="gatito.jpg"]{ }
selección por pseudoelementos: div::before{ }
selección por pseudoclases: a:hover{ }
```
BOX-MODEL || MODELO DE CAJA

elemento de bloque: estructura de caja: contenido | padding | border | margin
medidas de una caja: ancho de una caja por defecto se refiere al contenido. Se puede cambiar con la propiedad:
    `box-sizing` y valor `border-box`
    
    
