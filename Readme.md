# RabbitMq Docker
This is an official, open-source for RabbitMq based projects that run on Docker-Compose. 
    
## Usage
You are up and running in three simple steps:

$ cd rabbitmq-docker

$ docker-compose up --build -d 
 
You can just open your browser at:

http://localhost:15672 or you can get the container IP: docker inspect CONTAINER ID | grep IPAddress

Use guest as username and password.

To use the CLI to access mailhog directly execute the following:

$ docker exec -it rabbitmq
