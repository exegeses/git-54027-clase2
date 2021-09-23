# Listado de comandos

## crear un repositorio
    git init  
> Este comando crear un repositorio en el directorio donde estamos situados

## saber estado de cambios
    git status  
> Este comando te informa qué archivos estan sin seguimiento, 
> qué archivos estan con seguimiento (en el Staging area), 
> y si ya todos los archivos estan con puntos de restauración  
> En rojo: sin seguimiento  
> En verde: en el Staging area  

## crear punto de restauración
    git commit -m 'mensaje'

## agregar a staging area y crear punto de restauración en un sólo comando
    git commit -a -m 'mensaje'
 