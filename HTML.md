Mis apuntes de HTML
================
Patricio Said

### Apundes desde Codecademy:

#### Monstrar texto

Para mostrar texto se puede usa *párrafos* o *span*:

-   *Párrafo* (`<p>`) contiene un bloque de texto plano.
-   `<span>` contiene trozos cortos de texto. Se usa para separar contenido que está dentro de otro.

El mejor uso de span es para remarcar un objeto específico que está en una linea. Y usar `<div>` para dividir el contenido en *bloques*.

**Styling texts**

Se puede editar el estilo de untexto usando los tags HTML. El tag `<em>` hace enfasis en el texto, mientras `<strong>` resalta lo importante.

-   El tag `<em>` generalmente se renderiza como *cursiva*.
-   El tag `<strong>` generalmente se renferiza como **negrita**.

-   El tag `<br>`agrega un linea de *quiebre*.

**Lista desordenada**

`<ul>` `<li>Limones</li>` `<li>Tortillas</li>` `<li>Pollo</li>` `</ul>`

El output sería algo como esto:

-   Limones
-   Tortillas
-   Pollo

**Lista ordenada**

`<ol>   <li>Limones</li>   <li>Tortillas</li>   <li>Pollo</li> </ol>`

El output sería algo como esto:

1.  Limones
2.  Tortillas
3.  Pollo

**Imágenes**

Se puede insertar imagen con el tag `<img>`. Este tag se cierra solo, no requiere un slash `/`. El tag `<img>` requiere un atributo llamado `src` para determinar la fuente de la imagen (dirección). En este caso, el valor de `src` debe ser *uniform resourse locator* (URL).

**Ejemplo de imagen:**

Con `<img src = https://s3.amazonaws.com/codecademy-content/courses/web-101/web101-image_brownbear.jpg>` resulta:

<img src = https://s3.amazonaws.com/codecademy-content/courses/web-101/web101-image_brownbear.jpg>
