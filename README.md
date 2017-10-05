# docker-stack-test
testing docker stack https://docs.docker.com/get-started/part5/#introduction

* Setup a docker swarm
```
docker swarm init
docker swarn join worksers
docker stack deploy -c docker-compose.yml <name of stack> 
