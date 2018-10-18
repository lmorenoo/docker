
# Ejercicio #2 taller1 MicroUdea Servicio Bienes Raices API

## Integrantes
- Luis Fernando Moreno Oviedo


## Overview  
Crea la Api basado en tipo de inmuebles(Casa, Apartamento...), inmuebles y negociacion(compra, venta, arriendo)

## DB - MySQL
Al subir la aplicacion crea cada una de las tablas utilizadas, Inmueble, Negocio, TipoInmueble

## Pasos para correr la aplicacion

### Descargar las imagenes
#### Imagen back-end

docker pull lmorenoo/inmueble

#### Imagen base de datos

docker pull lmorenoo/mysql

### subir el docker-compose
Docker-compose up -d 

Correr la aplicacion en http://localhost:8081/bienesRaicesApi/swagger-ui.html

Se abrira un Swagger con todas las posibles acciones que se pueden ejecutar para la aplicacion de bienes raices

