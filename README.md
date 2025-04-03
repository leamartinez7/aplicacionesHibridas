# Git

## Iniciamos un Repositorio Nuevo
- Configurar el usuario
``` bash
    git config --global user.name "leamartinez7"
    git config --global user.email "leandro.amartinez@davinci.edu.ar"
``` 



- Inicio el repositorio
``` bash
    git init
```

- Agrego lo archivos
``` bash
    git add .
``` 

- Realizo el commit
``` bash
    git commit -m "Semana 02 - Módulos"
``` 

## Vínculamos GitHub con el repositorio local
``` bash
    git remote add origin https://github.com/leamartinez7/aplicacionesHibridas.git
``` 

- Subimos los commits
``` bash
    git push origin master
``` 

## Luego
``` bash
git add .
git commit -m "Descripción de los cambios"
git push origin master
``` 