A Cluster of Docker Containers for Monitoring
=============================================
[`grafana`][1] + [`influxdb`][2]

* [`docker-grafana`][1]: Official image
* [`influxdb`][2]: Official image

Usage
=====
```
docker-compose pull
docker-compose up -d
```

Listening Ports
===============
* `3000`: Grafana
* `8086`: InfluxDB
* `2003`: InfluxDB listening port for graphite metrics

`grafana`
=========
* Information on configuring Grafana docker [`webpage`][3]



On `graphite` software stack
============================
You can run [`docker-graphite`][0] separately and add it as a datasource to Grafana here.



__author__: *tuan t. pham*
[0]: https://github.com/neofob/docker-graphite
[1]: https://github.com/grafana/grafana-docker
[2]: https://hub.docker.com/_/influxdb
[3]: http://docs.grafana.org/installation/docker/
