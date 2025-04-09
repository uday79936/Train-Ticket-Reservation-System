let's we have to navigate aws console and then go to  EC2 instance (or) server
and then start a server and take it as ssh key:

open the terminal and then 

cd Downloads/

Now ssh key : "ssh -i "Test.pem" ubuntu@ec2-98-81-227-245.compute-1.amazonaws.com"

first i will take it as to install java11

sudo apt update         to update all the packages

and then install java 11 version "sudo apt install openjdk-11-jre-headless"

ubuntu@ip-172-31-25-35:~$ java --version
openjdk 11.0.26 2025-01-21
OpenJDK Runtime Environment (build 11.0.26+4-post-Ubuntu-1ubuntu124.04)
OpenJDK 64-Bit Server VM (build 11.0.26+4-post-Ubuntu-1ubuntu124.04, mixed mode, sharing)

Now we have to clone the code from git

ubuntu@ip-172-31-25-35:~$ git clone https://github.com/HouariZegai/Calculator.git


"sudo apt install maven" to install maven

maven validate   to validate the project 

mvn test          to test the project

ubuntu@ip-172-31-25-35:~/Calculator$ ls
LICENSE  README.md  pom.xml  screenshots  src  target
ubuntu@ip-172-31-25-35:~/Calculator$

tar -xvf  apache-tomcat-9.0.102.tar.gz

go to security group and edit the inbound rules

to keep it as all tcp  and anywhere ipv4

cd manager/

to comment the valve

cd host-manager/

to comment the valve

cd config/

 tomcat-users.xml    to change the credientials

 

 














