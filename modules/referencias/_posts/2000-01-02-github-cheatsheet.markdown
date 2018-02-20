---
title: Machete para GitHub
published: false
---

# Machete para Github

Este machete explica como hacer varias cosas en Hithub. Si buscan explicaciones sobre alguno de los terminos que usamos, chequeen el [Glosario de GitHub](https://help.github.com/articles/github-glossary) que lamentablemente está en inglés aun.

## Cómo forkear un repositorio

Para forkear un repositorio, vayan al repositorio que quieran forkear. Ej: "https://github.com/yourusername/repositoryname/"

Hagan click en "Fork" arriba a la derecha de la página. ¡Eso es todo! Ahora tienen su propia copia del repositorio ^_^.

![]({{site.baseurl}}/img/tools/github-fork-step-1.png)

## Cómo mandar un pull request

Para mandar un pull request, vayan al repositorio que forkearon. Ej: "https://github.com/yourusername/repositoryname/"

Selecionen la pestaña "Pull Requests".

![]({{site.baseurl}}/img/tools/github-pull-request-step-1-small.png)

Click en "New pull request".

![]({{site.baseurl}}/img/tools/github-pull-request-step-2-small.png)

Fijense se los cambios que se muestran son los correctos y hafan click en "Create pull request".

![]({{site.baseurl}}/img/tools/github-pull-request-step-3-small.png)

Ponganle un título al pull request y hagan click en "Create".


![]({{site.baseurl}}/img/tools/github-pull-request-step-4-small.png)

Listo, ya hicieron el pull request y se verá de la siguiente forma:

![]({{site.baseurl}}/img/tools/github-pull-request-step-5-small.png)

Pueden hacer click en la pestaña "files changed" para ver los cambios que hicieron.

![]({{site.baseurl}}/img/tools/github-pull-request-step-6-small.png)

## Cómo editar un archivo

Vayan a su repositorio

...

## How to upload an image

## How to keep your fork up-to-date
You just forked this awesome project but it got more awesome... what do you do?

### Through GitHub
> Note:  This is assuming none of the updates made to the main repository conflict with changes you have made to yours.  Conflicts can make things a bit trickier but hopefully this is useful in most situations.

Go to your repository on GitHub and click the green Pull Request button.

 ![]({{site.baseurl}}/img/tools/github-upstream-step-1.png)

If you haven't made any updates to your repository it will tell you there is nothing to compare.  Click 'switching the base' and jump past the next couple steps to 'Create pull request.'  If you have made updates to your repository click the 'Edit' button.

 ![]({{site.baseurl}}/img/tools/github-upstream-step-2.png)

Change the base fork to your repository

  ![]({{site.baseurl}}/img/tools/github-upstream-step-2-1.png)

It will tell you that there isn't anything to compare (Which is true! You are comparing your respository to itself!).

Click 'Edit' again and click 'compare across forks.'

  ![]({{site.baseurl}}/img/tools/github-upstream-step-2-2.png)

Change the head fork to main respository (p2pu in this case).

  ![]({{site.baseurl}}/img/tools/github-upstream-step-2-3.png)

Click 'Create pull request.'

 ![]({{site.baseurl}}/img/tools/github-upstream-step-3.png)

Fill out your merge request that will be submitted to yourself.

 ![]({{site.baseurl}}/img/tools/github-upstream-step-4.png)

Go to the bottom of the page and click 'Merge pull request.'

 ![]({{site.baseurl}}/img/tools/github-upstream-step-5.png)

Click 'Confirm merge.'

 ![]({{site.baseurl}}/img/tools/github-upstream-step-6.png)

That's it!  

### Through Git
> Note: This can only be done using git directly and cannot be done through the GitHub website

1. Open a terminal (for Mac and Linux users) or command line (for Windows users).

1. Add a new remote that points to the original repository.

        git remote add upstream https://github.com/p2pu/course-in-a-box.git

1. Update your repository so it knows about all the stuff that has been going on since you forked.

        git fetch upstream

1. Merge the changes from the upstream repository into yours.  This will bring your repository up-to-date without losing any of your local changes.

        git merge upstream/gh-pages

1. Push the changes up to your repository on GitHub.

        git push origin gh-pages

## How to create a new repository
