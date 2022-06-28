---
theme: seriph
background: https://images.unsplash.com/photo-1510915228340-29c85a43dcfe?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1170&q=80
---

# Introducción a la programación web

Carlos Andres Gomez Silva

---
layout: center
title: Presentación
---

<div class="flex gap-4">
    <img class="w-60 h-60 rounded-full" src="/images/profile.png" alt="Imagen de perfil">
    <div>
        <h1>Carlos Andres Gomez Silva</h1>
        <p>
        Soy un estudiante de ingeniería en sistemas, amante por el diseño y la programación; hace 4 años estoy estudiando
        programación viendo vídeos en YouTube, leyendo documentación oficial y libros, tomando cursos en algunas plataformas como
        Platzi, Udemy, Código Facilito, Edteam y algunas otras, todo esto totalmente gratis. Ahora quiero transmitir ese conocimiento
        adquirido a todos los que pueda.
        </p>
    </div>
</div>

<!-- Bievenida -->

---
layout: two-cols
---
# Contenido

<li>Instalación de las herramientas necesarias</li>
<li>Introducción a cómo funciona la web</li>
<li>Manejo básico de Visual Studio Code y creación de nuestra primera web</li>
<li>Introducción a HTML y CSS</li>
<li>Display Flex y Grid</li>
<li>Introducción a Git y GitHub</li>
<li>Práctica de HTML y CSS (Landing page)</li>
<li>Introducción a JavaScript</li>
<li>Objetos y arreglos en JavaScript</li>
<li>Manejo de arreglos y strings en JavaScript</li>
<li>Manipulación del DOM</li>

::right::
<li class="mt-13">Aplicación básica con HTML, CSS, JavaScript y Local Storage</li>
<li>Ejercicios básicos de lógica de programación</li>
<li>¿Qué es y cómo funciona una API?</li>
<li>¿Cómo consumir una API? Introducción a las promesas</li>
<li>Introducción al manejo de librerías</li>
<li>Práctica usando librerías interesantes</li>
<li>Introducción a un empaquetador (Vite)</li>
<li>Práctica de HTML, CSS, JavaScript y consumo de API</li>
<li>Ayuda con el proyecto final</li>
<li>Entrega del proyecto final</li>

<!-- Explicar por encima cada clase, puede ser que se incluyan más clases con el tiempo -->

---

# Herramientas necesarias

<div class="flex gap-20 flex-wrap justify-center mt-10">
    <div class="flex flex-col items-center gap-4">
        <fa-git class="text-8xl"/>
        <a href="https://git-scm.com/" class="text-center" target="_blank">Git</a>
    </div>
    <div class="flex flex-col items-center gap-4">
        <fa-github class="text-8xl"/>
        <a href="https://github.com/" class="text-center" target="_blank">GitHub</a>
    </div>
    <div class="flex flex-col items-center gap-4">
        <fa-firefox class="text-8xl"/>
        <a href="https://www.mozilla.org/en-US/firefox/new/" class="text-center" target="_blank">Navegador</a>
    </div>
    <div class="flex flex-col items-center gap-4">
        <mdi-nodejs class="text-8xl"/>
        <a href="https://nodejs.org/en/" class="text-center" target="_blank">Node JS</a>
    </div>
    <div class="flex flex-col items-center gap-4">
        <mdi-microsoft-visual-studio-code class="text-8xl"/>
        <a href="https://code.visualstudio.com/" class="text-center" target="_blank">VS Code</a>
    </div>
</div>

<!-- Descargar cada programa y mientras tanto explicar cada uno -->

---
layout: center
title: Git
---

<h1 class="text-center">Git</h1>

Es un software de control de versiones diseñado por Linus Torvalds, pensando en la eficiencia, la confiabilidad y compatibilidad del mantenimiento de versiones de aplicaciones cuando estas tienen un gran número de archivos de código fuente. Su propósito es llevar registro de los cambios en archivos de computadora incluyendo coordinar el trabajo que varias personas realizan sobre archivos compartidos en un repositorio de código. 

<!-- Hecho por el creador del sistema operativo Linux, ayuda mucho a no perder nunca ni una parte del proyecto -->

---
layout: center
title: GitHub
---

<h1 class="text-center">GitHub</h1>

GitHub es una plataforma de desarrollo colaborativo para alojar proyectos utilizando el sistema de control de versiones Git. Se utiliza principalmente para la creación de código fuente de programas de ordenador. El software que opera GitHub fue escrito en Ruby on Rails. Desde enero de 2010, GitHub opera bajo el nombre de GitHub, Inc. Anteriormente era conocida como Logical Awesome LLC. El código de los proyectos alojados en GitHub se almacena generalmente de forma pública.

<!-- Ahora pertenece a Microsoft y aunque hay más plataformas de este tipo GitHub es la más usada -->

---
title: Navegador
---

<h1 class="text-center">Navegador</h1>

<div class="flex gap-2">
    <div>
        <p>
            Un navegador web (en inglés, web browser) es un software, aplicación o programa que permite el acceso a la Web, interpretando la información de distintos tipos de archivos y sitios web para que estos puedan ser vistos. 
        </p>
        <div class="flex gap-10 flex-wrap justify-center mt-10">
            <fa-firefox class="text-8xl"/>
            <fa-chrome class="text-8xl"/>
            <fa-safari class="text-8xl"/>
            <fa-edge class="text-8xl"/>
            <fa-opera class="text-8xl"/>
            <fa-internet-explorer class="text-8xl"/>
        </div>
    </div>
    <img src="/images/browsers.png" alt="Estadistica de navegadores">
</div>

<!-- 
Cada navegador tiene sus ventajas y como programadores web debemos tener la mayoría para comprobar que nuestro
código funciona en todos.
-->

---
layout: center
title: Node JS
---

<h1 class="text-center">Node JS</h1>

Node.js es un entorno en tiempo de ejecución multiplataforma, de código abierto, para la capa del servidor (pero no limitándose a ello) basado en el lenguaje de programación JavaScript, asíncrono, con entrada y salida de datos en una arquitectura orientada a eventos y basado en el motor V8 de Google. Fue creado con el enfoque de ser útil en la creación de programas de red altamente escalables, como por ejemplo, servidores web. Fue creado por Ryan Dahl en 2009 y su evolución está apadrinada por la empresa Joyent, que además tiene contratado a Dahl en plantilla.

<!-- El creador después se dió cuenta que Node JS se podía mejorar y creó Deno -->

---
layout: center
title: Visual Studio Code
---

<h1 class="text-center">Visual Studio Code</h1>

Visual Studio Code es un editor de código fuente desarrollado por Microsoft para Windows, Linux, macOS y Web. Incluye soporte para la depuración, control integrado de Git, resaltado de sintaxis, finalización inteligente de código, fragmentos y refactorización de código. También es personalizable, por lo que los usuarios pueden cambiar el tema del editor, los atajos de teclado y las preferencias. Es gratuito y de código abierto, aunque la descarga oficial está bajo software privativo e incluye características personalizadas por Microsoft.

<!-- Aunque hay muchos más editores, este es el más usado, si quieres usar otro eres totalmente libre -->

---
layout: center
title: Fin
---

<h1 class="text-center">Hemos terminado nuestra primera clase, si tienes más preguntas es el momento final</h1>