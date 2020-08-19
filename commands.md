# GIT Y GITHUB

## Comandos para la configuracon de GIT

```
$ git config --list
$ git config --global user.name
$ git config --global user.email
```

Comando | Descripción
-------- | ------------
git config --list | Este comando lista todos las diferentes configuraciones de nuestro GIT
git config --global user.name "Name" | Utiliza para configura el nombre del autor a nivel global 
$ git config --global user.email "email" | Se ultiliza para configura el correo del autor a nivel global

## Comandos basicos 

```
$ git init
$ git add <name_file>
$ git commit -m 'mensaje'
```
Comando | Descripción
-------- | ------------
$ git init | Inicialeza el repositorio a nivel local
$ git add <name_file> | Adiciona el archivo a el stage area 
$ git commit -m 'mensaje' | Crea un snapshot del proyecto creando una nueva version

### Preguntas
* ¿ Que pasa cuando se ejecuta ```git init```?
* ¿ Que pasa cuando se ejecuta ```git add . ``` ?

## Comandos visualizar diferencias

```
$ git show <commit + reciente> <commit - reciente> <name_file>
$ git diff 
$ git diff <commit + reciente> <commit - reciente> <name_file>
```

Comando | Descripción
-------- | ------------
$ git show <commit + reciente> <commit - reciente> <name_file> | Muestra diferencia entre el primer commit y el segundo commit 
$ git diff | Compara los cambios de los archivos del staging area con respecto a el ultimo commit realizado
$ git diff <commit + reciente> <commit - reciente> <name_file> | Muestra diferencia entre el primer commit y el segundo commit

### Preguntas
* ¿ Que hace el comando ```git diff```?

