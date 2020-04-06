+++
showonlyimage = true
draft = false
image = "img/portfolio/bannerhugotutorial.jpg"
date = "2016-11-05T18:25:22+05:30"
title = "Tutorial Hugo"
weight = 0
+++

Cómo instalar Hugo desde 0 para la creación de páginas web.

En esta publicación podrás aprender desde la instalación de Hugo, hasta la instalación de un tema en tu sitio web.
<!--more-->

> ###### Instalación de Hugo + Creación de sitio web

**Paso #1** Descomprimir del rar los 3 archivos Hugo

**Paso #2** Crear en el disco que deseemos una carpeta destinada a Hugo. Luego creamos una carpeta llamada "bin" dentro y copiamos los 3 archivos ahí.

![Archivos Hugo][1]

**Paso #3** Tecla windows y escribir **"editar las variables del entorno de esta cuenta"**

* Doble click o editar en "Path"
* Clickear "nuevo" y después "examinar"
* Seleccionar la ruta en donde instalamos Hugo, en este caso **C:\Hugo\bin** y finalmente aceptar.

![editar variables][2]

**Paso #4** Ejecutar comando **"CMD"** en windows para abrir la consola de **símbolo del sistema**.

En este paso cada comando que escribamos lo debemos ejecutar presionando Enter.

* Escribir **"cd/."** para retroceder al disco local.
* Escribir **"cd hugo"** para entrar a la carpeta local de hugo que instalamos.
* Para comprobar la instalación, debemos escribir **"hugo version"**, y si nos aparece el siguiente mensaje: **"Hugo Static Site Generator v0.67.1-4F44227B windows/amd64 BuildDate: 2020-03-15T19:32:32Z"**, significa que funcionó.

![CMD][3]

**Paso #5** Crearemos nuestro primer sitio web con **hugo new site 'nombre de nuestro sitio web'** y se creará una carpeta en los archivos locales de hugo con el nombre que asignamos a nuestra web. En este caso le colocaré "website" a mi sitio.


> ###### Instalación de tema en nuestro sitio web

**Paso #1** en esa carpeta debemos instalar el tema que queramos arrastrando la carpeta del tema a "themes" Es importante que la carpeta que nos descarguemos no termine en "-master", si es así, debemos borrar eso del nombre. Por ejemplo yo utilizaré un tema que se llama **"hugo-creative-portfolio-theme"**

![CMD][5]

**Paso #2** Abrimos la carpeta de nuestro tema, entramos a "examplesite" y cortamos todo dentro.

* Pegamos en la carpeta "website" que creamos anteriormente y reemplazamos todo lo que nos pida reemplazar.

![CMD][6]

**Paso #3** Finalmente para comprobar que nuestro sitio web fue creado con el tema que nosotros escogimos, debemos escribir en la consola **"hugo server"** para hostear la página web y visualizar el resultado. 

> **Es importante que estemos dentro de la carpeta de nuestro sitio web para hostear.** 
* Para entrar escribimos **cd 'nombre de nuestro sitio' y luego hosteamos** 












[1]: /img/carpetashugo.jpg
[2]: /img/editarvariables.jpg
[3]: /img/cmd.jpg
[5]: /img/website.jpg
[6]: /img/examplesite.jpg

