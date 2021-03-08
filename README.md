# docker-grafana

Grafana + influxdb on docker for 7cav.us

## To run this

Create network for internal networking behind proxy.

- "docker network create monitor"

Create volumes for both influxdb and grafana

- "docker volume create --name=influxdb-data"
- "docker volume create --name=grafana-data"

Deploy the docker compose file:

- "docker-compose up -d"
