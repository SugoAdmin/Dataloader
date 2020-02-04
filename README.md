# Dataloader install process  
## Login Xshell and Winscp  
IP 3.18.16.107  
user ec2-user  
Key "dataloader-Test.pem"  

## Upload File
upload the "zulu11.37.17-ca-jdk11.0.6-linux.x86_64.rpm" package to /home/ec2-user/  
upload the "Dataloader" folder to /home/ec2-user/  

## Executive Command
****
```
sudo mkdir /usr/java/  
sudo mv zulu11.37.17-ca-jdk11.0.6-linux.x86_64.rpm /usr/java/  
sudo rpm -ivh /usr/java/zulu11.37.17-ca-jdk11.0.6-linux.x86_64.rpm  
```
****
