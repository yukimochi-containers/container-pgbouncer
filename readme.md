# PgBouncer - Lightweight connection pooler for PostgreSQL

Extremely small footprint PgBouncer container.

## Usage

````
docker run --name pooler -d -p 6432:6432 -v /home/yukimochi/pgbouncer:/etc/pgbouncer yukimochi/container-pgbouncer
````
