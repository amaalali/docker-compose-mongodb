# Docker compose for Percona Mongo

A compose file that start Percona Mongo distribution and initalise the replica-set.

## Requirements

You need the following

- docker
- docker-compose

## Usage

1. Clone repo
2. `cd` into the repo
3. Run the `./init.sh` script that will create the docker volume requred. Alternatively run `docker volume create mongo-data`
4. Run `docker compose up -d`

