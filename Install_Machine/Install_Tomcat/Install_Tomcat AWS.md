How to Install Tomcat on AWS ?


1.Login to server with admin access
 $ sudo sud
 
 $ yum update 


2.Install Java 

  $ yum install java
  
  $ java  -version
  
3.Download Tomcat 
 wget < file name>
 
4.Exaract file name 
tar -zxvf <file name.tar>

ls

pwd

5.In the Location go to file name 
cd <file name> /

pwd

ls

pwd

cd ...

6.go to in this path /home/ec2-user/ 
cd /home/ec2-user

clear 

ls

7.Remove in this file name  tar.gz 

rm -rf apache-tomcat-11.0.2.tar.gz

ls 

8.Move into apache-tomcat-11.0.2

mv ./apache-tomcat-11.0.2/  ./tomcat

ls

9.Go to in this location tomcat
 
cd tomcat/

ls 

10.Change back into Location 

cd ..

ls

cd/

11. Go to Opt in this location 

cd opt/

ls

pwd

12.Move go in this location tomcat

mv /home/ec2-user/  ./

ls

13.Change go to this location 

cd /home/ec2-user/

ls

14.Change /opt/tomcat lcation

cd /opt/tomcat

clear

ls

15.Change bin location 

cd bin/

ls

sh startup.sh

Port : 8080 
Port : 22



