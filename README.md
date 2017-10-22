# zerg
Simple docker deployments

# Simple-01

You can find the repository at `http://gitlab.hugocortes.me/swarm/simple-01`. This is a simple Hapi on NodeJS app that has two GET routes `/status` and `/simple`. 

They can be accessed here:  
http://simple-01.hugocortes.me/status  
http://simple-01.hugocortes.me/simple

The `docker-compose.yml` file is used to deploy to a swarm. If you want to run the image locally, you can find the image at `https://hub.docker.com/r/hugocortes/simple-01/`.

For this image, the following environment variables will be needed:  
`PORT`  
`ADDR`  
`LOG_LEVEL` (error, warn, info, debug)  
