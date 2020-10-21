# How to use Markdown

Para introducir el código Markdown lo primero que se necesita saber es que hay **tres tipos de elementos basicos**: 

- **Elementos de bloque**
    - Párrafos y saltos de línea
    - Encabezados
    - Citas
    - Listas
    - Códigos de bloque
    - Reglas horizontales

- **Elementos de línea**
    - Énfasis
    - Links o enlaces
    - Código
    - Imágenes

- **Elementos varios**
    - Links automáticos
    - Omitir Markdown

Con esto podemos empezar a introducirnos en el mundo del Markdown y explayarnos con los conceptos de cada uno de los elementos basicos.

## Elementos de bloque
----------------------------------------------------------------

## Párrafos y saltos de línea

Para generar un nuevo párrafo solamente hay que separar el texto mediante una línea en blanco.

**nota:** Markdown no soporta dobles líneas en blanco (es decir que al momento de procesar las líneas estas se convertiran en una sola).

Para empezar una frase en una línea siguiente dentro del mismo párrafo solo debe pulsar dosveces la barra espaciadora antes de pulsar una vez intro.

## Encabezados

Las *#* almohadillas nos sirven para crear encabezados en diferentes niveles.

**nota:** debes agregar una almohadilla por cada nivel.

- # Encabezado 1
- ## Encabezado 2
- ### Encabezado 3
- #### Encabezado 4
- ##### Encabezado 5
- ###### Encabezado 6

Tambien existe otra forma de hacer encabezados pero la desventaja es que esta limitado a dos niveles

Consiste un *subrayar* los encabezados con el símbolo *=* (para el encabezado 1), o con *-* (para encabezado 2)

Esto sería un encabezado 1
====

Esto sería un encabezado 2
----

## Citas

Las citas se generan usando el cáracter *>* al comienzo del bloque de texto.

> Esto sería una cita.

**nota:** Si la cita se compone de varios párrafos se debera añadir un símbolo *>* al comienzo de cada uno de ellos.  
Si conectas varios *>>* puedes hacer **citas anidadas**.

> Esto es una cita normal
>
>> Esto es una cita anidada
>
> Aquí termina la cita normal

## Listas


### Listas desordenadas

Para crear una lista desordenada se puede utilizar * *asteriscos*, - *guiones* o + *símbolo de suma*

- Elemento 1
* Elemento 2
+ Elemento 3

**nota:** no importa cual de los simbolos utilices todos se verán igual al procesarse

Para hacer una **lista anidada** solo debes poner cuatro espacios en blanco antes del siguiente símbolo
  
- Primer elemento
    - Primer subelemento

### Listas ordenadas

Para crear una lista ordenada debes utilizar la sintaxis de tipo *número* 1. (al igual que con las listas desordenadas, tambien podras **anidarlas o combinarlas**)

1. Elemento de lista 1
2. Elemento de lista 2
    - Elemento de lista 3
    - Elemento de lista 4
        1. Elemento de lista 5

## Código de bloque

Para crear un bloque de código solo debes encerrar dicho párrafo entre dos líneas formadas por tres *~* 

~~~~
Este es un bloque de código.
Puedes añadir tantas líneas y párrafos como quieras
~~~~

## Reglas horizontales

Las reglas horizontales se utilizan para separar secciones de una manera visual.

Para crearlas solo debes en una línea blanca incluir **tres de los siguientes elementos**: *, - o _.

***
---
___

**nota:** tambien puedes separarlos mediante un espacio en blanco por pura estética.

## Elementos de línea
----------------------------------------------------------------

## Énfasis (negritas y cursivas)

En Markdown se utiliza **asteriscos** o **guiones bajos** para enfatizar.

Simplimente se envuelve la palabra o en el texto con éstos símbolos para conseguir *cursivas* o **negritas**

- *cursiva*
- _cursiva_
- **negrita**
- __negrita__

**nota:** Si queremos usar los dos tipos de énfasis solo tenemos que combinar la sintaxis.  
***negrita y cursiva***  
___negrita y cursiva___

## Links o enlaces

### Links o enlaces en línea

Como su nombre lo indica, se encuentra en línea con el texto.
Se crean esribiendo la palabra o texto enlazada entre _[ ]_ **corchetes**, y el link en cuestión entre _( )_ **paréntesis**

[Projecto git_prueba](https://github.com/Paola-Sbert/git_prueba)

### Links o enlaces como referencia

Para tener un texto mas limplio y ordenado podemos usar los enlaces por referencia.

Esto quiere decir que en tu texto enlazarás **palabras o códigos concretos** (formados por letras y/o números), que en otro lugar más apartado de tu documento tendrás definidos como determinadas URL.

[Nombre que quieres darle a tu enlace][nombre de tu referencia]

## Código

A veces necesitaras añadir pequeñas secciones donde mostrar código de otro lenguaje, atajos de teclado, o demás contenido que no debería ser tratado como tal.

Para ello se tiene dos alternativas

**Código puro** 

La fórma más sencilla de escribir código en Markdown es envolver el texto entre dos comillas sencillas `.

`` Esto es una línea de código ``


**Texto preformateado**

La otra manera de añadir código en Markdown es comenzar un párrafo con cuatro espacios en blanco.

    Esto es una línea de código

**nota:** estos espacios deberan ser incluidos en cada línea que escribas.

## Imágenes

Insertar una imágen con Markdown es muy similar a insertar links, solo que en este caso se debe añadir el símbolo *!* **exclamación** al principio y el enlace sera la ubicación de la imagen.

![Texto alternativo][imágen referencia]

**nota:** El texto alternativo es lo que se mostraría si la carga dela imagen fallase.  
Si agregas un texto alternativo entrecomilládo al final de la ruta, esté sera el titulo mostrado al dejar el cursor sobre la imágen.

## Elementos varios
-----------------------------------------------------------------

## Links automáticos

Se utilizan cuando se quiere **mostrar una URL completa**.

Para generar links automáticos solo debes rodear el link con los símbolos *<>*

<https://github.com/Paola-Sbert/git_prueba>

## Omitir Markdown

Para poder escribir los símbolos *, -, _ sin que Markdown los procese como cursiva, negrita lista, etc. podemos utilizar el síbolo */*.  
 Escribiendola delante de cualquiera de los elementos anteriormente mensionados los mismos no tendran efecto a la hora de procesarse  


\`  acento invertido

\*  asterisco

\_  guión bajo

\{} llaves

\[] corchetes

\() paréntesis

\#  almohadilla

\+  símbolo de suma

\-  guión

\.  punto

\!  exclamación



[nombre de tu referencia]:https://github.com/Paola-Sbert/git_prueba

[imágen referencia]:https://i.pinimg.com/280x280_RS/dd/ac/cd/ddaccd9bf85a7ddcdea491beefadf922.jpg "titulo de la imagen"