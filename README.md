# LITA-CLOUD-COMPUTING-PROJECT
 Building a Scalable Web Infrastructure for "SmartShop"
 ### VPC CREATION 
A VPC has been created already though to maximum VPC to be created was reached.
### CREATING SECURITY GROUP
Proceed  to creating a security group controlling inbound and outbound traffic allowing inbound SSH and HTTP traffic
Below is the image of my SG details
![Security_Group details](/Security_Group.jpg)
### CREATING KEY PAIR
Then I created a key pair “loveth_litaKP” to connect to EC2 Instance
Below is the image of my KP details
![Keypair details](/Keypair.jpg)
### CREAATING EC2 INSTANCE 
Created an EC2 Instance “lovethoviri_lita”, on Amazon Linux 2 as the OS and a t2.micro instance type, configured with a public subnet and I assigned the SG I created and also my KP, then  connected it to the already created VPC
Below is the image of my EC2 Instance details
![EC2_Instance details](/EC2_Instance.jpg)
### INSTALLING APACHE WEB SERVER
I installed Apache web server SSH to the instance I launched by using the command prompt on my laptop, typed cd Downloads, then copied the code from my SSH and run in om command prompt , when it displayed the sketched bird, I procced to installing my Apache using the command codes on the project guide, then when it was completed I went back to my instance, copied the Public IPv4 address and pasted on a new tab on my browser to confirm it as successfully installed
Below is the image of my Test page details
![Test_page details](/Test_page.jpg)
