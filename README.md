# Setting-up-a-Swarm-Cluster-with-a-Manager-and-Worker-Node-Docker

Docker swarm is a container orchestration tool, meaning that it allows the user to manage multiple containers deployed across multiple host machines. One of the key benefits associated with the operation of a docker swarm is the high level of availability offered for applications.

```

1. On the master node, initialize the swarm
$ sudo docker swarm init

2. In the worker node, join the swarm as a worker node using the docker swarm join command generated through swarm init

3. Navigate back to the master node and list all the nodes of the swarm cluster
$ sudo docker node ls

```
