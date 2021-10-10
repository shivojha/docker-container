# docker-container
 A docker container demo application 
 Steps to create docker
 
 Definition:
 
 Docker is an open platform for developing, shipping, and running applications. Docker enables you to separate your applications from your infrastructure so you can deliver software quickly.
 
 Docker provides the ability to package and run an application in a loosely isolated environment called a container. The isolation and security allow you to run many containers simultaneously on a given host. Containers are lightweight and contain everything needed to run the application, so you do not need to rely on what is currently installed on the host.
 
 What can I use Docker for?
 
 - Fast, consistent delivery of your applications
 - Responsive deployment and scaling
 - Running more workloads on the same hardware
 
 Tools:
 -docker desktop
 -wsl2
 -windows terminal
 
 hub:
 
 #Commands:
 --docker build
 --docker tag
 --docker push
 
 --docker run -d -p 80:80 docker/getting-started

-d - run the container in detached mode (in the background)
-p 80:80 - map port 80 of the host to port 80 in the container
docker/getting-started - the image to use


 docker pull <image
 docker run <localhostport:containerport>                   
                    
                    
 
References:
https://docs.docker.com/get-started/overview/
Deep dive on Container https://youtu.be/8fi7uSYlOdc
