
/*
 Simple docker project.
 A simple nodejs server using 
 express framework and creating 
 a docker image of that.
*/


/*
Docker actions with commonds:

1)Run docker image
docker run image_name

2)Build image with tag
docker build -t image_tag_name .

3)Run docker image with specific port mapping
docker run -p 3000:3000 image_name

4)Stop docker container
sudo docker stop container_id

5)All running containers
sudo docker ps

6)Execute commond inside container
sudo docker exec -it 012cfa4f5591 sh


7)Running a docker-compose file
  sudo docker-compose up

8)build a docker-compose file and run
  sudo docker-compose up --build

9)Run container in detached mode:
  sudo docker run -d image_name
  
  The command "docker run -d" is used to run a Docker container
in detached mode, which means it runs the container in the background.


*/



