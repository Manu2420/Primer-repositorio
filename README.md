# Aprendiendo _Markdown_


### Encabezados

# Encabezado de nivel 1
## Encabezado de nivel 2
### Encabezado de nivel 3
#### Encabezado de nivel 4
##### Encabezado de nivel 5
###### Encabezado de nivel 6

### Párrafos

Párrafo 1...

Lorem ipsum dolor sit amet consectetur adipisicing elit. Labore vero temporibus libero commodi, magnam beatae eius, excepturi doloribus debitis unde voluptates dolorem quaerat corrupti inventore rerum harum quidem animi et!.

Más párrafos que estamos agregando.

### Textos

_cursiva_

**negrita**

~~tachado~~

_**cursiva y negrita**_

_~~cursiva y tachado~~_

**~~negrita y tachado~~**

_**~~cursiva, negrita y tachado~~**_


### Enlaces

[Youtube](https://www.youtube.com/)

[Google](https://www.google.cl/)


### Imágenes

![Ejemplo de imagen](/img/codigo.png "Titulo de la imágen")

![Otro ejemplo](/img/codigo2.jpg "Otro título")


### Divisiones

Un bloque de contenido.

---

Otro párrafo de contenido


### Listas ordenadas

1. Enero
1. Febrero
1. Marzo
1. Abril
1. Mayo
1. Junio

---

1. Prímavera
1. Verano
1. Otoño
1. Invierno

### Listas desordenadas

- Prímavera 
    - Septiembre
    - Octubre
    - Noviembre
    - Diciembre
- Verano
    - Diciembre
    - Enero
    - Febrero
    - Marzo
- Otoño
    - Marzo
    - Abril
    - MAyo
    - Junio
- Invierno
    - Junio
    - Julio
    - Agosto
    - Septiembre

* Julio
    * Agosto
* Septiembre
    * Octubre


### Citas

#### Citas en línea

>Todo lo que escuchamos es una opinión, no un hecho. Todo lo que vemos es una perspectiva, no la verdad. - Marco Aurelio.


#### Citas en bloque

> Todo lo que escuchamos es una opinión, no un hecho. Todo lo que vemos es una perspectiva, no la verdad.
>
> Marco Aurelio.


### Tablas

#### Forma 1

Color   |Número |Letra
:---    |:---:  |---:
Azul    |Uno    |A
Rojo    |Dos    |B
Verde   |Tres   |C

#### Forma 2

|Color   |Número |Letra|
|--------|-------|-----|
|Azul    |Uno    |A    |
|Rojo    |Dos    |B    |
|Verde   |Tres   |C    |


### Código

#### En línea

Esto es un `código` en línea.

En _JavaScript_ una variable se define así: `let saludo = "Hola Mundo";`.

#### En bloque

```js
function sumar(a, b) {
  if (typeof a !== "number" || typeof b !== "number") {
    console.error(`Los valores ingresados NO son números.`);
    return false;
  }

  let c = a + b;
  return c;
}
```

### Código HTML

<form>
  <label for="q">Buscar:</label>
  <input type="search" name="q" id="q" required />
  <input type="submit" value="🔍" />
</form>


### Comentarios

<!-- Esto es un comentario que no se verá en la vista previa -->


### Escape de caracteres

Texto en \_cursiva\_ y \*\*negrita\*\*


### Anclas

[Inicio](#aprendiendo-markdown)