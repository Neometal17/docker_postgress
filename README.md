# Proyecto de Prueba para Docker

## Gestion de los contenedores

### Para iniciar los contenedores
docker-compose -f postgress-admin.yaml up

### Para detener los contenedores
docker-compose -f postgress-admin.yaml down

### Variables de Entorno
Se encuentran en el .env para usuarios y password de **PG_ADMIN** y el **BD POSTGRESS**, se puede sustituir por las que se requieran

## Gestion Web

### Web PGADIN 
La web de administracion se ingresar por la siguiente URL: **http://localhost:5050/**

**Nota**: Si usa windows docker-desktop debe estar iniciardo
