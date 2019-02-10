# bdbackup
contiene el backup de la base de datos requerida para el mini proyecto web

La base de datos fue generada con: 
- [PostgreSQL](https://www.postgresql.org/) y la herramienta [pgAdminIII](https://www.pgadmin.org/).

## Indicaciones
Una vez instalada y configurada la herramienta pgAdmin, creamos una base de datos con el mismo nombre
que viene en nuestro archivo application.properties en nuestro proyecto de Spring.

Una vez creada la base de datos, le damos clic derecho> Restore > y elegimos el backup encontrado en este repositorio,
una vez ejecutado, refrescamos nuestra base de datos y debe contener todos los datos necesario.
