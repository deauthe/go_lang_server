# useful docker commands

```shell
docker run postgres:12-alpine 
```


## using container's shell to create db and run migrations

```shell
docker exec -it postgres /bin/sh 
  #shell_starts, the particular image gives access to commands like createdb, dropdb,   
createdb --username=root --owner=root simple_bank

psql simple_bank #entering the database

```
```
