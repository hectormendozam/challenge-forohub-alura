# CHALLENGE FORO-HUB ALURA

## Descripción Del Proyecto

Challenge de una aplicación de foro para desarrollar del programa ONE y Alura Latam

## Funcionalidades

* Permite hacer login ingresando el email y clave de usuario.
* Mediante autenticación es posible realizar operaciones CRUD para cursos, perfiles, usuarios, respuestas, topicos.
* Se genera la documentación de la api mediante Swagger-ui accediendo en el navegador.

## Dependencias (ver pom.xml)

* Swagger
* Lombok
* Flyway
* MySql-connector
* JWT
* Spring (web,security,validation,JPA)
* Versión Java (Initializr) 17
* Versión Java Intellij 21

## Funcionamiento

Se requieren crear un usuario con email y su clave en hash de tipo bcrypt en la base de datos y los perfiles.
Posteriormente hacer login y realizar nuevos registros para topicos y respuestas.

## Sobre el autor

Héctor Alejandro Mendoza Merino
