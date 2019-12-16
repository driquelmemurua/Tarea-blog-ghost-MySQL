# Tarea Blog Ghost + MySQL en Docker
## Ambiente
Maquina virtual - Ubuntu 18.04.3
## Instalación de docker y docker-compose
* [Guía de instalación de docker](https://docs.docker.com/install/linux/docker-ce/ubuntu/)
* [Guía de instalación de docker-compose](https://docs.docker.com/compose/install/)
## Ejecución de los contenedores
Luego de clonado el repositorio y dentro de la carpeta ejecute
```
$ docker-compose -p "ghost-platform" up -d
```
Se levantará primero el contendor con la instancia de MySQL seguido del contenedor con ls instancia de Ghost.
Luego de eso uno puede acceder al blog ingresando a [localhost](http://localhost) desde el navegador.

