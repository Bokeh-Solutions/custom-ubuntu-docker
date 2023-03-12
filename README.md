# Readme
This repository is a simple project with the basic structure of a 
docker compose file that you can use as a starting point for the creation of
more complex multi container architectures.

## What this project creates?
When we run this project we basically are downloading the base image of an
Ubuntu Server 22.04, where we install openssh server and we create the user
"ubuntu" with password "password".

This user then is assigned to the "root" and "sudo" groups, so it has 
privileges into the system, we then we enable the "sshd" service.

At this point you will have a container that will keep running and you can ssh into it

## More info
You can have more info in the article [Creating a Container Image and how to Push it to a Private Registry](https://www.bokehsolutions.com/component/content/article/creating-a-container-image-and-how-to-push-it-to-a-private-container-registry.html?catid=12&Itemid=101)
