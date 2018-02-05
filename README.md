# dockerspringbootapp
--------
### prerequisite
----
read the document to get better understanding of how to deploy the spring boot app using docker

https://spring.io/guides/gs/spring-boot-docker/


### Running the created docker image

#### docker images ----command
- list out the avaiable docker images using the command

#### docker run -i -t imageId (Example Image Id :3670d2fa098e) ----command

- run the image you want using the command


#### docker service create --env-file=/home/kirk/docker/main.env --replicas 1 --name rulesengine --publish 8080:8080 --log-driver gelf --log-opt gelf-address="udp://172.17.0.4:12201" --log-opt tag="rulesengine" reqwired-engine:latest
