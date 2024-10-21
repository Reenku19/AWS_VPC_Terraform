**🚀 Mini Project Alert: Automating EC2 Instance Creation with Terraform & AWS CLI! 🚀**

**🔍 Project Overview:**

In this project, I combined the power of Terraform with the versatility of AWS CLI to automate the deployment of an EC2 instance on AWS. This exercise not only demonstrates the infrastructure as code (IaC) paradigm but also emphasizes the importance of automation in cloud infrastructure management. 💥 

**These are the steps that I have taken in this project:**

✅ Setting Up AWS CLI:
Configured the AWS CLI with access keys using AWS configure.

✅ Defining the Terraform Configuration:
Created a Terraform configuration file (main.tf) to define the desired EC2 instance with parameters such as instance type and AMI ID.
Added the required AWS provider block, ensuring Terraform knows which provider to interact with.

✅ Initializing Terraform:
Ran terraform init to download necessary provider plugins and set up the working directory.

✅ Planning and Reviewing the Infrastructure:
Used terraform plan to generate an execution plan and review the changes Terraform would make to the AWS environment.
Carefully reviewed the output to ensure the infrastructure aligns with the intended architecture.

✅ Deploying the EC2 Instance:
Executed terraform apply to deploy the EC2 instance on AWS.
Monitored the deployment process and verified the creation of the EC2 instance in the AWS Management Console.

✅ Post-Deployment Verification:
Used AWS CLI commands like AWS EC2 describe-instances to confirm the instance's status and retrieve detailed information.

✅ Cleaning Up:
Practiced responsible cloud usage by running terraform destroy to terminate the EC2 instance and clean up associated resources.
Verified that all resources were deleted to avoid unnecessary charges.

![Screenshot (332)](https://github.com/user-attachments/assets/2dae102c-852d-4752-97f7-38e03e624534)

![Screenshot (337)](https://github.com/user-attachments/assets/7613b391-e5dc-4b62-9ed8-6cbeb2d193bb)

![Screenshot (338)](https://github.com/user-attachments/assets/13f79a6a-ecb0-4433-86fe-e4fbfd1902d6)

![Screenshot (339)](https://github.com/user-attachments/assets/2746ce1d-4d41-475e-8449-2caec41f522a)

![Screenshot (340)](https://github.com/user-attachments/assets/6d240072-be2a-4f68-8cee-2c7af6f7628c)
