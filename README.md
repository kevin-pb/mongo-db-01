# Introduccion a los fundamentos basicos de mongodb

## Para llebar a cabo este proyecto es nesesario:

* Descargar MongoDB Compass 
* Descargar Docker 
* Ejecutar el comando: git clone https://github.com/kevin-pb/mongo-db-01.git
* Ejecutar el comando: docker pull mongo
* Abrir el terminal en en el directorio del archivo y ejecutar el comando: docker-compose 
  docker-compose-mongo.yml up -d

## En este proyecto se verá:

* Crear una base de datos y una colección
* Insertar documentos
* Actualizar un documento específico cambiando un campo específico
* Eliminar un campo específico por un campo específico
* Hacer queries
* Creacion de un indicie
* Utilisacion del Agregation Framework
* Importacion y exportacion de datos

## Crear una base de datos y una colección

Una vez abramos el MongoDB Compass deberemos conectarnos a nuestra base de datos. Luego se crearan automáticamente unas bases de datos que no vamos a tocar, en la esquina superior derecha podrás ver un botón que dice crear base de datos, se nos abrirá un menu que nos dejara ponerle el nombre a la base de datos y a una coleccion en la cual trabajabaremos.

A continuación mostraré el proceso con imágenes:

## Insertar documentos

Para insertar documentos se ha de usar el comando insertOne o insertMany dependiendo de lo que se nesesite a continuacion se ve un ejemplo de ambos casos:

insertMany:

```MongoDB