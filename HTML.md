Mis apuntes de HTML
================
Patricio Said

### Apundes desde Codecademy:

#### Monstrar texto

Para mostrar texto se puede usa *párrafos* o *span*:

  - *Párrafo* (`<p>`) contiene un bloque de texto plano.
  - `<span>` contiene trozos cortos de texto. Se usa para separar
    contenido que está dentro de otro.

El mejor uso de span es para remarcar un objeto específico que está en
una linea. Y usar `<div>` para dividir el contenido en *bloques*.

#### Styling texts

Se puede editar el estilo de untexto usando los tags HTML. El tag `<em>`
hace enfasis en el texto, mientras `<strong>` resalta lo importante.

  - El tag `<em>` generalmente se renderiza como *cursiva*.

  - El tag `<strong>` generalmente se renferiza como **negrita**.

  - El tag `<br>`agrega un linea de *quiebre*.

#### Lista desordenada

`<ul>` `<li>Limones</li>` `<li>Tortillas</li>` `<li>Pollo</li>` `</ul>`

El output sería algo como esto:

  - Limones
  - Tortillas
  - Pollo

#### Lista ordenada

`<ol> <li>Limones</li> <li>Tortillas</li> <li>Pollo</li> </ol>`

El output sería algo como esto:

1.  Limones
2.  Tortillas
3.  Pollo

#### Imágenes

Se puede insertar imagen con el tag `<img>`. Este tag se cierra solo, no
requiere un slash `/`. El tag `<img>` requiere un atributo llamado `src`
para determinar la fuente de la imagen (dirección). En este caso, el
valor de `src` debe ser *uniform resourse locator* (URL).

#### Ejemplo de imagen:

Con `<img src =
https://s3.amazonaws.com/codecademy-content/courses/web-101/web101-image_brownbear.jpg>`
resulta:

<img src = https://s3.amazonaws.com/codecademy-content/courses/web-101/web101-image_brownbear.jpg>

En imágenes de puede usar el atributo `alt` , y sirve para entregar una
descripción de la imágen. Esto tiene varios propósitos:

  - Si alguna imágen falla al cargar puede ser facilmente localizada.
  - Ayuda en los motores de búsquedas.

`<img
src=https://s3.amazonaws.com/codecademy-content/courses/web-101/web101-image_brownbear.jpg
alt="oso"/>`

<img src = https://s3.amazonaws.com/codecademy-content/courses/web-101/web101-image_brownbear.jpg alt = "oso" />

#### Videos

Para insertar videos se utiliza `<video>` y este tag se debe cerrar
`</video>`

`<video src
="https://s3.amazonaws.com/codecademy-content/courses/freelance-1/unit-1/lesson-2/htmlcss1-vid_brown-bear.mp4"
width = "320" height="240" controls></video>`

Se puede modificar el tamaño con `width` y `height` . El atributo
`controls` indica los controles básicos de un video al navegador (pausa,
play , stop).

### Creando Documentos estandar en HTML

Los archivos HTML necesitan ciertos elementos para preparar un documento
apropiadamente. Le puedes indicar al navegador que está trabajando con
HTML empezando tu documento con una *declaración de tipo de documento*:

> `<!DOCTYPE html>`

Esta declaración es una instrucción y debe ser ser la primera linea de
código del documento HTML. `<!DOCTYPE html>` hace referencia a HTML5.
Un documento en HTML se debe guardar como **.html**. La declaración
`<!DOCTYPE html>` le entrega al navegador dos informaciones: el tipo de
documento y la versión.

Para crear una estructura y contenido se debe abrir y cerrar el tag
`<html>` después de la declaración `<!DOCTYPE html>`.

`<!DOCTYPE html>` `<html>` `  ` `</html>`

Todo lo que esté dentro del tag `<html>` será interpretado como HTML.

### El HEAD

El tag `<HEAD` contiene *metadata* de la web, es decir, información de
la página y que no es mostrada. Frecuentemente se pone depués del tag
`<html>`.

### Título de la página

El `<title>` va siempre dentro del `<head>` y se muestra en la pestaña
del navegador.
