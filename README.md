# swarm-note
## Create service
```sh
docker service create --replicas <replica> <image>
```
## Get container list of a service
```sh
docker service ps <service>
```
## Delete service
```sh
docker service rm <service>
```
## Get logs of a service
```sh
docker service logs <service>
```
## Get node list
```sh
docker node ls
```