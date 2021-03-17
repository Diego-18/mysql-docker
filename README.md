# mysql-docker
Dockerized mysql server


# Prerequisites:

  Docker
  
  Docker-compose

# RUN:
  
  1. Create the directory at the following location: /opt/mysql.
  
  2. Create a new network in which you will include the mysql container. Example:
      
    docker network create --driver bridge network_bd
  
  3. Execute the following command in the folder where the Dockercompose.yml file is located. 
    
    sudo docker-compose up -d  
    
    
@Diego-18
