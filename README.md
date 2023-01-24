# Práctica primeiro repo en GitHub

## Comandos empregados:

```bash
git init
```

>Inicialización do repositorio local.

```bash
git clone [url]
```
>Sirve para clonar un reporsitorio remoto a local

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
git push -u origin main
```

>Añadimos los cambios locales al repositonio en línea

```bash
git remote remove origin
```

>Eliminamos el origen remoto de un repositorio

```bash
git log
```

>Mostramos el historial de cambios del repositorio

```bash
git diff
```

>Mostramos las diferencias entre versiones

```bash
git annotate
```

>Mostramos quién ha hecho los cambios sobre el fichero

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

