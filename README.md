# docker
Popular Docker Commands for Devops work

#### Build Container 
sudo docker build <container_name> .

#### Run Container 
sudo docker run -p 80:80 <container_name>

#### Stop all containers 
sudo docker stop $(sudo docker ps -aq)

#### Remove all stopped containers
sudo docker rm $(sudo docker ps -aq)

#### Check docker system resources usage
sudo docker system df

#### Cleanup old and unused images
sudo docker image prune

### Cleanup all images
sudo docker image rm $(sudo docker image ls -q)
