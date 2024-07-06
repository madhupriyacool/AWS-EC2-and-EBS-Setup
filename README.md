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
