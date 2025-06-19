# vps-traefik
Docker traefik instance prepared for working on VPS

First of all you should create traefik network with command:
# docker network create traefik-public

Make sure to copy `.env.dist` file as `.env` and edit it to fill in necessary info

Then just run as usual with:
# docker compose up -d
