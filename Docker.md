Docker is an open platform for developing ,shipping and running applications.

Docker is a platform which packages an applications and all its dependencies together in the form of conatiners
\
fish

what problems Docker solves?
conteatiner with dependencises

understand the docker



we have a hardware -> ram,motherboard,ssd
we did assemble and make a computer

host operating system->
install python eclipse
after that we eil install windowa /linux/macos

if i want to run multiple software same time 

where we can use docker  engine

docker manges containers 

app dependencies conatiner
java app ,java8

this are iso lated

we can create multiple container
and we can go from  any other system  with conatiner

important

Dockerfile ,Image and container

Doockerfile:- Text Document which contains all the commands that a user can call on the commant line to assemble an image.


Docker Image:- Template to create docker coatainer.

Docker Conatiner:- Running instance off the docker image.Conatiners hold entire packages to run applications.


Docker -> build -> DockerImage -> run ->DockerConatiner

Docker Install

open cmd 

type docker -v
docker --version
docker run hello-world

docker images

docker hub is website where all images are their

we can pull explore
//cmd
image pull
docker pull [imagename]
show images 
docker images cmd
docker pull openjdk:18

image pull
docker pull [imagename]
show images 
docker images cmd
docker pull openjdk:18


docker seacrh mysql
docker seacrh nginx


docker container //
docker ps cmd

docker ps -a  

 docker run --name pythonContainer -d f92346e0c39e

  docker run --name pythonContainer1 -it -d python

  docker ps


  docker exec -t a51f54f068c6 python3


print("this is testing")

class test:
pass

ob=Test()
print(ob)
