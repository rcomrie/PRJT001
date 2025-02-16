#EC2 Webserver 

##Create EC2 Instance Resource Webpage (source code provided in GitHub link "(https://github.com/rcomrie/PRJT001.git) " publish on Public IP


### Project Specifications:
Region: US-East-1
VPC: Customized (Webpage)
IP Pool: 12.0.0.0/16
Subnet: 12.0.0.0/24
Security Group: Webpage (Allow SSH, ICMP, and HTTP only)
Instance Type: T2.micro (Free Tier Eligible)
Image: Ubuntu
Key Pair: .pem
Storage: Default
![Screenshot(vpc)](https://github.com/user-attachments/assets/ad56287a-b554-4fb5-b536-8b9da0f745e5)


Implementation Steps:
Create a VPC with the specified IP range (12.0.0.0/16).
Set up a Subnet within the VPC (12.0.0.0/24).
Create a Security Group with rules to allow SSH (port 22), ICMP (ping), and HTTP (port 80) access.



Launch an EC2 Instance using the Ubuntu AMI, selecting the T2.micro instance type.
Attach the Security Group to the instance.
Generate a Key Pair (.pem file) for SSH access.
Allocate and Assign a Public IP to the instance.
Configure the Instance to host a basic webpage.
Test Connectivity using SSH, ICMP, and HTTP.
![Screenshot 2025-02-16 121930](https://github.com/user-attachments/assets/e9c63d8a-2219-4a39-85ea-21e7a846e8e2)
![Screenshot 2025-02-16 121603](https://github.com/user-attachments/assets/fe3f8ebf-5c3a-4d27-b740-37d2799b4f95)

Expected Outcome:
A publicly accessible webpage hosted on the EC2 instance, accessible via its public IP address, with proper security configurations.
![Screenshot 2025-02-16 124205](https://github.com/user-attachments/assets/a1950e85-ae23-45c3-af53-36d05a918b5f)

