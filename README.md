#java

let's we have to navigate aws console and then go to  EC2 instance (or) server
and then start a server and take it as ssh key:

open the terminal and then 

cd Downloads/

Now ssh key : "ssh -i "Test.pem" ubuntu@ec2-98-81-227-245.compute-1.amazonaws.com"

first i will take it as to install java11

sudo apt update         to update all the packages

and then install java 11 version "sudo apt install openjdk-11-jre-headless"

Now we have to clone the code from git

ubuntu@ip-172-31-25-35:~$ git clone https://github.com/HouariZegai/Calculator.git


"sudo apt install maven" to install maven

maven validate   to validate the project 

mvn test          to test the project

wget <link> to install the tar file

tar -xvf  apache-tomcat-9.0.102.tar.gz

go to cd bin
./startup.sh

to start the tomcat

we have to shutdown the server means 

./shutdown.sh

go to security group and edit the inbound rules

to keep it as all tcp  and anywhere ipv4

cp -r TrainBook-1.0.0-SNAPSHOT.war ~/Train-Ticket-Reservation-System/apache-tomcat-9.0.102/webapps

cd manager/

to comment the valve

cd host-manager/

to comment the valve

cd config/

 tomcat-users.xml    to change the credientials

 

 














