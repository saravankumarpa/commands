#### build docker

docker build --tag=myservice .

#### find the built docker

docker image ls


#### run the app
docker run -p 4000:80 myservice

####  run in detached mode
docker run -d -p 4000:80 myservice

#### run interactively
docker exec -i -t container_name /bin/bash

#### remove everything 
docker system prune
