# Tutorial Markdown
Bienvenidos al tutorial deninitiuco en español para principiantes 2024
## Markdown
Primero que todo Markdown es un lenguaje de marcado que facilita la aplicación de formato a un texto empleando una serie de caracteres de una forma especial. En principio, fue pensado para elaborar textos cuyo destino iba a ser la web con más rapidez y sencillez que si estuviésemos empleando directamente HTML. Y si bien ese suele ser el mejor uso que podemos darle, también podemos emplearlo para cualquier tipo de texto, independientemente de cual vaya a ser su destino.
## Donde Practicar

Hay bastente lugar para escribir y editar tu código en Markdown, tienes varias opciones geniales. A continuación, te presento algunos sitios web donde puedes programar y previsualizar tus documentos Markdown:

1. [StackEdit](https://stackedit.io/): Un editor en línea poderoso que te permite escribir en Markdown y ver la previsualización al instante.

2. [Dillinger](https://dillinger.io/): Un editor Markdown en línea con una interfaz intuitiva y características avanzadas para ayudarte a editar tus documentos fácilmente.

3. [Markdown Live Preview](https://markdownlivepreview.com/): Una herramienta sencilla y rápida que te permite escribir en Markdown y ver la previsualización en tiempo real mientras escribes.

Cada uno de estos sitios tiene sus propias ventajas y características únicas, así que te animo a probarlos y elegir el que mejor se adapte a tus necesidades y preferencias. ¡Empieza a escribir en Markdown de forma rápida y sencilla con estas herramientas increíbles!

## Tutorial

Markdown es fácil de entender, pero para usarla correctamente es necesario conocer sus elementos de marcado. A continuación, se proporcionan explicaciones sobre las funciones clave.

### Titulos
En Markdown, puedes crear títulos utilizando numeral (#). Para un título principal, usas un numeral seguida de un espacio y luego tu texto. Para subtítulos, simplemente agregas más numerales antes del texto, creando hasta seis niveles de títulos. Esto es similar a cómo se crean títulos en HTML utilizando etiquetas de encabezado (h1, h2, h3, etc.).

#### Copia y prueba este codigo 
```markdown
# Título 1
## Título 2
### Título 3
#### Título 4
##### Título 5
###### Título 6
```
<div>
<a href="https://ibb.co/Yfy63g6">
<img src="https://i.ibb.co/XF39bH9/image.png" alt="image" width="300px" border="0" >
</a>
</div>

#### NOTA
Algunos usuarios también usan el numeral (#) después de los títulos en Markdown. Aunque esto puede hacer que la lectura sea más sencilla, no es necesario. Durante la conversión, este carácter simplemente se ignora.

### Comillas
Para hacer una cita en Markdown, usas el signo de mayor que (>). Puedes hacerlo línea por línea o al inicio del párrafo con una línea en blanco al final para terminar la cita. Además, puedes agregar otros elementos al formato de la cita en bloque.

#### Copia y prueba este codigo 
```markdown
>Este es un **fragmento con comillas**.
>El fragmento continúa aquí.

>Este es otro **fragmento con comillas**.
Este fragmento continúa en la siguiente línea.

Esta línea ya no está sangrada.

```
<div>
<a href="https://ibb.co/Yfy63g6">
<img src="https://i.ibb.co/h9pPfL1/image.png" alt="image" width="300px" border="0" >
</a>
</div>

### Listas
Para hacer una lista sin orden en Markdown, puedes usar el signo de más (+), un guion (-) o un asterisco (*). Todas estas opciones te darán el mismo resultado, una lista sin orden con viñetas.

#### Copia y prueba este codigo 
```markdown
- Elemento de la lista 1
- Elemento de la lista 2
- Elemento de la lista 3

```
<div>
<a href="https://ibb.co/Yfy63g6">
<img src="https://i.ibb.co/sqfWpgj/image.png" alt="image" width="300px" border="0" >
</a>
</div>

Si lo que quieres es crear una lista ordenada, **deberás introducir un número con un punto directamente después.**

```markdown
1. Elemento de la lista 1
2. Elemento de la lista 2
3. Elemento de la lista 3
```
### Imágenes e hipervínculos

Con Markdown, puedes agregar imágenes y enlaces fácilmente. Para crear un enlace, primero escribes el texto que quieres que aparezca visible entre corchetes, luego pones el enlace (URL) entre paréntesis justo después. Si quieres agregar un título que aparezca al desplazar el mouse sobre el enlace, simplemente escribe el título entre comillas dobles y paréntesis, separándolo del URL con un espacio.

#### Copia y prueba este codigo 
```markdown
A continuación se muestra un [Link](https://ejemplo.com/ "Título opcional del enlace").
```
A continuación se muestra un [Link](https://ejemplo.com/ "Título opcional del enlace").

Cuando incluyes un URL o una dirección de correo electrónico en tu texto en Markdown, la mayoría de los editores generarán automáticamente un hipervínculo que se puede seleccionar. Sin embargo, si prefieres que el URL se vea como texto normal y no se convierta en un hipervínculo, puedes rodearlo con los caracteres de menor que (<) y mayor que (>).

Además, si deseas que un URL aparezca literalmente y no se convierta en un hipervínculo, puedes marcarlo como código usando acentos graves (`), que es una práctica común en Markdown. Esto evitará que el editor lo convierta en un enlace.
 ```markdown
<https://ejemplo.com>
`https://ejemplo.com`
```
Asi se veria 

<https://ejemplo.com>
`https://ejemplo.com`

En Markdown, al igual que con los hipervínculos, también puedes insertar imágenes en tus documentos. Para hacerlo, primero coloca un signo de exclamación (!). Luego, escribe el texto alternativo de la imagen entre corchetes y el URL que lleva a la imagen entre paréntesis. De esta manera, la imagen se mostrará directamente en el texto.

![Esta es una imagen de ejemplo](https://qph.cf2.quoracdn.net/main-qimg-fd161a814da2b214c41c9e4e57df8c4c-lq)
