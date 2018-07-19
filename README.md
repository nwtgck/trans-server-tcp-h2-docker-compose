# trans-server-docker-compose
`docker-compose.yml` for [trans-server](https://github.com/nwtgck/trans-server-akka)

## Run

Here is how to run the servers.

```bash
docker-compose up
```

## Ports

The following ports are open ports.

* <http://localhost:8080/> is Trans server
* <http://localhost:8082/> is H2 Database Web Console

## Data Persistence
All data for persistence are under `./docker_volumes`.
