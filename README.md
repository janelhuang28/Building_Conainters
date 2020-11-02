# Building_Conainters
Followed https://www.youtube.com/watch?v=wH9XesmPUOk&amp;list=PLy7NrYWoggjzfAHlUusx2wuDwfCrmJYcs&amp;index=3 
for a tutorial on building containers

# Containers Overview
Containers are a way to package applications with all the necessary data. It is a method of OS virtualization. Containers run on dockers which is a software platform that enables building, testing and deployment of applications quickly. Note that the difference between an image and a container is that the image is not running and movable whereas a container is a running image. The difference between a conatiner and VM is that the VM runs on a hypervisor and provides an abstract machine whereas a container provides an abstract of an OS. 

## Container Development Benefits
Before containers: Services will need to be installed individually on each OS (e.g. mac/windows/linux). This increases the steps and human errors possible when installing.
After containers: All configurations and applications are stored in a single container, only requires a 1 command to install. 

## Container Deployment Benefits 
Before containers: Configuration of servers requires understanding of dependancy versions. There could also be miscommunications between the developers adn the operations team.
After containers: No environment configuration on servers except the docker image.

## Benefits
* Repeatable
* Self-contained execution environments
* Software can run in different environments
* Faster to launch, stop or terminate than VMs
* Highly scalable and fast 
* Orchestrates the execution of Docker containers
* Removes complex onstanding infrastructure
