# Laboratorio S2

Se realizo un docker compose en donde se creo 3 instancias para conectarlo a una base de datos PostgreSQL

## Stack
API: hola-mundo-api
- retornar un mensaje incluyendo mi nombre
- Docker
docker-compose.yaml
- clonacion de api
git clone https://github.com/nmatsui/hello-world-api.git

- PostgreSQL

# Indicaciones 
## Comandos
```
docker compose up
```

## Configuraciones por entorno

MESSAGE= Pereda 


# Volumenes y redes
## volumenes 
Ayudan a mantener archivos en el caso de eliminar el contenedor porque podemos conectar ese volumen a otro contenedor nuevo y se tendria los archivos intactos
## Tipos de volumenes
-   Volumen nativo: independiente del host y gestiona a travez del directorio donde trabaja docker
-   BIND MOUNT: monta un directorio del sistema de archivos del host para que sea visible desde el contenedor
-   TMPFS MOUNT:
Gestiona archivos en memoria en caso de que se quiera un sistema de archivos temporal

## Redes
Comunciacion
-   BRIDGE: Proporciona un puente entre los contenedores y permite mapear puertos
-   HOST: El contenedor se comunica a travez de la ip del host y usa la misma red 
-   OVERLAY: Unir y comunicar distintos docker 
-   IPVLAN: Gestiona la comunicacion la ip de cada contenedor 
-   MACVLAN:Gestiona la comunicacion por direcciones mac
-   NONE: Inhabilita la red del contenedor


## Creditos
- Pereda Flores Josep Karei

