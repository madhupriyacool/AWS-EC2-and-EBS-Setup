Aws-EBS PROJECT


AWS EC2 and EBS Setup Guide
Steps
1. Launch a Linux EC2 Instance
Log in to the AWS Management Console.
Navigate to the EC2 Dashboard.
Click on "Launch Instance."
Choose an Amazon Machine Image (AMI) (e.g., Amazon Linux 2).
Select an instance type (e.g., t2.micro).
Configure instance details.
Add storage.
Add tags (optional).
Configure the security group to allow SSH access.
Review and launch the instance.
Select or create a key pair for SSH access and launch the instance.
2. Create a 20GB EBS Volume
In the EC2 Dashboard, go to "Volumes" under the "Elastic Block Store" section.
Click on "Create Volume."
Specify the volume size (20GB), type (General Purpose SSD), and availability zone (same as your instance).
Click "Create Volume."
3. Attach the EBS Volume to the EC2 Instance
In the EC2 Dashboard, go to "Volumes."
Select the newly created volume and click on "Actions."
Choose "Attach Volume."
Select the instance to attach the volume to and specify the device name.
Click "Attach Volume."
4. Connect to the EC2 Instance
Obtain the public IP address of your EC2 instance from the EC2 Dashboard.
Use an SSH client to connect to the instance.
5. Resize the Attached Volume
List available disk devices to confirm the attachment.
Verify the filesystem on the device.
Create a filesystem on the volume if it doesn't already have one.
Create a mount point and mount the volume.
Resize the volume to reflect changes.
Verify the resized volume.
Cleanup
Unmount the volume if needed.
Detach the volume.
Delete the volume.
Terminate the EC2 instance.


output

 ![image](https://github.com/moorthyawsdevops/AWS-EC2-and-EBS-Setup/assets/162882673/d40503a7-d296-4f92-872f-4b070294990e)
![image](https://github.com/moorthyawsdevops/AWS-EC2-and-EBS-Setup/assets/162882673/52609c39-244c-481c-acd1-475b4add230f)
![image](https://github.com/moorthyawsdevops/AWS-EC2-and-EBS-Setup/assets/162882673/5efce259-8dbc-4b8d-ac64-3ae2dee4f2e3)
![image](https://github.com/moorthyawsdevops/AWS-EC2-and-EBS-Setup/assets/162882673/e4b65ca3-fc7d-466a-9ec1-f37c2f6ef8a4)
![image](https://github.com/moorthyawsdevops/AWS-EC2-and-EBS-Setup/assets/162882673/f97b1c1a-a4f3-4eda-a0ef-d62811ff26f4)
![image](https://github.com/moorthyawsdevops/AWS-EC2-and-EBS-Setup/assets/162882673/8187f042-d359-4ace-9ec2-fef43d50b5e9)
![image](https://github.com/moorthyawsdevops/AWS-EC2-and-EBS-Setup/assets/162882673/5ffb6845-f434-4565-ae31-fff0c325d857)
![image](https://github.com/moorthyawsdevops/AWS-EC2-and-EBS-Setup/assets/162882673/b2728927-3794-45da-a417-2f6e328ea2d3)
![image](https://github.com/moorthyawsdevops/AWS-EC2-and-EBS-Setup/assets/162882673/c1cad443-8a08-44df-a88d-0986c2497a32)
![image](https://github.com/moorthyawsdevops/AWS-EC2-and-EBS-Setup/assets/162882673/f6980fc8-ca4f-41af-9e56-d0e392509cc9)
![image](https://github.com/moorthyawsdevops/AWS-EC2-and-EBS-Setup/assets/162882673/e9a0ba36-b256-4fbf-8486-aac1e1bbb7b3)
![image](https://github.com/moorthyawsdevops/AWS-EC2-and-EBS-Setup/assets/162882673/1962b9cc-c0d3-477b-bd28-83a25c83bad5)
![image](https://github.com/moorthyawsdevops/AWS-EC2-and-EBS-Setup/assets/162882673/4984111d-e04d-48cf-b243-8cd7f2863e14)
![image](https://github.com/moorthyawsdevops/AWS-EC2-and-EBS-Setup/assets/162882673/8fd2093b-d585-4aa8-b7c6-2835bbdd22fa)
![image](https://github.com/moorthyawsdevops/AWS-EC2-and-EBS-Setup/assets/162882673/466e9e19-5454-4fa4-9baf-95aa7b58e92d)
![image](https://github.com/moorthyawsdevops/AWS-EC2-and-EBS-Setup/assets/162882673/b47aaaff-7411-450d-a4f3-7f9e5d2e02f6)
![image](https://github.com/moorthyawsdevops/AWS-EC2-and-EBS-Setup/assets/162882673/7579e499-177c-472a-ab1d-7750073845a3)
![image](https://github.com/moorthyawsdevops/AWS-EC2-and-EBS-Setup/assets/162882673/202ef2ea-ee75-44a8-8aff-6e595d31dfb5)
![image](https://github.com/moorthyawsdevops/AWS-EC2-and-EBS-Setup/assets/162882673/57f3af11-9efe-454c-a97c-013558e8521b)



















 
 
 
 
 
 
 
 
 
 
 
 
 
 
 
 


