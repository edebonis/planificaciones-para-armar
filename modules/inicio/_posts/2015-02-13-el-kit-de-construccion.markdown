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


Ahora sí, arrancamos:

1. <a class="btn btn-primary" href="https://github.com/acercadelaeducacion/planificaciones-para-armar/fork" target="_blank"><i class="fa fa-code-fork"></i> Forkeen este repositorio en GitHub.</a></li> El primer paso para tener la estructura de la planificación es ir a forkear el repositorio. Si todavía no saben bien qué es un repositorio o cómo funciona, echen un vistazo al <a href="https://help.github.com/articles/github-glossary" >glosario de GitHub</a> ojo, está en inglés. también pueden chequear <a href="http://www.yagoperez.com/un_poco_de_git_y_de_github%E2%80%8E/">otro glosario de Git + Github</a> que está en castellano. 
2. Then, in the repository interface, find the file called <a class="btn btn-primary" href="https://github.com/p2pu/course-in-a-box/edit/gh-pages/_data/course.yml" target="_blank"><i class="fa fa-edit"></i> Edit _data/course.yml</a> and add your name, profile image and Twitter handle.
3. Submit a pull request to get your changes merged into the main version of the course and have your mug show up in the gallery on the front page! Not sure how to submit a pull request? See the <a href="{{site.baseurl}}{% post_url 2000-01-02-github-cheatsheet %}">GitHub Cheatsheet</a>.
4. <a class="btn btn-primary" target="_blank" href="https://twitter.com/intent/tweet?url=http%3A%2F%2Fhowto.p2pu.org&text=Create%20engaged%20learning%20communities%20that%20lasts&hashtags=courseinabox&via=p2pu&related=p2pu"><i class="fa fa-twitter"></i> Send a tweet</a> and spread the word about Course in a Box! (Not actually a required step, promise).
5. <a class="btn btn-primary" target="_blank" href="http://community.p2pu.org/t/please-introduce-yourself/28"><i class="fa fa-weixin"></i> Introduce yourself</a> to the P2PU community. Tell us something about yourself and what you want to use Course in a Box for.



## Pasos para armar su propio curso



Si todavía no está claro qué es un repositorio, o cómo funciona echenle un vistazo a:

- <a href="http://www.yagoperez.com/un_poco_de_git_y_de_github%E2%80%8E/">Glosario de Git + Github</a>
- <a href="https://help.github.com/articles/github-glossary" >Glosario de GitHub</a> En inglés.
- <a href="http://aprendegit.com/fork-de-repositorios-para-que-sirve/">Qué es un fork</a>

