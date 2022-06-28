# Introducción a cómo funciona la web

---

<h1 class="text-center">¿Cómo funciona un sitio web?</h1>

<div class="flex flex-col mt-10 gap-10">
    <img src="/images/peticiones-servidor.png" alt="Diagrama de peticiones HTTP">
    <p>
        Al entrar a un sitio web pasan muchas cosas al mismo tiempo, como podemos ver
        en el 
        <a href="https://excalidraw.com/#json=YGhCkaM_m8jKNJN7Nus_F,htQYFXJ6gq0wq3ab6DPPyA" target="_blank">diagrama</a>,
         primero tenemos el cliente que puede ser un usuario, un bot, un microondas
        o cualquier otro dispositivo los cuales le piden algo al servidor, ya sea un HTML, un JSON,
        un XML, etc, después el servidor procesa esa petición y devuelve lo solicitado si tiene los permisos
        necesarios.
    </p>
</div>

---

<h1 class="text-center">Protocolo HTTP</h1>

<div class="flex flex-col mt-10 gap-10">
    <p>
        HTTP, de sus siglas en inglés: "Hypertext Transfer Protocol", es el nombre de un protocolo el cual nos permite realizar una petición de datos y recursos, como pueden ser documentos HTML. Es la base de cualquier intercambio de datos en la Web, y un protocolo de estructura cliente-servidor, esto quiere decir que una petición de datos es iniciada por el elemento que recibirá los datos (el cliente), normalmente un navegador Web. Así, una página web completa resulta de la unión de distintos sub-documentos recibidos, como, por ejemplo: un documento que especifique el estilo de maquetación de la página web (CSS), el texto, las imágenes, vídeos, scripts, etc...<br/>    
        <div class="text-right">Tomado de <a href="https://developer.mozilla.org/es/docs/Web/HTTP/Overview">MDN</a></div>
    </p>
</div>

---

<h1 class="text-center">Peticiones HTTP</h1>

<div class="flex flex-col mt-10 gap-10">
    <p>
        HTTP define un conjunto de métodos de petición para indicar la acción que se desea realizar para un recurso determinado. Aunque estos también pueden ser sustantivos, estos métodos de solicitud a veces son llamados HTTP verbs. Cada uno de ellos implementan una semántica diferente, pero algunas características similares son compartidas por un grupo de ellos: ej. un request method puede ser safe, idempotent, o cacheable.<br/>    
        <div class="text-right">Tomado de <a href="https://developer.mozilla.org/es/docs/Web/HTTP/Methods">MDN</a></div>
    </p>
    <ul class="flex gap-5 flex-wrap justify-center">
        <li>GET</li>
        <li>HEAD</li>
        <li>POST</li>
        <li>POST</li>
        <li>PUT</li>
        <li>DELETE</li>
        <li>CONNECT</li>
        <li>OPTIONS</li>
        <li>TRACE</li>
        <li>PATCH</li>
    </ul>
</div>

---

<h1 class="text-center">Frontend</h1>

<div class="flex gap-5">
    <div>
        <img class="w-80" src="/images/diagram-web.jpeg" alt="Diagrama de la estructura de un sitio web">
    </div>
    <p>
    En la programación frontend tenemos los siguientes lenguajes:
    <ul class="flex flex-col gap-5 mt-5">
        <li>HTML</li>
        <li>CSS</li>
        <li>JavaScript</li>
    </ul>
    </p>
</div>

---

<h1 class="text-center">HTML</h1>

<p><a href="https://developer.mozilla.org/es/docs/Web/HTML">HTML</a>: (Lenguaje de Marcas de Hipertexto, del inglés HyperText Markup Language) es el componente más básico de la Web. Define el significado y la estructura del contenido web. Además de HTML, generalmente se utilizan otras tecnologías para describir la apariencia/presentación de una página web (CSS) o la funcionalidad/comportamiento (JavaScript).</p>

```html
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mi primer HTML</title>
</head>
<body>
    <h1>Hola tesoros</h1>
</body>
</html>
```

---

<h1 class="text-center">CSS</h1>

<p><a href="https://developer.mozilla.org/es/docs/Web/CSS">CSS</a>: Hojas de Estilo en Cascada (del inglés Cascading Style Sheets) o CSS es el lenguaje de estilos utilizado para describir la presentación de documentos HTML o XML (en-US) (incluyendo varios languages basados en XML como SVG, MathML o XHTML). CSS describe como debe ser renderizado el elemento estructurado en la pantalla, en papel, en el habla o en otros medios.</p>

```css
p {
    color: red;
    padding: 1rem;
    background: white;
}
```
---

<h1 class="text-center">JavaScript</h1>

<p><a href="https://developer.mozilla.org/es/docs/Web/JavaScript">JavaScript</a>: JavaScript (JS) es un lenguaje de programación ligero, interpretado, o compilado justo-a-tiempo (just-in-time) con funciones de primera clase. Si bien es más conocido como un lenguaje de scripting (secuencias de comandos) para páginas web, y es usado en muchos entornos fuera del navegador, tal como Node.js, Apache CouchDB y Adobe Acrobat JavaScript es un lenguaje de programación basada en prototipos, multiparadigma, de un solo hilo, dinámico, con soporte para programación orientada a objetos, imperativa y declarativa (por ejemplo programación funcional)</p>

```js
function saludar(){
    console.log("Hola a todos");
}

saludar();
```

---

<h1 class="text-center">¿Aparte de la aplicaciones web, dónde podemos usar estos lenguajes?</h1>
<ul>
    <li><a href="https://www.electronjs.org/">Aplicaciones de escritorio</a></li>
    <li><a href="https://www.sitepoint.com/javascript-command-line-interface-cli-node-js/">Command Line interface</a></li>
    <li><a href="https://reactnative.dev/">Aplicaciones móviles</a></li>
    <li><a href="https://phaser.io/">Videojuegos</a></li>
    <li><a href="https://iotjs.net/demo/">Internet Of Things</a></li>
    <li>Y muchas cosas más</li>
</ul>