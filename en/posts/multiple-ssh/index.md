<!--
.. title: Configurar multiples usuarios de git con ssh
.. slug: multiple-ssh
.. date: 2024-04-21 12:21:09 UTC-03:00
.. tags: 
.. category: 
.. link: 
.. description: 
.. type: text
-->

Un problema con el que me encontre es tener distintos repositorios privados que necesitan autenticarse con distintas cuentas para poder pushear.

Una primera opción fue intentar usar el github cli (`gh`) pero requeria reautenticarse constantemente.

La alternativa fue clonar los distintos repositorios por ssh y configurar distintos hosts para cada autenticación.

Para definir los distintos hosts con sus alias hay que modificar `~/.ssh/config`

```powershell
PS❯ get-content "~\.ssh\config"
# account2
Host acc2
    HostName github.com
    User user2
    IdentityFile ~/.ssh/id_rsa2

# account1
Host acc1
    HostName github.com
    User user1
    IdentityFile ~/.ssh/id_rsa1
```

Después en cada repositorio hay que actualizar los url a donde apuntan

```pwsh
❯ git remote -v
origin  https://github.com/SomeUser/repo.git (fetch)
origin  https://github.com/SomeUser/repo.git (push)
```

Este es el formato que hay que usar para el url `git@hostname:CuentaGH/repo.git`

```pwsh
git remote set-url origin git@acc1:SomeUser/repo.git
```

```pwsh
git remote set-url origin git@acc2:SomeOtherUser/other-repo.git
```
