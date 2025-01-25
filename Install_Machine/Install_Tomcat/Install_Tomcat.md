1.How to Install Tomcat in Ubuntu to AWS Machine ?

 #Install OS Updates
 $ sudo apt-get update

 #Install JDK Pre-Requisite
 $ sudo apt install default-jdk

 #Verify Java install Commands
 $ java --version

 #Download link for Tomcat default take in the Google page.
 $ wget <File name>

 #untar the tar.gz file
  $ tar -zxvf <filename.tar>

  #go to in this location
  $ cd apache-tomcat-10.1.25/
  $ cd /

  #go to /opt root Directorty
  $ cd opt/
  $cd /home/ubuntu/apache-tomcat-10.1.25/
  $ cd ..
  $pwd

  #Create tomcat directory in /opt/tomcat
  $ sudo mkdir /opt/tomcat/

  #Move the tomcat files to opt/tomcat
  $ sudo mv <file name> /* /opt/tomcat
  ls
  $ cd <file name> /

 #set environment variables for tomcat
 $ echo ‘export CATALINA_HOME=”/opt/tomcat”’ >> ~/.bashrc
 $ echo ‘export PATH=”$PATH:CATALINA_HOME/bin”’ >>~/.bashrc
 $ source ~/.bashrc

 #go to /opt/tomcat
 cd /opt/tomcat
 ls

  #go to location  /bin
  cd bin/
  ls
  sh startup.sh

#Stop Instance get into New Public Genarate Commands 
$cd /opt/tomcat
$ cd bin 
$ ls 
$ sh startup.sh 