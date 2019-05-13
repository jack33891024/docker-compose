# docker-compose

## compose file example:

 - nginx
 - mysql
 - redis
 - pxc
 - haproxy
 - centos
 - nsq
 - grafana
 - influxdb
 - gitlab-ce

 ## create netowrk named common_network with default driver(bridge)

 ```
docker network create -d bridge \
--attachable \
--subnet 192.168.250.0/24 \
--gateway 192.168.250.254 \
common_network
 ```
