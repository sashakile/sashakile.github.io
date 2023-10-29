<!--
.. title: powershell
.. slug: powershell
.. date: 2023-10-29 14:03:28 UTC-03:00
.. tags: 
.. category: 
.. link: 
.. description: 
.. type: text
-->

### Obtener ayuda

```powershell
Get-Help
```

### Listar contenidos de un directorio

```powershell
Get-ChildItem 
```

### Leer contenido de un archivo

```powershell
Get-Content
```

### Importar / Exportar de formatos de texto

```powershell
ConvertFrom-Csv
ConvertFrom-Json
```

```powershell
ConvertTo-Csv
ConvertTo-Json
```

## 

### Verificar si un archivo existe

```powershell
Test-Path
```

### Crear un nuevo path

```powershell
Join-Path
```

### Obtener *path* del ejecutable de un comando

```powershell
Get-Command
```

### Listar aliases de un comando

```powershell
Get-Alias
```