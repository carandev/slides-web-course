# Introducción a HTML y CSS

---

<style>
    code {
        font-size: 1.3rem;
    }
</style>

<h1 class="text-center">Estructura de HTML</h1>

```html
<etiqueta atributo="valor">contenido</etiqueta>
```

<h2 class="mt-50 text-center">Comentarios en HTML</h2>

```html
<!-- Esto es un comentario de ejemplo que el navegador ignorará -->
```

---

# ¿Cómo usar CSS?

* **CSS Externo**: Se hace con la etiqueta `<link>` y el código se escribe en un archivo CSS
a parte, es el método más recomendado.

* **CSS Interno**: Se hace con la etiqueta `<style>` y el código se escribe dentro de la etiqueta.

* **Estilos en línea**: Se hace con el atributo `style="..."` y el código se escribe dentro del atributo.

---

# Estructura de CSS

<style>
    code {
        font-size: 1.3rem;
    }
</style>

```css
selector { 
    propiedad: valor;
    propiedad: valor;
}
```

<h3 class="text-center mt-20">Comentarios en CSS</h3>

`/* Comentario útil para recordar cosas */`

---

# Atributos comunes en HTML

<ul>
    <li>id</li>
    <li>class</li>
    <li>lang</li>
    <li>translate</li>
    <li>title</li>
    <li>data-*</li>
</ul>

---

# Identificador de etiqueta (id) 

En HTML, podemos darle un identificador a una etiqueta HTML y de esta forma darle un nombre. Simplemente, añadimos el atributo id y colocamos el nombre como valor de ese atributo. Ese nombre de identificador no debe empezar nunca por un número y puede contener letras mayúsculas, minúsculas, signos especiales (guión, guión bajo...) o números

```html
 <div id="articulo">Aquí irá el contenido de texto del artículo</div>
```

También es usado como selector de CSS de la siguiente manera:

```css
#articulo {
    color: red;
}
```

--- 
layout: two-cols
---

# Clases de etiquetas (class) 

Las clases funcionan de una forma muy similar a los id, pero son mucho más flexibles. En primer lugar, no tienen la limitación de los ids, por lo que su nombre se puede repetir y no es necesario que aparezca sólo una vez por página.
De hecho, la idea de las clases es establecer géneros o tipos de etiquetas, a los que les asociemos características comunes.

```html
<div id="pagina">
  <div class="anuncio primero">Aquí irá un anuncio</div>
  <div id="articulo">Aquí irá el contenido de texto del artículo</div>
  <div class="anuncio ultimo">Aquí irá un anuncio</div>
</div>
```
::right::

<div class="ml-20">
También es usado como selector de CSS de la siguiente manera:

```css
#articulo {
    color: red;
}

.anuncio {
    background-color: black;
    color: white;
}

.anuncio.primero {
    background-color: black;
    color: #ccc;
}
```
</div>

---

# Idioma del contenido 

Mediante el atributo lang podemos indicar el idioma del contenido de la etiqueta. El valor de dicho atributo tendrá que ser el código [ISO 639-1](https://es.wikipedia.org/wiki/ISO_639-1) del idioma al que queremos hacer referencia. También podemos utilizar el atributo translate para indicar si el contenido de un texto es o no traducible
```html
<p>
  Hace algunos días fuí a ver la nueva película de <span translate="no">StarWars</span>.
</p>
```

# Títulos o tooltips 

En la mayoría de las etiquetas HTML podemos indicar el atributo title para especificar un mensaje de texto que aparezca cuando el usuario detenga el ratón sobre el elemento un instante. Al usuario le aparece un pequeño aviso emergente, generalmente con fondo amarillo y letras negras, que muestra el texto en cuestión
```html
<div>
  <img src="Gandalf.jpg"
    alt="Gandalf el gris, utilizando un portátil para consultar su correo."
    title="¡Este es Gandalf el gris!" />
</div>
```

---

# Metadatos (datasets) 

En HTML, veremos que la mayoría de los metadatos (información adicional) se incluyen en la etiqueta `<head>` del documento HTML. Sin embargo, también se puede incluir metadatos en la propia etiqueta HTML a través de un atributo con prefijo data-

```html
<div id="compartir">
  <a href="https://twitter.com/share/?url=https://lenguajehtml.com/"
     data-share="43">Twitter</a>
  <a href="https://www.facebook.com/sharer/sharer.php?u=https://lenguajehtml.com/"
     data-share="66">Facebook</a>
  <a href="https://plus.google.com/share?url=https://lenguajehtml.com/"
     data-share="38">Google+</a>
</div>
```
