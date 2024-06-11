<!--
.. title: Peleando con configuraciones en GitHub Pages y Jekyll
.. slug: peleando-con-configuraciones-en-github-pages-y-jekyll
.. date: 2024-01-07 17:26:30 UTC-03:00
.. tags: 
.. category: 
.. link: 
.. description: 
.. type: text
-->

Finalmente me decidí por [reorganizar el blog](link://slug/completando-las-configuraciones-de-nikola) y eso derivó en también cambiar la estructura del repositorio de las presentaciones [akielbowicz/presentations](https://github.com/akielbowicz/presentations).

TL;DR

- Cambiar de 1 branch por charla por una subcarpeta
- Crear un nuevo repositorio para las diapositivas online [akielbowicz/slides](https://github.com/akielbowicz/slides)


```
 Conversion error: Jekyll::Converters::Markdown encountered an error while converting 'presentaciones/pyconar_2021/README.md':
                    The source text contains invalid characters for the used encoding UTF-8
```


[Troubleshooting jekyll build errors...](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/troubleshooting-jekyll-build-errors-for-github-pages-sites)

```bash
apt install autoconf patch build-essential rustc libssl-dev libyaml-dev libreadline6-dev zlib1g-dev libgmp-dev libncurses5-dev libffi-dev libgdbm6 libgdbm-dev libdb-dev uuid-dev
```

`git clone https://github.com/rbenv/rbenv.git ~/.rbenv`

[](https://github.com/rbenv/ruby-build#clone-as-rbenv-plugin-using-git)
`git clone https://github.com/rbenv/ruby-build.git "$(rbenv root)"/plugins/ruby-build`

[](https://jekyllrb.com/docs/)


[](https://talk.jekyllrb.com/t/error-when-executing-bundle-install/8822)

`We’ve detected the file encoding as ISO-8859-1. When you commit changes we will transcode it to UTF-8.`