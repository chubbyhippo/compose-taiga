# taiga
## start
```
docker compose up -d
```
## create admin user
```
docker compose -f compose.yaml -f compose-inits.yaml run --rm taiga-manage createsuperuser
```