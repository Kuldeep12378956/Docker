# Docker

Docker is opensource centralize platform design to Create, Deploy and run application.

Docker is OS level Virtualization technique, That can help us create Containers on the OS, 
Container uses the base host image as the OS image of itself. & resources it get as per requirement from H/W. it is very lieghtweight. 

## Advantages of Docker :- 

1. Lightweight 
2. No pre-allocation of RAM 
3. CI -effeciency 
4. less Cost
5. it can run on physical H/W, Hypervisor, Cloud
6. you can reuse the Image.
7. It takes very less time to create Container

## Disadvantes of Docker - 

1. It doesn't support cross platform
2. Difficult to manage the large amount of container
3. it is not good for GUI based application
4. No solution for Data recovery & Backup.
5. Docker is suitable for only if Developement Operation system and Testing OS is same.


### Docker Basic Commands - 

To check the Images on the Host
``` 
docker images
```
to search for the jenkins image    

``` 
docker search jenkins
``` 

to pull the jenkins image from the dockerhub to your Host 
``` 
docker pull jenkins
``` 
to run the container & give it name 

``` 
docker run -it --name <container name> <image name> /bin/bash
``` 

to check the service is start or not 
``` 
service docker status
``` 

to start the stopped container 
``` 
docker start <container name>
``` 

to go inside the container

``` 
docker attach  <container name>
``` 

to check status of all the container running or stopped
```
docker ps -a
``` 

to check the status of running container

```
docker ps
``` 

to stop the running container 
``` 
docker stop <containername>
``` 

to delete the container 
``` 
docker rm <container name>
```  

************************************************************************


   



