---
title: Generación  de contenido
---

## ¡Hagámos algunos módulos!

¡Ahora es momento de empezar a construir su sitio!


1. En sus repositorios en GitHub, creen un directorio para cada módulo dentro de la carpeta `modules`. El nombre de la carpeta se reflejará en la dirección de sus sitios. Si se fijan en la dirección de este sitio, verán que la primer parte de la URL es 'modules/inicio' ese es también el nombre [de la carpeta en el repositorio en GitHub](https://github.com/acercadelaeducacion/planificaciones-para-armar/tree/gh-pages/modules/inicio/).
2. Dentro de cada carpeta que creen, creen otra carpeta con el nombre `_posts`. Esta será la carpeta que contendrá el contenido de su sitio. Cada módulo puede tener multiples secciones.
3. 
1. Create a new file called `2000-01-01-projects.md` inside the `_posts` folder for the module you just created. The date part determines the order of the sections in the module. For instance, you can see all the sections for the learning module [here](https://github.com/p2pu/course-in-a-box/tree/gh-pages/modules/learning/_posts).

If you don't want to create all the folders yourself, rename or copy one of the folders that are already there (start, community, learning, content) and update the sections appropriately.

For modules to show up in the top navigation, you need to update the list modules in [https://github.com/your-github-username/course-in-a-box/blob/gh-pages/_data/course.yml](https://github.com/your-github-username/course-in-a-box/blob/gh-pages/_data/course.yml).

Update the list of modules to reflect the modules for your course:

{% highlight yaml %}
modules: [start, community, learning, content, feedback, references]
{% endhighlight %}

The video below shows all the steps for adding a module called 'variables' to a course.

<video src="{{site.baseurl}}/img/add-module.webm" width="640" height="360" controls></video>
