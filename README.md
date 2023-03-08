# Práctica comandos Git en GitHub

## Comandos iniciales:

```bash
git config --global user.name "nombre"
```
```bash
git config --global user.email "nombre@ejemplo.com"
```
>Configuración de nombre de usuario y email.

```bash
git config --list
```
>Muestra la configuración de git

```bash
git init
```
>Inicialización do repositorio local.

```bash
git add .
```
>Añadimos los cambios a la rama en la que nos encontramos

```bash
git commit -m ""
```
>Confirmamos los cambios con un commit y añadimos un comentario sobre esos cambios

```bash
git commit -amend -m ""
```
>Modificamos el commit anterior modificando su comentario

```bash
git push -u origin main
```
>Añadimos los cambios locales al repositonio en línea

## Comandos para trabajar en remoto:

```bash
git remote remove origin
```
>Eliminamos el origen remoto de un repositorio

```bash
git remote add github [Url]
```
>Añadimos un repositorio de github a local

```bash
git remote -v
```
>Muestra los repositorios remotos

```bash
git fetch
```
>Descarga un repositorio remoto con sus actualizaciones sin incluirlo al repositorio local

```bash
git pull
```
>Descarga un repositorio remoto con sus actualizaciones incluyéndolo al repositorio local. Se dice que git pull es equivalente a hacer git fetch seguido de un git merge.

```bash
git clone [url]
```
>Sirve para clonar un reporsitorio remoto a local

## Comandos para mostrar diferencias, cambios y estado del repositorio:

```bash
git status
```
>Muestra el estado del repositorio

```bash
git log
```
>Mostramos el historial de cambios del repositorio

```bash
git diff
```
>Mostramos las diferencias entre la última version y el repositorio local

```bash
git show
```
>Mostramos las diferencias entre diferentes commits

```bash
git annotate
```
>Mostramos quién ha hecho los cambios sobre el fichero

## Comandos para deshacer cambios en el repositorio:

```bash
git checkout --nombreFichero
```
>Deshacer cambios para volver a la versión anterior de un fichero

```bash
git restore
```
>Deshacer cambios en el directorio de trabajo

```bash
git restore --stage <file>
```
>Deshacer cambios guardados en el stage. Eliminamos el add.

```bash
git reset HEAD~
```
>Deshacer cambios del último commit y del stage

```bash
git reset --hard HEAD~
```
>Volvemos desde el HEAD actual al commit que especificamos

```bash
git reset --soft HEAD~
```
>Deshacemos el último commit

## Comandos para trabajar con ramas:

```bash
git branch
```
>Muestra el nombre de la rama en la que nos encontramos

```bash
git branch -av
```
>Muestra todas las ramas del repositorio

```bash
git branch nombreNuevaRama
```
>Crea una nueva rama

```bash
git checkout
```
>Cambia de rama

```bash
git merge
```
>Fusiona la rama nombrada con la rama donde nos encontramos

```bash
git branch -d
```
>Elimina la rama



