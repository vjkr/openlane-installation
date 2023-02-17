# Docker-installation
<details>
  <summary>## Didnt work :(</summary>

Installation procedure wrt https://github.com/The-OpenROAD-Project/OpenLane 

Setting up Linux system on Windows
Trying to use WSL - Windows subsystem on Linux instead of Virtual Machine Installation
Hoping to find smooth operation of IO peripherals and easy access to local system.

Step 1: Open CMD with administrator privileges.
![image](https://user-images.githubusercontent.com/16399079/206835686-87efb9b1-25ad-456a-9b11-b89bbbe3ce8a.png)
Above image indicates openlane is already installed.

Step 2: Install Ubuntu 20.04 as suggested here
https://github.com/The-OpenROAD-Project/OpenLane

![image](https://user-images.githubusercontent.com/16399079/206835778-56ce66c0-82f0-4f82-9402-d76ddb125463.png)

Installation should get completed as below.
![image](https://user-images.githubusercontent.com/16399079/206960407-a3153c96-558f-4c70-8bd9-c27627b5b13f.png)

 Step 3: Trying to install Openlane using github link 
 installed docker image as mentioned in short version of desktop also 
 https://docs.docker.com/desktop/install/windows-install/
  downloaded .exe file and installed as above
 running below commands to create a container i guess
 ![image](https://user-images.githubusercontent.com/16399079/206965630-9b1f45e1-126d-4e3a-a463-4e6086c6585f.png)
got error as below
![image](https://user-images.githubusercontent.com/16399079/206965878-4c30192e-88d7-44c9-a285-03b58c54abc8.png)
trying to change to wsl2 by refering mentioned url
too many errors in installation !!

Switching to direct install
running sudo python install, git install and make install. fingers crossed.
Need to study need of docker container!
</details>

<details>
  <summary>
## trying another way THIS WORKED. DOCKER INSTALLED</summary>
iNSTALL vmware
downloaded latest version of xubuntu because vsdiat lab used xfce xubuntu.
install xubuntu using 'easyinstall' on vmware
tried DOWNLOADING .deb file and install docker. encoountered error.
 # Best final solution amongst all is follow prerequisites and installation from below link
 https://docs.docker.com/engine/install/ubuntu/#set-up-the-repository
 Received reply for hello-world
 ![image](https://user-images.githubusercontent.com/16399079/207249689-f1122bbb-1e9b-4782-985a-161efde6be5c.png)

</details>

<details>
  <summary>## Worked individual standalone, but support is less. Switching to vsdflow</summary>
# Completed post docker installation steps from  https://docs.docker.com/engine/install/linux-postinstall/
![image](https://user-images.githubusercontent.com/16399079/207250381-48de0af9-e5da-4b2c-b2bd-d6fb8bce3697.png)

# Completed venv and python3-pip installation, git and make
![image](https://user-images.githubusercontent.com/16399079/207251702-fbf34cc2-467b-4d1f-9b2b-e3667c8997dc.png)

#cloning openlane project folder., make , make test !! Successful installation
![image](https://user-images.githubusercontent.com/16399079/207272611-a2fd4fe9-d7cc-48c4-90c3-685606f84d45.png)

![image](https://user-images.githubusercontent.com/16399079/207273051-0b5bde0e-ebb8-4f34-9bd4-39aff7258777.png)
Test passed!! Switching to project work.
</details>

<details>
  <summary>## vsdflow installation</summary>
 After git clone from
 https://github.com/nickson-jose/openlane_build_script.git
 
 ![image](https://user-images.githubusercontent.com/16399079/219558914-87007cd3-10e0-4a1c-b1e1-b8179649ca12.png)

</details>

 
 
