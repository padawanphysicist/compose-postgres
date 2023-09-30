# PostgreSQL & pgAdmin4 powered by Docker Compose

## Quick Start
1. Clone or download this repository: `git clone https://github.com/padawanphysicist/compose-postgres`
2. Go inside of directory: `cd compose-postgres`
3. Run the command `docker compose up`

## Environment
The Compose file contains the following environment variables:

- `POSTGRES_USER` the default value is **postgres**
- `POSTGRES_PASSWORD` the default value is **changeme**
- `PGADMIN_PORT` the default value is **8080**
- `PGADMIN_DEFAULT_EMAIL` the default value is **pgadmin4@pgadmin.org**
- `PGADMIN_DEFAULT_PASSWORD` the default value is **admin**

## Access to postgres: 
- `localhost:5432`
- **Username:** postgres (as a default)
- **Password:** changeme (as a default)

## Access to PgAdmin: 
- **URL:** `http://localhost:8080`
- **Username:** pgadmin4@pgadmin.org (as a default)
- **Password:** admin (as a default)

## Add a new server in PgAdmin:
- **Host name/address** `postgres`
- **Port** `5432`
- **Username** as `POSTGRES_USER`, by default: `postgres`
- **Password** as `POSTGRES_PASSWORD`, by default `changeme`
