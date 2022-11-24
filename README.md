### Docker Compose
Docker compose is a Docker runtime environment which makes running multiple Docker containers easy. You just simply need to create a
`docker-compose.yaml` file and run it via terminal, and then it will automatically take care of making your containers up.

#### Compose vs. Container
Container in a sense means only one single separated runtime environment inside docker network. These days most of the applications consume
more than one Docker container than in order to make every container live you need to make sure every container is running and is up through CLI which might becomes a bit tedious to manage all the containers. 


In order to solve this problem we can create a compose file and specify all our containers inside `docker-compose.yaml` file.


