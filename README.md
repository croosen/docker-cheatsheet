# docker-cheatsheet
Docker cheatsheet

#### View all images
`$ docker images`

#### Build image
`docker build -t IMAGE .`

#### Run image
Mostly port 80, otherwise choose a port that is not used by any other services
`$ docker run -p PORT:80 IMAGE`

#### Run image in background
`$ docker run -d -p PORT:80 IMAGE`

#### List all Docker services
This will get you a list with services and their ID's
`$ docker ps`

#### Stop service
`$ docker stop SERVICE_ID`

#### Remove service
`$ docker rm SERVICE_ID`

#### Login to Docker Cloud
`$ docker login`

#### Publish Docker image
`$ docker tag IMAGE username/repository:tag`

#### Push Docker image to Cloud registry
`$ docker push username/repository:tag`

#### Run Docker image from Docker Cloud registry
`$ docker run -p 4000:80 username/repository:tag`



