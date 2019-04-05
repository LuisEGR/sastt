# sastt
Sistema de apoyo al seguimiento de trabajos terminales


[![Build Status](https://travis-ci.org/LuisEGR/sastt.svg?branch=master)](https://travis-ci.org/LuisEGR/sastt)


Este proyecto levanta el sitio completo, que está conformado por un contenedor con MongoDB, un servidor HTTP para el front, y un servidor HTTP para los servicios web REST, estos 2 últimos se pueden acceder desde afuera del contenedor mediante las siguientes URLs:

Web: `http://localhost:8080`    
API: `http://localhost:3000`   

El servidor de MongoDB solo es accesible desde el contenedor **sasstServerApi**, mediante la URL localhost/< colección >


## Requerimientos:

### Para generar el projecto
* Docker 18+
* NodeJs 11+

### Para correr el proyecto
* Docker 18+
* docker-compose 1.2+


Build:
```bash
docker-compose build
```

Run:
```bash
docker-compose up
```

Stop:
```bash
docker-compose down
```