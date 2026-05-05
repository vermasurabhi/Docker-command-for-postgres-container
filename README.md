# Docker-command-for-postgres-container


## Bash File


```
docker run -d \
  --name postgres-container \
  -e POSTGRES_USER=admin \
  -e POSTGRES_PASSWORD=secret \
  -e POSTGRES_DB=mydb \
  -p 5432:5432 \
  -v postgres_data:/var/lib/postgresql/data \
  postgres:15

  ```
