# dockercloud/node

Get your `<token>` by clicking on `Bring your own node` in Docker Cloud's [Nodes dashboard](https://cloud.docker.com/node/cluster/list/)

## Usage (using Docker)

Run your Docker Cloud node inside a container!

	docker run -d --net=host --privileged --restart=always -e TOKEN=<token> dockercloud/node

## Versions available

	dockercloud/node:1.9.1-cs2
	dockercloud/node:latest


## Usage (using Vagrant)

Run your Docker Cloud node inside a Vagrant box!

	vagrant init dockercloud/node
	TOKEN=<token> vagrant up
