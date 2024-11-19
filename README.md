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

**installation of kubectl:**
         sudo curl -LO "https://dl.k8s.io/release/$(curl -L -s https://dl.k8s.io/release/stable.txt)/bin/linux/amd64/kubectl 
         
         sudo curl -LO "https://dl.k8s.io/$(curl -L -s https://dl.k8s.io/release/stable.txt)/bin/linux/amd64/kubectl.sha256
         
         sudo echo "$(cat kubectl.sha256) kubectl" | sha256sum --check
         
         sudo install -o root -g root -m 0755 kubectl /usr/local/bin/kubectl
         
         sudo kubectl version --client --output=yaml 
         
         chmod +x kubectl
         
         sudo minikube start --driver=docker --force
         
         ![Screenshot (12)](https://github.com/user-attachments/assets/97df39d9-ea58-42c6-96a3-0de079a261d9)

         **Create the pod commands:**
           kubectl run pod-name --image=image-name

          ![Screenshot (14)](https://github.com/user-attachments/assets/180c4a3d-3ffb-429e-822c-3c3c4b0e9c54)

          **step:4**
          create yam file

          ![Screenshot (16)](https://github.com/user-attachments/assets/12580b91-5bb4-4cc5-bb8b-82175a7ee0b3)
          
          vi ravi.yml

         kubectl api-resources
         
         ![Screenshot (18)](https://github.com/user-attachments/assets/78282e56-f263-4d01-8500-ea34f05de400)

         

         

         
          

               
                         
                


         
                      




