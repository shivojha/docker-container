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

**What is a container?**

A container is simply another process on your machine that has been isolated from all other processes on the host machine. That isolation leverages kernel namespaces and cgroups, features that have been in Linux for a long time. Docker has worked to make these capabilities approachable and easy to use.

**#What is a container image?**

When running a container, it uses an isolated filesystem. This custom filesystem is provided by a container image. Since the image contains the container's filesystem, it must contain everything needed to run an application - all dependencies, configuration, scripts, binaries, etc. The image also contains other configuration for the container, such as environment variables, a default command to run, and other metadata.
 
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
