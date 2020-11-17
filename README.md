# HAY TEKNOLOJI MONITORING STACK
Once we searched template for building a monitoring stack but can not find so we built our own. This repository can be used for experiments with Prometheus, Influxdb, Grafana, and Loki stack.

## Usage
First, volumes should be created;
```shell
docker volume create --name=loki-data
docker volume create --name=influxdb-data
docker volume create --name=grafana-data
```

then;
```shell
docker-compose up -d
```