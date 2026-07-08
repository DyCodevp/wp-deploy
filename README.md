# Correr este proyecto

## Descripción
Despliega un proyecto de Wordpress utilizando Docker y Docker Compose.
defininiendo variables de entorno para la base de datos y Wordpress.

> :rocket Importante: estas variables son de prueba y deben ser reemplazadas por valores seguros en un entorno de producción.


## Requisitos

- Docker
- Docker Compose

## Instalación

1. Clonar el repositorio: `git clone https://github.com/DyCodevp/wp-deploy`
2. Navegar al directorio del proyecto: `cd wp-deploy`
3. Instalar las dependencias: `docker-compose up --build`
4. Configurar las variables de entorno:

```sh
WORDPRESS_DB_HOST=db
WORDPRESS_DB_USER=wordpress
WORDPRESS_DB_PASSWORD=wordpress
WORDPRESS_DB_NAME=wordpress

MYSQL_ROOT_PASSWORD=root
MYSQL_DATABASE=wordpress
MYSQL_USER=wordpress
MYSQL_PASSWORD=wordpress
```
## correr el proyecto
1. docker-compose up -d 
2. ingresar a `http://localhost:8081` 
3. completar la instalación de Wordpress
