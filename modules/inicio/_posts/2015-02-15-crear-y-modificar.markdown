---
title: Generación  de contenido
---

## Entendiendo el sitio

Antes de empezar a meter mano, explicaremos un poco como funciona el sitio.

1. Cada sección con contendio de este sitio está dentro de un módulo. Estos módulos se encuentran en la carpeta `modules`
2. Dentro de cada módulo hay una carpeta llamada `_posts`
3. Dentro de esa carpeta están los archivos con las secciones de cada módulo.
El diagrama del módulo `incio` y `fundamentación` es el siguiente:

{% highlight bash %}
.
├── modules
|   ├── inicio
|   |   ├── _posts
|   |       ├── 2015-02-12-propuesta-y-objetivos.markdown
|   |       ├── 2015-02-13-formato-basico.markdown
|   |       ├── 2015-02-14-el-kit-de-construccion.markdown
|   |       ├── 2015-02-15-crear-y-modificar.markdown
|   ├── fundamentación
|   |   ├── _posts
|   |       ├── 2015-02-18-marco-conceptual.markdown
|   |       ├── 2015-02-19-propositos-y-objetivos.markdown
{% endhighlight %}

## Ahora si ¡Hagámos algunos módulos!

Es momento de empezar a construir su sitio.

1. Dentro de sus repositorios en GitHub, tendrán que crear un directorio para cada módulo dentro de la carpeta `modules`. El nombre de la carpeta se reflejará en la dirección de sus sitios. Si se fijan en la dirección de este sitio, verán que la primer parte de la URL es `modules/inicio` ese es también el nombre [de la carpeta en el repositorio en GitHub](https://github.com/acercadelaeducacion/planificaciones-para-armar/tree/gh-pages/modules/inicio/).
2. Dentro de cada carpeta que creen, creen otra carpeta con el nombre `_posts`. Esta será la carpeta que contendrá el contenido de su sitio. Cada módulo puede tener multiples secciones.
3. Dentro de la carpeta `_posts` que recien crearon, creen un archivo nuevo llamdo `2000-01-01-proyectos.md`. La parte de la fecha determina el orden de la sección en el módulo. Por ejemplo, pueden ver todas las secciones del módulo incio [aquí](https://github.com/acercadelaeducacion/planificaciones-para-armar/tree/gh-pages/modules/inicio/_posts)

Si no quieren crear nuevos módulos pueden usar los que están o renombrar los módulos que ya están creados (inicio, enfoques, contenidos, proyecotos, cronogramas, notas, referencias)

Para que se vean los módulos en la barra de navegación, tienen que listarlos en [https://github.com/your-github-username/planificaciones-para-armar/blob/gh-pages/_data/course.yml](https://github.com/your-github-username/planificaciones-para-armar/blob/gh-pages/_data/course.yml).

Actualizen el listado de módulos para que refleje los módulos de sus planificaciones:

{% highlight yaml %}
modules: [inicio, enfoques, contenidos, proyectos, cronogramas, notas, referencias]
{% endhighlight %}

Este video muestra todos los pasos para agregar un módulo llamado 'variabeles' al curso

<video src="{{site.baseurl}}/img/add-module.webm" width="640" height="360" controls></video>
