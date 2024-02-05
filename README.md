# ¿Qué es GIT?
Es un sistema control de versiones distribuido, libre y de código abierto, fue diseñado para manejar desde pequeños proyectos a proyectos muy grandes de manera eficiente.

Es el sistema de control de versiones más utilizado, es una herramienta con bastante madurez, su desarrollo inicial comenzó en el año 2005 por Linus Torvalds.

Git es el perfecto ejemplo de un sistema de control distribuido, ya que en vez de tener un lugar donde ver las versiones de cambio, cada copia de un repositorio puede tener su propio historial de cambios.

Otro de los beneficios que hacen tan popular a GIT, es que ha sido diseñado con seguridad, flexibilidad y rendimiento en mente.

# ¿Qué es GITHUB?

Es un sitio web para administrar y almacenar código, ya que permite llevar el control de cambios en el código.

Github es una implementación en la nube de GIT, facilita la colaboración y control entre equipos que ya utilizan GIT para almacenar código.

Uno de sus puntos a favor es que es una interfaz de usuario, donde se pueden hacer operaciones sin la necesidad de conocer los comandos necesarios si se estuviera utilizando una terminal de comandos. 

# ¿Qué es MARKDOWN?

Es un lenguaje de etiquetas, utilizado para agregar formato a documentos de texto plano, originalmente creado en el año 2004,

Markdown tiene la particularidad que puede usarse para sitios web, documentos, notas, libros e incluso correos electrónicos.

## Etiquetas de MARKDOWN


### Sintaxis básica

|Nombre|Sintaxis|
|--|--|
|Heading| #H1, ##H2, ### H3|
|Bold|** Bold  **|
|Italic|* italic *|
|Blockquote| > blockquote|
|Lista ordenada| 1. Primer elemento. 2. Segundo elemento.
|Lista sin orden|- Primer elemento. - Segundo elemento.|
|Código|\`código\`|
|Línea horizontal| --- |
|Link| \[title](https://www.example.com)|
|Imagen|\!\[alt text](image.jpg)|

### Sintaxis extendida
|Nombre|Sintaxis|
|--|--|
|Tabla|\|Sintaxis\|Descripción\| </p> \|--\|--\|  </p>  \|Contenido 1\|Contenido 2 \|| 

# MagicCells

Son comandos específicamente diseñados para Jupyter Notebook, permiten acceder a funcionalidades directas, permite la integración con otros sistemas y así como la ejecución de código.

Existen de dos tipos, de línea delimitados por "%" y de celda delimitados por "%%"

## Ejemplos
```
@register_line_magic
def hello(line):
    if line == 'french':
        print("Salut tout le monde!")
    else:
        print("Hello world!")
%hello
%hello french
```

Imprime:
```
Hello world!
Salut tout le monde!
```
