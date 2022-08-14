# Proxy Inverso
Para ejecutar el Proyecto:
- Debe ejecutar el comando docker-compose up en los directores site 1 y site 2
- Debe ejecutar el comando docker-compose build y luego docker-compose up en el directorio reverse-proxy
- En la ruta /etc/hosts agregar:
  1. iphost site1.example.com
  2. iphost site2.example.com
*Cabe aclalar que iphost es el ip de la maquina donde correrá el proyecto.

## Autores
* **Víctor Sapuyes** - *Desarrollador* - [victor262108](https://github.com/victor262108)
* **Kevin Marin** - *Desarrollador* - [kvinstuard](https://github.com/kvinstuard)

## Licencia
Este proyecto está bajo la Licencia MIT licence ver [LICENSE.md](LICENSE.md) para más detalles. 
Las páginas web usadas fueron tomadas en base al curso de [freeCodeCamp](https://www.freecodecamp.org/)
