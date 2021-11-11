title: 6. Udon: markdown para Urbit
++++

# Udon

Udon es el lenguaje utilizado en Urbit para crear y renderizar los textos y documentos con una clara inspiración en la sintaxis de markdown.

## Títulos o encabezados

Las cabeceras en udon comienzan con uno más **#** y seguido de un espacio. El número de "#" corresponde a su pareja en HTML: # corresponde a <h1>, ## corresponde a <h2>, y así hasta <h6>.

Por ejemplo:
```
### Cabecera (h3)

##### Cabecera (h5)
```
Genera:

> ### Cabecera (h3)
> ##### Cabecera (h5)

## Listas

Un texto que comience con **-** o **+** y seguido de un espacio es interpretado como un elemento de una lista desordenada como <ul>. Y un testo que comience con un número (x.) y seguido de un espacio es interpretado como un elemento de una lista ordenada como <ol>.

Ejemplos de listas desordenadas:
```
- Lista desordenada.
El texto que se encuentra en una nueva línea se incluye en la misma línea que la anterior.

- List desordenada con\
El elemento "\" provoca que el texto que aparece a continuación se interprete como un salto de línea de <br>

- Lista desordenada con sublistas:
    - Sublista
        - Subsublista
```
Genera:

> - Lista desordenada.
> El texto que se encuentra en una nueva línea se incluye en la misma línea que la anterior.
>
> - List desordenada con\
> 
> El elemento "\" provoca que el texto que aparece a continuación se interprete como un salto de línea de <br>
> 
> - Lista desordenada con sublistas:
>    - Sublista
>        - Subsublista

Ejemplos de listas ordenadas (se aplican las mismas reglas en el texto que en las desordenadas):
```
+ Lista ordenada 1
+ Lista ordenada 2

- Lista desordenada
    1. Sublista ordenada 1
    2. Sublista ordenada 2

1. Lista ordenada 1
    1. Sublista ordenada 1
    2. Sublista ordenada 2
1. Lista ordenada 2
```
Genera:

> 1. Lista ordenada 1
> 2. Lista ordenada 2
>
> - Lista desordenada
>    1. Sublista ordenada 1
>    2. Sublista ordenada 2
>
> 1. Lista ordenada 1
>    1. Sublista ordenada 1
>    2. Sublista ordenada 2
> 2. Lista ordenada 2

## Citas

Las citas se inician con un **>** y su texto indentado por dos espacios generará un <blockquote>. En la cita se puede incluir todo tipo de reglas de marcaje de Udon.

Por ejemplo:
```
>  Leave the internet behind. **Tlon.io**
```
Genera:
> Leave the internet behind. **Tlon.io**

## Bloques de código

Un bloque de código se puede generar al introducir y al finalizar el código con **```**.

Por ejemplo:

```
 (def Y (fn [f]
        ((fn [x]
           (x x))
         (fn [x]
           (f (fn [y]
                ((x x) y)))))))
```

## URL

Para insertar un enlace, debemos poner el contenido del texto a enlazar entre corchetes [], seguido por la URL de destino entre paréntesis (). El propio contenido del texto puede tener estilo.

Por ejemplo:
```
Para saber más, visita [*Urbit*](https://urbit.org/).
``` 
Genera:
> Para saber más, visita [*Urbit*](https://urbit.org/).


## Imágenes

Para insertar imágenes en un chat simplemente debemos poner la URL de la imagen con el tipo de archivo que es. 

Por ejemplo:
```
https://avilagrijalva.com/urbit/posts/images/eturbit.jpg
```
Genera:
![](posts/images/eturbit.jpg#small)

Para poder usar imágenes en las notas, posts, o colecciones, se debe usar:

```
![](url_imagen)
```
----

**Reconocimientos:**

> - https://bud.jaccarmac.com/unmark/doc/

*[5. Manual del operador](5_operaciones.md) < Anterior lección* - *Siguiente lección ```/~pendiente/``` > [7. A los mandos de la nave](7_mandos.md)*