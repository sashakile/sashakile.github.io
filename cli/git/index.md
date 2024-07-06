.. title: git
.. slug: git
.. date: 2023-10-29 14:07:04 UTC-03:00
.. tags: cli git
.. category: cli 
.. link: 
.. description: 
.. type: text


### Clonar un repositorio

```bash
git clone url_repositorio
```

### Crear una nueva *branch*

```bash
git switch --create nueva_brach
```

### Cambiar de *branch*

```bash
git switch otra_branch
```

### Actualizar repositorio local

```bash
git fetch --all --prune
```

### *Mergear* una *branch*

```bash
git merge repo/branch
```

#### Actualizar *branch* actual con último *master|main*

```bash
git fetch --all --prune; git merge origin/master
```

### Crear otro árbol de trabajo *worktree*

```bash
git worktree add -b nueva_branch commit ../path
```

### Listar *worktrees*

```bash
git worktree list
```

## Materiales extras

Julia Evans [How Git Works!](https://jvns.ca/blog/2024/04/25/new-zine--how-git-works-/) [Popular git config options](https://jvns.ca/blog/2024/02/16/popular-git-config-options/)

Nina Zakharenko [Advanced Git In-Depth](https://github.com/nnja/advanced-git/blob/master/presentation/slides.pdf)

Mark Dominus [Things I wish everyone knew about Git](https://blog.plover.com/2022/06/29/)

John Wiegley [Git from the Bottom Up](https://jwiegley.github.io/git-from-the-bottom-up/)