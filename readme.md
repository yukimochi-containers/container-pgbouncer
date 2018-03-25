# PgBouncer - Lightweight connection pooler for PostgreSQL

Extremely small footprint PgBouncer container.

## Build status

- amd64 image - ![AMD64 latest image Build status](https://img.shields.io/docker/build/yukimochi/container-pgbouncer.svg)
- arm32v7 image - ![arm32v7 latest image Build status](https://ci.yukimochi.com/api/badges/yukimochi-containers/container-pgbouncer/status.svg?branch=v1.8-armv7)
- arm64v8 image - ![arm64v8 latest image Build status](https://ci.yukimochi.com/api/badges/yukimochi-containers/container-pgbouncer/status.svg?branch=v1.8)

## Usage

````
docker run --name pooler -d -p 6432:6432 -v /home/yukimochi/pgbouncer:/etc/pgbouncer yukimochi/container-pgbouncer
````
