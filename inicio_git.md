# Inicio con Git

## Estado actual

Este proyecto está conectado con el repositorio remoto de GitHub:

```text
https://github.com/JimLee93/Angular-Formacion.git
```

La rama principal utilizada es `main` y el remoto se llama `origin`.

## Crear el repositorio local

Desde la carpeta del proyecto:

```powershell
cd "C:\Users\jilparedes\OneDrive - Sopra Steria\Documentos\Projects\Frontend"

git init
git branch -M main
```

Configurar la identidad de Git para este proyecto:

```powershell
git config user.name "JimLee93"
git config user.email "tu-email-de-github"
```

Comprobar el estado local:

```powershell
git status
```

## Guardar cambios localmente

Añadir los archivos al area de preparacion:

```powershell
git add .
```

Revisar los archivos preparados:

```powershell
git status
```

Crear un commit:

```powershell
git commit -m "Describe los cambios"
```

Un commit es una version guardada localmente del proyecto.

## Conectar con GitHub

Configurar el repositorio remoto:

```powershell
git remote add origin https://github.com/JimLee93/Angular-Formacion.git
```

Comprobar la conexion:

```powershell
git remote -v
```

## Subir el proyecto

La primera vez se sube la rama `main` con:

```powershell
git push -u origin main
```

GitHub puede solicitar el nombre de usuario y un token personal. El token se utiliza como contraseña y no debe guardarse en archivos del proyecto ni compartirse.

## Flujo habitual para futuros cambios

Antes de empezar a trabajar, descargar los cambios remotos:

```powershell
git pull
```

Despues de modificar el proyecto:

```powershell
git status
git add .
git commit -m "Describe el cambio realizado"
git push
```

Ejemplo:

```powershell
git add .
git commit -m "Añade ejercicios de componentes Angular"
git push
```

## Archivos que no deben subirse

Las dependencias y archivos generados deben estar excluidos mediante `.gitignore`:

```text
node_modules/
dist/
.angular/
coverage/
```

## Estado de este proyecto

`00-HTML` y `01-BASES` forman parte del mismo repositorio. `01-BASES` se guarda como una carpeta normal, no como un submodulo.
