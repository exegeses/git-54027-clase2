# Referencia de comandos clase 3

## Clonar un repo
    git clone URL  
> Este comento clona un repo remoto en un directorio local.  
> Le pone el nombre del repo remoto.  

    git clone URL nobre  
> Este comento clona un repo remoto en un directorio local.  
> Lo ponel el nombre que especifiquemos

## Publicar repositorio local
    git push

> Mi rama local debe estar más adelante que la rama remota
> Si esto no sucede, primero hacer un pull  
    git pull  
> y después un push

##  tags 

    git tag v1.0 -m 'Versión 1 del proyecto 30/09/2021' 
> Este comando crea un tag y le pone un mensaje

> si queremos ver listadod e tags
    git tag

> si queremos publicar los tags 
    git push --tags

