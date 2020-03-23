# Docker | Nginx | PHP 7.3.7 | Postgresql & PgAdmin

## Requirements:
* docker >= 17.12.0+
* docker-compose

## Quick Start
* Clone or download this repository
* Go inside of directory,  `cd lumen-docker`
* Run this command `docker-compose up -d`


## Environments
This Compose file contains the following environment variables:

* `POSTGRES_USER` the default value is **postgres**
* `POSTGRES_PASSWORD` the default value is **root**
* `PGADMIN_PORT` the default value is **5432**
* `PGADMIN_DEFAULT_EMAIL` the default value is **root@root.com.br**
* `PGADMIN_DEFAULT_PASSWORD` the default value is **root**

## Access to postgres: 
* `localhost:5432`
* **Username:** postgres (as a default)
* **Password:** root (as a default)

## Access to PgAdmin: 
* **URL:** `http://localhost:3380`
* **Username:** root@root.com.br (as a default)
* **Password:** root (as a default)
 

## Add a new server in PgAdmin:
* **Host name/address** `postgres`
* **Port** `5432`
* **Username** as `POSTGRES_USER`, by default: `postgres`
* **Password** as `POSTGRES_PASSWORD`, by default `root`