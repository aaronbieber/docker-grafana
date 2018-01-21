# Docker Compose for Grafana

This is my Docker Compose configuration for Grafana. This uses a local volume 
mount instead of the separate container volume because I want to be able to 
see the files and I'm not that great at Docker (full disclosure).

This config also maps Grafana's default port, 3000, to 80 on the host.
