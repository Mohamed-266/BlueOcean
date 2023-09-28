## Description
Building CI/CD pipeline using Jenkins and BlueOcean Plugin

### Steps
##### 1. AWS account for EC2 creation
Made an EC2 instance using AWS services and choosing Ubuntu server (type: t2.micro) and made a key pair to connect to it via SSH for secure connection using inbound security group rules

##### 2. Installing java and Configuring Jenkins on Ubuntu machine
1-	Updated existing packages first using: sudo apt update.
2-	Installed java using: sudo apt install –y default-jdk
3-	Installed Jenkins using: sudo apt install –y Jenkins
4-	Starting Jenkins and getting status using:
A-	sudo systemctl start Jenkins
B-	sudo systemctl enable Jenkins
C-	sudo systemctl status Jenkins

##### 3. Installing BlueOcean plugin
1-	Go to manage Jenkins from the dashboard
2-	Press manage plugins
3-	Navigate to available plugins
4-	Choose BlueOcean
5-	Restart Jenkins after installation is done



## Resources
###Github repo: https://github.com/Mohamed-266/BlueOcean-Pipeline

There are 4 branches made including the main branch

All screenshots of run will be available in folder images







