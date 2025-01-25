How to install nginx in Amazon Linux 2023 Server?

1.Login to server with admin access

$sudo su

#

2.Update the Package repository Before installing nginx
#sudo dnf update -y 

3.Install nginx 
#sudo dnf install - y

4.Start the nginx Service 
#sudo systemctl start nginx

5.Verify nginx service is started or not
#sudo systemctl status nginx

6.Enable nginx service start on server boot
#sudo systemctl enable nginx 

7.9.Enable http inbound rule in security group of instance in

port:22
Protocal : ssh
Source :Anywhere

port:80
Protocal:HTTP
Source:Anywhere

8.Take a public IP Of Instance and browser from any internet browser

Verify : it will show "Welcome to nginx!"
