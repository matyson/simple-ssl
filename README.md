# Simple ssl

Simple ssl nginx reverse proxy setup.

## Start

Setup `.env` like the example file `.env.example` and run:

```sh
docker compose up -d
```

> Note: be sure to put your `ssl` certificates inside the `./certs` directory as `server.key` and `server.crt`.