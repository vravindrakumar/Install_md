How to Install http service in Amazon Linux Instance ?

1.Login to server with admin access

$ sudo su

2.Update the Packages repository Before installing Apcahe &PHP
#sudo dnf update  -y 

3.Install apache & PHP
#sudo dnf install httpd php php-mysqlnd -y 

4.Start the apache service or start the httpd service
#sudo systemctl start httpd 

5.Verify httpd/apache services is started or not
#sudo systemctl status httpd

6.If you want to stop the httpd/apache services
#sudo systemctl stop httpd

7.Enable httpd service to start on boot
#sudo systemctl enable httpd

8.Verify after server reboot service is started or not
#sudo systemctl status httpd

9.Enable http inbound rule in security group of instance in

port:80
Protocal : http
Source :Anywhere

10.Take  a public IP Of Instance and browser from any internet browser

Verify : it will show " It works!"