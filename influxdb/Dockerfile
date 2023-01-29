FROM influxdb:2.6.1

VOLUME ./data/influxdb/data:/var/lib/influxdb2

VOLUME ./data/influxdb/config:/etc/influxdb2


ENV  DOCKER_INFLUXDB_INIT_MODE=setup
ENV  DOCKER_INFLUXDB_INIT_USERNAME=elias
ENV  DOCKER_INFLUXDB_INIT_PASSWORD=iotelias
ENV  DOCKER_INFLUXDB_INIT_ORG=unimag
ENV  DOCKER_INFLUXDB_INIT_BUCKET=iotdata

