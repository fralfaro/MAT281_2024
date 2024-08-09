# Markdown

<img src="https://downloads.marketplace.jetbrains.com/files/18897/166369/icon/pluginIcon.png" width="200" align="center"/>

## Introducción

[Markdown](https://www.markdownguide.org/) es un lenguaje de marcado ligero utilizado para dar formato a texto de manera sencilla y legible. Fue creado en 2004 por John Gruber y Aaron Swartz, y su principal ventaja es que es fácil de escribir y leer, tanto en su forma original como cuando se convierte a HTML u otros formatos de presentación.

Markdown se ha convertido en un estándar en la escritura de documentación, blogs, y hasta en sistemas de control de versiones como GitHub, donde se utiliza para escribir archivos README.

## Elementos Básicos de Markdown con Ejemplos

### 1. **Encabezados**

Los encabezados se crean utilizando el símbolo `#`. A mayor cantidad de `#`, menor será el nivel del encabezado.

#### Ejemplo:
```markdown
# Título Principal (H1)
## Subtítulo (H2)
### Sub-subtítulo (H3)
```

Resultado:

# Título Principal (H1)
## Subtítulo (H2)
### Sub-subtítulo (H3)

---

### 2. **Párrafos**

Un párrafo se crea simplemente escribiendo texto seguido de una línea en blanco. No se requieren saltos de línea explícitos a menos que quieras empezar un nuevo párrafo.

#### Ejemplo:
```markdown
Este es un párrafo simple.

Este es otro párrafo, separado del anterior por una línea en blanco.
```

Resultado:

Este es un párrafo simple.

Este es otro párrafo, separado del anterior por una línea en blanco.

---

### 3. **Negrita y Cursiva**

Puedes aplicar negrita y cursiva para destacar partes del texto.

- **Negrita:** Envuelve el texto con dos pares de asteriscos (`**texto**`) o guiones bajos (`__texto__`).
- *Cursiva:* Usa un par de asteriscos (`*texto*`) o guiones bajos (`_texto_`).

#### Ejemplo:
```markdown
**Texto en negrita**
*Texto en cursiva*
```

Resultado:

**Texto en negrita**  
*Texto en cursiva*

---

### 4. **Listas**

Markdown permite crear listas ordenadas y no ordenadas con facilidad.

- **Listas no ordenadas:** Usa `*`, `-`, o `+` seguido de un espacio.
- **Listas ordenadas:** Usa números seguidos de un punto.

#### Ejemplo de lista no ordenada:
```markdown
- Manzanas
- Naranjas
  - Valencia
  - Navel
- Uvas
```

Resultado:

- Manzanas
- Naranjas
  - Valencia
  - Navel
- Uvas

#### Ejemplo de lista ordenada:
```markdown
1. Primer paso
2. Segundo paso
3. Tercer paso
```

Resultado:

1. Primer paso
2. Segundo paso
3. Tercer paso

---

### 5. **Enlaces**

Puedes insertar enlaces tanto internos como externos. 

#### Ejemplo:
```markdown
[Visita Google](https://www.google.com)

[Mira la sección Encabezados](#encabezados)
```

Resultado:

[Visita Google](https://www.google.com)

[Mira la sección Encabezados](#encabezados)

---

### 6. **Imágenes**

Inserta imágenes de manera similar a los enlaces, pero precede el texto alternativo con `!`.

#### Ejemplo:
```markdown
![Logo de Markdown](https://downloads.marketplace.jetbrains.com/files/18897/166369/icon/pluginIcon.png)
```

Resultado:

![Logo de Markdown](https://downloads.marketplace.jetbrains.com/files/18897/166369/icon/pluginIcon.png)

---

### 7. **Citas**

Las citas se crean utilizando `>` al principio de la línea. Son útiles para destacar textos o para citas literales.

#### Ejemplo:
```markdown
> Esto es una cita importante.
```

Resultado:

> Esto es una cita importante.

---

### 8. **Código**

Para resaltar fragmentos de código en línea, usa acentos graves (`\``). Para bloques de código, envuélvelos con tres acentos graves.

#### Ejemplo de código en línea:
```markdown
El comando `ls` lista los archivos en el directorio.
```

Resultado:

El comando `ls` lista los archivos en el directorio.

#### Ejemplo de bloque de código:
```markdown
```
{
  "nombre": "John",
  "edad": 30
}
```
```

Resultado:

```
{
  "nombre": "John",
  "edad": 30
}
```

---

### 9. **Fórmulas Matemáticas**

Gracias a *MathJax*, puedes incluir expresiones matemáticas utilizando LaTeX dentro de Markdown.

#### Ejemplo de fórmula en línea:
```markdown
La ecuación de Einstein es $E = mc^2$.
```

Resultado:

La ecuación de Einstein es $E = mc^2$.

#### Ejemplo de fórmula en bloque:
```markdown
$$
\int_0^\infty \frac{\sin x}{x}\,dx = \frac{\pi}{2}
$$
```

Resultado:

$$
\int_0^\infty \frac{\sin x}{x}\,dx = \frac{\pi}{2}
$$




