# docker
Popular Docker Commands for Devops work

### Build Container 
sudo docker build <container_name> .

### Run Container 
sudo docker run -p 80:80 <container_name>

### Stop all containers 
sudo docker stop $(sudo docker ps -aq)

### Remove all stopped containers
sudo docker rm $(sudo docker ps -aq)
