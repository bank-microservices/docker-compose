# Bank Microservices

## Ejecutación:
 Para la ejecución de los microservicios ejecutamos los siguientes comandos:

 *Iniciamos con los servidores:*
 ````
 docker-compose -f common.yml -f servers.yml up
 ````

 *luego continuamos con los servicios:*

````
docker-compose -f common.yml -f services.yml up
````
 
 *O también puede ejecutar todo a la vez, mediante el siguiente comando:*

 ````
 docker-compose up
 ````

