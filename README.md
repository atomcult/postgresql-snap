# Postgresql Snap
PostgreSQL Snapcraft recipes

## Notes
- Once installed, Postgres is automatically configured.
- To launch the client:
```sh
sudo postgresql16.psql
```
> [!WARNING]
> By default the user `postgres` is created with the password `changeme`. Be sure to change this after starting a client session:
> ```sql
> ALTER USER postgres WITH PASSWORD 'new_password';
> ```

> [!NOTE]
> `psql` runs as user `snap_daemon`.
