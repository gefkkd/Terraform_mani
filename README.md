# Terraform_mani
# Requirements

# To stop ec2 instance use lambda function

#Instance tagname

#Name = demo

#To install Terraform on a Windows system, follow these steps:

#Download the latest version of Terraform for Windows from the official website: 

https://www.terraform.io/downloads.html

Extract the downloaded zip file to a directory of your choice. It is recommended to extract it to a directory that is in your system PATH, so that you can access the Terraform executable from anywhere in the command prompt.

Next, you will need to set up your system PATH to include the directory where the Terraform executable is located. To do this, open the Start menu and search for "Environment Variables".

Click on "Edit the system environment variables" to open the System Properties dialog box.

Click on the "Environment Variables" button.

Under "System Variables", scroll down and find the "Path" variable, and click the "Edit" button.

Click the "New" button and add the directory path where you extracted the Terraform executable, for example, C:\terraform.

Click "OK" on all the windows to save the changes.

variables:

accessKey           =""
secretKey           =""
region              = "ap-south-1"
lambdaname          ="lambda_mani-aws-ec2-start"
tagName             ="office-hours"
tagValue            ="ec2-data-platform"
commands

# 1. terraform version
# 2. terraform init
# 3. terraform plan -var-file=5-variable.tfvars
# 4. terraform apply -var-file=5-variable.tfvars
# 5. terraform destroy -var-file=5-variable.tfvars
