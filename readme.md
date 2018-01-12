# PgBouncer - Lightweight connection pooler for PostgreSQL

Extremely small footprint PgBouncer container.

## Supported tags

 - `latest` - Latest version PgBouncer.
 - `v1.8` - Latest PgBouncer v1.8.x
 - `v1.7` - Latest PgBouncer v1.7.x

## Usage

````
docker run --name pooler -d -p 6432:6432 -v /home/yukimochi/pgbouncer:/etc/pgbouncer yukimochi/container-pgbouncer
````
