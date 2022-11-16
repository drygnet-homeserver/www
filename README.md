# www
internet-facing nginx reverse proxy that sits in front of all the containers

using [jwilder/nginx-proxy](https://hub.docker.com/r/jwilder/nginx-proxy)

Automatic proxy based on the environment variable VIRTUAL_HOST in other containers.