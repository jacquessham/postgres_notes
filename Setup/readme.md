# Setup
There are two ways to setup a postgres database: Install locally or setup a Docker container. This section will go over how to setup a Postgres database for personal use cases.

## Install locally
For macOS, you may download Posgres from the <a href="https://www.postgresql.org/download/macosx/">official website</a> and follow the instructions.

## Setup with Docker
You may setup a Postgres database via Docker. You may either build it via <i>docker run</i> or <i>docker-compose up</i>:

### docker run
You may build a Postgres container and access it via Port 5432.

```
docker run --name container_name -e POSTGRES_PASSWORD=mysecretpassword -d database_name
```

### docker-compose up
Alternatively, you may build the Postgres database in a Docker network along with other applications. You may execute with the following code with the [docker-compose.yml](/docker-compose.yml) file which may find in this folder.

```
docker-compose up
```

