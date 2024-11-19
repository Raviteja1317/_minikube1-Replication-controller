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

       sudo mv minikube-linux-amd64 /usr/local/bin/minikube

sudo chmod +x /usr/local/bin/minikube

sudo minikube version

sudo apt install curl wget apt-transport-https -y

sudo curl -LO "https://dl.k8s.io/release/$(curl -L -s https://dl.k8s.io/release/stable.txt)/bin/linux/amd64/kubectl"

sudo kubectl version --client

sudo curl -LO "https://dl.k8s.io/$(curl -L -s https://dl.k8s.io/release/stable.txt)/bin/linux/amd64/kubectl.sha256"

sudo echo "$(cat kubectl.sha256) kubectl" | sha256sum --check

sudo install -o root -g root -m 0755 kubectl /usr/local/bin/kubectl

sudo kubectl version --client  

![Screenshot (13)](https://github.com/user-attachments/assets/36dfc623-1224-4f31-a758-47366630afb3)

Create the pod commands

![Screenshot (14)](https://github.com/user-attachments/assets/acec2f1f-048b-4ab5-b0c1-87af78b8867d)

create yam file
![Screenshot (17)](https://github.com/user-attachments/assets/3bc4dd18-3552-409b-a911-9521aaea6d98)

vi ravi.yml

kubectl create -f ravi.yml - by this command if pod is created then the work is done

           
         



         


         

         

         

         
          

               
                         
                


         
                      




