# _minikube1-Replication-controller

First of create a ec2 instance in in ubuntu with t2 medium.

Switch to root user by the command sudo su -

and update it using command apt update -y
![Screenshot (19)](https://github.com/user-attachments/assets/fe1ea923-ba35-4808-af8f-3dcc26795af3)

**step:2**
Now install docker

         sudo apt install curl wget apt-transport-https -y
         sudo curl -fsSL https://get.docker.com -o get-docker.sh 
         chmod 777 get-docker.sh sh get-docker.sh
         
         DOCKER VERSION
![Screenshot (10)](https://github.com/user-attachments/assets/575db7df-464a-4e44-8adb-5a6c403c9e8e)
**step:3**
#Installation of minikube:

               sudo curl -LO https://storage.googleapis.com/minikube/releases/latest/minikube-linux-amd64
                sudo mv minikube-linux-amd64 /usr/local/bin/minikube
                sudo chmod +x /usr/local/bin/minikube
                sudo minikube version



