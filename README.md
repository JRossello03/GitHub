<img src="https://www.trecebits.com/wp-content/uploads/2019/11/GITHUB.jpg" align="left" width="auto" height="100px"/>

# Integrado con GitHub

<br>

## **Subir proyecto a la nube de GitHub**

`git init`
`git add .` // `git add <archivo>`
`git commit -m "Ejemplo Commit"`
`git remote add origin https://github.com/JRossello03/Integrat-amb-Github.git`
`git push -u origin master`

## **Importar proyecto de GitHub**

### Clonar un repositorio al directorio en el que nos encontramos

`git clone https://github.com/aschmelyun/docker-compose-laravel.git`

### Clonar un repsositorio a una carpeta especifica

`git clone https://github.com/aschmelyun/docker-compose-laravel.git ./path/www/exemple-app`

## **Actualizar los archivos de un proyecto**

`git add <nombre-de-los-archivos-que-queremos-actualizar>`

`git commit -m "Ejemplo Commit Mejorado"`

`git push -u origin master`

## **Ver el estado de un repositorio**

`git status`