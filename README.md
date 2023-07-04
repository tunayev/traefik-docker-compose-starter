## Traefik Quick Start Boilerplate
### What is Traefik?
Traefik is an intelligent reverse proxy that is used to route traffic to different containers. It also takes the hassle out of setting up SSL certificates for each container. You can read more about it [here](https://doc.traefik.io/traefik/)
### Why
Starting a new project with deployment in mind can be a hassle. This repo is meant to be a quick start boilerplate for Traefik. Whenever you need to create a new server with Traefik, you can just clone this repo and run the command below.
### Installation
1. Clone this repo.
2. Fill out the traefik.toml and treafik_dynamic.toml file with your hostname, dashboard credentials and email address. 
3. Change or add any additional configuration you need.
3. Run the following command to create the container that Traefik will use.
``` docker-compose -f docker-compose-traefik.yml up -d ```