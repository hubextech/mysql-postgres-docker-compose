# MYSQL Server and Postgres Server

Docker Containers for MYSQL Server and Postgres Server

## Installation

Install [Docker](https://docs.docker.com/engine/install/ubuntu/).

Install [Docker Compose ](https://www.digitalocean.com/community/tutorials/how-to-install-and-use-docker-compose-on-ubuntu-20-04)


## Usage for MYSQL

```python
docker-compose -f docker-compose.mysql.yml up
```


## Usage for Postgres

```python
docker-compose -f docker-compose.postgres.yml up
```

### MYSQL Connection
```
Host: localhost
PORT: 3306
```

### Postgres Connection
```
Host: localhost
PORT: 5432
```


```
 Postgres client is hosted on http://localhost:5050/
 MYSQL client is hosted on http://localhost:3307/
```