### Forkear este curso
Este kit está construido usando las [Páginas de GitHub](https://pages.github.com/), para hacer una copia de este curso, necesitan *forkear*, hacer una copia o bifurcación del repositorio en GitHub.
Pueden hacer esto haciendo click en el link de acá abajo. Es probable que tengan que loguearse o crear una cuenta en GitHub.

<a class="btn btn-primary" href="https://github.com/acercadelaeducacion/planificaciones-para-armar/fork" target="_blank"><i class="fa fa-code-fork"></i> Forkear esta planificación</a>

Esta copia es en la que trabajaran de ahora en adelante. Algunas de las cuestiones técnicas pueden representar desafíos o resultar frustrantes. Pero abordandolas paso a paso, consultando y pidiendo ayuda a sus pares, pronto se convertiran en expertos/as y estaran ayudando a otras personas.


### Ajustar de algunos elementos de la páginas

Hay dos actualizaciones o modificaciones que tienen que hacerle al curso para tenerlo en funcionamiento. Primero cambien

{% highlight yaml %}baseurl:{% endhighlight %}

a

{% highlight yaml %}baseurl: /planificacion-para-armar{% endhighlight %}

en el archivo [https://github.com/your-github-username/planificacion-para-armar/blob/gh-pages/_config.yml](https://github.com/your-github-username/planificacion-para-armar/blob/gh-pages/_config.yml)

Luego, borren el archivo llamado CNAME [https://github.com/your-github-username/planificacion-para-armar/blob/gh-pages/CNAME](https://github.com/your-github-username/planificacion-para-armar/blob/gh-pages/CNAME)

Ahora que tienen un espacio de trabajo, hagamos un borrador de la planificación.

### Dar a la planificación un nombre

Para modificar el título de la planificación, vayan a
[https://github.com/your-github-username/planificacion-para-armar/](https://github.com/planificacion-para-armar/course-in-a-box/edit/gh-pages/_data/course.yml) y editen el archivo llamado `_data/course.yml`. Verán el título de este curso ahí, cambienlo al nombre que quieran para su curso. No se preocupen demasiado si no tienen el nombre perfecto. Ahora que ya saben como cambiar el título de su curso pueden hacerlo en cualquier momento.

{% highlight yaml %}title: "Course Title"{% endhighlight %}

<!--
### Who is the course for & what will they learn?
Will they be building something during the course. Put this basic information on the front page of the course to give a short overview of what to expect. To update the info on the front page, go to the file [https://github.com/your-github-username/course-in-a-box/blob/gh-pages/index.markdown](https://github.com/your-github-username/course-in-a-box/blob/gh-pages/index.markdown) and replace the text currently there to reflect what your course will be about. Once again, you can update it at any time and we will come back to this at a later stage.
-->
### ¿Para quién es el curso y que aprenderán en él?
¿Contruirán algo durante el curso?. Pongan la información básica en la página que incio del curso para que tengan un vestazo de lo que harán. Para actualizar la información en la *página de inicio*, vayan al archivo  [https://github.com/your-github-username/course-in-a-box/blob/gh-pages/index.markdown](https://github.com/your-github-username/course-in-a-box/blob/gh-pages/index.markdown) y remplacen el texto actual a uno que refleje de qué se tratara su curso. Como se dijo anteriormente, pueden cambiar esto en cualquier momento, más adelante volveremos más adelante volveremos sobre este tema.

<!--
### Lets have a look at your course!

You can view it by going to [https://your-github-username.github.io/course-in-a-box/](https://your-github-username.github.io/course-in-a-box/), just replace your-github-username with your GitHub username.
-->
### ¡Veamos cómo va quedando el curso!
Pueden verlo yendo a [https://your-github-username.github.io/course-in-a-box/](https://your-github-username.github.io/course-in-a-box/), solo remplacen *your-github-username* con el nombre de usuario de GitHub. 

<!--
## Resources and Help

- See our <a href="{{site.baseurl}}{% post_url 2000-01-02-github-cheatsheet %}">GitHub Cheatsheet</a> if you get stuck with any git related things. 
- Ask a question on the [P2PU community forum](http://community.p2pu.org/category/tech).

You may have noticed that the [https://github.com/your-github-username/course-in-a-box/blob/gh-pages/index.markdown](https://github.com/your-github-username/course-in-a-box/blob/gh-pages/index.markdown) file contained a few funny caracters. This is called [Markdown](https://en.wikipedia.org/wiki/Markdown), an easy way of writing files for the web. For some tips on how to get the most out of Markdown, see [our Markdown cheetsheet]({{site.baseurl}}/references/markdown-cheatsheet/).
 
**Possible error: pages not displayed.** You can get an email after forking the repository with the following message: "The page build failed with the following error: Page build failed". To solve this issue, check you have [enabled the automatic page generator](https://help.github.com/articles/creating-pages-with-the-automatic-generator) on your repository. Another possible cause would be a missing whitespace in your newly added content. Double check it and commit again to trigger page generation.
-->
## Recursos y ayudas
- Chequeen nuestro <a href="{{site.baseurl}}{% post_url 2000-01-02-github-cheatsheet %}">Machete de GitHub</a> si se quedan trabadxs con cualquier cosa relacionada a git. 
- Pregunten en el [foro de la comunidad P2PU](http://community.p2pu.org/category/tech).
- Se habran dado cuenta que el archivo [https://github.com/your-github-username/course-in-a-box/blob/gh-pages/index.markdown](https://github.com/your-github-username/course-in-a-box/blob/gh-pages/index.markdown) contiene algunos caracteres raros. Esto se llama [Markdown](https://es.wikipedia.org/wiki/Markdown), una forma sencilla de escribir paginas en la  web. Para tener algunos tips sobre como sacar el mejor provecho de Markdown vean [nuestro machete de Markdown]({{site.baseurl}}/references/markdown-cheatsheet/).
 
**Posibles errores: pages not displayed.** Puede ser que les llegue un mail despues de forkear el repositorio con el siguiente mensaje en inglése: "The page build failed with the following error: Page build failed". Para resolver este problema, chequeen que tienen habilitado el generador de páginas automáticas en inglés:  ["automatic page generator"](https://help.github.com/articles/creating-pages-with-the-automatic-generator) en su repositorio. Otra posible causa de este es que falte un espacio en blanco en los contenidos nuevos que agregaron. Chequeen nuevamente si cuando cambiaron el títlulo de la página o la descripsión dejaron un espacio en blanco entre los **":"** y su nuevo contenido.
