# SERVER
This repo contains all the docker compose files used to stand up the applications. Each stack is designed to stand alone but can be connected to eachother. 

## Docker Prerequisite
You will need to create a reverse-proxy network and add it to any service that you'd like to be behind the reverse-proxy. To do this, do `sudo docker network create reverse-proxy`. 