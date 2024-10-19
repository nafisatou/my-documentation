


> Written with [StackEdit](https://stackedit.io/).
	>## **CREATING A DOCKER CONTAINER IN MULTIPASS**

#1. Install multipass 
      >for ubuntu **sudo snap install multipass ** 
 #2. Launch multipass
     >using the command **multipass launch**
 #3.Creat a Virtual Machine VM
   > a new vm by: **multipass launch --name docker-vm**        #4.Install Docker in multipass
       >Access the multippass  vm :**multipass shell docker-vm**
  #5. Start the docker
  >start docker service:**sudo start docker**
  >#6 Pull a docker image
        >to pull  a docker image: **docker pull name-image
    >#7 verify docker installation
         > run docker --version
  >#8 Creat a docker container 
  >docker container create -i -t --name mycontainer
#9 Start a docker
> docker container start --attach -i mycontainer
#10 Creat a docker alias for ease fo use 
>  run alias docker ="multipass exec docker -vm --docker"

	
