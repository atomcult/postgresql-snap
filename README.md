# postgresql-snap
PostgreSQL snapcraft recipes

## Notes
- once installed, postgres is automatically configured and the postgres service is automatically started
- to launch client:
```
sudo postgresql14.psql -h "/var/snap/postgresql14/common/sockets/" postgres
```
note that psql runs with snap_daemon user privileges
