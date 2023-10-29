<!--
.. title: git
.. slug: git
.. date: 2023-10-29 14:07:04 UTC-03:00
.. tags: cli
.. category: cli 
.. link: 
.. description: 
.. type: text
-->

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