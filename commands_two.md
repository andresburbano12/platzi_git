# GIT Y GITHUB

## Comandos para la configuracon de GIT

```
$ git reset HEAD
$ git reset <sha> --soft
$ git reset <sha> --hard
```

Comando | Descripción
-------- | ------------
git reset HEAD |  Saca del stage area los cambios realizados y estos archivos quedan a espera de ser adicinados
git reset <sha> --soft| Saca los cambios del repositorie directory y los pasa al stage area y elimina el commits realizados  
git reset <sha> --hard | Este comando elimina todos los cambios realizados 

### Preguntas 
* ¿ Cual es la diferencia entre git reset HEAD, git reset <sha> --soft y git reset <sha> --hard ?

## Comandos para ir a versiones anteriores

```
$ git checkout <sha> <name_file>
```
Comando | Descripción
-------- | ------------
git checkout <sha> <name_file> | Este commando devuelve a la version anterior que se desee. volviendo todos los archivos al stage area