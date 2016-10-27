# Kong with Docker Compose

This repository contains a simple docker-compose file for [Kong](https://getkong.org/).

The goal is to provide a minimal Kong setup with docker-compose for local development and testing.

It provisions a Kong container with a Postgres database.

**Do not use it in Production!**

Instead use the offical docker-compose file from [Kong Docker Compose](https://github.com/Mashape/docker-kong/tree/master/compose).


## Usage

Just run

```
docker-compose up
```

After the startup Kong will be available on port `8000`, `8443` and `8001`.
