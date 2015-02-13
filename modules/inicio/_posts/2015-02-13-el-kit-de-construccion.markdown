---
title: Kit de construcción
published: true
---

## Ensamblar del kit de construcción

¡Durante esta etapa aprenderán las partes técnicas y teóricas a traves de la construcción de sus propias planificaciones en línea!


Van a construir sus propias planificaciones en GitHub. Github es una plataforma de desarrollo colaborativo de software que permite el alojamiento de proyectos, código y documentación usando el sistema de control de versiones Git y además nos permite crear y mantener páginas web.
Un repositorio es un lugar donde alojar datos, que posibilita adminstrar nuestro código (a partir de ahora todo es código, el contenido de las planificaciones como la estructura misma de las páginas), y ver las revisones y modificaciones que le hacemos a través de una interfaz web bonita y sencilla de usar.

La funcionalidad estrella de Github es el "forkeo" esta palabra castellanizada proviene del inglés "forking" que vendría a ser "ramificar". Algunos términos quedarán en inglés, otros seran "castellanizados". Pero en cualquier caso se van a ir aclarando en el proceso.
Entonces, forkear es copiar el repositorio de un usaurio en la cuenta de otro usuario. Esto es lo que harán con este mismo repositorio de contenido. Al forkear este repositorio estarán copiando la Planificación Para Armar de nuestro repositorio, y lo modificarán en su propia cuenta para luego publicarlo con su propia dirección web.

Sus planificaciones viviran en Github (así que no habrá que preocuparse del hosting) y harán todo el proceso de construcción y escritura ahí, al mismo timpo podrán ver las modificaciones en su propia página web.

Si no están registrados en GitHub van a tener que crearse una cuenta para poder comenzar.  <a class="btn btn-primary" href="https://github.com/join" target="_blank"><i class="fa fa-code-fork"></i>Crear una cuenta en GitHub</a>

Ahora sí, arrancamos:

1. <a class="btn btn-primary" href="https://github.com/acercadelaeducacion/planificaciones-para-armar/fork" target="_blank"><i class="fa fa-code-fork"></i> Forkeen este repositorio en GitHub.</a></li> El primer paso para tener la estructura de la planificación es ir a forkear el repositorio. Si todavía no saben bien qué es un repositorio o cómo funciona, echen un vistazo al <a href="https://help.github.com/articles/github-glossary" >glosario de GitHub</a> ojo, está en inglés. también pueden chequear <a href="http://www.yagoperez.com/un_poco_de_git_y_de_github%E2%80%8E/">otro glosario de Git + Github</a> que está en castellano. 
2. Luego, en la interface del repositorio, busquen el archivo llamado <a class="btn btn-primary" href="https://github.com/acercadelaeducacion/planificaciones-para-armar/edit/gh-pages/_data/course.yml" target="_blank"><i class="fa fa-edit"></i>_data/course.yml y edítenlo</a> agregando su nombre, imgen de perfil y su usuario de Twitter.
3. Hagan un **pull request** para que los cambios se agreguen a la versión principal del curso y aparezca su imagen en la galería de la primer página. Si no están muy segurxs de como hacer un **pull request** vean el <a href="{{site.baseurl}}{% post_url 2000-01-02-github-cheatsheet %}">Machete de GitHub</a>.
4. <a class="btn btn-primary" target="_blank" href="https://twitter.com/intent/tweet?url=http%3A%2F%2Fhowto.p2pu.org&text=Crear%20planificaciones%20online%20y%20participar%20de%20comunidades%20de%20Prácticas&hashtags=planificacionesparaarmar&via=p2pu&related=p2pu&via=amaciel&related=amaciel"><i class="fa fa-twitter"></i> Manden un tweet</a> y corran la voz sobre planificaciones para armar! (No es un paso obligatorio, :D  pero ayuda).
5. <a class="btn btn-primary" target="_blank" href="http://community.p2pu.org/t/please-introduce-yourself/28"><i class="fa fa-weixin"></i> presentense</a> en la comunidad de P2PU. Cuenten algo sobre ustedes y para que quieren usar las planificaciones para armar.

Cuando les pedimos que forkeen este sitio, lo que hicieron fue hacer una copia del mismo y ¡ya comenzaron a construir el de ustedes!

This copy is where you will be working during the course. Some of the technical things may be challenging or frustrating, but by tackling it bit by bit and asking your peers for help, you’ll soon be an expert and helping other people!

<div id="ghUsername-intro">
Below we will be doing some proper work on GitHub. We hope you won't mind telling us your username, so we can prepare some links and make things much easier for you. Don't worry, we are not storing any information about you on our servers. If you have JavaScript disabled for some reason, you will need to replace 'your-github-username' with your GitHub username where you see links containing 'your-github-username'
</div>

[your-github-username](https://github.com/your-github-username-set/course-in-a-box/)

### Tweak a few items.
There are two updates that you need to make to your course to get it working. First, change

{% highlight yaml %}baseurl:{% endhighlight %}

to

{% highlight yaml %}baseurl: /course-in-a-box{% endhighlight %}

in the file [https://github.com/your-github-username/course-in-a-box/blob/gh-pages/_config.yml](https://github.com/your-github-username/course-in-a-box/blob/gh-pages/_config.yml)

Next, delete the file called CNAME [https://github.com/your-github-username/course-in-a-box/blob/gh-pages/CNAME](https://github.com/your-github-username/course-in-a-box/blob/gh-pages/CNAME)

Now that you have a space to work, lets put a draft framework in place for your course.

### Give your course a name.
To update the title of your course, go to [https://github.com/your-github-username/course-in-a-box/blog/gh-pages/_data/course.yml](https://github.com/your-github-username/course-in-a-box/edit/gh-pages/_data/course.yml) and edit the file called `_data/course.yml`. You will see the title for this course there, change that to the name you decided on. Don't worry too much if you don't have the perfect name, you now know how to change the title for your course and you can update it at any time!

{% highlight yaml %}title: "Course Title"{% endhighlight %}

### Who is the course for & what will they learn?
Will they be building something during the course. Put this basic information on the front page of the course to give a short overview of what to expect. To update the info on the front page, go to the file [https://github.com/your-github-username/course-in-a-box/blob/gh-pages/index.markdown](https://github.com/your-github-username/course-in-a-box/blob/gh-pages/index.markdown) and replace the text currently there to reflect what your course will be about. Once again, you can update it at any time and we will come back to this at a later stage.

### Lets have a look at your course!

You can view it by going to [https://your-github-username.github.io/course-in-a-box/](https://your-github-username.github.io/course-in-a-box/).
