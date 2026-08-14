# `btn_ctrl_ops/docker`

See [Docker Compose](https://docs.docker.com/compose/), [Compose file reference](https://docs.docker.com/reference/compose-file/)

## Quickstart

1. Setup files in `cloudflared`, `traefik`
2. Run `docker compose up -d`.

## Services

### `cfargotunnel`

Client for Cloudflare Tunnel.

### `traefik`

Reverse proxy.

### `demo`

A simple website for testing.

Run `docker compose --profile demo up demo -d` to start the demo website.

### `mysql`

Configure `root_password.txt` in the `mysql` folder, then run `docker compose --profile mysql up mysql -d` to start the MySQL server.
