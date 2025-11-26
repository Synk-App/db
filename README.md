# DB
DB setup for Synk's services.

# Getting Started

First step is to create a `.env` file in project root and change example values to your config. You can use `example.env` file from `_setup` folder as template.

And then, run `docker compose up -d` into project root to start project.

Last step to run project, is to run docker command to build database. This database will need config from SQL file from `_setup` folder. And then just run SQL from `schame.sql` and you are ready to go.

## Network

You can use a custom network for this services, using then `synk_network` you must create before run it. So, to create on just run command below once during initial setup.

```
docker network create synk_network
```