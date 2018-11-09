# Tarea_2_TBD GRUPO 2

Integrantes:
* Ignacio Farias
* Barbara Peña
* Felipe Vásquez
* Carlos Alvarez


En la carpeta de Backend_tbd_taller2 se encuentra el codigo correspondiente al Backend de la aplicacion

## Peticiones GET:

* localhost:puerto/actors/              --- Retorna todos los actores.
* localhost:puerto/actors/1/             --- Retorna al actor con Id = 1.
* localhost:puerto/actors/1/films/       --- Retorna todas los films en las que ha participado el actor que tiene Id = 1.

* localhost:puerto/films/               --- Retorna todos los films.
* localhost:puerto/films/1/              --- Retorna el film con Id = 1.
* localhost:puerto/films/1/actors/       --- Retorna todos los actores que ha participado en el film que tiene con Id = 1.

## Peticiones POST

* localhost:puerto/actors/1/films/2/     --- Vincula el film con Id = 2 con el actor con Id = 1.
* localhost:puerto/films/1/actors/2/     --- Vincula al actor con Id = 2 con el film con Id = 1.

* localhost:puerto/actors/              --- Crea a un actor.


En la carpeta de Frontend_tbd_taller2 se encuentra el codigo correspondiente al Frontend de la aplicacion

Nota: modificar el archivo application.properties para configurar la DB, la URL y los puertos a conveniencia del usuario.
Nota: modificar archivos Actors.vue y AddActor.vue dentro de _Frontend_tbd_taller2/plantilla-vue/src/_ para configurar a que URL se conectará front
