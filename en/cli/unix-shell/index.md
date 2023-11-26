<!--
.. title: unix shell
.. slug: unix-shell
.. date: 2023-11-26 14:03:28 UTC-03:00
.. tags: cli, unix
.. category: 
.. link: 
.. description: 
.. type: text
-->

### Obtener ayuda de un comando

```sh
man comando
```

### Ejecutar un comando en segundo plano (**background**)

```sh
comando &
```

Además, no mostrar la salida, enviandola a un archivo

```sh
comando &>/algun/archivo &
```

O descartar la salida

```sh
comando &>/dev/null &
```

### Regresar un proceso secundario a principal

```sh
fg <id>
```

El `id` se puede ver con

```sh
jobs
```

### Agregar un usuario

```sh
sudo adduser <nuevo_usuario>
```

Con permisos de administrador

```sh
sudo adduser <nuevo_usuario> sudo
```

#### Cambiar de usuario

```sh
su -- <otro_usuario>
```

#### Agregar permisos de administrador a usuario

```sh
sudo usermod -a -G sudo <usuario>
```

#### Cambiar la contraseña de un usuario

```sh
sudo passwd <usuario>
```
