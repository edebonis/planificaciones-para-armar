---
title: Puesta a punto
published: true
---

## Ensamblar del kit de construcción

Durante esta etapa van a aprender algunas cuestiones técnicas y
teóricas mientras construyen sus propios sitios con sus planes y
proyectos educativos

![Imagen del proceso del proyecto]({{site.baseurl}}/img/process.png)


Los planes de enseñanza y el sitio viven en
[GitHub](http://github.com). Github es una plataforma de desarrollo
colaborativo de software que permite el alojamiento de proyectos,
código y documentación usando el sistema de control de versiones Git y
además nos permite crear y mantener páginas web. Un repositorio es un
lugar donde alojar datos que posibilita administrar nuestro código (a
partir de ahora todo es código, el contenido de las planificaciones
como la estructura misma de las páginas), y ver las revisones y
modificaciones que se hacemos a través de una interfaz web bonita y
sencilla de usar.

La funcionalidad estrella de Github es el "fork" esta palabra proviene
del inglés "forking" que vendría a ser "ramificar". Algunos términos
quedarán en inglés, otros seran "castellanizados". Pero en cualquier
caso se van a ir aclarando en el proceso. Entonces, forkear es copiar
el repositorio de un usuario en la cuenta de otro usuario. Esto es lo
que harán con el repositorio de este proyecto. Al forkear este
repositorio estarán copiando la Planificación Para Armar de nuestro
repositorio, y lo modificarán en su propia cuenta para luego
publicarlo con su propia dirección web.

Sus planificaciones viviran en Github (así que no habrá que
preocuparse del hosting) y harán todo el proceso de construcción y
escritura ahí, al mismo timpo podrán ver las modificaciones en su
propia página web.

Si no están registrados en GitHub van a tener que crearse una cuenta
para poder comenzar.  <a class="btn btn-primary"
href="https://github.com/join" target="_blank"><i class="fa
fa-code-fork"></i>Crear una cuenta en GitHub</a>

Ahora sí, arrancamos:

1. <a class="btn btn-primary"
   href="https://github.com/acercadelaeducacion/planificaciones-para-armar/fork"
   target="_blank"><i class="fa fa-code-fork"></i> Forkeen este
   repositorio en GitHub.</a></li> El primer paso para tener la
   estructura de la planificación forkear el repositorio. Si
   todavía no saben bien qué es un repositorio o cómo funciona, echen
   un vistazo al <a
   href="https://help.github.com/articles/github-glossary" >glosario
   de GitHub</a> ojo, está en inglés. También pueden chequear <a
   href="http://www.yagoperez.com/un_poco_de_git_y_de_github%E2%80%8E/">otro
   glosario de Git + Github</a> que está en castellano.
2. Luego, en la interface del repositorio, busquen el archivo llamado
   <a class="btn btn-primary"
   href="https://github.com/alvarmaciel/planificaciones-para-armar/edit/gh-pages/_data/course.yml"
   target="_blank"><i class="fa fa-edit"></i>_data/course.yml y
   edítenlo</a> agregando su nombre, link a la imagen de perfil y su usuario de
   Twitter.
3. Hagan un **pull request** para que los cambios se agreguen a la versión principal del curso y aparezca su imagen en la galería de
   la primer página. Si no están muy segurxs de como hacer un **pull request** vean el <a href="{{site.baseurl}}{% post_url 2000-01-02-github-cheatsheet %}">Machete de GitHub</a>.
4. <a class="btn btn-primary" target="_blank"
   href="https://twitter.com/intent/tweet?url=http%3A%2F%2Fhowto.p2pu.org&text=Crear%20planificaciones%20online%20y%20participar%20de%20comunidades%20de%20Prácticas&hashtags=planificacionesparaarmar&via=p2pu&related=p2pu&via=amaciel&related=amaciel"><i
   class="fa fa-twitter"></i> Manden un tweet</a> y hagan corran la voz
   sobre planificaciones para armar! (No es un paso obligatorio, :D
   pero ayuda).
5. <a class="btn btn-primary" target="_blank"
   href="http://community.p2pu.org/t/please-introduce-yourself/28"><i
   class="fa fa-weixin"></i> presentense</a> en la comunidad de
   P2PU. Cuenten algo sobre ustedes y para que quieren usar las
   planificaciones para armar.

Cuando les pedimos que forkeen este sitio, lo que hicieron fue hacer
una copia del mismo y ¡ya comenzaron a construir el de ustedes! Esta
copia es sobre la cual trabajarán. Algunas de las cuestiones técnicas
pueden resultar desafiantes o incluso frustrantes. Pero yendo paso a
paso y animandose a consultar y pedir ayuda al grupo de pares que está
involucrado en este proyecto, en breve serán expertos y estarán
ayudando a otras personas.

<div id="ghUsername-intro">

A continuación vamos a hacer algunas tareas propias de
GitHub. Esperamos que no les importe decirnos su nombre de usuario,
así podemos preparar algunos links y hacer las cosas mucho más
sencillas. No se preocupen, no se guarda ninguna información sobre
ustedes en los servidores. Si tienen deshabilitado JavaScript por
algún motivo, tendrán que remplazar 'your-github-username' con su
nombre de usuario de GitHub cada vez que vean links que digan
'your-github-username' </div>

[your-github-username](https://github.com/your-github-username-set/planificaciones-para-armar/)

### Retocar algunas partes.

Hay dos actualizciones que necesitan hacer a su nuevo sitio para que empiece a funcionar. Primero cambien

{% highlight yaml %}baseurl:{% endhighlight %}

a

{% highlight yaml %}baseurl: /planificaciones-para armar{% endhighlight %}

en este archivo [https://github.com/your-github-username/planificaciones-para-armar/blob/gh-pages/_config.yml](https://github.com/your-github-username/planificaciones-para-armar/blob/gh-pages/_config.yml)

<!--Luego, borrar un archivo llamado CNAME [https://github.com/your-github-username/planificaciones-para-armar/blob/gh-pages/CNAME](https://github.com/your-github-username/planificaciones-para-armar/blob/gh-pages/CNAME)-->


Ahora que tienen un espacio para trabajo, pongamos la estructura borrador a punto para la sus planificaciones.

### Cambiar el  nombre a su plataforma.

Para cambiar el título de sus plataforma, vayan a [https://github.com/your-github-username/planificaciones-para-armar/blog/gh-pages/_data/course.yml](https://github.com/your-github-username/planificaciones-para-armar/edit/gh-pages/_data/course.yml) y editen el archivo llamado `_data/course.yml`. Verán ahí el título de esta plataforma, cambienlo al nombre que prefieran. No se preocupen si no tienen el nombre perfecto, ahora ya saben dónde y cómo cambiarlo y pueden hacerlo ¡Todas las veces que quieran!

{% highlight yaml %}title: "Tiítulo de la plataforma"{% endhighlight %}

### ¿De quién es la plataforma y qué harán en ella?

¿Es de una Institución? ¿de uno o varios docentes?. Pongan la información básica en la página principal de la plataforma para que haya un breve resumen del sitio. Para modificar la información en la página principal, vayan a la página [https://github.com/your-github-username/planificaciones-para-armar/blob/gh-pages/index.markdown](https://github.com/your-github-username/planificaciones-para-armar/blob/gh-pages/index.markdown) y remplacen el texto que está ahí de manera que refleje de sus expectativas. De nuevo, sepan que pueden modificar este texto en cualquier momento, de todas maneras, volveremos a esto más adelante.

### ¡Echemos un vistazo al sitio!

Pueden ver como va quedando en  [https://your-github-username.github.io/planificaciones-para-armar/](https://your-github-username.github.io/planificaciones-para-armar/).
