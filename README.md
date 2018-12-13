# Docker
- [Docker Basic Commands](https://github.com/hugoledra/Help-and-Manuals/blob/master/Docker%20Comandos%20Basicos.txt)
- [Docker Overview](https://docs.docker.com/engine/docker-overview/)

#### Summary of this project
This project initiates through Docker Compose a database container with Mongo, three containers for the application in Node, and a container for load balancer in Nginx with the static files of the site. Compose will build the images for Nginx and Node, with the site files and project configuration.

#### Requirements to run this project
Docker Engine and Docker Compose 

#### Run this project
```
$docker-compose up

In web browser enter url localhost/seed to load the data into the database
The website is localhost
```
###### This project is based on the Alura course > [Docker Course: Creating Non-Headache Containers](https://cursos.alura.com.br/course/docker-e-docker-compose)
###### The whole coding part of this project was made by Douglas Quintanilha Barbosa Ferreira
