
- git branch = "Para ver en que rama estamos posicionados".
- git branch "nombre para la rama" = "Crea una nueva rama".
- git checkout = "Para cambiar entre una rama y otra".

##Para eliminar una rama:##

- git branch -d "nombre de la rama".


##Para llevar cambios de una rama a otra##

- Primero hay que posicionarse en la rama que no tiene el cambio
  y posterior a eso dijitar:

  git merge + rama que contiene los cambios y la rama a la cual van los cambios.

  Ejemplo:

    -git merge Rama1 main

##Para hacer un commit en ramas especificas##

- Utilizar lo siguiente:

    -git add .
    -git commit -m "first commit"
    -git push -u + origin y el nombre especifico de la rama.

##Node##

- Para poder correr el servidor deberan actualizar la version de node a minimo 18.13

##Ionic##

- Dos formas de correr el servidor:

  - Ionic lab -- Probablemente les pedida instalar algo le dan que si.
  - Ionic serve -- version de navegador.

IMPORTANTE: Siempre revisar en que rama estan trabajando antes de hacer un commit para evitar errores,
            Se crearon tres ramas Development, 2 y 3. En la rama Development estara el proyecto base y donde se aplicaran
            los cambios finales. En las ramas 2 y 3 se trabajaran los componentes y cualquier avance de back o fornt-end.



