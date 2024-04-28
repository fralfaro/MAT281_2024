# Markdown

<img src="https://downloads.marketplace.jetbrains.com/files/18897/166369/icon/pluginIcon.png" width = "200" align="center"/>

## Introducción

Markdown es un lenguaje de marcado ligero que se utiliza comúnmente para dar formato a texto de una manera sencilla y legible. Se diseñó originalmente para ser fácil de escribir usando un editor de texto plano y fácil de convertir a HTML u otros formatos de presentación

 Fue creado por John Gruber y Aaron Swartz en 2004 con el objetivo de facilitar la escritura y la lectura de texto sin necesidad de utilizar herramientas complicadas.


La cantidad de [tutoriales](https://joedicastro.com/pages/markdown.html) en la red sobre *Markdown* es inmenso, 
por lo que nos centraremos en indicar las opciones que más se utilizan.

* **Texto en negrita/cursiva**: El texto en negrita se indica entre dos pares de asteriscos. De este modo `**palabra**` aparecerá como **palabra**. Por otro lado, el texto en cursiva se indica entre dos asteriscos simples; es decir `*palabra*` aparecerá como *palabra*.


* **Listas**: Las listas en *Markdown* se realizan indicando un asterisco o un número seguido de un punto si se desean listas numeradas. *Markdown* organiza automáticamente los items asignándoles el número correcto.


* **Inclusión de imágenes**: La sintaxis para incluir imágenes en Markdown es `![nombre alternativo](dirección de la imagen)` en donde el nombre alternativo aparecerá en caso de que no se pueda cargar la imágen y la dirección puede referirse a una imagen local o un enlace en Internet.


* **Inclusión de código HTML**: El lenguaje *Markdown* es un subconjunto del lenguaje HTML y en donde se necesite un mayor control del formato, se puede incluir directamente el código HTML.


* **Enlaces**: Las celdas de texto pueden contener enlaces, tanto a otras partes del documento, como a páginas en internet u otros archivos locales. Su sintaxis es `[texto](dirección del enlace)`.


* **Fórmulas matemáticas**: Gracias al uso de *MathJax*, se puede incluir código en $\LaTeX$ para mostrar todo tipo de fórmulas y expresiones matemáticas. Las fórmulas dentro de una línea de texto se escriben entre símbolos de dólar `$...$`, mientras que las expresiones separadas del texto utilizan símbolos de dólar dobles `$$...$$`. Los siguientes son ejemplos de fórmulas matemáticas escritas en $\LaTeX$:

$$p(x) = 3x^2 + 5y^2 + x^2y^2$$

$$e^{\pi i} - 1 = 0$$

$$\lim_{x \rightarrow \infty} 3x+1$$

$$\sum_{n=1}^\infty\frac{1}{n^2}$$

$$\int_0^\infty\frac{\sin x}{x}\,\mathrm{d}x=\frac{\pi}{2}$$

$$R^2 = 
\begin{pmatrix} c & s \end{pmatrix} 
\begin{pmatrix} 1 & 0\\ 0 & 1 \end{pmatrix}
\begin{pmatrix} c \\ s \end{pmatrix} 
= c^2 + s^2$$


### Comandos Básicos 

#### Encabezados

Puedes crear encabezados utilizando el símbolo `#` seguido del texto del encabezado. Cuantos más `#` pongas, más pequeño será el encabezado.

Ejemplo:
```
# Encabezado de primer nivel
## Encabezado de segundo nivel
### Encabezado de tercer nivel
```

#### Párrafos

Los párrafos en Markdown son simplemente líneas de texto separadas por una línea en blanco.

Ejemplo:
```
Esto es un párrafo.

Esto es otro párrafo.
```

#### Negrita y Cursiva

Puedes hacer que el texto aparezca en negrita utilizando `**` o `_` alrededor del texto que deseas resaltar. Para cursiva, utiliza `*` o `_`.

Ejemplo:
```
**Texto en negrita**
__Texto en negrita__
*Texto en cursiva*
_Texto en cursiva_
```

#### Listas

Puedes crear listas ordenadas y no ordenadas utilizando `*`, `-` o `+` para elementos no ordenados, y números seguidos de un punto para listas ordenadas.

Ejemplo:
```
- Elemento 1
- Elemento 2
  - Subelemento 2.1
  - Subelemento 2.2
* Elemento 3
```

```
1. Elemento 1
2. Elemento 2
3. Elemento 3
```

#### Enlaces

Para crear un enlace, encierra el texto del enlace entre corchetes `[ ]` y la URL entre paréntesis `( )`.

Ejemplo:
```
[Texto del enlace](http://www.ejemplo.com)
```

#### Imágenes

Para insertar una imagen, utiliza el mismo formato que para los enlaces, pero precede el texto con un signo de exclamación `!`.

Ejemplo:
```
![Texto alternativo](ruta/a/la/imagen.jpg)
```

#### Citas

Para crear citas, utiliza el símbolo `>` al principio de la línea.

Ejemplo:
```
> Esto es una cita.
```

#### Código

Para resaltar código, encierra el texto entre backticks (\`).

Ejemplo:
```
`código`
```



