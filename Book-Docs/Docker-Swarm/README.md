<img width="527" alt="dock-swarm" src="https://user-images.githubusercontent.com/13994900/100534885-8bea8980-31d9-11eb-88f8-d400b2c579ae.PNG">

Initiliazing a breain new swarm

```
docker swarm init --advertise-addr 10.0.0.1:237 --listen-addr 10.0.0.1:2377 
docker node ls 
docker swarm join-token worker (copy the ooutput and execute it)
docker swarm join-token manager (copy the output and execute it)

```
